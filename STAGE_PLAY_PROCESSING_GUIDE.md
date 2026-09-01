# Stage Play Processing Guide

இந்த repository-யில் கலைஞர் மு. கருணாநிதியின் மேடை நாடகங்கள் / நாடக வடிவிலான படைப்புகளை source-first முறையில் மின்னாக்குவதற்கான நிரந்தர வழிகாட்டி.

## 1. Controlling source

> **வழங்கப்பட்ட மூல scan தான் controlling source.**

Repository text ஒரு புதிய பதிப்பு அல்ல. அது குறிப்பிட்ட physical/printed edition-ஐப் பாதுகாக்கும் archival transcription.

அமைதியாக செய்யக்கூடாதவை:

- எழுத்துப்பிழை எனத் தோன்றுவதைத் திருத்துதல்;
- பழைய எழுத்து/சொல் வடிவங்களை நவீனப்படுத்துதல்;
- punctuation, sandhi, இலக்கணம், பெயர், தேதி, எண், speaker label ஆகியவற்றை standardize செய்தல்;
- dialogue repetition-ஐ stylistic காரணத்தால் நீக்குதல்;
- stage direction-ஐ prose-ஆக மாற்றுதல் அல்லது prose-ஐ stage direction-ஆக மாற்றுதல்;
- later edition / இணைய transcription / நினைவிலுள்ள wording மூலம் scan text-ஐ மாற்றுதல்;
- தெளிவில்லாத எழுத்தை sentence பொருளை வைத்து நிரப்புதல்;
- source-ல் இல்லாத act/scene/section heading-ஐ body transcription-க்கு silently சேர்த்தல்.

### 1A. First-pass / Gemini / old-Tamil-glyph adjudication

OCR அல்லது Gemini first-pass **controlling authority அல்ல**; scan தான் controlling source. ஆனால் first-pass ஒரு comparison baseline. குறிப்பாக பழைய Tamil glyphs உள்ள source-களில், first-pass-ஐ semantic expectation அல்லது modern spelling அடிப்படையில் assistant தானாக மாற்றக்கூடாது.

Permanent rules:

1. user supplied first-pass இருந்தால் அதிலிருந்து தொடங்கு; scan-க்கு எதிராக compare செய்;
2. ஒரு glyph / சொல் பழைய வடிவத்தால் ambiguous என்றால், familiar modern spelling, dictionary expectation, proper-name familiarity, grammar அல்லது sentence meaning அடிப்படையில் மாற்ற வேண்டாம்;
3. **scan unambiguous ஆக வேறு reading காட்டினால் மட்டுமே** first-pass-ஐ மாற்று; evidence-ஐ page verification notes / discrepancy record-ல் பதிவு செய்;
4. scan ambiguity நீங்கவில்லை என்றால் first-pass reading-ஐ retain செய்து `needs-review` / ambiguity note பயன்படுத்து;
5. user ஒரு assistant-proposed correction source-ல் இல்லை என்று explicitly நிராகரித்தால், அந்த correction உடனே withdraw செய்ய வேண்டும். அந்த reading-ஐ மீண்டும் கொண்டு வர புதிய, தெளிவான source evidence இல்லாமல் கூடாது;
6. user-confirmed rollback பிறகு affected page ஏற்கெனவே `verified` என்றால், verification gate-ஐ reopen செய்து தேவையானால் `needs-review`-க்கு மாற்று; clean re-reconciliation முடிந்த பிறகே மீண்டும் `verified`;
7. OCR/re-OCR, published translation, later edition, general knowledge, common spelling ஆகியவற்றில் எதுவும் user-retained plausible old-glyph reading-ஐ override செய்யக்கூடாது;
8. new chat/session-ல் original first-pass text கிடைக்காவிட்டால் அதை memory-யில் இருந்து invent செய்யக்கூடாது. Repository-யில் durable text இருந்தால் அதை பயன்படுத்து; இல்லையெனில் relevant first-pass segment-ஐ user மீண்டும் வழங்கும் வரை disputed reading-ஐ adjudicate செய்ததாகக் கூறக்கூடாது.

இந்த விதி source-first policy-க்கு முரணல்ல: scan authority தொடர்கிறது; ஆனால் **uncertain scan pixels மீது assistant expectation authority ஆக மாறுவதைத் தடுக்கிறது**.

## 2. PDF policy

Source PDF repository-க்குள் commit செய்யப்படாது.

ஒவ்வொரு source-க்கும் `metadata/source.md`-ல் குறைந்தது பின்வருவன பதிவு செய்ய வேண்டும்:

- source filename;
- SHA-256 checksum;
- file size;
- scan page count;
- title / author as printed;
- visible publisher / imprint / edition / price details;
- publication year if and only if separately supported by the scan;
- printed-page numbering behaviour;
- front matter / body / back matter extent;
- scan condition;
- library stamps, accession numbers, handwriting, damage, bleed-through, illustrations, photographs, advertisements and other anomalies.

