# Kalaignar Stage Plays — Handover

Repository: `pugazg/kalaignar-stage-plays`, branch `main`.

## Startup rule

Always fetch live `main` first and treat it as authoritative. Preserve newer durable state. Do not reset, overwrite, repeat, or reopen completed work because a copied prompt contains an older checkpoint.

Permanent workflow: `STAGE_PLAY_PROCESSING_GUIDE.md`.

# ACTIVE WORK — காகிதப்பூ

## Mandatory startup

Before any source-dependent change, read completely:

1. `STAGE_PLAY_PROCESSING_GUIDE.md`;
2. this `HANDOVER.md`;
3. `NEXT_CHAT_PROMPT.md`;
4. `works/kagithapoo/README.md`;
5. `works/kagithapoo/SOURCE_INTAKE.md`;
6. `works/kagithapoo/metadata/source.md`;
7. `works/kagithapoo/indexes/page-map.md`;
8. relevant `works/kagithapoo/pages/*.md` files for the active batch.

Re-resolve / attach the controlling PDF before page-level visual work.

## Controlling source

`TVA_PRL_0001638_முரசொலி_ பொங்கல் மலர்_ 1967.pdf`

Raw identity:

- SHA-256: `b0a6499ba072a7346f8c2544a8a61c2363d83a60cad5227482008043cd310ec1`;
- size: **45,718,751 bytes**;
- full PDF: **131 physical scans**;
- user-selected `காகிதப்பூ` range: **91–131 inclusive**;
- selected range: **41 physical scans**.

The PDF itself remains external to the repository.

## Catalog context supplied by user

- title: **காகிதப்பூ**;
- author: **கலைஞர் மு. கருணாநிதி**;
- publication: **முரசொலி-பொங்கல் மலர்**;
- edition/year: **1967**;
- description: `பேசப்படும் சோசலிசம் என்பது பளபளப்பிலே, பார்வையிலேதான் பாரிஜாதப்பூ என்றும், உண்மையில் அது ஒரு காகிதப்பூ என்றும் விளக்கும் நாடகம் இது.`

Keep this catalog layer distinct from verbatim source transcription unless each detail is directly source-verified.

## Durable current state

- source intake: **COMPLETE**;
- work root: `works/kagithapoo/`;
- page placeholders: `pages/0091.md` through `0131.md` = **41 / 41 represented**;
- verified Tamil page transcriptions: **10 / 41** — scans **91–100**;
- first page-level batch: **COMPLETE**;
- next page-level batch: **101–110**;
- scene assembly: **not started / not authorized**;
- English translation: **not started / not authorized**.

### Durable first-batch page commits

- scan 91 — `a5a89c50e09c2c3f8e9d9176dc26b430ee71ef36` — `Transcribe and verify Kagithapoo scan 91`;
- scan 92 — `60ec231bcc277e792df95c4230b4729e26b57096` — `Transcribe and verify Kagithapoo scan 92`;
- scan 93 — `b0290ae07a8fd5d49f61f72e913e2fd31c0575c9` — `Transcribe and verify Kagithapoo scan 93`;
- scan 94 — `4c5b661dc592b01f50b99dd61954ad5d5aae2cb0` — `Transcribe and verify Kagithapoo scan 94`;
- scan 95 — `14a57821c8b33390004ae2d13d9ad1f4bee26ab4` — `Transcribe and verify Kagithapoo scan 95`;
- scan 96 — `8fc1e2e171afb1de29723b3066be925d35d342a0` — `Transcribe and verify Kagithapoo scan 96`;
- scan 97 — `fa486ecbf0a4d5cd714b4585730de7ed07615cb8` — `Transcribe and verify Kagithapoo scan 97`;
- scan 98 — `984f192a5c3f74229f49970d21a157730ccb8f40` — `Transcribe and verify Kagithapoo scan 98`;
- scan 99 — `e58f5ad7df6f711246eb84d78e627c75fa3f8a74` — `Transcribe and verify Kagithapoo scan 99`;
- scan 100 — `0cd7fa6a72abfaab108ac656a53e4b62be892056` — `Transcribe and verify Kagithapoo scan 100`.

