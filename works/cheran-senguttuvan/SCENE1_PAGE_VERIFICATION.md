# `காட்சி — 1` page verification — சேரன் செங்குட்டுவன்

## Scope

Controlling Tamil source: `TVA_BOK_0065576_நான்மணி_மாலை.pdf`.

Scene 1 spans:

- scan **44** / printed p.39 — work opening + Scene-1 opening — `pages/0044.md`;
- scan **45** / printed p.40 — Scene-1 continuation/closing — `pages/0045.md`.

## Result

| Scan | Printed page | Role | Result |
|---:|---:|---|---|
| 44 | 39 | work opening + `காட்சி — 1` opening | **PASS / verified** |
| 45 | 40 | `காட்சி — 1` continuation/closing | **PASS / verified** |

Scene-1 page gate: **2/2 verified — COMPLETE**.

## First-pass / source reconciliation

The user supplied a Gemini word-to-word first pass covering the Cheran source extent. It is used as the comparison baseline; the controlling Tamil scan remains authoritative under `STAGE_PLAY_PROCESSING_GUIDE.md`.

### Scan 44

Unambiguous differences retained in the canonical record include:

| Gemini first pass | Controlling scan | Decision |
|---|---|---|
| `காட்சி-1` | `காட்சி — 1` | source heading retained |
| `வேந்தர் குலதிலக` | `வேந்தர்குலதிலக` | source form retained |
| `கனக விஐயர்` | `கனக விஜயர்` | source form retained |
| `கன :` | `கன:` | source label spacing retained |

### Scan 45

Unambiguous differences retained in the canonical record include:

| Gemini first pass | Controlling scan | Decision |
|---|---|---|
| stray `ழ்!` after `செந்தமிழ்!` | absent | omitted; not printed in source |
| `யுல:` before poem | `புல:` | source speaker label retained |
| standalone `தமிழன்!` after `விஜ: நிறுத்தும் ஓய்!` | part of following `கன:` speech | source dialogue structure retained |
| `யுல: : கனகர் சொன்னது...` | `விஜ: கனகர் சொன்னது...` | source speaker label/structure retained |
| ASCII-hyphen-style separations | printed long dashes | source dash forms retained |

No change is made merely from grammar, familiar spelling, semantic expectation or the English witness.

## Scan-controlled structure

- scan 44 preserves the two-line work title `சேரன்` / `செங்குட்டுவன்`, the pre-scene voice-over and heading `காட்சி — 1`;
- scan 45 preserves the continuation dialogue and the closing speech ending `சேரன் செங்குட்டுவன்!!`;
- speaker-label forms are retained exactly from each scan;
- physical source lines are preserved in the two page records;
- printed page numbers `39` and `40` are represented separately;
- neither scan 44 nor scan 45 carries a printed scene-closing `*`; Scene 1 closes structurally at the end of scan 45 before the registered Scene-2 opening on the next source page.

## Integrity checkpoint

- source scans directly inspected for Scene 1: **2/2**;
- user-supplied first-pass compared: **yes**;
- English witness used to reconstruct Tamil: **no**;
- Scene-1 page records verified: **2/2**;
- Scene-1 page gate: **COMPLETE**;
- total Cheran Tamil pages verified: **2/10**.

## Downstream assembly state

Scene 1 has now been assembled exclusively from the two verified page records:

- assembled file: `scenes/01.md`;
- fidelity audit: `SCENE1_ASSEMBLY_FIDELITY_REVIEW.md`;
- page-record ↔ scene result: **PASS**;
- unresolved assembly discrepancies: **0**;
- speaker-label mismatches: **0**;
- assistant lexical substitutions: **0**;
- invented closing `*`: **no**.

Scenes assembled from controlling Tamil: **1/4**.

## Next activity

Verify **scan 46 / printed p.41 only**, the opening page of `காட்சி — 2`. Do not process scan 47 or assemble Scene 2 in the same activity.
