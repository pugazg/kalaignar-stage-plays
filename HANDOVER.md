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
11. assembled scene files `scenes/01.md` through `scenes/08.md`

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
- Scenes **1–8 are assembly-reviewed with `visual_text_fidelity: "passed"`**.
- **8 of 38 numbered scenes are assembly-reviewed.**
- English translation has not started and remains locked.

## Latest completed activity — காட்சி-8

Scene file: `works/silappathikaram-nataka-kappiyam/scenes/08.md`

- title: `கண்ணகி இல்லறம்`
- setting: `கோவலன் வீடு:—பள்ளியறை`
- source scans: 33–35
- status: `assembly-reviewed`
- `visual_text_fidelity: "passed"`

Direct high-resolution source inspection covered all three scans, both physical page boundaries, scan 33's two-column text and quoted marriage passage, scan 34's same-speaker cross-column continuation, scan 35's closing dialogue, and all visual layers.

No verified page-record correction was required during scene-8 fidelity review.

Assembly-only fidelity correction:

- draft `மகன்! ...என்` → source-faithful mechanical join `மகன்!...என்`; scan 34's next printed line begins with the ellipsis itself.

Boundary/structure checks:

- scan 33 closes `யாழிடைப் பிறவா இசை!....`; scan 34 begins new `கண் : அத்தான்!...`;
- on scan 34, `மாசாத் : ... பாடங்கற்பிக்கிறேன்......` continues in the right column with unlabelled `கண்ணகி! பயப்படாதே!...`; no redundant speaker label is inserted;
- scan 34 closes `[அழுகிறாள்!]`; scan 35 begins new `கண் : அம்மா!...`;
- scan 35 closes `காட்சி-8`; scan 36 begins `காட்சி-9`.

Protected scene-8 source forms include `நீ யில்லாமல்`, `சுவையே யில்லை!`, `உன் தல எழுத்து`, `நம்பி யிருந்தேன்`, `மருமகளாக வாழ்த்து;`, `போவதில்ல.`, `கனி யுன்னைத்`, `கவலைப்படாதே யம்மா!`, `இரண்டு சொன்று`, `தானு இருக்கிறாய்?`, `பொய்தானு?`, `எல்லோருந்தான்`, `அப்படியானு....`, `ஆதரவுபட்ட`, and `பார் முழுதும்`.

Visual layers remain separate: scan 33's two figure/statue photographs; scan 34's ornament/jewel-like and lotus illustrations; scan 35's standing-woman illustration. Pagination provenance: scan 33 none visible; scan 34 prints `18`; scan 35 none visible.

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

Process **காட்சி-9 / scans 36–38 — `பிரிவினை தந்த பேதை`, setting `கண்ணகி.கோவலன்—கட்டில் அறை`** as one complete scene-assembly + visual-text-fidelity activity.

- Inputs: `pages/0036.md`, `pages/0037.md`, `pages/0038.md`.
- Output: `scenes/09.md`.
- Preserve the setting punctuation exactly: `கண்ணகி.கோவலன்—கட்டில் அறை`.
- Preserve scan 36's quoted two-line passage `“பெய்யெனப் பெய்யும் மழையே! / கொழுநனைத் தொழுதெழும் நேரிழையே!”` exactly as printed.
- Preserve source-specific forms including `அப்படியென்றுல்?...`, `ஊடல் என்றுல்`, `தில சிறந்தது`, `இது ஒன்றும் ஊடல் இல்ல;`, `வெளிநாட்டுக்கா?.`, `கத்து கடல் கிழிச்`, `உன் மறந்தாலன்றோ`, `முடவனுயிருப்பேன்.`, `செல்வ!`, `கொல்லாமற் கொல்லாதீர் கண்ணுளா!...`, `மெய்தானு`, `கிணை தொடுத்...`, `என் வெறுக்கிறீர்`, and `உன் நூல்தான் எல்லாம்...`.
- Keep scan 36's uncaptioned ornamental oil-lamp/interior illustration, scan 37's photograph with exact caption `(சம்பாபதி கோயில் — பூம்புகார்)`, and scan 38's uncaptioned sculptural photograph separate from dramatic text.
- Scans 36–37 have no securely visible printed pagination; scan 38 prints `22`.
- Inspect all three scans directly, including both physical page boundaries and scan 38's bracketed left-column direction continuing at the top of the right column.
- Scan 38 closes scene 9; scan 39 begins `காட்சி-10`.

Do not begin English translation.