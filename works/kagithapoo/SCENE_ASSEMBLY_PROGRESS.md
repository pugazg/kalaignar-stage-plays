# காகிதப்பூ — Scene assembly progress

Status: **IN PROGRESS**

Scene assembly was explicitly authorized by the user's instruction to proceed after the page layer had closed at **41 / 41 verified**.

## Assembly rules

1. Assemble only from verified `pages/*.md` records.
2. Mechanical page/column line breaks may be removed for readability.
3. Do not alter lexical wording, punctuation, speaker labels, stage directions or source-visible scene numbering except to join a word/sentence mechanically split by a physical page boundary.
4. Preserve provenance with `source_scan_pages` and `assembled_from_verified_pages: true`.
5. Do not invent text for source-compressed or absent scene bodies.
6. Preserve the numbering anomaly: scan 124 has only `காட்சி,`; scan 125 later has `காட்சி 24.`. Never invent Scenes 22/23.
7. Translation remains a later separate phase.

## Scene inventory / source spans

| Scene / source block | Scan span | Assembly status | File |
|---|---:|---|---|
| 1 | 92–93 | assembly-reviewed | `scenes/01.md` |
| `காட்சிகள்: 2, 3, 4, 5.` | 93 | assembly-reviewed; source-compressed representation only | `scenes/02-05.md` |
| 6 | 93–94 | assembly-reviewed | `scenes/06.md` |
| 7 | 94–98 | assembly-reviewed | `scenes/07.md` |
| 8 | 98–102 | assembly-reviewed | `scenes/08.md` |
| 9 | 102 | assembly-reviewed | `scenes/09.md` |
| 10 | 102–104 | assembly-reviewed | `scenes/10.md` |
| 11 | 104–105 | assembly-reviewed | `scenes/11.md` |
| 12 | 105–107 | assembly-reviewed | `scenes/12.md` |
| 13 | 107 | next | — |
| 14 | 107–109 | pending | — |
| 15 | 109–110 | pending | — |
| 16 | 110–114 | pending | — |
| 17 | 114–115 | pending | — |
| 18 | 115–116 | pending | — |
| 19 | 116 | pending | — |
| 20 | 117–119 | pending | — |
| 21 | 119–124 | pending | — |
| unnumbered source `காட்சி,` | 124–125 | pending; do not assign 22/23 | — |
| 24 | 125–129 | pending | — |
| 25 | 129 | pending | — |
| 26 | 129–130 | pending | — |
| 27 | 130–131 | pending | — |

## Completed assembly

- `scenes/01.md` joins the verified scan-92/93 Scene-1 continuation and closes at `(திரை)`.
- `scenes/02-05.md` preserves exactly the source's collective `காட்சிகள்: 2, 3, 4, 5.` representation; no unprinted dialogue was invented.
- `scenes/06.md` joins the verified scan-93/94 continuation and closes at `(திரை)`.
- `scenes/07.md` assembles verified scans 94–98 and retains the already verified PDF-fallback material from scans 95 and 97. The scan-98 photograph caption belongs after the `காட்சி 8.` boundary and is not included in Scene 7.
- `scenes/08.md` assembles verified scans 98–102. Mechanical 98→99 and 99→100 joins were made; the printed `ஓ. எம். சுப்பிரமணியன்,` caption remains preserved in `pages/0098.md` as a separate non-dramatic element rather than being inserted into the dramatic reading order.
- `scenes/09.md` preserves the complete single-scan Scene 9 on scan 102.
- `scenes/10.md` assembles scans 102–104 and closes at the source `(திரை)` immediately before Scene 11.
- `scenes/11.md` assembles scans 104–105 and retains the repeated `முரு:—` speaker label at the physical 105 continuation rather than silently merging it away.
- `scenes/12.md` assembles scans 105–107; the physical `ஒப்ப—` / `டைக்கிறதா` split is mechanically joined as `ஒப்படைக்கிறதா` and the scene closes at `(திரை)` before Scene 13.

## Exact next activity

Assemble and page-record-check **Scene 13** from verified scan **107**, then continue with Scene 14 unless the user specifies a different batch size. Do not begin English translation.