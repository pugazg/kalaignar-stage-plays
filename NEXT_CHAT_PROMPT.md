# Next Chat Prompt — Kalaignar Stage Plays / திருவாளர் தேசீயம்பிள்ளை

Continue directly in `pugazg/kalaignar-stage-plays`, branch `main`, active work `works/thiruvalar-desiyampillai/`.

## LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first. Preserve newer durable state. Do not reopen closed காகிதப்பூ / மணிமகுடம் / நான்மணி மாலை work because an older copied prompt contains a stale checkpoint.

## Mandatory startup

Read before further work:

1. `STAGE_PLAY_PROCESSING_GUIDE.md`
2. `HANDOVER.md`
3. this `NEXT_CHAT_PROMPT.md`
4. `works/thiruvalar-desiyampillai/README.md`
5. `works/thiruvalar-desiyampillai/metadata/source.md`
6. `works/thiruvalar-desiyampillai/indexes/page-map.md`
7. `works/thiruvalar-desiyampillai/HISTORICAL_GLYPH_AUDIT.md`
8. `works/thiruvalar-desiyampillai/PAGE_LAYER_COMPLETION_AUDIT.md`
9. `works/thiruvalar-desiyampillai/STRUCTURAL_SCENE_INVENTORY.md`
10. `works/thiruvalar-desiyampillai/ASSEMBLY_REVIEW.md`
11. all seven `works/thiruvalar-desiyampillai/scenes/sru-*.md` files
12. controlling PDF only if new page-level source evidence must be adjudicated

The user-supplied `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md` remains mandatory methodology, not a lexical first-pass witness.

## Current source

`TVA_BOK_0064118_திருவாளர்_தேசீயம்பிள்ளை.pdf`

- SHA-256: `b336bbebb326803badecbaa93de4ca4d63d80f68137fe70673b07a884c4910eb`
- size: **58,035,177 bytes**
- scans: **49**
- second edition: **நவம்பர் 1965**
- publisher: **K. R. நாராயணன்**

## Page-layer checkpoint

**SOURCE-PAGE PASS COMPLETE.**

- page records/source processing: **49 / 49**;
- full historical-glyph passes: **49 / 49**;
- visually verified: **40 / 49** (`2, 6, 10–34, 37–49`);
- `needs-review`: **9 / 49** (`1, 3, 4, 5, 7, 8, 9, 35, 36`);
- unprocessed: **0**;
- unresolved visual/source clusters: **3** (scan 35: 1; scan 36: 2).

Completion audit: `works/thiruvalar-desiyampillai/PAGE_LAYER_COMPLETION_AUDIT.md`.

Audit verdict: **coverage PASS but not 49/49 verified**. These source limitations remain explicit and must never be repaired from context.

## Historical Tamil glyph checkpoint

