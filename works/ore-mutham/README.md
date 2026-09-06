# ஒரே முத்தம்

Archive slug: `ore-mutham`.

## Current status

**ACTIVE — SOURCE INTAKE OPEN. 131 PHYSICAL SCANS REGISTERED; PAGE TRANSCRIPTION / HISTORICAL-GLYPH PASS NOT YET STARTED.**

Controlling source: `TVA_BOK_0064325_ஒரே_முத்தம்.pdf`.

- file size: **224,884,964 bytes**;
- physical scans: **131**;
- SHA-256: **PENDING — must be computed before source intake is called fully closed**;
- source PDF committed to repository: **no**.

## User-supplied catalog metadata

- title: **ஒரே முத்தம்**
- author: **கலைஞர் மு. கருணாநிதி**
- publisher: **தென்றல் நூற்பதிப்புக் கழகம்**
- edition/year: **ஐந்தாம் பதிப்பு, 1964**

User-supplied catalog description:

> இலங்கையில் நிகழ்ந்த ஒரு வரலாற்று நிகழ்வின் சிறு சிதறலை அடிப்படையாகக் கொண்டு எழுதப்பட்ட வரலாற்று நாடகம் இது. தேவி நாடக சபையினரால் நிகழ்த்தப்பட்டது. சாதி ஒழிப்பு குறித்தும் இந்நாடகம் பேசுகிறது.

This is catalog/context metadata. It does not substitute for source transcription or source-visible dramatic structure.

## Source-visible identification at intake

- scan 1: front cover with **`ஒரே முத்தம்`**;
- scan 3: **`தென்றல் வெளியீடு 3.`**, title **`ஒரே முத்தம்`**, descriptor **`சரித்திரக் கற்பனை நாடகம்.`**, author line **`கலைஞர், மு. கருணாநிதி எம். எல். ஏ.`**, **`ஐந்தாம் பதிப்பு`**, and sales-rights block for **`பாபு நிலையம், 59, பிராட்வே, சென்னை-1.`**;
- scan 4: edition-history / publication-imprint page; the sequence visibly reaches the fifth edition in **1964**, publisher **`தென்றல் நூற்பதிப்புக் கழகம்`**, and price **`விலை ரூபா 2-00.`**;
- scan 5: `பதிப்புரை`;
- scan 6: author `முன்னுரை`, dated **`சென்னை, 25-5-1950`**, signed **`மு. கருணாநிதி.`**; it states that the play was built from a small fragment of history that occurred in Sri Lanka;
- scan 7: `நாடக உறுப்பினர்` / cast list;
- scan 8: dramatic body begins with source-visible **`காட்சி 1.`**, printed page **6**;
- scan 130: printed page **128**, final dramatic page with decorative close;
- scan 131: back-cover publisher advertisement / book list.

## Source extent / pagination

- scans **1–7**: front matter;
- scans **8–130**: dramatic work;
- scan **131**: back-cover advertisement;
- printed-page anchors currently confirmed: scan 8 = p.6, scan 125 = p.123, scan 130 = p.128;
- the apparent sequential mapping scans 8–130 → printed pp.6–128 is registered provisionally and must be confirmed page-by-page during source processing.

See `metadata/source.md` and `indexes/page-map.md`.

## Source-first safeguards

The supplied scan is controlling authority. OCR, later editions, web text, common spelling, contextual expectation and published translations are not transcription authority.

Historical Tamil glyphs must be decoded by character identity before modern Unicode transcription. The mandatory full-page family check is:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

No global replacement or spelling modernization is allowed. See `HISTORICAL_GLYPH_AUDIT.md` and root `STAGE_PLAY_PROCESSING_GUIDE.md`.

## Current progress

- source scans registered: **131 / 131**;
- checksum: **pending**;
- per-scan page records created: **0 / 131**;
- source transcription processed: **0 / 131**;
- visually verified: **0 / 131**;
- historical-glyph passes: **0 / 131**;
- structural/scene inventory: **not started**;
- Tamil scene/source-representation assembly: **not started**;
- English translation: **not authorized / not started**.

## Exact next activity

1. compute and record the controlling PDF SHA-256 without guessing;
2. create/process page records for **scans 1–5** source-first;
3. perform the full 13-family historical-glyph pass on every processed scan;
4. keep donor/library marks, damage and printed publication text separated;
5. update `indexes/page-map.md`, `HISTORICAL_GLYPH_AUDIT.md`, this README, root status, handover and next-chat prompt.

Do not begin dramatic-scene assembly or English translation during the page-source pass.
