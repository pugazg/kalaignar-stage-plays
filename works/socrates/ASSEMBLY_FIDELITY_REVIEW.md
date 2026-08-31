# Assembly Fidelity Review — சாக்ரடீஸ்

## Scope

Controlling Tamil source: `TVA_BOK_0065576_நான்மணி_மாலை.pdf`.

This review tests assembled `scenes/01.md` against the **final verified Tamil page records only**:

- `pages/0029.md` — scan 29 / printed p.24;
- `pages/0030.md` — scan 30 / printed p.25;
- `pages/0031.md` — scan 31 / printed p.26.

The Gemini first-pass and the 2009 published-English witness are not assembly authorities. Gemini/source adjudication was completed upstream in `SCENE1_PAGE_VERIFICATION.md`; this assembly uses those final page records as its sole literary-text input.

## Scene result

| Scene | Verified page records | Physical scans | Printed pages | Result |
|---|---|---:|---:|---|
| `காட்சி—1` | `0029.md`–`0031.md` | 29–31 | 24–26 | **PASS** |

Assembled file: `scenes/01.md`.

## Assembly decisions

- Source-printed heading `காட்சி—1.` and setting `சாக்ரடீசின் வீட்டு வாயில்` are retained.
- Mechanical print-line and physical-page breaks are removed for scene readability.
- Wording, punctuation, speaker labels, repetitions, stage directions, source-sensitive old-glyph readings and the closing `*` are not repaired or modernized.
- Scan 29→30 is one continuous Socrates utterance. Page 29 ends `...எனக்கு`; page 30 begins `வாய்த்த இளம் மனைவி...`; assembly renders `...எனக்கு வாய்த்த இளம் மனைவி...` without inserting a speaker label.
- `தின வெடுத்த` and `வாயிற்படியிலிருந்த படியே` retain inter-word spaces: the verified page records do not authorize silently fusing those line-boundary readings.

## Page-record ↔ scene matrix

| Scan | Printed page | Assembly comparison | Result |
|---:|---:|---|---|
| 29 | 24 | scene heading/setting, opening street direction, full public address, Xanthippe/Crito setup and page-final Socrates continuation represented | PASS |
| 30 | 25 | page-boundary continuation, Xanthippe/Socrates exchange, family complaint, youth/sun reply and repeated `சாகலாம் !` close represented | PASS |
| 31 | 26 | Xanthippe exit, Anitus/Meletus/Lycon passage, `“உன்னையே நீ அறிவாய்!”`, water-pouring action, Crito reaction, rain joke, final exit and `*` represented | PASS |

## Boundary and mechanical-join checks

| Location | Page-record evidence | Assembled reading | Decision |
|---|---|---|---|
| scan 29 | `போய்க்கொண்டிருக்` / `கிறார்கள்` | `போய்க்கொண்டிருக்கிறார்கள்` | mechanical print-line word join |
| scan 29 | `வாலிபர்` / `களே` | `வாலிபர்களே` | mechanical print-line word join |
| scan 29 | `காளை` / `யரே` | `காளையரே` | mechanical print-line word join |
| scan 29 | `போ` / `தாது` | `போதாது` | mechanical print-line word join |
| scan 29 | `இருட்டுமேனி` / `யும்` | `இருட்டுமேனியும்` | mechanical print-line word join |
| scan 29 | `மூழ்` / `கடித்து` | `மூழ்கடித்து` | mechanical print-line word join |
| scan 29 | `சாக்ர` / `டீசின்` | `சாக்ரடீசின்` | mechanical print-line word join |
| scan 29 | `போக்` / `கிலே` | `போக்கிலே` | mechanical print-line word join |
| scan 29→30 | `எனக்கு` / `வாய்த்த இளம் மனைவி...` | `எனக்கு வாய்த்த இளம் மனைவி...` | physical page break removed; normal inter-word space retained; no label added |
| scan 30 | `வருகிறவர்` / `களோடு` | `வருகிறவர்களோடு` | mechanical print-line word join |
| scan 30 | `விளக்கங்` / `களும்` | `விளக்கங்களும்` | mechanical print-line word join |
| scan 30 | `சுற்றியிருக்` / `கும்` | `சுற்றியிருக்கும்` | mechanical print-line word join |
| scan 30 | `உயிர்` / `களுக்கும்` | `உயிர்களுக்கும்` | mechanical print-line word join |
| scan 30 | `பேசிக்` / `கொண்டு` | `பேசிக்கொண்டு` | mechanical print-line word join |
| scan 30 | `விட்` / `டுவிடும்` | `விட்டுவிடும்` | mechanical print-line word join |
| scan 30 | `எவ்வ` / `ளவோ` | `எவ்வளவோ` | mechanical print-line word join |
| scan 31 | `இடையூறு` / `கள்` | `இடையூறுகள்` | mechanical print-line word join |
| scan 31 | `தர` / `மில்லை` | `தரமில்லை` | mechanical print-line word join |
| scan 31 | `இவர்` / `களெல்லாம்` | `இவர்களெல்லாம்` | mechanical print-line word join |
| scan 31 | `அதற்` / `காக` | `அதற்காக` | mechanical print-line word join |
| scan 31 | `அழைக்` / `கிறேன்` | `அழைக்கிறேன்` | mechanical print-line word join; occurs twice |
| scan 31 | `உபதேசத்` / `தின்` | `உபதேசத்தின்` | mechanical print-line word join |
| scan 31 | `உயிரினுமினியவர்` / `களே` | `உயிரினுமினியவர்களே` | mechanical print-line word join |
| scan 31 | `தண்ணீ` / `ரைக்` | `தண்ணீரைக்` | mechanical print-line word join |
| scan 31 | `எக்ஸேந்` / `திபி` | `எக்ஸேந்திபி` | mechanical print-line word join |

