# Kalaignar Stage Plays — Handover

Repository: `pugazg/kalaignar-stage-plays`, branch `main`.

## Startup rule

Always fetch live `main` first and treat it as authoritative. Scene-2 lexical rollback remains locked, Scenes 1–3 have assembly/fidelity PASS, and Scene 4 is now verified through scan 36. Preserve any newer live state and never restore withdrawn assistant word corrections.

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

### Completed through Scene 3

- intro scans 27–28: **2/2 verified**;
- `காட்சி—1`: **page gate + assembly/fidelity PASS**;
- `காட்சி—2`: **page gate + assembly/fidelity PASS after user-directed lexical rollback**;
- `காட்சி—3`: **page gate + assembly/fidelity PASS**.

Scene-2 rejected assistant corrections remain withdrawn; Gemini `கவிஞனாம் மெலிடசும்` and `அரசியல் நிபுணனாம் நீயும்` remain controlling lexical readings.

### `காட்சி—4` — PAGE GATE IN PROGRESS

Source extent: scans **34–39** / printed pp. **29–34**.

Current state:

- `pages/0034.md` — scan 34 / p.29 — **verified**;
- `pages/0035.md` — scan 35 / p.30 — **verified**;
- `pages/0036.md` — scan 36 / p.31 — **verified**;
- `SCENE4_PAGE_VERIFICATION.md` — **3/6 PASS**;
- scans 37–39 — not started;
- Scene-4 assembly — **blocked until all 6 pages are verified**.

Scan-36 lexical/visual controls:

- Gemini lexical words retained exactly, including `எல்லாரும்`;
- scan controls punctuation, long dashes, speaker-label spacing, physical line breaks and source marks;
- source labels retained as `மெலி :` and `சாக் :`;
- important scan punctuation includes `கெடுக்கிறீர்!........சந்தை`, `ஆமாம்—ஆமாம்!`, `இவ்வளவு பேரும்—ஏன்—ஏதென்சு`, `முடியுமா?........`, `விஷம்!... ....`, and final `எண்ணங்கள்!........`;
- physical splits include `அனிட / சின்` and `அள / வுக்கு`;
- scan 36 contains no Scene-4 closing `*`.

Durable `சாக்ரடீஸ்` progress:

- total page verification: **10/17**;
- dramatic-body pages: **8/15**;
- scenes assembled: **3/5**;
- Scene-4 page gate: **3/6**.

The 2009 published-English witness remains secondary and cannot reconstruct Tamil.

## Exact next activity

Process **`சாக்ரடீஸ்` `காட்சி—4` scan 37 / printed p.32 only** as the next Scene-4 page-verification slice.

Requirements:

- use the user-supplied Gemini first-pass as the lexical baseline;
- retain Gemini's words exactly;
- use direct scan inspection only for punctuation, long dash, speaker-label spacing, physical line boundaries and final source marks;
- create `works/socrates/pages/0037.md` only after verification;
- update Scene-4 gate and work/source status files;
- expected durable total after success: **11/17 verified**, Scene 4 **4/6**;
- do **not** process scan 38 in the same activity;
- do **not** assemble `காட்சி—4` until scans 34–39 are all verified;
- do not begin `சேரன் செங்குட்டுவன்`.

## Permanent safeguards

- live `main` controls repository state;
- PDF remains external;
- Gemini words are retained for active `சாக்ரடீஸ்` work;
- scan controls headings, punctuation, long dash, speaker-label spacing, physical line boundaries and final marks;
- user-rejected assistant word corrections stay withdrawn;
- English witnesses are secondary only;
- scene assembly occurs only after all pages of that scene are verified;
- translation is later and must derive from verified Tamil;
- `அந்தணர்` is not automatically “Brahmin” in future translation work.
