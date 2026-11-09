# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm:
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu):
- Quyết định cuối: Go / Not Yet / No-Go

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |
| 6 | | | | | |
| 7 | | | | | |
| 8 | | | | | |
| 9 | | | | | |
| 10 | | | | | |
| 11 | | | | | |
| 12 | | | | | |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A | | |
| B | | |
| C | | |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: 
├── Opportunity A: 
├── Opportunity B: 
└── Opportunity C: 
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

-

### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| | | | | | | | | |
| | | | | | | | | |
| | | | | | | | | |

**Candidate được chọn:**

**Vì sao chọn:**

**Vì sao loại các candidate còn lại:**

**Xử lý bất đồng (nếu có):**

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | Các video creator/editor khác cũng mất trên 45–60 phút mỗi lần đăng tải cùng một video lên 3 nền tảng (YouTube Shorts, TikTok, Instagram Reels) | Value | 5 | 2 | ✅ |
| 2 | Nút thắt gây tốn thời gian và mệt mỏi nhất là khâu tùy biến lại tiêu đề, hook, caption và bộ hashtag cho phù hợp văn hóa từng nền tảng, chứ không phải thao tác bấm nút upload file | Value | 5 | 2 | ✅ |
| 3 | Người xem trên TikTok, Reels và YouTube Shorts có phản ứng khác nhau rõ rệt với cùng một nội dung nếu không được tùy biến cách mở đầu (hook) và định dạng caption | Value | 4 | 3 | — |
| 4 | Việc sử dụng công cụ tự động hóa hoặc API bên thứ ba để đăng video không làm giảm tương tác tự nhiên (shadowban/bóp reach) so với việc đăng trực tiếp trên ứng dụng | Viability | 5 | 1 | ✅ |
| 5 | Các nền tảng mạng xã hội (YouTube, TikTok, Meta) cung cấp API ổn định cho phép tài khoản cá nhân upload và lên lịch tự động | Feasibility | 4 | 2 | ✅ |
| 6 | Creator sẵn sàng chấp nhận quy trình kiểm duyệt (review) 1 lần trên màn hình tập trung thay vì để hệ thống tự động đăng hoàn toàn | Usability | 3 | 4 | — |

*Điền 4–6 giả định; xóa dòng thừa.*

Giả định nhóm kiểm chứng trong buổi này: **Giả định #1, #2 và #4** (các giả định có độ quan trọng cao nhưng bằng chứng thực tế còn yếu).

### 3.2. Kiểm chứng

Cách đã dùng: **Phỏng vấn sâu theo The Mom Test (3 người)** + **Micro Poll (8 người trong lớp)**.

#### Interview snapshot 1:

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | Solo Creator kênh TikTok & YouTube Shorts giáo dục tài chính cá nhân (~18k followers) |
| Câu nói đáng nhớ nhất (nguyên văn) | *"Nhiều hôm dựng xong lúc 10h đêm mệt rã rời, định đăng cả 3 kênh nhưng mở TikTok lên chỉnh caption xong là muốn đi ngủ luôn, bỏ lỡ luôn YouTube với Instagram."* |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Tối thứ Năm tuần trước, dựng xong video phân tích lạm phát 45s, mất hơn 40 phút chỉ để đổi định dạng caption từ TikTok sang Reels và tìm lại hashtag phù hợp. |
| Hiện đang xử lý bằng cách nào (workaround)? | Tạo sẵn một ghi chú trong Apple Notes chứa khoảng 30 hashtag chung rồi mỗi lần đăng thì copy paste đại trà vào cả 3 app. |
| Mất bao lâu, bao lần? | Trung bình 45–50 phút cho mỗi video; 3 video/tuần (khoảng 2.5 tiếng/tuần chỉ để đăng). |
| Insight / opportunity rút ra | Nhu cầu phủ sóng đa nền tảng là có thật nhưng ma sát tâm lý (friction) ở khâu đổi văn phong caption khiến creator thường xuyên bỏ cuộc giữa chừng. |

