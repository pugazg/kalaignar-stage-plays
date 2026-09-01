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

The repository state — not uncommitted prior-chat work — is authoritative.

- scans **1–13** front matter: **13 / 13 VERIFIED**;
- scans **14–140** dramatic body: **127 / 127 VERIFIED**;
- overall page-level status: **140 / 170 verified**;
- durable page records: `works/manimagudam/pages/0001.md` through `0140.md`;
- `காட்சி 1`–`காட்சி 40`: page-level transcription complete;
- `காட்சி 41`: begins on scan 141 / printed page 132 and is the first uncommitted page;
- scene assembly: **not started**;
- English translation: **not authorized / not started**.

Completed fidelity records:

- `works/manimagudam/SCANS_0015_0039_VERIFICATION.md` — PASS / COMPLETE;
- `works/manimagudam/SCANS_0041_0065_VERIFICATION.md` — **25 / 25 VERIFIED, 0 unresolved readings**;
- `works/manimagudam/SCANS_0066_0090_VERIFICATION.md` — **25 / 25 VERIFIED, 0 unresolved readings**;
- `works/manimagudam/SCANS_0091_0115_VERIFICATION.md` — **25 / 25 VERIFIED, 0 unresolved readings**;
- `works/manimagudam/SCANS_0116_0140_VERIFICATION.md` — **25 / 25 VERIFIED, 0 unresolved readings**.

The scans 116–140 gate preserves enlarged-source readings including `பொசுக்கியதாக வேண்டும்!`, `உளவறியப் போயிருக்கிறார்!`, `சாஜூரைத் தவிர`, `அல்லியை அள்ளிப் பருக`, `நாமே அதையெல்லாம்`, `(முணுமுணுத்தபடி)`, `மாதேன்மத்தர்கள்!`, and `கல்நாட்டு`.

### Scene checkpoint through committed scan 140

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
- `காட்சி 41`: visibly begins scan 141.

Important physical continuities in the last committed batch:

- scan 116→117 continues அல்லி's utterance without a repeated speaker label;
- scan 122→123 continues அல்லி's utterance;
- scan 124→125 continues புதுமைப்பித்தன்;
- scan 127→128 continues கலாராணி;
- scan 130→131 continues the action after அல்லி's final line;
- scan 137→138 continues குருநாதர் without a repeated speaker label.

## Provisional final-batch work from the previous chat — NOT COMMITTED

The user subsequently instructed: **process all remaining pages**.

Source inspection was performed across the remaining physical range **scans 141–170**, but the page records and final fidelity gate were **not committed before the chat was handed over**. Do not promote this provisional work to verified merely from this handover.

What was established visually and may be used as a navigation map after re-resolving the source:

- scans **141–150** were directly inspected through the conversation PDF preview;
- scans **151–170** were directly inspected from raw-PDF renders because the conversation preview stops at 150;
- `காட்சி 41` begins scan **141** / printed page **132**;
- `காட்சி 42` begins scan **145** / printed page **136**;
- `காட்சி 43` begins scan **152** / printed page **143**;
- scan **162** / printed page **153** contains the openings of `காட்சி 44`, `காட்சி 45`, and `காட்சி 46` on the same physical page;
- scan **169** / printed page **160** closes the preceding material, contains `காட்சி 47`, and ends with source-visible `(முடிவுற்றது)`;
- scan **170** is back matter headed `கலைஞரின் சிறப்புமிகு நூல்கள்` / publisher catalogue-advertisement.

A preliminary final-range transcription/source pass was substantially advanced, but **no `pages/0141.md`–`0170.md` records exist durably on `main` yet**. Any local files/crops/renders from the previous chat may not survive into a fresh chat and must not be assumed available.

### Pending enlarged-source adjudication from provisional work

Before closing the final batch, recheck difficult / isolated readings identified during provisional inspection, especially on scans:

- **141**;
- **155**;
- **160**;
- **161**;
- **164**.

There was also additional local checking around scan 151 in the prior window, but because it was not durably committed, the fresh chat must verify it again from the controlling source rather than rely on memory or temporary crops.

## Critical source-boundary safeguard

The conversation preview exposes only **150 pages**, but raw-PDF inspection independently establishes **170 physical scans**. Never truncate future processing at scan 150.

For a fresh chat, attach / resolve `TVA_BOK_0064143_மணி_மகுடம்.pdf` again before source-dependent verification. Re-render scans 151–170 from the raw PDF if the preview still stops at 150. Temporary prior-chat container paths are not durable source references.

## Performance-history provenance safeguard

User-supplied catalog context states a **1962 Madurai DMK conference** performance. The controlling scan independently records:

- scan 4: May 1956, DMK second state conference, Tiruchirappalli, S. S. Rajendran troupe;
- scan 5: September 1963 staging associated with the Murasoli drama troupe under Anna's leadership.

Do not silently merge these into one reconstructed history. The 1962 statement remains user-supplied unless separately sourced.

## Exact next activity — finish all remaining pages in one go

Do **not** restart scans 1–140 and do not stop at scan 165. Finish the complete remaining physical range **scans 141–170**.

1. Fetch live `main` first and preserve anything newer than this handover.
2. Read `STAGE_PLAY_PROCESSING_GUIDE.md`, this `HANDOVER.md`, `NEXT_CHAT_PROMPT.md`, `works/manimagudam/README.md`, `metadata/source.md`, `indexes/page-map.md`, `SCANS_0116_0140_VERIFICATION.md`, and `pages/0140.md` completely.
3. Attach / resolve the controlling PDF again.
4. Reconcile scans **141–150** directly from the PDF preview/source.
5. Re-render and reconcile scans **151–170** directly from the raw PDF if the preview truncates at 150.
6. Resolve the pending difficult readings listed above using enlarged-source crops; do not normalize from expected spelling or semantics.
7. Create durable `works/manimagudam/pages/0141.md` through `0170.md` records, including the back-cover catalogue at scan 170.
8. Preserve exact speaker labels, punctuation, stage directions, old/source forms, printed pagination, and physical page boundaries.
9. Create `works/manimagudam/SCANS_0141_0170_VERIFICATION.md` (or an equivalently named final verification record) only after all 30 scans pass; record unresolved readings as `needs-review` rather than guessing.
10. Update `indexes/page-map.md`, work README, root README, `HANDOVER.md`, and `NEXT_CHAT_PROMPT.md`.
11. Only if every physical scan 1–170 has a source-reconciled record and the final gate passes, mark Tamil page-level archival transcription **170 / 170 COMPLETE**.
12. Commit the final batch to `main` and fetch live `main` again to verify the durable result.

After 170/170 page-level completion, **do not automatically begin scene assembly or English translation**. Those remain separate phases and require explicit authorization / a new checkpoint.

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
- every physical scan, including back matter, requires a record;
- provisional/uncommitted work is not durable verification;
- independent translation derives from verified Tamil;
- published English remains a secondary witness;
- `அந்தணர்` is not automatically `Brahmin` in future translation work.
