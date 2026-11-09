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
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |
| 6 | | | | | |

*Điền 4–6 giả định; xóa dòng thừa.*

Giả định nhóm kiểm chứng trong buổi này:

### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn / Survey / Log, ticket, review

Interview snapshot (mỗi buổi phỏng vấn một bảng, hoặc đặt file trong `report/assets/cp4-interview-snapshot-N.md`):

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | |
| Câu nói đáng nhớ nhất (nguyên văn) | |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | |
| Hiện đang xử lý bằng cách nào (workaround)? | |
| Mất bao lâu, bao lần? | |
| Insight / opportunity rút ra | |

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| | | | |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |
| | | | | | |

---

## 4. Quy trình trước/sau (CP5)

**Bài toán phân tích:** Phân phối video Education Animation lên YouTube Shorts, TikTok và Instagram Reels, giảm thao tác nhập và cấu hình lặp lại.

**Trạng thái dữ liệu:** Các thời gian hiện tại do học viên cung cấp đều là ước lượng, chưa bấm giờ. Quy trình tương lai là phương án đề xuất, chưa thử nghiệm. Chưa xác định tần suất xuất bản. Nội dung phần này chưa thay thế kết quả chọn problem ở CP3 hoặc kiểm chứng ở CP4.

**Phạm vi so sánh:** Từ khi đã có file video hoàn chỉnh, được kiểm tra chất lượng, đến khi kiểm tra xong nội dung và trạng thái đăng/hẹn giờ trên cả ba nền tảng. Loại 10 phút xuất và kiểm tra video khỏi cả hai quy trình. Vì vậy, baseline trong phạm vi này là **110 phút/lần**, thay vì 120 phút của quy trình ban đầu có cả bước xuất video.

**Mục tiêu ưu tiên:** Chuẩn bị dữ liệu tại một nơi và giảm thao tác lặp; không bắt buộc ba nền tảng công khai cùng một thời điểm. Creator duyệt riêng nội dung và lịch đăng của từng nền tảng.

### 4.1. i) Quy trình hiện tại

**Actor chính:** Creator kênh Education Animation tự vận hành phân phối đa kênh (solopreneur).

```text
ĐẦU VÀO: Video đã hoàn chỉnh và được kiểm tra chất lượng

[1. Soạn tiêu đề, caption gốc, hashtag và chọn cover: 30 phút]
→ [2. Đăng và cấu hình YouTube Shorts: 25 phút]
→ [3. Điều chỉnh nội dung và đăng TikTok: 30 phút] ← VÙNG NGHI NGỜ NGHẼN
→ [4. Điều chỉnh nội dung và đăng Instagram Reels: 20 phút] ← CẦN ĐO THÊM
→ [5. Kiểm tra nội dung, hiển thị và trạng thái ba nền tảng: 5 phút]

TỔNG: 110 phút/lần xuất bản, theo ước lượng.
```

| Bước | Actor | Input | Công việc và Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | Creator | Video hoàn chỉnh, nội dung kiến thức | Viết tiêu đề, caption, hashtag và chọn cover → bộ thông tin đăng ban đầu | Khoảng 30 phút/lần xuất bản | Chưa tách thời gian viết, chọn hashtag và chọn cover. |
| 2 | Creator, nền tảng YouTube | Video và bộ thông tin ban đầu | Tải video, điền thông tin, cấu hình danh sách phát/lịch đăng theo nhu cầu → bài YouTube Shorts đã cấu hình | Khoảng 25 phút/lần xuất bản | Gồm thao tác và thời gian nền tảng xử lý; chưa tách riêng. |
| 3 | Creator, nền tảng TikTok | Video và bộ thông tin ban đầu | Điều chỉnh caption/hashtag, thiết lập nhạc nếu cần, tải và cấu hình đăng → bài TikTok đã cấu hình | Khoảng 30 phút/lần xuất bản | Vùng nghi ngờ nghẽn; chưa rõ thời gian chỉnh nội dung so với tải và cấu hình. |
| 4 | Creator, nền tảng Instagram | Video và bộ thông tin ban đầu | Điều chỉnh caption, chọn cover, tải và cấu hình đăng → bài Instagram Reels đã cấu hình | Khoảng 20 phút/lần xuất bản | Còn lặp lại việc chuyển dữ liệu và cấu hình trên giao diện khác. |
| 5 | Creator | Bài đăng và trạng thái từng nền tảng | Kiểm tra nội dung, hiển thị và trạng thái đăng/hẹn giờ → kết quả kiểm tra và lỗi cần xử lý | Khoảng 5 phút/lần xuất bản | Nếu hẹn giờ, kiểm tra cấu hình trước và kiểm tra công khai khi đến giờ; phần chờ đến giờ không tính vào thời gian thao tác. |

