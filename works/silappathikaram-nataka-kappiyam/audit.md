# Tamil Transcription Completion Audit — சிலப்பதிகாரம் நாடகக் காப்பியம்

Audit scope: repository state after completion of direct page-level verification for the supplied 88-scan Tamil source.

## Result

**PASS — Tamil page-level transcription is complete for the supplied source and the work is ready to enter scene assembly.**

This result means:

- the supplied source contains **88 physical scans**;
- the repository tree contains a continuous page-record sequence `pages/0001.md` through `pages/0088.md` with no missing page filename;
- `indexes/page-map.md` marks scans **1–88** as `verified`;
- detailed dramatic-body verification covers **காட்சி-1 through காட்சி-38**;
- the post-scene closing tableau on scan 88 has also been archived;
- there is no remaining scene/page intentionally tracked as `needs-review`, `partial`, `blocked`, or `not-started` in the final page map;
- the source PDF remains outside the repository;
- scene assembly has not yet begun.

The Git tree used for this audit is non-truncated and contains all page files `0001.md`–`0088.md`. Historical batch review and live page records agree that the earlier structural-review states have been superseded by verified page records.

## Controlling source

`metadata/source.md` records:

- source filename: `TVA_BOK_0016473_சிலப்பதிகாரம்_நாடகக்_காப்பியம்.pdf`;
- SHA-256: `2886c8eaa9d79239eba3e9ed0ddefc4c7208da4761384ee7a8b4176e6b1a24dd`;
- file size: `49,459,844` bytes;
- scan count: **88**;
- source PDF committed to repository: **No**.

The supplied Tamil scan remains controlling authority. No scene assembly may silently modernize, correct, normalize, reconstruct, repunctuate or otherwise improve the verified page text.

## Page-record completeness

Repository tree check:

- first page record: `pages/0001.md`;
- final page record: `pages/0088.md`;
- continuous numeric sequence: **yes**;
- expected count: **88**;
- records present: **88**;
- gap detected: **none**.

Status reconciliation:

- `indexes/page-map.md` final checkpoint: scans **1–88 verified**;
- `BATCH_0010_0039_REVIEW.md`: scans 10–39 closed as verified, with scene 10 subsequently completed through its associated scan-41 pictorial page;
- scans 40–88 have verified page records in the live archive;
- no active page-map row remains non-final.

This audit is a repository-completion/readiness audit. It does not repeat the already completed 88 direct source-pixel verification passes.

## Dramatic scene extent manifest

The following manifest is the controlling assembly map. A range includes all physical scans associated with the numbered scene; visual-only source layers remain associated with the scene even when they are not literary text.

