# Making the automation usable beyond its author

## Historical evidence

| Record | What it supports |
| --- | --- |
| November 2024 failed run report | An export timeout was recorded; errors and output completeness needed investigation |
| December 2024 successful run forwarded by a colleague | The automation was used beyond the author's own environment |
| January 2025 launcher and scheduling guidance | Practical support covered batch-file setup, scheduled execution and questions about outputs and logging |

The original correspondence, paths and operational logs remain private. These records establish colleague use and support, not a measured reliability percentage or automatic recovery.

## Proposed operating checklist

This is a new portfolio reconstruction informed by that experience, not the original employer runbook or a claim that every check below was implemented historically.

1. **Before running:** confirm access, reporting period, requested scope, configuration and output location.
2. **Launch:** use the documented launcher; check the last scheduled execution before starting another run.
3. **Verify:** inspect errors as well as completion status. Check that expected files exist, are current and cover the requested periods.
4. **Recover:** retain failure details and identify successful versus incomplete exports before retrying. Prevent incomplete inputs being treated as a complete reporting set.
5. **Escalate:** give the support contact the affected scope, timestamp and failure information. Repeat output verification after recovery.

A good handover connects the operator's actions to the reporting consequence. It should answer what to run, what a valid result looks like and what to do when the result is uncertain.

[Project overview](../README.md) · [Architecture and evidence](ARCHITECTURE.md)
