# Kalaignar Stage Plays — Handover

Repository: `pugazg/kalaignar-stage-plays`, branch `main`.

## Startup rule

Always fetch live `main` first and treat it as authoritative. Scene-2 lexical rollback remains locked, Scenes 1–3 have assembly/fidelity PASS, and Scene 4 has now begun with scan 34 verified. Preserve any newer live state and never restore withdrawn assistant word corrections.

Permanent workflow: `STAGE_PLAY_PROCESSING_GUIDE.md`.

Controlling composite source: `TVA_BOK_0065576_நான்மணி_மாலை.pdf` — **54 scans** — SHA-256 `18d2b1405544b03507e9f92067d287cb28f5a92eaf02bed7054e6e78e5e38c89`.

The PDF itself is not committed. Attach it again in a fresh chat before new page-level visual verification.

## Locked completed work

- `பரதாயணம்`: Tamil archive/assembly PASS; independent English translation PASS.
- `அனார்கலி`: 9/9 Tamil pages verified; 4/4 scenes assembled; fidelity PASS.
- Silappathikaram completed state remains locked and unchanged.

Do not reopen these during active `சாக்ரடீஸ்` work unless the user explicitly requests it.

## Active work — சாக்ரடீஸ்

Controlling extent: scans **27–43** / printed pp. **22–38**.

### Active user-directed lexical / visual rule

For continuing `சாக்ரடீஸ்` transcription, the user has explicitly directed:

- **WORDS: keep Gemini's supplied word-to-word transcription.** Do not make assistant word corrections based on visual interpretation, familiar spelling, grammar or semantic expectation unless the user explicitly asks for a word-level recheck.
- **SCAN: use direct visual evidence for headings, punctuation, long dash, speaker-label spacing, physical line boundaries and final source marks such as `*`.**

### Completed through Scene 3

- introductory note scans 27–28: **2/2 verified**;
- `காட்சி—1` scans 29–31: **page gate + assembly/fidelity PASS**;
- `காட்சி—2` scan 32: **page gate + assembly/fidelity PASS after user-directed lexical rollback**;
- `காட்சி—3` scan 33: **page gate + assembly/fidelity PASS**.

Withdrawn Scene-2 assistant readings remain prohibited:

- `கவிஞனும் மெலிடசும்` → Gemini `கவிஞனாம் மெலிடசும்`;
- `அரசியல் நிபுணனும் நீயும்` → Gemini `அரசியல் நிபுணனாம் நீயும்`.

### `காட்சி—4` — PAGE GATE IN PROGRESS

Source extent: scans **34–39** / printed pp. **29–34**.

Current state:

- `pages/0034.md` — scan **34** / p.29 — **verified**;
- `SCENE4_PAGE_VERIFICATION.md` — Scene-4 page gate **1/6 PASS**;
- scans **35–39** — not started;
- Scene-4 assembly — **blocked until all 6 pages are verified**.

Scan-34 controls:

- Gemini lexical wording retained without assistant normalization;
- scan-controlled scene heading **`காட்சி — 4`**, including spaces around the long dash and no terminal period;
- scan-controlled speaker-label spacing `அனி :` and `நீதிமன்றத் தலைவர் :`;
- scan-controlled long-dash and punctuation usage;
- physical line breaks preserved in `pages/0034.md`;
- no Scene-4 closing `*` appears on scan 34; structural survey places the closing mark on scan 39.

Durable `சாக்ரடீஸ்` progress:

- total page verification: **8/17**;
- dramatic-body pages: **6/15**;
- scenes assembled: **3/5**;
- Scene-4 page gate: **1/6**.

The 2009 published-English witness remains secondary and cannot reconstruct Tamil.

### Remaining structural map

1. `காட்சி—1` — scans 29–31 / pp.24–26 — **page gate + assembly/fidelity COMPLETE**;
2. `காட்சி—2` — scan 32 / p.27 — **page gate + assembly/fidelity COMPLETE**;
3. `காட்சி—3` — scan 33 / p.28 — **page gate + assembly/fidelity COMPLETE**;
4. `காட்சி—4` — scans 34–39 / pp.29–34 — **1/6 pages verified; scan 35 next**;
5. `காட்சி—5` — scans 40–43 / pp.35–38 — not started.

## Exact next activity

Process **`சாக்ரடீஸ்` `காட்சி—4` scan 35 / printed p.30 only** as the next Scene-4 page-verification slice.

Requirements:

- use the user-supplied Gemini first-pass as the lexical baseline;
- **retain Gemini's words exactly**;
- use direct scan inspection only for punctuation, long dash, speaker-label spacing, physical line boundaries and final source marks;
- create `works/socrates/pages/0035.md` only after verification;
- update Scene-4 page gate and work/source page maps after verification;
- expected durable total after success: **9/17 verified**, Scene-4 **2/6**;
- do **not** process scan 36 in the same activity;
- do **not** assemble `காட்சி—4` until scans 34–39 are all verified;
- do not begin `சேரன் செங்குட்டுவன்`.

## Permanent safeguards

- live `main` controls repository state;
- PDF remains external;
- Gemini words are retained for active `சாக்ரடீஸ்` work as directed by the user;
- scan controls headings, punctuation, long dash, speaker-label spacing, physical line boundaries and final marks;
- user-rejected assistant word corrections stay withdrawn unless the user explicitly requests a recheck;
- English witnesses are secondary only;
- scene assembly occurs only after all pages of that scene are verified;
- translation is later and must derive from verified Tamil;
- `அந்தணர்` is not automatically “Brahmin” in future translation work.
