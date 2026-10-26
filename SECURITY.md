# Security Policy

We take the security of our software, firmware and hardware seriously, as well as the physical safety of anyone who builds or operates an Octonary tentacle.

## Reporting a vulnerability

**Please do not report security vulnerabilities or safety hazards through public issues, discussions or pull requests.**

Report them privately instead, using either:

1. **GitHub private vulnerability reporting**: open the affected repository, go to the **Security** tab and choose **Report a vulnerability**; or
2. **Email**: **[security@your-domain]**

Please include as much of the following as you can:

- The affected repository, version, commit or hardware revision
- A description of the issue and its potential impact
- Steps to reproduce, proof-of-concept code or logs
- For hardware: the configuration, firmware version and conditions under which it occurs

## What counts

- Vulnerabilities in our code, firmware, communication protocols or build pipeline
- Ways to bypass motion, force, speed or power limits
- Behaviour that could cause a tentacle to move unexpectedly or injure someone
- Exposed credentials, keys or sensitive data

## What to expect

- We aim to acknowledge your report within **[3] business days**.
- We will keep you informed while we investigate and work on a fix.
- Once a fix is available, we will publish an advisory and, if you wish, credit you for the discovery.

Please give us reasonable time to address the issue before disclosing it publicly.

## Supported versions

Security fixes are applied to the latest release of each repository unless its own `SECURITY.md` says otherwise.
