# Security policy

Security is central to what Crustates promises its customers. Thank you for
helping keep the platform and its users safe.

## Reporting a vulnerability

**Please don't report security issues through public GitHub issues,
discussions or pull requests.**

Report privately through one of these:

- GitHub: open the affected repository under
  [github.com/crustates](https://github.com/crustates), go to its **Security**
  tab and click **Report a vulnerability**
- Email: **security@crustates.eu**

Please include:

- what the issue is and where (component, version or URL)
- steps to reproduce, or a proof of concept
- the impact you think it has

You can write in English or Dutch.

## What to expect

| Step | Target |
|---|---|
| Acknowledgement | within 2 business days |
| Initial assessment | within 5 business days |
| Fix for critical issues | as fast as possible, aiming for 7 days |
| Fix for other issues | depending on severity, within 90 days |

We keep you updated, agree on a disclosure date with you, and credit you in the
advisory unless you prefer to stay anonymous. We follow coordinated disclosure
with a default window of 90 days.

## Scope

In scope:

- the code in any repository under [github.com/crustates](https://github.com/crustates)
- the hosted service at `*.crustates.eu`, including `*.tide.eu` app routing and Reef endpoints

When testing the hosted service:

- only use accounts and projects you own
- never access, change or delete other customers' data; stop and report as soon as you could
- no denial-of-service, spam or social engineering of our staff
- no physical attacks on data centres

Out of scope: issues in customers' own applications hosted on Tide, reports
from automated scanners without a demonstrated impact, and missing best-practice
headers without a concrete exploit.

## Safe harbour

If you act in good faith and follow this policy, we won't take legal action
against you and will treat your research as authorised. If in doubt, ask us
first at security@crustates.eu.

## Supported versions

Crustates is pre-alpha. Only the latest release on `main` receives security fixes.
