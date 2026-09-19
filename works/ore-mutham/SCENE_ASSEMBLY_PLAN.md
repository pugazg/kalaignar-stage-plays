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

### Fully verified physical-page inputs — 33 scenes

Main: **1–30**.

Supplementary: **Scenes 1–3**.

These use `status: "assembly-reviewed"`, `assembled_from_verified_pages: true`, `page_record_fidelity: "passed"`, `source_condition_scans: []`.

### Source-secure shared-boundary cases — 0 scenes

None. Scans 72 and 112 are now verified; boundary provenance remains documented but no exception is required.

### Hold-bearing scenes — 0 scenes

None.

## Assembly rules — permanent

1. Scene text comes only from canonical page records; never from memory, OCR expectation, another edition or plot continuity.
2. Preserve source speaker labels, scene/location headings, punctuation, stage directions, historical spelling and source-visible spacing.
3. Shared transition scans are split only at explicit source scene headings.
4. Documented physical page boundaries remain traceable through archival comments; mechanically split words are not silently respelled.
5. Every explicit `[source-held: ...]` / equivalent marker remains verbatim in the scene layer.
6. Where a blocked page carries canonical provisional wording instead of an explicit marker, retain that wording exactly and preserve the terminal scan dependency in front matter/provenance.
7. A hold-bearing scene remains non-release-final even though its page-record assembly fidelity has passed.
8. Scan 1 (now verified) and scan 131 remain outside scene assembly.
9. No Tamil wording is altered by assembly.
10. English translation is a separate later phase requiring explicit authorization.

## Assembly closure

- main scene files: **30 / 30 assembled**;
- supplementary scene files: **3 / 3 assembled**;
- total: **33 / 33**;
- fully verified-input scenes: **33**;
- source-secure shared-boundary scenes: **0**;
- hold-bearing scenes: **0**;
- complete page-to-scene consistency audit: **33 / 33 PASS** in `SCENE_ASSEMBLY_AUDIT.md`;
- contextual repairs: **0**;
- source-wording normalizations: **0**;
- invented unresolved wording: **0**.

## Exact next activity — Tamil pre-release / work-level closure gate

Scene assembly is closed. Do not create a second scene layer and do not begin English translation.

Next:

1. verify the scene-file inventory is exactly main `01–30` plus supplementary `01–03`, with no duplicate/missing files or numbering leakage;
2. verify terminal physical-page hold count is **0** and all page/scene status files agree;
3. confirm all **131 / 131** pages and **33 / 33** scenes are source-secure;
4. retain this plan as a closed historical assembly record;
5. synchronize README / handover / next-chat prompt with that closure outcome;
6. do **not** begin English translation unless explicitly authorized.
