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

Scans **1–15 are now fully verified**.

### Scan 15 — newly verified

`works/silappathikaram-nataka-kappiyam/pages/0015.md`

- Printed page marker: `xv` at lower right.
- Complete prose and all seven printed asterisk-led observations were transcribed and checked against an enlarged 400-ppi render.
- The page begins with the author's statement about changes made in adapting the work, followed by `எடுத்துக் காட்டுகளாகச் சில:-`.
- Source-supported forms preserved include `மாறுதல்களச்`, `வனேத்`, `அழகுங்கொண்ட`, `உள்ளத்தையேப்`, `(அவன் கூன்-குருடு-கிழடு யாராக இருந்தாலும்)`, `நிகழ்ச்சி யொன்றுக`, `‘கிரேக்கக் கிழவன்’`, `பழந் தமிழகத்திற்கும்`, `கேள்விக் கண் தாக்கிறது`, `அதின அறிந்த`, `ஒருமாற்றம்`, and `அதின நான் குறித்துள்ளேன்`.
- The physical printed line break `என் / றெழுந்த` is retained rather than normalized into a reconstructed word.

## 30-page structural batch state

Scans **10–39 inclusive** were previously directly inspected and individually represented. Scans 10–15 are now verified. Scans 16–39 remain `needs-review` until their complete Tamil text is enlarged and checked character by character.

Scan 16 visibly carries `xvi` and closes the author's preface with `அன்புடன்,` and a facsimile signature. The dramatic body from scans 17–39 is mapped through `காட்சி-10`, but scene assembly must not begin from pages still marked `needs-review`.

## Published English translation witness — future phase

The user supplied `TVA_BOK_0065513_Tale_of_the_anklet_and_one_act_plays.pdf`, recorded in `metadata/english-translation-source.md`. It remains a **secondary published translation witness** only. Do not use it to silently alter Tamil readings or to solve stylized Tamil headings by translation inference.

## Next activity

1. Process **scan 16**, visibly carrying printed page `xvi`.
2. Verify the complete closing preface text, `அன்புடன்,`, the facsimile signature, punctuation and page layout at enlarged/native resolution.
3. Promote scan 16 to `verified` only after complete character-level comparison.
4. Then begin detailed verification of **scan 17 / காட்சி-1**.
5. Continue sequentially through scans 17–39 before scene assembly.
6. Do not begin English translation until Tamil transcription/audit is complete.
