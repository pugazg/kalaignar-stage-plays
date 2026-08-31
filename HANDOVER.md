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

### `காட்சி — 1` — COMPLETE

Scans **44–45** / printed pp.39–40: **2/2 verified**, `scenes/01.md` assembled, fidelity **PASS**.

### `காட்சி — 2` — COMPLETE

Source extent: scans **46–49** / printed pp.41–44.

Durable artifacts:

- `works/cheran-senguttuvan/pages/0046.md`–`0049.md` — **4/4 verified**;
- `works/cheran-senguttuvan/SCENE2_PAGE_VERIFICATION.md` — **PASS / COMPLETE**;
- `works/cheran-senguttuvan/scenes/02.md` — **assembly-reviewed / PASS**;
- `works/cheran-senguttuvan/SCENE2_ASSEMBLY_FIDELITY_REVIEW.md` — **PASS**.

The Scene-2 assembly uses the verified page records as sole textual authority. It preserves the locked source reconciliations, speaker-label variants, punctuation and stage directions; only legitimate physical print-line/page-boundary joins are made. None of scans 46–49 contains a closing `*`, so none is invented.

Current Cheran progress:

- Tamil pages verified: **6/10**;
- Scene-1 assembly/fidelity: **PASS**;
- Scene-2 assembly/fidelity: **PASS**;
- scenes assembled from verified Tamil: **2/4**;
- scans **50–53**: not processed.

## Exact next activity

Process **`சேரன் செங்குட்டுவன்` scan 50 / printed p.45 only** as the opening-page verification activity for `காட்சி—3.`.

Requirements:

- fetch live `main` first;
- inspect scan 50 directly from the controlling PDF;
- use the user-supplied Gemini first pass as comparison baseline;
- preserve source wording, punctuation, speaker labels, stage directions, physical line boundaries and source marks;
- apply the old-glyph safeguard and avoid expectation-based lexical correction;
- create `works/cheran-senguttuvan/pages/0050.md` only after direct verification;
- create/update the Scene-3 page-verification record and work/source progress after verification;
- expected durable page progress after success: **7/10**;
- do **not** process scan 51 in the same activity;
- do **not** assemble Scene 3 in the same activity;
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
