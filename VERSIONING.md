# Versioning and release policy

No Cretes toolchain release exists yet. Repository initialization is not a language release.

Future toolchain versions use `MAJOR.MINOR.PATCH`, with tags such as `v0.0.1` and prereleases such as `v0.1.0-alpha.1`. Do not use four-part versions. During `0.x`, syntax and APIs may change; document breaking changes explicitly. Patch releases should favor compatible fixes. At 1.0, define the compatibility surface and apply Semantic Versioning consistently.

Record language/specification version, toolchain version, source commit and supported platforms independently where necessary. Never silently move a published release tag. Withdraw a faulty artifact with a public explanation and issue a corrected version.

Before a release: review changes; run applicable checks; document known limitations, migration guidance and security fixes; validate installation and representative examples; record checksums for binary artifacts; mark experimental builds as prereleases. Do not claim untested platforms are supported.

Suggested progression is experimental `0.0.x`, usable development `0.1.x`, later capability milestones, release candidates and finally 1.0 after an explicit stability review. These are milestones, not committed dates.
