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

Raw identity:

- SHA-256: `b0a6499ba072a7346f8c2544a8a61c2363d83a60cad5227482008043cd310ec1`;
- size: **45,718,751 bytes**;
- full PDF: **131 physical scans**;
- selected work range: **91–131 inclusive = 41 scans**.

## Lexical witness

User-supplied full-play transcription:

`kaagidha_poo.md`

## Locked dual-witness rule

1. **Words / lexical forms come only from `kaagidha_poo.md`.**
2. **PDF controls page/scene boundaries, paragraph and speaker structure, reading order, punctuation, brackets, headings/numbers, photographs and physical/layout evidence.**
3. MD words may be repositioned or respaced when PDF structure establishes placement.
4. If PDF structure contains a paragraph/stage direction/printed text for which MD supplies no lexical words, do not import those words from the PDF. Record a lexical-witness gap and use `needs-review` where the gap blocks completeness.
5. No OCR/common-spelling/semantic/assistant normalization may replace MD wording.

The user explicitly ordered this rule to be applied retroactively to **scans 91–101** before further new-page work.

## Durable current state

- source intake: **COMPLETE**;
- page placeholders: `works/kagithapoo/pages/0091.md`–`0131.md` = **41 / 41 represented**;
- retroactive MD lexical reconciliation of **91–101: COMPLETE AND APPLIED**;
- detailed audit: `works/kagithapoo/MD_LEXICAL_RECONCILIATION_0091_0101.md`;
- scan 102: already completed under the same dual-witness method and preserved;
- fully verified dual-witness pages: **20 / 41** — scans **91, 92, 94, 96, 99–114**;
- `needs-review` because MD witness is incomplete: **93, 95, 97, 98**;
- forward processing resumed by explicit user instruction; scans **103–114** are complete;
- scene assembly: **not started / not authorized**;
- English translation: **not started / not authorized**.

## Retroactive reconciliation outcome — scans 91–101

Reconciled and fully verified under the new rule:

- **91** — MD title/callout lexical forms applied; PDF controls callout placement;
- **92** — Scene-1 wording corrected to MD; misplaced MD `ராசேந்திரன்` / `மாணவமணி` reordered to PDF structure;
- **94** — difficult narrow Scene-6 wording replaced by MD lexical sequence, including `சீவி` and `புறநானூற்றிலே படித்திருக்கிறோம்`;
- **96** — MD forms including `மானப்படை`, `மாணவர் உலகம்`, `இந்தி எதிர்ப்பின்`, `எழுதி வைத்துக் கொள்ளச்` applied;
- **99** — MD wording applied and omitted `கண்:— சர்க்கார்` turn restored;
- **100** — MD wording applied with PDF stage/speaker structure and scan boundaries preserved;
- **101** — MD wording applied; PDF's three-way `மூவரும்` structure retained.

Outstanding lexical-witness gaps:

- **93** — PDF stage direction has additional words absent from MD;
- **95** — MD omits one complete `காவேரி:` paragraph and the opening of the following `மரகதம்:` paragraph;
- **97** — one PDF-structured parenthetical stage direction has no MD words at that location;
- **98** — a PDF-printed personal-name caption is absent from MD.

No missing lexical text has been copied from the PDF into those gaps.

## Existing scan 102

Scan 102 was completed before the retroactive 91–101 request. Preserve it. It closes Scene 8, contains Scene 9, closes with `(திரை)`, and begins Scene 10. Its words follow the MD; PDF controls its structure/punctuation.

## Exact next activity

Process **scans 115–124** using the locked dual-witness rule. Preserve scans **93, 95, 97 and 98** as unresolved lexical-gap records; do not backfill their missing words from the PDF. On scan **124**, preserve the source-visible post-Scene-21 heading exactly as `காட்சி,` with no invented numeral.

No scene assembly and no English translation.

## Scene-numbering anomaly safeguard

After `காட்சி 21`, scan 124 prints a new heading only as `காட்சி,` with no numeral. Scan 125 later prints `காட்சி 24.`. Do not invent `காட்சி 22` or `காட்சி 23`.

# CLOSED WORK SAFEGUARDS

`மணிமகுடம்` remains **COMPLETE / CLOSED**: Tamil physical archive 170/170, Tamil scenes 47/47 PASS, independent English 47/47 PASS, release READY/FINAL.

`கலைஞரின் நான்மணி மாலை` remains closed at its previously recorded completed state. Do not reopen closed work while continuing `காகிதப்பூ`.