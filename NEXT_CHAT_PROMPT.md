# Next Chat Prompt — Kalaignar Stage Plays / இரத்தக் கண்ணீர் fixed 10-scan assembly iteration 85–94

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

- Batches 01–06 are durably recorded;
- Scenes **1–24**: `assembly-reviewed`;
- no open draft scene;
- processed assembly scan range: **8–84**, contiguous;
- completed reviewed-scene coverage: **8–84**, contiguous;
- duplicate processed-scan coverage: **0**;
- omitted processed scans: **0**;
- unresolved assembly discrepancies: **0**.

Batch 06 mechanical joins:
- Scene 20: 74→75 `பூட்டி வைத்` + `திருக்கிறார்.` → `பூட்டி வைத்திருக்கிறார்.`;
- Scene 23: 82→83 `சேர்ந்` + `துள்ள` → `சேர்ந்துள்ள`.

## Exact next activity — scans 85–94 only

Use only verified page records `0085.md` through `0094.md`.

Expected handling from the verified page map:

- Scene 25: assemble scans **85–88** completely;
- Scene 26: assemble scans **89–90** completely;
- Scene 27: assemble scans **91–94** completely.

Then create `SCENE_ASSEMBLY_BATCH_07_REVIEW.md`, update `SCENE_ASSEMBLY_PROGRESS.md`, README, HANDOVER and this prompt, and commit durably.

Do not start English translation.
