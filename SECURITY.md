# Security Policy

HyperSentry Labs takes the security of its projects seriously. This document
describes how to report a vulnerability and what to expect afterward.

## Supported Versions

Unless a project's own `SECURITY.md` states otherwise, only the latest
released major version of each project receives security fixes.

| Version        | Supported          |
| -------------- | ------------------ |
| Latest release | :white_check_mark: |
| Older releases | :x:                |

Projects with a documented long-term support policy will note any
exceptions in their own repository.

## Reporting a Vulnerability

**Please do not open a public issue for a security vulnerability.**

Instead, report it privately using one of the following channels:

1. **GitHub Security Advisories** (preferred): open a private advisory
   through the affected repository's **Security** tab, or through this
   organization's [`.github`](https://github.com/hypersentry-labs/.github)
   repository if the affected project is unclear.
2. If private advisories are not available for a given repository, contact
   a maintainer directly through their GitHub profile with a request for a
   secure reporting channel.

When reporting, please include:

- A description of the vulnerability and its potential impact
- Steps to reproduce, or a proof-of-concept if available
- The affected version, commit, or configuration
- Any suggested remediation, if you have one

## Response Timeline

| Stage                        | Target Timeframe        |
| ----------------------------- | ------------------------ |
| Initial acknowledgment        | Within 3 business days   |
| Triage and severity assessment | Within 7 business days  |
| Fix development               | Depends on severity and complexity |
| Coordinated disclosure        | Agreed upon with reporter |

Timelines are best-effort targets, not guarantees, since this organization
is maintained on a volunteer basis.

## Disclosure Process

1. The report is triaged and its severity assessed.
2. A fix is developed privately, without disclosing details in public
   commits, branches, or issues until a patch is ready.
3. Where applicable, a CVE is requested through GitHub's advisory
   database once a fix is available.
4. A new release is published containing the fix.
5. A public advisory is disclosed, crediting the reporter unless they
   request otherwise.

We ask that reporters allow reasonable time for a fix to be released before
any public disclosure of the vulnerability.

## Scope

This policy covers vulnerabilities in code maintained within the
HyperSentry Labs GitHub organization. Vulnerabilities in third-party
dependencies should be reported to the maintainers of those projects
directly; if a dependency vulnerability affects a HyperSentry Labs project
directly, please still let us know so we can track and update the
dependency.

## Security Best Practices for Contributors

- Never commit secrets, credentials, tokens, or private keys.
- Review third-party dependencies before adding them.
- Validate and sanitize all external input in contributed code.
- Follow the principle of least privilege when adding new permissions to
  workflows, tokens, or integrations.
