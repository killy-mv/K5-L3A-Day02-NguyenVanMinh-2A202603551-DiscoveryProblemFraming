# Báo cáo cá nhân - 2A202603551_NguyenVanMinh


## 1. Thông tin sinh viên

- Họ và tên: Nguyễn Văn Minh
- Mã số sinh viên: 2A202603551
- Email (không bắt buộc):
- Tên nhóm: [CẦN ĐIỀN]
- Kho mã nguồn chung của nhóm: [CẦN ĐIỀN]

---

## 2. Rà soát vấn đề (CP1)

| STT | Góc nhìn | Job Story (nhu cầu trong tình huống cụ thể) | Người gặp vấn đề | Bằng chứng từ các sự việc từng trao đổi; thông tin còn thiếu |
|---:|---|---|---|---|
| 1 | Lặp lại | Khi cập nhật KillyTech cho màn hình điện thoại, tôi muốn xác định thành phần hoặc điểm ngắt giao diện (breakpoint) gây lỗi bố cục, để việc sửa lỗi không làm hỏng giao diện ở các kích thước màn hình khác. | Lập trình viên frontend của KillyTech | Trong tháng 10/2026 từng trao đổi về nhiều lỗi trên giao diện di động: chân trang, các thành phần chồng lấn và nút trở về đầu trang; ít nhất 3 nhóm lỗi. Cần xác nhận thời gian xử lý và ngày xảy ra chính xác. |
| 2 | Lặp lại | Khi cập nhật website có hai ngôn ngữ, tôi muốn kiểm tra bố cục ở cả hai phiên bản, để thay đổi ở một phiên bản không làm hỏng phiên bản còn lại. | Lập trình viên frontend quản lý giao diện Việt/Anh | Lỗi chân trang của trang Liên hệ bản tiếng Việt không phủ hết chiều rộng đã được báo riêng; website có 2 phiên bản ngôn ngữ (Việt/Anh). Chưa rõ số lần lặp lại và thời gian xử lý. |
| 3 | Tốn thời gian | Khi thay đổi giao diện website, tôi muốn tìm các kiểu CSS được viết cố định trong mã nguồn, để các trang có giao diện sáng và tối luôn đồng nhất. | Người bảo trì frontend | Từng trao đổi về lỗi định dạng ở chế độ tối của KillyTech (tháng 10/2026); chưa đo số bộ chọn CSS bị ảnh hưởng và thời gian xử lý. |
| 4 | Tốn thời gian | Khi lệnh đưa tệp vào vùng chờ commit của Git bị lỗi trên Windows, tôi muốn xác định tệp gây lỗi, để có thể commit mà không làm gián đoạn công việc. | Lập trình viên sử dụng Windows | Đã báo lỗi khi chạy lệnh `git add` trong tháng 10/2026; ít nhất 1 lần xảy ra. Cần kiểm tra nhật ký để xác nhận nguyên nhân và thời gian khắc phục. |
| 5 | Tốn thời gian | Khi ClickHouse không thực hiện được thao tác với hệ thống tệp trong WSL, tôi muốn xác định chính xác quyền truy cập không phù hợp, để khôi phục khả năng ghi mà không thay đổi cấu hình theo hướng thiếu an toàn. | Lập trình viên sử dụng ClickHouse/WSL | Từng gặp lỗi đổi tên tệp bị từ chối quyền (`Permission denied`) và các lỗi liên quan đến quyền truy cập (ít nhất 2 nhóm lỗi); chưa đo số lần xảy ra và thời gian xử lý. |
| 6 | Tổng hợp thông tin | Khi ứng dụng đang phát triển không kết nối được cơ sở dữ liệu, tôi muốn đối chiếu cổng mạng, trạng thái dịch vụ và quyền truy cập, để xác định đúng nguyên nhân sự cố. | Lập trình viên vận hành dịch vụ cục bộ | Các trao đổi trước đây có lỗi từ chối kết nối PostgreSQL ở cổng 5432 và lỗi kết nối ClickHouse; liên quan 2 hệ quản trị cơ sở dữ liệu. Chưa xác minh số phiên gỡ lỗi. |
| 7 | Tổng hợp thông tin | Khi nhận một repository bài lab có nhiều tài liệu hướng dẫn, tôi muốn đối chiếu yêu cầu thực hiện, tiêu chí chấm điểm và quy định nộp bài, để không bỏ sót yêu cầu. | Sinh viên thực hiện bài lab trên GitHub | Bài Day 02 có 5 tệp hướng dẫn cấp cao nhất (README, RULES, CHECKPOINTS, RUBRIC, SUBMISSION), cùng phiếu bài tập và ví dụ; sinh viên đã yêu cầu tóm tắt ngày 09/11/2026. Chưa rõ thời gian đọc thực tế. |
| 8 | Tổng hợp thông tin | Khi chuyển ứng dụng full-stack thành website chỉ có frontend, tôi muốn xác định dịch vụ và phần phụ thuộc không còn cần thiết, để bản build hoạt động mà không chứa tài nguyên dư thừa. | Người bảo trì KillyTech | Trước đây đã yêu cầu loại bỏ đăng nhập, trang quản trị (console), thanh toán, cơ sở dữ liệu, Docker và tệp `.env`: ít nhất 6 nhóm thành phần. Đây mới là một lần thay đổi phạm vi, chưa chứng minh được tính lặp lại. |

