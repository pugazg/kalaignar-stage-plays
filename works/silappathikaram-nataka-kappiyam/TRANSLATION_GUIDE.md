# English Translation Protocol — சிலப்பதிகாரம் நாடகக் காப்பியம்

This protocol governs the English translation of the verified Tamil archival edition in this repository.

## 1. Translation authority

Translate from the **verified assembled Tamil scene files** in `scenes/`.

Source hierarchy:

1. `scenes/NN.md` — immediate translation source;
2. contributing verified `pages/NNNN.md` and the controlling Tamil scan — for any Tamil-reading, punctuation, stage-direction or provenance question;
3. the published English edition, if later supplied — secondary comparison witness only.

Never revise the Tamil archive to make the English easier or to match another English edition.

## 2. Primary objective: retain Kalaignar's language

The English must sound like a dramatic translation of **Kalaignar**, not generic contemporary prose.

Preserve wherever English permits:

- oratorical cadence;
- political and literary force;
- direct address and vocatives;
- repetition and anaphora;
- rhetorical questions;
- sharp contrasts and antitheses;
- slogans and public-proclamation rhythms;
- metaphor, allusion and compressed imagery;
- wit, sarcasm and polemical bite;
- emotional escalation;
- stage timing, pauses and abrupt turns;
- deliberate lexical or grammatical roughness when it carries voice.

Do not smooth repeated words merely because English style manuals would avoid repetition. Do not turn public rhetoric into neutral explanatory prose.

## 3. Fidelity versus literalism

Fidelity means preserving meaning, dramatic function, rhetoric and register — not reproducing Tamil word order mechanically.

A translation may rearrange syntax when necessary for intelligible English, but it must not:

- add motives, explanations or political claims absent from the Tamil;
- delete repetitions or emphatic parallel structures;
- euphemize polemical wording;
- modernize historical-cultural terms into misleading present-day equivalents;
- replace Tamilakam-specific imagery with generic equivalents;
- silently resolve ambiguity that the Tamil leaves open.

When a source form is intentionally unusual, prefer a slightly marked English construction over a falsely smooth one.

## 4. Stage-play conventions

- Preserve scene titles and printed setting/internal headings.
- Preserve speaker identity and dramatic order.
- Translate stage directions as stage directions; do not absorb them into narrative prose.
- Keep source-visible repetitions, pauses, cries, exclamations and rhetorical punctuation dramatically perceptible.
- Exact Tamil ellipsis counts need not be mechanically duplicated when English typography would become unreadable, but the **degree and timing of the pause** must be retained. Where an unusual punctuation sequence is itself archival evidence, record it in the review note.
- Do not translate illustrations, stamps, page numbers or later handwriting as dramatic text.

## 5. Tamil political-cultural vocabulary

Do not flatten culturally or politically loaded Tamil terms into convenient generic English.

The terminology register in `TRANSLATION_TERMINOLOGY.md` is mandatory. If a recurring term is not yet settled, record it there before scaling the translation.

Permanent lock:

- `அந்தணர்` is **not automatically “Brahmin.”**
- Keep distinctions among `பிராமண`, `பார்ப்பன`, `அந்தணர்`, `மறையவன்`, and related terms.

Similarly, `தமிழகம்` should normally remain **Tamilakam**, not be silently converted to “Tamil Nadu,” unless the source context unmistakably calls for a modern administrative sense.

## 6. Dravidian movement conceptual relation

Kalaignar's modern dramatic language often places ancient Tamil literary material in a rhetorical world that can resonate with themes central to the Dravidian movement. The translation must preserve that resonance **without inserting ideology that the source does not state**.

Translation choices should therefore remain alert to source-supported themes such as:

- Tamil linguistic and cultural self-respect;
- Tamilakam as a historical/civilizational geography;
- dignity and self-respect (`சுயமரியாதை`) when the text invokes them;
- critique of birth hierarchy or caste when explicitly present;
- rationalism, argument against fatalism, or the assertion of human agency when present;
- social equality and justice when present;
- women's agency and moral authority when dramatized;
- resistance to domination or humiliation;
- public reason, justice and accountability;
- pride in Tamil literary, political and historical traditions.

### Critical separation rule

**Do not put interpretive Dravidian-movement terminology into a character's mouth unless the Tamil itself supports that wording.**

When a scene has a meaningful resonance, record it after the translation in a clearly separate section:

`## Dravidian movement resonance — interpretive note`

That note must:

- distinguish source text from interpretation;
- describe a resonance, not claim that an ancient character literally expresses a twentieth-century movement programme;
- explain how Kalaignar's wording, framing, repetition or historical emphasis creates the connection;
- avoid forcing every scene into an ideological template.

A scene with no defensible connection may state: `No separate movement-context note required for this scene.`

## 7. Names, places and dynastic terms

Use stable transliteration for proper names unless a familiar English form is clearly preferable and does not erase Tamil identity.

Default examples:

- `தமிழகம்` → `Tamilakam`
- `வஞ்சி` → `Vanchi`
- `சேரர்` → `Chera / the Cheras` according to grammar
- `செங்குட்டுவன்` → `Senguttuvan`
- `நெடுஞ் சேரலாதர்` → `Nedun Cheralathan`

Do not Anglicize names inconsistently from scene to scene.

## 8. Verse, slogans and elevated rhetoric

For songs, quoted verse, proclamations and highly patterned rhetoric:

- preserve lineation when lineation carries rhetorical force;
- preserve parallelism and repetition;
- prefer strong, speakable English over academic paraphrase;
- do not invent rhyme;
- do not reduce slogans to explanatory statements.

For slogans such as `வாழ்க தமிழ்! வெல்க தமிழகம்!`, the translation should remain slogan-like and performable.

## 9. Translation file structure

Each numbered English scene should use:

```yaml
---
scene: 1
title_ta: "..."
title_en: "..."
source_scene: "scenes/01.md"
source_scan_pages: [17]
status: "draft"
translation_review: "pending"
language: "en"
secondary_english_witness_used: false
---
```

Then:

1. translated scene;
2. `## Translation notes` for necessary lexical/rhetorical decisions;
3. `## Dravidian movement resonance — interpretive note` when justified.

After review passes, use:

- `status: "translation-reviewed"`
- `translation_review: "passed"`

## 10. Review gate for every scene

Before a translation becomes `translation-reviewed`, check line-by-line against the verified Tamil scene for:

- complete coverage — no omitted stage direction, speaker turn, repetition or slogan;
- semantic fidelity;
- speaker voice;
- Kalaignar's cadence and rhetorical escalation;
- imagery and historical references;
- culturally/politically loaded terminology;
- stage timing and performability;
- accidental addition of explanatory ideology;
- separation of interpretive Dravidian-movement notes from translated dialogue.

Any Tamil doubt returns to the verified page record and controlling scan. The English is never used to correct the Tamil.

## 11. Pilot rule

`காட்சி-1` is the translation pilot. Its convention must be reviewed and accepted before translation is scaled to later scenes or batches.

The pilot specifically tests:

- proclamation/slogan rhythm;
- translation of `தமிழகம்`, `செந்தமிழர்`, `முரசு`, `விற்கொடி`, and dynastic names;
- preservation of repetition (`கொட்டுவோம், கொட்டுவோம்`);
- translation of elevated geographic imagery (`இமிழ் கடல் வேலித் தமிழகம்`);
- separation of source translation from Dravidian-movement interpretive resonance.
