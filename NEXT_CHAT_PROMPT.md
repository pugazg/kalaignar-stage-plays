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
7. `works/cheran-senguttuvan/SCENE2_PAGE_VERIFICATION.md`
8. `works/cheran-senguttuvan/pages/0046.md`
9. `works/cheran-senguttuvan/pages/0047.md`
10. `works/cheran-senguttuvan/pages/0048.md`
11. `sources/naanmani-malai-tamil/README.md`
12. `sources/naanmani-malai-tamil/indexes/page-map.md`

Then re-fetch live `main` immediately before the first write.

## Completed durable state

- `பரதாயணம்` — Tamil archive/assembly PASS; independent English translation PASS.
- `அனார்கலி` — Tamil page/assembly fidelity PASS.
- `சாக்ரடீஸ்` — **17/17 pages verified; 5/5 scenes assembled; all fidelity gates PASS**.
- `சேரன் செங்குட்டுவன்` `காட்சி — 1` — **2/2 pages verified; assembly/fidelity PASS**.

## Active work — `சேரன் செங்குட்டுவன்`

Controlling extent:

- scans **44–53**;
- printed pp. **39–48**;
- source-printed dramatic scenes: **4**.

Current durable progress:

- Tamil pages verified: **5/10**;
- scenes assembled: **1/4**;
- `காட்சி — 2` source extent: scans **46–49** / pp.41–44;
- scan **46 / p.41** — **verified**;
- scan **47 / p.42** — **verified**;
- scan **48 / p.43** — **verified**;
- Scene-2 page gate: **3/4**;
- scan **49** — not processed.

Scene-2 durable files:

- `works/cheran-senguttuvan/pages/0046.md`;
- `works/cheran-senguttuvan/pages/0047.md`;
- `works/cheran-senguttuvan/pages/0048.md`;
- `works/cheran-senguttuvan/SCENE2_PAGE_VERIFICATION.md`.

## First-pass / source rule

The user supplied a Gemini word-to-word first pass covering the Cheran source extent.

- Gemini is a comparison baseline only;
- the Tamil scan is controlling;
- do not replace a plausible old-glyph reading because familiar spelling, grammar or semantics suggest another word;
- change the first pass only when scan evidence is unambiguous, and document the difference;
- the 2009 English witness is secondary and must not reconstruct Tamil.

Scan 48 recorded source-proven reconciliation including:

- hyphen-style separators → source long dashes;
- `சாவிலே வீழ்ந்து விட்டான் -` → source `சாவிலே வீழ்ந்துவிட்டான்—`;
- `மண்தானோ? இனிஇது தூங்காத` → source `மண் தானே? இனி இது தூங்காத`;
- `கண்தானோ?` → source `கண் தானே?`;
- `நாட்டுக்கே அன்றி.` → source `நாட்டுக்கே அன்றி,`;
- `தமிழ்நாட்டுமாதரக` → enlarged-scan `தமிழ்நாட்டுமாதரசு`.

The plausible first-pass `சோகத்தாள்` was retained under the old-glyph safeguard rather than normalized by expectation.

## Exact next activity

Process **`சேரன் செங்குட்டுவன்` scan 49 / printed p.44 only** as the closing-page verification activity for Scene 2.

Requirements:

- inspect scan 49 directly from the controlling PDF;
- use the user-supplied Gemini first-pass as comparison baseline;
- preserve source wording, punctuation, speaker labels, stage directions, physical line boundaries and final source marks;
- apply the old-glyph safeguard and avoid expectation-based lexical correction;
- create `works/cheran-senguttuvan/pages/0049.md` only after direct verification;
- update `SCENE2_PAGE_VERIFICATION.md`, work/source progress, page maps, README files and handover after verification;
- expected durable total after success: **6/10 pages verified**, Scene-2 gate **4/4 COMPLETE**;
- preserve any scene-closing `*` exactly if present;
- do **not** assemble Scene 2 in the same activity;
- do **not** process scan 50 in the same activity;
- do **not** use the English witness to reconstruct Tamil.

When I say **“Proceed with next activity”**, execute this exact activity directly without asking me to choose a routine next step.
