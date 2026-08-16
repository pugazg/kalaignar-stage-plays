# Project Guidelines — சிலப்பதிகாரம் நாடகக் காப்பியம்

This file supplements the repository-wide `STAGE_PLAY_PROCESSING_GUIDE.md` with decisions specific to the current Silappathikaram stage-play archival project.

## 1. Authority hierarchy

Use this order of authority:

1. **The attached Tamil scan of this edition** — controlling source.
2. Direct enlarged visual inspection of that scan.
3. Neighbouring pages/glyphs in the same edition for character-shape comparison.
4. User-supplied reading, only after checking it against the scan pixels.
5. Published English translation or other editions, only as explicitly labelled secondary witnesses.

OCR, internet texts, memory and other editions are never allowed to override a legible controlling scan.

## 2. Archival transcription, not correction

The goal is to preserve what this edition prints, not to create a corrected or modernized Silappathikaram text.

Therefore preserve:

- historical/authorial spelling;
- unexpected grammar;
- repeated words;
- unusual punctuation;
- source spacing;
- speaker-label abbreviations and variations;
- apparent typographical errors when visibly printed;
- physical word splits at important page/column boundaries when the page record is documenting source layout;
- anomalous printed page numbers exactly as seen.

Never silently repair a phrase because another wording seems more grammatical or familiar.

## 3. Page records and scene units

Every physical scan has its own file in `pages/`.

Detailed work should proceed by **complete scene** where practical:

- identify the `காட்சி-` opening;
- inspect forward until the next `காட்சி-` heading;
- treat that entire span as one working activity;
- verify every constituent physical page independently;
- update the page map only after the physical extent is confirmed.

Do not fall back to one-page-per-activity merely because a scene spans multiple pages.

## 4. Two-column reading order

Most dramatic pages are two-column.

- Determine order by direct visual reading, not OCR order.
- Preserve dialogue/stage-direction continuation across columns.
- Explicitly note cross-column breaks where they matter.
- If a sentence begins on one page/column and continues on the next, do not silently merge it inside the page record.

## 5. Scene titles and decorative typography

Decorative headings must be read from the image itself.

- Do not infer a title from plot context.
- If artwork is embedded in the heading, distinguish actual lexical text from decorative imagery.
- If uncertain, keep the title provisional and page status `needs-review`.

## 6. Images, photographs and captions

- Do not identify uncaptioned people, sculptures, sites or objects by inference.
- Describe an uncaptioned image neutrally and briefly.
- If a printed caption exists, transcribe it exactly, including punctuation and physical line/word breaks when relevant.
- Separate printed image captions from dramatic text.
- Separate library/accession stamps, handwriting and later annotations from publication text.

## 7. Pagination

Record printed pagination only when directly visible.

- Never infer missing numbers from neighbouring pages.
- Preserve anomalous numerals exactly.
- If no page number is securely visible, use `null`/state that none is visible.

## 8. Status discipline

Use `verified` only after direct source comparison of:

- scene marker/title;
- setting/sub-setting;
- every dialogue line;
- speaker labels;
- stage directions;
- punctuation;
- significant physical breaks;
- visible printed page number;
- image/caption layer;
- library marks and anomalies;
- following scene boundary.

If any material literary reading remains uncertain, keep the page at `needs-review` or `blocked`.

## 9. Difficult-reading escalation

Before leaving a difficult reading unresolved:

- inspect the native-resolution page;
- render 4x/6x or high-ppi crops;
- compare nearest-neighbour and smoother resampling;
- try grayscale/contrast/gamma/sharpening non-destructively;
- isolate column or word crops;
- compare repeated glyphs in the same page/nearby pages;
- inspect sentence continuation on previous/next scans.

Context can help choose where to look, but **context cannot authorize a character not supported by pixels**.

## 10. Previously verified material

At the current handover, scans **1–75** are verified.

Do not restart or retranscribe them in a new chat. If a possible error is noticed later:

1. reopen the controlling scan;
2. verify the suspected discrepancy visually;
3. document the correction and why it is source-supported;
4. update downstream status/handover files consistently.

## 11. Translation separation

Tamil transcription and English translation are separate phases.

The published English translation supplied by the user:

- may be used later for comparison/collation;
- must not be used to settle Tamil letters or words;
- must not retroactively change verified Tamil.

### Terminology lock

The user explicitly instructed:

- `அந்தணர்` is **not** to be automatically rendered as “Brahmin” in Kalaignar's language.
- Preserve distinctions among `பிராமண`, `பார்ப்பன`, `அந்தணர்`, `மறையவன்` and similar source terms.
- Build a dedicated terminology table before final English translation.

### Voice lock for future translation

When translation eventually starts, preserve Kalaignar's language as far as English allows:

- rhetorical force;
- repetitions;
- dramatic cadence;
- irony and wordplay;
- political/social register;
- literary allusions;
- shifts between formal, colloquial and emotional speech.

Do not turn the translation into neutral summary prose.

## 12. GitHub working discipline

Work directly on `main` unless the user instructs otherwise.

- Fetch a file before updating it so the current SHA is used.
- Avoid duplicate page records.
- Do not commit source PDFs.
- After every completed scene, synchronize:
  - page record(s),
  - `indexes/page-map.md`,
  - work `README.md`,
  - root `HANDOVER.md`,
  - `PROJECT_HANDOVER.md` when the major checkpoint changes.

## 13. Current next unit

At creation of this guideline, the next unit is:

- `காட்சி-30`
- scan `76`
- provisional title `சிலம்போ சிலம்பு`
- setting `பொற்கொல்லர் நிலையம்`
- printed page `60`
- status `needs-review`
- scan 77 begins `காட்சி-31`

Verify the entire one-scan scene before proceeding.
