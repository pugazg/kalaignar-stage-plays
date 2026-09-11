# Next Chat Prompt — Kalaignar Stage Plays / நச்சுக்கோப்பை Batch 01 complete Pass A

Continue directly in `pugazg/kalaignar-stage-plays`, branch `main`, active work:

`works/nachuk-koppai/`

## LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first and preserve newer durable state.

## Controlling source

`ACL-TDD_00314_நச்சுக்_கோப்பை.pdf`

Durable identity:

- physical scans: **63**;
- exact file size: **18,459,068 bytes**;
- SHA-256: **PENDING**;
- title: **நச்சுக்கோப்பை**;
- author: **மு. கருணாநிதி**;
- publisher: **திராவிடன் பதிப்பகம்**;
- edition: **முதல் பதிப்பு — 1951**;
- provenance: **attached PDF was downloaded from Tamil Digital Library**;
- route note: **Wikisource carries the same scan/copy; neither TDL nor Wikisource is an independent textual witness**.

## Current Batch 01 state

- `pages/0001.md` through `pages/0010.md` exist;
- scan 1 is full / ordinary verification PASS / H-GATE pending;
- scans 2–10 are conservative **partial** records;
- user-supplied first-pass for scans 1–10 is durably stored at `works/nachuk-koppai/first-pass/BATCH_01_USER_TRANSCRIPTION.md`;
- `BATCH_01_SOURCE_INSPECTION.md` is a durable partial checkpoint;
- **Pass A is NOT complete**;
- **do not create a PASS batch review from this state**;
- scan 8 is a shared boundary: Scene 1 closes in the upper portion; Scene 2 opens below the separator.

## Exact next activity

1. compute SHA-256 if checksum execution is available;
2. use `first-pass/BATCH_01_USER_TRANSCRIPTION.md` as the comparison baseline and **only the exact attached controlling PDF** as authority; reconcile scans **2–10** without retranscribing settled baseline text from scratch;
3. correct the baseline only where source pixels unambiguously support the change; otherwise retain the plausible first-pass reading and mark the locus for review; preserve source spelling, old glyphs, punctuation, speaker labels and stage directions;
4. once all scans 1–10 have complete canonical text and ordinary visual verification PASS, record Batch 01 Pass A COMPLETE;
5. then run the independent historical-glyph H-GATE;
6. create `BATCH_01_REVIEW.md` only after the gate passes;
7. synchronize page map / README / handover / prompt and commit.

Do not browse or use TDL/Wikisource/another download to fill source text. They are same-copy provenance/transport routes only. Do not use the unproofread Wikisource transcription, later editions, plot summaries or semantic expectation to fill source text. Do not begin scene assembly or English translation.
