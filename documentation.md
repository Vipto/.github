# Documentation System

## 1. Purpose

This document explains how Vipto organizes and maintains its documentation, so that contributors and interns know where to find, and where to contribute, information relevant to their work.

## 2. Confluence as the Main Documentation Platform

**Confluence** is Vipto's primary platform for structured internal documentation, including onboarding material, process guides, learning tracks, organizational policy, and internal knowledge that is not tied to a specific repository or code change.

## 3. GitHub README Files

Each Vipto repository maintains its own README file, providing an entry point for anyone accessing that specific repository, describing its purpose, setup instructions, and any repository-specific conventions not covered by Vipto's general documentation.

## 4. GitHub Issues

GitHub Issues serve as the documented record of specific development tasks, bugs, and feature requests, including the reasoning behind a given piece of work and the discussion that shaped its implementation, as described in [`workflow.md`](./workflow.md).

## 5. Pull Request Descriptions

Pull Request descriptions document the specific change being introduced, the reasoning behind implementation choices where relevant, and how the change was tested, providing a permanent, linked record connecting a code change to its originating Issue.

## 6. Technical Documentation

Technical documentation — covering architecture, system design, and implementation details intended for engineering reference — is maintained primarily on Confluence, with links from relevant repositories where appropriate, so that engineering decisions remain discoverable beyond the immediate context of a single Pull Request.

## 7. Product Documentation

Product documentation, including product requirements, feature specifications, and roadmap material, is maintained on Confluence and is owned by the Owner function, in coordination with the Engineering Lead where technical feasibility is relevant.

## 8. Decision Records

Significant technical or product decisions, particularly those that depart from a previous approach or establish a new convention, are documented on Confluence as a decision record, so that the reasoning behind the decision remains available to future contributors.

## 9. Internship Documentation

Documentation relating to Vipto's internship program — including onboarding material, the learning track, and internship policy documents — is maintained both on Confluence, for internal reference, and within this repository, for documents intended to be publicly accessible or version-controlled alongside the codebase.

## 10. Ownership of Documents

Each significant document maintained by Vipto has an identifiable owner responsible for keeping it accurate and current, generally aligned with the functional role most closely connected to that document's subject matter, as described in [`roles.md`](./roles.md).

## 11. Review Responsibilities

Document owners are expected to review their owned documentation periodically, and whenever a related process or policy changes, to ensure that Vipto's documentation continues to reflect actual current practice rather than becoming outdated.

## 12. Update Expectations

Contributors and interns who identify outdated, inaccurate, or missing documentation are expected to raise this with the relevant document owner, and, where appropriate, to propose or make the necessary update directly, consistent with Vipto's collaborative working culture.

## 13. Version and History

Confluence and GitHub both maintain version history for the documents they host, allowing changes to Vipto's documentation to be tracked over time. Significant documents, including this one, note their version and last-updated date where practical.

## 14. Confidential Versus Public Documentation

Documentation containing sensitive, unreleased, or confidential information is maintained exclusively on Confluence with restricted access, or within private repositories, and is never placed in a public GitHub repository, consistent with [`security.md`](./security.md) and [`intellectual-property.md`](./intellectual-property.md).

## 15. Links Between GitHub and Confluence

Where a topic is documented in more detail on Confluence than is practical to reproduce within a public repository, the relevant public document links to the Confluence page where appropriate access exists, or otherwise directs the reader to contact vipto.app@gmail.com for further detail.
