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
11. `works/silappathikaram-nataka-kappiyam/scenes/01.md`
12. `works/silappathikaram-nataka-kappiyam/scenes/02.md`
13. `works/silappathikaram-nataka-kappiyam/scenes/03.md`

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
- `காட்சி-1 / scan 17`: `scenes/01.md` — **assembly-reviewed**, `visual_text_fidelity: "passed"`.
- `காட்சி-2 / scan 18`: `scenes/02.md` — **assembly-reviewed**, `visual_text_fidelity: "passed"`.
- `காட்சி-3 / scans 19–20`: `scenes/03.md` — **assembly-reviewed**, `visual_text_fidelity: "passed"`.
- English translation: **not started and remains locked**.

## Scene-3 fidelity result

`scenes/03.md` assembles `காட்சி-3 — விழாவும் வினாவும்`, setting `சேரன் அரண்மனை`, from verified `pages/0019.md` and `pages/0020.md`.

This was the first multi-scan scene assembly. The scene file retains explicit `source scan 19` and `source scan 20` boundary comments, and both physical scans were inspected directly at high resolution.

The visual-text fidelity gate found genuine pre-existing page-record punctuation errors and corrected them only on direct source-pixel evidence:

- scan 19: `என்றும்....அந்நாள்` → source-visible `என்றும்...அந்நாள்`;
- scan 20: `உண்மைக் காது!....அவர்` → `உண்மைக் காது!...அவர்`;
- scan 20: `கலங்காது!....` → `கலங்காது!...`;
- scan 20: `இதோ....நான்` → `இதோ...நான்`;
- scan 20: `வெல்லுகிறேன்....அண்ணனையே` → `வெல்லுகிறேன்...அண்ணனையே`;
- scan 20: `பாரும்!....வருகிறேன்!...` → `பாரும்!...வருகிறேன்!...`.

The draft scene also briefly collapsed the source-supported spacing `செங்குட்டுவனுக்குத் தான்` to `செங்குட்டுவனுக்குத்தான்`; the direct scan comparison caught and corrected this **assembly-only** error before review passed.

The scan-20 cross-column continuation is retained as `... இது உண்மைக் காது!...` with no invented punctuation. The quoted குறள் wording is preserved exactly as printed and was not corrected from another edition.

Visual layers remain separate: scan 19's architectural title art, uncaptioned human-figure illustration and hanging-lamp-like motif, plus scan 20's uncaptioned throne/royal-seat-like illustration. Scan 20's printed page marker `4` remains provenance only.

## Assembly rules now controlling

- Assemble only from verified `pages/NNNN.md` records.
- Actual scan pixels are controlling for the mandatory fidelity gate.
- Join only demonstrably mechanical line/column/page wrapping.
- Preserve source wording, speaker labels, stage directions, repetitions, unusual forms, punctuation and source-supported spacing.
- Keep illustrations, photographs, captions and decorative artwork in separate source-visual sections.
- Preserve scan provenance for multi-scan scenes and inspect both sides of every source-page boundary.
- Do not infer pagination or reconstruct damaged/stamp-obscured text.
- Every scene begins `draft` / `visual_text_fidelity: pending` and can become `assembly-reviewed` only after direct scan comparison and page-record comparison both pass.

## Permanent future-translation terminology note

Do **not** automatically translate Kalaignar's `அந்தணர்` as “Brahmin.” Preserve distinctions among `பிராமண`, `பார்ப்பன`, `அந்தணர்`, `மறையவன்`, and other source-specific terms. English translation remains a later phase and must retain Kalaignar's rhetoric, cadence, repetition and dramatic voice.

## Exact next activity

Process **காட்சி-4 / scans 21–23 — `இளங்கோ துறவு`, setting `சேரலாதன் மாளிகை`** as one complete scene-assembly + visual-text-fidelity activity.

- Inputs: `pages/0021.md`, `pages/0022.md`, `pages/0023.md`.
- Output: `scenes/04.md`.
- Assemble at `draft` / `visual_text_fidelity: pending`.
- Preserve explicit source-scan provenance and both physical page boundaries.
- Inspect actual scans 21, 22 and 23 at native/enlarged resolution.
- Compare scene/title/setting text, stage directions, speaker labels, dialogue, punctuation, every mechanical join, and both page-boundary continuations character-by-character against source pixels.
- Compare again with all three verified page records.
- Promote only after both checks pass.
- Do not begin English translation.