**Gợi ý từ AI và bước tự rà soát:** Các vấn đề trên do AI đề xuất dựa trên những trải nghiệm đã từng chia sẻ. Để tuân thủ quy định của bài lab là **tự rà soát trước khi dùng AI**, tôi cần tự liệt kê các vấn đề của mình, sau đó xác minh gợi ý nào thực sự phù hợp; những gợi ý không đúng phải được sửa hoặc loại bỏ. Hiện chưa có bằng chứng về khó khăn thực tế của người khác nên chưa tự tạo thêm mục «vấn đề của người khác». Vấn đề số 2 và 3 có phần trùng với số 1; số 4 và 6 cần nhật ký chi tiết; số 8 có vẻ là tình huống chỉ xảy ra một lần. AI gợi ý ba vấn đề ưu tiên là số 1, 7 và 5, nhưng lựa chọn cuối cùng phải do tôi quyết định.

---

## 3. Ba Problem Card ưu tiên và quy trình dự thảo (CP2)

**Tất cả quy trình dưới đây mới là phác thảo đề xuất, không phải ghi nhận đã đo đạc. Mọi con số thời gian có dấu ~ đều là giả thuyết và phải thay bằng số liệu đo thực tế. Các chỉ tiêu đặt ra là mục tiêu đề xuất, không phải kết quả đã đạt được.**

### Lựa chọn ba vấn đề ưu tiên

| Thứ tự | Vấn đề | Lý do đưa vào danh sách ưu tiên | Điểm chưa chắc chắn |
|---:|---|---|---|
| 1 | Lỗi giao diện responsive của KillyTech | Có biểu hiện lỗi UI cụ thể, quy trình có thể kiểm tra và người gặp vấn đề được xác định rõ. | Chưa chắc việc xác định nguyên nhân trong CSS là công đoạn tốn thời gian nhất. |
| 2 | Phải đối chiếu nhiều tài liệu hướng dẫn bài lab | Có repository thực tế để kiểm tra và có thể đo tỷ lệ bỏ sót yêu cầu. | Chưa rõ đây là khó khăn lặp lại hay chỉ là chi phí học tập một lần. |
| 3 | Lỗi quyền ghi tệp của ClickHouse | Có lỗi kỹ thuật từng được ghi nhận, các bước kiểm tra cụ thể và hướng xử lý an toàn không cần AI. | Chưa rõ tần suất tái diễn, nguyên nhân gốc và thời gian xử lý thực tế. |

### Problem Card số 1 – Lỗi bố cục responsive

