# Kalaignar Stage Plays — Handover

## Repository

`pugazg/kalaignar-stage-plays` on `main`.

## Fresh-session continuation package

Before continuing Silappathikaram, read completely:

1. `STAGE_PLAY_PROCESSING_GUIDE.md`
2. `docs/SILAPPATHIKARAM_CONTINUATION_GUIDELINES.md`
3. `docs/SILAPPATHIKARAM_PROJECT_HANDOVER.md`
4. `docs/NEXT_CHAT_PROMPT_SILAPPATHIKARAM.md`
5. `works/silappathikaram-nataka-kappiyam/README.md`
6. `works/silappathikaram-nataka-kappiyam/indexes/page-map.md`
7. `works/silappathikaram-nataka-kappiyam/audit.md`
8. `works/silappathikaram-nataka-kappiyam/SCENE_ASSEMBLY_PLAN.md`
9. `works/silappathikaram-nataka-kappiyam/VISUAL_TEXT_FIDELITY_CHECK.md`
10. `works/silappathikaram-nataka-kappiyam/SCENE_ASSEMBLY_PILOT_REVIEW.md`
11. assembled scene files `scenes/01.md` through `scenes/06.md`

## Permanent source rules

The supplied Tamil scan is controlling authority. Do not silently modernize, correct, normalize, reconstruct or improve Kalaignar's Tamil. OCR and other editions are assistive/secondary only. Source PDFs are not committed.

Previously verified page records are protected: change a verified reading only when direct source-pixel inspection proves it wrong, and document the correction explicitly.

## Current checkpoint

Active work: `works/silappathikaram-nataka-kappiyam/`

Tamil source: `TVA_BOK_0016473_சிலப்பதிகாரம்_நாடகக்_காப்பியம்.pdf`

- Supplied source length: **88 scans**.
- Scans **1–88 are visually verified**.
- Page-level verification covers **காட்சி-1 through காட்சி-38** plus the scan-88 closing tableau.
- Tamil transcription completion audit: **PASS**.
- Scene assembly is active with mandatory direct visual-text fidelity review.
- Scenes **1–6 are assembly-reviewed with `visual_text_fidelity: "passed"`**.
- **6 of 38 numbered scenes are assembly-reviewed.**
- English translation has not started and remains locked.

## Latest completed activity — காட்சி-6

Scene file: `works/silappathikaram-nataka-kappiyam/scenes/06.md`

- title: `பூம்புகார்ப் பொற்றொடி`
- separate setting heading: none; `setting: null`
- source scans: 26–28
- status: `assembly-reviewed`
- `visual_text_fidelity: "passed"`

Direct high-resolution source inspection covered all three scans, scan 27's `ஆடல், பாடல்` and quoted song block, both physical page boundaries, scan 28's left-column → right-column continuation, and all visual layers.

Source-pixel correction made during this fidelity pass:

- `pages/0027.md`: `[சாத்தனூரின் குரல் தொடர்கிறது]` → source-visible `[சாத்தனரின் குரல் தொடர்கிறது]`.

No scan-26 or scan-28 page-record wording correction was required.

Assembly-only fidelity fixes:

- retain `வெண் மணல்` rather than collapsing it to `வெண்மணல்`;
- retain the word boundary in `தங்கமே...இந்தா... உனக்காகக்`.

Boundary/structure checks:

- scan 26 ends `தெருவெல்லாம் தமிழ் முழக்கம்!`; scan 27 begins the new `ஆடல், பாடல்` block;
- scan 27 ends `கோவ : கண்ணகி!`; scan 28 begins `கண் : எத்தனை நாளத்தான்...`;
- scan 28's same-speaker column transition joins `...தேன் சிந்தும் திங்கள்` to `முகம்—மறப்பேனு...` without inserted punctuation;
- scans 26–27 have no securely visible printed page number; scan 28 prints `12`;
- scan 26's man/woman illustration, scan 27's dancer figure and scan 28's ship illustration remain visual-only layers.

## Assembly rules now controlling

For every scene:

- assemble only from verified page records;
- begin `draft` / `visual_text_fidelity: pending`;
- preserve exact source wording, spacing, punctuation, repetitions, speaker labels and stage directions;
- join only demonstrably mechanical line/column/page wrapping;
- preserve explicit scan provenance for multi-scan scenes;
- inspect every contributing scan directly at native/enlarged resolution;
- verify both sides of every physical page and column boundary;
- compare the assembled scene again against all contributing page records;
- promote to `assembly-reviewed` / `visual_text_fidelity: passed` only when both checks pass;
- if source pixels prove a page record wrong, correct only that affected reading and document it before finalizing the scene;
- keep illustrations, photographs, captions, page numbers, stamps and handwriting separate from literary text.

## Permanent future-translation terminology note

Do **not** automatically translate `அந்தணர்` as “Brahmin.” Preserve distinctions among `பிராமண`, `பார்ப்பன`, `அந்தணர்`, `மறையவன்`, and related source terms. English translation remains a later phase and must retain Kalaignar's rhetoric, cadence, repetition and dramatic voice.

## Exact next activity

Process **காட்சி-7 / scans 29–32 — `கலைக்கரசி மாதவி`, setting `முத்துப் பந்தல்`** as one complete scene-assembly + visual-text-fidelity activity.

- Inputs: `pages/0029.md` through `pages/0032.md`.
- Output: `scenes/07.md`.
- Preserve explicit provenance for all four scans and inspect all three physical page boundaries.
- Preserve scan 29's verse block, source punctuation and terminal `சுயம்வரம் ஏற்பாடு செய்யப்பட்டிருக்கிறது!.` exactly.
- Keep all illustrations/photographs separate from literary text; scan 32 has a large uncaptioned circular dancing-figure sculpture photograph/reproduction.
- Scan 29 has no securely visible printed pagination; scan 32 visibly prints `16`; retain every page record's verified pagination as provenance only.
- Inspect scans 29–32 directly at native/enlarged resolution, compare the scene against source pixels and all four verified page records, and promote only after both checks pass.

Do not begin English translation.