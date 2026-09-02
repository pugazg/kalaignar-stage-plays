# Kalaignar Stage Plays — Handover

Repository: `pugazg/kalaignar-stage-plays`, branch `main`.

## Startup rule

Always fetch live `main` first and treat it as authoritative. Preserve newer durable state. Do not reset, overwrite, repeat, or reopen completed source work unless the user explicitly requests it or new source evidence requires reconciliation.

Permanent workflow: `STAGE_PLAY_PROCESSING_GUIDE.md`.

## மணிமகுடம் — durable source state

Controlling source: `TVA_BOK_0064143_மணி_மகுடம்.pdf`.

- SHA-256: `a629509c3404fcc5c2844f5b693e72a41aca03ad2e2494588807af4ff8f16f3b`;
- file size: **187,091,728 bytes**;
- physical PDF scans: **170**;
- sixth edition scan statement: **May 2010**, price **Rs.40.00**.

### Tamil page-level checkpoint — COMPLETE

- front matter scans **1–13**: **13 / 13 VERIFIED**;
- dramatic-body scans **14–169**: **156 / 156 VERIFIED**;
- back matter scan **170**: **1 / 1 VERIFIED**;
- overall physical-page archive: **170 / 170 COMPLETE**;
- durable page records: `works/manimagudam/pages/0001.md` through `0170.md`;
- `காட்சி 1` through `காட்சி 47`: page-level source transcription complete;
- scan **169 / printed page 160** closes the drama with `(முடிவுற்றது)`;
- scan **170** is verified publisher catalogue / advertisement;
- final-range verification is closed at **30 / 30 VERIFIED, 0 unresolved** for scans 141–170.

### Tamil scene assembly checkpoint — COMPLETE

- `காட்சி 1` through `காட்சி 47`: **47 / 47 PASS / COMPLETE**;
- assembled files: `works/manimagudam/scenes/01.md` through `47.md`;
- per-scene fidelity reviews through `SCENE47_ASSEMBLY_FIDELITY_REVIEW.md`;
- source wording, punctuation, speaker-label variants, repetitions, ellipses, stage directions and source-specific forms retained;
- shared physical pages with multiple scenes split only at source-visible headings;
- unresolved assembly discrepancies: **0**.

Final `காட்சி 47` retains `(முடிவுற்றது)`. Scan 170 remains separate back matter.

## Independent English translation — AUTHORIZED / IN PROGRESS

Translation authority is the verified Tamil scene assembly. OCR, outside summaries and any published English are not drafting authorities. Published English, if later available, remains a separate secondary-witness layer to be opened only after the independent translation and Tamil→English review for the relevant scope are locked.

### Completed English Batch 1 — Scenes 1–5

- `works/manimagudam/translations/en/01.md` through `05.md`;
- all five scenes: **translation-reviewed / PASS**.

### Completed English Batch 2 — Scenes 6–10

- `06.md` through `10.md`;
- all five scenes: **translation-reviewed / PASS**.

### Completed English Batch 3 — Scenes 11–20

The user explicitly requested processing from Scene 11 through Scene 20 in one activity. All ten scenes have been independently translated from their verified Tamil assemblies and reviewed back against those authorities.

- `11.md` — Scene 11 / scans **55–58** — **PASS**;
- `12.md` — Scene 12 / scans **58–59** — **PASS**;
- `13.md` — Scene 13 / scans **60–65** — **PASS**;
- `14.md` — Scene 14 / scans **65–68** — **PASS**;
- `15.md` — Scene 15 / scans **68–70** — **PASS**;
- `16.md` — Scene 16 / scans **70–74** — **PASS**;
- `17.md` — Scene 17 / scans **74–75** — **PASS**;
- `18.md` — Scene 18 / scans **76–80** — **PASS**;
- `19.md` — Scene 19 / scans **80–81** — **PASS**;
- `20.md` — Scene 20 / scans **81–85** — **PASS**;
- `translations/en/TRANSLATION_REVIEW.md` now covers **Scenes 1–20**;
- independent English dramatic progress: **20 / 47 scenes translated and reviewed**;
- unresolved translation blocks through Scene 20: **0**;
- secondary-English contamination: **0**.

Batch-3 source-sensitive / rhetorical controls include:

