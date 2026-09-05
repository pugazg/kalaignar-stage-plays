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
| 13 | 107 | assembly-reviewed | `scenes/13.md` |
| 14 | 107–109 | assembly-reviewed | `scenes/14.md` |
| 15 | 109–110 | assembly-reviewed | `scenes/15.md` |
| 16 | 110–114 | assembly-reviewed | `scenes/16.md` |
| 17 | 114–115 | assembly-reviewed | `scenes/17.md` |
| 18 | 115–116 | assembly-reviewed | `scenes/18.md` |
| 19 | 116 | assembly-reviewed | `scenes/19.md` |
| 20 | 117–119 | next | — |
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
- `scenes/13.md` preserves the complete single-scan Scene 13 on scan 107 and closes at `(திரை விழுகிறது)` before `காட்சி: 14`.
- `scenes/14.md` assembles scans 107–109; the physical `வெற்றிகளக் குவிக்கத்—` / `தான் போகிறார்கள் மக்கள்!...` boundary is mechanically joined as `வெற்றிகளக் குவிக்கத்தான் போகிறார்கள் மக்கள்!...`, and Scene 14 closes at `(திரை)` before Scene 15.
- `scenes/15.md` assembles scans 109–110; the physical `வார்த்தை—` / `யைச்` boundary is mechanically joined as `வார்த்தையைச்`, and Scene 15 closes at `(திரை)` before Scene 16.
- `scenes/16.md` assembles scans 110–114; the physical `இய—` / `லாது` boundary is mechanically joined as `இயலாது`. The unusual verified MD tokens on scan 112 are preserved exactly, and the scan-113/114 sentence continuation is joined without normalization.
- `scenes/17.md` assembles scans 114–115; Gandhi's long speech is joined across the physical page boundary and the scene closes at `(திரை)` before Scene 18.
- `scenes/18.md` assembles scans 115–116; the physical continuation is joined while preserving the page-record speaker-label variation, including `திர:—` on scan 116.
- `scenes/19.md` preserves the complete single-scan Scene 19 on scan 116 and closes at `(திரை)`.

## Exact next activity

Assemble and page-record-check **Scene 20** from verified scans **117–119**, then continue with Scene 21 unless the user specifies a different batch size. Do not begin English translation.