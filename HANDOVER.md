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
8. `works/ore-mutham/TERMINAL_SOURCE_CONDITION_HOLDS.md`;
9. `works/ore-mutham/SCENE_BOUNDARY_AUDIT.md`;
10. `works/ore-mutham/STRUCTURAL_INVENTORY.md`;
11. `works/ore-mutham/SCENE_ASSEMBLY_PLAN.md`;
12. existing `works/ore-mutham/scenes/*.md`;
13. relevant canonical `works/ore-mutham/pages/0001.md`–`0131.md`;
14. supplied controlling PDF only when new source-dependent adjudication is attempted.

## Source identity

Controlling PDF: `TVA_BOK_0064325_ஒரே_முத்தம்.pdf`

- file size: **224,884,964 bytes**;
- physical scans: **131**;
- SHA-256: **`60780e340e6b0c6d6f3956af8beeb69692fab3f20e843c6ed4275b9962aae220`**;
- source PDF committed to repository: **no**.

## Major checkpoint — boundary-aware scene assembly STARTED

- raw source pass: **131 / 131 COMPLETE**;
- complete physical-range closure audit: **131 / 131 COMPLETE**;
- residual-hold re-audit: **COMPLETE — every terminal page directly revisited**;
- verified physical scans: **103 / 131**;
- terminal current-source-condition / `blocked`: **28 / 131**;
- ordinary `needs-review` remaining in terminal set: **0**;
- historical-glyph PASS: **103 / 131**;
- main play: **30 / 30 structural scene anchors verified**;
- supplementary `நகைச் சுவைப் பகுதி.`: **3 / 3 anchors verified separately**;
- terminal hold inventory: **COMPLETE**;
- scene-boundary audit: **COMPLETE**;
- boundary-aware structural inventory: **COMPLETE**;
- scene-assembly plan: **CORRECTED / ACTIVE**;
- main scenes assembled / page-record-audited: **1–5 / 30**;
- supplementary scenes assembled: **0 / 3**;
- English translation: **not authorized / not started**.

### Verified scans — 103 / 131

`2–20`, `22–26`, `28–42`, `44–46`, `49–50`, `53–59`, `62–64`, `66–68`, `70–71`, `75–76`, `78`, `80–87`, `89`, `91–93`, `96–97`, `101–111`, `114–127`, `129`, `131`.

### Terminal current-source-condition scans — 28 / 131

`1`, `21`, `27`, `43`, `47–48`, `51–52`, `60–61`, `65`, `69`, `72–74`, `77`, `79`, `88`, `90`, `94–95`, `98–100`, `112–113`, `128`, `130`.

These records are `blocked`, not unreviewed. Exact unresolved loci remain in the page files and `TERMINAL_SOURCE_CONDITION_HOLDS.md`. Reopen only with genuinely stronger source evidence.

## Boundary-aware correction discovered during assembly

The earlier scene inventory used non-overlapping scan allocations. That was sufficient to locate scene anchors but would omit closing text when a physical page contains both the end of one scene and the heading/opening of the next.

This has been corrected durably in:

- `works/ore-mutham/SCENE_BOUNDARY_AUDIT.md`;
- `works/ore-mutham/STRUCTURAL_INVENTORY.md`;
- `works/ore-mutham/SCENE_ASSEMBLY_PLAN.md`.

Permanent assembly rule: **a transition scan may contribute source text to both adjacent scene files**. Hold ownership is segment-level: a globally blocked page does not make the preceding scene text unresolved when the held locus occurs only after the next-scene anchor.

Examples:

- main Scene 1 uses scans **8–9**; scan 9 also opens Scene 2;
- Scene 2 uses **9–11**; scan 11 also opens Scene 3;
- Scene 3 uses **11–15**; scan 15 also opens Scene 4;
- Scene 4 uses **15–19**; scan 19 also opens Scene 5;
- Scene 7 requires scan **27**, and Scene-7 wording itself is held there; it is therefore **not verified-only**;
- main Scene 28 closes on the secure pre-Scene-29 segment of globally blocked scan **112**;
- supplementary Scene 2 closes on the secure pre-Scene-3 segment of globally blocked scan **128**.

## Current scene layer

Completed and page-record-audited:

