# Kalaignar Stage Plays — Handover

Repository: `pugazg/kalaignar-stage-plays`, branch `main`.

## Startup rule

Always fetch live `main` first. The checkpoint recorded below was current when this handover was written, but a newer live commit must take precedence.

Checkpoint before this handover update: `26dc146f13956e7be6d45014186bd79f43c4d4b6` — `Reconcile Socrates intro with Gemini and source`.

Permanent workflow: `STAGE_PLAY_PROCESSING_GUIDE.md`.

Controlling composite source: `TVA_BOK_0065576_நான்மணி_மாலை.pdf` — **54 scans** — SHA-256 `18d2b1405544b03507e9f92067d287cb28f5a92eaf02bed7054e6e78e5e38c89`.

The PDF itself is not committed. In a fresh chat, attach the controlling PDF again before page-level visual verification.

## Locked completed work

- `பரதாயணம்`: Tamil archive/assembly PASS; independent English translation PASS.
- `அனார்கலி`: 9/9 Tamil pages verified; 4/4 scenes assembled; fidelity PASS.
- Silappathikaram state remains unchanged and locked.

Do not reopen these completed works during the active `சாக்ரடீஸ்` batch unless the user explicitly requests it.

## Active work — சாக்ரடீஸ்

Work folder: `works/socrates/`.

Controlling extent:

- scans **27–43**;
- printed pp. **22–38**;
- scans **27–28**: introductory note;
- scans **29–43**: five source-printed dramatic scenes.

### Introductory note — corrected PASS / durable

Scans **27–28** were re-reconciled after the user identified that an earlier assistant pass had misread old Tamil glyphs and overwritten the supplied Gemini transcription with familiar-looking alternatives.

Durable result:

- `pages/0027.md` — scan 27 / printed p.22 — **verified**;
- `pages/0028.md` — scan 28 / printed p.23 — **verified**;
- intro: **2/2 verified**;
- total durable `சாக்ரடீஸ்` progress: **2/17 pages verified**;
- reconciliation record: `works/socrates/INTRO_RECONCILIATION.md`.

Do **not** revert these restored readings:

- `மார்க்சும், எஞ்சல்சும்`;
- `ஹெகல்`;
- `‘ஜாடை’ காட்டினான்`;
- `தூசு நிகர் காரணங்களைக்கொண்டு`;
- `ஆஸ்திகப்பழமாக்கியிருக்கிறார்`;
- `நானோ`;
- `சபைன்`.

`‘சோக்ரதர்’` remains exactly as retained in the Gemini/source working text; do not expand, regularize or reinterpret it.

Permanent rule established by the user correction:

> **For plausible old-Tamil-glyph readings, retain Gemini unless direct scan evidence is unambiguous. Never replace Gemini merely because another spelling, name or grammatical form looks more familiar.**

See the expanded rule in `STAGE_PLAY_PROCESSING_GUIDE.md` §1A.

### Structural scene map — durable

1. `காட்சி—1` — scans **29–31** / pp.24–26;
2. `காட்சி—2` — scan **32** / p.27;
3. `காட்சி—3` — scan **33** / p.28;
4. `காட்சி—4` — scans **34–39** / pp.29–34;
5. `காட்சி—5` — scans **40–43** / pp.35–38.

### Previous-chat provisional work — NOT durable

In the immediately preceding chat activity, scans **29–31** / pp.24–26 (`காட்சி—1`) were visually inspected at normal and enlarged views. Structural facts were confirmed:

- scan 29 opens source-printed `காட்சி—1` at `சாக்ரடீசின் வீட்டு வாயில்`;
- the scene continues through scans 30–31;
- scan 31 closes the scene with a printed `*`.

However, **no `pages/0029.md`–`0031.md` files were committed and none of these three pages was marked verified**. Several scan-31 old-glyph-sensitive readings were still being checked when the previous execution ended.

Therefore the durable count remains **2/17**, not 5/17. A new chat must not copy provisional wording from memory or claim those pages are complete. Re-open scans 29–31 and perform the page-level reconciliation again under the Gemini/old-glyph policy.

## Exact next activity

Complete **`சாக்ரடீஸ்` `காட்சி—1` page verification only**:

- scans **29–31** / printed pp. **24–26**;
- start from the user-supplied Gemini first-pass where available;
- compare every word, punctuation mark, speaker label, stage direction and physical line/page boundary to the scan;
- preserve Gemini for ambiguous old-glyph readings;
- change Gemini only where scan evidence is unambiguous;
- create `works/socrates/pages/0029.md`, `0030.md`, `0031.md`;
- update `works/socrates/indexes/page-map.md`, work README/source metadata, source-level page map/README, root README and this handover as appropriate;
- expected progress after a clean pass: **5/17 pages verified**;
- **do not assemble `காட்சி—1` in the same activity**;
- do not begin `காட்சி—2` or `சேரன் செங்குட்டுவன்` in that activity.

After that page-verification commit, the next distinct activity should be `காட்சி—1` assembly from verified page records plus page-record ↔ scene fidelity audit.

## Fresh-chat mandatory reading order

Before making any repository change in a fresh chat, read completely:

1. `STAGE_PLAY_PROCESSING_GUIDE.md`;
2. `HANDOVER.md`;
3. `NEXT_CHAT_PROMPT.md`;
4. `works/socrates/INTRO_RECONCILIATION.md`;
5. `works/socrates/README.md`;
6. `works/socrates/metadata/source.md`;
7. `works/socrates/indexes/page-map.md`;
8. `works/socrates/pages/0027.md`;
9. `works/socrates/pages/0028.md`;
10. `sources/naanmani-malai-tamil/README.md`;
11. `sources/naanmani-malai-tamil/indexes/page-map.md`.

Then inspect live `main` again before writing, so concurrent/newer work is not overwritten.

## Remaining Tamil source sequence

After `காட்சி—1`:

- `காட்சி—2` — scan 32 / p.27;
- `காட்சி—3` — scan 33 / p.28;
- `காட்சி—4` — scans 34–39 / pp.29–34;
- `காட்சி—5` — scans 40–43 / pp.35–38;
- only after `சாக்ரடீஸ்` Tamil archival work reaches its intended gate: `சேரன் செங்குட்டுவன்`, scans 44–53 / pp.39–48.

## Permanent safeguards

- source scan controls; PDF remains external;
- Gemini is a working baseline, not permission to invent text;
- old glyphs are not to be modernized by expectation;
- user-rejected assistant corrections stay withdrawn unless new unambiguous source evidence appears;
- 2009 published-English witnesses are secondary only and cannot reconstruct Tamil;
- scene assembly occurs only after all source pages for that scene are verified;
- translation is a later phase based on verified Tamil;
- `அந்தணர்` is not automatically “Brahmin” in any future translation; preserve Kalaignar's terminology distinctions.
