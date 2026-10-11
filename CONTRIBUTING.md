# Contributing to the Dependable AI Initiative

Thank you for your interest! This guide explains how ideas become work here. If anything is unclear, ask in [Discussions → Q&A](https://github.com/Dependable-AI-Initiative/dependable-ai-initiative/discussions).

## Ways to contribute

- **Discuss:** share ideas, experiences and questions in Discussions.
- **Review:** comment on open pull requests and draft guidance.
- **Write:** improve or add Framework guidance, guides and documentation.
- **Build:** contribute checklists, reference tests and tools to the Toolkit.
- **Evaluate:** share evaluation results in the Commons (see the [evaluation template](commons/evaluations/_template.md)).

## From idea to merged work

```
 Discussion  ──►  Issue  ──►  Pull request  ──►  Decision record (if it sets direction)
  (explore)      (agreed,       (the work)        decisions/NNNN-title.md
                 actionable)
```

1. **Start a Discussion** for anything new or uncertain (category **Ideas**, or the Framework / Toolkit / Commons categories).
2. **Turn it into an Issue** once there's rough agreement and it's actionable. Maintainers can convert a discussion to an issue in one click.
3. **Plan before you build.** For anything larger than a small fix, comment on the issue with a short plan: what you'll do, how, and how we'll know it's done. Wait for a maintainer or peer to respond before investing significant time. This saves everyone rework.
4. **Open a pull request** that references the issue (`Closes #123`). Draft PRs are welcome early.
5. **Review:** every PR needs at least one approving review from someone other than the author.
6. **Record decisions:** if the change sets a direction (scope, naming, method, policy), add or update a record in [`decisions/`](decisions/).

Small fixes (typos, broken links, wording) can go straight to a pull request.

## Quality expectations

- **Practical over theoretical.** Guidance should be something an organisation can act on.
- **Evidence-based.** Cite sources and link to standards (e.g. NIST AI RMF, OWASP, ISO/IEC 42001, EU AI Act) where relevant.
- **Reproducible.** Evaluations and reference tests must state model versions, settings and environment so others can repeat them.
- **Verified by a second person.** Toolkit tests and Commons evaluation results are checked by someone other than the author before merging.
- **Declare interests.** If your contribution relates to a product or vendor you're connected to, say so in the PR (see [GOVERNANCE.md](GOVERNANCE.md#conflicts-of-interest)).

## Style

- British English spelling.
- Markdown for documents; one sentence per line is encouraged (it makes reviews easier).
- File and folder names in `lower-case-with-hyphens`.

## Labels

| Label | Meaning |
|---|---|
| `framework` · `toolkit` · `commons` · `governance` | Area of work |
| `good first issue` | Well-scoped, suitable for newcomers |
| `help wanted` | We'd especially welcome contributors here |
| `needs-discussion` | Not ready to work on: needs agreement first |

## Licensing of contributions

By contributing, you agree that your contributions are licensed under the repository's licences: **CC BY 4.0** for documentation and written content, and **Apache 2.0** for code, tests and tooling.

## Code of Conduct

All participation is governed by our [Code of Conduct](CODE_OF_CONDUCT.md).
