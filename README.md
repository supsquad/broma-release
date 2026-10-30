# broma-release

Public release channel for **Broma App**. Installer assets are published here as
GitHub Release assets; the app's in-app updater checks this repo's latest release
and downloads the `broma-setup-v<version>.exe` installer.

The application source lives in a separate private repository.

## Release notes

What each release changes, newest first. Broma App shows these notes next to an
available update, in English or Vietnamese.

### v1.0.0-beta.38 — 2026-10-30

**English**

- **Extensions**: add extensions right from a profile. Pick several at once from your library, the Store, pasted Chrome Web Store links, or .crx and .zip files and folders on this computer.
- **Extensions**: your extension library now follows you to every computer you sign in on. An extension you import from your computer is uploaded once and counts towards your plan's storage; extensions from a store do not. Past your storage, the import is refused and nothing is left behind.
- **Extensions**: every team has a shared extension library, and a team's profiles load their extensions from it on every computer. Pick which library you are looking at on the Extensions screen.
- **Extensions**: deleting an extension now removes it from your library on every computer and from every profile using it.
- **Store**: a new Popular shelf lists the most used extensions on the Chrome Web Store, refreshed every day.
- **Teams**: simpler roles. Members can create, change and delete the team's profiles, flows and extensions. Viewers use what is shared with them and change nothing. Who sees which profile and flow is still the owner's call.
- **Profiles**: when creating a profile, pick the team it belongs to if you are a member of one.

**Tiếng Việt**

- **Tiện ích**: thêm tiện ích ngay trong profile. Chọn nhiều cái một lúc từ thư viện, Cửa hàng, link Chrome Web Store dán vào, hoặc tệp .crx, .zip và thư mục trên máy.
- **Tiện ích**: thư viện tiện ích giờ theo bạn sang mọi máy đăng nhập. Tiện ích import từ máy được tải lên một lần và tính vào dung lượng của gói; tiện ích từ cửa hàng thì không. Vượt dung lượng thì việc import bị từ chối và không để lại gì trên máy.
- **Tiện ích**: mỗi team có một thư viện tiện ích chung, profile của team lấy tiện ích từ đó trên mọi máy. Chọn thư viện muốn xem ở màn Tiện ích mở rộng.
- **Tiện ích**: xóa một tiện ích giờ gỡ nó khỏi thư viện trên mọi máy và khỏi mọi profile đang dùng.
- **Cửa hàng**: thêm kệ Phổ biến gồm những tiện ích nhiều người dùng nhất trên Chrome Web Store, cập nhật mỗi ngày.
- **Team**: phân quyền đơn giản hơn. Thành viên tạo, sửa và xóa được profile, flow và tiện ích của team. Người chỉ xem dùng những gì được chia sẻ và không thay đổi gì. Ai thấy profile và flow nào vẫn do chủ team quyết định.
- **Profile**: khi tạo profile, chọn team của nó nếu bạn là thành viên của một team.

### v1.0.0-beta.37 — 2026-10-30

**English**

- **Extensions**: “Install in Broma” on the extension pages of the Broma website now opens Broma on the Store tab of the Extensions screen, showing that extension, ready to add.
- **Store**: “View on the web” for a flow opens its page at the store's new address.

**Tiếng Việt**

- **Tiện ích**: nút “Cài trong Broma” ở các trang tiện ích trên web Broma giờ mở thẳng Broma tại tab Cửa hàng của màn Tiện ích mở rộng, hiện đúng tiện ích đó để bạn thêm.
- **Cửa hàng**: “Xem trên web” của một flow mở đúng trang của nó theo địa chỉ mới của cửa hàng.

### v1.0.0-beta.36 — 2026-10-29

**English**

