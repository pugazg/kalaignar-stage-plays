# கலைஞரின் நான்மணி மாலை — controlling Tamil source

Source: `TVA_BOK_0065576_நான்மணி_மாலை.pdf` — **54 scans** — SHA-256 `18d2b1405544b03507e9f92067d287cb28f5a92eaf02bed7054e6e78e5e38c89`.

The scan is controlling. The Gemini first pass is a working comparison layer. For ambiguous old Tamil glyphs, do not override a plausible Gemini reading merely because another spelling looks more familiar; change it only when the scan is unambiguous.

## Current work state

- `பரதாயணம்` scans 6–17: Tamil archival/assembly PASS; independent English translation PASS.
- `அனார்கலி` scans 18–26: Tamil archival/assembly PASS.
- `சாக்ரடீஸ்` scans 27–43: scans **27–32 = 6/17 total pages verified** — intro 2/2, `காட்சி—1` pages 3/3 + assembly/fidelity PASS, `காட்சி—2` scan 32 page gate PASS; scenes assembled **1/5**.
- `சேரன் செங்குட்டுவன்` scans 44–53: pending Tamil verification.

For `சாக்ரடீஸ்`, the intro reconciliation is at `../../works/socrates/INTRO_RECONCILIATION.md`; Scene-1 page gate is at `../../works/socrates/SCENE1_PAGE_VERIFICATION.md`; Scene-1 assembly audit is at `../../works/socrates/ASSEMBLY_FIDELITY_REVIEW.md`; Scene-2 page gate is at `../../works/socrates/SCENE2_PAGE_VERIFICATION.md`.

On scan 32, direct source inspection proves `கவிஞனும் மெலிடசும்` and `அரசியல் நிபுணனும் நீயும்` against the flattened Gemini `...னாம்` readings; source punctuation and label spacing are preserved in `pages/0032.md`.

Next source-sequential activity: assemble **`சாக்ரடீஸ்` `காட்சி—2`** exclusively from verified `pages/0032.md` and run its fidelity audit. Do not begin scan 33 / `காட்சி—3` in that same activity.
