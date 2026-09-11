# நச்சுக்கோப்பை — Word-by-word visual text fidelity audit

Authority: attached `ACL-TDD_00314_நச்சுக்_கோப்பை.pdf` only.

Batch size: **5 physical scans per iteration**.

Method: every visible publication-text token is compared in reading order against the canonical page record. This includes headings, speaker labels, stage directions, punctuation, numerals and Latin-script material. Non-authorial source marks are checked for correct separation. No semantic normalization is permitted.

## Progress

| Fidelity batch | Scans | Result |
|---|---:|---|
| 01 | 1–5 | **5 PASS / COMPLETE** |
| 02 | 6–10 | **5 PASS / COMPLETE** |
| 03 | 11–15 | **5 PASS / COMPLETE** |
| 04 | 16–20 | **5 PASS / COMPLETE** |
| 05 | 21–25 | **4 PASS / 1 NEEDS-REVIEW** |
| 06 | 26–30 | **5 PASS / COMPLETE** |
| 07 | 31–35 | **4 PASS / 1 NEEDS-REVIEW** |
| 08 | 36–40 | **5 PASS / COMPLETE** |
| 09 | 41–45 | **5 PASS / COMPLETE** |
| 10 | 46–50 | **5 PASS / COMPLETE** |
| 11 | 51–55 | **5 PASS / COMPLETE** |
| 12 | 56–60 | **5 PASS / COMPLETE** |
| 13 | 61–63 | **3 PASS / COMPLETE** |

Current coverage: **63 / 63 scans — COMPLETE**.

Current fidelity results:
- PASS: **61** — scans **1–21, 23–34, 36–63**;
- TERMINAL SOURCE-CONDITION HOLDS: **2** — scans **22, 35**;
- source-proven / user-confirmed correction loci in fidelity phase: **281**.

## Batch 01 summary

- scan 1 — PASS; all publication-text tokens match; later stamps remain excluded;
- scan 2 — PASS; all publication-text tokens match after mechanical line-wrap joining; presentation/library mark remains separate;
- scan 3 — PASS after source-proven sign-off repair: `திராவிடன் பதிப்பகத்தார்`;
- scan 4 — PASS after source-proven name repairs: `ஆதிகேசவலு முதலியார்`, `சிஷ்யன்`;
- scan 5 — PASS; full printed p.1 literary text matches; accession mark `14063` remains excluded.

## Batch 02 summary

- scan 6 — PASS after 3 source-proven repairs;
- scan 7 — PASS, no changes;
- scan 8 — PASS after `சாந்தர்` → `சாந்தா`; devotional invocation confirmed source-unlabelled;
- scan 9 — PASS after 5 correction loci;
- scan 10 — PASS after `மூக்குக் கண்ணாடி` repair.

## Batch 03 summary

- scan 11 — PASS after 4 source-proven repairs;
- scan 12 — PASS, no changes;
- scan 13 — PASS after 5 source-proven repairs;
- scan 14 — PASS, source confirms unusual punctuation/dialect;
- scan 15 — PASS after 3 source-proven repairs.

## Batch 04 summary

- scans 16–19 — PASS after source-secure label/header/word repairs;
- scan 20 — PASS; three earlier source-secure repairs plus later user-confirmed source reading `வேணும்லும்` → `வேணும்னாலும்`.

## Batch 05 summary

- scans 21, 23, 24 and 25 — PASS after **28** source-proven correction loci;
- scan 22 — NEEDS-REVIEW after **8** source-proven corrections; the only remaining locus is the pair of adjacent unidentified source glyph clusters after `சாந்தா`;
- Batch 05 total source-proven correction loci: **36**;
- cumulative fidelity correction loci: **73**.

## Batch 06 summary

- scans 26–30 — **5 PASS / COMPLETE**;
- Batch 06 source-proven correction loci: **28**;
- scan 30 received a physical-boundary repair: stale text from the following scan was removed and the page is correctly a Scene 7 continuation, not the scene close;
- the source-supported historical `னா` identity in `படைக்குறானா?` was checked against same-edition evidence and preserved;
- cumulative fidelity correction loci: **101**;
- known follow-up: existing `pages/0031.md` is stale/misaligned and must be rebuilt from physical scan 31 before downstream scene mapping is trusted.

## Batch 07 summary

- scans 31–34 — **4 PASS**;
- scan 35 — **NEEDS-REVIEW** at one damaged/overinked source word immediately before `சூர்ய நாராயண`; prior first-pass `சுடகோடி` is retained provisionally only;
- all five page records 31–35 were rebuilt source-first because the earlier records were shifted one physical scan ahead;
- Batch 07 source-proven textual correction loci: **24**;
- structural physical-page realignments: **5**;
- cumulative fidelity correction loci: **125**;
- downstream warning: do not assume a fixed offset beyond scan 35; each next page must be re-anchored directly to its physical source scan.

## Batch 08 summary

- scans 36–40 — **5 PASS / COMPLETE**;
- each physical page was independently re-anchored to source; all five confirmed the prior one-page record drift continued through scan 40;
- Batch 08 source-proven textual correction loci: **28**;
- structural physical-page realignments: **5**;
- scan 40 is source-confirmed as a Scene 9 continuation, not the Scene 9 / Scene 10 boundary;
- cumulative fidelity correction loci: **153**;
- downstream warning remains: re-anchor each next physical scan independently; do not infer the offset.

