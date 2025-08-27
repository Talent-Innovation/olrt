# Security Policy

OLRT (Open Legal Retrieval Toolkit) is an open-source project. We welcome responsible disclosure of vulnerabilities.

## Supported Versions
We triage and fix issues on the default branch (`main`) and the latest tagged release.

## How to Report a Vulnerability

- **Preferred:** Use GitHub “Private vulnerability reporting” or “Security advisories” on this repository.
- **Alternative:** Email **[daniel.cerveny@t-i.cz]** (replace with your address).
- Optionally encrypt with our PGP key: **[PGP fingerprint or URL]**.

Please include:
- affected version/commit and environment,
- minimal steps to reproduce (PoC),
- expected vs. actual behavior,
- impact assessment (e.g., data exposure, RCE, DoS).

## Coordinated Disclosure

We aim to acknowledge within **2 business days** and provide a status update within **7 days**.
Target remediation timelines (may vary with complexity/severity):

| Severity (CVSS/qualitative) | Target timeline |
| --- | --- |
| Critical | fix or mitigation within **14 days** |
| High | **30 days** |
| Medium | **60 days** |
| Low | next regular release |

We appreciate a **90-day** coordinated disclosure window. We’ll keep you updated and request extension if needed.

## Out of Scope (examples)

- Clickjacking on pages with no sensitive actions
- Missing security headers that do not lead to a concrete exploit
- Denial-of-service from unrealistic resource limits or non-default debug builds
- Vulnerabilities exclusively in third-party dependencies (please report upstream; we will track & patch via updates)

## Safe Harbor

- Make a good-faith effort to avoid privacy violations, service degradation, or data destruction.
- Do not access more data than necessary to demonstrate the issue.
- Do not publicly disclose or share details before we release a fix, unless agreed.

## Acknowledgements

We are happy to credit reporters in release notes unless you prefer to remain anonymous. Thank you for helping keep OLRT users safe.
