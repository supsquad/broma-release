# Broma

Release notes for **Broma**, the Windows desktop app. Its installers are the
`app-v<version>` releases of this repository, named
`broma-setup-v<version>.exe`. Install once; the app then offers each new
version itself and downloads it from here.

## Release notes

What each release changes, newest first. Broma shows these notes next to an
available update, in English or Vietnamese.

### v1.0.0-beta.53 — 2026-11-11

**English**

- **Broma**: the app is now called Broma instead of Broma App, in the Start menu, the window title and the taskbar. A new install goes to `Program Files\Broma`; an update stays in the folder you installed to and replaces the old Start menu and desktop shortcuts.
- If you pinned the app to the taskbar, unpin it and pin it again after updating, so one icon stays for the app.

**Tiếng Việt**

- **Broma**: app giờ tên là Broma thay vì Broma App, trong Start menu, tiêu đề cửa sổ và thanh taskbar. Cài mới sẽ vào `Program Files\Broma`; cập nhật thì giữ thư mục đang cài và thay shortcut cũ ở Start menu và desktop.
- Nếu bạn đã ghim app lên taskbar, sau khi cập nhật hãy bỏ ghim rồi ghim lại để chỉ còn một biểu tượng.

### v1.0.0-beta.52 — 2026-11-10

**English**

- **Team**: everyone in a team can now add profiles, flows, extensions and data to it. Whoever adds something, and the team owner, can do everything with it and decide who else may **Use**, **Edit** or **Edit and delete** it — the whole team at one level, or person by person.
- **Team**: one **Share** dialog for profiles, flows, extensions and data files. Pick several profiles of the same team to set access for all of them at once; a level that differs between them is kept as it is for each one unless you change it.
- **Team**: the Viewer role is gone. Former viewers are now members, and what was shared with them keeps the access it had. Inviting someone no longer asks for a role.
- **Profiles**: the **Sharing** column shows whether the whole team or some people may use each profile, and on a profile shared with you, what you may do with it. A team profile now names who created it.
- **Extensions**: in a team library, editing or deleting an extension follows your access to it; applying it to your profiles only needs Use.
- **Data**: when you push a new file, choose right away what the whole team may do with it.
- **Agent**: the Agent can show and change who may use a profile, flow, extension or data file, after you approve.

**Tiếng Việt**

- **Team**: giờ ai trong team cũng thêm được profile, flow, tiện ích và dữ liệu lên team. Người thêm và chủ team làm được mọi thứ với nó, và quyết định ai khác được **Dùng**, **Sửa** hay **Sửa và xóa** — cả team một mức, hoặc từng người một.
- **Team**: một hộp **Chia sẻ** chung cho profile, flow, tiện ích và tệp dữ liệu. Chọn nhiều profile cùng một team để đặt quyền cho tất cả một lần; mức nào đang khác nhau giữa các profile thì mỗi profile giữ nguyên, trừ khi bạn đổi.
- **Team**: bỏ vai trò Người xem. Người xem trước đây giờ là thành viên, những gì đã chia sẻ cho họ giữ nguyên quyền như cũ. Mời người vào team không còn phải chọn vai trò.
- **Profile**: cột **Chia sẻ** cho biết cả team hay những ai được dùng từng profile, và với profile người khác chia sẻ cho bạn thì bạn được làm gì. Profile của team giờ ghi tên người tạo.
- **Tiện ích**: trong thư viện của team, sửa hay xóa một tiện ích theo quyền của bạn với tiện ích đó; áp tiện ích vào profile của bạn chỉ cần quyền Dùng.
- **Dữ liệu**: khi đẩy một tệp mới, chọn ngay cả team được làm gì với tệp đó.
- **Agent**: Agent xem và đổi được ai được dùng một profile, flow, tiện ích hay tệp dữ liệu, sau khi bạn cho phép.

### v1.0.0-beta.51 — 2026-11-09

**English**

