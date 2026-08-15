# Kalaignar Stage Plays — Handover

## Repository

`pugazg/kalaignar-stage-plays` on `main`.

## Permanent rules

Read `STAGE_PLAY_PROCESSING_GUIDE.md` completely before continuing any work.

The supplied scan is the controlling source. Do not silently modernize, correct, normalize, reconstruct or improve the Tamil. OCR is assistive only. Source PDFs are not committed to the repository.

## Current work

**சிலப்பதிகாரம் — நாடகக் காப்பியம்**  
Path: `works/silappathikaram-nataka-kappiyam/`

Source:

`TVA_BOK_0016473_சிலப்பதிகாரம்_நாடகக்_காப்பியம்.pdf`

Source facts already recorded:

- 88 scan pages
- SHA-256 `2886c8eaa9d79239eba3e9ed0ddefc4c7208da4761384ee7a8b4176e6b1a24dd`
- 49,459,844 bytes
- scan 17 begins `காட்சி-1`
- scan 18 begins `காட்சி-2` and visibly carries printed page `2`
- scan 88 visibly carries `காட்சி-38`

## Completed page records

### Scan 1 — verified

`works/silappathikaram-nataka-kappiyam/pages/0001.md`

Title / imprint page directly rechecked at enlarged resolution. Important source-specific punctuation preserved exactly:

- lower left: `பதிப்புரிமை ]`
- lower right: `[ விலை ரூ. 5`

Do not symmetrize or silently repair these brackets.

### Scan 2 — verified

`works/silappathikaram-nataka-kappiyam/pages/0002.md`

Photograph/caption page. Printed caption preserved as:

`தமிழக முதல்வர்`  
`பேரறிஞர் அண்ணா`  
`அணிந்துரை`

Non-authorial marks are recorded separately:

- large circular library/ownership stamp;
- handwritten accession number `164596` inside the stamp;
- later pencil/shelf notation at mid-right, first line not secure enough for normalization; second line clearly reads `N67`.

### Scan 3 — verified

`works/silappathikaram-nataka-kappiyam/pages/0003.md`

Opening prose page of the `அணிந்துரை`. The lower-right printed page marker is `iii`.

The complete page was checked against the PDF's native embedded scan image (1662 × 2630 pixels, 300 ppi), rather than relying on the lower-resolution render. This resolved and preserved source-supported readings including:

- `இமய உயர்வில்`
- `கலைகளைப் படைத்த மாதவி!`
- `இனிய காதலிக் கலையாகிய பெருந்தலைவி`
- `துயரக் கடலில்`
- `மலைமலையான பொருளைத் தண்ணீராய்ச் செலவிடும்`

No library stamp or later handwriting crosses the prose on this scan; age staining and speckling are recorded as physical-copy evidence.

### Scan 4 — verified

`works/silappathikaram-nataka-kappiyam/pages/0004.md`

Continuation of the `அணிந்துரை`. The printed page marker `iv` appears at the lower left.

The full page was compared directly against the PDF's native embedded scan image. Source-specific wording and typography preserved without normalization include:

- `ஒப்புவமையற்ற`
- `காழ்ப்பு உணர்ச்சி`
- `மூழ்கி-ஈருடல்`
- `காட்டினனே கோவலன்!`
- `துயரமுள் காட்டில்`
- `ஐம்பெருங் காப்பியங்களில்`
- `மாயமந்திர காவியத்தாரிகை`
- `இக்கவின் தமிழ்க்கதையின்`

No library stamp or later handwriting crosses the prose on this scan; age staining and speckling remain copy/scan evidence.

## Page-map state

`indexes/page-map.md` now records scans 1–4 individually as `verified`. The remaining Anna-foreword startup range is now `5–9` and must continue to be expanded one scan at a time.

## Exact checkpoint

Scans **1–4 are complete and verified**. No dramatic body page has yet been transcribed.

## Next activity

1. Process **scan page 5**, continuing the Anna foreword.
2. Preserve every source-supported spelling, punctuation mark and paragraph break; do not silently regularize wording.
3. Use the PDF's native embedded scan image when the normal render leaves small type uncertain.
4. Continue sequentially through scans 6–9 only after each preceding page is visually checked.
5. Expand `indexes/page-map.md` one scan at a time.
6. Do not assemble scenes yet. Scene assembly begins only after the underlying physical pages are visually transcribed and reviewed.