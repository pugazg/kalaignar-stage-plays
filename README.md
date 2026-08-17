# Kalaignar Stage Plays

A source-first archival repository for stage plays and dramatic works written by **கலைஞர் மு. கருணாநிதி**.

The repository preserves each supplied printed edition as an archival transcription project. The controlling authority for an edition is its scanned source, not later editions, web text, OCR output, memory, or modernized Tamil.

## Core principles

- Preserve source-supported spelling, punctuation, wording, names, numbers, repetition, grammar, speaker labels and stage directions.
- Do not silently modernize or correct the printed Tamil.
- Treat OCR only as an aid; direct comparison with the scan is required before a page is marked verified.
- Record covers, photographs, forewords, advertisements, blank pages, stamps, handwriting, damage and other physical-copy evidence instead of discarding them.
- Keep printed errata distinct from page-level transcription; do not silently apply it.
- **Do not commit source PDFs to this repository.** Record provenance, checksum and scan characteristics in each work's metadata instead.

See [`STAGE_PLAY_PROCESSING_GUIDE.md`](STAGE_PLAY_PROCESSING_GUIDE.md) for the permanent workflow.

## Works

| Work | Current authority/source | Status |
|---|---|---|
| [சிலப்பதிகாரம் — நாடகக் காப்பியம்](works/silappathikaram-nataka-kappiyam/) | controlling Tamil scan `TVA_BOK_0016473_சிலப்பதிகாரம்_நாடகக்_காப்பியம்.pdf` | **Tamil archive COMPLETE / PASS; 38/38 scenes + closing tableau; independent English translation COMPLETE / READY** |
| [Anarkali](works/anarkali/) | 2009 published-English secondary witness available; Tamil controlling source not yet supplied | **work registered; English witness verified** |
| [Cheran Senguttuvan](works/cheran-senguttuvan/) | 2009 published-English secondary witness available; Tamil controlling source not yet supplied | **work registered; English witness verified** |
| [Socrates](works/socrates/) | 2009 published-English secondary witness available; Tamil controlling source not yet supplied | **work registered; English witness verified** |

## Published-English secondary witness

The supplied 2009 volume *Tale of the Anklet and One Act Plays* has been separately archived as a secondary English witness.

- **163/163 physical scans accounted for and visually reviewed**;
- **109 passed** without correction;
- **54 corrected-and-passed**;
- **0 unresolved**;
- one-act plays are separated into dedicated witness folders for `Anarkali`, `Cheran Senguttuvan`, and `Socrates`;
- this witness was **not used** to draft or review the independent English translation of `சிலப்பதிகாரம் — நாடகக் காப்பியம்`.

See [`sources/one-act-plays-2009/RELEASE_REPORT.md`](sources/one-act-plays-2009/RELEASE_REPORT.md) and [`sources/one-act-plays-2009/VISUAL_FIDELITY_REVIEW.md`](sources/one-act-plays-2009/VISUAL_FIDELITY_REVIEW.md).

## Standard work layout

```text
works/<work>/
  README.md
  metadata/
    source.md
  indexes/
    page-map.md
  pages/
    0001.md
    ...
  scenes/
    ...
  audit.md
  translations/en/         # optional later phase
  HANDOVER.md
```

Page records preserve the physical edition page by page. Scene files, when created, are assembled only from verified page records and must retain explicit provenance back to scan pages.

## Current repository phase

The first controlling Tamil work, `சிலப்பதிகாரம் — நாடகக் காப்பியம்`, has completed archival verification, scene assembly, global Tamil review, independent English translation, individual translation review and final English consistency review.

The 2009 published-English witness has completed transcription and full visual-fidelity review. Further work on that witness should be explicitly labelled secondary-witness analysis rather than canonical source editing.
