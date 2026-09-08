# Kalaignar Stage Plays

A source-first archival repository for stage plays and dramatic works written by **கலைஞர் மு. கருணாநிதி**.

The controlling authority is the supplied scan. OCR/Gemini may assist discovery or comparison but is never controlling authority. Historical Tamil glyphs are decoded by character identity rather than visual resemblance, without silently modernizing source wording.

## Works

| Work | Status |
|---|---|
| [இரத்தக் கண்ணீர்](works/iratha-kanneer/) | **ACTIVE — P0 PASS; scans 1–20 / 20 of 188 canonical + initial-verified + H-GATE PASS + final `verified`; 6 historical-glyph corrections recorded; next scans 21–30** |
| [ஒரே முத்தம்](works/ore-mutham/) | **COMPLETE / CLOSED FOR CURRENT SOURCE EVIDENCE — Tamil source/closure 131/131; 103 verified + 28 terminal `blocked`; 30/30 main + 3/3 supplementary Tamil scenes; scene audit PASS 33/33; Tamil closure PASS; English 33/33 reviewed; 7/7 batches PASS/LOCKED; final English review PASS; 18/18 hold-bearing English scenes preserve holds** |
| [திருவாளர் தேசீயம்பிள்ளை](works/thiruvalar-desiyampillai/) | **COMPLETE / CLOSED FOR CURRENT SOURCE EVIDENCE — Tamil page pass 49/49; historical-glyph pass 49/49; 40 verified; 9 source-condition needs-review; 7/7 Tamil SRUs assembled/reviewed PASS; independent English 7/7 reviewed; 4/4 batches PASS/LOCKED; final English review PASS** |
| [காகிதப்பூ](works/kagithapoo/) | **COMPLETE / CLOSED — Tamil 41/41; scene layer 23/23; English 23/23; final reviews PASS** |
| [சிலப்பதிகாரம் — நாடகக் காப்பியம்](works/silappathikaram-nataka-kappiyam/) | **Tamil archive PASS; English COMPLETE; secondary-witness comparison PASS** |
| [பரதாயணம்](works/bharathayanam/) | **Tamil archive/assembly PASS; independent English PASS; 2009 One Act Plays witness N/A** |
| [அனார்கலி](works/anarkali/) | **Tamil 9/9; 4/4 scenes; fidelity PASS; independent English PASS; 2009 witness comparison PASS** |
| [சாக்ரடீஸ்](works/socrates/) | **Tamil 17/17; 5/5 scenes; fidelity PASS; independent English PASS; 2009 witness comparison PASS** |
| [சேரன் செங்குட்டுவன்](works/cheran-senguttuvan/) | **Tamil 10/10; 4/4 scenes; fidelity PASS; independent English PASS; 2009 witness comparison PASS** |
| [மணிமகுடம்](works/manimagudam/) | **COMPLETE / CLOSED — Tamil 170/170; scenes 47/47; independent English 47/47; release READY/FINAL** |

## Repository-wide historical Tamil glyph gate

Historical-type sources use two explicit repository authorities:

- [`HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`](HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md) — character-identity / source-first decoding guide;
- [`HISTORICAL_TAMIL_GLYPH_GATE.md`](HISTORICAL_TAMIL_GLYPH_GATE.md) — mandatory post-initial-verification gate.

For applicable older Tamil pages the required order is:

**canonical transcription → initial visual verification → historical-glyph H-GATE → final verification.**

