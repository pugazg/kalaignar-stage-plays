# Kalaignar Stage Plays — Handover

Repository: `pugazg/kalaignar-stage-plays`, branch `main`.

## Startup rule

Always fetch live `main` first and treat it as authoritative. Preserve newer durable state and never reopen completed work unless the user explicitly requests it.

Permanent workflow: `STAGE_PLAY_PROCESSING_GUIDE.md`.

Controlling composite source: `TVA_BOK_0065576_நான்மணி_மாலை.pdf` — **54 scans** — SHA-256 `18d2b1405544b03507e9f92067d287cb28f5a92eaf02bed7054e6e78e5e38c89`.

## Locked completed work

- `பரதாயணம்`: Tamil archive/assembly PASS; independent English translation PASS.
- `அனார்கலி`: Tamil page/assembly fidelity PASS.
- `சாக்ரடீஸ்`: **17/17 pages verified; 5/5 scenes assembled; all fidelity gates PASS**.
- Silappathikaram completed state remains locked and unchanged.
- `சேரன் செங்குட்டுவன்`: **10/10 Tamil pages verified; 4/4 scenes assembled; all page-record ↔ scene fidelity gates PASS**.

Completed Cheran Scene-4 locked controls include source `காட்சி—4.`, `குயிலாலுவம்`, exact speaker-label variants `சேர்:`, `சேர்;`, unusual `சேர்!`, `வில்லவன்:`, `வில்:`, `வில்!`, `கன:`, source long dashes, `ராம ராவணப் போர்?....`, `புறப்படுவோம்—வில்லவா.`, `கனக—விஜயா`, `சொல்—இப்போது`, and centered final `- * -`.

## Composite source — கலைஞரின் நான்மணி மாலை

- total scans: **54**;
- scans **6–53** contain the four dramatic works at their durable completed checkpoints;
- scan **1 / illustrated front cover** is **verified** at `sources/naanmani-malai-tamil/pages/0001.md`;
- scan **2 / title page** is **verified** at `sources/naanmani-malai-tamil/pages/0002.md`;
- scan **3 / copyright-imprint page** is **verified** at `sources/naanmani-malai-tamil/pages/0003.md`;
- scan **4 / `என்னுரை`** is **verified** at `sources/naanmani-malai-tamil/pages/0004.md`;
- for scan 4, the user-supplied words are locked as the lexical baseline; source inspection controls heading, punctuation/spacing, physical line structure, typography and source marks only;
- verified scan-4 punctuation includes spaces before `!` in `மாலை !`, `மாலையாக !`, `கேட்டது !`, `படித்தது !`, and `நடித்தது !`;
- the closing `அன்புள்ள` is followed by a printed facsimile signature; the supplied trailing `5` is not a separate printed textual digit and was not transcribed;
- scan **54 / illustrated back cover** is **verified** at `sources/naanmani-malai-tamil/pages/0054.md`;
- the only remaining shared front-matter page-level task is **scan 5 / `பதிப்புரை`**;
- source PDF remains external to the repository.

## Exact next activity

Process **scan 5 / `பதிப்புரை` only** from `TVA_BOK_0065576_நான்மணி_மாலை.pdf` as the final shared-front-matter page-level archival transcription.

The user has already supplied a lexical transcription for scan 5 in the current conversation. Use those **words as the baseline and keep them**. Direct scan comparison should control only heading, punctuation, hyphens/dashes, quotation marks, paragraph/physical line structure, signature/imprint treatment, and other source marks unless the user separately authorizes lexical changes.

Requirements:

- fetch live `main` first;
- inspect scan 5 directly from the controlling PDF;
- preserve the user-supplied words;
- create `sources/naanmani-malai-tamil/pages/0005.md` only after direct visual verification;
- distinguish printed publication text from library marks, later handwriting, stamps, damage, bleed-through or other non-authorial marks;
- update the composite source page map, source metadata/README, root README, handover and next-chat checkpoint after verification;
- do **not** reopen any completed dramatic work;
- do **not** begin another work in the same activity.

## Permanent safeguards

- live `main` controls repository state;
- PDF remains external;
- no silent lexical normalization or semantic reconstruction;
- ambiguous old-glyph readings are not overridden by expectation;
- scene assembly occurs only after every source page for that scene is verified;
- English witnesses are secondary only;
- translation must derive from verified Tamil;
- `அந்தணர்` is not automatically “Brahmin” in future translation work.
