# Governance

The maintainers decide. They hold the final word on what is merged, released and retired in every Kolwen-AI repository. There is no vote.

## How a change is accepted

Each repository's `CONTRIBUTING.md` or README names its own gates, and its active rulesets are listed at `github.com/Kolwen-AI/<repository>/rules`. At the organization level, a ruleset blocks deleting or transferring any repository. A change is accepted by a maintainer's review, after the repository's own gates pass. Dependabot's patch and minor updates merge on green checks without a review; a major update waits for a maintainer.

## Who writes the changes

AI agents author much of the code, tests and documentation. They work under the maintainers' review; the `Co-Authored-By` trailer on a commit records which model wrote it. An agent never widens its own permissions, installs an integration or changes a repository setting; those are the maintainers' decisions.

## Where to report

Defects and questions go to the repository's issue tracker ([how to get help](https://github.com/Kolwen-AI/.github/blob/main/.github/SUPPORT.md)), security reports to the channel in [SECURITY.md](https://github.com/Kolwen-AI/.github/blob/main/.github/SECURITY.md), conduct concerns to the [Code of Conduct](https://github.com/Kolwen-AI/.github/blob/main/.github/CODE_OF_CONDUCT.md).

The maintainers' internal working rules are private. This file is the public summary of who decides and how, not a copy of them.
