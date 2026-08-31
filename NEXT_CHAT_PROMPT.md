# Next Chat Prompt — Continue `சாக்ரடீஸ்` in Kalaignar Stage Plays

Continue the Kalaignar Stage Plays archival project directly in:

`https://github.com/pugazg/kalaignar-stage-plays`

Branch: `main`

Use the GitHub connector and work directly on `main`.

Controlling source PDF:

`TVA_BOK_0065576_நான்மணி_மாலை.pdf`

**Attach the controlling PDF again in the fresh chat before page-level visual work.**

## Live-state rule

Fetch live GitHub `main` **FIRST** and treat it as authoritative. Do not assume the checkpoint below is still current and do not overwrite newer work.

Checkpoint when this prompt was prepared:

`26dc146f13956e7be6d45014186bd79f43c4d4b6`

Commit: `Reconcile Socrates intro with Gemini and source`

If live `main` has advanced, preserve the newer state and continue from it.

## Mandatory startup reading

Before making any repository change, read completely:

1. `STAGE_PLAY_PROCESSING_GUIDE.md`
2. `HANDOVER.md`
3. `NEXT_CHAT_PROMPT.md`
4. `works/socrates/INTRO_RECONCILIATION.md`
5. `works/socrates/README.md`
6. `works/socrates/metadata/source.md`
7. `works/socrates/indexes/page-map.md`
8. `works/socrates/pages/0027.md`
9. `works/socrates/pages/0028.md`
10. `sources/naanmani-malai-tamil/README.md`
11. `sources/naanmani-malai-tamil/indexes/page-map.md`

Then re-fetch live `main` immediately before the first write.

## Durable project state

Completed and locked:

- `பரதாயணம்` — Tamil page verification/assembly PASS; independent English translation PASS.
- `அனார்கலி` — 9/9 Tamil pages verified; 4/4 scenes assembled; fidelity PASS.
- Silappathikaram completed state must remain unchanged.

Active work: **`சாக்ரடீஸ்`**.

Source extent:

- scans **27–43**;
- printed pp. **22–38**;
- scans **27–28** introductory note;
- five dramatic scenes after the introduction.

Durable `சாக்ரடீஸ்` progress:

- scan 27 / p.22 — verified;
- scan 28 / p.23 — verified;
- introductory note: **2/2 verified**;
- total work: **2/17 verified**.

The intro was re-reconciled after a prior assistant incorrectly overwrote old-glyph readings. Do not revert the restored forms recorded in `works/socrates/INTRO_RECONCILIATION.md`, including:

`மார்க்சும், எஞ்சல்சும்`, `ஹெகல்`, `‘ஜாடை’ காட்டினான்`, `தூசு நிகர் காரணங்களைக்கொண்டு`, `ஆஸ்திகப்பழமாக்கியிருக்கிறார்`, `நானோ`, `சபைன்`.

Keep `‘சோக்ரதர்’` exactly as retained; do not expand or modernize it.

## Critical old-glyph rule

The user explicitly corrected the earlier assistant behaviour.

**Use Gemini as the baseline for plausible old-Tamil-glyph readings. Do not replace Gemini because another spelling/name/grammar looks more familiar. Change Gemini only when the controlling scan is unambiguous. If ambiguous, retain Gemini and document the ambiguity.**

If the original Gemini first-pass segment is not visible in the fresh chat, do **not** reconstruct it from memory. Use durable repository text where it exists. For a disputed new page where the baseline is required but unavailable, ask for only the relevant Gemini segment rather than inventing it.

The 2009 published-English witness is secondary only and must not be used to reconstruct Tamil.

## Scene structure

1. `காட்சி—1` — scans **29–31** / pp.24–26
2. `காட்சி—2` — scan **32** / p.27
3. `காட்சி—3` — scan **33** / p.28
4. `காட்சி—4` — scans **34–39** / pp.29–34
5. `காட்சி—5` — scans **40–43** / pp.35–38

## Important provisional-state warning

In the previous chat, scans **29–31** were visually inspected and enlarged, but the activity ended before page records could be completed and committed.

No `pages/0029.md`, `0030.md` or `0031.md` exists at the durable checkpoint, and none of those pages is verified. The durable total is still **2/17**.

The only safe structural facts from that provisional inspection are:

- scan 29 opens `காட்சி—1` at `சாக்ரடீசின் வீட்டு வாயில்`;
- the scene continues through scans 30–31;
- scan 31 closes with a printed `*`.

Do not reuse uncommitted provisional wording from memory.

## Exact next activity

Process **`சாக்ரடீஸ்` `காட்சி—1` scans 29–31 / printed pp.24–26** as one page-verification batch.

Requirements:

- visually reconcile all three scans against Gemini/source under the old-glyph rule;
- preserve exact wording, punctuation, speaker labels, stage directions, repetitions and physical line/page boundaries;
- create `works/socrates/pages/0029.md`, `0030.md`, `0031.md` only after direct visual verification;
- explicitly record any Gemini discrepancy that is genuinely scan-proven;
- update work/source page maps and handover after the batch;
- expected durable total after success: **5/17 verified**;
- **do not assemble `காட்சி—1` in the same activity**;
- do not begin scan 32 / `காட்சி—2`;
- do not begin `சேரன் செங்குட்டுவன்`.

After the three page records are committed and verified, the following distinct activity is to assemble `காட்சி—1` exclusively from those verified page records and run the page-record ↔ scene fidelity audit.

When I say **“Proceed with next activity”**, execute this exact next activity directly without asking me to choose a routine next step.
