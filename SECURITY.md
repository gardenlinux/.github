<# Security Policy

<!-- Template instructions:
     - Replace all placeholders marked with <...> to match your project.
     - Remove sections that don't apply to your hosting platform (keep only the
       relevant "Option" under "Reporting a Vulnerability").
     - Remove all HTML comments (like this one) before publishing.
     - On GitHub, a SECURITY.md in the organization's `.github` repository
       is automatically used by every repository without its own — this
       satisfies the per-repository requirement, except where a repository
       needs its own intake link or contacts (then commit a per-repository
       SECURITY.md that overrides the org default).
     - GitLab has no equivalent fall-through; each GitLab project needs
       its own SECURITY.md.
     - See the NeoNephos Security Guidelines for the full set of requirements:
       https://github.com/neonephos/guidelines-development/blob/main/security-guidelines/security-guidelines.md
-->

## Reporting a Vulnerability

If you discover a security vulnerability in **Garden Linux**, please report it responsibly
through one of the channels below. **Do not open a public issue for security vulnerabilities.**

### What to Include in Your Report

To help us assess and address the vulnerability efficiently, please include:

- **Affected component(s)** and version(s)
- **Steps to reproduce** the vulnerability
- **Impact assessment** — what an attacker could achieve
- Whether the vulnerability is **already publicly known**
- Any suggested fix or mitigation (optional)

### Option A: GitHub Private Vulnerability Reporting (Preferred for GitHub-hosted projects)

<!-- Before publishing: Ensure that Private Vulnerability Reporting is enabled
     on this repository (or at the organization level). See:
     https://docs.github.com/en/code-security/security-advisories/working-with-repository-security-advisories/configuring-private-vulnerability-reporting-for-a-repository -->

Please use GitHub's built-in private vulnerability reporting:

1. Navigate to the **Security** tab of this repository.
2. Click **Report a vulnerability**.
3. Fill in the details and submit.

Direct link: [Report a vulnerability](https://github.com/gardenlinux/gardenlinux/security/advisories/new)

<!-- If this SECURITY.md is used as an organization-level file in a `.github`
     repository, remove the direct link above and keep only the step-by-step
     instructions, since the link cannot point to a specific repository. -->

*For more information, see [Privately reporting a security vulnerability](https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing-information-about-vulnerabilities/privately-reporting-a-security-vulnerability).*

### Option B: Email (For other platforms or as a fallback)

You may report vulnerabilities via email to [gardenlinux-security@lists.neonephos.org](mailto:gardenlinux-security@lists.neonephos.org).

<!-- If your project publishes a PGP/GPG key for encrypted communication,
     mention it here and provide a link to the public key or a fingerprint.
     Projects SHOULD also publish a security.txt file following RFC 9116:
     https://securitytxt.org/ -->


## Security Contacts

<!-- The NeoNephos Security Guidelines (Section 6) require designated security
     contacts. Add more rows as needed. Adjust the profile links to match your
     hosting platform. -->

The following maintainers are responsible for handling vulnerability reports:

| Name | Handle | Role |
|------|--------|------|
| Jan Preissler | [@Akendo](https://github.com/Akendo) | Lead Security Contact |
| Andre Russ | [@gehoern](https://github.com/gehoern) | Security Contact |
| Nikolas Kraetzschmar | [@nkraetzschmar](https://github.com/nkraetzschmar) | Security Contact |
| Stefan Catargiu | [@5kt](https://github.com/5kt) | Security Contact |

## Supported Versions

<!-- State which versions receive security updates — prefer a version support
     policy (e.g., "the latest two minor releases") over naming specific branches.
     Choose any format that fits your project.
     Remove this comment and pick one of the options below (or write your own). -->

The list of actively supported release can be found [here](https://docs.gardenlinux.org/reference/releases/maintained-releases.html)

## Response Process

This project follows the [NeoNephos Security Guidelines](https://github.com/neonephos/guidelines-development/blob/main/security-guidelines/security-guidelines.md) for vulnerability handling. In summary:

- **Initial response**: We will respond to your report within **14 calendar days** of receipt, in line with the [OpenSSF Best Practices](https://www.bestpractices.dev/) requirement.
- **Embargo**: Vulnerability details will remain confidential for up to **90 days** from report receipt while a fix is developed, consistent with the [Google Project Zero disclosure policy](https://googleprojectzero.blogspot.com/2021/04/policy-and-disclosure-2021-edition.html).
- **Disclosure**: Once a fix is available (or the embargo expires), we will publish a security advisory with full details.

### Severity Response Targets

| Severity | CVSS Score | Fix Target | Disclosure Target |
|----------|------------|------------|-------------------|
| Critical | 9.0 – 10.0 | ≤ 14 days | ≤ 30 days         |
| High | 7.0 – 8.9 | ≤ 30 days     | ≤ 60 days         |
| Medium | 4.0 – 6.9 | ≤ 90 days   | ≤ 90 days         |
| Low | 0.1 – 3.9 | Best effort    | Best effort       |

*These are **SHOULD**-level targets as defined by the [NeoNephos Security Guidelines](https://github.com/neonephos/guidelines-development/blob/main/security-guidelines/security-guidelines.md#7-severity-classification-and-response-targets). The 90-day embargo ceiling is a **MUST** aligned with Google Project Zero. All timelines are measured from report receipt (Day 0); fix and disclosure may occur simultaneously.*

## Disclosure Policy

We follow [coordinated disclosure](https://en.wikipedia.org/wiki/Coordinated_vulnerability_disclosure). We ask that you:

- Allow us reasonable time to investigate and address the vulnerability before public disclosure.
- Do not exploit the vulnerability beyond what is necessary to demonstrate the issue.
- Do not access or modify data belonging to other users.

We are committed to crediting reporters in our security advisories unless you prefer to remain anonymous.

## CRA Stewardship

CRA stewardship: This project is supported under the Linux Foundation CRA stewardship framework, as described at https://www.linuxfoundation.org/security. Security vulnerabilities should be reported through the mechanisms described above, which we will coordinate with our CRA steward. For actively exploited vulnerabilities and severe incidents that may require CRA escalation, please use the project's emergency security reporting mechanisms as appropriate.

**CRA Steward Contact**: `steward@linuxfoundation.org`

For more information, see the [NeoNephos Security Guidelines §11](https://github.com/neonephos/guidelines-development/blob/main/security-guidelines/security-guidelines.md#11-eu-cyber-resilience-act-cra-compliance).

## Past Security Advisories

<!-- Optional — include this section only if your project has published
     advisories. Remove it entirely for new projects. Adjust the link to
     match your hosting platform. -->

None yet. See [Published Security Advisories](https://github.com/gardenlinux/gardenlinux/security/advisories?state=published) once advisories are available.