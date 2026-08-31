# கலைஞரின் நான்மணி மாலை — controlling Tamil source

Source: `TVA_BOK_0065576_நான்மணி_மாலை.pdf` — **54 scans** — SHA-256 `18d2b1405544b03507e9f92067d287cb28f5a92eaf02bed7054e6e78e5e38c89`.

## Current work state

- `பரதாயணம்`: Tamil archival/assembly PASS; independent English translation PASS.
- `அனார்கலி`: Tamil archival/assembly PASS.
- `சாக்ரடீஸ்`: scans **27–43 = 17/17 pages verified COMPLETE**; all five scenes assembled with page-record fidelity **PASS**.
- `சேரன் செங்குட்டுவன்`: scans **44–45 / pp.39–40 verified**; Tamil page progress **2/10**; `காட்சி — 1` page gate **2/2 COMPLETE**; scenes assembled **0/4**.

For active `சேரன் செங்குட்டுவன்`, the user-supplied Gemini first pass is a comparison baseline. The Tamil scan remains controlling under `STAGE_PLAY_PROCESSING_GUIDE.md`; ambiguous old-glyph readings are not normalized by expectation, while unambiguous scan evidence controls canonical wording, spacing, punctuation and labels. The 2009 English witness remains secondary only.

Scan 45 closes the verified Scene-1 page gate. Source-proven first-pass reconciliation there includes removal of the stray Gemini `ழ்!`, correction of `யுல:` to source `புல:`, restoration of `தமிழன்!` inside the following `கன:` speech, and correction of `யுல: : கனகர் சொன்னது...` to source `விஜ: கனகர் சொன்னது...`.

Next source-sequential activity: assemble **`சேரன் செங்குட்டுவன்` `காட்சி — 1` only** from verified scans 44–45 page records and run its fidelity audit. Do not process scan 46 in the same activity.
