# Contributing to Vipto

## 1. Who May Contribute

Contributions to Vipto's repositories are accepted from authorized Software Engineering Interns, engineering team members, and, where a repository is explicitly designated as open for external contribution, members of the public who follow the process set out in this document. Contribution to private or internal repositories is restricted to individuals who have been granted access in accordance with [`organization.md`](./organization.md).

## 2. Identifying a Task

All development work at Vipto is tracked through GitHub Issues. Contributors should identify an appropriate open Issue, confirm that it is not already assigned to another contributor, and request assignment before beginning work, in order to avoid duplicated effort.

## 3. Task Assignment

Issues are assigned by the Engineering Lead or another individual holding task-assignment authority as described in [`organization.md`](./organization.md). Contributors should not begin substantial work on an unassigned Issue without first confirming assignment.

## 4. Branch Creation

Once assigned, a contributor should create a new branch from the current main development branch, dedicated to the Issue being addressed. Branches should not be created for multiple unrelated changes.

## 5. Branch Naming

Branches should follow a consistent, descriptive naming convention that reflects the type of change and the associated Issue, for example prefixing the branch with the type of work (such as feature, fix, or chore) followed by a short, descriptive identifier and the relevant Issue number where applicable.

## 6. Commit Expectations

Commits should be scoped to a single logical change where practical, accompanied by a clear and descriptive commit message explaining what was changed and why. Commit history should be legible enough that another contributor can understand the evolution of a change without external explanation.

## 7. Pull Requests

Once development work on a branch is complete, the contributor should open a Pull Request against the appropriate target branch, with a description that clearly explains the change, references the relevant Issue, and notes any special considerations for the reviewer, including testing performed.

## 8. Review Process

Every Pull Request must be reviewed before being merged. Review is conducted by the Engineering Lead or another authorized reviewer, who will assess the change for correctness, code quality, adherence to project conventions, and completeness of testing and documentation. Contributors should respond to review feedback promptly and professionally.

## 9. Testing Requirements

Contributors are responsible for testing their own changes before submitting a Pull Request, and for addressing any testing gaps identified during review. Where automated tests exist for the affected functionality, contributions should not break existing tests without a documented and reviewed justification.

## 10. Documentation Requirements

Where a contribution introduces new functionality, changes existing behaviour, or affects how another contributor would use or extend the code, the contributor is expected to update relevant documentation — whether inline code comments, README content, or associated Confluence documentation — as part of the same contribution.

## 11. Issue Updates

Contributors are expected to keep the associated GitHub Issue updated with meaningful progress, including flagging blockers as soon as they arise rather than at the point of a missed deadline, so that supervision and coordination can respond appropriately.

## 12. Maintainer Responsibilities

Maintainers and reviewers are responsible for providing timely, constructive feedback on Pull Requests, ensuring that merged code meets Vipto's quality standards, and maintaining the overall health and consistency of the codebase across contributions from multiple individuals.

## 13. Code Quality Expectations

Contributions are expected to be readable, reasonably efficient, and consistent with the existing conventions of the codebase. Code that is functional but significantly departs from established patterns without justification may be returned for revision before merge.

## 14. Acceptance and Rejection of Contributions

Vipto reserves the right to accept, request changes to, or decline any contribution, based on considerations including code quality, alignment with the product roadmap, security, and maintainability. A declined contribution does not reflect a judgment on the contributor's ability generally, and reasons for decline will be communicated where practical.

## 15. Security Considerations

Contributors must not introduce known vulnerabilities, hardcoded credentials, or insecure handling of sensitive data into any Vipto repository. Any security concern identified during contribution should be raised in accordance with [`security.md`](./security.md) rather than addressed silently within an unrelated Pull Request.

## 16. Third-Party Code and Licensing

Any third-party code, library, or asset introduced into a Vipto repository must be appropriately licensed for the intended use, and its license terms must be compatible with the repository's own licensing position as described in [`open-source.md`](./open-source.md). Contributors should disclose the origin and license of any non-original code introduced.

## 17. License Requirements

By contributing to a Vipto repository, a contributor agrees that their contribution may be used, maintained, and distributed by Vipto in accordance with the applicable repository license, or, where no license is specified, in accordance with Vipto's internal use as described in [`intellectual-property.md`](./intellectual-property.md).
