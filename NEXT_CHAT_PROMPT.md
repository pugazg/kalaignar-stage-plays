# Next Chat Prompt — Kalaignar Stage Plays / இரத்தக் கண்ணீர் fixed 20-scan assembly iteration 145–164

Continue directly in `pugazg/kalaignar-stage-plays`, branch `main`, active work `works/iratha-kanneer/`.

## LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first and preserve newer durable state. Keep all previously closed works closed.

## Closed page layer

- physical scans: **188 / 188**
- canonical / initial verification / H-GATE / final verified: **188 / 188**
- page layer: **COMPLETE / CLOSED FOR CURRENT SOURCE EVIDENCE**
- historical-glyph corrections: **37**
- page-level unresolved / needs-review / blocked: **0 / 0 / 0**

Scene assembly must use only the verified page records. Do not reopen page transcription or H-GATE merely for assembly.

## Fixed assembly cadence

Latest user directive: **process 20 source scans in each iteration**.

Permanent rule:
1. each iteration consumes exactly the next **20 source scans**;
2. do not extend the batch merely to finish a scene;
3. if scan 20 lands inside a scene, persist that scene as an explicit `draft`;
4. next iteration resumes that draft from the next scan;
5. promote a scene to `assembly-reviewed` only after its full source span is assembled;
6. never pull text from scan 21 of an iteration.

## Durable checkpoint

- Scene Assembly Batches 01–10 are durably recorded;
- Scenes **1–43**: `assembly-reviewed`;
- Scene **44**: `scenes/44.md` is `draft` through scan **144** only;
- processed assembly scan range: **8–144**, contiguous;
- completed reviewed-scene coverage: **8–143**, contiguous;
- duplicate processed-scan coverage: **0**;
- omitted processed scans: **0**;
- unresolved assembly discrepancies: **0**.

Batch 10 key handling:
- Scene 37: 130→131 `புறப்` + `படுகின்றனர்.` → `புறப்படுகின்றனர்.`;
- Scene 38: 132→133 `பள்ளி` + `யறைக்` → `பள்ளியறைக்`;
- Scene 39: 134→135 sentence continuation;
- Scene 41 preserves `கண்ணை மறைக்கும் பேய்`;
- Scene 42 preserves scan-141 internal `★ ★ ★` as an internal transition;
- Scene 44 contains scan 144 only and is still open.

## Exact next activity — scans 145–164 only

Use only verified page records `0145.md` through `0164.md`.

Expected handling from the verified page map:
- complete Scene 44 with scan **145**;
- Scene 45: scans **146–148**;
- Scene 46: scans **149–150**;
- Scene 47: scans **151–152**;
- Scene 48: scan **153**;
- Scene 49: scans **154–155**;
- Scene 50: scans **156–157**;
- Scene 51: scan **158**;
- Scene 52: scan **159**;
- Scene 53: scan **160**;
- Scene 54: scan **161**;
- Scene 55: scans **162–163**;
- Scene 56: scan **164**.

Then create `SCENE_ASSEMBLY_BATCH_11_REVIEW.md`, update `SCENE_ASSEMBLY_PROGRESS.md`, README, HANDOVER and this prompt, and commit durably.

Do not start English translation.
