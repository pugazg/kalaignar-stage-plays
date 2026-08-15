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
- later edition / இணைய transcription / நினைவிலுள்ள Silappathikaram wording மூலம் scan text-ஐ மாற்றுதல்;
- தெளிவில்லாத எழுத்தை sentence பொருளை வைத்து நிரப்புதல்;
- source-ல் இல்லாத act/scene/section heading-ஐ body transcription-க்கு silently சேர்த்தல்.

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

`verified` என்பது scan-ஐ நேரடியாகப் பார்த்து text, punctuation, speaker labels, stage directions, paragraph/column structure மற்றும் source marks அனைத்தையும் உறுதிப்படுத்திய பின்னரே பயன்படுத்த வேண்டும்.

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
8. user-provided reading இருந்தால் source pixels-க்கு எதிராக verify செய்;
9. அவசியமெனில் independent secondary witness-ஐ provenance-உடன் corroboration-க்கு மட்டும் பயன்படுத்தலாம்;
10. secondary witness wording-ஐ controlling scan-க்கு silently import செய்யக்கூடாது.

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
- verification status.

A new chat/session should be able to continue without guessing prior decisions.