Internal dates in forewords/reviews must not be promoted to a publication year unless the edition itself supports that conclusion.

## 3. Work structure

```text
works/<work>/
  README.md
  metadata/
    source.md
  indexes/
    page-map.md
  pages/
    0001.md
    0002.md
    ...
  scenes/
    ...
```

Later phases may add:

```text
  audit.md
  ASSEMBLY_REVIEW.md
  POSSIBLE_ERRORS_FOR_REVIEW.md
  FIRST_PASS_DISCREPANCIES.md
  INTRO_RECONCILIATION.md
  translations/en/
  TRANSLATION_REVIEW.md
  HANDOVER.md
```

## 4. Every scan page must be represented

Cover, title page, photograph, dedication, foreword, preface, body text, illustration, blank page, advertisement and back cover all receive page records.

Recommended front matter:

```yaml
---
scan_page: 1
printed_page: null
work: "silappathikaram-nataka-kappiyam"
section: "front-matter"
scene: null
page_type: "title-page"
status: "verified"
language: "ta"
source_filename: "...pdf"
transcription_method: "direct visual comparison with source scan"
---
```

Status values:

- `not-started`
- `partial`
- `needs-review`
- `verified`
- `blocked`

`verified` என்பது scan-ஐ நேரடியாகப் பார்த்து text, punctuation, speaker labels, stage directions, paragraph/column structure மற்றும் source marks அனைத்தையும் உறுதிப்படுத்திய பின்னரே பயன்படுத்த வேண்டும். Old-glyph dispute user correction மூலம் reopen செய்யப்பட்டால் முன்னைய `verified` status தானாக authoritative ஆகாது; re-reconciliation தேவை.

## 5. Drama-specific transcription rules

### Speaker labels

Speaker names/labels source-ல் எப்படியிருக்கிறதோ அப்படியே பாதுகாக்கப்பட வேண்டும். Abbreviation, colon, dash, spacing ஆகியவை silently normalized செய்யப்படக்கூடாது.

### Dialogue

- Dialogue order source layout-ஐப் பின்பற்ற வேண்டும்.
- Two-column layout இருந்தால் reading order visual inspection மூலம் தீர்மானிக்க வேண்டும்; OCR column order authoritative அல்ல.
- Broken line / continued utterance page boundary-ஐத் தாண்டினால் இரண்டு page records-லும் physical break preserve செய்ய வேண்டும்.
- Later assembled scene file-ல் break joining செய்யலாம்; ஆனால் provenance / page boundary மறைக்கக்கூடாது.

### Stage directions

Brackets, parentheses, italics-like typography, decorative symbols, prose direction, entrance/exit cue போன்றவை source-supported வடிவில் பதிவு செய்ய வேண்டும். Editorially invented stage directions சேர்க்கக்கூடாது.

### Scene headings

`காட்சி`, scene number, decorative scene title மற்றும் subtitle source image-ஐ நேரடியாக வாசித்து பதிவு செய்ய வேண்டும். Stylized heading தெளிவில்லையெனில் body context வைத்து ஊகிக்காமல் `needs-review` ஆக விட வேண்டும்.

### Illustrations and photographs

Image content textual transcription அல்ல. Page record-ல் concise archival description மற்றும் position பதிவு செய்ய வேண்டும். Printed caption இருந்தால் caption verbatim transcribe செய்ய வேண்டும்.

## 6. Source marks versus printed text

Library stamp, accession number, handwritten shelf mark, later pencil/ink annotation, torn area, stain, bleed-through ஆகியவற்றை printed authorial text-இலிருந்து வேறுபடுத்த வேண்டும்.

Recommended notation in page notes:

- `printed_text:` source publication text
- `library_mark:` stamp / accession mark
- `handwriting:` later handwritten mark
- `damage:` physical loss or obstruction
- `illustration:` printed image description

Do not silently merge a library mark into the literary text.

## 7. Difficult-reading escalation

ஒரு reading-ஐ `blocked` என்று terminal ஆக விடுவதற்கு முன்:

