# Kalaignar Stage Plays — Handover

Repository: `pugazg/kalaignar-stage-plays`, branch `main`.

## Startup rule

Always fetch live `main` first and treat it as authoritative. Preserve newer durable state. Do not reset, overwrite, repeat, or reopen completed source work unless the user explicitly requests it or new source evidence requires reconciliation.

Permanent workflow: `STAGE_PLAY_PROCESSING_GUIDE.md`.

## மணிமகுடம் — page-level Tamil archive COMPLETE; scene assembly ACTIVE

Controlling source: `TVA_BOK_0064143_மணி_மகுடம்.pdf`.

Durable source identity:

- SHA-256: `a629509c3404fcc5c2844f5b693e72a41aca03ad2e2494588807af4ff8f16f3b`;
- file size: **187,091,728 bytes**;
- physical PDF scans: **170**;
- sixth edition scan statement: **May 2010**, price **Rs.40.00**.

### Page-level checkpoint

- front matter scans **1–13**: **13 / 13 VERIFIED**;
- dramatic-body scans **14–169**: **156 / 156 VERIFIED**;
- back matter scan **170**: **1 / 1 VERIFIED**;
- overall physical-page archive: **170 / 170 COMPLETE**;
- durable page records: `works/manimagudam/pages/0001.md` through `0170.md`;
- `காட்சி 1` through `காட்சி 47`: page-level source transcription complete;
- scan **169 / printed page 160** closes `காட்சி 47` with source-visible `(முடிவுற்றது)`;
- scan **170** is the verified publisher catalogue / advertisement headed `கலைஞரின் சிறப்புமிகு நூல்கள்`.

Final-range page verification remains closed and authoritative, including `SCANS_0141_0170_VERIFICATION.md` at **30 / 30 VERIFIED, 0 unresolved**. `works/manimagudam/indexes/page-map.md` is synchronized through scan 170.

## Tamil scene assembly checkpoint

The user explicitly authorized assembly through `காட்சி 7`. Assembly derives only from verified page records; no page-level source gate was reopened.

Completed scene assemblies:

- `காட்சி 1` — scans **14–19** — `scenes/01.md` — **PASS**;
- `காட்சி 2` — scans **20–24** — `scenes/02.md` — **PASS**;
- `காட்சி 3` — scans **24–26** — `scenes/03.md` — **PASS**;
- `காட்சி 4` — scans **27–30** — `scenes/04.md` — **PASS**;
- `காட்சி 5` — scans **30–32** — `scenes/05.md` — **PASS**;
- `காட்சி 6` — scans **32–39** — `scenes/06.md` — **PASS**;
- `காட்சி 7` — scans **39–44** — `scenes/07.md` — **PASS**.

Scene assembly overall: **7 / 47 PASS**.

Per-scene fidelity reviews exist as `SCENE1_ASSEMBLY_FIDELITY_REVIEW.md` through `SCENE7_ASSEMBLY_FIDELITY_REVIEW.md`. Through Scene 7:

- all verified source-page portions are represented;
- shared physical pages containing two scene boundaries are split at the source-visible scene heading;
- only mechanical page interruptions are joined;
- source wording, punctuation, speaker-label variants, repetitions, ellipses, stage directions and source-specific forms are retained;
- unresolved assembly discrepancies: **0**.

Notable shared-page boundaries already handled:

- scan 24: `காட்சி 2` close / `காட்சி 3` open;
- scan 30: `காட்சி 4` close / `காட்சி 5` open;
- scan 32: `காட்சி 5` close / `காட்சி 6` open;
- scan 39: `காட்சி 6` close / `காட்சி 7` open;
- scan 44: `காட்சி 7` close / `காட்சி 8` open.

### Exact next activity

**Assemble `காட்சி 8` only.**

1. Fetch live `main` first and preserve newer durable state.
2. Read `STAGE_PLAY_PROCESSING_GUIDE.md`, this handover, `NEXT_CHAT_PROMPT.md`, `works/manimagudam/README.md`, `SCENE7_ASSEMBLY_FIDELITY_REVIEW.md`, and `scenes/07.md`.
3. Read verified page records `pages/0044.md` through `0049.md` completely.
4. Assemble only the Scene 8 portions into `works/manimagudam/scenes/08.md`.
5. Scan 44 begins `காட்சி 8` after Scene 7 closes; scan 49 closes Scene 8 and then opens `காட்சி 9` on the same physical scan.
6. Stop exactly before the source-visible `காட்சி 9` heading.
7. Join only mechanical physical-page interruptions; preserve all source wording, punctuation, labels and stage directions.
8. Create `SCENE8_ASSEMBLY_FIDELITY_REVIEW.md` and promote status to **8 / 47** only after PASS.
9. Commit directly to `main`, refetch live `main`, and verify the assembled scene and review.

Do not automatically continue beyond Scene 8 unless the user explicitly asks.

## Critical source-boundary safeguard

A conversation preview exposed only 150 pages, but the raw controlling PDF contains **170 physical scans**. The raw 170-page count is authoritative; scans 151–170 were rendered directly from the raw source.

## Performance-history provenance safeguard

The user-supplied catalog context records a **1962 Madurai DMK conference** performance. The controlling scan independently records:

- scan 4: **May 1956**, DMK second state conference, Tiruchirappalli, S. S. Rajendran troupe;
- scan 5: **September 1963** staging associated with the Murasoli drama troupe under Anna's leadership.

Do not silently merge these statements. The 1962 statement remains user-supplied unless separately sourced.

## Phase boundary

- Tamil page-level archival transcription: **COMPLETE — 170 / 170**.
- Tamil scene assembly: **ACTIVE — 7 / 47 PASS**.
- English translation: **not authorized / not started**.

Do not begin English translation merely because scene assembly is active.

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
- every physical scan, including back matter, has a durable record;
- scene assembly derives only from verified page records;
- assembly may remove mechanical page breaks only when provenance is documented;
- provisional/uncommitted work is not durable verification;
- independent translation derives from verified Tamil;
- published English remains a secondary witness;
- `அந்தணர்` is not automatically `Brahmin` in future translation work.
