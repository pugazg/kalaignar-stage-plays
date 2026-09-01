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

### Final page-level checkpoint

- front matter scans **1–13**: **13 / 13 VERIFIED**;
- dramatic-body scans **14–169**: **156 / 156 VERIFIED**;
- back matter scan **170**: **1 / 1 VERIFIED**;
- overall physical-page archive: **170 / 170 COMPLETE**;
- durable page records: `works/manimagudam/pages/0001.md` through `0170.md`;
- `காட்சி 1` through `காட்சி 47`: page-level source transcription complete;
- scan **169 / printed page 160** closes `காட்சி 47` with source-visible `(முடிவுற்றது)`;
- scan **170** is the verified publisher catalogue / advertisement headed `கலைஞரின் சிறப்புமிகு நூல்கள்`.

Final-range verification remains closed and authoritative:

- `SCANS_0141_0145_VERIFICATION.md` — **5 / 5 VERIFIED, 0 unresolved**;
- `SCANS_0146_0150_VERIFICATION.md` — **5 / 5 VERIFIED, 0 unresolved**;
- `SCANS_0151_0155_VERIFICATION.md` — **5 / 5 VERIFIED, 0 unresolved**;
- `SCANS_0156_0160_VERIFICATION.md` — **5 / 5 VERIFIED, 0 unresolved**;
- `SCANS_0161_0170_VERIFICATION.md` — **10 / 10 VERIFIED, 0 unresolved**;
- `SCANS_0141_0170_VERIFICATION.md` — aggregate **30 / 30 VERIFIED, 0 unresolved**.

`works/manimagudam/indexes/page-map.md` is synchronized through scan 170 and records the final **170 / 170 COMPLETE** page-level checkpoint.

## Scene assembly checkpoint

The user has now explicitly authorized the next phase by asking to proceed with the next activity. The sequential next phase is **Tamil scene assembly**. English translation remains separately unauthorized.

Completed scene-assembly gate:

- `காட்சி 1`: **PASS / COMPLETE**;
- source page records: `pages/0014.md` through `pages/0019.md`;
- physical scans: **14–19**;
- printed pages: scan 14 unnumbered, then **6–10**;
- assembled file: `works/manimagudam/scenes/01.md`;
- fidelity review: `works/manimagudam/SCENE1_ASSEMBLY_FIDELITY_REVIEW.md`;
- verified page records represented: **6 / 6**;
- mechanical cross-page joins checked: **4 / 4**;
- unresolved assembly discrepancies: **0**;
- scene assembly overall: **1 / 47 PASS**.

The Scene 1 assembly joins only mechanical physical-page interruptions. It does not alter source wording, punctuation, speaker-label variants, stage directions, repetitions, ellipses or old/source-specific forms. The review records the exact scan 14→15, 16→17, 17→18 and 18→19 joins.

### Exact next activity

**Assemble `காட்சி 2` only.**

1. Fetch live `main` first and preserve newer durable state.
2. Read `STAGE_PLAY_PROCESSING_GUIDE.md`, this handover, `NEXT_CHAT_PROMPT.md`, `works/manimagudam/README.md`, `works/manimagudam/SCENE1_ASSEMBLY_FIDELITY_REVIEW.md`, and `works/manimagudam/scenes/01.md`.
3. Read the verified page records `works/manimagudam/pages/0020.md` through `0024.md`.
4. Assemble Scene 2 only from the verified Scene 2 portions of those page records.
5. Scans **20–24** correspond to printed pages **11–15**; scan 24 closes `காட்சி 2` and then opens `காட்சி 3` on the same physical page.
6. Stop Scene 2 assembly exactly at the source-visible `காட்சி 3` boundary. Do not absorb Scene 3 text.
7. Remove only mechanical physical-page breaks needed for readable assembly; preserve exact source words, punctuation, labels, stage directions and source forms.
8. Create `works/manimagudam/scenes/02.md` and a Scene 2 assembly-fidelity review.
9. Update the work/root status, this handover and next-chat prompt to **2 / 47** only after the fidelity gate passes.
10. Commit directly to `main`, refetch live `main`, and verify the assembled scene plus its review.

Do not automatically continue to Scene 3 in the same activity unless the user explicitly asks to continue immediately.

## Critical source-boundary safeguard

A conversation preview exposed only 150 pages, but the raw controlling PDF contains **170 physical scans**. The raw 170-page count is authoritative; scans 151–170 were rendered directly from the raw source.

## Performance-history provenance safeguard

The user-supplied catalog context records a **1962 Madurai DMK conference** performance. The controlling scan independently records:

- scan 4: **May 1956**, DMK second state conference, Tiruchirappalli, S. S. Rajendran troupe;
- scan 5: **September 1963** staging associated with the Murasoli drama troupe under Anna's leadership.

Do not silently merge these statements. The 1962 statement remains user-supplied unless separately sourced.

## Phase boundary

- Tamil page-level archival transcription: **COMPLETE — 170 / 170**.
- Tamil scene assembly: **ACTIVE — 1 / 47 PASS**.
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