Initial visual verification alone does not permit final `verified`. While H-GATE is pending, the page remains `needs-review`. The mandatory minimum gate family is:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`.

No global replacement and no spelling modernization are permitted.

## இரத்தக் கண்ணீர் — active page-layer checkpoint

Controlling source: `TVA_BOK_0064189_இரத்தக்_கண்ணீர்.pdf`.

- raw PDF physical scans: **188**;
- file size: **319,220,349 bytes**;
- SHA-256: **`120428985bd327456df46b9e06271896b106332711f4c9063d4f0c7fe72b6441`**;
- source type: **image-only**;
- source-visible edition: **முதல் பதிப்பு — 1953**;
- publisher: **திராவிடப் பண்ணை**;
- source PDF committed to repository: **no**.

The conversation preview exposes only 150 page images; direct raw-PDF inspection establishes **188**, and the raw physical range controls processing.

Current durable state:

- P0 source intake: **PASS**;
- canonical page records: **20 / 188**;
- initial visual verification: **20 / 188**;
- historical-glyph H-GATE: **20 / 188**;
- final verified pages: **20 / 188**;
- contiguous final-verified range: **scans 1–20**;
- historical-glyph corrections recorded: **6**;
- unresolved page-level source issues: **0**;
- scene assembly: **not started / blocked on page layer**;
- English translation: **not authorized / not started**.

Batch authorities:

- `works/iratha-kanneer/BATCH_01_REVIEW.md` — PASS, including retrospective scan-9 `னா` correction and re-pass;
- `works/iratha-kanneer/BATCH_02_REVIEW.md` — PASS / COMPLETE, scans 11–20.

Historical-glyph corrections currently recorded:

- scan 9 `வயதுடையவனு அல்லது கிழவனு` → `வயதுடையவனா அல்லது கிழவனா` (`னா`);
- scan 11 `அஞ்சல் மண்ணில்` → `அஞ்சல் மனையில்` (`னை`);
- scans 12 and 16 `அஞ்சல் மண்` → `அஞ்சல் மனை` (`னை`);
- scan 17 `மருத்துவக் கிழவனூர்` → `மருத்துவக் கிழவனார்` (`னா`);
- scan 18 `ஏன் வந்தேனு?` → `ஏன் வந்தேனா?` (`னா`).

Verified page evidence currently establishes Scene 1 close on scan 13, Scene 2 on scans 14–18, and Scene 3 beginning on scan 19. This is not yet a final whole-work scene inventory.

Exact next activity: process **scans 21–30** through transcription → initial verification → H-GATE → final verification where clean.

## ஒரே முத்தம் — Tamil closure checkpoint

Controlling source: `TVA_BOK_0064325_ஒரே_முத்தம்.pdf`.

- file size: **224,884,964 bytes**;
- physical scans: **131**;
- SHA-256: **`60780e340e6b0c6d6f3956af8beeb69692fab3f20e843c6ed4275b9962aae220`**;
- source PDF committed to repository: **no**;
- main play: scans **8–118 / pp.6–116**, **30 scenes**;
- separate `நகைச் சுவைப் பகுதி.`: scans **119–130 / pp.117–128**, its own **3 scenes**;
- scan **131**: verified back-cover publisher advertisement.

Physical-page state:

- source-processed / closure-audited: **131 / 131 — COMPLETE**;
- verified: **103 / 131**;
- terminal current-source-condition `blocked`: **28 / 131**;
- ordinary `needs-review`: **0**;
- historical-glyph PASS: **103 / 131**.

Tamil scene layer:

- main scenes: **30 / 30**;
- supplementary scenes: **3 / 3**;
- full page-to-scene audit: **PASS — 33 / 33**;
- source-secure scenes: **15**;
- hold-bearing scenes: **18**;
- source-wording normalizations during assembly: **0**;
- terminal held wording repaired from context: **0**;
- unresolved wording invented: **0**.

Authoritative Tamil closure documents remain under `works/ore-mutham/`, especially `indexes/page-map.md`, `TERMINAL_SOURCE_CONDITION_HOLDS.md`, `SCENE_ASSEMBLY_AUDIT.md`, and `TAMIL_CLOSURE_REVIEW.md`.

Work-level Tamil state:

**TAMIL ARCHIVAL TRANSCRIPTION COMPLETE / CLOSED FOR CURRENT SOURCE EVIDENCE — WITH 28 EXPLICIT TERMINAL SOURCE-CONDITION PAGE HOLDS.**

The closure does not pretend all 131 scans are verified. It means the current-source workflow has been exhausted defensibly and all remaining ambiguity is explicit and traceable.

## ஒரே முத்தம் — English translation closure

English translation was explicitly authorized after Tamil closure. Immediate drafting authority was the closed 33-scene Tamil layer; Tamil source artifacts remain unchanged.

Final English authorities:

- `works/ore-mutham/TRANSLATION_PLAN.md`;
- `works/ore-mutham/translations/en/README.md`;
- `works/ore-mutham/translations/en/BATCH_01_REVIEW.md` through `BATCH_07_REVIEW.md`;
- `works/ore-mutham/translations/en/TRANSLATION_REVIEW.md` — **PASS / COMPLETE**.

Final English state:

- main English scenes: **30 / 30**;
- supplementary English scenes: **3 / 3**;
- total English scenes present / reviewed: **33 / 33**;
- completed review batches: **7 / 7 PASS / LOCKED**;
- source-hold-bearing English scenes completed: **18 / 18**;
- Tamil terminal holds resolved by English translation: **0**;
- unresolved blocking English issues: **0**;
- secondary-English contamination: **0**.

Every terminal Tamil source hold remains explicit in the corresponding hold-bearing English artifact. Source-secure shared-boundary main Scene 28 and supplementary Scene 2 do not inherit the following scene's terminal hold.

Final English work-level state:

**ENGLISH TRANSLATION COMPLETE / CLOSED FOR CURRENT TAMIL SOURCE EVIDENCE.**

### User-directed iteration policy — fulfilled

The user directed **10 scenes per iteration**. The five-scene review-batch files were preserved, so ten-scene iterations executed two review batches where possible.

The final remainder contained only **8** scenes and was completed in one go:

- main Scenes **26–30** / Batch 6;
- supplementary `நகைச் சுவைப் பகுதி.` Scenes **1–3** / Batch 7;
- final 33-scene `TRANSLATION_REVIEW.md` — **PASS / COMPLETE**.

## Closed work safeguards

`ஒரே முத்தம்` Tamil and English workflows, `திருவாளர் தேசீயம்பிள்ளை`, `காகிதப்பூ`, `மணிமகுடம்`, and closed `கலைஞரின் நான்மணி மாலை` components remain closed unless explicitly reopened with genuinely new source evidence or a separately authorized phase.

There is no further authorized `ஒரே முத்தம்` phase at the current checkpoint.