- **Data**: a new **Data** screen, next to **Run**. **On this machine** lists every run whose flow writes a result table, with how many rows it has and where it was shared.
- **Data**: **Push to cloud** shares a run's whole result as one file with a team you own or are a member of. Everyone in the team can open and download it; pushing again replaces the file. Turn on **Push again after every run** and the file updates itself whenever a run ends. Shared files count against the team owner's plan storage.
- **Data**: the **Cloud** tab shows a team's shared files like a shared drive. Open one, or pick several and **View merged** to see them as one table, then export to Excel, CSV or JSON. Owners and members can rename and delete; viewers can open and download.
- **Editor**: new **HTTP request** step, to send what a flow collected to a webhook, a Google Sheets Apps Script or an API while it runs. In a JSON body, write `{{var.items}}` without quotes and any value becomes valid JSON. The response can be saved for the next steps.
- **Agent**: the Agent can list your data and push a run's result to a team's cloud, after you approve.

**Tiếng Việt**

- **Dữ liệu**: màn **Dữ liệu** mới, ngay dưới **Chạy**. Tab **Trên máy** liệt kê các run có flow ghi bảng kết quả, kèm số dòng và nơi đã chia sẻ.
- **Dữ liệu**: nút **Đẩy lên cloud** chia sẻ toàn bộ kết quả của một run thành một tệp cho team mà bạn là chủ hoặc thành viên. Mọi người trong team mở và tải được; đẩy lại sẽ thay tệp cũ. Bật **Tự đẩy sau mỗi lần chạy** thì tệp tự cập nhật mỗi khi một lượt chạy kết thúc. Tệp chia sẻ tính vào dung lượng gói của chủ team.
- **Dữ liệu**: tab **Cloud** hiện các tệp team đã chia sẻ, như một ổ đĩa chung. Mở từng tệp, hoặc chọn nhiều tệp rồi **Xem gộp** thành một bảng và xuất ra Excel, CSV hay JSON. Chủ team và thành viên đổi tên, xóa được; người xem thì mở và tải.
- **Editor**: thêm bước **Gọi HTTP**, để gửi dữ liệu flow thu được tới webhook, Apps Script của Google Sheets hoặc một API ngay trong lúc chạy. Trong nội dung JSON, viết `{{var.items}}` không có ngoặc kép, giá trị nào cũng thành JSON hợp lệ. Có thể lưu phản hồi cho các bước sau.
- **Agent**: Agent xem được dữ liệu của bạn và đẩy kết quả của một run lên cloud của team, sau khi bạn cho phép.

### v1.0.0-beta.50 — 2026-11-09

**English**

- **Updates**: **Download & install** now fetches the latest download link first, so an update offered earlier in the session no longer fails with "404 Not Found".
- **Updates**: "What's new" shows release notes again, both for an available update and for the version you are running.
- **Engine upgrade**: the Chromium engine upgrade dialog shows what each new engine version changes again.

**Tiếng Việt**

- **Cập nhật**: nút **Tải & cài đặt** giờ lấy link tải mới nhất trước, nên bản cập nhật được báo từ đầu phiên không còn lỗi "404 Not Found".
- **Cập nhật**: mục "Có gì mới" lại hiện ghi chú, cả cho bản cập nhật lẫn phiên bản đang chạy.
- **Nâng engine**: hộp thoại nâng engine Chromium lại hiện ghi chú của từng bản engine mới.

### v1.0.0-beta.49 — 2026-11-08

**English**

- **Editor**: with no profile selected, **Run** now uses a clean temporary browser that exists only in the Editor and is deleted when it closes. You no longer have to pick or create a profile just to try a flow.
- **Editor**: the temporary browser opens with the extensions the flow requires, downloading Chrome Web Store and Broma Store extensions when needed. If it is already open without them, it restarts with them. A local extension only has to be on this computer.
- **Editor**: when the selected profile lacks a required extension, the Editor now names it and says what to do, instead of showing a generic error. For a Store extension, **Add and run** adds it to the profile and starts the run.
- **Store**: a flow's page lists the extensions it needs before you buy, and where each one comes from. An extension only the seller has is clearly marked: Broma cannot install it, so the flow will not run without it. Sellers see the same list on each version, with a warning for local extensions.
- **Flow data**: **Requirements** moved to the bottom of the panel, after the form, the shared memory and the result table.
- **Agent**: the agent picker shows a Claude Code or Codex agent's plan (for example `max`) instead of "CLI default".

**Tiếng Việt**

