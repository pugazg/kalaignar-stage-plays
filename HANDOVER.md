# Kalaignar Stage Plays — Handover

Repository: `pugazg/kalaignar-stage-plays`, branch `main`.

## Startup rule

Always fetch live `main` first and treat it as authoritative. Preserve newer durable state and never reopen completed work unless the user explicitly requests it.

Permanent workflow: `STAGE_PLAY_PROCESSING_GUIDE.md`.

Controlling composite source: `TVA_BOK_0065576_நான்மணி_மாலை.pdf` — **54 scans** — SHA-256 `18d2b1405544b03507e9f92067d287cb28f5a92eaf02bed7054e6e78e5e38c89`.

## Locked completed work

- `பரதாயணம்`: Tamil archive/assembly PASS; independent English translation PASS.
- `அனார்கலி`: Tamil page/assembly fidelity PASS.
- `சாக்ரடீஸ்`: **17/17 pages verified; 5/5 scenes assembled; all fidelity gates PASS**.
- Silappathikaram completed state remains locked and unchanged.
- `சேரன் செங்குட்டுவன்`: **10/10 Tamil pages verified; 4/4 scenes assembled; all page-record ↔ scene fidelity gates PASS**.

## `சேரன் செங்குட்டுவன்` — completed Tamil dramatic-source state

Controlling Tamil extent: scans **44–53** / printed pp. **39–48**; four source-printed dramatic scenes. The 2009 published-English witness is secondary only.

### First-pass / source rule

The user supplied a Gemini word-to-word first pass covering the Cheran source extent. Gemini is a comparison baseline, not the controlling authority. Do not replace plausible old-glyph readings by familiar spelling, grammar or semantic expectation. Use unambiguous scan evidence when it differs and document the difference. Do not use the English witness to reconstruct Tamil.

### Completed scenes

- `காட்சி — 1`: scans **44–45** / pp.39–40 — page gate + assembly/fidelity **PASS**.
- `காட்சி — 2`: scans **46–49** / pp.41–44 — page gate + assembly/fidelity **PASS**.
- `காட்சி—3.`: scans **50–51** / pp.45–46 — page gate + assembly/fidelity **PASS**.
- `காட்சி—4.`: scans **52–53** / pp.47–48 — page gate **2/2 COMPLETE**, `scenes/04.md` assembled, `SCENE4_ASSEMBLY_FIDELITY_REVIEW.md` **PASS**.

Important locked final-scene controls:

- source heading `காட்சி—4.` and setting `குயிலாலுவம்`;
- source-order opening direction assembled only by mechanical print-line joining;
- exact source speaker-label punctuation variants `சேர்:`, `சேர்;`, unusual `சேர்!`, `வில்லவன்:`, `வில்:`, `வில்!`, and `கன:`;
- source long dashes and `ராம ராவணப் போர்?....`;
- `புறப்படுவோம்—வில்லவா.`, `கனக—விஜயா`, `சொல்—இப்போது`;
- scan 53 centered final source mark **`- * -`** retained exactly.

Durable Cheran completion:

- Tamil pages verified: **10/10 COMPLETE**;
- scenes assembled from verified Tamil: **4/4 COMPLETE**;
- unresolved assembly discrepancies: **0**;
- speaker-label mismatches: **0**;
- assistant lexical substitutions introduced during final assembly: **0**;
- English-witness reconstruction: **0**.

## Exact next activity

Process **scan 54 / back cover only** from `TVA_BOK_0065576_நான்மணி_மாலை.pdf` as an archival-description page for the composite Tamil source.

Requirements:

- fetch live `main` first;
- inspect scan 54 directly from the controlling PDF;
- treat it as a back-cover / non-literary source page unless the scan itself proves printed literary text;
- distinguish printed publication material from library marks, later handwriting, stamps, damage or other non-authorial marks;
- preserve any printed caption/text exactly if present;
- create/update the appropriate composite-source page record and page map according to repository conventions;
- update source README, root README, handover and next-chat checkpoint after verification;
- do **not** reopen completed `சேரன் செங்குட்டுவன்` dramatic text;
- do **not** begin another work in the same activity.

## Permanent safeguards

- live `main` controls repository state;
- PDF remains external;
- no silent lexical normalization or semantic reconstruction;
- ambiguous old-glyph readings are not overridden by expectation;
- scene assembly occurs only after every source page for that scene is verified;
- English witnesses are secondary only;
- translation must derive from verified Tamil;
- `அந்தணர்` is not automatically “Brahmin” in future translation work.
