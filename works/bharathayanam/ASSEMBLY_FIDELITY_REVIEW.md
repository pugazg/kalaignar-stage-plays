# Assembly Fidelity Review — பரதாயணம்

## Scope

Controlling Tamil source: `TVA_BOK_0065576_நான்மணி_மாலை.pdf`.

This review tests the assembled continuous reading at `scenes/continuous-play.md` against the **verified page records only**:

- `pages/0006.md` through `pages/0017.md`;
- physical scans **6–17**;
- printed pages **—, 2–12**.

The Gemini first-pass transcription and the 2009 published-English witness are not assembly authorities.

## Assembly decision

`பரதாயணம்` has no source-printed numbered scene structure in this edition. The repository therefore uses `scenes/continuous-play.md` as a neutral assembled-reading path with `scene: null`; no editorial `காட்சி-1` or other invented scene heading is introduced.

Mechanical print-line and physical-page breaks may be removed in the assembled reading. Wording, punctuation, speaker labels, repetitions, lexical forms, and source anomalies may not be repaired or modernized.

## Page-record ↔ assembly matrix

| Scan | Printed page | Page-record status | Assembly comparison | Result |
|---:|---:|---|---|---|
| 6 | — | verified | title, opening note, `குறிப்பு`, full/abbreviated opening speaker labels and dialogue represented | PASS |
| 7 | 2 | verified | all dialogue represented; source speaker order retained | PASS |
| 8 | 3 | verified | all dialogue represented; page-final `கார` handled only at the 8→9 boundary | PASS |
| 9 | 4 | verified | all dialogue represented; initial `ணத்தால்` joined with scan 8; `நடத்து` and `இது தான்` retained | PASS |
| 10 | 5 | verified | all dialogue represented; `(கோபமாக) என்னு சொல்லு!` retained | PASS |
| 11 | 6 | verified | all dialogue represented; `கன்யா சுல்க`, `எப்படியம்மா?` and page-final `ஏற்றுக்` retained in provenance | PASS |
| 12 | 7 | verified | initial `கொள்கிறேன்` joined to the preceding phrase; `பட்டங் கட்டிவிட்டு` retained | PASS |
| 13 | 8 | verified | `இட்டது தான்`, `ஒரு நாடகம்`, Three-D / `திருடி` exchange retained | PASS |
| 14 | 9 | verified | Gemini-omitted `சிஷ் : சீதை........` retained; page-final `கூடாது` handled at 14→15 boundary | PASS |
| 15 | 10 | verified | anomalous `நீயல்ல` / `வர்` source sequence retained through mechanical join as `நீயல்லவர்`; page-final `பாதுகாப்` handled at 15→16 boundary | PASS |
| 16 | 11 | verified | initial `பாக` treated as second half of `பாதுகாப்பாக`, not as a speaker label; subsequent speaker sequence retained | PASS |
| 17 | 12 | verified | two consecutive `சிஷ்` labels, closing forms, `முற்றிற்று!`, and final `*` retained | PASS |

## Physical boundary checks

| Boundary | Page records | Assembled reading | Decision |
|---|---|---|---|
| scan 8 → 9 | `கார` / `ணத்தால்` | `காரணத்தால்` | mechanical word join only |
| scan 11 → 12 | `ஏற்றுக்` / `கொள்கிறேன்` | `ஏற்றுக் கொள்கிறேன்` | page break removed; lexical spacing retained |
| scan 14 → 15 | `கூடாது` / `அவன்தான்` | `கூடாது அவன்தான்` | sentence continuation with normal inter-word spacing |
| scan 15 → 16 | `பாதுகாப்` / `பாக` | `பாதுகாப்பாக` | mechanical word join; initial scan-16 `பாக` is **not** a label |
| scan 15 internal line break | `நீயல்ல` / `வர்` | `நீயல்லவர்` | mechanical line join only; **not** normalized to `நீயல்லவா` |

## Speaker-label accounting

Actual dialogue-label counts were compared between the verified page records and the assembled continuous reading:

| Label | Verified page records | Assembly |
|---|---:|---:|
| `பாகவதர் :` | 1 | 1 |
| `சிஷ்யன் :` | 1 | 1 |
| `பாக :` | 63 | 63 |
| `சிஷ் :` | 64 | 64 |

The counts match exactly. The scan-16 page-initial `பாக` is excluded from the `பாக :` count because the source itself has no colon there and it completes `பாதுகாப்பாக`.

## Targeted source-controlled forms

The assembled text was specifically checked to retain these verified readings:

- `நடத்து என்று பழமொழியே இருக்கிறது`;
- `(கோபமாக) என்னு சொல்லு!`;
- `கன்யா சுல்க`;
- `பட்டங் கட்டிவிட்டு`;
- `இட்டது தான்`;
- `ஒரு நாடகம்`;
- `சிஷ் : சீதை........`;
- `பாதுகாப்பாக ரதகஜதுரகபதாதிகளை`;
- `நீயல்லவர் தெய்வம்!` as the mechanical assembly of the source's `நீயல்ல` / `வர்`, without semantic repair;
- `மோக்ஷத்திற்குப்`;
- `மோட்சத்திற்கும்`;
- `மோசத்திற்கும்`;
- `நமப் பகுத்தறிவுபதே!`;
- `பரதாயணம் முற்றிற்று!`;
- final `*`.

## Integrity checkpoint

- verified source-page records used: **12 / 12**;
- page-record → assembly comparison: **PASS**;
- unresolved assembly discrepancies: **0**;
- speaker-label count mismatches: **0**;
- undocumented lexical substitutions: **0**;
- Gemini text imported over a verified page reading: **0**;
- published-English wording imported into Tamil: **0**;
- assembly SHA-256 at this checkpoint: `579582b2601cba7c366763a36ef68153331f07c8a8e15a0eef83baf4e4053750`.

## Result

**PASS — `பரதாயணம்` Tamil page verification and continuous-text assembly/fidelity gate are complete.**

The next repository activity is a new-work phase: begin `அனார்கலி` Tamil page verification at **scan 18 / printed page 13**. This review does not begin that work.
