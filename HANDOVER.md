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
- scan **1 / illustrated front cover** — **verified** at `sources/naanmani-malai-tamil/pages/0001.md`;
- scan **2 / title page** — **verified** at `sources/naanmani-malai-tamil/pages/0002.md`;
- scan **3 / copyright-imprint page** — **verified** at `sources/naanmani-malai-tamil/pages/0003.md`;
- scan **4 / `என்னுரை`** — **verified** at `sources/naanmani-malai-tamil/pages/0004.md`;
- scan **5 / `பதிப்புரை`** — **verified** at `sources/naanmani-malai-tamil/pages/0005.md`;
- scans **6–53** contain the four dramatic works at their durable completed checkpoints;
- scan **54 / illustrated back cover** — **verified** at `sources/naanmani-malai-tamil/pages/0054.md`;
- all **54/54 physical scans** are now represented in the repository workflow;
- source PDF remains external to the repository.

For scans 4–5, the user-supplied words are locked as the lexical baseline. Source inspection controls heading, punctuation/spacing, physical line structure, typography, dashes/quotation treatment and source marks. For scan 5 specifically, verified controls include long dashes in the descriptive sequence, no spaces around the internal dashes in `அனார்கலி—சாக்ரடீஸ்—சேரன் செங்குட்டுவன்`, `இந்நூல்!`, `வழங்குகிறோம்!`, closing `என்றும்போல் ஆதரவு தருக — ஆக்கம் பெருகிட;`, and publisher sign-off `— தமிழ்க்கனி பதிப்பகத்தார்.`. The supplied lexical `நாடகங்களின்` remains retained under the user's explicit word-retention instruction.

## Exact next activity

Run a **composite-source 54-scan coverage / closure audit only** for `கலைஞரின் நான்மணி மாலை`.

Requirements:

- fetch live `main` first;
- read the source README, metadata, physical page map and page records `0001.md`–`0005.md` plus `0054.md`;
- inspect the work-level mapping/status for scans **6–53** without reopening completed literary transcription;
- verify that every physical scan **1–54** is mapped exactly once to front matter, a work/page range, or back cover;
- verify there are no gaps, overlaps or composite-source pages still marked pending/partial;
- verify the source metadata, source README, root README, page map, handover and next-chat checkpoint agree on the completed 54-scan coverage;
- create a durable composite-source closure/audit record if repository conventions support one;
- do **not** change verified literary wording during this audit;
- do **not** begin translation or another dramatic work in the same activity.

## Permanent safeguards

- live `main` controls repository state;
- PDF remains external;
- no silent lexical normalization or semantic reconstruction;
- ambiguous old-glyph readings are not overridden by expectation;
- scene assembly occurs only after every source page for that scene is verified;
- English witnesses are secondary only;
- translation must derive from verified Tamil;
- `அந்தணர்` is not automatically “Brahmin” in future translation work.
