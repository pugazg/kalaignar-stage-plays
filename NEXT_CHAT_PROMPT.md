# Next Chat Prompt — Kalaignar Stage Plays / இரத்தக் கண்ணீர் fixed 20-scan assembly iteration 125–144

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

Latest user directive: **process 20 source scans in each iteration**.

This supersedes the earlier 10-scan cadence.

Permanent rule:
1. each iteration consumes exactly the next **20 source scans**;
2. do not extend the batch merely to finish a scene;
3. if scan 20 lands inside a scene, persist that scene as an explicit `draft`;
4. next iteration resumes that draft from the next scan;
5. promote a scene to `assembly-reviewed` only after its full source span is assembled;
6. never pull text from scan 21 of an iteration.

## Durable checkpoint

- Scene Assembly Batches 01–09 are durably recorded;
- Scenes **1–36**: `assembly-reviewed`;
- Scene **37**: `scenes/37.md` is `draft` through scans **123–124** only;
- processed assembly scan range: **8–124**, contiguous;
- completed reviewed-scene coverage: **8–122**, contiguous;
- duplicate processed-scan coverage: **0**;
- omitted processed scans: **0**;
- unresolved assembly discrepancies: **0**.

Batch 09 processed exactly scans **105–124** and established the new 20-scan cadence.

Key Batch-09 mechanical joins:
- Scene 35: 111→112 `இப்போது,` + `சுகதேவன்...`;
- Scene 35: 112→113 `முத்தன்` + `அடைக்கப்பட்டிருக்கிறான்.`;
- Scene 35: 113→114 `உன்பால்` + `எனக்கு அன்பு ஏற்பட்டது.`;
- Scene 36: 117→118 `எந்த அழகுக்` + `காகத்` → `எந்த அழகுக்காகத்`.

## Exact next activity — scans 125–144 only

Use only verified page records `0125.md` through `0144.md`.

Expected handling from the verified page map:
- complete Scene 37 with scans **125–131**;
- Scene 38: scans **132–133**;
- Scene 39: scans **134–135**;
- Scene 40: scan **136**;
- Scene 41: scans **137–139**;
- Scene 42: scans **140–141**;
- Scene 43: scans **142–143**;
- Scene 44: assemble scan **144** only as a `draft`; Scene 44 closes on scan 145, so **do not include scan 145**.

Then create `SCENE_ASSEMBLY_BATCH_10_REVIEW.md`, update `SCENE_ASSEMBLY_PROGRESS.md`, README, HANDOVER and this prompt, and commit durably.

Do not start English translation.
