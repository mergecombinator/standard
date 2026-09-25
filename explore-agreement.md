# Explore Agreement

**Version 1.6**

*Published and maintained as open source by Merge Combinator under CC BY 4.0.
Used to clearly document early partnership exploration, including expectations
and deliverables for partners and entrepreneurs. This agreement can stand
alone, but it does not limit other agreements or rights. Suggest a change at:
github.com/mergecombinator/standard.*

---

This agreement is between **{{first_party_name}}** (the first party) and
**{{counterparty_name}}** (the second party), effective
**{{effective_date}}**.

For thirty days after the effective date, the parties will evaluate whether to
pursue this opportunity together:

> {{opportunity}}

---

## 1. What each party produces

Each party will deliver one concrete result by the date below. Each result should
be small enough to complete within thirty days alongside normal work.

| Party | Deliverable | Due date |
|---|---|---|
| First party | {{deliverable_mc}} | {{deliverable_mc_date}} |
| Second party | {{deliverable_cp_1}} | {{deliverable_cp_1_date}} |
| {{deliverable_cp_2_who}} | {{deliverable_cp_2}} | {{deliverable_cp_2_date}} |

*A concrete result could be a prototype tested with five users, ten customer
interviews with notes, a written acquisition-path assessment, three introductions
followed by completed calls, or a one-page technical assessment.*

If a party does not deliver, the Explore ends on the review date with no penalty
or claim. That result is still useful because it tells the parties not to
proceed. The deliverable exists so that, thirty days later, the parties can
review evidence instead of remembering a conversation.

## 2. The review

**Review date: {{review_date}}** (thirty days from the effective date)

On the review date, the parties meet once, review the work, and choose one:

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

Each party may share information that is not public. The receiving party will
use it only to evaluate this opportunity, protect it with at least the care used
for its own confidential information, and share it only with people who need it
and are bound by these same terms. This obligation lasts two years from the
effective date.

It does not apply to information already public through no fault of the receiving
party, already held by the receiving party, developed independently, or received
from a third party with no duty of confidence. It also does not apply when a law,
regulation, or court requires disclosure. When legally permitted, the party
required to disclose will notify the other first.

## 5. What each party keeps

Each party keeps everything it brought and everything it produces under
section 1. Neither party assigns, licenses, or transfers any intellectual
property, data, or other rights under this agreement. If the parties decide to
create something jointly, they will agree in writing on ownership and permitted
use before creating it.

## 6. No exclusivity

Each party remains free to talk to anyone, work on anything, and pursue this
opportunity separately or with others. Neither party restricts whom the other
hires, works with, or sells to.

## 7. No money, no equity, no obligation to continue

Neither party owes the other a fee, a share, or reimbursement. Each party bears
its own costs. Either party may end this agreement before the review date, for
any reason, without explanation or penalty.

## 8. It expires on its own

This agreement ends on the review date unless both parties sign an extension or
a Pursue Agreement. Section 4 survives for its full two years.

## 9. Entire agreement

This is the entire agreement between the parties on this subject and replaces
all prior discussions and agreements about it. Any change must be in writing
and signed by both parties. The laws of {{governing_state}} govern this
agreement.

---

**First party**

Name {{mc_signer_name}}  Signature {{mc_signature}}

Title {{mc_signer_title}}  Date {{mc_sign_date}}

**Second party**

Name {{cp_signer_name}}  Signature {{cp_signature}}

Title {{cp_signer_title}}  Date {{cp_sign_date}}

---

## Merge fields (for Sign)

Every blank in this document is a named token, `{{like_this}}`. The tokens below
are the complete set. Nothing else in the text changes when a copy is filled in.

The section 1 table is **fixed at three rows** so a frozen AcroForm PDF can
express it. The third row is optional and renders blank when unused.

| Field | Type | Notes |
|---|---|---|
| `first_party_name` | text | Legal name of the first party. Sign defaults this to Merge Combinator, LLC |
| `counterparty_name` | text | Legal name of the second party |
| `effective_date` | date | |
| `opportunity` | long text | Two lines |
| `deliverable_mc` | text | |
| `deliverable_mc_date` | date | |
| `deliverable_cp_1` | text | |
| `deliverable_cp_1_date` | date | |
| `deliverable_cp_2_who` | text | Responsible party for the optional third row. Blank if unused |
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

- **1.6** (2026-09-25) Clarified the open-source purpose and standalone effect
  of the agreement and moved change suggestions to the repository homepage.
- **1.5** (2026-09-25) Renamed the document Explore Agreement, removed the
  asymmetric "Merge" and "You" defined terms, added a first-party merge field,
  named both parties consistently throughout, and added the public change
  proposal path.
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
