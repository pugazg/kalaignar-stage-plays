# Scene Assembly Plan — ஒரே முத்தம்

Status: **BOUNDARY-AWARE PLAN ACTIVE — MAIN SCENES 1–5 ASSEMBLED / PAGE-RECORD-AUDITED**.

Authority chain:

1. controlling scan;
2. canonical visually checked `pages/*.md` records;
3. `SCENE_BOUNDARY_AUDIT.md` for shared transition-page segmentation;
4. `STRUCTURAL_INVENTORY.md` for boundary-aware scene ranges;
5. `TERMINAL_SOURCE_CONDITION_HOLDS.md` for unresolved-locus traceability.

This plan does not authorize English translation and does not authorize any repair of held wording.

## Assembly namespaces

Keep the two source numbering systems separate:

- main play: `scenes/main-01.md` through `scenes/main-30.md`;
- supplementary `நகைச் சுவைப் பகுதி.`: `scenes/nagai-suvai-01.md` through `scenes/nagai-suvai-03.md`.

The supplementary scenes remain **1–3**. They must never be presented as main-play scenes 31–33.

## Transition-page rule

A scan can contribute to two adjacent scenes. Assembly therefore operates on the **scene segment** of each canonical page record, not by assigning each physical page to only one scene.

When a shared page is terminally `blocked`, distinguish:

- a hold that belongs to the scene being assembled — list that scan in `source_condition_scans` and retain its hold marker;
- a hold that occurs only after the next scene anchor — the earlier scene may use its source-secure prefix, but must not falsely claim that every contributing physical page is `verified`.

## Scene front matter

For a scene assembled entirely from `verified` physical page records:

```yaml
---
scene: 1
work: "ore-mutham"
section: "main-play"
source_scan_pages: [8, 9]
printed_pages: [6, 7]
status: "assembly-reviewed"
assembled_from_verified_pages: true
page_record_fidelity: "passed"
source_condition_scans: []
---
```

For a hold-bearing scene, use `assembled_from_verified_pages: false`, list the held scans, preserve the unresolved marker exactly, and keep scene status non-release-final until the source condition changes or the archival release policy explicitly accepts terminal holds.

For a scene whose text is source-secure but whose final shared physical page is blocked only **after the next scene anchor** (main Scene 28; supplementary Scene 2), use `assembled_from_verified_pages: false`, `source_condition_scans: []`, and document the boundary-only blocked page in provenance.

## Boundary-aware main-play dependencies

| Scene | Contributing scans | All contributing physical page records verified? | Unresolved locus inside scene |
|---:|---:|---|---|
| 1 | 8–9 | yes | `[]` |
| 2 | 9–11 | yes | `[]` |
| 3 | 11–15 | yes | `[]` |
| 4 | 15–19 | yes | `[]` |
| 5 | 19–20 | yes | `[]` |
| 6 | 21–24 | no | `[21]` |
| 7 | 24–27 | no | `[27]` |
| 8 | 27–32 | no | `[27]` |
| 9 | 32–37 | yes | `[]` |
| 10 | 37–40 | yes | `[]` |
| 11 | 41–46 | no | `[43]` |
| 12 | 46–51 | no | `[47, 48, 51]` |
| 13 | 51–52 | no | `[52]` |
| 14 | 52–53 | no | `[52]` |
| 15 | 53–59 | yes | `[]` |
| 16 | 59–64 | no | `[60, 61]` |
| 17 | 64–68 | no | `[65]` |
| 18 | 68–72 | no | `[69]` |
| 19 | 72–75 | no | `[72, 73, 74]` |
| 20 | 75–80 | no | `[77, 79]` |
| 21 | 80–85 | yes | `[]` |
| 22 | 85–87 | yes | `[]` |
| 23 | 87–94 | no | `[88, 90]` |
| 24 | 94–95 | no | `[94, 95]` |
| 25 | 96–99 | no | `[98, 99]` |
| 26 | 100–104 | no | `[100]` |
| 27 | 104–105 | yes | `[]` |
| 28 | 106–112 | no * | `[]` — scan 112 hold belongs only to Scene 29 after its anchor |
| 29 | 112–117 | no | `[112, 113]` |
| 30 | 117–118 | yes | `[]` |

`*` Scene 28 is source-secure end to end, but one contributing physical page (`112`) is globally `blocked` because of later Scene-29 text on the same page.

## Boundary-aware supplementary dependencies

| Supplement scene | Contributing scans | All contributing physical page records verified? | Unresolved locus inside scene |
|---:|---:|---|---|
| 1 | 119–125 | yes | `[]` |
| 2 | 125–128 | no * | `[]` — scan 128 hold belongs only to Scene 3 after its anchor |
| 3 | 128–130 | no | `[128, 130]` |

`*` Supplementary Scene 2 is source-secure end to end, but scan 128 is globally `blocked` because of the later Scene-3 opening parenthetical.

## Assembly rules

1. Assemble only from canonical page records; do not retype from OCR, memory, another edition or plot continuity.
2. Preserve every source speaker label, scene/location heading, punctuation mark, stage direction and historical spelling exactly as represented in the page layer.
3. A transition scan may be split at the explicit next-scene heading; both adjacent scene files may cite the same physical scan.
4. Physical page boundaries may be preserved as non-rendered archival comments. Documented word continuations must never be silently normalized.
5. A terminal hold marker must survive assembly if the held locus belongs to that scene. Do not replace `[source-held: ...]` or equivalent page-layer markers with inferred words.
6. Scenes containing a terminal unresolved locus use `assembled_from_verified_pages: false` and list every affected scene-relevant scan under `source_condition_scans`.
7. Scenes with only verified page inputs may use `assembled_from_verified_pages: true` only after a page-to-scene consistency audit.
8. Boundary-secure Scene 28 and supplementary Scene 2 use source-secure segments from a page whose later segment is blocked; provenance must state this and `assembled_from_verified_pages` remains false.
9. Supplementary scene numbering is independent and must display `நகைச் சுவைப் பகுதி. — காட்சி 1/2/3`, never 31/32/33.
10. Scan 1 and scan 131 are not scene inputs. Front/back matter stay outside scene assembly.
11. No Tamil wording may be altered as part of assembly. English translation remains a separate, later, explicitly authorized phase.

## Current assembly checkpoint

Completed and page-record-audited:

- main Scene 1 — `scenes/main-01.md` — scans 8–9;
- main Scene 2 — `scenes/main-02.md` — scans 9–11;
- main Scene 3 — `scenes/main-03.md` — scans 11–15;
- main Scene 4 — `scenes/main-04.md` — scans 15–19;
- main Scene 5 — `scenes/main-05.md` — scans 19–20.

These five scenes explicitly preserve shared transition pages and do not omit the closing text that precedes the next scene heading.

## Corrected next assembly order

Continue with scenes whose **entire contributing physical page set is verified**:

1. main scenes **9–10**;
2. main scene **15**;
3. main scenes **21–22**;
4. main scene **27**;
5. main scene **30**;
6. supplementary Scene **1**.

Then assemble the two source-secure boundary cases with special provenance:

7. main Scene **28** using only the secure Scene-28 prefix of blocked scan 112;
8. supplementary Scene **2** using only the secure Scene-2 prefix of blocked scan 128.

After those are audited, proceed to hold-bearing scenes with explicit terminal-locus preservation. Main Scene **7 is no longer in the verified-only batch** because its closing portion on scan 27 contains held Scene-7 wording.
