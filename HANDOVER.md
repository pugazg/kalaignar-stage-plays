# Kalaignar Stage Plays — Handover

Repository: `pugazg/kalaignar-stage-plays`, branch `main`.

## Startup rule

Always fetch live `main` first and treat it as authoritative. Preserve newer durable state and never reopen completed work unless the user explicitly requests it.

Permanent workflow: `STAGE_PLAY_PROCESSING_GUIDE.md`.

## Active work — மணிமகுடம்

Controlling source: `TVA_BOK_0064143_மணி_மகுடம்.pdf`.

Durable source identity:

- SHA-256: `a629509c3404fcc5c2844f5b693e72a41aca03ad2e2494588807af4ff8f16f3b`;
- file size: **187,091,728 bytes**;
- physical PDF pages: **170**;
- sixth edition scan statement: **May 2010**, price **Rs.40.00**;
- scan 169: printed page 160, `காட்சி 47`, `(முடிவுற்றது)`;
- scan 170: publisher catalogue / advertisement.

### Current durable checkpoint

- scans **1–13** front matter: **13 / 13 VERIFIED**;
- scans **14–140** dramatic body: **127 / 127 VERIFIED**;
- overall page-level status: **140 / 170 verified**;
- durable page records: `works/manimagudam/pages/0001.md` through `0140.md`;
- `காட்சி 1`–`காட்சி 40`: page-level transcription complete;
- `காட்சி 41`: begins on scan 141 / printed page 132 and is the next unprocessed scene;
- scene assembly: **not started**;
- English translation: **not authorized / not started**.

Completed fidelity records:

- `works/manimagudam/SCANS_0015_0039_VERIFICATION.md` — PASS / COMPLETE;
- `works/manimagudam/SCANS_0041_0065_VERIFICATION.md` — **25 / 25 VERIFIED, 0 unresolved readings**;
- `works/manimagudam/SCANS_0066_0090_VERIFICATION.md` — **25 / 25 VERIFIED, 0 unresolved readings**;
- `works/manimagudam/SCANS_0091_0115_VERIFICATION.md` — **25 / 25 VERIFIED, 0 unresolved readings**;
- `works/manimagudam/SCANS_0116_0140_VERIFICATION.md` — **25 / 25 VERIFIED, 0 unresolved readings**.

The scans 116–140 gate preserves enlarged-source readings including `பொசுக்கியதாக வேண்டும்!`, `உளவறியப் போயிருக்கிறார்!`, `சாஜூரைத் தவிர`, `அல்லியை அள்ளிப் பருக`, `நாமே அதையெல்லாம்`, `(முணுமுணுத்தபடி)`, `மாதேன்மத்தர்கள்!`, and `கல்நாட்டு`.

### Scene checkpoint through scan 140

- `காட்சி 29`: closes scan 117.
- `காட்சி 30`: scan 117–121.
- `காட்சி 31`: scan 121–122.
- `காட்சி 32`: scan 122–127.
- `காட்சி 33`: scan 127–131.
- `காட்சி 34`: complete on scan 131.
- `காட்சி 35`: scan 131–132.
- `காட்சி 36`: scan 132–135.
- `காட்சி 37`: scan 135–136.
- `காட்சி 38`: complete on scan 136.
- `காட்சி 39`: scan 136–137.
- `காட்சி 40`: scan 137–140; closes scan 140.
- `காட்சி 41`: begins scan 141.

Important physical continuities in the completed batch:

- scan 116→117 continues அல்லி's utterance without a repeated speaker label;
- scan 122→123 continues அல்லி's utterance;
- scan 124→125 continues புதுமைப்பித்தன்;
- scan 127→128 continues கலாராணி;
- scan 130→131 continues the action after அல்லி's final line;
- scan 137→138 continues குருநாதர் without a repeated speaker label.

### Source-boundary safeguard

The conversation preview exposed only 150 pages. Raw-PDF inspection independently established **170 physical scans** and scans 151–170 were rendered during intake. Never truncate future work at scan 150.

### Performance-history provenance safeguard

User-supplied catalog context states a **1962 Madurai DMK conference** performance. The controlling scan independently records:

- scan 4: May 1956, DMK second state conference, Tiruchirappalli, S. S. Rajendran troupe;
- scan 5: September 1963 staging associated with the Murasoli drama troupe under Anna's leadership.

Do not silently merge these into one reconstructed history. The 1962 statement remains user-supplied unless separately sourced.

### Exact next activity

Process the next user-requested **25-page iteration: scans 141–165**.

Start at **scan 141 / printed page 132 / `காட்சி 41` opening** and continue sequentially through scan 165. For every page:

1. inspect the controlling scan directly;
2. preserve speaker labels, punctuation, stage directions, source/old forms and physical page boundaries;
3. record printed pagination only when directly visible;
4. use enlarged-source adjudication for difficult readings;
5. create durable `pages/0141.md` through `pages/0165.md` records;
6. create a batch fidelity/verification record and update page map / checkpoint docs only after the 25-page gate passes.

Do not begin English translation unless explicitly authorized.

## Closed `கலைஞரின் நான்மணி மாலை` state

- Tamil composite coverage: **54/54 PASS / COMPLETE**;
- independent English translations: **4/4 COMPLETE**;
- applicable 2009 witness comparisons: **3/3 PASS / COMPLETE**;
- `பரதாயணம்` witness comparison: **NOT APPLICABLE**.

Do not reopen its verified Tamil, reviewed English, or completed witness comparisons without explicit direction or new source evidence.

## Permanent safeguards

- live `main` controls repository state;
- source PDFs remain external;
- no silent lexical normalization or semantic reconstruction;
- ambiguous old-glyph readings are not overridden by expectation;
- physical page boundaries are preserved;
- independent translation derives from verified Tamil;
- published English remains a secondary witness;
- `அந்தணர்` is not automatically `Brahmin` in future translation work.
