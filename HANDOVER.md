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

Scans **1–11 are now fully verified**.

### Scan 11 — newly verified

`works/silappathikaram-nataka-kappiyam/pages/0011.md`

- Upper portion: black-and-white coastal/settlement photograph associated with பூம்புகார்.
- Lower portion: complete opening author-preface prose transcribed and checked against an enlarged 300-ppi render.
- Opening: `பூம்புகார் - இதுதான் இன்றைய பூம்புகார் - ...`
- Source-specific material preserved includes `காவிரிப்பூம் / பட்டினத்துக்`, `தென்மாரி பொழிகின்ற தீந்தமிழ் இலக்கிய`, `அவந்திநன்னன்`, `வச்சிரநாட்டு`, `முத்துப்பந்தர்`, `பட்டிமண்டபம்`, and `தாழாது - தாழாது!`.
- No printed page number is visible; none is inferred.
- Final printed line ends with `இமயம்`; the sentence continues on scan 12 and is deliberately not completed inside scan 11.

## 30-page structural batch state

Scans **10–39 inclusive** were previously directly inspected and individually represented. Scan 10 was already verified. Scans 12–39 remain `needs-review` until their complete Tamil text is enlarged and checked character by character.

Visible Roman pagination in the remaining preface includes scan 12=`xii`, scan 14=`xiv`, scan 15=`xv`, scan 16=`xvi`. Scan 16 closes with `அன்புடன்,` and facsimile signature.

The dramatic body from scans 17–39 is mapped through `காட்சி-10`, but scene assembly must not begin from pages still marked `needs-review`.

## Published English translation witness — future phase

The user supplied `TVA_BOK_0065513_Tale_of_the_anklet_and_one_act_plays.pdf`, recorded in `metadata/english-translation-source.md`. It remains a **secondary published translation witness** only. Do not use it to silently alter Tamil readings or to solve stylized Tamil headings by translation inference.

## Next activity

1. Process **scan 12** in the detailed transcription-review pass.
2. Verify the visible printed page marker `xii`.
3. Preserve the continuation from scan 11 exactly as printed and transcribe the centred verse-like passage without modernization.
4. Promote scan 12 to `verified` only after complete character-level comparison.
5. Continue sequentially through scans 13–39 before scene assembly.
6. Do not begin English translation until Tamil transcription/audit is complete.
