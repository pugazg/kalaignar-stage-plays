# `காட்சி—5` page verification — சாக்ரடீஸ்

## Scope

Controlling Tamil source: `TVA_BOK_0065576_நான்மணி_மாலை.pdf`.

Scene-5 extent: scans **40–43** / printed pp.35–38.

Verified page records:

- scan **40** / printed p.35 — opening — `pages/0040.md`;
- scan **41** / printed p.36 — continuation — `pages/0041.md`;
- scan **42** / printed p.37 — continuation — `pages/0042.md`;
- scan **43** / printed p.38 — closing — `pages/0043.md`.

## Result

| Scan | Printed page | Role | Result |
|---:|---:|---|---|
| 40 | 35 | `காட்சி—5` opening | **PASS / verified** |
| 41 | 36 | continuation | **PASS / verified** |
| 42 | 37 | continuation | **PASS / verified** |
| 43 | 38 | closing | **PASS / verified** |

`காட்சி—5` source-page gate: **4/4 verified — COMPLETE**.

## User-directed lexical / visual rule

The active user instruction controls the Scene-5 page work:

- **words:** retain the supplied Gemini first-pass;
- **scan:** use direct visual evidence for headings where present, punctuation, dash, speaker-label spacing/structure, physical line boundaries and final source marks.

No assistant dialogue-word normalization, correction or insertion is introduced from spelling familiarity, grammar, semantics or visual expectation.

## Scan 40 controls

- heading `காட்சி—5.`;
- setting `சிறைச்சாலை`;
- scan punctuation/dashes, speaker-label spacing, physical lines and source marks retained;
- scan 40 ends at `இன்றுதான்!`;
- no closing `*`.

Two positions on scan 40 visibly contain lexical material absent from the supplied Gemini first-pass. Under the explicit Gemini-words rule, no scan-derived word is inserted there.

## Scan 41 controls

- Gemini dialogue words retained;
- scan-controlled labels `கிரி :`, `சாக்:`, `காவ:`;
- duplicated/shifted Gemini label tokens near the final two turns are treated as structural label-extraction artifacts;
- scan punctuation/dashes and physical source lines retained;
- scan 41 ends with the jailer instruction `பிறகு இங்குமங்கும் நடந்து கொண்டேயிருக்க வேண்டும்!`;
- no closing `*`.

## Scan 42 controls

- scan 42 begins with the unlabeled continuation of the jailer's scan-41 instruction and ends with Socrates' `போகிறேன்....`;
- scan-controlled speaker labels are `சாக்:` and `கிரி:`;
- Gemini's isolated `:` before `நண்ப!` is treated as a speaker-label extraction artifact;
- `(விஷக் கிண்ணத்தை வாங்குகிறான்.)` is structurally separated as a stage direction as printed in the scan;
- long dashes, quote marks and punctuation runs are scan-controlled;
- Gemini lexical spacing `பகுத்த றிவால்` is retained;
- no closing `*`.

## Scan 43 controls

- scan 43 begins as the unlabeled continuation of Socrates' scan-42 speech;
- Gemini lexical `சாச் / ரடீஸ்` is retained across the source physical line boundary under the explicit word-retention rule;
- scan punctuation includes `போகிறான்!...`, `உத்திரவிட்டிருக்கிறது!...`, `விடும்!- வருகிறேன்`, `கிரேக்கமே! .......வருகிறேன்!`, `வருகிறேன்!.....நான்`, `வணக்கம், வணக்கம்.`, and `ஏ, ஜெகமே! சிந்திக்கத்`;
- stage-direction punctuation includes `மூடுகிறான், சில வினாடிகளுக்குப்பின்,` and closing `விலக்கி)`;
- scan-controlled speaker-label spacing is `சாக்:`;
- physical lines include `சாச் / ரடீஸ்`, `திண்ணை / களே`, `விடைபெறு / கிறான்`, `உண்மை / யாக`, `சிந்திக் / கத்`, and `கல்லறை / யைக்`;
- the centered Scene-5 closing `*` is retained;
- printed p.38 is represented separately.

## Integrity checkpoint

- source scans directly inspected for Scene 5: **4/4**;
- Gemini lexical baseline retained: **yes**;
- assistant dialogue-word substitutions/insertions introduced: **0**;
- page records verified: **4/4**;
- Scene-5 pages verified: **4/4 COMPLETE**;
- total Socrates pages verified: **17/17 COMPLETE**;
- dramatic-body pages verified: **15/15 COMPLETE**.

## Subsequent assembly state

`காட்சி—5` has now been assembled exclusively from these verified page records:

- assembled scene: `scenes/05.md`;
- fidelity audit: `SCENE5_ASSEMBLY_FIDELITY_REVIEW.md`;
- page-record ↔ scene fidelity: **PASS**;
- scenes assembled for `சாக்ரடீஸ்`: **5/5 COMPLETE**.

## Next activity

Tamil page verification and scene assembly for `சாக்ரடீஸ்` are complete. The next distinct source-sequential activity is **`சேரன் செங்குட்டுவன்` scan 44 / printed p.39 page verification only**. Do not process scan 45 in the same activity.
