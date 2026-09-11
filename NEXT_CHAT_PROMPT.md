# Next Chat Prompt — Kalaignar Stage Plays / இரத்தக் கண்ணீர் fixed 10-scan assembly iteration 95–104

Continue directly in `pugazg/kalaignar-stage-plays`, branch `main`, active work `works/iratha-kanneer/`.

## LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first and preserve newer durable state. Keep all previously closed works closed.

## Closed page layer

- physical scans: **188 / 188**
- canonical / initial verification / H-GATE / final verified: **188 / 188**
- page layer: **COMPLETE / CLOSED FOR CURRENT SOURCE EVIDENCE**
- historical-glyph corrections: **37**
- page-level unresolved / needs-review / blocked: **0 / 0 / 0**

Scene assembly must use the verified page records. Do not reopen page transcription or H-GATE merely for assembly.

## Fixed assembly cadence

User directive: **assemble 10 source scans in each iteration**.

Permanent rule:
1. each iteration consumes exactly the next **10 source scans**;
2. do not extend the batch merely to finish a scene;
3. if scan 10 lands inside a scene, persist that scene as an explicit `draft`;
4. next iteration resumes that draft from the next scan;
5. promote a scene to `assembly-reviewed` only after its full source span is assembled;
6. never pull text from scan 11 of an iteration.

## Durable checkpoint

- Batches 01–07 are durably recorded;
- Scenes **1–27**: `assembly-reviewed`;
- no open draft scene;
- processed assembly scan range: **8–94**, contiguous;
- completed reviewed-scene coverage: **8–94**, contiguous;
- duplicate processed-scan coverage: **0**;
- omitted processed scans: **0**;
- unresolved assembly discrepancies: **0**.

Batch 07 mechanical join:
- Scene 27: 91→92 `அவள் அசை` + `யாமல்` → `அவள் அசையாமல்`.

## Exact next activity — scans 95–104 only

Use only verified page records `0095.md` through `0104.md`.

Expected handling from the verified page map:
- Scene 28: scans **95–96**;
- Scene 29: scans **97–98**;
- Scene 30: scans **99–100**;
- Scene 31: scans **101–104**.

Then create `SCENE_ASSEMBLY_BATCH_08_REVIEW.md`, update `SCENE_ASSEMBLY_PROGRESS.md`, README, HANDOVER and this prompt, and commit durably.

Do not start English translation.
