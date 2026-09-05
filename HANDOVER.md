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
6. `works/kagithapoo/LEXICAL_GAP_ADJUDICATION.md`;
7. `works/kagithapoo/PAGE_LAYER_CONSISTENCY_AUDIT.md`;
8. `works/kagithapoo/MD_LEXICAL_RECONCILIATION_0091_0101.md`;
9. `works/kagithapoo/indexes/page-map.md` and relevant verified page records.

## Source identity

Controlling PDF: `TVA_PRL_0001638_முரசொலி_ பொங்கல் மலர்_ 1967.pdf`

- SHA-256: `b0a6499ba072a7346f8c2544a8a61c2363d83a60cad5227482008043cd310ec1`;
- size: **45,718,751 bytes**;
- full PDF: **131 scans**;
- selected work range: **91–131 = 41 scans**.

Primary lexical witness: `kaagidha_poo.md`.

## Witness / assembly policy

- MD is the primary lexical witness.
- PDF controls boundaries, reading order, scene/speaker/paragraph structure, punctuation, brackets, headings/numbers, photographs, captions, boxed features and physical evidence.
- The user explicitly authorized direct PDF lexical fallback only for the five genuine MD omissions on scans **93, 95, 97, 98 and 130**; those gaps are closed in the verified page layer.
- Scene assembly uses only verified page records. Mechanical page/column line breaks may be removed for readability, but wording, punctuation, speaker labels, stage directions and source scene numbering must not be editorially normalized.
- The source-compressed `காட்சிகள்: 2, 3, 4, 5.` block must not be expanded into invented dialogue.

## Durable page-layer state

**PAGE LAYER COMPLETE / CLOSED.**

- processed: **41 / 41**;
- verified: **41 / 41**;
- `needs-review`: **0**;
- final consistency audit: **PASS**.

## Durable scene-assembly state

**SCENE ASSEMBLY AUTHORIZED / IN PROGRESS.**

Committed assembly-reviewed files:

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
- `works/kagithapoo/scenes/21.md` — Scene 21, scans 119–124.

Assembly notes:

- scan-98 caption `ஓ. எம். சுப்பிரமணியன்,` remains a separate non-dramatic page element;
- Scene 12 joins `ஒப்ப—` / `டைக்கிறதா` as `ஒப்படைக்கிறதா`;
- Scene 14 joins `வெற்றிகளக் குவிக்கத்—` / `தான் போகிறார்கள் மக்கள்!...` as `வெற்றிகளக் குவிக்கத்தான் போகிறார்கள் மக்கள்!...`;
- Scene 15 joins `வார்த்தை—` / `யைச்` as `வார்த்தையைச்`;
- Scene 16 joins `இய—` / `லாது` as `இயலாது` and preserves the unusual verified scan-112 MD tokens exactly;
- Scene 17 joins Gandhi's speech across scans 114→115 without normalization;
- Scene 18 preserves the verified page-record speaker-label variation across scans 115→116;
- Scene 19 is a complete single-scan scene;
- Scene 20 joins the scan-118→119 sentence continuation `நீங்கள் சிந்திய ரத்தம் கூட—` / `உங்கள் மகன்...` mechanically and closes before Scene 21;
- Scene 21 joins `நலத்—` / `திட்ட` as `நலத்திட்ட`, `ஆட்சி—` / `மொழிகளாகட்டும்` as `ஆட்சிமொழிகளாகட்டும்`, and joins the 123→124 sentence continuation without lexical normalization;
- unusual verified page-record wording in Scene 21 remains unchanged rather than being modernized;
- no scene body has been reconstructed from material absent from the verified page layer.

Tracking: `works/kagithapoo/SCENE_ASSEMBLY_PROGRESS.md`.

English translation: **not started / not authorized**.

## Structural safeguards

- scan 124: source heading **`காட்சி,`** with no numeral;
- scan 125: source-visible **`காட்சி 24.`**;
- never invent Scenes 22/23;
- scan 130 boxed `கண்டுபிடியுங்கள்` remains separate from dramatic reading order;
- scan 131 closes with `(முற்றும்)` and then `நாடகத்தில்—பங்கேற்பவர்கள்!`.

## Exact next activity

Assemble and page-record-check the **unnumbered source `காட்சி,`** from verified scans **124–125**, preserving the heading exactly and assigning no Scene 22/23 number. Then continue with **Scene 24** unless the user specifies a different batch size. Update `SCENE_ASSEMBLY_PROGRESS.md`, README, HANDOVER and NEXT_CHAT_PROMPT at the next substantial checkpoint.

Do not begin English translation without separate authorization.

# CLOSED WORK SAFEGUARDS

`மணிமகுடம்` remains complete/closed. `கலைஞரின் நான்மணி மாலை` remains closed. Do not reopen closed work while handling `காகிதப்பூ`.