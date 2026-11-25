# RD Agent — APK downloads

This repository holds **only the installable Android builds** of RD Agent
(`com.toia.rdagent`). The source code is kept in a separate private repository;
nothing here reveals it.

## Download

Newest build:

https://github.com/thara-hangnung/agentRD-releases/releases/latest

All builds:

https://github.com/thara-hangnung/agentRD-releases/releases

Each release names the version and what changed.

## Which file to install

- `rd-agent-<version>-release.apk` — release-signed. Use this one.
- `rd-agent-<version>-debug.apk` — debug build, for testing only.

The two variants are signed with different keys, so Android refuses to install
one over the other. Uninstall the other variant first.

## Install

1. Download the `.apk` directly on the phone.
2. When Android asks, allow installing from this source (Chrome / Files).
3. Open the downloaded file and install.

Updating: install the newer APK of the same variant over the installed app —
same signing key, so your data is kept. Switching between the release and debug
variant needs an uninstall, which deletes the app's data (export a backup from
Settings first).

Requirements: Android 8.1 (API 26) or newer.

## Notes

- Data stays on the device; RD Agent has no server of its own apart from the
  optional cloud backup the agent configures.
- Pro features (LOT upload, LOT check, ASLAAS push, Passbook, FormFill) are
  unlocked per DOP agent ID after signing in with Google in Settings.
