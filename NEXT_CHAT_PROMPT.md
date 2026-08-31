# Next Chat Prompt — Continue `சாக்ரடீஸ்` in Kalaignar Stage Plays

Continue the Kalaignar Stage Plays archival project directly in:

`https://github.com/pugazg/kalaignar-stage-plays`

Branch: `main`.

Use the GitHub connector and work directly on `main`.

Controlling source PDF: `TVA_BOK_0065576_நான்மணி_மாலை.pdf`.

## Live-state rule

Fetch live GitHub `main` first and treat it as authoritative. Scenes 1–4 have assembly/fidelity PASS and Scene 5 is verified through scan 41 / printed p.36. Preserve any newer live state and never restore withdrawn assistant lexical corrections.

## Durable state

Active work: `சாக்ரடீஸ்`.

- intro scans 27–28: **2/2 verified**;
- `காட்சி—1`: **page gate + assembly/fidelity PASS**;
- `காட்சி—2`: **page gate + assembly/fidelity PASS after lexical rollback**;
- `காட்சி—3`: **page gate + assembly/fidelity PASS**;
- `காட்சி — 4`: **6/6 page gate + assembly/fidelity PASS**;
- `காட்சி—5`: **scans 40–41 / pp.35–36 verified; page gate 2/4**;
- total page progress: **15/17 verified**;
- dramatic-body progress: **13/15**;
- scenes assembled: **4/5**.

Scene-5 durable artifacts:

- `works/socrates/pages/0040.md` — verified;
- `works/socrates/pages/0041.md` — verified;
- `works/socrates/SCENE5_PAGE_VERIFICATION.md` — **2/4 PASS**.

## Critical transcription rule

The user explicitly instructed:

- **For words, keep Gemini's transcription.**
- For **heading, punctuation, long dash, speaker-label spacing, physical line breaks and final source marks**, keep what is found in the controlling scan.

Do not make assistant dialogue-word corrections, additions or reconstructions based on visual interpretation, grammar, familiar spelling or sentence meaning unless explicitly requested.

Scan 40 has two scan-visible lexical omissions from Gemini; they remain documented and deliberately unfilled.

Scan 41 retains Gemini dialogue wording while the scan controls punctuation/dashes, physical lines and speaker-label structure/spacing. Gemini's duplicated/shifted label tokens around the final two turns are treated as structural label-extraction artifacts rather than dialogue words. Scan 41 contains no closing `*`.

## Exact next activity

Process **`சாக்ரடீஸ்` `காட்சி—5` scan 42 / printed p.37 only** as the next Scene-5 page-verification slice.

Requirements:

- use the user-supplied Gemini first-pass as the lexical baseline;
- retain Gemini's dialogue words exactly;
- use direct scan inspection for punctuation, long dash, speaker-label spacing, physical line boundaries and source marks;
- create `works/socrates/pages/0042.md` only after verification;
- update `SCENE5_PAGE_VERIFICATION.md`, work/source page maps, metadata/readmes and handover;
- expected durable total after success: **16/17 verified**, Scene 5 **3/4**;
- do **not** process scan 43 in the same activity;
- do **not** assemble `காட்சி—5` until scans 40–43 are all verified;
- do not begin `சேரன் செங்குட்டுவன்`.

When I say **“Proceed with next activity”**, execute this exact activity directly without asking me to choose a routine next step.
