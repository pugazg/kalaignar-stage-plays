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
- scan **54 / back cover** is now **verified** at `sources/naanmani-malai-tamil/pages/0054.md`;
- scan 54 printed wording: `கலைஞரின் நான்மணி மாலை` over three lines;
- scan 54 is a full-page colour printed illustration with no visible literary body text, pagination, publisher/imprint line, price line, library stamp, accession mark or later handwriting;
- shared front matter scans **1–5** remain only partially represented at page level;
- source PDF remains external to the repository.

## Exact next activity

Process **scan 1 / illustrated front cover only** from `TVA_BOK_0065576_நான்மணி_மாலை.pdf` as an archival-description page for the composite Tamil source.

Requirements:

- fetch live `main` first;
- inspect scan 1 directly from the controlling PDF;
- treat it as a front-cover / non-literary source page unless the scan itself proves printed literary text;
- distinguish printed publication material from library marks, later handwriting, stamps, damage or other non-authorial marks;
- preserve every visible printed title/imprint/caption element exactly;
- create `sources/naanmani-malai-tamil/pages/0001.md` only after direct visual verification;
- update the composite source page map, source metadata/README, root README, handover and next-chat checkpoint after verification;
- do **not** process scan 2 in the same activity;
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
