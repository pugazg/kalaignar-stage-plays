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
- **SCAN: use direct visual evidence for headings, punctuation, long dash, speaker-label spacing, physical line boundaries and final source marks such as `*`.**
- Do not make assistant word corrections, additions or reconstructions from spelling familiarity, grammar, semantics or visual expectation unless the user explicitly asks for a word-level recheck.

### Durable completed state

- intro scans 27–28: **2/2 verified**;
- `காட்சி—1`: **page gate + assembly/fidelity PASS**;
- `காட்சி—2`: **page gate + assembly/fidelity PASS after user-directed lexical rollback**;
- `காட்சி—3`: **page gate + assembly/fidelity PASS**;
- `காட்சி — 4`: **6/6 page gate + assembly/fidelity PASS**;
- `காட்சி—5`: **scan 40 / p.35 verified; page gate 1/4**.

Scene-5 durable files so far:

- `works/socrates/pages/0040.md` — verified opening page;
- `works/socrates/SCENE5_PAGE_VERIFICATION.md` — **1/4 PASS**.

### Scan 40 controls

The user-supplied Gemini first-pass remains the lexical baseline.

- scan-controlled heading: `காட்சி—5.`;
- setting: `சிறைச்சாலை`;
- scan controls punctuation/dashes, speaker-label spacing, physical source lines and source marks;
- scan 40 ends at `இன்றுதான்!`;
- no closing `*` appears on scan 40;
- printed p.35 is recorded separately.

Two positions on scan 40 visibly contain lexical material that is absent from the supplied Gemini first-pass. Under the explicit **Gemini words** rule, no scan-derived word was inserted at those positions. `SCENE5_PAGE_VERIFICATION.md` records this intentionally rather than silently reconstructing the omissions.

Durable `சாக்ரடீஸ்` progress:

- total page verification: **14/17**;
- dramatic-body pages: **12/15**;
- scenes assembled: **4/5**;
- Scene-5 page gate: **1/4**.

The 2009 published-English witness remains secondary and cannot reconstruct Tamil.

## Exact next activity

Process **`சாக்ரடீஸ்` `காட்சி—5` scan 41 / printed p.36 only** as the next Scene-5 page-verification slice.

Requirements:

- use the user-supplied Gemini first-pass as the lexical baseline;
- retain Gemini's words exactly;
- use direct scan inspection for punctuation, long dash, speaker-label spacing, physical line boundaries and source marks;
- create `works/socrates/pages/0041.md` only after verification;
- update `SCENE5_PAGE_VERIFICATION.md`, work/source page maps, metadata/readmes and handover after verification;
- expected durable total after success: **15/17 verified**, Scene 5 **2/4**;
- do **not** process scan 42 in the same activity;
- do **not** assemble `காட்சி—5` until scans 40–43 are all verified;
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