- **Editor**: khi chưa chọn profile, nút **Chạy** giờ dùng một browser tạm sạch, chỉ có trong Editor và bị xóa khi đóng. Không còn phải chọn hay tạo profile chỉ để chạy thử flow.
- **Editor**: browser tạm mở kèm các extension flow yêu cầu, tự tải bản Chrome Web Store và Broma Store khi cần. Nếu nó đang mở mà thiếu, nó tự mở lại với đủ extension. Extension cục bộ chỉ cần có trên máy này.
- **Editor**: khi profile đã chọn thiếu extension bắt buộc, Editor giờ nói rõ thiếu cái nào và cần làm gì, thay vì báo lỗi chung chung. Với extension từ Store, nút **Thêm và chạy** thêm nó vào profile rồi chạy luôn.
- **Cửa hàng**: trang flow liệt kê các extension flow cần trước khi bạn mua, kèm nguồn của từng cái. Extension chỉ người bán có được ghi rõ: Broma không cài được nên flow sẽ không chạy nếu thiếu. Người bán thấy cùng danh sách ở từng phiên bản, kèm cảnh báo khi có extension cục bộ.
- **Dữ liệu flow**: mục **Yêu cầu** chuyển xuống cuối panel, sau Form nhập, Bộ nhớ chung và Bảng kết quả.
- **Agent**: bộ chọn agent hiện gói của agent Claude Code hoặc Codex (ví dụ `max`) thay vì "Mặc định của CLI".

### v1.0.0-beta.48 — 2026-11-08

**English**

- **Flows**: a flow can now declare the browser extensions it needs in **Flow data → Requirements**. The declaration travels with shared and Store flows without carrying a database id from the author's computer.
- **Runs**: before a flow runs, Broma checks every selected profile for its required extensions and shows what is missing, disabled or waiting for a browser restart. **Add to profile** explicitly downloads portable Store extensions and enables existing ones; a local extension still has to be added from the Profiles screen.
- **Runs and schedules**: a flow cannot start without its required extensions. A browser that was already open must be reopened before it can load a newly added extension, and a scheduled run rejected by this check now leaves a visible error in Runs instead of failing silently.

**Tiếng Việt**

- **Flow**: flow giờ khai báo được các extension trình duyệt bắt buộc trong **Dữ liệu flow → Yêu cầu**. Khai báo này đi theo flow khi chia sẻ hoặc bán trong Cửa hàng mà không mang theo id database trên máy của người tạo.
- **Chạy**: trước khi flow chạy, Broma kiểm tra mọi profile đã chọn và cho biết extension nào đang thiếu, bị tắt hoặc cần mở lại browser. Nút **Thêm vào profile** chỉ tải extension có nguồn Store và bật extension sẵn có khi bạn chủ động bấm; extension cục bộ vẫn phải được thêm từ màn Profile.
- **Chạy và lịch chạy**: flow không thể bắt đầu khi chưa đủ extension bắt buộc. Browser đang mở phải được mở lại để nạp extension vừa thêm, và lịch chạy bị từ chối bởi kiểm tra này giờ để lại lỗi rõ ràng trong màn Chạy thay vì im lặng thất bại.

### v1.0.0-beta.47 — 2026-11-07

**English**

- **Proxies**: the Proxy screen now has three tabs. **Added by you** holds the proxies you add or import, and only those — every one of them can be edited, deleted and exported. **Purchased** holds the proxies you bought. **Buy proxies** shows the plans on sale.
- **Proxies**: **Buy proxies** lays every plan out side by side, each with its price per day, protocol, bandwidth, countries and IP rotation, so you can compare them at a glance. A plan that cannot be bought right now stays on the shelf with the reason. Pick a plan, then choose the term, quantity and country on the right and pay. Once paid you land on **Purchased**, where the new proxy reads "Provisioning…" until it is ready.
- **Proxies**: fixed buying a proxy — after you confirmed the order, the payment screen with the QR code did not appear. The confirmation step also shows the plan, provider, term and quantity properly now, instead of placeholder text.
- **Proxies**: **Purchased** shows each proxy's name and host:port — the name you will see when picking a proxy for a profile — and adds **Copy address**. Renewing opens a small dialog where you only choose the term; the plan, country and rotation stay as they are.

**Tiếng Việt**