#### Interview snapshot 2:

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | Freelance Video Editor kiêm quản trị viên kênh cho trung tâm Anh ngữ |
| Câu nói đáng nhớ nhất (nguyên văn) | *"Mỗi nền tảng có một gu riêng: TikTok thích giật gân hài hước, YouTube Shorts thích tò mò kiến thức, Instagram cần chia sẻ sâu sắc. Copy y nguyên 1 caption đăng cả 3 nơi là view tụt thảm hại."* |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Thứ Sáu vừa qua, phụ trách đăng 2 video ngắn lên hệ thống mạng xã hội của trung tâm, mất gần 2 tiếng đồng hồ vì phải viết lại 6 phiên bản caption khác nhau. |
| Hiện đang xử lý bằng cách nào (workaround)? | Dùng ChatGPT mở 1 tab riêng, copy kịch bản vào prompt: 'viết lại caption này cho TikTok/Reels', sau đó copy thủ công qua từng nền tảng. |
| Mất bao lâu, bao lần? | Khoảng 50–60 phút mỗi lần đăng 1 video đa kênh. |
| Insight / opportunity rút ra | Thao tác upload thuần túy không nặng bằng việc chuyển đổi "tone of voice" (ngữ điệu và cấu trúc text) cho từng tệp khán giả. |

#### Interview snapshot 3 (Tín hiệu phản bác):

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | Bạn sinh viên làm video vlog / giải trí đời sống cá nhân trên TikTok |
| Câu nói đáng nhớ nhất (nguyên văn) | *"Mình dựng bằng CapCut trên điện thoại xong có nút bấm chia sẻ thẳng lên TikTok trong 30 giây là xong, mình chẳng cần đăng lên nhiều nền tảng làm gì cho mệt đầu."* |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Không gặp vấn đề, chỉ tập trung làm 1 nền tảng duy nhất là TikTok. |
| Hiện đang xử lý bằng cách nào (workaround)? | Dùng tính năng Export to TikTok tích hợp sẵn của CapCut. |
| Mất bao lâu, bao lần? | 1–2 phút/lần đăng. |
| Insight / opportunity rút ra | **Tín hiệu phản bác:** Người làm nội dung giải trí thông thường hoặc kênh đơn lẻ không có nỗi đau này. Nhóm bắt buộc phải thu hẹp actor sang nhóm người sáng tạo nội dung giáo dục/thương hiệu có chiến lược đa kênh. |

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| Phỏng vấn sâu (The Mom Test) | 3 | 2/3 người khẳng định mất từ 40–60 phút/lần đăng và thừa nhận khâu tùy biến caption/hashtag là nút thắt mệt mỏi nhất | 1 người (làm vlog giải trí) cho biết chỉ đăng 1 kênh duy nhất qua CapCut và không có nhu cầu làm đa nền tảng |
| Micro Poll trong lớp | 8 sinh viên có kênh nội dung | 6/8 bạn từng cố gắng đăng video lên cả TikTok và Shorts nhưng bỏ cuộc sau vài tuần vì tốn thời gian format lại text | 2/8 bạn bày tỏ lo ngại sâu sắc rằng việc dùng công cụ tự động đăng tải bên thứ ba sẽ bị TikTok bóp tương tác (shadowban) |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**
1. **Thu hẹp tệp Actor:** Không làm cho đối tượng sáng tạo video giải trí ngẫu hứng, mà tập trung chính xác vào **Solo Creator / Video Editor kênh Education & Knowledge**, nơi nội dung đòi hỏi tính chính xác, phân phối đa kênh để tối đa hóa lượt tiếp cận và cần tùy biến thông điệp theo từng cộng đồng.
2. **Định hình lại trọng tâm bài toán:** Chuyển từ "tự động hóa bấm nút upload video" thành "**hỗ trợ tự động hóa việc tùy biến metadata (hook, caption, hashtag) từ kịch bản gốc và phân phối tập trung**".
3. **Thêm cơ chế phòng ngừa rủi ro (Boundary & Fallback):** Để giải quyết lo ngại bị bóp reach (tín hiệu phản bác ở poll), hệ thống tương lai sẽ không auto-publish ngầm, mà giữ chế độ tải video ở dạng bản nháp (Draft) hoặc webhook gửi thông báo về điện thoại để Creator bấm nút xác nhận cuối cùng trên app native nếu muốn an toàn 100%.

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| **Metricool** | https://metricool.com/ | Bước 3, 4, 5 (Lên lịch và đăng tải đa kênh tập trung từ 1 dashboard) | Quản lý đa nền tảng (YouTube, TikTok, Instagram, Facebook), kết nối API chính thống, có báo cáo phân tích trực quan | Tính năng AI Assistant chỉ viết lại câu chữ chung chung, không tự bóc tách ngữ cảnh kịch bản video giáo dục để tối ưu hook chuyên sâu; chi phí bản trả phí khá cao đối với sinh viên/solo creator | Không cần tự lập trình server publish video từ đầu, có thể học hỏi cách Metricool tổ chức giao diện quản lý lịch xuất bản đa kênh |
| **Repurpose.io** | https://repurpose.io/ | Bước 1 → 5 (Tự động lấy video từ kênh nguồn như TikTok để re-up sang YouTube Shorts và Instagram Reels) | Tự động hóa hoàn toàn 100% (Full Automate), không cần can thiệp thủ công sau khi setup quy trình | Sao chép nguyên xi caption và hashtag từ nền tảng gốc sang nền tảng đích (không đổi tone-of-voice); rủi ro dính logo/watermark; dễ bị thuật toán đánh giá là spam/re-up nội dung rác | **Bài học lớn:** Tự động hóa hoàn toàn (Automate) sẽ giết chết chất lượng nội dung. Bắt buộc phải đi theo hướng **Workflow (Augment)** có bước AI biến đổi văn phong và con người kiểm duyệt trước khi đăng |
| **Make.com (Integromat) + OpenAI API** | https://www.make.com/en/templates | Bước 2, 4 (Kịch bản tự động: nhận file/text → gửi OpenAI prompt sinh 3 format metadata → gửi webhook) | Cực kỳ linh hoạt, chi phí tính theo lượt chạy (pay-as-you-go) rất rẻ, dễ dàng tùy biến system prompt cho ngách giáo dục hoạt họa | Đòi hỏi kiến thức cấu hình kỹ thuật, token xác thực mạng xã hội (đặc biệt là TikTok/Meta) hay hết hạn và cần tạo tài khoản nhà phát triển (Developer Account) | Mượn kiến trúc tích hợp: dùng Rule/Webhook để trung chuyển dữ liệu và dùng LLM chuyên trách bước sáng tạo ngôn ngữ |

