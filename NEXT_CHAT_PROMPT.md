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
9. `works/cheran-senguttuvan/SCENE1_ASSEMBLY_FIDELITY_REVIEW.md`
10. `sources/naanmani-malai-tamil/README.md`
11. `sources/naanmani-malai-tamil/indexes/page-map.md`

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

- Tamil pages verified: **3/10**;
- scenes assembled: **1/4**;
- `காட்சி — 2` source extent: scans **46–49** / pp.41–44;
- scan **46 / p.41** — **verified**;
- Scene-2 page gate: **1/4**;
- scans **47–49** — not processed.

Scene-2 durable files:

- `works/cheran-senguttuvan/pages/0046.md`;
- `works/cheran-senguttuvan/SCENE2_PAGE_VERIFICATION.md`.

## First-pass / source rule

The user supplied a Gemini word-to-word first pass covering the Cheran source extent.

- Gemini is a comparison baseline only;
- the Tamil scan is controlling;
- do not replace a plausible old-glyph reading because familiar spelling, grammar or semantics suggest another word;
- change the first pass only when scan evidence is unambiguous, and document the difference;
- the 2009 English witness is secondary and must not reconstruct Tamil.

Scan 46 recorded source-proven reconciliation including:

- `காட்சி - 2` → source `காட்சி — 2`;
- `சொல்லட்டுமா !` → source `சொல்லட்டுமா!`;
- source punctuation grouping `புறநானூற்றிலே... ...`;
- `ஓர் களத்தில்,` restored to its source position after `அந்நாளில்` and before `தாய்நாடு காக்க...`;
- scan-visible paired quotation punctuation retained.

The old-glyph area corresponding to Gemini's `தன் மகனை / யும்` was deliberately not modernized from visual expectation; the plausible first-pass reading was retained.

## Exact next activity

Process **`சேரன் செங்குட்டுவன்` scan 47 / printed p.42 only** as the next Scene-2 continuation-page verification activity.

Requirements:

- inspect scan 47 directly from the controlling PDF;
- use the user-supplied Gemini first-pass as comparison baseline;
- preserve source wording, punctuation, speaker labels, stage directions, physical line boundaries and source marks;
- apply the old-glyph safeguard and avoid expectation-based lexical correction;
- create `works/cheran-senguttuvan/pages/0047.md` only after direct verification;
- update `SCENE2_PAGE_VERIFICATION.md`, work/source progress, page maps, README files and handover after verification;
- expected durable total after success: **4/10 pages verified**, Scene-2 gate **2/4**;
- do **not** process scan 48 in the same activity;
- do **not** assemble Scene 2 in the same activity;
- do **not** use the English witness to reconstruct Tamil.

When I say **“Proceed with next activity”**, execute this exact activity directly without asking me to choose a routine next step.