- **Proxy**: màn Proxy giờ có ba tab. **Tự thêm** chỉ chứa proxy bạn tự thêm hoặc nhập — tất cả đều sửa, xóa và xuất được. **Đã mua** chứa proxy bạn đã mua. **Mua proxy** hiện các gói đang bán.
- **Proxy**: tab **Mua proxy** bày mọi gói cạnh nhau, mỗi gói có giá theo ngày, giao thức, băng thông, quốc gia và kiểu xoay IP, để so sánh trong một lần nhìn. Gói đang không mua được vẫn nằm trên kệ kèm lý do. Chọn gói, rồi chọn thời hạn, số lượng và quốc gia ở bên phải và trả tiền. Trả xong bạn được đưa sang tab **Đã mua**, nơi proxy mới hiện "Đang cấp proxy…" cho tới khi sẵn sàng.
- **Proxy**: sửa lỗi mua proxy — xác nhận đơn xong thì màn thanh toán có mã QR không hiện ra. Bước xác nhận cũng hiện đúng gói, nhà cung cấp, thời hạn và số lượng, thay vì chữ giữ chỗ.
- **Proxy**: tab **Đã mua** hiện tên và host:port của từng proxy — đúng cái tên bạn thấy khi chọn proxy cho profile — và có thêm **Sao chép địa chỉ**. Gia hạn mở một dialog nhỏ chỉ để chọn thời hạn; gói, quốc gia và kiểu xoay giữ nguyên.

### v1.0.0-beta.46 — 2026-11-06

**English**

- **Proxies**: buy a proxy from a partner right inside Broma. **Buy proxies** on the Proxy screen shows the plans on sale: pick a term, how many, the country and how the IP rotates, then pay the way you pay for a plan. The proxy lands in your proxy list by itself about a minute later — nothing to copy, nothing to import — and a profile can pick it like any other proxy.
- **Proxies**: the new **Purchased** tab is those same proxies seen as purchases: how many days are left, where to renew, a free **Rotate IP**, and a switch between HTTP and SOCKS5. Renewing keeps the plan, country and rotation it already has.
- **Proxies**: a bought proxy does not count against your plan's proxy limit, and it cannot be edited or deleted on the **Mine** tab — it is the partner's session, and it leaves your list on its own when it expires. Select everything and press delete and only your own proxies go.
- **Agent**: delete every conversation at once, from the button at the bottom of the history popover. A conversation still running is kept, and it says so. The delete button on the Agent panel header is gone; deleting one conversation is still on its row in the history.
- **Agent**: when Claude fails, the message now says what it actually said instead of showing a block of JSON. A stale "another Claude Code process is refreshing" is cleared by itself and the request retried once, instead of staying stuck. A long error without spaces no longer runs outside its box.
- **Profiles, Utilities**: the hint inside the search box is no longer cut off halfway.
- **Profile groups**: the **New group** button in the Manage groups dialog no longer wraps onto two lines.

**Tiếng Việt**

- **Proxy**: mua proxy của đối tác ngay trong Broma. Nút **Mua proxy** ở màn Proxy hiện các gói đang bán: chọn thời hạn, số lượng, quốc gia và kiểu xoay IP, rồi trả tiền đúng cách bạn vẫn trả cho gói. Khoảng một phút sau proxy tự vào danh sách proxy của bạn — không phải copy, không phải import — và profile chọn được nó như mọi proxy khác.
- **Proxy**: tab mới **Đã mua** là cũng những proxy đó nhìn theo góc đã mua: còn bao nhiêu ngày, gia hạn ở đâu, **Xoay IP** miễn phí, và chuyển giữa HTTP với SOCKS5. Gia hạn giữ nguyên gói, quốc gia và kiểu xoay sẵn có.
- **Proxy**: proxy đã mua không tính vào giới hạn proxy của gói, và không sửa hay xóa được ở tab **Của tôi** — đó là session của đối tác, và nó tự rời danh sách khi hết hạn. Chọn hết rồi bấm xóa thì chỉ proxy của bạn bị xóa.
- **Agent**: xóa toàn bộ cuộc trò chuyện trong một lần, bằng nút ở cuối popover lịch sử. Cuộc trò chuyện đang chạy được giữ lại, và app nói rõ điều đó. Nút xóa trên header panel Agent không còn nữa; xóa từng cuộc vẫn ở từng dòng trong lịch sử.
- **Agent**: Claude lỗi thì tin nhắn hiện đúng câu nó trả về, thay vì một khối JSON. Khóa "another Claude Code process is refreshing" mồ côi được tự tháo rồi chạy lại một lượt, thay vì treo mãi. Lỗi dài không có dấu cách không còn tràn ra ngoài ô.
- **Profile, Tiện ích**: chữ gợi ý trong ô tìm kiếm không còn bị cắt mất một nửa.
- **Nhóm profile**: nút **Nhóm mới** trong dialog Quản lý nhóm không còn bị bóp xuống hai dòng.

