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

## Permanent source rules

The supplied Tamil scan is controlling authority. Do not silently modernize, correct, normalize, reconstruct or improve Kalaignar's Tamil. OCR and other editions are assistive/secondary only. Source PDFs are not committed.

Previously verified scans are protected: change a verified reading only when direct source-pixel inspection proves it wrong, and document the correction explicitly.

## Current work

**சிலப்பதிகாரம் — நாடகக் காப்பியம்**  
Path: `works/silappathikaram-nataka-kappiyam/`

Tamil source: `TVA_BOK_0016473_சிலப்பதிகாரம்_நாடகக்_காப்பியம்.pdf`

## Current checkpoint

- Supplied scan length: **88 physical scans**.
- Scans **1–88 are visually verified**.
- Detailed page-level verification covers **காட்சி-1 through காட்சி-38** and the scan-88 closing tableau.
- Tamil transcription completion audit: **PASS**.
- Scene-assembly readiness plan: complete.
- Mandatory direct visual-text fidelity protocol: active.
- Scene assembly: **started**.
- `காட்சி-1 / scan 17`: `scenes/01.md` is **assembly-reviewed** with `visual_text_fidelity: "passed"`.
- Reusable assembly/fidelity pilot: **accepted**.
- English translation: **not started and remains locked**.

## Completed scene-1 assembly pilot

Pilot review:

`works/silappathikaram-nataka-kappiyam/SCENE_ASSEMBLY_PILOT_REVIEW.md`

Scene file:

`works/silappathikaram-nataka-kappiyam/scenes/01.md`

Verified results:

- scene: `காட்சி-1`;
- title: `வஞ்சி மூதூரில் முரசறைதல்`;
- physical extent: scan 17 only;
- no separate printed setting heading; `setting: null` is correct;
- actual controlling scan 17 was rendered at high resolution and inspected as full-page plus enlarged title/left/right text views;
- complete assembled stage direction, speaker label, dialogue, punctuation, repetitions and mechanical joins were compared directly against source pixels and against `pages/0017.md`;
- no verified page-record correction was required;
- title artwork and the lower uncaptioned pictorial layer remain separate from literary text.

Accepted mechanical joins include `பொறிக்கப்பட்டிருக் / கிறது` → `பொறிக்கப்பட்டிருக்கிறது`, `வேலைப் / பாடமைந்த` → `வேலைப்பாடமைந்த`, `காணப் / படுகிறது` → `காணப்படுகிறது`, `தமி / ழகம்` → `தமிழகம்`, and `சேர / லாதர்` → `சேரலாதர்` within `நெடுஞ் சேரலாதர்`.

Source-supported forms such as `தலை நகரான`, `அறிவிப்பு!....`, `ஆனை`, `விற்கொடி. நாட்டிய`, repeated `கொட்டுவோம்`, and `பூரிப்போடு!` remain unchanged.

## Assembly rules now controlling

- Assemble only from verified `pages/NNNN.md` records.
- Actual scan pixels are controlling for the mandatory fidelity gate.
- Join only demonstrably mechanical line/column/page wrapping.
- Preserve source wording, speaker labels, stage directions, repetitions, unusual forms and punctuation.
- Keep illustrations, photographs, captions and decorative artwork in separate source-visual sections.
- Preserve scan provenance for multi-scan scenes.
- Do not infer pagination or reconstruct damaged/stamp-obscured text.
- Every scene begins `draft` / `visual_text_fidelity: pending` and can become `assembly-reviewed` only after direct scan comparison and page-record comparison both pass.

## Permanent future-translation terminology note

Do **not** automatically translate Kalaignar's `அந்தணர்` as “Brahmin.” Preserve distinctions among `பிராமண`, `பார்ப்பன`, `அந்தணர்`, `மறையவன்`, and other source-specific terms. English translation remains a later phase and must retain Kalaignar's rhetoric, cadence, repetition and dramatic voice.

## Exact next activity

Process **காட்சி-2 / scan 18 — `செங்குட்டுவன் பிறந்தநாள் விழா`, setting `வஞ்சி`** as the next combined scene-assembly + visual-text-fidelity activity.

- Input: `pages/0018.md`.
- Output: `scenes/02.md`.
- Assemble at `draft` / `visual_text_fidelity: pending`.
- Inspect actual scan 18 at native/enlarged resolution.
- Compare all scene/title/setting text, stage directions, speaker labels, dialogue, punctuation and every mechanical join character-by-character against source pixels.
- Compare again with `pages/0018.md`.
- Promote only after both checks pass.
- Do not begin English translation.
