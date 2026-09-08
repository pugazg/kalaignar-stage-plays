# Next Chat Prompt — Kalaignar Stage Plays / ஒரே முத்தம்

Continue directly in `pugazg/kalaignar-stage-plays`, branch `main`, active work `works/ore-mutham/`.

## LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first and preserve newer durable state. Do not reopen closed `திருவாளர் தேசீயம்பிள்ளை`, `காகிதப்பூ`, `மணிமகுடம்`, or `கலைஞரின் நான்மணி மாலை` work because an older prompt contains a stale checkpoint.

## Mandatory startup

Read before further work:

1. `STAGE_PLAY_PROCESSING_GUIDE.md`
2. `HANDOVER.md`
3. this `NEXT_CHAT_PROMPT.md`
4. `works/ore-mutham/README.md`
5. `works/ore-mutham/metadata/source.md`
6. `works/ore-mutham/indexes/page-map.md`
7. `works/ore-mutham/HISTORICAL_GLYPH_AUDIT.md`
8. `works/ore-mutham/TERMINAL_SOURCE_CONDITION_HOLDS.md`
9. `works/ore-mutham/SCENE_BOUNDARY_AUDIT.md`
10. `works/ore-mutham/STRUCTURAL_INVENTORY.md`
11. `works/ore-mutham/SCENE_ASSEMBLY_PLAN.md`
12. existing `works/ore-mutham/scenes/*.md`
13. relevant canonical page records `works/ore-mutham/pages/0001.md`–`0131.md`
14. controlling PDF `TVA_BOK_0064325_ஒரே_முத்தம்.pdf` only when new source-dependent adjudication is required

## Source identity

- filename: `TVA_BOK_0064325_ஒரே_முத்தம்.pdf`
- file size: **224,884,964 bytes**
- physical scans: **131**
- SHA-256: **`60780e340e6b0c6d6f3956af8beeb69692fab3f20e843c6ed4275b9962aae220`**
- source PDF committed to repository: **no**

## Major checkpoint — BOUNDARY-AWARE TAMIL SCENE ASSEMBLY STARTED

All **131 / 131** physical scans remain source-processed and closure-audited.

- verified physical scans: **103 / 131**;
- terminal current-source-condition / `blocked`: **28 / 131**;
- ordinary `needs-review` in terminal set: **0**;
- historical-glyph PASS: **103 / 131**;
- main scene anchors: **30 / 30 structurally verified**;
- supplementary anchors: **3 / 3 structurally verified separately**;
- terminal hold inventory: **COMPLETE**;
- scene-boundary audit: **COMPLETE**;
- boundary-aware structural inventory: **COMPLETE**;
- corrected scene-assembly plan: **ACTIVE**;
- main scenes assembled / page-record-audited: **1–5 / 30**;
- supplementary scenes assembled: **0 / 3**;
- English translation: **not authorized / not started**.

The 28 `blocked` pages are not unreviewed. Their exact unresolved loci remain in `TERMINAL_SOURCE_CONDITION_HOLDS.md` and the page records. Reopen only with genuinely stronger source evidence.

## Critical assembly correction — shared transition scans

At the start of assembly, the earlier non-overlapping range allocation was found insufficient: many physical scans contain the end of one scene **and** the heading/opening of the next scene.

This is now durably corrected in `SCENE_BOUNDARY_AUDIT.md`, `STRUCTURAL_INVENTORY.md`, and `SCENE_ASSEMBLY_PLAN.md`.

Permanent rule: a transition scan may contribute source text to **both adjacent scenes**. Never omit the pre-next-scene closing portion merely because the page also contains the next scene anchor.

Important consequences:

- Scene 1 = scans **8–9**, not scan 8 alone;
- Scene 2 = **9–11**;
- Scene 3 = **11–15**;
- Scene 4 = **15–19**;
- Scene 7 = **24–27** and is **not verified-only**, because Scene-7 wording itself remains held on scan 27;
- Scene 28 = **106–112**; its Scene-28 prefix on scan 112 is secure, while the terminal hold on that physical page belongs only to the later Scene-29 opening parenthetical;
- supplementary Scene 2 = **125–128**; its Scene-2 prefix on scan 128 is secure, while the terminal hold belongs only to the later Scene-3 opening parenthetical.

## Current scene files

Completed and audited:

- `scenes/main-01.md` — scans **8–9 / pp.6–7**;
- `scenes/main-02.md` — scans **9–11 / pp.7–9**;
- `scenes/main-03.md` — scans **11–15 / pp.9–13**;
- `scenes/main-04.md` — scans **15–19 / pp.13–17**;
- `scenes/main-05.md` — scans **19–20 / pp.17–18**.