### v1.0.0-beta.45 — 2026-11-05

**English**

- **Flows**: the **AI Vision** node works again, and it runs on an AI of your own. Point it at a screenshot, ask a question about it, and keep the answer in a variable for the nodes after it.
- **Flows**: the AI for flows is a list of its own, in **Settings → AI for flows**, separate from the Agent in the ✦ panel. Add an API key, or sign in to a Claude Code or Codex plan — each one signs in to its own account, so it leaves the Agent's alone. The key never leaves this computer.
- **Flows**: a flow names an **AI field** on its form, not an AI. Whoever runs the flow picks the AI behind that field, on their own computer. So a flow you share with your team or sell in the Store carries no key of yours, and a flow you buy runs on your own AI. What you pick there is the one thing in the form that no node can read.
- **Flows**: drop an AI Vision node and the editor declares the AI field for you and points the node at it. A flow that used this node in an older version needs it set again: open the node and pick its AI field.
- **Store**: a flow's page says you bring your own AI before you buy it.
- **Runs**: picking an AI that runs on a plan (Claude Code, Codex) for more than one profile now says what to expect — a plan allows one call at a time for the whole account, so the AI steps wait for each other instead of running side by side. An API key is what runs them in parallel.
- **Runs**: a run on a flow with no AI picked, or whose AI has been deleted, is refused before it starts and says which field to fill in, instead of failing on every profile at the node.
- **Editor**: the **Flow data** panel now folds to a strip with one button instead of closing, and the button for it on the toolbar is gone.

**Tiếng Việt**

- **Flow**: node **AI Vision** chạy lại được, và nó chạy bằng AI của chính bạn. Trỏ nó vào một ảnh chụp, hỏi một câu về ảnh đó, rồi giữ câu trả lời vào một biến cho các node sau dùng.
- **Flow**: AI dùng cho flow là một danh sách riêng, ở **Cài đặt → AI cho flow**, không liên quan Agent ở panel ✦. Thêm bằng khóa API, hoặc đăng nhập gói Claude Code / Codex — mỗi cái đăng nhập vào tài khoản riêng của nó, nên không ảnh hưởng tài khoản của Agent. Khóa không bao giờ ra khỏi máy này.
- **Flow**: flow khai một **ô cấu hình AI** trong form nhập, chứ không ghi một AI cụ thể. Người chạy flow mới chọn AI đứng sau ô đó, trên máy của họ. Nên flow bạn chia sẻ cho team hay bán ở Cửa hàng không mang theo khóa của bạn, còn flow bạn mua thì chạy bằng AI của bạn. Thứ bạn chọn ở ô đó là thứ duy nhất trong form mà không node nào đọc được.
- **Flow**: thả node AI Vision vào canvas thì editor tự khai ô cấu hình AI và trỏ node vào đó. Flow nào đã dùng node này ở bản cũ thì cần đặt lại: mở node ra và chọn ô cấu hình AI cho nó.
- **Cửa hàng**: trang của flow cho biết bạn cần có AI riêng trước khi mua.
- **Chạy**: chọn AI loại gói thuê tháng (Claude Code, Codex) cho nhiều profile thì giờ được nói trước — gói thuê tháng chỉ cho một lệnh tại một thời điểm trên cả tài khoản, nên các bước AI chờ nhau chứ không chạy song song. Muốn song song thì dùng AI kiểu khóa API.
- **Chạy**: lần chạy nào chưa chọn AI, hoặc AI đã bị xóa, bị từ chối ngay từ đầu và nói rõ cần điền ô nào, thay vì chạy rồi chết ở node AI trên từng profile.
- **Editor**: panel **Dữ liệu flow** giờ thu gọn thành một dải có một nút thay vì đóng hẳn, và nút bật/tắt nó trên thanh công cụ không còn nữa.

