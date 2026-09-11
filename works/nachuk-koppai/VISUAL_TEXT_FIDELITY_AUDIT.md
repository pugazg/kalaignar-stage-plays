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
| 04 | 16–20 | **4 PASS / 1 NEEDS-REVIEW** |
| 05 | 21–25 | **4 PASS / 1 NEEDS-REVIEW** |
| 06 | 26–30 | **5 PASS / COMPLETE** |
| 07 | 31–35 | pending |
| 08 | 36–40 | pending |
| 09 | 41–45 | pending |
| 10 | 46–50 | pending |
| 11 | 51–55 | pending |
| 12 | 56–60 | pending |
| 13 | 61–63 | pending |

Current coverage: **30 / 63 scans**.

Current fidelity results:
- PASS: **28** — scans **1–19, 21, 23–30**;
- NEEDS-REVIEW: **2** — scans **20, 22**;
- source-proven correction loci in fidelity phase: **101**.

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
- scan 20 — NEEDS-REVIEW after three source-secure repairs; only `வேணும்லும்` remains unresolved.

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

Next fidelity batch: **scans 31–35**.
