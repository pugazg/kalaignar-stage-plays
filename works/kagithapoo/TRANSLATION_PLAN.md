# காகிதப்பூ — English translation plan

Status: **AUTHORIZED / BATCH 1 COMPLETE — PASS / LOCKED**

The Tamil archival layer is already closed: page layer **41 / 41 verified**, scene assembly **COMPLETE / CLOSED**, and final scene-assembly review **PASS**.

The user's instruction to proceed after Tamil closure authorizes the separate English-translation phase. This document defines the translation controls for all English batches.

## 1. Translation authority

Immediate drafting authority is the closed verified Tamil scene layer under `scenes/`.

English translation must **not** be drafted from:

- OCR output;
- `kaagidha_poo.md` first-pass text;
- the controlling PDF as a substitute for the verified scene layer;
- a modern/later edition;
- web text, summaries or general knowledge;
- any published/secondary English witness.

If a source-level question arises during translation, consult the corresponding verified page record and, only when necessary, the controlling PDF as adjudication support. Translation itself does not reopen or silently alter the locked Tamil layer.

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

Expected English scene-representation artifacts: **23**.

There must be **no `22.md` or `23.md`**, because the source prints no Scene 22/23 numbers. The unnumbered block between Scenes 21 and 24 must remain explicitly unnumbered.

## 3. Translation goals

The English should be readable and performable while remaining source-faithful.

Preserve:

- dramatic structure and scene order;
- speaker identity and meaningful speaker-label distinctions;
- stage directions and entrances/exits;
- repetitions, slogans and rhetorical cadence;
- political and Dravidian/rationalist rhetoric;
- satire, jokes, sarcasm and wordplay;
- colloquial register where the Tamil is colloquial;
- source ambiguity where certainty is not supported.

Do not silently modernize, euphemize or ideologically soften the text. If a source-sensitive choice cannot be represented cleanly in English, retain the best supported rendering and document it in a translation note rather than inventing certainty.

Proper names should normally be transliterated from the verified Tamil layer. Outside knowledge must not be used to normalize a source-sensitive name or term unless separately authorized as a comparison layer.

## 4. Source-compressed / anomalous structures

### `02-05.md`

Preserve the source's collective/compressed representation of Scenes 2–5. Do not invent missing dialogue or narrative bodies.

### `unnumbered-between-21-and-24.md`

Preserve the fact that the source heading is only `காட்சி,` with no numeral. The English artifact may describe it as an unnumbered scene, but must never assign or imply Scene 22 or Scene 23.

### `25.md`

Preserve Scene 25 as the source-compressed bracketed campaign-action representation only. Do not expand it into dialogue.

## 5. Recurring terminology control

Establish recurring English equivalents progressively from the verified scene context and record stable choices in `translations/en/README.md` as they become durable.

Terms likely to require consistent treatment include:

- `திராவிட முன்னேற்றக் கழகம்`;
- `காங்கிரஸ்`;
- `சோஷலிசம்`;
- `சமதர்மம்`;
- `காகிதப்பூ`;
- `பாரிஜாதப்பூ`;
- `உதயசூரியன்`;
- `இந்தி`;
- `ஆங்கிலம்`;
- `மகாநாடு`.

Do not pre-lock an uncertain equivalent merely for consistency. Context and source rhetoric control the choice.

Batch-1 durable choices are recorded in `translations/en/README.md` and may be reused only in matching contexts.

## 6. English scene-file format

Recommended front matter for a normal numbered scene:

```yaml
---
scene: 1
work: "kagithapoo"
source_scene: "../../scenes/01.md"
source_scan_pages: [...]
printed_pages: [...]
status: "translation-draft"
translation_review: "pending"
language: "en"
secondary_english_witness_used: false
---
```

After Tamil→English fidelity review passes:

```yaml
status: "translation-reviewed"
translation_review: "passed"
```

For source-compressed or unnumbered artifacts, preserve the corresponding Tamil artifact's structural identity in front matter rather than manufacturing a normal scene number.

Each English artifact should end with `## Translation notes` containing only source-sensitive decisions, ambiguities, puns, culturally specific expressions or terminology choices that materially benefit from documentation. Ordinary phrases should not be over-annotated.

## 7. Review gate

For each batch:

1. draft only from the corresponding closed Tamil `scenes/*.md` artifacts;
2. compare every English artifact back against its Tamil scene for complete coverage;
3. verify speaker turns, stage directions, repetitions, scene structure and rhetorical force;
4. resolve or explicitly record any translation ambiguity;
5. set each reviewed file to `translation-reviewed` / `passed` only after the fidelity review;
6. update `translations/en/README.md` with the durable batch result.

Batch-review records may be added under `translations/en/` to preserve the review result. Batch 1 is recorded in `translations/en/BATCH_01_REVIEW.md` — **PASS / LOCKED**.

After all 23 English artifacts are complete, create `translations/en/TRANSLATION_REVIEW.md` for the final Tamil→English coverage/fidelity review.

## 8. Batch plan

### Batch 1 — COMPLETE / PASS / LOCKED

- `01.md`
- `02-05.md`
- `06.md`
- `07.md`
- `08.md`

### Batch 2 — NEXT

- `09.md`
- `10.md`
- `11.md`
- `12.md`
- `13.md`

### Batch 3

- `14.md`
- `15.md`
- `16.md`
- `17.md`
- `18.md`

### Batch 4

- `19.md`
- `20.md`
- `21.md`
- `unnumbered-between-21-and-24.md`
- `24.md`

Scene 21 is comparatively large; Batch 4 may be split operationally if needed, but artifact order and review controls must remain unchanged.

### Batch 5

- `25.md`
- `26.md`
- `27.md`

## 9. Phase safeguards

- Tamil page records remain locked unless genuine source evidence requires a separately documented correction.
- Tamil scene assemblies remain locked unless such a source correction propagates into them.
- Translation choices must never be back-propagated into the Tamil archival text.
- No secondary English witness is authorized for drafting or silent correction.
- The scan-130 `கண்டுபிடியுங்கள்` box and scan-131 cast/imprint material remain outside Scene 27's dramatic translation because they are outside the closed Tamil scene artifact.

## Current English status

- expected artifacts: **23**;
- present: **5 / 23**;
- reviewed: **5 / 23**;
- completed batches: **1 / 5**;
- unresolved blocking translation issues: **0**;
- secondary-English contamination: **0**.

## Exact next activity

Translate and Tamil→English review **Batch 2** from the closed Tamil scene layer only:

`09.md`, `10.md`, `11.md`, `12.md`, `13.md`.

Do not use OCR, the MD first pass, the PDF, a modern edition or a secondary English text as the drafting authority.