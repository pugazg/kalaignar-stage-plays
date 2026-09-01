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
- scans **14–39** dramatic body: **26 / 26 VERIFIED**;
- overall page-level status: **39 / 170 verified**;
- durable page records: `works/manimagudam/pages/0001.md` through `0039.md`;
- `காட்சி 1`–`காட்சி 6`: page-level transcription complete;
- `காட்சி 7`: begins on scan 39 and remains in progress;
- scene assembly: **not started**;
- English translation: **not authorized / not started**.

The 25-scan batch 15–39 received a final enlarged-source fidelity pass before commit. The correction log is durable at:

`works/manimagudam/SCANS_0015_0039_VERIFICATION.md`.

Important source-supported corrected forms include `எலும்பு உடலினர்`, `ஏறத்தாழ`, `முல்லை அரும்புகள்`, `குமுறியெழும் வறுமைத் தீயை`, `எலும்பாய்த் தேய்ந்து, எறும்பாய் உழைத்து`, `தேர்களாய்`, `புகையும் எரிமலை`, and `நிர்மூலமாக்கப்பட்டு`.

### Source-boundary safeguard

The conversation preview exposed only 150 pages. Raw-PDF inspection independently established **170 physical scans** and scans 151–170 were rendered during intake. Never truncate future work at scan 150.

### Performance-history provenance safeguard

User-supplied catalog context states a **1962 Madurai DMK conference** performance. The controlling scan independently records:

- scan 4: May 1956, DMK second state conference, Tiruchirappalli, S. S. Rajendran troupe;
- scan 5: September 1963 staging associated with the Murasoli drama troupe under Anna's leadership.

Do not silently merge these into one reconstructed history. The 1962 statement remains user-supplied unless separately sourced.

### Exact next activity

Process **scan 40 / காட்சி 7 continuation** only:

1. inspect the controlling scan directly;
2. create `works/manimagudam/pages/0040.md`;
3. preserve the physical continuation from the open அல்லி utterance on scan 39;
4. preserve speaker labels, punctuation, stage directions and source forms;
5. record printed pagination only if directly visible on scan 40;
6. update page map and checkpoint docs after reconciliation.

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
