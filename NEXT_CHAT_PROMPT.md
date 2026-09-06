# Next Chat Prompt — Kalaignar Stage Plays / ஒரே முத்தம்

Continue directly in `pugazg/kalaignar-stage-plays`, branch `main`, active work `works/ore-mutham/`.

## LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first and preserve newer durable state. Do not reopen closed `திருவாளர் தேசீயம்பிள்ளை`, `காகிதப்பூ`, `மணிமகுடம்`, or `கலைஞரின் நான்மணி மாலை` work because an older prompt contains a stale checkpoint.

## Mandatory startup

Read before any source-dependent change:

1. `STAGE_PLAY_PROCESSING_GUIDE.md`
2. `HANDOVER.md`
3. this `NEXT_CHAT_PROMPT.md`
4. `works/ore-mutham/README.md`
5. `works/ore-mutham/metadata/source.md`
6. `works/ore-mutham/indexes/page-map.md`
7. `works/ore-mutham/HISTORICAL_GLYPH_AUDIT.md`
8. controlling PDF `TVA_BOK_0064325_ஒரே_முத்தம்.pdf`

## Source checkpoint

- filename: `TVA_BOK_0064325_ஒரே_முத்தம்.pdf`
- file size: **224,884,964 bytes**
- physical scans: **131**
- SHA-256: **PENDING — compute from this exact PDF before calling intake complete**
- source PDF committed to repository: **no**

Source-visible intake:

- scan 1: `ஒரே முத்தம்` cover;
- scan 2: donor/library slip;
- scan 3: `தென்றல் வெளியீடு 3.`, title `ஒரே முத்தம்`, `சரித்திரக் கற்பனை நாடகம்.`, `கலைஞர், மு. கருணாநிதி எம். எல். ஏ.`, `ஐந்தாம் பதிப்பு`, `பாபு நிலையம், 59, பிராட்வே, சென்னை-1.`;
- scan 4: edition/publication page; fifth-edition sequence reaches **1964**; publisher `தென்றல் நூற்பதிப்புக் கழகம்`; price `விலை ரூபா 2-00.`;
- scan 5: `பதிப்புரை`;
- scan 6: `முன்னுரை`, dated `சென்னை, 25-5-1950`, signed `மு. கருணாநிதி.`; source-visible statement that the drama takes a small fragment of Sri Lankan history as its basis;
- scan 7: `நாடக உறுப்பினர்` cast list;
- scan 8: dramatic body begins with `காட்சி 1.` at printed p.6;
- scan 130: printed p.128 and final dramatic page;
- scan 131: back-cover publisher advertisement.

## User catalog context

- title: **ஒரே முத்தம்**
- author: **கலைஞர் மு. கருணாநிதி**
- publisher: **தென்றல் நூற்பதிப்புக் கழகம்**
- edition/year: **ஐந்தாம் பதிப்பு, 1964**
- catalog description: historical drama based on a small fragment of a Sri Lankan event; staged by Devi Nataka Sabha; also addresses caste abolition.

Treat the catalog description as context, not word-for-word source authority.

## Work extent / pagination

- scans **1–7**: front matter;
- scans **8–130**: dramatic body;
- scan **131**: back-cover advertisement;
- confirmed printed anchors: scan 8 = p.6, scan 125 = p.123, scan 130 = p.128;
- scans 8–130 → pp.6–128 is provisional until every page is visually verified.

## Mandatory historical-glyph methodology

Source pixels control. Read character identity, not modern resemblance.

Full family check on every processed scan:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

No global replacement. No spelling, grammar, punctuation, speaker-label or scene-heading normalization. No context-based repair. Build same-edition reference examples only from positively verified source pixels. If unresolved, use `needs-review` / explicit unresolved markers.

## Current metrics

- physical scans registered: **131 / 131**
- checksum: **pending**
- page records: **0 / 131**
- source processing: **0 / 131**
- visually verified: **0 / 131**
- historical-glyph passes: **0 / 131**
- structural inventory: **not started**
- scene assembly: **not started**
- English translation: **not authorized / not started**

## Exact next activity

Process **scans 1–5** source-first, but first compute the exact PDF SHA-256 and record it in the source metadata.

For scans 1–5:

1. create `pages/0001.md` through `pages/0005.md`;
2. inspect direct source pixels / enlarged source as required;
3. transcribe publication text without normalization;
4. separate donor/library/handwritten marks and physical damage from authorial/printed text;
5. run the complete 13-family historical-glyph pass on each scan;
6. mark `verified` only if full visual + glyph gate passes; otherwise use `needs-review`;
7. synchronize `indexes/page-map.md`, `HISTORICAL_GLYPH_AUDIT.md`, work/root README, `HANDOVER.md`, and this prompt;
8. fetch final live `main` SHA.

Do not begin structural assembly or English translation.

## Closed-work safeguard — திருவாளர் தேசீயம்பிள்ளை

It remains **COMPLETE / CLOSED**: 49/49 Tamil source processing, 49/49 historical-glyph passes, 7/7 Tamil SRUs reviewed, independent English 7/7 reviewed, 4/4 batches PASS/LOCKED, final English review PASS. Its nine source-condition holds are not to be reopened without new source evidence.
