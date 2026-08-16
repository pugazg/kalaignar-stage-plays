# சிலப்பதிகாரம் — நாடகக் காப்பியம்

Archive slug: `silappathikaram-nataka-kappiyam`

The supplied scan is the controlling source. The PDF itself is not committed.

## Processing status

- Scan length: **88 pages**.
- Scans **1–88 are visually verified**.
- Detailed dramatic-body verification covers **காட்சி-1 through காட்சி-38**.
- The post-scene closing tableau on scan **88** has also been inspected and archived.
- Tamil page-level visual verification: **complete for the supplied source**.
- Repository-wide Tamil transcription completion audit: **complete / PASS** — see `audit.md`.
- Scene-assembly readiness plan: **complete** — see `SCENE_ASSEMBLY_PLAN.md`.
- Visual text fidelity protocol: **defined and mandatory for every assembled scene** — see `VISUAL_TEXT_FIDELITY_CHECK.md`.
- Scene assembly: **not yet started**.
- English translation: **not started** and remains locked through assembly/global Tamil review unless the user explicitly changes phase.

## Audit result

The completion audit confirms:

- a continuous repository page-record sequence `pages/0001.md` through `pages/0088.md`;
- all physical scans represented;
- the live page map at final `verified` state for scans 1–88;
- verified scene extents for `காட்சி-1` through `காட்சி-38`;
- known pagination anomalies, image/caption layers and library/accession obstructions documented;
- no scene-assembly files yet exist, so no assembled text can accidentally supersede the page archive.

The assembly manifest and rules are recorded in `SCENE_ASSEMBLY_PLAN.md`. Scene assembly will create `scenes/01.md` through `scenes/38.md`, plus a separate `scenes/closing-tableau.md` for the post-scene scan-88 material.

## Visual text fidelity rule

Scene assembly creates a new derivative text layer and therefore receives a second direct source-pixel check.

After each `scenes/NN.md` draft is assembled from verified page records, compare the complete assembled Tamil directly against the actual contributing scan(s), following `VISUAL_TEXT_FIDELITY_CHECK.md`.

A scene cannot become `assembly-reviewed` until:

- every source-supported character/textual layer has been rechecked against the scan;
- every mechanical line/column/page join has been verified not to omit, duplicate or normalize text;
- visual/non-literary layers remain separated correctly; and
- `visual_text_fidelity: "passed"` is recorded.

## Final verified scene — காட்சி-38

`காட்சி-38` is physically a **one-scan scene on scan 88**, which is also the final supplied physical scan.

- Decorative title verified as **`கண்ணகி சிலைக்குக் கல்`**.
- Setting verified as **`இமயத்தில் - குயிலாலுவம்`**.
- Complete source-visible two-column dramatic text verified directly against native/enlarged controlling-source views and targeted crops.
- No printed page number is securely visible; none is inferred.
- The left column ends mid-speech with `இதற்குப் பதில்`; the right column continues `சொல்லுங்கள்!`.
- Source-supported readings/punctuation retained without normalization include `காஷாய`, `ரிஷிகளைப்`, `உரிய / தான`, `மகானாய் மாறுவது!`, `வட நாட்டிலே நடத்தியபோர்`, `பதினெட்டே நாழிகையில்`, `அது உங்களை மன்னிக்கட்டும்.`, `முப்பத்திரண்டு`, `வில்லவா ;`, and the physical `கனக— / விஜயா` split.
- Final targeted source-pixel reinspection established `நடைபெற்ற` in the opening direction and `அது உங்களை மன்னிக்கட்டும்.` in the king's speech; these replace the earlier provisional misreads `நடைபெறுகிற` / `உங்களே`.
- Decorative mountain/stone title artwork is recorded separately from literary text.

## Same-scan closing tableau

After scene 38 closes, three centred printed `*` marks introduce a distinct post-scene tableau:

- `வஞ்சிமூதூரில்`
- `கண்ணகி சிலை நாட்டு விழா`

The source-visible tableau text is archived in `pages/0088.md`. A large later circular library/accession stamp overlaps the leading characters of two lines and contains handwritten `164596`; additional later handwriting is present near the lower margin.

Non-destructive enlarged/contrast/gamma inspection could not securely recover the characters directly beneath the opaque stamp. `pages/0088.md` therefore marks the obscured positions explicitly before the source-visible suffixes `ங்குட்டுவன்` and `ங்கோவடிகள்`; the hidden letters are **not silently reconstructed**.

The visible closing tableau ends with:

`மாதவி, துறவுக் கோலத்தில், கண்களில் நீர்வழிய, குழந்தை`

`மணிமேகலையைக் கொண்டுவந்து சிலையின் காலடியில் வைக்கிறாள்.]`

## Translation terminology lock

Kalaignar's `அந்தணர்` must **not** be automatically equated with or translated as “Brahmin.” Preserve distinctions among `பிராமண`, `பார்ப்பன`, `அந்தணர்`, and other source terms such as `மறையவன்`; English renderings will be decided only during dedicated terminology review.

When translation eventually begins, it must be based on the verified Tamil archival text and retain Kalaignar's rhetoric, cadence, repetition and dramatic voice. The published English volume remains only a secondary comparison witness.

## Assembly rule

Assembly is a new derivative archival layer. Verified page records remain controlling for construction, and the actual scan remains controlling for the mandatory visual-text fidelity gate.

Mechanical line/column/page wrapping may be joined for readability only where it does not alter source wording or punctuation. Repetition, unusual spacing/punctuation, stage directions and genuine source anomalies must remain. Visual material stays in separate source-layer notes. Every multi-scan scene must retain scan provenance.

## Exact next work

Process **காட்சி-1 / scan 17** as the combined **scene-assembly + visual-text fidelity pilot** using `SCENE_ASSEMBLY_PLAN.md` and `VISUAL_TEXT_FIDELITY_CHECK.md`.

The activity must:

1. create `scenes/01.md` from verified `pages/0017.md` at `draft` with `visual_text_fidelity: "pending"`;
2. preserve the verified title `வஞ்சி மூதூரில் முரசறைதல்` and use `setting: null` because no separate printed setting heading exists;
3. keep the decorative architectural/drummer title artwork separate from literary text;
4. inspect the actual scan 17 at native/enlarged resolution and compare the complete assembled scene character-by-character against the pixels;
5. verify every mechanical join, speaker label, stage direction, punctuation mark, repetition and source-significant spacing;
6. compare the assembled file against `pages/0017.md` after the visual pass;
7. set `visual_text_fidelity: "passed"` and `status: "assembly-reviewed"` only if both the direct scan comparison and page-record comparison pass;
8. do not begin scene 2 until the pilot format and fidelity method are accepted.

Do not begin English translation.