**Bottleneck chính — giả thuyết cần kiểm chứng:** Vùng bước 3–4 chiếm khoảng 50 phút, có nhiều thao tác điều chỉnh và đăng lặp lại. Chưa đủ cơ sở khẳng định sửa caption/hashtag là bước nghẽn chính vì chưa tách được: (a) chỉnh nội dung, (b) thao tác cấu hình, (c) chờ tải/xử lý video. Cần đo riêng từng phần; 50 phút không được coi là toàn bộ thời gian có thể loại bỏ bằng tự động hóa.

**Handoff:** Creator chuyển video và nội dung cho từng nền tảng, nhận trạng thái xử lý rồi tự kiểm tra. Không có người khác nhận bàn giao trong quy trình mô tả.

### 4.2. ii) Quy trình tương lai

**Phương án:** Template dùng chung + Rule hỗ trợ phân phối và theo dõi trạng thái. Creator tự viết và điều chỉnh nội dung; quy trình này không có bước AI tạo hoặc tối ưu caption/hashtag. Khả năng kết nối, đăng/hẹn giờ và các trường được hỗ trợ trên từng nền tảng phải được kiểm tra trước khi triển khai.

```text
[1. CON NGƯỜI: Chuẩn bị video và bộ nội dung cho từng nền tảng tại một nơi]
→ [2. CON NGƯỜI: Kiểm tra, sửa và duyệt riêng từng nền tảng]
→ [3. RULE: Kiểm tra điều kiện, gửi bản đã duyệt và ghi trạng thái từng kênh]
→ [4. CON NGƯỜI: Kiểm tra kết quả và xử lý ngoại lệ]

ĐIỂM KIỂM SOÁT: Chưa duyệt thì không gửi; sửa bản đã duyệt thì phải duyệt lại.
QUAY VỀ: Kết nối lỗi hoặc trường không được hỗ trợ → creator đăng/cấu hình thủ công.
```

| Bước | Phân công | Input | Công việc và Output | Thời gian / tần suất |
|---:|---|---|---|---|
| 1 | Con người | Video hoàn chỉnh, kiến thức trong video, template | Creator chuẩn bị tiêu đề, caption, hashtag, cover và lịch đăng riêng từng nền tảng trong một nơi → bộ dữ liệu đăng tập trung | Chưa ước lượng lại; thực hiện mỗi lần xuất bản. Không dùng thời gian của phương án AI cũ. |
| 2 | Con người — bước kiểm tra bắt buộc | Bộ dữ liệu từng nền tảng | Kiểm tra nội dung kiến thức, đúng file video, thông tin, cover và lịch đăng; sửa rồi duyệt riêng → các phiên bản được phép gửi | Chưa đo; gồm cả thời gian sửa trước khi duyệt. |
| 3 | Rule | Phiên bản đã duyệt, cấu hình nền tảng và kết nối hợp lệ | Kiểm tra trường bắt buộc theo cấu hình đã xác minh; gửi đăng/hẹn giờ; lưu mã bài và trạng thái từng nền tảng → kết quả thành công, thất bại hoặc đang xử lý | Chưa đo; phải tách thời gian điều phối khỏi thời gian chờ tải/xử lý. |
| 4 | Con người — bước kiểm tra sau gửi | Bài đăng, lịch đăng, trạng thái và thông báo lỗi | Kiểm tra nội dung/hiển thị, đối chiếu bản đã duyệt; xử lý kênh lỗi → xác nhận hoàn tất hoặc danh sách việc cần làm thủ công | Chưa đo; thời gian xử lý ngoại lệ ghi riêng. |

**Boundary:**

