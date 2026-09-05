# Kalaignar Stage Plays — Handover

Repository: `pugazg/kalaignar-stage-plays`, branch `main`.

## Startup rule

Always fetch live `main` first and treat it as authoritative. Preserve newer durable state. Do not reset, overwrite, repeat, or reopen completed work because a copied prompt contains an older checkpoint.

Permanent workflow: `STAGE_PLAY_PROCESSING_GUIDE.md`.

# ACTIVE WORK — காகிதப்பூ

## Mandatory startup

Read completely before any source-dependent change:

1. `STAGE_PLAY_PROCESSING_GUIDE.md`;
2. this `HANDOVER.md`;
3. `NEXT_CHAT_PROMPT.md`;
4. `works/kagithapoo/README.md`;
5. `works/kagithapoo/MD_LEXICAL_RECONCILIATION_0091_0101.md`;
6. `works/kagithapoo/SOURCE_INTAKE.md`;
7. `works/kagithapoo/metadata/source.md`;
8. `works/kagithapoo/indexes/page-map.md`;
9. relevant `works/kagithapoo/pages/*.md` files.

Re-resolve / attach both the controlling PDF and the user-supplied lexical witness before page-level work.

## Controlling structural source

`TVA_PRL_0001638_முரசொலி_ பொங்கல் மலர்_ 1967.pdf`

- SHA-256: `b0a6499ba072a7346f8c2544a8a61c2363d83a60cad5227482008043cd310ec1`;
- size: **45,718,751 bytes**;
- full PDF: **131 physical scans**;
- selected work range: **91–131 inclusive = 41 scans**.

## Lexical witness

User-supplied full-play transcription: `kaagidha_poo.md`.

## Locked dual-witness rule

1. **Words / lexical forms come only from `kaagidha_poo.md`.**
2. **PDF controls page/scene boundaries, paragraph and speaker structure, reading order, punctuation, brackets, headings/numbers, photographs and physical/layout evidence.**
3. MD words may be repositioned or respaced when PDF structure establishes placement.
4. If PDF structure contains text for which MD supplies no lexical words, do not import those words from the PDF. Record a lexical-witness gap and use `needs-review` where appropriate.
5. No OCR/common-spelling/semantic/assistant normalization may replace MD wording.

## Durable current state

- source intake: **COMPLETE**;
- page placeholders: **41 / 41 represented** (`0091.md`–`0131.md`);
- retroactive MD lexical reconciliation of **91–101: COMPLETE AND APPLIED**;
- detailed audit: `works/kagithapoo/MD_LEXICAL_RECONCILIATION_0091_0101.md`;
- fully verified dual-witness pages: **30 / 41** — scans **91, 92, 94, 96, 99–124**;
- `needs-review` because MD witness is incomplete: **93, 95, 97, 98**;
- forward page processing completed through **scan 124**;
- final unprocessed page batch: **125–131**;
- scene assembly: **not started / not authorized**;
- English translation: **not started / not authorized**.

## Outstanding earlier lexical-witness gaps

- **93** — PDF stage direction has additional words absent from MD;
- **95** — MD omits one complete `காவேரி:` paragraph and the opening of the following `மரகதம்:` paragraph;
- **97** — one PDF-structured parenthetical stage direction has no MD words at that location;
- **98** — a PDF-printed personal-name caption is absent from MD.

No missing lexical text has been copied from the PDF into those gaps. The user explicitly allowed forward processing to continue while they remain tracked.

## Durable structural progress through scan 124

- 115 closes Scene 17 and begins Scene 18;
- 116 closes Scene 18 and contains all of Scene 19;
- 117–118 carry Scene 20;
- 119 closes Scene 20 and begins `காட்சி 21.`;
- 120–123 carry Scene 21's embedded political reading and language debate;
- 124 closes Scene 21 and begins a new road scene under the source-visible heading **`காட்சி,`** with no numeral.

## Scene-numbering anomaly safeguard

This is now directly verified, not merely intake-level:

- scan **124** prints only **`காட்சி,`** with no visible numeral;
- scan **125** later prints **`காட்சி 24.`**.

Do **not** invent `காட்சி 22` or `காட்சி 23`.

## Exact next activity

Process the **final page-level batch: scans 125–131**.

For each scan:

1. use only MD-supplied words;
2. derive page/scene boundaries, reading order, punctuation, speaker/stage structure and visual evidence from the PDF;
3. preserve the unnumbered scene continuation on scan 125 before the source-visible `காட்சி 24.`;
4. preserve all source-visible later scene numbering exactly;
5. on scan 131 preserve `(முற்றும்)` and the following boxed `நாடகத்தில்—பங்கேற்பவர்கள்!` block according to the dual-witness rule;
6. commit completed pages durably and synchronize page-map/README/HANDOVER/NEXT_CHAT_PROMPT after scan 131.

Do not begin scene assembly or English translation without separate authorization.

# CLOSED WORK SAFEGUARDS

`மணிமகுடம்` remains **COMPLETE / CLOSED**: Tamil physical archive 170/170, Tamil scenes 47/47 PASS, independent English 47/47 PASS, release READY/FINAL.

`கலைஞரின் நான்மணி மாலை` remains closed at its previously recorded completed state. Do not reopen closed work while continuing `காகிதப்பூ`.