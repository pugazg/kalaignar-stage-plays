# Next Chat Prompt — Kalaignar Stage Plays / இரத்தக் கண்ணீர் fixed 10-scan assembly iteration 65–74

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

- Batches 01–04 are durably recorded;
- Scenes **1–16**: `assembly-reviewed`;
- Scene **17**: `scenes/17.md` is `draft` through scans **63–64** only;
- processed assembly scan range: **8–64**, contiguous;
- completed reviewed-scene coverage: **8–62**, contiguous;
- duplicate processed-scan coverage: **0**;
- omitted processed scans: **0**;
- unresolved assembly discrepancies: **0**.

Batch 04 mechanical joins:
- Scene 15: 54→55 `எதைக் குறிக்` + `கின்றன—` → `எதைக் குறிக்கின்றன—`;
- Scene 15: 56→57 `நீயே மரண` + `படும்போது` → `நீயே மரணப்படும்போது`;
- Scene 16: 60→61 `உன்னால் நடத்த` + `முடியுமா` → `உன்னால் நடத்த முடியுமா`.

## Exact next activity — scans 65–74 only

Use only verified page records `0065.md` through `0074.md`.

Expected handling from the verified page map:

- Scene 17: append scan **65**, resolve only page-record-proven continuation if any, then promote `scenes/17.md` to `assembly-reviewed`;
- Scene 18: assemble scans **66–67** completely;
- Scene 19: assemble scan **68** completely;
- Scene 20: assemble scans **69–74** only into `scenes/20.md` as a `draft`; Scene 20 closes on scan 75, so **do not include scan 75**.

Then create `SCENE_ASSEMBLY_BATCH_05_REVIEW.md`, update `SCENE_ASSEMBLY_PROGRESS.md`, README, HANDOVER and this prompt, and commit durably.

Do not start English translation.
