# சிலப்பதிகாரம் நாடகக் காப்பியம் — Project Handover

Prepared for continuation in a fresh chat/session.

## Repository

- Repository: `pugazg/kalaignar-stage-plays`
- Branch: `main`
- Active work: `works/silappathikaram-nataka-kappiyam/`
- Controlling Tamil source filename: `TVA_BOK_0016473_சிலப்பதிகாரம்_நாடகக்_காப்பியம்.pdf`
- The source PDF is **not** committed to GitHub and must remain outside the repository.

## Mandatory source authority

The supplied Tamil scan is the controlling source for this edition.

Do not silently modernize, normalize, correct, reconstruct or improve the printed Tamil. Preserve source-supported spelling, punctuation, spacing, speaker labels, stage directions, repetitions, unusual grammar, historical forms, page/column breaks, visible page numbers and anomalies.

OCR, parsed text, other editions and the published English translation are assistive/secondary witnesses only. They are never authority over the controlling Tamil scan.

Before continuing, read completely:

1. `STAGE_PLAY_PROCESSING_GUIDE.md`
2. `docs/SILAPPATHIKARAM_CONTINUATION_GUIDELINES.md`
3. this handover
4. root `HANDOVER.md`
5. `works/silappathikaram-nataka-kappiyam/README.md`
6. `works/silappathikaram-nataka-kappiyam/indexes/page-map.md`
7. `works/silappathikaram-nataka-kappiyam/audit.md`
8. `works/silappathikaram-nataka-kappiyam/SCENE_ASSEMBLY_PLAN.md`
9. `works/silappathikaram-nataka-kappiyam/VISUAL_TEXT_FIDELITY_CHECK.md`
10. `works/silappathikaram-nataka-kappiyam/SCENE_ASSEMBLY_PILOT_REVIEW.md`
11. `works/silappathikaram-nataka-kappiyam/scenes/01.md`
12. `works/silappathikaram-nataka-kappiyam/scenes/02.md`
13. `works/silappathikaram-nataka-kappiyam/scenes/03.md`
14. `works/silappathikaram-nataka-kappiyam/pages/0021.md`
15. `works/silappathikaram-nataka-kappiyam/pages/0022.md`
16. `works/silappathikaram-nataka-kappiyam/pages/0023.md`

## Current verified checkpoint

- Supplied source length: **88 physical scans**.
- Scans **1–88 are visually verified**.
- Detailed page-level verification covers **காட்சி-1 through காட்சி-38** and the scan-88 closing tableau.
- Tamil page-level visual verification is complete.
- Tamil transcription completion audit / scene-assembly readiness review: **PASS**.
- Mandatory direct visual-text fidelity protocol: active for every assembly.
- Scene assembly: **started**.
- `காட்சி-1 / scan 17`: `assembly-reviewed`, `visual_text_fidelity: "passed"`.
- `காட்சி-2 / scan 18`: `assembly-reviewed`, `visual_text_fidelity: "passed"`.
- `காட்சி-3 / scans 19–20`: `assembly-reviewed`, `visual_text_fidelity: "passed"`.
- **3 of 38 numbered scenes are assembled and assembly-reviewed.**
- English translation has **not started** and remains locked.

Previously verified page records must not be restarted, retranscribed or casually modified. Any change to a verified reading requires direct source-pixel evidence and explicit documentation.

## Assembly records

- Audit: `works/silappathikaram-nataka-kappiyam/audit.md`
- Assembly plan: `works/silappathikaram-nataka-kappiyam/SCENE_ASSEMBLY_PLAN.md`
- Visual fidelity protocol: `works/silappathikaram-nataka-kappiyam/VISUAL_TEXT_FIDELITY_CHECK.md`
- Pilot review: `works/silappathikaram-nataka-kappiyam/SCENE_ASSEMBLY_PILOT_REVIEW.md`

Planned assembled outputs remain `scenes/01.md` through `scenes/38.md`, plus separate `scenes/closing-tableau.md` for the distinct scan-88 post-scene tableau.

## Completed scene assemblies

### காட்சி-1 / scan 17

- File: `scenes/01.md`
- Title: `வஞ்சி மூதூரில் முரசறைதல்`
- Separate setting heading: none; `setting: null`
- Status: `assembly-reviewed`
- Visual fidelity: `passed`
- No page-record correction was required.

### காட்சி-2 / scan 18

- File: `scenes/02.md`
- Title: `செங்குட்டுவன் பிறந்தநாள் விழா`
- Setting: `வஞ்சி`
- Status: `assembly-reviewed`
- Visual fidelity: `passed`
- Source-pixel correction: `தனி மாடத்தைவிட்டு` → `தனி மாடத்தை விட்டு` in `pages/0018.md`.

### காட்சி-3 / scans 19–20

- File: `scenes/03.md`
- Title: `விழாவும் வினாவும்`
- Setting: `சேரன் அரண்மனை`
- Status: `assembly-reviewed`
- Visual fidelity: `passed`
- First multi-scan assembly; explicit scan-19 / scan-20 source-boundary comments retained.

