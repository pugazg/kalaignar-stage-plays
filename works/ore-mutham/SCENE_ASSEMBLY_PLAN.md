# Scene Assembly Plan — ஒரே முத்தம்

Status: **ASSEMBLY COMPLETE / FULL PAGE-TO-SCENE AUDIT PASS — 30 MAIN + 3 SUPPLEMENTARY SCENES**.

Authority chain:

1. controlling scan;
2. canonical visually checked `pages/*.md` records;
3. `SCENE_BOUNDARY_AUDIT.md` for shared transition-page segmentation;
4. `STRUCTURAL_INVENTORY.md` for boundary-aware scene ranges;
5. `TERMINAL_SOURCE_CONDITION_HOLDS.md` for unresolved-locus traceability;
6. `SCENE_ASSEMBLY_AUDIT.md` for the complete 33-scene page-to-scene consistency audit.

English translation remains **not authorized / not started**.

## Assembly namespaces — complete

- main play: `scenes/main-01.md` through `scenes/main-30.md` — **30 / 30 present**;
- supplementary `நகைச் சுவைப் பகுதி.`: `scenes/nagai-suvai-01.md` through `scenes/nagai-suvai-03.md` — **3 / 3 present**.

Supplementary scenes remain source-numbered **1–3**. They are never main scenes 31–33.

## Permanent transition-page rule

A physical scan may contribute source text to two adjacent scenes. Assembly operates on the **scene segment** of each canonical page record, not by assigning each scan exclusively to one scene.

When a shared page is terminally `blocked`, hold ownership is segment-level:

- if the held locus belongs to the scene being assembled, that scan is listed in `source_condition_scans` and its explicit hold marker / canonical provisional page-layer wording is retained;
- if the held locus begins only after the next scene anchor, the preceding scene may use its source-secure prefix, but `assembled_from_verified_pages` remains false because one contributing physical page record is globally blocked.

## Final assembly classes

### Fully verified physical-page inputs — 13 scenes

Main: **1–5, 9–10, 15, 21–22, 27, 30**.

Supplementary: **Scene 1**.

These use `status: "assembly-reviewed"`, `assembled_from_verified_pages: true`, `page_record_fidelity: "passed"`, `source_condition_scans: []`.

### Source-secure shared-boundary cases — 2 scenes

- main Scene **28** — secure pre-`காட்சி 29.` segment of blocked scan 112;
- supplementary Scene **2** — secure pre-`காட்சி 3.` segment of blocked scan 128.

These use `assembled_from_verified_pages: false`, `page_record_fidelity: "passed"`, `source_condition_scans: []`, with explicit boundary-only provenance.

### Hold-bearing scenes — 18 scenes

Main: **6–8, 11–14, 16–20, 23–26, 29**.

Supplementary: **Scene 3**.

These use `status: "assembly-held"`, `assembled_from_verified_pages: false`, `page_record_fidelity: "passed-with-terminal-source-hold"` or plural as applicable, and the exact scene-relevant terminal scans:

| Scene | Contributing scans | `source_condition_scans` |
|---:|---:|---|
| 6 | 21–24 | `[21]` |
| 7 | 24–27 | `[27]` |
| 8 | 27–32 | `[27]` |
| 11 | 41–46 | `[43]` |
| 12 | 46–51 | `[47, 48, 51]` |
| 13 | 51–52 | `[52]` |
| 14 | 52–53 | `[52]` |
| 16 | 59–64 | `[60, 61]` |
| 17 | 64–68 | `[65]` |
| 18 | 68–72 | `[69]` |
| 19 | 72–75 | `[72, 73, 74]` |
| 20 | 75–80 | `[77, 79]` |
| 23 | 87–94 | `[88, 90]` |
| 24 | 94–95 | `[94, 95]` |
| 25 | 96–99 | `[98, 99]` |
| 26 | 100–104 | `[100]` |
| 29 | 112–117 | `[112, 113]` |
| supplementary 3 | 128–130 | `[128, 130]` |

## Assembly rules — permanent

1. Scene text comes only from canonical page records; never from memory, OCR expectation, another edition or plot continuity.
2. Preserve source speaker labels, scene/location headings, punctuation, stage directions, historical spelling and source-visible spacing.
3. Shared transition scans are split only at explicit source scene headings.
4. Documented physical page boundaries remain traceable through archival comments; mechanically split words are not silently respelled.
5. Every explicit `[source-held: ...]` / equivalent marker remains verbatim in the scene layer.
6. Where a blocked page carries canonical provisional wording instead of an explicit marker, retain that wording exactly and preserve the terminal scan dependency in front matter/provenance.
7. A hold-bearing scene remains non-release-final even though its page-record assembly fidelity has passed.
8. Scan 1 and scan 131 remain outside scene assembly.
9. No Tamil wording is altered by assembly.
10. English translation is a separate later phase requiring explicit authorization.

## Assembly closure

- main scene files: **30 / 30 assembled**;
- supplementary scene files: **3 / 3 assembled**;
- total: **33 / 33**;
- fully verified-input scenes: **13**;
- source-secure shared-boundary scenes: **2**;
- hold-bearing scenes: **18**;
- complete page-to-scene consistency audit: **33 / 33 PASS** in `SCENE_ASSEMBLY_AUDIT.md`;
- contextual repairs: **0**;
- source-wording normalizations: **0**;
- invented unresolved wording: **0**.

## Exact next activity — Tamil pre-release / work-level closure gate

Scene assembly is closed. Do not create a second scene layer and do not begin English translation.

Next:

1. verify the scene-file inventory is exactly main `01–30` plus supplementary `01–03`, with no duplicate/missing files or numbering leakage;
2. verify all 28 terminal physical-page holds remain traceable through page records and, where scene-relevant, through scene files;
3. reconcile stale secondary index labels such as legacy `needs-review` entries with the terminal `blocked` classification without altering canonical page text;
4. run the work-level Tamil release/closure decision under the repository's terminal-source-condition policy;
5. synchronize README / handover / next-chat prompt with that closure outcome;
6. do **not** begin English translation unless explicitly authorized.
