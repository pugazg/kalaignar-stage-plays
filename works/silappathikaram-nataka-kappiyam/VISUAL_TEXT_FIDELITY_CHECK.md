# Visual Text Fidelity Check — சிலப்பதிகாரம் நாடகக் காப்பியம்

This protocol is a mandatory assembly-phase quality gate.

Its purpose is to ensure that a readable `scenes/NN.md` assembly still corresponds exactly to the **actual controlling Tamil scan**, not merely to the already-verified page record from which it was assembled.

## Source authority

For this check, use:

1. the actual controlling Tamil scan at native/enlarged resolution;
2. the verified contributing `pages/NNNN.md` record(s);
3. the newly assembled `scenes/NN.md` file.

The scan remains controlling authority. If the scene file and page record agree but the pixels prove them wrong, correct only the affected verified page after direct source-pixel proof and document the correction explicitly before updating the scene assembly.

Do not use OCR, another edition, remembered Silappathikaram wording or the published English translation to resolve a Tamil reading silently.

## Mandatory visual-text fidelity pass

Every assembled scene must receive a direct scan-to-scene comparison before it can become `assembly-reviewed`.

Check all source-supported textual layers that belong to the scene:

- scene number;
- decorative lexical scene title;
- explicit setting and internal/sub-setting headings;
- speaker labels and abbreviations;
- dialogue wording;
- stage directions and their brackets/parentheses;
- punctuation, ellipses, quotation marks, dashes and unusual closing marks;
- repetitions;
- names and numbers;
- unusual/historical grammar or spelling;
- source-significant spacing;
- cross-column and cross-page continuation behaviour;
- printed textual separators such as `★` or `*` when they belong to the publication text;
- printed captions associated with visual material.

## Mechanical joins

Scene assembly may remove only **mechanical** line, column or page wrapping.

During the visual check, verify every join against the scan:

- no source character was dropped;
- no character was duplicated;
- no hyphen/dash was invented or deleted;
- no repeated word or phrase was collapsed;
- no punctuation was moved or regularized;
- no physical break was joined when the split itself carries source meaning;
- no editorial word spacing was introduced where the source-supported form must remain distinct.

For multi-scan scenes, inspect both sides of every physical page boundary directly.

## Visual / non-literary layer separation

Confirm directly from the scan that:

- decorative artwork has not been converted into invented lexical text;
- illustrations and photographs are not mixed into dialogue;
- printed captions are preserved verbatim when present;
- uncaptioned images remain neutrally described rather than identified by inference;
- printed pagination is not inserted into literary text;
- library stamps, accession numbers, handwriting, stains, damage and bleed-through remain outside Kalaignar's publication text.

Known permanent example: scan 88's library stamp obscures leading characters in two closing-tableau lines. Those characters must remain explicitly unresolved unless new source evidence defensibly recovers them.

## Fidelity result

Use this result vocabulary in scene front matter or review notes:

- `visual_text_fidelity: pending`
- `visual_text_fidelity: passed`
- `visual_text_fidelity: failed`

A scene may move to `status: "assembly-reviewed"` only when:

1. it has been compared against all contributing verified page records; and
2. `visual_text_fidelity: passed` has been established by direct inspection of the actual scan pixels.

If the visual pass fails, keep the scene at `draft`, document the mismatch, determine whether the error belongs to assembly or to a verified page record, and correct only with source-pixel evidence.

## Pilot requirement — காட்சி-1

The next activity must apply this protocol to **காட்சி-1 / scan 17** immediately after creating `scenes/01.md`.

For the pilot specifically:

- inspect scan 17 at native/enlarged resolution;
- compare the complete assembled scene character-by-character against the visible source text;
- reconfirm `காட்சி-1` and `வஞ்சி மூதூரில் முரசறைதல்` from the pixels;
- confirm there is no separate printed setting heading;
- verify the complete opening stage direction, speaker labels, dialogue, punctuation and all mechanical line joins;
- verify that the architectural/drummer scene-title artwork remains a separate visual layer;
- compare the assembled text also against `pages/0017.md`;
- record `visual_text_fidelity: passed` only after both comparisons succeed.

Do not proceed to `காட்சி-2` until the scene-1 pilot passes this direct visual-text fidelity gate and the reusable assembly format is accepted.

## Translation lock

This is a Tamil archival fidelity check, not translation. English translation remains locked during scene assembly and fidelity review.