| Trường thông tin | Nội dung |
|---|---|
| Job Story | Khi cập nhật KillyTech cho màn hình điện thoại, tôi muốn xác định thành phần hoặc breakpoint gây lỗi bố cục, để việc sửa lỗi không làm hỏng giao diện ở những kích thước màn hình khác. |
| Người gặp vấn đề | Lập trình viên frontend của KillyTech đang kiểm thử các trang Next.js; không mặc định là một khách hàng bên ngoài chưa được xác minh. |
| Bối cảnh | Khi thay đổi chữ, thẻ nội dung, thanh đầu trang hoặc chân trang, cần kiểm tra cả giao diện di động và máy tính. |
| Quy trình hiện tại (5 bước) | Nhận thấy lỗi ~3 phút → tái hiện trên kích thước màn hình điện thoại ~7 phút → kiểm tra DOM/CSS/breakpoint ~20 phút → chỉnh thành phần/CSS ~15 phút → kiểm tra hồi quy trên điện thoại và máy tính ~15 phút. Tổng ~60 phút (**toàn bộ chỉ là giả định**). |
| Điểm nghẽn | Bước 3: xác định xung đột CSS/breakpoint, ~20 phút (chưa xác minh). |
| Tác động | Phải sửa đi sửa lại, có nguy cơ phát sinh lỗi hồi quy và tốn thời gian bảo trì giao diện. |
| Chỉ số thành công | **Giả thuyết:** giảm thời gian sửa và xác minh mỗi lỗi từ ~60 phút xuống còn tối đa 30 phút. Dùng đồng hồ đo 5 trường hợp thực tế tiếp theo và theo dõi lỗi hồi quy. **Chưa đo số liệu ban đầu.** |
| Phương án không dùng AI | Danh sách kiểm tra breakpoint chuẩn, DevTools của trình duyệt, các biến thiết kế CSS và quy trình kiểm tra hồi quy theo kích thước màn hình. |
| Vai trò AI có thể có | Đề xuất nguyên nhân CSS dựa trên ảnh chụp màn hình và mã nguồn, nhưng lập trình viên phải xác minh; chưa chứng minh được sự cần thiết. |
| Đánh giá hướng can thiệp ban đầu | Chưa quyết định; thử danh sách kiểm tra / giải pháp không AI trước. |

Sơ đồ quy trình hiện tại (thời gian **chưa được đo**):

```text
[1. Phát hiện lỗi giao diện ~3 phút]
                  |
[2. Tái hiện trên màn hình cần kiểm thử ~7 phút]
                  |
[3. Xác định CSS/breakpoint xung đột ~20 phút] <-- ĐIỂM NGHẼN GIẢ ĐỊNH
                  |
[4. Chỉnh sửa thành phần/CSS ~15 phút]
                  |
[5. Kiểm tra lại trên di động và máy tính ~15 phút]
                  |
[Tổng minh họa ~60 phút: cần thay bằng thời gian thực tế]
```

### Problem Card số 2 – Đối chiếu hướng dẫn bài lab

| Trường thông tin | Nội dung |
|---|---|
| Job Story | Khi nhận một repository bài lab có nhiều tài liệu hướng dẫn, tôi muốn đối chiếu yêu cầu thực hiện, tiêu chí chấm điểm và quy định nộp bài, để không bỏ sót yêu cầu. |
| Người gặp vấn đề | Sinh viên đọc một bài lab mới trên GitHub. |
| Bối cảnh | Bắt đầu bài Day 02 với README, RULES, CHECKPOINTS, RUBRIC, SUBMISSION và các biểu mẫu. |
| Quy trình hiện tại (5 bước) | Xem cấu trúc repository ~3 phút → đọc README ~6 phút → đọc RULES và CHECKPOINTS ~12 phút → đối chiếu RUBRIC và SUBMISSION ~12 phút → lập rồi kiểm tra danh sách yêu cầu ~10 phút. Tổng ~43 phút (**giả định**). |
| Điểm nghẽn | Bước 4: đối chiếu tiêu chí đánh giá và yêu cầu nộp bài ~12 phút (chưa xác minh; bước 3 có thể tốn thời gian tương đương). |
| Tác động | Bỏ sót nhiệm vụ, đặt sai tên tệp, có nguy cơ vi phạm quy định và bị trừ điểm. |
| Chỉ số thành công | **Giả thuyết:** giảm thời gian lập danh sách yêu cầu từ ~43 phút xuống tối đa 20 phút, không bỏ sót yêu cầu bắt buộc nào. Bấm giờ thực tế và đối chiếu từng mục với tệp gốc. **Chưa đo số liệu ban đầu.** |
| Phương án không dùng AI | Duy trì danh sách kiểm tra theo checkpoint, dẫn chiếu tài liệu nguồn và rà soát thủ công theo rubric trước khi nộp. |
| Vai trò AI có thể có | Tóm tắt yêu cầu thành danh sách kiểm tra; sinh viên phải tự kiểm tra lại tài liệu gốc. |
| Đánh giá hướng can thiệp ban đầu | Có thể không cần AI; danh sách kiểm tra hoặc quy tắc đơn giản đã đủ. |

