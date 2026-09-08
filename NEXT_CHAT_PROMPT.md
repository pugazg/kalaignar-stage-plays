# Next Chat Prompt — Kalaignar Stage Plays / இரத்தக் கண்ணீர் scans 1–10

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
10. relevant page records once created

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

Important: the conversation preview exposes only **150** pages, but direct raw-PDF inspection confirms **188** physical scans. The raw count controls. Never stop at 150 because of preview truncation.

## Durable checkpoint

- P0 source intake — **PASS**
- canonical page records — **0 / 188**
- initial visual verification — **0 / 188**
- post-verification historical-glyph H-GATE — **0 / 188**
- final verified — **0 / 188**
- scene assembly — **not started**
- English — **not authorized / not started**

Intake structure includes scans 1 cover, 2 title page, 3 first-edition/imprint page, 4 `பதிப்புரை`, 5 `முன்னுரை`, 6–7 `நுழைவாய்`, and scan 8 `இரத்தக் கண்ணீர் [நாடகம்]` / `காட்சி 1]`. Late intake spot checks show scenes 59–61 and a source `முடிவு`, but no final scene inventory is authorized yet.

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

## Exact next activity — first 10 scans

Process **scans 1–10** step by step in this iteration:

1. create `works/iratha-kanneer/pages/0001.md` through `0010.md`;
2. transcribe or archivally describe each physical scan from the source;
3. perform initial visual verification;
4. run the separate historical-glyph H-GATE after initial verification;
5. finalize page status only after the gate;
6. update page map and glyph audit;
7. synchronize work README, root handover and next-chat prompt;
8. fetch final live `main` SHA.

Do not begin scene assembly or English translation.
