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

> **Nhật ký đóng góp đối chiếu từ repo và các yêu cầu tôi đã trực tiếp đưa ra.** Những nơi cần xác nhận việc phát biểu trực tiếp trong buổi họp hoặc thay đổi ý kiến thực tế được để rõ, không gán cho bản thân các hoạt động chưa có bằng chứng.

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| **Trình bày Problem Card (CP3)** | Chuẩn bị 3 candidate cá nhân: (1) tìm lỗi responsive KillyTech, (2) đối chiếu nhiều tài liệu hướng dẫn lab, (3) xử lý lỗi quyền ClickHouse trong WSL. Đưa 3 ý này vào bảng pitch nhóm ở mục 2.1. | Nhóm có đủ danh sách 12 candidate từ 4 thành viên để so sánh; các ý của tôi được xếp vào cluster tài liệu và debug phần mềm. **Cần tự xác nhận câu nào đã trực tiếp trình bày ở buổi họp.** |
| **Phản biện bài của bạn khác (CP3)** | Câu hỏi tôi đã cung cấp về candidate đăng video: **“Tại sao không dùng AI để làm cho nhanh, tại sao lại dùng tools và code?”** Câu trả lời được ghi trong nhóm: **“Dùng tools vì độ chính xác cao và hoàn toàn có thể tự làm được, không cần AI.”** | Làm rõ khả năng giải quyết bài toán đăng video bằng tool/code thông thường, thay vì mặc định chọn AI. Các câu hỏi #2–#12 ở báo cáo nhóm được AI đề xuất sau đó nên **không tính là phản biện thật nếu chưa diễn ra**. |
| **Nhận phản biện (CP3)** | Trong bảng pitch có các câu gợi ý từ Võ Công Minh về ba candidate của tôi: có chắc tìm CSS là bước nghẽn, có thật cần AI để đối chiếu rubric, và có nên cho AI tự sửa quyền ClickHouse. **Chưa có đủ bằng chứng các câu hỏi này thực sự được nêu trong cuộc họp.** | Các Problem Card đã thể hiện hướng giải thích thận trọng hơn: bottleneck là giả thuyết, cần đo thời gian, và ưu tiên checklist/Rule trước. **Để đạt yêu cầu phản biện thật, tôi cần thay bằng câu hỏi mình thực sự nhận và thay đổi do mình quyết định.** |
| **Gom nhóm vấn đề / cây OST (CP3)** | Tổng hợp 12 candidate thành 4 cluster: sản xuất video, quản lý công việc, đọc tài liệu, chẩn đoán lỗi kỹ thuật; bổ sung ảnh ghi chú trao đổi vào báo cáo; thiết kế OST xoay quanh pain khi đăng cùng video lên nhiều nền tảng. | Phân biệt rõ *opportunity* (thao tác lặp, sai cấu hình, khó kiểm tra trạng thái) với *solution* (AI, script hoặc agent). |
| **Chọn vấn đề ứng viên (CP3)** | Tổng hợp bảng so sánh 3 candidate #1 (đăng video), #2 (tìm tư liệu dựng video), #5 (tra cứu README) và lập luận ưu tiên candidate #1. Bảng điểm là **đánh giá đề xuất**, chưa được xác minh là điểm nhóm đã bỏ phiếu. | Chốt chủ đề để nhóm phân tích: giảm thao tác và sai sót khi phân phối cùng video lên nhiều nền tảng; không đồng nghĩa với quyết định phải dùng AI. |
| **Kiểm chứng / nghiên cứu (CP4)** | Hỗ trợ cấu trúc Assumption Map gồm 6 giả định, đọc đối chiếu tài liệu Buffer/Metricool và API các nền tảng; bổ sung các trường hợp trải nghiệm công khai làm tài liệu thứ cấp; chuẩn bị 3 case phỏng vấn **mô phỏng** (học viên, lab coach, nhân viên văn phòng). | Có dữ liệu để lập câu hỏi kiểm chứng và tín hiệu phản bác.  |
| **Quy trình nhóm (CP5)** | Theo dõi/đối chiếu hai phương án từ các nhánh: phương án có AI của Nguyễn Đức Đạt và quy trình Rule có duyệt nội dung, trạng thái từng kênh, fallback của Võ Công Minh; hỗ trợ tổng hợp bản nhóm. | Báo cáo xác định được bước con người chuẩn bị/duyệt/kiểm tra, bước Rule có thể xử lý và điều kiện quay về đăng thủ công.  |
| **Phát biểu vấn đề (CP5–CP6)** | Hỗ trợ rà soát tính thống nhất giữa Problem Statement v0 và v1, đặc biệt phạm vi đo từ lúc video đã hoàn tất tới khi xác nhận trạng thái đăng ba kênh; đưa vào bản tổng hợp target **110 → ≤85 phút/lượt**, đều là ước lượng chưa thử. | Làm rõ baseline, target, cách đo và ranh giới con người phê duyệt nội dung; tránh trình bày thời gian ước lượng như dữ liệu đo. |
| **Mức can thiệp AI (CP6)** | Đối chiếu lập luận No AI / Rule / Workflow / Agent với đặc điểm bài toán và các giới hạn API; đây là phần Tạ Tiến Dũng chủ trì trong bản nhóm. | Kết luận phù hợp với các thao tác xác định trước: ưu tiên Rule hoặc công cụ có sẵn, chưa đủ lý do xây agent tự quyết định. |
| **Quyết định (CP6)** | Hỗ trợ tổng hợp và kiểm tra tính nhất quán của kết luận đã ghi: **No-Go cho AI**, **Not Yet cho việc triển khai Rule tùy biến** nếu thiếu bằng chứng nhu cầu và quyền API. | Phân biệt được việc không cần AI với việc có nên lập trình công cụ mới ngay hay không; giữ các điều kiện pilot và ngưỡng dừng trong báo cáo nhóm. |

