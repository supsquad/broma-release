# chromium-release

Public release channel for **Broma Chromium**, the browser engine used by Broma
App. Engine builds are published here as GitHub Release assets.

Assets are named `broma-chromium-v<chromium-version>-<build>-win-x64.zip`. The
archive is flat: `chrome.exe` sits at its root, with no wrapper directory.

Tags are `v<chromium-version>-<build>`. The build number increments when the
patch set changes but the underlying Chromium version does not.

The engine source and patches live in a separate private repository.

## Release notes

What each engine build changes, newest first. Broma App shows these notes when
it offers to upgrade a profile's engine, in English or Vietnamese.

### v151.0.7922.175-3 — 2026-10-09

**English**

- Site settings and preferences that Chromium protects now travel with a synced profile to another computer instead of being reset there.

**Tiếng Việt**

- Cài đặt trang và các tùy chọn được Chromium bảo vệ giờ đi theo profile đồng bộ sang máy khác, không còn bị đặt lại ở máy đó.

### v151.0.7922.175-2 — 2026-10-07

**English**

- The "Google API keys are missing" bar no longer appears on a profile's first tab.

**Tiếng Việt**

- Thanh thông báo "Google API keys are missing" không còn hiện ở tab đầu tiên của profile.

### v151.0.7922.175-1 — 2026-09-10

**English**

- First Broma Chromium build, on Chromium 151.

**Tiếng Việt**

- Bản Broma Chromium đầu tiên, dựa trên Chromium 151.
