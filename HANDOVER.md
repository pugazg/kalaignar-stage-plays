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
- scans **14–90** dramatic body: **77 / 77 VERIFIED**;
- overall page-level status: **90 / 170 verified**;
- durable page records: `works/manimagudam/pages/0001.md` through `0090.md`;
- `காட்சி 1`–`காட்சி 20`: page-level transcription complete;
- `காட்சி 21`: begins on scan 85, is verified through scan 90, and remains in progress onto scan 91;
- scene assembly: **not started**;
- English translation: **not authorized / not started**.

Completed fidelity records:

- `works/manimagudam/SCANS_0015_0039_VERIFICATION.md` — PASS / COMPLETE;
- `works/manimagudam/SCANS_0041_0065_VERIFICATION.md` — **25 / 25 VERIFIED, 0 unresolved readings**;
- `works/manimagudam/SCANS_0066_0090_VERIFICATION.md` — **25 / 25 VERIFIED, 0 unresolved readings**.

The scans 66–90 gate records scan-supported corrections including `பொன்மலர்`, `நாங்க படிக்கணும்.`, `கோரதாண்டவம்`, `என்றைக்கு`, `அந்த லட்சணங்கள் அத்தனையும்`, `பின்னடைந்து போனவரின்`, `அரச பதவியைத் துறந்து விட்டார்!`, and `அது பெரிய ஆபத்து அமைச்சரே!`. Unusual printed forms `அந்த மலரை மட்டும் பறிப்பாளேன்?` and `இதுபோன்ற தேய்ந்து போனதுகள்` were inspected and intentionally retained.

### Scene checkpoint through scan 90

- `காட்சி 14`: closes scan 68.
- `காட்சி 15`: scan 68–70.
- `காட்சி 16`: scan 70–74.
- `காட்சி 17`: scan 74–75.
- `காட்சி 18`: scan 76–80.
- `காட்சி 19`: scan 80–81.
- `காட்சி 20`: scan 81–85.
- `காட்சி 21`: begins scan 85; verified through scan 90; continues scan 91.

Important physical continuities in the completed batch:

- scan 73→74 continues புதுமைப்பித்தன் across the physical break;
- scan 74→75 continues the newspaper quotation;
- scan 80→81 continues the minister without a repeated speaker label;
- scan 85→86 continues குணசீலர் after `எதுவுமே` without a repeated label;
- scan 90→91 carries an incomplete stage direction into the next physical scan.

### Source-boundary safeguard

The conversation preview exposed only 150 pages. Raw-PDF inspection independently established **170 physical scans** and scans 151–170 were rendered during intake. Never truncate future work at scan 150.

### Performance-history provenance safeguard

User-supplied catalog context states a **1962 Madurai DMK conference** performance. The controlling scan independently records:

- scan 4: May 1956, DMK second state conference, Tiruchirappalli, S. S. Rajendran troupe;
- scan 5: September 1963 staging associated with the Murasoli drama troupe under Anna's leadership.

Do not silently merge these into one reconstructed history. The 1962 statement remains user-supplied unless separately sourced.

### Exact next activity

Process the next user-requested **25-page iteration: scans 91–115**.

Start at **scan 91 / printed page 82 / `காட்சி 21` continuation** and continue sequentially through scan 115. For every page:

1. inspect the controlling scan directly;
2. preserve speaker labels, punctuation, stage directions, source/old forms and physical page boundaries;
3. record printed pagination only when directly visible;
4. use enlarged-source adjudication for difficult readings;
5. create durable `pages/0091.md` through `pages/0115.md` records;
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
