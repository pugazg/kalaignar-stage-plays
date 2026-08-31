# Kalaignar Stage Plays — Handover

Repository: `pugazg/kalaignar-stage-plays`, branch `main`.

## Startup rule

Always fetch live `main` first and treat it as authoritative. Preserve newer durable state and never reopen completed work unless the user explicitly requests it.

Permanent workflow: `STAGE_PLAY_PROCESSING_GUIDE.md`.

Controlling composite source: `TVA_BOK_0065576_நான்மணி_மாலை.pdf` — **54 scans** — SHA-256 `18d2b1405544b03507e9f92067d287cb28f5a92eaf02bed7054e6e78e5e38c89`.

## Locked completed work

- `பரதாயணம்`: Tamil archive/assembly PASS; independent English translation PASS.
- `அனார்கலி`: Tamil page/assembly fidelity PASS.
- `சாக்ரடீஸ்`: **17/17 pages verified; 15/15 dramatic-body pages verified; 5/5 scenes assembled; all scene fidelity gates PASS**.
- Silappathikaram completed state remains locked and unchanged.

## Active work — சேரன் செங்குட்டுவன்

Controlling Tamil extent:

- scans **44–53**;
- printed pp. **39–48**;
- source-printed dramatic scenes: **4**;
- 2009 published-English witness: **secondary only**.

### First-pass / source rule

The user supplied a Gemini word-to-word first pass covering the Cheran source extent.

- Gemini is a comparison baseline, not the controlling authority;
- the Tamil scan is controlling;
- do not change a plausible first-pass reading merely because modern spelling, grammar or semantics suggest another form;
- use unambiguous scan evidence when it differs and document the difference;
- do not use the English witness to reconstruct Tamil.

### `காட்சி — 1` — COMPLETE

Scans **44–45** / printed pp.39–40: **2/2 verified**, `scenes/01.md` assembled, fidelity **PASS**.

### `காட்சி — 2` — PAGE GATE COMPLETE

Source extent: scans **46–49** / printed pp.41–44.

Durable state:

- `works/cheran-senguttuvan/pages/0046.md` — verified;
- `works/cheran-senguttuvan/pages/0047.md` — verified;
- `works/cheran-senguttuvan/pages/0048.md` — verified;
- `works/cheran-senguttuvan/pages/0049.md` — verified;
- `works/cheran-senguttuvan/SCENE2_PAGE_VERIFICATION.md` — **4/4 PASS / COMPLETE**;
- Scene-2 assembly — **not yet performed**.

Important locked Scene-2 controls:

- scan 46: `ஓர் களத்தில்,` is after `அந்நாளில்`; plausible old-glyph `தன் மகனை / யும்` retained;
- scan 47: source `“நடந்திடுக கண்ணே” என்றாள்!`, long dashes, `வாழ்த்துகள் வழங்கினர்!`;
- scan 48: source `மண் தானே?`, `கண் தானே?`, `தமிழ்நாட்டுமாதரசு`; plausible `சோகத்தாள்` retained;
- scan 49: source long dashes; a separate printed `பூண்டார்!` absent from Gemini is restored; source `வெள்ளிமாடத்திற்கு`, `வந்திருக்கிறேனே`, and `காலத்திலே` retained;
- **none of scans 46–49 contains a scene-closing `*`**.

Current Cheran progress:

- Tamil pages verified: **6/10**;
- Scene-1 assembly/fidelity: **PASS**;
- Scene-2 page gate: **4/4 COMPLETE**;
- scenes assembled from verified Tamil: **1/4**;
- scan 50: **not processed**.

## Exact next activity

Assemble **`சேரன் செங்குட்டுவன்` `காட்சி — 2` only** from verified page records `works/cheran-senguttuvan/pages/0046.md`–`0049.md`.

Requirements:

- fetch live `main` first;
- treat the four verified page records as the sole textual authority for assembly;
- mechanically join only legitimate physical print-line/page-boundary breaks;
- preserve wording, punctuation, speaker-label variants, stage directions and verified source reconciliations;
- do not invent a closing `*` because none exists on scans 46–49;
- create the Scene-2 assembled file using repository naming conventions;
- run a page-record ↔ scene fidelity audit and require PASS;
- update work/source/readme/page-map/handover state only after fidelity PASS;
- do **not** process scan 50 / begin `காட்சி—3.` in the same activity;
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
