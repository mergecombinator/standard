# Merge Combinator Explore Agreement

**Version 1.4**

*This is Merge Combinator's standard Explore Agreement. We publish it, use it
for every Explore, and do not negotiate it for individual deals. Proposed
changes go into the next version for everyone.*

---

This agreement is between **Merge Combinator, LLC** ("Merge") and
**{{counterparty_name}}** ("You"), effective **{{effective_date}}**.

For the next thirty days, Merge and You will decide whether this opportunity is
worth pursuing together:

> {{opportunity}}

---

## 1. What each of us produces

Each party will deliver one concrete result by the date below. Each result should
be small enough to complete within thirty days alongside normal work.

| Party | Deliverable | Due date |
|---|---|---|
| Merge Combinator | {{deliverable_mc}} | {{deliverable_mc_date}} |
| You | {{deliverable_cp_1}} | {{deliverable_cp_1_date}} |
| {{deliverable_cp_2_who}} | {{deliverable_cp_2}} | {{deliverable_cp_2_date}} |

*A concrete result could be a prototype tested with five users, ten customer
interviews with notes, a written acquisition-path assessment, three introductions
followed by completed calls, or a one-page technical assessment.*

If a party does not deliver, the Explore ends on the review date with no penalty
or claim. That result is still useful: it tells us not to proceed. The deliverable
exists so that thirty days from now we are looking at evidence instead of
remembering a conversation.

## 2. The review

**Review date: {{review_date}}** (thirty days from the effective date)

On the review date, we meet once, review the work, and choose one:

- **Proceed.** Sign the Pursue Agreement and assign roles.
- **Stop.** Walk away. Nothing is owed.
- **Extend once.** Agree in writing to thirty more days and name new
  deliverables. There is no second extension.

## 3. What moves this to Pursue

All three of the following have to be true. Anything less is a stop or an
extension.

1. **Every party produced what they named.**
2. **Demand exists outside this room.** At least five people who are not friends
   of the team described the problem in their own words, or one party has a
   written expression of interest, a letter of intent, or money on the table.
3. **Every core role needed for Pursue has a named owner.** The person does not
   have to be permanent, but they must own the role through Pursue.

## 4. Confidentiality, both directions

Each of us may share information that is not public. Each of us will use it only
to evaluate this opportunity. We will protect it with at least the care we use
for our own information and share it only with people on our side who need it and
are held to these same terms. This obligation lasts two years from the effective
date.

It does not apply to information already public through no fault of the receiving
party, already held by the receiving party, developed independently, or received
from a third party with no duty of confidence. It also does not apply when a law,
regulation, or court requires disclosure. When legally permitted, the party
required to disclose will notify the other first.

## 5. Nobody gains anything new

Each of us keeps everything we brought, and keeps what we produce under
section 1. Neither party is assigning, licensing, or transferring any
intellectual property, data, or rights under this agreement. If we decide to
create something jointly, we will agree ownership and permitted use in writing
before creating it.

## 6. No exclusivity

Both of us stay free to talk to anyone, work on anything, and pursue this same
opportunity separately or with others. Neither of us is restricting who the other
hires, partners with, or sells to.

## 7. No money, no equity, no obligation to continue

Neither party owes the other a fee, a share, or a reimbursement. Each party bears
its own costs. Either of us can end this before the review date, for any reason,
without explanation and without penalty.

## 8. It expires on its own

This ends on the review date unless both parties sign an extension or move to a
Pursue Agreement. Section 4 survives for its full two years.

## 9. Entire agreement

This is the entire agreement between us on this subject and replaces anything
discussed before it. Changes must be in writing and signed by both. Governed by
the laws of {{governing_state}}.

---

**Merge Combinator, LLC**

Name {{mc_signer_name}}  Signature {{mc_signature}}

Title {{mc_signer_title}}  Date {{mc_sign_date}}

**Counterparty**

Name {{cp_signer_name}}  Signature {{cp_signature}}

Title {{cp_signer_title}}  Date {{cp_sign_date}}

---

## Merge fields (for Sign)

Every blank in this document is a named token, `{{like_this}}`. The tokens below
are the complete set. Nothing else in the text changes when a copy is filled in.

The section 1 table is **fixed at three rows** (one Merge, two counterparty) so a
frozen AcroForm PDF can express it. Unused rows render blank.

| Field | Type | Notes |
|---|---|---|
| `counterparty_name` | text | Legal entity or individual |
| `effective_date` | date | |
| `opportunity` | long text | Two lines |
| `deliverable_mc` | text | |
| `deliverable_mc_date` | date | |
| `deliverable_cp_1` | text | |
| `deliverable_cp_1_date` | date | |
| `deliverable_cp_2_who` | text | Third row. "You" or a named person. Blank if unused |
| `deliverable_cp_2` | text | Third row, blank if unused |
| `deliverable_cp_2_date` | date | Blank if unused |
| `review_date` | date | Effective date plus 30 |
| `governing_state` | text | |
| `mc_signature` | text | Typed name, filled when Merge countersigns |
| `mc_signer_name` | text | Filled when Merge countersigns |
| `mc_signer_title` | text | Filled when Merge countersigns |
| `mc_sign_date` | date | Filled when Merge countersigns |
| `cp_signature` | text | Typed name, filled when the counterparty signs |
| `cp_signer_name` | text | Filled when the counterparty signs |
| `cp_signer_title` | text | Filled when the counterparty signs |
| `cp_sign_date` | date | Filled when the counterparty signs |

## Changelog

- **1.4** (2026-09-25) Clarified the thirty-day bargain, deliverable standard,
  review choices, core-role gate, confidentiality exceptions, and joint-work
  language. Renamed the table columns. Added signer titles and stacked each
  signature block into two rows. Moved the explanatory material about Pursue,
  Form, federal pursuits, and fiscal sponsorship out of the agreement.
- **1.3** (2026-09-25) Staging-only iteration that added signer titles to the
  Sign template. It was never published as the current standard.
- **1.2** (2026-09-21) The heading no longer carries a draft label. The text is
  published and in use; Merge Combinator reviews it internally and every change
  is a new version here. No term changed.
- **1.1** (2026-09-18) Term cut from 90 to 30 days. Added section 1 deliverables
  table, section 2 review date, section 3 gate criteria. Added the note that MC's
  vehicle and a fiscal sponsor cover both stages without forming an entity.
  Blanks written as named merge-field tokens, with the signature and date
  fields added to the field table. No term changed. Section 5 rewrapped so a
  line no longer starts with "1.", which markdown rendered as a list.
- **1.0** (2026-09-17) First version. Mutual NDA, no exclusivity, no equity,
  90-day term.