---

## 5. Dùng AI

> Ghi nhận trung thực việc sử dụng AI trong quá trình xây dựng tài liệu. Các mô tả dưới đây **không được dùng để nhận những phần do AI gợi ý là kết quả họp nhóm hay phỏng vấn thật**.

| Mốc hoạt động | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì / cần xác minh gì? |
|---|---|---|---|---|
| **CP1 — Rà soát vấn đề** | Nhờ AI tổng hợp 8 khó khăn kỹ thuật từng trao đổi (KillyTech, Git, ClickHouse, đọc repo). | Biến tình huống thành Job Story, gợi ý actor và dấu hiệu cần kiểm chứng. | Không có số phút hoặc tần suất thật cho nhiều vấn đề; không thể thay bước tự scan. | Giữ các tình huống có dấu vết, đánh dấu rõ sự kiện chưa đo; tự kiểm chứng lại trước nộp. |
| **CP2 — Problem Card** | Nhờ AI tạo cấu trúc 3 card, vẽ quy trình nháp và phản biện giả thuyết. | Chỉ ra bottleneck cụ thể, gợi ý cách đo và phương án không AI. | AI tự ước lượng 60/43/58 phút; các con số và bước nghẽn chưa được đo thật. | Ghi rõ toàn bộ là ước lượng, không coi là kết quả thực nghiệm; cần tự xác nhận thứ tự và bottleneck. |
| **CP3 — Tổng hợp tài liệu sau thảo luận** | Nhờ AI sắp xếp 12 candidate, hỗ trợ Cluster, OST, bảng shortlist và câu hỏi minh họa. | Giúp trình bày nhất quán problem → actor → bottleneck và tách pain khỏi solution. | AI đề xuất candidate #3/#6/#9 và một loạt câu hỏi, không có nghĩa là thành viên đã pitch hoặc hỏi nguyên văn như vậy. | Tôi xác nhận ba candidate bổ sung được đưa vào bảng; tách riêng câu hỏi tôi thực sự cung cấp với các câu do AI gợi ý. **CP3 live pitch/challenge không được dùng AI thay.** |
| **CP4 — Research** | Nhờ AI tổng hợp tài liệu công cụ quản lý nội dung và tài liệu API; chuẩn bị case mô phỏng và phân tích nguồn diễn đàn công khai. | Gợi ý giới hạn quyền đăng, rủi ro API và các tín hiệu phản bác về tần suất đăng hoặc thời gian chờ tải. | AI không thể tạo dữ liệu phỏng vấn thật. Case được viết giống Interview Snapshot có thể dễ bị hiểu nhầm là kiểm chứng thực tế. | Đặt nhãn **MÔ PHỎNG**, giữ số phỏng vấn/survey thật bằng 0; các nguồn diễn đàn được ghi là nghiên cứu thứ cấp. Cần đối chiếu từng link trước nộp. |
| **CP5 — Quy trình** | Nhờ AI hỗ trợ ghép bản CP5 từ các nhánh cá nhân và rà soát phạm vi before/after. | Làm nổi bật bước Rule, human approval, kiểm tra trạng thái, fallback khi API lỗi. | Quy trình AI và Rule ban đầu khác nhau; số 120 và 110 phút không cùng phạm vi và chưa được đo. | Giữ phương án Rule làm bản phân tích chính, lưu bản AI làm phương án so sánh; loại 10 phút xuất video khỏi cả hai phía. |
| **CP5–CP6 — Problem Statement** | Nhờ AI đối chiếu v0–v1, gợi ý rủi ro sai tài khoản/đăng trùng và cách kiểm tra metric. | Giúp xác định trường còn thiếu và giữ baseline/target trong cùng phạm vi. | Các target tiết kiệm thời gian chỉ là giả định; AI không xác nhận được công cụ đã hoạt động trên đủ các nền tảng. | Đánh dấu **110 → ≤85 phút/lượt** là baseline/target ước lượng, kèm điều kiện thử nghiệm và cách đo; quyết định cuối phải do nhóm tự chốt. |
| **CP6 — Mức can thiệp / quyết định** | Dùng AI hỗ trợ so sánh No AI / Rule / Workflow / Agent và kiểm tra tính logic giữa rủi ro với kết luận. | Nêu được lý do Rule có thể đủ cho thao tác cố định, không cần Agent. | AI không thể xác minh tính khả thi API thực tế hay thay nhóm quyết định Go/No-Go. | Giữ kết luận của nhóm **No-Go đối với AI; Not Yet đối với việc tự xây Rule**, chỉ triển khai sau khi thử công cụ/API và có bằng chứng người dùng. |

