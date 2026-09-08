# Historical Tamil Glyph Gate

Status: **MANDATORY FOR HISTORICAL-TYPE SOURCES**

Authority: `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md`.

This gate formalizes a second source-pixel check **after initial visual verification and before a page may become finally `verified`**.

## Why this gate exists

A page can pass ordinary visual transcription checks for wording, punctuation, speaker labels, stage directions and layout while still carrying a historical Tamil typeform that resembles the wrong modern Unicode character. Therefore initial visual verification alone is not sufficient for older Tamil editions when historical typeforms are present or reasonably possible.

## Required order

For applicable pages the durable order is:

1. **Canonical transcription / first pass** from the controlling scan.
2. **Initial visual verification** against the whole source page.
3. **H-GATE — Historical Tamil glyph audit** at enlarged/native source resolution.
4. **Final page verification** only if both the initial verification and H-GATE pass and no other unresolved source issue remains.

Initial verification is therefore not synonymous with final `verified` status.

## Status rule

After initial visual verification, while H-GATE is still pending:

```yaml
status: "needs-review"
initial_verification: "passed"
historical_glyph_gate: "pending"
```

After H-GATE passes and no other issue remains:

```yaml
status: "verified"
initial_verification: "passed"
historical_glyph_gate: "passed"
```

If the glyph gate finds an unresolved cluster:

```yaml
status: "needs-review"
initial_verification: "passed"
historical_glyph_gate: "needs-review"
```

If the source pixels are physically insufficient even after the normal difficult-reading escalation, use `blocked` and document the exact locus.

## Mandatory H-GATE family set

Every applicable page must explicitly check the complete minimum known family set, even if no positive occurrence is found:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`

The set is a minimum, not an exhaustive claim about all historical Tamil typography.

## H-GATE method

1. inspect the complete page at enlarged/native resolution;
2. identify candidate historical-type clusters by character identity, not modern visual resemblance;
3. inspect the complete cluster rather than only the final curl/vowel mark;
4. compare clearer same-font / same-edition witnesses when necessary;
5. encode only positively supported character identity in modern Unicode;
6. preserve source spelling, grammar, vocabulary, punctuation and spacing unless the source itself proves a separate correction;
7. do not use OCR, dictionary expectation, grammar, plot context or familiar spelling as proof;
8. never global-replace a historical family across the work;
9. record any correction with scan number, apparent reading, source-supported reading, family and evidence;
10. if character identity remains uncertain, do not guess.

## Page-note requirement

Each applicable page should include a short gate record, for example:

```markdown
## Historical-glyph gate

- initial visual verification: PASS;
- full family set checked: `ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`;
- enlarged/native source inspection: complete;
- same-edition comparison: `<not required | details>`;
- historical-glyph corrections: `<none | list>`;
- unresolved glyph loci: `<none | list>`;
- result: `<PASS | NEEDS-REVIEW | BLOCKED>`.
```

## Work-level audit requirement

Historical-type works must maintain a work-level `HISTORICAL_GLYPH_AUDIT.md` that tracks:

- pages initially verified;
- pages H-GATE checked;
- pages finally verified;
- corrections by historical family;
- same-edition reference witnesses;
- unresolved / blocked loci;
- retrospective reopening if a systematic glyph error is later discovered.

## Downstream gate

For a work using this policy:

- scene/SRU assembly may use only text whose page-level source state is explicitly known;
- a work cannot be called Tamil archival `PASS` merely because initial verification reached 100%;
- the historical-glyph work-level gate must be complete before Tamil closure, release or English translation;
- later discovery of a systematic historical-glyph error reopens affected `verified` pages to `needs-review` until re-audited.

## Short rule

> **Initial verification → historical-glyph gate → final verification.**

For historical Tamil print, `verified` means both visual fidelity and H-GATE closure.
