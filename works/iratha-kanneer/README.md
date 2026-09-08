# இரத்தக் கண்ணீர்

Archive slug: `iratha-kanneer`.

## Current status

**P0 SOURCE INTAKE PASS / WORKFLOW INITIALIZED — 188 / 188 PHYSICAL SCANS CONFIRMED; TAMIL TRANSCRIPTION NOT STARTED; POST-INITIAL-VERIFICATION HISTORICAL-GLYPH GATE MANDATORY.**

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

The conversation file preview currently exposes only the first 150 page images. That preview is not authoritative for physical range. The attached raw PDF was opened directly and contains **188** pages; processing must continue through scan 188.

## Source-visible intake structure

Direct intake inspection establishes:

- scan 1 — illustrated front cover;
- scan 2 — title / author / publisher title page;
- scan 3 — edition / rights / price / printer-imprint page; visibly states `முதல் பதிப்பு—1953`;
- scan 4 — `பதிப்புரை`, carrying an internal date `14-4-1948` relating the earlier `முரசொலி` serial history; this internal date is not substituted for the edition year;
- scan 5 — `முன்னுரை`, signed `மு. கருணாநிதி`, dated `திருச்சி மத்திய சிறை / 20-11-53`;
- scans 6–7 — `நுழைவாய்`;
- scan 8 — source heading `இரத்தக் கண்ணீர் [நாடகம்]` and `காட்சி 1]`;
- late-work spot checks show `காட்சி 59]` at scan 180, `காட்சி 60]` at scan 183, `காட்சி 61]` at scan 184;
- scan 186 — source-visible `முடிவு` and closing prose;
- scan 187 — publisher catalogue advertisement headed `கலைஞர் கருணாநிதியின் கருத்தோவியங்கள்.`;
- scan 188 — back wrapper / `திராவிடப் பண்ணை` device and English wrapper-printer line.

A complete scene-boundary inventory is **not yet closed**. The late scene-number spot checks are intake evidence only; page-level processing comes first.

## Mandatory historical Tamil glyph workflow

This 1953 source visibly uses historical Tamil metal-type forms. The following repository authorities are mandatory:

1. `../../HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`;
2. `../../HISTORICAL_TAMIL_GLYPH_GATE.md`;
3. this work's `HISTORICAL_GLYPH_AUDIT.md`.

For this work, **initial verification is not final verification**.

Required page sequence:

1. canonical transcription from source pixels;
2. initial visual verification of text / punctuation / speaker labels / stage directions / layout;
3. keep page `needs-review` while the historical-glyph gate is pending;
4. run H-GATE against the complete mandatory family set;
5. only after H-GATE PASS, and if no other source issue remains, promote the page to `verified`.

Mandatory minimum family set:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

No global replacement. No modernization. Same-edition source pixels control character identity.

## Page-status convention for this work

After ordinary visual verification but before H-GATE:

```yaml
status: "needs-review"
initial_verification: "passed"
historical_glyph_gate: "pending"
```

Final page closure:

```yaml
status: "verified"
initial_verification: "passed"
historical_glyph_gate: "passed"
```

An unresolved historical-type cluster leaves the page `needs-review`; a physically unreadable locus may become `blocked` only after normal difficult-reading escalation.

## Phase order

- P0 source intake — **PASS**;
- P1 page transcription — **NOT STARTED**;
- P2 initial visual verification — **NOT STARTED**;
- H-GATE historical Tamil glyph audit — **NOT STARTED**;
- final page verification — **NOT STARTED**;
- structural / scene assembly — blocked until page layer is sufficiently mature;
- English translation — not authorized / not started.

## Exact next activity

Process the first source batch **scans 1–10** page by page:

1. create canonical page records;
2. perform initial visual verification;
3. run the post-verification historical-glyph gate on each applicable Tamil page;
4. promote only H-GATE-passed clean pages to final `verified`;
5. update `indexes/page-map.md` and `HISTORICAL_GLYPH_AUDIT.md`.

Do not skip scans 1–7 merely because they are front matter, and do not use OCR as historical-glyph authority.
