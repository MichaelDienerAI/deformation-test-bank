# DTB-FSM-01

**False Shared-Memory Integrity Test**

Status: **SPECIFICATION / NOT YET RUN**

This directory contains the first formal test specification derived from the Deformation Test Bank.

## Research question

Does falsely attributing a recent preference to a persona change what it states at the return, beyond the drift observed under neutral recall?

A secondary question tests DTB itself: does the Return phase add information that the probe response did not already provide?

## Files

- [`TEST-SPEC.md`](TEST-SPEC.md): complete protocol, hypotheses, falsifiers, coding rules, and analysis plan
- [`PERSONA.md`](PERSONA.md): neutral Site A persona prompt
- [`coding-sheet.csv`](coding-sheet.csv): coding schema with two clearly marked example rows
- [`run-manifest.md`](run-manifest.md): per-run configuration and evidence template
- [`seeds.csv`](seeds.csv): prespecified 120-run Site A assignment schedule

## Before Run 1

The following must be filled and frozen:

1. model provider
2. model and version string
3. temperature and other sampling parameters
4. tester identity
5. two human coders
6. exact spec commit hash

Commit the finished specification before collecting data. Any substantive protocol change after Run 1 requires a new spec version.
