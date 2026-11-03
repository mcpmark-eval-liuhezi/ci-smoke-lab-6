# ci-smoke-lab-6
Sandbox for release-readiness smoke tests: contribution loop + CI. Safely disposable.

## Build artifact

This section documents the `demo-build` artifact produced by CI. The demo-build workflow
writes a short text file (`build-artifact.txt`) during the build step and uploads it as a
GitHub Actions build artifact named exactly `demo-build`, which can be inspected or
downloaded from every finished run in the repository's Actions tab.
