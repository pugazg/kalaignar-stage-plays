# திருவாளர் தேசீயம்பிள்ளை — English translation plan

Status: **AUTHORIZED / IN PROGRESS — BATCHES 01–03 PASS / LOCKED; 4 / 7 ENGLISH SRUs REVIEWED**

The Tamil archival layer remains closed for the current source evidence: source-page coverage **49 / 49**, historical-glyph pass **49 / 49**, structural inventory **PASS**, Tamil source-representation assembly **7 / 7 SRUs**, and `ASSEMBLY_REVIEW.md` **PASS / REVIEWED**.

English translation is explicitly authorized. Translation remains independent of and must never reopen or modify that Tamil archival layer.

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

The English layer mirrors the Tamil SRU filenames:

- `translations/en/sru-01-yama-court.md`
- `translations/en/sru-02-guesthouse.md`
- `translations/en/sru-03-eman-interview.md`
- `translations/en/sru-04-gandhi-journey.md`
- `translations/en/sru-05-stairfall-dream-exit.md`
- `translations/en/sru-06-domestic-election-argument.md`
- `translations/en/sru-07-udayasuriyan-kolam-close.md`

Expected English artifacts: **7**.

Do not add source scene numbering, act numbering, curtain directions, or other unsupported structure.

## 3. Translation goals

Preserve, to the extent English allows:

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

SRU-01 preserves all **7 / 7** exact `[paper loss]` markers. Batch 01 review has locked that result.

### `[unresolved glyph cluster]`

SRU-04 preserves the exact scan-35 `[unresolved glyph cluster]` marker. Batch 03 review confirms **1 / 1 retained**. The apparent reading resembling `கொழுப்பேறி` remains non-canonical and is not translated as resolved.

### `[unresolved descriptive cluster]`

SRU-04 preserves both exact scan-36 `[unresolved descriptive cluster]` markers. Batch 03 review confirms **2 / 2 retained**.

No descriptive wording may be supplied from semantic expectation. These markers are provenance controls, not English prose.

## 5. Source-sensitive structural safeguards

- SRU-01 remains visibly source-damaged where the Tamil source is physically lost.
- SRU-04 remains visibly unresolved at all three source-marker locations.
- Scan-47 centered **`உதயசூரியன் கோலம்`** remains an **internal descriptive/intertitle inside SRU-07**, not a source scene title.
- Its English rendering must remain an internal standalone line at the corresponding position.
- Scan 48 has no source-visible `முற்றும்`; the English layer must **not** add `The End`, `End`, a curtain cue, or equivalent invented closure.
- Scan 49 back-cover advertising remains outside the English dramatic layer.

## 6. Proper names, labels and recurring terms

Translation should prefer transparent transliteration where a confident English replacement would erase source register or over-resolve ambiguity.

Source spelling/spacing variation must remain traceable. Historically/politically loaded terms must not be ideologically softened or silently replaced by present-day paraphrases.

Where a term has no clean English equivalent, transliteration plus a concise translation note is preferable to an overconfident substitution.

## 7. Translation file metadata

Every reviewed English SRU must use:

```yaml
source_scene_number: null
status: "translation-reviewed"
translation_review: "passed"
secondary_english_witness_used: false
```

During drafting it remains `translation-draft` / `pending`. SRU-01 and SRU-04 additionally record their source-loss/unresolved provenance.

## 8. Translation notes

Each English artifact may end with a concise `## Translation notes` section only for materially source-sensitive decisions, including wordplay, culturally specific terms, speaker-label anomalies, ambiguous/malformed Tamil wording, surviving source markers, or deliberately literal rhetoric.

Notes do not authorize rewriting the Tamil archival layer.

## 9. Review procedure for every English SRU

Before an English artifact can be marked reviewed/passed:

1. read the complete reviewed Tamil SRU;
2. draft the entire English artifact from that Tamil SRU only;
3. compare the complete English artifact back to the complete Tamil SRU;
4. confirm every dramatic paragraph, speaker turn, stage direction, narrative transition and repetition is represented;
5. verify SRU start/end anchors and source order;
6. confirm political/social rhetoric, humour, colloquial speech and cadence have not been flattened or softened;
7. confirm every source-loss/unresolved marker appears in the corresponding English location when applicable;
8. confirm no text from a later/earlier SRU has been duplicated or omitted;
9. document materially source-sensitive choices;
10. only then set `translation_review: "passed"`.

