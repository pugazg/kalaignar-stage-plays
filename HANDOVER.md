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
12. `works/ore-mutham/SCENE_ASSEMBLY_AUDIT.md`;
13. `works/ore-mutham/scenes/*.md` as needed;
14. canonical `works/ore-mutham/pages/0001.md`–`0131.md` as needed;
15. supplied controlling PDF only when new source-dependent adjudication is attempted.

## Source identity

Controlling PDF: `TVA_BOK_0064325_ஒரே_முத்தம்.pdf`

- file size: **224,884,964 bytes**;
- physical scans: **131**;
- SHA-256: **`60780e340e6b0c6d6f3956af8beeb69692fab3f20e843c6ed4275b9962aae220`**;
- source PDF committed to repository: **no**.

## Major checkpoint — FULL TAMIL SCENE ASSEMBLY COMPLETE / AUDIT PASS

- raw source pass: **131 / 131 COMPLETE**;
- physical-range closure audit: **131 / 131 COMPLETE**;
- residual-hold re-audit: **COMPLETE**;
- verified physical scans: **103 / 131**;
- terminal current-source-condition / `blocked`: **28 / 131**;
- ordinary `needs-review` remaining in terminal set: **0**;
- historical-glyph PASS: **103 / 131**;
- main structural scene anchors: **30 / 30**;
- supplementary `நகைச் சுவைப் பகுதி.` anchors: **3 / 3**;
- terminal hold inventory: **COMPLETE**;
- scene-boundary audit: **COMPLETE**;
- boundary-aware structural inventory: **COMPLETE**;
- main Tamil scene files assembled: **30 / 30**;
- supplementary Tamil scene files assembled: **3 / 3**;
- complete Tamil scene layer: **33 / 33**;
- full page-to-scene consistency audit: **33 / 33 PASS**;
- Tamil work-level pre-release / closure gate: **NEXT**;
- English translation: **not authorized / not started**.

### Verified scans — 103 / 131

`2–20`, `22–26`, `28–42`, `44–46`, `49–50`, `53–59`, `62–64`, `66–68`, `70–71`, `75–76`, `78`, `80–87`, `89`, `91–93`, `96–97`, `101–111`, `114–127`, `129`, `131`.

### Terminal current-source-condition scans — 28 / 131

`1`, `21`, `27`, `43`, `47–48`, `51–52`, `60–61`, `65`, `69`, `72–74`, `77`, `79`, `88`, `90`, `94–95`, `98–100`, `112–113`, `128`, `130`.

These are **terminal current-source-condition holds**, not unreviewed pages. Exact unresolved loci remain in page files and `TERMINAL_SOURCE_CONDITION_HOLDS.md`. Reopen only with genuinely stronger source evidence.

## Boundary-aware permanent rule

A physical transition page may contain both the end of one scene and the heading/opening of the next. Therefore a transition scan may contribute source text to **both adjacent scene files**. Hold ownership is segment-level.

Durable consequences:

- Scene 7 genuinely carries a Scene-7 hold on scan 27;
- Scene 18 does not inherit scan 72's later Scene-19 hold;
- Scene 23 does not inherit scan 94's later Scene-24 hold;
- main Scene 28 uses only the secure pre-Scene-29 part of globally blocked scan 112;
- supplementary Scene 2 uses only the secure pre-Scene-3 part of globally blocked scan 128.

## Final scene classes

### Fully verified-input scenes — 13

Main: **1–5, 9–10, 15, 21–22, 27, 30**.

Supplementary: **Scene 1**.

These are `assembly-reviewed`, `assembled_from_verified_pages: true`, `page_record_fidelity: "passed"`, `source_condition_scans: []`.

### Source-secure shared-boundary scenes — 2

- main Scene **28**;
- supplementary Scene **2**.

These are `assembly-reviewed`, `assembled_from_verified_pages: false`, `page_record_fidelity: "passed"`, `source_condition_scans: []`, with explicit provenance that the blocked locus belongs only to the following scene.

### Hold-bearing scenes — 18

Main: **6–8, 11–14, 16–20, 23–26, 29**.

Supplementary: **Scene 3**.

Scene-relevant terminal dependencies:

