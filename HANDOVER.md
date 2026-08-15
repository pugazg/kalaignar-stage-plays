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

Scans **1–14 are now fully verified**.

### Scan 14 — newly verified

`works/silappathikaram-nataka-kappiyam/pages/0014.md`

- Printed page marker: `xiv` at lower left.
- Complete prose, the inset Korkai quotation and the later character-name transformation passage were transcribed and checked against an enlarged 400-ppi render.
- The page physically continues scan 13's terminal `பாண்டி நாட்டுக் கொற்கைப்` with `பெருந்துறைக்கு அருகில்...`; the page boundary remains explicit rather than silently repairing the sentence.
- Source-supported forms preserved include `இணை இல்ல யென்பதை`, `நுண்ணியபருத்தி`, `முசிறித்துறை`, `தமிழிலக்கியம்`, `கர்ணகி`, `மாதகியானாள்; ஏன் / பாதகியும் ஆனாள்`, `கோவலன்; கோவிலன் ஆனான்—`, `மாச்சோட்டான்`, `மாணுக்கன்`, and `குந்தகமின்றிப்`.
- One narrow OCR check was used only as assistive evidence for the difficult reading `தரப்படுகிற உருவகமும்`; visual comparison with the scan remained authoritative.

## 30-page structural batch state

Scans **10–39 inclusive** were previously directly inspected and individually represented. Scans 10–14 are now verified. Scans 15–39 remain `needs-review` until their complete Tamil text is enlarged and checked character by character.

Visible Roman pagination in the remaining preface includes scan 15=`xv` and scan 16=`xvi`. Scan 16 closes with `அன்புடன்,` and facsimile signature.

The dramatic body from scans 17–39 is mapped through `காட்சி-10`, but scene assembly must not begin from pages still marked `needs-review`.

## Published English translation witness — future phase

The user supplied `TVA_BOK_0065513_Tale_of_the_anklet_and_one_act_plays.pdf`, recorded in `metadata/english-translation-source.md`. It remains a **secondary published translation witness** only. Do not use it to silently alter Tamil readings or to solve stylized Tamil headings by translation inference.

## Next activity

1. Process **scan 15**, visibly carrying printed page `xv`.
2. Preserve all asterisk-led passages, punctuation, paragraphing and page boundaries at enlarged/native resolution.
3. Promote scan 15 to `verified` only after complete character-level comparison.
4. Continue sequentially through scans 16–39 before scene assembly.
5. Do not begin English translation until Tamil transcription/audit is complete.
