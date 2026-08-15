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

## Current verification checkpoint

Scans **1–12 are now fully verified**.

### Scan 12 — newly verified

`works/silappathikaram-nataka-kappiyam/pages/0012.md`

- Printed page marker: `xii` at lower left.
- Complete visible prose plus both indented/verse-like passages transcribed and checked against an enlarged 400-ppi render.
- The page begins by physically continuing scan 11's terminal `இமயம்` with `சென்று கண்ணகிக்குச்...`; this cross-page sentence is not silently joined inside either page record.
- Source forms preserved include `தமிழ்மீதுள்ள`, `நலங்`, `தொண்டர்க்குத் தொண்டனுடைய`, `ஈழத் துணவும்`, `காழகத் தாக்கமும்`, `திருவிடைக் கழி`, `குராப் பள்ளி`, and `பாடி யிருக்கிறார்`.
- The final quotation ends physically at `நீவிர் இரு பெருந்` and continues on scan 13; it is deliberately not completed from context in scan 12.

## 30-page structural batch state

Scans **10–39 inclusive** were previously directly inspected and individually represented. Scans 10–12 are now verified. Scans 13–39 remain `needs-review` until their complete Tamil text is enlarged and checked character by character.

Visible Roman pagination in the remaining preface includes scan 14=`xiv`, scan 15=`xv`, scan 16=`xvi`. Scan 16 closes with `அன்புடன்,` and facsimile signature.

The dramatic body from scans 17–39 is mapped through `காட்சி-10`, but scene assembly must not begin from pages still marked `needs-review`.

## Published English translation witness — future phase

The user supplied `TVA_BOK_0065513_Tale_of_the_anklet_and_one_act_plays.pdf`, recorded in `metadata/english-translation-source.md`. It remains a **secondary published translation witness** only. Do not use it to silently alter Tamil readings or to solve stylized Tamil headings by translation inference.

## Next activity

1. Process **scan 13** in the detailed transcription-review pass.
2. Begin with the continuation of scan 12's unfinished quotation and preserve its exact page boundary.
3. Verify every printed line, punctuation mark and paragraph at enlarged/native resolution.
4. Do not infer a page number for scan 13 unless one is directly visible.
5. Promote scan 13 to `verified` only after complete character-level comparison.
6. Continue sequentially through scans 14–39 before scene assembly.
7. Do not begin English translation until Tamil transcription/audit is complete.
