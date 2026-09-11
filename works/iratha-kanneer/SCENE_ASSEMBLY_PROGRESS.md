# இரத்தக் கண்ணீர் — Scene assembly progress

Status: **IN PROGRESS — Scenes 1–24 / 61 ASSEMBLY-REVIEWED; Batches 01–06 PASS**

Page-layer authority: **188 / 188 final verified / CLOSED FOR CURRENT SOURCE EVIDENCE**.

## Assembly rules

1. Assemble only from final verified `pages/*.md` records.
2. Do not reopen source transcription or H-GATE during assembly.
3. Mechanical physical-page interruptions may be removed only when the verified page records prove a direct continuation.
4. Do not alter lexical wording, punctuation, speaker labels, stage directions, repetitions, old/source forms or scene numbering.
5. Preserve source-proven scene headings and closing markers.
6. Reviewed scene artifacts use `status: "assembly-reviewed"`, `assembled_from_verified_pages: true`, and `page_record_fidelity: "passed"`.
7. If a fixed ten-scan iteration ends inside a scene, persist only the covered verified scans as a clearly marked `draft` scene artifact; complete and promote that scene only in the next iteration.
8. Keep front matter, scan 186 `முடிவு`, scan 187 catalogue and scan 188 wrapper outside the numbered scene layer.
9. English translation remains not authorized / not started.

## Fixed assembly iteration size

Per user direction, scene assembly advances by **exactly 10 source scans per iteration**.

If the tenth scan lands inside a scene:
- do not pull text from the next scan;
- keep the boundary scene as `draft`;
- resume it from the next ten-scan block;
- only mark the scene `assembly-reviewed` after its full source span is included.

## Durable assembly batches

| Batch | Source scans | Scene result | Status | Review |
|---|---:|---|---|---|
| 01 | 8–29 | Scenes 1–5 reviewed | **PASS / COMPLETE / LOCKED** | `SCENE_ASSEMBLY_BATCH_01_REVIEW.md` |
| 02 | 30–44 | Scenes 6–10 reviewed | **PASS / COMPLETE / LOCKED** | `SCENE_ASSEMBLY_BATCH_02_REVIEW.md` |
| 03 | 45–54 | Scenes 11–14 reviewed; Scene 15 draft through scan 54 | **PASS / ITERATION COMPLETE / CARRY-FORWARD** | `SCENE_ASSEMBLY_BATCH_03_REVIEW.md` |
| 04 | 55–64 | Scene 15 completed; Scene 16 reviewed; Scene 17 draft through scan 64 | **PASS / ITERATION COMPLETE / CARRY-FORWARD** | `SCENE_ASSEMBLY_BATCH_04_REVIEW.md` |
| 05 | 65–74 | Scene 17 completed; Scenes 18–19 reviewed; Scene 20 draft through scan 74 | **PASS / ITERATION COMPLETE / CARRY-FORWARD** | `SCENE_ASSEMBLY_BATCH_05_REVIEW.md` |
| 06 | 75–84 | Scene 20 completed; Scenes 21–24 reviewed | **PASS / COMPLETE / LOCKED** | `SCENE_ASSEMBLY_BATCH_06_REVIEW.md` |

## Current coverage

- numbered scenes expected: **61**;
- fully assembled/reviewed scene artifacts: **24 / 61**;
- open boundary scene: **none**;
- assembly source scans processed: **8–84**, contiguous;
- completed reviewed-scene coverage: **8–84**, contiguous;
- duplicate dramatic-page coverage: **0**;
- omitted processed dramatic scans: **0**;
- unresolved assembly discrepancies: **0**.

## Batch 06 mechanical joins

- Scene 20: scan 74→75 `பூட்டி வைத்` / `திருக்கிறார்.` → `பூட்டி வைத்திருக்கிறார்.`;
- Scene 21: no lexical page-boundary join required;
- Scene 22 and Scene 24 are one-page scenes;
- Scene 23: scan 82→83 `சேர்ந்` / `துள்ள` → `சேர்ந்துள்ள`.

## Next 10-scan assembly iteration

Process **scans 85–94 only**.

Expected source-span effect from the verified page map:
- Scene 25: scans **85–88**;
- Scene 26: scans **89–90**;
- Scene 27: scans **91–94**.

This iteration should close all three scenes with no carry-forward if the verified page map remains authoritative.