- Rule chỉ gửi phiên bản đã được creator duyệt cho đúng nền tảng và đúng lịch. Mỗi nền tảng có trạng thái duyệt riêng; thay đổi nội dung hoặc lịch sau duyệt phải duyệt lại.
- Rule không tự viết lại nội dung, thay hashtag, chọn nhạc hoặc thay đổi kiến thức trong video/caption.
- Chỉ tự động hóa những thao tác được kết nối hỗ trợ và đã kiểm tra; không giả định mọi thiết lập trên giao diện đều làm được qua công cụ/API.
- Nếu thiếu thông tin bắt buộc, kết nối không hợp lệ hoặc trạng thái bài trước chưa rõ, dừng riêng kênh đó để creator xử lý; không gửi lại một cách mù quáng.
- Creator giữ quyền quyết định xuất bản và chịu trách nhiệm kiểm tra kết quả.

**Phương án quay về khi nội dung, kết nối hoặc Rule có lỗi:**

- Nội dung chưa đạt: creator sửa thủ công theo template, duyệt lại rồi mới gửi.
- Kết nối không khả dụng hoặc trường cấu hình không được hỗ trợ: xuất bộ nội dung đã duyệt để creator đăng hoặc hoàn thiện cấu hình thủ công trên nền tảng đó.
- Một kênh thất bại: kiểm tra bài có được tạo chưa, giữ nguyên các kênh đã thành công và chỉ thử lại phần lỗi khi chắc chắn không tạo bài trùng.
- Phát hiện nội dung hoặc lịch đăng sai sau gửi: creator kiểm tra và sửa/hủy theo khả năng của nền tảng, ghi nhận lỗi để điều chỉnh quy trình.

### 4.3. iii) Before / after

Đếm các bước chính từ chuẩn bị thông tin đăng đến kiểm tra kết quả, trong cùng phạm vi đã nêu. Số bước ít hơn không tự chứng minh tiết kiệm thời gian; quy trình sau vẫn phải xử lý và theo dõi riêng từng nền tảng.

| Chỉ số | Trước — ước lượng | Sau — kỳ vọng, chưa đo | Ghi chú |
|---|---|---|---|
| Số bước chính | 5 | 4 | Gom thao tác phân phối ba kênh vào bước Rule, bổ sung điểm duyệt rõ ràng. |
| Tổng thời gian | Khoảng 110 phút/lần | Chưa ước lượng lại sau khi bỏ bước AI | Phải tính cả creator tự soạn nội dung, duyệt, hệ thống gửi/xử lý và kiểm tra; chưa có cơ sở chốt dưới 25 phút. |
| Thời gian con người trực tiếp thao tác | Chưa tách khỏi thời gian chờ trong 110 phút | Chưa đo | Đo riêng để tránh nhầm giảm công thao tác với giảm thời gian tải video. |
| Số bước cần thao tác thủ công | 5/5 | 3/4 khi kết nối đáp ứng yêu cầu | Creator vẫn chuẩn bị nội dung, duyệt và kiểm tra; khi kết nối lỗi phát sinh thêm thao tác thủ công. |
| Bottleneck chính | Nghi ngờ bước điều chỉnh/đăng TikTok và Instagram; chưa xác định phần chiếm nhiều thời gian nhất | Có thể còn ở soạn/duyệt nội dung hoặc chờ nền tảng xử lý | Bỏ AI nên phần sáng tạo và thích ứng nội dung vẫn do creator làm. |
| Rủi ro mới phát sinh | Creator thao tác trực tiếp từng kênh; vẫn có thể nhập nhầm | Gửi sai phiên bản, sai lịch, đăng trùng khi thử lại, kết nối hết hiệu lực hoặc chỉ thành công một phần | Kiểm soát bằng duyệt riêng từng kênh, lưu phiên bản/trạng thái và kiểm tra trước khi thử lại. |
| Phương án quay về | Creator đăng thủ công | Creator dùng bộ nội dung đã duyệt để đăng/cấu hình thủ công riêng kênh lỗi | Không yêu cầu làm lại các kênh đã thành công. |

**Cách đo tiếp theo:** Với mỗi lần xuất bản, ghi giờ bắt đầu/kết thúc cùng phạm vi; ghi riêng thời gian chuẩn bị nội dung, duyệt, cấu hình, chờ tải/xử lý, kiểm tra và sửa lỗi. Ghi số kênh thành công, số lần đăng trùng/sai lịch và số lần phải quay về thủ công. Đối chiếu các video có mức độ chỉnh sửa tương tự trước khi kết luận tiết kiệm thời gian. Nếu có hẹn giờ, ghi thời gian chờ đến lịch công khai riêng, không dùng để so sánh công thao tác.

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

-

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
