# Scene Assembly Plan — சிலப்பதிகாரம் நாடகக் காப்பியம்

This plan begins only after completion of the Tamil page-level transcription audit recorded in `audit.md`.

## Phase purpose

Create readable scene-level archival files **only from verified page records** while preserving recoverable provenance to the physical scans.

This phase is assembly, not rewriting, editing, modernization, correction or translation.

Every assembled scene must also pass the direct **visual text fidelity check** defined in `VISUAL_TEXT_FIDELITY_CHECK.md` before it can become `assembly-reviewed`.

## Source authority during assembly

Use this hierarchy:

1. verified `pages/NNNN.md` records for mechanical scene assembly;
2. the controlling Tamil scan for the mandatory visual-text fidelity check and whenever a join or page-record interpretation must be rechecked;
3. repository verification notes for provenance;
4. other editions / published English translation only as explicitly labelled later witnesses, never to change Tamil silently.

If an assembled line conflicts with a verified page record, the verified page record controls unless a new direct source-pixel correction is documented first. If the verified page record itself conflicts with clearly inspected source pixels, the scan controls and only the affected page may be corrected with explicit documentation.

## Planned output structure

Create:

```text
works/silappathikaram-nataka-kappiyam/scenes/
  01.md
  02.md
  ...
  38.md
  closing-tableau.md
```

The post-scene `வஞ்சிமூதூரில் / கண்ணகி சிலை நாட்டு விழா` material on scan 88 is structurally separate from `காட்சி-38`; assemble it as `closing-tableau.md`, not as an invented `காட்சி-39` and not silently inside scene 38.

## Required scene front matter

Use this shape unless the pilot demonstrates a necessary adjustment:

```yaml
---
scene: 1
title: "வஞ்சி மூதூரில் முரசறைதல்"
setting: null
source_scan_pages: [17]
status: "draft"
assembled_from_verified_pages: true
visual_text_fidelity: "pending"
language: "ta"
source_filename: "TVA_BOK_0016473_சிலப்பதிகாரம்_நாடகக்_காப்பியம்.pdf"
---
```

For scenes with an explicit setting heading, record it verbatim. If the source has **no separate setting heading**, use `setting: null`; do not promote an inferred location from stage prose into a formal setting field.

Where the source has multiple/internal headings, keep the initial setting in front matter and preserve internal headings in the assembled text/structure.

## Assembly rules

### 1. Literary text

Copy only source publication text represented in verified page records:

- scene heading;
- decorative lexical title;
- explicit setting/sub-setting headings;
- speaker labels exactly as printed;
- dialogue;
- stage directions;
- source typographic separators that belong to the dramatic text.

Do not copy verification commentary into the dramatic text.

### 2. Mechanical line and column breaks

Page records intentionally preserve physical breaks. Scene assembly may remove **mechanical** line/column wrapping for readability, but it must not change spelling, wording, punctuation or spacing that is linguistically/source-significant.

Examples:

- a word physically split only because a printed line ends may be joined in the scene file;
- a repeated word or phrase at a column/page transition must remain if the source actually repeats it;
- punctuation at the end/beginning of a physical break must not be silently regularized;
- an uncertain reading or explicit obstruction marker must remain unresolved.

### 3. Page provenance

Every scene file must keep scan provenance recoverable. Use source-boundary comments between physical page contributions when a scene spans more than one scan:

```md
<!-- source scan 44 -->
...
<!-- source scan 45 -->
...
```

For a one-scan scene, front matter `source_scan_pages` is sufficient unless a boundary note adds value.

### 4. Visual layers

Illustrations, photographs, captions and decorative artwork are not dialogue.

After the literary text, add a separate archival section when the scene has visual material:

```md
## Source visual layers

- Scan 41: full-page uncaptioned pictorial/reproduction page; no identity inferred.
```

Printed captions must be reproduced verbatim under the visual-layer section.

### 5. Decorative scene titles

Preserve the verified lexical title exactly.

Do not convert title artwork into inferred words. Important examples:

- scene 21: lexical title is `கலைமகள்`; eye-and-tears artwork remains visual only;
- scene 37: weapon/shield motifs remain visual only;
- scene 38: mountain/stone artwork remains visual only.

### 6. Printed pagination

Do not insert printed page numbers into the literary text. Page numbers remain page-record metadata/provenance.

