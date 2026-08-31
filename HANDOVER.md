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
- `காட்சி—3.`: scans **50–51** / pp.45–46 — page gate **2/2 COMPLETE**, `scenes/03.md` assembled, `SCENE3_ASSEMBLY_FIDELITY_REVIEW.md` **PASS**.

Important locked Scene-3 controls:

- source `காட்சி—3.` and `சேரன் கொலுமண்டபம்`;
- source labels `சேரன்:` and `ஒரு அமைச்சர் :`;
- source `உத்திரனும்—விசித்திரனும்—சித்தரனும்—சிவேதனும்—பைரவனும்!` and `கனகனும்விசயனும்`;
- source short spaced hyphen `வீணன் - கயலைப்`;
- plausible first-pass `காணா` retained under the old-glyph safeguard;
- scan 51 continues the same `சேரன்:` speech with no new label;
- source long dashes, `நதியும், பொழிலும்`, `இல்லை!....இல்லை!..`, `தோழர்களே! ....புறப்படுங்கள்!`, and the centered closing `*` retained in assembly.

Current Cheran progress:

- Tamil pages verified: **8/10**;
- scenes assembled from verified Tamil: **3/4**;
- scans **52–53** / printed pp.47–48: not yet processed.

## Exact next activity

Process **`சேரன் செங்குட்டுவன்` scan 52 / printed p.47 only** as the opening-page verification activity for the final scene.

Requirements:

- fetch live `main` first;
- inspect scan 52 directly from the controlling PDF;
- use the user-supplied Gemini first pass as comparison baseline;
- preserve source wording, punctuation, speaker labels, stage directions, physical line boundaries and source marks;
- apply the old-glyph safeguard and avoid expectation-based lexical correction;
- create `works/cheran-senguttuvan/pages/0052.md` only after direct verification;
- create/update the final-scene page-verification record and work/source progress after verification;
- expected durable page progress after success: **9/10**;
- do **not** process scan 53 in the same activity;
- do **not** assemble the final scene in the same activity;
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
