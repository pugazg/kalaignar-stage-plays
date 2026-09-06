# Page Map — ஒரே முத்தம்

Controlling source: `TVA_BOK_0064325_ஒரே_முத்தம்.pdf`.

All **131 physical scans** are registered at intake. Per-scan page records will be created and expanded in source-first batches; registration does not imply transcription or verification.

| Scan(s) | Printed page(s) | Section | Page type | Status | Intake note |
|---:|---:|---|---|---|---|
| 1 | — | front matter | front cover | not-started | Cover visibly carries `ஒரே முத்தம்`. |
| 2 | — | front matter | donor/library slip | not-started | Pasted later donor/library label; keep separate from publication text. |
| 3 | — | front matter | title page | not-started | Title, `சரித்திரக் கற்பனை நாடகம்.`, author, fifth-edition and sales-rights details visible. |
| 4 | — | front matter | edition / publication / imprint | not-started | Edition history reaches fifth edition in 1964; publisher and price visible; exact printer line awaits page-level verification. |
| 5 | — | front matter | publisher note (`பதிப்புரை`) | not-started | Source-first transcription pending. |
| 6 | — | front matter | author foreword (`முன்னுரை`) | not-started | Dated `சென்னை, 25-5-1950`; signed `மு. கருணாநிதி.` |
| 7 | — | front matter | cast list (`நாடக உறுப்பினர்`) | not-started | Character/cast list; source-first transcription pending. |
| 8–130 | 6–128* | body | dramatic text | not-started | Scan 8 visibly begins `காட்சி 1.` at p.6; scan 125 = p.123; scan 130 = p.128. Sequential mapping is provisional until each page is visually checked. |
| 131 | — | back matter | back-cover advertisement | not-started | Publisher book-list advertisement; outside dramatic text. |

`*` Printed-page policy: the scan→printed-page mapping for scans 8–130 is registered provisionally from visible anchors. Each individual printed numeral must be confirmed during page processing; arithmetic alone does not make a page verified.

## Intake checkpoint

- physical scans registered: **131 / 131**;
- per-scan page records created: **0 / 131**;
- source transcription processed: **0 / 131**;
- visually verified: **0 / 131**;
- historical-glyph passes: **0 / 131**;
- checksum: **pending**;
- structural/scene inventory: **not started**;
- scene assembly: **not started**;
- English translation: **not authorized / not started**.

## Page-record policy

Page records will be created as source-processing batches are opened, using zero-padded names `0001.md` through `0131.md`.

Every page record must preserve:

- raw physical scan number;
- source-visible printed page number only when visually confirmed;
- front/body/back-matter identity;
- printed text separately from library/donor/handwritten marks;
- physical damage or uncertain clusters explicitly;
- full historical-glyph family check;
- `verified` only after complete direct visual review.

## Exact next activity

Compute the exact PDF SHA-256 and process **scans 1–5**. Create `pages/0001.md` through `pages/0005.md`, perform full direct visual and 13-family historical-glyph checks, and update this map with actual per-scan statuses.
