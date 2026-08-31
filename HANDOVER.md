# Kalaignar Stage Plays — Handover

Repository: `pugazg/kalaignar-stage-plays`, branch `main`.

## Startup rule

Always fetch live `main` first and treat it as authoritative. Preserve newer durable state and never reopen completed work unless the user explicitly requests it.

Permanent workflow: `STAGE_PLAY_PROCESSING_GUIDE.md`.

Controlling composite source: `TVA_BOK_0065576_நான்மணி_மாலை.pdf` — **54 scans** — SHA-256 `18d2b1405544b03507e9f92067d287cb28f5a92eaf02bed7054e6e78e5e38c89`.

## Locked completed work

- `பரதாயணம்`: Tamil archive/assembly PASS; independent English translation PASS.
- `அனார்கலி`: Tamil page/assembly fidelity PASS.
- `சாக்ரடீஸ்`: **17/17 pages verified; 5/5 scenes assembled; all fidelity gates PASS**.
- Silappathikaram completed state remains locked and unchanged.

## Active work — சேரன் செங்குட்டுவன்

Controlling Tamil extent: scans **44–53** / printed pp. **39–48**; four source-printed dramatic scenes. The 2009 published-English witness is secondary only.

### First-pass / source rule

The user supplied a Gemini word-to-word first pass covering the Cheran source extent. Gemini is a comparison baseline, not the controlling authority. Do not replace plausible old-glyph readings by familiar spelling, grammar or semantic expectation. Use unambiguous scan evidence when it differs and document the difference. Do not use the English witness to reconstruct Tamil.

### Completed scenes

- `காட்சி — 1`: scans **44–45** / pp.39–40 — page gate + assembly/fidelity **PASS**.
- `காட்சி — 2`: scans **46–49** / pp.41–44 — page gate + assembly/fidelity **PASS**.

### `காட்சி—3.` — PAGE GATE COMPLETE

Source extent: scans **50–51** / printed pp.45–46.

Durable state:

- `works/cheran-senguttuvan/pages/0050.md` — scan 50 / p.45 — **verified**;
- `works/cheran-senguttuvan/pages/0051.md` — scan 51 / p.46 — **verified**;
- `works/cheran-senguttuvan/SCENE3_PAGE_VERIFICATION.md` — **2/2 PASS / COMPLETE**;
- Scene-3 assembly — **not yet performed**.

Important controls:

- scan 50: source `காட்சி—3.`, `சேரன் கொலுமண்டபம்`, `உத்திரனும்—விசித்திரனும்—சித்தரனும்—சிவேதனும்—பைரவனும்!`, `கனகனும்விசயனும்`, source punctuation/labels, short spaced hyphen `வீணன் - கயலைப்`, and plausible first-pass `காணா` retained;
- scan 51 continues the same `சேரன்:` speech without a new label;
- scan 51 preserves source long dashes, `நதியும், பொழிலும்`, `இல்லை!....இல்லை!..`, `தோழர்களே! ....புறப்படுங்கள்!`, and the centered closing `*`.

Current Cheran progress:

- Tamil pages verified: **8/10**;
- scenes assembled from verified Tamil: **2/4**;
- Scene-3 page gate: **2/2 COMPLETE**;
- scans 52–53: not processed.

## Exact next activity

Assemble **`சேரன் செங்குட்டுவன்` `காட்சி—3.` only** from verified page records `works/cheran-senguttuvan/pages/0050.md` and `0051.md`.

Requirements:

- fetch live `main` first;
- use the two verified page records as the sole textual authority;
- mechanically join only legitimate physical print-line/page-boundary breaks;
- preserve verified wording, punctuation, speaker-label forms and the scan-51 closing `*`;
- create the Scene-3 assembled file using repository naming conventions;
- run a page-record ↔ scene fidelity audit and require PASS;
- update durable status only after fidelity PASS;
- do **not** process scan 52 / begin the final scene in the same activity;
- do **not** use the English witness to reconstruct Tamil.

## Permanent safeguards

- live `main` controls repository state;
- PDF remains external;
- no silent lexical normalization or semantic reconstruction;
- ambiguous old-glyph readings are not overridden by expectation;
- scene assembly occurs only after every source page for that scene is verified;
- English witnesses are secondary only;
- translation must derive from verified Tamil;
- `அந்தணர்` is not automatically “Brahmin” in future translation work.
