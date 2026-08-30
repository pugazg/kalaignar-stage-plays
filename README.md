# Kalaignar Stage Plays

A source-first archival repository for stage plays and dramatic works written by **கலைஞர் மு. கருணாநிதி**.

The repository preserves each supplied printed edition as an archival transcription project. The controlling authority for an edition is its scanned source, not later editions, web text, OCR output, memory, or modernized Tamil.

## Core principles

- Preserve source-supported spelling, punctuation, wording, names, numbers, repetition, grammar, speaker labels and stage directions.
- Do not silently modernize or correct the printed Tamil.
- Treat OCR only as an aid; direct comparison with the scan is required before a page is marked verified.
- Record covers, photographs, forewords, advertisements, blank pages, stamps, handwriting, damage and other physical-copy evidence instead of discarding them.
- Keep printed errata distinct from page-level transcription; do not silently apply it.
- **Do not commit source PDFs to this repository.** Record provenance, checksum and scan characteristics instead.

See [`STAGE_PLAY_PROCESSING_GUIDE.md`](STAGE_PLAY_PROCESSING_GUIDE.md) for the permanent workflow.

## Works

| Work | Current authority/source | Status |
|---|---|---|
| [சிலப்பதிகாரம் — நாடகக் காப்பியம்](works/silappathikaram-nataka-kappiyam/) | controlling Tamil scan `TVA_BOK_0016473_சிலப்பதிகாரம்_நாடகக்_காப்பியம்.pdf` | **Tamil archive COMPLETE / PASS; 38/38 scenes + closing tableau; independent English COMPLETE / READY; secondary-witness comparison COMPLETE / PASS** |
| [பரதாயணம்](works/bharathayanam/) | controlling Tamil composite scan `TVA_BOK_0065576_நான்மணி_மாலை.pdf`, scans 6–17 | **Tamil archive/assembly PASS / COMPLETE; independent English translation PASS / COMPLETE** |
| [Anarkali](works/anarkali/) | same controlling Tamil source, scans 18–26; verified 2009 English secondary witness also retained | **Tamil page verification COMPLETE — 9/9; Scenes 1–4 assembly/fidelity next** |
| [Socrates](works/socrates/) | same controlling Tamil source, scans 27–43; verified 2009 English secondary witness also retained | **Tamil source registered; page verification pending** |
| [Cheran Senguttuvan](works/cheran-senguttuvan/) | same controlling Tamil source, scans 44–53; verified 2009 English secondary witness also retained | **Tamil source registered; page verification pending** |

## New controlling Tamil composite source — நான்மணி மாலை

The supplied **54-scan** volume `TVA_BOK_0065576_நான்மணி_மாலை.pdf` is registered under [`sources/naanmani-malai-tamil/`](sources/naanmani-malai-tamil/).

It contains four short plays named in the publisher's note: `பரதாயணம்`, `அனார்கலி`, `சாக்ரடீஸ்`, and `சேரன் செங்குட்டுவன்`.

The user supplied a Gemini first-pass transcription for the volume. It is navigation assistance only. Direct visual comparison with the source scan controls every archival reading, including old-style Tamil glyphs.

`பரதாயணம்` is complete through Tamil archival verification/assembly and independent English translation review.

`அனார்கலி` now has **9/9 Tamil scans visually verified** at [`works/anarkali/pages/`](works/anarkali/pages/), covering all four source-printed scenes. Material source-control findings and page boundaries are recorded in [`works/anarkali/FIRST_PASS_DISCREPANCIES.md`](works/anarkali/FIRST_PASS_DISCREPANCIES.md).

## Silappathikaram navigation

For movement between the verified Tamil scenes, independent English translations, individual reviews and secondary-witness comparison records, use:

- [`works/silappathikaram-nataka-kappiyam/NAVIGATION.md`](works/silappathikaram-nataka-kappiyam/NAVIGATION.md)

## Published-English secondary witness

The supplied 2009 volume *Tale of the Anklet and One Act Plays* remains separately archived as a secondary English witness.

- **163/163 physical scans accounted for and visually reviewed**;
- **109 passed** without correction;
- **54 corrected-and-passed**;
- **0 unresolved**;
- one-act plays are separated into dedicated witness folders for `Anarkali`, `Cheran Senguttuvan`, and `Socrates`.

It cannot override the controlling Tamil pages.

## Current repository phase

Current active work: **`அனார்கலி`**.

Its page-level Tamil verification is complete: **scans 18–26 = 9/9 verified**. Next assemble source-printed **காட்சி—1 through காட்சி—4** strictly from those page records and run the scene-assembly fidelity gate.

After the `அனார்கலி` Tamil assembly gate passes, continue sequentially with `சாக்ரடீஸ்` and `சேரன் செங்குட்டுவன்`.
