# Kalaignar Stage Plays — Handover

Repository: `pugazg/kalaignar-stage-plays`, branch `main`.

## Startup rule

Always fetch live `main` first and treat it as authoritative. Preserve newer durable state and never reopen completed work unless the user explicitly requests it.

Permanent workflow: `STAGE_PLAY_PROCESSING_GUIDE.md`.

## Active work — மணிமகுடம்

The user has explicitly authorized `மணிமகுடம்` as the next work.

Controlling source:

`TVA_BOK_0064143_மணி_மகுடம்.pdf`

Durable source intake:

- source SHA-256: `a629509c3404fcc5c2844f5b693e72a41aca03ad2e2494588807af4ff8f16f3b`;
- file size: **187,091,728 bytes**;
- physical PDF pages: **170**;
- user catalog metadata: title `மணிமகுடம்`, author `கலைஞர் மு. கருணாநிதி`, publisher `பாரதி பதிப்பகம்`, sixth edition 2010;
- scan 11 independently supports **Sixth Edition: May 2010** and **Rs. 40.00**;
- scans 12–13: author preface `என்னுரை`, dated **22.7.1986**;
- scan 14: **காட்சி 1** begins;
- scan 145: **காட்சி 42** begins;
- scan 152: **காட்சி 43** begins;
- scan 162: **காட்சி 44 / 45 / 46** begin on the same physical page;
- scan 169: printed page **160**, **காட்சி 47**, closure **`(முடிவுற்றது)`**;
- scan 170: back-cover publisher catalogue / advertisement.

Work files created:

- `works/manimagudam/README.md`;
- `works/manimagudam/metadata/source.md`;
- `works/manimagudam/indexes/page-map.md`.

### Source-boundary safeguard

The conversation file-preview layer exposed only the first **150** pages. Raw-PDF inspection of the attached bytes independently established **170** pages, and scans **151–170** were directly rendered and visually inspected. Future processing must never truncate the work at scan 150.

### Performance-history provenance safeguard

The user-supplied catalog description states a **1962 Madurai DMK conference** performance. The currently inspected controlling scan instead/differently establishes additional performance evidence:

- scan 4: **May 1956**, DMK second state conference, Tiruchirappalli, staging by the **S. S. Rajendran** troupe;
- scan 5: **September 1963** staging associated with the Murasoli drama troupe under **Anna's leadership**.

The inspected scan does not itself verify the 1962 Madurai statement. Keep that statement in the user-supplied catalog layer pending a separate source; do not silently erase it or promote it to source-derived metadata.

### Current `மணிமகுடம்` checkpoint

- source intake / physical survey: **REGISTERED**;
- page-level Tamil transcription: **0 / 170 verified**;
- scene assembly: **not started**;
- English translation: **not authorized / not started**.

### Exact next activity

Process **scans 1–13** page by page from the controlling scan:

1. create archival page records;
2. transcribe exact printed text/captions where applicable;
3. describe photographs without treating image content as literary text;
4. preserve dates, punctuation and visible source wording;
5. distinguish later/copy-specific marks from publication text;
6. update `works/manimagudam/indexes/page-map.md` with individual statuses.

After scans 1–13 are complete, begin **scan 14 / காட்சி 1**.

Do not begin English translation unless the user explicitly authorizes a later translation phase.

## Closed `கலைஞரின் நான்மணி மாலை` state

Controlling composite Tamil source: `TVA_BOK_0065576_நான்மணி_மாலை.pdf` — **54 scans** — SHA-256 `18d2b1405544b03507e9f92067d287cb28f5a92eaf02bed7054e6e78e5e38c89`.

### Locked Tamil archival state

- `பரதாயணம்`: Tamil archive/assembly **PASS**.
- `அனார்கலி`: **9/9 pages verified; 4/4 scenes; fidelity PASS**.
- `சாக்ரடீஸ்`: **17/17 pages verified; 5/5 scenes; fidelity PASS**.
- `சேரன் செங்குட்டுவன்`: **10/10 pages verified; 4/4 scenes; fidelity PASS**.
- composite source coverage: `sources/naanmani-malai-tamil/COVERAGE_AUDIT.md` — **54/54 scans, PASS / COMPLETE**.

Physical partition remains **1–5 / 6–17 / 18–26 / 27–43 / 44–53 / 54 = 54**, with **0 gaps, 0 overlaps and 0 pending composite-source pages**.

### English-phase closed state

`sources/naanmani-malai-tamil/ENGLISH_PHASE_CLOSURE_AUDIT.md` — **PASS / COMPLETE**.

Independent English translations:

- `பரதாயணம்` — **PASS / COMPLETE**;
- `அனார்கலி` — **PASS / COMPLETE**;
- `சாக்ரடீஸ்` — **PASS / COMPLETE**;
- `சேரன் செங்குட்டுவன்` — **PASS / COMPLETE**.

Count: **4 / 4 COMPLETE**.

Applicable 2009 published-English witness plays: **3** — `Anarkali`, `Cheran Senguttuvan`, `Socrates`.
Completed applicable comparisons: **3 / 3 PASS / COMPLETE**.
`பரதாயணம்`: **NOT APPLICABLE**, not pending.

No verified Tamil or reviewed independent English wording was changed merely to harmonize with a published witness.

## Permanent safeguards

- live `main` controls repository state;
- source PDFs remain external;
- no silent lexical normalization or semantic reconstruction;
- ambiguous old-glyph readings are not overridden by expectation;
- independent translation derives from verified Tamil;
- published English remains a secondary witness, never a backdoor authority over Tamil;
- comparison and revision are separate decisions;
- completed `நான்மணி மாலை` Tamil or reviewed English is not reopened without explicit user direction;
- `அந்தணர்` is not automatically `Brahmin` in future translation work.