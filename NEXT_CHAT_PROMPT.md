# Next Chat Prompt — Continue `சேரன் செங்குட்டுவன்` in Kalaignar Stage Plays

Continue the Kalaignar Stage Plays archival project directly in:

`https://github.com/pugazg/kalaignar-stage-plays`

Branch: `main`.

Use the GitHub connector and work directly on `main`.

Controlling source PDF: `TVA_BOK_0065576_நான்மணி_மாலை.pdf`.

## Live-state rule

Fetch live GitHub `main` first and treat it as authoritative. Preserve any newer durable state. Do not reopen completed `சாக்ரடீஸ்` work.

## Mandatory startup reading

Before any write, read completely:

1. `STAGE_PLAY_PROCESSING_GUIDE.md`
2. `HANDOVER.md`
3. `NEXT_CHAT_PROMPT.md`
4. `works/cheran-senguttuvan/README.md`
5. `works/cheran-senguttuvan/metadata/source.md`
6. `works/cheran-senguttuvan/indexes/page-map.md`
7. `works/cheran-senguttuvan/SCENE1_PAGE_VERIFICATION.md`
8. `works/cheran-senguttuvan/pages/0044.md`
9. `works/cheran-senguttuvan/pages/0045.md`
10. `sources/naanmani-malai-tamil/README.md`
11. `sources/naanmani-malai-tamil/indexes/page-map.md`

Then re-fetch live `main` immediately before the first write.

## Completed durable state

- `பரதாயணம்` — Tamil archive/assembly PASS; independent English translation PASS.
- `அனார்கலி` — Tamil page/assembly fidelity PASS.
- `சாக்ரடீஸ்` — **17/17 pages verified; 5/5 scenes assembled; all fidelity gates PASS**.

## Active work — `சேரன் செங்குட்டுவன்`

Controlling extent:

- scans **44–53**;
- printed pp. **39–48**;
- source-printed dramatic scenes: **4**.

Current durable progress:

- scan **44 / p.39** — verified work opening + `காட்சி — 1` opening;
- scan **45 / p.40** — verified Scene-1 continuation/closing;
- Tamil pages verified: **2/10**;
- Scene-1 page gate: **2/2 COMPLETE**;
- scenes assembled: **0/4**.

Scene-1 durable files:

- `works/cheran-senguttuvan/pages/0044.md`;
- `works/cheran-senguttuvan/pages/0045.md`;
- `works/cheran-senguttuvan/SCENE1_PAGE_VERIFICATION.md` — **2/2 PASS / COMPLETE**;
- `works/cheran-senguttuvan/indexes/page-map.md`.

## First-pass / source rule

The user supplied a Gemini word-to-word first pass covering the Cheran source extent.

- Gemini is a comparison baseline only;
- the Tamil scan is controlling;
- do not replace a plausible old-glyph reading because familiar spelling, grammar or semantics suggest another word;
- change the first pass only when scan evidence is unambiguous, and document the difference;
- the 2009 English witness is secondary and must not reconstruct Tamil.

Scan 45 recorded source-proven reconciliation including removal of the stray Gemini `ழ்!`, `யுல:` → `புல:`, restoration of `தமிழன்!` inside the following `கன:` speech, and `யுல: : கனகர் சொன்னது...` → `விஜ: கனகர் சொன்னது...`.

## Exact next activity

Assemble **`சேரன் செங்குட்டுவன்` `காட்சி — 1` only** from verified page records `works/cheran-senguttuvan/pages/0044.md` and `0045.md`.

Requirements:

- treat the verified page records as the sole textual authority;
- mechanically join only legitimate physical print-line/page-boundary breaks;
- preserve the pre-scene voice-over, source scene heading, wording, punctuation and speaker-label variants;
- neither verified page contains a closing `*`, so do not invent one;
- follow existing scene-file naming/format convention;
- run the page-record ↔ scene fidelity audit and require PASS;
- update work/source/readme/page-map/handover state only after fidelity PASS;
- do **not** process scan 46 in the same activity;
- do **not** use the English witness to reconstruct Tamil.

When I say **“Proceed with next activity”**, execute this exact activity directly without asking me to choose a routine next step.
