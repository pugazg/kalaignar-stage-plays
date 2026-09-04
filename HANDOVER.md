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
8. relevant `works/kagithapoo/pages/*.md` files for the batch.

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
- verified Tamil page transcriptions: **3 / 41** — scans **91–93**;
- latest page commit: scan **93**;
- active page-level remainder of first batch: **94–100**;
- scene assembly: **not started / not authorized**;
- English translation: **not started / not authorized**.

### Durable page commits

- scan 91 — `a5a89c50e09c2c3f8e9d9176dc26b430ee71ef36` — `Transcribe and verify Kagithapoo scan 91`;
- scan 92 — `60ec231bcc277e792df95c4230b4729e26b57096` — `Transcribe and verify Kagithapoo scan 92`;
- scan 93 — `b0290ae07a8fd5d49f61f72e913e2fd31c0575c9` — `Transcribe and verify Kagithapoo scan 93`.

### Boundary facts

- scans 88–90 are preceding periodical material and outside the selected work scope;
- scan 91 visibly introduces `காகிதப்பூ` with a full-page staged photograph / title graphic;
- scan 92 begins `காட்சி 1`;
- scan 93 closes Scene 1, preserves `காட்சிகள்: 2, 3, 4, 5.`, and begins `காட்சி: 6.`;
- scan 131 closes `காட்சி 27` with `(முற்றும்)` and then carries a boxed `நாடகத்தில்—பங்கேற்பவர்கள்!` block.

### Important scene-numbering anomaly

Initial source survey found:

- `காட்சி 21` begins scan 119;
- after Scene 21 closes, scan 124 prints a new heading only as `காட்சி,` with no numeral;
- scan 125 later prints `காட்சி 24.`.

Do **not** silently label the unnumbered scene as 22 or 23 and do not create a missing scene by inference. Preserve the source and resolve only from direct evidence.

## Exact next activity

Continue with **scans 94–100** to finish the first page-level transcription/verification batch.

For each scan:

1. inspect the native scan and enlarged render directly;
2. transcribe printed Tamil word-for-word, including speaker labels, punctuation, stage directions, captions and visible source marks;
3. preserve image/photograph content with concise archival description rather than invented textual content;
4. distinguish printed text from stamps, damage, bleed-through or later marks;
5. update the corresponding page record;
6. mark `verified` only after direct visual comparison;
7. commit completed pages durably rather than waiting for the whole batch;
8. after scan 100 passes, synchronize page map, work README, this handover and next-chat prompt and set the next batch to **101–110**.

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
