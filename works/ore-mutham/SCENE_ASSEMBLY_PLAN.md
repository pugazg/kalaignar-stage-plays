# Scene Assembly Plan — ஒரே முத்தம்

Status: **PLAN COMPLETE — ASSEMBLY NOT STARTED**.

Authority chain:

1. controlling scan;
2. visually checked `pages/*.md` records;
3. `STRUCTURAL_INVENTORY.md` for source ranges;
4. `TERMINAL_SOURCE_CONDITION_HOLDS.md` for unresolved-locus traceability.

This plan does not authorize English translation and does not authorize any repair of held wording.

## Assembly namespaces

Keep the two source numbering systems separate:

- main play: proposed scene files `scenes/main-01.md` through `scenes/main-30.md`;
- supplementary `நகைச் சுவைப் பகுதி.`: proposed files `scenes/nagai-suvai-01.md` through `scenes/nagai-suvai-03.md`.

The supplementary scenes remain **1–3**. They must never be presented as main-play scenes 31–33.

## Proposed scene front matter

```yaml
---
work: "ore-mutham"
section: "main-play" # or "supplementary-comedy"
scene: 1
source_scan_pages: [8]
source_printed_pages: [6]
status: "draft"
assembled_from_verified_pages: true
source_condition_scans: []
---
```

For a scene containing any terminal hold, use `assembled_from_verified_pages: false` and list every affected scan under `source_condition_scans`.

## Main-play assembly dependencies

| Scene | Input scans | Fully verified input range? | `source_condition_scans` |
|---:|---:|---|---|
| 1 | 8 | yes | `[]` |
| 2 | 9–10 | yes | `[]` |
| 3 | 11–14 | yes | `[]` |
| 4 | 15–18 | yes | `[]` |
| 5 | 19–20 | yes | `[]` |
| 6 | 21–23 | no | `[21]` |
| 7 | 24–26 | yes | `[]` |
| 8 | 27–31 | no | `[27]` |
| 9 | 32–36 | yes | `[]` |
| 10 | 37–40 | yes | `[]` |
| 11 | 41–45 | no | `[43]` |
| 12 | 46–50 | no | `[47, 48]` |
| 13 | 51 | no | `[51]` |
| 14 | 52 | no | `[52]` |
| 15 | 53–58 | yes | `[]` |
| 16 | 59–63 | no | `[60, 61]` |
| 17 | 64–67 | no | `[65]` |
| 18 | 68–71 | no | `[69]` |
| 19 | 72–74 | no | `[72, 73, 74]` |
| 20 | 75–79 | no | `[77, 79]` |
| 21 | 80–84 | yes | `[]` |
| 22 | 85–86 | yes | `[]` |
| 23 | 87–93 | no | `[88, 90]` |
| 24 | 94–95 | no | `[94, 95]` |
| 25 | 96–99 | no | `[98, 99]` |
| 26 | 100–103 | no | `[100]` |
| 27 | 104–105 | yes | `[]` |
| 28 | 106–111 | yes | `[]` |
| 29 | 112–116 | no | `[112, 113]` |
| 30 | 117–118 | yes | `[]` |

## Supplementary assembly dependencies

| Supplement scene | Input scans | Fully verified input range? | `source_condition_scans` |
|---:|---:|---|---|
| 1 | 119–124 | yes | `[]` |
| 2 | 125–127 | yes | `[]` |
| 3 | 128–130 | no | `[128, 130]` |

## Assembly rules

1. Assemble only from the canonical page records; do not retype from memory, OCR, another edition or plot continuity.
2. Preserve every source speaker label, scene/location heading, punctuation mark, stage direction and historical spelling exactly as represented in the page layer.
3. Mechanical page breaks may later be removed for readability only when the page-to-page continuation is already documented. Provenance must remain recoverable from `source_scan_pages` / printed-page metadata.
4. Physical word splits already documented at page boundaries must not be silently rewritten in page records. An assembled scene may join a mechanically split word only if the source relationship is already explicitly verified; record the joined boundary in assembly notes.
5. A terminal hold marker must survive assembly. Do not replace `[source-held: ...]` or equivalent page-layer markers with inferred words. The scene front matter must list the affected scan.
6. Scenes containing a terminal hold remain `draft` / `assembled_from_verified_pages: false` even if all other pages in the scene are verified.
7. Scenes with only verified page inputs may be assembled with `assembled_from_verified_pages: true`, but still require a scene-level audit against the contributing page records before any release-complete claim.
8. Supplementary scene numbering is independent and must be displayed as `நகைச் சுவைப் பகுதி. — காட்சி 1/2/3`, never 31/32/33.
9. Scan 1 and scan 131 are not scene inputs. Front/back matter stay outside scene assembly.
10. No Tamil wording may be altered as part of assembly. English translation remains a separate, later, explicitly authorized phase.

## Recommended assembly order

For the next authorized assembly phase, assemble the **fully verified scenes first** to validate the mechanical workflow without touching terminal holds: main scenes **1–5, 7, 9–10, 15, 21–22, 27–28, 30**, then supplementary scenes **1–2**. After that, assemble hold-bearing scenes with explicit `source_condition_scans` traceability.

This ordering is operational only; it does not change source scene order or publication order.
