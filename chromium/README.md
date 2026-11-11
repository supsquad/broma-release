# Broma Chromium

Release notes for **Broma Chromium**, the browser engine used by Broma. Its
builds are the `chromium-v<chromium-version>-<build>` releases of this
repository. There is nothing to install by hand: Broma downloads the engine
a profile needs and offers each upgrade.

Assets are named `broma-chromium-v<chromium-version>-<build>-win-x64.zip`. The
archive is flat: `chrome.exe` sits at its root, with no wrapper directory.

The build number increments when the patch set changes but the underlying
Chromium version does not. Broma knows a build by its version without the
`chromium-` prefix, for example `v151.0.7922.175-5`, and the notes below
are headed the same way.

## Release notes

What each engine build changes, newest first. Broma shows these notes when
it offers to upgrade a profile's engine, in English or Vietnamese.

### v151.0.7922.175-5 — 2026-10-31

**English**

- Opening a profile no longer makes its extensions act as if they were just installed. Extensions that show a welcome or help page now do so once, the first time they are added to a profile, not on every launch.
- Extensions now keep their scheduled tasks, context menus and registered scripts between launches, and their startup routines run each time a profile opens.
- An updated extension now knows it was updated, instead of starting over as a new install.

**Tiếng Việt**

- Mở profile không còn khiến tiện ích hành xử như vừa được cài. Tiện ích có trang chào hoặc trang hướng dẫn giờ chỉ mở trang đó một lần, khi mới thêm vào profile, không mở lại ở mỗi lần mở profile.
- Tiện ích giờ giữ được tác vụ đã hẹn, menu chuột phải và script đã đăng ký giữa các lần mở, và các bước khởi động của tiện ích chạy mỗi khi mở profile.
- Tiện ích được cập nhật giờ nhận biết đó là bản cập nhật, không bắt đầu lại như mới cài.

### v151.0.7922.175-4 — 2026-10-15

**English**

- New icon: an orange circle with a white chrysanthemum, so profile windows are easy to tell apart from Broma App on the taskbar.

**Tiếng Việt**

- Biểu tượng mới: hình tròn cam với bông hoa cúc trắng, để cửa sổ profile dễ phân biệt với Broma App trên thanh taskbar.

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