### v1.0.0-beta.44 — 2026-11-04

**English**

- **Flows**: a flow can now ask for input. Declare an input form (text, number, on/off, choice or list, each with a default) and every run asks for those values on the Run screen; a blank one takes the default. Nodes use them as `{{input.name}}`, so the same flow works for any keyword, link list or page count. The Agent can fill them in when it runs a flow for you.
- **Flows**: a flow can now give back a table. Declare its columns and write rows with the new **Write result row** node. Each run's rows show on the Run screen under **Result**, kept on this computer only, and export to Excel, CSV or JSON.
- **Flows**: nodes can pass data to each other through a shared memory. The new **Set memory** node sets a variable, appends to a list or adds to a number; **Save as variable** on the reading nodes keeps what they read; later nodes use it as `{{var.name}}`. **Loop** can now run once per item of a list, and **Extract text** can read every matching element or an attribute such as a link.
- **Editor**: the input form, shared memory and result table live in the new **Flow data** panel, left of the canvas, which also shows which nodes write and read each variable. Click a value there to insert it into the node field you were editing.
- **Store**: a flow's page in the Store, in the app and on the website, shows what you fill in and what you get before you buy it.
- **Profiles**: the selection bar no longer runs into the buttons on its right; buttons that do not fit move into its ⋯ menu.

**Tiếng Việt**

- **Flow**: flow giờ hỏi được dữ liệu đầu vào. Khai báo form nhập (văn bản, số, bật/tắt, chọn một hoặc danh sách, mỗi ô có giá trị mặc định) thì mỗi lần chạy sẽ hỏi các giá trị đó ở màn Chạy; ô để trống lấy giá trị mặc định. Các node dùng chúng bằng `{{input.tên}}`, nên một flow chạy được với bất kỳ từ khóa, danh sách link hay số trang nào. Agent điền được các ô này khi chạy flow giúp bạn.
- **Flow**: flow giờ trả về được một bảng. Khai báo các cột rồi ghi từng dòng bằng node mới **Ghi dòng kết quả**. Kết quả mỗi lần chạy hiện ở màn Chạy, mục **Kết quả**, chỉ lưu trên máy này, và xuất được ra Excel, CSV hoặc JSON.
- **Flow**: các node truyền dữ liệu cho nhau qua bộ nhớ chung. Node mới **Ghi bộ nhớ** gán biến, thêm vào danh sách hoặc cộng vào số; ô **Lưu vào biến** ở các node đọc dữ liệu giữ lại thứ chúng đọc được; node sau dùng bằng `{{var.tên}}`. **Loop** giờ chạy được một lượt cho mỗi phần tử của danh sách, và **Extract text** lấy được tất cả phần tử khớp hoặc một thuộc tính như link.
- **Editor**: form nhập, bộ nhớ chung và bảng kết quả nằm ở panel mới **Dữ liệu flow** bên trái canvas, cho biết node nào ghi và node nào đọc từng biến. Bấm vào một giá trị ở đó để chèn vào ô của node bạn đang sửa.
- **Cửa hàng**: trang của flow trong Cửa hàng, cả trong app lẫn trên website, cho biết bạn cần nhập gì và nhận được gì trước khi mua.
- **Profile**: thanh chọn nhiều không còn đè lên các nút bên phải; nút nào không đủ chỗ được dồn vào menu ⋯.

### v1.0.0-beta.43 — 2026-11-04

**English**

- **Profile groups**: file your profiles into groups. On the Profiles screen, the new **Groups** button in the toolbar creates groups, manages them (rename, delete) and picks which groups the list shows: tick the ones you want, or use **Only this**, **Show all** and **Hide all**. Your choice is kept the next time you open Broma.
- **Profile groups**: move profiles with **Move to group…** or **Remove from group** in a profile's ⋯ menu or in the selection bar, or pick a group when you edit a profile. A profile is in one group at most. The list has a new **Group** column, and search finds profiles by their group's name too. A new profile goes into the group on show when only one is.
- **Profile groups**: groups belong to the team and sync between computers, so everybody in the team sees the same groups. Owners and members can change them; viewers can filter by them. Deleting a group deletes no profile: its profiles become **Not grouped**.
- **Agent**: the Agent can list, create and rename groups and move profiles into them for you. It asks before deleting a group.
- **Agent**: choose how hard the model thinks with the new **Effort** chip under the chat box, or type `/effort`. Each agent keeps its own level; **Model default** leaves it to the model.
- **Agent**: a Codex agent now shows the email and ChatGPT plan it is signed in with, as a Claude Code agent does.
- **Agent**: the chat box no longer shrinks to a thin line when the Agent panel was closed as you signed in.

