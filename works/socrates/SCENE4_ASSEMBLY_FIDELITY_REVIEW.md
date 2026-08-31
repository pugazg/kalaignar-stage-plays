# `காட்சி—4` Assembly Fidelity Review — சாக்ரடீஸ்

## Scope

This audit tests assembled `scenes/04.md` against the six **verified page records only**:

- `pages/0034.md` — scan 34 / printed p.29;
- `pages/0035.md` — scan 35 / printed p.30;
- `pages/0036.md` — scan 36 / printed p.31;
- `pages/0037.md` — scan 37 / printed p.32;
- `pages/0038.md` — scan 38 / printed p.33;
- `pages/0039.md` — scan 39 / printed p.34.

The verified page records are the sole textual authority for assembly. No new scan reading, OCR reconciliation, semantic correction or lexical normalization is introduced here.

## Scene result

| Scene | Verified page records | Physical scans | Printed pages | Result |
|---|---|---|---|---|
| `காட்சி — 4` | `0034.md`–`0039.md` | 34–39 | 29–34 | **PASS** |

Assembled file: `scenes/04.md`.

## Assembly decisions

- Source heading `காட்சி — 4` is retained exactly.
- Setting `நீதிமன்றம்` and all stage directions are retained.
- Gemini lexical wording already locked into verified page records is retained.
- Scan-resolved punctuation, long dashes, speaker-label spacing, quote marks and final `*` are retained.
- Only legitimate physical print-line and page-boundary breaks are joined.
- Printed page numbers and scan-38 marginal mark `3` remain provenance metadata and are not imported into the dramatic scene body.
- The centered final `*` from scan 39 is retained.

## Page-boundary checks

| Boundary | Verified-page evidence | Assembly decision | Result |
|---|---|---|---|
| 34→35 | p.29 ends `நீதிமன்றத் தலைவர் : என்ன சிரிப்பு? என்ன காரணம்?`; p.30 begins `சாக் :` | separate speaker turn retained | PASS |
| 35→36 | p.30 ends Socrates question; p.31 begins `மெலி :` | separate reply retained | PASS |
| 36→37 | p.31 ends Socrates at `எண்ணங்கள்!........`; p.32 begins unlabeled continuation `அழகு மொழியால்...` | joined to same Socrates speech with a lexical space; source paragraph break inside the continuing speech otherwise preserved | PASS |
| 37→38 | p.32 ends `மரண தண்டனை`; p.33 begins unlabeled `கிடைத்திருக்கும், அப்போதே!` | joined as `மரண தண்டனை கிடைத்திருக்கும், அப்போதே!` | PASS |
| 38→39 | p.33 ends court verdict `வேண்டும்!`; p.34 begins `சாக்:` | separate speaker turn retained | PASS |

## Mechanical print-line joins checked

Representative joins were audited against the verified records:

- `பெஞ்சு / களில்` → `பெஞ்சுகளில்`;
- `பலகை / கள்` → `பலகைகள்`;
- `சாட்சி / களும்` → `சாட்சிகளும்`;
- `குற்றப்பத்திரி / கைகள்` → `குற்றப்பத்திரிகைகள்`;
- `குற்றப் பத்திரிகை- / களைக்` → `குற்றப் பத்திரிகைகளைக்`;
- `ஒத்துக்கொள்வ / தில்லை` → `ஒத்துக்கொள்வதில்லை`;
- `முயலு / கிறான்` → `முயலுகிறான்`;
- `இழிகுணக் / கிழவன்` → `இழிகுணக்கிழவன்`;
- `அனிடசுக் / கும்` → `அனிடசுக்கும்`;
- `விரும்பு / கிறேன்` → `விரும்புகிறேன்`;
- `வழக்கிற் / கும்` → `வழக்கிற்கும்`;
- `அவமதிக் / கிறான்` → `அவமதிக்கிறான்`;
- `கெடுத் / தான்` → `கெடுத்தான்`;
- `அலங் / காரம்` → `அலங்காரம்`;
- `இப் / படிப்பல` → `இப்படிப்பல`;
- `அனிட / சின்` → `அனிடசின்`;
- `அள / வுக்கு` → `அளவுக்கு`;
- `பார்க் / கட்டுமே` → `பார்க்கட்டுமே`;
- `துடி / யாய்த்` → `துடியாய்த்`;
- `சபை / யின்` → `சபையின்`;
- `தடை / யாக` → `தடையாக`;
- `அதி / காரிகளின்` → `அதிகாரிகளின்`;
- `என் / னுடைய` → `என்னுடைய`;
- `தண்டனை / யாக` → `தண்டனையாக`;
- `எனக் / கும்` → `எனக்கும்`;
- `வாக் / கெடுப்பு` → `வாக்கெடுப்பு`;
- `சாக்ர / டீஸின்` → `சாக்ரடீஸின்`;
- `சரித்திரத் / திலே` → `சரித்திரத்திலே`;
- `கிடைத்திருக் / கிறது` → `கிடைத்திருக்கிறது`;
- `கூறிய / தற்கு` → `கூறியதற்கு`;
- `ஆயிரக் / கணக்கான` → `ஆயிரக்கணக்கான`;
- `வாங்கப் / பட்டவை` → `வாங்கப்பட்டவை`;
- `காட்டி / லும்` → `காட்டிலும்`.