## Batch 09 summary

- scans 41–45 — **5 PASS / COMPLETE**;
- each physical page was independently re-anchored to source; all five confirmed the prior one-page record drift continued through scan 45;
- Batch 09 source-proven textual correction loci: **27**;
- structural physical-page realignments: **5**;
- physical scan 41 contains the Scene 9 / Scene 10 boundary; scan 42 closes Scene 10; scan 43 contains the Scene 11 / Scene 12 boundary; scan 44 contains the Scene 12 / Scene 13 boundary; scan 45 remains within Scene 13;
- cumulative fidelity correction loci: **180**;
- downstream warning remains: re-anchor each next physical scan independently; do not infer the offset.

## Batch 10 summary

- scans 46–50 — **5 PASS / COMPLETE**;
- each physical page was independently re-anchored to source; all five confirmed the prior one-page record drift continued through scan 50;
- Batch 10 source-proven textual correction loci: **26**;
- structural physical-page realignments: **5**;
- physical scan 46 contains the Scene 13 / Scene 14 boundary; scan 48 closes Scene 14; scan 49 opens Scene 15; scan 50 contains the Scene 15 / Scene 16 boundary;
- cumulative fidelity correction loci: **206**;
- downstream warning remains: re-anchor each next physical scan independently; do not infer the offset.

## Batch 11 summary

- scans 51–55 — **5 PASS / COMPLETE**;
- each physical page was independently re-anchored to source; all five confirmed the one-page record drift continued through scan 55;
- Batch 11 source-proven textual correction loci: **29**;
- structural physical-page realignments: **5**;
- physical scan 54 closes Scene 16 and opens Scene 17; scan 55 closes Scene 17 and opens Scene 18;
- source-visible unusual ordering and wording on scans 54–55 were preserved without contextual repair;
- cumulative fidelity correction loci: **235**;
- downstream warning remains: re-anchor each next physical scan independently; do not infer the offset.

## Batch 12 summary

- scans 56–60 — **5 PASS / COMPLETE**;
- each physical page was independently re-anchored to source; all five confirmed the one-page record drift continued through scan 60;
- Batch 12 source-proven textual correction loci: **35**;
- structural physical-page realignments: **5**;
- scan 57 source-proves `என் தங்கையைக் கொலை செய்து`, correcting the stale `என் தந்தையைக்...` reading;
- scan 58 disproves the prior non-Tamil glyph cluster as a first-pass/OCR artefact;
- scans 59–60 preserve multilingual / phonetic police dialogue directly from source pixels without normalization;
- cumulative fidelity correction loci: **270**;
- final fidelity batch remains **scans 61–63**; re-anchor all three independently because scan 63 was separately source-confirmed earlier and no offset may be presumed.

## Batch 13 summary

- scans 61–63 — **3 PASS / COMPLETE**;
- all three final physical scans were independently re-anchored rather than inheriting the earlier offset;
- scan 61 confirms the drift continued one more page and source-disproves both the non-Tamil cluster after `மணியப்ப முதலியாருக்கும்` and the standalone `C`;
- scan 62 is the continuation of Sivaguru's lament and closes with `(சாந்தா வரல்)`;
- scan 63 contains the **final dialogue + `முற்றும்` + printer imprint on the same physical scan**; the stale `ரகா:` label is source-resolved as `ஏகா :`;
- Batch 13 source-proven textual correction loci: **10**;
- structural physical-page realignments / closure reconciliations: **3**;
- cumulative fidelity correction loci: **280**;
- word-by-word visual fidelity coverage is now **63 / 63 COMPLETE**.

Next phase: **full 63-page state reconciliation**, beginning with the three remaining fidelity holds at scans **20, 22 and 35**. Do not begin scene assembly yet.


## Full page-state reconciliation

Status: **COMPLETE / 63 OF 63 PAGE STATES RECONCILED**

Reconciliation actions:

- all 63 page-file metadata blocks were checked against the completed word-by-word fidelity layer;
- `scan_page`, section/scene state, page type, final `status`, `historical_glyph_gate`, and `visual_text_fidelity` are internally aligned;
- stale early Pass-A notes on scans **6, 8, 9 and 10** were repaired so they no longer claim H-GATE `NEEDS-REVIEW` after later PASS closure;
- the repaired downstream page alignment is now authoritative through scan **63**;
- scan **63** remains the source-proven combined **final dialogue + முற்றும் + printer imprint** page;
- the remaining loci on scans **20, 22 and 35** were re-read during reconciliation; scan 20 was subsequently resolved by the user's direct source reading as `வேணும்னாலும்`;
- scans **22 and 35** remain explicit **terminal source-condition holds for the current attached PDF**.

Reconciled page state:

- verified / PASS: **61 / 63**;
- terminal source-condition `needs-review`: **2 / 63** — scans **22, 35**;
- blocked: **0**;
- word-by-word fidelity coverage: **63 / 63 COMPLETE**;
- page-state reconciliation: **COMPLETE**.

Scene assembly may now begin from the reconciled page layer. Scene 3 is clean after the scan 20 resolution; assembled scenes intersecting scans 22 or 35 must carry those remaining holds forward explicitly.
