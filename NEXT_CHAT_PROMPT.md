# Next Chat Prompt — Continue `சாக்ரடீஸ்` in Kalaignar Stage Plays

Continue the Kalaignar Stage Plays archival project directly in:

`https://github.com/pugazg/kalaignar-stage-plays`

Branch: `main`.

Use the GitHub connector and work directly on `main`.

Controlling source PDF: `TVA_BOK_0065576_நான்மணி_மாலை.pdf`.

## Live-state rule

Fetch live GitHub `main` first and treat it as authoritative. Scene-2 lexical rollback remains locked, Scenes 1–3 have assembly/fidelity PASS, and Scene 4 is verified through scan 35 / printed p.30. Preserve any newer live state.

## Durable state

Active work: `சாக்ரடீஸ்`.

- intro scans 27–28: **2/2 verified**;
- `காட்சி—1`: **page gate + assembly/fidelity PASS**;
- `காட்சி—2`: **page gate + assembly/fidelity PASS after lexical rollback**;
- `காட்சி—3`: **page gate + assembly/fidelity PASS**;
- `காட்சி—4` scans 34–39: **2/6 verified (34–35 / pp.29–30)**;
- total page progress: **9/17 verified**;
- dramatic-body progress: **7/15**;
- scenes assembled: **3/5**.

## Critical transcription rule

The user explicitly instructed:

- **For words, keep Gemini's transcription.**
- For **heading, punctuation, long dash, speaker-label spacing, physical line breaks and final source marks**, keep what is found in the controlling scan.

Do not make assistant word corrections based on visual interpretation, grammar, familiar spelling or sentence meaning unless explicitly requested.

Scan 35 is durably recorded in `works/socrates/pages/0035.md`. Gemini lexical `செடுக்கிறேனா` is retained. Scan-controlled labels include `சாக் :`, `மெலி :`, `நீதி :`, `சார் :`, `அனி :`; the page has no Scene-4 closing `*`.

## Exact next activity

Process **`சாக்ரடீஸ்` `காட்சி—4` scan 36 / printed p.31 only**.

Requirements:

- use the user-supplied Gemini first-pass as the lexical baseline;
- retain Gemini's words exactly;
- use direct scan inspection only for punctuation, long dash, speaker-label spacing, physical line boundaries and final source marks;
- create `works/socrates/pages/0036.md` only after verification;
- update `SCENE4_PAGE_VERIFICATION.md`, work/source page maps, metadata/readmes and handover;
- expected durable total after success: **10/17 verified**, Scene 4 **3/6**;
- do **not** process scan 37 in the same activity;
- do **not** assemble `காட்சி—4` until scans 34–39 are all verified;
- do not begin `சேரன் செங்குட்டுவன்`.

When I say **“Proceed with next activity”**, execute this exact activity directly without asking me to choose a routine next step.
