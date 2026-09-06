# Kalaignar Stage Plays — Handover

Repository: `pugazg/kalaignar-stage-plays`, branch `main`.

## Startup rule

Always fetch live `main` first and preserve newer durable state. Permanent workflow: `STAGE_PLAY_PROCESSING_GUIDE.md`.

# ACTIVE WORK — ஒரே முத்தம்

Work path: `works/ore-mutham/`.

## Mandatory startup

Read before further source-dependent work:

1. `STAGE_PLAY_PROCESSING_GUIDE.md`;
2. this `HANDOVER.md`;
3. `NEXT_CHAT_PROMPT.md`;
4. `works/ore-mutham/README.md`;
5. `works/ore-mutham/metadata/source.md`;
6. `works/ore-mutham/indexes/page-map.md`;
7. `works/ore-mutham/HISTORICAL_GLYPH_AUDIT.md`;
8. existing `works/ore-mutham/pages/0001.md`–`0010.md` as relevant;
9. the supplied controlling PDF.

## Source identity

Controlling PDF: `TVA_BOK_0064325_ஒரே_முத்தம்.pdf`

- file size: **224,884,964 bytes**;
- physical scans: **131**;
- SHA-256: **PENDING exact byte-level computation — never invent**;
- source PDF committed to repository: **no**.

Source-visible identity / anchors:

- scan 1: `ஒரே முத்தம்` cover;
- scan 3: `தென்றல் வெளியீடு. 3.`, `ஒரே முத்தம்`, `சரித்திரக் கற்பனை நாடகம்.`, author `கலைஞர், மு. கருணாநிதி எம். எல். ஏ.`, `ஐந்தாம் பதிப்பு.` and sales-rights block;
- scan 4: edition history reaches fifth edition **December 1964**, publisher `தென்றல் நூற்பதிப்புக் கழகம்.`, printer `செந்தமிழ் அச்சகம்`, price `விலை ரூபா 2-00.`;
- scan 5: `பதிப்புரை.` publisher note;
- scan 6: complete `முன்னுரை`, dated `சென்னை, 25-5-1950`, signed `மு. கருணாநிதி.`; source directly states Sri Lankan historical-fragment basis and first staging by `தேவி நாடக சபை`;
- scan 7: `நாடக உறுப்பினர்` cast list;
- scan 8: printed p.6, `காட்சி 1.`, `இடம்:- இன்பபுரித் தெரு`;
- scan 9: printed p.7, source transition to `காட்சி 2.`, `இடம்:- விழா மண்டபம்`;
- scan 10: printed p.8, continuation of `காட்சி 2.`;
- scan 130: printed p.128, final dramatic page;
- scan 131: back-cover publisher advertisement.

User catalog context remains distinct from transcription authority. The Sri Lankan historical basis and Devi Nataka Sabha first staging are now independently source-supported by scan 6. The caste-abolition thematic note remains catalog context until source-processed dramatic text itself supports it.

## Work extent / pagination

- scans **1–7**: front matter;
- scans **8–130**: dramatic work;
- scan **131**: back-cover advertisement;
- printed numerals directly confirmed so far: scan 8 = p.6, scan 9 = p.7, scan 10 = p.8;
- scans 8–130 → pp.6–128 remains provisional until every numeral is directly checked.

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

Current secure reference bank:

- `லை`: scan 3 `கலைஞர்`; scan 4 `விலை`; scan 6 `சிதறலை`, `கூறுவதற்கில்லை`;
- `ணா`: scans 3 and 6 `கருணாநிதி`;
- `னை`: scan 3 `விற்பனை`, `சென்னை`; scan 4 `சென்னை`; scan 6 `சென்னை`;
- `றா`: scan 6 `காரணமாகும்`.

No global replacement is authorized from these examples.

## Processed checkpoint — scans 1–10

- `0001.md` — **needs-review**: principal cover title secure; stylized vertical lettering/tiny signature unresolved;
- `0002.md` — **verified**: donor/library slip fully read and separated;
- `0003.md` — **verified**: title page;
- `0004.md` — **verified**: edition/publication/imprint;
- `0005.md` — **needs-review**: `பதிப்புரை.` heading/close secure; dense body held;
- `0006.md` — **verified**: complete author foreword; full glyph gate PASS;
- `0007.md` — **needs-review**: cast-list structure/secure anchors recorded; row-level details held;
- `0008.md` — **needs-review**: p.6, `காட்சி 1.`, location and prominent crowd cries secure; dense body held;
- `0009.md` — **needs-review**: p.7, `காட்சி 2.` transition/location secure; dense body held;
- `0010.md` — **needs-review**: p.8 and scene-2 continuation secure; dense body held.

Do not silently fill any held passage from plot continuity, OCR-like expectation, modern spelling, another edition, or general knowledge.

## Current metrics

- source scans registered: **131 / 131**;
- checksum: **pending**;
- page records created: **10 / 131**;
- source scans processed: **10 / 131**;
- visually verified: **4 / 131** (`2, 3, 4, 6`);
- `needs-review`: **6 / 131** (`1, 5, 7, 8, 9, 10`);
- completed historical-glyph passes: **4 / 131** (`2, 3, 4, 6`);
- structural/scene inventory: **not started**;
- Tamil assembly: **not started**;
- English translation: **not authorized / not started**.

## Exact next activity

Process scans **11–15** source-first:

1. create `pages/0011.md` through `0015.md`;
2. directly inspect and transcribe source-visible text without normalization;
3. confirm each printed page numeral rather than inferring it;
4. preserve exact source `காட்சி`, stage-direction and speaker-label forms;
5. perform the complete 13-family historical-glyph gate on every scan;
6. mark `verified` only if full visual + glyph review passes; otherwise retain explicit `needs-review`;
7. keep existing holds (`1, 5, 7–10`) open unless stronger enlarged pixels genuinely resolve them;
8. compute the exact PDF SHA-256 only when byte-level hashing becomes available; never infer it;
9. synchronize page map, glyph audit, metadata/status docs, work/root README, this handover and `NEXT_CHAT_PROMPT.md`;
10. do not begin structural assembly or English translation.

# CLOSED WORK SAFEGUARDS

## திருவாளர் தேசீயம்பிள்ளை

Remains **COMPLETE / CLOSED FOR CURRENT SOURCE EVIDENCE**: Tamil source processing 49/49, historical-glyph passes 49/49, 7/7 Tamil SRUs assembled/reviewed, independent English 7/7 reviewed, 4/4 English batches PASS/LOCKED, final `TRANSLATION_REVIEW.md` PASS. Its nine Tamil source-condition holds remain closed unless new source evidence is supplied.

`காகிதப்பூ`, `மணிமகுடம்`, and closed `கலைஞரின் நான்மணி மாலை` component works remain closed unless explicitly reopened.
