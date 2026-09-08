# Kalaignar Stage Plays — Handover

Repository: `pugazg/kalaignar-stage-plays`, branch `main`.

## Startup rule

Always fetch live `main` first and preserve newer durable state.

Permanent source-first workflow: `STAGE_PLAY_PROCESSING_GUIDE.md`.

Historical-type authority for the active work:

1. `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`;
2. `HISTORICAL_TAMIL_GLYPH_GATE.md`.

# CURRENT CHECKPOINT — இரத்தக் கண்ணீர் ACTIVE / P0 SOURCE INTAKE PASS

Active work path: `works/iratha-kanneer/`.

Controlling source: `TVA_BOK_0064189_இரத்தக்_கண்ணீர்.pdf`.

Current durable state:

- P0 source intake: **PASS**;
- raw physical range: **188 / 188 scans confirmed**;
- canonical page transcription: **0 / 188**;
- initial visual verification: **0 / 188**;
- historical-glyph H-GATE: **0 / 188**;
- final verified pages: **0 / 188**;
- structural / scene assembly: **not started**;
- English translation: **not authorized / not started**.

The conversation file preview exposes only **150** page images. Direct raw-PDF inspection established **188 physical scans**. The raw PDF count controls; never stop at preview page 150.

## Mandatory startup before further இரத்தக் கண்ணீர் work

Read completely:

1. `STAGE_PLAY_PROCESSING_GUIDE.md`;
2. `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`;
3. `HISTORICAL_TAMIL_GLYPH_GATE.md`;
4. this `HANDOVER.md`;
5. `NEXT_CHAT_PROMPT.md`;
6. `works/iratha-kanneer/README.md`;
7. `works/iratha-kanneer/metadata/source.md`;
8. `works/iratha-kanneer/indexes/page-map.md`;
9. `works/iratha-kanneer/HISTORICAL_GLYPH_AUDIT.md`;
10. relevant `works/iratha-kanneer/pages/NNNN.md` records once they exist.

Resolve / attach the controlling PDF before source-dependent page work. Do not substitute OCR, web text, later editions or memory for source pixels.

## Source identity

- title: **இரத்தக் கண்ணீர்**;
- author as printed: **மு. கருணாநிதி**;
- publisher: **திராவிடப் பண்ணை**;
- title-page location: **தெப்பக்குளம் :: திருச்சி**;
- edition: **முதல் பதிப்பு — 1953**;
- source-visible price: **ரூ. 2-0-0.**;
- SHA-256: **`120428985bd327456df46b9e06271896b106332711f4c9063d4f0c7fe72b6441`**;
- size: **319,220,349 bytes**;
- physical scans: **188**;
- image-only: **yes**;
- source PDF committed to repository: **no**.

Internal front-matter dates are separately preserved:

- scan 4 `பதிப்புரை` — **14-4-1948**;
- scan 5 `முன்னுரை` — **20-11-53**, `திருச்சி மத்திய சிறை`, signed `மு. கருணாநிதி`.

Do not promote the 1948 internal date over the source-visible 1953 first-edition statement.

## Intake structure — not yet a final structural audit

Source-visible intake findings:

- scan 1 — illustrated front cover;
- scan 2 — title / author / publisher page;
- scan 3 — `முதல் பதிப்பு—1953`, rights / price / printer-imprint page;
- scan 4 — `பதிப்புரை`;
- scan 5 — `முன்னுரை`;
- scans 6–7 — `நுழைவாய்`;
- scan 8 — `இரத்தக் கண்ணீர் [நாடகம்]`, `காட்சி 1]`;
- scan 180 — intake spot check `காட்சி 59]`;
- scan 183 — intake spot check `காட்சி 60]`;
- scan 184 — intake spot check `காட்சி 61]`;
- scan 186 — source-visible `முடிவு` / closing prose;
- scan 187 — publisher catalogue advertisement;
- scan 188 — back wrapper / `திராவிடப் பண்ணை` device.

Do **not** declare a final 61-scene inventory from these spot checks. Page transcription / verification precedes scene-boundary closure.

# Mandatory post-initial-verification historical-glyph gate

The user explicitly directed that historical Tamil glyph checking occur **after initial verification**.

For this work the page pipeline is therefore:

**P1 canonical transcription → P2 initial visual verification → H-GATE historical Tamil glyph audit → final page verification.**

Initial verification alone is not final `verified`.

After initial visual verification while H-GATE is pending:

```yaml
status: "needs-review"
initial_verification: "passed"
historical_glyph_gate: "pending"
```

Only after H-GATE PASS, and if no other source issue remains:

```yaml
status: "verified"
initial_verification: "passed"
historical_glyph_gate: "passed"
```

Mandatory minimum family set:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

Permanent rules:

- source pixels control character identity;
- inspect complete page / complete glyph cluster at enlarged/native resolution;
- compare clearer same-edition witnesses when needed;
- OCR / grammar / familiar spelling / context are not proof;
- encode proven historical character identity into modern Unicode without modernizing source wording;
- no global replacement;
- unresolved glyph identity remains `needs-review`;
- `blocked` only after source-condition escalation is exhausted;
- historical-glyph corrections are logged separately from ordinary transcription corrections.

Work-level tracker: `works/iratha-kanneer/HISTORICAL_GLYPH_AUDIT.md`.

## Exact next activity — scans 1–10

Process the first ten physical scans in one source-first batch:

1. create `pages/0001.md` through `pages/0010.md`;
2. transcribe / describe every page, including cover and front matter;
3. perform initial visual verification against source pixels;
4. after initial verification, run H-GATE on every applicable Tamil page;
5. promote only H-GATE-passed clean pages to final `verified`;
6. leave unresolved pages `needs-review` / `blocked` as supported;
7. expand/reconcile `indexes/page-map.md`;
8. update `HISTORICAL_GLYPH_AUDIT.md`, work README, this handover and `NEXT_CHAT_PROMPT.md`;
9. fetch final live `main` SHA.

Do not begin scene assembly or English translation merely because a page batch completes.

# CLOSED WORK SAFEGUARDS

The completed `ஒரே முத்தம்` Tamil + English workflows remain **CLOSED**. Also keep `திருவாளர் தேசீயம்பிள்ளை`, `காகிதப்பூ`, `மணிமகுடம்`, and closed `கலைஞரின் நான்மணி மாலை` components closed unless the user separately reopens them with new evidence / a named phase.
