# TerminalGrid releases

Public binary channel for **TerminalGrid** — the tiled terminal manager
with AI-chat and CLI agent integrations (macOS, universal arm64 + x86_64).

This repository contains **only** release artifacts: `.dmg` installers,
updater archives, their minisign signatures and the `latest.json` updater
manifest. The application source lives in a private repository.

## Install

1. Download the newest `TerminalGrid_<version>_universal.dmg` from
   [Releases](https://github.com/Attikaaaa/terminalgrid-releases/releases/latest).
2. Open the dmg and drag TerminalGrid to Applications.

Updates are delivered in-app (Settings > About > Check for Updates) and are
cryptographically verified before install.

> Until the first Developer-ID-signed release is published, builds are
> ad-hoc signed and meant for testing; macOS Gatekeeper may quarantine them.
