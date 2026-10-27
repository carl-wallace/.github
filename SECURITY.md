# Security Policy

## Supported versions

Security fixes go into the default branch and the latest published release of each crate. Older
releases do not get patched, so to pick up a fix, upgrade to the latest release.

## Reporting a vulnerability

Please do not open a public issue for a security problem.

Report it privately through GitHub instead: go to the repository's **Security** tab and click
**Report a vulnerability**. Only the maintainer can see the report.

A useful report includes:

- the crate and version, or the commit, that is affected
- the input that triggers the problem (a certificate, CRL, CMS message, PKCS #12 file, etc.), attached
  as the original bytes
- what happens, and what you expected to happen
- the impact as you understand it, for example accepting an invalid certification path or a panic on
  untrusted input

## What to expect

These projects have a single maintainer, so responses are best effort. You should get an
acknowledgement within a week.

If the report is accepted, the fix is prepared privately and released together with a GitHub security
advisory, and a CVE is requested when one is warranted. You will be credited in the advisory unless
you ask not to be.

If the report is declined, you will get an explanation of why, and you are free to discuss it
publicly after that.
