# Kalaignar Stage Plays — Handover

Repository: `pugazg/kalaignar-stage-plays`, branch `main`.

## Startup rule

Always fetch live `main` first and preserve newer durable state.

Permanent source-first workflow: `STAGE_PLAY_PROCESSING_GUIDE.md`.

Historical-type authority:

1. `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`;
2. `HISTORICAL_TAMIL_GLYPH_GATE.md`.

# CURRENT CHECKPOINT — இரத்தக் கண்ணீர் ACTIVE / SCANS 1–110 VERIFIED

Active work: `works/iratha-kanneer/`.

Controlling source: `TVA_BOK_0064189_இரத்தக்_கண்ணீர்.pdf`.

Source provenance: the user-supplied controlling PDF was downloaded from the **Tamil Digital Library (TDL)**. The TDL catalogue/record documents provenance for this exact supplied source; it is **not an independent secondary textual witness** and must not be treated as one.

Current durable state:

- P0 source intake: **PASS**;
- physical scans: **188 / 188 confirmed**;
- canonical page transcription: **110 / 188**;
- initial visual verification: **110 / 188**;
- historical-glyph H-GATE: **110 / 188**;
- final verified pages: **110 / 188**;
- contiguous final-verified range: **scans 1–110**;
- Batches 01–11: **PASS / COMPLETE**;
- Batch 11: **PASS / COMPLETE / LOCKED FOR CURRENT SOURCE EVIDENCE**;
- historical-glyph corrections recorded: **23**;
- unresolved page-level source issues: **0**;
- `needs-review`: **0**;
- `blocked`: **0**;
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
10. `BATCH_01_REVIEW.md` through `BATCH_11_REVIEW.md`;
11. relevant page records through `pages/0110.md`.

Resolve the controlling PDF before page-level visual work. Do not substitute OCR, web text, later editions or memory for source pixels.

## Source identity

- title **இரத்தக் கண்ணீர்**;
- author **மு. கருணாநிதி**;
- publisher **திராவிடப் பண்ணை**;
- edition **முதல் பதிப்பு — 1953**;
- SHA-256 `120428985bd327456df46b9e06271896b106332711f4c9063d4f0c7fe72b6441`;
- size **319,220,349 bytes**;
- image-only; source PDF not committed.

## Verified structural evidence through scan 110

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
- Scene 20: scans 69–75;
- Scene 21: scans 76–80;
- Scene 22: scan 81 only;
- Scene 23: scans 82–83;
- Scene 24: scan 84 only;
- Scene 25: scans 85–88;
- Scene 26: scans 89–90;
- Scene 27: scans 91–94;
- Scene 28: scans 95–96;
- Scene 29: scans 97–98;
- Scene 30: scans 99–100;
- Scene 31: scans 101–104;
- Scene 32: scans 105–106;
- Scene 33: scan 107 only;
- Scene 34: scans 108–110.

Do not declare a final whole-work scene inventory until the page layer closes.

## Historical-glyph gate

Required order:

**canonical transcription → initial visual verification → H-GATE → final verification.**

Mandatory minimum family set:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`.

The list is a minimum, not a closed universe: Batch 05 additionally confirmed historical `ளா` look-alikes. Source pixels control. No global replacement. No grammar/spelling modernization. Same-edition comparison is preferred for doubtful clusters. Unresolved identity stays `needs-review`.

## Historical-glyph corrections through scan 110

Twenty-three corrections are durably recorded in `works/iratha-kanneer/HISTORICAL_GLYPH_AUDIT.md`.

Latest correction-ledger additions remain Batch 09:

21. scan 84 `முத்தனு?` → `முத்தனா?` (`னா`);
22. scan 84 `நல்லவனு யிற்றே` → `நல்லவனாயிற்றே` (`னா`);
23. scan 86 `இப்படித்தானு?` → `இப்படித்தானா?` (`னா`).

Batch 09 resolved the difficult scan-82 passage directly from source pixels as `ஏழையின் குரல் எஜமானின் காதில் எப்படி கேட்கும்?`, verified the physical split scan 82 `சேர்ந்` → scan 83 `துள்ள`, and corrected ordinary source-transcription mismatches documented in `works/iratha-kanneer/BATCH_09_REVIEW.md`. Those ordinary corrections are separate from the historical-glyph count.

Batch 10 added no new correction-ledger entry. Secure source witnesses include scan 92 `புறாக்கள்` (`றா`), `அவள்தானா?` / `மாயனால்` (`னா`), scan 95 `வீணை` (`ணை`), `என்னால்` / `மறப்பேனா` (`னா`) and `பேசினாள்` (supplemental `ளா`). The difficult scan-97 opening is resolved as `மாயங்காத சாமியார்`. Physical continuations `அசை` → `யாமல்` (91→92) and `வண்டுகளாக` → `வும்` (95→96) are preserved.

Batch 11 added **no new correction-ledger entry**, so the total remains **23**. Secure positive witnesses include scan 101 `கண்ணை` (`ணை`) and `கிழவனானான்` (`னா`), scan 107 `கண்ணாடி` (`ணா`), and scan 110 `என்னால்` (`னா`). Source-sensitive readings retained include scan 103 `தீண்டேன் தீண்டேன்`, scan 104 `சமாதான மடைந்துவிடுவார்`, scan 106 `நில விலங்கு` / `ஆறுதலாகயிருந்தது`, scan 107 `ஐம்பது கல்` / `ஆனந்த நகரில்`, scan 108 `வேரை`, and scan 109 `பாழும் பொருளாசையால்` / `அவர்கள் சுயநலம்`.

Source-sensitive scan 81 `அஞ்சல் மண்ணில் தான்` remains authoritative and must not be globally replaced from earlier `அஞ்சல் மனை` decisions.

## Exact next activity — Batch 12 / scans 111–120

Process scans **111–120** as the next ten-scan page batch:

1. resolve the controlling PDF and inspect native/enlarged source pixels;
2. create `pages/0111.md` through `0120.md` with direct source transcription;
3. establish any scan-110→111 continuation from scan-111 source pixels only;
4. complete ordinary initial visual verification;
5. run the separate full H-GATE on every page, covering the mandatory family set plus any additional historical look-alikes;
6. preserve source spelling, punctuation, scene structure and physical scan-boundary continuations; no global replacement or silent modernization;
7. promote only clean pages to final `verified`;
8. create `BATCH_12_REVIEW.md` and synchronize `indexes/page-map.md`, `HISTORICAL_GLYPH_AUDIT.md`, READMEs, this handover and `NEXT_CHAT_PROMPT.md`;
9. fetch and report final live `main` SHA.

Do not begin scene assembly or English translation merely because Batch 12 completes.

# CLOSED WORK SAFEGUARDS

Keep completed `ஒரே முத்தம்` Tamil + English, `திருவாளர் தேசீயம்பிள்ளை`, `காகிதப்பூ`, `மணிமகுடம்`, and closed `கலைஞரின் நான்மணி மாலை` components closed unless explicitly reopened with genuinely new source evidence or a separately authorized phase.
