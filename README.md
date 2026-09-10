# Kalaignar Stage Plays

A source-first archival repository for stage plays and dramatic works written by **கலைஞர் மு. கருணாநிதி**.

The controlling authority is the supplied scan. OCR/Gemini may assist discovery or comparison but is never controlling authority. Historical Tamil glyphs are decoded by character identity rather than visual resemblance, without silently modernizing source wording.

## Works

| Work | Status |
|---|---|
| [இரத்தக் கண்ணீர்](works/iratha-kanneer/) | **ACTIVE — P0 PASS; scans 1–170 / 170 of 188 canonical + initial-verified + H-GATE PASS + final `verified`; 34 historical-glyph corrections recorded; next scans 171–180** |
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

Source provenance: the controlling PDF supplied by the user was downloaded from the **Tamil Digital Library (TDL)**. TDL and the Wikisource copy are provenance/transport routes for this same scan set, not independent secondary textual witnesses. When the exact controlling PDF is attached/readable locally, routine page work uses that local PDF directly.

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
- canonical page records: **170 / 188**;
- initial visual verification: **170 / 188**;
- historical-glyph H-GATE: **170 / 188**;
- final verified pages: **170 / 188**;
- contiguous final-verified range: **scans 1–170**;
- historical-glyph corrections recorded: **34**;
- unresolved page-level source issues: **0**;
- `needs-review`: **0**;
- `blocked`: **0**;
- scene assembly: **not started / blocked on page layer**;
- English translation: **not authorized / not started**.

Batch authorities now run through `works/iratha-kanneer/BATCH_17_REVIEW.md` — **PASS / COMPLETE / LOCKED / scans 161–170**.

The active work uses `works/iratha-kanneer/BATCH_EXECUTION_WORKFLOW.md`, requiring: **local PDF → Pass A whole-page once → durable Pass-A commit → targeted independent H-GATE → final closure commit**. Settled prose is not re-transcribed during H-GATE, and crops are created only for genuine uncertainty.

Recent historical-glyph corrections include scan 146 `இளஞரே` → `இளைஞரே` (`ளை`), scan 160 `நீங்கள் தானு முத்தாயி?` → `நீங்கள் தானா முத்தாயி?` (`னா`), scan 169 `இதுதானு` → `இதுதானா` (`னா`), and scan 170 `மில்ப்பாம்பே` → `மலைப்பாம்பே` (`லை`). The cumulative historical-glyph count is now **34**. Batch 17 required no separate ordinary source-fidelity correction.

Verified page evidence through scan 170 establishes Scene 54 scan **161**, Scene 55 scans **162–163**, Scene 56 scan **164**, and Scene 57 opening on scan **165** and continuing through scan **170** into scan 171. Scan 166→167 preserves `வெளியிலிருந்து` → `வேதாளமும்...`; scan 167→168 preserves `ஏந்திக்` → `கொண்டே`; scan 168's internal `* * *` is not a scene close; scan 170 ends mid-utterance at `பெண்கள்`.

Exact next activity: **Batch 18 / scans 171–180** using `BATCH_EXECUTION_WORKFLOW.md`: raw local controlling PDF beyond the 150-page preview, Pass A whole-page once and durable commit, then targeted H-GATE and final closure commit. Scene assembly and English remain blocked/not authorized while the page layer is incomplete.

## ஒரே முத்தம் — Tamil closure checkpoint

Controlling source: `TVA_BOK_0064325_ஒரே_முத்தம்.pdf`.

Physical-page state: source-processed / closure-audited **131 / 131 — COMPLETE**; verified **103 / 131**; terminal `blocked` **28 / 131**; ordinary `needs-review` **0**; historical-glyph PASS **103 / 131**.

Tamil scene layer: main **30 / 30**; supplementary **3 / 3**; full page-to-scene audit **PASS — 33 / 33**. Work-level Tamil state: **TAMIL ARCHIVAL TRANSCRIPTION COMPLETE / CLOSED FOR CURRENT SOURCE EVIDENCE — WITH 28 EXPLICIT TERMINAL SOURCE-CONDITION PAGE HOLDS.**

Final English state: **33 / 33** scenes reviewed; **7 / 7 PASS / LOCKED** batches; final `TRANSLATION_REVIEW.md` **PASS / COMPLETE**. Work-level English state: **ENGLISH TRANSLATION COMPLETE / CLOSED FOR CURRENT TAMIL SOURCE EVIDENCE.**

## Closed work safeguards

`ஒரே முத்தம்` Tamil and English workflows, `திருவாளர் தேசீயம்பிள்ளை`, `காகிதப்பூ`, `மணிமகுடம்`, and closed `கலைஞரின் நான்மணி மாலை` components remain closed unless explicitly reopened with genuinely new source evidence or a separately authorized phase.
