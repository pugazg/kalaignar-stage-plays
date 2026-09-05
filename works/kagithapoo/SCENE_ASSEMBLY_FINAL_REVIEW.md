# காகிதப்பூ — Final scene-assembly consistency review

Status: **PASS — SCENE ASSEMBLY COMPLETE / CLOSED**

Scope: assembled dramatic reading layer derived only from the already verified page records for selected source scans **92–131** within the closed 91–131 work range.

Controlling source: `TVA_PRL_0001638_முரசொலி_ பொங்கல் மலர்_ 1967.pdf`

Primary lexical witness: `kaagidha_poo.md`

Page-layer authority: `PAGE_LAYER_CONSISTENCY_AUDIT.md` — **PASS, 41 / 41 verified**.

## 1. Assembly artifact coverage — PASS

The `scenes/` directory now contains **23 assembly artifacts** representing the full source-visible dramatic sequence:

- `01.md`;
- `02-05.md` — source-compressed `காட்சிகள்: 2, 3, 4, 5.` block;
- `06.md` through `21.md`;
- `unnumbered-between-21-and-24.md` — source heading `காட்சி,` exactly as printed;
- `24.md`;
- `25.md`;
- `26.md`;
- `27.md`.

No `22.md` or `23.md` exists or is implied.

## 2. Source numbering / compression — PASS

- Scene 1 is represented normally.
- Source-compressed Scenes 2–5 remain compressed exactly to the printed collective representation; no missing bodies were invented.
- Scenes 6–21 are represented in source order.
- Scan 124's anomalous heading remains exactly `காட்சி,` with no numeral.
- Scan 125 resumes with source-visible `காட்சி 24.`.
- Scene 25 remains a source-compressed bracketed campaign-action scene only; no dialogue was invented.
- Scenes 26 and 27 follow the source sequence unchanged.

## 3. Page provenance — PASS

Every scene artifact records its controlling `source_scan_pages` and declares:

- `status: "assembly-reviewed"`;
- `assembled_from_verified_pages: true`;
- `page_record_fidelity: "passed"`.

Assembly uses the verified `pages/*.md` layer rather than re-transcribing or silently replacing it.

## 4. Mechanical joins — PASS

Only positively established physical-page joins were collapsed in the assembled reading layer. Recorded examples include:

- Scene 12: `ஒப்ப—` / `டைக்கிறதா` → `ஒப்படைக்கிறதா`;
- Scene 14: `வெற்றிகளக் குவிக்கத்—` / `தான் போகிறார்கள் மக்கள்!...` → `வெற்றிகளக் குவிக்கத்தான் போகிறார்கள் மக்கள்!...`;
- Scene 15: `வார்த்தை—` / `யைச்` → `வார்த்தையைச்`;
- Scene 16: `இய—` / `லாது` → `இயலாது`;
- Scene 20: scan-118→119 sentence continuation joined without lexical rewriting;
- Scene 21: `நலத்—` / `திட்ட` → `நலத்திட்ட`, and `ஆட்சி—` / `மொழிகளாகட்டும்` → `ஆட்சிமொழிகளாகட்டும்`;
- Scene 24: `முடி` / `யாம` → `முடியாம`, and `கொள்` / `ளுங்கள்` → `கொள்ளுங்கள்`.

No join was made where a page boundary fell between complete turns, including Scene 26 and Scene 27's 130→131 boundary.

## 5. Lexical / structural fidelity — PASS

- Verified lexical wording was not modernized or silently corrected.
- Verified unusual spellings/tokens remain unchanged.
- Speaker-label variation was preserved rather than normalized.
- Stage-direction punctuation and brackets/parentheses follow the verified page records.
- Scene headings and scene numbering were not editorially repaired.
- No global replacement was used to normalize source wording.

## 6. User-authorized PDF lexical fallback — PASS

Direct PDF lexical fallback remains limited to the five previously adjudicated MD omissions on scans **93, 95, 97, 98 and 130**.

Scene 27 retains the three already verified scan-130 fallback turns exactly:

- `குரல்:— அப்படியா?...ஹ ஹ ஹ...!`;
- `குரல்:— ஹ ஹ ஹ!...`;
- `கண்:— அம்மா!...`.

No new PDF lexical fallback was introduced during scene assembly.

## 7. Non-dramatic physical material — PASS

The assembled dramatic reading layer does not absorb separate page-level physical features:

- scan 98 photograph caption `ஓ. எம். சுப்பிரமணியன்,` remains outside dramatic Scene 8 flow;
- scan 130 boxed `கண்டுபிடியுங்கள்` remains outside Scene 27 dramatic reading order;
- scan 131 `நாடகத்தில்—பங்கேற்பவர்கள்!` cast block remains outside Scene 27;
- scan 131 publication/imprint and deputy-editor lines remain page-level closure material rather than dramatic dialogue.

## 8. Final-scene closure — PASS

`scenes/27.md` assembles verified scans **130–131** and closes at the source marker:

`(முற்றும்)`

The cast block begins only after that dramatic closure and is not included in the scene file.

## 9. Final result

**SCENE ASSEMBLY COMPLETE / CLOSED.**

- page layer: **41 / 41 verified — CLOSED**;
- scene assembly artifacts: **23 / 23 expected source-representation artifacts present**;
- unresolved assembly gaps: **0**;
- invented scene numbers: **0**;
- invented source-compressed dialogue: **0**;
- unreviewed scene artifacts: **0**;
- final scene closure: **PASS at `(முற்றும்)`**;
- English translation: **not started / not authorized**.

No further Tamil page-level or scene-assembly work remains unless a later source-based correction reopens the verified layer. Any English translation phase requires separate authorization.