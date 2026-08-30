# Kalaignar Stage Plays — Handover

## Repository

`pugazg/kalaignar-stage-plays` on `main`.

Permanent workflow: `STAGE_PLAY_PROCESSING_GUIDE.md`.

## Active controlling source

`TVA_BOK_0065576_நான்மணி_மாலை.pdf` — 54 scans — SHA-256 `18d2b1405544b03507e9f92067d287cb28f5a92eaf02bed7054e6e78e5e38c89`.

The scan remains controlling. Gemini is normally assistive, but where old Tamil glyphs are ambiguous do not silently replace the user's Gemini first pass with an assistant guess.

## Locked completed work

- `பரதாயணம்`: Tamil archive/assembly PASS; independent English translation PASS.
- `அனார்கலி`: 9/9 Tamil pages verified; 4/4 scenes assembled; fidelity PASS.

## Active work — சாக்ரடீஸ்

Extent: scans **27–43** / printed pp. **22–38**.

### Corrected durable checkpoint

The prior commit `360d14592161035c467c82a19d7f7eef1511bacc` incorrectly marked scans 27–28 verified after overriding portions of the supplied Gemini transcription with assistant old-glyph guesses.

The user explicitly corrected this and instructed that Gemini's transcription be retained.

Therefore:

- scans **27–28** are now **needs-review**, not verified;
- Gemini is retained as the working transcription layer;
- the assistant-introduced `மார்க்கமும், ஏஞ்சல்சும்`, `ஹெகெல்`, `நாமே`, and the broader advertised correction set for these two scans are withdrawn as source corrections;
- do not describe `‘ஜாடை’ காட்டினன்`, `தாச நிகர் காரணங்களைக்கொண்டு`, `‘சோக்ரதர்’`, `சபையன்`, `ஆஸ்திகப்பழமைவாதியாக்கியிருக்கிறார்`, or any other disputed intro reading as a new assistant-confirmed correction merely from glyph appearance;
- if a source glyph is ambiguous on re-review, keep Gemini and record the ambiguity;
- 2009 English remains secondary and must not reconstruct Tamil.

Current page files:

- `works/socrates/pages/0027.md` — needs-review;
- `works/socrates/pages/0028.md` — needs-review.

Current verified Socrates count: **0/17**.

### Structural map — unchanged

1. `காட்சி—1` — scans **29–31** / pp.24–26;
2. `காட்சி—2` — scan **32** / p.27;
3. `காட்சி—3` — scan **33** / p.28;
4. `காட்சி—4` — scans **34–39** / pp.29–34;
5. `காட்சி—5` — scans **40–43** / pp.35–38.

### Exact next activity

Re-reconcile scans **27–28** against the user's Gemini transcription using conservative old-glyph handling. Do not advance to scan 29 until both introductory pages are cleanly re-verified.

## Permanent controls

Preserve source wording, punctuation, speaker labels, stage directions, page boundaries and old Tamil forms. Never normalize an uncertain glyph silently. `அந்தணர்` is not automatically “Brahmin” in future translation work.
