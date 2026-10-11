# Dependable AI Toolkit

*Open-source assessment tools, checklists and reference tests.*

> **Status: not started (Phase 1).** The first deliverable will be a checklist derived from the Framework.

| Folder | What goes there |
|---|---|
| [`checklists/`](checklists/) | Human-readable checklists organisations can use directly, each linked to a Framework area |
| [`reference-tests/`](reference-tests/) | Repeatable automated tests (scripts, evaluation configurations) |

## Principles for Toolkit contributions

- Every item traces back to a check in the [Framework](../framework/).
- Tests must be reproducible: pin versions, document settings and environment.
- A second contributor verifies new tests before merging.
- We prefer building on existing open evaluation tools (e.g. Inspect, Project Moonshot) over writing from scratch.
- Code is licensed under [Apache 2.0](../LICENSE-CODE).

When the Toolkit grows into real software, it will likely move to its own repository.
