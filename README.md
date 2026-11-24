# The Merge Standard

Published agreements for forming ventures between companies and individuals.
Three documents take a partnership from first evaluation to an equity
relationship.

Published by [Merge Combinator](https://mergecombinator.com).

## Documents

| File | Stage | Term | Equity | Status |
|---|---|---|---|---|
| [`explore-agreement.md`](explore-agreement.md) | 01 Explore | 30 days | None | v1.1 |
| [`pursue-agreement.md`](pursue-agreement.md) | 02 Pursue | 6 months | None | v1.1 |
| [`form-agreement.md`](form-agreement.md) | 03 Form | Ongoing | Yes, with vesting | v0.9, pre-release draft |
| [`role-taxonomy.md`](role-taxonomy.md) | Reference | | | v1.1 |
| [`pipeline-and-gates.md`](pipeline-and-gates.md) | Reference | | | v1.1 |

- **Explore** is a 30-day mutual evaluation: confidentiality, one named
  deliverable per party, no exclusivity, no fees, and a review date.
- **Pursue** is a 6-month joint pursuit of a defined opportunity: named roles,
  conditions for forming a company, notice-based exclusivity on that
  opportunity only, and no equity.
- **Form** grants equity to a contributing partner, whether an individual or
  an organization, in exchange for defined contributions, vesting on named
  milestones. It works for a new company or an existing one. It does not cover
  an investment of money.

`spec/page-reference.html` is the reference markup for the public page at
mergecombinator.com/standard. It is a page specification, not a document of the
standard.

## Stable URLs

Every document is served as plain text at a stable URL.

```
https://mergecombinator.com/standard/llms.txt      index of everything
https://mergecombinator.com/standard/explore.md    Explore Agreement
https://mergecombinator.com/standard/pursue.md     Pursue Agreement
https://mergecombinator.com/standard/form.md       Form Agreement
https://mergecombinator.com/standard/roles.md      Role Taxonomy
https://mergecombinator.com/standard/pipeline.md   Venture Pipeline and Gates
```

This repository is the source. The site serves a pinned release of it.

## Purpose

Partnership discussions at an early stage often turn to equity splits, scope,
and exclusivity before the parties have defined the venture. Counsel drafting
for an undefined relationship tends to draft for maximum protection of its own
client, and the resulting paper is often one-sided. The Merge Standard divides
the relationship into three stages and addresses at each stage only the terms
that can be settled at that stage: confidentiality and evaluation at Explore,
roles and formation conditions at Pursue, and equity at Form.

The SAFE standardized the terms on which an investor provides money before a
priced round. The Merge Standard does the same for partners who contribute
work, roles, relationships, or capabilities instead of money.

## Principles

1. **Published and free to use.** Anyone may use these documents, including
   parties who never work with Merge Combinator.
2. **Merge Combinator uses them** in the partnerships it starts.
3. **Standard text, deal-specific terms.** The text of each document is the
   same for every party. The terms that properly differ between deals, such as
   deliverables, roles, milestones, and equity positions, are blanks and
   schedules. Where a party departs from a published default, the departure
   and its reason are recorded in the schedule rather than written into the
   text.
4. **Numbered versions.** Each version is dated, and superseded versions remain
   published in [`archive/`](archive/).

## Proposing a change

Open an issue using the change proposal form. Identify the document, version,
and section, give the proposed text, and explain why it is better for every
party. Responses are given in the issue so that the request and the decision
are both on the record. Accepted changes appear in the next version.

## Versioning

- Each document carries its own `MAJOR.MINOR` version. A minor version
  clarifies or adds terms. A major version changes the meaning of a term for a
  party that has already signed.
- Each document states its version in its first heading block and its
  changelog at the end.
- Superseded versions move to `archive/<version>/` and are not deleted.
- Repository releases are tagged by date, `vYYYY.MM.DD`.

## Merge fields

Documents that can be sent through Sign, Merge Combinator's signing service,
mark each blank with a named token such as `{{counterparty_name}}`. The field
table at the end of the document lists every token.

## License and name

**The text is licensed under [CC BY 4.0](LICENSE).** You may use and adapt these
documents, including commercially. The version header in each document
satisfies attribution.

*These documents are templates provided as is, with no warranty and no
representation that they fit any particular situation. They are not legal
advice. Each party should have its own counsel review any document before
signing.*

**The name is reserved.** See [TRADEMARK.md](TRADEMARK.md). A document with
modified text must not be called The Merge Standard or carry a Merge version
header.
