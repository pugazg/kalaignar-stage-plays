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
- `அனார்கலி`: independent English translation **4/4 scenes COMPLETE; translation review PASS**.
- `சாக்ரடீஸ்`: independent English translation **pending**.
- `சேரன் செங்குட்டுவன்`: independent English translation **pending**.

### Anarkali independent English — durable checkpoint

Files:

- `works/anarkali/translations/en/01.md` — Scene 1 — translation-reviewed;
- `works/anarkali/translations/en/02.md` — Scene 2 — translation-reviewed;
- `works/anarkali/translations/en/03.md` — Scene 3 — translation-reviewed;
- `works/anarkali/translations/en/04.md` — Scene 4 — translation-reviewed;
- `works/anarkali/translations/en/TRANSLATION_REVIEW.md` — **PASS**;
- `works/anarkali/translations/en/README.md` — authority/status record.

Translation authority was the verified Tamil scene assemblies `works/anarkali/scenes/01.md`–`04.md`, backed by verified page records `0018.md`–`0026.md`. The Gemini first pass was not a translation source.

The complete 2009 published-English `Anarkali` witness under `sources/one-act-plays-2009/anarkali/` was **not consulted for wording during drafting or Tamil-to-English translation review**. It remains a secondary witness for the next phase.

Protected Anarkali translation controls include:

- verified `என் திழையே!` retained conservatively as `my thizhaiye!`, not silently normalized;
- verified unusual `என்னுள் உன் குடிசை பெருமையுற்றது` translated without repairing the Tamil;
- uncertain `சப்ரகூட மஞ்சம்` retained as the *sabrakooda* couch rather than guessed;
- `காதல் சுதந்திரம்` → `freedom of love`;
- `டில்லி ஏகாதிபத்தியம்` → `Delhi imperialism`;
- `ஜரிகைப்பூ` → `zari-flower`;
- `(திரையில் குரல்)` preserved as dramatic `Voice behind the curtain`;
- `மாசற்ற ஜோதி மழையே!`, `நீதியில்லாத பூமியில்`, the royal-privilege catalogue, suicide-attempt directions and final source `*` marks remain represented.

## Exact next activity

Run a **post-translation secondary-witness comparison for `அனார்கலி` only**.

Requirements:

1. fetch live `main` first;
2. read `STAGE_PLAY_PROCESSING_GUIDE.md`, this `HANDOVER.md`, `NEXT_CHAT_PROMPT.md`, `works/anarkali/README.md`, the four verified Tamil scenes, the four independent English translation files, and `works/anarkali/translations/en/TRANSLATION_REVIEW.md`;
3. only after the independent translation checkpoint is confirmed, read the complete 2009 published-English `Anarkali` witness under `sources/one-act-plays-2009/anarkali/`;
4. compare source coverage, scene structure, speaker turns, stage directions, omissions/additions, terminology and interpretive choices;
5. create a durable secondary-witness comparison record under `works/anarkali/` or `works/anarkali/translations/en/` according to existing repository convention;
6. do **not** automatically rewrite the verified Tamil archive or the independent English translation merely because the published witness differs;
7. record any genuinely useful alternative rendering as comparison evidence only unless the user separately authorizes a translation revision;
8. do **not** begin `சாக்ரடீஸ்` English translation in the same activity.

## Permanent safeguards

- live `main` controls repository state;
- Tamil source PDF remains external;
- no silent lexical normalization or semantic reconstruction;
- ambiguous old-glyph readings are not overridden by expectation;
- translation derives from verified Tamil;
- published English is a secondary witness, never a backdoor authority over Tamil;
- comparison and revision are separate decisions;
- `அந்தணர்` is not automatically “Brahmin” in future translation work.