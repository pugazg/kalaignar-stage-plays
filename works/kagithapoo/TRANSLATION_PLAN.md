# காகிதப்பூ — English translation plan

Status: **AUTHORIZED / BATCHES 1–4 COMPLETE — PASS / LOCKED**

The Tamil archival layer is closed: page layer **41 / 41 verified**, scene assembly **COMPLETE / CLOSED**, final scene-assembly review **PASS**.

## 1. Translation authority

Immediate drafting authority is the closed verified Tamil scene layer under `scenes/`.

English translation must **not** be drafted from OCR, `kaagidha_poo.md`, the controlling PDF as a substitute for the verified scene layer, a modern/later edition, web text, summaries, general knowledge or a published/secondary English witness.

If a genuine source-level question arises, verified page records and, only when necessary, the controlling PDF may be consulted as adjudication support. Translation itself does not reopen or silently alter the locked Tamil layer.

## 2. Expected English artifact mapping

Mirror the closed Tamil scene representation exactly under `translations/en/`:

- `01.md`;
- `02-05.md` — source-compressed Scenes 2–5;
- `06.md` through `21.md`;
- `unnumbered-between-21-and-24.md` — source-visible unnumbered `காட்சி,`;
- `24.md`;
- `25.md` — source-compressed campaign-action scene;
- `26.md`;
- `27.md`.

Expected English source-representation artifacts: **23**.

There must be **no `22.md` or `23.md`**. The unnumbered block between Scenes 21 and 24 must remain explicitly unnumbered.

## 3. Translation goals

The English should be readable and performable while remaining source-faithful. Preserve dramatic structure, speaker identity, stage directions, repetitions, slogans, political and Dravidian/rationalist rhetoric, satire, jokes, sarcasm, colloquial register, wordplay and supported ambiguity.

Do not silently modernize, euphemize or ideologically soften the text. If a source-sensitive choice cannot be represented cleanly in English, retain the best supported rendering and document it in a translation note rather than inventing certainty.

Proper names should normally be transliterated from the verified Tamil layer. Outside knowledge must not be used to normalize a source-sensitive name or term unless separately authorized as a comparison layer.

## 4. Structural safeguards

- `02-05.md` remains source-compressed; no dialogue/body may be invented.
- `unnumbered-between-21-and-24.md` preserves the source heading with no numeral and never assigns or implies Scene 22 or Scene 23.
- `25.md` remains source-compressed campaign action only.
- scan-130 boxed `கண்டுபிடியுங்கள்` and scan-131 cast/imprint material remain outside Scene 27's dramatic translation because they are outside the closed Tamil scene artifact.

## 5. Recurring terminology control

Stable choices are established progressively from the verified scene context and recorded in `translations/en/README.md`. Do not force an uncertain term into a fixed English equivalent merely for consistency.

Durable choices through Batch 4 are recorded in the English tracker and batch-review files.

## 6. English scene-file format

Normal reviewed file front matter:

```yaml
---
scene: 1
work: "kagithapoo"
source_scene: "../../scenes/01.md"
source_scan_pages: [...]
printed_pages: [...]
status: "translation-reviewed"
translation_review: "passed"
language: "en"
secondary_english_witness_used: false
---
```

Source-compressed or unnumbered artifacts must preserve their Tamil structural identity rather than manufacture a normal scene number.

Each English artifact ends with concise `## Translation notes` only for source-sensitive decisions, ambiguity, wordplay or terminology that materially benefits from documentation.

## 7. Review gate

For each batch:

1. draft only from the corresponding closed Tamil `scenes/*.md` artifacts;
2. compare every English artifact back against its complete Tamil scene;
3. verify speaker turns, stage directions, repetitions, scene structure and rhetorical force;
4. resolve or explicitly record translation ambiguity;
5. set `translation-reviewed` / `passed` only after fidelity review;
6. update the English tracker and a durable batch-review record.

Completed review records:

- `translations/en/BATCH_01_REVIEW.md` — **PASS / LOCKED**;
- `translations/en/BATCH_02_REVIEW.md` — **PASS / LOCKED**;
- `translations/en/BATCH_03_REVIEW.md` — **PASS / LOCKED**;
- `translations/en/BATCH_04_REVIEW.md` — **PASS / LOCKED**.

After all 23 English artifacts are complete, create `translations/en/TRANSLATION_REVIEW.md` for the final Tamil→English coverage/fidelity review. The English layer is not complete/closed until that final review passes.

## 8. Batch plan

### Batch 1 — COMPLETE / PASS / LOCKED

`01.md`, `02-05.md`, `06.md`, `07.md`, `08.md`

### Batch 2 — COMPLETE / PASS / LOCKED

`09.md`, `10.md`, `11.md`, `12.md`, `13.md`

### Batch 3 — COMPLETE / PASS / LOCKED

`14.md`, `15.md`, `16.md`, `17.md`, `18.md`

### Batch 4 — COMPLETE / PASS / LOCKED

`19.md`, `20.md`, `21.md`, `unnumbered-between-21-and-24.md`, `24.md`

Batch-4 safeguards include preservation of the unnumbered post-21 source scene, no invented Scene 22/23, full Scene-21 political/language-policy coverage, and the Scene-24 Parijatha/paper-flower title metaphor.

### Batch 5 — NEXT

`25.md`, `26.md`, `27.md`

## Current English status

- expected artifacts: **23**;
- present: **20 / 23**;
- reviewed: **20 / 23**;
- completed batches: **4 / 5**;
- unresolved blocking translation issues: **0**;
- secondary-English contamination: **0**.

## Exact next activity

Translate and Tamil→English review **Batch 5** from the closed Tamil scene layer only:

`25.md`, `26.md`, `27.md`.

Then create and complete `translations/en/TRANSLATION_REVIEW.md` across all 23 English artifacts before declaring the English phase complete/closed.