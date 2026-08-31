# Next Chat Prompt — Continue `சாக்ரடீஸ்` in Kalaignar Stage Plays

Continue the Kalaignar Stage Plays archival project directly in:

`https://github.com/pugazg/kalaignar-stage-plays`

Branch: `main`.

Use the GitHub connector and work directly on `main`.

Controlling source PDF: `TVA_BOK_0065576_நான்மணி_மாலை.pdf`.

**Attach the controlling PDF again in a fresh chat before new page-level visual work.**

## Live-state rule

Fetch live GitHub `main` **FIRST** and treat it as authoritative. Scene-2 lexical rollback remains locked, Scenes 1–3 have assembly/fidelity PASS, and Scene 4 has begun with scan 34 verified. Preserve any newer live state and never restore withdrawn assistant word corrections.

## Mandatory startup reading

Read completely before any write:

1. `STAGE_PLAY_PROCESSING_GUIDE.md`
2. `HANDOVER.md`
3. `NEXT_CHAT_PROMPT.md`
4. `works/socrates/INTRO_RECONCILIATION.md`
5. `works/socrates/SCENE1_PAGE_VERIFICATION.md`
6. `works/socrates/ASSEMBLY_FIDELITY_REVIEW.md`
7. `works/socrates/SCENE2_PAGE_VERIFICATION.md`
8. `works/socrates/SCENE2_ASSEMBLY_FIDELITY_REVIEW.md`
9. `works/socrates/SCENE3_PAGE_VERIFICATION.md`
10. `works/socrates/SCENE3_ASSEMBLY_FIDELITY_REVIEW.md`
11. `works/socrates/SCENE4_PAGE_VERIFICATION.md`
12. `works/socrates/README.md`
13. `works/socrates/metadata/source.md`
14. `works/socrates/indexes/page-map.md`
15. `works/socrates/pages/0034.md`
16. `sources/naanmani-malai-tamil/README.md`
17. `sources/naanmani-malai-tamil/indexes/page-map.md`

Then re-fetch live `main` immediately before the first write.

## Durable state

Completed/locked:

- `பரதாயணம்` — Tamil archive/assembly PASS; independent English translation PASS.
- `அனார்கலி` — Tamil archive/assembly PASS.
- Silappathikaram complete state remains locked.

Active work: `சாக்ரடீஸ்`.

- source extent: scans **27–43** / pp.22–38;
- introductory note scans 27–28: **2/2 verified**;
- `காட்சி—1` scans 29–31: **page gate + assembly/fidelity PASS**;
- `காட்சி—2` scan 32: **page gate + assembly/fidelity PASS after lexical rollback**;
- `காட்சி—3` scan 33: **page gate + assembly/fidelity PASS**;
- `காட்சி—4` scans 34–39: **1/6 verified (scan 34 / p.29)**;
- total Socrates page progress: **8/17 verified**;
- dramatic page progress: **6/15**;
- scenes assembled: **3/5**.

## Critical current transcription rule

The user explicitly instructed:

- **For words, keep Gemini's transcription.**
- For **heading, punctuation, long dash, speaker-label spacing, physical line breaks and final source marks**, keep what is found in the controlling scan.

Do not make assistant word corrections based on visual interpretation, grammar, familiar spelling or sentence meaning unless the user explicitly requests a word-level recheck.

Scan 34 is durably recorded in `pages/0034.md`. Its scan-controlled heading is `காட்சி — 4`; speaker labels include `அனி :` and `நீதிமன்றத் தலைவர் :`; the page has no Scene-4 closing `*`.

The 2009 published-English witness remains secondary and cannot reconstruct Tamil.

## Exact next activity

Process **`சாக்ரடீஸ்` `காட்சி—4` scan 35 / printed p.30 only** as the next Scene-4 page-verification slice.

Requirements:

- use the user-supplied Gemini first-pass as the lexical baseline;
- **retain Gemini's words exactly**;
- use direct scan inspection only for punctuation, long dash, speaker-label spacing, physical line boundaries and final source marks;
- create `works/socrates/pages/0035.md` only after verification;
- update `SCENE4_PAGE_VERIFICATION.md`, work/source page maps, metadata/readmes and handover after the page gate;
- expected durable total after success: **9/17 verified**, Scene 4 **2/6**;
- do **not** process scan 36 in the same activity;
- do **not** assemble `காட்சி—4` until all scans 34–39 are verified;
- do not begin `சேரன் செங்குட்டுவன்`.

When I say **“Proceed with next activity”**, execute this exact activity directly without asking me to choose a routine next step.
