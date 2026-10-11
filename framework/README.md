# Dependable AI Framework

*Practical guidelines for evaluating open-weight models, agent harnesses and AI infrastructure.*

> **Status: not started (Phase 1).** We're designing the structure now. Join the conversation in Discussions → Framework.

## Scope

The Framework covers the three layers of an open AI deployment. Dependability depends on all three.

| Area | Covers | Folder |
|---|---|---|
| **Open-weight models** | Provenance and licensing, model cards, safety behaviour, bias, robustness, known vulnerabilities | [`open-weight-models/`](open-weight-models/) |
| **Agent harnesses** | Tool and permission design, sandboxing, prompt-injection exposure, human oversight, logging | [`agent-harnesses/`](agent-harnesses/) |
| **AI infrastructure** | Hosting and isolation, network and access control, model serving, data handling, monitoring, update and patching | [`ai-infrastructure/`](ai-infrastructure/) |

## Planned structure for each area

Each area will follow the same pattern, so guidance is easy to navigate and compare:

1. **Risks:** what can go wrong, and why it matters
2. **Checks:** what to evaluate, at proportionate levels (*essential* / *standard* / *advanced*)
3. **Controls:** practical mitigations
4. **Standards mapping:** links to NIST AI RMF, OWASP, ISO/IEC 42001, EU AI Act and others
5. **Worked example:** an end-to-end illustration

## Wanted now

- Proposals for the risk taxonomy of each area
- Real-world adoption experiences: what did you check before deploying?

## Maintainers

See [`.github/CODEOWNERS`](../.github/CODEOWNERS).
