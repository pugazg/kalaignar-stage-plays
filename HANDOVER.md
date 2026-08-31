# Kalaignar Stage Plays — Handover

Repository: `pugazg/kalaignar-stage-plays`, branch `main`.

## Startup rule

Always fetch live `main` first and treat it as authoritative. The Scene-1 assembly activity began from live `main` `7ec8d99c4dc6784ab39fc9144e8eb6a839601b3e`, after the final Gemini/source reconciliation of scans 29–31. Preserve any newer live state.

Permanent workflow: `STAGE_PLAY_PROCESSING_GUIDE.md`.

Controlling composite source: `TVA_BOK_0065576_நான்மணி_மாலை.pdf` — **54 scans** — SHA-256 `18d2b1405544b03507e9f92067d287cb28f5a92eaf02bed7054e6e78e5e38c89`.

The PDF itself is not committed. Attach it again in a fresh chat before new page-level visual verification.

## Locked completed work

- `பரதாயணம்`: Tamil archive/assembly PASS; independent English translation PASS.
- `அனார்கலி`: 9/9 Tamil pages verified; 4/4 scenes assembled; fidelity PASS.
- Silappathikaram completed state remains locked and unchanged.

Do not reopen these during active `சாக்ரடீஸ்` work unless the user explicitly requests it.

## Active work — சாக்ரடீஸ்

Controlling extent: scans **27–43** / printed pp. **22–38**.

### Introductory note — durable PASS

- `pages/0027.md` — scan 27 / p.22 — verified;
- `pages/0028.md` — scan 28 / p.23 — verified;
- intro: **2/2 verified**.

The user-corrected old-glyph readings in `INTRO_RECONCILIATION.md` remain locked. Do not reintroduce withdrawn assistant normalizations.

### `காட்சி—1` — COMPLETE THROUGH ASSEMBLY/FIDELITY GATE

Source extent: scans **29–31** / printed pp. **24–26**.

- `pages/0029.md` — verified;
- `pages/0030.md` — verified;
- `pages/0031.md` — verified;
- final page gate: **3/3 PASS**;
- assembled scene: `works/socrates/scenes/01.md` — **assembly-reviewed**;
- page-record ↔ scene audit: `works/socrates/ASSEMBLY_FIDELITY_REVIEW.md` — **PASS**;
- unresolved assembly discrepancies: **0**;
- scene assemblies completed: **1/5**.

Durable `சாக்ரடீஸ்` page progress remains **5/17 verified** (dramatic body **3/15**).

The assembly uses the final verified page records only. The scan 29→30 boundary is joined mechanically as `...எனக்கு வாய்த்த இளம் மனைவி...`, with no invented speaker label.

Important Scene-1 controls that must not be silently normalized:

- scan 29: `சாக்ரடீசின் வீட்டு வாயில்`, `கச்சைக்கட்டிக்`, `ஈட்டியும்மாத்திரம்`, `மடமைப் பைசாசத்தை`, `காணா`, `புலிநிகர்`, `என்னோடு-புறப்படுங்கள்!`;
- scan 30: `இரண்டாம்தாரம்`, `விழிகளா அவைகள் ?`, `மின்னலப்பா ;`, `இந்தக் கிண்ணாரக் கிழவருக்கு`, `கஷ்டப்பட`, `நட்டாற்றில்`, `ஏண்டி`, `சுடுகாடு`, source label variation `எக்ஸேந்திபி :` / `சாக் :` / `எக்ஸ்:`;
- scan 31: `அனிடஸ்`, `மெலிடஸ்`, `லைகன்`, `முளைக்கக்`, `புவனமறியாததல்ல`, `கீறல்களை`, `சிரந்தாழ்த்தி`, `உயிரினுமினியவர்`, water-pouring stage direction and final `*`.

Withdrawn preliminary assistant substitutions include `காண`, `புவிநிகர்`, `மின்னல்பா`, `இந்தத் திண்ணைக் கிழவனுக்கு`, `கஷ்டப்பட்ட`, `நடுத்தெருவில்`, and `ஏனடி`. Do not reintroduce them without new unambiguous scan evidence.

Permanent old-glyph rule: **retain plausible Gemini readings unless direct scan evidence is unambiguous. Never substitute familiar spelling/name/grammar merely by expectation.**

The 2009 published-English witness remains secondary and cannot reconstruct Tamil.

### Remaining structural map

1. `காட்சி—1` — scans 29–31 / pp.24–26 — **page gate + assembly/fidelity COMPLETE**;
2. `காட்சி—2` — scan 32 / p.27 — not started;
3. `காட்சி—3` — scan 33 / p.28 — not started;
4. `காட்சி—4` — scans 34–39 / pp.29–34 — not started;
5. `காட்சி—5` — scans 40–43 / pp.35–38 — not started.

## Exact next activity

Verify **`சாக்ரடீஸ்` `காட்சி—2` only**, scan **32** / printed p.27.

Requirements:

- use the user-supplied Gemini first-pass as baseline where it is available in the active chat;
- compare every word, punctuation mark, speaker label, stage direction and physical line boundary directly against scan 32;
- retain Gemini for plausible old-glyph readings unless the scan is unambiguous;
- create `works/socrates/pages/0032.md` only after direct visual verification;
- update work/source page maps and handover after the page gate;
- expected page progress after success: **6/17 verified**;
- because `காட்சி—2` is a one-scan scene, **do not assemble it in the same activity**; assembly/fidelity is the following distinct activity;
- do not begin scan 33 / `காட்சி—3`;
- do not begin `சேரன் செங்குட்டுவன்`.

If a fresh chat does not contain the Gemini first-pass segment for scan 32 and no durable baseline exists in the repository, ask only for that relevant segment rather than reconstructing it from memory.

## Permanent safeguards

- scan controls; PDF remains external;
- Gemini is a baseline, not authority to invent text;
- uncertain old glyphs are not modernized by expectation;
- user-rejected assistant corrections stay withdrawn absent new unambiguous source evidence;
- English witnesses are secondary only;
- scene assembly occurs only after all pages of that scene are verified;
- translation is later and must derive from verified Tamil;
- `அந்தணர்` is not automatically “Brahmin” in future translation work.