---

## 6. Tự đánh giá (CP7)

**6.1. Tôi học được gì khi nghe ba vấn đề ưu tiên của các bạn khác?**

Trong bảng tổng hợp của nhóm, các vấn đề không chỉ xuất phát từ lập trình mà còn liên quan đến sản xuất video, quản lý công việc và đọc tài liệu. Những đề xuất về đăng video và tìm tư liệu dựng video khác với vấn đề sửa giao diện responsive, tra cứu hướng dẫn hoặc xử lý lỗi ClickHouse mà tôi chuẩn bị. Sự khác biệt quan trọng là mỗi nhóm người có tình huống, tần suất và mức ảnh hưởng riêng; vì thế không thể chỉ dựa vào tên vấn đề hoặc việc có thể sử dụng AI để quyết định ưu tiên. Một vấn đề đáng chọn cần có người gặp vấn đề rõ ràng, bằng chứng về thao tác thực tế và khả năng đo lường.

Sau khi nghe Nguyễn Đức Đạat trình bày về các case liên quan đến edit video hay Võ Công Minh trình bày về các case khi mua hàng, tôi nhận ra vấn đề mà AI có thể được áp dụng để xử lý có thể rất đời thường, không cần phải là những vấn đề quá hàn lâm và máy móc.

**6.2. Nhóm có lúc nào bị “ưu tiên giải pháp trước” (solution-first) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

Trong danh sách ứng viên ban đầu có những cách gọi gắn sẵn giải pháp, chẳng hạn “AI upload video”, “AI tìm source” hoặc “agent hỗ trợ”. Những cách gọi này có nguy cơ khiến nhóm mặc định cần AI trước khi hiểu người đăng video đang khó ở đâu. Tài liệu nhóm về sau chuyển trọng tâm sang các thao tác đăng lặp lại, nguy cơ sai cấu hình và việc khó theo dõi trạng thái của từng nền tảng. Sau khi tách vấn đề khỏi giải pháp, nhóm mới có cơ sở so sánh đăng thủ công bằng checklist, sử dụng công cụ có sẵn, lập trình theo quy tắc và AI.

Sau khi nghe các case của mọi người, tôi thường có xu hướng đề xuất hoặc đào sâu vào phân tích vấn đề trước khi tán thành hoặc đề xuất giải pháp với mọi người.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

Trong phần CP3 có ghi lại câu hỏi tôi cung cấp về vấn đề đăng video: **“Tại sao không dùng AI để làm cho nhanh, tại sao lại dùng tools và code?”** Câu trả lời được ghi nhận là công cụ và mã nguồn thông thường có thể xử lý công việc theo quy tắc một cách chính xác, nên không nhất thiết phải đưa AI vào. Đây là một ví dụ cụ thể về việc thách thức lựa chọn giải pháp, đồng thời phù hợp với kết luận thận trọng của phần CP6: chưa có lý do để xây Agent chỉ nhằm tự động hóa các bước đăng đã xác định trước. Tuy nhiên, sau khi nghe Nguyễn Đức đạt trình bày lý do, tôi đã đồng ý rằng hướng dùng AI chưa thực sự tốt hơn dùng tool.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