Non-fused source line-boundary readings deliberately retained in assembly:

- `தின` / `வெடுத்த` → `தின வெடுத்த`;
- `வாயிற்படியிலிருந்த` / `படியே` → `வாயிற்படியிலிருந்த படியே`.

## Speaker-label accounting

| Source label | Count in verified page records | Count in assembled scene | Result |
|---|---:|---:|---|
| `சாக்ரடீஸ் :` | 1 | 1 | PASS |
| `சாக் :` | 5 | 5 | PASS |
| `எக்ஸேந்திபி :` | 1 | 1 | PASS |
| `எக்ஸ்:` | 2 | 2 | PASS |
| `கிரிட்டோ :` | 1 | 1 | PASS |

No source dialogue label is lost or introduced.

## Targeted source-controlled forms

The assembled scene was specifically checked to retain the final page-gate readings, including:

- `கச்சைக்கட்டிக்`;
- `ஈட்டியும்மாத்திரம்`;
- `மடமைப் பைசாசத்தை`;
- `புறங் காணா`;
- `புலிநிகர்`;
- `என்னோடு-புறப்படுங்கள்!`;
- `படை எதுவுமின்றி!.....`;
- `இரண்டாம்தாரம்`;
- `விழிகளா அவைகள் ?`;
- `மின்னலப்பா ;`;
- `இந்தக் கிண்ணாரக் கிழவருக்கு`;
- `கஷ்டப்பட`;
- `நட்டாற்றில்`;
- `ஏண்டி`;
- `சுடுகாடு`;
- `அனிடஸ்`, `மெலிடஸ்`, `லைகன்`;
- `முளைக்கக்`;
- `புவனமறியாததல்ல`;
- `கீறல்களை`;
- `சிரந்தாழ்த்தி`;
- `உயிரினுமினியவர்களே`;
- `“உன்னையே நீ அறிவாய்!”`;
- the water-pouring stage direction;
- the final source `*`.

Withdrawn preliminary assistant readings documented in `SCENE1_PAGE_VERIFICATION.md` were not reintroduced.

## Integrity checkpoint

- verified source-page records used: **3 / 3**;
- source-printed Scene 1 assembled: **1 / 1**;
- page-record → scene comparison: **PASS**;
- page-boundary continuation errors: **0**;
- unresolved assembly discrepancies: **0**;
- speaker-label count mismatches: **0**;
- undocumented lexical substitutions: **0**;
- Gemini wording imported over final verified Tamil: **0**;
- published-English wording imported into Tamil: **0**.

## Result

**PASS — `சாக்ரடீஸ்` `காட்சி—1` assembly and page-record fidelity gate are complete.**

The next distinct activity is page verification of **`காட்சி—2` only**, scan **32** / printed p.27. That page is not processed in this activity.
