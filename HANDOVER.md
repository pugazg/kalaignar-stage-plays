# Kalaignar Stage Plays — Handover

## Repository

`pugazg/kalaignar-stage-plays` on `main`.

Permanent workflow: `STAGE_PLAY_PROCESSING_GUIDE.md`.

## Active controlling source — கலைஞரின் நான்மணி மாலை

A new authentic Tamil source has been supplied, reopening the repository's one-act-play Tamil work:

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
- scans **6–17**: **பரதாயணம்**; scan 6 has no visible printed page number, scans 7–17 show pages 2–12;
- scans **18–26**: **அனார்கலி**, printed pages 13–21;
- scans **27–43**: **சாக்ரடீஸ்**, printed pages 22–38; scans 27–28 are introductory note;
- scans **44–53**: **சேரன் செங்குட்டுவன்**, printed pages 39–48;
- scan **54**: illustrated back cover.

The publisher's note on scan 5 explicitly names these four short plays.

## First-pass transcription policy

The user supplied a Gemini first-pass transcription of the volume. Treat it only as a working/navigation layer.

The scan is controlling. Every word must be visually checked. Do not silently normalize old Tamil glyphs, spelling, punctuation, speaker labels, repetition, stage directions, physical line splits or apparent source anomalies.

The first verified page already proves that the first pass contains material OCR/order errors: scan 6 has a non-Tamil OCR fragment and loses/reorders the opening `பாக` / `சிஷ்` dialogue around `உலகமென்றால்........?`.

## Active work — பரதாயணம்

Work folder: `works/bharathayanam/`.

Current durable checkpoint:

- scan **6**: **verified** at `pages/0006.md`;
- next scan: **7** / printed page **2**;
- remaining `பரதாயணம்` scans **7–17**: not started.

Next activity: visually verify scans **7–17** sequentially against the Gemini first pass and record discrepancies. Do not move to `அனார்கலி` until this play's page-level Tamil pass is complete.

## Existing one-act work entities

The previously registered work entities now have a controlling Tamil source:

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
