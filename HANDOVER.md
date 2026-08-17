# Kalaignar Stage Plays — Handover

## Repository

`pugazg/kalaignar-stage-plays` on `main`.

Completed controlling-Tamil work: `works/silappathikaram-nataka-kappiyam/`

Registered one-act-play work entities:

- `works/anarkali/`
- `works/cheran-senguttuvan/`
- `works/socrates/`

Controlling Tamil source for Silappathikaram: `TVA_BOK_0016473_சிலப்பதிகாரம்_நாடகக்_காப்பியம்.pdf` — supplied externally and **not committed**.

## Mandatory startup for any future Silappathikaram phase

Read completely:

1. `STAGE_PLAY_PROCESSING_GUIDE.md`
2. `docs/SILAPPATHIKARAM_CONTINUATION_GUIDELINES.md`
3. `docs/SILAPPATHIKARAM_PROJECT_HANDOVER.md`
4. `docs/NEXT_CHAT_PROMPT_SILAPPATHIKARAM.md`
5. this handover
6. work `README.md`
7. `GLOBAL_TAMIL_REVIEW.md`
8. `TRANSLATION_GUIDE.md`
9. `TRANSLATION_TERMINOLOGY.md`
10. `translations/en/README.md`
11. `translations/en/TRANSLATION_REVIEW.md`
12. `translations/en/FINAL_ENGLISH_CONSISTENCY_REVIEW.md`
13. `translations/en/RELEASE_REPORT.md`
14. `translations/en/PUBLISHED_WITNESS_COMPARISON.md` when doing secondary-witness analysis

## Completed Silappathikaram Tamil state

- **88/88 scans** visually verified at page-record level.
- Tamil transcription completion audit: **PASS**.
- **38/38 numbered scenes** assembled / visual fidelity passed.
- Separate closing tableau assembled / fidelity passed.
- Global Tamil consistency/source review: **PASS**.

### Scan-87 corrections discovered during translation

Direct source-pixel reinspection corrected three earlier Tamil readings in `pages/0087.md` and `scenes/37.md`:

- `தீவர்களாம்` → `தலைவர்களாம்`;
- `அன்ன நற்சோணையே` → `அன்னை நற்சோணையே`;
- `சுடற்ற புலவனே` → `ஈடற்ற புலவனே`.

These are source corrections, not normalization. Do not revert them.

## Completed Silappathikaram English state

- Scenes **1–38**: `translation-reviewed` / **PASS**.
- Separate unnumbered `கண்ணகி சிலை நாட்டு விழா` closing tableau: `translation-reviewed` / **PASS**.
- Final English consistency review: **PASS**.
- English release report: **READY**.
- English progress: **38/38 numbered scenes + closing tableau COMPLETE**.
- No published English edition was used in drafting or reviewing the independent translation.

## Published-English secondary witness

The supplied 2009 *Tale of the Anklet and One Act Plays* witness is separately archived under `sources/`.

Final witness status:

- **163/163 physical scans accounted for**;
- **163/163 visually reviewed**;
- **109 passed**;
- **54 corrected-and-passed**;
- **0 unresolved**;
- release status: **ARCHIVAL WITNESS READY**.

The one-act plays are separated into dedicated witness folders and registered under `works/` for future controlling-Tamil ingestion.

A secondary-witness comparison framework now exists at `works/silappathikaram-nataka-kappiyam/translations/en/PUBLISHED_WITNESS_COMPARISON.md`. It is analytical only and cannot override Tamil authority or the reviewed independent translation without a fresh Tamil-based review.

## Closing-tableau source obstruction

The scan-88 later library/accession stamp obscures the leading characters of two publication lines. The Tamil archive and English translation preserve those portions as unresolved. Do **not** reconstruct them from another edition, memory, or the published English translation.

The tableau is **not Scene 39**.

## Permanent language / terminology controls

Retain Kalaignar's rhetorical force, cadence, repetition, humour, emotional escalation, dramatic timing and political/literary register.

`அந்தணர்` is **not automatically “Brahmin.”** Preserve the distinctions among `பிராமண`, `பார்ப்பன`, `பார்ப்பார்`, `அந்தணர்`, `மறையவன் / மறையவர்`, and related terms.

Keep Dravidian-movement interpretation separate from dialogue unless the source states the concept. Scene 37 explicitly contains `சுயமரியாதை`, translated as `self-respect`.

## Current project state

The repository's existing supplied sources have completed their intended archival/transcription/review phases.

Remaining meaningful work is source-dependent or analytical:

- detailed secondary-witness comparison of the independent Silappathikaram translation against the verified 2009 published witness;
- ingest controlling Tamil editions for `Anarkali`, `Cheran Senguttuvan`, and `Socrates` when supplied;
- metadata/navigation and reader-facing repository organization that does not create downloadable EPUB/web editions.

No future phase may silently overwrite verified Tamil readings or reviewed English translation decisions.
