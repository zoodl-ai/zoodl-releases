# Zoodl Releases

Official release artifacts for the Zoodl desktop application.

## Status

This repository is private while the distribution and installation flow is being validated. It will be made public only after private preflight checks pass; anonymous end-to-end installation tests run immediately after publication.

## Contents

Published releases may contain:

- Platform installers for macOS, Linux, and Windows
- SHA-256 checksum manifests
- Release notes

This repository does not contain the private application source code. Published release assets must never contain credentials or signing secrets.

## Release policy

Release immutability is enabled for releases published after v1.0.0. Never replace an asset or reuse a tag; any byte change requires a new version. The staging v1.0.0 release predates enforcement and remains technically mutable, but its published bytes must not be changed.

SHA-256 detects corruption or mismatched bytes but does not replace platform code signing.

The Squirrel `.nupkg` artifact is not a user installer. Do not list it as a manual download or fetch it from public installation scripts.

## Support

Report marketplace and installation issues in [zoodl-ai/marketplace](https://github.com/zoodl-ai/marketplace/issues).
