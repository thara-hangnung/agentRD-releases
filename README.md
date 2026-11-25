# RD Agent — APK downloads

This repository holds **only the installable Android builds** of RD Agent
(`com.toia.rdagent`). The source code is kept in a separate private repository;
nothing here reveals it.

## Download

Grab the newest APK from the releases page (newest build at the top):

https://github.com/thara-hangnung/agentRD-releases/releases

Current build: v1.0.0 — https://github.com/thara-hangnung/agentRD-releases/releases/tag/v1.0.0

Each release names the version and what changed.

## Install

1. Download the `.apk` directly on the phone.
2. When Android asks, allow installing from this source (Chrome / Files).
3. Open the downloaded file and install.

To update, install the newer APK over the installed app — the builds are signed
with the same key, so your data is kept.

Requirements: Android 8.1 (API 26) or newer.

## Notes

- Builds marked **pre-release** are debug-signed test builds. If the phone
  already has a release-signed copy of `com.toia.rdagent`, uninstall it first —
  Android refuses to install over a different signature.
- Data stays on the device; RD Agent has no server of its own apart from the
  optional cloud backup the agent configures.
