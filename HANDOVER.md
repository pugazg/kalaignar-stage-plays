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

Durable files:

- `works/cheran-senguttuvan/pages/0044.md` — **verified**;
- `works/cheran-senguttuvan/pages/0045.md` — **verified**;
- `works/cheran-senguttuvan/SCENE1_PAGE_VERIFICATION.md` — **2/2 PASS / COMPLETE**;
- `works/cheran-senguttuvan/scenes/01.md` — **assembly-reviewed**;
- `works/cheran-senguttuvan/SCENE1_ASSEMBLY_FIDELITY_REVIEW.md` — **PASS**;
- `works/cheran-senguttuvan/indexes/page-map.md` — synchronized.

Scene-1 assembly integrity:

- verified page records used: **2/2**;
- page-record ↔ scene comparison: **PASS**;
- unresolved assembly discrepancies: **0**;
- speaker-label count mismatches: **0**;
- assistant lexical substitutions introduced: **0**;
- English-witness reconstruction: **0**;
- closing `*`: **not present in either source page and not invented**.

The assembled scene retains the work-opening pre-scene voice-over and source heading `காட்சி — 1`. It uses the verified page records as the sole textual authority and joins only legitimate physical print-line boundaries.

Locked upstream source reconciliations include:

- scan 44: `வேந்தர் குலதிலக` → `வேந்தர்குலதிலக`; `கனக விஐயர்` → `கனக விஜயர்`;
- scan 45: stray Gemini `ழ்!` removed because absent from source; `யுல:` → `புல:`; standalone `தமிழன்!` restored inside the following `கன:` speech; `யுல: : கனகர் சொன்னது...` → `விஜ: கனகர் சொன்னது...`.

Current Cheran progress:

- Tamil pages verified: **2/10**;
- scenes assembled from verified Tamil: **1/4**;
- scan 46: **not processed**.

## Exact next activity

Process **`சேரன் செங்குட்டுவன்` scan 46 / printed p.41 only** as the opening-page verification activity for `காட்சி — 2`.

Requirements:

- fetch live `main` first and read the permanent guide/current handover/work/source state;
- inspect scan 46 directly from the controlling PDF;
- use the user-supplied Gemini first-pass segment as comparison baseline if available; in a fresh chat, ask for only the relevant scan-46 / p.41 segment rather than inventing it from memory;
- preserve source wording, punctuation, speaker labels, stage directions, physical line boundaries and source marks;
- create `works/cheran-senguttuvan/pages/0046.md` only after direct verification;
- start/update a dedicated Scene-2 page-verification record and page maps after verification;
- expected durable page progress after success: **3/10**;
- do **not** process scan 47 in the same activity;
- do **not** assemble Scene 2 in the same activity;
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
