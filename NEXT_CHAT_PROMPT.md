# Next Chat Prompt — Kalaignar Stage Plays / இரத்தக் கண்ணீர் fixed 10-scan assembly iteration 75–84

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

- Batches 01–05 are durably recorded;
- Scenes **1–19**: `assembly-reviewed`;
- Scene **20**: `scenes/20.md` is `draft` through scans **69–74** only;
- processed assembly scan range: **8–74**, contiguous;
- completed reviewed-scene coverage: **8–68**, contiguous;
- duplicate processed-scan coverage: **0**;
- omitted processed scans: **0**;
- unresolved assembly discrepancies: **0**.

Batch 05 mechanical joins:
- Scene 18: 66→67 `பாளையக்காரருக்கு` + `அதிகாரமில்லை.`;
- Scene 20: 72→73 `வேண்` + `டியவள்` → `வேண்டியவள்`;
- Scene 20: 73→74 sentence continuation joined into one paragraph.

## Exact next activity — scans 75–84 only

Use only verified page records `0075.md` through `0084.md`.

Expected handling from the verified page map:

- Scene 20: append scan **75**, resolve only page-record-proven continuation if any, then promote `scenes/20.md` to `assembly-reviewed`;
- Scene 21: assemble scans **76–80** completely;
- Scene 22: assemble scan **81** completely;
- Scene 23: assemble scans **82–83** completely;
- Scene 24: assemble scan **84** completely.

Then create `SCENE_ASSEMBLY_BATCH_06_REVIEW.md`, update `SCENE_ASSEMBLY_PROGRESS.md`, README, HANDOVER and this prompt, and commit durably.

Do not start English translation.
