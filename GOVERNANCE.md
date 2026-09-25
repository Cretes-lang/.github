# Governance

## Initial stewardship

Bunga Krishanth (@krishanth7) is the initial project lead and maintainer. Cretes currently uses a single-maintainer model; no foundation, board, staff or independent review team is implied.

The project lead stewards language design, compiler, runtime, standard library, tooling, security and documentation until maintainers are appointed. Maintain the smallest practical set of organization owners. Give contributors repository-scoped access appropriate to their duties. Require member 2FA before inviting additional maintainers, after checking account readiness and recovery.

## Decisions

Routine documentation and maintenance changes use pull requests. Changes affecting language semantics, runtime architecture, compatibility, governance or public APIs require an RFC in `Cretes-lang/rfcs` before implementation. Record motivation, alternatives, security consequences, unresolved questions and the decision rationale publicly.

The lead seeks consensus, documents objections, and records accepted, rejected or deferred outcomes. Accepted proposals are not proof of implementation. Specification updates, implementation, conformance tests and release notes follow separately.

## Maintainers and review

Appoint maintainers through a public proposal identifying responsibilities, contributions and scope. Access changes require the owner's deliberate action; a document or CODEOWNERS entry does not grant access. Review permissions periodically and remove unused access through a documented handover.

Use independent review when another qualified maintainer is available. During sole maintainership, a lead-authored change may merge after documented self-review and passing applicable checks. Do not fabricate reviewer approvals or impose an impossible self-approval requirement. Security-sensitive changes deserve extra review and may be deferred until expertise is available.

## Disputes and conflicts

Raise technical disputes in the relevant issue or RFC with evidence and alternatives. The lead records the final rationale. Report conduct matters privately as described in CODE_OF_CONDUCT.md. A conflicted decision-maker should recuse and seek a mutually acceptable independent reviewer where available. No independent appeals body currently exists.

Governance amendments use an RFC with at least seven calendar days for public comment except urgent incident handling, which must be documented afterward without exposing private details.
