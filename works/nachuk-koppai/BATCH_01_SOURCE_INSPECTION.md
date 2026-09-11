# நச்சுக்கோப்பை — Batch 01 source-inspection checkpoint

Scope: physical scans **1–10**.

Status: **DURABLE PARTIAL CHECKPOINT — NOT PASS A COMPLETE**

## Completed in this checkpoint

- exact uploaded-file size recovered from the conversation file service: **18,459,068 bytes**;
- physical page count reconfirmed: **63**;
- scans **1–10** directly inspected from the controlling attachment;
- page records `pages/0001.md` through `pages/0010.md` created;
- secure bibliographic / structural text recorded without importing later-edition wording;
- scan 8 structural correction established: **Scene 1 closes on scan 8 and Scene 2 opens later on the same physical scan**;
- printed page sequence for dramatic scans 5–10 directly visible as **1–6**.

## New first-pass baseline received

The user supplied a transcription file for the work. Batch 01 content for scans 1–10 is now durably preserved in:

`first-pass/BATCH_01_USER_TRANSCRIPTION.md`

Per repository policy, this is a **comparison baseline, not controlling authority**. The attached PDF remains controlling. The next work is comparison repair, not blind import or retranscription from scratch.

## Not completed

- exact SHA-256 remains pending because the runtime currently cannot execute a local-byte checksum;
- full verbatim prose/dialogue transcription for scans 2–10 is not yet source-secure at the available rendered-image resolution;
- therefore Pass A is **not** declared complete;
- initial verification is PASS only for scan 1; scans 2–10 remain partial;
- H-GATE has not started;
- no `BATCH_01_REVIEW.md` PASS artifact has been created.

## Integrity rule

No missing body text was reconstructed from plot knowledge, a later edition, OCR, or the unproofread Wikisource transcription.

The next source-dependent pass must compare the new user-supplied first-pass baseline against the attached PDF for scans 2–10, correct only source-proven mismatches, complete Pass A, commit it durably, then run targeted H-GATE.


## Pass-A completion

The user's supplied transcription has now been reconciled into full canonical baselines for scans **1–10**. See BATCH_01_PASS_A.md.

- full canonical baselines: **10 / 10**;
- initial verification: **10 / 10 PASS**;
- status after Pass A: **10 / 10 needs-review**;
- H-GATE: **pending**;
- final Batch 01 review: **not yet created**.

The earlier partial checkpoint is superseded for Pass-A completeness but remains useful as history.
