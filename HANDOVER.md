# Kalaignar Stage Plays — Handover

Repository: `pugazg/kalaignar-stage-plays`, branch `main`.

## Startup rule

Always fetch live `main` first and treat it as authoritative. The preliminary Scene-1 page-gate commit was `df8ad9d34f71948543f757cce856c999fb7b02cd` — `Verify Socrates Scene 1 source pages 29-31`; the user then supplied the original Gemini first-pass segment and the three pages were re-reconciled against Gemini + the controlling scan. Preserve the newer reconciled state.

Permanent workflow: `STAGE_PLAY_PROCESSING_GUIDE.md`.

Controlling composite source: `TVA_BOK_0065576_நான்மணி_மாலை.pdf` — **54 scans** — SHA-256 `18d2b1405544b03507e9f92067d287cb28f5a92eaf02bed7054e6e78e5e38c89`.

The PDF itself is not committed.

## Locked completed work

- `பரதாயணம்`: Tamil archive/assembly PASS; independent English translation PASS.
- `அனார்கலி`: 9/9 Tamil pages verified; 4/4 scenes assembled; fidelity PASS.
- Silappathikaram completed state remains locked and unchanged.

Do not reopen these during the active `சாக்ரடீஸ்` work unless the user explicitly requests it.

## Active work — சாக்ரடீஸ்

Controlling extent: scans **27–43** / printed pp. **22–38**.

### Introductory note — durable PASS

- `pages/0027.md` — scan 27 / p.22 — verified;
- `pages/0028.md` — scan 28 / p.23 — verified;
- intro: **2/2 verified**.

The user-corrected old-glyph readings in `INTRO_RECONCILIATION.md` remain locked. Do not reintroduce withdrawn assistant normalizations.

### `காட்சி—1` page gate — FINAL RECONCILIATION COMPLETE

- `pages/0029.md` — scan 29 / p.24 — verified;
- `pages/0030.md` — scan 30 / p.25 — verified;
- `pages/0031.md` — scan 31 / p.26 — verified;
- Scene-1 source pages: **3/3 verified**;
- detailed gate / discrepancy record: `works/socrates/SCENE1_PAGE_VERIFICATION.md`;
- Scene-1 assembly: **not yet begun**.

Durable `சாக்ரடீஸ்` progress: **5/17 pages verified** (dramatic body **3/15**).

The final page gate was re-opened after the user supplied the original Gemini first-pass. The Gemini baseline was restored for plausible old-glyph/source readings and changed only where the scan was unambiguous.

Important Scene-1 controls that must not be silently normalized:

- scan 29: `சாக்ரடீசின் வீட்டு வாயில்`, `கச்சைக்கட்டிக்`, `ஈட்டியும்மாத்திரம்`, `மடமைப் பைசாசத்தை`, `காணா`, `புலிநிகர்`, `என்னோடு-புறப்படுங்கள்!`;
- scan 29→30: page 29 ends `எனக்கு`; page 30 continues `வாய்த்த இளம் மனைவி...` with no new speaker label;
- scan 30: `இரண்டாம்தாரம்`, `விழிகளா அவைகள் ?`, `மின்னலப்பா ;`, `இந்தக் கிண்ணாரக் கிழவருக்கு`, `கஷ்டப்பட`, `நட்டாற்றில்`, `ஏண்டி`, `சுடுகாடு`, source speaker-label variation `எக்ஸேந்திபி :` / `சாக் :` / `எக்ஸ்:`;
- scan 31: `அனிடஸ்`, `மெலிடஸ்`, `லைகன்`, `முளைக்கக்`, `புவனமறியாததல்ல`, `கீறல்களை`, `சிரந்தாழ்த்தி`, `உயிரினுமினியவர்`, water-pouring stage direction and final `*`.

Withdrawn preliminary assistant substitutions include `காண`, `புவிநிகர்`, `மின்னல்பா`, `இந்தத் திண்ணைக் கிழவனுக்கு`, `கஷ்டப்பட்ட`, `நடுத்தெருவில்`, and `ஏனடி`. Do not reintroduce them without new unambiguous scan evidence.

Scan-proven changes to the supplied Gemini first-pass are recorded in `SCENE1_PAGE_VERIFICATION.md`, including `காட்சி-1.` → `காட்சி—1.`, `என்னோடு - புறப்படுங்கள்!` → `என்னோடு-புறப்படுங்கள்!`, `படை எதுவுமின்றி.....` → `படை எதுவுமின்றி!.....`, `இருந்தால்.` → `இருந்தால்,`, `சுடுசாடு` → `சுடுகாடு`, and `உயிரினு மினியவர்` → `உயிரினுமினியவர்`.

Permanent old-glyph rule: **retain plausible Gemini readings unless direct scan evidence is unambiguous. Never substitute familiar spelling/name/grammar merely by expectation.**

The 2009 published-English witness remains secondary and cannot reconstruct Tamil.

### Remaining structural map

1. `காட்சி—1` — scans 29–31 / pp.24–26 — page gate COMPLETE, assembly pending;
2. `காட்சி—2` — scan 32 / p.27 — not started;
3. `காட்சி—3` — scan 33 / p.28 — not started;
4. `காட்சி—4` — scans 34–39 / pp.29–34 — not started;
5. `காட்சி—5` — scans 40–43 / pp.35–38 — not started.

## Exact next activity

Assemble **`சாக்ரடீஸ்` `காட்சி—1` only** from verified `pages/0029.md`, `0030.md`, `0031.md`.

Requirements:

- use the **final re-reconciled** verified page records as the sole textual authority for assembly;
- mechanically join legitimate physical print-line/page breaks only;
- specifically handle scan 29→30 `எனக்கு / வாய்த்த...` without inserting a speaker label;
- preserve wording, punctuation, labels, repetitions and stage directions;
- create the Scene-1 assembled file under `works/socrates/scenes/`;
- create/run a page-record ↔ scene fidelity audit;
- do **not** begin scan 32 / `காட்சி—2` in the same activity;
- do not begin `சேரன் செங்குட்டுவன்`.

After a clean assembly/fidelity PASS, the following activity is scan 32 / `காட்சி—2` page verification.

## Permanent safeguards

- scan controls; PDF remains external;
- Gemini is a baseline, not authority to invent text;
- uncertain old glyphs are not modernized by expectation;
- user-rejected assistant corrections stay withdrawn absent new unambiguous source evidence;
- English witnesses are secondary only;
- scene assembly occurs only after all pages of that scene are verified;
- translation is later and must derive from verified Tamil;
- `அந்தணர்` is not automatically “Brahmin” in future translation work.
