# Next Chat Prompt — Kalaignar Stage Plays / இரத்தக் கண்ணீர் scans 141–150

Continue directly in `pugazg/kalaignar-stage-plays`, branch `main`, active work:

`works/iratha-kanneer/`

## LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first and preserve newer durable state.

Keep closed `ஒரே முத்தம்`, `திருவாளர் தேசீயம்பிள்ளை`, `காகிதப்பூ`, `மணிமகுடம்`, and closed `கலைஞரின் நான்மணி மாலை` work closed unless separately authorized.

## Mandatory startup

Read completely before source-dependent work:

1. `STAGE_PLAY_PROCESSING_GUIDE.md`
2. `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`
3. `HISTORICAL_TAMIL_GLYPH_GATE.md`
4. root `HANDOVER.md`
5. this `NEXT_CHAT_PROMPT.md`
6. `works/iratha-kanneer/BATCH_EXECUTION_WORKFLOW.md`
7. `works/iratha-kanneer/README.md`
8. `works/iratha-kanneer/metadata/source.md`
9. `works/iratha-kanneer/indexes/page-map.md`
10. `works/iratha-kanneer/HISTORICAL_GLYPH_AUDIT.md`
11. `BATCH_01_REVIEW.md` through `BATCH_14_REVIEW.md`
12. relevant page records through `pages/0140.md`

Resolve / attach the controlling PDF before page-level visual work.

## Controlling source

`TVA_BOK_0064189_இரத்தக்_கண்ணீர்.pdf`

Source provenance: the user-supplied controlling PDF was downloaded from the **Tamil Digital Library (TDL)**. The TDL record and Wikisource copy are provenance/transport routes for the **same scan set**, not independent secondary textual witnesses.

**Operational source rule:** when this exact PDF is attached/readable locally, routine transcription and verification must use the local controlling PDF directly. Do not detour to TDL/Wikisource merely to re-check the same pixels. External transport is justified only if the local bytes are unavailable/unreadable or the user explicitly requests an outside comparison.

- title: **இரத்தக் கண்ணீர்**
- author: **மு. கருணாநிதி**
- publisher: **திராவிடப் பண்ணை**
- edition: **முதல் பதிப்பு — 1953**
- physical scans: **188**
- size: **319,220,349 bytes**
- SHA-256: **`120428985bd327456df46b9e06271896b106332711f4c9063d4f0c7fe72b6441`**
- image-only; source PDF is not committed

The conversation preview exposes only **150** pages, but raw-PDF inspection confirms **188**. Never stop at 150.

## Durable checkpoint

- P0 source intake — **PASS**
- canonical page records — **140 / 188**
- initial visual verification — **140 / 188**
- post-verification historical-glyph H-GATE — **140 / 188**
- final verified — **140 / 188**
- contiguous verified range — **scans 1–140**
- Batches 01–14 — **PASS / COMPLETE**
- Batch 14 — **PASS / COMPLETE / LOCKED FOR CURRENT SOURCE EVIDENCE**
- historical-glyph corrections recorded — **30**
- unresolved page-level source issues — **0**
- `needs-review` — **0**
- `blocked` — **0**
- scene assembly — **not started / blocked on page layer**
- English — **not authorized / not started**

Batch 14 followed the mandatory two-commit anti-loop workflow: Pass A was durably persisted before H-GATE; Pass B re-read only targeted historical/source-sensitive loci and physical joins; settled prose was not retranscribed.

## Verified structure through scan 140

