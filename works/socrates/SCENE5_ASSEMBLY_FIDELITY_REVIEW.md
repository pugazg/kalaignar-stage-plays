# `காட்சி—5` Assembly Fidelity Review — சாக்ரடீஸ்

## Scope

This audit tests assembled `scenes/05.md` against the four **verified page records only**:

- `pages/0040.md` — scan 40 / printed p.35;
- `pages/0041.md` — scan 41 / printed p.36;
- `pages/0042.md` — scan 42 / printed p.37;
- `pages/0043.md` — scan 43 / printed p.38.

The verified page records are the sole textual authority for assembly. No new scan reading, Gemini reconciliation, semantic correction or lexical normalization is introduced here.

## Scene result

| Scene | Verified page records | Physical scans | Printed pages | Result |
|---|---|---|---|---|
| `காட்சி—5.` | `0040.md`–`0043.md` | 40–43 | 35–38 | **PASS** |

Assembled file: `scenes/05.md`.

## Assembly decisions

- Source heading `காட்சி—5.` and setting `சிறைச்சாலை` are retained.
- All verified Gemini lexical wording already locked into the page records is retained.
- Scan-resolved punctuation, dash usage, speaker-label variants/spacing, stage-direction structure and final `*` are retained.
- Only legitimate physical print-line and page-boundary breaks are joined.
- Printed page numbers remain provenance metadata and are not imported into the dramatic scene body.
- The centered final `*` from scan 43 is retained.
- The two scan-visible lexical omissions already documented on scan 40 remain unfilled because the verified page record itself is the sole assembly authority.

## Page-boundary checks

| Boundary | Verified-page evidence | Assembly decision | Result |
|---|---|---|---|
| 40→41 | p.35 ends Socrates with `இன்றுதான்!`; p.36 begins `கிரி : சாக்ரடீஸ்!` | separate speaker turn retained | PASS |
| 41→42 | p.36 ends jailer speech `பிறகு இங்குமங்கும் நடந்து கொண்டேயிருக்க வேண்டும்!`; p.37 begins unlabeled `கால்கள் மரத்துப்போகும்...` | joined as the same `காவ:` utterance with a lexical space | PASS |
| 42→43 | p.37 ends Socrates `போகிறேன்....`; p.38 begins unlabeled `எனதருமை ஏதென்சு...` | joined as the same Socrates speech with a lexical space | PASS |

## Mechanical print-line joins checked

Representative joins audited against the verified page records:

- `இடத் / திலே` → `இடத்திலே`;
- `மாறிவிட் / டான்` → `மாறிவிட்டான்`;
- `யாருக் / கும்` → `யாருக்கும்`;
- `முயலுங் / கள்` → `முயலுங்கள்`;
- `வசப் / படுத்திக்கொண்டு` → `வசப்படுத்திக்கொண்டு`;
- `தயா / ராக` → `தயாராக`;
- `நெருங்கிக்கொண்டே / யிருக்கிறது` → `நெருங்கிக்கொண்டேயிருக்கிறது`;
- `புருவங் / களை` → `புருவங்களை`;
- `முறை / களைச்` → `முறைகளைக்`;
- `சாப்பிட / லாம்` → `சாப்பிடலாம்`;
- `சாப்பிடு / கிறேன்` → `சாப்பிடுகிறேன்`;
- `சாச் / ரடீஸ்` → `சாச்ரடீஸ்`;
- `ஆவேச / மாகப்` → `ஆவேசமாகப்`;
- `திண்ணை / களே` → `திண்ணைகளே`;
- `விடைபெறு / கிறான்` → `விடைபெறுகிறான்`;
- `உண்மை / யாக` → `உண்மையாக`;
- `சிந்திக் / கத்` → `சிந்திக்கத்`;
- `கல்லறை / யைக்` → `கல்லறையைக்`.

These are mechanical removal of physical print-line boundaries only. In particular, `சாச்ரடீஸ்` is the direct assembly of verified `சாச் / ரடீஸ்`; it is **not** normalized to another spelling.

## Speaker-label accounting

| Source label / structural line | Count in verified page records | Count in assembled scene | Result |
|---|---:|---:|---|
| `சாக்:` | 11 | 11 | PASS |
| `கிரி :` | 3 | 3 | PASS |
| `கிரி:` | 3 | 3 | PASS |
| `காவ:` | 1 | 1 | PASS |
| bare `: !........` line from scan 40 | 1 | 1 | PASS |

No speaker label is added, lost or regularized.

## Locked lexical controls

The assembled scene specifically retains verified forms including:

- `பயனற்ற தத்துவ விசாரணையில்` as produced by joining the verified page-40 physical line break;
- `மனங்குலையாமாவீர`;
- `தொகை தொகையாகப் பகைவரினும் துவளாது`;
- `தேசப் பிரஷ்ட உத்திரவு`;
- `வியாக்யானம்`;
- `பகுத்த றிவால்`;
- assembled `சாச்ரடீஸ்` from verified `சாச் / ரடீஸ்`;
- `தருமைஏதென்ஸ்` within the verified scan-43 wording.

No assistant word-level substitution is introduced.

## Scan-resolved non-lexical controls retained

The assembled scene retains, among other verified forms:

- heading `காட்சி—5.` and setting `சிறைச்சாலை`;
- `திறக்கப்படுகிறது—கிரிட்டோ`;
- `அன்புள்ளவளே!........பார்த்தாயா?.... ....`;
- `செய்ததும்—மரணத்திற்கு`;
- standalone `(விஷக் கிண்ணத்தை வாங்குகிறான்.)`;
- long dashes in `போகிறேன் — உன்னையே நீ` and `வேண்டாம் — எவர்`;
- the verified quotation marks around the Socrates maxims;
- `விடும்!- வருகிறேன்`;
- `கிரேக்கமே! .......வருகிறேன்!`;
- `வருகிறேன்!.....நான்`;
- stage-direction punctuation `மூடுகிறான், சில வினாடிகளுக்குப்பின்,` and `விலக்கி)`;
- final centered `*`.

## Integrity checkpoint

- verified page records used: **4 / 4**;
- source-printed Scene 5 assembled: **1 / 1**;
- page-record → scene comparison: **PASS**;
- unresolved assembly discrepancies: **0**;
- speaker-label count mismatches: **0**;
- assistant lexical substitutions introduced: **0**;
- source punctuation/dash changes introduced: **0**;
- final `*` retained: **yes**.

## Result

**PASS — `சாக்ரடீஸ்` `காட்சி—5` assembly and page-record fidelity gate are complete.**

With this result, `சாக்ரடீஸ்` has **17/17 verified pages, 15/15 verified dramatic-body pages, and 5/5 assembled scenes with fidelity PASS**. Tamil page-level and scene-assembly work for this source extent is complete.

The next distinct source-sequential activity is `சேரன் செங்குட்டுவன்` scan **44** / printed p.39 page verification only. Do not begin later scans in the same activity.
