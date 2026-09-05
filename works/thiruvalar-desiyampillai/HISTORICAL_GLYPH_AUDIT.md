# Historical Tamil Glyph Audit — திருவாளர் தேசீயம்பிள்ளை

Status: **INITIALIZED — 0 / 49 SCANS COMPLETE**

This work-level audit implements the user-supplied `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md` for the 1965 second-edition scan of **திருவாளர் தேசீயம்பிள்ளை**.

## Authority boundary

- controlling authority: source scan pixels;
- historical-glyph guide: methodology / candidate-family reference only;
- lexical first-pass witness: **none supplied**;
- OCR / language-model expectation / modern spelling: **not authority**.

The guide's core rule applies throughout:

> **Read character identity, not modern visual resemblance.**

A historical glyph correction decodes character identity into modern Unicode. It does **not** authorize modernization of the source word.

## Mandatory 13-family check

Every scan, including front matter and advertisements, must explicitly consider:

| Unicode identity | Audit family |
|---|---|
| `ணா` | `ணா` |
| `ணை` | `ணை` |
| `ணொ` | `ணொ` |
| `ணோ` | `ணோ` |
| `லை` | `லை` |
| `ளை` | `ளை` |
| `றா` | `றா` |
| `றொ` | `றொ` |
| `றோ` | `றோ` |
| `னா` | `னா` |
| `னை` | `னை` |
| `னொ` | `னொ` |
| `னோ` | `னோ` |

This is a minimum reference set, not a claim that these are the only possible historical/edition-specific ambiguities.

## Mandatory page procedure

For each scan:

1. inspect the whole page first to understand typeface, ink, damage and repeated glyph behaviour;
2. inspect difficult clusters at enlarged/native resolution;
3. check the full 13-family set even if the page seems easy;
4. read the complete glyph cluster, not only a final curl/loop/vowel mark;
5. compare same-edition / same-font occurrences when uncertain;
6. separate character identity from lexical expectation;
7. encode only the positively established historical identity in modern Unicode;
8. preserve source spelling, sandhi, grammar, vocabulary, punctuation and period-specific spacing otherwise;
9. if uncertainty remains, use `needs-review`; do not guess;
10. never perform a global replacement.

## Damage rule

This source has substantial physical loss. Historical-glyph decoding must not be used to reconstruct characters that are actually missing behind paper loss/abrasion. Record the damage separately and leave unsupported text unresolved.

## Audit-record format

When a historical-glyph correction is made, record:

- scan page;
- apparent/earlier reading if one existed;
- source-supported Unicode reading;
- historical family;
- evidence used (native/enlarged pixels and, when applicable, same-edition comparison);
- status.

Keep glyph corrections separate from ordinary lexical/transcription corrections.

## Current progress

- scans in work: **49**;
- full historical-glyph passes complete: **0 / 49**;
- scans with documented corrections: **0**;
- unresolved glyph clusters: **0 currently recorded**;
- pages permitted to be called verified solely from intake: **0**.

## Exact next activity

Run the full source-pixel + historical-glyph verification for **scans 1–5** while creating their canonical transcriptions. Update this file with representative same-edition evidence and any corrections/ambiguities found.
