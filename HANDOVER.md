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
- Do not make assistant word corrections from spelling familiarity, grammar, semantics or visual expectation unless the user explicitly asks for a word-level recheck.

### Durable completed state

- intro scans 27–28: **2/2 verified**;
- `காட்சி—1`: **page gate + assembly/fidelity PASS**;
- `காட்சி—2`: **page gate + assembly/fidelity PASS after user-directed lexical rollback**;
- `காட்சி—3`: **page gate + assembly/fidelity PASS**;
- `காட்சி — 4` scans 34–39 / pp.29–34: **6/6 page gate + assembly/fidelity PASS**.

Scene-4 durable files:

- verified pages: `works/socrates/pages/0034.md`–`0039.md`;
- assembled scene: `works/socrates/scenes/04.md`;
- page gate: `works/socrates/SCENE4_PAGE_VERIFICATION.md` — PASS;
- assembly audit: `works/socrates/SCENE4_ASSEMBLY_FIDELITY_REVIEW.md` — PASS.

Scene-4 assembly uses the verified page records as the sole textual authority. Only legitimate print-line/page-boundary joins are made; wording, punctuation, speaker-label variants, stage directions and final `*` are preserved. Fidelity audit reports **0 unresolved discrepancies**, **0 speaker-label mismatches**, and **0 assistant lexical substitutions**.

Scene-2 rejected assistant corrections remain withdrawn; Gemini `கவிஞனாம் மெலிடசும்` and `அரசியல் நிபுணனாம் நீயும்` remain controlling lexical readings.

Durable `சாக்ரடீஸ்` progress:

- total page verification: **13/17**;
- dramatic-body pages: **11/15**;
- scenes assembled: **4/5**.

The 2009 published-English witness remains secondary and cannot reconstruct Tamil.

## Exact next activity

Process **`சாக்ரடீஸ்` `காட்சி—5` scan 40 / printed p.35 only** as the opening Scene-5 page-verification slice.

Requirements:

- use the user-supplied Gemini first-pass as the lexical baseline;
- retain Gemini's words exactly;
- use direct scan inspection for the Scene-5 heading, punctuation, long dash, speaker-label spacing, physical line boundaries and source marks;
- create `works/socrates/pages/0040.md` only after verification;
- update work/source page-gate status after verification;
- expected durable total after success: **14/17 verified**, Scene 5 **1/4**;
- do **not** process scan 41 in the same activity;
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