| Scene | Physical scan extent | Verified decorative title | Verified setting / structural note |
|---:|---|---|---|
| 1 | 17 | `வஞ்சி மூதூரில் முரசறைதல்` | no separate setting heading; opening direction locates வஞ்சி மூதூர் |
| 2 | 18 | `செங்குட்டுவன் பிறந்தநாள் விழா` | `வஞ்சி` |
| 3 | 19–20 | `விழாவும் வினாவும்` | `சேரன் அரண்மனை` |
| 4 | 21–23 | `இளங்கோ துறவு` | `சேரலாதன் மாளிகை` |
| 5 | 24–25 | `சிலம்பின் தோற்றம்` | `சேரநாடு` |
| 6 | 26–28 | `பூம்புகார்ப் பொற்றொடி` | no separate setting heading |
| 7 | 29–32 | `கலைக்கரசி மாதவி` | `முத்துப் பந்தல்` |
| 8 | 33–35 | `கண்ணகி இல்லறம்` | `கோவலன் வீடு:—பள்ளியறை` |
| 9 | 36–38 | `பிரிவினை தந்த பேதை` | `கண்ணகி.கோவலன்—கட்டில் அறை` |
| 10 | 39–41 | `கலையரசி கண்ட உவகை` | `மாதவி இல்லம்`; literary text closes on scan 40; scan 41 is an associated pictorial page |
| 11 | 42 | `கற்பரசியின் கலக்கம்` | `கண்ணகி வீடு` |
| 12 | 43 | `இன்ப வாழ்வில் கோவலன்` | `மாதவி வீடு` |
| 13 | 44–45 | `துன்பப் புயலில் கண்ணகி` | `கண்ணகி வீடு` |
| 14 | 46–48 | `மாதவியின் மாண்பு` | `காவிரி ஆற்றோரம்` |
| 15 | 49 | `மனமாறிந்த கோவலன்` | `கண்ணகி வீடு` |
| 16 | 50 | `மணிமேகலை பிறப்பு` | `மாதவி வீடு` |
| 17 | 51–52 | `மாசறு பொன்மகிழ்வு` | `கண்ணகி வீடு` |
| 18 | 53–54 | `இந்திர விழா-இருமனைகளில்` | no separate setting heading; source states `[பல உட்காட்சிகள் அடங்கியது]` |
| 19 | 55–58 | `கானல் வரியும் / காதல் பிரிவும்` | `புகார்` |
| 20 | 59–60 | `திருந்திய கோவலன் / திரும்பி வருதல்` | `கண்ணகி வீடு` |
| 21 | 61–62 | `கலைமகள்` | `மாதவி வீடு`; eye-and-tears artwork is a separate title layer |
| 22 | 63–64 | `மதுரைப் பயணம்` | `மதுரை செல்லும் வழி` |
| 23 | 65 | `மாதவி துறவு` | `மாசாத்துவான் வீடு` |
| 24 | 66 | `கவுந்தியுடன் கண்ணகி கோவலன்` | `வழியில்` |
| 25 | 67–68 | `நீதி வழுவா நெடுஞ்செழியன்` | `பாண்டியன் அவை` |
| 26 | 69 | `அரசியின் சிலம்பு` | `பொற்கொல்லன் வீடு` |
| 27 | 70 | `ஆய்ச்சியர் அறிமுகம்` | `மதுரை எல்லை`; internal location shift `மாதரி வீடு...` |
| 28 | 71 | `பொற்கொல்லர் முறையீடு` | `பாண்டியன் தனிமாடம்` |
| 29 | 72–75 | `ஒற்றைச் சிலம்பின் ஒலி` | `மாதரி வீடு` |
| 30 | 76 | `சிலம்போ சிலம்பு` | `பொற்கொல்லர் நிலையம்`; internal heading `சாலை` |
| 31 | 77 | `வளைந்தது செங்கோல்` | `நெடுஞ்செழியன் பள்ளியறை`; internal heading `தாழ்வாரம்` |
| 32 | 78–79 | `மதுரை மண்ணில் கோவலன் குருதி` | `வீதியிலுள்ள மண்டபம்` |
| 33 | 80 | `கணவன் கள்வனா?` | `குரவைக் கூத்து` |
| 34 | 81 | `வஞ்சினங் கூறுதல்` | `வீதியிலுள்ள மண்டபம்` |
| 35 | 82–85 | `வழக்குரை படலம்` | `பாண்டியன் கொலு மண்டபம் (வெளியே)` |
| 36 | 86 | `தீயினில் திருநகர்` | `தெருக்கள்` |
| 37 | 87 | `வடபுலப் படையெடுப்பு` | `சேரன் செங்குட்டுவன் அவை` |
| 38 | 88 | `கண்ணகி சிலைக்குக் கல்` | `இமயத்தில் - குயிலாலுவம்` |

After scene 38 closes on scan 88, a separate post-scene closing tableau follows after three centred `*` separators:

- `வஞ்சிமூதூரில்`
- `கண்ணகி சிலை நாட்டு விழா`

That tableau is **not** a numbered scene and must not be silently folded into scene 38 during assembly.

## Source irregularities / protected evidence inventory

The following are assembly-critical source facts already documented in page records, the page map, metadata or historical review files. This list is a readiness inventory, not permission to alter the readings.

### Pagination

- Printed pagination is often absent; missing numbers remain `null` rather than inferred.
- Scan 25 visibly carries anomalous printed numeral `2`; preserve it.
- Scan 73 visibly carries anomalous printed numeral `8`; preserve it.
- Scan 81 shows a clear lower-left `9` followed by a damaged/indistinct mark; the complete page number is not recoverable and remains `null`.
- No page number is securely visible on final scan 88.

### Library/accession and handwritten layers

