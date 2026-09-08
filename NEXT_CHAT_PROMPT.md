# Next Chat Prompt — Kalaignar Stage Plays / இரத்தக் கண்ணீர் scans 21–30

Continue directly in `pugazg/kalaignar-stage-plays`, branch `main`, active work:

`works/iratha-kanneer/`

## LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first and preserve newer durable state.

`ஒரே முத்தம்` is closed for both Tamil and English. Do not reopen it from an older prompt. Also keep closed `திருவாளர் தேசீயம்பிள்ளை`, `காகிதப்பூ`, `மணிமகுடம்`, and closed `கலைஞரின் நான்மணி மாலை` work closed unless separately authorized.

## Mandatory startup

Read completely before source-dependent work:

1. `STAGE_PLAY_PROCESSING_GUIDE.md`
2. `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`
3. `HISTORICAL_TAMIL_GLYPH_GATE.md`
4. root `HANDOVER.md`
5. this `NEXT_CHAT_PROMPT.md`
6. `works/iratha-kanneer/README.md`
7. `works/iratha-kanneer/metadata/source.md`
8. `works/iratha-kanneer/indexes/page-map.md`
9. `works/iratha-kanneer/HISTORICAL_GLYPH_AUDIT.md`
10. `works/iratha-kanneer/BATCH_01_REVIEW.md`
11. `works/iratha-kanneer/BATCH_02_REVIEW.md`
12. relevant page records `pages/0001.md`–`0020.md` as needed

Resolve / attach the controlling PDF before page-level visual work.

## Controlling source

`TVA_BOK_0064189_இரத்தக்_கண்ணீர்.pdf`

Recorded identity:

- title: **இரத்தக் கண்ணீர்**
- author: **மு. கருணாநிதி**
- publisher: **திராவிடப் பண்ணை**
- edition: **முதல் பதிப்பு — 1953**
- physical scans: **188**
- size: **319,220,349 bytes**
- SHA-256: **`120428985bd327456df46b9e06271896b106332711f4c9063d4f0c7fe72b6441`**
- image-only
- source PDF is not committed

Important: the conversation preview exposes only **150** pages, but direct raw-PDF inspection confirms **188 physical scans**. The raw count controls. Never stop at 150 because of preview truncation.

## Durable checkpoint

- P0 source intake — **PASS**
- canonical page records — **20 / 188**
- initial visual verification — **20 / 188**
- post-verification historical-glyph H-GATE — **20 / 188**
- final verified — **20 / 188**
- contiguous verified range — **scans 1–20**
- Batch 01 — **PASS / COMPLETE**, including retrospective scan-9 correction/re-pass
- Batch 02 — **PASS / COMPLETE / LOCKED FOR CURRENT SOURCE EVIDENCE**
- historical-glyph corrections recorded — **6**
- unresolved page-level source issues — **0**
- scene assembly — **not started / blocked on page layer**
- English — **not authorized / not started**

Verified structure so far:

- Scene 1 begins scan 8 and closes scan 13;
- Scene 2 begins scan 14 and closes scan 18;
- Scene 3 begins scan 19 and continues beyond scan 20.

Do not turn this partial evidence into a final whole-work scene inventory.

## Mandatory historical-glyph gate

User directive: historical Tamil glyph checking must occur **after initial verification**.

For each applicable page:

1. canonical transcription;
2. initial visual verification;
3. keep `status: needs-review` while H-GATE is pending;
4. run H-GATE at enlarged/native source pixels;
5. only after H-GATE PASS, and if no other issue remains, promote to final `verified`.

Minimum family set to check on every applicable page:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

Read character identity, not modern visual resemblance. No global replacement. No spelling/grammar/punctuation modernization. OCR and expected wording are not glyph authority. Unresolved identities remain `needs-review`.

## Established historical corrections — do not regress

- scan 9: `வயதுடையவனா அல்லது கிழவனா` (`னா`) is authoritative; never restore `...வனு ...கிழவனு`;
- scan 11: `அஞ்சல் மனையில்` (`னை`);
- scans 12 and 16: `அஞ்சல் மனை` (`னை`);
- scan 17: `மருத்துவக் கிழவனார்` (`னா`);
- scan 18: `ஏன் வந்தேனா?` (`னா`).

These are historical character identities, not modernization precedents.

## Exact next activity — scans 21–30 / Batch 03

Process **scans 21–30** step by step in this iteration:

1. create `works/iratha-kanneer/pages/0021.md` through `0030.md`;
2. transcribe each physical scan directly from source pixels;
3. perform initial visual verification;
4. run the separate historical-glyph H-GATE after initial verification;
5. finalize page status only after the gate;
6. record every glyph correction / unresolved locus explicitly;
7. create `works/iratha-kanneer/BATCH_03_REVIEW.md` only when scans 21–30 have completed the gate;
8. update page map, glyph audit and work README;
9. synchronize root README, `HANDOVER.md`, and this next-chat prompt;
10. fetch final live `main` SHA.

Do not begin scene assembly or English translation merely because Batch 03 completes.