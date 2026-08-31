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
- `சேரன் செங்குட்டுவன்` Scenes 1–3: page gates + assembly/fidelity **PASS**.

## Active work — சேரன் செங்குட்டுவன்

Controlling Tamil extent: scans **44–53** / printed pp. **39–48**; four source-printed dramatic scenes. The 2009 published-English witness is secondary only.

### First-pass / source rule

The user supplied a Gemini word-to-word first pass covering the Cheran source extent. Gemini is a comparison baseline, not the controlling authority. Do not replace plausible old-glyph readings by familiar spelling, grammar or semantic expectation. Use unambiguous scan evidence when it differs and document the difference. Do not use the English witness to reconstruct Tamil.

### Completed scenes

- `காட்சி — 1`: scans **44–45** / pp.39–40 — page gate + assembly/fidelity **PASS**.
- `காட்சி — 2`: scans **46–49** / pp.41–44 — page gate + assembly/fidelity **PASS**.
- `காட்சி—3.`: scans **50–51** / pp.45–46 — page gate + assembly/fidelity **PASS**.

### `காட்சி—4.` — PAGE GATE COMPLETE

Source extent: scans **52–53** / printed pp.47–48.

Current durable state:

- `works/cheran-senguttuvan/pages/0052.md` — scan **52** / p.47 — **verified**;
- `works/cheran-senguttuvan/pages/0053.md` — scan **53** / p.48 — **verified**;
- `works/cheran-senguttuvan/SCENE4_PAGE_VERIFICATION.md` — **2/2 PASS / COMPLETE**;
- final-scene assembly — **not yet performed**.

Important final-scene controls:

- scan 52: source heading `காட்சி—4.`, setting `குயிலாலுவம்`, source-order opening direction `...கனக—விஜயருக்கும் நடை / பெற்ற போரில்...`, exact source label/punctuation variants, source long dashes and `ராம ராவணப் போர்?....`;
- scan 53: source labels include `சேர்:`, unusual second-turn `சேர்!`, and `வில்:`;
- scan 53 source `புறப்படுவோம்—வில்லவா.`, `கனக—விஜயா`, `சொல்—இப்போது`;
- scan 53 centered final source mark is **`- * -`**, not a bare `*`.

Current Cheran progress:

- Tamil pages verified: **10/10 COMPLETE**;
- scenes assembled from verified Tamil: **3/4**;
- final-scene page gate: **2/2 COMPLETE**.

## Exact next activity

Assemble **`சேரன் செங்குட்டுவன்` `காட்சி—4.` only** from verified page records `works/cheran-senguttuvan/pages/0052.md` and `0053.md`.

Requirements:

- fetch live `main` first;
- use the two verified page records as the sole textual authority;
- mechanically join only legitimate physical print-line/page-boundary breaks;
- preserve all verified wording, punctuation and source speaker-label forms, including `சேர்!`;
- preserve the scan-53 centered final mark `- * -` exactly;
- create the Scene-4 assembled file using repository naming conventions;
- run a page-record ↔ scene fidelity audit and require PASS;
- update durable completion state only after fidelity PASS;
- do **not** process scan 54 / the back cover in the same activity;
- do **not** begin another work in the same activity;
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
