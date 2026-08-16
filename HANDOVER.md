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
11. assembled scene files `scenes/01.md` through `scenes/09.md`

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
- Scenes **1–9 are assembly-reviewed with `visual_text_fidelity: "passed"`**.
- **9 of 38 numbered scenes are assembly-reviewed.**
- English translation has not started and remains locked.

## Latest completed activity — காட்சி-9

Scene file: `works/silappathikaram-nataka-kappiyam/scenes/09.md`

- title: `பிரிவினை தந்த பேதை`
- setting: `கண்ணகி.கோவலன்—கட்டில் அறை`
- source scans: 36–38
- status: `assembly-reviewed`
- `visual_text_fidelity: "passed"`

Direct high-resolution source inspection covered all three scans, both physical page boundaries, all column transitions, scan 36's ornate heading/setting and quoted passage, scan 37's photograph/caption plus split textual blocks, and scan 38's bracketed left-column direction continuing into the right column.

Source-pixel corrections during this fidelity pass:

- `pages/0037.md`: `உன் மறந்தாலன்றோ` → source-visible `உனை மறந்தாலன்றோ`.
- `pages/0037.md`: `என்ன எடுத்துப்` → source-visible `என்னை எடுத்துப்`.

No wording correction was required in `pages/0036.md` or `pages/0038.md`.

Boundary/structure checks:

- scan 36 closes with கண்ணகியின் `...என நினைப்பீரா அத்தான்?...`; scan 37 resumes with கோவலன்'s `நினைக்கமாட்டேன் கண்ணே; ...`;
- on scan 37, the left-column Kovalan speech above the photograph continues below it with unlabelled `கனவுக் கற்பனையில் உன் எழிலே உண்ணுவேன்.` before reading proceeds to the right column;
- scan 37 closes with `...அகல்வதில்லே உன்னைவிட்டு என்றுமே!...`; scan 38 begins new `கண் : மெய்தானு அத்தான்...`;
- scan 38's bracket beginning `[கோவலன் தர்ம சங்கடத்தில் துடிக்கிறான்.` crosses columns and closes with `கண்ணகி வந்தவாறு...]`;
- scan 38 closes scene 9; scan 39 begins `காட்சி-10`.

Visual layers remain separate: scan 36's uncaptioned ornamental oil-lamp/interior illustration; scan 37's photograph with exact printed caption `(சம்பாபதி கோயில் — பூம்புகார்)`; scan 38's uncaptioned sculptural photograph. Pagination provenance: scans 36–37 none visible; scan 38 prints `22`.

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

Process **காட்சி-10 / scans 39–41 — `கலையரசி கண்ட உவகை`, setting `மாதவி இல்லம்`** as one complete scene-assembly + visual-text-fidelity activity.

- Inputs: `pages/0039.md`, `pages/0040.md`, `pages/0041.md`.
- Output: `scenes/10.md`.
- Scan 39 contains the decorative title, setting `மாதவி இல்லம்`, internal heading `தெரு`, and a later circular library/accession stamp overlapping the decorative heading; the stamp is not publication text.
- Scan 40 contains the final literary text of scene 10 and prints page `24`. Preserve source forms including repeated `ஆடுகிறாள்.`, `அது வும்`, `“தடால்!”`, `கலை பெண்ணும் அலை`, `மண்ணுளும்`, `கண்ணுளன்`, and `கண்ணு!`.
- Scan 40's small uncaptioned ornamental/conch-like illustration remains a visual layer.
- Scan 41 is a full-page pictorial-only scan associated with scene 10: no literary text, caption or visible pagination. Do not omit it from source provenance or infer an identity for the figure.
- Scan 42 begins `காட்சி-11`, so scene 10 physically spans scans 39–41 although literary text ends on scan 40.
- Inspect scans 39–41 directly at native/enlarged resolution; verify the literary boundary 39 → 40, pictorial boundary 40 → 41, every column transition and all visual layers before promotion.

Do not begin English translation.