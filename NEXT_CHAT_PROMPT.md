# Next Chat Prompt — Continue `சேரன் செங்குட்டுவன்` in Kalaignar Stage Plays

Continue the Kalaignar Stage Plays archival project directly in:

`https://github.com/pugazg/kalaignar-stage-plays`

Branch: `main`.

Use the GitHub connector and work directly on `main`.

Controlling source PDF: `TVA_BOK_0065576_நான்மணி_மாலை.pdf`.

## Live-state rule

Fetch live GitHub `main` first and treat it as authoritative. Preserve any newer durable state. Do not reopen completed `சாக்ரடீஸ்` or completed Cheran Scene 1 work unless explicitly requested.

## Mandatory startup reading

Before any write, read completely:

1. `STAGE_PLAY_PROCESSING_GUIDE.md`
2. `HANDOVER.md`
3. `NEXT_CHAT_PROMPT.md`
4. `works/cheran-senguttuvan/README.md`
5. `works/cheran-senguttuvan/metadata/source.md`
6. `works/cheran-senguttuvan/indexes/page-map.md`
7. `works/cheran-senguttuvan/SCENE1_PAGE_VERIFICATION.md`
8. `works/cheran-senguttuvan/SCENE1_ASSEMBLY_FIDELITY_REVIEW.md`
9. `works/cheran-senguttuvan/scenes/01.md`
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

- scans **44–45 / pp.39–40** — verified;
- `காட்சி — 1` page gate: **2/2 COMPLETE**;
- `காட்சி — 1` assembly/fidelity: **PASS**;
- Tamil pages verified: **2/10**;
- scenes assembled: **1/4**;
- scan 46: **not processed**.

Scene-1 durable artifacts:

- `works/cheran-senguttuvan/pages/0044.md`;
- `works/cheran-senguttuvan/pages/0045.md`;
- `works/cheran-senguttuvan/SCENE1_PAGE_VERIFICATION.md`;
- `works/cheran-senguttuvan/scenes/01.md`;
- `works/cheran-senguttuvan/SCENE1_ASSEMBLY_FIDELITY_REVIEW.md` — **PASS**.

The completed assembly uses verified page records only, retains the pre-scene voice-over and `காட்சி — 1` heading, introduces no assistant lexical substitutions and does not invent a closing `*`.

## First-pass / source rule

The user supplied a Gemini word-to-word first pass covering the Cheran source extent.

- Gemini is a comparison baseline only;
- the Tamil scan is controlling;
- do not replace a plausible old-glyph reading because familiar spelling, grammar or semantics suggest another word;
- change the first pass only when scan evidence is unambiguous, and document the difference;
- the 2009 English witness is secondary and must not reconstruct Tamil.

## Exact next activity

Process **`சேரன் செங்குட்டுவன்` scan 46 / printed p.41 only** as the opening-page verification activity for `காட்சி — 2`.

Requirements:

- inspect scan 46 directly from the controlling PDF;
- use the user-supplied Gemini first-pass segment as comparison baseline if available; if this is a fresh chat and the first-pass text is unavailable, ask the user to paste only the scan-46 / p.41 segment rather than inventing it;
- preserve source wording, punctuation, speaker labels, stage directions, physical line boundaries and source marks;
- create `works/cheran-senguttuvan/pages/0046.md` only after direct verification;
- create/update the Scene-2 page-verification record and work/source progress after verification;
- expected durable total after success: **3/10 pages verified**;
- do **not** process scan 47 in the same activity;
- do **not** assemble Scene 2 in the same activity;
- do **not** use the English witness to reconstruct Tamil.

When I say **“Proceed with next activity”**, execute this exact activity directly without asking me to choose a routine next step.
