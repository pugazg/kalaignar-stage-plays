# Scene Assembly Consistency Audit — ஒரே முத்தம்

Status: **PASS — FULL TAMIL SCENE LAYER 33 / 33 ASSEMBLED AND PAGE-RECORD-CONSISTENT**.

This audit checks the complete Tamil scene layer against the canonical `pages/*.md` records and the boundary-aware segmentation in `SCENE_BOUNDARY_AUDIT.md`. A PASS here means **assembly fidelity / traceability PASS**. It does **not** convert terminal source-condition holds into verified wording and does not authorize English translation.

## Audit method

For every assembled scene:

1. confirm the boundary-aware contributing scan range;
2. compare the scene text with the scene-relevant segment of each canonical page record;
3. split shared transition scans only at explicit source scene headings;
4. preserve documented physical scan boundaries as archival comments rather than silently normalizing them;
5. preserve source speaker labels, punctuation, stage directions, historical spelling and source-visible spacing;
6. verify `assembled_from_verified_pages`, `page_record_fidelity` and `source_condition_scans` against the page layer;
7. preserve every explicit `[source-held: ...]` / equivalent marker exactly where present;
8. where a blocked page carries canonical provisional wording rather than an explicit marker, retain that page-layer wording exactly and keep the scan listed as a terminal source-condition dependency;
9. ensure a hold belonging only to the following scene is not imported into the preceding source-secure boundary case;
10. do not use OCR expectation, plot continuity, grammar, modern spelling or another edition to fill a held locus.

## Main play — 30 / 30 assembled

| Scene | Scene file | Contributing scans | Source-condition scans inside scene | Result |
|---:|---|---:|---|---|
| 1 | `scenes/main-01.md` | 8–9 | — | PASS |
| 2 | `scenes/main-02.md` | 9–11 | — | PASS |
| 3 | `scenes/main-03.md` | 11–15 | — | PASS |
| 4 | `scenes/main-04.md` | 15–19 | — | PASS |
| 5 | `scenes/main-05.md` | 19–20 | — | PASS |
| 6 | `scenes/main-06.md` | 21–24 | 21 | PASS — hold preserved |
| 7 | `scenes/main-07.md` | 24–27 | 27 | PASS — holds preserved |
| 8 | `scenes/main-08.md` | 27–32 | 27 | PASS — holds preserved |
| 9 | `scenes/main-09.md` | 32–37 | — | PASS |
| 10 | `scenes/main-10.md` | 37–40 | — | PASS |
| 11 | `scenes/main-11.md` | 41–46 | 43 | PASS — hold preserved |
| 12 | `scenes/main-12.md` | 46–51 | 47, 48, 51 | PASS — holds preserved |
| 13 | `scenes/main-13.md` | 51–52 | 52 | PASS — hold preserved |
| 14 | `scenes/main-14.md` | 52–53 | 52 | PASS — hold preserved |
| 15 | `scenes/main-15.md` | 53–59 | — | PASS |
| 16 | `scenes/main-16.md` | 59–64 | 60, 61 | PASS — holds preserved |
| 17 | `scenes/main-17.md` | 64–68 | 65 | PASS — canonical provisional page-layer wording retained |
| 18 | `scenes/main-18.md` | 68–72 | 69 | PASS — holds preserved |
| 19 | `scenes/main-19.md` | 72–75 | 72, 73, 74 | PASS — explicit/provisional holds preserved |
| 20 | `scenes/main-20.md` | 75–80 | 77, 79 | PASS — explicit/provisional holds preserved |
| 21 | `scenes/main-21.md` | 80–85 | — | PASS |
| 22 | `scenes/main-22.md` | 85–87 | — | PASS |
| 23 | `scenes/main-23.md` | 87–94 | 88, 90 | PASS — holds preserved; scan-94 hold belongs to Scene 24 |
| 24 | `scenes/main-24.md` | 94–95 | 94, 95 | PASS — canonical blocked-page wording retained |
| 25 | `scenes/main-25.md` | 96–99 | 98, 99 | PASS — holds preserved |
| 26 | `scenes/main-26.md` | 100–104 | 100 | PASS — hold preserved |
| 27 | `scenes/main-27.md` | 104–105 | — | PASS |
| 28 | `scenes/main-28.md` | 106–112 | — * | PASS — source-secure boundary case |
| 29 | `scenes/main-29.md` | 112–117 | 112, 113 | PASS — holds preserved |
| 30 | `scenes/main-30.md` | 117–118 | — | PASS |

`*` Main Scene 28 uses only the secure pre-`காட்சி 29.` segment of globally blocked scan 112. The scan-112 held locus belongs to Scene 29 and is not imported into Scene 28.

## Supplementary `நகைச் சுவைப் பகுதி.` — 3 / 3 assembled

