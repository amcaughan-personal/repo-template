# repo-name

One or two sentences: what this is, and why it exists.

## Usage

## Development

## Checks

Every pull request runs the org's shared security scan: leaked secrets (gitleaks),
vulnerable dependencies (Trivy) and workflow problems (actionlint). If this repo gets
infrastructure code, add `checkov` to the scans in `.github/workflows/security-scan.yml`.

`pre-commit install` adds the same secret check to every local commit.
