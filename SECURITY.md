# Security Policy

This document describes how to report security vulnerabilities for the
**Open Legal Retrieval Toolkit (OLRT)** repository.

## Supported Versions
OLRT is currently under active development. The `main` branch and the latest
tagged release (if any) are in scope for security fixes.

## How to Report a Vulnerability

**Preferred:** Use GitHub “Private vulnerability reporting” or “Security advisories” on this repository.  

**Alternative:** Email **security@t-i.cz** (or **daniel.cerveny@t-i.cz**)  

**Optional:** Encrypt with our PGP key (if available): [PGP fingerprint or URL]  

Please include:
- A clear description of the issue and its potential impact
- Minimal steps to reproduce (PoC), affected files/paths, and environment details
- Suggested remediation, if available
- Whether you want public credit after coordinated disclosure

### Our commitment / response targets
- **Acknowledgement:** within **2 business days**
- **Triage & initial assessment:** within **7 business days**
- **Fix or mitigation plan:** shared within **30 days**, depending on severity and complexity

If you don’t receive acknowledgement in the expected time, please follow up via
the alternative channel.

## Coordinated Disclosure
We aim to acknowledge reports within **2 business days** and provide a status update within **7 business days**.  
Target remediation timelines (may vary with complexity/severity):

| Severity | Target timeline |
|----------|-----------------|
| Critical | fix or mitigation within 14 days |
| High     | 30 days |
| Medium   | 60 days |
| Low      | next regular release |

We appreciate a **90-day coordinated disclosure window**. We’ll keep you updated and request an extension if needed.

## Scope
Reports should focus on vulnerabilities in this repository’s code, build
artifacts and CI configuration.  
Third-party dependencies should be reported to their respective upstreams; however, if a dependency issue significantly impacts OLRT, please still let us know.

## Out of Scope (examples)
- Clickjacking on pages with no sensitive actions
- Missing security headers that do not lead to a concrete exploit
- Denial-of-service from unrealistic resource limits or non-default debug builds
- Vulnerabilities exclusively in third-party dependencies (please report upstream; we will track & patch via updates)

## Safe Harbor
We support **good-faith** security research:
- Do not exfiltrate data, disrupt services, or degrade availability.
- Do not attempt social engineering or physical intrusion.
- Make a good-faith effort to avoid privacy violations and data destruction.
- Give us a reasonable time to remediate before public disclosure.

Activities consistent with this policy and applicable law will be considered
authorized; we will not pursue legal action for good-faith research.

## Disclosure
We practice **coordinated disclosure**. After a fix is available, we’ll publish
a security advisory with credits (if requested) and mitigation steps.

## Credits
We are happy to credit researchers who report vulnerabilities responsibly.
Please tell us how you’d like to be acknowledged.
