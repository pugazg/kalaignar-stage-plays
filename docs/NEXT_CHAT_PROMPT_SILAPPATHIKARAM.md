# Next Chat Prompt — சிலப்பதிகாரம் நாடகக் காப்பியம்

Copy/paste the prompt below into a fresh ChatGPT window. **Attach the Tamil source PDF** `TVA_BOK_0016473_சிலப்பதிகாரம்_நாடகக்_காப்பியம்.pdf` because every scene assembly requires a direct visual-text fidelity comparison against the controlling scan.

---

Continue the Kalaignar Stage Plays archival project directly in:

`pugazg/kalaignar-stage-plays`

Work on `main`.

Active work:

`works/silappathikaram-nataka-kappiyam/`

Controlling Tamil source:

`TVA_BOK_0016473_சிலப்பதிகாரம்_நாடகக்_காப்பியம்.pdf`

## Mandatory startup

Before making any change, read these files completely and follow them exactly:

1. `STAGE_PLAY_PROCESSING_GUIDE.md`
2. `docs/SILAPPATHIKARAM_CONTINUATION_GUIDELINES.md`
3. `docs/SILAPPATHIKARAM_PROJECT_HANDOVER.md`
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

Use the GitHub connector and work directly in the existing repository.

If the Tamil PDF is not attached/available, **stop and ask me to attach it**. Do not perform the visual-text fidelity gate from repository text alone.

## Source authority

The Tamil scan remains controlling authority. Verified `pages/NNNN.md` records are the immediate source for scene assembly, but every assembled scene must also be compared directly against the actual source pixels.

Do not silently modernize, correct, normalize, reconstruct or improve Kalaignar's Tamil.

Preserve spelling, punctuation, speaker labels, stage directions, repetition, unusual grammar, source-supported spacing, page/column continuations and source anomalies. OCR, another edition and the published English translation are secondary/assistive only.

## Completed work — do not restart

- All **88 supplied physical scans are visually verified**.
- **காட்சி-1 through காட்சி-38 are complete at page-record level**.
- The scan-88 post-scene closing tableau is archived.
- Tamil page-level visual verification is complete.
- Repository-wide Tamil transcription completion audit is **complete / PASS**.
- Scene-assembly plan and mandatory visual-text fidelity protocol are active.
- `காட்சி-1 / scan 17` → `scenes/01.md`: **assembly-reviewed**, `visual_text_fidelity: "passed"`.
- `காட்சி-2 / scan 18` → `scenes/02.md`: **assembly-reviewed**, `visual_text_fidelity: "passed"`.
- `காட்சி-3 / scans 19–20` → `scenes/03.md`: **assembly-reviewed**, `visual_text_fidelity: "passed"`.
- **3 of 38 numbered scenes are now assembled and assembly-reviewed.**
- English translation has not begun.

Scene-3 fidelity review corrected only source-pixel-proven issues:

- scan 19 `என்றும்....அந்நாள்` → `என்றும்...அந்நாள்`;
- scan 20 `உண்மைக் காது!....அவர்` → `உண்மைக் காது!...அவர்`;
- scan 20 `கலங்காது!....` → `கலங்காது!...`;
- scan 20 `இதோ....நான்` → `இதோ...நான்`;
- scan 20 `வெல்லுகிறேன்....அண்ணனையே` → `வெல்லுகிறேன்...அண்ணனையே`;
- scan 20 `பாரும்!....வருகிறேன்!...` → `பாரும்!...வருகிறேன்!...`.

The scene-3 draft also briefly collapsed source spacing `செங்குட்டுவனுக்குத் தான்`; that assembly-only error was corrected before fidelity passed.

Do not retranscribe or casually modify verified pages. Change a verified page only if direct source-pixel inspection during a fidelity check proves the existing reading wrong.

## Accepted assembly convention

For each scene:

- assemble only from verified page record(s);
- begin at `status: "draft"` and `visual_text_fidelity: "pending"`;
- join only demonstrably mechanical print line/column/page wrapping;
- preserve exact source wording, punctuation, repetitions, speaker labels, stage directions and source-supported spacing;
- keep visual material/captions separate from literary text;
- preserve explicit scan provenance for multi-scan scenes;
- inspect every contributing source scan directly at native/enlarged resolution;
- compare every assembled character and mechanical join to source pixels;
- for multi-scan scenes, inspect both sides of every source-page boundary and every column transition;
- compare the assembly again against all contributing verified page records;
- promote to `status: "assembly-reviewed"` / `visual_text_fidelity: "passed"` only if both checks succeed;
- if source pixels prove a verified page wrong, correct only the affected reading with explicit documentation before updating the scene.

## Exact next activity — காட்சி-4 / scans 21–23

Process **காட்சி-4 / scans 21–23 — `இளங்கோ துறவு`, setting `சேரலாதன் மாளிகை`** as one complete scene-assembly + visual-text-fidelity activity.

Inputs:

- `works/silappathikaram-nataka-kappiyam/pages/0021.md`
- `works/silappathikaram-nataka-kappiyam/pages/0022.md`
- `works/silappathikaram-nataka-kappiyam/pages/0023.md`

Output target:

`works/silappathikaram-nataka-kappiyam/scenes/04.md`

For this activity:

1. Read all three contributing verified page records completely.
2. Create `scenes/04.md` using the accepted front-matter convention, initially `status: "draft"`, `visual_text_fidelity: "pending"`.
3. Preserve `காட்சி-4`, decorative title `இளங்கோ துறவு`, explicit setting `சேரலாதன் மாளிகை`, all stage directions, speaker labels, dialogue, punctuation, repetitions and unusual forms.
4. Keep explicit source-scan boundary provenance in the scene file so contributions from scans 21, 22 and 23 remain recoverable.
5. Join only demonstrably mechanical printed wrapping. Do not silently join a page/column continuation until both physical sides have been inspected.
6. Keep all illustrations/decorative artwork/captions as separate source-visual layers.
7. Inspect the **actual attached scans 21, 22 and 23** at native/enlarged resolution.
8. Compare the complete assembled Tamil character-by-character against source pixels, including scene/title/setting, directions, speaker labels, dialogue, punctuation, source-supported spacing and all joins.
9. Inspect both physical page boundaries and every column transition especially carefully for omissions, duplications or normalized wording.
10. Confirm pagination/visual/library layers remain outside literary text.
11. Compare the visually checked scene again against all three verified page records.
12. If source pixels prove any page record wrong anywhere, correct only that affected verified reading with explicit source-pixel documentation, then regenerate/recheck the scene.
13. Set `visual_text_fidelity: "passed"` and `status: "assembly-reviewed"` only after both direct scan and page-record checks pass.
14. Update README/handover records and identify the next complete scene assembly activity.

## Translation lock

Do not begin English translation.

Permanent terminology instruction: **Do not automatically translate `அந்தணர்` as “Brahmin.”** Preserve distinctions among `பிராமண`, `பார்ப்பன`, `அந்தணர்`, `மறையவன்`, and other source terms. English renderings will be decided only in dedicated terminology review.

When translation eventually begins, retain Kalaignar's language, rhetoric, cadence, repetition and dramatic voice.

## End-of-activity report

Report:

- scene assembled and exact source scans;
- direct visual-text fidelity result;
- both page-boundary / all column-transition verification results;
- whether any verified page reading required correction and why;
- important mechanical joins performed and visually verified;
- visual layers separated;
- files created/updated;
- final `scenes/04.md` status and fidelity state;
- exact next complete scene assembly activity.

Proceed now with **காட்சி-4 / scans 21–23 scene assembly + visual text fidelity**.

---
