# Next Chat Prompt — Kalaignar Stage Plays / இரத்தக் கண்ணீர் scans 71–80

Continue directly in `pugazg/kalaignar-stage-plays`, branch `main`, active work:

`works/iratha-kanneer/`

## LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first and preserve newer durable state.

Keep closed `ஒரே முத்தம்`, `திருவாளர் தேசீயம்பிள்ளை`, `காகிதப்பூ`, `மணிமகுடம்`, and closed `கலைஞரின் நான்மணி மாலை` work closed unless separately authorized.

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
10. `BATCH_01_REVIEW.md` through `BATCH_07_REVIEW.md`
11. relevant page records through `pages/0070.md`

Resolve / attach the controlling PDF before page-level visual work.

## Controlling source

`TVA_BOK_0064189_இரத்தக்_கண்ணீர்.pdf`

Source provenance: the user-supplied controlling PDF was downloaded from the **Tamil Digital Library (TDL)**. Treat the TDL record as provenance for this exact supplied source, not as an independent secondary textual witness.

- title: **இரத்தக் கண்ணீர்**
- author: **மு. கருணாநிதி**
- publisher: **திராவிடப் பண்ணை**
- edition: **முதல் பதிப்பு — 1953**
- physical scans: **188**
- size: **319,220,349 bytes**
- SHA-256: **`120428985bd327456df46b9e06271896b106332711f4c9063d4f0c7fe72b6441`**
- image-only; source PDF is not committed

The conversation preview exposes only **150** pages, but raw-PDF inspection confirms **188**. Never stop at 150.

## Durable checkpoint

- P0 source intake — **PASS**
- canonical page records — **70 / 188**
- initial visual verification — **70 / 188**
- post-verification historical-glyph H-GATE — **70 / 188**
- final verified — **70 / 188**
- contiguous verified range — **scans 1–70**
- Batches 01–07 — **PASS / COMPLETE**
- Batch 07 — **PASS / COMPLETE / LOCKED FOR CURRENT SOURCE EVIDENCE**
- historical-glyph corrections recorded — **18**
- unresolved page-level source issues — **0**
- scene assembly — **not started / blocked on page layer**
- English — **not authorized / not started**

Verified structure through scan 70:

- Scene 1 scans 8–13;
- Scene 2 scans 14–18;
- Scene 3 scans 19–21;
- Scene 4 scans 22–25;
- Scene 5 scans 26–29;
- Scene 6 scan 30 only;
- Scene 7 scans 31–33;
- Scene 8 scans 34–39;
- Scene 9 scans 40–41;
- Scene 10 scans 42–44;
- Scene 11 scans 45–46;
- Scene 12 scans 47–49;
- Scene 13 scans 50–51;
- Scene 14 scans 52–53;
- Scene 15 scans 54–57;
- Scene 16 scans 58–62;
- Scene 17 scans 63–65;
- Scene 18 scans 66–67;
- Scene 19 scan 68 only;
- Scene 20 begins scan 69 and continues beyond scan 70.

Do not turn this partial evidence into a final whole-work scene inventory.

## Mandatory historical-glyph gate

For every page:

1. canonical transcription;
2. initial visual verification;
3. H-GATE at enlarged/native source pixels;
4. only then final `verified` if clean.

Mandatory minimum family set:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

The family list is a minimum, not a ceiling. Batch 05 also established historical `ளா` look-alikes and future additional historical look-alikes must be adjudicated similarly. No global replacement. No spelling/grammar/punctuation modernization. OCR and expected wording are not glyph authority. Prefer same-edition comparison for doubtful clusters.

## Established historical corrections — do not regress

Eighteen corrections are recorded through scan 70. Batch-07 additions:

- scan 61 `மனிதனாயிற்றே` (`னா`) — never restore apparent `மனிதனுயிற்றே`;
- scan 61 `வேலை பார்த்தாய்` (`லை`) — never restore apparent `வேல் பார்த்தாய்`;
- scan 61 `அஞ்சல் மனைக்கு` (`னை`) — never restore apparent `அஞ்சல் மணிக்கு`;
- scan 63 `வீரப்பனா?` (`னா`) — never restore apparent `வீரப்பனு?`.

The separately source-visible scan-63 `அஞ்சல் மண் வேலையை` remains authoritative and must not be globally replaced.

## Exact next activity — Batch 08 split into three activities

Batch 08 is deliberately split so ordinary source transcription and historical-glyph adjudication do not contaminate one another.

### Activity 1 — scan 75 glyph adjudication

**COMPLETE as working source evidence.** Lock scan-75 reading `அவனை` (`னை`). This is not yet a durable page-count advance because `pages/0075.md` has not been committed.

### Activity 2 — ACTIVE / do this next

1. create `pages/0071.md` through `0080.md`;
2. establish scan-70 continuation from scan 71 pixels only;
3. transcribe all ten scans directly from source pixels;
4. perform ordinary initial visual verification only;
5. after initial PASS but before H-GATE, keep each page exactly as `status: needs-review`, `initial_verification: passed`, `historical_glyph_gate: pending`;
6. preserve Scene 20 closure on scan 75 and Scene 21 scans 76–80, closing on scan 80;
7. do **not** create `BATCH_08_REVIEW.md` yet and do **not** promote pages to final `verified`.

### Activity 3 — only after Activity 2 is committed

Run the separate full H-GATE on scans 71–80, including the complete mandatory family set and any additional look-alikes. Working candidates isolated for this activity include scan 77 apparent `மலபோல்` → source-supported `மலைபோல்` (`லை`) and scan 78 apparent `வீரனில்ல` → source-supported `வீரனில்லை` (`லை`). Record only corrections actually proven by source pixels. Then create `BATCH_08_REVIEW.md`, update page map/glyph audit/READMEs/handover/prompt, and fetch final live `main` SHA.

Do not begin scene assembly or English translation merely because Batch 08 completes.