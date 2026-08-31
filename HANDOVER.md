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

The user supplied a Gemini word-to-word first pass covering the Cheran source extent in the current chat.

For Cheran, follow the permanent source-first old-glyph policy:

- Gemini is a comparison baseline, not the controlling authority;
- the Tamil scan is controlling;
- do not change a plausible first-pass reading merely because a modern spelling, grammar or semantic form seems more familiar;
- if the scan is unambiguous, use the scan-supported form and document the difference;
- do not use the English witness to reconstruct Tamil.

### `காட்சி — 1` page gate — COMPLETE

Durable files:

- `works/cheran-senguttuvan/pages/0044.md` — scan 44 / p.39 — **verified**;
- `works/cheran-senguttuvan/pages/0045.md` — scan 45 / p.40 — **verified**;
- `works/cheran-senguttuvan/SCENE1_PAGE_VERIFICATION.md` — **2/2 PASS / COMPLETE**;
- `works/cheran-senguttuvan/indexes/page-map.md`.

Scan-44 controls include:

- printed title displayed as `சேரன்` / `செங்குட்டுவன்`;
- pre-scene voice-over beginning `நாடகத் துவக்கத்திற்கு முன்பு குரல்:`;
- source heading `காட்சி — 1`;
- unambiguous first-pass/source differences including `வேந்தர் குலதிலக` → `வேந்தர்குலதிலக` and `கனக விஐயர்` → `கனக விஜயர்`.

Scan-45 controls include:

- no printed stray `ழ்!` after `செந்தமிழ்!`;
- `யுல:` before the poem is source `புல:`;
- Gemini's standalone `தமிழன்!` belongs inside the following `கன:` speech after `...போராடினான்`;
- `யுல: : கனகர் சொன்னது...` is source `விஜ: கனகர் சொன்னது...`;
- source long-dash forms and physical print-line boundaries are retained;
- scan 45 closes Scene 1 structurally but carries **no printed closing `*`**.

Current Cheran progress:

- Tamil pages verified: **2/10**;
- Scene-1 page gate: **2/2 COMPLETE**;
- scenes assembled from verified Tamil: **0/4**;
- scan 46: **not processed**.

## Exact next activity

Assemble **`சேரன் செங்குட்டுவன்` `காட்சி — 1` only** from verified page records `works/cheran-senguttuvan/pages/0044.md` and `0045.md`.

Requirements:

- fetch live `main` first and read the permanent guide/current handover/Scene-1 page records and page-gate record;
- treat verified page records as the **sole textual authority** for assembly;
- mechanically join only legitimate physical print-line and page-boundary breaks;
- preserve the work-opening pre-scene voice-over, source heading, wording, punctuation and speaker-label variants;
- do **not** invent a closing `*` because neither verified Scene-1 page contains one;
- create the Scene-1 assembled file following existing repository naming/format conventions;
- run a page-record ↔ scene fidelity audit and require PASS;
- update work/source/readme/page-map/handover state after fidelity PASS;
- do **not** process scan 46 in the same activity;
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
