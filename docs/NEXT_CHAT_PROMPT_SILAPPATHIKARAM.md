# Next Chat Prompt — சிலப்பதிகாரம் நாடகக் காப்பியம்

Copy/paste the prompt below into a fresh ChatGPT window. Attach the Tamil source PDF `TVA_BOK_0016473_சிலப்பதிகாரம்_நாடகக்_காப்பியம்.pdf` so any assembly discrepancy can be rechecked directly against source pixels.

---

Continue the Kalaignar Stage Plays archival project directly in:

`pugazg/kalaignar-stage-plays`

Work on `main`.

Active work:

`works/silappathikaram-nataka-kappiyam/`

Controlling Tamil source:

`TVA_BOK_0016473_சிலப்பதிகாரம்_நாடகக்_காப்பியம்.pdf`

## Mandatory startup

Before making any change, read these files completely and follow them exactly:

1. `STAGE_PLAY_PROCESSING_GUIDE.md`
2. `docs/SILAPPATHIKARAM_CONTINUATION_GUIDELINES.md`
3. `docs/SILAPPATHIKARAM_PROJECT_HANDOVER.md`
4. root `HANDOVER.md`
5. `works/silappathikaram-nataka-kappiyam/README.md`
6. `works/silappathikaram-nataka-kappiyam/indexes/page-map.md`
7. `works/silappathikaram-nataka-kappiyam/audit.md`
8. `works/silappathikaram-nataka-kappiyam/SCENE_ASSEMBLY_PLAN.md`
9. `works/silappathikaram-nataka-kappiyam/pages/0017.md`

Use the GitHub connector and work directly in the existing repository.

## Source authority

The Tamil scan remains controlling authority. Verified `pages/NNNN.md` records are the immediate source for scene assembly. Do not silently modernize, correct, normalize, reconstruct or improve Kalaignar's Tamil.

Preserve spelling, punctuation, speaker labels, stage directions, repetition, unusual grammar, source-supported spacing, page/column continuations and source anomalies. OCR, another edition and the published English translation are secondary/assistive only.

## Completed work — do not restart

- All **88 supplied physical scans are visually verified**.
- **காட்சி-1 through காட்சி-38 are complete at page-record level**.
- The scan-88 post-scene closing tableau is archived.
- Tamil page-level visual verification is complete.
- Repository-wide Tamil transcription completion audit is **complete / PASS**.
- `audit.md` confirms continuous `pages/0001.md`–`pages/0088.md` coverage and scene extents 1–38.
- `SCENE_ASSEMBLY_PLAN.md` defines the scene assembly format and rules.
- No scene assembly file has yet been created.
- English translation has not begun.

Do not retranscribe or casually modify verified pages. Change a verified page only if an assembly discrepancy gives a concrete reason and direct source-pixel inspection proves the existing reading wrong.

## Assembly convention

Planned output:

`works/silappathikaram-nataka-kappiyam/scenes/01.md` through `38.md`, plus `scenes/closing-tableau.md`.

Assembly rules:

- assemble only from verified page records;
- keep page records authoritative;
- mechanical printed line/column wrapping may be joined only when wording and punctuation are unchanged;
- preserve repeated wording and source-specific punctuation;
- preserve exact speaker labels and stage directions;
- keep visual material/captions in a separate source-visual section;
- retain scan provenance for multi-scan scenes;
- do not infer printed pagination;
- do not reconstruct scan-88 stamp-obscured characters;
- an assembled scene starts at `draft` and needs separate assembly review.

## Exact next activity — scene-1 assembly pilot

Assemble **காட்சி-1 / scan 17**.

Input:

`works/silappathikaram-nataka-kappiyam/pages/0017.md`

Output target:

`works/silappathikaram-nataka-kappiyam/scenes/01.md`

Verified structure:

- scene: `காட்சி-1`
- decorative title: **`வஞ்சி மூதூரில் முரசறைதல்`**
- physical source extent: scan **17 only**
- there is **no separate printed setting heading**; use `setting: null` and do not invent one from the opening stage direction
- the decorative architectural/drummer heading artwork is a separate visual layer, not literary text

For the pilot:

1. Read `pages/0017.md` completely.
2. Create `scenes/01.md` using the front-matter convention in `SCENE_ASSEMBLY_PLAN.md`.
3. Assemble the scene from the verified page record without changing source wording, punctuation, speaker labels or stage directions.
4. Remove only mechanical printed line wrapping where the assembly plan permits it; do not remove genuine repetition or source-significant spacing/punctuation.
5. Keep title artwork in a separate `Source visual layers` section.
6. Set assembly status to `draft` and `assembled_from_verified_pages: true`.
7. Perform an assembly-level comparison of the new scene file against `pages/0017.md`.
8. If the pilot format is sound, update the assembly plan/handover to record the accepted convention and identify `காட்சி-2 / scan 18` as the next assembly activity.
9. Do not begin scene 2 in the same activity unless explicitly instructed.

## Translation lock

Do not begin English translation.

Permanent terminology instruction: **Do not automatically translate `அந்தணர்` as “Brahmin.”** Preserve distinctions among `பிராமண`, `பார்ப்பன`, `அந்தணர்`, `மறையவன்`, and other source terms. English renderings will be decided only in dedicated terminology review.

When translation eventually begins, retain Kalaignar's language, rhetoric, cadence, repetition and dramatic voice.

## End-of-activity report

Report:

- scene assembled and exact source scan;
- whether any verified page reading required correction;
- mechanical joins performed, if any;
- visual layers separated;
- files created/updated;
- assembly status of `scenes/01.md`;
- whether the pilot format was accepted;
- exact next scene assembly activity.

Proceed now with **காட்சி-1 / scan 17 scene assembly pilot**.

---
