# இரத்தக் கண்ணீர் — Scene assembly progress

Status: **IN PROGRESS — Scenes 1–31 / 61 ASSEMBLY-REVIEWED; Batches 01–08 PASS**

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
| 07 | 85–94 | Scenes 25–27 reviewed | **PASS / COMPLETE / LOCKED** | `SCENE_ASSEMBLY_BATCH_07_REVIEW.md` |
| 08 | 95–104 | Scenes 28–31 reviewed | **PASS / COMPLETE / LOCKED** | `SCENE_ASSEMBLY_BATCH_08_REVIEW.md` |

## Current coverage

- numbered scenes expected: **61**;
- fully assembled/reviewed scene artifacts: **31 / 61**;
- open boundary scene: **none**;
- assembly source scans processed: **8–104**, contiguous;
- completed reviewed-scene coverage: **8–104**, contiguous;
- duplicate dramatic-page coverage: **0**;
- omitted processed dramatic scans: **0**;
- unresolved assembly discrepancies: **0**.

## Batch 08 mechanical joins

- Scene 28: scan 95→96 `வண்டுகளாக` / `வும்` → `வண்டுகளாகவும்`;
- Scene 29: scan 97→98 `அவன் நம்` / `வீட்டில்` joined into one sentence;
- Scene 30: scan 99→100 `தேடித் தந்திருப்பேனே` / `உனக்கு!` joined into one sentence;
- Scene 31: no lexical page-boundary join required.

## Next 10-scan assembly iteration

Process **scans 105–114 only**.

Expected source-span effect from the verified page map:
- Scene 32: scans **105–106**;
- Scene 33: scan **107**;
- Scene 34: scans **108–110**;
- Scene 35: begin with scans **111–114** and leave it draft because Scene 35 closes on scan 115.

Do not read or assemble scan 115 in that iteration.
