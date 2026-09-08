# Historical Tamil Glyph Audit — இரத்தக் கண்ணீர்

Status: **BATCHES 01–03 PASS — SCANS 1–30 / 30 OF 188 H-GATES COMPLETE; 30 FINAL `verified`; 8 HISTORICAL-GLYPH CORRECTIONS RECORDED**

Controlling source: `TVA_BOK_0064189_இரத்தக்_கண்ணீர்.pdf`.

Repository authorities:

- `../../HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`
- `../../HISTORICAL_TAMIL_GLYPH_GATE.md`

This 1953 first-edition source visibly uses historical Tamil typeforms. A page may become finally `verified` only after both ordinary initial visual verification and the separate historical-glyph H-GATE pass.

## Mandatory family set

Every applicable Tamil page receives the complete minimum-family check:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

Absence of a positive witness does not waive the gate.

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
| Canonical page records created | 30 / 188 |
| Initial visual verification PASS | 30 / 188 |
| H-GATE checked / PASS | 30 / 188 |
| Final `verified` | 30 / 188 |
| `needs-review` after processing | 0 |
| `blocked` | 0 |
| Historical-glyph corrections recorded | 8 |

Batch authorities:

- `BATCH_01_REVIEW.md` — **PASS / scans 1–10**, including retrospective scan-9 reopen / correction / re-pass;
- `BATCH_02_REVIEW.md` — **PASS / scans 11–20**;
- `BATCH_03_REVIEW.md` — **PASS / scans 21–30**.

## Secure same-edition reference bank

### `ணா`

- scans 1–2, 4–5: `கருணாநிதி`;
- scan 19: `ஆணாகப்`;
- scan 28: `அண்ணா`.

### `ணை`

- scan 2: `பண்ணை`;
- scan 5: `பண்ணையார்`;
- scan 29: `பெண்ணை` — same-edition historical `ணை` decoding.

### `ணொ`

_no secure positive witness yet_

### `ணோ`

_no secure positive witness yet_

### `லை`

- scans 4–20: established witnesses including `தலைப்பில்`, `கலைஞரின்`, `ஓலைகள்`, `தலைமயிரும்`, `வேலையும்`;
- scans 21–30: additional page-level occurrences checked during H-GATE.

### `ளை`

- scans 6–16: established witnesses including `பாளையக்காரர்`, `படைகளை`, `வீரக்களை`, `வாளையும்`;
- scans 26–30: `பாளையக்காரர்` and related environments.

### `றா`

_no secure correction witness yet_

### `றொ`

_no secure correction witness yet_

### `றோ`

_no secure correction witness yet_

### `னா`

- scan 9: `வயதுடையவனா`, `கிழவனா` — retrospective historical-glyph correction;
- scan 17: `மருத்துவக் கிழவனார்`;
- scan 18: `ஏன் வந்தேனா?`;
- scan 21: `சரிதானா?`.

### `னை`

- scan 5: `கற்பனை`;
- scan 8: `அரண்மனையை`;
- scan 11: `அஞ்சல் மனையில்`;
- scans 12, 16: `அஞ்சல் மனை`;
- scans 13–17: `அரண்மனை...` forms;
- scans 26, 28, 30: further `அரண்மனை...` witnesses.

### `னொ`

_no secure positive witness yet_

### `னோ`

_no secure positive witness yet_

## Correction log

| Scan | Printed page | Apparent / earlier reading | Source-supported reading | Historical family | Evidence | Gate result |
|---:|:---:|---|---|---|---|---|
| 9 | 8 | `வயதுடையவனு அல்லது கிழவனு` | `வயதுடையவனா அல்லது கிழவனா` | `னா` | user flagged old glyph; retrospective enlarged source-pixel review and same-edition comparison | PASS after reopen / re-audit |
| 11 | 10 | `அஞ்சல் மண்ணில்` | `அஞ்சல் மனையில்` | `னை` | enlarged source cluster + same-edition `னை` witnesses | PASS |
| 12 | 11 | `அஞ்சல் மண்` | `அஞ்சல் மனை` | `னை` | repeated same-edition location wording | PASS |
| 16 | 15 | `அஞ்சல் மண்` | `அஞ்சல் மனை` | `னை` | repeated same-edition location wording | PASS |
| 17 | 16 | `மருத்துவக் கிழவனூர்` | `மருத்துவக் கிழவனார்` | `னா` | enlarged cluster + scan-9 same-edition `னா` identity | PASS |
| 18 | 17 | `ஏன் வந்தேனு?` | `ஏன் வந்தேனா?` | `னா` | enlarged cluster + established same-edition `னா` identity | PASS |
| 21 | 20 | `சரிதானு?` | `சரிதானா?` | `னா` | enlarged source pixels + scans 9/17/18 same-edition `னா` witnesses | PASS |
| 29 | 28 | `பெண்ணு பெற்று வைத்திருக்கிறாய்` | `பெண்ணை பெற்று வைத்திருக்கிறாய்` | `ணை` | enlarged cluster + same-edition `பண்ணை` `ணை` witness; not inferred from grammar | PASS |

## Batch 03 source-sensitive observations

H-GATE did not authorize modernization of other unusual forms. Source-faithful readings retained include `அலைபெயருப்பி`, `அடியா சொல்லப்போகிறார்கள்?`, `படைகளிழந்தார்`, `நான்தேடிய`, `மதிப்பிடலா மென்றாலும்`, `அப்பய்யோ`, `விழுந்ததா நல்லதை`, `மற்றவர் களும்`, `தூங்கு மூஞ்சிக் கழுதை`, `எச்சில் இலை நாயே`, `அவளாயறியாமல்`, `குரு நிறைந்த ஒரு பெருமூச்சு!`, and `இளயராணி`.

## Batch checkpoint

- scans 1–10 — **PASS / COMPLETE**;
- scan 9 retrospective H-GATE reopening — **PASS / CLOSED**;
- scans 11–20 — **PASS / COMPLETE**;
- scans 21–30 — **PASS / COMPLETE**;
- contiguous final-verified range — **scans 1–30**;
- next H-GATE batch — **scans 31–40**, after each page's initial visual verification.