Direct 500-ppi fidelity inspection corrected the following earlier page-record punctuation only on source-pixel evidence:

- scan 19: `என்றும்....அந்நாள்` → `என்றும்...அந்நாள்`;
- scan 20: `உண்மைக் காது!....அவர்` → `உண்மைக் காது!...அவர்`;
- scan 20: `கலங்காது!....` → `கலங்காது!...`;
- scan 20: `இதோ....நான்` → `இதோ...நான்`;
- scan 20: `வெல்லுகிறேன்....அண்ணனையே` → `வெல்லுகிறேன்...அண்ணனையே`;
- scan 20: `பாரும்!....வருகிறேன்!...` → `பாரும்!...வருகிறேன்!...`.

The scene-3 draft also contained an assembly-only spacing collapse, `செங்குட்டுவனுக்குத்தான்`; source pixels and the corrected page record require `செங்குட்டுவனுக்குத் தான்`, which was restored before `assembly-reviewed` status.

The scan-20 left-to-right column continuation is preserved as `... இது உண்மைக் காது!...`. The quoted குறள் wording remains exactly as printed on the source; no standard-text correction was imported.

## Assembly phase rules

For every scene:

- first assemble from verified page record(s) at `status: "draft"`, `visual_text_fidelity: "pending"`;
- retain exact speaker labels, dialogue, stage directions, repetitions, punctuation, source-supported spacing and unusual forms;
- join only demonstrably mechanical printed line/column/page wrapping;
- preserve scan provenance, especially across multi-scan scenes;
- keep visual material/captions distinct from literary text;
- do not infer a setting heading, pagination or obscured text;
- inspect every contributing source scan directly at native/enlarged resolution;
- compare every assembled character, punctuation mark and mechanical join against source pixels;
- for multi-scan scenes, inspect both sides of each physical page boundary directly;
- compare the assembly again against all contributing verified page records;
- set `visual_text_fidelity: "passed"` and `status: "assembly-reviewed"` only when both checks pass;
- if source pixels prove a page record wrong, correct only the affected verified reading and explicitly document the source-pixel reason first.

## Final source obstruction — scan 88

After `காட்சி-38 — கண்ணகி சிலைக்குக் கல்`, three centred printed `*` marks introduce `வஞ்சிமூதூரில் / கண்ணகி சிலை நாட்டு விழா`.

A later circular library/accession stamp containing handwritten `164596` obscures leading characters of two tableau lines. Those characters remain explicitly unresolved in `pages/0088.md` and must not be reconstructed from context, another edition or the English translation.

## Translation terminology lock

Future English translation has not started.

- `அந்தணர்` must **not** automatically be translated as “Brahmin.”
- Preserve distinctions among `பிராமண`, `பார்ப்பன`, `அந்தணர்`, `மறையவன்`, and other source-specific terms.
- Decide English renderings only during dedicated terminology review.
- When translation eventually begins, retain Kalaignar's rhetoric, cadence, repetition and dramatic voice.

The published English translation remains a secondary comparison witness only and must never be used to alter verified Tamil silently.

## Exact next activity — காட்சி-4 assembly + visual fidelity

Do **not** begin English translation.

Process **காட்சி-4 / scans 21–23 — `இளங்கோ துறவு`, setting `சேரலாதன் மாளிகை`** as one complete scene.

1. Read verified `pages/0021.md`, `pages/0022.md`, and `pages/0023.md` completely.
2. Create `scenes/04.md` at `status: "draft"`, `visual_text_fidelity: "pending"`.
3. Preserve the exact printed scene number, decorative title, setting heading, stage directions, speaker labels, dialogue, punctuation, repetitions and unusual forms.
4. Insert explicit source-scan provenance so both physical page boundaries remain recoverable.
5. Join only demonstrably mechanical printed wrapping; do not silently join a cross-page or cross-column continuation until both source sides have been visually checked.
6. Inspect actual scans 21–23 at native/enlarged resolution and compare the complete assembled Tamil character-by-character against source pixels.
7. Verify both page boundaries and every column transition especially carefully.
8. Compare `scenes/04.md` again against all three verified page records.
9. Promote to `assembly-reviewed` / `visual_text_fidelity: "passed"` only if both checks pass.
10. If source pixels prove a verified page reading wrong, document and correct only that affected reading before updating the scene.

## Phase state

Completed:

- physical page mapping and page records for all 88 scans;
- direct Tamil page-level verification;
- scenes 1–38 page-level verification;
- closing-tableau source-layer separation;
- Tamil transcription completion audit;
- scene-assembly plan;
- visual-text fidelity protocol;
- scene-1 assembly/fidelity pilot;
- scene-2 assembly/fidelity review;
- scene-3 multi-scan assembly/fidelity review.

Next:

- scene 4 assembly + visual fidelity;
- scenes 5–38 + closing tableau with the same gate;
- global Tamil consistency/source review;
- only then, if directed, English translation and translation review.
