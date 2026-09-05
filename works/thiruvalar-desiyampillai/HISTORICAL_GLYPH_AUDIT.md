# Historical Tamil Glyph Audit — திருவாளர் தேசீயம்பிள்ளை

Status: **SOURCE PASS COMPLETE — 49 / 49 SCANS CHECKED**

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

Every scan has now been checked for:

`ணா / ணை / ணொ / ணோ / லை / ளை / றா / றொ / றோ / னா / னை / னொ / னோ`.

## Established same-edition reference set

Positive same-edition evidence supports:

`லை / ளை / ணா / ணை / னா / னை / றா`.

Representative anchors include:

- `லை`: `கலைஞர்`, `தலைகள்`, `மாலைதானே`, `விலைமதிக்க`, `மாலையை`, `உடுமலைப்`, `காலை`, `ஆலை முதலாளி`, scan-48 physical `மலை / யேறும்`;
- `ளை`: `பிள்ளை`, `உங்களை`, `விளையும்`, `கால்களைப்`, `கண்களைத்`;
- `ணா`: `கருணாநிதி`, `கல்யாண`, `ஆகாஷவாணி`, physical `சொல் / வொணா`, `அரையணா`;
- `ணை`: scan-25 `சொரணை`;
- `னா`: `கெட்டிக்காரர்தானா`, `உடையவர்தானா`, `மானால்`, `தானா`, `மகனா`, `உடைதானா`, `அரசனா / ஆண்டவனா`;
- `னை`: `அவனை`, `தண்டனை`, `என்னை`;
- `றா`: `வண்ணமிருக்கிறார்களே`, `பார்க்கிறார்`, `நன்றாக`, `என்றாரே`, `மாறியிருக்கிறது`, `பொறாமை`, `மாறிப்போச்சு`.

These references are used only for character-identity comparison. They never authorize reconstruction of physically absent text, lexical normalization, or global replacement.

## Authoritative character-identity corrections

The following source-pixel rechecks are canonical and must not be reverted:

- scan 15 `என்றுரே` → **`என்றாரே`** (`றா`);
- scan 15 `தானு` → **`தானா`** (`னா`);
- scan 20 `நன்றுக` → **`நன்றாக`** (`றா`);
- scan 21 `மகனு` → **`மகனா`** (`னா`);
- scan 28 `மால்தானே` → **`மாலைதானே`** (`லை`);
- scan 42 first-line old-type form → **`பொறாமை`** (`றா`);
- scan 44 page-ending old-type form → **`ஆலை முதலாளி`** (`லை`).

Final-source enlarged rechecks also preserve exact source forms on scans 46–48:

- scan 46 **`நம்ப`**, not normalized to `நம்ம`;
- scan 46 **`தேசீயம் பிள்ளை`**;
- scan 47 **`தேசீயம்பிள்ளை / தேசீயம் பிள்ளையின் / போட்டகோலம்`**;
- scan 48 **`தேசீயம் பிள்ளையின்`** and physical **`மலை / யேறும்`**.

## Completed batches

- **Batch 1 — scans 1–5:** full passes complete; scan 2 verified; 1, 3, 4, 5 damage-limited.
- **Batch 2 — scans 6–10:** full passes complete; 6 and 10 verified; 7–9 damage-limited; `னை` established.
- **Batch 3 — scans 11–15:** all verified; `றா` established; later scan-15 recheck.
- **Batch 4 — scans 16–20:** all verified; scan 20 `நன்றாக` adjudication.
- **Batch 5 — scans 21–25:** all verified; `ணை` established from `சொரணை`.
- **Batch 6 — scans 26–30:** all verified; `னா` established; scan 28 `மாலைதானே` correction.
- **Batch 7 — scans 31–35:** 31–34 verified; scan 35 has one unresolved visual/source cluster.
- **Batch 8 — scans 36–40:** scan 36 has two unresolved clusters; 37–40 verified.
- **Batch 9 — scans 41–45:** all verified; `பொறாமை` and `ஆலை முதலாளி` explicitly adjudicated.
- **Batch 10 — scans 46–49:** **all four verified**; final body and back-cover source pass complete.

## Batch 10 — scans 46–49

| Scan | Representative evidence | Result |
|---:|---|---|
| 46 | `நம்ப`, `பிள்ளையாண்டான்`, `‘உதயசூரியனு’க் / குத்தானே`, `கலைத் / திருப்பார்களே`, `தேசீயம் பிள்ளை` | **verified** — enlarged recheck preserves source colloquial/name forms and established `லை / ளை / னை` identities |
| 47 | `மாலைப்`, `தேசீயம்பிள்ளை`, `தேசீயம் பிள்ளையின்`, `போட்டகோலம்`, centered `உதயசூரியன் கோலம்` | **verified** — source wording/spacing and historical families checked without normalization |
| 48 | `மலை / யேறும்`, `தேசீயம் பிள்ளையின்`, `மனைவி` | **verified** — final dramatic-body text; historical `லை` identity confirmed; no source-visible `முற்றும்` marker |
| 49 | `க. முத்துக்கண்ணன்`, `“அல்லி விழி”`, `(கவிதை)`, `1-50`, `K. R. நாராயணன்` | **verified** — back-cover advertisement fully readable despite extensive cover wear; full 13-family pass complete |

## Remaining review holds

The full 49-scan glyph pass does **not** convert unsupported source areas into verified text.

`needs-review` pages remain:

- physical-damage holds: **1, 3, 4, 5, 7, 8, 9**;
- unresolved visual/source-cluster holds: **35, 36**.

Current unresolved visual/source clusters: **3** total — scan 35: 1; scan 36: 2.

Later scans 37–49 do not provide genuine same-edition evidence strong enough to clear those three clusters. The apparent scan-35 `கொழுப்பேறி` reading remains non-canonical.

## Final progress

- scans in work: **49**;
- full historical-glyph passes complete: **49 / 49**;
- visually verified pages: **40 / 49** (`2, 6, 10–34, 37–49`);
- `needs-review`: **9 / 49** (`1, 3, 4, 5, 7, 8, 9, 35, 36`);
- unresolved visual/source clusters: **3**;
- unprocessed scans: **0 / 49**.

The source/glyph pass is therefore **complete**, while full-page verification remains transparently limited by source condition. See `PAGE_LAYER_COMPLETION_AUDIT.md` for the completion verdict and scene-assembly gate.

## Exact next activity

Perform the **source-visible structural / scene inventory across scans 7–48**. Use page records and source-visible headings only; do not invent scene numbering or repair the five body review holds (`7, 8, 9, 35, 36`).