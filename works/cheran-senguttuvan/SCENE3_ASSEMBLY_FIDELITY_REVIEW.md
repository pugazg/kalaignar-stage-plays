# `காட்சி—3.` Assembly Fidelity Review — சேரன் செங்குட்டுவன்

## Scope

This audit tests assembled `scenes/03.md` against the two **verified Tamil page records only**:

- `pages/0050.md` — scan 50 / printed p.45 — Scene-3 opening;
- `pages/0051.md` — scan 51 / printed p.46 — Scene-3 closing.

The verified page records are the sole textual authority for assembly. No new scan reading, Gemini reconciliation, semantic correction, lexical normalization or English-witness reconstruction is introduced here.

## Scene result

| Scene | Verified page records | Physical scans | Printed pages | Result |
|---|---|---|---|---|
| `காட்சி—3.` | `0050.md`–`0051.md` | 50–51 | 45–46 | **PASS** |

Assembled file: `scenes/03.md`.

## Assembly decisions

- Source heading `காட்சி—3.` and setting `சேரன் கொலுமண்டபம்` are retained.
- Source speaker-label forms `சேரன்:` and `ஒரு அமைச்சர் :` are retained exactly.
- Scan 51 is assembled as a direct continuation of the second `சேரன்:` speech from scan 50; no new speaker label is inserted.
- All verified punctuation and locked source reconciliations from scans 50–51 are preserved unchanged.
- Only legitimate physical print-line and page-boundary joins are made.
- Printed page numbers remain provenance metadata and are not imported into the dramatic scene body.
- The centered closing `*` from scan 51 is retained exactly.
- The secondary 2009 English witness is not used to reconstruct Tamil.

## Page-record ↔ scene matrix

| Scan | Printed page | Assembly comparison | Result |
|---:|---:|---|---|
| 50 | 45 | heading, setting, first `சேரன்:` speech, `ஒரு அமைச்சர் :` turn and second `சேரன்:` speech through `உம்மையெல்லாம் இகழ்ந்தார்கள்!` represented | PASS |
| 51 | 46 | continuation from `இகழ்ந்தார்கள்! இகழ்ந்தவர்கள்!...` through `தோழர்களே! ....புறப்படுங்கள்!` plus centered `*` represented | PASS |

## Page-boundary check — scan 50 → 51

- scan 50 ends: `கவிஞரே! கலைவாணரே! உம்மையெல்லாம் இகழ்ந்தார்கள்!`
- scan 51 begins: `இகழ்ந்தார்கள்! இகழ்ந்தவர்கள்! இகழ்ந்தவர்கள் உயிரோடு`

There is no new speaker label. Assembly removes only the physical page boundary and keeps the same `சேரன்:` speech continuous as `...உம்மையெல்லாம் இகழ்ந்தார்கள்! இகழ்ந்தார்கள்! இகழ்ந்தவர்கள்!...`. No bridge wording is inserted. **PASS**.

## Mechanical print-line joins checked

Representative joins audited against the verified page records:

- `வேங்கைப் / புலிகளே` → `வேங்கைப் புலிகளே`;
- `கேட்ட / றியாக்` → `கேட்டறியாக்`;
- `விடுத்தார் / களாம்` → `விடுத்தார்களாம்`;
- `இருக்க / லாம்` → `இருக்கலாம்`;
- `சாத்த / னாரே` → `சாத்தனாரே`;
- `இகழ்ந்தார் / கள்` → `இகழ்ந்தார்கள்`;
- `நெடுஞ்சேரலா / தனின்` → `நெடுஞ்சேரலாதனின்`;
- `சாகப் / பயப்படும்` → `சாகப் பயப்படும்`;
- `தட்டுங் / கள்!` → `தட்டுங்கள்!`.

These are mechanical removal of physical print-line boundaries only. No lexical substitution is introduced.

The verified source spacing `வேட்ட / மங்கலம்` is conservatively assembled as `வேட்ட மங்கலம்`; no expectation-based place-name compounding is introduced.

## Speaker-label accounting

| Source label | Count in verified page records | Count in assembled scene | Result |
|---|---:|---:|---|
| `சேரன்:` | 2 | 2 | PASS |
| `ஒரு அமைச்சர் :` | 1 | 1 | PASS |

Scan 51 has no new speaker label, and none is invented.

## Locked source-reconciled controls retained

The assembled scene preserves the verified upstream decisions, including:

- `காட்சி—3.` and `சேரன் கொலுமண்டபம்`;
- `உத்திரனும்—விசித்திரனும்—சித்தரனும்—சிவேதனும்—பைரவனும்!`;
- `கனகனும்விசயனும்`;
- source short spaced hyphen `வீணன் - கயலைப்`;
- retained plausible old-glyph `காணா`;
- `வள்ளுவனே!`, `முல்லைக் கொல்லையே!`, `நெடுஞ்செழியனே!`;
- scan-51 source long dashes after `தளபதியாயிருக்க`, `பிறையாயிருக்க`, and `கூச்சலிட்டதாம்`;
- `நதியும், பொழிலும்`;
- `இல்லை!....இல்லை!..`;
- `தோழர்களே! ....புறப்படுங்கள்!`;
- centered closing `*`.

## Integrity checkpoint

- verified page records used: **2 / 2**;
- source-printed Scene 3 assembled: **1 / 1**;
- page-record → scene comparison: **PASS**;
- unresolved assembly discrepancies: **0**;
- speaker-label count mismatches: **0**;
- assistant lexical substitutions introduced: **0**;
- English-witness reconstruction: **0**;
- closing `*` retained: **yes**.

## Result

**PASS — `சேரன் செங்குட்டுவன்` `காட்சி—3.` assembly and page-record fidelity gate are complete.**

Durable Cheran state after this audit:

- Tamil pages verified: **8/10**;
- Scene-1 assembly/fidelity: **PASS**;
- Scene-2 assembly/fidelity: **PASS**;
- Scene-3 page gate: **2/2 COMPLETE**;
- Scene-3 assembly/fidelity: **PASS**;
- scenes assembled from verified Tamil: **3/4**.

The next distinct source-sequential activity is **scan 52 / printed p.47 page verification only**, opening the final scene. Do not process scan 53 or assemble the final scene in the same activity.
