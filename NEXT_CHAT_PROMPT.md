# Next Chat Prompt — நச்சுக்கோப்பை final English translation review

Continue directly in `pugazg/kalaignar-stage-plays`, branch `main`, active work `works/nachuk-koppai/`.

## LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first and preserve newer durable work.

## Durable state

- Tamil scene layer: **18 / 18 CLOSED / final consistency PASS**;
- sole Tamil source hold: **scan 22 / Scene 5**;
- English scenes: **18 / 18 translated / reviewed**;
- English Batches 01–04: **PASS / LOCKED**;
- source-hold-bearing English scenes: **Scene 5 only**;
- secondary-English witness used: **no**;
- English final whole-work review: **NEXT**;
- P0 SHA-256: **pending / separate hold**.

## Exact next activity

Perform the **final whole-work Tamil→English translation review** across `translations/en/01.md` through `18.md`.

Audit:

1. 18 / 18 English files exist and map one-to-one to Tamil Scenes 1–18;
2. every English artifact has correct `source_scene` and `source_scan_pages`;
3. names and terminology are consistent across all four batches;
4. Scene 5 alone carries `source_condition_scans: [22]` and an explicit source-held marker; no guessed scan-22 characters appear;
5. Scene 9 preserves user-confirmed `சுடகோடி` conservatively as `Sudakodi` and does not invent an etymology;
6. Scene 18 preserves the multilingual/phonetic police passage conservatively, excludes non-authorial `4063` / printer imprint, and renders source `முற்றும்` as **The End**;
7. verify no Tamil scene artifact was altered by the English phase;
8. write `translations/en/TRANSLATION_REVIEW.md`, synchronize README / plan / workflow / HANDOVER / NEXT_CHAT_PROMPT / root README, and commit atomically;
9. if PASS, close English for current Tamil source evidence.

Do not reopen the closed Tamil layer.
