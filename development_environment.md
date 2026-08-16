# Development Environment

## 1. Purpose

This document describes the actual technical environment and tooling used to develop Vipto's product, so that contributors and interns can set up a working local environment consistently and understand the standards their contributions are expected to meet.

## 2. Primary Application Technology

Vipto's application is developed primarily using **Flutter**, which is used for the product's cross-platform application development. Contributors working on the application layer are expected to have, or to develop during onboarding, working proficiency with Flutter and its associated tooling.

## 3. Version Control

**Git** is used as Vipto's version control system, with **GitHub** serving as the hosted platform for all repositories, issue tracking, and Pull Request-based review, as described further in [`workflow.md`](./workflow.md) and [`contributing.md`](./contributing.md).

## 4. Development Tooling

**Visual Studio Code** is the primary recommended code editor for Vipto's development work, configured with extensions relevant to Flutter and Dart development. Where native platform-specific development is required, **Android Studio** is used to the extent necessary for Android build configuration, emulation, and debugging.

## 5. Repository Structure

Vipto's repositories are organized to separate application code, documentation, and configuration in a consistent and predictable structure. Contributors are expected to place new code and assets in the location consistent with existing repository conventions, and to raise a question with the Engineering Lead where the correct location is unclear rather than introducing an inconsistent structure.

## 6. Local Development Setup

New contributors are expected to verify their local development environment using the Flutter tooling's built-in diagnostic command before beginning development work, in order to confirm that their local setup is correctly configured and to identify any missing dependencies early.

## 7. Branch Naming

Development branches follow the naming convention described in [`contributing.md`](./contributing.md), reflecting the type of change and, where applicable, the associated GitHub Issue number, to keep the repository's branch history legible and traceable.

## 8. Commit Standards

Commits are expected to be reasonably scoped and accompanied by clear, descriptive messages, consistent with the standards set out in [`contributing.md`](./contributing.md). Large, unexplained, or unrelated batches of changes in a single commit should be avoided.

## 9. GitHub Issues

All planned development work is tracked as a GitHub Issue before implementation begins, providing a single source of truth for what is being built, by whom, and why, and allowing progress to be tracked transparently across the team.

## 10. GitHub Projects

Vipto uses GitHub Projects to visualize and track the status of development work across its lifecycle, from initial backlog through to completion, consistent with the status flow described in [`workflow.md`](./workflow.md).

## 11. Pull Requests

All code changes are submitted for integration through a Pull Request, which serves as the mechanism for review, discussion, and eventual merge into the relevant branch, as described in [`contributing.md`](./contributing.md).

## 12. Code Review

Every Pull Request is reviewed by the Engineering Lead or another authorized reviewer prior to merge, with review focused on correctness, code quality, adherence to existing conventions, and appropriate testing, consistent with the standards described in [`contributing.md`](./contributing.md).

## 13. Testing

Contributors are expected to test their changes locally before submitting a Pull Request, and to add or update automated tests where the existing testing framework supports the affected functionality. Testing expectations are addressed further in the review process described above.

## 14. Merge Requirements

A Pull Request may be merged only after receiving the required review approval and passing any configured automated checks. Contributors should not merge their own Pull Requests without the required approval, except where explicitly authorized to do so for minor, low-risk changes.

## 15. Main Branch Protection

Where branch protection is implemented on Vipto's main development branch, direct commits to that branch are not permitted, and all changes must proceed through the Pull Request and review process described above, in order to preserve the stability and integrity of the primary codebase.

## 16. Development Expectations

Contributors are expected to keep their local development environment reasonably up to date with the project's dependencies, to communicate promptly if their environment prevents them from completing assigned work, and to raise environment-related blockers through Microsoft Teams rather than allowing them to delay a task silently.

## 17. Environment and Configuration Requirements

Any environment-specific configuration required for local development — including required tool versions or configuration files — is documented within the relevant repository. Contributors should refer to repository-specific setup instructions in addition to this general document, and should raise any discrepancy they encounter with the Engineering Lead.
