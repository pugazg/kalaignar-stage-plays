# Kalaignar Stage Plays — Handover

Repository: `pugazg/kalaignar-stage-plays`, branch `main`.

## Startup rule

Always fetch live `main` first and treat it as authoritative. Preserve newer durable state and never restore withdrawn assistant word corrections.

Permanent workflow: `STAGE_PLAY_PROCESSING_GUIDE.md`.

Controlling composite source: `TVA_BOK_0065576_நான்மணி_மாலை.pdf` — **54 scans** — SHA-256 `18d2b1405544b03507e9f92067d287cb28f5a92eaf02bed7054e6e78e5e38c89`.

## Locked completed work

- `பரதாயணம்`: Tamil archive/assembly PASS; independent English translation PASS.
- `அனார்கலி`: 9/9 Tamil pages verified; 4/4 scenes assembled; fidelity PASS.
- Silappathikaram completed state remains locked and unchanged.

## Active work — சாக்ரடீஸ்

Controlling extent: scans **27–43** / printed pp. **22–38**.

### Active user-directed lexical / visual rule

- **WORDS: keep Gemini's supplied word-to-word transcription.**
- **SCAN: use direct visual evidence for headings, punctuation, dash, speaker-label spacing/structure, physical line boundaries and final source marks such as `*`.**
- Do not make assistant dialogue-word corrections, additions or reconstructions from spelling familiarity, grammar, semantics or visual expectation unless the user explicitly asks for a word-level recheck.

### Durable completed state

- intro scans 27–28: **2/2 verified**;
- `காட்சி—1`: **page gate + assembly/fidelity PASS**;
- `காட்சி—2`: **page gate + assembly/fidelity PASS after user-directed lexical rollback**;
- `காட்சி—3`: **page gate + assembly/fidelity PASS**;
- `காட்சி — 4`: **6/6 page gate + assembly/fidelity PASS**;
- `காட்சி—5`: **scans 40–43 / pp.35–38 verified; page gate 4/4 COMPLETE**.

Scene-5 durable files:

- `works/socrates/pages/0040.md` — verified opening page;
- `works/socrates/pages/0041.md` — verified continuation;
- `works/socrates/pages/0042.md` — verified continuation;
- `works/socrates/pages/0043.md` — verified closing page, final `*` retained;
- `works/socrates/SCENE5_PAGE_VERIFICATION.md` — **4/4 PASS / COMPLETE**.

### Scene-5 controls through scan 43

Scan 40:

- scan-controlled heading `காட்சி—5.` and setting `சிறைச்சாலை`;
- two scan-visible lexical omissions from Gemini are documented and deliberately not filled under the Gemini-words rule;
- no closing `*`.

Scan 41:

- Gemini dialogue wording retained, including `மனங்குலையாமாவீர`, `தொகை தொகையாகப் பகைவரினும் துவளாது`, `தேசப் பிரஷ்ட உத்திரவு`, and `வியாக்யானம்`;
- scan controls punctuation/dashes, physical source lines and speaker-label structure/spacing;
- no closing `*`.

Scan 42:

- Gemini dialogue wording retained, including lexical spacing `பகுத்த றிவால்`;
- scan begins as the unlabeled continuation of the jailer's scan-41 instruction;
- scan-visible speaker labels are `சாக்:` and `கிரி:`;
- `(விஷக் கிண்ணத்தை வாங்குகிறான்.)` is retained as a standalone stage direction;
- scan controls long dashes, quote punctuation, punctuation runs and physical source lines;
- scan ends with Socrates' `போகிறேன்....`;
- no closing `*`.

Scan 43:

- begins as the unlabeled continuation of Socrates' scan-42 speech;
- Gemini lexical `சாச் / ரடீஸ்` is retained across the physical source line boundary under the user rule;
- scan controls punctuation including `போகிறான்!...`, `விடும்!- வருகிறேன்`, the dot runs around `கிரேக்கமே! .......வருகிறேன்!` and `வருகிறேன்!.....நான்`, and later punctuation;
- scan controls stage-direction punctuation and `சாக்:` label spacing;
- physical source lines are preserved;
- centered closing `*` is retained;
- printed p.38 is separately recorded.

Durable `சாக்ரடீஸ்` progress:

- total page verification: **17/17 COMPLETE**;
- dramatic-body pages: **15/15 COMPLETE**;
- scenes assembled: **4/5**;
- Scene-5 page gate: **4/4 COMPLETE**.

The 2009 published-English witness remains secondary and cannot reconstruct Tamil.

## Exact next activity

Assemble **`சாக்ரடீஸ்` `காட்சி—5` only** from verified page records `works/socrates/pages/0040.md` through `0043.md`.

Requirements:

- treat the verified page records as the **sole textual authority**;
- mechanically join only legitimate print-line and page-boundary breaks;
- preserve wording, punctuation, speaker-label variants, stage directions, repetitions and the final `*`;
- follow the existing scene-file naming/format convention;
- run the page-record ↔ scene fidelity audit and require PASS;
- update work/source/readme/page-map/handover state only after fidelity PASS;
- expected durable state after success: **5/5 scenes assembled**, `சாக்ரடீஸ்` Tamil page + scene assembly complete;
- do **not** begin `சேரன் செங்குட்டுவன்` in the same activity.

## Permanent safeguards

- live `main` controls repository state;
- PDF remains external;
- Gemini dialogue words are retained for active `சாக்ரடீஸ்` page transcription;
- scan controls headings, punctuation, dash, speaker-label spacing/structure, physical line boundaries and final marks;
- user-rejected assistant word corrections stay withdrawn;
- assembly must use verified page records, not a fresh Gemini/source reconstruction;
- English witnesses are secondary only;
- translation is later and must derive from verified Tamil;
- `அந்தணர்` is not automatically “Brahmin” in future translation work.
