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

### `காட்சி—3.` — PAGE GATE IN PROGRESS

Source extent: scans **50–51** / printed pp.45–46.

Current durable state:

- `works/cheran-senguttuvan/pages/0050.md` — scan **50** / p.45 — **verified**;
- `works/cheran-senguttuvan/SCENE3_PAGE_VERIFICATION.md` — **1/2 PASS**;
- scan **51** — not processed;
- Scene-3 assembly — blocked until 2/2 pages verified.

Important scan-50 controls:

- source heading `காட்சி—3.`;
- setting `சேரன் கொலுமண்டபம்`;
- source speaker labels `சேரன்:` and `ஒரு அமைச்சர் :`;
- source `உத்திரனும்—விசித்திரனும்—சித்தரனும்—சிவேதனும்—பைரவனும்!` rather than Gemini's `...னாம்` sequence;
- source `கனகனும்விசயனும்` rather than Gemini `கனகனாம் விசயனாம்`;
- source punctuation `வள்ளுவனே!`, `முல்லைக் கொல்லையே!`, and joined `நெடுஞ்செழியனே!`;
- source short spaced hyphen retained in `வீணன் - கயலைப்`;
- plausible first-pass `காணா` retained under the old-glyph safeguard;
- scan 50 contains no closing `*`.

Current Cheran progress:

- Tamil pages verified: **7/10**;
- scenes assembled from verified Tamil: **2/4**;
- Scene-3 page gate: **1/2**.

## Exact next activity

Process **`சேரன் செங்குட்டுவன்` scan 51 / printed p.46 only** as the closing-page verification activity for `காட்சி—3.`.

Requirements:

- fetch live `main` first;
- inspect scan 51 directly from the controlling PDF;
- use the user-supplied Gemini first pass as comparison baseline;
- preserve source wording, punctuation, speaker labels, physical line boundaries and final source marks;
- apply the old-glyph safeguard and avoid expectation-based lexical correction;
- create `works/cheran-senguttuvan/pages/0051.md` only after direct verification;
- update `SCENE3_PAGE_VERIFICATION.md`, work/source progress, page maps, README files and handover after verification;
- expected durable page progress after success: **8/10**, Scene-3 gate **2/2 COMPLETE**;
- preserve the scene-closing `*` exactly if confirmed on scan 51;
- do **not** assemble Scene 3 in the same activity;
- do **not** process scan 52 in the same activity;
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