Tài liệu nghiên cứu thứ cấp cho thấy người đăng nhiều video có thể thấy mệt vì phải thao tác trên nhiều nền tảng, nhưng không phải ai cũng gặp cùng một điểm nghẽn. Có trường hợp mất thời gian chỉnh nội dung cho từng mạng xã hội, có trường hợp phải chờ tải video và xử lý, và cũng có người đã sử dụng công cụ quản lý đa kênh. Việc xem xét Buffer, Metricool và tài liệu API cho thấy có nhiều khả năng hỗ trợ bằng công cụ sẵn có hoặc quy tắc cố định mà chưa cần đến AI. Vì vậy, nhóm cần kiểm tra riêng thời gian thao tác, thời gian chờ và việc xác nhận đăng thành công, thay vì kết luận ngay rằng mọi người đều cần AI để tự động đăng video.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

Điểm cần làm rõ trong Problem Statement là nối được **actor → quy trình → bottleneck → tác động → chỉ số → ranh giới can thiệp** mà không nhảy thẳng sang giải pháp. Với tình huống đăng video đa nền tảng, phạm vi đo phải nhất quán: bắt đầu từ lúc video đã sẵn sàng và kết thúc khi xác nhận trạng thái của ba kênh; không trộn thời gian quay hoặc dựng vào một phía của phép so sánh. Trong bản tổng hợp, mốc **110 phút/lượt → tối đa 85 phút/lượt** mới là giả định, không phải số đã bấm giờ. Một ranh giới quan trọng khác là nội dung phải được con người kiểm duyệt, xác nhận tài khoản và kiểm tra kết quả, tránh tự đăng nhầm hoặc đăng trùng. Nếu không nêu rõ những điều này, chỉ số sẽ khó kiểm chứng và giải pháp có thể tạo thêm rủi ro.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

Các khoảng trống còn thấy trong báo cáo gợi ý một thứ tự làm việc hợp lý hơn: tự xác minh các candidate và tình huống thực tế trước, hỏi những người ngoài nhóm thực sự đăng nhiều nền tảng, ghi thời gian từng bước, rồi thử template/checklist hoặc công cụ có sẵn trước khi đề xuất tự xây hệ thống. Đặc biệt cần tách công sức chuẩn bị nội dung khỏi thao tác tải lên và thời gian chờ nền tảng xử lý. Khi phản biện một giải pháp, cần hỏi về bằng chứng của điểm nghẽn, khả năng giải quyết bằng cách đơn giản hơn, điều kiện sử dụng API và rủi ro nếu đăng nhầm tài khoản hoặc trùng bài.

Nếu được làm lại, tôi sẽ dành nhiều tg hơn để khảo sát người dùng thực tế, ghi lại các case cụ thể hơn.

**6.7. Hiểu bài — tự giải thích bằng 5–8 câu, không nhìn tài liệu**

1. **Problem:** Người cần phân phối cùng một video lên nhiều nền tảng có thể mất công làm lại thao tác và theo dõi kết quả từng kênh.
2. **Quy trình:** Video hoàn tất → chuẩn bị mô tả/cấu hình → đăng trên các kênh → kiểm tra trạng thái từng nơi.
3. **Bottleneck:** Thao tác lặp và nguy cơ bỏ sót hoặc đăng nhầm; thời gian thao tác cần được đo riêng với thời gian chờ tải/xử lý.
4. **Metric:** Mốc 110 → ≤85 phút/lượt là **giả định cần kiểm chứng**, không được coi là kết quả thực nghiệm; còn phải theo dõi lỗi, đăng trùng và trạng thái đúng kênh.
5. **Boundary:** Con người phải duyệt nội dung và tài khoản trước khi đăng; hệ thống không được tự ý thay đổi nội dung, bỏ qua quyền hoặc đăng lại khi trạng thái chưa rõ.
6. **Mức can thiệp:** Ưu tiên cải thiện quy trình, công cụ có sẵn hoặc Rule; chưa có căn cứ để sử dụng AI/Agent cho các bước xác định trước.
7. **Quyết định:** Theo kết luận được tổng hợp trong báo cáo cá nhân, **No-Go với AI**, đồng thời **Not Yet** đối với việc tự xây Rule cho đến khi xác minh nhu cầu thực và quyền API.

---
## 7. Tài liệu tham khảo

-