A completed batch must receive its own durable `BATCH_0N_REVIEW.md` record before it is called locked.

## 10. Translation batching and progress

### Batch 1 — **PASS / LOCKED**

- `sru-01-yama-court.md` — translated/reviewed; `[paper loss]` **7 / 7 retained**;
- `sru-02-guesthouse.md` — translated/reviewed.

Durable review: `translations/en/BATCH_01_REVIEW.md`.

### Batch 2 — **PASS / LOCKED**

- `sru-03-eman-interview.md` — translated/reviewed.

Durable review: `translations/en/BATCH_02_REVIEW.md`.

Controls include the repeated `pillai` sequence, `uyarthinai / ahrinai`, `pancha-varnam / pancham`, tax/Congress/election/Five-Year-Plan satire, source-label variation and the exact SRU boundary.

### Batch 3 — **PASS / LOCKED**

- `sru-04-gandhi-journey.md` — translated/reviewed.

Durable review: `translations/en/BATCH_03_REVIEW.md`.

Controls passed:

- `[unresolved glyph cluster]`: **1 / 1 retained**;
- `[unresolved descriptive cluster]`: **2 / 2 retained**;
- apparent `கொழுப்பேறி`: **not promoted / not resolved**;
- Nandan / Gandhi / `சொர்க்கச் சிறை` structure: **PASS**;
- source `போப்பந்தர்`: retained as *Poppanthar*;
- `Harijan Welfare` retained as historical source terminology;
- source-sensitive *kottaan*, `எங்குவேன்`, `நாகத்திலும்`, and `மகானத்துக்கு ஓர் “ஆயாக் கிழவி”` handled conservatively and documented;
- secondary-English witness use: **0**;
- blocking issues: **0**.

### Batch 4 — **NEXT**

- `sru-05-stairfall-dream-exit.md`
- `sru-06-domestic-election-argument.md`
- `sru-07-udayasuriyan-kolam-close.md`

Special controls:

- preserve stair/place-name wordplay in SRU-05;
- preserve domestic colloquial/election/political register in SRU-06;
- preserve scan-47 `உதயசூரியன் கோலம்` as an internal intertitle in SRU-07;
- preserve source close without an invented `The End`.

Expected completed batches: **4**; completed: **3 / 4**.

## 11. Final English review gate

After all seven English artifacts have individually passed review:

1. create `translations/en/TRANSLATION_REVIEW.md`;
2. verify **7 / 7** English artifacts present and reviewed;
3. verify all four batch review records are PASS / LOCKED;
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

This first source-faithful English phase uses **no secondary English witness**. Any later comparison with a published/other English translation is a separately authorized phase after independent English closure.

## 13. Current phase state

Current English status:

- expected artifacts: **7**;
- present: **4 / 7**;
- reviewed: **4 / 7**;
- completed batches: **3 / 4**;
- Batch 01: **PASS / LOCKED**;
- Batch 02: **PASS / LOCKED**;
- Batch 03: **PASS / LOCKED**;
- secondary-English witness use: **0**;
- Tamil archival layer modified by translation: **no**.

## Exact next activity

Begin **English Translation Batch 04** from the three reviewed Tamil SRUs only:

- `scenes/sru-05-stairfall-dream-exit.md` → `translations/en/sru-05-stairfall-dream-exit.md`
- `scenes/sru-06-domestic-election-argument.md` → `translations/en/sru-06-domestic-election-argument.md`
- `scenes/sru-07-udayasuriyan-kolam-close.md` → `translations/en/sru-07-udayasuriyan-kolam-close.md`

Perform complete Tamil→English fidelity review for all three and create `translations/en/BATCH_04_REVIEW.md` before marking Batch 04 PASS / LOCKED. Do not create final `TRANSLATION_REVIEW.md` until Batch 04 is durably closed.