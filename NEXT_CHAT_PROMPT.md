# Next Chat Prompt — Continue `சேரன் செங்குட்டுவன்` in Kalaignar Stage Plays

Continue the Kalaignar Stage Plays archival project directly in:

`https://github.com/pugazg/kalaignar-stage-plays`

Branch: `main`.

Use the GitHub connector and work directly on `main`.

Controlling source PDF: `TVA_BOK_0065576_நான்மணி_மாலை.pdf`.

## Live-state rule

Fetch live GitHub `main` first and treat it as authoritative. Preserve any newer durable state. Do not reopen completed `சாக்ரடீஸ்`, Cheran Scene 1 or Cheran Scene 2 unless explicitly requested.

## Mandatory startup reading

Before any write, read completely:

1. `STAGE_PLAY_PROCESSING_GUIDE.md`
2. `HANDOVER.md`
3. `NEXT_CHAT_PROMPT.md`
4. `works/cheran-senguttuvan/README.md`
5. `works/cheran-senguttuvan/metadata/source.md`
6. `works/cheran-senguttuvan/indexes/page-map.md`
7. `works/cheran-senguttuvan/SCENE3_PAGE_VERIFICATION.md`
8. `works/cheran-senguttuvan/pages/0050.md`
9. `sources/naanmani-malai-tamil/README.md`
10. `sources/naanmani-malai-tamil/indexes/page-map.md`

Then re-fetch live `main` immediately before the first write.

## Completed durable state

- `பரதாயணம்` — Tamil archive/assembly PASS; independent English translation PASS.
- `அனார்கலி` — Tamil page/assembly fidelity PASS.
- `சாக்ரடீஸ்` — **17/17 pages verified; 5/5 scenes assembled; all fidelity gates PASS**.
- `சேரன் செங்குட்டுவன்` `காட்சி — 1` — **page gate + assembly/fidelity PASS**.
- `சேரன் செங்குட்டுவன்` `காட்சி — 2` — **page gate + assembly/fidelity PASS**.

## Active work — `சேரன் செங்குட்டுவன்`

Controlling extent: scans **44–53** / printed pp. **39–48**; four source-printed scenes.

Current durable progress:

- Tamil pages verified: **7/10**;
- scenes assembled: **2/4**;
- `காட்சி—3.` source extent: scans **50–51** / pp.45–46;
- scan **50 / p.45** — **verified**;
- Scene-3 page gate: **1/2**;
- scan **51 / p.46** — not processed.

## First-pass / source rule

The user supplied a Gemini word-to-word first pass covering the Cheran source extent. Gemini is a comparison baseline only; the Tamil scan is controlling. Do not replace plausible old-glyph readings by expectation. Change first-pass wording only when scan evidence is unambiguous and document it. The 2009 English witness is secondary and must not reconstruct Tamil.

Important scan-50 controls:

- source `காட்சி—3.` and `சேரன் கொலுமண்டபம்`;
- `உத்திரனும்—விசித்திரனும்—சித்தரனும்—சிவேதனும்—பைரவனும்!`;
- `கனகனும்விசயனும்`;
- source `வள்ளுவனே!`, `முல்லைக் கொல்லையே!`, `நெடுஞ்செழியனே!`;
- short spaced source hyphen `வீணன் - கயலைப்`;
- plausible first-pass `காணா` retained under the old-glyph safeguard;
- no closing `*` on scan 50.

## Exact next activity

Process **`சேரன் செங்குட்டுவன்` scan 51 / printed p.46 only** as the closing-page verification activity for `காட்சி—3.`.

Requirements:

- inspect scan 51 directly from the controlling PDF;
- use the user-supplied Gemini first-pass as comparison baseline;
- preserve source wording, punctuation, speaker labels, physical line boundaries and final source marks;
- apply the old-glyph safeguard and avoid expectation-based lexical correction;
- create `works/cheran-senguttuvan/pages/0051.md` only after direct verification;
- update `SCENE3_PAGE_VERIFICATION.md`, work/source progress, page maps, README files and handover after verification;
- expected durable total after success: **8/10 pages verified**, Scene-3 gate **2/2 COMPLETE**;
- preserve the closing `*` exactly if confirmed on scan 51;
- do **not** assemble Scene 3 in the same activity;
- do **not** process scan 52 in the same activity;
- do **not** use the English witness to reconstruct Tamil.

When I say **“Proceed with next activity”**, execute this exact activity directly without asking me to choose a routine next step.
