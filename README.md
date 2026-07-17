# Eidetic Releases

Public distribution channel for [Eidetic](https://meeteidetic.com) — the private, on-device macOS meeting recorder.

Website: **[meeteidetic.com](https://meeteidetic.com)**

This repository hosts only release artifacts (no source code):

- **`Eidetic.dmg`** — the installer. Always fetch the newest one via
  [`releases/latest/download/Eidetic.dmg`](https://github.com/tigranu80-lang/eidetic-releases/releases/latest/download/Eidetic.dmg).
- **`Eidetic_<version>_aarch64.app.tar.gz` + `.sig`** — auto-update payloads consumed by the in-app updater.
- **`latest.json`** — the update manifest the app polls.

All builds are Developer ID signed and notarized by Apple. Update payloads are additionally
signed with minisign; the app verifies the signature before installing.

Requires macOS 13+ on Apple Silicon.
