# Governance

This document describes how decisions are made across HyperSentry Labs
projects.

## Roles

### Maintainers

Maintainers have write access to a repository and are responsible for:

- Reviewing and merging pull requests
- Triaging and responding to issues
- Setting technical direction for the project
- Making releases
- Upholding the [Code of Conduct](CODE_OF_CONDUCT.md)

Maintainers are listed in each repository's `CODEOWNERS` file and in
[MAINTAINERS.md](MAINTAINERS.md).

### Contributors

Anyone who opens an issue, submits a pull request, or participates in
discussions is a contributor. Contributors do not require special access
and are welcome regardless of experience level.

## Decision-making

HyperSentry Labs currently operates under a **benevolent maintainer** model:
technical decisions are made by the project's maintainer(s), informed by
community discussion in issues and discussions.

As individual projects and the organization grow, decisions that affect
multiple repositories or the organization's direction will move toward
lazy consensus among maintainers — proposals are considered approved if no
maintainer objects within a reasonable review period, typically 5 business
days for non-trivial changes.

## Adding new maintainers

New maintainers are added based on sustained, high-quality contributions to
a project over time. There is no fixed contribution count or tenure
requirement; existing maintainers evaluate readiness based on:

- Demonstrated understanding of the codebase and its design decisions
- Quality and consistency of past contributions and reviews
- Constructive participation in issues and discussions

An existing maintainer proposes a new maintainer, and the addition proceeds
absent objection from other maintainers within the review period described
above.

## Removing maintainers

Maintainer status may be removed for prolonged inactivity, or for conduct
that violates the [Code of Conduct](CODE_OF_CONDUCT.md). Removal for
conduct reasons follows the enforcement process described in that
document.

## Repository lifecycle

- New repositories under the organization should include the standard
  community health files (via inheritance from this `.github` repository)
  unless a specific exception is documented in the repository itself.
- Repositories that become unmaintained will be marked as archived, with a
  note in the `README.md` indicating that active development has stopped.

## Changes to this document

Changes to organizational governance are proposed as a pull request to this
repository and follow the lazy-consensus process described above.
