# கலைஞரின் நான்மணி மாலை — controlling Tamil source

Source: `TVA_BOK_0065576_நான்மணி_மாலை.pdf` — **54 scans** — SHA-256 `18d2b1405544b03507e9f92067d287cb28f5a92eaf02bed7054e6e78e5e38c89`.

## Current work state

- `பரதாயணம்`: Tamil archival/assembly PASS; independent English translation PASS.
- `அனார்கலி`: Tamil archival/assembly PASS.
- `சாக்ரடீஸ்`: scans **27–43 = 17/17 pages verified COMPLETE**; all five scenes assembled with page-record fidelity **PASS**.
- `சேரன் செங்குட்டுவன்`: scans **44–53 / pp.39–48 verified COMPLETE**; Tamil page progress **10/10**; all four scenes assembled with page-record fidelity **PASS**; scenes assembled **4/4 COMPLETE**.

For `சேரன் செங்குட்டுவன்`, the user-supplied Gemini first pass is a comparison baseline. The Tamil scan remains controlling under `STAGE_PLAY_PROCESSING_GUIDE.md`; ambiguous old-glyph readings are not normalized by expectation, while unambiguous scan evidence controls canonical wording, spacing, punctuation, labels and source order. The 2009 English witness remains secondary only.

Final-scene artifacts:

- `../../works/cheran-senguttuvan/pages/0052.md`–`0053.md` — scans 52–53 / pp.47–48 — **2/2 verified**;
- `../../works/cheran-senguttuvan/SCENE4_PAGE_VERIFICATION.md` — **PASS / COMPLETE**;
- `../../works/cheran-senguttuvan/scenes/04.md` — **assembly-reviewed / PASS**;
- `../../works/cheran-senguttuvan/SCENE4_ASSEMBLY_FIDELITY_REVIEW.md` — **PASS**.

Scene 4 preserves the source `சேர்!` label variant, `புறப்படுவோம்—வில்லவா.`, `கனக—விஜயா`, `சொல்—இப்போது`, exact source speaker-label punctuation variants, and centered final source mark `- * -`.

**`சேரன் செங்குட்டுவன்` Tamil dramatic-source processing is complete for scans 44–53 / pp.39–48.**

## Composite-source outer/front matter

- scan **1 / illustrated front cover** — **verified** at [`pages/0001.md`](pages/0001.md);
- scan **2 / title page** — **verified** at [`pages/0002.md`](pages/0002.md);
- scan **3 / copyright-imprint page** — **verified** at [`pages/0003.md`](pages/0003.md);
- scan **4 / `என்னுரை`** — **verified** at [`pages/0004.md`](pages/0004.md);
- scan **5 / `பதிப்புரை`** — **verified** at [`pages/0005.md`](pages/0005.md);
- scans 4–5 retain the user-supplied lexical wording; direct scan comparison controls heading, punctuation, spacing, physical lines, dashes/quotation treatment, display/source marks and sign-off treatment;
- scan **54 / illustrated back cover** — **verified** at [`pages/0054.md`](pages/0054.md).

## Composite-source closure

Coverage audit: [`COVERAGE_AUDIT.md`](COVERAGE_AUDIT.md) — **PASS / COMPLETE**.

The 54 physical scans form one exact, non-overlapping partition:

- scans **1–5** — front matter;
- scans **6–17** — `பரதாயணம்`;
- scans **18–26** — `அனார்கலி`;
- scans **27–43** — `சாக்ரடீஸ்`;
- scans **44–53** — `சேரன் செங்குட்டுவன்`;
- scan **54** — back cover.

Result: **54/54 physical scans represented; 0 gaps; 0 overlaps; 0 pending composite-source pages**.

No verified literary wording was changed during the closure audit. The source PDF remains external to the repository.

There is no remaining source-sequential archival task for this composite volume. Further work should begin only from an explicit new user direction.
