# Git workshop exercises

Small text exercises from a Git course (ITI intake 40). This is a version-control practice repository, with no application build or runtime.

Clone the repository, create a practice branch, edit an exercise file, and inspect `git diff` before committing. Keep real credentials outside the repository.

## Exposed key remediation

An SSH private key and its public-key companion were previously tracked as `mira` and `mira.pub`. This cleanup removes the files from the proposed tree and adds ignore rules. The owner must revoke the old key wherever it was authorized and generate a replacement outside this repository. File deletion does not remove historical copies; coordinate history cleanup separately.