- Scene 1 scans 8–13;
- Scene 2 scans 14–18;
- Scene 3 scans 19–21;
- Scene 4 scans 22–25;
- Scene 5 scans 26–29;
- Scene 6 scan 30 only;
- Scene 7 scans 31–33;
- Scene 8 scans 34–39;
- Scene 9 scans 40–41;
- Scene 10 scans 42–44;
- Scene 11 scans 45–46;
- Scene 12 scans 47–49;
- Scene 13 scans 50–51;
- Scene 14 scans 52–53;
- Scene 15 scans 54–57;
- Scene 16 scans 58–62;
- Scene 17 scans 63–65;
- Scene 18 scans 66–67;
- Scene 19 scan 68 only;
- Scene 20 scans 69–75;
- Scene 21 scans 76–80;
- Scene 22 scan 81 only;
- Scene 23 scans 82–83;
- Scene 24 scan 84 only;
- Scene 25 scans 85–88;
- Scene 26 scans 89–90;
- Scene 27 scans 91–94;
- Scene 28 scans 95–96;
- Scene 29 scans 97–98;
- Scene 30 scans 99–100;
- Scene 31 scans 101–104;
- Scene 32 scans 105–106;
- Scene 33 scan 107 only;
- Scene 34 scans 108–110;
- Scene 35 scans 111–115;
- Scene 36 scans 116–122;
- Scene 37 scans **123–131**;
- Scene 38 scans **132–133**;
- Scene 39 scans **134–135**;
- Scene 40 scan **136** only;
- Scene 41 scans **137–139**;
- Scene 42 opens scan **140** and **continues into scan 141**.

Scan 141 was inspected during Batch 14 only to establish the continuation boundary. It is **not** already verified and must be processed fully in Batch 15.

Do not turn this partial evidence into a final whole-work scene inventory.

## Mandatory efficient batch workflow

For Batch 15 follow `works/iratha-kanneer/BATCH_EXECUTION_WORKFLOW.md` exactly:

1. **Pass A — whole-page once:** render/read scans 141–150 from the local controlling PDF, create canonical transcription, establish physical joins/scene boundaries, ordinary visual verification;
2. **commit Pass A immediately:** persist `pages/0141.md` through `0150.md` as `status: needs-review`, `initial_verification: passed`, `historical_glyph_gate: pending` before any H-GATE work;
3. **Pass B — targeted H-GATE only:** inspect mandatory historical families plus actual candidate/source-sensitive loci and joins; do not retranscribe settled prose;
4. crop/enhance only an actual unresolved locus; stop once resolved or formally held;
5. final closure commit only after clean pages receive H-GATE PASS / final `verified` and controls are synchronized.

Short rule:

> **Local PDF → Pass A once → commit → targeted H-GATE → final commit. No external detour and no settled-text loop.**

## Mandatory historical-glyph gate

Mandatory minimum family set:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

The family list is a minimum, not a ceiling. Batch 05 also established historical `ளா` look-alikes. No global replacement. No spelling/grammar/punctuation modernization. OCR and expected wording are not glyph authority. Prefer same-edition comparison for doubtful clusters.

## Established historical corrections — do not regress

Thirty corrections are recorded through scan 140. Batch 14 added:

- scan 138 `கண்ணை மறைக்கும் பேய்` (`ணை`) — never restore Pass-A apparent `கண்ண மறைக்கும் பேய்`.

Batch-13 corrections including scan 122 `இருப்பானா?`, scan 124 `கண்ணாடி` ×2, scan 127 `கண்ணாடியிடம்`, and scan 130 `பெண்ணாகவும்` / `ஆணாகவும்` remain authoritative. Source-sensitive local readings remain local; do not globalize any historical-glyph adjudication.

## Exact next activity — Batch 15 / scans 141–150

1. Start scan 141 as the continuing Scene-42 page; establish the scan-140→141 physical continuation from source pixels.
2. Process **all of scan 141** from source pixels; do not inherit verification from the prior boundary-only inspection.
3. Perform Pass A once for scans 141–150 and make the mandatory Pass-A commit before H-GATE.
4. Perform targeted independent H-GATE only after that durable boundary.
5. Create `BATCH_15_REVIEW.md` after full batch closure.
6. Synchronize `indexes/page-map.md`, `HISTORICAL_GLYPH_AUDIT.md`, work/root READMEs, root `HANDOVER.md`, and this prompt.
7. Fetch and report final live `main` SHA.

Do not begin scene assembly or English translation merely because Batch 15 completes.
