# Next Chat Prompt — Continue Kalaignar Stage Plays

Continue the Kalaignar Stage Plays archival project directly in:

`https://github.com/pugazg/kalaignar-stage-plays`

Branch: `main`.

Use the GitHub connector and work directly on `main`.

Controlling source PDF: `TVA_BOK_0065576_நான்மணி_மாலை.pdf`.

## Live-state rule

Fetch live GitHub `main` first and treat it as authoritative. Preserve any newer durable state. Do not reopen completed dramatic works unless explicitly requested.

## Mandatory startup reading

Before any write, read completely:

1. `STAGE_PLAY_PROCESSING_GUIDE.md`
2. `HANDOVER.md`
3. `NEXT_CHAT_PROMPT.md`
4. root `README.md`
5. `sources/naanmani-malai-tamil/README.md`
6. `sources/naanmani-malai-tamil/metadata/source.md`
7. `sources/naanmani-malai-tamil/indexes/page-map.md`
8. `sources/naanmani-malai-tamil/pages/0001.md`
9. `sources/naanmani-malai-tamil/pages/0002.md`
10. `sources/naanmani-malai-tamil/pages/0054.md`

Then re-fetch live `main` immediately before the first write.

## Completed durable state

- `பரதாயணம்` — Tamil archive/assembly PASS; independent English translation PASS.
- `அனார்கலி` — Tamil page/assembly fidelity PASS.
- `சாக்ரடீஸ்` — **17/17 pages verified; 5/5 scenes assembled; all fidelity gates PASS**.
- `சேரன் செங்குட்டுவன்` — **10/10 Tamil pages verified; 4/4 scenes assembled; all fidelity gates PASS**.

## Composite source state — `கலைஞரின் நான்மணி மாலை`

- total scans: **54**;
- scans **6–53** contain the completed dramatic works;
- scan **1 / illustrated front cover** — **verified** at `sources/naanmani-malai-tamil/pages/0001.md`;
- scan **2 / title page** — **verified** at `sources/naanmani-malai-tamil/pages/0002.md`;
- scan 2 preserves `கலைஞரின் நான்மணி மாலை`, publisher `தமிழ்க்கனி பதிப்பகம்`, the decorative lamp emblem between the publisher words, and `சென்னை-28`;
- scan **54 / illustrated back cover** — **verified** at `sources/naanmani-malai-tamil/pages/0054.md`;
- shared front-matter scans **3–5** remain pending at page level;
- source PDF remains external to the repository.

## Exact next activity

Process **scan 3 / copyright-imprint page only** as a page-level archival transcription/description for the composite Tamil source.

Requirements:

- inspect scan 3 directly from the controlling PDF;
- preserve every visible printed copyright, price, printer/imprint, address/location and other publication line exactly, including punctuation and spacing;
- distinguish printed publication material from library stamps, accession marks, later handwriting, damage or other non-authorial marks;
- create `sources/naanmani-malai-tamil/pages/0003.md` only after direct visual verification;
- update the composite source page map, source metadata/README, root README, handover and this next-chat prompt after verification;
- do **not** process scan 4 in the same activity;
- do **not** reopen any completed dramatic work;
- do **not** begin another work in the same activity.

When I say **“Proceed with next activity”**, execute this exact activity directly without asking me to choose a routine next step.
