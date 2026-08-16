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

## Current verified checkpoint

- Supplied source length: **88 physical scans**.
- Scans **1–88 are visually verified**.
- Detailed dramatic-body verification covers **காட்சி-1 through காட்சி-38**.
- The post-scene closing tableau on scan 88 is also archived.
- **Tamil page-level visual verification is complete for the supplied source.**
- **Tamil transcription completion audit / scene-assembly readiness review is complete and passed.**
- Scene assembly has **not yet started**.
- Previously verified page records must not be restarted, retranscribed or casually modified.
- Any change to a verified reading requires direct source-pixel evidence and explicit documentation.

## Completion-audit result

Audit record:

`works/silappathikaram-nataka-kappiyam/audit.md`

Assembly plan:

`works/silappathikaram-nataka-kappiyam/SCENE_ASSEMBLY_PLAN.md`

The audit establishes:

- continuous page-record coverage `pages/0001.md` through `pages/0088.md`;
- no missing physical page record;
- live page-map status `verified` for scans 1–88;
- verified scene extents for all 38 numbered scenes;
- scene headings/settings/special internal headings reconciled for assembly;
- known pagination anomalies, photographs, illustrations, captions and library/accession obstructions inventoried;
- scan-88 stamp-covered leading characters remain explicitly unresolved and may not be reconstructed from context.

The assembly manifest records the following broad scene extents:

- scenes 1–10: scans 17–41;
- scenes 11–16: scans 42–50;
- scenes 17–28: scans 51–71;
- scene 29: scans 72–75;
- scenes 30–34: scans 76–81;
- scene 35: scans 82–85;
- scenes 36–38: scans 86–88;
- scan 88 additionally contains a **separate post-scene closing tableau** after scene 38.

Use the exact per-scene manifest in `audit.md` / `SCENE_ASSEMBLY_PLAN.md`; do not infer boundaries from the broad ranges above.

## Final source obstruction — scan 88

After `காட்சி-38 — கண்ணகி சிலைக்குக் கல்`, three centred printed `*` marks introduce:

- `வஞ்சிமூதூரில்`
- `கண்ணகி சிலை நாட்டு விழா`

A later circular library/accession stamp containing handwritten `164596` obscures leading characters on two closing-tableau lines. Native/enlarged and non-destructive image variants could not securely recover the hidden strokes.

`pages/0088.md` therefore preserves explicit obstruction markers before the source-visible suffixes `ங்குட்டுவன்` and `ங்கோவடிகள்`. Scene assembly and later translation must retain that uncertainty unless new source evidence defensibly resolves it.

## Assembly phase rules

Assembly is a new derivative archival layer; verified page records remain controlling.

Planned output:

```text
works/silappathikaram-nataka-kappiyam/scenes/
  01.md
  02.md
  ...
  38.md
  closing-tableau.md
```

Rules:

- assemble only from verified page records;
- retain exact speaker labels, dialogue, stage directions, repetition and punctuation;
- mechanical printed line/column wrapping may be joined only where wording/punctuation remain unchanged;
- preserve scan provenance, especially across multi-scan scenes;
- visual material and captions remain a distinct source layer;
- do not infer a setting heading where the source has none;
- do not insert printed page numbers into literary text;
- do not repair anomalous printed pagination;
- do not reconstruct library-stamp-obscured text;
- every assembled scene begins at `draft` and requires assembly-level review before it is considered ready for global review.

## Translation terminology lock

Future English translation has **not started**.

Permanent instruction:

- `அந்தணர்` must **not** automatically be translated as “Brahmin.”
- Preserve distinctions among `பிராமண`, `பார்ப்பன`, `அந்தணர்`, `மறையவன்`, and other source-specific terms.
- Decide English renderings only during dedicated terminology review.
- When translation eventually begins, retain Kalaignar's rhetoric, cadence, repetition and dramatic voice.

The published English translation remains a secondary comparison witness only and must never be used to alter the verified Tamil silently.

## Exact next activity — scene assembly pilot

Do **not** begin English translation.

Assemble **காட்சி-1 / scan 17** as the pilot scene file:

- verified page source: `works/silappathikaram-nataka-kappiyam/pages/0017.md`;
- output target: `works/silappathikaram-nataka-kappiyam/scenes/01.md`;
- decorative title: **`வஞ்சி மூதூரில் முரசறைதல்`**;
- no separate printed setting heading is present, so `setting: null` should be used rather than inventing one from the opening stage direction;
- the architectural/drummer heading artwork remains a separate visual layer;
- assemble at status `draft`;
- immediately perform an assembly-level comparison against `pages/0017.md` and document whether the pilot file format is accepted before moving to scene 2.

## Phase state

Completed:

- physical page mapping for all 88 scans;
- direct Tamil page-level verification;
- detailed verification of scenes 1–38;
- final closing-tableau source-layer separation;
- Tamil transcription completion audit;
- scene-assembly readiness plan.

Next:

- scene-1 assembly pilot;
- assembly review;
- scenes 2–38 + closing tableau assembly;
- global Tamil consistency/source review;
- only then, if directed, English translation and translation review.
