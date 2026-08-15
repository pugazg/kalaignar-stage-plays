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

Scans **1–17 are now fully verified**.

The title/front matter, Anna's `அணிந்துரை`, Karunanidhi portrait page, Kalaignar's complete introductory/prefatory section through printed page `xvi`, and the first dramatic page (`காட்சி-1`) are now represented by character-level checked page records.

### Scan 17 — newly verified

`works/silappathikaram-nataka-kappiyam/pages/0017.md`

- Scene marker: `காட்சி-1`.
- Decorative title confirmed at enlarged resolution as `வஞ்சி மூதூரில் முரசறைதல்`.
- No printed page number is visible; none is inferred.
- The page uses two dramatic-text columns beneath the ornate title.
- Left column: bracketed opening stage description beginning `சேர நாட்டுத் தலை நகரான வஞ்சி மூதூரில்...` and ending `முழக்குகிறான் பூரிப்போடு!`.
- Right column: `முரசறைவோன் :` proclamation beginning `வாழ்க தமிழ்! வெல்க...` and ending `செந்தமிழர் தாயகம்!`, followed by `[முரசு முழங்குகிறது]`.
- Source forms/punctuation preserved include `தலை நகரான`, `ஆனை`, `அறிவிப்பு!....`, `இமிழ் கடல் வேலித் தமிழகம்`, the visibly printed `விற்கொடி. நாட்டிய`, and `பூரிப்போடு!`.
- Physical printed word splits retained include `இருக் / கிறது`, `வேலைப் / பாடமைந்த`, `காணப் / படுகிறது`, `தமி / ழகம்`, and `சேர / லாதர்`.
- The lower half contains a large grayscale printed image of a female figure/bust. There is no visibly printed caption on this scan, so no identity is inferred.
- Verification used the source scan plus enlarged 400-ppi and targeted 800-ppi views. The published English translation was not used to settle Tamil readings.

## 30-page structural batch state

Scans **10–39 inclusive** were previously directly inspected and individually represented. Scans 10–17 have now been upgraded to `verified` during the detailed review pass. Scans 18–39 remain `needs-review` until their complete Tamil dialogue, headings, stage directions and illustrations/captions are enlarged and checked character by character.

The dramatic body from scans 17–39 is mapped through `காட்சி-10`, but scene assembly must not begin from pages still marked `needs-review`.

## Published English translation witness — future phase

The user supplied `TVA_BOK_0065513_Tale_of_the_anklet_and_one_act_plays.pdf`, recorded in `metadata/english-translation-source.md`. It remains a **secondary published translation witness** only. Do not use it to silently alter Tamil readings or to solve stylized Tamil headings by translation inference.

## Next activity

1. Process **scan 18 / காட்சி-2**, visibly carrying printed page `2`.
2. Verify the heading `செங்குட்டுவன் பிறந்தநாள் விழா` at enlarged/native resolution.
3. Transcribe the complete two-column dialogue/stage text, speaker labels, punctuation, physical word splits and any illustration/caption evidence exactly.
4. Promote scan 18 to `verified` only after complete character-level comparison.
5. Continue sequentially through scans 19–39 before scene assembly.
6. Do not begin English translation until Tamil transcription/audit is complete.