The 13-family pass is complete for all 49 scans:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`.

Positive same-edition reference families:

`லை / ளை / ணா / ணை / னா / னை / றா`.

Authoritative source-pixel decisions — do not revert:

- scan 15 `என்றுரே / தானு` → `என்றாரே / தானா`;
- scan 20 `நன்றுக` → `நன்றாக`;
- scan 21 `மகனு` → `மகனா`;
- scan 28 `மால்தானே` → `மாலைதானே`;
- scan 42 → `பொறாமை`;
- scan 44 → `ஆலை முதலாளி`;
- scan 46 source colloquial `நம்ப`, not `நம்ம`;
- scans 46–48 source work/name spelling `தேசீயம்`;
- scan 47 source `போட்டகோலம்`;
- scan 48 physical `மலை / யேறும்`.

## Structural inventory — COMPLETE / PASS

`works/thiruvalar-desiyampillai/STRUCTURAL_SCENE_INVENTORY.md` is **PASS / REVIEWED**.

- source-visible `காட்சி`, numbered scenes, or acts: **0**;
- seven editorial SRUs only;
- shared-page boundaries: scans **15, 20, 28, 40**;
- scan-47 `உதயசூரியன் கோலம்`: internal descriptive/intertitle in SRU-07;
- scan-48: no source `முற்றும்`.

SRU numbers are repository/editorial identifiers only, not source scene numbers.

## Tamil source-representation assembly — COMPLETE / REVIEWED / PASS

Durable review: `works/thiruvalar-desiyampillai/ASSEMBLY_REVIEW.md`.

Seven reviewed Tamil SRUs:

1. `scenes/sru-01-yama-court.md`
2. `scenes/sru-02-guesthouse.md`
3. `scenes/sru-03-eman-interview.md`
4. `scenes/sru-04-gandhi-journey.md`
5. `scenes/sru-05-stairfall-dream-exit.md`
6. `scenes/sru-06-domestic-election-argument.md`
7. `scenes/sru-07-udayasuriyan-kolam-close.md`

Assembly-review results:

- SRUs present: **7 / 7**;
- dramatic source scans represented: **42 / 42** (`7–48`);
- shared-page boundaries checked: **4 / 4**;
- source scene/act numbers invented: **0**;
- scan 49 included in dramatic assembly: **no**;
- invented `முற்றும்`: **no**;
- scan-47 `உதயசூரியன் கோலம்`: preserved internally in SRU-07.

Review-hold propagation:

- **SRU-01:** `assembled_from_verified_pages: false`; all scan 7–9 `[paper loss]` markers retained; no loss reconstructed.
- **SRU-04:** `assembled_from_verified_pages: false`; scan-35 `[unresolved glyph cluster]` and both scan-36 `[unresolved descriptive cluster]` markers retained.
- **SRU-02 / 03 / 05 / 06 / 07:** verified-source assembly, `assembled_from_verified_pages: true`.

The Tamil archival layer is now **assembly-complete / reviewed for current source evidence**. Do not modify it from translation choices.

## English translation state

**NOT AUTHORIZED / NOT STARTED.**

Do not draft English until a translation plan is created and explicitly authorized.

When English is later authorized, immediate drafting authority must be the reviewed Tamil SRUs only. Do not draft from OCR, the PDF, another edition, web text, general knowledge, or any secondary English witness. Page records/PDF may be consulted only to adjudicate a source question and must not be used to bypass the reviewed Tamil assembly.

## Exact next activity — create English translation plan only

Create a durable `works/thiruvalar-desiyampillai/TRANSLATION_PLAN.md` and an English tracker stub such as `works/thiruvalar-desiyampillai/translations/en/README.md`, but **do not create translated SRU body files yet**.

The plan must define:

1. immediate drafting authority: the seven reviewed Tamil SRUs;
2. expected English mapping that mirrors the seven SRU filenames without implying numbered source scenes;
3. how source markers are translated/preserved:
   - `[paper loss]` must remain explicit and untranslated as a provenance marker or use an explicitly documented English-equivalent marker consistently;
   - `[unresolved glyph cluster]` must remain unresolved;
   - `[unresolved descriptive cluster]` must remain unresolved;
   - no inferred wording may be inserted around those markers;
4. preservation of speaker-label variation, stage directions, narrative prose, satire, political rhetoric, repetitions, colloquial register, proper names and supported ambiguity;
5. preservation of internal scan-47 `உதயசூரியன் கோலம்` in the final English SRU as an internal descriptive/intertitle, not a source scene title;
6. no invented `முற்றும்` / “The End” marker;
7. translation metadata must state the Tamil SRU source and `secondary_english_witness_used: false` unless a later separately authorized comparison phase changes that;
8. every English artifact must receive a complete Tamil→English fidelity review before `translation_review: passed`;
9. propose a sensible translation order/batching for all seven SRUs and a final `TRANSLATION_REVIEW.md` gate;
10. translation must never retroactively alter the Tamil archival layer.

After writing the plan/tracker, stop and record the phase as **PLAN READY / NOT YET AUTHORIZED** unless the user explicitly authorizes English translation.

## Closed-work safeguards

`காகிதப்பூ` remains COMPLETE / CLOSED: Tamil 41/41, source-representation scenes 23/23, English 23/23, final reviews PASS. `மணிமகுடம்` and closed `கலைஞரின் நான்மணி மாலை` components remain closed unless explicitly reopened.