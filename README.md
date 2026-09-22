# The Merge Standard

Free, published agreements for forming ventures. Three documents carry a
partnership from the first conversation to a company.

Published by [Merge Combinator](https://mergecombinator.com).

Each document states its version in its first heading block. Merge Combinator
publishes these documents, uses them on every conversation it starts, and
reviews them internally. A change is a new version with a changelog entry.

## Documents

| File | Stage | Length | Term | Equity | Status |
|---|---|---|---|---|---|
| [`explore-agreement.md`](explore-agreement.md) | 01 Explore | 1 page | 30 days | None | v1.2 |
| [`pursue-agreement.md`](pursue-agreement.md) | 02 Pursue | 2 pages | 6 months | None | v1.0 |
| [`form-agreement.md`](form-agreement.md) | 03 Form | Full set | Permanent | Yes, once | Not written |
| [`role-taxonomy.md`](role-taxonomy.md) | Reference | | | | v1.0 |
| [`pipeline-and-gates.md`](pipeline-and-gates.md) | Reference | | | | v1.0 |

`spec/page-reference.html` is the reference markup for the public page at
mergecombinator.com/standard. It is a page specification, not a document of the
standard.

## Stable URLs

Every document is served as plain text at a stable URL, so a person or an agent
can read it without downloading a file.

```
https://mergecombinator.com/standard/llms.txt      index of everything
https://mergecombinator.com/standard/explore.md    Explore Agreement
https://mergecombinator.com/standard/pursue.md     Pursue Agreement
https://mergecombinator.com/standard/form.md       Form Agreement
https://mergecombinator.com/standard/roles.md      Role Taxonomy
https://mergecombinator.com/standard/pipeline.md   Venture Pipeline and Gates
```

This repository is the source. The site serves a pinned release of it.

## Why it exists

Two people who want to build something together open a conversation about
splits, scope, and exclusivity before either of them knows what the thing is.
Counsel drafting for an undefined relationship writes for maximum protection.
The paper comes back one-sided and the work stops while the terms get argued.

The Merge Standard splits that negotiation into three stages and settles only
what can honestly be settled at each one. Trust first, roles second, equity last
and only once.

## The four rules that make it a standard

1. **Published and free.** Anyone may use these, including people who will never
   work with Merge and people who compete with us. A document only one party can
   use is not a standard.
2. **We use them ourselves**, on every conversation we start.
3. **We do not negotiate them.** Proposed changes go through issues and land in
   the next version for everyone. Side deals on different terms would end the
   standard.
4. **Versions are numbered and dated, and old versions stay published.** If a
   party signed 1.0, they can always read 1.0.

## Proposing a change

Open an issue using the change proposal form. Say which document, version, and
section, give the text you propose, and say why it is better for every party and
not only for one. We answer in the issue, so what was asked for and what we
decided are both on the record. Accepted changes land in the next version for
everyone.

We do not sign modified copies.

## Versioning

- `MAJOR.MINOR` per document. Minor for clarifications and added structure. Major
  when a term changes meaning for a party who already signed.
- Every document carries its version in the first heading block and its
  changelog at the bottom.
- Superseded versions move to [`archive/<version>/`](archive/) and are never
  deleted.
- Repository releases are tagged by date, `vYYYY.MM.DD`, because each document
  versions on its own.

## Merge fields

Documents that can be sent through Sign, Merge Combinator's signing surface,
mark each blank with a named token such as `{{counterparty_name}}`. The field
table at the bottom of the document lists every token. Tokens make a blank
unambiguous for an agent filling in a draft and for the tool that builds the
signing PDF from this text.

## License and name

**The text is licensed under [CC BY 4.0](LICENSE).** You may use and adapt these
documents, including commercially. The version header in each document satisfies
attribution.

*These documents are templates provided as is, with no warranty and no
representation that they fit your situation. They are not legal advice. Have your
own counsel review anything you sign.*

**The name is reserved.** See [TRADEMARK.md](TRADEMARK.md). A modified document
must not be called The Merge Standard or carry a Merge version header.
