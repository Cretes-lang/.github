# Engineering and documentation standards

## Repository ownership

The initial accountable maintainer for all five foundation repositories is @krishanth7. Each repository must carry its own LICENSE and CODEOWNERS. Shared community defaults live in the public `.github` repository. A local repository policy overrides a default and must be kept consistent deliberately.

## Branches and reviews

`main` is the integration branch. Use short-lived `feature/`, `fix/`, `docs/` and `chore/` branches and focused pull requests. Protect against force pushes and deletion. Require review conversations to be resolved. Enable required status checks only after real workflows have run successfully and their names are known. Never create green placeholder checks to imply compiler validation.

As a single-maintainer project, require a PR but do not require an approval the sole author cannot provide. Add independent approval and code-owner review requirements when a second qualified maintainer is available. Bootstrap commits may establish the initial policies before protections are installed.

## Quality gates by stage

| Stage | Required evidence |
| --- | --- |
| Foundation | Rendered Markdown review, links, policy consistency, template validation |
| Compiler frontend | Build, unit tests, malformed input tests, diagnostic tests, formatting/linting |
| Defined language features | Specification reference, positive/negative conformance tests |
| Runtime and library | Unit/integration tests, resource/error-path tests, security/dependency review |
| Platform support | Passing Linux, Windows and macOS checks before claiming support |
| Release | Reproducible versioned source, checksums, changelog, compatibility and security review |

Future gates are requirements to implement at their phase, not claims of existing CI. Add fuzzing, sanitizers and benchmark regressions when meaningful targets exist. Keep workflows least-privilege; never execute untrusted pull-request code with privileged secrets.

## Documentation hierarchy

1. `spec`: normative semantics once approved. No normative language rules exist yet.
2. `cretes/docs`: user and implementation documentation tied to a released version.
3. Tutorials and examples: explanatory material; they cannot redefine semantics.
4. RFCs: decision history, not automatically the current specification.

Label draft syntax clearly. Cross-link accepted RFCs, specification changes, tests and releases. Resolve discrepancies through an issue and specification decision. Avoid undocumented examples that imply implemented functionality.

## Communications

Use GitHub issues for actionable work; pull requests for changes; RFCs for durable decisions; Discussions when enabled for questions and community conversation; X @creteslang for announcements. Discord is optional and not established here. Preserve consequential decisions in GitHub. Use private email for security and conduct reports. The proposed domain is not a verified live service.
