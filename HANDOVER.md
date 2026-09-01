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
- `அனார்கலி`: independent English **4/4 COMPLETE; translation review PASS; 2009 secondary-witness comparison PASS / COMPLETE**.
- `சாக்ரடீஸ்`: independent English **introductory note + 5/5 COMPLETE; translation review PASS; 2009 secondary-witness comparison PASS / COMPLETE**.
- `சேரன் செங்குட்டுவன்`: independent English translation **pending**.

### Socrates English — durable closed checkpoint

Independent translation files:

- `works/socrates/translations/en/00-introduction.md`;
- `works/socrates/translations/en/01.md`–`05.md`;
- `works/socrates/translations/en/TRANSLATION_REVIEW.md` — **PASS**;
- `works/socrates/translations/en/SECONDARY_WITNESS_COMPARISON.md` — **PASS / COMPLETE**.

The 2009 published-English `Socrates` witness under `sources/one-act-plays-2009/socrates/` and provenance records `pages/0150.md`–`0160.md` was consulted only after the independent translation had been locked.

No verified Tamil or independent English scene wording was changed by the comparison.

Important Socrates witness-comparison findings to preserve:

- intro `பல தகுதிகளுக்கும்` → published `certain misdeeds`;
- source `அறிவுலக ஜோதியாக` → published `an intellectual who enjoyed his life`;
- published normalization of protected source forms including `சார் :`, `செடுக்கிறேனா`, and `சாச்ரடீஸ்`;
- published `281...221` at one Socrates line despite the witness's own 281/220 vote count, while `31 votes` is also retained;
- `கால் நாழிகை` / `இரண்டு நாழிகை` converted to minutes in the 2009 witness;
- final source `அங்கிளிப்பியசு` / neighbouring-house `கோழிக் குஞ்சு` replaced by the familiar `Asclepius / cock` formulation;
- several source stage directions / `*` marks compressed or omitted.

These are comparison evidence only, not revision authority.

## Cheran Tamil checkpoint for translation

Work: `works/cheran-senguttuvan/`.

- source scans: **44–53** / printed pp. **39–48**;
- verified Tamil pages: **10/10**;
- source-printed scenes: **4**;
- assembled scenes: **4/4**;
- all page-record ↔ scene fidelity gates: **PASS**.

Scene ranges:

1. Scene 1 — scans **44–45** / pp.39–40;
2. Scene 2 — scans **46–49** / pp.41–44;
3. Scene 3 — scans **50–51** / pp.45–46;
4. Scene 4 — scans **52–53** / pp.47–48.

Final Scene-4 locked controls include source `காட்சி—4.`, `குயிலாலுவம்`, exact label variants `சேர்:`, `சேர்;`, unusual `சேர்!`, `வில்லவன்:`, `வில்:`, `வில்!`, `கன:`, source long dashes, `ராம ராவணப் போர்?....`, `புறப்படுவோம்—வில்லவா.`, `கனக—விஜயா`, `சொல்—இப்போது`, and centered final `- * -`.

## Exact next activity

Run the **independent English translation phase for `சேரன் செங்குட்டுவன்` only**.

Requirements:

1. fetch live `main` first;
2. read `STAGE_PLAY_PROCESSING_GUIDE.md`, this `HANDOVER.md`, `NEXT_CHAT_PROMPT.md`, root `README.md`, `works/cheran-senguttuvan/README.md`, all four verified Tamil scene assemblies, and relevant scene/page fidelity reviews where a source-sensitive form needs confirmation;
3. derive English only from the verified Tamil archive;
4. create `works/cheran-senguttuvan/translations/en/` with a clear authority/status README, Scene 1–4 translation files, and a complete `TRANSLATION_REVIEW.md`;
5. preserve scene structure, speaker-label distinctions, stage directions, repetitions, Tamil historical/political rhetoric, source-sensitive lexical forms, source dashes, and closing marks where textually meaningful;
6. preserve the final-scene label distinctions rather than normalizing all of them into one English speaker label without documentation;
7. do **not** consult or borrow wording from the complete 2009 published-English `Cheran Senguttuvan` witness during drafting or Tamil→English review;
8. only after the independent translation review is PASS may that witness be opened for a separate comparison;
9. do **not** start another work or reopen completed `பரதாயணம்`, `அனார்கலி`, or `சாக்ரடீஸ்` English work in the same activity.

## Permanent safeguards

- live `main` controls repository state;
- Tamil source PDF remains external;
- no silent lexical normalization or semantic reconstruction;
- ambiguous old-glyph readings are not overridden by expectation;
- translation derives from verified Tamil;
- published English is a secondary witness, never a backdoor authority over Tamil;
- comparison and revision are separate decisions;
- `அந்தணர்` is not automatically “Brahmin” in future translation work.