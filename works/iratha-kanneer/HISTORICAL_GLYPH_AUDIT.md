# Historical Tamil Glyph Audit — இரத்தக் கண்ணீர்

Status: **BATCHES 01–05 PASS — SCANS 1–50 / 50 OF 188 H-GATES COMPLETE; 50 FINAL `verified`; 13 HISTORICAL-GLYPH CORRECTIONS RECORDED**

Controlling source: `TVA_BOK_0064189_இரத்தக்_கண்ணீர்.pdf`.

Repository authorities:

- `../../HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`
- `../../HISTORICAL_TAMIL_GLYPH_GATE.md`

This 1953 first-edition source visibly uses historical Tamil typeforms. A page may become finally `verified` only after both ordinary initial visual verification and the separate historical-glyph H-GATE pass.

## Mandatory minimum family set

Every applicable Tamil page receives the complete minimum-family check:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

This is a minimum, not a closed list. If another historical look-alike appears, it must also be adjudicated. Batch 05 exposed a supplemental `ளா` form on scan 48.

## Gate order

1. canonical source transcription;
2. initial visual verification;
3. H-GATE at enlarged/native source pixels;
4. final `verified` only after H-GATE PASS and closure of all other source issues.

## Permanent rules

1. source pixels control character identity;
2. read historical character identity, not the closest-looking modern glyph;
3. inspect whole pages and complete glyph clusters at enlarged/native resolution;
4. use clearer same-font / same-edition witnesses when a cluster is doubtful;
5. OCR, grammar, common spelling and dramatic context are never proof of glyph identity;
6. preserve source spelling, vocabulary, punctuation, grammar, speaker labels and spacing unless separate source evidence proves a correction;
7. no global replacement of any glyph family;
8. record historical-glyph corrections separately from ordinary transcription corrections;
9. unresolved identity stays `needs-review`; `blocked` requires exhausted source-condition escalation;
10. if a systematic glyph error is discovered later, reopen affected `verified` pages and re-run H-GATE.

## Work-level progress

| Measure | Count |
|---|---:|
| Physical scans | 188 |
| Canonical page records created | 50 / 188 |
| Initial visual verification PASS | 50 / 188 |
| H-GATE checked / PASS | 50 / 188 |
| Final `verified` | 50 / 188 |
| `needs-review` after processing | 0 |
| `blocked` | 0 |
| Historical-glyph corrections recorded | 13 |

Batch authorities:

- `BATCH_01_REVIEW.md` — **PASS / scans 1–10**, including retrospective scan-9 reopen / correction / re-pass;
- `BATCH_02_REVIEW.md` — **PASS / scans 11–20**;
- `BATCH_03_REVIEW.md` — **PASS / scans 21–30**;
- `BATCH_04_REVIEW.md` — **PASS / scans 31–40**;
- `BATCH_05_REVIEW.md` — **PASS / scans 41–50**.

## Secure same-edition reference bank

### `ணா`
- scans 1–2, 4–5: `கருணாநிதி`;
- scan 19: `ஆணாகப்`;
- scan 28: `அண்ணா`.

### `ணை`
- scan 2: `பண்ணை`;
- scan 5: `பண்ணையார்`;
- scan 29: `பெண்ணை`;
- scan 36: `கண்ணையா!`.

### `ணொ`
_no secure positive witness yet_

### `ணோ`
_no secure positive witness yet_

### `லை`
Established repeatedly through scans 1–50, including `தலைப்பில்`, `கலைஞரின்`, `ஓலைகள்`, `வேலையும்`, `மாளிகை`, and scan 50 `அலைமோதும்`.

### `ளை`
Established repeatedly through scans 1–50, including `பாளையக்காரர்`, `படைகளை`, `வாளையும்`, and related environments.

### `றா`
_no secure correction witness yet_

### `றொ`
_no secure correction witness yet_

### `றோ`
_no secure correction witness yet_

### `னா`
- scan 9: `வயதுடையவனா`, `கிழவனா`;
- scan 17: `மருத்துவக் கிழவனார்`;
- scan 18: `ஏன் வந்தேனா?`;
- scan 21: `சரிதானா?`;
- scan 40: `நானா?`;
- scan 48: `வருவானா?`.

### `னை`
- scan 5: `கற்பனை`;
- scan 8 onward: repeated `அரண்மனை...` forms;
- scan 11: `அஞ்சல் மனையில்`;
- scans 12, 16: `அஞ்சல் மனை`;
- scan 31: `யானை போல்`.

### `னொ`
_no secure positive witness yet_