Do not repair anomalies such as scan 25's printed `2`, scan 73's printed `8`, or scan 81's unresolved `9` plus damaged mark.

### 7. Library/accession layers

Do not place stamps, shelf marks or handwriting into the literary text.

For scan 88, preserve the explicit obstruction markers in the closing tableau. Do not reconstruct the stamp-covered leading letters from context, memory, another edition or the English translation.

### 8. Translation lock

No English translation is performed during assembly.

Permanent terminology instruction remains active: `அந்தணர்` must not automatically be rendered as “Brahmin” in the future. Distinctions among `பிராமண`, `பார்ப்பன`, `அந்தணர்`, `மறையவன்` and related source terms must survive into later terminology review.

### 9. Mandatory visual text fidelity check

After a scene is assembled at `draft`, compare the **assembled scene directly against the actual controlling scan pixels**, not only against its page record.

Follow `VISUAL_TEXT_FIDELITY_CHECK.md` completely.

At minimum, visually recheck:

- scene number and decorative lexical title;
- explicit setting/internal headings;
- every speaker label and abbreviation;
- every dialogue and stage-direction character;
- punctuation, ellipses, dashes, quotation/bracket marks and repetitions;
- every mechanical line/column/page join introduced by assembly;
- source-significant spacing and unusual forms;
- printed textual separators/captions;
- separation of artwork, photographs, pagination and later library/accession marks from literary text.

For multi-scan scenes, inspect both sides of every source-page boundary.

Use `visual_text_fidelity: "passed"` only after the direct scan-to-scene comparison succeeds. If it fails, keep the scene at `draft`, document the mismatch and correct only with source-pixel evidence.

## Scene manifest for assembly

| Scene | Scans | Title | Setting / special structure |
|---:|---|---|---|
| 1 | 17 | `வஞ்சி மூதூரில் முரசறைதல்` | no separate setting heading |
| 2 | 18 | `செங்குட்டுவன் பிறந்தநாள் விழா` | `வஞ்சி` |
| 3 | 19–20 | `விழாவும் வினாவும்` | `சேரன் அரண்மனை` |
| 4 | 21–23 | `இளங்கோ துறவு` | `சேரலாதன் மாளிகை` |
| 5 | 24–25 | `சிலம்பின் தோற்றம்` | `சேரநாடு` |
| 6 | 26–28 | `பூம்புகார்ப் பொற்றொடி` | no separate setting heading |
| 7 | 29–32 | `கலைக்கரசி மாதவி` | `முத்துப் பந்தல்` |
| 8 | 33–35 | `கண்ணகி இல்லறம்` | `கோவலன் வீடு:—பள்ளியறை` |
| 9 | 36–38 | `பிரிவினை தந்த பேதை` | `கண்ணகி.கோவலன்—கட்டில் அறை` |
| 10 | 39–41 | `கலையரசி கண்ட உவகை` | `மாதவி இல்லம்`; scan 41 visual-only associated page |
| 11 | 42 | `கற்பரசியின் கலக்கம்` | `கண்ணகி வீடு` |
| 12 | 43 | `இன்ப வாழ்வில் கோவலன்` | `மாதவி வீடு` |
| 13 | 44–45 | `துன்பப் புயலில் கண்ணகி` | `கண்ணகி வீடு` |
| 14 | 46–48 | `மாதவியின் மாண்பு` | `காவிரி ஆற்றோரம்` |
| 15 | 49 | `மனமாறிந்த கோவலன்` | `கண்ணகி வீடு` |
| 16 | 50 | `மணிமேகலை பிறப்பு` | `மாதவி வீடு` |
| 17 | 51–52 | `மாசறு பொன்மகிழ்வு` | `கண்ணகி வீடு` |
| 18 | 53–54 | `இந்திர விழா-இருமனைகளில்` | `[பல உட்காட்சிகள் அடங்கியது]`; no separate setting heading |
| 19 | 55–58 | `கானல் வரியும் / காதல் பிரிவும்` | `புகார்` |
| 20 | 59–60 | `திருந்திய கோவலன் / திரும்பி வருதல்` | `கண்ணகி வீடு` |
| 21 | 61–62 | `கலைமகள்` | `மாதவி வீடு`; separate eye/tear artwork |
| 22 | 63–64 | `மதுரைப் பயணம்` | `மதுரை செல்லும் வழி` |
| 23 | 65 | `மாதவி துறவு` | `மாசாத்துவான் வீடு` |
| 24 | 66 | `கவுந்தியுடன் கண்ணகி கோவலன்` | `வழியில்` |
| 25 | 67–68 | `நீதி வழுவா நெடுஞ்செழியன்` | `பாண்டியன் அவை` |
| 26 | 69 | `அரசியின் சிலம்பு` | `பொற்கொல்லன் வீடு` |
| 27 | 70 | `ஆய்ச்சியர் அறிமுகம்` | `மதுரை எல்லை`; internal `மாதரி வீடு...` |
| 28 | 71 | `பொற்கொல்லர் முறையீடு` | `பாண்டியன் தனிமாடம்` |
| 29 | 72–75 | `ஒற்றைச் சிலம்பின் ஒலி` | `மாதரி வீடு` |
| 30 | 76 | `சிலம்போ சிலம்பு` | `பொற்கொல்லர் நிலையம்`; internal `சாலை` |
| 31 | 77 | `வளைந்தது செங்கோல்` | `நெடுஞ்செழியன் பள்ளியறை`; internal `தாழ்வாரம்` |
| 32 | 78–79 | `மதுரை மண்ணில் கோவலன் குருதி` | `வீதியிலுள்ள மண்டபம்` |
| 33 | 80 | `கணவன் கள்வனா?` | `குரவைக் கூத்து` |
| 34 | 81 | `வஞ்சினங் கூறுதல்` | `வீதியிலுள்ள மண்டபம்` |
| 35 | 82–85 | `வழக்குரை படலம்` | `பாண்டியன் கொலு மண்டபம் (வெளியே)` |
| 36 | 86 | `தீயினில் திருநகர்` | `தெருக்கள்` |
| 37 | 87 | `வடபுலப் படையெடுப்பு` | `சேரன் செங்குட்டுவன் அவை` |
| 38 | 88 | `கண்ணகி சிலைக்குக் கல்` | `இமயத்தில் - குயிலாலுவம்` |
| — | 88 | closing tableau | `வஞ்சிமூதூரில்` / `கண்ணகி சிலை நாட்டு விழா` |

