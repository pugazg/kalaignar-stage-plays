# Next Chat Prompt — Continue Kalaignar Stage Plays

Continue the Kalaignar Stage Plays archival/translation project directly in:

`https://github.com/pugazg/kalaignar-stage-plays`

Branch: `main`.

Use the GitHub connector and work directly on `main`.

Controlling Tamil source PDF: `TVA_BOK_0065576_நான்மணி_மாலை.pdf`.

## Live-state rule

Fetch live GitHub `main` first and treat it as authoritative. Preserve any newer durable state. Do not reopen completed Tamil literary wording or reviewed English wording unless explicitly required by new source evidence or user direction.

## Mandatory startup reading

Before any write, read completely:

1. `STAGE_PLAY_PROCESSING_GUIDE.md`
2. `HANDOVER.md`
3. `NEXT_CHAT_PROMPT.md`
4. root `README.md`
5. `sources/naanmani-malai-tamil/COVERAGE_AUDIT.md`
6. English authority/status and review files for `பரதாயணம்`
7. `works/anarkali/translations/en/README.md`, `TRANSLATION_REVIEW.md`, `SECONDARY_WITNESS_COMPARISON.md`
8. `works/socrates/translations/en/README.md`, `TRANSLATION_REVIEW.md`, `SECONDARY_WITNESS_COMPARISON.md`
9. `works/cheran-senguttuvan/translations/en/README.md`, `TRANSLATION_REVIEW.md`, `SECONDARY_WITNESS_COMPARISON.md`
10. `sources/one-act-plays-2009/README.md` and live directory/witness organization needed to determine applicability across the four plays

Then re-fetch live `main` immediately before the first write.

## Durable Tamil state

The composite `கலைஞரின் நான்மணி மாலை` Tamil source is closed at **54/54 physical scans** with coverage audit **PASS / COMPLETE**.

- `பரதாயணம்` — Tamil assembly PASS;
- `அனார்கலி` — **9/9 pages verified; 4/4 scenes assembled; fidelity PASS**;
- `சாக்ரடீஸ்` — **17/17 pages verified; 5/5 scenes assembled; fidelity PASS**;
- `சேரன் செங்குட்டுவன்` — **10/10 pages verified; 4/4 scenes assembled; fidelity PASS**.

## English translation state

Independent English translation of the four `நான்மணி மாலை` plays is **4/4 COMPLETE**:

- `பரதாயணம்` — independent English **PASS / COMPLETE**;
- `அனார்கலி` — independent English **PASS / COMPLETE**, 2009 witness comparison **PASS / COMPLETE**;
- `சாக்ரடீஸ்` — independent English **PASS / COMPLETE**, 2009 witness comparison **PASS / COMPLETE**;
- `சேரன் செங்குட்டுவன்` — independent English **PASS / COMPLETE**, 2009 witness comparison **PASS / COMPLETE**.

### Cheran closed English checkpoint

- `works/cheran-senguttuvan/translations/en/01.md`–`04.md` — independent translation, translation-reviewed;
- `works/cheran-senguttuvan/translations/en/TRANSLATION_REVIEW.md` — **PASS**;
- `works/cheran-senguttuvan/translations/en/SECONDARY_WITNESS_COMPARISON.md` — **PASS / COMPLETE**.

The 2009 Cheran witness was consulted only after the independent translation had been locked. No published wording was automatically imported into the verified Tamil or independent English.

Important comparison findings include:

- Scene 1 `பாரதந்தான்` → `another Mahabharatham`, `மண்` → `sand`, label normalization;
- Scene 2 `சாதல் கதையொன்று` → `love story`;
- Scene 2 `வேழப்படை` → `Tiger flags`;
- Scene 3 `வாளேந்தி` → `holding lances`;
- materially rewritten Sattanar / Athani-hall wording;
- `இமயத்தை முட்டுங்கள்!` → `Invade the Himalayas!`;
- Scene 4 label normalization;
- `நாழிகை` → `nali` with a 24-minute gloss;
- `on your heads` added to the final stone command;
- source closing marks omitted in the witness transcription.

These remain witness differences, not revisions.

## Exact next activity

Run a **`நான்மணி மாலை` English-phase closure audit only**.

Tasks:

- confirm from live repository files that independent English is complete for all **4 / 4** plays;
- inspect `sources/one-act-plays-2009/` and establish exactly which of the four plays have a complete applicable 2009 published-English witness;
- do **not** assume whether `பரதாயணம்` is applicable; resolve it from live repository evidence;
- confirm every applicable secondary-witness comparison is **PASS / COMPLETE** and linked to its provenance range;
- keep `not applicable` distinct from `pending`;
- create `sources/naanmani-malai-tamil/ENGLISH_PHASE_CLOSURE_AUDIT.md` unless live `main` already contains an equivalent/superseding convention;
- update the relevant source/root/handover status files only after the audit result is established;
- do not change verified Tamil, independent translation wording, or completed comparison findings;
- do not begin another work or phase in the same activity.

The closure record should answer whether `கலைஞரின் நான்மணி மாலை` can now be marked **English phase PASS / COMPLETE**, with exact numerator/denominator counts for independent translations and for applicable secondary-witness comparisons.

When I say **“Proceed with next activity”**, execute this exact English-phase closure audit directly.