**Kết luận research:**
Thị trường đã có nhiều công cụ lên lịch (như Metricool, Buffer) hoặc re-up tự động (như Repurpose.io), nhưng đều bộc lộ điểm yếu chết người: hoặc chỉ đăng thủ công kèm text sơ sài, hoặc auto-copy nguyên xi làm tụt tương tác. Hướng đi đúng đắn nhất là: **Lấy kịch bản gốc → AI (LLM) tùy biến 3 phong cách caption/hashtag theo gu từng nền tảng → Creator review duyệt 1 chạm → Webhook/API đẩy sang chế độ hẹn giờ**.

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```text
HIỆN TẠI — 120 phút (2 tiếng/lần xuất bản video)

[1. Xuất file & kiểm tra lỗi video: 10']
→ [2. Soạn tiêu đề, caption gốc & hashtag chung: 30']
→ [3. Mở YouTube Studio, tải video, điền thẻ tag & hẹn giờ: 25']
→ [4. Mở TikTok, viết lại caption ngắn & dò hashtag trend: 30'] ← BOTTLENECK CHÍNH
→ [5. Mở Meta Business Suite, sửa caption Reels & link bio: 20']
→ [6. Mở điện thoại kiểm tra hiển thị trên 3 app: 5']
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | Solo Creator | File project Premiere/CapCut hoàn chỉnh | File video `.mp4` chuẩn tỉ lệ 9:16 | 10 phút / lần | Kiểm tra lại lỗi âm thanh, phụ đề trước khi xuất |
| 2 | Solo Creator | Ý tưởng kịch bản video giáo dục | Bản nháp tiêu đề, mô tả gốc, ảnh cover | 30 phút / lần | Soạn thảo trên Notion / Google Docs |
| 3 | Solo Creator | File video `.mp4` + mô tả gốc | Video tải lên YouTube Shorts (chế độ riêng tư/hẹn giờ) | 25 phút / lần | Chọn danh sách phát, gắn thẻ tag SEO, kiểm tra bản quyền |
| 4 | Solo Creator | File video `.mp4` | Video tải lên TikTok (chờ duyệt) | 30 phút / lần | **BOTTLENECK:** Viết lại caption ngắn hook giật gân, lướt tìm 4–5 hashtag trending |
| 5 | Solo Creator | File video `.mp4` | Video tải lên Instagram Reels | 20 phút / lần | Sửa lại format caption chia sẻ, kêu gọi comment, gắn link bio, chọn cover frame |
| 6 | Solo Creator | 3 ứng dụng di động (YT, TikTok, IG) | Video hiển thị chuẩn trên feed | 5 phút / lần | Kiểm tra xem tiêu đề có bị che bởi nút bấm UI của app không |

**Bottleneck chính:**
Bước 4 & 5 (viết lại caption, tìm hashtag phù hợp với thuật toán và thị hiếu từng nền tảng). Mất tới 50 phút chỉ để "xào xáo" lại cùng một nội dung video kiến thức cho hợp phong cách từng mạng xã hội.

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text
TƯƠNG LAI — khoảng 20 phút/lần

[1. Đẩy video & mô tả gốc lên Dashboard: 2']                 ← CON NGƯỜI
→ [2. Tự động sinh 3 bản metadata tối ưu cho từng nền tảng: 1'] ← AI (LLM)
→ [3. Creator review, chỉnh sửa nhanh & bấm Duyệt: 15']       ← CON NGƯỜI (HITL - chốt chặn chất lượng)
→ [4. Tự động publish/hẹn giờ lên YT, TikTok, IG: 2']        ← RULE / SCRIPT (API Webhook)

BOUNDARY: AI không tự ý publish khi chưa có xác nhận từ Creator; không tự bịa link/tài trợ.
PHƯƠNG ÁN QUAY VỀ: Nếu API lỗi hoặc AI sinh caption quá nhạt → Creator copy caption gốc đăng thủ công theo cách cũ.
```

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | 6 bước | 4 bước | Tích hợp tập trung vào 1 giao diện |
| Tổng thời gian | 120 phút | ~20 phút | Giảm ~83% thời gian đăng bài |
| Số bước thủ công | 6/6 bước | 2/4 bước | Con người chỉ nạp input và kiểm duyệt output |
| Bottleneck chính | Viết lại caption & dò hashtag từng nơi (50') | Creator kiểm tra và tinh chỉnh bản nháp (15') | Nút thắt trở thành chốt chặn kiểm soát chất lượng |
| Rủi ro mới phát sinh | Không có (chỉ tốn sức người) | AI sinh caption sai lệch kiến thức hoặc giật tít quá đà; token API mạng xã hội bị hết hạn | Xử lý bằng **Human-in-the-loop** bắt buộc và hệ thống cảnh báo token |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | Solo Creator kiêm Video Editor đang tự vận hành một kênh về **Education Animation**, chịu trách nhiệm toàn bộ từ khâu nội dung, hậu kỳ đến phân phối video trên đa nền tảng (YouTube Shorts, TikTok, Instagram Reels). |
| **Quy trình** | Sau khi dựng xong video: xuất file `.mp4` → soạn tiêu đề và caption gốc → mở lần lượt từng nền tảng (YouTube Studio, TikTok Web, Meta Business Suite) → gõ lại caption, tìm lại hashtag và cấu hình metadata riêng cho từng nền tảng → kiểm tra lại hiển thị thực tế trên điện thoại. |
| **Bottleneck** | Bước viết lại caption và điều chỉnh định dạng/hashtag riêng cho từng nền tảng (mất 50 phút trên tổng 120 phút), do mỗi mạng xã hội có thói quen đọc, độ dài text và thuật ngữ phân phối hoàn toàn khác nhau. |
| **Impact** | - Mất 120 phút (2 tiếng) cho mỗi video xuất bản; với tần suất 3 video ngắn/tuần, creator mất tới **6 tiếng/tuần** chỉ cho việc copy-paste và căn chỉnh format.<br>- Thường xuyên lỡ "khung giờ vàng" (19h–20h) tiếp cận người xem.<br>- Rất dễ dẫn đến sai sót (nhầm hashtag, sai link bio, định dạng lỗi) do kiệt sức sau khi dựng video. |
| **Success Metric** (baseline → target, cách đo) | - **Baseline:** 120 phút/lần đăng tải lên 3 nền tảng (đo bằng việc tự bấm giờ ghi lại trong 2 tuần gần nhất).<br>- **Target:** Dưới 25 phút/lần đăng tải; 100% video xuất bản đúng khung giờ hẹn; tỉ lệ lỗi format/nhầm hashtag = 0.<br>- **Cách đo:** Creator tự ghi log thời gian thao tác và kiểm tra chất lượng bài đăng trong 4 tuần thử nghiệm. |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | - AI chỉ hỗ trợ tạo bản nháp metadata (tiêu đề, caption, hashtag); AI **tuyệt đối không được tự động xuất bản (auto-publish)** trực tiếp lên kênh nếu chưa có xác nhận từ Creator (Bắt buộc Human-In-The-Loop).<br>- AI **không được tự bịa** thông tin khoa học, nguồn tham khảo hoặc cam kết thương mại.<br>- AI **không tự xử lý** các kháng nghị bản quyền (copyright dispute). |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

