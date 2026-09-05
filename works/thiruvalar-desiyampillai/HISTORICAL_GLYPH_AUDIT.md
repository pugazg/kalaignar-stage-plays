# Historical Tamil Glyph Audit — திருவாளர் தேசீயம்பிள்ளை

Status: **IN PROGRESS — 40 / 49 SCANS COMPLETE**

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

- `லை`: `கலைஞர்`, `தலைகள்`, `மாலைதானே`, `விலைமதிக்க`, `மாலையை`, scan-37 `மாலையை`, scan-39/40 `உடுமலைப் / காலை`;
- `ளை`: `பிள்ளை`, `உங்களை`, `விளையும்`, scan-38 `கால்களைப்`, scan-40 `கண்களைத்`;
- `ணா`: `கருணாநிதி`, `கல்யாண`, `ஆகாஷவாணி`, physical `சொல் / வொணா`;
- `ணை`: scan-25 `சொரணை`;
- `னா`: `கெட்டிக்காரர்தானா`, `உடையவர்தானா`, `மானால்`, `தானா`, `மகனா`, `உடைதானா`, `அரசனா / ஆண்டவனா`;
- `னை`: `அவனை`, `தண்டனை`;
- `றா`: `வண்ணமிருக்கிறார்களே`, `பார்க்கிறார்`, `நன்றாக`, `என்றாரே`.

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

## Batch 8 — scans 36–40

Full source-pixel + 13-family passes completed for all five scans.

| Scan | Representative evidence | Result |
|---:|---|---|
| 36 | `பிள்ளை`, repeated verbal `றா`; continuation after scan-35 `எங்குவேன்` | **needs-review** — two short descriptive clusters in the `ஹரிஜன நலம்` / `சவலைப் பிள்ளை` imagery remain visually insecure |
| 37 | `மாலையை`, `தேசீயம் பிள்ளை`, repeated `றா` | **verified** — old-type `லை` identity in `மாலையை` supported; source colloquialisms retained |
| 38 | `கால்களைப்`, `இடமில்லை`, `தேசீயம் பிள்ளை` | **verified** — source `நாகத்திலும்` checked and retained rather than normalized |
| 39 | `உடுமலைப்`, `தேசீயம் பிள்ளை`, repeated verbal endings | **verified** — place-name stair sequence through `உடுமலைப் படியில்` fully supported |
| 40 | `கண்களைத்`, `காலை`, candidate families across page | **verified** — stair/place-name sequence and `உதய சூரியன்` wake-from-dream passage fully supported |

### Scan-35 review hold remains open

Later same-edition evidence in scans 36–40 did **not** genuinely resolve scan 35's single cluster in:

`கொம்பு மாடெனக் … மட்டும் / வளர்த்து ஒன்றிரண்டு முட்டிக்கொண்டு`

The apparent reading resembling `கொழுப்பேறி` remains non-canonical.

### Scan-36 review hold

Scan 36 is otherwise source-readable and the full 13-family pass is complete, but two short descriptive clusters in the sick-child metaphor remain visually insecure. They are represented explicitly in `pages/0036.md` rather than reconstructed from expectation.

## Review / damage boundary through scan 40

`needs-review` pages are now:

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
- full historical-glyph passes complete: **40 / 49**;
- visually verified pages: **31 / 49** (`2, 6, 10–34, 37–40`);
- `needs-review`: **9 / 49** (`1, 3, 4, 5, 7, 8, 9, 35, 36`);
- unresolved visual/source clusters: **3**;
- unprocessed scans: **9 / 49**.

## Exact next activity

Run the full source-pixel + historical-glyph verification for **scans 41–45** (printed pages **39–43**) while creating their canonical transcriptions. Keep scans 35 and 36 review holds open unless later same-edition evidence genuinely resolves them.