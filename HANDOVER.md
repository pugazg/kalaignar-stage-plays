# Kalaignar Stage Plays — Handover

Repository: `pugazg/kalaignar-stage-plays`, branch `main`.

## Startup rule

Always fetch live `main` first and treat it as authoritative. Preserve newer durable state. Do not reset, overwrite, repeat, or reopen completed source work unless the user explicitly requests it or new source evidence requires reconciliation.

Permanent workflow: `STAGE_PLAY_PROCESSING_GUIDE.md`.

## மணிமகுடம் — page-level Tamil archive COMPLETE

Controlling source: `TVA_BOK_0064143_மணி_மகுடம்.pdf`.

Durable source identity:

- SHA-256: `a629509c3404fcc5c2844f5b693e72a41aca03ad2e2494588807af4ff8f16f3b`;
- file size: **187,091,728 bytes**;
- physical PDF scans: **170**;
- sixth edition scan statement: **May 2010**, price **Rs.40.00**.

### Final durable checkpoint

- front matter scans **1–13**: **13 / 13 VERIFIED**;
- dramatic-body scans **14–169**: **156 / 156 VERIFIED**;
- back matter scan **170**: **1 / 1 VERIFIED**;
- overall physical-page archive: **170 / 170 COMPLETE**;
- durable page records: `works/manimagudam/pages/0001.md` through `0170.md`;
- `காட்சி 1` through `காட்சி 47`: page-level source transcription complete;
- scan **169 / printed page 160** closes `காட்சி 47` with source-visible `(முடிவுற்றது)`;
- scan **170** is the verified publisher catalogue / advertisement headed `கலைஞரின் சிறப்புமிகு நூல்கள்`;
- scene assembly: **not started**;
- English translation: **not authorized / not started**.

Final-range verification:

- `SCANS_0141_0145_VERIFICATION.md` — **5 / 5 VERIFIED, 0 unresolved**;
- `SCANS_0146_0150_VERIFICATION.md` — **5 / 5 VERIFIED, 0 unresolved**;
- `SCANS_0151_0155_VERIFICATION.md` — **5 / 5 VERIFIED, 0 unresolved**;
- `SCANS_0156_0160_VERIFICATION.md` — **5 / 5 VERIFIED, 0 unresolved**;
- `SCANS_0161_0170_VERIFICATION.md` — **10 / 10 VERIFIED, 0 unresolved**;
- `SCANS_0141_0170_VERIFICATION.md` — aggregate **30 / 30 VERIFIED, 0 unresolved**.

`works/manimagudam/indexes/page-map.md` is synchronized through scan 170 and records the final **170 / 170 COMPLETE** checkpoint.

### Final scene boundary

- `காட்சி 41`: scans 141–144;
- `காட்சி 42`: scans 145–152;
- `காட்சி 43`: scans 152–162;
- `காட்சி 44`: complete on scan 162;
- `காட்சி 45`: complete on scan 162;
- `காட்சி 46`: scans 162–169;
- `காட்சி 47`: complete on scan 169.

### Difficult-reading closure

Previously difficult final-range readings were freshly checked against the controlling scan. The durable archive closes with **0 `needs-review` readings**. Source-retained examples include `கேளடா!`, `சித்தங் கலங்கியவனைப்`, `குடல் கருகிச் செத்த`, `கன்னியர் சூழ் கட்டிலறையும்`, `சுயமரியாதைத் தனமும்`, `சூறாவளி வேகத்திலே`, `நமது வாலை!`, and the anomalous source wording `இந்தத் துப்பாக்கியின் யார் என்று காட்டப் போகிறேன்!`.

The scan-170 catalogue was directly rechecked at closure; the source title is `தேர் சென்ற பாதையிலே`.

## Critical source-boundary safeguard

A conversation preview exposed only 150 pages, but the raw controlling PDF contains **170 physical scans**. The raw 170-page count is authoritative; scans 151–170 were rendered directly from the raw source.

## Performance-history provenance safeguard

The user-supplied catalog context records a **1962 Madurai DMK conference** performance. The controlling scan independently records:

- scan 4: **May 1956**, DMK second state conference, Tiruchirappalli, S. S. Rajendran troupe;
- scan 5: **September 1963** staging associated with the Murasoli drama troupe under Anna's leadership.

Do not silently merge these statements. The 1962 statement remains user-supplied unless separately sourced.

## Exact next activity

**STOP at the completed page-level archive.** Do not automatically begin scene assembly or English translation.

Wait for explicit user authorization for the next phase. If scene assembly is authorized, assemble only from the verified `pages/0001.md`–`0170.md` source records while preserving physical/source provenance. If English translation is separately authorized, derive it from the verified Tamil archive under the repository translation rules.

## Closed `கலைஞரின் நான்மணி மாலை` state

- Tamil composite coverage: **54/54 PASS / COMPLETE**;
- independent English translations: **4/4 COMPLETE**;
- applicable 2009 witness comparisons: **3/3 PASS / COMPLETE**;
- `பரதாயணம்` witness comparison: **NOT APPLICABLE**.

Do not reopen closed work without explicit direction or new source evidence.

## Permanent safeguards

- live `main` controls repository state;
- source PDFs remain external;
- no silent lexical, punctuation, speaker, stage-direction, or old-glyph normalization;
- physical page boundaries are preserved;
- every physical scan, including back matter, has a durable record;
- provisional/uncommitted work is not durable verification;
- independent translation derives from verified Tamil;
- published English remains a secondary witness;
- `அந்தணர்` is not automatically `Brahmin` in future translation work.
