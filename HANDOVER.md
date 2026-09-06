# Kalaignar Stage Plays — Handover

Repository: `pugazg/kalaignar-stage-plays`, branch `main`.

## Startup rule

Always fetch live `main` first and preserve newer durable state. Permanent workflow: `STAGE_PLAY_PROCESSING_GUIDE.md`.

# ACTIVE WORK — ஒரே முத்தம்

Work path: `works/ore-mutham/`.

## Mandatory startup

Read before further work:

1. `STAGE_PLAY_PROCESSING_GUIDE.md`;
2. this `HANDOVER.md`;
3. `NEXT_CHAT_PROMPT.md`;
4. `works/ore-mutham/README.md`;
5. `works/ore-mutham/metadata/source.md`;
6. `works/ore-mutham/indexes/page-map.md`;
7. `works/ore-mutham/HISTORICAL_GLYPH_AUDIT.md`;
8. relevant existing `works/ore-mutham/pages/*.md` records;
9. the supplied controlling PDF for source-dependent page work.

## Source identity / intake state

Controlling PDF: `TVA_BOK_0064325_ஒரே_முத்தம்.pdf`

- file size: **224,884,964 bytes**;
- physical scans: **131**;
- SHA-256: **PENDING exact byte-level computation — never invent**;
- source PDF committed to repository: **no**.

Source-visible identity:

- scan 1: `ஒரே முத்தம்` cover;
- scan 3: `தென்றல் வெளியீடு. 3.`, `ஒரே முத்தம்`, `சரித்திரக் கற்பனை நாடகம்.`, author `கலைஞர், மு. கருணாநிதி எம். எல். ஏ.`, `ஐந்தாம் பதிப்பு.` and sales-rights block;
- scan 4: edition history reaches fifth edition **December 1964**, publisher `தென்றல் நூற்பதிப்புக் கழகம்.`, printer `செந்தமிழ் அச்சகம்`, price `விலை ரூபா 2-00.`;
- scan 5: `பதிப்புரை.` publisher note;
- scan 6: `முன்னுரை`, dated `சென்னை, 25-5-1950`, signed `மு. கருணாநிதி.` and source-visible Sri Lankan historical-fragment basis;
- scan 7: `நாடக உறுப்பினர்` cast list;
- scan 8: dramatic body begins with `காட்சி 1.` at printed p.6;
- scan 130: printed p.128, final dramatic page;
- scan 131: back-cover publisher advertisement.

User catalog context remains separate from transcription authority: historical drama based on a small Sri Lankan historical fragment; staged by Devi Nataka Sabha; addresses caste abolition.

## Pagination / work extent

- scans **1–7**: front matter;
- scans **8–130**: dramatic work;
- scan **131**: back-cover advertisement;
- scans 8–130 → pp.6–128 is provisional until each printed numeral is visually checked.

## Historical Tamil glyph gate

Every processed scan must receive the full family check:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

Permanent rules:

- source pixels control;
- read character identity, not modern resemblance;
- no global replacement;
- no spelling/grammar/punctuation normalization;
- no semantic repair of unclear pixels;
- same-edition references only from positively verified examples;
- uncertain readings remain explicit `needs-review` / unresolved markers.

## Batch 1 checkpoint — scans 1–5

Created:

- `pages/0001.md` — **needs-review**: principal title secure; stylized vertical cover lettering and tiny signature unresolved;
- `pages/0002.md` — **verified**: donor/library slip fully read and separated;
- `pages/0003.md` — **verified**: title page fully checked;
- `pages/0004.md` — **verified**: edition/publication/imprint page fully checked;
- `pages/0005.md` — **needs-review**: `பதிப்புரை.` heading and publisher close secure; dense body requires enlarged line-by-line source review.

First secure same-edition reference bank:

- `லை`: scan 3 `கலைஞர்`, scan 4 `விலை`;
- `ணா`: scan 3 `கருணாநிதி`;
- `னை`: scan 3 `விற்பனை`, `சென்னை`; scan 4 `சென்னை`.

No global replacement is authorized from these examples.

## Current metrics

- source scans registered: **131 / 131**;
- checksum: **pending**;
- page records created: **5 / 131**;
- source scans processed: **5 / 131**;
- visually verified: **3 / 131** (`2, 3, 4`);
- `needs-review`: **2 / 131** (`1, 5`);
- completed historical-glyph passes: **3 / 131** (`2, 3, 4`);
- scan 1 full text/glyph gate: **open**;
- scan 5 full text/glyph gate: **open**;
- structural/scene inventory: **not started**;
- Tamil assembly: **not started**;
- English translation: **not authorized / not started**.

## Exact next activity

Process scans **6–10** source-first:

1. create `pages/0006.md` through `0010.md`;
2. inspect source-visible text, scene headings, speaker labels and marks directly;
3. perform the complete 13-family historical-glyph gate on each;
4. confirm printed page numerals on body scans 8–10 rather than inferring them;
5. keep scan 1 and scan 5 holds open unless enlarged pixels genuinely resolve them;
6. compute and record the exact PDF SHA-256 when byte-level hashing becomes available; do not invent a value;
7. synchronize page map, glyph audit, work/root README, this handover and `NEXT_CHAT_PROMPT.md`;
8. do not begin scene assembly or English translation.

# CLOSED WORK SAFEGUARDS

## திருவாளர் தேசீயம்பிள்ளை

Remains **COMPLETE / CLOSED FOR CURRENT SOURCE EVIDENCE**: Tamil source processing 49/49, historical-glyph passes 49/49, 7/7 Tamil SRUs assembled/reviewed, independent English 7/7 reviewed, 4/4 English batches PASS/LOCKED, final `TRANSLATION_REVIEW.md` PASS. Its nine Tamil source-condition holds remain closed unless new source evidence is supplied.

`காகிதப்பூ`, `மணிமகுடம்`, and closed `கலைஞரின் நான்மணி மாலை` component works remain closed unless explicitly reopened.
