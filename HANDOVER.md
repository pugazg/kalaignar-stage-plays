# Kalaignar Stage Plays — Handover

Repository: `pugazg/kalaignar-stage-plays`, branch `main`.

## Startup rule

Always fetch live `main` first and treat it as authoritative. The `காட்சி—2` page-verification activity began from live `main` `c0ca398e4b6583638fdcefe58393f976e06a9c51`. After its first pass, the user explicitly rejected the assistant's word-level changes and required a lexical rollback. Preserve the newer corrected state.

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

This newer instruction supersedes any earlier practice that allowed the assistant to replace Gemini word readings merely because a scan appeared to support another lexical form.

### Introductory note — durable PASS

- `pages/0027.md` — scan 27 / p.22 — verified;
- `pages/0028.md` — scan 28 / p.23 — verified;
- intro: **2/2 verified**.

The user-corrected old-glyph readings in `INTRO_RECONCILIATION.md` remain locked. Do not reintroduce withdrawn assistant normalizations.

### `காட்சி—1` — COMPLETE THROUGH ASSEMBLY/FIDELITY

- scans **29–31** / pp.24–26;
- page records **3/3 verified**;
- `scenes/01.md` — **assembly-reviewed**;
- `ASSEMBLY_FIDELITY_REVIEW.md` — **PASS**;
- unresolved assembly discrepancies: **0**.

Scene-1 source-sensitive controls remain locked, including `காணா`, `புலிநிகர்`, `மின்னலப்பா`, `இந்தக் கிண்ணாரக் கிழவருக்கு`, `கஷ்டப்பட`, `நட்டாற்றில்`, `ஏண்டி`, `சுடுகாடு`, `புவனமறியாததல்ல`, `சிரந்தாழ்த்தி`, and `உயிரினுமினியவர்`.

### `காட்சி—2` — PAGE GATE COMPLETE AFTER USER ROLLBACK

Source extent: scan **32** / printed p. **27**; one-page scene.

- `pages/0032.md` — **verified after user-directed lexical rollback**;
- page-gate record: `works/socrates/SCENE2_PAGE_VERIFICATION.md` — **PASS after rollback**;
- unresolved readings under the user's rule: **0**;
- final centred `*`: preserved;
- Scene-2 assembly: **not yet begun**.

The first Scene-2 verification pass incorrectly changed Gemini words. Those assistant substitutions are now withdrawn:

- incorrect assistant `கவிஞனும் மெலிடசும்` → restored Gemini `கவிஞனாம் மெலிடசும்`;
- incorrect assistant `அரசியல் நிபுணனும் நீயும்` → restored Gemini `அரசியல் நிபுணனாம் நீயும்`.

For scan 32, direct scan inspection is retained only for the non-lexical features specified by the user, including:

- `காட்சி—2.`;
- source label variation `அனிடஸ் :` / `லைகன்:` / `மெலிடஸ் :`;
- `சாக்ரடீஸ்—சமுத்திரத்துத்` with the printed long dash;
- source punctuation runs;
- physical print-line splits preserved in `pages/0032.md`;
- centred final `*`.

Durable `சாக்ரடீஸ்` progress:

- total page verification: **6/17**;
- dramatic-body pages: **4/15**;
- scenes assembled: **1/5**.

The 2009 published-English witness remains secondary and cannot reconstruct Tamil.

### Remaining structural map

1. `காட்சி—1` — scans 29–31 / pp.24–26 — **page gate + assembly/fidelity COMPLETE**;
2. `காட்சி—2` — scan 32 / p.27 — **corrected page gate COMPLETE; assembly pending**;
3. `காட்சி—3` — scan 33 / p.28 — not started;
4. `காட்சி—4` — scans 34–39 / pp.29–34 — not started;
5. `காட்சி—5` — scans 40–43 / pp.35–38 — not started.

## Exact next activity

Assemble **`சாக்ரடீஸ்` `காட்சி—2` only** from the corrected verified `pages/0032.md`.

Requirements:

- use corrected verified `pages/0032.md` as the sole textual authority;
- mechanically remove legitimate physical print-line breaks only;
- retain Gemini lexical words exactly, including `கவிஞனாம் மெலிடசும்` and `அரசியல் நிபுணனாம் நீயும்`;
- preserve scan-controlled punctuation, speaker labels/spacing, long dash, repetitions, stage directions and final `*`;
- create the Scene-2 assembled file under `works/socrates/scenes/`;
- extend/create the page-record ↔ scene fidelity audit and require PASS;
- **do not begin scan 33 / `காட்சி—3` in the same activity**;
- do not begin `சேரன் செங்குட்டுவன்`.

After a clean Scene-2 assembly/fidelity PASS, the following distinct activity is scan **33** / printed p.28 (`காட்சி—3`) page verification under the same Gemini-words / scan-typography rule.

## Permanent safeguards

- live `main` controls repository state;
- PDF remains external;
- for active `சாக்ரடீஸ்`, Gemini words are retained as directed by the user;
- scan controls headings, punctuation, long dash, speaker-label spacing, physical line boundaries and final marks;
- user-rejected assistant word corrections stay withdrawn unless the user explicitly requests a recheck;
- English witnesses are secondary only;
- scene assembly occurs only after all pages of that scene are verified;
- translation is later and must derive from verified Tamil;
- `அந்தணர்` is not automatically “Brahmin” in future translation work.