**Tiếng Việt**

- **Nhóm profile**: xếp profile vào nhóm. Ở màn Profile, nút **Nhóm** mới trên thanh công cụ dùng để tạo nhóm, quản lý nhóm (đổi tên, xóa) và chọn nhóm nào hiện trong danh sách: tick các nhóm muốn xem, hoặc dùng **Chỉ nhóm này**, **Hiện tất cả**, **Ẩn hết**. Lựa chọn được giữ cho lần mở Broma sau.
- **Nhóm profile**: chuyển profile bằng **Chuyển vào nhóm…** hoặc **Bỏ khỏi nhóm** trong menu ⋯ của profile hay trên thanh chọn nhiều, hoặc chọn nhóm khi sửa profile. Mỗi profile thuộc tối đa một nhóm. Danh sách có thêm cột **Nhóm**, và ô tìm kiếm cũng tìm theo tên nhóm. Profile mới tạo vào luôn nhóm đang hiện nếu chỉ có một nhóm hiện.
- **Nhóm profile**: nhóm thuộc về team và đồng bộ giữa các máy, nên mọi người trong team thấy chung các nhóm. Owner và member thay đổi được nhóm; viewer dùng nhóm để lọc. Xóa nhóm không xóa profile nào: profile trong nhóm về **Chưa có nhóm**.
- **Agent**: Agent có thể xem, tạo, đổi tên nhóm và chuyển profile vào nhóm giúp bạn. Agent hỏi trước khi xóa nhóm.
- **Agent**: chọn mức model nghĩ kỹ bằng chip **Effort** mới dưới ô chat, hoặc gõ `/effort`. Mỗi agent giữ mức của riêng nó; **Mặc định của model** để model tự quyết.
- **Agent**: agent Codex giờ hiện email và gói ChatGPT đang đăng nhập, giống agent Claude Code.
- **Agent**: ô chat không còn bị co lại thành một vạch mỏng khi panel Agent đang đóng lúc bạn đăng nhập.

### v1.0.0-beta.42 — 2026-11-02

**English**

- **Extensions**: install extensions on many profiles at once. Select the profiles on the Profiles screen, press **Add extensions** in the selection bar, then pick from your library, the Store, pasted Chrome Web Store links or files on this computer. A profile that has another version of an extension you pick from the library or a file gets the new one and keeps it switched on or off; an extension from the Store or a link is only added where it is missing. A profile that is open gets them the next time it opens.
- **Extensions**: each profile now keeps its own copy of its extensions, like its proxy. Adding an extension inside a profile no longer puts it in your library, and changing or deleting something in the library leaves your profiles as they are. To offer a profile's extension to your other profiles, press **Save to the library** next to it; to move profiles to the library's version, choose **Apply to profiles using it…** on that extension in the library.
- **Extensions**: the same extension added twice, say once as a .crx file and once as a folder, is now recognized as one, so it is kept and counted against your storage only once however many profiles use it. An extension from your computer that only a profile uses is uploaded only if that profile syncs.
- **Profile sync**: removing the last extension from a profile now reaches your other computers too.

**Tiếng Việt**

