# கலைஞரின் நான்மணி மாலை — controlling Tamil source

Source: `TVA_BOK_0065576_நான்மணி_மாலை.pdf` — **54 scans** — SHA-256 `18d2b1405544b03507e9f92067d287cb28f5a92eaf02bed7054e6e78e5e38c89`.

## Current work state

- `பரதாயணம்`: Tamil archival/assembly PASS; independent English translation PASS.
- `அனார்கலி`: Tamil archival/assembly PASS.
- `சாக்ரடீஸ்`: scans **27–43 = 17/17 pages verified COMPLETE**; all five scenes assembled with page-record fidelity **PASS**.
- `சேரன் செங்குட்டுவன்`: scans **44–49 / pp.39–44 verified**; Tamil page progress **6/10**; `காட்சி — 1` assembly/fidelity **PASS**; `காட்சி — 2` page gate **4/4 COMPLETE**; scenes assembled **1/4**.

For active `சேரன் செங்குட்டுவன்`, the user-supplied Gemini first pass is a comparison baseline. The Tamil scan remains controlling under `STAGE_PLAY_PROCESSING_GUIDE.md`; ambiguous old-glyph readings are not normalized by expectation, while unambiguous scan evidence controls canonical wording, spacing, punctuation, labels and source order. The 2009 English witness remains secondary only.

Current Scene-2 artifacts:

- `../../works/cheran-senguttuvan/pages/0046.md`–`0049.md` — **4/4 verified**;
- `../../works/cheran-senguttuvan/SCENE2_PAGE_VERIFICATION.md` — **PASS / COMPLETE**.

Scan 49 adds source-proven `பூண்டார்!` omitted by Gemini and retains source `வெள்ளிமாடத்திற்கு`, `வந்திருக்கிறேனே`, and `காலத்திலே`. None of the four Scene-2 pages carries a closing `*`.

Next source-sequential activity: assemble **`சேரன் செங்குட்டுவன்` `காட்சி — 2` only** from verified page records 0046–0049 and run the page-record fidelity audit. Do not process scan 50 in that activity.