### `னோ`
_no secure positive witness yet_

### Supplemental `ளா`
- scan 48: `உட்கார்ந்தாள்`, `எழுந்தாள்`, `நின்றாள்`, `உலவினாள்`, `அயர்ந்தாள்`, `சாய்ந்தாள்`, `முயன்றாள்`, `கொண்டாள்`, `துவங்கிறாள்`, `வைத்தாள்`, `அலறினாள்`;
- scan 49: `விட்டாள்` confirms the same-edition identity.

The scan-48 `முயன்றாள்` / `அலறினாள்` loci are explicitly logged because their historical forms can look like modern `முயன்றுள்` / `அலறினுள்`.

## Correction log

| Scan | Printed page | Apparent / earlier reading | Source-supported reading | Historical family | Evidence | Gate result |
|---:|:---:|---|---|---|---|---|
| 9 | 8 | `வயதுடையவனு அல்லது கிழவனு` | `வயதுடையவனா அல்லது கிழவனா` | `னா` | user flagged old glyph; retrospective enlarged source-pixel review and same-edition comparison | PASS after reopen / re-audit |
| 11 | 10 | `அஞ்சல் மண்ணில்` | `அஞ்சல் மனையில்` | `னை` | enlarged cluster + same-edition `னை` witnesses | PASS |
| 12 | 11 | `அஞ்சல் மண்` | `அஞ்சல் மனை` | `னை` | repeated same-edition location wording | PASS |
| 16 | 15 | `அஞ்சல் மண்` | `அஞ்சல் மனை` | `னை` | repeated same-edition location wording | PASS |
| 17 | 16 | `மருத்துவக் கிழவனூர்` | `மருத்துவக் கிழவனார்` | `னா` | enlarged cluster + established same-edition `னா` identity | PASS |
| 18 | 17 | `ஏன் வந்தேனு?` | `ஏன் வந்தேனா?` | `னா` | enlarged cluster + established same-edition `னா` identity | PASS |
| 21 | 20 | `சரிதானு?` | `சரிதானா?` | `னா` | enlarged pixels + same-edition `னா` witnesses | PASS |
| 29 | 28 | `பெண்ணு பெற்று வைத்திருக்கிறாய்` | `பெண்ணை பெற்று வைத்திருக்கிறாய்` | `ணை` | enlarged cluster + same-edition `பண்ணை` witness; not grammar | PASS |
| 31 | 30 | `யானே போல்` | `யானை போல்` | `னை` | enlarged cluster + established same-edition `னை` witnesses | PASS |
| 40 | 39 | `நானு?` | `நானா?` | `னா` | enlarged cluster + established same-edition `னா` identity | PASS |
| 48 | 47 | `முத்தன் வருவானு?` | `முத்தன் வருவானா?` | `னா` | enlarged source cluster + scans 9/17/18/21/40 `னா` witnesses | PASS |
| 48 | 47 | `முயன்றுள்` | `முயன்றாள்` | supplemental `ளா` | enlarged cluster + same-page / adjacent-page `ளா` witnesses | PASS |
| 48 | 47 | `அலறினுள்` | `அலறினாள்` | supplemental `ளா` | enlarged cluster + same-page / adjacent-page `ளா` witnesses | PASS |

## Batch 05 source-sensitive observations

H-GATE did **not** authorize modernization of other unusual forms. Source-faithful readings retained include `அச்சாரமா`, `என் வாங்கிக் கொள்வேன்`, `கழுதை யாயிற்றே`, `கொள் வைக்கவேண்டும்`, `பொன்றும்`, `பாவமண்ணு`, `அக்கரை`, `வேண்டா மென்று`, `ஐப மாலையை`, `வேலையிலேப்பட்டிருந்த`, `இடமொரு திரும்பவே`, `விம்மியழ`, `காதற் புறாக்கள்`, `தேவையில்லை யென்று`, `கங்கணம்`, `ராஜா பர்த்துருஹரி`, `முடியாதப்பா`, and `முழுக்குப் போட்டுவிடு`.

## Batch checkpoint

- scans 1–10 — **PASS / COMPLETE**;
- scan 9 retrospective H-GATE reopening — **PASS / CLOSED**;
- scans 11–20 — **PASS / COMPLETE**;
- scans 21–30 — **PASS / COMPLETE**;
- scans 31–40 — **PASS / COMPLETE**;
- scans 41–50 — **PASS / COMPLETE**;
- contiguous final-verified range — **scans 1–50**;
- next H-GATE batch — **scans 51–60**, after each page's initial visual verification.