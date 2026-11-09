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

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```text

```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |

**Bottleneck chính:**

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text

```

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | | | |
| Tổng thời gian | | | |
| Số bước thủ công | | | |
| Bottleneck chính | | | |
| Rủi ro mới phát sinh | | | |

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

**Bài của nhóm nằm ở ô:** Độ mơ hồ thấp × Độ phức tạp trung bình.

**Vì sao:**

- **Độ mơ hồ thấp:** Người dùng đã xác định rõ nội dung cần đăng, các nền tảng đích và thông tin bài đăng. Hệ thống chỉ cần thực hiện những thao tác theo yêu cầu, không phải tự suy luận hay đưa ra quyết định thay người dùng.
- **Độ phức tạp trung bình:** Quy trình đăng tải có thể xác định trước, nhưng mỗi nền tảng mạng xã hội có API, cơ chế xác thực, định dạng nội dung và giới hạn riêng.
- **Tính lặp lại cao:** Các bước tải ảnh/video, nhập caption và đăng bài phải thực hiện nhiều lần trên những nền tảng khác nhau.

**Kết luận:** Bài toán phù hợp với công cụ tự động hóa theo quy tắc (Rule-based Automation), chưa cần tích hợp AI.

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | Sử dụng checklist, lịch đăng bài và bảng quản lý nội dung chung để hạn chế sai sót. | Khi số lượng nền tảng và tần suất đăng bài ít, người dùng có thể thao tác thủ công. | Vẫn phải đăng riêng trên từng nền tảng, chưa giảm đáng kể các thao tác lặp lại. | Không |
| **Rule** | Xây dựng công cụ cho phép tải nội dung một lần, chọn nền tảng, thiết lập thông tin và tự động gửi yêu cầu đăng bài theo quy trình cố định. | Khi người dùng chủ động quyết định nội dung và nền tảng, các thao tác có thể thực hiện qua API hợp lệ. | Giới hạn API, lỗi xác thực, khác biệt định dạng, đăng trùng hoặc đăng thất bại. | **Có** |
| **Workflow** | Kết hợp quy trình đăng bài cố định với AI để gợi ý caption, hashtag hoặc điều chỉnh nội dung theo từng nền tảng. | Khi người dùng có thêm nhu cầu xử lý hoặc tối ưu nội dung bằng AI. | Tăng chi phí, độ phức tạp và nguy cơ AI tạo nội dung không chính xác. | Không |
| **Agent** | AI tự lựa chọn nền tảng, thời điểm đăng, nội dung và công cụ cần sử dụng. | Khi bài toán thực sự yêu cầu lập kế hoạch và ra quyết định linh hoạt qua nhiều bước. | Khó kiểm soát hành động, có nguy cơ đăng sai nội dung, tăng chi phí và rủi ro bảo mật. | Không |

**Mức chọn:** **Rule — Rule-based Automation (không sử dụng AI).**

**Vì sao không chọn mức đơn giản hơn:**

Mức No AI chỉ giúp cải thiện cách tổ chức công việc bằng checklist hoặc lịch đăng bài, nhưng người dùng vẫn phải truy cập từng nền tảng và thực hiện các thao tác tương tự nhau.

Trong khi đó, Rule có thể tự động hóa những bước lặp lại theo quy trình cố định, giúp giảm thời gian thao tác mà không cần AI suy luận.

Vì vậy, Rule là mức can thiệp đơn giản nhất có khả năng giải quyết trực tiếp bottleneck của nhóm.

### 6.3. AI Canvas rút gọn

**Không áp dụng AI Canvas theo nghĩa dự đoán của AI**, vì nhóm lựa chọn Rule và không sử dụng mô hình AI.

Thay vào đó, nhóm mô tả các thành phần tương ứng của công cụ:

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | Không áp dụng. Hệ thống không sử dụng AI để dự đoán hoặc tạo nội dung; chỉ xử lý theo quy tắc đã lập trình. |
| **Judgment** — con người cân nhắc, quyết định gì? | Người dùng lựa chọn ảnh/video, caption, nền tảng đích và xác nhận trước khi đăng. |
| **Action** — hành động cuối cùng là gì, ai làm? | Công cụ gửi yêu cầu đăng bài đến các nền tảng được hỗ trợ thông qua API hợp lệ. Người dùng kiểm tra kết quả. |
| **Outcome** — đo kết quả bằng gì? | Thời gian đăng bài, tỷ lệ đăng thành công, độ chính xác nội dung và số thao tác thủ công được giảm. |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | Không có đầu vào cho AI. Công cụ cần file ảnh/video, caption, nền tảng đích, cấu hình đăng và quyền truy cập tài khoản. Người dùng cung cấp nội dung; quyền API cần được kiểm chứng. |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | Trạng thái trả về từ API, nhật ký lỗi, kết quả đăng bài và phản hồi trực tiếp của người dùng. |

### 6.4. Hai câu hỏi của Google PAIR

**Người dùng muốn được hỗ trợ (augment) hay giao hẳn việc (automate)? Bằng chứng:**

Nhóm định hướng **automate các thao tác đăng tải lặp lại**, nhưng vẫn giữ quyền quyết định nội dung và xác nhận đăng bài cho người dùng.

- Người dùng tự chọn nội dung và nền tảng.
- Công cụ tự động thực hiện các bước kỹ thuật sau khi được xác nhận.
- Người dùng theo dõi kết quả và xử lý khi có lỗi.

**Bằng chứng hiện có:** Nhóm đã xác định vấn đề thao tác đăng bài lặp lại và thống nhất hướng xây dựng công cụ không dùng AI. Chưa có kết quả phỏng vấn được cung cấp để khẳng định mức độ chấp nhận tự động hóa của người dùng.

**AI sai kiểu nào tệ hơn, báo nhầm hay bỏ sót? Vì sao, và thiết kế đã xử lý thế nào:**

Do không sử dụng AI, hai loại lỗi này được xem xét dưới góc độ lỗi tự động hóa:

- **Báo nhầm / thực hiện nhầm:** Công cụ báo đăng thành công khi thực tế thất bại, đăng sai tài khoản hoặc đăng sai nội dung.
- **Bỏ sót:** Công cụ không đăng lên một nền tảng đã chọn hoặc không ghi nhận tác vụ thất bại.

**Đánh giá:** Đăng nhầm nội dung hoặc sai tài khoản có thể nghiêm trọng hơn bỏ sót một bài đăng vì ảnh hưởng trực tiếp đến uy tín và quyền riêng tư của người dùng.

**Cách xử lý:** Yêu cầu xác nhận trước khi đăng, hiển thị tài khoản và nền tảng đích, theo dõi trạng thái từng tác vụ, ghi log và chỉ thông báo thành công khi có xác nhận phù hợp từ nền tảng. Cơ chế thử lại cần hạn chế nguy cơ đăng trùng.

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | Người sáng tạo nội dung, nhân viên marketing hoặc người quản lý nhiều tài khoản mạng xã hội. |
| **Quy trình** | Người dùng chuẩn bị ảnh/video và caption, sau đó truy cập từng nền tảng để tải nội dung, nhập thông tin, thiết lập tùy chọn và đăng bài. |
| **Bottleneck** | Phải thực hiện lặp lại các thao tác đăng cùng một nội dung trên nhiều nền tảng, gây mất thời gian và dễ sai sót. |
| **Impact** | Giảm hiệu suất làm việc, tăng thời gian quản lý nội dung, dễ đăng thiếu, đăng sai hoặc khó theo dõi trạng thái bài đăng. |
| **Success Metric** (baseline → target, cách đo) | **Giả định:** Giảm thời gian đăng cùng nội dung lên 3 nền tảng từ 15 phút xuống ≤ 5 phút. Đo bằng cách bấm giờ quy trình thủ công và quy trình sử dụng công cụ trên cùng các nền tảng được hỗ trợ. Mục tiêu tỷ lệ tác vụ đăng thành công ≥ 95%. |
| **Boundary** | Chỉ hỗ trợ nền tảng, loại tài khoản và định dạng có API cùng quyền đăng bài hợp lệ. Không tự tạo nội dung, không tự quyết định đăng bài, không vượt qua giới hạn của nền tảng. Người dùng phải xác nhận trước khi đăng. |
| **AI intervention point** | Không có điểm can thiệp AI. Công cụ tự động hóa các bước đăng tải sau khi người dùng chọn nội dung và nền tảng đích. |
| **Mức chọn** | **Rule — không sử dụng AI.** |
| **Rủi ro & người kiểm tra** | Rủi ro API, quyền truy cập, định dạng, bảo mật, đăng sai hoặc đăng trùng. Người dùng kiểm tra nội dung và kết quả; nhóm phát triển kiểm tra lỗi kỹ thuật và tính ổn định của hệ thống. |

**Thay đổi so với v0 và lý do:**

*Chưa có nguyên văn Problem Statement v0 của nhóm, vì vậy bảng dưới đây là các thay đổi đề xuất cần đối chiếu với v0 trước khi nộp.*

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| Actor | Người sử dụng nhiều nền tảng mạng xã hội. | Người sáng tạo nội dung, nhân viên marketing hoặc người quản lý nhiều tài khoản. | Xác định rõ đối tượng gặp vấn đề. |
| Quy trình | Phải đăng bài nhiều lần trên các nền tảng. | Làm rõ các bước chuẩn bị nội dung, truy cập, tải file, nhập thông tin và đăng bài. | Xác định chính xác vị trí phát sinh thao tác lặp lại. |
| Bottleneck | Đăng bài mất nhiều thời gian. | Lặp lại các thao tác tương tự trên từng nền tảng. | Làm rõ nguyên nhân chính. |
| Success Metric | Mong muốn tiết kiệm thời gian. | Đề xuất giảm từ 15 xuống ≤ 5 phút khi đăng lên 3 nền tảng. | Có chỉ số cụ thể để kiểm thử; số liệu hiện là giả định. |
| Boundary | Chưa xác định rõ. | Giới hạn theo API, loại tài khoản, định dạng và quyền truy cập. | Tránh đặt mục tiêu vượt khả năng kỹ thuật hoặc quy định nền tảng. |
| Mức can thiệp | Chưa xác định cụ thể. | Rule-based Automation, không tích hợp AI. | Phù hợp với tính chất lặp lại và quy trình xác định trước. |
| Kiểm soát và rủi ro | Chưa làm rõ. | Người dùng xác nhận trước khi đăng, công cụ ghi nhận trạng thái và lỗi. | Hạn chế đăng sai, đăng trùng và bảo vệ tài khoản. |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

Do nhóm **không sử dụng AI**, các tiêu chí được thay bằng tiêu chí đánh giá đầu ra của công cụ tự động hóa.

Các ngưỡng dưới đây là mục tiêu thử nghiệm giả định.

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | Thời gian đăng bài | Đăng cùng nội dung lên 3 nền tảng được hỗ trợ trong ≤ 5 phút. | Thời gian vượt 5 phút trong điều kiện kiểm thử đã xác định. |
| 2 | Tỷ lệ đăng thành công | ≥ 95% tác vụ đăng hợp lệ được nền tảng xác nhận thành công. | Tỷ lệ thành công dưới 95%. |
| 3 | Độ chính xác nội dung | ≥ 98% bài đăng đúng file, caption, tài khoản và nền tảng đã chọn. | Tỷ lệ chính xác dưới 98% hoặc phát sinh lỗi đăng nhầm nghiêm trọng. |
| 4 | Khả năng sử dụng | ≥ 90% người dùng thử nghiệm hoàn thành quy trình mà không cần hỗ trợ. | Dưới 90% người dùng hoàn thành độc lập. |
| 5 | Kiểm soát lỗi | Mỗi tác vụ có trạng thái rõ ràng; không ghi nhận trường hợp đăng trùng ngoài ý muốn trong bộ kiểm thử. | Có tác vụ mất trạng thái, báo thành công sai hoặc đăng trùng ngoài ý muốn. |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | **TB** | Nhóm đã xác định vấn đề thao tác lặp lại, nhưng chưa có số liệu được cung cấp về thời gian thực tế và mức độ sẵn sàng sử dụng công cụ. |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | **TB** | Không có đầu ra AI. Tuy nhiên, việc kết nối tài khoản, chọn nền tảng, kiểm tra nội dung và xử lý lỗi vẫn có thể gây khó khăn. |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | **Cao** | Chưa có bằng chứng kiểm chứng quyền đăng bài qua API của các nền tảng mục tiêu. Mỗi nền tảng có giới hạn kỹ thuật, định dạng và xác thực khác nhau. |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | **TB** | Cần tính chi phí máy chủ, lưu trữ, bảo mật, bảo trì API và tuân thủ chính sách nền tảng. Nhóm phát triển dự kiến vận hành trong giai đoạn thử nghiệm, chưa có kế hoạch vận hành dài hạn. |

### 8.2. Kết luận

**Quyết định: NOT YET**

**Lý do:**

Nhóm đã xác định được vấn đề thực tế cần nghiên cứu và lựa chọn hướng giải quyết phù hợp là Rule-based Automation, không cần AI.

Tuy nhiên, trước khi triển khai MVP đầy đủ, nhóm cần xác minh khả năng tích hợp API, quyền đăng tải, nhu cầu người dùng và hiệu quả tiết kiệm thời gian.

Rủi ro Feasibility hiện được đánh giá cao do chưa có kết quả thử nghiệm kỹ thuật được cung cấp. Vì vậy, lựa chọn Not Yet giúp nhóm kiểm chứng các giả định quan trọng trước khi đầu tư phát triển.

**Nếu Go — pilot nhỏ nhất:**

- Chọn 2 nền tảng mạng xã hội có API và quyền đăng bài phù hợp.
- Chỉ hỗ trợ một loại nội dung chung mà cả hai nền tảng chấp nhận.
- Xây dựng giao diện tải nội dung, nhập caption, chọn tài khoản và xác nhận đăng.
- Thực hiện đăng bài bằng API chính thức.
- Hiển thị trạng thái từng nền tảng.
- Kiểm thử với một nhóm nhỏ người dùng và so sánh thời gian với thao tác thủ công.

**Nếu Not Yet — cần kiểm chứng gì trước:**

1. Xác định các nền tảng mục tiêu và kiểm tra tài liệu API chính thức.
2. Xác nhận loại tài khoản, quyền truy cập và điều kiện đăng bài tự động.
3. Thử nghiệm đăng thành công lên ít nhất 2 nền tảng.
4. Phỏng vấn hoặc quan sát người dùng để xác nhận tần suất và thời gian thao tác lặp lại.
5. So sánh hiệu quả của công cụ với phương pháp thủ công.
6. Kiểm tra khả năng xử lý lỗi, bảo mật tài khoản và tránh đăng trùng.

**Nếu No-Go — nên làm gì thay AI:**

Nếu việc tích hợp đa nền tảng không khả thi, nhóm có thể chuyển sang công cụ hỗ trợ chuẩn bị nội dung tập trung: lưu file, quản lý caption, tạo checklist, lên lịch và theo dõi trạng thái đăng thủ công.

Đây vẫn là phương án không sử dụng AI và có thể giảm một phần công việc quản lý nội dung.

**Ngưỡng dừng** (các ngưỡng đề xuất cần nhóm thống nhất):

- **Sau giai đoạn kiểm chứng kỹ thuật ban đầu (đề xuất 1–2 tuần):** Nếu không thể đăng bài hợp lệ lên ít nhất 2 nền tảng mục tiêu, dừng phát triển tính năng đăng đa nền tảng và xem xét thu hẹp phạm vi.
- **Sau pilot nhỏ:** Nếu thời gian thao tác không giảm đáng kể so với cách thủ công, quay lại đánh giá bottleneck và giá trị của công cụ.
- **Nếu phát hiện nguy cơ bảo mật nghiêm trọng hoặc đăng nhầm không kiểm soát được:** Dừng thử nghiệm với tài khoản thật cho đến khi khắc phục.
- **Nếu chi phí và công sức bảo trì vượt nguồn lực nhóm:** Thu hẹp tính năng hoặc chuyển sang công cụ hỗ trợ quản lý nội dung không tự động đăng.

---

## 9. Hạn chế và hướng tiếp theo

**Hạn chế:**

- Chưa có số liệu thực tế đầy đủ về thời gian đăng bài và tần suất sử dụng của người dùng.
- Khả năng tích hợp phụ thuộc vào API, chính sách và quyền truy cập của từng nền tảng mạng xã hội.
- Mỗi nền tảng có yêu cầu riêng về định dạng video, hình ảnh, caption và loại tài khoản.
- Có thể phát sinh lỗi mạng, lỗi xác thực, giới hạn API hoặc đăng bài không thành công.
- Cần bảo vệ thông tin xác thực và hạn chế rủi ro đăng sai hoặc đăng trùng.
- Công cụ chưa hỗ trợ tạo nội dung, phân tích hiệu quả bài đăng hoặc đề xuất chiến lược bằng AI.
- Chưa có kết quả pilot để xác nhận các mục tiêu hiệu suất đã đề xuất.

**Hướng tiếp theo:**

1. Phỏng vấn người dùng thường xuyên quản lý nhiều tài khoản mạng xã hội.
2. Khảo sát API chính thức và điều kiện đăng bài của các nền tảng mục tiêu.
3. Xây dựng thử nghiệm kỹ thuật nhỏ để xác nhận khả năng tích hợp.
4. Thiết kế MVP với các chức năng đăng nội dung tập trung và theo dõi trạng thái.
5. Kiểm thử với người dùng thật, đo thời gian, độ chính xác và tỷ lệ thành công.
6. Đánh giá lại quyết định Go / Not Yet / No-Go dựa trên kết quả kiểm chứng.
7. Chỉ cân nhắc bổ sung AI trong tương lai nếu có nhu cầu được xác nhận như hỗ trợ viết caption, điều chỉnh nội dung hoặc phân tích hiệu quả đăng bài.

## 10. Tài liệu tham khảo

Các nguồn chính thức cần tham khảo và kiểm chứng khi xác định nền tảng hỗ trợ:

1. **Meta for Developers — Graph API:** https://developers.facebook.com/docs/graph-api/
2. **Instagram Platform Documentation:** https://developers.facebook.com/docs/instagram-platform/
3. **TikTok for Developers — Content Posting API:** https://developers.tiktok.com/doc/content-posting-api-get-started
4. **YouTube Data API — Videos:** https://developers.google.com/youtube/v3/docs/videos/insert
5. **Google PAIR Guidebook:** https://pair.withgoogle.com/guidebook/
6. **AI Canvas:** https://aicanvas.org/
