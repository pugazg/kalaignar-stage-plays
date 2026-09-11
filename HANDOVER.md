# Kalaignar Stage Plays — Handover

Repository: `pugazg/kalaignar-stage-plays`, branch `main`.

## Startup rule

Always fetch live `main` first and preserve newer durable state.

Permanent source-first workflow: `STAGE_PLAY_PROCESSING_GUIDE.md`.

Historical-type authority:

1. `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`;
2. `HISTORICAL_TAMIL_GLYPH_GATE.md`.

Active-work anti-loop authority: `works/iratha-kanneer/BATCH_EXECUTION_WORKFLOW.md`.

# CURRENT CHECKPOINT — இரத்தக் கண்ணீர் PAGE LAYER CLOSED / SCENE ASSEMBLY 5 OF 61

Active work: `works/iratha-kanneer/`.

Controlling source: `TVA_BOK_0064189_இரத்தக்_கண்ணீர்.pdf`.

Source provenance: the user-supplied controlling PDF was downloaded from the **Tamil Digital Library (TDL)**. The TDL catalogue and Wikisource transport copy refer to this same scan set; they are **not independent secondary textual witnesses**. When the exact PDF is attached/readable locally, routine transcription and verification must use the local controlling PDF directly.

Current durable state:

- P0 source intake: **PASS**;
- physical scans: **188 / 188 confirmed**;
- canonical page transcription: **188 / 188**;
- initial visual verification: **188 / 188**;
- historical-glyph H-GATE: **188 / 188**;
- final verified pages: **188 / 188**;
- contiguous final-verified range: **scans 1–188**;
- Batches 01–19: **PASS / COMPLETE**;
- Batch 19: **PASS / COMPLETE / LOCKED FOR CURRENT SOURCE EVIDENCE**;
- Batch-17 Pass-A durable commit: **`d951cdfc913b375d0c99a3c602a0a0743ef5d091`**;
- earlier Batch-17 checkpoint commit: **`eadec47b4014962ddb4323b18f0d428b051f5b78`**;
- historical-glyph corrections recorded: **37**;
- unresolved page-level source issues: **0**;
- `needs-review`: **0**;
- `blocked`: **0**;
- structural / scene assembly: **IN PROGRESS — Scenes 1–5 / 61 assembly-reviewed; Scene Assembly Batch 01 PASS**;
- English translation: **not authorized / not started**.

The conversation preview exposes only 150 images; direct raw-PDF inspection established **188 physical scans**. Never stop at preview page 150.

## Mandatory startup

Read completely before source-dependent work:

1. `STAGE_PLAY_PROCESSING_GUIDE.md`;
2. `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`;
3. `HISTORICAL_TAMIL_GLYPH_GATE.md`;
4. this `HANDOVER.md`;
5. `NEXT_CHAT_PROMPT.md`;
6. `works/iratha-kanneer/BATCH_EXECUTION_WORKFLOW.md`;
7. `works/iratha-kanneer/README.md`;
8. `works/iratha-kanneer/metadata/source.md`;
9. `works/iratha-kanneer/indexes/page-map.md`;
10. `works/iratha-kanneer/HISTORICAL_GLYPH_AUDIT.md`;
11. `BATCH_01_REVIEW.md` through `BATCH_17_REVIEW.md`;
12. relevant page records through `pages/0188.md` and `BATCH_19_REVIEW.md`.

Resolve / attach the exact controlling PDF before source-dependent page work. If it is locally readable, do not detour to TDL/Wikisource for routine transcription or verification.

## Source identity

- title **இரத்தக் கண்ணீர்**;
- author **மு. கருணாநிதி**;
- publisher **திராவிடப் பண்ணை**;
- edition **முதல் பதிப்பு — 1953**;
- SHA-256 `120428985bd327456df46b9e06271896b106332711f4c9063d4f0c7fe72b6441`;
- size **319,220,349 bytes**;
- physical scans **188**;
- image-only; source PDF not committed.

## Mandatory efficient batch workflow

For this work, each routine ten-scan batch follows a hard two-commit boundary:

1. **Pass A:** whole-page source read once from the local controlling PDF; canonical transcription + physical joins/scene structure + ordinary visual verification;
2. **durable Pass-A commit:** persist every processed page as `needs-review`, `initial_verification: passed`, `historical_glyph_gate: pending` before beginning H-GATE;
3. **Pass B:** targeted independent H-GATE only — mandatory historical families plus actual candidate/source-sensitive loci and joins; do not retranscribe settled prose;
4. create crops/enhancements only for a genuine unresolved locus and stop once resolved/held;
5. **final closure commit:** promote clean pages to `verified`, create batch review, synchronize controls.

Short rule:

> **Local PDF → Pass A once → commit → targeted H-GATE → final commit. No external detour and no settled-text loop.**

## Verified structural evidence through scan 188

Scenes 1–53 remain as previously closed through scan 160. New Batch-17 evidence:

- Scene 54: scan **161** only, centred close-star;
- Scene 55: scans **162–163**, centred close-star on scan 163;
- Scene 56: scan **164** only, centred close-star;
- Scene 57: scans **165–171**, centred close-star on scan 171;
- Scene 58: scans **172–179**, centred close-star on scan 179;
- Scene 59: scans **180–182**, centred close-star on scan 182;
- Scene 60: scan **183** only, internal `* * *` transition plus centred close-star;
- Scene 61: scans **184–185**, centred close-star on scan 185;
- scan 186: source-visible `முடிவு` prose;
- scan 187: publisher catalogue;
- scan 188: final back wrapper / imprint.

