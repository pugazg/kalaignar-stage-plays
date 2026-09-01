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
- scans **14–115** dramatic body: **102 / 102 VERIFIED**;
- overall page-level status: **115 / 170 verified**;
- durable page records: `works/manimagudam/pages/0001.md` through `0115.md`;
- `காட்சி 1`–`காட்சி 28`: page-level transcription complete;
- `காட்சி 29`: begins on scan 110, is verified through scan 115, and remains in progress onto scan 116;
- scene assembly: **not started**;
- English translation: **not authorized / not started**.

Completed fidelity records:

- `works/manimagudam/SCANS_0015_0039_VERIFICATION.md` — PASS / COMPLETE;
- `works/manimagudam/SCANS_0041_0065_VERIFICATION.md` — **25 / 25 VERIFIED, 0 unresolved readings**;
- `works/manimagudam/SCANS_0066_0090_VERIFICATION.md` — **25 / 25 VERIFIED, 0 unresolved readings**;
- `works/manimagudam/SCANS_0091_0115_VERIFICATION.md` — **25 / 25 VERIFIED, 0 unresolved readings**.

The scans 91–115 gate preserves enlarged-source readings including `குள்ளநரிக் கூட்டத்தார்`, `இந்நிலையில்`, `க்ஷேமலாபத்தில் அக்கரை`, `திராட்டை பழம்`, `தூது விட்டானே`, `அழிந்தது மமதையார் தர்பார்!`, `கண்ணஜாடை`, `பிணக் கொலுவைக்`, `புடைசூழ`, and `மாநிலத்து மக்கள் அழாமல் இருந்தால், அது ஒன்றே போதும்!`.

### Scene checkpoint through scan 115

- `காட்சி 21`: closes scan 94.
- `காட்சி 22`: scan 94–95.
- `காட்சி - 23`: scan 95–99.
- `காட்சி 24`: scan 100–101.
- `காட்சி 25`: scan 101–104.
- `காட்சி 26`: scan 104–108.
- `காட்சி 27`: complete on scan 108.
- `காட்சி 28`: scan 108–110.
- `காட்சி 29`: begins scan 110; verified through scan 115; continues scan 116.

Important physical continuities in the completed batch:

- scan 90→91 completes the prior incomplete stage direction;
- scan 97→98 continues அரசன் without a repeated label;
- scan 103→104 continues குரு;
- scan 105→106 and 106→107 continue அரசன்;
- scan 108→109 continues the `காட்சி 28` opening stage direction;
- scan 111→112 continues அரசன்'s internal monologue;
- scan 112→113 continues the stage direction;
- scan 113→114 continues அல்லி after `தந்தம் ஓடாகத்`;
- scan 115→116 continues `காட்சி 29`.

### Source-boundary safeguard

The conversation preview exposed only 150 pages. Raw-PDF inspection independently established **170 physical scans** and scans 151–170 were rendered during intake. Never truncate future work at scan 150.

### Performance-history provenance safeguard

User-supplied catalog context states a **1962 Madurai DMK conference** performance. The controlling scan independently records:

- scan 4: May 1956, DMK second state conference, Tiruchirappalli, S. S. Rajendran troupe;
- scan 5: September 1963 staging associated with the Murasoli drama troupe under Anna's leadership.

Do not silently merge these into one reconstructed history. The 1962 statement remains user-supplied unless separately sourced.

### Exact next activity

Process the next user-requested **25-page iteration: scans 116–140**.

Start at **scan 116 / printed page 107 / `காட்சி 29` continuation** and continue sequentially through scan 140. For every page:

1. inspect the controlling scan directly;
2. preserve speaker labels, punctuation, stage directions, source/old forms and physical page boundaries;
3. record printed pagination only when directly visible;
4. use enlarged-source adjudication for difficult readings;
5. create durable `pages/0116.md` through `pages/0140.md` records;
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
