# Kalaignar Stage Plays — Handover

## Repository

`pugazg/kalaignar-stage-plays` on `main`.

## Permanent rules

Read `STAGE_PLAY_PROCESSING_GUIDE.md` completely before continuing any work.

The supplied Tamil scan is the controlling source. Do not silently modernize, correct, normalize, reconstruct or improve the Tamil. OCR is assistive only. Source PDFs are not committed to the repository.

## Current work

**சிலப்பதிகாரம் — நாடகக் காப்பியம்**  
Path: `works/silappathikaram-nataka-kappiyam/`

Tamil source:

`TVA_BOK_0016473_சிலப்பதிகாரம்_நாடகக்_காப்பியம்.pdf`

Source facts already recorded:

- 88 scan pages
- SHA-256 `2886c8eaa9d79239eba3e9ed0ddefc4c7208da4761384ee7a8b4176e6b1a24dd`
- 49,459,844 bytes
- scan 17 begins `காட்சி-1`
- scan 18 begins `காட்சி-2` and visibly carries printed page `2`
- scan 88 visibly carries `காட்சி-38`

## Completed page records

### Scan 1 — verified

`works/silappathikaram-nataka-kappiyam/pages/0001.md`

Title / imprint page. Important source-specific punctuation preserved exactly:

- lower left: `பதிப்புரிமை ]`
- lower right: `[ விலை ரூ. 5`

### Scan 2 — verified

`works/silappathikaram-nataka-kappiyam/pages/0002.md`

Anna photograph/caption page. Printed caption preserved separately from library/copy marks.

### Scan 3 — verified

`works/silappathikaram-nataka-kappiyam/pages/0003.md`

Opening prose page of the `அணிந்துரை`; printed page marker `iii`.

### Scan 4 — verified

`works/silappathikaram-nataka-kappiyam/pages/0004.md`

Continuation of the `அணிந்துரை`; printed page marker `iv` at lower left.

### Scan 5 — verified

`works/silappathikaram-nataka-kappiyam/pages/0005.md`

Continuation of the `அணிந்துரை`. No printed page marker is visibly present; do **not** infer `v` from neighbouring pagination.

The page was checked against an enlarged 300-ppi render. Source-supported readings and typography preserved include:

- `கொணர்ந்து`
- `அந்நாள் நல்வாழ்வை`
- `தமிழ் ஆளுநிறன்`
- `செயற்பட்டதாக`
- doubled question marks in the quoted question
- `அழகுதரும்`
- `நிறையுருவைக்`
- physical line break `அமைக்கப்பட் / டிருக்கிறது!`

No library stamp or later handwriting crosses this prose.

## Published English translation witness — future phase

The user supplied:

`TVA_BOK_0065513_Tale_of_the_anklet_and_one_act_plays.pdf`

Recorded in:

`works/silappathikaram-nataka-kappiyam/metadata/english-translation-source.md`

Source facts:

- title: **Tale of the Anklet and One Act Plays**
- series/display line: **Kalaignar in English Translation**
- Bharathiar University / Macmillan
- first published **2009**
- `Tale of the Anklet` translated by **T. G. Narayanaswamy**
- `One Act Plays` translated by **M. D. Jayabalan**
- editors: **P. Marudanayagam** and **V. Murugan**
- English contents list **38** numbered sections for `Tale of the Anklet`
- SHA-256 `d1f00bc5738f381fbe9547c718c35d8b73ad5148cbecdd7582bb8797ffe30cdb`
- 96,518,108 bytes; 158 scan pages

Policy: this is a **secondary published translation witness**, not authority for the Tamil archival text. Do not use it to silently alter Tamil readings. When translation work eventually begins, collate it against the completed verified Tamil transcription, preserve translator choices separately, and respect copyright rather than committing the scanned English book or reproducing it extensively.

## Page-map state

`indexes/page-map.md` records scans 1–5 individually as `verified`. Remaining Anna-foreword startup range is now `6–9`.

## Exact checkpoint

Scans **1–5 are complete and verified**. No dramatic body page has yet been transcribed.

## Next activity

1. Process **scan page 6**, visibly carrying printed page `vi`.
2. Preserve every source-supported spelling, punctuation mark and paragraph break.
3. Use enlarged/native scan inspection where small type is uncertain.
4. Continue sequentially through scans 7–9 only after each preceding page is visually checked.
5. Expand `indexes/page-map.md` one scan at a time.
6. Do not assemble scenes yet.
7. Do not begin English translation yet; retain the published English volume only as a documented future witness until the Tamil archival text is complete and audited.