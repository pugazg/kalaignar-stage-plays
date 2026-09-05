# காகிதப்பூ — Final page-layer consistency audit

Status: **PASS WITH FIVE OPEN LEXICAL-WITNESS EXCEPTIONS**

Scope: physical scans **91–131 inclusive = 41 page records**.

Structural authority: `TVA_PRL_0001638_முரசொலி_ பொங்கல் மலர்_ 1967.pdf`

Lexical witness: user-supplied `kaagidha_poo.md`.

Gap adjudication authority: `LEXICAL_GAP_ADJUDICATION.md`.

## Audit checks

### 1. Page-record coverage — PASS

- expected physical range: **91–131**;
- expected records: **41**;
- repository page layer: `pages/0091.md` through `pages/0131.md`;
- unprocessed page placeholders remaining: **0**.

### 2. Status accounting — PASS

- fully dual-witness `verified`: **36 / 41**;
- `needs-review`: **5 / 41** — **93, 95, 97, 98, 130**;
- `not-started`: **0 / 41**.

The five exceptions match the separately adjudicated lexical-witness gaps. No page is left in an ambiguous processing state.

### 3. Witness-policy consistency — PASS

Across the page layer, the durable policy is:

- MD controls lexical words/forms;
- PDF controls page and scene boundaries, punctuation, speaker/paragraph grouping, stage-direction placement, reading order, headings, photographs, captions/boxed features and other physical evidence;
- PDF-only lexical material is not silently imported.

The five `needs-review` pages explicitly expose the positions where this policy prevents full lexical completion.

### 4. Scene-boundary chain — PASS

The page map and page records preserve the physical scene sequence:

- scan 91 — work opener;
- 92 — `காட்சி 1`;
- 93 — Scene 1 close, `காட்சிகள்: 2, 3, 4, 5.`, Scene 6 opening;
- 94 — Scene 6 close / Scene 7 opening;
- 98 — Scene 7 close / Scene 8 opening;
- 102 — Scene 8 close, Scene 9, Scene 10 opening;
- 104 — Scene 10 close / Scene 11 opening;
- 105 — Scene 11 close / Scene 12 opening;
- 107 — Scene 12 close, Scene 13, Scene 14 opening;
- 109 — Scene 14 close / Scene 15 opening;
- 110 — Scene 15 close / Scene 16 opening;
- 114 — Scene 16 close / Scene 17 opening;
- 115 — Scene 17 close / Scene 18 opening;
- 116 — Scene 18 close / Scene 19;
- 117 — Scene 20 opening;
- 119 — Scene 20 close / Scene 21 opening;
- 124 — Scene 21 close / unnumbered `காட்சி,` opening;
- 125 — unnumbered scene close / source-visible `காட்சி 24.` opening;
- 129 — Scene 24 close, Scene 25, Scene 26 opening;
- 130 — Scene 26 close / Scene 27 opening;
- 131 — Scene 27 close with `(முற்றும்)` and cast block.

### 5. Scene-number anomaly — PASS

The source anomaly is preserved without editorial repair:

- scan **124**: `காட்சி,` with no numeral;
- scan **125**: `காட்சி 24.`.

No `காட்சி 22` or `காட்சி 23` has been invented in the physical page layer.

### 6. Cross-page continuation handling — PASS

Known source-controlled continuations and word/sentence splits are represented rather than silently reflowed, including the previously audited transitions around scans 92→93, 96→97, 98→99, 99→100→101, 102→103→104, 106→107, 109→110, 111→112, 113→114, 117→118→119, 120→121, 123→124, 127→128 and 128→129.

### 7. Non-dramatic physical features — PASS WITH ONE OPEN CAPTION GAP

The page layer separately records staged photographs, decorative borders, the scan-130 boxed `கண்டுபிடியுங்கள்` feature and the scan-131 `நாடகத்தில்—பங்கேற்பவர்கள்!` cast block.

Scan **98** remains the one open caption exception because the PDF has a printed personal-name caption for which the MD supplies no lexical witness.

### 8. Final closure — PASS

Scan 131 preserves:

- Scene-27 conclusion;
- `(முற்றும்)`;
- boxed `நாடகத்தில்—பங்கேற்பவர்கள்!` material;
- MD-supplied publication/imprint wording.

The selected physical source range therefore has a durable endpoint.

## Final page-layer result

**PAGE LAYER COMPLETE WITH DOCUMENTED EXCEPTIONS.**

- processed: **41 / 41**;
- fully verified: **36 / 41**;
- confirmed lexical exceptions: **5 / 41**;
- unprocessed: **0**;
- scene-number anomaly: preserved;
- scene assembly: **not started / not authorized**;
- English translation: **not started / not authorized**.

No further page-level source work can close the five lexical exceptions without a change in lexical-witness authority or an explicit user decision accepting the gaps permanently.
