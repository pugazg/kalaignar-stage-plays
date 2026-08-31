# `காட்சி—4` page verification — சாக்ரடீஸ்

## Scope

Controlling Tamil source: `TVA_BOK_0065576_நான்மணி_மாலை.pdf`.

Scene-4 extent: scans **34–39** / printed pp.29–34.

Verified page records:

- scan **34** / p.29 — opening — `pages/0034.md`;
- scan **35** / p.30 — continuation — `pages/0035.md`;
- scan **36** / p.31 — continuation — `pages/0036.md`;
- scan **37** / p.32 — continuation — `pages/0037.md`;
- scan **38** / p.33 — continuation / verdict — `pages/0038.md`;
- scan **39** / p.34 — closing — `pages/0039.md`.

No Scene-4 assembly is performed in the scan-39 activity.

## Result

| Scan | Printed page | Role | Result |
|---:|---:|---|---|
| 34 | 29 | `காட்சி—4` opening | **PASS / verified** |
| 35 | 30 | continuation | **PASS / verified** |
| 36 | 31 | continuation | **PASS / verified** |
| 37 | 32 | continuation | **PASS / verified** |
| 38 | 33 | continuation / verdict | **PASS / verified** |
| 39 | 34 | closing | **PASS / verified** |

`காட்சி—4` source-page gate: **6/6 PASS / complete**.

## User-directed lexical / visual rule

For all Scene-4 page records:

- **words:** retain the supplied Gemini first-pass;
- **scan:** use direct visual evidence for headings where present, punctuation, long dash, speaker-label spacing, physical line boundaries and final source marks.

No assistant lexical normalization is introduced from spelling familiarity, grammar, semantics or name familiarity.

## Scan 39 controls

The closing page retains Gemini lexical wording while taking non-lexical evidence from the controlling scan.

- speaker-label spacing: `சாக்:` with no space before the colon;
- opening source quote before `அறிவு` retained as punctuation;
- `281—220!........` retained from the scan, replacing Gemini's OCR-like punctuation rendering without changing the lexical numbers;
- `மேன்மையானது!........` retained from the scan;
- long dash retained at `ஒரு மனிதன்—`;
- physical source lines retained, including `சரித்திரத் / திலே`, `கிடைத்திருக் / கிறது`, `கூறிய / தற்கு`, `ஆயிரக் / கணக்கான`, `வாங்கப் / பட்டவை`, and `காட்டி / லும்`;
- Gemini lexical forms such as `விட்டர்கள்` and `களத்தில்` remain unchanged under the active user rule;
- centered scene-closing `*` is present and preserved;
- centered printed page number `34` is represented separately from the dramatic text.

## Integrity checkpoint

- source scans directly inspected for Scene 4: **6/6**;
- Gemini lexical baseline retained: **yes**;
- assistant lexical substitutions introduced in scan-39 activity: **0**;
- page records verified: **6/6**;
- Scene-4 pages verified: **6/6 PASS**;
- total Socrates pages verified: **13/17**;
- dramatic-body pages verified: **11/15**;
- scenes assembled: **3/5**;
- Scene-4 assembly performed: **No**;
- `காட்சி—5` processed: **No**.

## Next activity

Assemble **`காட்சி—4` only** from verified `pages/0034.md` through `pages/0039.md`, using those verified page records as the sole textual authority. Mechanically join legitimate physical print-line/page-boundary breaks, preserve wording/punctuation/labels/stage directions/source marks, then run a page-record ↔ scene fidelity audit. Do not begin `காட்சி—5` in the same activity.
