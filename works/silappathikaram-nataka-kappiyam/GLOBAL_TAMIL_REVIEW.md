# Global Tamil Consistency / Source Review — சிலப்பதிகாரம் நாடகக் காப்பியம்

Review date: 2026-08-16

## Result

**PASS — the assembled Tamil corpus is structurally complete, internally consistent with the verified page archive, and ready to move to the separate English-translation phase.**

Scope reviewed:

- controlling source length: **88 scans**;
- verified page records: `pages/0001.md` through `pages/0088.md`;
- numbered scene outputs: `scenes/01.md` through `scenes/38.md`;
- separate post-scene output: `scenes/closing-tableau.md`;
- scene manifest and provenance rules in `SCENE_ASSEMBLY_PLAN.md`;
- direct-fidelity rules in `VISUAL_TEXT_FIDELITY_CHECK.md`;
- page-map, source anomaly records and prior per-scene fidelity notes.

This is a global consistency/source audit of the already completed page verification and per-scene direct visual-fidelity passes. It does not replace or weaken those source-pixel checks.

## 1. Corpus inventory and front-matter audit

All **38 numbered scene files** are present in continuous order, and the separate `closing-tableau.md` is present.

Every numbered scene has:

- the correct `scene` number;
- the verified decorative lexical title;
- the verified explicit setting, or `setting: null` where the source has no separate setting heading;
- the correct `source_scan_pages` extent from the assembly manifest;
- `status: "assembly-reviewed"`;
- `assembled_from_verified_pages: true`;
- `visual_text_fidelity: "passed"`;
- `language: "ta"`;
- the controlling source filename.

`closing-tableau.md` correctly uses `scene: null`, setting `வஞ்சிமூதூரில்`, title `கண்ணகி சிலை நாட்டு விழா`, source scan `[88]`, and the same completed assembly/fidelity statuses.

The scene-number/title/setting/scan mapping matches the 38-scene manifest. Special structural cases remain correct:

- scene 1: no separate printed setting heading;
- scene 6: no separate printed setting heading;
- scene 10: scans 39–41, with scan 41 retained as an associated pictorial-only physical page;
- scene 18: no separate setting heading; `[பல உட்காட்சிகள் அடங்கியது]` and its internal locations remain part of the scene;
- scene 27: initial `மதுரை எல்லை`, internal `மாதரி வீடு...`;
- scene 30: `பொற்கொல்லர் நிலையம்`, internal `சாலை`;
- scene 31: `நெடுஞ்செழியன் பள்ளியறை`, internal `தாழ்வாரம்`;
- scene 38 is confined to scan 88 and is followed by, but not merged with, the separate closing tableau.

## 2. Multi-scan provenance and mechanical-join audit

All multi-scan assembled scenes were re-read at repository level with their physical scan-boundary comments and per-scene fidelity records:

`03, 04, 05, 06, 07, 08, 09, 10, 13, 14, 17, 18, 19, 20, 21, 22, 25, 29, 32, 35`.

The source extents agree with the manifest, and the assembly continues to distinguish mechanical print wrapping from source-significant wording/spacing/punctuation.

Representative high-risk boundaries remain correctly protected:

- scene 3: scan 19 → 20 starts a new physical page without losing the preceding scene structure;
- scene 4: scan 22 → 23 preserves the separate farewell lines and the six-dot `வருகிறேன்......`;
- scene 5: scan 24 ends `கணவன் வருவான் வருவான்`; scan 25 continues `என்று கண் கலங்கக் கூறிக் கொண்டிருந்தாள்...` without an invented speaker label or punctuation;
- scene 7: scan 30 remains a pictorial/caption-only physical page between scans 29 and 31;
- scene 9: the scan-37 left-column speech continues below the photograph before reading proceeds to the upper-right column;
- scene 10: literary text closes on scan 40; scan 41 remains pictorial-only source provenance;
- scene 18: internal `மாதவி வீடு`, `கண்ணகி வீடு`, and later `கடற்கரை` structure remains within one numbered scene;
- scene 22: `என் பத்தினியின்` → `பாதம் பட்டுப்...` remains the same speech across scans 63–64;
- scene 29: scan 72 `கழற்றுமல்` → scan 73 `வீட்டு வைத்திருக்கும்...` remains source-faithful and unnormalized; scan 74 `கவலைப்படாமல்,` continues on scan 75 with the same Kannagi speech;
- scene 32: scan 78 `...நெடுஞ்செழியன் முன்னிலையில்` → scan 79 `நிற்கின்றேன்.` remains the same Kovalan speech;
- scene 35: all four scans 82–85 remain in order, with no lost or duplicated transition text.

