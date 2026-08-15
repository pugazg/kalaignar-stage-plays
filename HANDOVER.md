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

Scans **1–16 are now fully verified**.

This means the title/front matter, Anna's `அணிந்துரை`, Karunanidhi portrait page, and Kalaignar's complete introductory/prefatory section through printed page `xvi` are all represented by character-level checked page records.

### Scan 16 — newly verified

`works/silappathikaram-nataka-kappiyam/pages/0016.md`

- Printed page marker: `xvi` at lower left.
- Contains the final asterisk-led observation begun as part of the adaptation-change series on scan 15.
- Complete closing prose and acknowledgements were checked against enlarged 400-ppi and targeted 800-ppi source views.
- Source-supported forms preserved include `சிலம்புகளையுந்தான்`, `யிருக்காது`, `கண்டிருக்கமுடியாது`, `ஒற்றைச்சிலம்பு`, `அச்சியற்றிய`, `அவர்கட்கும்`, `என்னருந்தலைவர்`, and the visibly printed `தலதாழ்ந்த`.
- Physical word splits retained include `வாங்கு / வது`, `உரு / வாக்கிய`, and `வெளியீட் / டார்க்கும்`.
- The acknowledgements visibly name `டி. ஜி. நாராயணசாமி`, `பி. என். கே.`, `ஐடியல் அச்சகத்தார்`, artists `அமுதன்` and `விஜயா`, archaeological-department director `திரு. நாகசாமி`, `அஞ்சுகம் வெளியீட்டார்`, and `ஆனந்தம்`, `கோபாலசாமி`, `தினகரன்`.
- The page closes with `அன்புடன்,` above a large facsimile signature. The signature remains image evidence rather than conjectural typed text.

## 30-page structural batch state

Scans **10–39 inclusive** were previously directly inspected and individually represented. Scans 10–16 have now been upgraded to `verified` during the detailed review pass. Scans 17–39 remain `needs-review` until their complete Tamil dialogue, headings, stage directions and illustrations/captions are enlarged and checked character by character.

The dramatic body from scans 17–39 is mapped through `காட்சி-10`, but scene assembly must not begin from pages still marked `needs-review`.

## Published English translation witness — future phase

The user supplied `TVA_BOK_0065513_Tale_of_the_anklet_and_one_act_plays.pdf`, recorded in `metadata/english-translation-source.md`. It remains a **secondary published translation witness** only. Do not use it to silently alter Tamil readings or to solve stylized Tamil headings by translation inference.

## Next activity

1. Begin detailed verification of **scan 17 / காட்சி-1**.
2. Enlarge the decorative heading before accepting or correcting the provisional scene-title reading.
3. Transcribe the complete printed text, including stage directions, paragraphing, punctuation and any printed caption associated with the lower illustration.
4. Keep illustration/image evidence distinct from dramatic text.
5. Promote scan 17 to `verified` only after complete character-level comparison.
6. Continue sequentially through scans 18–39 before scene assembly.
7. Do not begin English translation until Tamil transcription/audit is complete.
