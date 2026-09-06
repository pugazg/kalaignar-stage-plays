# Historical Tamil Glyph Audit — ஒரே முத்தம்

Status: **OPEN — 0 / 131 SCANS PASSED**

Controlling source: `TVA_BOK_0064325_ஒரே_முத்தம்.pdf`.

This audit is mandatory for the complete source-page pass. Historical Tamil type must be decoded by character identity before transcription into modern Unicode. Visual resemblance to a modern glyph is not sufficient evidence.

## Mandatory families

Every processed scan must be checked for the complete known family set:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

A family may be absent on a page; the page-level audit still records that it was checked.

## Permanent rules

1. the source scan is controlling authority;
2. read character identity, not familiar modern visual appearance;
3. do not modernize source spelling, grammar, sandhi, punctuation, labels, names or numbers;
4. do not perform global replacement of historical shapes;
5. use same-edition comparison only after positive source-visible examples are established;
6. semantic expectation, dictionary spelling, proper-name familiarity and sentence meaning cannot override uncertain pixels;
7. if the scan remains insecure, retain an explicit unresolved marker / `needs-review` status rather than guessing;
8. donor/library/handwritten marks are not literary text;
9. scene headings and speaker labels receive the same glyph scrutiny as dialogue/body prose;
10. a page is not `verified` until both full visual fidelity and the historical-glyph gate pass.

Root authority: `../../STAGE_PLAY_PROCESSING_GUIDE.md`.

## Same-edition reference bank

**Not yet established.**

Positive source examples will be added only after direct visual verification during page processing. No family reading is preloaded from another work or edition.

## Progress

| Scan range | Visual/source processing | 13-family pass | Status / note |
|---|---|---|---|
| 1–5 | not started | not started | next batch |
| 6–131 | not started | not started | unopened |

Current metrics:

- physical scans: **131**;
- source-processed: **0 / 131**;
- full historical-glyph passes: **0 / 131**;
- visually verified: **0 / 131**;
- unresolved glyph clusters: **0 recorded yet** — this means not yet assessed, not that the source is clean.

## Exact next activity

Process scans **1–5** directly from source pixels and establish the first same-edition reference examples only where the characters are visually secure. Update this audit after each page; do not infer from modern spelling.
