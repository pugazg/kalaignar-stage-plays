# Scene Assembly Consistency Audit — ஒரே முத்தம்

Status: **PASS — 15 / 15 ASSEMBLED SOURCE-SECURE SCENES PAGE-RECORD-CONSISTENT**.

This audit checks the currently assembled Tamil scene layer against the canonical `pages/*.md` records and the boundary-aware segmentation in `SCENE_BOUNDARY_AUDIT.md`. It does not reopen source adjudication and does not authorize English translation.

## Audit method

For each assembled scene:

1. confirm the boundary-aware contributing scan range;
2. compare the scene text against the source-visible scene segment in each canonical page record;
3. confirm shared transition scans are split only at explicit source scene headings;
4. retain documented physical scan boundaries as archival comments rather than silently normalizing them;
5. confirm speaker labels, punctuation, stage directions, historical spellings and source-visible spacing are unchanged;
6. verify `assembled_from_verified_pages` and `source_condition_scans` accurately describe the contributing physical-page state;
7. ensure no terminal held locus from the following scene is imported into a source-secure boundary case.

## PASS set

### Main play — 13 / 30 assembled

| Scene | Scene file | Contributing scans | Assembly class | Result |
|---:|---|---:|---|---|
| 1 | `scenes/main-01.md` | 8–9 | all contributing page records verified | PASS |
| 2 | `scenes/main-02.md` | 9–11 | all contributing page records verified | PASS |
| 3 | `scenes/main-03.md` | 11–15 | all contributing page records verified | PASS |
| 4 | `scenes/main-04.md` | 15–19 | all contributing page records verified | PASS |
| 5 | `scenes/main-05.md` | 19–20 | all contributing page records verified | PASS |
| 9 | `scenes/main-09.md` | 32–37 | all contributing page records verified | PASS |
| 10 | `scenes/main-10.md` | 37–40 | all contributing page records verified | PASS |
| 15 | `scenes/main-15.md` | 53–59 | all contributing page records verified | PASS |
| 21 | `scenes/main-21.md` | 80–85 | all contributing page records verified | PASS |
| 22 | `scenes/main-22.md` | 85–87 | all contributing page records verified | PASS |
| 27 | `scenes/main-27.md` | 104–105 | all contributing page records verified | PASS |
| 28 | `scenes/main-28.md` | 106–112 | source-secure boundary case; scan 112 blocked only after `காட்சி 29.` | PASS |
| 30 | `scenes/main-30.md` | 117–118 | all contributing page records verified | PASS |

### Supplementary `நகைச் சுவைப் பகுதி.` — 2 / 3 assembled

| Scene | Scene file | Contributing scans | Assembly class | Result |
|---:|---|---:|---|---|
| 1 | `scenes/nagai-suvai-01.md` | 119–125 | all contributing page records verified | PASS |
| 2 | `scenes/nagai-suvai-02.md` | 125–128 | source-secure boundary case; scan 128 blocked only after `காட்சி 3.` | PASS |

## Front-matter audit

- **13 / 15** assembled scenes use only globally `verified` physical page records and correctly use `assembled_from_verified_pages: true`, `page_record_fidelity: "passed"`, `source_condition_scans: []`.
- Main Scene **28** and supplementary Scene **2** correctly use `assembled_from_verified_pages: false`, `page_record_fidelity: "passed"`, `source_condition_scans: []` because their scene text is source-secure but one shared contributing physical page is globally `blocked` only for later-scene text.
- No currently assembled scene contains a terminal unresolved locus inside its own scene text.

## Boundary checks

Confirmed shared-page segmentation includes:

- 9: Scene 1 / Scene 2;
- 11: Scene 2 / Scene 3;
- 15: Scene 3 / Scene 4;
- 19: Scene 4 / Scene 5;
- 32: Scene 8 / Scene 9;
- 37: Scene 9 / Scene 10;
- 53: Scene 14 / Scene 15;
- 59: Scene 15 / Scene 16;
- 80: Scene 20 / Scene 21;
- 85: Scene 21 / Scene 22;
- 87: Scene 22 / Scene 23;
- 104: Scene 26 / Scene 27;
- 112: Scene 28 / Scene 29 — only the secure Scene-28 prefix is imported;
- 117: Scene 29 / Scene 30;
- 125: supplementary Scene 1 / Scene 2;
- 128: supplementary Scene 2 / Scene 3 — only the secure Scene-2 prefix is imported.

Documented physical continuations remain visible through archival boundary comments, including scan 39→40 in Scene 10, scan 55→56 in Scene 15, scan 106→107 in Scene 28, and scan 121→122 in supplementary Scene 1.

## Audit closure

- assembled scene files audited: **15 / 15 — PASS**;
- main scenes assembled: **13 / 30**;
- supplementary scenes assembled: **2 / 3**;
- source-secure assembled scenes: **15 / 15**;
- scenes with an unresolved locus imported: **0**;
- source wording modified by assembly: **0**;
- unresolved wording invented: **0**;
- contextual / OCR / another-edition repair: **0**;
- English translation: **not authorized / not started**.

## Exact next activity

Proceed to the **hold-bearing Tamil scene assembly**. Assemble from canonical page-record segments only and preserve every terminal marker exactly.

Main scenes remaining with scene-relevant terminal loci:

**6–8, 11–14, 16–20, 23–26, 29**.

Supplementary remaining hold-bearing scene:

**`நகைச் சுவைப் பகுதி.` Scene 3**.

For each, use `assembled_from_verified_pages: false`, list every scene-relevant held scan in `source_condition_scans`, retain `[source-held: ...]` / equivalent markers exactly, and do not infer missing wording from context.
