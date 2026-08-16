# Next Chat Prompt — சிலப்பதிகாரம் நாடகக் காப்பியம்

Copy/paste the prompt below into a fresh ChatGPT window. **Attach the Tamil source PDF** `TVA_BOK_0016473_சிலப்பதிகாரம்_நாடகக்_காப்பியம்.pdf` because the next activity requires a direct visual text fidelity comparison against scan 17.

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
9. `works/silappathikaram-nataka-kappiyam/VISUAL_TEXT_FIDELITY_CHECK.md`
10. `works/silappathikaram-nataka-kappiyam/pages/0017.md`

Use the GitHub connector and work directly in the existing repository.

If the Tamil PDF is not attached/available, **stop and ask me to attach it**. Do not perform the visual-text fidelity gate from repository text alone.

## Source authority

The Tamil scan remains controlling authority. Verified `pages/NNNN.md` records are the immediate source for scene assembly, but every assembled scene must also be compared directly against the actual source pixels.

Do not silently modernize, correct, normalize, reconstruct or improve Kalaignar's Tamil.

Preserve spelling, punctuation, speaker labels, stage directions, repetition, unusual grammar, source-supported spacing, page/column continuations and source anomalies. OCR, another edition and the published English translation are secondary/assistive only.

## Completed work — do not restart

- All **88 supplied physical scans are visually verified**.
- **காட்சி-1 through காட்சி-38 are complete at page-record level**.
- The scan-88 post-scene closing tableau is archived.
- Tamil page-level visual verification is complete.
- Repository-wide Tamil transcription completion audit is **complete / PASS**.
- `audit.md` confirms continuous `pages/0001.md`–`pages/0088.md` coverage and scene extents 1–38.
- `SCENE_ASSEMBLY_PLAN.md` defines the scene assembly format and rules.
- `VISUAL_TEXT_FIDELITY_CHECK.md` defines a mandatory direct scan-to-scene fidelity gate for every assembled scene.
- No scene assembly file has yet been created.
- English translation has not begun.

Do not retranscribe or casually modify verified pages. Change a verified page only if the visual-text fidelity activity gives a concrete discrepancy and direct source-pixel inspection proves the existing page reading wrong.

## Assembly convention

Planned output:

`works/silappathikaram-nataka-kappiyam/scenes/01.md` through `38.md`, plus `scenes/closing-tableau.md`.

Assembly rules:

- assemble only from verified page records;
- keep page records authoritative for construction and the source scan authoritative for direct visual verification;
- mechanical printed line/column wrapping may be joined only when wording and punctuation are unchanged;
- preserve repeated wording and source-specific punctuation;
- preserve exact speaker labels and stage directions;
- keep visual material/captions in a separate source-visual section;
- retain scan provenance for multi-scan scenes;
- do not infer printed pagination;
- do not reconstruct scan-88 stamp-obscured characters;
- an assembled scene starts at `status: "draft"` with `visual_text_fidelity: "pending"`;
- a scene can become `assembly-reviewed` only after a direct source-pixel fidelity pass and a page-record comparison both succeed.

## Exact next activity — scene-1 assembly + visual text fidelity pilot

Process **காட்சி-1 / scan 17**.

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
2. Read `VISUAL_TEXT_FIDELITY_CHECK.md` completely.
3. Create `scenes/01.md` using the front-matter convention in `SCENE_ASSEMBLY_PLAN.md`, initially with `status: "draft"` and `visual_text_fidelity: "pending"`.
4. Assemble the scene from the verified page record without changing source wording, punctuation, speaker labels or stage directions.
5. Remove only mechanical printed line wrapping where the assembly plan permits it; do not remove genuine repetition or source-significant spacing/punctuation.
6. Keep title artwork in a separate `Source visual layers` section.
7. **Inspect the actual attached scan 17 at native/enlarged resolution.**
8. Compare the complete assembled scene directly against the scan pixels, character-by-character. Reconfirm scene number/title, opening stage direction, every speaker label and dialogue line, punctuation, ellipses, dashes, brackets, repetitions, names/numbers and source-significant spacing.
9. Verify every mechanical join introduced during assembly so that no source character/word/punctuation was omitted, duplicated, moved or normalized.
10. Confirm directly from the scan that the architectural/drummer artwork is visual-only and that no library/accession mark or pagination has entered the literary text.
11. Compare the visually checked scene again against `pages/0017.md` to detect any assembly-only omission/duplication.
12. If source pixels prove `pages/0017.md` wrong at any point, correct only that affected verified reading, document the source-pixel reason, then regenerate/recheck the scene.
13. Set `visual_text_fidelity: "passed"` and `status: "assembly-reviewed"` only after both the direct scan comparison and page-record comparison pass.
14. Update the assembly plan/handover to record whether the pilot file format and fidelity procedure are accepted.
15. Do not begin scene 2 in the same activity unless explicitly instructed.

## Translation lock

Do not begin English translation.

Permanent terminology instruction: **Do not automatically translate `அந்தணர்` as “Brahmin.”** Preserve distinctions among `பிராமண`, `பார்ப்பன`, `அந்தணர்`, `மறையவன்`, and other source terms. English renderings will be decided only in dedicated terminology review.

When translation eventually begins, retain Kalaignar's language, rhetoric, cadence, repetition and dramatic voice.

## End-of-activity report

Report:

- scene assembled and exact source scan;
- direct visual-text fidelity result against scan 17;
- whether any verified page reading required correction and the source-pixel reason;
- mechanical joins performed and visually verified;
- visual layers separated;
- files created/updated;
- final assembly status and `visual_text_fidelity` state of `scenes/01.md`;
- whether the pilot format/fidelity procedure was accepted;
- exact next scene assembly activity.

Proceed now with **காட்சி-1 / scan 17 scene assembly + visual text fidelity pilot**.

---
