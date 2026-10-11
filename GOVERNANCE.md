# Governance

> **Status: draft for discussion.** This is a lightweight starting model for a small founding group. We expect to revise it as the community grows; changes are made through a [decision record](decisions/).

## Roles

| Role | Who | Responsibilities |
|---|---|---|
| **Contributor** | Anyone who participates in Discussions, issues or pull requests | Follow the Code of Conduct; declare relevant interests |
| **Maintainer** | Contributors trusted to review and merge in one or more areas (Framework, Toolkit, Commons) | Review and merge PRs; triage issues; keep their area's README current |
| **Steering Group** | Founding members, initially | Set direction and roadmap; approve governance changes; resolve disputes; represent the initiative externally |

**Becoming a maintainer:** after sustained, quality contributions, a contributor can be nominated by any maintainer and confirmed by the Steering Group by lazy consensus.

Current members are listed in [Members](#members) below and in [`.github/CODEOWNERS`](.github/CODEOWNERS).

## How decisions are made

| Type of decision | How | Minimum comment period |
|---|---|---|
| Routine (content, fixes, task priorities) | Pull request with one approving review | None |
| Significant (scope, methodology, naming, policies) | Decision record in [`decisions/`](decisions/) via PR, announced in Discussions | 7 days |
| Governance changes | Decision record, approved by the Steering Group | 14 days |

We use **lazy consensus**: a proposal is accepted if no one raises a substantive objection within the comment period. If objections can't be resolved through discussion, the Steering Group decides by simple majority and records its reasoning.

## Conflicts of interest

Independence is central to our mission. Many participants work for organisations that build, sell or use AI products, which is welcome, provided interests are transparent.

1. **Declare.** Members list their professional affiliations below. Contributors declare relevant interests in the pull request or discussion.
2. **Recuse.** No one leads, reviews or approves an evaluation of a product or service from their own employer, clients or competitors.
3. **Vendor neutrality.** Framework guidance and Toolkit tests must not favour any vendor. Products are named only as examples, and alternatives are shown where practical.
4. **Funding transparency.** Any funding, sponsorship or in-kind support is disclosed publicly. Sponsors have no editorial control over guidance or evaluation results.

## Members

| Name | GitHub | Role | Affiliation(s) |
|---|---|---|---|
| Patrick Fan | [@PatrickCSFan](https://github.com/PatrickCSFan) | Steering Group, Maintainer | Founder, FabriXAI |
| _to be added_ | | | |

## Open questions

- [ ] Legal form and home of the nonprofit (e.g. registered charity or company limited by guarantee; jurisdiction)
- [ ] Size and selection of the Steering Group beyond the founding members
- [ ] Funding model and sponsorship policy
