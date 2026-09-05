# Kalaignar Stage Plays — Handover

Repository: `pugazg/kalaignar-stage-plays`, branch `main`.

## Startup rule

Always fetch live `main` first and preserve newer durable state. Permanent workflow: `STAGE_PLAY_PROCESSING_GUIDE.md`.

# ACTIVE WORK — காகிதப்பூ

## Mandatory startup

Read before any further work:

1. `STAGE_PLAY_PROCESSING_GUIDE.md`;
2. this `HANDOVER.md`;
3. `NEXT_CHAT_PROMPT.md`;
4. `works/kagithapoo/README.md`;
5. `works/kagithapoo/SCENE_ASSEMBLY_PROGRESS.md`;
6. `works/kagithapoo/SCENE_ASSEMBLY_FINAL_REVIEW.md`;
7. `works/kagithapoo/TRANSLATION_PLAN.md`;
8. `works/kagithapoo/translations/en/README.md`;
9. completed English batch review records: `BATCH_01_REVIEW.md` and `BATCH_02_REVIEW.md`;
10. relevant closed Tamil `works/kagithapoo/scenes/*.md` artifacts for the current English batch;
11. `works/kagithapoo/PAGE_LAYER_CONSISTENCY_AUDIT.md` and verified page records only if a source-level question arises.

## Source identity

Controlling PDF: `TVA_PRL_0001638_முரசொலி_ பொங்கல் மலர்_ 1967.pdf`

- SHA-256: `b0a6499ba072a7346f8c2544a8a61c2363d83a60cad5227482008043cd310ec1`;
- size: **45,718,751 bytes**;
- full PDF: **131 scans**;
- selected work range: **91–131 = 41 scans**.

Primary lexical witness for the closed Tamil archival layer: `kaagidha_poo.md`.

## Durable Tamil archival state

**TAMIL ARCHIVAL LAYER COMPLETE / CLOSED.**

Page layer:

- processed: **41 / 41**;
- verified: **41 / 41**;
- `needs-review`: **0**;
- final consistency audit: **PASS**.

Scene assembly:

- status: **COMPLETE / CLOSED**;
- expected source-representation artifacts: **23 / 23 present**;
- unresolved assembly gaps: **0**;
- final scene-assembly consistency review: **PASS** in `works/kagithapoo/SCENE_ASSEMBLY_FINAL_REVIEW.md`.

Final source-representation sequence remains:

- Scene 1;
- source-compressed Scenes 2–5;
- Scenes 6–21;
- source-visible unnumbered `காட்சி,` between 21 and 24;
- Scenes 24–27.

There is no Scene 22/23 artifact because the source does not print those scene numbers.

## Permanent Tamil safeguards

- MD is the primary lexical witness for the closed Tamil layer; PDF controls physical structure and source evidence.
- Direct PDF lexical fallback remains limited to the five previously user-authorized MD omissions on scans **93, 95, 97, 98 and 130**.
- Scene assembly uses only verified page records; only mechanical page/column joins were made.
- Source wording, punctuation, speaker labels, stage directions and numbering were not silently normalized.
- Source-compressed scene bodies were not invented.
- scan 98 caption `ஓ. எம். சுப்பிரமணியன்,` remains separate from dramatic Scene 8 flow.
- scan 124 heading remains exactly `காட்சி,`; scan 125 resumes at `காட்சி 24.`; never invent Scenes 22/23.
- Scene 25 remains source-compressed action only.
- Scene 27 retains the three verified scan-130 PDF-fallback turns, excludes boxed `கண்டுபிடியுங்கள்`, excludes scan-131 cast/imprint material, and closes exactly at `(முற்றும்)`.

Key mechanical joins already locked in the Tamil scene layer include:

- Scene 12: `ஒப்ப—` / `டைக்கிறதா` → `ஒப்படைக்கிறதா`;
- Scene 14: `வெற்றிகளக் குவிக்கத்—` / `தான் போகிறார்கள் மக்கள்!...` → `வெற்றிகளக் குவிக்கத்தான் போகிறார்கள் மக்கள்!...`;
- Scene 15: `வார்த்தை—` / `யைச்` → `வார்த்தையைச்`;
- Scene 16: `இய—` / `லாது` → `இயலாது`;
- Scene 21: `நலத்—` / `திட்ட` → `நலத்திட்ட`, `ஆட்சி—` / `மொழிகளாகட்டும்` → `ஆட்சிமொழிகளாகட்டும்`;
- Scene 24: `முடி` / `யாம` → `முடியாம`, `கொள்` / `ளுங்கள்` → `கொள்ளுங்கள்`.

## English translation phase

**AUTHORIZED / IN PROGRESS — BATCHES 1–2 COMPLETE / PASS / LOCKED.**

Immediate drafting authority is the closed verified Tamil scene layer under `works/kagithapoo/scenes/`.

Permanent translation controls:

- do not draft from OCR, `kaagidha_poo.md`, the PDF, a modern edition, web text, outside summaries or a secondary English witness;
- source-level questions may consult verified page records / controlling PDF only as adjudication support, without silently reopening the Tamil layer;
- preserve dramatic structure, source compression, speaker identity, stage directions, repetitions, political rhetoric, satire, jokes, slogans, colloquial register, wordplay and supported ambiguity;
- translation choices must never be back-propagated into the locked Tamil archival text;
- no secondary English witness is authorized for drafting or silent correction.

Durable translation records:

- `works/kagithapoo/TRANSLATION_PLAN.md` — artifact mapping, controls, batch plan and review gate;
- `works/kagithapoo/translations/en/README.md` — live English-phase tracker;
- `works/kagithapoo/translations/en/BATCH_01_REVIEW.md` — **PASS / LOCKED**;
- `works/kagithapoo/translations/en/BATCH_02_REVIEW.md` — **PASS / LOCKED**.

Expected English artifact set: **23**, mirroring the Tamil source representation exactly. No `22.md` or `23.md` is permitted.

### Completed Batches 1–2

Completed and Tamil→English reviewed:

1. `translations/en/01.md` ← `scenes/01.md`;
2. `translations/en/02-05.md` ← source-compressed `scenes/02-05.md`;
3. `translations/en/06.md` ← `scenes/06.md`;
4. `translations/en/07.md` ← `scenes/07.md`;
5. `translations/en/08.md` ← `scenes/08.md`;
6. `translations/en/09.md` ← `scenes/09.md`;
7. `translations/en/10.md` ← `scenes/10.md`;
8. `translations/en/11.md` ← `scenes/11.md`;
9. `translations/en/12.md` ← `scenes/12.md`;
10. `translations/en/13.md` ← `scenes/13.md`.

Current English status:

- expected artifacts: **23**;
- present: **10 / 23**;
- reviewed: **10 / 23**;
- completed batches: **2 / 5**;
- unresolved blocking translation issues: **0**;
- secondary-English contamination: **0**.

Stable terminology and source-sensitive choices through Batch 2 are recorded in `translations/en/README.md` and the two batch-review files. Important retained source-sensitive forms include Scene 6 `அந்சு ... சொம்பு வீரமாதம்`, Scene 10 `பூச்ண`, Scene 12 `அங்கவனும்—பவனும்` / `புள்ள குட்டி`, and the documented anomalous Scene-12 `விந்து` repetition. None is a reopened Tamil correction.

## Exact next activity — English Batch 3

Translate and Tamil→English review, in order:

1. `scenes/14.md` → `translations/en/14.md`;
2. `scenes/15.md` → `translations/en/15.md`;
3. `scenes/16.md` → `translations/en/16.md`;
4. `scenes/17.md` → `translations/en/17.md`;
5. `scenes/18.md` → `translations/en/18.md`.

For each file, draft only from the closed Tamil scene artifact, then compare the full English artifact back against the Tamil scene before setting `translation-reviewed` / `passed`. Update the English tracker, work README, HANDOVER and NEXT_CHAT_PROMPT after the batch.

# CLOSED WORK SAFEGUARDS

`மணிமகுடம்` remains complete/closed. `கலைஞரின் நான்மணி மாலை` remains closed. Do not reopen closed work while handling `காகிதப்பூ`.