Important physical joins:

- scan 130 `புறப்` → scan 131 `படுகின்றனர்.`;
- scan 146 `ஆரணங்கின்` → scan 147 `மயக்கத்தால்...`;
- scan 166 `வெளியிலிருந்து` → scan 167 `வேதாளமும்...`;
- scan 167 `ஏந்திக்` → scan 168 `கொண்டே`;
- scan 170 `பெண்கள்` → scan 171 `விபசாரப் பதுமைகளாக...`;
- scan 173 `உடனே போய்,` → scan 174 `வைத்தியர் பூபதியை...`;
- scan 178 `அந்தக்` → scan 179 `கதைகள்...`.

Scan 168's internal `* * *` ornament is a transition, not a scene close. Do not declare a final whole-work scene inventory until the page layer closes.

## Historical-glyph gate

Required order:

**canonical transcription → initial visual verification → H-GATE → final verification.**

Mandatory minimum family set:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`.

The list is a minimum, not a closed universe: Batch 05 additionally confirmed historical `ளா` look-alikes. Source pixels control. No global replacement. No grammar/spelling modernization. Same-edition comparison is preferred for doubtful clusters. Unresolved identity stays `needs-review`.

## Historical-glyph corrections through scan 188

Thirty-four corrections are durably recorded in `works/iratha-kanneer/HISTORICAL_GLYPH_AUDIT.md`.

Recent additions:

30. scan 138 `கண்ண மறைக்கும் பேய்` → `கண்ணை மறைக்கும் பேய்` (`ணை`);
31. scan 146 `இளஞரே` → `இளைஞரே` (`ளை`);
32. scan 160 `நீங்கள் தானு முத்தாயி?` → `நீங்கள் தானா முத்தாயி?` (`னா`);
33. scan 169 `இதுதானு` → `இதுதானா` (`னா`);
34. scan 170 `மில்ப்பாம்பே` → `மலைப்பாம்பே` (`லை`).
35. scan 172 `வரமாட்டானு?` → `வரமாட்டானா?` (`னா`).
36. scan 180 `முத்தனுள்` → `முத்தனால்` (`னா`).
37. scan 183 `முத்தன் மீட்டு` → `முத்தனை மீட்டு` (`னை`).

Batch 16 recorded one ordinary source-fidelity correction, scan 151 `மில்கள் உருளுவது போல` → `மலைகள் உருளுவது போல`; it is not part of the historical-glyph count. Batch 17 required no separate ordinary source-fidelity correction. Batch 18 and Batch 19 ordinary source-fidelity corrections are recorded in their reviews.

## Batch 19 durable state

- `BATCH_17_PASS_A.md` records Pass-A completion before H-GATE;
- Pass-A durable commit: `d951cdfc913b375d0c99a3c602a0a0743ef5d091`;
- Pass-A durable commit: `64343c46ae14791dfde44155f1543768081b6c8c`;
- `pages/0181.md` through `pages/0188.md` are final `verified` after targeted H-GATE;
- `BATCH_19_REVIEW.md` is **PASS / COMPLETE / LOCKED**;
- whole physical page layer: **188 / 188 COMPLETE / CLOSED FOR CURRENT SOURCE EVIDENCE**;
- `BATCH_17_REVIEW.md` is **PASS / COMPLETE / LOCKED**;
- scan 169 carries historical correction `இதுதானு` → `இதுதானா` (`னா`);
- scan 170 carries historical correction `மில்ப்பாம்பே` → `மலைப்பாம்பே` (`லை`);
- unusual source-visible readings retained after targeted checking include scan 162 `முழுங்கிவிடே`, `நடத்தொரு நாராயணன்`, `என்றுல`; scan 163 standalone `நெருங்கிய`; scan 165 `வாசப்பூது`; scan 169 `பொருத்தன்`; scan 170 `சொன்னுளாமே`, `பஞ்சணைப் பசியால்`, `சுக்கு நாறுக்கிவிடு`.

## Scene assembly durable state

The page layer is **188 / 188 COMPLETE / CLOSED FOR CURRENT SOURCE EVIDENCE**. Do not reopen it without genuinely new source evidence.

Scene Assembly Batch 01 is **PASS / COMPLETE / LOCKED**:

- `scenes/01.md` through `scenes/05.md` are `assembly-reviewed`;
- source scans **8–29** are covered exactly once by these scene artifacts;
- unresolved assembly discrepancies: **0**;
- durable authorities: `SCENE_ASSEMBLY_PROGRESS.md` and `SCENE_ASSEMBLY_BATCH_01_REVIEW.md`.

## Exact next activity — Scene Assembly Batch 02 / Scenes 6–10

Assemble Scenes **6–10** from verified source scans **30–44**. Do not re-read the PDF or reopen the closed page layer merely for assembly. Collapse only page-record-proven mechanical joins, preserve source scene-heading forms and closing stars, then update the assembly progress/review controls. English remains not authorized / not started.

# CLOSED WORK SAFEGUARDS

Keep completed `ஒரே முத்தம்` Tamil + English, `திருவாளர் தேசீயம்பிள்ளை`, `காகிதப்பூ`, `மணிமகுடம்`, and closed `கலைஞரின் நான்மணி மாலை` components closed unless explicitly reopened with genuinely new source evidence or a separately authorized phase.
