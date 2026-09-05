# Historical Tamil Glyph Audit — திருவாளர் தேசீயம்பிள்ளை

Status: **IN PROGRESS — 45 / 49 SCANS COMPLETE**

This work-level audit implements the user-supplied `HISTORICAL_TAMIL_GLYPH_TRANSCRIPTION_GUIDE.md` for the 1965 second-edition scan of **திருவாளர் தேசீயம்பிள்ளை**.

## Authority boundary

- controlling authority: source scan pixels;
- historical-glyph guide: methodology / candidate-family reference only;
- lexical first-pass witness: **none supplied**;
- OCR / language-model expectation / modern spelling: **not authority**.

Core rule:

> **Read character identity, not modern visual resemblance.**

A historical-glyph correction decodes character identity into modern Unicode. It does **not** authorize modernization of the source word.

## Mandatory 13-family check

Every scan explicitly considers:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`.

## Established same-edition reference set

Positive same-edition evidence currently supports:

`லை / ளை / ணா / ணை / னா / னை / றா`.

Representative anchors include:

- `லை`: `கலைஞர்`, `தலைகள்`, `மாலைதானே`, `விலைமதிக்க`, `மாலையை`, scan-37 `மாலையை`, scan-39/40 `உடுமலைப் / காலை`, scan-44 `ஆலை முதலாளி`;
- `ளை`: `பிள்ளை`, `உங்களை`, `விளையும்`, scan-38 `கால்களைப்`, scan-40 `கண்களைத்`;
- `ணா`: `கருணாநிதி`, `கல்யாண`, `ஆகாஷவாணி`, physical `சொல் / வொணா`, scan-42 `அரையணா`;
- `ணை`: scan-25 `சொரணை`;
- `னா`: `கெட்டிக்காரர்தானா`, `உடையவர்தானா`, `மானால்`, `தானா`, `மகனா`, `உடைதானா`, `அரசனா / ஆண்டவனா`, scan-41 `அருந்தினார் / கூறினாள்`;
- `னை`: `அவனை`, `தண்டனை`, scan-45 `என்னை`;
- `றா`: `வண்ணமிருக்கிறார்களே`, `பார்க்கிறார்`, `நன்றாக`, `என்றாரே`, scan-41 `மாறியிருக்கிறது`, scan-42 `பொறாமை`, scan-45 `மாறிப்போச்சு`.

These references are used only for character-identity comparison. They never authorize reconstruction of physically absent text, lexical normalization, or global replacement.

## Authoritative backward glyph corrections

The following source-pixel rechecks remain canonical:

- scan 15 `என்றுரே` → **`என்றாரே`** (`றா`);
- scan 15 `தானு` → **`தானா`** (`னா`);
- scan 20 `நன்றுக` → **`நன்றாக`** (`றா`);
- scan 21 `மகனு` → **`மகனா`** (`னா`);
- scan 28 `மால்தானே` → **`மாலைதானே`** (`லை`).

## Completed batches

- **Batch 1 — scans 1–5:** full passes complete; scan 2 verified; 1, 3, 4, 5 damage-limited.
- **Batch 2 — scans 6–10:** full passes complete; 6 and 10 verified; 7–9 damage-limited; `னை` established.
- **Batch 3 — scans 11–15:** all verified; `றா` established; later backward glyph correction on scan 15.
- **Batch 4 — scans 16–20:** all verified; scan 20 `நன்றாக` adjudication.
- **Batch 5 — scans 21–25:** all verified; `ணை` established from `சொரணை`.
- **Batch 6 — scans 26–30:** all verified; `னா` established; scan 28 `மாலைதானே` correction.
- **Batch 7 — scans 31–35:** 31–34 verified; scan 35 has one unresolved visual/glyph cluster.
- **Batch 8 — scans 36–40:** scan 36 has two unresolved clusters; scans 37–40 verified.

## Batch 9 — scans 41–45

Full source-pixel + 13-family passes completed for all five scans. **All five are verified.**

| Scan | Representative evidence | Result |
|---:|---|---|
| 41 | `மாறியிருக்கிறது`, `அருந்தினார்`, `கூறினாள்`, `பிள்ளையார்` | **verified** — `றா / னா / ளை` identities agree with established same-edition anchors; election-result shock/domestic dialogue fully supported |
| 42 | first-line old-type `பொறாமை`, `அரையணா`, repeated `விலை` | **verified** — `பொறாமை` decoded by historical `றா`; `ணா / லை` supported; source `தீட்டி` retained; later ink near `ஆள—` does not remove supported text |
| 43 | colloquial election dialogue; `கல்யாணங் காட்சிக்கு`; repeated verbal endings | **verified** — established families checked; no new correction; source colloquialisms preserved |
| 44 | `தமிழ் வாழ்க`, `ஆலை முதலாளி`, repeated argument forms | **verified** — old-type `லை` in `ஆலை` decoded from same-edition evidence; later pale ink does not remove literary text |
| 45 | `மாறிப்போச்சு`, `என்னை`, `உதயசூரியனுக்குத்தானே` | **verified** — established `றா / னை / னா` candidates checked; election/slogan dialogue fully supported |

### New Batch-9 character-identity adjudications

Two page-level readings are worth carrying forward explicitly:

- scan 42 first-line apparent old-type `பொறுமை`-like shape is canonically **`பொறாமை`**, supported by the established `றா` identity and the complete glyph cluster;
- scan 44 page-ending old-type form is canonically **`ஆலை முதலாளி`**, supported by the established `லை` identity.

These are historical character-identity decodings, not semantic modernization.

### Earlier review holds remain open

Scans 41–45 provide no genuine same-edition evidence strong enough to resolve the existing three clusters:

- scan 35: one cluster in `கொம்பு மாடெனக் … மட்டும்`;
- scan 36: two short descriptive clusters in the `ஹரிஜன நலம்` / `சவலைப் பிள்ளை` passage.

The apparent scan-35 `கொழுப்பேறி` reading remains non-canonical.

## Review / damage boundary through scan 45

`needs-review` pages remain:

- physical-damage holds: **1, 3, 4, 5, 7, 8, 9**;
- unresolved visual/glyph-cluster holds: **35, 36**.

Current unresolved visual/source clusters: **3** total — scan 35: 1; scan 36: 2.

## Mandatory page procedure

For each remaining scan:

1. inspect the whole page first for typeface, ink, damage and repeated glyph behaviour;
2. inspect difficult clusters at enlarged/native resolution;
3. check the full 13-family set;
4. compare same-edition occurrences only for character identity;
5. separate glyph identity from lexical expectation;
6. encode only positively established historical identity in modern Unicode;
7. preserve source spelling, grammar, vocabulary, punctuation and period spacing otherwise;
8. if uncertainty remains, use `needs-review`; do not guess;
9. never perform a global replacement.

## Current progress

- scans in work: **49**;
- full historical-glyph passes complete: **45 / 49**;
- visually verified pages: **36 / 49** (`2, 6, 10–34, 37–45`);
- `needs-review`: **9 / 49** (`1, 3, 4, 5, 7, 8, 9, 35, 36`);
- unresolved visual/source clusters: **3**;
- unprocessed scans: **4 / 49**.

## Exact next activity

Process the **final source batch, scans 46–49**. Scans 46–48 are printed pp.44–46; scan 49 is the back-cover `அல்லி விழி` advertisement. Complete the full source-pixel + 13-family pass for all four, keep scans 35–36 explicit unless genuine evidence resolves them, then perform a page-layer completion audit before any scene assembly.