1. `works/ore-mutham/scenes/main-01.md` — scans **8–9 / pp.6–7**;
2. `works/ore-mutham/scenes/main-02.md` — scans **9–11 / pp.7–9**;
3. `works/ore-mutham/scenes/main-03.md` — scans **11–15 / pp.9–13**;
4. `works/ore-mutham/scenes/main-04.md` — scans **15–19 / pp.13–17**;
5. `works/ore-mutham/scenes/main-05.md` — scans **19–20 / pp.17–18**.

All five are:

- `status: "assembly-reviewed"`;
- `assembled_from_verified_pages: true`;
- `page_record_fidelity: "passed"`;
- `source_condition_scans: []`.

Shared transition pages and physical boundaries are explicitly retained in assembly provenance. No OCR, contextual repair, modernization or another-edition wording was introduced. Scene 2 retains the documented scan-10→11 physical continuation as page-record fragments rather than silently respelling it.

## Corrected scene classes

### Entirely from verified physical page records

Main: **1–5, 9–10, 15, 21–22, 27, 30**.

Supplementary: **Scene 1**.

Main scenes **1–5** are complete. Remaining in this class: **9–10, 15, 21–22, 27, 30**, then supplementary **Scene 1**.

### Source-secure text with a shared globally blocked boundary page whose hold belongs only to the following scene

- main Scene **28** — secure Scene-28 prefix of scan **112**;
- supplementary Scene **2** — secure Scene-2 prefix of scan **128**.

When assembled, use `assembled_from_verified_pages: false`, `source_condition_scans: []`, and explicit boundary-only blocked-page provenance.

### Hold-bearing scenes

Main: **6–8, 11–14, 16–20, 23–26, 29**.

Supplementary: **Scene 3**.

Held markers must survive assembly exactly; no missing wording may be inferred.

## Terminal hold policy

Permanent rule:

- no source-held wording from context;
- no OCR expectation;
- no another-edition completion;
- no spelling / grammar / punctuation / speaker-label / scene-heading normalization;
- no global historical-glyph replacement;
- a `blocked` record may be reopened only with genuinely stronger source evidence.

## Residual-hold durable history

- **Batch 1:** reviewed `1, 21, 23, 27–32, 34`; promoted **23, 28–32, 34**.
- **Batch 2:** reviewed `35–36, 38–39, 41–46`; promoted **35, 36, 38, 39, 41, 42, 44, 45, 46**.
- **Batch 3:** reviewed `47–52, 60–61, 65–66`; promoted **49, 50, 66**.
- **Batch 4:** reviewed `69, 72–74, 77–79, 88–90`; promoted **78, 89**.
- **Batch 5:** reviewed `92, 94–95, 98–100, 112–113, 117, 128, 130`; promoted **92, 117**.

Durable later findings include scan 92 **`(விபீஷணன் வாளை உருவிப் பொன்னியின் மேல் வீசுந்தோரணையில் நின்றுகொண்டு)`** with earlier `வீரப் பயமுறுத்தல் கூட` retained, and scan 117 **`சித்ராவும்`** in the Scene-30 opening cluster.

## Mandatory historical-glyph gate

Every candidate page receives:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

Only whole-page `verified` pages may contribute new secure same-edition reference forms. Terminal `blocked` pages keep the family gate open at their unresolved locus.

## Exact next activity — continue verified-page Tamil scene assembly

Do **not** begin English translation.

Follow the corrected `works/ore-mutham/SCENE_ASSEMBLY_PLAN.md`.

1. Assemble and page-record-audit main scenes **9–10**.
2. Continue main Scene **15**.
3. Continue main scenes **21–22**.
4. Continue main Scene **27**.
5. Continue main Scene **30**.
6. Assemble supplementary `நகைச் சுவைப் பகுதி.` **Scene 1**.
7. Then assemble source-secure shared-boundary main Scene **28** and supplementary Scene **2** with explicit boundary-only blocked-page provenance and `assembled_from_verified_pages: false`.
8. Only after that widen to hold-bearing scenes, preserving every terminal marker exactly.
9. Synchronize work/root READMEs, `HANDOVER.md`, and `NEXT_CHAT_PROMPT.md` after the next substantial checkpoint.
10. Fetch final live `main` SHA.

# CLOSED WORK SAFEGUARDS

`திருவாளர் தேசீயம்பிள்ளை`, `காகிதப்பூ`, `மணிமகுடம்`, and closed `கலைஞரின் நான்மணி மாலை` components remain closed unless explicitly reopened with new source evidence or a separately authorized phase.
