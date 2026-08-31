# Controlling Tamil source — சாக்ரடீஸ்

- Source: `TVA_BOK_0065576_நான்மணி_மாலை.pdf`
- Composite source registry: `../../../sources/naanmani-malai-tamil/`
- SHA-256: `18d2b1405544b03507e9f92067d287cb28f5a92eaf02bed7054e6e78e5e38c89`
- Work scan range: **27–43**
- Printed pages: **22–38**
- Introductory note scans **27–28**: **2/2 verified**
- `காட்சி—1` scans **29–31**: **3/3 verified; assembly/fidelity PASS**
- `காட்சி—2` scan **32**: **1/1 verified after user-directed lexical rollback; assembly/fidelity PASS**
- `காட்சி—3` scan **33**: **1/1 verified; assembly/fidelity PASS**
- `காட்சி—4` scans **34–39**: **1/6 verified (scan 34 / p.29)**
- Total Tamil page-level verification: **8/17**
- Dramatic-body page verification: **6/15**
- Numbered dramatic scenes: **5**
- Scene assembly completed: **3/5**
- `காட்சி—1` assembly/fidelity: **PASS** (`../scenes/01.md`; `../ASSEMBLY_FIDELITY_REVIEW.md`)
- `காட்சி—2` corrected page gate: **PASS** (`../pages/0032.md`; `../SCENE2_PAGE_VERIFICATION.md`)
- `காட்சி—2` assembly/fidelity: **PASS** (`../scenes/02.md`; `../SCENE2_ASSEMBLY_FIDELITY_REVIEW.md`)
- `காட்சி—3` page gate: **PASS** (`../pages/0033.md`; `../SCENE3_PAGE_VERIFICATION.md`)
- `காட்சி—3` assembly/fidelity: **PASS** (`../scenes/03.md`; `../SCENE3_ASSEMBLY_FIDELITY_REVIEW.md`)
- `காட்சி—4` page gate: **1/6 PASS** (`../pages/0034.md`; `../SCENE4_PAGE_VERIFICATION.md`)

## Active user-directed transcription rule

For continuing `சாக்ரடீஸ்` work:

- lexical **words are retained from the user-supplied Gemini transcription**;
- the controlling scan is used to verify **headings, punctuation, long dash, speaker-label spacing, physical line boundaries and final source marks**;
- assistant word-level substitutions based on visual interpretation, grammar, spelling familiarity or semantic expectation are not permitted unless the user explicitly requests a word-level recheck.

On scan 32, the withdrawn assistant readings `கவிஞனும் மெலிடசும்` and `அரசியல் நிபுணனும் நீயும்` remain restored to Gemini's `கவிஞனாம் மெலிடசும்` and `அரசியல் நிபுணனாம் நீயும்`; assembled `scenes/02.md` preserves them.

On scan 33, Gemini supplies lexical wording. The scan controls `காட்சி—3.`, punctuation, speaker-label spacing, the long dash in `அறிவுத் தங்கத்தை — விடு`, physical line evidence and source marks; assembled `scenes/03.md` preserves them.

On scan 34, Gemini supplies lexical wording. The scan controls the source heading `காட்சி — 4`, punctuation, long dashes, speaker-label spacing and physical line evidence. Scan 34 has no scene-closing `*`.

Next activity: verify `காட்சி—4` scan **35** / printed p.30 only under the same Gemini-words / scan-typography rule. Do not process scan 36 or assemble Scene 4 in the same activity.
