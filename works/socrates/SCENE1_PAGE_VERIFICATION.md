# `காட்சி—1` page verification — சாக்ரடீஸ்

## Scope

Controlling Tamil source: `TVA_BOK_0065576_நான்மணி_மாலை.pdf`.

- source scans: **29–31**;
- printed pages: **24–26**;
- page records: `pages/0029.md` through `pages/0031.md`;
- source-printed scene: **`காட்சி—1`**;
- setting: **`சாக்ரடீசின் வீட்டு வாயில்`**.

This record documents the page-verification activity. The downstream assembly is now complete at `scenes/01.md`; its page-record fidelity audit is `ASSEMBLY_FIDELITY_REVIEW.md`.

## Reconciliation history

A preliminary live page-gate commit was created before the user supplied the original Gemini first-pass segment for scans 29–31. After the user supplied that baseline, all three scans were re-opened and compared again under the permanent old-glyph rule.

The later reconciliation is controlling. Assistant substitutions made by familiarity/expectation were withdrawn wherever the Gemini reading remained plausible and the scan did not unambiguously support the substitution.

## Result

| Scan | Printed page | Role | Result |
|---:|---:|---|---|
| 29 | 24 | Scene 1 opening | PASS / verified |
| 30 | 25 | Scene 1 continuation | PASS / verified |
| 31 | 26 | Scene 1 closing | PASS / verified |

`காட்சி—1` source pages: **3/3 verified**.

## Boundary control

Scan 29 ends Socrates' utterance at:

`...கடமையிலே விரைந்து நடக்கிறேன் நான்!.... எனக்கு`

Scan 30 begins:

`வாய்த்த இளம் மனைவி, இரண்டாம்தாரம்....எக்ஸேந்திபி, ...`

This is one continuous utterance across the physical page boundary. The page records preserve that break. The assembled scene removes the physical page break mechanically as `...எனக்கு வாய்த்த இளம் மனைவி...`, without inserting a speaker label or altering the wording.

## Old-glyph / source-sensitive controls

The re-review followed `STAGE_PLAY_PROCESSING_GUIDE.md` §1A: Gemini is a comparison baseline; a plausible old-glyph reading is not replaced by modern spelling, semantic expectation, proper-name familiarity or grammar unless the controlling scan is unambiguous.

Final controlled readings include:

- scan 29: `சாக்ரடீசின் வீட்டு வாயில்`, `கச்சைக்கட்டிக்`, `ஈட்டியும்மாத்திரம்`, `மடமைப் பைசாசத்தை`, `காணா`, `புலிநிகர்`, `என்னோடு-புறப்படுங்கள்!`;
- scan 30: `இரண்டாம்தாரம்`, `விழிகளா அவைகள் ?`, `மின்னலப்பா ;`, `இந்தக் கிண்ணாரக் கிழவருக்கு`, `கஷ்டப்பட`, `நட்டாற்றில்`, `ஏண்டி`, `சுடுகாடு`, source label variation `எக்ஸேந்திபி :` / `சாக் :` / `எக்ஸ்:`;
- scan 31: `அனிடஸ்`, `மெலிடஸ்`, `லைகன்`, `முளைக்கக்`, `புவனமறியாததல்ல`, `கீறல்களை`, `சிரந்தாழ்த்தி`, `உயிரினுமினியவர்`, the water-pouring stage direction and final `*`.

### Withdrawn preliminary assistant substitutions

These readings from the preliminary live page-gate pass are not controlling and must not be reintroduced without new unambiguous scan evidence:

| Preliminary assistant reading | Final Gemini/source-controlled reading |
|---|---|
| `காண` | `காணா` |
| `புவிநிகர்` | `புலிநிகர்` |
| `மின்னல்பா` | `மின்னலப்பா` |
| `இந்தத் திண்ணைக் கிழவனுக்கு` | `இந்தக் கிண்ணாரக் கிழவருக்கு` |
| `கஷ்டப்பட்ட` | `கஷ்டப்பட` |
| `நடுத்தெருவில்` | `நட்டாற்றில்` |
| `ஏனடி` | `ஏண்டி` |

### Genuine Gemini/source discrepancies proved by the scan

These are changes to the supplied first-pass that are directly supported by the controlling scan rather than by assistant expectation:

| Scan | Gemini first-pass | Controlling scan |
|---:|---|---|
| 29 | `காட்சி-1.` | `காட்சி—1.` |
| 29 | `என்னோடு - புறப்படுங்கள்!` | `என்னோடு-புறப்படுங்கள்!` |
| 29 | `படை எதுவுமின்றி.....` | `படை எதுவுமின்றி!.....` |
| 30 | `இருந்தால்.` | `இருந்தால்,` |
| 30 | `சுடுசாடு` | `சுடுகாடு` |
| 31 | `உயிரினு மினியவர்` | `உயிரினுமினியவர்` |

Scan-visible punctuation sequences on scan 31 are also preserved from the image where the first-pass flattened or shortened them, including `போன்றது ! .......`, `கிரிட்டோ ! ....`, `மழையும் பெய்கிறது.....`, and `அவ்வளவுதான் !.....`.

No published-English wording was used to reconstruct Tamil.

## Integrity checkpoint

- source pages examined directly after receipt of the Gemini baseline: **3/3**;
- page records re-reconciled and verified: **3/3**;
- unresolved page-level readings: **0**;
- page-boundary continuation documented: **1** (29→30);
- scene assembly performed in the original page-verification activity: **No**;
- downstream `scenes/01.md` assembly: **PASS**;
- downstream page-record ↔ scene audit: **PASS** (`ASSEMBLY_FIDELITY_REVIEW.md`).

## Next activity

Verify **`காட்சி—2` only**, scan **32** / printed p.27, under the same source/Gemini old-glyph rule. Do not begin `காட்சி—3` or `சேரன் செங்குட்டுவன்` in that activity.
