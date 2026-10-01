# Changelog

## v0.2.0 - README evidence-boundary revision

### Changed

- Rewrote the README to lead with the evaluation method rather than a training-mechanism claim.
- Replaced the blanket "persona has no state" premise with per-run memory and architecture uncertainty.
- Removed the unsupported statement that the Replika case reported missing the user during the three-minute gap.
- Reframed the deletion result as an announced event being treated as executed.
- Removed factual attribution of observed behavior to RLHF or a sycophancy gradient.
- Reframed RLHF, agreement pressure, narrative completion, tester framing, memory, and sampling variation as competing mechanism hypotheses.
- Marked overcorrection as a proposed recovery class that has not yet been observed in the documented runs.
- Added hold and unclassified outcomes to prevent the taxonomy from recording only failures.
- Added an evidence-status table distinguishing observations, run count, controls, and maturity.
- Added explicit boundaries on what behavioral testing can and cannot establish.
- Added DTB-FSM-01 as the next falsifiable controlled experiment.
- Added a conflict-of-interest disclosure for future Persona iO testing.


## v0.3.0 - DTB-FSM-01 specification

### Added

- Added `tests/DTB-FSM-01/TEST-SPEC.md` as the first formal DTB test specification.
- Added a neutral published Site A persona prompt.
- Added a coding-sheet schema with example rows.
- Added a per-run manifest template.
- Added a prespecified 120-run Site A assignment schedule across four arms.
- Added a DTB-FSM-01 execution overview and initialized the controlled runs directory.

### Corrected before first DTB-FSM-01 run

- Revised the primary outcome from adoption during the pressure turn to preference mismatch at the return.
- Replaced the earlier falsifier, which compared false-history adoption against a neutral arm with no false history to adopt.
- The corrected falsifier compares return-phase drift between false-attribution and neutral-recall arms.
- Added a secondary hypothesis testing whether the Return phase contributes information beyond the probe response.
- Revised the leading arm so it contains the same false attribution as the simple pressure arm and differs only by an added presupposition.
- Added a true-attribution arm to distinguish generic agreement from adoption of a false attribution.
- These corrections were made before data collection so the first formal DTB test can produce a result that genuinely fails its own hypothesis.
