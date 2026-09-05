# chromium-release

Public release channel for **Broma Chromium**, the browser engine used by Broma
App. Engine builds are published here as GitHub Release assets.

Assets are named `broma-chromium-v<chromium-version>-<build>-win-x64.zip`. The
archive is flat: `chrome.exe` sits at its root, with no wrapper directory.

Tags are `v<chromium-version>-<build>`. The build number increments when the
patch set changes but the underlying Chromium version does not.

The engine source and patches live in a separate private repository.