No new accidental cross-page or cross-column wording/punctuation change was found during this global pass.

## 3. Regression audit of earlier pixel-proven corrections

Previously documented source-pixel corrections were checked for regression in the assembled corpus. The corrected readings remain intact, including:

- scene 2: `தனி மாடத்தை விட்டு`;
- scene 3: `என்றும்...அந்நாள்`, `உண்மைக் காது!...அவர்`, `கலங்காது!...`, `இதோ...நான்`, `வெல்லுகிறேன்...அண்ணனையே`, `பாரும்!...வருகிறேன்!...`, and source spacing `செங்குட்டுவனுக்குத் தான்`;
- scene 4: `தங்கப் போகிறேன்!`, six-dot `வருகிறேன்......`, and assembled `எண்ணியிருந்தால்....அப்பா`;
- scene 5: `செங்கு : கண்ணகி...!`;
- scene 6: `[சாத்தனரின் குரல் தொடர்கிறது]`, `வெண் மணல்`, and `தங்கமே...இந்தா... உனக்காகக்`;
- scene 8: `மகன்!...என்`;
- scene 9: `உனை மறந்தாலன்றோ` and `என்னை எடுத்துப்`;
- scene 10: `உண்மைதானே?..`;
- scene 33: `உச்சக் குரலில்`;
- scene 38: opening direction `நடைபெற்ற` and `அது உங்களை மன்னிக்கட்டும்.`.

No corrected reading has reverted to its earlier provisional form.

## 4. Speaker labels, stage directions and source punctuation

The global review found no evidence of systematic expansion or standardization of speaker labels. Full and abbreviated forms remain source-dependent rather than editorially harmonized.

Protected punctuation/stage-direction evidence remains represented, including:

- scene 5's source-visible gift-list ending `குவிக்கின்றனர்.]` without an invented opening bracket;
- scene 28's unmatched closing bracket in `கோப்பெருந்தேவி கேட்டுக்கொண்டே வருகிறாள்.]`;
- scene 31's unmatched opening bracket in `[என வேகமாகப் போகிறான்!`;
- scene 34's repeated but differently spaced column-transition wording `என்னை ஏமாற்றிவிட்டீர்களே` / `அத்தான், என்னை ஏமாற்றி விட்டீர்களே!`;
- scene 35's exact distinction `“கொன்று வருக அவனை!”` versus `“கொன்று வருக அவன்”`;
- scene 36's printed `★` separator;
- scene 37's four-dot `இகழ்ந்தார்கள்!....அன்ன` and final printed `புறப்படுங்கள்!’`;
- scene 38's physical left→right continuation `இதற்குப் பதில்` → `சொல்லுங்கள்!`, `வில்லவா ;`, and preserved em dash in assembled `கனக—விஜயா`;
- the three centred `*` marks separating scene 38 from the closing tableau.

No source anomaly was normalized merely because a more conventional form was available.

## 5. Visual, caption and pictorial-only source layers

Visual material remains separate from dramatic literary text throughout the assembled corpus. Checked protected examples include:

- scene 7 / scan 30: exact caption `“பூம்புகார்” அகழ்வாராய்ச்சியில் கிடைத்த / யானச்சின்னம் பொறிக்கப்பட்ட / கரிகாலன் காலத்துக் காசுகள்.`;
- scene 9 / scan 37: `(சம்பாபதி கோயில் — பூம்புகார்)`;
- scene 10 / scan 41: full-page pictorial/reproduction page with no literary text or caption;
- scene 17 / scan 51: `“பூம்புகார்” அகழ்வாராய்ச்சியில் / கிடைத்த பெளத்தப் பள்ளி`, with scan 52 retained as pictorial-only continuation;
- scene 21 / scan 62: `“மூலன் பேடு அந்தனன் உமண்”...... என்ற தமிழ் எழுத்துக்களின் அந்நாளைய வரிவடிவம், / பூம்புகார் அகழ்வாராய்ச்சியில் கிடைத்த தாழி`;
- scene 25 / scan 67: `“பூம்புகார்” அகழ்வாராய்ச்சி- / கி.மு. 3ஆம் நூற்றாண்டின் / படகு கட்டும் துறை.`;
- scene 29 / scan 75: `“பூம்புகார்” அகழ்வாராய்ச்சி— / கரிகாலன் காலத்துப் பொற்காசு / களும் அவற்றில் பொறித்துள்ள / சின்னங்களும்.`;
- scene 35 / scan 84: `“பூம்புகார்” அகழ்வாராய்ச்சியில் / கண்ட படகுத்துறை`;
- scene 36: two lower photographic/reproduction images remain uncaptioned rather than assigned identities;
- scenes 37–38: decorative title artwork remains visual-only.

