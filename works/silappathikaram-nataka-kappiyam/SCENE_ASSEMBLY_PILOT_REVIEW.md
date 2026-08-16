# Scene Assembly Pilot Review — காட்சி-1

## Result

**PASS — the reusable Tamil scene-assembly format and mandatory visual-text-fidelity gate are accepted.**

Pilot output:

`scenes/01.md`

Source inputs:

- controlling Tamil PDF scan **17**;
- verified page record `pages/0017.md`.

## Scene identity

- Scene: `காட்சி-1`
- Decorative lexical title: `வஞ்சி மூதூரில் முரசறைதல்`
- Physical source extent: scan 17 only
- Separate printed setting heading: **none**; scene front matter therefore uses `setting: null`
- Assembly status after review: `assembly-reviewed`
- Visual fidelity: `passed`

## Assembly method accepted

The pilot confirms that scene files may remove purely mechanical printed line wrapping while preserving source wording, punctuation, repetitions, speaker labels and stage directions.

Mechanical joins verified directly against scan 17 include:

- `பொறிக்கப்பட்டிருக் / கிறது` → `பொறிக்கப்பட்டிருக்கிறது`
- `வேலைப் / பாடமைந்த` → `வேலைப்பாடமைந்த`
- `காணப் / படுகிறது` → `காணப்படுகிறது`
- `தமி / ழகம்` → `தமிழகம்`
- `சேர / லாதர்` → `சேரலாதர்` within `நெடுஞ் சேரலாதர்`

Source-supported forms deliberately retained include `தலை நகரான`, `ஆனை`, `அறிவிப்பு!....`, `விற்கொடி. நாட்டிய`, `பிறந்த நாள்`, repeated `கொட்டுவோம்`, and `பூரிப்போடு!`.

## Visual text fidelity check

The actual attached controlling PDF was rendered at high resolution and scan 17 was inspected as a full page plus enlarged title, left-column and right-column views.

The following were compared directly against source pixels:

- `காட்சி-1`;
- decorative lexical title `வஞ்சி மூதூரில் முரசறைதல்`;
- absence of a separate setting heading;
- complete opening bracketed stage direction;
- `முரசறைவோன் :` speaker label;
- complete speech and punctuation;
- final `[முரசு முழங்குகிறது]` direction;
- all mechanical joins introduced during assembly;
- title artwork and lower pictorial layer separation.

The assembled file was then compared with verified `pages/0017.md`. No omitted, duplicated, normalized or silently corrected literary content was found.

**No correction to `pages/0017.md` was required.**

## Visual layers

- The decorative title integrates architectural forms and a drummer. Artwork remains separate from lexical title text.
- A large grayscale printed image of a female figure/bust occupies the lower half of scan 17. It is uncaptioned on this scan and remains unidentified in the archive.
- No printed page number is visibly present; none is inferred.

## Accepted reusable gate

For every later scene:

1. assemble from verified page record(s) at `draft` / `visual_text_fidelity: pending`;
2. inspect every contributing controlling-source scan directly at native/enlarged resolution;
3. compare every assembled literary character and mechanical join to source pixels;
4. compare the assembled scene again to its verified page record(s);
5. set `visual_text_fidelity: passed` and `status: assembly-reviewed` only if both comparisons pass;
6. if source pixels prove a verified page wrong, correct only the affected page with explicit documentation before updating the scene.

## Exact next activity

Assemble and visually fidelity-check **காட்சி-2 / scan 18 — `செங்குட்டுவன் பிறந்தநாள் விழா`, setting `வஞ்சி`**.

Do not begin English translation.
