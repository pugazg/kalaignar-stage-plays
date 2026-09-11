# இரத்தக் கண்ணீர் — Scene assembly progress

Status: **IN PROGRESS — Scenes 1–14 / 61 ASSEMBLY-REVIEWED; Scene 15 DRAFT through scan 54; Batches 01–03 PASS**

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

Per user direction, scene assembly now advances by **exactly 10 source scans per iteration**.

This may cut across a scene boundary. In that case:
- do not pull text from the next iteration;
- keep the boundary scene as `draft`;
- resume it from the next ten-scan block;
- only mark the scene `assembly-reviewed` after its full source span is included.

## Durable assembly batches

| Batch | Source scans | Scene result | Status | Review |
|---|---:|---|---|---|
| 01 | 8–29 | Scenes 1–5 reviewed | **PASS / COMPLETE / LOCKED** | `SCENE_ASSEMBLY_BATCH_01_REVIEW.md` |
| 02 | 30–44 | Scenes 6–10 reviewed | **PASS / COMPLETE / LOCKED** | `SCENE_ASSEMBLY_BATCH_02_REVIEW.md` |
| 03 | 45–54 | Scenes 11–14 reviewed; Scene 15 draft through scan 54 | **PASS / ITERATION COMPLETE / CARRY-FORWARD** | `SCENE_ASSEMBLY_BATCH_03_REVIEW.md` |

## Current coverage

- numbered scenes expected: **61**;
- fully assembled/reviewed scene artifacts: **14 / 61**;
- open boundary scene: **Scene 15 draft through scan 54**;
- assembly source scans processed: **8–54**, contiguous;
- completed reviewed-scene coverage: **8–53**, contiguous;
- scan 54 is represented once in the Scene-15 draft and nowhere else;
- duplicate dramatic-page coverage: **0**;
- omitted processed dramatic scans: **0**;
- unresolved assembly discrepancies: **0**.

## Batch 03 mechanical joins

- Scene 12: scan 47→48 `அவள் கண்கள் அடிக்கடி` + `வாயிற் புறத்தை...` joined into one sentence;
- Scene 12: scan 48→49 `நிற்க` / `வில்லை` → `நிற்கவில்லை`;
- Scene 14: scan 52→53 `தோன்றுகிற` / `கிறேன்` → `தோன்றுகிறேன்`;
- Scene 11 and Scene 13 require no lexical page-boundary join;
- Scene 15 is intentionally incomplete after scan 54 and carries forward.

## Next 10-scan assembly iteration

Process **scans 55–64 only**.

Expected source-span effect from the verified page map:
- complete Scene 15 with scans **55–57**;
- assemble Scene 16 from scans **58–62**;
- begin Scene 17 with scans **63–64** and leave it draft because Scene 17 closes on scan 65.

Do not read or assemble scan 65 in that iteration.
