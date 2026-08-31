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
- printed title: **சேரன் செங்குட்டுவன்**;
- source-printed dramatic scenes: **4**;
- 2009 published-English witness: **secondary only**.

### First-pass / source rule

The user supplied a Gemini word-to-word first pass covering the Cheran source extent.

For Cheran, follow the permanent source-first old-glyph policy:

- Gemini is a comparison baseline, not the controlling authority;
- the Tamil scan is controlling;
- do not change a plausible first-pass reading merely because a modern spelling, grammar or semantic form seems more familiar;
- if the scan is unambiguous, use the scan-supported form and document the difference;
- do not use the English witness to reconstruct Tamil.

### `காட்சி — 1` — COMPLETE

Source extent: scans **44–45** / printed pp.39–40.

Durable artifacts:

- `works/cheran-senguttuvan/pages/0044.md` — **verified**;
- `works/cheran-senguttuvan/pages/0045.md` — **verified**;
- `works/cheran-senguttuvan/SCENE1_PAGE_VERIFICATION.md` — **2/2 PASS / COMPLETE**;
- `works/cheran-senguttuvan/scenes/01.md` — **assembly-reviewed**;
- `works/cheran-senguttuvan/SCENE1_ASSEMBLY_FIDELITY_REVIEW.md` — **PASS**.

### `காட்சி — 2` — PAGE GATE IN PROGRESS

Source extent: scans **46–49** / printed pp.41–44.

Current durable state:

- `works/cheran-senguttuvan/pages/0046.md` — scan **46** / p.41 — **verified**;
- `works/cheran-senguttuvan/pages/0047.md` — scan **47** / p.42 — **verified**;
- `works/cheran-senguttuvan/pages/0048.md` — scan **48** / p.43 — **verified**;
- `works/cheran-senguttuvan/SCENE2_PAGE_VERIFICATION.md` — **3/4 PASS**;
- scan **49** — not processed;
- Scene-2 assembly — blocked until 4/4 pages are verified.

Scan-48 controls include:

- continuation of the same recitation with no new speaker label or heading;
- source long dashes throughout the narrative sequence;
- source `சாவிலே வீழ்ந்துவிட்டான்—` rather than Gemini `சாவிலே வீழ்ந்து விட்டான் -`;
- source `மண் தானே? இனி இது தூங்காத / கண் தானே?` rather than Gemini `மண்தானோ? இனிஇது தூங்காத / கண்தானோ?`;
- source punctuation `நாட்டுக்கே அன்றி,`;
- enlarged-scan reading `தமிழ்நாட்டுமாதரசு` rather than Gemini `தமிழ்நாட்டுமாதரக`;
- plausible first-pass `சோகத்தாள்` retained under the old-glyph safeguard rather than normalized by grammar or semantics;
- no scene-closing `*` on scan 48.

Current Cheran progress:

- Tamil pages verified: **5/10**;
- Scene-1 assembly/fidelity: **PASS**;
- Scene-2 page gate: **3/4**;
- scenes assembled from verified Tamil: **1/4**.

## Exact next activity

Process **`சேரன் செங்குட்டுவன்` scan 49 / printed p.44 only** as the closing-page verification activity for `காட்சி — 2`.

Requirements:

- fetch live `main` first and read the permanent guide/current handover/work/source state;
- inspect scan 49 directly from the controlling PDF;
- use the user-supplied Gemini first-pass as comparison baseline;
- preserve source wording, punctuation, speaker labels, stage directions, physical line boundaries and final source marks;
- apply the old-glyph safeguard: do not replace a plausible Gemini reading merely from modern spelling/grammar/semantics;
- create `works/cheran-senguttuvan/pages/0049.md` only after direct verification;
- update `SCENE2_PAGE_VERIFICATION.md`, page maps, README/source metadata and handover after verification;
- expected durable page progress after success: **6/10**, Scene-2 gate **4/4 COMPLETE**;
- preserve any scene-closing `*` exactly if present;
- do **not** assemble Scene 2 in the same activity;
- do **not** begin scan 50 in the same activity;
- do **not** use the English witness to fill Tamil gaps.

## Permanent safeguards

- live `main` controls repository state;
- PDF remains external;
- no silent lexical normalization or semantic reconstruction;
- ambiguous old-glyph readings are not overridden by expectation;
- scene assembly occurs only after every source page for that scene is verified;
- English witnesses are secondary only;
- translation must derive from verified Tamil;
- `அந்தணர்` is not automatically “Brahmin” in future translation work.
