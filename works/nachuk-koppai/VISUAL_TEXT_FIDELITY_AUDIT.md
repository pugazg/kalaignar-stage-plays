# நச்சுக்கோப்பை — Word-by-word visual text fidelity audit

Authority: attached `ACL-TDD_00314_நச்சுக்_கோப்பை.pdf` only.

Batch size: **5 physical scans per iteration**.

Method: every visible publication-text token is compared in reading order against the canonical page record. This includes headings, speaker labels, stage directions, punctuation, numerals and Latin-script material. Non-authorial source marks are checked for correct separation. No semantic normalization is permitted.

## Progress

| Fidelity batch | Scans | Result |
|---|---:|---|
| 01 | 1–5 | **3 PASS / 2 NEEDS-REVIEW** |
| 02 | 6–10 | next |
| 03 | 11–15 | pending |
| 04 | 16–20 | pending |
| 05 | 21–25 | pending |
| 06 | 26–30 | pending |
| 07 | 31–35 | pending |
| 08 | 36–40 | pending |
| 09 | 41–45 | pending |
| 10 | 46–50 | pending |
| 11 | 51–55 | pending |
| 12 | 56–60 | pending |
| 13 | 61–63 | pending |

Current coverage: **5 / 63 scans**.

Current fidelity results:
- PASS: **3** — scans **1, 2, 5**;
- NEEDS-REVIEW: **2** — scans **3, 4**;
- source-proven text corrections in fidelity phase: **0**.

## Batch 01 summary

- scan 1 — PASS; all publication-text tokens match; later stamps remain excluded;
- scan 2 — PASS; all publication-text tokens match after mechanical line-wrap joining; presentation/library mark remains separate;
- scan 3 — NEEDS-REVIEW; all readable text through `என்றுமுங்கள்,` matches; final publisher/sign-off line remains visually unresolved;
- scan 4 — NEEDS-REVIEW; all readable names match except unresolved `திகேசவலு முதலியார்` and `ஷெசிஷ்யன்`;
- scan 5 — PASS; full printed p.1 literary text matches; accession mark `14063` remains excluded.

Next fidelity batch: **scans 6–10**.
