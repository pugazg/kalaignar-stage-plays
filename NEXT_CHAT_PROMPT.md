# Next Chat Prompt — Kalaignar Stage Plays / இரத்தக் கண்ணீர் fixed 10-scan assembly iteration 105–114

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

- Batches 01–08 are durably recorded;
- Scenes **1–31**: `assembly-reviewed`;
- no open draft scene;
- processed assembly scan range: **8–104**, contiguous;
- completed reviewed-scene coverage: **8–104**, contiguous;
- duplicate processed-scan coverage: **0**;
- omitted processed scans: **0**;
- unresolved assembly discrepancies: **0**.

Batch 08 mechanical joins:
- Scene 28: 95→96 `வண்டுகளாக` + `வும்` → `வண்டுகளாகவும்`;
- Scene 29: 97→98 sentence continuation `அவன் நம்` + `வீட்டில்`;
- Scene 30: 99→100 `தேடித் தந்திருப்பேனே` + `உனக்கு!` joined into one sentence.

## Exact next activity — scans 105–114 only

Use only verified page records `0105.md` through `0114.md`.

Expected handling from the verified page map:
- Scene 32: scans **105–106**;
- Scene 33: scan **107**;
- Scene 34: scans **108–110**;
- Scene 35: assemble scans **111–114** only into a `draft`; Scene 35 closes on scan 115, so **do not include scan 115**.

Then create `SCENE_ASSEMBLY_BATCH_09_REVIEW.md`, update `SCENE_ASSEMBLY_PROGRESS.md`, README, HANDOVER and this prompt, and commit durably.

Do not start English translation.