- **Extensions**: a new Store tab beside your library, laid out like the Chrome Web Store. It offers hand-picked extensions for people who run many profiles, sorted by kind (crypto wallets, ad blocking, proxy & VPN, cookies & sessions, captcha, automation, productivity), with users and ratings. Add one in one click; an extension you already have says so.
- **Extensions**: sellers can now publish their own extensions on the Broma store. They are always free to install, and one that charges for something inside itself says so on its card. Broma reviews every version before it reaches the store, and an extension taken down from the store stops loading in your profiles.
- **Extensions**: pasting a Chrome Web Store link shows the extension's name, icon, users and rating before you add it, and tells you when the store has no such extension or your library already has it.
- **Extensions**: renaming an extension added from the Chrome Web Store no longer stops it syncing to your other computers.
- **Sellers**: ask to publish extensions from the Seller screen. Once allowed, create an extension listing and upload each version from its folder or a .zip.
- **Profiles**: switching between None, Saved and Manual in the proxy section no longer marks the browser version in red, and the page no longer jumps around.
- **App**: switching tabs in a form without typing anything no longer asks whether to discard changes. An address typed in Manual proxy that would be lost is still asked about.

**Tiếng Việt**

- **Tiện ích**: thêm tab Cửa hàng cạnh thư viện, trình bày giống Chrome Web Store. Cửa hàng có các tiện ích tuyển chọn cho người dùng nhiều profile, xếp theo nhóm (ví crypto, chặn quảng cáo, proxy & VPN, cookie & phiên, captcha, tự động hóa, năng suất), kèm số người dùng và đánh giá. Thêm tiện ích chỉ với một lần bấm; tiện ích đã có trong thư viện thì ghi “Đã có”.
- **Tiện ích**: người bán giờ đăng được tiện ích của riêng họ lên cửa hàng Broma. Tiện ích luôn cài miễn phí; tiện ích nào thu phí bên trong thì ghi rõ trên thẻ. Broma duyệt từng phiên bản trước khi lên cửa hàng, và tiện ích bị gỡ khỏi cửa hàng sẽ ngừng chạy trong profile của bạn.
- **Tiện ích**: dán link Chrome Web Store là thấy ngay tên, icon, số người dùng và đánh giá trước khi thêm, kèm thông báo nếu cửa hàng không có tiện ích đó hoặc thư viện đã có.
- **Tiện ích**: đổi tên tiện ích lấy từ Chrome Web Store không còn làm nó ngừng đồng bộ sang máy khác.
- **Người bán**: xin quyền đăng tiện ích ở màn Người bán. Khi được duyệt, tạo sản phẩm loại tiện ích rồi tải từng phiên bản lên từ thư mục hoặc file .zip.
- **Profile**: chuyển giữa Không dùng, Đã lưu và Nhập tay ở mục proxy không còn làm ô phiên bản trình duyệt báo đỏ, và màn hình không còn bị nhảy.
- **App**: chuyển tab trong form mà chưa nhập gì thì bấm Hủy không còn hỏi bỏ thay đổi. Địa chỉ đã gõ ở proxy Nhập tay mà sắp mất thì vẫn được hỏi.

### v1.0.0-beta.35 — 2026-10-29

**English**

- **App**: reopening Broma picks up where you left off. You are back on the screen you were on, with its search, filters and sort; the drawer or dialog you had open comes back on the same item, with the changes you had not saved yet; and so does the message you were typing to the Agent. If that item was changed elsewhere in the meantime, on another computer or by a team member, only your own changes are put back, and a field changed on both sides is flagged so you can check it before saving. Payments, sign-ins and anything that was running are never resumed.
- **App**: the Agent panel, the sidebar and the size of each panel are now remembered per account, so someone else signing in on the same computer keeps their own layout. The Agent panel is open the first time you use the app.
- **Profiles**: the proxy section now offers three choices: None, Saved or Manual. Removing a proxy is one click on None. Saved shows the proxy the profile uses, and warns you if that proxy has since been deleted from your list. In Manual, pasting `socks5://host:port:user:pass` into Host fills in every field.
- **Profiles**: new “Remove proxy” in a profile’s ⋯ menu and for a selection, after asking you.
- **Profiles**: share several profiles at once: select them and choose Share. Tick a person to share them all, untick to stop sharing them; someone who has only some of them shows how many.
- **Profiles**: the share dialog keeps your ticks when the list refreshes, and before you stop sharing it says how many profiles each person will lose.
- **Editor**: what you typed just before quitting is no longer lost.

