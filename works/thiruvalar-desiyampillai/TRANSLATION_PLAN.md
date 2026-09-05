# திருவாளர் தேசீயம்பிள்ளை — English translation plan

Status: **AUTHORIZED / IN PROGRESS — BATCH 01 PASS / LOCKED; 2 / 7 ENGLISH SRUs REVIEWED**

The Tamil archival layer remains closed for the current source evidence: source-page coverage **49 / 49**, historical-glyph pass **49 / 49**, structural inventory **PASS**, Tamil source-representation assembly **7 / 7 SRUs**, and `ASSEMBLY_REVIEW.md` **PASS / REVIEWED**.

English translation is now explicitly authorized. Translation must remain independent of and must never reopen or modify that Tamil archival layer.

## 1. Translation authority

Immediate drafting authority is **only** the seven reviewed Tamil SRUs under `scenes/`:

1. `scenes/sru-01-yama-court.md`
2. `scenes/sru-02-guesthouse.md`
3. `scenes/sru-03-eman-interview.md`
4. `scenes/sru-04-gandhi-journey.md`
5. `scenes/sru-05-stairfall-dream-exit.md`
6. `scenes/sru-06-domestic-election-argument.md`
7. `scenes/sru-07-udayasuriyan-kolam-close.md`

Do **not** draft English from OCR, the controlling PDF, another edition, web text, summaries, general knowledge, a prior model transcription, or any published/secondary English witness.

Page records and the controlling PDF may be consulted only when a genuine source question must be adjudicated. They must not be used to bypass or silently alter the reviewed Tamil SRU layer.

Translation choices must never be back-propagated into the Tamil archival files.

## 2. Structural identity

The source has **no numbered scenes or acts**. `SRU-01` through `SRU-07` are repository/editorial source-representation identifiers only.

The English layer mirrors the Tamil SRU filenames rather than manufacturing numbered source scenes:

- `translations/en/sru-01-yama-court.md`
- `translations/en/sru-02-guesthouse.md`
- `translations/en/sru-03-eman-interview.md`
- `translations/en/sru-04-gandhi-journey.md`
- `translations/en/sru-05-stairfall-dream-exit.md`
- `translations/en/sru-06-domestic-election-argument.md`
- `translations/en/sru-07-udayasuriyan-kolam-close.md`

Expected English artifacts: **7**.

Do not add `Scene 1`, `Scene 2`, act numbers, curtain directions, or any other source structure that does not exist in the reviewed Tamil layer.

## 3. Translation goals

The English should be readable and performable while remaining source-faithful. Preserve, to the extent English allows:

- complete dramatic order and SRU boundaries;
- speaker identity and meaningful speaker-label variation;
- narrative prose and stage directions;
- entrances, exits and action cues;
- repetitions, slogans and rhetorical escalation;
- political satire and political rhetoric;
- social-reform and rationalist argumentation;
- election/cost-of-living/language-policy rhetoric;
- jokes, sarcasm, irony and wordplay;
- colloquial register and code-switching;
- proper names and historically specific terms;
- source ambiguity, malformed forms and unresolved source evidence.

Do not silently modernize, euphemize, ideologically soften, correct, regularize or complete the Tamil text while translating it.

## 4. Source-loss / unresolved-marker policy

### `[paper loss]`

The exact marker **`[paper loss]`** must remain visible in the English artifact at the corresponding point.

- Do not translate it into prose.
- Do not infer the missing word from grammar, repetition, context or another edition.
- Do not use the intact repetition on scan 9 to complete the damaged first occurrence.

SRU-01 therefore preserves all **7** page-layer `[paper loss]` locations. Batch 01 review confirms **7 / 7 retained**.

### `[unresolved glyph cluster]`

The exact marker **`[unresolved glyph cluster]`** must remain visible in the corresponding SRU-04 English location.

The apparent scan-35 reading resembling `கொழுப்பேறி` is non-canonical and must not be translated as though resolved.

### `[unresolved descriptive cluster]`

Both exact **`[unresolved descriptive cluster]`** markers from scan 36 must remain visible in the English SRU-04 artifact.

No descriptive wording may be supplied from semantic expectation.

These markers are provenance controls, not English prose. They survive until genuine source evidence resolves the underlying Tamil record.

## 5. Source-sensitive structural safeguards

- SRU-01 remains an assembly containing source-loss markers; translation must not conceal that limitation.
- SRU-04 remains an assembly containing three unresolved source markers; translation must not resolve them editorially.
- Scan-47 centered **`உதயசூரியன் கோலம்`** remains an **internal descriptive/intertitle inside SRU-07**, not a source scene title.
- Its English rendering should appear as a standalone internal line at the corresponding position, while preserving its internal/intertitle status.
- Scan 48 has no source-visible `முற்றும்`; therefore the English layer must **not** add `The End`, `End`, a curtain cue, or any equivalent invented closure.
- Scan 49 back-cover advertising remains outside the English dramatic layer.

## 6. Proper names, labels and recurring terms

Translation should prefer transparent transliteration for proper names unless an established English form is necessary for comprehension.

Source spelling/spacing variation must remain traceable. In particular:

- `தேசீயம் பிள்ளை` and `தேசீயம்பிள்ளை` are distinct source-visible forms; do not use English translation to rewrite the Tamil archival layer into one normalized spelling;
- abbreviated speaker label `தேசீ :` must remain recognizably linked to the same character without pretending the Tamil source used a single uniform label;
- `எமன் / எமதர்மன் / எமதர்ம ராஜன்` should be rendered consistently with context while preserving meaningful distinctions in the Tamil wording;
- `காங்கிரஸ்`, `தி. மு. க`, `உதய சூரியன்`, `தமிழ் வாழ்க`, `ஹரிஜன நலம்`, `ஆகாஷவாணி`, `நவகாளி`, `சொர்க்கம்`, and other historically/politically loaded terms must not be ideologically softened or silently replaced by present-day paraphrases.