Sơ đồ quy trình hiện tại (thời gian **chưa được đo**):

```text
[1. Xem cây thư mục ~3 phút]
                  |
[2. Đọc README ~6 phút]
                  |
[3. Đọc RULES + CHECKPOINTS ~12 phút]
                  |
[4. Đối chiếu RUBRIC + SUBMISSION ~12 phút] <-- ĐIỂM NGHẼN GIẢ ĐỊNH
                  |
[5. Lập và kiểm tra danh sách việc cần làm ~10 phút]
                  |
[Tổng minh họa ~43 phút: cần thay bằng thời gian thực tế]
```

### Problem Card số 3 – Lỗi quyền truy cập hệ thống tệp ClickHouse

| Trường thông tin | Nội dung |
|---|---|
| Job Story | Khi ClickHouse không thực hiện được thao tác với hệ thống tệp trong WSL, tôi muốn xác định chính xác quyền truy cập không phù hợp, để khôi phục khả năng ghi mà không thay đổi cấu hình theo hướng thiếu an toàn. |
| Người gặp vấn đề | Lập trình viên cấu hình ClickHouse trong WSL/Linux. |
| Bối cảnh | Thao tác ghi hoặc đổi tên tệp thất bại và xuất hiện ngoại lệ `Permission denied`. |
| Quy trình hiện tại (6 bước) | Ghi nhận lỗi ~3 phút → kiểm tra nhật ký/đường dẫn ~8 phút → kiểm tra chủ sở hữu, tài khoản chạy dịch vụ và quyền truy cập ~18 phút → kiểm tra cấu hình lưu trữ/dịch vụ/mount ~12 phút → áp dụng thay đổi tối thiểu, an toàn ~10 phút → thử ghi lại ~7 phút. Tổng ~58 phút (**giả định**). |
| Điểm nghẽn | Bước 3: đối chiếu người dùng chạy dịch vụ với quyền của thư mục ~18 phút (chưa xác minh). |
| Tác động | Gián đoạn ghi dữ liệu, kéo dài thời gian gỡ lỗi và có nguy cơ cấp quyền quá rộng, thiếu an toàn. |
| Chỉ số thành công | **Giả thuyết:** giảm thời gian từ lần ghi thất bại đầu tiên đến khi thử ghi thành công một cách an toàn từ ~58 phút xuống tối đa 30 phút. Ghi thời điểm theo nhật ký và đếm số lần thay đổi không hiệu quả. **Chưa đo số liệu ban đầu.** |
| Phương án không dùng AI | Danh sách chẩn đoán gồm nhật ký, chủ sở hữu/nhóm, thư mục dữ liệu, tài khoản chạy dịch vụ, đường dẫn lưu trữ và mount; chỉ sửa theo nguyên tắc quyền tối thiểu. |
| Vai trò AI có thể có | Đề xuất thứ tự kiểm tra dựa trên nhật ký lỗi; không tự động chạy lệnh đặc quyền. |
| Đánh giá hướng can thiệp ban đầu | Danh sách kiểm tra / quy tắc có thể đã đủ; chưa có cơ sở chọn Agent. |

Sơ đồ quy trình hiện tại (thời gian **chưa được đo**):

```text
[1. Ghi nhận lần ghi thất bại ~3 phút]
                  |
[2. Đọc nhật ký và đường dẫn ~8 phút]
                  |
[3. Kiểm tra tài khoản dịch vụ/chủ sở hữu/quyền ~18 phút] <-- ĐIỂM NGHẼN GIẢ ĐỊNH
                  |
[4. Kiểm tra dịch vụ và lưu trữ/mount WSL ~12 phút]
                  |
[5. Áp dụng thay đổi quyền tối thiểu, an toàn ~10 phút]
                  |
[6. Thử ghi lại ~7 phút]
                  |
[Tổng minh họa ~58 phút: cần thay bằng thời gian thực tế]
```

