# Kalaignar Stage Plays — Handover

Repository: `pugazg/kalaignar-stage-plays`, branch `main`.

## Startup rule

Always fetch live `main` first and treat it as authoritative. Preserve newer durable state and never restore withdrawn assistant word corrections.

Permanent workflow: `STAGE_PLAY_PROCESSING_GUIDE.md`.

Controlling composite source: `TVA_BOK_0065576_நான்மணி_மாலை.pdf` — **54 scans** — SHA-256 `18d2b1405544b03507e9f92067d287cb28f5a92eaf02bed7054e6e78e5e38c89`.

## Locked completed work

- `பரதாயணம்`: Tamil archive/assembly PASS; independent English translation PASS.
- `அனார்கலி`: 9/9 Tamil pages verified; 4/4 scenes assembled; fidelity PASS.
- `சாக்ரடீஸ்`: **17/17 Tamil pages verified; 15/15 dramatic-body pages verified; 5/5 scenes assembled; page-record fidelity PASS for all scenes**.
- Silappathikaram completed state remains locked and unchanged.

Do not reopen completed work unless the user explicitly requests it.

## `சாக்ரடீஸ்` final durable state

Controlling extent: scans **27–43** / printed pp. **22–38**.

- intro scans 27–28: **2/2 verified**;
- `காட்சி—1`: **page gate + assembly/fidelity PASS**;
- `காட்சி—2`: **page gate + assembly/fidelity PASS after user-directed lexical rollback**;
- `காட்சி—3`: **page gate + assembly/fidelity PASS**;
- `காட்சி — 4`: **6/6 page gate + assembly/fidelity PASS**;
- `காட்சி—5.`: **4/4 page gate + assembly/fidelity PASS**;
- total page verification: **17/17 COMPLETE**;
- dramatic-body pages: **15/15 COMPLETE**;
- scenes assembled: **5/5 COMPLETE**.

Final Scene-5 durable artifacts:

- `works/socrates/pages/0040.md`–`0043.md` — verified;
- `works/socrates/SCENE5_PAGE_VERIFICATION.md` — **4/4 PASS / COMPLETE**;
- `works/socrates/scenes/05.md` — assembled exclusively from verified page records;
- `works/socrates/SCENE5_ASSEMBLY_FIDELITY_REVIEW.md` — **PASS**.

Scene-5 assembly integrity:

- verified page records used: **4/4**;
- page-record ↔ scene fidelity: **PASS**;
- unresolved assembly discrepancies: **0**;
- speaker-label count mismatches: **0**;
- assistant lexical substitutions introduced: **0**;
- final centered `*` retained: **yes**.

The user-directed Gemini-word / scan-typography rule remains part of the durable `சாக்ரடீஸ்` archival record. Assembly itself uses verified page records as the sole textual authority.

The 2009 published-English witness remains secondary and cannot reconstruct controlling Tamil.

## Next active work — சேரன் செங்குட்டுவன்

Controlling Tamil source remains the same composite PDF.

Registered extent:

- scans **44–53**;
- printed pages **39–48**;
- printed title **சேரன் செங்குட்டுவன்**;
- Tamil page-level verification: **not started**;
- source-printed dramatic scenes: **4** according to the existing structural registry;
- 2009 published-English witness: already verified but **secondary only**.

Existing work registry:

- `works/cheran-senguttuvan/README.md`;
- `works/cheran-senguttuvan/metadata/source.md`;
- composite source registry under `sources/naanmani-malai-tamil/`.

## Exact next activity

Process **`சேரன் செங்குட்டுவன்` scan 44 / printed p.39 only** as the first Tamil page-verification slice.

Requirements:

- fetch live `main` first and read the permanent guide plus current handover/work/source registry;
- inspect scan 44 directly from the controlling PDF;
- use any user-supplied first-pass text only as a comparison baseline; do not invent unavailable first-pass wording from memory;
- preserve source wording, punctuation, speaker labels, stage directions, physical line boundaries and source marks under `STAGE_PLAY_PROCESSING_GUIDE.md`;
- create the first `works/cheran-senguttuvan/pages/` record only after direct verification;
- update the Cheran work/source page-map and durable handover state after verification;
- do **not** process scan 45 in the same activity;
- do **not** use the English witness to reconstruct Tamil.

## Permanent safeguards

- live `main` controls repository state;
- PDF remains external;
- controlling Tamil scan outranks secondary witnesses;
- user-rejected assistant word corrections stay withdrawn in completed Socrates records;
- no silent lexical normalization, semantic reconstruction or speaker-label standardization;
- scene assembly occurs only after every source page for that scene is verified;
- English witnesses are secondary only;
- translation is later and must derive from verified Tamil;
- `அந்தணர்` is not automatically “Brahmin” in future translation work.
