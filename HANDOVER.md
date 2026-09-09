# Kalaignar Stage Plays — Handover

Repository: `pugazg/kalaignar-stage-plays`, branch `main`.

## Startup rule

Always fetch live `main` first and preserve newer durable state.

Permanent source-first workflow: `STAGE_PLAY_PROCESSING_GUIDE.md`.

Historical-type authority:

1. `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`;
2. `HISTORICAL_TAMIL_GLYPH_GATE.md`.

# CURRENT CHECKPOINT — இரத்தக் கண்ணீர் ACTIVE / SCANS 1–70 VERIFIED

Active work: `works/iratha-kanneer/`.

Controlling source: `TVA_BOK_0064189_இரத்தக்_கண்ணீர்.pdf`.

Source provenance: the user-supplied controlling PDF was downloaded from the **Tamil Digital Library (TDL)**. The TDL catalogue/record therefore documents provenance for this exact supplied source; it is **not an independent secondary textual witness** and must not be treated as one.

Current durable state:

- P0 source intake: **PASS**;
- physical scans: **188 / 188 confirmed**;
- canonical page transcription: **70 / 188**;
- initial visual verification: **70 / 188**;
- historical-glyph H-GATE: **70 / 188**;
- final verified pages: **70 / 188**;
- contiguous final-verified range: **scans 1–70**;
- Batches 01–07: **PASS / COMPLETE**;
- Batch 07: **PASS / COMPLETE / LOCKED FOR CURRENT SOURCE EVIDENCE**;
- historical-glyph corrections recorded: **18**;
- unresolved page-level source issues: **0**;
- structural / scene assembly: **not started / blocked on page layer**;
- English translation: **not authorized / not started**.

The conversation preview exposes only 150 images; direct raw-PDF inspection established **188 physical scans**. Never stop at preview page 150.

## Mandatory startup

Read completely before source-dependent work:

1. `STAGE_PLAY_PROCESSING_GUIDE.md`;
2. `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`;
3. `HISTORICAL_TAMIL_GLYPH_GATE.md`;
4. this `HANDOVER.md`;
5. `NEXT_CHAT_PROMPT.md`;
6. `works/iratha-kanneer/README.md`;
7. `works/iratha-kanneer/metadata/source.md`;
8. `works/iratha-kanneer/indexes/page-map.md`;
9. `works/iratha-kanneer/HISTORICAL_GLYPH_AUDIT.md`;
10. `BATCH_01_REVIEW.md` through `BATCH_07_REVIEW.md`;
11. relevant page records through `pages/0070.md`.

Resolve the controlling PDF before page-level visual work. Do not substitute OCR, web text, later editions or memory for source pixels.

## Source identity

- title **இரத்தக் கண்ணீர்**;
- author **மு. கருணாநிதி**;
- publisher **திராவிடப் பண்ணை**;
- edition **முதல் பதிப்பு — 1953**;
- SHA-256 `120428985bd327456df46b9e06271896b106332711f4c9063d4f0c7fe72b6441`;
- size **319,220,349 bytes**;
- image-only; source PDF not committed.

## Verified structural evidence through scan 70

- Scene 1: scans 8–13;
- Scene 2: scans 14–18;
- Scene 3: scans 19–21;
- Scene 4: scans 22–25;
- Scene 5: scans 26–29;
- Scene 6: scan 30 only;
- Scene 7: scans 31–33;
- Scene 8: scans 34–39;
- Scene 9: scans 40–41;
- Scene 10: scans 42–44;
- Scene 11: scans 45–46;
- Scene 12: scans 47–49;
- Scene 13: scans 50–51;
- Scene 14: scans 52–53;
- Scene 15: scans 54–57;
- Scene 16: scans 58–62;
- Scene 17: scans 63–65;
- Scene 18: scans 66–67;
- Scene 19: scan 68 only;
- Scene 20: begins scan 69 and continues beyond scan 70.

Do not declare a final whole-work scene inventory until the page layer closes.

## Historical-glyph gate

Required order:

**canonical transcription → initial visual verification → H-GATE → final verification.**

Mandatory minimum family set:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`.

The list is a minimum, not a closed universe: Batch 05 additionally confirmed historical `ளா` look-alikes. Source pixels control. No global replacement. No grammar/spelling modernization. Same-edition comparison is preferred for doubtful clusters. Unresolved identity stays `needs-review`.

## Historical-glyph corrections through scan 70

Eighteen corrections are durably recorded in `works/iratha-kanneer/HISTORICAL_GLYPH_AUDIT.md`.

Batch-07 additions:

15. scan 61 `மனிதனுயிற்றே` → `மனிதனாயிற்றே` (`னா`);
16. scan 61 `வேல் பார்த்தாய்` → `வேலை பார்த்தாய்` (`லை`);
17. scan 61 `அஞ்சல் மணிக்கு` → `அஞ்சல் மனைக்கு` (`னை`);
18. scan 63 `வீரப்பனு?` → `வீரப்பனா?` (`னா`).

The source-visible scan-63 `அஞ்சல் மண் வேலையை` remains retained after independent re-reading; no global replacement was used.

## Exact next activity — Batch 08 split into three activities

To reduce cross-contamination between ordinary transcription and glyph adjudication, Batch 08 is intentionally split:

1. **Activity 1 — scan-75 glyph adjudication: COMPLETE as working source evidence.** Source-supported reading locked as `அவனை` (`னை`). This does not yet advance the durable page count because `0075.md` has not been committed.
2. **Activity 2 — ACTIVE:** create `pages/0071.md` through `0080.md`, transcribe directly from source pixels, establish scan-70→71 continuation from scan 71 pixels only, and complete ordinary initial visual verification. While H-GATE is pending, each clean page must remain `status: needs-review`, `initial_verification: passed`, `historical_glyph_gate: pending`.
3. **Activity 3 — only after Activity 2 is durably complete:** run the separate full H-GATE, adjudicate all mandatory families plus additional look-alikes, record genuine corrections/unresolved loci, promote only clean pages to final `verified`, create `BATCH_08_REVIEW.md`, and synchronize page map/audit/checkpoint documents.

Working H-GATE candidates already isolated for Activity 3 include scan 77 apparent `மலபோல்` vs source-supported `மலைபோல்`, and scan 78 apparent `வீரனில்ல` vs source-supported `வீரனில்லை`; do not silently fold these into Activity 2.

After Activity 3, fetch final live `main` SHA.

Do not begin scene assembly or English translation merely because a page batch completes.

# CLOSED WORK SAFEGUARDS

Keep completed `ஒரே முத்தம்` Tamil + English, `திருவாளர் தேசீயம்பிள்ளை`, `காகிதப்பூ`, `மணிமகுடம்`, and closed `கலைஞரின் நான்மணி மாலை` components closed unless explicitly reopened.