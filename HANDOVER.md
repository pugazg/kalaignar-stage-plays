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
- scan **169 / printed page 160** closes `காட்சி 47` with `(முடிவுற்றது)`;
- scan **170** is verified publisher catalogue / advertisement;
- `works/manimagudam/indexes/page-map.md` synchronized through scan 170;
- final-range page verification remains closed and authoritative at **30 / 30 VERIFIED, 0 unresolved** for scans 141–170.

## Tamil scene assembly checkpoint

The user explicitly authorized scene assembly through `காட்சி 27`. Scene assembly derives only from verified page records; no page-level source gate was reopened.

Completed scene assemblies:

- `காட்சி 1`–`காட்சி 7` — previously completed — **PASS**;
- `காட்சி 8` — scans **44–49** — **PASS**;
- `காட்சி 9` — scans **49–50** — **PASS**;
- `காட்சி 10` — scans **50–55** — **PASS**;
- `காட்சி 11` — scans **55–58** — **PASS**;
- `காட்சி 12` — scans **58–59** — **PASS**;
- `காட்சி 13` — scans **60–65** — **PASS**;
- `காட்சி 14` — scans **65–68** — **PASS**;
- `காட்சி 15` — scans **68–70** — **PASS**;
- `காட்சி 16` — scans **70–74** — **PASS**;
- `காட்சி 17` — scans **74–75** — **PASS**;
- `காட்சி 18` — scans **76–80** — **PASS**;
- `காட்சி 19` — scans **80–81** — **PASS**;
- `காட்சி 20` — scans **81–85** — **PASS**;
- `காட்சி 21` — scans **85–94** — **PASS**;
- `காட்சி 22` — scans **94–95** — **PASS**;
- `காட்சி 23` — scans **95–100** — **PASS**;
- `காட்சி 24` — scans **100–101** — **PASS**;
- `காட்சி 25` — scans **101–104** — **PASS**;
- `காட்சி 26` — scans **104–108** — **PASS**;
- `காட்சி 27` — scan **108** — **PASS**.

Scene assembly overall: **27 / 47 PASS**.

Assembled files exist as `works/manimagudam/scenes/01.md` through `27.md`. Per-scene fidelity reviews exist through `SCENE27_ASSEMBLY_FIDELITY_REVIEW.md`.

Through Scene 27:

- all verified source-page portions are represented;
- shared physical pages containing multiple scene boundaries are split only at source-visible scene headings;
- only mechanical physical-page interruptions are joined;
- source wording, punctuation, speaker-label variants, repetitions, ellipses, stage directions and source-specific forms are retained;
- unresolved assembly discrepancies: **0**.

Latest-batch mechanical joins / boundary controls:

- scan 80→81: Scene 19 `அமை:` continuation;
- scan 82→83: Scene 20 அல்லி continuation;
- scan 85→86: Scene 21 குணசீலர் continuation;
- scan 90→91: Scene 21 physically split stage direction, retaining source punctuation;
- scan 91→92: Scene 21 நாடோடி utterance;
- scan 94→95: Scene 22 newspaper/street-sale continuation;
- scan 95→96, 97→98 and 98→99: Scene 23 continuations;
- scan 103→104: Scene 25 குருநாதர் continuation;
- scan 105→106, 106→107 and 107→108: Scene 26 அரசன் continuations;
- scan 108 contains Scene 26 close, the complete Scene 27, and Scene 28 opening; Scene 27 is bounded exactly by its headings.

### Exact next activity

**Assemble `காட்சி 28` only.**

1. Fetch live `main` first and preserve newer durable state.
2. Read `STAGE_PLAY_PROCESSING_GUIDE.md`, this handover, `NEXT_CHAT_PROMPT.md`, `works/manimagudam/README.md`, `SCENE27_ASSEMBLY_FIDELITY_REVIEW.md`, and `scenes/27.md`.
3. Read verified page records `pages/0108.md` through `0110.md` completely.
4. Assemble only Scene 28 into `works/manimagudam/scenes/28.md`.
5. Scene 28 begins on scan **108**, continues through **109**, and closes on scan **110** before `காட்சி 29` begins on the same physical scan.
6. Stop exactly before the source-visible Scene 29 heading.
7. Join only mechanical physical-page interruptions; preserve all source wording, punctuation, labels, repetitions and stage directions.
8. Create `SCENE28_ASSEMBLY_FIDELITY_REVIEW.md` and promote status to **28 / 47** only after PASS.
9. Commit directly to `main`, refetch live `main`, and verify the assembled scene and review.

Do not automatically continue beyond Scene 28 unless the user explicitly asks.

## Critical source-boundary safeguard

A conversation preview exposed only 150 pages, but the raw controlling PDF contains **170 physical scans**. The raw 170-page count is authoritative.

## Performance-history provenance safeguard

The user-supplied catalog context records a **1962 Madurai DMK conference** performance. The controlling scan independently records May 1956 Tiruchirappalli and September 1963 performance evidence. Do not silently merge these statements.

## Phase boundary

- Tamil page-level archival transcription: **COMPLETE — 170 / 170**.
- Tamil scene assembly: **ACTIVE — 27 / 47 PASS**.
- English translation: **not authorized / not started**.

Do not begin English translation merely because scene assembly is active.

## Closed `கலைஞரின் நான்மணி மாலை` state

Tamil composite coverage **54/54 PASS / COMPLETE**; independent English **4/4 COMPLETE**; applicable 2009 witness comparisons **3/3 PASS / COMPLETE**; `பரதாயணம்` witness comparison **NOT APPLICABLE**. Do not reopen without explicit direction or new source evidence.

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
