## Cursor Cloud specific instructions

This repository is a GitHub profile README repository, not an application repo. There are no local services, package manifests, lockfiles, devcontainers, or Docker services to install or run.

The only automation is `.github/workflows/update-readme.yml`, which updates the dynamic README sections on GitHub Actions using the built-in `GITHUB_TOKEN`. For development checks, validate the README markers and workflow behavior locally; use GitHub Actions manual dispatch only when live workflow verification is specifically needed.