**Tiếng Việt**

- **App**: mở lại Broma là tiếp tục đúng chỗ đang dở. Bạn quay về màn đang ở, giữ nguyên ô tìm kiếm, bộ lọc và sắp xếp; drawer hoặc dialog đang mở hiện lại đúng mục đó, kèm những thay đổi chưa lưu; tin nhắn đang gõ cho Agent cũng còn nguyên. Nếu trong lúc đó mục ấy đã được sửa ở nơi khác, trên máy khác hoặc bởi thành viên team, thì chỉ những thay đổi của bạn được áp lại, và ô nào cả hai bên cùng sửa sẽ được đánh dấu để bạn xem lại trước khi Lưu. Thanh toán, đăng nhập và những việc đang chạy thì không bao giờ được tiếp tục lại.
- **App**: panel Agent, sidebar và kích thước từng panel giờ được nhớ theo từng tài khoản, nên người khác đăng nhập trên cùng máy vẫn giữ bố cục của họ. Lần đầu dùng app, panel Agent mở sẵn.
- **Profile**: mục proxy giờ có ba lựa chọn: Không dùng, Đã lưu hoặc Nhập tay. Gỡ proxy chỉ cần bấm Không dùng. Đã lưu hiện đúng proxy profile đang dùng, và cảnh báo nếu proxy đó đã bị xóa khỏi danh sách. Ở Nhập tay, dán `socks5://host:port:user:pass` vào ô Host là điền đủ mọi ô.
- **Profile**: thêm “Gỡ proxy” trong menu ⋯ của profile và cho nhiều profile đang chọn, có hỏi trước.
- **Profile**: chia sẻ nhiều profile một lần: chọn các profile rồi bấm Chia sẻ. Tick một người là chia sẻ cả, bỏ tick là ngừng chia sẻ cả; người đang có một phần thì hiện số profile họ có.
- **Profile**: dialog chia sẻ giữ nguyên các tick khi danh sách được đọc lại, và trước khi ngừng chia sẻ sẽ nói rõ mỗi người mất bao nhiêu profile.
- **Editor**: những gì bạn vừa gõ ngay trước khi thoát không còn bị mất.

### v1.0.0-beta.34 — 2026-10-23

**English**

- **Agent**: an empty chat now shows how many things the Agent remembers, and takes you to the Memory screen in one click. With nothing remembered yet, it reminds you that typing `#` adds an entry.
- **Agent**: the way to Memory now stays at the bottom of the agent list, however many agents you have.
- **Agent**: signing out clears the memory shown in the app, so the next account to sign in never sees the previous one’s.

**Tiếng Việt**

- **Agent**: chat trống giờ cho biết Agent đang nhớ bao nhiêu mục, bấm một lần là tới màn Ghi nhớ. Chưa có ghi nhớ nào thì nhắc bạn gõ `#` để thêm.
- **Agent**: lối vào Ghi nhớ giờ luôn nằm ở chân danh sách agent, dù bạn có bao nhiêu agent.
- **Agent**: đăng xuất thì ghi nhớ đang hiện trong app được xóa, tài khoản đăng nhập sau không thấy ghi nhớ của tài khoản trước.

### v1.0.0-beta.33 — 2026-10-23

**English**

- **Plans**: buying a different plan while your current one is still running now says what happens before you pay. The new plan starts right away, and the time left on your current plan is converted by value into days of the new one. Moving to a cheaper plan is highlighted, because the current plan and everything it includes ends at once.
- **Plans**: a team with more members or synced profiles than its plan allows now has cloud sync paused for everyone in it until it fits again. Profiles keep working on every machine. The Plan and Team screens say what is over and how to fix it, and checkout warns you before you buy a plan your team would not fit.
- **Profiles**: new “Remove from cloud, keep here” action, for one profile or a selection. It takes profiles out of the cloud and keeps them on this machine as local-only profiles; turning sync back on puts them back. The Agent can do it too, after asking you.

**Tiếng Việt**

