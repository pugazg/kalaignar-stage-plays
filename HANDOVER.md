# Kalaignar Stage Plays — Handover

## Repository

`pugazg/kalaignar-stage-plays` on `main`.

Permanent workflow: `STAGE_PLAY_PROCESSING_GUIDE.md`.

## Active controlling source — கலைஞரின் நான்மணி மாலை

Authentic Tamil source:

- filename: `TVA_BOK_0065576_நான்மணி_மாலை.pdf`;
- scans: **54**;
- SHA-256: `18d2b1405544b03507e9f92067d287cb28f5a92eaf02bed7054e6e78e5e38c89`;
- file size: **146,754,449 bytes**;
- title: **கலைஞரின் நான்மணி மாலை**;
- publisher / imprint visible: **தமிழ்க்கனி பதிப்பகம், சென்னை-28**;
- price visible: **ரூ. 4/-**;
- printer visible: **ஜெம் பிரஸ், சென்னை - 600 001**;
- standalone publication year: **not established from the scan**;
- source PDF remains external and is not committed.

Source registry: `sources/naanmani-malai-tamil/`.

## Physical source map

- scans **1–5**: shared front matter;
- scans **6–17**: **பரதாயணம்**; scan 6 unnumbered, scans 7–17 printed pages 2–12;
- scans **18–26**: **அனார்கலி**, printed pages 13–21;
- scans **27–43**: **சாக்ரடீஸ்**, printed pages 22–38; scans 27–28 are introductory note;
- scans **44–53**: **சேரன் செங்குட்டுவன்**, printed pages 39–48;
- scan **54**: illustrated back cover.

The publisher's note on scan 5 explicitly names these four short plays.

## Source-control policy

The user supplied a Gemini first-pass transcription of the volume. Treat it only as a working/navigation layer.

The scan is controlling. Every word must be visually checked. Do not silently normalize old Tamil glyphs, spelling, punctuation, speaker labels, repetition, stage directions, physical line/page breaks or apparent source anomalies.

Existing 2009 published-English one-act witnesses are **secondary only**. Never use them to reconstruct or override Tamil.

## Completed work — பரதாயணம்

Work folder: `works/bharathayanam/`.

- Tamil scans **6–17**: **12/12 visually verified**.
- Continuous assembly: `scenes/continuous-play.md`.
- Page-record ↔ assembly fidelity: **PASS / COMPLETE**.
- Independent English translation: `translations/en/continuous-play.md`.
- English translation review: **PASS / COMPLETE**.
- Unresolved Tamil/translation blocks: **0**.
- Published-English witness used as translation authority: **No**.

Important `பரதாயணம்` source controls remain documented in `works/bharathayanam/FIRST_PASS_DISCREPANCIES.md` and must not be reverted, including the `பாதுகாப்` / `பாக` → `பாதுகாப்பாக` page join and the source anomaly mechanically assembled as `நீயல்லவர்`.

## Active work — அனார்கலி

Work folder: `works/anarkali/`.

### Page-level Tamil checkpoint — COMPLETE

Controlling Tamil extent:

- scans **18–26**;
- printed pages **13–21**;
- source-printed scenes: **4**;
- page records: `pages/0018.md` through `pages/0026.md`;
- visual verification: **9/9 scans COMPLETE**;
- unresolved literary-text readings: **0** at this page gate.

Scene map:

1. `காட்சி—1` — scan **18** / printed p.13;
2. `காட்சி—2` — scans **19–21** / pp.14–16;
3. `காட்சி—3` — scans **22–24** / pp.17–19;
4. `காட்சி—4` — scans **25–26** / pp.20–21.

Material source controls are recorded at `works/anarkali/FIRST_PASS_DISCREPANCIES.md`.

Important readings / boundaries that must not be silently changed:

