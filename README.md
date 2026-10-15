# broma-release

Public release channel for **Broma App**. Installer assets are published here as
GitHub Release assets; the app's in-app updater checks this repo's latest release
and downloads the `broma-setup-v<version>.exe` installer.

The application source lives in a separate private repository.

## Release notes

What each release changes, newest first. Broma App shows these notes next to an
available update, in English or Vietnamese.

### v1.0.0-beta.28 — 2026-10-15

**English**

- **About**: shows what is new in the version you are running, even when there is no update to install.
- **Agent**: fixed the whole app scrolling out of the window while the Agent panel showed a long chat.

**Tiếng Việt**

- **Giới thiệu**: hiện những gì mới ở phiên bản bạn đang dùng, kể cả khi không có bản cập nhật nào.
- **Agent**: sửa lỗi cả app cuộn ra ngoài cửa sổ khi panel Agent đang hiện một cuộc trò chuyện dài.

### v1.0.0-beta.27 — 2026-10-13

**English**

- **Agent**: type `/` for commands, and `@` to point the Agent at a profile, proxy, flow or extension.
- **Agent**: three modes — *Ask first*, *Auto-approve* (still asks before deleting anything) and *Plan* (looks things up and proposes a plan without changing anything). Switch with Shift+Tab.
- **Agent**: attach screenshots and text files, or paste an image straight into the message box.
- **Agent**: the model that answers is shown next to the agent. Each Claude Code or Codex agent now has an account of its own, signed in from the Agent panel with a browser link and code. Agents added before this version need to sign in once again.
- **Tables**: choose which columns each table shows; the choice is kept for your account.
- **Profiles**: new *Owner* and *Sharing* columns, and a profile can be shared with team members straight from its row.

**Tiếng Việt**

- **Agent**: gõ `/` để dùng lệnh, `@` để chỉ cho Agent một profile, proxy, flow hoặc extension.
- **Agent**: ba chế độ — *Hỏi trước*, *Tự duyệt* (vẫn hỏi trước khi xóa) và *Lên kế hoạch* (chỉ xem dữ liệu rồi đề xuất kế hoạch, không thay đổi gì). Đổi nhanh bằng Shift+Tab.
- **Agent**: đính kèm ảnh chụp màn hình và tệp văn bản, hoặc dán ảnh thẳng vào ô nhập.
- **Agent**: hiện model đang trả lời ngay cạnh agent. Mỗi agent Claude Code hoặc Codex giờ có tài khoản riêng, đăng nhập ngay trong panel Agent bằng link trình duyệt và mã. Các agent thêm từ trước bản này cần đăng nhập lại một lần.
- **Bảng**: chọn cột hiển thị cho từng bảng, lựa chọn được lưu theo tài khoản.
- **Profile**: thêm cột *Chủ sở hữu* và *Chia sẻ*; chia sẻ profile cho thành viên team ngay từ hàng của nó.

### v1.0.0-beta.26 — 2026-10-12

**English**

- **Teams**: roles are now Owner, Member and Viewer. Every account keeps a team of its own and can join several other teams at once; what you can do with a profile follows the team it belongs to.
- **Profiles**: a *Sync now* button replaces the background check every few minutes.
- Notifications moved to a bell in the top-right corner, and screens that show account data have a refresh button.

**Tiếng Việt**

- **Team**: vai trò gồm Chủ team, Thành viên và Chỉ xem. Mỗi tài khoản luôn có team riêng và tham gia được nhiều team khác cùng lúc; quyền với từng profile theo team của profile đó.
- **Profile**: nút *Đồng bộ ngay* thay cho việc tự kiểm tra định kỳ vài phút một lần.
- Thông báo chuyển thành biểu tượng chuông ở góc trên bên phải; các màn hiển thị dữ liệu tài khoản có nút tải lại.
