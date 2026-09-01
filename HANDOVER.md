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
- `சாக்ரடீஸ்`: independent English translation **pending**.
- `சேரன் செங்குட்டுவன்`: independent English translation **pending**.

### Anarkali English — durable closed checkpoint

Independent translation files:

- `works/anarkali/translations/en/01.md` — Scene 1 — translation-reviewed;
- `works/anarkali/translations/en/02.md` — Scene 2 — translation-reviewed;
- `works/anarkali/translations/en/03.md` — Scene 3 — translation-reviewed;
- `works/anarkali/translations/en/04.md` — Scene 4 — translation-reviewed;
- `works/anarkali/translations/en/TRANSLATION_REVIEW.md` — **PASS**;
- `works/anarkali/translations/en/README.md` — authority/status record.

Post-translation secondary-witness comparison:

- `works/anarkali/translations/en/SECONDARY_WITNESS_COMPARISON.md` — **PASS / COMPLETE**;
- secondary witness: `sources/one-act-plays-2009/pages/0135.md`–`0140.md` / M. D. Jayabalan 2009 published English;
- witness consulted only after independent drafting/review was locked;
- verified Tamil changed by comparison: **0**;
- independent English scene files changed by comparison: **0**;
- automatic published-witness revisions imported: **0**.

Comparison findings to preserve:

- the 2009 witness contains all four scenes and the complete core plot;
- it is generally freer/smoother than the independent archival translation;
- it normalizes or interprets source-sensitive forms such as `என் திழையே!`, `என்னுள் உன் குடிசை பெருமையுற்றது`, and `சப்ரகூட மஞ்சம்`;
- additions absent from verified Tamil include examples such as `geisha girl` and `disco`;
- Scene 4 has material divergences including verified `அவள் அழுகை மறைத்தீர்கள்!` rendered as hidden `eternal beauty`, `நீதியில்லாத பூமியில்` rendered as `world without you`, and altered royal-status causality;
- some rhetorical repetition, inventory details and source `*` marks are compressed/omitted in the published witness;
- useful published alternatives are comparison evidence only and do not control revision.

## Exact next activity

Begin the **independent English translation of `சாக்ரடீஸ்`**.

Requirements:

1. fetch live `main` first;
2. read `STAGE_PLAY_PROCESSING_GUIDE.md`, this `HANDOVER.md`, `NEXT_CHAT_PROMPT.md`, root `README.md`, `works/socrates/README.md`, `works/socrates/INTRO_RECONCILIATION.md`, verified Tamil introductory-note records for scans **27–28**, and all five verified Tamil scene assemblies;
3. derive the English only from the verified Tamil archive; use page records for source-form/boundary questions;
4. do **not** consult the complete 2009 published-English `Socrates` witness for wording before independent translation + Tamil→English fidelity review are complete;
5. translate the introductory note as part of the work, then Scenes 1–5;
6. preserve dramatic structure, speaker distinctions, repetitions, stage directions, source-sensitive philosophical/political terminology and documented user-retained lexical forms;
7. create a translation authority/status README and a complete Tamil→English fidelity review;
8. only after independent translation review PASS may a separate 2009 secondary-witness comparison begin;
9. do **not** begin `சேரன் செங்குட்டுவன்` English translation in the same activity.

## Permanent safeguards

- live `main` controls repository state;
- Tamil source PDF remains external;
- no silent lexical normalization or semantic reconstruction;
- ambiguous old-glyph readings are not overridden by expectation;
- translation derives from verified Tamil;
- published English is a secondary witness, never a backdoor authority over Tamil;
- comparison and revision are separate decisions;
- `அந்தணர்` is not automatically “Brahmin” in future translation work.