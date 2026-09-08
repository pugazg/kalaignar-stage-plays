# ஒரே முத்தம் — English translation plan

Status: **ACTIVE — BATCHES 4–5 PASS / LOCKED; 25 / 33 ENGLISH SCENES REVIEWED**

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

Locked through Batch 5 unless a later review documents a justified global refinement:

- `புத்தன்` → `Puthan`;
- `மகாவீரர்` → `Mahaveerar`;
- `யாளித்தத்தர்` → `Yaaliththathar`;
- `குமரி` → `Kumari`;
- `ரமேலா` → `Ramela`;
- `விபீஷணன்` → `Vibhishanan`;
- `இமயா` → `Imaya`;
- `பொன்னி` → `Ponni`;
- `மலையன்` → `Malayan`;
- `சித்ரா` → `Chithra`;
- `மாதவன்` → `Madhavan`;
- `சிங்கநாகன்` → `Singanagan`;
- `எல்லப்பன்` → `Ellappan`;
- `இன்பபுரி` → `Inbapuri`;
- `முல்லைக்காடு` → `Mullaikadu`;
- `பூந்தோட்டம்` → `Poonthottam`;
- `பவளமலை` → `Pavalamalai`;
- `மின்னல்` → `Lightning` when used as Kumari's undercover alias;
- recurring `மது, மங்கை` → `wine and women` in matching contexts;
- `தாலி` → *thali* where the marriage pendant itself is meant;
- `காலக்ஷேபம்` → *kalakshepam* where the religious storytelling performance form is meant;
- `தாண்டவம்` → *tandava* where the source-specific dance image itself matters;
- `சண்டாளன்` → `chandala` where the historically specific insult itself matters;
- `மச்சான்` → *machan* when the exact kinship sense should remain non-narrowed;
- `பராக்` → `paraak` where the court/herald announcement form itself matters;
- source `மகாராணி` → `Maharani` where used as a title;
- `அத்தான்` → `Aththaan` where the marked kinship/affection address itself matters;
- `நாழிகை` → `naazhigai` rather than silently converting the source time-unit;
- `பறையர்` → `Paraiyar` where the source explicitly names the caste community;
- `ஜே! ஜே!` → `Jai! Jai!`.

Reviewed mythic-name forms include Ahalya, Nalayini, Savitri, Kumbakarna, Duryodhana, Draupadi, Shakuntala, Dushyanta and Harishchandra. `ஆலகாலம்` is carried as `Alakala poison` in the poison/nectar contrast.

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

## 7. Review-batch plan

The durable review unit remains the existing five-scene batch:

1. **Batch 1:** main Scenes **1–5** — **PASS / LOCKED**;
2. **Batch 2:** main Scenes **6–10** — **PASS / LOCKED — SOURCE HOLDS PRESERVED**;
3. **Batch 3:** main Scenes **11–15** — **PASS / LOCKED — SOURCE HOLDS PRESERVED**;
4. **Batch 4:** main Scenes **16–20** — **PASS / LOCKED — SOURCE HOLDS PRESERVED**;
5. **Batch 5:** main Scenes **21–25** — **PASS / LOCKED — SOURCE HOLDS PRESERVED**;
6. **Batch 6:** main Scenes **26–30** — **NEXT**;
7. **Batch 7:** supplementary `நகைச் சுவைப் பகுதி.` Scenes **1–3** — **FINAL REMAINDER**.

After each batch, `translations/en/BATCH_0N_REVIEW.md` checks complete Tamil-turn coverage, stage-direction coverage, naming consistency, source-hold transparency and absence of secondary-English contamination.

After all seven batches, run `translations/en/TRANSLATION_REVIEW.md` as the final 33-scene Tamil→English fidelity gate.

## 8. User-directed iteration policy

The user has directed: **process 10 scenes in each iteration**.

To preserve the already-established five-scene review artifacts, one normal iteration now executes **two consecutive review batches / 10 scenes** where ten scenes are available.

The current iteration completed:

- Batch 4 — main **16–20**;
- Batch 5 — main **21–25**;
- total: **10 scenes**.

Only **8 English scenes remain**, so the next iteration is the final remainder iteration and should process **all eight** in one go rather than inventing nonexistent scenes:

- Batch 6 — main **26–30** — 5 scenes;
- Batch 7 — supplementary **1–3** — 3 scenes;
- then final `TRANSLATION_REVIEW.md` if both reviews pass.

## 9. Current checkpoint

Completed / reviewed English scene artifacts: **25 / 33**.

- completed batches: **5 / 7**;
- source-hold-bearing English scenes completed: **15 / 18** — main `6–8, 11–14, 16–20, 23–25`;
- Tamil terminal holds resolved by English translation: **0**;
- secondary-English contamination: **0**;
- unresolved blocking English issues: **0**.

Current batch-review authorities:

- `translations/en/BATCH_01_REVIEW.md`;
- `translations/en/BATCH_02_REVIEW.md`;
- `translations/en/BATCH_03_REVIEW.md`;
- `translations/en/BATCH_04_REVIEW.md`;
- `translations/en/BATCH_05_REVIEW.md`.

Exact next activity: process the **final 8-scene remainder** from the closed Tamil scene layer only:

- main Scenes **26–30**;
- supplementary `நகைச் சுவைப் பகுதி.` Scenes **1–3**;
- run `BATCH_06_REVIEW.md` and `BATCH_07_REVIEW.md`;
- if both pass, run final `TRANSLATION_REVIEW.md` and synchronize closure documents.

Do not alter Tamil source artifacts.