The global review found no illustration description or caption improperly merged into dialogue.

## 6. Pagination and copy-specific anomalies

The assembled scene files continue to keep printed pagination as provenance rather than literary text.

Protected cases include:

- scan 25: anomalous printed `2` remains source evidence and is not normalized to the expected sequence;
- scan 73: anomalous printed `8` remains source evidence;
- scan 81: only a clear `9` plus a damaged/indistinct following mark is recoverable; the full page number remains unresolved and no `65` is inferred;
- absent page numbers remain absent rather than inferred from neighbours.

Later library/accession stamps and handwriting remain outside the literary layer.

## 7. Scan-88 obstruction review

The final scan was re-inspected directly during the final assembly activity and its state was rechecked in this global review.

The post-scene tableau remains structurally separate from scene 38. A later circular library/accession stamp containing handwritten `164596` physically obscures the leading characters of two printed tableau lines.

The assembled tableau therefore retains:

- `⟦later library stamp obscures leading letters⟧ங்குட்டுவன்`
- `⟦later library stamp obscures leading letters⟧ங்கோவடிகள்`

The hidden characters remain **unreconstructed**. Context, another edition, memory and the published English translation are not used to fill them.

## 8. Documentation consistency finding

One repository-documentation drift was found during this global review:

- `indexes/page-map.md` still ended with an obsolete `Next phase` instruction to begin the scene-1 assembly pilot, even though all 38 scenes and the closing tableau are now complete.

This is a documentation-state issue only; it does not affect verified Tamil text. The live page-map continuation note is being corrected as part of this review.

The earlier `audit.md` remains intentionally historical: its scope is the pre-assembly page-level completion/readiness checkpoint. It should be read together with this report for the current post-assembly state.

## 9. Corrections made by this global review

### Literary / source transcription

**None.**

No new Tamil page-record or scene-literary-text correction was required.

### Assembly text

**None.**

No new accidental assembly join, omission, duplication or punctuation change was found.

### Documentation

- advance `indexes/page-map.md` from its obsolete scene-1 pilot instruction to the completed assembly/global-review state;
- advance README and handover documents to record this global review PASS and the next separate translation phase.

## 10. Final Tamil archival checkpoint

The Tamil archival layer is now complete for the supplied source at the current project scope:

- **88/88 physical scans represented and page-level verified**;
- **38/38 numbered scenes assembled**;
- **38/38 numbered scenes direct visual-text fidelity passed**;
- **separate closing tableau assembled and direct visual-text fidelity passed**;
- **global Tamil consistency/source review: PASS**;
- **unresolved literary source text:** only the explicitly marked stamp-obscured leading characters on scan 88; these are source-obstructed, not pending guesses.

## 11. Translation gate

The Tamil-source lock has been satisfied. English translation may now begin as a **separate phase** based on the verified assembled Tamil corpus.

Translation must continue to obey:

- verified Tamil, not OCR, as the primary translation source;
- the controlling Tamil scan/page record whenever a Tamil reading is questioned;
- the published English volume only as a labelled secondary comparison witness;
- preservation of Kalaignar's rhetorical force, cadence, wit, repetition, dramatic timing and political/literary language;
- no retroactive change to Tamil merely to fit English wording;
- permanent terminology lock: `அந்தணர்` is not automatically “Brahmin”; preserve distinctions among `பிராமண`, `பார்ப்பன`, `அந்தணர்`, `மறையவன்` and related terms pending dedicated translation review.

## Exact next activity

Create the work-specific English translation protocol/terminology register and translation directory, then use **காட்சி-1** as the English translation pilot. The pilot must be translated from `scenes/01.md`, reviewed against the verified Tamil/source rhetoric, and accepted before scaling to later scene batches.
