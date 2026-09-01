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
- scans **14–65** dramatic body: **52 / 52 VERIFIED**;
- overall page-level status: **65 / 170 verified**;
- durable page records: `works/manimagudam/pages/0001.md` through `0065.md`;
- `காட்சி 1`–`காட்சி 13`: page-level transcription complete;
- `காட்சி 14`: begins on scan 65 and remains in progress onto scan 66;
- scene assembly: **not started**;
- English translation: **not authorized / not started**.

Completed fidelity records:

- `works/manimagudam/SCANS_0015_0039_VERIFICATION.md` — PASS / COMPLETE;
- `works/manimagudam/SCANS_0041_0065_VERIFICATION.md` — **25 / 25 VERIFIED, 0 unresolved readings**.

The latter records source-supported corrections including `பரவ விடாமல்`, `மன்றத்தினர்`, `அரசனிடம்`, `சம்மந்தி உறவும்`, `தேவைப்படுகிற`, `பாடையில் ஏறும் வரையில்`, `தங்கைகளில்`, and `அனாதைக் குடிசையைக்`. Unusual source forms `குஷிமிக்க வேண்டும்!`, `மன்னிடம் பணி செய்கிறோம்`, and `அக்கரை` were inspected and intentionally retained.

### Scene checkpoint through scan 65

- `காட்சி 7`: closes scan 44.
- `காட்சி 8`: scan 44–49.
- `காட்சி 9`: scan 49–50.
- `காட்சி 10`: scan 50–55.
- `காட்சி 11`: scan 55–58.
- `காட்சி 12`: scan 58–59.
- `காட்சி 13`: scan 60–65.
- `காட்சி 14`: begins scan 65, continues scan 66.

Important physical continuities in the completed batch:

- scan 40→41 and 41→42 continue புதுமைப்பித்தன் without repeated speaker labels;
- scan 57→58 breaks குணசீலர் after `சீமான்களுக்கு`;
- scan 63→64 breaks அரசன் after `ஆயிரக்கணக்கான`, resuming `பவுன்கள்`;
- scan 65 closes scene 13 and begins scene 14.

### Source-boundary safeguard

The conversation preview exposed only 150 pages. Raw-PDF inspection independently established **170 physical scans** and scans 151–170 were rendered during intake. Never truncate future work at scan 150.

### Performance-history provenance safeguard

User-supplied catalog context states a **1962 Madurai DMK conference** performance. The controlling scan independently records:

- scan 4: May 1956, DMK second state conference, Tiruchirappalli, S. S. Rajendran troupe;
- scan 5: September 1963 staging associated with the Murasoli drama troupe under Anna's leadership.

Do not silently merge these into one reconstructed history. The 1962 statement remains user-supplied unless separately sourced.

### Exact next activity

Process the next user-requested **25-page iteration: scans 66–90**.

Start at **scan 66 / printed page 57 / `காட்சி 14` continuation** and continue sequentially through scan 90. For every page:

1. inspect the controlling scan directly;
2. preserve speaker labels, punctuation, stage directions, source/old forms and physical page boundaries;
3. record printed pagination only when directly visible;
4. use enlarged-source adjudication for difficult readings;
5. create durable `pages/0066.md` through `pages/0090.md` records;
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
