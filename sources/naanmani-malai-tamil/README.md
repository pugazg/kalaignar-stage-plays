# கலைஞரின் நான்மணி மாலை — controlling Tamil source

Source: `TVA_BOK_0065576_நான்மணி_மாலை.pdf` — **54 scans** — SHA-256 `18d2b1405544b03507e9f92067d287cb28f5a92eaf02bed7054e6e78e5e38c89`.

The scan is controlling. The Gemini first pass is a working comparison layer. For ambiguous old Tamil glyphs, do not override a plausible Gemini reading merely because another spelling looks more familiar; change it only when the scan is unambiguous.

## Current work state

- `பரதாயணம்` scans 6–17: Tamil archival/assembly PASS; independent English translation PASS.
- `அனார்கலி` scans 18–26: Tamil archival/assembly PASS.
- `சாக்ரடீஸ்` scans 27–43: scans **27–31 = 5/17 total pages verified** — intro 2/2 plus `காட்சி—1` source pages 3/3; Scene-1 assembly pending.
- `சேரன் செங்குட்டுவன்` scans 44–53: pending Tamil verification.

For `சாக்ரடீஸ்`, the intro rollback/reconciliation is at `../../works/socrates/INTRO_RECONCILIATION.md`; the **final Gemini/source-reconciled** Scene-1 page gate is at `../../works/socrates/SCENE1_PAGE_VERIFICATION.md`.

The Scene-1 gate was re-opened after the user supplied the original Gemini first-pass. Final retained controls include `காணா`, `புலிநிகர்`, `மின்னலப்பா`, `இந்தக் கிண்ணாரக் கிழவருக்கு`, `கஷ்டப்பட`, `நட்டாற்றில்`, `ஏண்டி`, `சுடுகாடு`, and `உயிரினுமினியவர்`.

Next source-sequential activity: assemble **`சாக்ரடீஸ்` `காட்சி—1`** exclusively from final verified `pages/0029.md`–`0031.md` and run its fidelity audit. Do not begin scan 32 / `காட்சி—2` in that same activity.
