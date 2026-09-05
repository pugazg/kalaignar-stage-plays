# Kalaignar Stage Plays — Handover

Repository: `pugazg/kalaignar-stage-plays`, branch `main`.

## Startup rule

Always fetch live `main` first and preserve newer durable state. Permanent workflow: `STAGE_PLAY_PROCESSING_GUIDE.md`.

# ACTIVE WORK — காகிதப்பூ

## Mandatory startup

Read before any further work:

1. `STAGE_PLAY_PROCESSING_GUIDE.md`;
2. this `HANDOVER.md`;
3. `NEXT_CHAT_PROMPT.md`;
4. `works/kagithapoo/README.md`;
5. `works/kagithapoo/SCENE_ASSEMBLY_PROGRESS.md`;
6. `works/kagithapoo/LEXICAL_GAP_ADJUDICATION.md`;
7. `works/kagithapoo/PAGE_LAYER_CONSISTENCY_AUDIT.md`;
8. `works/kagithapoo/MD_LEXICAL_RECONCILIATION_0091_0101.md`;
9. `works/kagithapoo/indexes/page-map.md` and relevant verified page records.

## Source identity

Controlling PDF: `TVA_PRL_0001638_முரசொலி_ பொங்கல் மலர்_ 1967.pdf`

- SHA-256: `b0a6499ba072a7346f8c2544a8a61c2363d83a60cad5227482008043cd310ec1`;
- size: **45,718,751 bytes**;
- full PDF: **131 scans**;
- selected work range: **91–131 = 41 scans**.

Primary lexical witness: `kaagidha_poo.md`.

## Witness / assembly policy

- MD is the primary lexical witness.
- PDF controls boundaries, reading order, scene/speaker/paragraph structure, punctuation, brackets, headings/numbers, photographs, captions, boxed features and physical evidence.
- The user explicitly authorized direct PDF lexical fallback only for the five genuine MD omissions on scans **93, 95, 97, 98 and 130**; those gaps are closed in the verified page layer.
- Scene assembly uses only verified page records. Mechanical page/column line breaks may be removed for readability, but wording, punctuation, speaker labels, stage directions and source scene numbering must not be editorially normalized.
- The source-compressed `காட்சிகள்: 2, 3, 4, 5.` block must not be expanded into invented dialogue.

## Durable page-layer state

**PAGE LAYER COMPLETE / CLOSED.**

- processed: **41 / 41**;
- verified: **41 / 41**;
- `needs-review`: **0**;
- final consistency audit: **PASS**.

## Durable scene-assembly state

**SCENE ASSEMBLY AUTHORIZED / IN PROGRESS.**

Committed assembly-reviewed files:

- `works/kagithapoo/scenes/01.md` — Scene 1, scans 92–93;
- `works/kagithapoo/scenes/02-05.md` — source-compressed representation of `காட்சிகள்: 2, 3, 4, 5.` on scan 93; no unprinted dialogue invented;
- `works/kagithapoo/scenes/06.md` — Scene 6, scans 93–94;
- `works/kagithapoo/scenes/07.md` — Scene 7, scans 94–98; verified 96→97 and 97→98 continuations joined mechanically; verified PDF-fallback wording from scans 95 and 97 retained.

The scan-98 printed photograph caption `ஓ. எம். சுப்பிரமணியன்,` belongs after the `காட்சி 8.` boundary and is therefore not included in Scene 7.

Tracking: `works/kagithapoo/SCENE_ASSEMBLY_PROGRESS.md`.

English translation: **not started / not authorized**.

## Structural safeguards

- scan 124: source heading **`காட்சி,`** with no numeral;
- scan 125: source-visible **`காட்சி 24.`**;
- never invent Scenes 22/23;
- scan 130 boxed `கண்டுபிடியுங்கள்` remains separate from dramatic reading order;
- scan 131 closes with `(முற்றும்)` and then `நாடகத்தில்—பங்கேற்பவர்கள்!`.

## Exact next activity

Assemble and page-record-check **Scene 8** from verified scans **98–102**. Preserve the scan-98 photograph caption as a separate non-dialogue source element and join only mechanical physical-page breaks. Then update `SCENE_ASSEMBLY_PROGRESS.md`, README, HANDOVER and NEXT_CHAT_PROMPT.

Do not begin English translation without separate authorization.

# CLOSED WORK SAFEGUARDS

`மணிமகுடம்` remains complete/closed. `கலைஞரின் நான்மணி மாலை` remains closed. Do not reopen closed work while handling `காகிதப்பூ`.