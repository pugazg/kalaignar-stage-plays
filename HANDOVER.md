# Kalaignar Stage Plays — Handover

Repository: `pugazg/kalaignar-stage-plays`, branch `main`.

## Startup rule

Always fetch live `main` first and preserve newer durable state. Permanent workflow: `STAGE_PLAY_PROCESSING_GUIDE.md`.

# ACTIVE WORK — திருவாளர் தேசீயம்பிள்ளை

## Mandatory startup

Read before further source-dependent work:

1. `STAGE_PLAY_PROCESSING_GUIDE.md`;
2. this `HANDOVER.md`;
3. `NEXT_CHAT_PROMPT.md`;
4. `works/thiruvalar-desiyampillai/README.md`;
5. `works/thiruvalar-desiyampillai/metadata/source.md`;
6. `works/thiruvalar-desiyampillai/indexes/page-map.md`;
7. `works/thiruvalar-desiyampillai/HISTORICAL_GLYPH_AUDIT.md`;
8. the relevant `works/thiruvalar-desiyampillai/pages/*.md` records for the current batch;
9. the controlling PDF must be attached/resolved for direct page-level visual work.

The user-supplied `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md` has been adopted into the work-level glyph audit. It is a **methodological verification guide**, not a lexical first-pass witness.

## Source identity

Controlling PDF: `TVA_BOK_0064118_திருவாளர்_தேசீயம்பிள்ளை.pdf`

- SHA-256: `b336bbebb326803badecbaa93de4ca4d63d80f68137fe70673b07a884c4910eb`;
- size: **58,035,177 bytes**;
- physical scans: **49**;
- source-visible second edition: **நவம்பர் 1965**;
- publisher: **K. R. நாராயணன்**;
- title-page address: **131, பிராட்வே சென்னை—1.**;
- printer/imprint: **முத்தமிழ்ச் செல்வி அச்சகம், 1/65, பிராட்வே.**

User-supplied catalog metadata:

- title: **திருவாளர் தேசீயம்பிள்ளை**;
- author: **கலைஞர் மு. கருணாநிதி**;
- publisher: **K. R. நாராயணன்**;
- edition: **இரண்டாம் பதிப்பு, 1965**.

User-supplied description:

> இளைஞர்களிடையே தமிழ் உணர்வும், உதயசூரியனின் தாக்கம் விரைந்து எழுவதையும் உணர்த்தும் நாடகம் இது. சமூகச் சீர்திருத்தம் தொடங்கப்பட வேண்டிய இடமே முதலில் அறியாமை படைத்த பெண்களிடம்தான் என்பதை எடுத்துச் சொல்வதாக அமைந்துள்ளது.

This is catalog context only and never substitutes for source transcription.

## Physical structure registered at intake

- scan 1: colour front cover;
- scan 2: pasted donor/gift slip (`பேராசிரியர். தி.வ. மெய்க்கண்டார் அவர்களின் அன்பளிப்பு`) — keep separate as later/library evidence;
- scan 3: title page;
- scan 4: second-edition / printing / imprint page;
- scans 5–6: publisher note `வணக்கம்.`;
- scans 7–48: dramatic work;
- scans 8–48 visibly carry printed pages **6–46**;
- scan 49: back-cover advertisement for `அல்லி விழி`.

Do not infer a printed page number for scan 7 merely from sequence.

## Scan condition

The source is image-only and materially damaged:

- substantial paper loss / white abrasion, especially in front matter;
- stains, handwriting and later ink marks;
- worn/uneven print;
- late-page purple/blue ink contamination and edge damage;
- historical Tamil typeforms / look-alike glyph risk;
- non-authorial library/donation material that must remain separate from literary text.

Do not reconstruct text that is physically missing behind damage.

## Historical-glyph verification — mandatory

Every page must apply the user-supplied historical-glyph methodology now durable in `works/thiruvalar-desiyampillai/HISTORICAL_GLYPH_AUDIT.md`.

Minimum families checked on every scan:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`.

Permanent rules:

- read character identity, not modern visual resemblance;
- controlling authority is the scan pixel evidence;
- encode proven old-glyph identity in modern Unicode only;
- preserve source spelling/grammar/vocabulary/punctuation otherwise;
- compare same-edition evidence if uncertain;
- no global replacement;
- no context-based modernization;
- if uncertainty remains, use `needs-review`;
- keep historical-glyph corrections separate from ordinary transcription corrections.

There is **no user-supplied lexical first-pass MD** for this play at intake. Do not invent one, and do not treat the glyph guide as missing-word authority.

## Current state

**SOURCE INTAKE COMPLETE / PRODUCTION NOT STARTED.**

- scans registered: **49 / 49**;
- page placeholders: **49 / 49 created** (`0001.md`–`0049.md`);
- canonical transcriptions: **0 / 49**;
- visually verified pages: **0 / 49**;
- historical-glyph passes complete: **0 / 49**;
- structural / scene inventory: **pending full source pass**;
- English translation: **not authorized / not started**.

No page is verified merely because its metadata was visually inspected during onboarding.

## Exact next activity

Process **scans 1–5** source-first.

For each scan:

1. inspect the complete native/enlarged scan;
2. transcribe only positively visible printed text;
3. separate printed text from handwriting, donor/library marks and damage;
4. run the full 13-family historical-glyph check;
5. use same-edition comparisons where useful;
6. do not reconstruct physically lost wording;
7. leave unsupported clusters `needs-review`;
8. update `indexes/page-map.md` and `HISTORICAL_GLYPH_AUDIT.md` after the batch.

Do not begin scene assembly or English translation during this page-layer phase.

# CLOSED WORK SAFEGUARDS

## காகிதப்பூ

Fully closed for the current source-first bilingual scope:

- Tamil page layer **41/41 PASS**;
- Tamil source-representation artifacts **23/23 PASS**;
- English source-representation artifacts **23/23 FINAL PASS**;
- no Scene 22/23 was invented;
- secondary-English contamination **0**.

Do not reopen it because of an older checkpoint.

`மணிமகுடம்` remains complete/closed. `கலைஞரின் நான்மணி மாலை` component works remain closed unless explicitly reopened for new source evidence or a separately authorized phase.
