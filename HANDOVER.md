# Kalaignar Stage Plays — Handover

Repository: `pugazg/kalaignar-stage-plays`, branch `main`.

## Startup rule

Always fetch live `main` first and treat it as authoritative. Preserve newer durable state and never reopen completed work unless the user explicitly requests it.

Permanent workflow: `STAGE_PLAY_PROCESSING_GUIDE.md`.

Controlling composite Tamil source: `TVA_BOK_0065576_நான்மணி_மாலை.pdf` — **54 scans** — SHA-256 `18d2b1405544b03507e9f92067d287cb28f5a92eaf02bed7054e6e78e5e38c89`.

## Locked Tamil archival state

- `பரதாயணம்`: Tamil archive/assembly PASS.
- `அனார்கலி`: **9/9 Tamil pages verified; 4/4 scenes assembled; page-record ↔ scene fidelity PASS**.
- `சாக்ரடீஸ்`: **17/17 pages verified; 5/5 scenes assembled; all fidelity gates PASS**.
- `சேரன் செங்குட்டுவன்`: **10/10 Tamil pages verified; 4/4 scenes assembled; all fidelity gates PASS**.
- Silappathikaram completed state remains locked and unchanged.

Composite-source coverage audit: `sources/naanmani-malai-tamil/COVERAGE_AUDIT.md` — **PASS / COMPLETE**.

The exact scan partition remains **1–5 / 6–17 / 18–26 / 27–43 / 44–53 / 54 = 54 scans**, with **0 gaps, 0 overlaps and 0 pending composite-source pages**.

## English translation state — நான்மணி மாலை plays

- `பரதாயணம்`: independent English translation **PASS / COMPLETE**.
- `அனார்கலி`: independent English translation **4/4 scenes COMPLETE; translation review PASS; 2009 secondary-witness comparison PASS / COMPLETE**.
- `சாக்ரடீஸ்`: independent English **introductory note + 5/5 scenes COMPLETE; translation review PASS**.
- `சேரன் செங்குட்டுவன்`: independent English translation **pending**.

### Anarkali English — durable closed checkpoint

- `works/anarkali/translations/en/01.md`–`04.md` — independent translation, translation-reviewed;
- `works/anarkali/translations/en/TRANSLATION_REVIEW.md` — **PASS**;
- `works/anarkali/translations/en/SECONDARY_WITNESS_COMPARISON.md` — **PASS / COMPLETE**.

The 2009 published-English `Anarkali` witness was consulted only after independent drafting/review was locked. No published wording was automatically imported into the verified Tamil or independent translation.

### Socrates independent English — durable checkpoint

Files:

- `works/socrates/translations/en/00-introduction.md` — scans 27–28 introductory note — translation-reviewed;
- `works/socrates/translations/en/01.md` — Scene 1 — translation-reviewed;
- `works/socrates/translations/en/02.md` — Scene 2 — translation-reviewed;
- `works/socrates/translations/en/03.md` — Scene 3 — translation-reviewed;
- `works/socrates/translations/en/04.md` — Scene 4 — translation-reviewed;
- `works/socrates/translations/en/05.md` — Scene 5 — translation-reviewed;
- `works/socrates/translations/en/TRANSLATION_REVIEW.md` — **PASS**;
- `works/socrates/translations/en/README.md` — authority/status record.

Translation authority was the verified Tamil introductory-note records `pages/0027.md`–`0028.md` and verified scene assemblies `scenes/01.md`–`05.md`. The complete 2009 published-English `Socrates` witness was **not consulted for wording** during independent drafting or Tamil→English review.

Protected Socrates translation controls include:

- intro `‘சோக்ரதர்’` → conservative `‘Sogradhar’`;
- unusual `ஆஸ்திகப்பழமாக்கியிருக்கிறார்` represented visibly as `astika-pazham`, not silently repaired;
- `சபைன்` → `Sabain` without external identification;
- Scene 4 source label `சார் :` → `Sar :`, not regularized;
- Scene 4 locked `செடுக்கிறேனா` represented visibly as `sedukkirēn`;
- source `முப்பத்தொரு வாக்குகள்` → `thirty-one votes` despite the printed totals `281—220`; no arithmetic repair;
- Scene 5 bare `: !........` remains unassigned;
- source `சாச்ரடீஸ்` → `Sasrates` at its verified occurrence;
- `அங்கிளிப்பியசு` → `Angilipiyas`; no external famous-name substitution;
- `நாழிகை` remains `nazhigai` rather than being silently converted to a modern clock value.

Independent-English result for `சாக்ரடீஸ்`:

- intro coverage: **PASS**;
- 5/5 scene coverage: **PASS**;
- philosophical / political rhetoric: **PASS**;
- source-anomaly protection: **PASS**;
- unresolved translation blocks: **0**;
- published-English contamination: **0**.

## Exact next activity

Run a **post-translation secondary-witness comparison for `சாக்ரடீஸ்` only**.

Requirements:

1. fetch live `main` first;
2. read `STAGE_PLAY_PROCESSING_GUIDE.md`, this `HANDOVER.md`, `NEXT_CHAT_PROMPT.md`, `works/socrates/README.md`, the verified Tamil intro records / five scenes, and all independent English files plus `TRANSLATION_REVIEW.md`;
3. confirm the independent translation checkpoint before opening the complete 2009 published-English `Socrates` witness;
4. compare introductory framing, scene coverage/order, speaker turns, stage directions, philosophical terminology, political/court rhetoric, omissions/additions, normalization, source-sensitive lexical forms, death-vote sequence, prison farewell, rationalist maxims and final creditor line;
5. create a durable secondary-witness comparison record under `works/socrates/translations/en/`;
6. do **not** automatically rewrite the verified Tamil or independent English merely because the published witness differs;
7. useful published alternatives remain comparison evidence only unless the user separately authorizes revision;
8. do **not** begin `சேரன் செங்குட்டுவன்` English translation in the same activity.

## Permanent safeguards

- live `main` controls repository state;
- Tamil source PDF remains external;
- no silent lexical normalization or semantic reconstruction;
- ambiguous old-glyph readings are not overridden by expectation;
- translation derives from verified Tamil;
- published English is a secondary witness, never a backdoor authority over Tamil;
- comparison and revision are separate decisions;
- `அந்தணர்` is not automatically “Brahmin” in future translation work.