1. native scan image-ஐ inspect செய்;
2. enlarged crops உருவாக்கு;
3. nearest-neighbour மற்றும் high-quality resampling இரண்டிலும் compare செய்;
4. grayscale, contrast, gamma, threshold, sharpening போன்ற non-destructive variants முயற்சி செய்;
5. stamp/bleed-through இருந்தால் print strokes மற்றும் overlay strokes வேறுபடுத்த முயற்சி செய்;
6. அதே font/glyph வடிவம் வரும் neighbouring pages-ஐ compare செய்;
7. previous/next page continuation பார்க்கவும்;
8. user-provided reading / first-pass இருந்தால் source pixels-க்கு எதிராக verify செய்; ambiguity இருந்தால் அதை retain செய்வதே default;
9. user ஒரு proposed correction-ஐ நிராகரித்திருந்தால், semantic expectation கொண்டு அதையே மீண்டும் propose செய்ய வேண்டாம்;
10. அவசியமெனில் independent secondary witness-ஐ provenance-உடன் corroboration-க்கு மட்டும் பயன்படுத்தலாம்;
11. secondary witness wording-ஐ controlling scan-க்கு silently import செய்யக்கூடாது.

Processing objective: defensible reading recover செய்யக்கூடிய இடங்களில் unresolved literary-text blocks zero-க்கு கொண்டு வருதல்; fabrication மூலம் அல்ல.

## 8. Printed errata

Publication-ல் `பிழை திருத்தம்` / errata இருந்தால் அதை தனித்த source layer ஆக verbatim archive செய்ய வேண்டும்.

Page transcription-ல் printed error-ஐ silently correct செய்யக்கூடாது. An assembled reading may explicitly reference the errata later.

## 9. Page map

`indexes/page-map.md` ஒவ்வொரு scan page-ஐ track செய்ய வேண்டும்:

- scan page;
- printed page if visibly supported;
- section / scene;
- page type;
- transcription status;
- notes / anomalies.

Pagination must not be inferred merely because adjacent pages are sequential.

## 10. Scene assembly

Page transcription first; scene assembly later.

A scene file must be assembled only from page records that have been visually checked. It may remove mechanical page breaks for readability, but must not change wording or silently repair the source.

Suggested scene front matter:

```yaml
---
scene: 1
source_scan_pages: [17, 18]
status: "draft"
assembled_from_verified_pages: false
---
```

## 11. Audit

Before a work is considered transcription-complete:

- every scan page has a record;
- every body page has been compared with the source;
- every scene heading has been checked visually;
- all `needs-review` and `blocked` locations are revisited;
- page map matches repository files;
- assembled scenes match page records;
- no silent normalization is present;
- first-pass / user-correction discrepancy records are resolved or explicitly documented;
- non-literary marks are distinguished from printed text;
- source PDF remains outside the repository.

## 12. Translation

Translation is a separate later phase. English translation must be based on the verified Tamil archival text, not OCR or a modern edition. Translation must not retroactively alter the Tamil source transcription.

## 13. Handover discipline

At the end of each substantial batch, update the work README / `HANDOVER.md` with:

- exact pages completed;
- current unresolved readings;
- files created/updated;
- next page/scene to process;
- any source anomalies discovered;
- verification status;
- any user correction that invalidated or reopened an earlier verification gate;
- whether provisional visual work was performed but **not committed**.

If the repository uses `NEXT_CHAT_PROMPT.md`, update it at the same checkpoint. A new chat/session must:

1. fetch live `main` first and treat it as authoritative;
2. read this guide, `HANDOVER.md`, and the active-work reconciliation/page-map files completely;
3. distinguish **durable committed state** from provisional work done in a prior chat but never committed;
4. never claim a provisional/uncommitted page as verified merely because an earlier chat said it had been inspected.

A new chat/session should be able to continue without guessing prior decisions.

### 13A. Provisional-work transfer across chat windows

When a chat ends after source inspection but before a durable commit, use the following rules:

1. **Committed repository state remains authoritative.** Provisional page transcriptions, local crops, temporary renders and uncommitted Git trees are evidence of progress only; they are not durable verification.
2. `HANDOVER.md` and `NEXT_CHAT_PROMPT.md` must explicitly record the last committed page, the provisional scan range already inspected, unresolved readings still needing adjudication, and the exact write/verification step that remains.
3. A fresh chat must re-resolve or reattach the controlling PDF before source-dependent work. Do not assume temporary container paths, local crops or rendered images from the earlier chat still exist.
4. If a conversation/file preview exposes fewer pages than the raw PDF, the raw PDF page count and direct raw-page renders control. Never truncate processing merely because the preview stops early.
5. When the user asks to process **all remaining pages**, continue through literary closure **and all remaining physical back matter** (advertisements, catalogue pages, back cover, blanks, etc.), because every physical scan requires a page record.
6. A provisional page may be promoted to `verified` only after the fresh chat has either directly rechecked the controlling scan or has durable, source-reconciled page text already committed in the repository.
7. Final-batch closure requires: page records for the entire remaining physical range, zero unresolved readings or explicit `needs-review` records, a batch/final verification record, synchronized page map/work README/root README/handover/prompt, a Git commit, and a final live-`main` verification.
8. Do not begin scene assembly or English translation merely because page-level transcription reaches 100%; those remain separate phases requiring their own authorization/checkpoint.