- **Gói**: mua gói khác trong lúc gói hiện tại còn hạn giờ được nói rõ trước khi trả tiền. Gói mới có hiệu lực ngay, thời gian còn lại của gói hiện tại được quy theo giá trị thành ngày dùng gói mới. Chuyển xuống gói rẻ hơn được tô cảnh báo, vì gói hiện tại và các quyền lợi của nó kết thúc ngay.
- **Gói**: team có nhiều thành viên hoặc profile đồng bộ hơn gói cho phép giờ tạm dừng đồng bộ cloud cho cả team cho đến khi về lại trong giới hạn. Profile vẫn dùng bình thường trên mọi máy. Màn Gói và màn Team nói rõ vượt phần nào và cách xử lý, và bước thanh toán cảnh báo trước nếu team sẽ vượt gói bạn định mua.
- **Profile**: thêm thao tác “Gỡ khỏi cloud, giữ ở máy” cho một hoặc nhiều profile. Profile được đưa ra khỏi cloud và giữ lại trên máy này thành profile chỉ ở máy; bật lại đồng bộ sẽ đưa lên cloud lại. Agent cũng làm được việc này, sau khi hỏi bạn.

### v1.0.0-beta.32 — 2026-10-22

**English**

- **Agent**: the Agent can now remember things for you. Ask it to “remember …” in a chat, start a message with `#`, or write them yourself on the new Memory screen (`/memory`). Every agent reads them in every chat. If the Agent has just read a web page it asks you before saving, and it always asks before forgetting one.
- **Agent**: add an agent right on the agent list. Pick how it connects from one menu, and see the accounts you already added while you add another. You can sign in to several Claude or ChatGPT accounts and switch between them.
- **Agent**: an agent that was signed out signs in again right from the list.

**Tiếng Việt**

- **Agent**: Agent giờ ghi nhớ được cho bạn. Bảo Agent “ghi nhớ …” trong chat, gõ `#` ở đầu tin nhắn, hoặc tự viết trong màn Ghi nhớ mới (`/memory`). Mọi agent đều đọc các ghi nhớ này ở mọi chat. Nếu vừa đọc trang web, Agent hỏi bạn trước khi ghi, và luôn hỏi trước khi quên một ghi nhớ.
- **Agent**: thêm agent ngay trên danh sách agent. Chọn cách kết nối trong một ô chọn, và thấy luôn các tài khoản đã thêm trong lúc thêm tài khoản khác. Bạn có thể đăng nhập nhiều tài khoản Claude hoặc ChatGPT và chuyển qua lại.
- **Agent**: agent bị đăng xuất được đăng nhập lại ngay trên danh sách.

### v1.0.0-beta.31 — 2026-10-21

**English**

- **Editor**: nodes have a cleaner look. Each node's icon takes the colour of its group, the same as in the node list, and the text is larger and easier to read.
- **Editor**: Condition and Loop nodes show each output on a row of its own, so the labels no longer cover the node's text.
- **Editor**: a node shows whether it finished, is running or failed in the last run, and warns when a required value is missing. Its delete button appears when you point at the node or select it.
- **Profiles**: the option that refuses to open a profile while its proxy check fails is now on by default for every profile with a proxy. You can turn it off in the profile's settings.

**Tiếng Việt**

- **Editor**: node trông gọn gàng hơn. Icon của mỗi node mang màu theo nhóm, giống trong Bảng node, chữ to và dễ đọc hơn.
- **Editor**: node Điều kiện và Lặp hiện mỗi nhánh trên một dòng riêng, nhãn nhánh không còn đè lên chữ của node.
- **Editor**: node cho biết đã chạy xong, đang chạy hay bị lỗi ở lần chạy vừa rồi, và cảnh báo khi còn thiếu giá trị bắt buộc. Nút xóa hiện khi rê chuột vào node hoặc khi chọn node.
- **Profile**: tùy chọn chặn mở profile khi proxy kiểm tra lỗi giờ bật sẵn cho mọi profile có proxy. Bạn có thể tắt trong thông số của profile.

### v1.0.0-beta.30 — 2026-10-17

**English**

