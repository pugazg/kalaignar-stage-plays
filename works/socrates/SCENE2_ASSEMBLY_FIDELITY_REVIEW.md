# `காட்சி—2` Assembly Fidelity Review — சாக்ரடீஸ்

## Scope

Controlling source context: `TVA_BOK_0065576_நான்மணி_மாலை.pdf`.

This audit tests assembled `scenes/02.md` against the **corrected verified page record only**:

- `pages/0032.md` — scan 32 / printed p.27 — verified after user-directed lexical rollback.

For assembly, `pages/0032.md` is the sole textual authority. Gemini lexical wording is already locked in that verified page record; scan-controlled heading, punctuation, long dash, speaker-label spacing, physical line provenance and final `*` were resolved upstream in `SCENE2_PAGE_VERIFICATION.md`.

## Scene result

| Scene | Verified page record | Physical scan | Printed page | Result |
|---|---|---:|---:|---|
| `காட்சி—2` | `0032.md` | 32 | 27 | **PASS** |

Assembled file: `scenes/02.md`.

## Assembly decisions

- Source heading `காட்சி—2.` is retained.
- The opening and closing stage directions are retained.
- Gemini lexical wording from the corrected verified page is retained exactly, including `கவிஞனாம் மெலிடசும்` and `அரசியல் நிபுணனாம் நீயும்`.
- Scan-controlled punctuation, source speaker-label spacing, `சாக்ரடீஸ்—சமுத்திரத்துத்` long dash, repetitions and final `*` are retained.
- Only mechanical physical print-line breaks are removed for scene readability; no lexical rewriting is introduced.

## Page-record ↔ scene matrix

| Scan | Printed page | Assembly comparison | Result |
|---:|---:|---|---|
| 32 | 27 | heading, opening direction, Anitus turn, Lycon turn, Meletus turn, closing direction and final `*` all represented | PASS |

## Mechanical line-join checks

| Page-record evidence | Assembled reading | Decision |
|---|---|---|
| `ஆழ்ந்த` / `யோசனையில்` | `ஆழ்ந்த யோசனையில்` | physical line removed; lexical word boundary retained |
| `இவைகளை` / `விடப்` | `இவைகளை விடப்` | physical line removed; lexical word boundary retained |
| `முடி` / `யாது` | `முடியாது` | mechanical print-line word join |
| `ஒரு` / `காலத்திலே` | `ஒரு காலத்திலே` | physical line removed; lexical word boundary retained |
| `மாறிவிட்` / `டான்` | `மாறிவிட்டான்` | mechanical print-line word join |
| `கவிஞ` / `னாம்` | `கவிஞனாம்` | mechanical print-line word join; Gemini lexical reading preserved |
| `கழுதை` / `களாயிருந்தால்தான்` | `கழுதைகளாயிருந்தால்தான்` | mechanical print-line word join |
| `பொய்மூட்டை` / `களைச்` | `பொய்மூட்டைகளைச்` | mechanical print-line word join |
| `கோட்` / `டைத்` | `கோட்டைத்` | mechanical print-line word join |
| `அழித்துவிட` / `வேண்டும்` | `அழித்துவிட வேண்டும்` | physical line removed; separate Gemini words retained |

## Speaker-label accounting

| Source label | Count in verified page record | Count in assembled scene | Result |
|---|---:|---:|---|
| `அனிடஸ் :` | 1 | 1 | PASS |
| `லைகன்:` | 1 | 1 | PASS |
| `மெலிடஸ் :` | 1 | 1 | PASS |

No speaker label is lost, added or regularized.

## Locked lexical controls

The assembled scene was checked specifically to retain the corrected user-directed Gemini words, including:

- `கவிஞனாம் மெலிடசும்`;
- `அரசியல் நிபுணனாம் நீயும்`.

The withdrawn assistant readings `கவிஞனும் மெலிடசும்` and `அரசியல் நிபுணனும் நீயும்` do not appear in the assembled scene.

## Scan-controlled non-lexical controls

The assembled scene retains the scan-resolved:

- `காட்சி—2.` heading;
- `அனிடஸ் :` / `லைகன்:` / `மெலிடஸ் :` speaker-label spacing;
- `சாக்ரடீஸ்—சமுத்திரத்துத்` long dash;
- punctuation runs from the corrected page record;
- opening and closing stage directions;
- final `*`.

## Integrity checkpoint

- verified page records used: **1 / 1**;
- source-printed Scene 2 assembled: **1 / 1**;
- page-record → scene comparison: **PASS**;
- unresolved assembly discrepancies: **0**;
- speaker-label count mismatches: **0**;
- assistant lexical substitutions introduced: **0**;
- withdrawn lexical readings reintroduced: **0**;
- final source `*` retained: **yes**.

## Result

**PASS — `சாக்ரடீஸ்` `காட்சி—2` assembly and page-record fidelity gate are complete.**

The next distinct activity is page verification of **`காட்சி—3` only**, scan **33** / printed p.28, under the active rule: Gemini supplies words; the scan controls heading, punctuation, long dash, speaker-label spacing, physical line boundaries and final source marks. Do not assemble `காட்சி—3` in the same activity.
