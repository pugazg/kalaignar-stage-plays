# Next Chat Prompt — Continue `சேரன் செங்குட்டுவன்` in Kalaignar Stage Plays

Continue the Kalaignar Stage Plays archival project directly in:

`https://github.com/pugazg/kalaignar-stage-plays`

Branch: `main`.

Use the GitHub connector and work directly on `main`.

Controlling source PDF: `TVA_BOK_0065576_நான்மணி_மாலை.pdf`.

## Live-state rule

Fetch live GitHub `main` first and treat it as authoritative. Preserve any newer durable state. Do not reopen completed `சாக்ரடீஸ்` or Cheran Scenes 1–3 unless explicitly requested.

## Mandatory startup reading

Before any write, read completely:

1. `STAGE_PLAY_PROCESSING_GUIDE.md`
2. `HANDOVER.md`
3. `NEXT_CHAT_PROMPT.md`
4. `works/cheran-senguttuvan/README.md`
5. `works/cheran-senguttuvan/metadata/source.md`
6. `works/cheran-senguttuvan/indexes/page-map.md`
7. `works/cheran-senguttuvan/SCENE3_ASSEMBLY_FIDELITY_REVIEW.md`
8. `works/cheran-senguttuvan/scenes/03.md`
9. `sources/naanmani-malai-tamil/README.md`
10. `sources/naanmani-malai-tamil/indexes/page-map.md`

Then re-fetch live `main` immediately before the first write.

## Completed durable state

- `பரதாயணம்` — Tamil archive/assembly PASS; independent English translation PASS.
- `அனார்கலி` — Tamil page/assembly fidelity PASS.
- `சாக்ரடீஸ்` — **17/17 pages verified; 5/5 scenes assembled; all fidelity gates PASS**.
- `சேரன் செங்குட்டுவன்` `காட்சி — 1` — **page gate + assembly/fidelity PASS**.
- `சேரன் செங்குட்டுவன்` `காட்சி — 2` — **page gate + assembly/fidelity PASS**.
- `சேரன் செங்குட்டுவன்` `காட்சி—3.` — **2/2 page gate + assembly/fidelity PASS**.

## Active work — `சேரன் செங்குட்டுவன்`

Controlling extent: scans **44–53** / printed pp. **39–48**; four source-printed scenes.

Current durable progress:

- Tamil pages verified: **8/10**;
- scenes assembled: **3/4**;
- scans **44–51 / pp.39–46** complete through Scene 3;
- scan **52 / p.47** — not processed;
- final scene spans scans **52–53** / pp.47–48.

## First-pass / source rule

The user supplied a Gemini word-to-word first pass covering the Cheran source extent. Gemini is a comparison baseline only; the Tamil scan is controlling. Do not replace plausible old-glyph readings by expectation. Change first-pass wording only when scan evidence is unambiguous and document it. The 2009 English witness is secondary and must not reconstruct Tamil.

## Exact next activity

Process **`சேரன் செங்குட்டுவன்` scan 52 / printed p.47 only** as the opening-page verification activity for the final scene.

Requirements:

- inspect scan 52 directly from the controlling PDF;
- use the user-supplied Gemini first-pass as comparison baseline;
- preserve source wording, punctuation, speaker labels, stage directions, physical line boundaries and source marks;
- apply the old-glyph safeguard and avoid expectation-based lexical correction;
- create `works/cheran-senguttuvan/pages/0052.md` only after direct verification;
- create/update the final-scene page-verification record, work/source progress, page maps, README files and handover after verification;
- expected durable total after success: **9/10 pages verified**;
- do **not** process scan 53 in the same activity;
- do **not** assemble the final scene in the same activity;
- do **not** use the English witness to reconstruct Tamil.

When I say **“Proceed with next activity”**, execute this exact activity directly without asking me to choose a routine next step.