- **Team flows**: share a flow with your team instead of selling it. The team owner chooses who may share flows and who sees each one. Only the person who shared a flow can change it; everyone else can run it, or make a copy to change. Team flows count toward the team's storage.
- **Store**: flows bought from the Store are now protected. They run on any of your profiles, but cannot be opened in the editor, exported or sold again. The app checks your purchase before a run, and keeps working offline for up to 7 days.
- **Store**: sellers' flows are protected when published. Publishing a flow needs this version or newer.
- **Store**: *Open in Broma* links from the Broma website open the flow in the app's Store.
- **Proxy**: proxy checks ask several services in turn, so one service being down no longer fails the check. You can add your own check services in Settings.
- **Profiles**: a new option refuses to open a profile while its proxy check fails.
- **Agent**: the Agent panel lists your agents, and adding one is guided step by step. Signing an agent out removes it.

**Tiếng Việt**

- **Flow của team**: chia sẻ flow cho team thay vì đem bán. Chủ team chọn ai được đẩy flow lên và ai thấy từng flow. Chỉ người đẩy flow lên mới sửa được; người khác chạy được, hoặc tạo bản riêng để sửa. Flow của team tính vào dung lượng của team.
- **Cửa hàng**: flow mua từ Cửa hàng giờ được bảo vệ. Flow chạy được trên mọi profile của bạn nhưng không mở trong editor, không xuất ra và không bán lại được. App kiểm tra giao dịch mua trước khi chạy, và vẫn chạy được khi mất mạng tối đa 7 ngày.
- **Cửa hàng**: flow của người bán được bảo vệ khi đăng bán. Đăng bán flow cần phiên bản này trở lên.
- **Cửa hàng**: liên kết *Mở trong Broma* trên website Broma mở thẳng flow trong Cửa hàng của app.
- **Proxy**: kiểm tra proxy hỏi lần lượt nhiều dịch vụ, nên một dịch vụ lỗi không làm hỏng lần kiểm tra. Bạn có thể thêm dịch vụ kiểm tra riêng trong Cài đặt.
- **Profile**: tùy chọn mới chặn mở profile khi proxy của nó kiểm tra lỗi.
- **Agent**: panel Agent liệt kê các agent của bạn, thêm agent mới được hướng dẫn từng bước. Đăng xuất một agent là xóa agent đó.

### v1.0.0-beta.29 — 2026-10-15

**English**

- **Payment**: buying a plan or a flow now starts with a confirmation step that shows what you are buying, each payment method as a button with its own amount, and the total. Your order is created only when you confirm.
- **Payment**: plans can take a coupon code. The discount shows before you confirm, and if a code does not apply you are told why.
- **Payment**: crypto and card payments open the payment page in your browser by themselves. You can still change the payment method of an open order.
- **Profiles**: a new profile starts on the latest browser version, so you no longer have to pick one.
- **Team**: owners can switch a person between Member and Viewer. Viewers now use and sync team profiles like members; they just cannot change a profile's settings.
- **Agent**: the Agent button moved to the top bar, next to notifications.

**Tiếng Việt**

- **Thanh toán**: mua gói hoặc flow giờ bắt đầu bằng bước xác nhận: hiện thứ bạn mua, mỗi phương thức thanh toán là một nút kèm số tiền riêng, và tổng tiền. Đơn chỉ được tạo khi bạn bấm xác nhận.
- **Thanh toán**: mua gói có thể nhập mã giảm giá. Số tiền giảm hiện trước khi bạn xác nhận; mã không dùng được thì app nói rõ lý do.
- **Thanh toán**: trả bằng tiền điện tử hoặc thẻ thì trang thanh toán tự mở trong trình duyệt. Đơn đang chờ trả vẫn đổi được phương thức.
- **Profile**: profile mới được chọn sẵn phiên bản trình duyệt mới nhất, không cần tự chọn nữa.
- **Team**: chủ team đổi được vai trò Thành viên và Chỉ xem. Người Chỉ xem giờ dùng và đồng bộ profile của team như thành viên, chỉ không sửa được thông số profile.
- **Agent**: nút Agent chuyển lên thanh trên cùng, cạnh nút thông báo.

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
