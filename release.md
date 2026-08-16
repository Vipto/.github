# Release Process

## 1. Purpose

This document describes the actual process Vipto follows to move a change from completed development to a released version of the product, so that contributors understand what happens after a Pull Request is merged.

## 2. Development Completion

A change is considered ready for the release pipeline once it has been implemented, has passed the code review process described in [`contributing.md`](./contributing.md) and [`workflow.md`](./workflow.md), and has been merged into the appropriate branch.

## 3. Testing

Before a release is prepared, merged changes intended for that release undergo testing to confirm they function correctly both individually and in combination with other recently merged changes, reducing the risk of regressions reaching a released version.

## 4. Pull Request Approval

As described in [`development.md`](./development.md), no change is eligible for inclusion in a release unless it has received the required Pull Request approval and passed any configured automated checks.

## 5. Merge

Approved changes are merged into the relevant branch in accordance with [`workflow.md`](./workflow.md), forming the basis of the next release candidate.

## 6. Build Generation

Once the set of changes intended for a release has been merged and tested, a build is generated using Vipto's Flutter-based build tooling, producing the artifact intended for release testing and, subsequently, distribution.

## 7. Release Testing

The generated build undergoes release-specific testing, distinct from the testing conducted during individual code review, intended to verify the overall stability and correctness of the build as a whole before it is made available more broadly.

## 8. Version Numbering

Each release is assigned a version number reflecting its place in Vipto's release history, allowing releases to be tracked, referenced, and, where necessary, rolled back to a known prior state.

## 9. Release Notes

Vipto maintains release notes summarizing the changes included in a given release, providing a readable record of what changed between versions for both internal reference and, where appropriate, external communication.

## 10. Deployment Approval

Before a release is deployed or published, it is reviewed and approved by the Engineering Lead, or another individual holding release approval authority, to confirm that the release is ready for distribution.

## 11. Production Release

Once approved, the release is deployed to production or submitted for distribution through the relevant platform, depending on the nature of the release and the distribution channel involved.

## 12. Post-Release Verification

Following release, the team verifies that the released version is functioning as intended in its live environment, monitoring for any issues that were not identified during release testing.

## 13. Rollback Procedure

Where a released version is found to contain a significant defect, Vipto's process allows for reverting to the most recent known-stable version while a fix is developed, tested, and prepared for a subsequent release, minimizing the impact of the defect on users.

## 14. Responsibility for Release Decisions

Final responsibility for deciding whether a release proceeds, is delayed, or is rolled back rests with the Engineering Lead, in coordination with the Owner function where the decision has product-level implications beyond pure technical readiness.

## 15. Google Play Store and App Store Process

Where a release is intended for distribution through the Google Play Store or another application store, the release additionally follows that platform's own submission, review, and publication process, and is expected to comply with the platform's applicable developer policies before and after publication.
