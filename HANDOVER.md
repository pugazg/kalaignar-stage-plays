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

Scans **1–13 are now fully verified**.

### Scan 13 — newly verified

`works/silappathikaram-nataka-kappiyam/pages/0013.md`

- Complete dense author-preface prose transcribed and checked against an enlarged 400-ppi render.
- The first paragraph physically continues scan 12's unfinished quotation; the page boundary is retained rather than silently repaired.
- No printed page number is visible, so `xiii` is not inferred.
- Source-supported material includes `இளங்கோகொண்டு`, `அகஸ்டஸ் சீசர்`, `நீரோ`, `கடிமதில் வாயிற் சிறந்த - அடல்வாள் யவனர்`, `தண்கமழ் தேறல்`, `பவுண்டு`, `காவிரிஸ்`, and `புடோக்கா`.
- The final printed words are `பாண்டி நாட்டுக் கொற்கைப்`; the sentence continues physically on scan 14 and is deliberately not completed inside scan 13.

## 30-page structural batch state

Scans **10–39 inclusive** were previously directly inspected and individually represented. Scans 10–13 are now verified. Scans 14–39 remain `needs-review` until their complete Tamil text is enlarged and checked character by character.

Visible Roman pagination in the remaining preface includes scan 14=`xiv`, scan 15=`xv`, scan 16=`xvi`. Scan 16 closes with `அன்புடன்,` and facsimile signature.

The dramatic body from scans 17–39 is mapped through `காட்சி-10`, but scene assembly must not begin from pages still marked `needs-review`.

## Published English translation witness — future phase

The user supplied `TVA_BOK_0065513_Tale_of_the_anklet_and_one_act_plays.pdf`, recorded in `metadata/english-translation-source.md`. It remains a **secondary published translation witness** only. Do not use it to silently alter Tamil readings or to solve stylized Tamil headings by translation inference.

## Next activity

1. Process **scan 14**, visibly carrying printed page `xiv`.
2. Begin with the continuation of scan 13's terminal `பாண்டி நாட்டுக் கொற்கைப்`.
3. Preserve every printed line, punctuation mark, inset/list-like passage and page boundary at enlarged/native resolution.
4. Promote scan 14 to `verified` only after complete character-level comparison.
5. Continue sequentially through scans 15–39 before scene assembly.
6. Do not begin English translation until Tamil transcription/audit is complete.
