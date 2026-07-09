# Contributing to HyperSentry Labs

Thanks for your interest in contributing. This document describes the
conventions shared across HyperSentry Labs projects. Individual
repositories may extend these guidelines with project-specific notes in
their own `CONTRIBUTING.md`; where they differ, the repository-level
document takes precedence.

## Before you start

- Search existing [issues](https://github.com/orgs/hypersentry-labs/repositories)
  and [discussions](https://github.com/orgs/hypersentry-labs/discussions) to
  see if your idea or bug has already been reported.
- For small fixes (typos, broken links, minor documentation issues), feel
  free to open a pull request directly.
- For anything larger — new features, architectural changes, or breaking
  changes — open an issue first so the approach can be discussed before you
  invest time in an implementation.

## Development workflow

1. Fork the repository and clone your fork locally.
2. Create a branch from `main` using a descriptive name:
   `feature/short-description` or `fix/short-description`.
3. Make your changes, keeping commits focused and atomic.
4. Write or update tests for any behavioral change.
5. Update documentation affected by your change.
6. Run the project's local checks (linting, formatting, tests) before
   opening a pull request.
7. Open a pull request against `main` using the provided template.

## Commit messages

Commit messages should be written in the imperative mood and describe the
change clearly:

```text
Fix incorrect timeout calculation in retry handler
Add support for custom log formatters
Update installation instructions for Python 3.12
```

Where a project uses [Conventional Commits](https://www.conventionalcommits.org),
follow that repository's convention instead.

## Code style

- Follow the formatting and linting configuration already present in the
  repository (`.editorconfig`, `.prettierrc`, or language-specific tooling).
- Keep functions small and single-purpose. Prefer clarity over cleverness.
- Public functions, classes, and modules should include docstrings or
  equivalent inline documentation.
- Avoid introducing new dependencies unless there's a clear justification;
  discuss significant new dependencies in an issue first.

## Testing

- New features should include tests covering the expected behavior and, where
  relevant, edge cases.
- Bug fixes should include a test that reproduces the original issue.
- Pull requests that reduce test coverage without justification may be asked
  for changes before merging.

## Pull request review

- A maintainer will review your pull request as time allows. Response times
  vary, since this is maintained on a volunteer basis.
- Reviews may request changes. Please respond to review comments directly in
  the pull request rather than via other channels, so discussion stays
  attached to the code.
- Once approved, a maintainer will merge the pull request. Contributors
  should not merge their own pull requests unless explicitly given
  permission to do so.

## Reporting bugs

Use the **Bug Report** issue form in the relevant repository. Include:

- The version or commit you're running
- Steps to reproduce the issue
- What you expected to happen versus what actually happened
- Relevant logs or error output

## Suggesting features

Use the **Feature Request** issue form, or start a discussion under
**Ideas** if the proposal is still taking shape and would benefit from
early community input.

## Security issues

Do not open a public issue for a security vulnerability. Follow the process
described in [SECURITY.md](SECURITY.md).

## License

By contributing, you agree that your contributions will be licensed under
the same license as the repository you're contributing to (see that
repository's `LICENSE` file).
