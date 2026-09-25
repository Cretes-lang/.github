# Security policy

## Support status

Cretes is in project-foundation development. There are no supported compiler/runtime releases and no production-readiness or security guarantees. The default branch is experimental. A supported-version matrix will be published when releases exist.

## Private reporting

Email **creteslang@gmail.com**, subject `Cretes security report`. Do not publish unpatched vulnerability details in public issues, discussions or pull requests. GitHub private vulnerability reporting may also be used where enabled; email is the current documented fallback. Domain-based security email is not yet established.

Include the affected repository, commit or version, impact, reproduction steps and a minimal example where safe. Remove credentials, personal information and unrelated customer data. Do not access other users' data or test systems without authorization.

## Handling and disclosure

The initial security contact is @krishanth7. The project aims to acknowledge reports within five business days; this is a target, not an SLA. If unanswered after seven days, resend to the same address. Maintainers assess scope and severity, coordinate a fix privately, validate it, and agree a disclosure date with the reporter. Timelines depend on impact, exploitation and fix readiness; no fixed disclosure embargo is guaranteed.

When appropriate, publish a GitHub advisory with affected versions, mitigations, fixed versions and reporter credit with consent. Request a CVE when applicable. Dependency issues should be coordinated with upstream maintainers while tracking Cretes impact. Never promise a bounty: no bounty program is established.

Releases will require dependency review, secret scanning where available, limited workflow permissions and validated artifacts. Implemented controls must be distinguished from planned controls in the foundation checklist.
