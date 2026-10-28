# Security policy

## Report a vulnerability privately

Do not open a public issue for a suspected vulnerability. Either route is fine:

- **GitHub private vulnerability reporting** — the repository's **Security** tab →
  *Report a vulnerability*. The report, the discussion and the advisory stay in one
  place, and it is the fastest route.
- **Email [sushant.poudel2028@gmail.com](mailto:sushant.poudel2028@gmail.com)** —
  include the repository, the affected commit or release, and what you observed.

A report that says "this looks wrong, and here is why" is more useful than one that
waits for a perfect reproduction. If you have a reproducer, include it; if you do not,
describe the conditions you saw.

## What to expect

This account is maintained by one person. No response-time SLA is offered, because one
that is not met is worse than none. What you will get: an acknowledgement when the
report is read, an honest assessment of whether it is in scope and reproducible, and —
if it is — a fix with a regression test, or a written explanation of why it will not be
fixed.

## Scope

**In scope:** defects in the code and detection logic of the repositories here — a
detector that misses the case it documents, a gate that can be bypassed, a parser that
can be crashed or made to fail open, a released artefact that does not match its source.

**Not in scope:** vulnerabilities in third-party projects these tools analyse (report
those upstream); reports that require a hostile party to already control the machine,
the account, or the CI runner; findings demonstrated only on an unreleased or local
patch, without saying so.

## Disclosure

Please give a fix a reasonable chance before publishing. If a report goes unacknowledged,
publish — a silent maintainer is not a reason to sit on a finding. Credit is given in the
advisory unless you ask otherwise.
