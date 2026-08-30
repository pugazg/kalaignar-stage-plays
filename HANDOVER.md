# Kalaignar Stage Plays — Handover

## Repository

`pugazg/kalaignar-stage-plays` on `main`.

Permanent workflow: `STAGE_PLAY_PROCESSING_GUIDE.md`.

## Active controlling source — கலைஞரின் நான்மணி மாலை

An authentic Tamil source has reopened the repository's one-act-play Tamil work:

- filename: `TVA_BOK_0065576_நான்மணி_மாலை.pdf`;
- scans: **54**;
- SHA-256: `18d2b1405544b03507e9f92067d287cb28f5a92eaf02bed7054e6e78e5e38c89`;
- file size: **146,754,449 bytes**;
- title: **கலைஞரின் நான்மணி மாலை**;
- publisher / imprint visible: **தமிழ்க்கனி பதிப்பகம், சென்னை-28**;
- price visible: **ரூ. 4/-**;
- printer visible: **ஜெம் பிரஸ், சென்னை - 600 001**;
- standalone publication year: **not established from the scan**;
- source PDF remains external and is not committed.

Source registry: `sources/naanmani-malai-tamil/`.

## Physical source map

- scans **1–5**: shared front matter;
- scans **6–17**: **பரதாயணம்**; scan 6 unnumbered, scans 7–17 printed pages 2–12;
- scans **18–26**: **அனார்கலி**, printed pages 13–21;
- scans **27–43**: **சாக்ரடீஸ்**, printed pages 22–38; scans 27–28 are introductory note;
- scans **44–53**: **சேரன் செங்குட்டுவன்**, printed pages 39–48;
- scan **54**: illustrated back cover.

The publisher's note on scan 5 explicitly names these four short plays.

## First-pass transcription policy

The user supplied a Gemini first-pass transcription of the volume. Treat it only as a working/navigation layer.

The scan is controlling. Every word must be visually checked. Do not silently normalize old Tamil glyphs, spelling, punctuation, speaker labels, repetition, stage directions, physical line/page breaks or apparent source anomalies.

## Completed work — பரதாயணம்

Work folder: `works/bharathayanam/`.

### Page-level Tamil checkpoint — COMPLETE

- scans **6–17**: **12/12 visually verified**;
- files: `pages/0006.md` through `pages/0017.md`;
- unresolved literary-text readings: **0**;
- material Gemini/source differences: `FIRST_PASS_DISCREPANCIES.md`.

### Continuous assembly / fidelity checkpoint — PASS / COMPLETE

- assembled reading: `scenes/continuous-play.md`;
- no source scene number exists; assembly uses `scene: null` and does not invent a `காட்சி`;
- page-record ↔ assembly review: `ASSEMBLY_FIDELITY_REVIEW.md`;
- verified page records used: **12/12**;
- unresolved assembly discrepancies: **0**;
- speaker-label counts match page records exactly:
  - `பாகவதர் :` — 1;
  - `சிஷ்யன் :` — 1;
  - `பாக :` — 63;
  - `சிஷ் :` — 64.

Important source-controlled findings that must not be reverted:

- scan 9: `நடத்து`, and `இது தான்`;
- scan 10: `(கோபமாக) என்னு சொல்லு!`;
- scan 11: `கன்யா சுல்க`, `நான் காரணமாயிருக்கமாட்டேன்`, `எப்படியம்மா?`;
- scan 12: **`பட்டங் கட்டிவிட்டு`**, not Gemini's `பட்டங் சட்டிவிட்டு`;
- scan 13: `இட்டது தான்`, `ஒரு நாடகம்`;
- scan 14: source line `சிஷ் : சீதை........` exists and was omitted by Gemini;
- scan 15→16: page-final `பாதுகாப்` + next-page initial `பாக` = physical `பாதுகாப்பாக`; scan-16 initial `பாக` is not a speaker label;
- scan 15: source physically prints `நீயல்ல` / `வர் தெய்வம்!`; continuous assembly mechanically joins this as `நீயல்லவர் தெய்வம்!` and **must not** normalize it to `நீயல்லவா தெய்வம்!`;
- scan 17: two consecutive `சிஷ்` labels are source-real; preserve them;
- ending forms `மோக்ஷத்திற்குப்`, `மோட்சத்திற்கும்`, `மோசத்திற்கும்`, `நமப் பகுத்தறிவுபதே!` are source-controlled.

### Exact next activity

Begin **`அனார்கலி` Tamil visual verification** at scan **18** / printed page **13**.

Process `அனார்கலி` under `STAGE_PLAY_PROCESSING_GUIDE.md` using the supplied Gemini transcription only as a first-pass/navigation layer. The Tamil scan controls every reading. Do not use the completed 2009 published-English witness to reconstruct or override Tamil.

## Existing one-act work entities

- `works/anarkali/` — Tamil scans **18–26**;
- `works/socrates/` — Tamil scans **27–43**;
- `works/cheran-senguttuvan/` — Tamil scans **44–53**.

Their previously completed 2009 published-English transcriptions remain **secondary witnesses only**. They must not be used to overwrite or reconstruct Tamil source readings.

## Completed Silappathikaram state — preserve unchanged

`works/silappathikaram-nataka-kappiyam/` remains complete and locked at its previously reviewed state:

- **88/88 scans** visually verified;
- Tamil transcription audit: **PASS**;
- **38/38 numbered scenes** plus separate closing tableau assembled / fidelity passed;
- global Tamil source review: **PASS**;
- independent English translation: **COMPLETE / READY**;
- published-English secondary-witness comparison: **PASS / COMPLETE**.

Do not revert the scan-87 source corrections already recorded there (`தலைவர்களாம்`, `அன்னை நற்சோணையே`, `ஈடற்ற புலவனே`).

## Permanent terminology controls

Retain Kalaignar's rhetorical force, cadence, repetition, humour, emotional escalation and dramatic register.

`அந்தணர்` is not automatically “Brahmin.” Preserve distinctions among `பிராமண`, `பார்ப்பன`, `பார்ப்பார்`, `அந்தணர்`, `மறையவன் / மறையவர்`, and related terms in any future translation phase.
