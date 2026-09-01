# `காட்சி 1` Assembly Fidelity Review — மணிமகுடம்

## Scope

Controlling source context: `TVA_BOK_0064143_மணி_மகுடம்.pdf`.

This audit tests assembled `scenes/01.md` against the already verified page records only:

- `pages/0014.md` — scan 14 / unnumbered first dramatic page;
- `pages/0015.md` — scan 15 / printed p.6;
- `pages/0016.md` — scan 16 / printed p.7;
- `pages/0017.md` — scan 17 / printed p.8;
- `pages/0018.md` — scan 18 / printed p.9;
- `pages/0019.md` — scan 19 / printed p.10.

All six page records are `verified`. Scene assembly therefore uses those records as the textual authority and does not reopen the completed page-level source gate.

## Scene result

| Scene | Verified page records | Physical scans | Printed pages | Result |
|---|---|---|---|---|
| `காட்சி 1` | `0014.md`–`0019.md` | 14–19 | unnumbered, 6–10 | **PASS** |

Assembled file: `scenes/01.md`.

## Assembly decisions

- Source heading `காட்சி 1` is retained.
- Opening and closing stage directions are retained.
- Only mechanical physical-page breaks are removed for readability.
- No wording, punctuation, speaker label, stage direction, repetition, ellipsis or source-specific form is silently regularized.
- Source speaker-label variants remain distinct, including `குள்ளன்:`, `குள்:`, `விளக்கடி மனிதன்:`, `வி.மனிதன்:`, `வி. மனிதன்:`, `பொன்னழகன்:`, `பொன்:`, `புதுமைப்பித்தன்:` and `புதுமை:`.
- Scan 14 has no visible printed page number; no number is inferred for it in assembly metadata.

## Mechanical page-break joins

| Physical boundary | Verified page-record evidence | Assembled reading | Decision |
|---|---|---|---|
| 14 → 15 | stage direction ends `அந்தப் பக்கம்` / next scan begins `வருகிறான்.` | `அந்தப் பக்கம் வருகிறான்.` | mechanical page break removed inside the same stage direction |
| 16 → 17 | `... ஜனங்கள் நாட்டை ஆள வேண்டும் என்று` / `பிரச்சாரம் செய்கிறது!` | `... ஜனங்கள் நாட்டை ஆள வேண்டும் என்று பிரச்சாரம் செய்கிறது!` | same `குள்:` utterance joined |
| 17 → 18 | `... இந்தப் பத்திரிகையை விற்கவும் எனக்கு மனம்` / `வரவில்லை.` | `... இந்தப் பத்திரிகையை விற்கவும் எனக்கு மனம் வரவில்லை.` | same `குள்:` utterance joined |
| 18 → 19 | `புதுமை:` utterance ends `... அவ்வளவுதான்!` / scan 19 begins unlabeled `பொன்னழகரே!` | one continuous `புதுமை:` utterance | repeated speaker label was not invented |

These joins remove only the physical scan interruption. The page provenance remains documented by `source_scan_pages`, `printed_pages`, this review, and the underlying verified page records.

## Page-record → scene coverage

| Scan | Printed page | Assembly coverage | Result |
|---:|---:|---|---|
| 14 | — | scene heading, opening stage direction, first dialogue sequence and open continuation | PASS |
| 15 | 6 | stage-direction continuation, moon/star exchange and newspaper handoff | PASS |
| 16 | 7 | spider-web analogy and மக்கள் மன்றம் discussion | PASS |
| 17 | 8 | political critique, மக்கள் தொண்டன் critique and open `குள்:` continuation | PASS |
| 18 | 9 | continuation, newspaper rejection, பொன்னழகன் encounter and open `புதுமை:` continuation | PASS |
| 19 | 10 | continuation, membership request, `கருப்பு ரோஜா` naming and closing exit direction | PASS |

## Source-form controls retained

The assembled scene specifically preserves page-record wording and forms such as:

- `நம்ப நாடகத்தை`;
- `நான் சொன்னதை யெல்லாம்`;
- `ஸ்ரீஜத் அரிஹரநாதன்`;
- `அந்த கட்டு மஸ்தான தோற்றமுள்ள மனிதன்`;
- `அரச குருவும்`;
- `மக்களை சந்தியில் நிறுத்தும்`;
- `ராஜாங்க விரோதியை`;
- `பிரியமாக்கும்?`;
- `ஒருவரை யொருவர்`.

No modern spelling or semantic repair has been introduced during assembly.

## Integrity checkpoint

- verified page records used: **6 / 6**;
- source-printed Scene 1 assembled: **1 / 1**;
- page-record → scene comparison: **PASS**;
- mechanical cross-page joins checked: **4 / 4**;
- unresolved assembly discrepancies: **0**;
- speaker labels added or regularized: **0**;
- assistant lexical substitutions introduced: **0**.

## Result

**PASS — `மணிமகுடம்` `காட்சி 1` assembly and page-record fidelity gate are complete.**

The next distinct scene-assembly activity is `காட்சி 2`, assembled only from the verified portions of scans **20–24** / printed pages **11–15**. Scan 24 also opens `காட்சி 3`; the Scene 2 assembly must stop at the source-visible `காட்சி 3` boundary and must not absorb Scene 3 text.
