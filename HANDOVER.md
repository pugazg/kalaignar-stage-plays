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

Independent English translation is now **4/4 COMPLETE**:

- `பரதாயணம்`: independent English translation **PASS / COMPLETE**.
- `அனார்கலி`: independent English **4/4 COMPLETE; translation review PASS; 2009 secondary-witness comparison PASS / COMPLETE**.
- `சாக்ரடீஸ்`: independent English **introductory note + 5/5 COMPLETE; translation review PASS; 2009 secondary-witness comparison PASS / COMPLETE**.
- `சேரன் செங்குட்டுவன்`: independent English **4/4 COMPLETE; translation review PASS**.

## Cheran independent English — durable checkpoint

Work: `works/cheran-senguttuvan/`.

Tamil authority:

- Scene 1 — scans **44–45** / pp.39–40 — `scenes/01.md` — fidelity PASS;
- Scene 2 — scans **46–49** / pp.41–44 — `scenes/02.md` — fidelity PASS;
- Scene 3 — scans **50–51** / pp.45–46 — `scenes/03.md` — fidelity PASS;
- Scene 4 — scans **52–53** / pp.47–48 — `scenes/04.md` — fidelity PASS.

Independent English files:

- `works/cheran-senguttuvan/translations/en/01.md` — Scene 1 — translation-reviewed;
- `works/cheran-senguttuvan/translations/en/02.md` — Scene 2 — translation-reviewed;
- `works/cheran-senguttuvan/translations/en/03.md` — Scene 3 — translation-reviewed;
- `works/cheran-senguttuvan/translations/en/04.md` — Scene 4 — translation-reviewed;
- `works/cheran-senguttuvan/translations/en/TRANSLATION_REVIEW.md` — **PASS**;
- `works/cheran-senguttuvan/translations/en/README.md` — authority/status record.

Translation authority was the verified Tamil scene assemblies only, with verified Tamil page/assembly records used for source-sensitive checks. The complete 2009 published-English `Cheran Senguttuvan` witness was **not consulted for wording** during independent drafting or Tamil→English review.

Protected Cheran translation controls include:

- Scene 1 pre-scene voice-over retained; `விஜ.` / `விஜ:` remain distinct; `புலி—வில்—கயல்` → `tiger—bow—fish`;
- Scene 2 `சேரன்:` / `சேர:` and `புலவர்:` / `புல:` remain distinct; the long embedded recitation remains present; uncertain poetic forms `கட்டாணி முத்தாள்`, `ஆரணங்கு`, and `பனவெல்ல` are represented conservatively rather than silently normalized;
- Scene 3 `மண்டூக மன்னர்கள்` → `frog-kings`; Tamil identity / self-respect / northern-challenge rhetoric remains explicit; source-spaced `வேட்ட மங்கலம்` remains two words; final `*` retained;
- Scene 4 `குயிலாலுவம்` → conservative `Kuyilaluvam`; exact label/punctuation variants `சேர்:`, `சேர்;`, `சேர்!`, `வில்லவன்:`, `வில்:`, `வில்!`, `கன:` are preserved as distinct English labels; `நாழிகை` remains `nazhigai`; final `- * -` retained exactly.

Independent-English result for `சேரன் செங்குட்டுவன்`:

- 4/4 scene coverage: **PASS**;
- pre-scene voice-over coverage: **PASS**;
- embedded verse / historical-political rhetoric: **PASS**;
- speaker-label distinction protection: **PASS**;
- source-anomaly handling: **PASS**;
- unresolved translation blocks: **0**;
- published-English contamination: **0**.

## Prior closed English-comparison checkpoints

`அனார்கலி` and `சாக்ரடீஸ்` have completed post-translation 2009 witness comparisons. Those comparison files are separate evidence layers and did not rewrite verified Tamil or independent English.

For Socrates, preserve the documented major witness divergences including intro `பல தகுதிகளுக்கும்` → published `certain misdeeds`, `அறிவுலக ஜோதியாக` → published `an intellectual who enjoyed his life`, normalized protected forms, a published `281...221` variant, conversion of `நாழிகை` into minutes, and final `அங்கிளிப்பியசு` / `கோழிக் குஞ்சு` → `Asclepius / cock`.

## Exact next activity

Run a **post-translation secondary-witness comparison for `சேரன் செங்குட்டுவன்` only**.

Requirements:

1. fetch live `main` first;
2. read `STAGE_PLAY_PROCESSING_GUIDE.md`, this `HANDOVER.md`, `NEXT_CHAT_PROMPT.md`, root `README.md`, `works/cheran-senguttuvan/README.md`, all four verified Tamil scene assemblies, all four independent English files, `translations/en/README.md`, `translations/en/TRANSLATION_REVIEW.md`, and relevant scene/page fidelity reviews for source-sensitive forms;
3. confirm the independent translation checkpoint before opening the complete 2009 published-English `Cheran Senguttuvan` witness;
4. compare pre-scene framing, four-scene coverage/order, speaker turns and label normalization, stage directions, embedded poem/verse coverage, Tamil historical/political vocabulary, Chera/Chola/Pandya framing, northern challenge, honour/self-respect rhetoric, tiger/bow/fish emblems, source-sensitive poetic forms, scene-3 mobilization speech, Scene-4 label variants, `நாழிகை`, Kanaka-Vijaya humiliation, Kannagi-stone ending and closing marks;
5. create `works/cheran-senguttuvan/translations/en/SECONDARY_WITNESS_COMPARISON.md` according to existing repository convention;
6. do **not** automatically rewrite the verified Tamil or independent English merely because the published witness differs;
7. useful published alternatives remain comparison evidence only unless the user separately authorizes revision;
8. do **not** begin another work in the same activity.

## Permanent safeguards

- live `main` controls repository state;
- Tamil source PDF remains external;
- no silent lexical normalization or semantic reconstruction;
- ambiguous old-glyph readings are not overridden by expectation;
- translation derives from verified Tamil;
- published English is a secondary witness, never a backdoor authority over Tamil;
- comparison and revision are separate decisions;
- `அந்தணர்` is not automatically “Brahmin” in future translation work.