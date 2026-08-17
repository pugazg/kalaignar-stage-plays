# சிலப்பதிகாரம் நாடகக் காப்பியம் — Continuation Guidelines

This file is a work-specific supplement to `STAGE_PLAY_PROCESSING_GUIDE.md`.

If there is any conflict, the controlling Tamil source scan and repository-level processing guide take precedence.

## 1. Source hierarchy

Use this order of authority:

1. **Controlling Tamil scan**
2. Verified archival page record derived from that scan
3. Other pages in the same printed edition for glyph/font comparison
4. User-provided reading, after checking it against source pixels
5. Published English translation or another edition, only as explicitly labelled secondary corroboration
6. OCR/parsed text as assistive evidence only

Never let a secondary witness silently overwrite a source-supported Tamil reading.

## 2. No silent normalization

Preserve the printed edition as an archive, not a corrected edition. Do not silently change spelling, historical/authorial forms, word spacing, punctuation, ellipsis counts, abbreviations, speaker labels, stage-direction brackets, repetitions, names, numbers, unusual grammar or visible typographical anomalies.

If the source visibly prints something unexpected, retain it and document it.

## 3. Work by complete scene / controlled translation unit

For Tamil archival work, the normal unit is one complete scene, not an arbitrary page. Establish the full physical scan extent and keep one page record per scan.

For English translation, use the accepted controlled batch/review discipline in `TRANSLATION_GUIDE.md` and `translations/en/TRANSLATION_REVIEW.md`. Every translated unit must pass its own review before promotion.

## 4. Page records and Tamil status

Each physical scan has `pages/NNNN.md`.

Allowed Tamil page statuses:

- `not-started`
- `partial`
- `needs-review`
- `verified`
- `blocked`

`verified` requires direct visual checking of the complete page text and source layers.

## 5. Decorative headings

Read stylized titles from pixels, not context. Distinguish decorative artwork from lexical text. If a heading is not secure, leave it unresolved rather than infer from another edition.

## 6. Two-column pages

Establish reading order visually. Track utterances/stage directions crossing columns and preserve physical breaks in page records. Scene assembly may join only mechanical breaks while keeping provenance recoverable.

## 7. Page boundaries and pagination

Record printed pagination only when visibly present. Never infer a page number from neighbouring pages. Known anomalies remain anomalies.

## 8. Stage directions and speaker labels

Preserve source labels, including abbreviations, brackets/unmatched brackets, entrances/exits, prose action and punctuation. Do not expand source abbreviations in the Tamil archive.

## 9. Difficult-reading escalation

Before leaving a literary reading unresolved:

1. inspect native scan;
2. render enlarged full page;
3. create targeted crops;
4. compare resampling/contrast variants without altering the source;
5. compare recurring glyphs on neighbouring pages;
6. inspect page/column continuation;
7. compare any user-provided reading against pixels;
8. use another edition only as labelled corroboration if still useful.

Do not guess from sentence meaning.

## 10. Illustrations, photographs and captions

Treat visual material as a separate source layer. Transcribe printed captions verbatim; describe uncaptioned material neutrally; never turn image description into dramatic text.

## 11. Library/accession marks and obstruction

Separate later stamps, accession numbers, handwriting, damage, stains and bleed-through from publication text.

The scan-88 closing-tableau library stamp is a permanent source-obstruction issue: obscured leading characters must remain unresolved unless the controlling scan itself supports recovery. Do not reconstruct them from another edition.

## 12. Repository write discipline

Work directly in `pugazg/kalaignar-stage-plays` on `main` unless the user explicitly changes that instruction.

For meaningful checkpoint changes update as applicable:

- work README;
- translation tracker and terminology register;
- root `HANDOVER.md`;
- `docs/SILAPPATHIKARAM_PROJECT_HANDOVER.md`;
- next-chat prompt.

Do not commit the source PDF.

## 13. Completed material is protected

Verified Tamil must not be reopened casually. A verified reading may change only when direct source pixels show the prior transcription was wrong, or a user correction is verified against the scan. Document every such correction.

### Translation-stage scan-87 precedent

During scene-37 translation, direct enlarged source pixels proved three prior readings wrong and the archive was corrected:

- `தீவர்களாம்` → `தலைவர்களாம்`;
- `அன்ன நற்சோணையே` → `அன்னை நற்சோணையே`;
- `சுடற்ற புலவனே` → `ஈடற்ற புலவனே`.

This is the model for a legitimate post-verification correction: source-pixel proof, documented page/scene update, no outside normalization.

## 14. English translation discipline

English translation is now an active/near-complete project phase.

Translate from the **verified Tamil archival text** and return to source pixels whenever a Tamil reading is questioned.

Preserve Kalaignar's rhetorical force, cadence, repetition, wit, satire, dramatic timing, imagery and political/literary language. Do not retroactively change Tamil to fit English.

A published English edition, if consulted, is a labelled secondary witness only.

### Permanent terminology lock

`அந்தணர்` is **not automatically equivalent to “Brahmin.”** Preserve distinctions among `பிராமண`, `பார்ப்பன`, `பார்ப்பார்`, `அந்தணர்`, `மறையவன் / மறையவர்` and related source terms.

Additional current controls include:

- `Tamilakam` versus contextual `Tamil land`;
- `சுயமரியாதை` → `self-respect` when the actual word occurs;
- `நாழிகை` → retained `naazhigai`;
- source-supported state, retaliatory and martial violence must not be softened into invented procedure or generic prose.

## 15. Current project checkpoint

Current live state:

- scans **1–88** verified;
- Tamil transcription audit: **PASS**;
- `காட்சி-1` through `காட்சி-38`: assembly-reviewed / visual fidelity passed;
- separate `scenes/closing-tableau.md`: assembly-reviewed / visual fidelity passed;
- global Tamil review: **PASS**;
- English `translations/en/01.md` through `38.md`: **translation-reviewed / PASS**;
- English progress: **38/38 numbered scenes**;
- no published English edition used for scenes 1–38.

### Exact next controlled activity

Translate the separate **unnumbered** `scenes/closing-tableau.md` — `கண்ணகி சிலை நாட்டு விழா`.

Before drafting, inspect scan 88 and the verified tableau/page record, preserve the stamp-obscured uncertainty, and do not invent the obscured leading characters. After tableau PASS, run a final whole-English consistency/release review over scenes 1–38 plus the closing tableau.

Always re-read the live `README.md`, `TRANSLATION_REVIEW.md` and handover documents because the checkpoint will continue to advance.