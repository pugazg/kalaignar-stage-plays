# இரத்தக் கண்ணீர்

Archive slug: `iratha-kanneer`.

## Current status

**ACTIVE — P0 SOURCE INTAKE PASS; SCANS 1–20 / 20 OF 188 CANONICAL + INITIAL-VERIFIED + H-GATE PASS + FINAL `verified`; BATCHES 01–02 PASS; NEXT SCANS 21–30.**

Controlling source: `TVA_BOK_0064189_இரத்தக்_கண்ணீர்.pdf`.

- SHA-256: `120428985bd327456df46b9e06271896b106332711f4c9063d4f0c7fe72b6441`;
- file size: **319,220,349 bytes**;
- physical scans from direct raw-PDF inspection: **188**;
- image-only source: **yes**;
- source PDF committed to repository: **no**;
- title as printed: **இரத்தக் கண்ணீர்**;
- author as printed: **மு. கருணாநிதி**;
- publisher / imprint: **திராவிடப் பண்ணை**, தெப்பக்குளம், திருச்சி;
- source-visible edition: **முதல் பதிப்பு — 1953**;
- source-visible price: **ரூ. 2-0-0**.

The conversation file preview exposes only 150 page images. Direct raw-PDF inspection establishes **188 physical scans**; the raw physical range is authoritative and processing must continue through scan 188.

## Source-visible intake structure

- scan 1 — illustrated front cover;
- scan 2 — title / author / publisher page;
- scan 3 — `முதல் பதிப்பு—1953`, rights, price and printer-imprint page;
- scan 4 — `பதிப்புரை`, internal date `14-4-1948`;
- scan 5 — `முன்னுரை`, signed `மு. கருணாநிதி`, `திருச்சி மத்திய சிறை`, `20-11-53`;
- scans 6–7 — `நுழைவாய்`;
- scan 8 — `இரத்தக் கண்ணீர் [நாடகம்]`, `காட்சி 1]`, `[பழுதூர்`;
- scan 13 — verified Scene 1 close;
- scan 14 — verified `காட்சி—2]` / `[பழுதூர் மடாலயம்`;
- scan 18 — verified Scene 2 close;
- scan 19 — verified `காட்சி 3]` / `[பழுதூரின் தெரு`;
- late intake spot checks: scan 180 `காட்சி 59]`, scan 183 `காட்சி 60]`, scan 184 `காட்சி 61]`;
- scan 186 — `முடிவு` / closing prose;
- scan 187 — publisher catalogue advertisement;
- scan 188 — back wrapper / publisher device.

A final scene inventory is **not** inferred from the early verified scenes or late intake spot checks. Page-level archival processing remains the active phase.

## Mandatory historical Tamil glyph workflow

Repository authorities:

1. `../../HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`;
2. `../../HISTORICAL_TAMIL_GLYPH_GATE.md`;
3. `HISTORICAL_GLYPH_AUDIT.md`.

Required page pipeline:

**canonical transcription → initial visual verification → historical-glyph H-GATE → final verification.**

Initial verification alone is not final `verified`. The minimum family set checked on every applicable page is:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`.

Source pixels control. No OCR authority, no global replacement, no lexical modernization, and no contextual guessing at uncertain historical type.

## Batch 01 — scans 1–10

Review authority: `BATCH_01_REVIEW.md` — **PASS / COMPLETE**.

Durable results:

- canonical / initial verification / H-GATE / final verified: **10 / 10**;
- `needs-review`: **0**;
- `blocked`: **0**.

Retrospective scan-9 H-GATE correction:

`வயதுடையவனு அல்லது கிழவனு` → **`வயதுடையவனா அல்லது கிழவனா`** (`னா`).

Scan 9 was reopened and cleanly re-passed after this historical character-identity correction.

## Batch 02 — scans 11–20

Review authority: `BATCH_02_REVIEW.md` — **PASS / COMPLETE / LOCKED FOR CURRENT SOURCE EVIDENCE**.

Durable results:

- page records: `pages/0011.md` through `pages/0020.md`;
- canonical transcription: **10 / 10**;
- initial visual verification: **10 / 10 PASS**;
- H-GATE: **10 / 10 PASS**;
- final `verified`: **10 / 10**;
- `needs-review`: **0**;
- `blocked`: **0**;
- historical-glyph corrections in Batch 02: **5**.

Batch-02 historical corrections:

- scan 11 `அஞ்சல் மண்ணில்` → `அஞ்சல் மனையில்` (`னை`);
- scan 12 `அஞ்சல் மண்` → `அஞ்சல் மனை` (`னை`);
- scan 16 `அஞ்சல் மண்` → `அஞ்சல் மனை` (`னை`);
- scan 17 `மருத்துவக் கிழவனூர்` → `மருத்துவக் கிழவனார்` (`னா`);
- scan 18 `ஏன் வந்தேனு?` → `ஏன் வந்தேனா?` (`னா`).

These are character-identity decodings, not spelling modernization.

Verified structural evidence through scan 20:

- Scene 1 closes on scan 13;
- Scene 2 spans scans 14–18 and closes on scan 18;
- Scene 3 begins on scan 19 and continues through scan 20.

## Current progress

- P0 source intake — **PASS**;
- canonical page records — **20 / 188**;
- initial visual verification — **20 / 188**;
- historical-glyph H-GATE — **20 / 188**;
- final verified pages — **20 / 188**;
- contiguous verified range — **scans 1–20**;
- historical-glyph corrections recorded — **6 total**;
- unresolved page-level source issues — **0**;
- structural / scene assembly — **not started / blocked on page layer**;
- English translation — **not authorized / not started**.

## Exact next activity

Process **scans 21–30** in the same order:

1. create `pages/0021.md` through `pages/0030.md`;
2. transcribe each scan directly from source pixels;
3. perform initial visual verification;
4. run the separate post-verification H-GATE on every page;
5. promote only clean H-GATE-passed pages to final `verified`;
6. record every historical-glyph correction or unresolved locus explicitly;
7. update `indexes/page-map.md`, `HISTORICAL_GLYPH_AUDIT.md`, Batch 03 review and handover documents.

Do not begin scene assembly or English translation merely because a page batch completes.