## Assembly review gates

Each assembled scene moves through these gates:

1. **draft** — mechanically assembled from verified page records; `visual_text_fidelity: pending`;
2. **visual-text-fidelity passed** — assembled text checked directly against all contributing source-scan pixels according to `VISUAL_TEXT_FIDELITY_CHECK.md`;
3. **assembly-reviewed** — direct scan fidelity has passed and the scene has also been checked against all contributing page records, including every cross-page/column join;
4. **ready-for-global-review** — title, setting, stage directions, visual-layer separation, provenance and review notes all confirmed.

Do not mark a scene assembly reviewed/final merely because its page sources are verified; assembly introduces a new risk at mechanical joins, and the assembled derivative must therefore be checked directly against the scan again.

## Pilot decision

The first assembly activity will be **காட்சி-1 / scan 17**, and the same activity must include its **visual text fidelity check**.

Reasons:

- it is a complete one-scan scene;
- its page record is verified;
- it exercises scene heading, decorative title, stage direction, speaker/dialogue structure and title artwork without a cross-page join;
- it can establish the exact reusable scene-file format and the visual-fidelity review method before multi-scan scenes are assembled.

Pilot sequence:

1. assemble `scenes/01.md` from verified `pages/0017.md` at `draft`;
2. inspect the actual scan 17 at native/enlarged resolution;
3. perform character-level scan-to-scene fidelity comparison under `VISUAL_TEXT_FIDELITY_CHECK.md`;
4. compare again against `pages/0017.md` to ensure no assembly-only omission/duplication/normalization;
5. set `visual_text_fidelity: "passed"` and `status: "assembly-reviewed"` only if both checks pass;
6. document any correction if direct source pixels prove an existing page record wrong;
7. accept the reusable scene-file format before proceeding to scene 2.

After the pilot passes, continue in numerical scene order unless a later assembly issue requires a targeted recheck.

## Translation boundary

English translation remains locked throughout this assembly phase. After all scene files are assembled, visually fidelity-checked and assembly-reviewed, perform a global Tamil consistency/source audit before deciding whether the work is ready for translation.