All five use:

- `status: "assembly-reviewed"`;
- `assembled_from_verified_pages: true`;
- `page_record_fidelity: "passed"`;
- `source_condition_scans: []`.

Shared transition pages and physical boundaries are explicitly documented. Scene 2 retains the scan-10→11 physical continuation as canonical page-record fragments rather than silently respelling it.

## Corrected scene classes

### Entirely verified physical-page inputs

Main: **1–5, 9–10, 15, 21–22, 27, 30**.

Supplementary: **Scene 1**.

Scenes **1–5 are complete**. Remaining verified-page batch: main **9–10, 15, 21–22, 27, 30**, then supplementary **Scene 1**.

### Source-secure boundary cases on globally blocked transition pages

- main Scene **28**: use only secure Scene-28 text before `காட்சி 29.` on scan 112;
- supplementary Scene **2**: use only secure Scene-2 text before `காட்சி 3.` on scan 128.

For these, use `assembled_from_verified_pages: false`, `source_condition_scans: []`, and explicit provenance that the blocked locus belongs only to the following scene.

### Hold-bearing scenes

Main: **6–8, 11–14, 16–20, 23–26, 29**.

Supplementary: **Scene 3**.

Retain every terminal marker exactly. No contextual completion.

## Durable source findings

Keep all prior page-level corrections authoritative, including:

- scan 23 `ஏழைகள்!` / `ஆனா`;
- scan 36 `மன்னனைக்`;
- scan 39 `புயல்காற்றைப் புருஷனாகப் பெற்றிருக்கும்`;
- scan 41 `அநியாயமாவது அக்கிரமமாவது.`;
- scan 42 `பாஷைகளே`;
- scan 44 `அரும்பிலேயே`;
- scan 45 `மரண தண்டனை அதற்குத்தீர்ப்பு.`;
- scan 49 `மலரைக் காப்பாற்றினாய்`;
- scan 66 `ஹ ஹ ஹா!` / `சிங்கநாகன்`;
- scan 78 `வெளிநாட்டுக்`;
- scan 89 `(மறைந்து வருபவரில் ஒருவன், இளவரசனின் வாளை விபீஷணனுக்குச் சுட்டிக் காட்டுதல்)`;
- scan 91 `ஓஹோ!` / `சற்றுப்`;
- scan 92 `(விபீஷணன் வாளை உருவிப் பொன்னியின் மேல் வீசுந்தோரணையில் நின்றுகொண்டு)` with earlier `வீரப் பயமுறுத்தல் கூட` retained;
- scan 94 `வரி கொடுக்கமாட்டேன்னு` / `எழுத்துக்கள்`;
- scan 96 `சில சிப்பாய்களால், யாளித்தத்தர் அழைத்து வரப்படுகிறார்`;
- scan 117 scene-30 opener `சித்ராவும்`;
- scan 128 `என் கொலப் பெருமையே போச்சு!`.

## Historical-glyph gate

Full mandatory family gate:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

No global replacement. No spelling, grammar, punctuation, speaker-label or scene-heading normalization. No context-based / plot-based repair. Terminal `blocked` pages do not contribute new secure glyph-bank witnesses at their unresolved locus.

## Exact next activity — CONTINUE VERIFIED-PAGE SCENE ASSEMBLY

Do **not** begin English translation.

1. Assemble and page-record-audit main scenes **9–10** using boundary-aware ranges **32–37** and **37–40**.
2. Assemble main Scene **15** using **53–59**.
3. Assemble main scenes **21–22** using **80–85** and **85–87**.
4. Assemble main Scene **27** using **104–105**.
5. Assemble main Scene **30** using **117–118**.
6. Assemble supplementary `நகைச் சுவைப் பகுதி.` **Scene 1** using boundary-aware scans **119–125**.
7. Then assemble source-secure shared-boundary main Scene **28** and supplementary Scene **2** with explicit boundary-only blocked-page provenance.
8. Only after these are audited proceed to hold-bearing scenes with their exact unresolved markers intact.
9. Synchronize work/root READMEs, `HANDOVER.md`, and this prompt at the next substantial checkpoint.
10. Fetch final live `main` SHA.

## Closed-work safeguard

`திருவாளர் தேசீயம்பிள்ளை` remains **COMPLETE / CLOSED** and its source-condition holds are not to be reopened without new source evidence. `காகிதப்பூ`, `மணிமகுடம்`, and closed `கலைஞரின் நான்மணி மாலை` work also remain closed unless explicitly reopened.