- scan 18: `அணுப்பொழுதும்`, `காந்தக் கண்`, source-printed `ஆறுதல்கூறி-வாய்`, `அக்பரது குடைநிழலில்`, `என் திழையே!`;
- scan 19: `சாவதானமாக—ஆனால் குறும்பாக`, `என்னுள் உன் குடிசை பெருமையுற்றது`;
- scan 20: source anachronism `அவசரச்சட்டம்`; `நன்றாகத்தெரியும்`; `சப்ரகூட மஞ்சம்`;
- scan 21: `உங்கள் மகுடபதியின் மகன்தான்`; source-anomalous `சிம்மாசனமேறிகளை நான் மதிக்கமாட்டேன்`; `(மண்ணையள்ளிக் காட்டல்)`; `‘காதல் சுதந்திரம்’`; `டில்லி ஏகாதிபத்தியத்திற்குப் பணிந்துவிடாது!`;
- scan 22→23: `அந்தஸ்து பேதத்` / `தின் அளவு!` mechanically joins as `அந்தஸ்து பேதத்தின் அளவு!`;
- scan 22: `மிதியுண்ட நாகம்போல்`; `நீங்கள் ஜரிகைப்பூ அல்ல! சாமந்திப்பூ!`;
- scan 23: physical line splits `செய் / திருக்கிறார்`, `களங்க / மற்ற`, `கோட் / டைச்`, `என் / பதை`; the last mechanically yields `என்பதை` in scene assembly;
- scan 24: `(திரையில் குரல்)` is source stage text; the live-entombment narration closes Scene 3; centred `*` retained;
- scan 25→26: scan 25 ends mid-speech `இவ்வளவும்`; scan 26 continues `இருந்தால் என்ன...`;
- scan 25: `மாசற்ற ஜோதி மழையே!`; physical `தொழுத் / திட`; `கற்பின் ஆரமே!`; `கல்லினும்`; `பிரும்மாண்ட`; `பஞ்சத்திலே பரப்ப`;
- scan 26: `நீதியில்லாத பூமியில்`; `மூடியுள்ள கல்லறையே`; `ராஜபுத்திர ஜோதிபாயை`; `ஜோதிபாயின்`; final suicide-attempt direction and centred `*`.

### Exact next activity

Assemble **`காட்சி—1` through `காட்சி—4`** strictly from `pages/0018.md`–`pages/0026.md`.

Requirements:

- do not re-read from Gemini or the published-English witness for assembly;
- use verified page records as immediate authority;
- remove only mechanical print-line/page breaks;
- preserve wording, punctuation, stage directions, speaker order, repetition and source anomalies;
- handle scan 22→23 and 25→26 boundaries explicitly;
- run a page-record ↔ scene-assembly fidelity audit;
- **do not begin `சாக்ரடீஸ்` in the same activity**.

Only after the `அனார்கலி` Tamil assembly/fidelity gate passes should any independent English translation/comparison phase be considered.

## Remaining one-act work

- `works/socrates/` — Tamil scans **27–43**, pending visual verification;
- `works/cheran-senguttuvan/` — Tamil scans **44–53**, pending visual verification.

Their completed 2009 published-English transcriptions remain secondary witnesses only.

## Completed Silappathikaram state — preserve unchanged

`works/silappathikaram-nataka-kappiyam/` remains complete and locked:

- **88/88 scans** visually verified;
- Tamil transcription audit: **PASS**;
- **38/38 numbered scenes** plus separate closing tableau assembled / fidelity passed;
- global Tamil source review: **PASS**;
- independent English translation: **COMPLETE / READY**;
- published-English secondary-witness comparison: **PASS / COMPLETE**.

Do not revert the scan-87 source corrections already recorded there (`தலைவர்களாம்`, `அன்னை நற்சோணையே`, `ஈடற்ற புலவனே`).

## Permanent terminology controls

Retain Kalaignar's rhetorical force, cadence, repetition, humour, emotional escalation and dramatic register.

`அந்தணர்` is not automatically “Brahmin.” Preserve distinctions among `பிராமண`, `பார்ப்பன`, `பார்ப்பார்`, `அந்தணர்`, `மறையவன் / மறையவர்`, and related terms in any future translation phase.
