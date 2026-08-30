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

1. **பரதாயணம்** — scans **6–17**; Tamil page verification **COMPLETE (12/12)**; continuous assembly/fidelity **PASS / COMPLETE**; independent English translation **PASS / COMPLETE**.
2. **அனார்கலி** — scans **18–26**; printed pages **13–21**; Tamil page verification **COMPLETE (9/9)**; four-scene assembly/fidelity **PASS / COMPLETE**.
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

- `பரதாயணம்` scans **6–17**: Tamil page/assembly gate **PASS / COMPLETE**; reviewed English translation **PASS / COMPLETE**.
- `அனார்கலி` scans **18–26**: **9/9 visually verified**, four source scenes **4/4 assembled**, page-record ↔ scene-assembly fidelity **PASS / COMPLETE**.
- `அனார்கலி` scenes: `../../works/anarkali/scenes/01.md` through `04.md`.
- `அனார்கலி` assembly audit: `../../works/anarkali/ASSEMBLY_FIDELITY_REVIEW.md`.
- remaining unverified body scans: **27–53** (`சாக்ரடீஸ்`, `சேரன் செங்குட்டுவன்`).

Next source-sequential Tamil activity: begin **`சாக்ரடீஸ்` at scan 27 / printed page 22**. Scans 27–28 are introductory text before its numbered scenes. The Gemini transcription remains assistive only and the completed 2009 English witness remains secondary.
