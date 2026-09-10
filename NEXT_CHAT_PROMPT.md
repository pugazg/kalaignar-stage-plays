# Next Chat Prompt — Kalaignar Stage Plays / இரத்தக் கண்ணீர் scans 171–180

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
11. `BATCH_01_REVIEW.md` through `BATCH_17_REVIEW.md`
12. relevant page records through `pages/0170.md`

Resolve / attach the controlling PDF before page-level visual work.

## Controlling source

`TVA_BOK_0064189_இரத்தக்_கண்ணீர்.pdf`

Source provenance: the user-supplied controlling PDF was downloaded from the **Tamil Digital Library (TDL)**. The TDL record and Wikisource copy are provenance/transport routes for the **same scan set**, not independent secondary textual witnesses.

**Operational source rule:** when this exact PDF is attached/readable locally, routine transcription and verification must use the local controlling PDF directly. Do not detour to TDL/Wikisource merely to re-check the same pixels.

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
- canonical page records — **170 / 188**
- initial visual verification — **170 / 188**
- post-verification historical-glyph H-GATE — **170 / 188**
- final verified — **170 / 188**
- contiguous verified range — **scans 1–170**
- Batches 01–17 — **PASS / COMPLETE**
- Batch 17 — **PASS / COMPLETE / LOCKED FOR CURRENT SOURCE EVIDENCE**
- Batch-17 Pass-A durable commit — **`d951cdfc913b375d0c99a3c602a0a0743ef5d091`**
- earlier Batch-17 checkpoint — **`eadec47b4014962ddb4323b18f0d428b051f5b78`**
- historical-glyph corrections recorded — **34**
- unresolved page-level source issues — **0**
- `needs-review` — **0**
- `blocked` — **0**
- scene assembly — **not started / blocked on page layer**
- English — **not authorized / not started**

Batch 17 followed the mandatory two-commit anti-loop workflow: Pass A was durably persisted before H-GATE; Pass B re-read only targeted historical/source-sensitive loci and physical joins; settled prose was not retranscribed.

## Verified Batch-17 structure

- Scene 54: scan **161** only, centred close-star;
- Scene 55: scans **162–163**, centred close-star on scan 163;
- Scene 56: scan **164** only, centred close-star;
- Scene 57: opens scan **165** and remains open through scan **170**, continuing into scan 171;
- scan 166 `வெளியிலிருந்து` → scan 167 `வேதாளமும்...` is a physical continuation;
- scan 167 `ஏந்திக்` → scan 168 `கொண்டே` is a physical split-word continuation;
- scan 168's internal `* * *` is a transition, not a scene close;
- scan 170 ends mid-utterance at `பெண்கள்`, directly establishing continuation into scan 171.

Do not turn this partial evidence into a final whole-work scene inventory.

## Mandatory efficient batch workflow

For Batch 18 follow `works/iratha-kanneer/BATCH_EXECUTION_WORKFLOW.md` exactly:

1. **Pass A — whole-page once:** render/read scans 171–180 from the local controlling PDF, create canonical transcription, establish physical joins/scene boundaries, ordinary visual verification;
2. **commit Pass A immediately:** persist `pages/0171.md` through `0180.md` as `status: needs-review`, `initial_verification: passed`, `historical_glyph_gate: pending` before any H-GATE work;
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

Thirty-four corrections are recorded through scan 170. Recent corrections include:

- scan 170 `மலைப்பாம்பே` (`லை`) — never restore Pass-A apparent `மில்ப்பாம்பே`;
- scan 169 `இதுதானா` (`னா`) — never restore Pass-A apparent `இதுதானு`;
- scan 160 `நீங்கள் தானா முத்தாயி?` (`னா`);
- scan 146 `இளைஞரே` (`ளை`);
- scan 138 `கண்ணை மறைக்கும் பேய்` (`ணை`).

Source-sensitive local readings remain local; do not globalize any historical-glyph adjudication. Batch 17 retained source-visible readings including scan 162 `முழுங்கிவிடே`, `நடத்தொரு நாராயணன்`, `என்றுல`; scan 163 standalone `நெருங்கிய`; scan 165 `வாசப்பூது`; scan 169 `பொருத்தன்`; scan 170 `சொன்னுளாமே`, `பஞ்சணைப் பசியால்`, `சுக்கு நாறுக்கிவிடு`.

## Exact next activity — Batch 18 / scans 171–180

1. Resolve/read the raw controlling PDF directly; the raw 188-scan source controls beyond the 150-page preview.
2. Begin scan 171 by preserving the direct continuation from scan 170 `பெண்கள்`.
3. Perform Pass A once for scans **171–180** and make the mandatory Pass-A commit before H-GATE.
4. Establish source-proven scene boundaries and physical joins only; note intake spot-check evidence that scan 180 visibly opens `காட்சி 59]`, but verify it from the source during Pass A rather than inferring surrounding boundaries.
5. Perform targeted independent H-GATE only after the durable Pass-A boundary.
6. Create `BATCH_18_REVIEW.md` after full batch closure.
7. Synchronize `indexes/page-map.md`, `HISTORICAL_GLYPH_AUDIT.md`, work/root READMEs, root `HANDOVER.md`, and this prompt.
8. Fetch and report final live `main` SHA.

Do not begin scene assembly or English translation merely because Batch 18 completes.
