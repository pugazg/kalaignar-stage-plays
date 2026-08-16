# சிலப்பதிகாரம் நாடகக் காப்பியம் — Continuation Guidelines

This file is a work-specific supplement to `STAGE_PLAY_PROCESSING_GUIDE.md`.

If there is any conflict, the controlling Tamil source scan and the repository-level processing guide take precedence.

## 1. Source hierarchy

Use this order of authority:

1. **Controlling Tamil scan**
2. Verified archival page record derived from that scan
3. Other pages in the same printed edition for glyph/font comparison
4. User-provided reading, only after checking it against source pixels
5. Published English translation or another edition, only as explicitly labelled secondary corroboration
6. OCR/parsed text as assistive evidence only

Never let a secondary witness overwrite a source-supported Tamil reading silently.

## 2. No silent normalization

Preserve the printed edition as an archive, not as a corrected edition.

Do not silently change:

- spelling;
- historical/authorial forms;
- sandhi or word spacing;
- punctuation or ellipsis counts;
- abbreviations;
- speaker labels;
- stage-direction brackets;
- repeated words/phrases;
- names;
- numbers;
- grammar that looks unusual;
- visible typographical anomalies;
- page numbers that look wrong or out of sequence.

If the source visibly prints something unexpected, retain it and document it.

## 3. Work by complete scene

The normal working unit is **one complete scene per activity**, not one arbitrary page.

Procedure:

1. Identify the `காட்சி-` opening.
2. Inspect forward until the next numbered `காட்சி-` heading.
3. Establish the scene's full physical scan extent.
4. Process all scans belonging to that scene together when practical.
5. Keep one page record per physical scan even when processing the whole scene as one activity.

Do not stop after one page merely because the page is dense. Do not merge scenes because they are short.

## 4. Page records and status

Each physical scan must have its own `pages/NNNN.md` record.

Use only these status values:

- `not-started`
- `partial`
- `needs-review`
- `verified`
- `blocked`

A structural survey can create a `needs-review` record with scene number, provisional title, setting, visible pagination, images and boundary information.

`verified` requires direct visual checking of the complete page text and source layers.

## 5. Decorative headings

Kalaignar's stage-play edition often uses stylized decorative scene titles.

Rules:

- Read the title from the image, not from context.
- Enlarge the heading when necessary.
- Distinguish decorative artwork from lexical text.
- Do not convert a pictorial element into an inferred word unless the source actually prints that word.
- If a heading is not secure, leave it provisional/`needs-review`.

## 6. Two-column pages

Most dramatic pages use two-column composition.

For each page:

- establish left/right reading order visually;
- track utterances and stage directions crossing the column boundary;
- preserve the physical break in the archival page record when a word/utterance is split across columns;
- do not trust OCR column ordering;
- do not silently join a broken word in a way that hides the physical source boundary.

Later scene assembly may join mechanical breaks, but provenance must remain recoverable.

## 7. Page boundaries and pagination

Printed pagination is recorded **only when visibly present**.

Never infer a number from neighbouring pages.

Known example: scan 73 visibly prints only `8`; that anomaly is intentionally preserved rather than converted into an expected sequence number.

If no page number is securely visible, use `printed_page: null` and state that none was inferred.

## 8. Stage directions and speaker labels

Preserve speaker labels exactly, including abbreviated forms.

Do not expand `கோவ`, `கண்`, `பொற்`, `அதி`, etc. unless the source itself prints the full form on that occurrence.

Preserve:

- brackets and unmatched brackets;
- parentheses;
- entrances/exits;
- prose action;
- physical action embedded between lines;
- punctuation attached to speaker labels or dialogue.

If a stage direction physically crosses a column/page boundary, record that boundary.

## 9. Difficult-reading escalation

Before leaving a literary reading unresolved:

1. inspect the native scan;
2. render an enlarged full page;
3. create targeted crops;
4. compare nearest-neighbour and high-quality resampling;
5. try grayscale/contrast/gamma/sharpening/threshold variants without altering the source file;
6. compare recurring glyphs/fonts on neighbouring pages;
7. inspect previous/next-page continuation;
8. compare a user-provided reading against pixels;
9. use another edition/translation only as labelled corroboration if still useful.

Do not guess from sentence meaning.

## 10. Illustrations, photographs and captions

Treat visual material as a separate source layer.

- If a printed caption exists, transcribe it verbatim.
- If there is no caption, describe the image concisely and neutrally.
- Do not identify a person/statue/object beyond what the source supports.
- Do not turn image description into dramatic text.

## 11. Library/accession marks

Separate later marks from publication text:

- library stamps;
- accession numbers;
- handwriting;
- pencil/ink annotations;
- stains/damage;
- bleed-through.

Do not incorporate these into Kalaignar's text.

## 12. Repository write discipline

Work directly in `pugazg/kalaignar-stage-plays` on `main` unless the user explicitly changes that instruction.

After each completed scene, update at minimum:

1. the relevant `pages/NNNN.md` files;
2. `works/silappathikaram-nataka-kappiyam/indexes/page-map.md`;
3. `works/silappathikaram-nataka-kappiyam/README.md`;
4. root `HANDOVER.md`.

When useful, update `docs/SILAPPATHIKARAM_PROJECT_HANDOVER.md` if the continuation checkpoint materially changes.

Do not commit the source PDF.

## 13. Completed material is protected

Scans already marked `verified` should not be reopened casually.

A verified reading may be changed only when:

- a direct source-pixel reinspection shows the prior transcription was wrong; or
- the user provides a correction that is then verified against the scan.

Document such corrections clearly.

Do not restart earlier scenes to reproduce work that is already complete.

## 14. Translation is a later phase

Do not begin English translation while Tamil page-level verification is still incomplete unless the user explicitly changes the project phase.

When translation eventually begins:

- translate from the **verified Tamil archival text**;
- use the published English volume only as a secondary comparison witness;
- preserve Kalaignar's rhetorical force, cadence, wit, repetition, dramatic timing and political/literary language;
- do not retroactively change Tamil to fit an English edition.

### Permanent terminology lock

`அந்தணர்` is **not automatically equivalent to “Brahmin.”**

Preserve distinctions among:

- `பிராமண`
- `பார்ப்பன`
- `அந்தணர்`
- `மறையவன்`
- other context-specific source terms

Decide English renderings only during dedicated terminology review.

## 15. Current project checkpoint

At the time this guideline package was created:

- scans **1–75** are verified;
- **காட்சி-1 through காட்சி-29** are complete;
- `காட்சி-30` is structurally mapped on scan **76**;
- scan 76 visibly prints page **60**;
- provisional title: `சிலம்போ சிலம்பு`;
- setting: `பொற்கொல்லர் நிலையம்`;
- scan 77 begins `காட்சி-31`.

Always re-read the live `page-map.md` and root `HANDOVER.md` because this checkpoint will advance over time.
