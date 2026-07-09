# .github

This repository provides the default community health files, issue and
discussion templates, GitHub Actions workflows, and organization profile
for [HyperSentry Labs](https://github.com/hypersentry-labs).

## What lives here

| Path                               | Purpose                                                                    |
| ---------------------------------- | -------------------------------------------------------------------------- |
| `profile/README.md`                | The organization's public profile page                                     |
| `.github/ISSUE_TEMPLATE/`          | Default issue forms, inherited by repositories that don't define their own |
| `.github/DISCUSSION_TEMPLATE/`     | Default discussion category templates                                      |
| `.github/workflows/`               | Reusable, organization-wide CI and automation workflows                    |
| `.github/PULL_REQUEST_TEMPLATE.md` | Default pull request template                                              |
| `.github/CODEOWNERS`               | Default code ownership rules                                               |
| `.github/dependabot.yml`           | Default Dependabot configuration                                           |
| `CODE_OF_CONDUCT.md`               | Default Code of Conduct                                                    |
| `CONTRIBUTING.md`                  | Default contribution guidelines                                            |
| `SECURITY.md`                      | Default security disclosure policy                                         |
| `SUPPORT.md`                       | Where to get help                                                          |
| `GOVERNANCE.md`                    | How decisions are made                                                     |
| `MAINTAINERS.md`                   | Current maintainers                                                        |
| `COMMUNITY.md`                     | How to get involved                                                        |

GitHub automatically applies the files in this repository to any other
repository in the organization that does not define its own version of the
same file. See
["Creating a default community health file"](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file)
for details on how this inheritance works.

## Updating shared files

Changes to files in this repository affect every repository in the
organization that relies on the default. Proposed changes should be opened
as a pull request here and follow the review process described in
[GOVERNANCE.md](GOVERNANCE.md).

## License

The contents of this repository are available under the [MIT License](LICENSE).
