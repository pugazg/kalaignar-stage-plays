# Kalaignar Stage Plays — Handover

Repository: `pugazg/kalaignar-stage-plays`, branch `main`.

## Startup rule

Always fetch live `main` first and treat it as authoritative. Preserve newer durable state and never reopen completed work unless the user explicitly requests it.

Permanent workflow: `STAGE_PLAY_PROCESSING_GUIDE.md`.

Controlling composite Tamil source: `TVA_BOK_0065576_நான்மணி_மாலை.pdf` — **54 scans** — SHA-256 `18d2b1405544b03507e9f92067d287cb28f5a92eaf02bed7054e6e78e5e38c89`.

## Locked Tamil archival state

- `பரதாயணம்`: Tamil archive/assembly PASS.
- `அனார்கலி`: **9/9 Tamil pages verified; 4/4 scenes assembled; fidelity PASS**.
- `சாக்ரடீஸ்`: **17/17 pages verified; 5/5 scenes assembled; all fidelity gates PASS**.
- `சேரன் செங்குட்டுவன்`: **10/10 Tamil pages verified; 4/4 scenes assembled; all fidelity gates PASS**.
- Silappathikaram completed state remains locked and unchanged.

Composite-source coverage audit: `sources/naanmani-malai-tamil/COVERAGE_AUDIT.md` — **PASS / COMPLETE**.

Physical scan partition remains **1–5 / 6–17 / 18–26 / 27–43 / 44–53 / 54 = 54**, with **0 gaps, 0 overlaps and 0 pending composite-source pages**.

## English translation state — நான்மணி மாலை plays

Independent English translation is now **4/4 COMPLETE**:

- `பரதாயணம்`: independent English **PASS / COMPLETE**.
- `அனார்கலி`: independent English **4/4 COMPLETE; translation review PASS; 2009 secondary-witness comparison PASS / COMPLETE**.
- `சாக்ரடீஸ்`: independent English **introductory note + 5/5 COMPLETE; translation review PASS; 2009 secondary-witness comparison PASS / COMPLETE**.
- `சேரன் செங்குட்டுவன்`: independent English **4/4 COMPLETE; translation review PASS; 2009 secondary-witness comparison PASS / COMPLETE**.

## Cheran English — durable closed checkpoint

Independent files:

- `works/cheran-senguttuvan/translations/en/01.md`–`04.md` — translation-reviewed;
- `works/cheran-senguttuvan/translations/en/TRANSLATION_REVIEW.md` — **PASS**;
- `works/cheran-senguttuvan/translations/en/README.md` — authority/status record.

Post-translation witness comparison:

- `works/cheran-senguttuvan/translations/en/SECONDARY_WITNESS_COMPARISON.md` — **PASS / COMPLETE**;
- secondary witness: M. D. Jayabalan 2009 published English, provenance `sources/one-act-plays-2009/pages/0141.md`–`0149.md`;
- witness opened only after the independent translation was locked;
- verified Tamil changed by comparison: **0**;
- independent English changed by comparison: **0**;
- automatic published-witness wording imported: **0**.

Important Cheran comparison findings to preserve:

- Scene 1 `பாரதந்தான்` → published `another Mahabharatham`, `மண்` → published `sand`, and source label distinctions normalized;
- Scene 2 `சாதல் கதையொன்று` → published `love story`;
- Scene 2 `வேழப்படை முறிபட்டது` → published `Foes with Tiger flags defeated`;
- source-sensitive poetic forms such as `கட்டாணி முத்தாள்`, `ஆரணங்கு`, `பனவெல்ல` are confidently normalized/interpreted in the published witness;
- Scene 3 `வாளேந்தி` → published `holding lances`;
- Scene 3 Sattanar / Athani-hall line is materially rewritten;
- Scene 3 `இமயத்தை முட்டுங்கள்!` → published `Invade the Himalayas!`;
- Scene 4 exact source label variants are normalized to ordinary names;
- Scene 4 `பதினெட்டே நாழிகை` → published `eighteen 'nali' [1 nali equals 24 minutes]`;
- Scene 4 final `இப்போது தூக்கு கல்!` gains published `on your heads`;
- source closing `*` / `- * -` marks are omitted in the published-witness transcription.

These are evidence only and do not authorize revision.

## Prior closed English-comparison checkpoints

- `அனார்கலி` — independent English + 2009 witness comparison **PASS / COMPLETE**.
- `சாக்ரடீஸ்` — independent English + 2009 witness comparison **PASS / COMPLETE**.
- `சேரன் செங்குட்டுவன்` — independent English + 2009 witness comparison **PASS / COMPLETE**.

`பரதாயணம்` independent English is **PASS / COMPLETE**. Its applicability to the 2009 witness collection must be resolved from the repository during the volume-level closure audit rather than assumed.

## Exact next activity

Run a **`நான்மணி மாலை` English-phase closure audit only**.

Requirements:

1. fetch live `main` first;
2. read `STAGE_PLAY_PROCESSING_GUIDE.md`, this `HANDOVER.md`, `NEXT_CHAT_PROMPT.md`, root `README.md`, `sources/naanmani-malai-tamil/COVERAGE_AUDIT.md`, and the English authority/status + review files for all four plays;
3. verify independently from repository state that all four independent English translation gates are complete;
4. inspect `sources/one-act-plays-2009/` to establish exactly which `நான்மணி மாலை` plays have an applicable complete 2009 published-English witness; do not assume `பரதாயணம்` applicability from memory;
5. verify every applicable post-translation comparison gate is complete and linked to its provenance range;
6. create a durable volume-level English closure record, preferably `sources/naanmani-malai-tamil/ENGLISH_PHASE_CLOSURE_AUDIT.md`, if no existing convention supersedes it;
7. record counts as **independent translations complete / total plays** and **secondary-witness comparisons complete / applicable witness plays**, keeping `not applicable` distinct from `pending`;
8. do not reopen or revise verified Tamil, reviewed independent English, or completed comparison files merely to harmonize wording;
9. do not begin a new work or new translation phase in the same activity.

Expected closure question to answer from live repository evidence: whether the four-play volume can be marked **English phase PASS / COMPLETE**, with any 2009-witness non-applicability explicitly documented.

## Permanent safeguards

- live `main` controls repository state;
- Tamil source PDF remains external;
- no silent lexical normalization or semantic reconstruction;
- ambiguous old-glyph readings are not overridden by expectation;
- translation derives from verified Tamil;
- published English is a secondary witness, never a backdoor authority over Tamil;
- comparison and revision are separate decisions;
- `அந்தணர்` is not automatically “Brahmin” in future translation work.