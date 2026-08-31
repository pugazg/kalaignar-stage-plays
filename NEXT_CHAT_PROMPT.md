# Next Chat Prompt — Continue `சாக்ரடீஸ்` in Kalaignar Stage Plays

Continue the Kalaignar Stage Plays archival project directly in:

`https://github.com/pugazg/kalaignar-stage-plays`

Branch: `main`.

Use the GitHub connector and work directly on `main`.

Controlling source PDF: `TVA_BOK_0065576_நான்மணி_மாலை.pdf`.

**Attach the controlling PDF again in a fresh chat before new page-level visual work.**

## Live-state rule

Fetch live GitHub `main` **FIRST** and treat it as authoritative. Scene-2 page verification was corrected after the user rejected assistant word-level substitutions. Preserve the newer lexical-rollback state and never restore the withdrawn word corrections.

## Mandatory startup reading

Read completely before any write:

1. `STAGE_PLAY_PROCESSING_GUIDE.md`
2. `HANDOVER.md`
3. `NEXT_CHAT_PROMPT.md`
4. `works/socrates/INTRO_RECONCILIATION.md`
5. `works/socrates/SCENE1_PAGE_VERIFICATION.md`
6. `works/socrates/ASSEMBLY_FIDELITY_REVIEW.md`
7. `works/socrates/SCENE2_PAGE_VERIFICATION.md`
8. `works/socrates/README.md`
9. `works/socrates/metadata/source.md`
10. `works/socrates/indexes/page-map.md`
11. `works/socrates/scenes/01.md`
12. `works/socrates/pages/0032.md`
13. `sources/naanmani-malai-tamil/README.md`
14. `sources/naanmani-malai-tamil/indexes/page-map.md`

Then re-fetch live `main` immediately before the first write.

## Durable state

Completed/locked:

- `பரதாயணம்` — Tamil archive/assembly PASS; independent English translation PASS.
- `அனார்கலி` — Tamil archive/assembly PASS.
- Silappathikaram complete state remains locked.

Active work: `சாக்ரடீஸ்`.

- source extent: scans **27–43** / pp.22–38;
- introductory note scans 27–28: **2/2 verified**;
- `காட்சி—1` scans 29–31: **3/3 verified; assembly/fidelity PASS**;
- `காட்சி—2` scan 32 / p.27: **1/1 verified after user-directed lexical rollback; assembly pending**;
- total Socrates page progress: **6/17 verified**;
- dramatic page progress: **4/15**;
- scenes assembled: **1/5**.

## Critical current transcription rule

The user explicitly instructed:

- **For words, keep Gemini's transcription.**
- For **heading, punctuation, long dash, speaker-label spacing, physical line breaks and final `*`**, keep what is found in the controlling scan.

Do not make assistant word corrections based on visual interpretation, grammar, familiar spelling or sentence meaning unless the user explicitly requests a word-level recheck.

For Scene 2 specifically, the prior assistant readings `கவிஞனும் மெலிடசும்` and `அரசியல் நிபுணனும் நீயும்` are wrong and withdrawn. Corrected verified `pages/0032.md` retains Gemini's:

- `கவிஞனாம் மெலிடசும்`;
- `அரசியல் நிபுணனாம் நீயும்`.

The scan-controlled heading, punctuation, long dash, speaker-label spacing, physical line breaks and final `*` remain preserved in that page record.

The 2009 published-English witness remains secondary and cannot reconstruct Tamil.

## Exact next activity

Assemble **`சாக்ரடீஸ்` `காட்சி—2` only** from corrected verified `works/socrates/pages/0032.md`.

Requirements:

- `pages/0032.md` is the sole textual authority for assembly;
- mechanically join legitimate print-line splits only;
- retain Gemini lexical words exactly;
- preserve scan-controlled punctuation, speaker-label spacing, long dash, repetitions, stage directions and final `*`;
- create the assembled Scene-2 file under `works/socrates/scenes/`;
- extend/create the page-record ↔ scene fidelity audit and require PASS before advancing;
- **do not start scan 33 / `காட்சி—3` in the same activity**;
- do not start `சேரன் செங்குட்டுவன்`.

After Scene-2 assembly/fidelity PASS, the next distinct activity is `காட்சி—3` page verification at scan **33** / printed p.28 under the same Gemini-words / scan-typography rule.

When I say **“Proceed with next activity”**, execute this exact activity directly without asking me to choose a routine next step.
