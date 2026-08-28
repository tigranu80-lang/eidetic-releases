# Eidetic Releases

Public distribution channel for [Eidetic](https://meeteidetic.com) — the private, on-device
macOS **meeting recorder and push-to-talk dictation app**.

Website: **[meeteidetic.com](https://meeteidetic.com)** · [Dictation](https://meeteidetic.com/dictation) · [Release notes](https://meeteidetic.com/whats-new)

## What Eidetic does

- **Records both sides of a call without a bot joining** — microphone plus Mac system audio, so it
  works with Zoom, Google Meet, Microsoft Teams, Slack, browser calls or a conversation in the room.
- **Live, speaker-labelled transcript** beside the notes you type yourself.
- **Editable AI summaries** with version history, written from the transcript and your notes.
- **Ask questions** about one meeting or your whole library — locally.
- **Push-to-talk dictation in every Mac app**: hold a modifier key, speak, release, and the text is
  pasted where your cursor already was. The dictionary learns the words you correct.
- **Insights**: hours recorded, talk share, speaking rate, recurring topics and coaching metrics,
  computed from recordings already on your Mac.

Speech recognition, summarisation and dictation all run **on the machine** — no meeting audio,
transcript or dictated sentence is uploaded for processing. One-time purchase, no subscription,
no account.

## This repository

It hosts only release artifacts (no source code):

- **`Eidetic.dmg`** — the installer. Always fetch the newest one via
  [`releases/latest/download/Eidetic.dmg`](https://github.com/tigranu80-lang/eidetic-releases/releases/latest/download/Eidetic.dmg).
- **`Eidetic_<version>_aarch64.app.tar.gz` + `.sig`** — auto-update payloads consumed by the in-app updater.
- **`latest.json`** — the update manifest the app polls.

All builds are Developer ID signed and notarized by Apple. Update payloads are additionally
signed with minisign; the app verifies the signature before installing.

Requires macOS 13+ on Apple Silicon (M1 or newer).

## Links

- Product site: https://meeteidetic.com
- Dictation: https://meeteidetic.com/dictation
- What's new: https://meeteidetic.com/whats-new
- Blog and comparisons: https://meeteidetic.com/blog
- Privacy policy: https://meeteidetic.com/privacy
- Support: hello@esperastudio.com