No lexical correction beyond these mechanical physical-line joins is introduced.

## Speaker-label accounting

| Source label | Count in verified page records | Count in assembled scene | Result |
|---|---:|---:|---|
| `அனி :` | 2 | 2 | PASS |
| `நீதிமன்றத் தலைவர் :` | 1 | 1 | PASS |
| `சாக் :` | 13 | 13 | PASS |
| `மெலி :` | 10 | 10 | PASS |
| `நீதி :` | 2 | 2 | PASS |
| `சார் :` | 1 | 1 | PASS |
| `நீதி:` | 2 | 2 | PASS |
| `சாக்:` | 1 | 1 | PASS |

No speaker label is added, lost or regularized.

## Locked lexical controls

The assembled scene specifically retains verified lexical forms including:

- `செடுக்கிறேனா`;
- `எல்லாரும்`;
- `இன்னும`;
- `கொன்றோம்என்ற`;
- `எனக்கேட்கலாம்`;
- `அபராதங்`;
- `என்னுடைய.சொந்த`;
- `எனதருமை ஏதென்ஸ் நகரத்தும்`;
- `விட்டர்கள்`;
- `களத்தில்`.

No assistant word-level substitution is introduced.

## Scan-resolved non-lexical controls retained

The assembled scene retains, among other verified forms:

- heading `காட்சி — 4`;
- `கட்சிக்காரர்களும் — அவர்களின் சாட்சிகளும்`;
- `சொற்களால்—கேளாரும்` and `வார்த்தைகளால்—சேடுமலியும்`;
- `அனிடஸ் — தன்னை`;
- `நினைத்தேன்—சிரித்தேன்`;
- `ஆமாம்—ஆமாம்!`;
- `இவ்வளவு பேரும்—ஏன்—ஏதென்சு`;
- `கருத்துக்கள் — தரங்குறையாத கொள்கைகள் — இந்தத்`;
- `மரணமா?........மன்னிப்பா?........`;
- quoted `“சங்கு”`, `‘மரணம்’`, `‘மன்னிப்பு’`;
- `281—220!........`;
- `மேன்மையானது!........`;
- `ஒரு மனிதன்—`;
- final centered `*`.

## Integrity checkpoint

- verified page records used: **6 / 6**;
- source-printed Scene 4 assembled: **1 / 1**;
- page-record → scene comparison: **PASS**;
- unresolved assembly discrepancies: **0**;
- speaker-label count mismatches: **0**;
- assistant lexical substitutions introduced: **0**;
- source punctuation/long-dash changes introduced: **0**;
- final `*` retained: **yes**.

## Result

**PASS — `சாக்ரடீஸ்` `காட்சி—4` assembly and page-record fidelity gate are complete.**

The next distinct activity is `காட்சி—5` page verification beginning at scan **40** / printed p.35 only. Do not assemble Scene 5 until its scans 40–43 are all verified.
