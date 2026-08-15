# Kalaignar Stage Plays — Handover

## Repository

`pugazg/kalaignar-stage-plays` on `main`.

## Permanent rules

Read `STAGE_PLAY_PROCESSING_GUIDE.md` completely before continuing any work.

The supplied Tamil scan is the controlling source. Do not silently modernize, correct, normalize, reconstruct or improve the Tamil. OCR is assistive only. Source PDFs are not committed to the repository.

## Current work

**சிலப்பதிகாரம் — நாடகக் காப்பியம்**  
Path: `works/silappathikaram-nataka-kappiyam/`

Tamil source: `TVA_BOK_0016473_சிலப்பதிகாரம்_நாடகக்_காப்பியம்.pdf`

Source facts:

- 88 scan pages
- SHA-256 `2886c8eaa9d79239eba3e9ed0ddefc4c7208da4761384ee7a8b4176e6b1a24dd`
- 49,459,844 bytes
- scan 17 begins `காட்சி-1`
- scan 88 visibly carries `காட்சி-38`

## Exact checkpoint after 30-page batch

The user requested that the next **30 pages** be considered in one activity. Scans **10–39 inclusive** were therefore directly inspected and individually represented in `pages/0010.md` through `pages/0039.md`.

### Verified

- Scans **1–9**: previously complete and verified.
- Scan **10**: author photograph/caption page, now verified.

### Directly inspected / needs-review

- Scans **11–16**: author's prefatory material; individual page records exist. Visible Roman pagination recorded where secure: scan 12=`xii`, scan 14=`xiv`, scan 15=`xv`, scan 16=`xvi`. Scan 16 closes with `அன்புடன்,` and facsimile signature.
- Scans **17–39**: dramatic body mapped page by page through `காட்சி-10`. Individual files exist, but remain `needs-review` because their complete dialogue/prose has not yet received enlarged character-by-character verification.

Do **not** misread `needs-review` as uninspected: these pages were visually inspected for page identity, scene boundaries, layout, illustrations/photos, visible pagination and major headings. They are intentionally not called `verified` until full text is audited.

## Scene map through scan 39

- scan 17 — `காட்சி-1`; decorative title provisionally read `வஞ்சி மூதூரில் முரசறைதல்`
- scan 18 — `காட்சி-2`; `செங்குட்டுவன் பிறந்தநாள் விழா`; printed page `2`
- scan 19 — `காட்சி-3`; stylized title provisional, enlarged audit still required
- scan 21 — `காட்சி-4`; `இளங்கோ துறவு`
- scan 24 — `காட்சி-5`; `சிலம்பின் தோற்றம்`; printed page `8`
- scan 26 — `காட்சி-6`; ornate title provisionally read `பூம்புகார்ப் பொற்றொடி`
- scan 29 — `காட்சி-7`; `கலைக்கரசி மாதவி`
- scan 33 — `காட்சி-8`; `கண்ணகி இல்லறம்`
- scan 36 — `காட்சி-9`; stylized title provisionally read `பிரிவினை தந்த பேதை`
- scan 39 — `காட்சி-10`; `மாதவி இல்லம்`; ornate scene title intentionally left unresolved rather than guessed

Other secure printed page numbers in the batch include scan 20=`4`, 22=`6`, 28=`12`, 31=`15`, 32=`16`, 34=`18`, and 38=`22`. Where a number was not secure, none was inferred.

## Batch documentation

`works/silappathikaram-nataka-kappiyam/BATCH_0010_0039_REVIEW.md`

This document explains exactly what was completed in the 30-page pass and why scans 11–39 remain `needs-review`.

## Published English translation witness — future phase

The user supplied `TVA_BOK_0065513_Tale_of_the_anklet_and_one_act_plays.pdf`, recorded in `metadata/english-translation-source.md`. It remains a **secondary published translation witness** only. Do not use it to silently alter Tamil readings or to solve stylized Tamil headings by translation inference.

## Next activity

1. Resume at **scan 11** for the detailed transcription-review pass.
2. Enlarge/native-render each page and transcribe every printed line, punctuation mark, paragraph break, caption and special inset.
3. For scene pages, preserve speaker labels, stage directions, column reading order and physical page breaks exactly.
4. Promote each page from `needs-review` to `verified` only after character-level comparison.
5. Proceed sequentially through scan 39 before scene assembly.
6. Do not begin English translation until Tamil transcription/audit is complete.