Where a term has no clean English equivalent, transliteration plus a concise translation note is preferable to an overconfident substitution.

## 7. Translation file metadata

Each English SRU uses metadata such as:

```yaml
---
source_scene_number: null
structural_unit: "SRU-01"
work: "thiruvalar-desiyampillai"
source_sru: "../../scenes/sru-01-yama-court.md"
source_scan_pages: [7, 8, 9, 10, 11, 12, 13, 14, 15]
status: "translation-draft"
translation_review: "pending"
language: "en"
secondary_english_witness_used: false
---
```

After full Tamil→English fidelity review of that artifact, change only the English artifact metadata to:

- `status: "translation-reviewed"`
- `translation_review: "passed"`

For SRU-01 and SRU-04, source-loss/unresolved provenance must also be described in translation notes. Do not imply those Tamil source areas are fully verified.

## 8. Translation notes

Each English artifact may end with a concise `## Translation notes` section only for materially source-sensitive decisions, such as:

- wordplay that cannot be reproduced exactly in English;
- politically or culturally specific terms retained by transliteration;
- source speaker-label anomalies;
- ambiguous or malformed Tamil wording;
- surviving source-loss/unresolved markers;
- a deliberately literal rendering needed to preserve rhetoric or satire.

Do not use notes to silently rewrite the main translation into a smoother but unsupported version.

## 9. Review procedure for every English SRU

Before an English artifact can be marked reviewed/passed:

1. read the complete reviewed Tamil SRU;
2. draft the entire English artifact from that Tamil SRU only;
3. compare the complete English artifact back to the complete Tamil SRU;
4. confirm every dramatic paragraph, speaker turn, stage direction, narrative transition and repetition is represented;
5. verify SRU start/end anchors and source order;
6. confirm political/social rhetoric, humour, colloquial speech and rhetorical cadence have not been flattened or softened;
7. confirm every source-loss/unresolved marker appears in the corresponding English location when applicable;
8. confirm no text from a later/earlier SRU has been duplicated or omitted;
9. document materially source-sensitive choices in `## Translation notes`;
10. only then set `translation_review: "passed"`.

A completed batch must receive its own durable `BATCH_0N_REVIEW.md` record before it is called locked.

## 10. Translation batching and progress

The seven SRUs are divided into four review batches so the two large/high-risk units receive dedicated attention.

### Batch 1 — **PASS / LOCKED**

- `sru-01-yama-court.md` — translated and reviewed;
- `sru-02-guesthouse.md` — translated and reviewed.

Durable review: `translations/en/BATCH_01_REVIEW.md`.

Controls passed:

- SRU-01 `[paper loss]`: **7 / 7 retained**;
- artifacts reviewed: **2 / 2**;
- secondary-English witness use: **0**;
- blocking translation issues: **0**.

### Batch 2 — **NEXT**

- `sru-03-eman-interview.md`

Dedicated batch because of sustained tax/political satire, speaker-label variation and wordplay.

### Batch 3

- `sru-04-gandhi-journey.md`

Dedicated batch because it is the longest unit and contains all three unresolved source markers.

### Batch 4

- `sru-05-stairfall-dream-exit.md`
- `sru-06-domestic-election-argument.md`
- `sru-07-udayasuriyan-kolam-close.md`

Special controls: preserve the stair/place-name wordplay, domestic colloquial/political register, internal `உதயசூரியன் கோலம்` intertitle, and the source close without an invented `The End`.

Expected completed batches: **4**; completed: **1 / 4**.

## 11. Final English review gate

After all seven English artifacts have individually passed review:

1. create `translations/en/TRANSLATION_REVIEW.md`;
2. verify **7 / 7** English artifacts present and reviewed;
3. verify all four SRU-batch review records are PASS / LOCKED;
4. verify SRU order and boundaries mirror the reviewed Tamil layer;
5. verify no source scene/act numbering was invented;
6. verify all **7** `[paper loss]` markers survive in SRU-01;
7. verify the **1 + 2** unresolved markers survive in SRU-04;
8. verify `உதயசூரியன் கோலம்` remains an internal intertitle in SRU-07;
9. verify no invented `The End` / `முற்றும்` equivalent exists;
10. verify `secondary_english_witness_used: false` across all first-pass English artifacts;
11. verify translation choices have not modified the Tamil archival layer.

Only after that final review may the English first-pass translation layer be called complete/closed.

## 12. Secondary English witnesses

This first source-faithful English phase uses **no secondary English witness**.

If a published or other English translation is later supplied, comparison with it must be a separately authorized phase after this independent English layer is closed. That later comparison must not retroactively contaminate the first-pass English wording.

## 13. Current phase state

English translation was explicitly authorized by the user's instruction to proceed with the planned next activity.

Current English status:

- expected artifacts: **7**;
- present: **2 / 7**;
- reviewed: **2 / 7**;
- completed batches: **1 / 4**;
- Batch 01: **PASS / LOCKED**;
- secondary-English witness use: **0**;
- Tamil archival layer modified by translation: **no**.

## Exact next activity

Begin **English Translation Batch 02** from the reviewed Tamil SRU only:

- `scenes/sru-03-eman-interview.md` → `translations/en/sru-03-eman-interview.md`

Perform the complete Tamil→English fidelity review for the artifact and create `translations/en/BATCH_02_REVIEW.md` before marking Batch 02 PASS / LOCKED.