- Kalarani / Vanji's unnamed `அவர்` retained as `him` until the source identifies him;
- `காதல் அரிச்சுவடி` → `alphabet-primer of love`;
- Scene-14 `மெய்` truth/body pun preserved explicitly;
- `ரசமில்லாத கண்ணாடி` / `காதல் ரசம்` → `unsilvered mirror` / `rasa of love`;
- `மயக்கம்` remains context-dependent — charm, unconsciousness or ideological stupor;
- `குருபீடம் - அதிகார பீடம் - பிரச்சார பீடம்` → `guru-seat - seat of power - propaganda-seat`;
- source-specific `குரப்புலிகள்` retained as `kurappuligal` rather than assigned an unsupported modern equivalent.

Recurring controls continue:

- `மக்கள் மன்றம்` → `People's Forum`;
- `சீமான்கள் சபை` → `Assembly of Nobles`;
- `மக்கள் தொண்டன்` → *People's Servant*;
- `ஆட்சிப் பீடம்` → `seat of power` where abstract authority is meant;
- `கொடிக்கால் நகரம்` → `Kodikkal Nagar`;
- `விசேஷ அதிகாரம்` → `special authority`;
- newspaper title `மணிமகுடம்` → *Manimagudam*.

## Exact next activity

Continue the independent English translation with **Scenes 21–25 only**.

1. Fetch live `main` first.
2. Read this handover, `NEXT_CHAT_PROMPT.md`, `STAGE_PLAY_PROCESSING_GUIDE.md`, `works/manimagudam/README.md`, `works/manimagudam/translations/en/README.md`, and the current `TRANSLATION_REVIEW.md`.
3. Fetch complete verified Tamil assemblies `works/manimagudam/scenes/21.md` through `25.md`.
4. Translate each scene independently into `works/manimagudam/translations/en/21.md` through `25.md` using the established schema and terminology controls.
5. Preserve scene structure, speaker identity, stage directions, rhetoric, repetition, humour, ambiguity, political meaning and source-specific terminology.
6. Review every new English scene back against its verified Tamil assembly before marking `translation-reviewed` / PASS.
7. Extend `translations/en/TRANSLATION_REVIEW.md` and `translations/en/README.md` to **25 / 47** only after the batch passes.
8. Update root/work README and handover tracking.
9. Stop at Scene 25 unless the user explicitly requests a larger continuation.

Do **not** reopen the closed Tamil page or scene-assembly gates during ordinary translation work.

## Critical source-boundary safeguard

A conversation preview exposed only 150 pages, but the raw controlling PDF contains **170 physical scans**. The raw 170-page count is authoritative.

## Performance-history provenance safeguard

The user-supplied catalog context records a **1962 Madurai DMK conference** performance. The controlling scan independently records:

- scan 4: **May 1956**, DMK second state conference, Tiruchirappalli, S. S. Rajendran troupe;
- scan 5: **September 1963** staging associated with the Murasoli drama troupe under Anna's leadership.

Do not silently merge these statements.

## Phase boundary

- Tamil page-level archival transcription: **COMPLETE — 170 / 170**.
- Tamil scene assembly: **COMPLETE — 47 / 47 PASS**.
- Independent English translation: **IN PROGRESS — 20 / 47 translation-reviewed**.
- Secondary-English witness comparison for `மணிமகுடம்`: **not started**.

## Closed `கலைஞரின் நான்மணி மாலை` state

- Tamil composite coverage: **54/54 PASS / COMPLETE**;
- independent English translations: **4/4 COMPLETE**;
- applicable 2009 witness comparisons: **3/3 PASS / COMPLETE**;
- `பரதாயணம்` witness comparison: **NOT APPLICABLE**.

Do not reopen closed work without explicit direction or new source evidence.

## Permanent safeguards

- live `main` controls repository state;
- source PDFs remain external;
- no silent lexical, punctuation, speaker, stage-direction, or old-glyph normalization;
- physical page boundaries remain preserved in page records;
- scene assembly derives only from verified page records;
- independent translation derives from verified Tamil scene assemblies;
- provisional/uncommitted work is not durable verification;
- published English remains a secondary witness;
- `அந்தணர்` is not automatically `Brahmin` without contextual justification.