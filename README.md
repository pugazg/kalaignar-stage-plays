# Kalaignar Stage Plays

A source-first archival repository for stage plays and dramatic works written by **கலைஞர் மு. கருணாநிதி**.

The controlling authority is the supplied scan. OCR/Gemini may assist discovery or comparison but is never controlling authority. Historical Tamil glyphs are decoded by character identity rather than visual resemblance, without silently modernizing source wording.

## Works

| Work | Status |
|---|---|
| [நச்சுக்கோப்பை](works/nachuk-koppai/) | **ACTIVE — Tamil page layer reconciled 63/63; 61 verified + 2 terminal source-condition holds; scene assembly next; P0 SHA-256 hold remains** |
| [இரத்தக் கண்ணீர்](works/iratha-kanneer/) | **COMPLETE / CLOSED FOR CURRENT SOURCE EVIDENCE — Tamil page layer 188/188; Tamil scenes 61/61; English 61/61 reviewed; 13/13 translation batches PASS/LOCKED; final English review PASS** |
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

## இரத்தக் கண்ணீர் — closure checkpoint

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
- canonical page records: **188 / 188**;
- initial visual verification: **188 / 188**;
- historical-glyph H-GATE: **188 / 188**;
- final verified pages: **188 / 188**;
- contiguous final-verified range: **scans 1–188**;
- historical-glyph corrections recorded: **37**;
- unresolved page-level source issues: **0**;
- `needs-review`: **0**;
- `blocked`: **0**;
- scene assembly: **COMPLETE / CLOSED — Scenes 1–61 / 61 assembly-reviewed; Batches 01–11 PASS; final consistency review PASS**;
- English translation: **COMPLETE / CLOSED — 61 / 61 scenes reviewed; 13 / 13 batches PASS / LOCKED; final `TRANSLATION_REVIEW.md` PASS**.

Batch authorities now run through `works/iratha-kanneer/BATCH_19_REVIEW.md` — **PASS / COMPLETE / LOCKED / scans 181–188**.

The active work uses `works/iratha-kanneer/BATCH_EXECUTION_WORKFLOW.md`, requiring: **local PDF → Pass A whole-page once → durable Pass-A commit → targeted independent H-GATE → final closure commit**. Settled prose is not re-transcribed during H-GATE, and crops are created only for genuine uncertainty.

Recent historical-glyph corrections include scan 146 `இளஞரே` → `இளைஞரே` (`ளை`), scan 160 `நீங்கள் தானு முத்தாயி?` → `நீங்கள் தானா முத்தாயி?` (`னா`), scan 169 `இதுதானு` → `இதுதானா` (`னா`), scan 170 `மில்ப்பாம்பே` → `மலைப்பாம்பே` (`லை`), scan 172 `வரமாட்டானு?` → `வரமாட்டானா?` (`னா`), and scan 180 `முத்தனுள்` → `முத்தனால்` (`னா`). The cumulative historical-glyph count is now **37**. Batch 19 adds scan 183 `முத்தன் மீட்டு` → `முத்தனை மீட்டு` (`னை`). Batch 19 ordinary source-fidelity fixes are recorded in its review.

Verified page evidence through scan 188 establishes Scene 59 scans **180–182**, Scene 60 scan **183**, Scene 61 scans **184–185**, scan 186 `முடிவு`, scan 187 publisher catalogue, and scan 188 back wrapper/imprint. The complete numbered scene range is now source-proven through Scene **61**.

No further Tamil page-layer or scene-assembly activity remains for current source evidence. English translation is **COMPLETE / CLOSED FOR CURRENT TAMIL SOURCE EVIDENCE — 61 / 61 scenes reviewed; 13 / 13 batches PASS / LOCKED; final review PASS**.

## ஒரே முத்தம் — Tamil closure checkpoint

Controlling source: `TVA_BOK_0064325_ஒரே_முத்தம்.pdf`.

Physical-page state: source-processed / closure-audited **131 / 131 — COMPLETE**; verified **103 / 131**; terminal `blocked` **28 / 131**; ordinary `needs-review` **0**; historical-glyph PASS **103 / 131**.

Tamil scene layer: main **30 / 30**; supplementary **3 / 3**; full page-to-scene audit **PASS — 33 / 33**. Work-level Tamil state: **TAMIL ARCHIVAL TRANSCRIPTION COMPLETE / CLOSED FOR CURRENT SOURCE EVIDENCE — WITH 28 EXPLICIT TERMINAL SOURCE-CONDITION PAGE HOLDS.**

Final English state: **33 / 33** scenes reviewed; **7 / 7 PASS / LOCKED** batches; final `TRANSLATION_REVIEW.md` **PASS / COMPLETE**. Work-level English state: **ENGLISH TRANSLATION COMPLETE / CLOSED FOR CURRENT TAMIL SOURCE EVIDENCE.**

## Closed work safeguards

`ஒரே முத்தம்` Tamil and English workflows, `திருவாளர் தேசீயம்பிள்ளை`, `காகிதப்பூ`, `மணிமகுடம்`, and closed `கலைஞரின் நான்மணி மாலை` components remain closed unless explicitly reopened with genuinely new source evidence or a separately authorized phase.


## நச்சுக்கோப்பை — reconciled Tamil page-layer checkpoint

Controlling source: `ACL-TDD_00314_நச்சுக்_கோப்பை.pdf`.

Current intake state:

- physical scans: **63**;
- source type: **image-only / no usable parsed text layer**;
- title visible on source: **நச்சுக்கோப்பை**;
- author: **மு. கருணாநிதி**;
- publisher: **திராவிடன் பதிப்பகம்**;
- edition: **முதல் பதிப்பு — 1951**;
- numbered dramatic scenes visually located: **18**;
- literary close: scan **63**, source-visible **முற்றும்**;
- SHA-256: **PENDING checksum calculation**;
- file size: **18,459,068 bytes**;
- P0 status: **PARTIAL / NOT CLOSED**;
- page records: **63 / 63 canonical — PAGE-LAYER PASS A COMPLETE**;
- Batch 01 Pass A: **COMPLETE — 10 / 10 initial verification PASS**;
- user-supplied first-pass baseline: **INGESTED for scans 1–10** (`works/nachuk-koppai/first-pass/BATCH_01_USER_TRANSCRIPTION.md`);
- H-GATE: **63 / 63 checked — 61 PASS / 2 terminal source-condition needs-review**;
- word-by-word visual fidelity: **63 / 63 COMPLETE — 61 PASS / 2 terminal holds**;
- full page-state reconciliation: **COMPLETE — 63 / 63**;
- scene assembly: **not started — NEXT**;
- English translation: **not started / not authorized as an active phase yet**.

The user's contextual description (1943 origin/performance history, alternate title `சாந்தா (அ) பழனியப்பன்`, and thematic summary) is recorded separately as **user-supplied context**, not as controlling-scan text.

Exact next activity: begin **Tamil scene assembly, Scenes 1–5**, from the reconciled canonical page layer. The terminal source-condition holds on scans **22 and 35** must be propagated explicitly into affected assembled scenes. Scan 20 is resolved as **`வேணும்னாலும்`**. SHA-256 remains a separate P0 fingerprint hold.