| Scene | Scene file | Contributing scans | Source-condition scans inside scene | Result |
|---:|---|---:|---|---|
| 1 | `scenes/nagai-suvai-01.md` | 119–125 | — | PASS |
| 2 | `scenes/nagai-suvai-02.md` | 125–128 | — * | PASS — source-secure boundary case |
| 3 | `scenes/nagai-suvai-03.md` | 128–130 | 128, 130 | PASS — holds preserved |

`*` Supplementary Scene 2 uses only the secure pre-`காட்சி 3.` segment of globally blocked scan 128. The scan-128 held locus belongs to supplementary Scene 3 and is not imported into Scene 2.

## Front-matter audit

- **13 / 33** scenes use only globally `verified` physical page records and correctly use `assembled_from_verified_pages: true`, `page_record_fidelity: "passed"`, `source_condition_scans: []`.
- **2 / 33** source-secure boundary cases — main Scene **28** and supplementary Scene **2** — correctly use `assembled_from_verified_pages: false`, `page_record_fidelity: "passed"`, `source_condition_scans: []` because a shared contributing physical page is globally blocked only for later-scene text.
- **18 / 33** hold-bearing scenes correctly use `assembled_from_verified_pages: false`, `status: "assembly-held"`, and list their scene-relevant terminal scans under `source_condition_scans`.
- No hold-bearing scene is falsely promoted to source-verified/release-final status.

## Terminal-hold traceability audit

Scene-relevant hold ownership is preserved as follows:

- Scene 6 → `21`;
- Scene 7 → `27`;
- Scene 8 → `27`;
- Scene 11 → `43`;
- Scene 12 → `47, 48, 51`;
- Scene 13 → `52`;
- Scene 14 → `52`;
- Scene 16 → `60, 61`;
- Scene 17 → `65`;
- Scene 18 → `69`;
- Scene 19 → `72, 73, 74`;
- Scene 20 → `77, 79`;
- Scene 23 → `88, 90`;
- Scene 24 → `94, 95`;
- Scene 25 → `98, 99`;
- Scene 26 → `100`;
- Scene 29 → `112, 113`;
- supplementary Scene 3 → `128, 130`.

This ownership is segment-aware. Globally blocked transition scans are not automatically attributed to both adjacent scenes.

## Boundary checks

Confirmed shared-page segmentation includes:

- 9: Scene 1 / Scene 2;
- 11: Scene 2 / Scene 3;
- 15: Scene 3 / Scene 4;
- 19: Scene 4 / Scene 5;
- 24: Scene 6 / Scene 7;
- 27: Scene 7 / Scene 8;
- 32: Scene 8 / Scene 9;
- 37: Scene 9 / Scene 10;
- 46: Scene 11 / Scene 12;
- 51: Scene 12 / Scene 13;
- 52: Scene 13 / Scene 14;
- 53: Scene 14 / Scene 15;
- 59: Scene 15 / Scene 16;
- 64: Scene 16 / Scene 17;
- 68: Scene 17 / Scene 18;
- 72: Scene 18 / Scene 19;
- 75: Scene 19 / Scene 20;
- 80: Scene 20 / Scene 21;
- 85: Scene 21 / Scene 22;
- 87: Scene 22 / Scene 23;
- 94: Scene 23 / Scene 24;
- 104: Scene 26 / Scene 27;
- 112: Scene 28 / Scene 29;
- 117: Scene 29 / Scene 30;
- 125: supplementary Scene 1 / Scene 2;
- 128: supplementary Scene 2 / Scene 3.

Documented physical continuations remain explicit through archival boundary comments rather than being silently respelled or normalized, including the known scan 10→11, 39→40, 55→56, 63→64, 67→68, 79→80, 88→89, 93→94, 96→97, 97→98, 102→103, 106→107 and 121→122 continuations.

## Full Tamil scene-layer closure

- main scene files assembled: **30 / 30**;
- supplementary scene files assembled: **3 / 3**;
- total Tamil scene files assembled: **33 / 33**;
- source-secure scene files: **15 / 33**;
- hold-bearing scene files: **18 / 33**;
- all scene files page-record-consistency audited: **33 / 33 — PASS**;
- terminal source-condition loci repaired from context: **0**;
- source wording normalized by assembly: **0**;
- unresolved wording invented: **0**;
- OCR / plot-continuity / another-edition completion: **0**;
- English translation: **not authorized / not started**.

## Exact next activity

The Tamil page layer, structural layer and scene-assembly layer are now complete for the current source evidence. The **next archival activity is a Tamil pre-release / work-level closure gate**:

1. verify scene-file inventory is exactly main `01–30` plus supplementary `01–03` with no duplicates or numbering leakage;
2. verify all 28 terminal physical-page holds remain traceable from page records through the scene layer where scene-relevant;
3. reconcile README / handover / prompt status and any stale `needs-review` labels in secondary indexes without changing the canonical page records or pretending terminal holds are resolved;
4. decide/document the work-level Tamil release state under the repository's terminal-source-condition policy;
5. do **not** begin English translation unless explicitly authorized.
