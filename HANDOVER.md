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
9. `works/kagithapoo/LEXICAL_GAP_ADJUDICATION.md`;
10. `works/kagithapoo/PAGE_LAYER_CONSISTENCY_AUDIT.md`;
11. `works/kagithapoo/MD_LEXICAL_RECONCILIATION_0091_0101.md`;
12. relevant closed Tamil `works/kagithapoo/scenes/*.md` artifacts for the current English batch;
13. `works/kagithapoo/indexes/page-map.md` and relevant verified page records only if a source-level question arises.

## Source identity

Controlling PDF: `TVA_PRL_0001638_முரசொலி_ பொங்கல் மலர்_ 1967.pdf`

- SHA-256: `b0a6499ba072a7346f8c2544a8a61c2363d83a60cad5227482008043cd310ec1`;
- size: **45,718,751 bytes**;
- full PDF: **131 scans**;
- selected work range: **91–131 = 41 scans**.

Primary lexical witness for the closed Tamil archival layer: `kaagidha_poo.md`.

## Witness / assembly policy

- MD is the primary lexical witness for the closed Tamil layer.
- PDF controls boundaries, reading order, scene/speaker/paragraph structure, punctuation, brackets, headings/numbers, photographs, captions, boxed features and physical evidence.
- The user explicitly authorized direct PDF lexical fallback only for the five genuine MD omissions on scans **93, 95, 97, 98 and 130**; those gaps are closed in the verified page layer.
- Scene assembly uses only verified page records. Mechanical page/column line breaks may be removed for readability, but wording, punctuation, speaker labels, stage directions and source scene numbering must not be editorially normalized.
- Source-compressed scene representations must not be expanded into invented dialogue.

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

## Final scene assembly artifacts

- `works/kagithapoo/scenes/01.md` — Scene 1, scans 92–93;
- `works/kagithapoo/scenes/02-05.md` — source-compressed representation of `காட்சிகள்: 2, 3, 4, 5.` on scan 93;
- `works/kagithapoo/scenes/06.md` — Scene 6, scans 93–94;
- `works/kagithapoo/scenes/07.md` — Scene 7, scans 94–98;
- `works/kagithapoo/scenes/08.md` — Scene 8, scans 98–102;
- `works/kagithapoo/scenes/09.md` — Scene 9, scan 102;
- `works/kagithapoo/scenes/10.md` — Scene 10, scans 102–104;
- `works/kagithapoo/scenes/11.md` — Scene 11, scans 104–105;
- `works/kagithapoo/scenes/12.md` — Scene 12, scans 105–107;
- `works/kagithapoo/scenes/13.md` — Scene 13, scan 107;
- `works/kagithapoo/scenes/14.md` — Scene 14, scans 107–109;
- `works/kagithapoo/scenes/15.md` — Scene 15, scans 109–110;
- `works/kagithapoo/scenes/16.md` — Scene 16, scans 110–114;
- `works/kagithapoo/scenes/17.md` — Scene 17, scans 114–115;
- `works/kagithapoo/scenes/18.md` — Scene 18, scans 115–116;
- `works/kagithapoo/scenes/19.md` — Scene 19, scan 116;
- `works/kagithapoo/scenes/20.md` — Scene 20, scans 117–119;
- `works/kagithapoo/scenes/21.md` — Scene 21, scans 119–124;
- `works/kagithapoo/scenes/unnumbered-between-21-and-24.md` — source unnumbered `காட்சி,`, scans 124–125;
- `works/kagithapoo/scenes/24.md` — Scene 24, scans 125–129;
- `works/kagithapoo/scenes/25.md` — Scene 25, scan 129;
- `works/kagithapoo/scenes/26.md` — Scene 26, scans 129–130;
- `works/kagithapoo/scenes/27.md` — Scene 27, scans 130–131, closing at `(முற்றும்)`.

## Key assembly safeguards preserved

