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
8. the supplied controlling PDF for source-dependent page work.

## Source identity / intake state

Controlling PDF: `TVA_BOK_0064325_ஒரே_முத்தம்.pdf`

- file size: **224,884,964 bytes**;
- physical scans: **131**;
- SHA-256: **PENDING — compute from the exact supplied PDF; never invent**;
- source PDF committed to repository: **no**.

Source-visible identity already registered:

- scan 1: `ஒரே முத்தம்` cover;
- scan 3: `தென்றல் வெளியீடு 3.`, `ஒரே முத்தம்`, `சரித்திரக் கற்பனை நாடகம்.`, author `கலைஞர், மு. கருணாநிதி எம். எல். ஏ.`, `ஐந்தாம் பதிப்பு`, sales-rights block for `பாபு நிலையம், 59, பிராட்வே, சென்னை-1.`;
- scan 4: edition/publication page, fifth-edition sequence reaches **1964**, publisher `தென்றல் நூற்பதிப்புக் கழகம்`, price `விலை ரூபா 2-00.`;
- scan 5: `பதிப்புரை`;
- scan 6: `முன்னுரை`, dated `சென்னை, 25-5-1950`, signed `மு. கருணாநிதி.` and source-visible Sri Lankan historical-fragment basis;
- scan 7: `நாடக உறுப்பினர்` cast list;
- scan 8: dramatic body begins with `காட்சி 1.` at printed p.6;
- scan 130: printed p.128, final dramatic page;
- scan 131: back-cover publisher advertisement.

User-supplied catalog context:

- title: **ஒரே முத்தம்**;
- author: **கலைஞர் மு. கருணாநிதி**;
- publisher: **தென்றல் நூற்பதிப்புக் கழகம்**;
- edition/year: **ஐந்தாம் பதிப்பு, 1964**;
- historical basis: a small fragment of a Sri Lankan historical event;
- catalog performance context: staged by Devi Nataka Sabha;
- catalog thematic context: caste abolition.

Catalog context is not transcription authority.

## Pagination / work extent

- scans **1–7**: front matter;
- scans **8–130**: dramatic work;
- scan **131**: back-cover advertisement;
- visible anchors: scan 8 = p.6, scan 125 = p.123, scan 130 = p.128;
- scans 8–130 → pp.6–128 is registered provisionally and must be confirmed page-by-page.

## Historical Tamil glyph gate

Every processed scan must receive the full family check:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

Rules:

- scan pixels control;
- read character identity, not modern visual resemblance;
- no global replacement;
- no spelling/grammar/punctuation normalization;
- no semantic repair of unclear pixels;
- same-edition references may be built only from positively verified source examples;
- uncertain readings remain explicit `needs-review` / unresolved markers.

## Current metrics

- source scans registered: **131 / 131**;
- checksum: **pending**;
- page records created: **0 / 131**;
- source transcription processed: **0 / 131**;
- visually verified: **0 / 131**;
- historical-glyph passes: **0 / 131**;
- structural/scene inventory: **not started**;
- Tamil assembly: **not started**;
- English translation: **not authorized / not started**.

## Exact next activity

1. compute and record the exact controlling PDF SHA-256;
2. process source scans **1–5** only;
3. create `works/ore-mutham/pages/0001.md` through `0005.md`;
4. perform full visual/source fidelity and all 13 historical-glyph family checks on each;
5. separate donor/library/handwritten marks from printed publication text;
6. update page map, glyph audit, work/root README, handover and next-chat prompt;
7. do not begin scene assembly or English translation.

# CLOSED WORK SAFEGUARDS

## திருவாளர் தேசீயம்பிள்ளை

Remains **COMPLETE / CLOSED FOR CURRENT SOURCE EVIDENCE**: Tamil source processing 49/49, historical-glyph passes 49/49, 7/7 Tamil SRUs assembled/reviewed, independent English 7/7 reviewed, 4/4 English batches PASS/LOCKED, final `TRANSLATION_REVIEW.md` PASS. Its nine Tamil source-condition holds remain closed unless new source evidence is supplied.

`காகிதப்பூ`, `மணிமகுடம்`, and closed `கலைஞரின் நான்மணி மாலை` component works remain closed unless explicitly reopened.
