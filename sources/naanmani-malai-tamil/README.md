# கலைஞரின் நான்மணி மாலை — controlling Tamil source

This folder registers the supplied Tamil composite source **`TVA_BOK_0065576_நான்மணி_மாலை.pdf`**. The PDF itself is not committed to the repository.

## Source identity

- Printed title: **கலைஞரின் நான்மணி மாலை**
- Publisher / imprint visible on scan 2: **தமிழ்க்கனி பதிப்பகம், சென்னை-28**
- Price visible on scan 3: **ரூ. 4/-**
- Printer visible on scan 3: **ஜெம் பிரஸ், சென்னை - 600 001**
- Physical scans: **54**
- SHA-256: `18d2b1405544b03507e9f92067d287cb28f5a92eaf02bed7054e6e78e5e38c89`
- File size: **146,754,449 bytes**
- External identifier carried by filename: `TVA_BOK_0065576`
- Standalone publication year: **not established from the supplied scan**

See `metadata/source.md` for the full source record.

## Composite contents

The publisher's note on scan 5 names four short plays in this volume:

1. **பரதாயணம்** — scans **6–17**; page-level Tamil visual verification **COMPLETE (12/12)**.
2. **அனார்கலி** — scans **18–26**; printed pages **13–21**; Tamil verification pending.
3. **சாக்ரடீஸ்** — scans **27–43**; printed pages **22–38**; scans 27–28 are the printed introductory note; Tamil verification pending.
4. **சேரன் செங்குட்டுவன்** — scans **44–53**; printed pages **39–48**; Tamil verification pending.

Shared source matter:

- scans **1–5**: cover / title / rights-and-price / `என்னுரை` / `பதிப்புரை`;
- scan **54**: illustrated back cover.

No page number is inferred for scan 6 merely because scan 7 prints `2`.

## Authority and first-pass policy

The supplied scan is the controlling Tamil authority. The user supplied a Gemini word-for-word first-pass transcription in chat; that text is **assistive only**. It must be checked word by word against the scan before any page is marked `verified`.

Do not silently normalize old Tamil glyph forms, spelling, punctuation, speaker labels, line breaks, stage directions, numbers or apparent print anomalies. The verified 2009 published-English one-act-play witness remains secondary and cannot override this Tamil source.

## Current checkpoint

- source registered and physical extents mapped;
- `பரதாயணம்` scans **6–17** are directly visually verified and archived at `../../works/bharathayanam/pages/`;
- material first-pass discrepancies are recorded at `../../works/bharathayanam/FIRST_PASS_DISCREPANCIES.md`;
- remaining body scans **18–53** are pending Tamil visual verification.

Next within `பரதாயணம்`: assemble and fidelity-audit the continuous play text from verified page records. After that, begin `அனார்கலி` at scan **18** / printed page **13**.