# கலைஞரின் நான்மணி மாலை — controlling Tamil source

Source: `TVA_BOK_0065576_நான்மணி_மாலை.pdf` — **54 scans** — SHA-256 `18d2b1405544b03507e9f92067d287cb28f5a92eaf02bed7054e6e78e5e38c89`.

## Current work state

- `பரதாயணம்`: Tamil archival/assembly **PASS**; independent English **PASS / COMPLETE**; 2009 One Act Plays witness **NOT APPLICABLE**.
- `அனார்கலி`: Tamil **9/9**, 4/4 scenes and fidelity **PASS**; independent English **PASS / COMPLETE**; 2009 comparison **PASS / COMPLETE**.
- `சாக்ரடீஸ்`: Tamil **17/17**, 5/5 scenes and fidelity **PASS**; independent English introduction + 5/5 scenes **PASS / COMPLETE**; 2009 comparison **PASS / COMPLETE**.
- `சேரன் செங்குட்டுவன்`: Tamil **10/10**, 4/4 scenes and fidelity **PASS**; independent English **PASS / COMPLETE**; 2009 comparison **PASS / COMPLETE**.

The Tamil scan remains controlling under `STAGE_PLAY_PROCESSING_GUIDE.md`. Published English is secondary only and must not reconstruct Tamil or silently control an independent translation.

## Composite-source outer/front matter

- scan **1 / illustrated front cover** — **verified** at [`pages/0001.md`](pages/0001.md);
- scan **2 / title page** — **verified** at [`pages/0002.md`](pages/0002.md);
- scan **3 / copyright-imprint page** — **verified** at [`pages/0003.md`](pages/0003.md);
- scan **4 / `என்னுரை`** — **verified** at [`pages/0004.md`](pages/0004.md);
- scan **5 / `பதிப்புரை`** — **verified** at [`pages/0005.md`](pages/0005.md);
- scan **54 / illustrated back cover** — **verified** at [`pages/0054.md`](pages/0054.md).

Scans 4–5 retain the user-supplied lexical wording; direct scan comparison controls heading, punctuation, spacing, physical lines, dashes/quotation treatment, display/source marks and sign-off treatment.

## Composite-source Tamil closure

Coverage audit: [`COVERAGE_AUDIT.md`](COVERAGE_AUDIT.md) — **PASS / COMPLETE**.

The 54 physical scans form one exact, non-overlapping partition:

- scans **1–5** — front matter;
- scans **6–17** — `பரதாயணம்`;
- scans **18–26** — `அனார்கலி`;
- scans **27–43** — `சாக்ரடீஸ்`;
- scans **44–53** — `சேரன் செங்குட்டுவன்`;
- scan **54** — back cover.

Result: **54/54 physical scans represented; 0 gaps; 0 overlaps; 0 pending composite-source pages**.

## English-phase closure

English closure audit: [`ENGLISH_PHASE_CLOSURE_AUDIT.md`](ENGLISH_PHASE_CLOSURE_AUDIT.md) — **PASS / COMPLETE**.

Independent English translation gates:

- `பரதாயணம்` — **PASS / COMPLETE**;
- `அனார்கலி` — **PASS / COMPLETE**;
- `சாக்ரடீஸ்` — **PASS / COMPLETE**;
- `சேரன் செங்குட்டுவன்` — **PASS / COMPLETE**.

Count: **4 / 4 independent English translations COMPLETE**.

The repository's 2009 *One Act Plays* witness contains exactly `Anarkali`, `Cheran Senguttuvan`, and `Socrates`. It contains no `Bharathayanam`.

Therefore:

- applicable complete 2009 witness plays: **3**;
- completed applicable post-translation comparisons: **3 / 3**;
- `பரதாயணம்`: **NOT APPLICABLE**, not pending;
- pending independent translations: **0**;
- pending applicable witness comparisons: **0**.

Comparison provenance:

- `அனார்கலி` — 2009 scans **135–140** — comparison **PASS / COMPLETE**;
- `சேரன் செங்குட்டுவன்` — 2009 scans **141–149** — comparison **PASS / COMPLETE**;
- `சாக்ரடீஸ்` — 2009 scans **150–160** — comparison **PASS / COMPLETE**.

No verified Tamil or reviewed independent English wording was changed by the English-phase closure audit.

## Closed volume state

**Tamil archival phase: PASS / COMPLETE.**  
**Independent English phase: PASS / COMPLETE.**  
**Applicable 2009 secondary-witness comparison phase: PASS / COMPLETE.**

There is no remaining source-sequential or English-sequential task for this four-play composite volume. A new work or revision phase should begin only from explicit user direction. The source PDF remains external to the repository.