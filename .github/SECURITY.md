# Security policy

**Report a vulnerability privately, never in a public issue.** On a public repository, open the repository's **Security** tab and choose **Report a vulnerability**. For the `Kolwen-AI/.github` repository itself, that is [Report a vulnerability](https://github.com/Kolwen-AI/.github/security/advisories/new). There is no e-mail address for security reports.

**What to expect:** the report is read and acknowledged, triaged against the repository's scope, and disclosed once a fix ships as a GitHub security advisory. Published advisories are listed on that repository's Security tab, under Advisories. We acknowledge a report within 5 days, send an assessment within 10 days, and disclose publicly once the fix ships, or at 90 days at most. During an absence announced on the [Kolwen-AI organization page](https://github.com/Kolwen-AI), the 5 days count from the first day back. A public issue stays the right place for an ordinary, non-security bug.

A repository's own `SECURITY.md` wins where it has one: it names that project's scope.

## What counts as a vulnerability

The shipped code and services are in scope: what a Kolwen-AI repository installs, runs or serves for a user. The repository's own tooling (its CI workflows and build scripts) is welcome to report on, and a flaw there is fixed as hardening. Either part earns a published advisory only when an outsider can reach the flaw through input they control. Where it is unclear whether an outsider can reach a flaw, it counts as reachable until the maintainers have decided.

More about Kolwen is at [kolwen.com](https://kolwen.com).
