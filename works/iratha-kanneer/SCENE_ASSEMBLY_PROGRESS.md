# இரத்தக் கண்ணீர் — Scene assembly progress

Status: **IN PROGRESS — Scenes 1–36 / 61 ASSEMBLY-REVIEWED; Scene 37 DRAFT through scan 124; Batches 01–09 PASS**

Page-layer authority: **188 / 188 final verified / CLOSED FOR CURRENT SOURCE EVIDENCE**.

## Assembly rules

1. Assemble only from final verified `pages/*.md` records.
2. Do not reopen source transcription or H-GATE during assembly.
3. Mechanical physical-page interruptions may be removed only when the verified page records prove a direct continuation.
4. Do not alter lexical wording, punctuation, speaker labels, stage directions, repetitions, old/source forms or scene numbering.
5. Preserve source-proven scene headings and closing markers.
6. Reviewed scene artifacts use `status: "assembly-reviewed"`, `assembled_from_verified_pages: true`, and `page_record_fidelity: "passed"`.
7. If a fixed iteration ends inside a scene, persist only the covered verified scans as a clearly marked `draft` scene artifact; complete and promote that scene only in the next iteration.
8. Keep front matter, scan 186 `முடிவு`, scan 187 catalogue and scan 188 wrapper outside the numbered scene layer.
9. English translation remains not authorized / not started.

## Fixed assembly iteration size

Per user direction, scene assembly now advances by **exactly 20 source scans per iteration**.

If the twentieth scan lands inside a scene:
- do not pull text from the next scan;
- keep the boundary scene as `draft`;
- resume it from the next twenty-scan block;
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
| 07 | 85–94 | Scenes 25–27 reviewed | **PASS / COMPLETE / LOCKED** | `SCENE_ASSEMBLY_BATCH_07_REVIEW.md` |
| 08 | 95–104 | Scenes 28–31 reviewed | **PASS / COMPLETE / LOCKED** | `SCENE_ASSEMBLY_BATCH_08_REVIEW.md` |
| 09 | 105–124 | Scenes 32–36 reviewed; Scene 37 draft through scan 124 | **PASS / ITERATION COMPLETE / CARRY-FORWARD** | `SCENE_ASSEMBLY_BATCH_09_REVIEW.md` |

## Current coverage

- numbered scenes expected: **61**;
- fully assembled/reviewed scene artifacts: **36 / 61**;
- open boundary scene: **Scene 37 draft through scan 124**;
- assembly source scans processed: **8–124**, contiguous;
- completed reviewed-scene coverage: **8–122**, contiguous;
- scans **123–124** are represented once in the Scene-37 draft and nowhere else;
- duplicate dramatic-page coverage: **0**;
- omitted processed dramatic scans: **0**;
- unresolved assembly discrepancies: **0**.

## Batch 09 mechanical joins

- Scene 35: 111→112 `இப்போது,` + `சுகதேவன்...`;
- Scene 35: 112→113 `முத்தன்` + `அடைக்கப்பட்டிருக்கிறான்.`;
- Scene 35: 113→114 `உன்பால்` + `எனக்கு அன்பு ஏற்பட்டது.`;
- Scene 36: 117→118 `எந்த அழகுக்` + `காகத்` → `எந்த அழகுக்காகத்`;
- Scene 36 preserves scan-116 internal `* * *` as an internal transition;
- Scene 37 is intentionally incomplete after scan 124.

## Next 20-scan assembly iteration

Process **scans 125–144 only**.

Expected source-span effect from the verified page map:
- complete Scene 37 with scans **125–131**;
- Scene 38: scans **132–133**;
- Scene 39: scans **134–135**;
- Scene 40: scan **136**;
- Scene 41: scans **137–139**;
- Scene 42: scans **140–141**;
- Scene 43: scans **142–143**;
- begin Scene 44 with scan **144** only and leave it draft because Scene 44 closes on scan 145.

Do not read or assemble scan 145 in that iteration.
