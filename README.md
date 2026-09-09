# Kalaignar Stage Plays

A source-first archival repository for stage plays and dramatic works written by **கலைஞர் மு. கருணாநிதி**.

The controlling authority is the supplied scan. OCR/Gemini may assist discovery or comparison but is never controlling authority. Historical Tamil glyphs are decoded by character identity rather than visual resemblance, without silently modernizing source wording.

## Works

| Work | Status |
|---|---|
| [இரத்தக் கண்ணீர்](works/iratha-kanneer/) | **ACTIVE — P0 PASS; scans 1–80 / 80 of 188 canonical + initial-verified + H-GATE PASS + final `verified`; 20 historical-glyph corrections recorded; next scans 81–90** |
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

Initial visual verification alone does not permit final `verified`. The mandatory minimum gate family is:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`.

This is a minimum rather than a closed list: `இரத்தக் கண்ணீர்` Batch 05 additionally exposed historical `ளா` look-alikes. No global replacement and no spelling modernization are permitted.

## இரத்தக் கண்ணீர் — active page-layer checkpoint

Controlling source: `TVA_BOK_0064189_இரத்தக்_கண்ணீர்.pdf`.

Source provenance: the controlling PDF supplied by the user was downloaded from the **Tamil Digital Library (TDL)**. TDL is therefore the provenance/catalogue source for this exact PDF, not an independent secondary textual witness.

- raw PDF physical scans: **188**;
- file size: **319,220,349 bytes**;
- SHA-256: **`120428985bd327456df46b9e06271896b106332711f4c9063d4f0c7fe72b6441`**;
- source type: **image-only**;
- source-visible edition: **முதல் பதிப்பு — 1953**;
- publisher: **திராவிடப் பண்ணை**;
- source PDF committed: **no**.

The conversation preview exposes only 150 page images; direct raw-PDF inspection establishes **188**, and the raw physical range controls processing.

Current durable state:

- P0 source intake: **PASS**;
- canonical page records: **80 / 188**;
- initial visual verification: **80 / 188**;
- historical-glyph H-GATE: **80 / 188**;
- final verified pages: **80 / 188**;
- contiguous final-verified range: **scans 1–80**;
- historical-glyph corrections recorded: **20**;
- unresolved page-level source issues: **0**;
- `needs-review`: **0**;
- `blocked`: **0**;
- scene assembly: **not started / blocked on page layer**;
- English translation: **not authorized / not started**.

Batch authorities:

- `works/iratha-kanneer/BATCH_01_REVIEW.md` — PASS;
- `works/iratha-kanneer/BATCH_02_REVIEW.md` — PASS / scans 11–20;
- `works/iratha-kanneer/BATCH_03_REVIEW.md` — PASS / scans 21–30;
- `works/iratha-kanneer/BATCH_04_REVIEW.md` — PASS / scans 31–40;
- `works/iratha-kanneer/BATCH_05_REVIEW.md` — PASS / scans 41–50;
- `works/iratha-kanneer/BATCH_06_REVIEW.md` — PASS / scans 51–60;
- `works/iratha-kanneer/BATCH_07_REVIEW.md` — PASS / scans 61–70;
- `works/iratha-kanneer/BATCH_08_REVIEW.md` — PASS / scans 71–80.

Latest H-GATE additions:

- scan 77 `மலபோல்` → `மலைபோல்` (`லை`);
- scan 78 `வீரனில்ல` → `வீரனில்லை` (`லை`).

Scan 75 `அவனை` (`னை`) was source-adjudicated before its canonical page was committed and reconfirmed by the full Batch-08 H-GATE, so it is not an additional correction-count entry. Scan 72 `நானோ` is a secure positive same-edition `னோ` witness.

Verified page evidence through scan 80 establishes Scene 1 scans 8–13, Scene 2 scans 14–18, Scene 3 scans 19–21, Scene 4 scans 22–25, Scene 5 scans 26–29, Scene 6 scan 30, Scene 7 scans 31–33, Scene 8 scans 34–39, Scene 9 scans 40–41, Scene 10 scans 42–44, Scene 11 scans 45–46, Scene 12 scans 47–49, Scene 13 scans 50–51, Scene 14 scans 52–53, Scene 15 scans 54–57, Scene 16 scans 58–62, Scene 17 scans 63–65, Scene 18 scans 66–67, Scene 19 scan 68, Scene 20 scans 69–75, and Scene 21 scans 76–80. This is not yet a final whole-work scene inventory.

Exact next activity: **Batch 09 / scans 81–90** — direct source transcription, ordinary initial visual verification, independent full historical-glyph H-GATE, final verification, `BATCH_09_REVIEW.md`, and checkpoint synchronization. Scene assembly and English remain blocked/not authorized while the page layer is incomplete.

## ஒரே முத்தம் — Tamil closure checkpoint

Controlling source: `TVA_BOK_0064325_ஒரே_முத்தம்.pdf`.

- file size: **224,884,964 bytes**;
- physical scans: **131**;
- SHA-256: **`60780e340e6b0c6d6f3956af8beeb69692fab3f20e843c6ed4275b9962aae220`**;
- source PDF committed to repository: **no**;
- main play: scans **8–118 / pp.6–116**, **30 scenes**;
- separate `நகைச் சுவைப் பகுதி.`: scans **119–130 / pp.117–128**, its own **3 scenes**;
- scan **131**: verified back-cover publisher advertisement.

Physical-page state: source-processed / closure-audited **131 / 131 — COMPLETE**; verified **103 / 131**; terminal `blocked` **28 / 131**; ordinary `needs-review` **0**; historical-glyph PASS **103 / 131**.

Tamil scene layer: main **30 / 30**; supplementary **3 / 3**; full page-to-scene audit **PASS — 33 / 33**; source-secure scenes **15**; hold-bearing scenes **18**; source-wording normalizations **0**; terminal held wording repaired from context **0**; unresolved wording invented **0**.

Work-level Tamil state: **TAMIL ARCHIVAL TRANSCRIPTION COMPLETE / CLOSED FOR CURRENT SOURCE EVIDENCE — WITH 28 EXPLICIT TERMINAL SOURCE-CONDITION PAGE HOLDS.**

## ஒரே முத்தம் — English translation closure

Final English authorities remain under `works/ore-mutham/translations/en/`; final `TRANSLATION_REVIEW.md` is **PASS / COMPLETE**.

Final English state: **33 / 33** scenes reviewed; **7 / 7 PASS / LOCKED** batches; **18 / 18** hold-bearing English scenes preserve holds; Tamil holds resolved by translation **0**; unresolved blocking English issues **0**; secondary-English contamination **0**.

Final English work-level state: **ENGLISH TRANSLATION COMPLETE / CLOSED FOR CURRENT TAMIL SOURCE EVIDENCE.**

## Closed work safeguards

`ஒரே முத்தம்` Tamil and English workflows, `திருவாளர் தேசீயம்பிள்ளை`, `காகிதப்பூ`, `மணிமகுடம்`, and closed `கலைஞரின் நான்மணி மாலை` components remain closed unless explicitly reopened with genuinely new source evidence or a separately authorized phase.