- 6 `[21]`;
- 7 `[27]`;
- 8 `[27]`;
- 11 `[43]`;
- 12 `[47, 48, 51]`;
- 13 `[52]`;
- 14 `[52]`;
- 16 `[60, 61]`;
- 17 `[65]`;
- 18 `[69]`;
- 19 `[72, 73, 74]`;
- 20 `[77, 79]`;
- 23 `[88, 90]`;
- 24 `[94, 95]`;
- 25 `[98, 99]`;
- 26 `[100]`;
- 29 `[112, 113]`;
- supplementary 3 `[128, 130]`.

These use `status: "assembly-held"`, `assembled_from_verified_pages: false`, and `page_record_fidelity: "passed-with-terminal-source-hold"` or plural. Explicit source-held markers and canonical provisional blocked-page wording are preserved. Assembly fidelity PASS does not resolve the underlying source condition.

## Full assembly audit result

`works/ore-mutham/SCENE_ASSEMBLY_AUDIT.md` is the durable audit authority:

- assembled scene files: **33 / 33**;
- page-record consistency: **PASS 33 / 33**;
- source-secure scene files: **15**;
- hold-bearing scene files: **18**;
- terminal loci repaired from context: **0**;
- source wording normalized: **0**;
- unresolved wording invented: **0**;
- OCR / plot / another-edition completion: **0**.

## Terminal hold policy

Permanent rule:

- no source-held wording from context;
- no OCR expectation;
- no another-edition completion;
- no spelling / grammar / punctuation / speaker-label / scene-heading normalization;
- no global historical-glyph replacement;
- a `blocked` record may be reopened only with genuinely stronger source evidence.

## Durable source findings

Keep all page-level corrections authoritative, especially:

- scan 23 `ஏழைகள்!` / `ஆனா`;
- scan 36 `மன்னனைக்`;
- scan 39 `புயல்காற்றைப் புருஷனாகப் பெற்றிருக்கும்`;
- scan 41 `அநியாயமாவது அக்கிரமமாவது.`;
- scan 42 `பாஷைகளே`;
- scan 45 `மரண தண்டனை அதற்குத்தீர்ப்பு.`;
- scan 49 `மலரைக் காப்பாற்றினாய்`;
- scan 66 `ஹ ஹ ஹா!` / `சிங்கநாகன்`;
- scan 78 `வெளிநாட்டுக்`;
- scan 89 `(மறைந்து வருபவரில் ஒருவன், இளவரசனின் வாளை விபீஷணனுக்குச் சுட்டிக் காட்டுதல்)`;
- scan 91 `ஓஹோ!` / `சற்றுப்`;
- scan 92 `(விபீஷணன் வாளை உருவிப் பொன்னியின் மேல் வீசுந்தோரணையில் நின்றுகொண்டு)` with `வீரப் பயமுறுத்தல் கூட`;
- scan 94 `வரி கொடுக்கமாட்டேன்னு` / `எழுத்துக்கள்`;
- scan 96 `சில சிப்பாய்களால், யாளித்தத்தர் அழைத்து வரப்படுகிறார்`;
- scan 117 `சித்ராவும்`;
- scan 128 `என் கொலப் பெருமையே போச்சு!`.

## Mandatory historical-glyph gate

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

Only whole-page `verified` pages may contribute new secure same-edition reference forms. Terminal `blocked` pages keep the family gate open at their unresolved locus.

## Exact next activity — Tamil pre-release / work-level closure gate

Do **not** begin English translation.

1. Verify the scene-file inventory is exactly main `01–30` plus supplementary `01–03`, with no duplicate/missing files or numbering leakage.
2. Verify all **28** terminal physical-page holds remain traceable at page level and all scene-relevant holds remain traceable in the scene layer.
3. Reconcile stale secondary index/status labels — especially legacy `needs-review` entries in `indexes/page-map.md` — to the terminal `blocked` classification, without changing canonical page text or pretending the holds are resolved.
4. Run/document the Tamil work-level release/closure decision under the repository's terminal-source-condition policy.
5. Synchronize work/root READMEs, this handover and `NEXT_CHAT_PROMPT.md` with the closure result.
6. Fetch final live `main` SHA.

# CLOSED WORK SAFEGUARDS

`திருவாளர் தேசீயம்பிள்ளை`, `காகிதப்பூ`, `மணிமகுடம்`, and closed `கலைஞரின் நான்மணி மாலை` components remain closed unless explicitly reopened with new source evidence or a separately authorized phase.