### Problem Card dự kiến mang đi trình bày

- Thẻ vấn đề: số 1, chờ tôi xác nhận lựa chọn sau khi đối chiếu thực tế.
- Lý do: đã có lỗi giao diện nhìn thấy được và quy trình gỡ lỗi có thể đo lường. Có thể thử giải pháp danh sách kiểm tra không dùng AI trước.
- Câu hỏi cần phản biện: «Điểm nghẽn thực sự có phải là tìm xung đột CSS, hay là thiếu bước kiểm tra hồi quy responsive trước khi chấp nhận thay đổi?»

### Phản biện của AI (không đồng nghĩa sinh viên đã đồng ý)

| Điểm yếu được chỉ ra | Mức độ đồng ý của sinh viên | Thay đổi đề xuất / việc cần thực hiện |
|---|---|---|
| Người gặp vấn đề có thể bị mô tả nhầm thành khách hàng bên ngoài chưa được xác minh. | Cần tự xác nhận. | Giới hạn người gặp vấn đề ở lập trình viên sửa giao diện. |
| Chưa có dữ liệu thời gian chứng minh công đoạn gỡ lỗi nào dài nhất. | Cần đo thực tế. | Chia thành các bước và đánh dấu điểm nghẽn chỉ là giả thuyết. |
| Một danh sách kiểm tra có thể giải quyết vấn đề mà không cần AI. | Cần thử nghiệm. | Bổ sung phương án không AI; chưa vội lựa chọn Agent. |
| Số liệu thời gian ban đầu ước tính có thể bị hiểu nhầm là sự thật. | Đây là lo ngại hợp lý. | Đánh dấu tất cả thời gian và mục tiêu là minh họa, chờ kiểm chứng. |

---
## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Trình bày Problem Card | | |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: | |
| Nhận phản biện | Câu hỏi tôi nhận được: | Tôi đã sửa gì: |
| Gom nhóm vấn đề / cây OST | | |
| Chọn vấn đề ứng viên | | |
| Kiểm chứng / nghiên cứu | | |
| Quy trình nhóm | | |
| Phát biểu vấn đề (Problem Statement) | | |
| Mức can thiệp AI | | |
| Quyết định | | |

---

## 5. Dùng AI

| Mốc hoạt động | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Rà soát vấn đề | AI tổng hợp 8 vấn đề gợi ý từ những sự cố phát triển phần mềm từng được trao đổi trước đó. | Giúp diễn đạt Job Story theo người gặp vấn đề và chỉ ra những chỗ còn thiếu bằng chứng. | Một số ngày tháng, thời gian xử lý và tần suất chưa được xác minh; các gợi ý của AI không thay thế bước tự rà soát ban đầu. | Cần tự kiểm tra từng sự cố, tự rà soát vấn đề và thay các số liệu thiếu căn cứ trước khi nộp bài. |
| CP2 Problem Card | AI phác thảo 3 thẻ vấn đề, các quy trình và phần phản biện từ góc nhìn người quản lý sản phẩm. | Làm rõ các điểm nghẽn, ý tưởng về số liệu ban đầu/mục tiêu và phương án không dùng AI. | Thời gian đề xuất chỉ là giả định và các điểm nghẽn chưa được đo thực tế. | Cần tự rà soát các thẻ vấn đề, bấm giờ công việc thật, xác nhận thẻ muốn lựa chọn và ghi lại các quyết định thực tế của bản thân. |
| CP4 Research | | | | |
| CP5 Quy trình | | | | |
| CP5–6 Problem Statement | | | | |
| CP6 Mức can thiệp / quyết định | | | | |

---

## 6. Tự đánh giá (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe ba vấn đề ưu tiên của các bạn khác?**

**6.2. Nhóm có lúc nào bị "ưu tiên giải pháp trước" (solution-first: nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

---

## 7. Tài liệu tham khảo

-