- scan-98 caption `ஓ. எம். சுப்பிரமணியன்,` remains a separate non-dramatic page element;
- Scene 12 joins `ஒப்ப—` / `டைக்கிறதா` as `ஒப்படைக்கிறதா`;
- Scene 14 joins `வெற்றிகளக் குவிக்கத்—` / `தான் போகிறார்கள் மக்கள்!...` as `வெற்றிகளக் குவிக்கத்தான் போகிறார்கள் மக்கள்!...`;
- Scene 15 joins `வார்த்தை—` / `யைச்` as `வார்த்தையைச்`;
- Scene 16 joins `இய—` / `லாது` as `இயலாது` and preserves the unusual verified scan-112 MD tokens exactly;
- Scene 17 joins Gandhi's speech across scans 114→115 without normalization;
- Scene 18 preserves the verified page-record speaker-label variation across scans 115→116;
- Scene 20 joins the scan-118→119 continuation mechanically;
- Scene 21 joins `நலத்—` / `திட்ட` as `நலத்திட்ட`, `ஆட்சி—` / `மொழிகளாகட்டும்` as `ஆட்சிமொழிகளாகட்டும்`, and joins the 123→124 continuation without lexical normalization;
- the post-Scene-21 source heading is preserved exactly as `காட்சி,`; no Scene 22/23 is assigned;
- Scene 24 joins `முடி` / `யாம` as `முடியாம` and `கொள்` / `ளுங்கள்` as `கொள்ளுங்கள்`; repeated continuation label remains preserved;
- Scene 25 remains source-compressed to its single bracketed campaign-action direction; no body was invented;
- Scene 26 preserves the verified unusual speaker-label sequence exactly;
- Scene 27 retains the three already verified direct-PDF fallback turns from scan 130, keeps the boxed `கண்டுபிடியுங்கள்` outside dramatic reading order, excludes the scan-131 cast/imprint block, and closes at `(முற்றும்)`;
- no scene body has been reconstructed from material absent from the verified page layer.

## English translation phase

**AUTHORIZED / PLAN ESTABLISHED — DRAFTING NOT YET STARTED.**

The user's instruction to proceed after Tamil closure authorizes the separate English-translation phase.

Permanent translation controls:

- immediate drafting authority is the closed verified Tamil scene layer under `works/kagithapoo/scenes/`;
- do not draft from OCR, `kaagidha_poo.md`, the PDF, a modern edition, web text, outside summaries or a secondary English witness;
- source-level questions may consult verified page records / controlling PDF only as adjudication support, without silently reopening the Tamil layer;
- English translation must preserve dramatic structure, speaker identity, stage directions, repetitions, political rhetoric, satire, jokes, slogans, colloquial register, wordplay and supported ambiguity;
- translation choices must never be back-propagated into the locked Tamil archival text;
- no secondary English witness is authorized for drafting or silent correction.

Durable translation records:

- `works/kagithapoo/TRANSLATION_PLAN.md` — artifact mapping, controls, batch plan and review gate;
- `works/kagithapoo/translations/en/README.md` — phase tracker.

Expected English artifact set: **23**, mirroring the Tamil source representation exactly. No `22.md` or `23.md` is permitted. `02-05.md`, the unnumbered block between 21 and 24, and source-compressed Scene 25 remain structurally compressed/unumbered as applicable.

Current English status:

- expected artifacts: **23**;
- present: **0 / 23**;
- reviewed: **0 / 23**;
- secondary-English contamination: **0**.

## Structural safeguards

- scan 124: source heading **`காட்சி,`** with no numeral;
- scan 125: source-visible **`காட்சி 24.`**;
- never invent Scenes 22/23;
- scan 130 boxed `கண்டுபிடியுங்கள்` remains separate from dramatic reading order;
- scan 131 dramatic text closes with `(முற்றும்)`, followed by separate `நாடகத்தில்—பங்கேற்பவர்கள்!` cast/imprint material.

## Exact next activity

Translate and Tamil→English review **Batch 1** from the closed Tamil scene layer only:

1. `scenes/01.md` → `translations/en/01.md`;
2. `scenes/02-05.md` → `translations/en/02-05.md`;
3. `scenes/06.md` → `translations/en/06.md`;
4. `scenes/07.md` → `translations/en/07.md`;
5. `scenes/08.md` → `translations/en/08.md`.

Update `translations/en/README.md`, work README, HANDOVER and NEXT_CHAT_PROMPT after the batch. Do not use OCR, the MD first-pass, PDF, modern edition or secondary English text as drafting authority.

# CLOSED WORK SAFEGUARDS

`மணிமகுடம்` remains complete/closed. `கலைஞரின் நான்மணி மாலை` remains closed. Do not reopen closed work while handling `காகிதப்பூ`.