- **Tiện ích**: cài tiện ích cho nhiều profile cùng lúc. Chọn các profile ở màn Profile, bấm **Thêm tiện ích** trên thanh chọn nhiều, rồi chọn từ thư viện, cửa hàng, link Chrome Web Store hoặc tệp trên máy. Profile đang có bản khác của tiện ích bạn chọn từ thư viện hay từ tệp sẽ nhận bản mới và giữ nguyên bật/tắt; tiện ích từ cửa hàng hoặc link chỉ được thêm vào profile chưa có. Profile đang mở nhận tiện ích ở lần mở sau.
- **Tiện ích**: mỗi profile giờ giữ bản tiện ích của riêng nó, giống proxy. Thêm tiện ích trong profile không còn đưa vào thư viện, và sửa hay xóa trong thư viện không làm profile thay đổi. Muốn dùng tiện ích của một profile cho các profile khác, bấm **Lưu vào thư viện** cạnh tiện ích đó; muốn chuyển các profile sang bản trong thư viện, chọn **Áp dụng cho profile đang dùng…** ở tiện ích đó trong thư viện.
- **Tiện ích**: cùng một tiện ích thêm hai lần, ví dụ một lần bằng tệp .crx và một lần bằng thư mục, giờ được nhận ra là một, nên chỉ lưu và chỉ tính vào dung lượng một lần dù nhiều profile cùng dùng. Tiện ích từ máy tính mà chỉ một profile dùng chỉ được tải lên khi profile đó bật đồng bộ.
- **Đồng bộ profile**: gỡ tiện ích cuối cùng khỏi một profile giờ cũng cập nhật sang các máy khác.

### v1.0.0-beta.41 — 2026-10-31

**English**

- **Extensions**: a new browser engine stops extensions from reopening their welcome or help page every time you open a profile. They also keep their scheduled tasks, context menus and registered scripts between launches. New profiles get this engine automatically; for an existing profile, choose **Upgrade engine** from its ⋯ menu.
- **Profile sync**: more of an extension's data now travels with a synced profile: its registered scripts, network rules and the settings it keeps in sync storage.

**Tiếng Việt**

- **Tiện ích**: engine trình duyệt mới giúp tiện ích không còn mở lại trang chào hoặc trang hướng dẫn mỗi lần mở profile. Tiện ích cũng giữ được tác vụ đã hẹn, menu chuột phải và script đã đăng ký giữa các lần mở. Profile mới tự dùng engine này; với profile đã có, chọn **Nâng engine** trong menu ⋯ của profile.
- **Đồng bộ profile**: nhiều dữ liệu của tiện ích hơn giờ đi theo profile đồng bộ: script đã đăng ký, quy tắc mạng và cài đặt tiện ích lưu trong bộ nhớ đồng bộ.

### v1.0.0-beta.40 — 2026-10-31

**English**

- **Extensions**: extensions you add from inside a profile now always show in the Library tab of the Extensions screen, and the eye button is gone. Deleting one still tells you which profiles on this computer will lose it.
- **Extensions**: the add dialog in a profile now says clearly that what you add there also goes into your library right away, even if you don't save the profile.
- **Sync actions**: a following profile whose page is briefly busy now keeps up instead of losing actions or opening extra tabs. If a page still doesn't respond, that action is skipped rather than clicked blindly.

**Tiếng Việt**

- **Tiện ích**: tiện ích thêm từ trong profile giờ luôn hiện ở tab Thư viện của màn Tiện ích mở rộng, không còn nút con mắt. Khi xóa, Broma vẫn báo những profile nào trên máy này sẽ mất tiện ích đó.
- **Tiện ích**: hộp thoại thêm tiện ích trong profile giờ nói rõ tiện ích thêm ở đó cũng được đưa vào thư viện ngay, kể cả khi bạn không lưu profile.
- **Đồng bộ thao tác**: profile theo có trang đang bận trong chốc lát giờ vẫn theo kịp, không mất thao tác hay mở thừa tab. Nếu trang vẫn không trả lời, thao tác đó được bỏ qua chứ không bấm mù.

### v1.0.0-beta.39 — 2026-10-31

**English**

- **Extensions**: extensions you add from inside a profile no longer crowd the Library tab of the Extensions screen. On the computer where you added them they are hidden by default; press the eye button to show them. Adding the same extension from the Extensions screen brings it onto the list.
- **Extensions**: before you delete an extension, Broma now tells you how many profiles on this computer will lose it and names them.

**Tiếng Việt**

- **Tiện ích**: tiện ích thêm từ trong profile không còn làm đầy tab Thư viện của màn Tiện ích mở rộng. Trên máy đã thêm, chúng được ẩn theo mặc định; bấm nút con mắt để hiện. Thêm chính tiện ích đó từ màn Tiện ích mở rộng thì nó hiện lại trong danh sách.
- **Tiện ích**: trước khi xóa một tiện ích, Broma báo rõ bao nhiêu profile trên máy này sẽ mất nó và nêu tên các profile đó.

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
