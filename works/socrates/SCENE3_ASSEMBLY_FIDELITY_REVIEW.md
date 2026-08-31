# `காட்சி—3` Assembly Fidelity Review — சாக்ரடீஸ்

## Scope

Controlling source context: `TVA_BOK_0065576_நான்மணி_மாலை.pdf`.

This audit tests assembled `scenes/03.md` against the **verified page record only**:

- `pages/0033.md` — scan 33 / printed p.28 — verified under the active Gemini-words / scan-typography rule.

For assembly, `pages/0033.md` is the sole textual authority. Gemini lexical wording is already locked in that verified page record; scan-controlled heading, punctuation, long dash, speaker-label spacing, physical line provenance and source marks were resolved upstream in `SCENE3_PAGE_VERIFICATION.md`.

## Scene result

| Scene | Verified page record | Physical scan | Printed page | Result |
|---|---|---:|---:|---|
| `காட்சி—3` | `0033.md` | 33 | 28 | **PASS** |

Assembled file: `scenes/03.md`.

## Assembly decisions

- Source heading `காட்சி—3.` is retained.
- All four stage directions are retained.
- Gemini lexical wording from the verified page record is retained exactly.
- Scan-controlled punctuation, speaker-label spacing and the long dash in `அறிவுத் தங்கத்தை — விடு` are retained.
- Only mechanical physical print-line breaks are removed for scene readability; no lexical rewriting is introduced.
- Scan 33 has **no closing `*`**; none is added to the assembled scene.
- Printed page number `28` is provenance metadata and is not imported into the dramatic scene body.

## Page-record ↔ scene matrix

| Scan | Printed page | Assembly comparison | Result |
|---:|---:|---|---|
| 33 | 28 | heading, market-stage direction, opening Socrates address, soldier entrance, all dialogue turns, pulling action, Crito intervention, final Socrates response and closing exit direction represented | PASS |

## Mechanical line-join checks

| Page-record evidence | Assembled reading | Decision |
|---|---|---|
| `என்` / `தோழர்கள்` | `என் தோழர்கள்` | physical line removed; lexical word boundary retained |
| `புத்துலகு` / `சமைப்போரின்` | `புத்துலகு சமைப்போரின்` | physical line removed; lexical word boundary retained |
| `காட்டுக்` / `குதிரையல்ல` | `காட்டுக் குதிரையல்ல` | physical line removed; lexical word boundary retained |
| `அடங்கி` / `ஒடுங்கிவிட!....` | `அடங்கி ஒடுங்கிவிட!....` | physical line removed; lexical word boundary retained |
| `விடு` / `வீரனே` | `விடு வீரனே` | physical line removed; lexical word boundary retained |
| `எங்கே` / `போகிறேன்?நீதிமன்றத்திற்குத்தானே!` | `எங்கே போகிறேன்?நீதிமன்றத்திற்குத்தானே!` | physical line removed; source punctuation adjacency retained |
| `கொலைக்களத்திற்கு` / `அல்லவே!....என்னைப்` | `கொலைக்களத்திற்கு அல்லவே!....என்னைப்` | physical line removed; lexical boundary retained |
| `தெளிவும்` / `கொள்கையிலே` | `தெளிவும் கொள்கையிலே` | physical line removed; lexical boundary retained |
| `விசாரணைக்கும்` / `வழக்கிற்கும்` | `விசாரணைக்கும் வழக்கிற்கும்` | physical line removed; lexical boundary retained |
| `அழிவுப்பா` / `தைக்கு` | `அழிவுப்பாதைக்கு` | mechanical print-line word join |
| `சந்` / `தித்துப்` | `சந்தித்துப்` | mechanical print-line word join |

## Speaker-label accounting

| Source label | Count in verified page record | Count in assembled scene | Result |
|---|---:|---:|---|
| `சாக் :` | 4 | 4 | PASS |
| `சிப்பாய் :` | 1 | 1 | PASS |
| `சிப் :` | 2 | 2 | PASS |
| `கிரி :` | 1 | 1 | PASS |

No speaker label is lost, added or regularized.

## Locked lexical controls

The assembled scene was checked specifically to retain Gemini lexical wording from the verified page record, including:

- `விந்தை மனிதர்காள்`;
- `விலை மதிக்கவொண்ணா வைரம்`;
- `பிர சங்கத்தை`;
- `தெகிடுதத்தம்`;
- `அதிகப்பிரசங்கியாரே`;
- `அறிவுத் தங்கத்தை`;
- `அழிவுப்பாதைக்கு` after mechanical joining of the physical split `அழிவுப்பா / தைக்கு`;
- `சந்தித்துப்` after mechanical joining of the physical split `சந் / தித்துப்`.

No assistant word correction is introduced.

## Scan-controlled non-lexical controls

The assembled scene retains the scan-resolved:

- `காட்சி—3.` heading;
- speaker-label spacing `சாக் :`, `சிப்பாய் :`, `சிப் :`, `கிரி :`;
- long dash in `அறிவுத் தங்கத்தை — விடு`;
- punctuation sequences including `வாங்கும்....விந்தை`, `பிர சங்கத்தை!........`, `கெடுக்கிறாய்;`, `போய்ச்சொல்....`, `ஒடுங்கிவிட!....`, `வயதில்....எங்கள்`, `விடு!....`, `வேண்டாம் ...!`, and `அல்லவே!....என்னைப்`;
- all stage directions;
- absence of a final `*`.

## Integrity checkpoint

- verified page records used: **1 / 1**;
- source-printed Scene 3 assembled: **1 / 1**;
- page-record → scene comparison: **PASS**;
- unresolved assembly discrepancies: **0**;
- speaker-label count mismatches: **0**;
- assistant lexical substitutions introduced: **0**;
- source punctuation/long-dash changes introduced: **0**;
- final `*` invented: **no**.

## Result

**PASS — `சாக்ரடீஸ்` `காட்சி—3` assembly and page-record fidelity gate are complete.**

The next distinct activity is page verification for **`காட்சி—4`**, beginning at scan **34** / printed p.29, under the active rule: Gemini supplies words; the scan controls heading, punctuation, long dash, speaker-label spacing, physical line boundaries and final source marks. Do not assemble `காட்சி—4` until its source pages are verified.
