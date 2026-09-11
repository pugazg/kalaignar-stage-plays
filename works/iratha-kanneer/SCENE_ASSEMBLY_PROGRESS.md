# இரத்தக் கண்ணீர் — Scene assembly progress

Status: **IN PROGRESS — Scenes 1–19 / 61 ASSEMBLY-REVIEWED; Scene 20 DRAFT through scan 74; Batches 01–05 PASS**

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

## Current coverage

- numbered scenes expected: **61**;
- fully assembled/reviewed scene artifacts: **19 / 61**;
- open boundary scene: **Scene 20 draft through scan 74**;
- assembly source scans processed: **8–74**, contiguous;
- completed reviewed-scene coverage: **8–68**, contiguous;
- scans **69–74** are represented once in the Scene-20 draft and nowhere else;
- duplicate dramatic-page coverage: **0**;
- omitted processed dramatic scans: **0**;
- unresolved assembly discrepancies: **0**.

## Batch 05 mechanical joins

- Scene 17: scan 64→65 continues between complete speaker turns; no lexical join required;
- Scene 18: scan 66→67 `பாளையக்காரருக்கு` / `அதிகாரமில்லை.` joined as one sentence;
- Scene 19 is a one-page scene;
- Scene 20: scan 72→73 `வேண்` / `டியவள்` → `வேண்டியவள்`;
- Scene 20: scan 73→74 sentence continuation `அப்படியானால்` / `இந்த ஆடும் மார்கழியில்...` joined into one paragraph;
- Scene 20 is intentionally incomplete after scan 74 and carries forward.

## Next 10-scan assembly iteration

Process **scans 75–84 only**.

Expected source-span effect from the verified page map:
- complete Scene 20 with scan **75**;
- assemble Scene 21 from scans **76–80**;
- assemble Scene 22 from scan **81**;
- assemble Scene 23 from scans **82–83**;
- assemble Scene 24 from scan **84**.

This iteration should close all five scenes with no carry-forward if the verified page map remains authoritative.
