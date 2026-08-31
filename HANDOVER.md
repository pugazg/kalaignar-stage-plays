# Kalaignar Stage Plays — Handover

Repository: `pugazg/kalaignar-stage-plays`, branch `main`.

## Startup rule

Always fetch live `main` first and treat it as authoritative. Scene-2 lexical rollback remains locked, Scenes 1–3 have assembly/fidelity PASS, and Scene 4 now has a complete 6/6 page gate through scan 39. Preserve any newer live state and never restore withdrawn assistant word corrections.

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
- **SCAN: use direct visual evidence for headings, punctuation, long dash, speaker-label spacing, physical line boundaries and final source marks such as `*`.**
- Do not make assistant word corrections from spelling familiarity, grammar, semantics or visual expectation unless the user explicitly asks for a word-level recheck.

### Completed state

- intro scans 27–28: **2/2 verified**;
- `காட்சி—1`: **page gate + assembly/fidelity PASS**;
- `காட்சி—2`: **page gate + assembly/fidelity PASS after user-directed lexical rollback**;
- `காட்சி—3`: **page gate + assembly/fidelity PASS**;
- `காட்சி—4` scans 34–39 / pp.29–34: **6/6 page verification PASS; assembly not yet performed**.

Scene-2 rejected assistant corrections remain withdrawn; Gemini `கவிஞனாம் மெலிடசும்` and `அரசியல் நிபுணனாம் நீயும்` remain controlling lexical readings.

### Scan 39 closing controls

`works/socrates/pages/0039.md` is verified from the user-supplied Gemini baseline plus direct scan inspection.

- Gemini lexical wording is retained, including `விட்டர்கள்` and `களத்தில்`;
- source speaker-label spacing is `சாக்:`;
- scan-controlled punctuation includes `281—220!........` and `மேன்மையானது!........`;
- scan-controlled long dash is retained at `ஒரு மனிதன்—`;
- physical source breaks include `சரித்திரத் / திலே`, `கிடைத்திருக் / கிறது`, `கூறிய / தற்கு`, `ஆயிரக் / கணக்கான`, `வாங்கப் / பட்டவை`, and `காட்டி / லும்`;
- centered final `*` is present and preserved;
- printed page number `34` is represented separately.

Durable `சாக்ரடீஸ்` progress:

- total page verification: **13/17**;
- dramatic-body pages: **11/15**;
- scenes assembled: **3/5**;
- Scene-4 page gate: **6/6 PASS**.

The 2009 published-English witness remains secondary and cannot reconstruct Tamil.

## Exact next activity

Assemble **`சாக்ரடீஸ்` `காட்சி—4` only** from verified page records:

- `works/socrates/pages/0034.md`
- `works/socrates/pages/0035.md`
- `works/socrates/pages/0036.md`
- `works/socrates/pages/0037.md`
- `works/socrates/pages/0038.md`
- `works/socrates/pages/0039.md`

Requirements:

- use these verified page records as the **sole textual authority** for assembly;
- mechanically join only legitimate physical print-line and page-boundary breaks;
- preserve wording, punctuation, speaker labels, stage directions, repetitions and the final `*`;
- create the Scene-4 assembled file using existing scene-file conventions;
- run a page-record ↔ scene fidelity audit and require PASS before updating durable status;
- after success, expected scene state: **4/5 scenes assembled**;
- do **not** begin `காட்சி—5` in the same activity;
- do not begin `சேரன் செங்குட்டுவன்`.

## Permanent safeguards

- live `main` controls repository state;
- PDF remains external;
- Gemini words are retained for active `சாக்ரடீஸ்` page transcription;
- scan controls headings, punctuation, long dash, speaker-label spacing, physical line boundaries and final marks;
- user-rejected assistant word corrections stay withdrawn;
- assembly must use verified page records, not a fresh Gemini/source reconstruction;
- English witnesses are secondary only;
- translation is later and must derive from verified Tamil;
- `அந்தணர்` is not automatically “Brahmin” in future translation work.
