# Kalaignar Stage Plays — Handover

Repository: `pugazg/kalaignar-stage-plays`, branch `main`.

## Startup rule

Always fetch live `main` first and treat it as authoritative. Preserve newer durable state and never reopen completed work unless the user explicitly requests it.

Permanent workflow: `STAGE_PLAY_PROCESSING_GUIDE.md`.

Controlling composite source: `TVA_BOK_0065576_நான்மணி_மாலை.pdf` — **54 scans** — SHA-256 `18d2b1405544b03507e9f92067d287cb28f5a92eaf02bed7054e6e78e5e38c89`.

## Locked completed work

- `பரதாயணம்`: Tamil archive/assembly PASS; independent English translation PASS.
- `அனார்கலி`: Tamil page/assembly fidelity PASS.
- `சாக்ரடீஸ்`: **17/17 pages verified; 15/15 dramatic-body pages verified; 5/5 scenes assembled; all scene fidelity gates PASS**.
- Silappathikaram completed state remains locked and unchanged.

## Active work — சேரன் செங்குட்டுவன்

Controlling Tamil extent:

- scans **44–53**;
- printed pp. **39–48**;
- printed title: **சேரன் செங்குட்டுவன்**;
- source-printed dramatic scenes: **4**;
- 2009 published-English witness: **secondary only**.

### First-pass / source rule

The user supplied a Gemini word-to-word first pass covering the Cheran source extent in the current chat.

For Cheran, follow the permanent source-first old-glyph policy:

- Gemini is a comparison baseline, not the controlling authority;
- the Tamil scan is controlling;
- do not change a plausible first-pass reading merely because a modern spelling, grammar or semantic form seems more familiar;
- if the scan is unambiguous, use the scan-supported form and document the difference;
- do not use the English witness to reconstruct Tamil.

### Scan 44 / printed p.39 — COMPLETE

Durable files:

- `works/cheran-senguttuvan/pages/0044.md` — **verified**;
- `works/cheran-senguttuvan/SCENE1_PAGE_VERIFICATION.md` — Scene-1 page gate **1/2 PASS**;
- `works/cheran-senguttuvan/indexes/page-map.md` — created.

Scan-44 controls include:

- printed title displayed as `சேரன்` / `செங்குட்டுவன்`;
- pre-scene voice-over beginning `நாடகத் துவக்கத்திற்கு முன்பு குரல்:`;
- source heading `காட்சி — 1`;
- labels `மன்னர்கள்:`, `கனகர்:`, `விஜயர்:`, `கன:`, `மன்:`, `தமிழ்நாட்டுப் புலவர்:`, `விஜ.`;
- printed page number `39`;
- no scene-closing `*` on scan 44.

Unambiguous first-pass/source differences recorded:

- `காட்சி-1` → `காட்சி — 1`;
- `வேந்தர் குலதிலக` → `வேந்தர்குலதிலக`;
- `கனக விஐயர்` → `கனக விஜயர்`;
- `கன :` → `கன:`.

Current Cheran progress:

- Tamil pages verified: **1/10**;
- Scene-1 page gate: **1/2**;
- scenes assembled from verified Tamil: **0/4**.

## Exact next activity

Process **`சேரன் செங்குட்டுவன்` scan 45 / printed p.40 only** as the Scene-1 continuation/closing page-verification activity.

Requirements:

- fetch live `main` first and read the permanent guide/current handover/work page-map/page record;
- inspect scan 45 directly from the controlling PDF;
- use the user-supplied Gemini first pass as the comparison baseline if it is available in the chat; in a fresh chat, ask for only the relevant first-pass segment rather than inventing it from memory;
- preserve source wording, punctuation, speaker labels, stage directions, physical line boundaries and source marks;
- create `works/cheran-senguttuvan/pages/0045.md` only after direct verification;
- update `SCENE1_PAGE_VERIFICATION.md`, work/source progress, page maps, README files and handover;
- expected durable state after success: **2/10 pages verified**, Scene-1 page gate **2/2 COMPLETE**;
- do **not** process scan 46 in the same activity;
- do **not** assemble Scene 1 in the same activity;
- do **not** use the English witness to fill Tamil gaps.

## Permanent safeguards

- live `main` controls repository state;
- PDF remains external;
- no silent lexical normalization or semantic reconstruction;
- ambiguous old-glyph readings are not overridden by expectation;
- scene assembly occurs only after every source page for that scene is verified;
- English witnesses are secondary only;
- translation must derive from verified Tamil;
- `அந்தணர்` is not automatically “Brahmin” in future translation work.
