# Scene Boundary Audit — ஒரே முத்தம்

Status: **BOUNDARY-AWARE AUDIT COMPLETE — SOURCE-SECURE ASSEMBLY CHECKPOINT 15 / 15 PASS**.

This audit was triggered at the start of Tamil scene assembly. The earlier structural inventory used non-overlapping scan allocations. That model is adequate for locating scene anchors, but it is **not sufficient for complete scene assembly** because many physical scans contain the close of one scene and the heading/opening of the next scene on the same page.

The canonical `pages/*.md` records control. A transition scan may therefore contribute text to **both** adjacent scene files. No source wording is changed by this audit.

## Main-play boundary-aware contributing ranges

| Scene | Contributing scans | Shared transition scan(s) | Terminal unresolved locus inside this scene? |
|---:|---:|---|---|
| 1 | 8–9 | 9 with Scene 2 | no |
| 2 | 9–11 | 9 with Scene 1; 11 with Scene 3 | no |
| 3 | 11–15 | 11 with Scene 2; 15 with Scene 4 | no |
| 4 | 15–19 | 15 with Scene 3; 19 with Scene 5 | no |
| 5 | 19–20 | 19 with Scene 4 | no |
| 6 | 21–24 | 24 with Scene 7 | **scan 21** |
| 7 | 24–27 | 24 with Scene 6; 27 with Scene 8 | **scan 27 — Scene-7 material itself includes held parenthetical wording** |
| 8 | 27–32 | 27 with Scene 7; 32 with Scene 9 | **scan 27** |
| 9 | 32–37 | 32 with Scene 8; 37 with Scene 10 | no |
| 10 | 37–40 | 37 with Scene 9 | no |
| 11 | 41–46 | 46 with Scene 12 | **scan 43** |
| 12 | 46–51 | 46 with Scene 11; 51 with Scene 13 | **scans 47, 48, 51** |
| 13 | 51–52 | 51 with Scene 12; 52 with Scene 14 | **scan 52**; scan-51 hold belongs to Scene 12 before the Scene-13 anchor |
| 14 | 52–53 | 52 with Scene 13; 53 with Scene 15 | **scan 52** |
| 15 | 53–59 | 53 with Scene 14; 59 with Scene 16 | no |
| 16 | 59–64 | 59 with Scene 15; 64 with Scene 17 | **scans 60, 61** |
| 17 | 64–68 | 64 with Scene 16; 68 with Scene 18 | **scan 65** |
| 18 | 68–72 | 68 with Scene 17; 72 with Scene 19 | **scan 69**; the scan-72 hold is after the Scene-19 anchor |
| 19 | 72–75 | 72 with Scene 18; 75 with Scene 20 | **scans 72, 73, 74** |
| 20 | 75–80 | 75 with Scene 19; 80 with Scene 21 | **scans 77, 79** |
| 21 | 80–85 | 80 with Scene 20; 85 with Scene 22 | no |
| 22 | 85–87 | 85 with Scene 21; 87 with Scene 23 | no |
| 23 | 87–94 | 87 with Scene 22; 94 with Scene 24 | **scans 88, 90**; the scan-94 hold is after the Scene-24 anchor |
| 24 | 94–95 | 94 with Scene 23 | **scans 94, 95** |
| 25 | 96–99 | — | **scans 98, 99** |
| 26 | 100–104 | 104 with Scene 27 | **scan 100** |
| 27 | 104–105 | 104 with Scene 26 | no |
| 28 | 106–112 | 112 with Scene 29 | **no Scene-28 unresolved locus**; scan 112 is page-level `blocked` only for the Scene-29 opening parenthetical after the Scene-29 anchor |
| 29 | 112–117 | 112 with Scene 28; 117 with Scene 30 | **scans 112, 113** |
| 30 | 117–118 | 117 with Scene 29 | no |

## Supplementary `நகைச் சுவைப் பகுதி.` boundary-aware ranges

| Supplement scene | Contributing scans | Shared transition scan(s) | Terminal unresolved locus inside this scene? |
|---:|---:|---|---|
| 1 | 119–125 | 125 with Scene 2 | no |
| 2 | 125–128 | 125 with Scene 1; 128 with Scene 3 | **no Scene-2 unresolved locus**; scan 128 is page-level `blocked` only for the Scene-3 opening parenthetical after the Scene-3 anchor |
| 3 | 128–130 | 128 with Scene 2 | **scans 128, 130** |

## Assembly consequences

The earlier non-overlapping dependency table would have omitted source-visible scene tails on transition pages. Confirmed examples include:

- Scene 1 continues onto scan 9 before `காட்சி 2.`;
- Scene 2 continues onto scan 11 before `காட்சி 3.`;
- Scene 3 continues onto scan 15 before `காட்சி 4.`;
- Scene 4 continues onto scan 19 before `காட்சி 5.`;
- Scene 7 continues onto blocked scan 27, where Scene-7 parenthetical wording remains held;
- Scene 28 closes on the secure pre-`காட்சி 29.` portion of scan 112, even though scan 112 is blocked later on the Scene-29 opening parenthetical;
- supplementary Scene 2 closes on the secure pre-`காட்சி 3.` portion of scan 128, even though scan 128 is blocked later on the Scene-3 opening parenthetical.

Therefore scene assembly is **segment-aware**, not merely page-status-aware.

## Assembly classes

### Entirely from `verified` page records

Main scenes: **1–5, 9–10, 15, 21–22, 27, 30**.

Supplementary: **Scene 1**.

All of these are now assembled and page-record-audited.

### Source-secure scene text with a shared page whose blocked locus belongs only to the following scene

- main Scene **28** — secure Scene-28 prefix on scan 112;
- supplementary Scene **2** — secure Scene-2 prefix on scan 128.

Both are now assembled with `assembled_from_verified_pages: false`, `source_condition_scans: []`, and explicit boundary-only blocked-page provenance. Neither imports the later held locus.

### Hold-bearing scenes

Main scenes: **6–8, 11–14, 16–20, 23–26, 29**.

Supplementary: **Scene 3**.

Every held locus must remain traceable exactly as documented in `TERMINAL_SOURCE_CONDITION_HOLDS.md` and the canonical page record.

## Current assembly checkpoint

Main scenes assembled / page-record-audited: **13 / 30** — **1–5, 9–10, 15, 21–22, 27–28, 30**.

Supplementary scenes assembled / page-record-audited: **2 / 3** — **1–2**.

Total source-secure assembled scene files: **15 / 33**.

`SCENE_ASSEMBLY_AUDIT.md` records **PASS — 15 / 15** currently assembled source-secure scenes page-record-consistent. No unresolved terminal locus has been imported into an assembled scene, no source wording has been changed, and no contextual/OCR/another-edition repair has been used.

## Exact next activity

Proceed to hold-bearing Tamil scene assembly in source order:

- main **6–8**;
- main **11–14**;
- main **16–20**;
- main **23–26**;
- main **29**;
- supplementary **Scene 3**.

For each hold-bearing scene, copy only canonical page-record segments, preserve every source-held marker exactly, set `assembled_from_verified_pages: false`, list the scene-relevant held scans under `source_condition_scans`, and do not infer missing wording from context. English translation remains unauthorized.