- Library/accession stamps and handwritten shelf/accession marks occur in the physical copy and remain outside Kalaignar's publication text.
- Scan 39 has a later circular library stamp overlapping the decorative scene-10 heading.
- Scan 88 has a large circular later library/accession stamp with handwritten `164596`, plus lower-margin handwriting.
- On scan 88 that stamp physically obscures the leading characters of two closing-tableau lines. The archive preserves explicit obstruction markers before source-visible suffixes `ங்குட்டுவன்` and `ங்கோவடிகள்`; hidden letters must not be reconstructed during assembly.

### Illustrations, photographs and captions

- Visual material remains a separate source layer and must not be converted into dialogue or stage text.
- Scan 30 preserves the printed caption wording `யானச்சின்னம்`.
- Scan 41 is a full-page uncaptioned pictorial/reproduction page associated with scene 10.
- Scene 21 uses lexical title `கலைமகள்` plus separate eye-and-tears artwork; scan 62's `தாழி` caption remains source text attached to the visual layer.
- Scan 73's anomalous pagination is independent of its literary transcription.
- Scan 75 carries an archaeological image/caption layer already verified in its page record.
- Scan 79 carries a large uncaptioned dramatic illustration.
- Scan 80 carries an uncaptioned decorative bird/peacock-like medallion illustration.
- Scan 83 carries a large uncaptioned dramatic illustration.
- Scan 84 preserves the photograph caption `“பூம்புகார்” அகழ்வாராய்ச்சியில் / கண்ட படகுத்துறை`.
- Scan 85 carries a small uncaptioned burst/fragment-like illustration.
- Scan 86 contains two lower photographic/reproduction images with no securely visible separate caption, and retains the printed `★` separator in the literary/source typography.
- Scan 88's mountain/stone scene-title artwork remains separate from lexical title text.

### Source-supported unusual readings

Many page records intentionally retain historical, authorial or typographical forms that may look irregular. Assembly must copy those readings from verified page records, not repair them. Examples include:

- scene 9: `ஊடல் என்றுல்`, `முடவனுயிருப்பேன்.`, `கொல்லாமற் கொல்லாதீர் கண்ணுளா!...`;
- scene 10: `அது வும்`, `மண்ணுளும்`, `கண்ணுளன்`, `கண்ணு!`;
- scene 15 title: `மனமாறிந்த கோவலன்`;
- scene 29: scan-73 numeral `8`;
- scene 34: `இதற்குத்தானு;`, `மதுரை மூதார்`, repeated `பழிக்குப்பழி!`;
- scene 35: `கணவனு`, `அறிந்திடுக!.`, `மாணிக்கமிழைத்த`, and the distinct quoted orders `“கொன்று வருக அவனை!”` / `“கொன்று வருக அவன்”`;
- scene 36: `கனலே கிளம்பு....!`, `விரும்பினர்கள்`;
- scene 37: `சோழனு பாண்டியனு`, `பகைவனுக`, `கிழித் தெறியப்படலாம்!`, `இகழ்ந்தார்கள்!....அன்ன`;
- scene 38: `காஷாய`, `ரிஷிகளைப்`, `பதினெட்டே நாழிகையில்`, `வில்லவா ;`, and the physical `கனக— / விஜயா` break.

These examples are reminders only; the page records remain the controlling transcription source for assembly.

## Assembly-readiness decision

**Ready for assembly.**

Conditions satisfied:

- complete supplied-source page coverage;
- all numbered scenes mapped and verified;
- scene boundaries known;
- front matter and non-dramatic source layers preserved separately;
- known pagination anomalies documented;
- known visual/caption layers documented;
- scan-88 obstruction explicitly represented without fabrication;
- translation remains a separate later phase.

Conditions not yet satisfied:

- no `scenes/` assembly files exist yet;
- no assembly-level cross-page join review has been performed;
- no global consistency review has been performed;
- no English translation has begun.

## Next activity

Begin **scene assembly with காட்சி-1 / scan 17 as a pilot** using `SCENE_ASSEMBLY_PLAN.md`.

The pilot must establish the final scene-file convention before scaling to scenes 2–38. It must be assembled only from the verified page record, preserve the source wording and stage structure, and keep visual-title artwork separate from literary text.