Tracking checkpoint after completion of scans 91–100: `e344a8c3ea543ccce27c36e118ff64792cd0d2e4`.

### First-batch source-sensitive notes

- Scan 91 is the staged `காகிதப்பூ` title opener.
- Scan 92 begins `காட்சி 1`.
- Scan 93 closes Scene 1, preserves `காட்சிகள்: 2, 3, 4, 5.`, and begins `காட்சி: 6.`.
- Scan 94's difficult narrow Scene-6 continuation required a fresh 600-dpi render before verification. Source forms including `சேலி`, `தணற்காடு`, and `இல்லே` are preserved without normalization; Scene 6 closes and `காட்சி 7.` begins on that scan.
- Scans 95–97 continue Scene 7.
- Scan 98 closes Scene 7 and begins `காட்சி 8.`.
- Scans 99–100 continue Scene 8; scan-boundary joins were checked against adjacent scans.

### Boundary facts for later work

- scans 88–90 are preceding periodical material and outside the selected work scope;
- scan 130 begins `காட்சி 27`;
- scan 131 closes `காட்சி 27` with `(முற்றும்)` and then carries a boxed `நாடகத்தில்—பங்கேற்பவர்கள்!` block.

### Important scene-numbering anomaly

Initial source survey found:

- `காட்சி 21` begins scan 119;
- after Scene 21 closes, scan 124 prints a new heading only as `காட்சி,` with no numeral;
- scan 125 later prints `காட்சி 24.`.

Do **not** silently label the unnumbered scene as 22 or 23 and do not create a missing scene by inference. Preserve the source and resolve only from direct evidence.

## Exact next activity

Process **scans 101–110** as the second page-level transcription/verification batch.

For each scan:

1. inspect the native scan and enlarged render directly;
2. transcribe printed Tamil word-for-word, including speaker labels, punctuation, stage directions, captions and visible source marks;
3. preserve image/photograph content with concise archival description rather than invented textual content;
4. distinguish printed text from stamps, damage, bleed-through or later marks;
5. update `pages/0101.md` through `0110.md`;
6. mark `verified` only after direct visual comparison;
7. commit completed pages or small completed groups durably instead of waiting for the whole batch;
8. keep `indexes/page-map.md` synchronized as durable state advances;
9. after scan 110 passes, synchronize work README, this handover and next-chat prompt and derive the following batch from live repository state.

No scene assembly and no English translation during this phase.

## Source-sensitive safeguards

- controlling scan wins over OCR, expected spelling or semantic guesswork;
- no silent spelling, punctuation, speaker-label, stage-direction or old-glyph normalization;
- mixed-column reading order must be visually established;
- photographs/graphics are archival objects, not OCR prose;
- physical scan boundaries remain explicit;
- printed pagination is recorded only when visibly supported;
- source-visible scene numbering must not be repaired editorially.

# CLOSED WORK — மணிமகுடம்

`மணிமகுடம்` remains **COMPLETE / CLOSED** for the source-first Tamil archive + independent-English scope:

- Tamil physical archive: **170 / 170 COMPLETE**;
- Tamil scene assembly: **47 / 47 PASS**;
- independent English: **47 / 47 PASS**;
- release status: **READY / FINAL**;
- project completion: **COMPLETE / CLOSED**.

Current authorities: `works/manimagudam/RELEASE_READINESS.md` and `works/manimagudam/PROJECT_COMPLETION.md`. Do not reopen merely because the active project has changed.

# CLOSED `கலைஞரின் நான்மணி மாலை` STATE

- Tamil composite coverage: **54 / 54 PASS / COMPLETE**;
- independent English translations: **4 / 4 COMPLETE**;
- applicable 2009 witness comparisons: **3 / 3 PASS / COMPLETE**;
- `பரதாயணம்` witness comparison: **NOT APPLICABLE**.

## Permanent safeguards

- live `main` controls repository state;
- source PDFs remain external;
- provisional visual work is not durable verification until committed;
- scene assembly derives only from verified Tamil page records;
- translation is a separate later phase based on verified Tamil;
- historical checkpoint documents remain provenance evidence, not current-status authorities.
