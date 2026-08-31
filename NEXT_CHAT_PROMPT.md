# Next Chat Prompt — Continue `சாக்ரடீஸ்` in Kalaignar Stage Plays

Continue the Kalaignar Stage Plays archival project directly in:

`https://github.com/pugazg/kalaignar-stage-plays`

Branch: `main`.

Use the GitHub connector and work directly on `main`.

Controlling source PDF: `TVA_BOK_0065576_நான்மணி_மாலை.pdf`.

## Live-state rule

Fetch live GitHub `main` **FIRST** and treat it as authoritative. The Scene-1 page gate was first committed at `df8ad9d34f71948543f757cce856c999fb7b02cd`, then re-opened after the user supplied the original Gemini first-pass for scans 29–31. Preserve the newer final Gemini/source reconciliation and do not revert it.

## Mandatory startup reading

Read completely before any write:

1. `STAGE_PLAY_PROCESSING_GUIDE.md`
2. `HANDOVER.md`
3. `NEXT_CHAT_PROMPT.md`
4. `works/socrates/INTRO_RECONCILIATION.md`
5. `works/socrates/SCENE1_PAGE_VERIFICATION.md`
6. `works/socrates/README.md`
7. `works/socrates/metadata/source.md`
8. `works/socrates/indexes/page-map.md`
9. `works/socrates/pages/0029.md`
10. `works/socrates/pages/0030.md`
11. `works/socrates/pages/0031.md`

Then re-fetch live `main` immediately before the first write.

## Durable state

Completed/locked:

- `பரதாயணம்` — Tamil archive/assembly PASS; independent English translation PASS.
- `அனார்கலி` — Tamil archive/assembly PASS.
- Silappathikaram complete state remains locked.

Active work: `சாக்ரடீஸ்`.

- source extent: scans **27–43** / pp.22–38;
- introductory note scans 27–28: **2/2 verified**;
- `காட்சி—1` scans 29–31 / pp.24–26: **3/3 page records verified after final Gemini/source reconciliation**;
- total Socrates page progress: **5/17 verified**;
- dramatic page progress: **3/15**;
- Scene-1 assembly: **pending**.

Critical page boundary: scan 29 ends Socrates' speech at `எனக்கு`; scan 30 begins `வாய்த்த இளம் மனைவி...`. Assembly must join this mechanically without inventing a new speaker label.

## Critical Scene-1 controls

The user supplied the original Gemini first-pass after a preliminary page-gate commit. The three page records were therefore re-reconciled and the later text is controlling.

Retain these final readings exactly unless new unambiguous scan evidence appears:

- scan 29: `மடமைப் பைசாசத்தை`, `காணா`, `புலிநிகர்`, `என்னோடு-புறப்படுங்கள்!`;
- scan 30: `மின்னலப்பா ;`, `இந்தக் கிண்ணாரக் கிழவருக்கு`, `கஷ்டப்பட`, `நட்டாற்றில்`, `ஏண்டி`, `சுடுகாடு`;
- scan 31: `புவனமறியாததல்ல`, `கீறல்களை`, `சிரந்தாழ்த்தி`, `உயிரினுமினியவர்` plus the source punctuation recorded in `pages/0031.md`.

Do **not** reintroduce the withdrawn preliminary assistant readings `காண`, `புவிநிகர்`, `மின்னல்பா`, `இந்தத் திண்ணைக் கிழவனுக்கு`, `கஷ்டப்பட்ட`, `நடுத்தெருவில்`, or `ஏனடி`.

The complete discrepancy record is `works/socrates/SCENE1_PAGE_VERIFICATION.md`. The 2009 published-English witness remains secondary and cannot reconstruct Tamil.

## Exact next activity

Assemble **`சாக்ரடீஸ்` `காட்சி—1` only** from the three **final re-reconciled verified** page records.

Requirements:

- verified page records are the sole textual authority;
- mechanically join legitimate print-line and page-boundary splits only;
- preserve all dialogue labels, punctuation, repetitions and stage directions;
- create the assembled Scene-1 file under `works/socrates/scenes/`;
- run/create a page-record ↔ scene fidelity audit and require PASS before advancing;
- **do not start scan 32 / `காட்சி—2` in the same activity**;
- do not start `சேரன் செங்குட்டுவன்`.

After Scene-1 assembly/fidelity PASS, the next distinct activity is `காட்சி—2` page verification at scan **32** / printed p.27.

When I say **“Proceed with next activity”**, execute this exact activity directly without asking me to choose a routine next step.
