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

| Work | Source | Status |
|---|---|---|
| [சிலப்பதிகாரம் — நாடகக் காப்பியம்](works/silappathikaram-nataka-kappiyam/) | `TVA_BOK_0016473_சிலப்பதிகாரம்_நாடகக்_காப்பியம்.pdf` | Source audit started |

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
  audit.md                 # added during verification
  translations/en/         # optional later phase
  HANDOVER.md              # added/updated as processing advances
```

Page records preserve the physical edition page by page. Scene files, when created, are assembled only from verified page records and must retain explicit provenance back to scan pages.
