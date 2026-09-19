# Scene Boundary Audit — ஒரே முத்தம்

Status: **BOUNDARY-AWARE AUDIT COMPLETE — FULL TAMIL SCENE LAYER 33 / 33 ASSEMBLED / CONSISTENCY PASS**.

This audit was triggered at the start of Tamil scene assembly. The earlier structural inventory used non-overlapping scan allocations. That model was sufficient to locate scene anchors but not for complete scene assembly because many physical scans contain the close of one scene and the heading/opening of the next scene on the same page.

The canonical `pages/*.md` records control. A transition scan may therefore contribute text to **both** adjacent scene files. No source wording is changed by this audit.

## Main-play boundary-aware contributing ranges

| Scene | Contributing scans | Shared transition scan(s) | Terminal unresolved locus inside this scene? |
|---:|---:|---|---|
| 1 | 8–9 | 9 with Scene 2 | no |
| 2 | 9–11 | 9 with Scene 1; 11 with Scene 3 | no |
| 3 | 11–15 | 11 with Scene 2; 15 with Scene 4 | no |
| 4 | 15–19 | 15 with Scene 3; 19 with Scene 5 | no |
| 5 | 19–20 | 19 with Scene 4 | no |
| 6 | 21–24 | 24 with Scene 7 | no |
| 7 | 24–27 | 24 with Scene 6; 27 with Scene 8 | no |
| 8 | 27–32 | 27 with Scene 7; 32 with Scene 9 | no |
| 9 | 32–37 | 32 with Scene 8; 37 with Scene 10 | no |
| 10 | 37–40 | 37 with Scene 9 | no |
| 11 | 41–46 | 46 with Scene 12 | no |
| 12 | 46–51 | 46 with Scene 11; 51 with Scene 13 | no |
| 13 | 51–52 | 51 with Scene 12; 52 with Scene 14 | no |
| 14 | 52–53 | 52 with Scene 13; 53 with Scene 15 | no |
| 15 | 53–59 | 53 with Scene 14; 59 with Scene 16 | no |
| 16 | 59–64 | 59 with Scene 15; 64 with Scene 17 | no |
| 17 | 64–68 | 64 with Scene 16; 68 with Scene 18 | no |
| 18 | 68–72 | 68 with Scene 17; 72 with Scene 19 | no |
| 19 | 72–75 | 72 with Scene 18; 75 with Scene 20 | no |
| 20 | 75–80 | 75 with Scene 19; 80 with Scene 21 | no |
| 21 | 80–85 | 80 with Scene 20; 85 with Scene 22 | no |
| 22 | 85–87 | 85 with Scene 21; 87 with Scene 23 | no |
| 23 | 87–94 | 87 with Scene 22; 94 with Scene 24 | no |
| 24 | 94–95 | 94 with Scene 23 | no |
| 25 | 96–99 | — | no |
| 26 | 100–104 | 104 with Scene 27 | no |
| 27 | 104–105 | 104 with Scene 26 | no |
| 28 | 106–112 | 112 with Scene 29 | no |
| 29 | 112–117 | 112 with Scene 28; 117 with Scene 30 | no |
| 30 | 117–118 | 117 with Scene 29 | no |

## Supplementary `நகைச் சுவைப் பகுதி.` boundary-aware ranges

| Supplement scene | Contributing scans | Shared transition scan(s) | Terminal unresolved locus inside this scene? |
|---:|---:|---|---|
| 1 | 119–125 | 125 with Scene 2 | no |
| 2 | 125–128 | 125 with Scene 1; 128 with Scene 3 | no |
| 3 | 128–130 | 128 with Scene 2 | no |

## Permanent boundary consequences

- Scene assembly is **segment-aware**, not merely page-status-aware.
- All shared transition scans are now globally verified; segment-aware boundaries remain preserved for provenance.

## Final assembly classes

### Fully verified physical-page inputs

Main: **1–30**.

Supplementary: **Scenes 1–3**.

### Source-secure shared-boundary cases

None — all contributing physical scans are now verified.

### Hold-bearing scenes

Main: **none**.

Supplementary: **none**.

## Assembly closure

- main scenes assembled: **30 / 30**;
- supplementary scenes assembled: **3 / 3**;
- total Tamil scene layer: **33 / 33**;
- complete page-to-scene consistency audit: **PASS — 33 / 33** in `SCENE_ASSEMBLY_AUDIT.md`;
- terminal source-condition wording inferred during assembly: **0**;
- source wording normalized during assembly: **0**;
- English translation: **COMPLETE / CLOSED — 33 / 33 scenes reviewed**.

## Exact next activity

Proceed to the **Tamil pre-release / work-level closure gate**. Verify the exact scene-file inventory and terminal-hold traceability, reconcile stale secondary `needs-review` labels with the terminal `blocked` classification, decide/document the Tamil work-level release state under current-source evidence, and synchronize durable status documents. Do **not** begin English translation unless explicitly authorized.
