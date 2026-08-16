# Engineering Workflow

## 1. Purpose

This document describes the actual workflow followed for engineering work at Vipto, from the point a requirement is identified through to its completion and deployment. It is intended as a practical reference for interns and contributors to understand how work moves through Vipto's system.

## 2. Workflow Overview

Vipto's engineering workflow follows a consistent sequence:

**Requirement → GitHub Issue → Assignment → Branch → Development → Pull Request → Review → Testing → Merge → Done**

Each stage of this sequence is described below.

## 3. From Requirement to Issue

A requirement may originate from product planning, a bug report, or an internal improvement identified by the team. Once identified, the requirement is translated into a clearly defined GitHub Issue, describing what needs to be done, why, and, where relevant, any constraints or acceptance criteria that define when the work is complete.

## 4. Issue Assignment

Issues are assigned by the Engineering Lead or another individual holding assignment authority, taking into account the contributor's current workload, relevant skill area, and, for interns, appropriate developmental fit. A contributor should not begin substantial work on an Issue until assignment has been confirmed.

## 5. Project Status Flow

Assigned Issues move through a defined status flow tracked on Vipto's GitHub Project board:

**Backlog → Ready → In Progress → Review → Testing → Done**

Contributors are expected to keep an Issue's status accurate and current as their work progresses, so that the status flow reflects the true state of the work at any given time.

## 6. Branch Creation

Once an Issue is ready to be worked on, the assigned contributor creates a dedicated branch from the current main development branch, named according to the convention described in [`contributing.md`](./contributing.md) and [`development.md`](./development.md).

## 7. Development

Development proceeds on the dedicated branch, with the contributor implementing the change described in the Issue, testing it locally, and keeping the branch reasonably up to date with the main development branch where the duration of the task makes this necessary.

## 8. Commits

Work is committed incrementally, with commit messages that clearly describe the change made, consistent with the commit standards described in [`contributing.md`](./contributing.md).

## 9. Pull Requests

When development on the Issue is complete, the contributor opens a Pull Request describing the change, referencing the associated Issue, and providing the reviewer with any context necessary to review the change efficiently, including how it was tested.

## 10. Review

The Pull Request is reviewed by the Engineering Lead or another authorized reviewer, who assesses the change for correctness, quality, and adherence to Vipto's conventions, and provides feedback directly on the Pull Request.

## 11. Feedback

Where a reviewer requests changes, the contributor addresses the feedback on the same branch, updates the Pull Request accordingly, and requests re-review. This cycle continues until the reviewer is satisfied that the change meets the required standard.

## 12. Testing

Testing occurs both during development, as the contributor verifies their own change, and during review, where the reviewer or another designated party verifies the change functions as intended, including any regression risk to existing functionality.

## 13. Approval

Once a reviewer is satisfied with a Pull Request, they provide formal approval on GitHub, which is a precondition for merge under Vipto's development standards described in [`development.md`](./development.md).

## 14. Merge

Following approval, the Pull Request is merged into the target branch, and the associated Issue's status is updated to reflect that the work has moved into its final stage.

## 15. Issue Completion

Once a change is merged and verified, the associated GitHub Issue is marked as Done, providing a permanent, traceable record connecting the original requirement to the code that fulfilled it.

## 16. Blocker Communication

Where a contributor encounters a blocker at any stage of this workflow — whether a technical obstacle, a dependency on another task, or an unclear requirement — the blocker should be raised promptly through Microsoft Teams rather than allowed to silently delay the associated Issue.

## 17. Teams Communication When Necessary

While GitHub remains the authoritative record of engineering work, Microsoft Teams is used for real-time coordination, clarification, and discussion that supports the workflow described above, particularly where a quicker resolution is needed than asynchronous GitHub comments would allow.
