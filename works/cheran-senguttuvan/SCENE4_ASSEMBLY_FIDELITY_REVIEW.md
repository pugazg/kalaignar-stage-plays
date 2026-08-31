# `காட்சி—4.` Assembly Fidelity Review — சேரன் செங்குட்டுவன்

## Scope

This audit tests assembled `scenes/04.md` against the two **verified Tamil page records only**:

- `pages/0052.md` — scan 52 / printed p.47 — Scene-4 opening;
- `pages/0053.md` — scan 53 / printed p.48 — Scene-4 closing.

The verified page records are the sole textual authority for assembly. No new scan reading, Gemini reconciliation, semantic correction, lexical normalization or English-witness reconstruction is introduced here.

## Scene result

| Scene | Verified page records | Physical scans | Printed pages | Result |
|---|---|---|---|---|
| `காட்சி—4.` | `0052.md`–`0053.md` | 52–53 | 47–48 | **PASS** |

Assembled file: `scenes/04.md`.

## Assembly decisions

- Source heading `காட்சி—4.` and setting `குயிலாலுவம்` are retained.
- The opening stage direction is assembled only by removing its physical print-line break: `நடை / பெற்ற` → `நடைபெற்ற`.
- Every verified speaker-label form and punctuation variant is retained exactly, including `சேர்:`, `சேர்;`, unusual `சேர்!`, `வில்லவன்:`, `வில்:`, `வில்!`, and `கன:`.
- All verified punctuation and locked source reconciliations from scans 52–53 are preserved unchanged.
- Only legitimate physical print-line and page-boundary joins are made.
- Printed page numbers remain provenance metadata and are not imported into the dramatic scene body.
- The centered final source mark `- * -` from scan 53 is retained exactly.
- The secondary 2009 English witness is not used to reconstruct Tamil.

## Page-record ↔ scene matrix

| Scan | Printed page | Assembly comparison | Result |
|---:|---:|---|---|
| 52 | 47 | heading, setting, opening stage direction and all dialogue through `கன: பதினெட்டு நாட்கள்!` represented | PASS |
| 53 | 48 | continuation from `சேர்: வீரர்களே...` through `சொல்—இப்போது தூக்கு கல்!` plus centered `- * -` represented | PASS |

## Page-boundary check — scan 52 → 53

- scan 52 ends: `கன: பதினெட்டு நாட்கள்!`
- scan 53 begins: `சேர்: வீரர்களே, நினைவிருக்கட்டும். சேரன் செங்குட்டுவன்`

This is a genuine new speaker turn. Assembly removes the physical page boundary only and does not merge the two utterances or invent bridge wording. **PASS**.

## Mechanical print-line joins checked

Representative joins audited against the verified page records:

- `நடை / பெற்ற` → `நடைபெற்ற`;
- `பெயர் / என்ன?` → `பெயர் என்ன?`;
- `விடக் / கூடாது.` → `விடக் கூடாது.`;
- `ஓடி / விட்டார்களாம்` → `ஓடி விட்டார்களாம்`;
- `கொண்டுவரப்படு / கிறார்கள்.` → `கொண்டுவரப்படுகிறார்கள்.`;
- `தாக்கு / வது—` → `தாக்குவது—`;
- `செங்குட்டுவன் / வடநாட்டிலே` → `செங்குட்டுவன் வடநாட்டிலே`;
- `நாழிகையில் / முடிந்துவிட்டது.` → `நாழிகையில் முடிந்துவிட்டது.`;
- `மண்ணில் / வந்து` → `மண்ணில் வந்து`;
- `புறப்பட்டு / முப்பத்திரண்டு` → `புறப்பட்டு முப்பத்திரண்டு`;
- `சிலை / நாட்ட` → `சிலை நாட்ட`;
- `எருதுகள் / கிடைத்து` → `எருதுகள் கிடைத்து`.

These are mechanical removal of physical print-line boundaries only. No lexical substitution is introduced.

## Speaker-label accounting

| Source label | Count in verified page records | Count in assembled scene | Result |
|---|---:|---:|---|
| `சேர்:` | 8 | 8 | PASS |
| `சேர்;` | 2 | 2 | PASS |
| `சேர்!` | 1 | 1 | PASS |
| `வில்லவன்:` | 1 | 1 | PASS |
| `வில்:` | 3 | 3 | PASS |
| `வில்!` | 1 | 1 | PASS |
| `கன:` | 4 | 4 | PASS |

No source label is normalized to another form.

## Locked source-reconciled controls retained

The assembled scene preserves the verified upstream decisions, including:

- `காட்சி—4.` and `குயிலாலுவம்`;
- source `கனக—விஜயருக்கும்` and the source-order opening stage direction;
- source `சேர்;` and `வில்!` label variants on scan 52;
- `காட்டுவது—முக்காடு போடுவது—மறைந்திருந்து தாக்குவது—மகானாய் மாறுவது.`;
- `ராம ராவணப் போர்?....`;
- scan-53 unusual `சேர்!` label;
- `புறப்படுவோம்—வில்லவா.`;
- `கனக—விஜயா`;
- `சொல்—இப்போது`;
- centered final source mark `- * -`.

## Integrity checkpoint

- verified page records used: **2 / 2**;
- source-printed Scene 4 assembled: **1 / 1**;
- page-record → scene comparison: **PASS**;
- unresolved assembly discrepancies: **0**;
- speaker-label count mismatches: **0**;
- assistant lexical substitutions introduced: **0**;
- English-witness reconstruction: **0**;
- final `- * -` retained: **yes**.

## Result

**PASS — `சேரன் செங்குட்டுவன்` `காட்சி—4.` assembly and page-record fidelity gate are complete.**

Durable Cheran state after this audit:

- Tamil pages verified: **10/10 COMPLETE**;
- Scene-1 assembly/fidelity: **PASS**;
- Scene-2 assembly/fidelity: **PASS**;
- Scene-3 assembly/fidelity: **PASS**;
- Scene-4 page gate: **2/2 COMPLETE**;
- Scene-4 assembly/fidelity: **PASS**;
- scenes assembled from verified Tamil: **4/4 COMPLETE**.

The next distinct source-sequential activity is **scan 54 / back-cover archival description only**. Do not begin another work in the same activity.
