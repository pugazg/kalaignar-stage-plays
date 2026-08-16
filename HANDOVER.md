# Kalaignar Stage Plays — Handover

## Repository

`pugazg/kalaignar-stage-plays` on `main`.

## Fresh-session continuation package

For a new chat/window, read these together before making changes:

1. `STAGE_PLAY_PROCESSING_GUIDE.md`
2. `docs/SILAPPATHIKARAM_CONTINUATION_GUIDELINES.md`
3. `docs/SILAPPATHIKARAM_PROJECT_HANDOVER.md`
4. `docs/NEXT_CHAT_PROMPT_SILAPPATHIKARAM.md`
5. `works/silappathikaram-nataka-kappiyam/README.md`
6. `works/silappathikaram-nataka-kappiyam/indexes/page-map.md`
7. `works/silappathikaram-nataka-kappiyam/audit.md`
8. `works/silappathikaram-nataka-kappiyam/SCENE_ASSEMBLY_PLAN.md`
9. `works/silappathikaram-nataka-kappiyam/VISUAL_TEXT_FIDELITY_CHECK.md`

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
- Detailed dramatic-body verification covers **காட்சி-1 through காட்சி-38**.
- The scan-88 post-scene closing tableau is archived separately from the numbered scene.
- Tamil page-level visual verification is **complete**.
- Repository-wide Tamil transcription completion audit: **complete / PASS**.
- Scene-assembly readiness plan: **complete**.
- Mandatory assembly visual-text fidelity protocol: **defined**.
- Scene assembly: **not yet started**.
- English translation: **not started and remains locked**.

## Newly completed activity — Tamil completion audit / assembly readiness

The audit is recorded in:

`works/silappathikaram-nataka-kappiyam/audit.md`

It confirms:

- continuous page-record coverage `pages/0001.md` through `pages/0088.md` with no missing filename;
- live page-map status `verified` across scans 1–88;
- scene extents mapped for **காட்சி-1 through காட்சி-38**;
- scene titles/settings and special structural notes reconciled for assembly;
- pagination anomalies, visual/caption layers and library/accession obstructions inventoried;
- scan-88 stamp-obscured tableau characters remain explicitly unresolved rather than reconstructed.

The assembly convention is recorded in:

`works/silappathikaram-nataka-kappiyam/SCENE_ASSEMBLY_PLAN.md`

The mandatory direct scan-to-scene fidelity protocol is recorded in:

`works/silappathikaram-nataka-kappiyam/VISUAL_TEXT_FIDELITY_CHECK.md`

Planned outputs are `scenes/01.md` through `scenes/38.md`, plus `scenes/closing-tableau.md` for the distinct scan-88 post-scene material.

## Assembly rules now controlling

- Assemble only from verified `pages/NNNN.md` records.
- Verified page records remain authoritative over scene files during construction; the actual scan remains controlling if direct pixel inspection proves a discrepancy.
- Mechanical line/column/page wrapping may be joined only when wording and punctuation are unchanged.
- Preserve repetitions, stage directions, source-supported unusual grammar/spelling and punctuation.
- Keep every illustration, photograph, caption and decorative title artwork in a separate source-visual layer.
- Preserve scan provenance for multi-scan scenes.
- Do not infer missing pagination.
- Do not reconstruct scan-88 stamp-covered characters.
- Every assembled scene must undergo a **direct visual text fidelity check against its actual contributing scan(s)**, not just against page records.
- A scene may become `assembly-reviewed` only after `visual_text_fidelity: "passed"` and a page-record comparison both succeed.

## Permanent future-translation terminology note

Do **not** automatically translate Kalaignar's `அந்தணர்` as “Brahmin.” Preserve distinctions among `பிராமண`, `பார்ப்பன`, `அந்தணர்`, `மறையவன்`, and other source-specific terms. Decide English renderings only during dedicated terminology/translation review.

When English translation eventually begins, translate from the verified, visually fidelity-checked and assembly-reviewed Tamil archive and retain Kalaignar's rhetoric, cadence, repetition and dramatic voice. The published English translation remains a secondary comparison witness only.

## Exact next activity

Do **not** begin English translation.

Process **காட்சி-1 / scan 17** as the combined **scene-assembly + visual-text fidelity pilot**:

- input page record: `works/silappathikaram-nataka-kappiyam/pages/0017.md`;
- output target: `works/silappathikaram-nataka-kappiyam/scenes/01.md`;
- title: `வஞ்சி மூதூரில் முரசறைதல்`;
- physical source: scan 17;
- there is no separate printed setting heading, so use `setting: null` and do not invent one;
- keep the architectural/drummer title artwork separate from literary text;
- first create the scene at `status: "draft"`, `visual_text_fidelity: "pending"`;
- then inspect the **actual scan 17 pixels at native/enlarged resolution** and compare the complete assembled Tamil character-by-character against the source;
- verify scene/title text, opening stage direction, speaker labels, dialogue, punctuation, ellipses/dashes/brackets, repetitions, source-significant spacing and every mechanical line join;
- compare the completed assembly against `pages/0017.md` as a second check;
- if both pass, set `visual_text_fidelity: "passed"` and `status: "assembly-reviewed"`;
- if source pixels reveal an existing page-record error, correct only that affected reading and document the reason explicitly;
- do not begin scene 2 until the pilot file format and fidelity procedure are accepted.

The next phase is **Tamil scene assembly with mandatory visual-text fidelity review**, not translation.