| Điểm yếu / Lỗ hổng phản biện chỉ ra | Đồng ý? | Nhóm xử lý / Sửa gì ở v1 |
|---|---|---|
| Metric hiện chỉ đo về tốc độ (120' → 25'), thiếu đo lường chất lượng: nếu caption AI viết khuôn mẫu làm giảm 50% view thì sao? | Đồng ý | Sẽ bổ sung metric chất lượng ở v1: Tỷ lệ retention xem video không giảm, và Creator không phải viết lại quá 20% nội dung nháp của AI |
| Nghi vấn về Bottleneck: 120' có bao gồm thời gian render video và nghẽn băng thông mạng khi upload không? AI không giải quyết được việc này | Đồng ý một phần | Bóc tách rõ: 10' render là cố định, bottleneck 50' thực chất là khâu "nhận thức & sáng tạo text" (cognitive load). Sẽ giữ phạm vi bài toán tập trung vào việc tùy biến metadata đa kênh |
| Rủi ro nền tảng (Platform risk): TikTok/Instagram hay siết API bên thứ ba hoặc bóp reach video auto-upload | Đồng ý | Đưa rủi ro này vào Assumption Map và ma trận rủi ro (Feasibility/Viability); chuẩn bị sẵn phương án dùng webhook đẩy bản nháp về app để người dùng bấm nút đăng native |
| Liệu có đang nhảy sang AI quá sớm khi chỉ cần Rule (bảng Google Sheets mẫu)? | Đồng ý một phần | Quy trình tương lai sẽ kết hợp cả hai: Dùng Rule cho việc lưu trữ mẫu cấu trúc và đẩy API, chỉ dùng AI (LLM) duy nhất cho bước biến đổi ngôn ngữ/văn phong (tone-of-voice) từ kịch bản gốc sang phong cách từng nền tảng |

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô:

Vì sao:

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | | | | |
| **Rule** | | | | |
| **Workflow** | | | | |
| **Agent** | | | | |

**Mức chọn:**

**Vì sao không chọn mức đơn giản hơn:**

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | |
| **Judgment** — con người cân nhắc, quyết định gì? | |
| **Action** — hành động cuối cùng là gì, ai làm? | |
| **Outcome** — đo kết quả bằng gì? | |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng:
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào:

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** | |
| **AI intervention point** | |
| **Mức chọn** | No AI / Rule / Workflow / Agent |
| **Rủi ro & người kiểm tra** | |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| | | | |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | | | |
| 2 | | | |
| 3 | | | |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | | |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | | |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | | |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | | |

### 8.2. Kết luận

**Quyết định:** Go / Not Yet / No-Go

**Lý do:**

**Nếu Go — pilot nhỏ nhất:**

**Nếu Not Yet — cần kiểm chứng gì trước:**

**Nếu No-Go — nên làm gì thay AI:**

**Ngưỡng dừng** (nếu sau … mà … thì quay về …):

---

## 9. Hạn chế và hướng tiếp theo

-

## 10. Tài liệu tham khảo

-
