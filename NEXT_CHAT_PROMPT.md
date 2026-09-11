# Next Chat Prompt — நச்சுக்கோப்பை Tamil scene assembly / Scenes 6–10

Continue directly in `pugazg/kalaignar-stage-plays`, branch `main`, active work `works/nachuk-koppai/`.

## LIVE MAIN IS AUTHORITATIVE

Fetch live `main` first and preserve newer durable work.

## Durable state

- canonical page layer: **63 / 63 reconciled**;
- verified pages: **62 / 63**;
- sole terminal page-layer hold: **scan 22**;
- Tamil scene assembly: **5 / 18 COMPLETE / REVIEWED**;
- Scenes **1–4** — assembly-reviewed / clean;
- Scene **5** — assembly-reviewed with inherited scan-22 source-cluster hold;
- scan 20 — user-confirmed `வேணும்னாலும்`;
- scan 35 — user-confirmed `சுடகோடி`;
- English translation: **not started / blocked until Tamil scene assembly review completes**;
- P0 SHA-256: **pending / separate hold**.

## Exact next activity

Assemble **Scenes 6–10** into:

- `works/nachuk-koppai/scenes/06.md`
- `works/nachuk-koppai/scenes/07.md`
- `works/nachuk-koppai/scenes/08.md`
- `works/nachuk-koppai/scenes/09.md`
- `works/nachuk-koppai/scenes/10.md`

Source scan spans:

- Scene 6 — scans **24–25**;
- Scene 7 — scans **25–31**;
- Scene 8 — scans **32–33**;
- Scene 9 — scans **34–41**;
- Scene 10 — scans **41–42**.

Assembly rules:

1. assemble only from reconciled canonical page records;
2. on shared boundary pages, include only text belonging to the target scene;
3. remove only mechanical physical-page breaks;
4. preserve wording, punctuation, speaker labels, stage directions and unusual source forms;
5. running headers and non-authorial marks do not enter scene text;
6. this batch has **no unresolved page-layer hold**; preserve scan 35 exactly as `சுடகோடி`;
7. review all five scenes against their page records;
8. write `SCENE_ASSEMBLY_BATCH_02.md`, update controls, and commit atomically.

Do not start English translation in this iteration.
