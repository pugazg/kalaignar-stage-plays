# `காட்சி — 2` Assembly Fidelity Review — சேரன் செங்குட்டுவன்

## Scope

This audit tests assembled `scenes/02.md` against the four **verified Tamil page records only**:

- `pages/0046.md` — scan 46 / printed p.41 — Scene-2 opening;
- `pages/0047.md` — scan 47 / printed p.42 — continuation;
- `pages/0048.md` — scan 48 / printed p.43 — continuation;
- `pages/0049.md` — scan 49 / printed p.44 — closing.

The verified page records are the sole textual authority for assembly. No new scan reading, Gemini reconciliation, semantic correction, lexical normalization or English-witness reconstruction is introduced here.

## Scene result

| Scene | Verified page records | Physical scans | Printed pages | Result |
|---|---|---|---|---|
| `காட்சி — 2` | `0046.md`–`0049.md` | 46–49 | 41–44 | **PASS** |

Assembled file: `scenes/02.md`.

## Assembly decisions

- Source heading `காட்சி — 2`, setting `சேரனின் மண்டபம்`, opening stage direction and all verified speaker-label forms are retained.
- All locked source reconciliations from the four verified page records are preserved unchanged.
- Only legitimate physical print-line and page-boundary joins are made.
- Verse/prose grouping already represented in the verified page records is retained where it carries readable source structure.
- Printed page numbers remain provenance metadata and are not imported into the dramatic scene body.
- None of scans 46–49 contains a printed closing `*`; none is invented in `scenes/02.md`.
- The secondary 2009 English witness is not used to reconstruct Tamil.

## Page-record ↔ scene matrix

| Scan | Printed page | Assembly comparison | Result |
|---:|---:|---|---|
| 46 | 41 | heading, setting, opening dialogue and recitation through `“இல்லை அன்பே!”` represented | PASS |
| 47 | 42 | continuation from `முல்லைசூழ்...` through `ஏனந்த மனிதன் வந்தானோ?` represented | PASS |
| 48 | 43 | continuation from `இழவுச் சேதி சொல்வதற்கு!` through page-ending `என்றான்—` represented | PASS |
| 49 | 44 | continuation from `“திரும்பிவந்து...` through final `வருகிறேன்!` represented | PASS |

## Page-boundary checks

### Scan 46 → 47

- scan 46 ends: `“இல்லை அன்பே!”`
- scan 47 begins: `முல்லைசூழ் இந்நாட்டுப் படையிலோர் வீரர் குறைந்திட்டால்`

There is no new speaker label. Assembly keeps the continuous recitation and introduces no bridge wording. **PASS**.

### Scan 47 → 48

- scan 47 ends: `ஏனந்த மனிதன் வந்தானோ?`
- scan 48 begins: `இழவுச் சேதி சொல்வதற்கு!`

Assembly joins this rhetorical continuation as `ஏனந்த மனிதன் வந்தானோ? இழவுச் சேதி சொல்வதற்கு!` without changing either source phrase. **PASS**.

### Scan 48 → 49

- scan 48 ends: `“அப்பா, தாத்தா, ஊர் திரும்பினாரோ?” என்றான்—`
- scan 49 begins: `“திரும்பிவந்து சாவூர் சென்று விட்டார்—`

Assembly removes only the physical page boundary, yielding the source-continuous `என்றான்—“திரும்பிவந்து...` sequence. No word or punctuation is inserted. **PASS**.

## Mechanical print-line joins checked

Representative joins audited against the verified page records:

- `இந்தச் / சிலையை` → `இந்தச் சிலையை`;
- `தன் மகனை / யும்` → `தன் மகனையும்`;
- `போர்ச் செய்தி / தந்திட்டாள்` → `போர்ச் செய்தி தந்திட்டாள்`;
- `தழை / உதிர்ந்துவிட்ட` → `தழை உதிர்ந்துவிட்ட`;
- `ரத்தக் / காவி` → `ரத்தக் காவி`;
- `படை / யெடுத்தோமாம்` → `படையெடுத்தோமாம்`;
- `வீரத் / துக்குச்` → `வீரத்துக்குச்`.

These are mechanical removal of physical print-line boundaries only. No lexical substitution is introduced.

## Speaker-label accounting

| Source label | Count in verified page records | Count in assembled scene | Result |
|---|---:|---:|---|
| `வேண்:` | 6 | 6 | PASS |
| `சேரன்:` | 5 | 5 | PASS |
| `புலவர்:` | 1 | 1 | PASS |
| `சேர:` | 5 | 5 | PASS |
| `புல:` | 5 | 5 | PASS |

No speaker label is added, lost or regularized.

## Locked source-reconciled controls retained

The assembled scene preserves the verified upstream decisions, including:

- scan 46 source placement of `ஓர் களத்தில்,` immediately after `அந்நாளில்`;
- old-glyph reading represented physically as `தன் மகனை / யும்`, mechanically joined only at assembly;
- scan 47 `“நடந்திடுக கண்ணே” என்றாள்!`, source long dashes, `பார்! பார்! பார்!`, and `வாழ்த்துகள் வழங்கினர்!`;
- scan 48 `சாவிலே வீழ்ந்துவிட்டான்—`, `மண் தானே?`, `கண் தானே?`, `தமிழ்நாட்டுமாதரசு`, and retained plausible `சோகத்தாள்`;
- scan 49 separate source `பூண்டார்!`, plus `வெள்ளிமாடத்திற்கு`, `வந்திருக்கிறேனே`, `காலத்திலே`, and source label/punctuation forms;
- no closing `*`.

## Integrity checkpoint

- verified page records used: **4 / 4**;
- source-printed Scene 2 assembled: **1 / 1**;
- page-record → scene comparison: **PASS**;
- unresolved assembly discrepancies: **0**;
- speaker-label count mismatches: **0**;
- assistant lexical substitutions introduced: **0**;
- English-witness reconstruction: **0**;
- invented closing `*`: **no**.

## Result

**PASS — `சேரன் செங்குட்டுவன்` `காட்சி — 2` assembly and page-record fidelity gate are complete.**

Durable Cheran state after this audit:

- Tamil pages verified: **6/10**;
- Scene-1 assembly/fidelity: **PASS**;
- Scene-2 page gate: **4/4 COMPLETE**;
- Scene-2 assembly/fidelity: **PASS**;
- scenes assembled from verified Tamil: **2/4**.

The next distinct source-sequential activity is **scan 50 / printed p.45 page verification only**, the opening page of `காட்சி—3.`. Do not process scan 51 or assemble Scene 3 in the same activity.
