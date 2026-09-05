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
| 20 | 117–119 | assembly-reviewed | `scenes/20.md` |
| 21 | 119–124 | assembly-reviewed | `scenes/21.md` |
| unnumbered source `காட்சி,` | 124–125 | assembly-reviewed; no 22/23 assigned | `scenes/unnumbered-between-21-and-24.md` |
| 24 | 125–129 | assembly-reviewed | `scenes/24.md` |
| 25 | 129 | assembly-reviewed; source-compressed action only | `scenes/25.md` |
| 26 | 129–130 | assembly-reviewed | `scenes/26.md` |
| 27 | 130–131 | next | — |

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
- `scenes/16.md` assembles scans 110–114; the physical `இய—` / `லாது` boundary is mechanically joined to `இயலாது`. The unusual verified MD tokens on scan 112 are preserved exactly, and the scan-113/114 sentence continuation is joined without normalization.
- `scenes/17.md` assembles scans 114–115; Gandhi's long speech is joined across the physical page boundary and the scene closes at `(திரை)` before Scene 18.
- `scenes/18.md` assembles scans 115–116; the physical continuation is joined while preserving the page-record speaker-label variation, including `திர:—` on scan 116.
- `scenes/19.md` preserves the complete single-scan Scene 19 on scan 116 and closes at `(திரை)`.
- `scenes/20.md` assembles verified scans 117–119; the scan-118→119 sentence continuation `நீங்கள் சிந்திய ரத்தம் கூட—` / `உங்கள் மகன்...` is joined mechanically, and Scene 20 closes at `(திரை)` before Scene 21.
- `scenes/21.md` assembles verified scans 119–124. The physical word splits `நலத்—` / `திட்ட` and `ஆட்சி—` / `மொழிகளாகட்டும்` are mechanically joined as `நலத்திட்ட` and `ஆட்சிமொழிகளாகட்டும்`; the scan-123→124 sentence continuation is joined without lexical normalization. Unusual verified page-record wording remains unchanged. Scene 21 closes at `(திரை)` immediately before the unnumbered source heading `காட்சி,`.
- `scenes/unnumbered-between-21-and-24.md` assembles verified scans 124–125 and preserves the heading exactly as `காட்சி,`; no Scene 22 or Scene 23 number is assigned or implied.
- `scenes/24.md` assembles verified scans 125–129; physical splits `முடி` / `யாம` and `கொள்` / `ளுங்கள்` are mechanically joined as `முடியாம` and `கொள்ளுங்கள்`. The repeated `திர:—` continuation label remains source-faithful.
- `scenes/25.md` preserves the complete source-compressed Scene 25 on scan 129 exactly as the bracketed campaign-action direction; no dialogue or body is invented.
- `scenes/26.md` assembles verified scans 129–130. The physical boundary falls between complete turns, so no lexical join is made; unusual verified speaker labels are preserved exactly. Scene 26 closes before `காட்சி 27`.

## Exact next activity

Assemble and page-record-check **Scene 27** from verified scans **130–131**. Keep the scan-130 boxed `கண்டுபிடியுங்கள்` feature separate from dramatic reading order, preserve the already verified three PDF-fallback turns on scan 130, and close the dramatic scene with source `(முற்றும்)` on scan 131. The following `நாடகத்தில்—பங்கேற்பவர்கள்!` cast block remains separate page-level non-dramatic material. After Scene 27, perform the final scene-assembly consistency/closure review. Do not begin English translation.
