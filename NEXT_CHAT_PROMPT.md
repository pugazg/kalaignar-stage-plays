# Next Chat Prompt — Continue `சாக்ரடீஸ்` in Kalaignar Stage Plays

Continue the Kalaignar Stage Plays archival project directly in:

`https://github.com/pugazg/kalaignar-stage-plays`

Branch: `main`.

Use the GitHub connector and work directly on `main`.

Controlling source PDF: `TVA_BOK_0065576_நான்மணி_மாலை.pdf`.

## Live-state rule

Fetch live GitHub `main` **FIRST** and treat it as authoritative. The checkpoint immediately before the Scene-1 page-verification batch was `e4cef290c33808bd7efeb13251bc10010731ccc0`; if live `main` is newer, preserve the newer state.

## Mandatory startup reading

Read completely before any write:

1. `STAGE_PLAY_PROCESSING_GUIDE.md`
2. `HANDOVER.md`
3. `NEXT_CHAT_PROMPT.md`
4. `works/socrates/INTRO_RECONCILIATION.md`
5. `works/socrates/SCENE1_PAGE_VERIFICATION.md`
6. `works/socrates/README.md`
7. `works/socrates/metadata/source.md`
8. `works/socrates/indexes/page-map.md`
9. `works/socrates/pages/0029.md`
10. `works/socrates/pages/0030.md`
11. `works/socrates/pages/0031.md`

Then re-fetch live `main` immediately before the first write.

## Durable state

Completed/locked:

- `பரதாயணம்` — Tamil archive/assembly PASS; independent English translation PASS.
- `அனார்கலி` — Tamil archive/assembly PASS.
- Silappathikaram complete state remains locked.

Active work: `சாக்ரடீஸ்`.

- source extent: scans **27–43** / pp.22–38;
- introductory note scans 27–28: **2/2 verified**;
- `காட்சி—1` scans 29–31 / pp.24–26: **3/3 page records verified**;
- total Socrates page progress: **5/17 verified**;
- dramatic page progress: **3/15**;
- Scene-1 assembly: **pending**.

Critical page boundary: scan 29 ends Socrates' speech at `எனக்கு`; scan 30 begins `வாய்த்த இளம் மனைவி...`. Assembly must join this mechanically without inventing a new speaker label.

Old-glyph controls and user-rejected normalizations are recorded in `INTRO_RECONCILIATION.md` and `SCENE1_PAGE_VERIFICATION.md`. Retain plausible Gemini readings unless the scan is unambiguous; do not normalize by expectation.

## Exact next activity

Assemble **`சாக்ரடீஸ்` `காட்சி—1` only** from the three verified page records.

Requirements:

- verified page records are the sole textual authority;
- mechanically join legitimate print-line and page-boundary splits only;
- preserve all dialogue labels, punctuation, repetitions and stage directions;
- create the assembled Scene-1 file under `works/socrates/scenes/`;
- run/create a page-record ↔ scene fidelity audit and require PASS before advancing;
- **do not start scan 32 / `காட்சி—2` in the same activity**;
- do not start `சேரன் செங்குட்டுவன்`.

After Scene-1 assembly/fidelity PASS, the next distinct activity is `காட்சி—2` page verification at scan **32** / printed p.27.

When I say **“Proceed with next activity”**, execute this exact activity directly without asking me to choose a routine next step.
