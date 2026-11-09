# broma-release

Public release channel for **Broma**: Broma App, the Windows desktop app, and
Broma Chromium, the browser engine its profiles run on. This repository holds
only the builds (as GitHub Releases) and their release notes; the source code
lives in separate private repositories.

## Install

Download `broma-setup-v<version>.exe` from the newest `app-v…` release, or
from [bromaapp.com/download](https://bromaapp.com/download). Install once; the
app then offers each new version itself, and installs the browser engine your
profiles need.

## Releases

| Product | Tag | Asset | Release notes |
|---|---|---|---|
| Broma App | `app-v<version>` | `broma-setup-v<version>.exe` | [app/README.md](app/README.md) |
| Broma Chromium | `chromium-v<chromium-version>-<build>` | `broma-chromium-v<chromium-version>-<build>-win-x64.zip` | [chromium/README.md](chromium/README.md) |

Beta builds are marked as pre-releases. The **Latest** label only ever marks a
stable Broma App installer, never an engine build.

Broma App reads the release notes in those two files to show what changed, in
English or Vietnamese: next to an app update, and when upgrading a profile's
engine.
