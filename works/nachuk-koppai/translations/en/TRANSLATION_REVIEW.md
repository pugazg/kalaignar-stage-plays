# நச்சுக்கோப்பை — Final English Translation Review

Status: **PASS / COMPLETE / CLOSED FOR CURRENT TAMIL SOURCE EVIDENCE — 18 / 18 ENGLISH SCENES REVIEWED; 4 / 4 BATCHES PASS / LOCKED; SCENE 5 SOURCE HOLD PRESERVED**

Immediate authority: the closed Tamil scene layer under `../../scenes/`.

English is a derivative archival layer. This final review does not reopen, normalize or overwrite the Tamil page or scene layer.

## 1. Artifact completeness

Expected English scene artifacts:

- `01.md` through `18.md` — **18**.

Final state:

- present: **18 / 18**;
- translation-reviewed: **18 / 18**;
- missing: **0**;
- duplicate numbered English scenes: **0**;
- batch-review artifacts: **4 / 4 present**.

Each English artifact maps one-to-one to the corresponding closed Tamil scene through `source_scene`.

## 2. Source-span / metadata consistency

All 18 English scene front matters were checked.

Result: **PASS**.

Confirmed across the set:

- each `source_scene` points to the matching Tamil scene number;
- each `source_scan_pages` matches the closed Tamil scene span;
- `language: "en"` is used throughout;
- `secondary_english_witness_used: false` is used throughout;
- source-secure scenes carry ordinary `translation-reviewed / passed` state;
- Scene 5 alone carries `translation-reviewed-with-source-holds / passed-with-source-holds`.

## 3. Batch closure

- `BATCH_01_REVIEW.md` — Scenes 1–5 — **PASS / LOCKED — Scene 5 source hold preserved**;
- `BATCH_02_REVIEW.md` — Scenes 6–10 — **PASS / LOCKED**;
- `BATCH_03_REVIEW.md` — Scenes 11–15 — **PASS / LOCKED**;
- `BATCH_04_REVIEW.md` — Scenes 16–18 — **PASS / LOCKED**.

Completed translation batches: **4 / 4**.

## 4. Whole-work Tamil→English fidelity gate

The final review confirms the completed English layer preserves the reviewed Tamil dramatic structure and the batch-level fidelity decisions:

- scene order and identity preserved;
- source-secure speaker turns represented;
- source-secure stage directions, entrances, exits, songs, letters and internal scene transitions represented;
- romantic dialogue and imagery retained;
- religious / astrological satire retained;
- rationalist, Self-Respect, social-reform, anti-caste, class and gender rhetoric retained rather than neutralized;
- widow-remarriage arguments retained explicitly;
- alcohol critique and repeated rhetorical refrains retained;
- colloquial humour, code-switching and source-specific insults retained where dramatically material;
- source-visible unusual wording was not repaired by silently changing the closed Tamil layer;
- no Tamil scene artifact was changed by the English phase;
- no OCR text, web text, later edition or secondary/published English translation was used as drafting authority;
- secondary-English contamination: **0**.

Repository comparison from the Tamil-scene closure checkpoint through completion of all four English batches shows **no file under `works/nachuk-koppai/scenes/` changed during translation**.

Whole-work fidelity result: **PASS**.

## 5. Source-condition transparency

The closed Tamil layer contains one terminal source-condition hold:

- scan **22** / Scene **5** — two adjacent unidentified source clusters after `சாந்தா`.

Final English state:

- source-hold-bearing English scenes: **1 / 18 — Scene 5**;
- Scene 5 carries `source_condition_scans: [22]`;
- an explicit `Source-held` marker is present;
- the earlier guessed character forms are absent;
- no English wording is invented for the two unreadable clusters;
- the user's view that the locus likely indicates a song/performance remains only an interpretation note;
- Tamil source holds resolved by translation: **0**.

Result: **PASS — HOLD PRESERVED TRANSPARENTLY**.

## 6. Source-sensitive reviewed readings

### Scene 3

User-confirmed scan-20 `வேணும்னாலும்` is reflected in the secure translation meaning “whatever they want.”

### Scene 9

User-confirmed `சுடகோடி` is preserved as **Sudakodi** in **Sudakodi Surya Narayana Ayyar**.

No etymology, lexical normalization or unsupported meaning is assigned to `சுடகோடி`.

### Scene 18

Confirmed:

- the multilingual / phonetic police passage remains represented conservatively as performance text;
- it was not externally normalized into standard Telugu or Malayalam;
- the dramatic body does **not** contain non-authorial `4063`;
- the dramatic body does **not** contain the printer imprint;
- the final source-visible `முற்றும்` is represented as **The End**.

The translation note may mention `4063` only to document its exclusion; it is not dramatic text.

## 7. Stable translation conventions

Core reviewed forms include:

- Santha;
- Ekambaram;
- Pazhaniyappan / Pazhani;
- Maniyappa Mudaliar / Maniyappa;
- Azhagappan;
- Ayyar;
- Kandhan;
- Pitchumani;
- Meenakshi;
- Adikesava Mudaliar;
- Sivaguru;
- Jambu;
- Ganapathi;
- Chinnaiya Pillai;
- Kannaiya Chetti;
- Karuppan;
- Sudakodi Surya Narayana Ayyar;
- Ariyalur;
- Tamilagam;
- Dravidam;
- Arignar Anna.

Source-sensitive retained terms include:

- `nalungu`, `namaskaram`, `dakshina`, `padi`, `salli`;
- `Radha Kalyanam`, `katha-kalakshepam`, `marakkal`, `dharmakartha`, `kumbabhishekam`;
- `tiruppani`, `thuthivannam`, `soma-panam`, `thali`, `shastra`;
- `Chandalas` / historically specific caste-marked or insulting source forms where the dramatic wording itself matters;
- `kammanatti` in Scene 18 as a preserved historical insult rather than a silently substituted modern label.

No reviewed English convention overwrites the Tamil archive.

## 8. Final English state

**ENGLISH TRANSLATION COMPLETE / CLOSED FOR CURRENT TAMIL SOURCE EVIDENCE — 18 / 18 SCENES PRESENT AND REVIEWED; 4 / 4 BATCHES PASS / LOCKED; WHOLE-WORK TAMIL→ENGLISH FIDELITY PASS; 1 / 1 HOLD-BEARING SCENE PRESERVES ITS TAMIL HOLD; 0 TAMIL HOLDS RESOLVED BY TRANSLATION; 0 ENGLISH BLOCKERS; 0 SECONDARY-ENGLISH CONTAMINATION.**

No English translation scene remains pending.

## 9. Reopening rule

Do not reopen the completed English layer merely to smooth wording.

Reopen only for a separately authorized phase, such as:

- documented editorial refinement;
- comparison against an explicitly introduced independent English witness;
- genuinely stronger Tamil source evidence that first passes the Tamil reopening/adjudication rules and then requires corresponding English revision.

The separate P0 SHA-256 fingerprint remains pending. It is **not** part of English closure and must not be computed/promoted unless separately authorized.
