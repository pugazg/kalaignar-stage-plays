# `காட்சி—4.` page verification — சேரன் செங்குட்டுவன்

## Scope

Controlling Tamil source: `TVA_BOK_0065576_நான்மணி_மாலை.pdf`.

The final scene spans scans **52–53** / printed pp. **47–48**.

Both source pages are now verified:

- scan **52** / printed p.47 — final-scene opening — `pages/0052.md`;
- scan **53** / printed p.48 — final-scene closing — `pages/0053.md`.

The final scene is not assembled in this activity.

## Result

| Scan | Printed page | Role | Result |
|---:|---:|---|---|
| 52 | 47 | `காட்சி—4.` opening | **PASS / verified** |
| 53 | 48 | `காட்சி—4.` closing | **PASS / verified** |

Final-scene page gate: **2/2 PASS / COMPLETE**.

## First-pass / source reconciliation

The user supplied a Gemini word-to-word first pass covering the Cheran source extent. It is the comparison baseline; the controlling Tamil scan remains authoritative under `STAGE_PLAY_PROCESSING_GUIDE.md`.

### Scan 52

Locked source controls include:

- source heading `காட்சி—4.` and setting `குயிலாலுவம்`;
- source-order opening direction `...கனக—விஜயருக்கும் நடை / பெற்ற போரில்...`;
- source speaker-label punctuation variants `சேர்:`, `வில்லவன்:`, `வில்:`, `சேர்;`, `வில்!`, and `கன:`;
- source long dashes in the stage direction and action sequence;
- source spacing `ராம ராவணப் போர்?....`;
- no closing `*` on scan 52.

### Scan 53

Unambiguous scan-53 structural/source differences retained in the canonical page record include:

| Gemini first pass | Controlling scan | Decision |
|---|---|---|
| `சேர:` | `சேர்:` | source label retained |
| second `சேர:` turn | `சேர்!` | unusual source label punctuation retained exactly |
| `சேர:புறப்படுவோம் - வில்லவா.` | `சேர்: புறப்படுவோம்—வில்லவா.` | source spacing + long dash retained |
| `வில் : ஆமாம்,` | `வில்: ஆமாம்,` | source label spacing retained |
| `கனக - விஜயா` | `கனக—விஜயா` | source long dash retained |
| `சொல்- இப்போது` | `சொல்—இப்போது` | source long dash/spacing retained |
| no closing mark represented in Gemini extraction | `- * -` | centered final source mark retained exactly |

No word is changed merely from modern spelling, grammar, semantic expectation or the English witness.

## Scan-controlled structure

- source heading and setting occur on scan 52;
- scan 53 continues the scene with source speaker-label punctuation retained exactly;
- physical print-line boundaries are preserved in both page records;
- printed page numbers `47` and `48` are represented separately;
- scan 52 has no closing `*`;
- scan 53 contains the centered final mark `- * -`.

## Integrity checkpoint

- source scans directly inspected: **2/2**;
- user-supplied first pass compared: **yes**;
- English witness used to reconstruct Tamil: **no**;
- final-scene page records verified: **2/2 COMPLETE**;
- total Cheran Tamil pages verified: **10/10 COMPLETE**;
- scenes assembled from controlling Tamil: **3/4**;
- final-scene assembly performed: **No**.

## Next activity

Assemble **`காட்சி—4.` only** from verified `pages/0052.md` and `pages/0053.md`, using those page records as the sole textual authority, then run the page-record ↔ scene fidelity audit. Preserve the scan-53 final `- * -` exactly. Do not process the back cover or begin another work in the same activity.
