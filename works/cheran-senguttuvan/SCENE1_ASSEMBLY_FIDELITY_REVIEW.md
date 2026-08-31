# `காட்சி — 1` Assembly Fidelity Review — சேரன் செங்குட்டுவன்

## Scope

This audit tests assembled `scenes/01.md` against the two **verified Tamil page records only**:

- `pages/0044.md` — scan 44 / printed p.39 — work opening + Scene-1 opening;
- `pages/0045.md` — scan 45 / printed p.40 — Scene-1 continuation/closing.

The verified page records are the sole textual authority for assembly. No new scan reading, Gemini reconciliation, semantic correction, lexical normalization or English-witness reconstruction is introduced here.

## Scene result

| Scene | Verified page records | Physical scans | Printed pages | Result |
|---|---|---|---|---|
| `காட்சி — 1` | `0044.md`–`0045.md` | 44–45 | 39–40 | **PASS** |

Assembled file: `scenes/01.md`.

## Assembly decisions

- The work-opening pre-scene voice-over from scan 44 is retained before the scene heading.
- Source heading `காட்சி — 1` is retained.
- All verified wording, punctuation and speaker-label variants are retained.
- Only legitimate physical print-line boundaries are removed for scene readability.
- Printed page numbers remain provenance metadata and are not imported into the dramatic scene body.
- Neither verified page contains a printed scene-closing `*`; none is invented in the assembled scene.
- The secondary 2009 English witness is not used to reconstruct Tamil.

## Page-record ↔ scene matrix

| Scan | Printed page | Assembly comparison | Result |
|---:|---:|---|---|
| 44 | 39 | pre-scene voice-over, `காட்சி — 1` heading, opening proclamation and all speaker turns through `விஜ. யாரப்பா நீ? என்ன பேசுகிறாய்?` represented | PASS |
| 45 | 40 | all continuation turns from `புல: தமிழ்! செந்தமிழ்!...` through `சேரன் செங்குட்டுவன்!!` represented | PASS |

## Page-boundary check

The scan-44 → scan-45 boundary contains **no continued utterance**:

- scan 44 ends: `விஜ. யாரப்பா நீ? என்ன பேசுகிறாய்?`
- scan 45 begins: `புல: தமிழ்! செந்தமிழ்!...`

The assembled scene therefore preserves these as separate speaker turns with no invented bridge text. **PASS**.

## Mechanical print-line joins checked

Representative joins audited against the verified page records:

- `கல் / கொண்டு` → `கல் கொண்டு`;
- `வீர / வரிகள்` → `வீர வரிகள்`;
- `கொண்டிருக் / கிறீர்கள்` → `கொண்டிருக்கிறீர்கள்`;
- `சுயம்வரப் / போட்டியில்` → `சுயம்வரப் போட்டியில்`;
- `பங்கு போட்டுக் / கொள்வது` → `பங்கு போட்டுக் கொள்வது`;
- `மண்ட / பத்தில்` → `மண்டபத்தில்`;
- `தூக்கத் / தெரியாத` → `தூக்கத் தெரியாத`;
- `திரும்பு / கிறேன்` → `திரும்புகிறேன்`;
- `பித்து / மனம்` → `பித்து மனம்`;
- `செங்குட் / டுவன்` → `செங்குட்டுவன்`.

These are mechanical removal of physical print-line boundaries only. No lexical substitution is introduced.

## Speaker-label accounting

| Source label | Count in verified page records | Count in assembled scene | Result |
|---|---:|---:|---|
| `மன்னர்கள்:` | 2 | 2 | PASS |
| `கனகர்:` | 1 | 1 | PASS |
| `விஜயர்:` | 1 | 1 | PASS |
| `கன:` | 4 | 4 | PASS |
| `மன்:` | 1 | 1 | PASS |
| `தமிழ்நாட்டுப் புலவர்:` | 1 | 1 | PASS |
| `விஜ.` | 1 | 1 | PASS |
| `விஜ:` | 3 | 3 | PASS |
| `புல:` | 6 | 6 | PASS |

No speaker label is added, lost or regularized.

## Locked source-reconciled controls retained

The assembled scene retains the verified source decisions already locked upstream, including:

- `வேந்தர்குலதிலக`;
- `கனக விஜயர்`;
- no stray standalone `ழ்!` after `செந்தமிழ்!`;
- `புல:` before the poem;
- `தமிழன்!` inside the following `கன:` speech rather than as a separate turn;
- `விஜ: கனகர் சொன்னது...`;
- source long dashes in `தமிழ்ப்புலவன்—வடநாட்டு`, `புலவன்—கத்தி`, `வீரன்—இவர்களைத்`, `போராடினான்—தமிழன்`, `ஆண்டான்—தமிழன்`, and `புலி—வில்—கயல்`.

## Integrity checkpoint

- verified page records used: **2 / 2**;
- source-printed Scene 1 assembled: **1 / 1**;
- page-record → scene comparison: **PASS**;
- unresolved assembly discrepancies: **0**;
- speaker-label count mismatches: **0**;
- assistant lexical substitutions introduced: **0**;
- English-witness reconstruction: **0**;
- invented closing `*`: **no**.

## Result

**PASS — `சேரன் செங்குட்டுவன்` `காட்சி — 1` assembly and page-record fidelity gate are complete.**

Durable Cheran state after this audit:

- Tamil pages verified: **2/10**;
- Scene-1 page gate: **2/2 COMPLETE**;
- scenes assembled from verified Tamil: **1/4**.

The next distinct source-sequential activity is **scan 46 / printed p.41 page verification only**, the opening page of `காட்சி — 2`. Do not process scan 47 or assemble Scene 2 in the same activity.
