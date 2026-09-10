# இரத்தக் கண்ணீர் — Batch execution workflow

Status: **MANDATORY FOR ACTIVE PAGE BATCHES**

This work follows the repository-wide anti-loop policy in `STAGE_PLAY_PROCESSING_GUIDE.md` with the following stricter local rules.

## Source rule

- The attached/local `TVA_BOK_0064189_இரத்தக்_கண்ணீர்.pdf` is the controlling source.
- The Tamil Digital Library record and Wikisource copy are the same source copy/provenance path, **not independent textual witnesses**.
- When the exact controlling PDF is attached and readable locally, routine transcription/verification must **not** switch to TDL, Wikisource or another transport copy. External transport is allowed only if the local controlling bytes are unavailable/unreadable or the user explicitly requests an outside comparison.

## Hard two-commit batch boundary

For each ten-scan page batch:

1. **Pass A — whole pages once.** Render the requested scans from the local controlling PDF. Read each whole page once, transcribe it, establish physical joins/scene boundaries, and complete ordinary visual verification.
2. **Immediate durable commit.** Before any independent H-GATE work, write all Pass-A page records as `status: needs-review`, `initial_verification: passed`, `historical_glyph_gate: pending` and commit them. Do not keep a completed whole-page pass only in chat/crops.
3. **Pass B — targeted independent H-GATE.** Do not retranscribe prose. Check the mandatory historical families and only the candidate/source-sensitive clusters and joins that need character-identity confirmation.
4. **Crop only uncertainty.** Generate a crop/enhancement only for an actual unresolved cluster. One useful crop first; stop once resolved or formally held. Never recrop settled lines for reassurance.
5. **Final closure commit.** Promote clean pages to `verified`, record any genuine correction/hold, create the batch review, synchronize the page map/audit/README/handover/prompt, and commit the closure.
6. **No running inspection diary.** Report after durable commits.

Short rule:

> **Local PDF → Pass A once → commit → targeted H-GATE → final commit. No external detour and no settled-text loop.**
