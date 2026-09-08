# ஒரே முத்தம் — English translation plan

Status: **ACTIVE — ENGLISH TRANSLATION AUTHORIZED; BATCH 1 IN PROGRESS**

The Tamil archival layer is closed for current source evidence. English translation is a separate derivative layer and must not reopen, normalize or overwrite that Tamil closure.

## 1. Translation authority

Immediate drafting authority is the closed Tamil scene layer under `scenes/`:

- main play: `scenes/main-01.md` through `scenes/main-30.md`;
- supplementary `நகைச் சுவைப் பகுதி.`: `scenes/nagai-suvai-01.md` through `scenes/nagai-suvai-03.md`.

The Tamil scene layer is **33 / 33 assembled**, with `SCENE_ASSEMBLY_AUDIT.md` **PASS — 33 / 33** and `TAMIL_CLOSURE_REVIEW.md` **PASS**.

English is **not** to be drafted from OCR, a web transcription, plot memory, a modern/later edition, another English translation or the controlling PDF as a substitute for the closed Tamil scene layer.

Translation choices do not authorize changes to the Tamil page or scene files.

## 2. Artifact mapping

The English layer mirrors the Tamil scene namespace exactly:

- `translations/en/main-01.md` through `translations/en/main-30.md`;
- `translations/en/nagai-suvai-01.md` through `translations/en/nagai-suvai-03.md`.

Expected English scene artifacts: **33**.

The supplementary scenes remain independently numbered **1–3**. They must never be presented as main scenes 31–33.

## 3. Translation goals

Preserve, as supported by each closed Tamil scene artifact:

- scene order and location headings;
- speaker identity and dramatic turn order;
- stage directions, entrances, exits and crowd cries;
- repetitions, rhetorical escalation and political cadence;
- class/caste/social-justice argumentation without neutralizing it;
- satire, jokes, sarcasm and colloquial register;
- proper names and source-specific place names consistently;
- source uncertainty rather than silently repairing it.

The English should be readable dramatic English, but it is a source-faithful archival translation, not a modernization or adaptation.

## 4. Stable naming / terminology baseline

Initial romanization / translation choices:

- `புத்தன்` → `Puthan`;
- `மகாவீரர்` → `Mahaveerar`;
- `யாளித்தத்தர்` → `Yaaliththathar`;
- `குமரி` → `Kumari`;
- `ரமேலா` → `Ramela`;
- `விபீஷணன்` → `Vibhishanan`;
- `இமயா` → `Imaya`;
- `இன்பபுரி` → `Inbapuri`;
- `முல்லைக்காடு` → `Mullaikadu`;
- `பூந்தோட்டம்` → `Poonthottam`;
- `தாலி` → *thali* where the marriage pendant itself is meant;
- `காலக்ஷேபம்` → *kalakshepam* where the religious storytelling performance form is meant.

These choices may be refined only through explicit translation review; refinements must remain consistent across already reviewed English artifacts.

## 5. Terminal-source-hold rule

The Tamil closure contains **28 terminal current-source-condition blocked pages**. Eighteen scene artifacts are hold-bearing.

Permanent English rule:

1. translate only source-secure Tamil wording;
2. never infer the exact wording of a Tamil `[source-held: ...]` or equivalent held locus;
3. in the English dramatic body, retain a visibly marked `Source-held` bracket at that locus;
4. translate only the secure descriptive information already present in the canonical Tamil scene marker, and keep the uncertainty explicit;
5. list the same scene-relevant held scans in English front matter / translation notes;
6. a successful English review does **not** convert a Tamil terminal hold into resolved source text.

Source-secure shared-boundary scenes (main 28; supplementary 2) remain source-secure in English because their globally blocked transition-page locus belongs to the following scene segment.

## 6. Review front matter

For a source-secure reviewed translation:

```yaml
status: "translation-reviewed"
translation_review: "passed"
secondary_english_witness_used: false
source_condition_scans: []
```

For a reviewed translation containing terminal Tamil source holds:

```yaml
status: "translation-reviewed-with-source-holds"
translation_review: "passed-with-source-holds"
secondary_english_witness_used: false
source_condition_scans: [<same scene-relevant terminal scans>]
```

`passed-with-source-holds` means Tamil→English fidelity passed for all secure wording and the unresolved loci remained explicitly unresolved. It does not mean the Tamil source hold was solved.

## 7. Batch plan

Use scene-order batches:

1. **Batch 1:** main Scenes **1–5**;
2. **Batch 2:** main Scenes **6–10**;
3. **Batch 3:** main Scenes **11–15**;
4. **Batch 4:** main Scenes **16–20**;
5. **Batch 5:** main Scenes **21–25**;
6. **Batch 6:** main Scenes **26–30**;
7. **Batch 7:** supplementary `நகைச் சுவைப் பகுதி.` Scenes **1–3**.

After each batch, create `translations/en/BATCH_0N_REVIEW.md`, check complete Tamil-turn coverage, stage-direction coverage, naming consistency, source-hold transparency and absence of secondary-English contamination, then lock that batch if it passes.

After all seven batches, run `translations/en/TRANSLATION_REVIEW.md` as the final 33-scene Tamil→English fidelity gate.

## 8. Current checkpoint

English authorization is now explicit.

Exact current activity: translate and review **Batch 1 — main Scenes 1–5** from the closed Tamil scene files only. Do not alter Tamil source artifacts.