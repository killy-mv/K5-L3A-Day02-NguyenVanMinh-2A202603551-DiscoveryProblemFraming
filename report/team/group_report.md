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
**Ảnh ghi chú thảo luận candidate của nhóm (CP3):**

![Ảnh chụp ghi chú thảo luận các candidate: hóa đơn siêu thị, README nội bộ, đăng video, nguồn dựng video, học tập, deadline và ClickHouse](../assets/2d7665c9401ac044990b.jpg)

*Ảnh ghi lại các **chủ đề** nhóm đã nêu (đặc biệt các ý liên quan #1, #2, #4, #5, #7, #8 và #12). Ảnh không phải biên bản đầy đủ cả 12 Job Story hay bằng chứng phỏng vấn người dùng.*


**Nguồn:** Các ý #1–2, #4–5, #7–8 được người dùng thuật lại từ nhóm; #10–12 là ba candidate của Nguyễn Văn Minh. Các ý bổ sung #3, #6, #9 **đã được Nguyễn Văn Minh xác nhận đưa vào danh sách**. Bước nghẽn là nhận định ban đầu, chưa có số phút đo. Phần hỏi–đáp #1 do người dùng cung cấp; #2–#12 là phương án do AI đề xuất, không phải biên bản đối thoại đã diễn ra.

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | Nguyễn Đức Đạt | Khi đăng cùng một video lên nhiều nền tảng mạng xã hội, tôi muốn hoàn tất việc đăng đúng định dạng và thông tin, để tránh thao tác lặp lại và bỏ sót kênh. | Người sáng tạo nội dung | Chỉnh thông tin và upload riêng lên từng nền tảng | Xem phan hoi-dap #1 ben duoi |
| 2 | Nguyễn Đức Đạt | Khi dựng video cần âm thanh, hình ảnh và clip minh họa, tôi muốn tìm tư liệu phù hợp, có quyền sử dụng, để hoàn thành video mà không tốn nhiều thời gian tìm kiếm. | Người dựng video | Tìm, lọc và kiểm tra quyền dùng sound effect, ảnh, clip ngắn | Xem phan hoi-dap #2 ben duoi |
| 3 | Nguyễn Đức Đạt | Khi dựng video ngắn có lời thoại, tôi muốn tạo và đồng bộ phụ đề với thời điểm nói, để người xem hiểu nội dung khi tắt âm thanh. | Người dựng video ngắn | Nghe lại, chép lời, căn thời điểm phụ đề | Xem phan hoi-dap #3 ben duoi |
| 4 | Võ Công Minh | Khi mua thực phẩm ở siêu thị, tôi muốn biết tổng chi tiêu từ các hóa đơn mua hàng, để quản lý ngân sách thực phẩm chính xác. | Người mua hàng | Đọc, nhập và cộng từng khoản trên hóa đơn siêu thị | Xem phan hoi-dap #4 ben duoi |
| 5 | Võ Công Minh | Khi bắt đầu nhiệm vụ trong công ty có nhiều repository, tôi muốn tìm đúng hướng dẫn trong các README nội bộ, để hiểu dự án mà không cần hỏi đi hỏi lại. | Lập trình viên / nhân viên kỹ thuật | Tìm và đối chiếu thông tin giữa nhiều README | Xem phan hoi-dap #5 ben duoi |
| 6 | Võ Công Minh | Khi thư viện của dự án được cập nhật, tôi muốn xác định thay đổi nào ảnh hưởng tới mã nguồn hiện tại, để hạn chế lỗi sau nâng cấp. | Lập trình viên bảo trì dự án | Đọc changelog và đối chiếu thay đổi với các thành phần đang dùng | Xem phan hoi-dap #6 ben duoi |
| 7 | Tạ Tiến Dũng | Khi tự học nhiều chủ đề có độ khó khác nhau, tôi muốn biết trình độ hiện tại và bài học nên học tiếp, để tiến bộ có định hướng. | Sinh viên / người tự học | Đánh giá mức hiểu và chọn bài phù hợp | Xem phan hoi-dap #7 ben duoi |
| 8 | Tạ Tiến Dũng | Khi có nhiều bài tập và deadline, tôi muốn biết việc nào cần ưu tiên, để tránh trễ hạn và sử dụng thời gian hợp lý. | Sinh viên có nhiều bài tập | Tập hợp deadline, độ khó và ưu tiên từ nhiều nguồn | Xem phan hoi-dap #8 ben duoi |
| 9 | Tạ Tiến Dũng | Khi làm bài tập nhóm, tôi muốn biết ai đang phụ trách việc gì và phần nào còn thiếu, để nhóm phối hợp và nộp đúng hạn. | Thành viên nhóm học tập | Tổng hợp tiến độ từ chat, file và ghi chú rời rạc | Xem phan hoi-dap #9 ben duoi |
| 10 | Nguyễn Văn Minh | Khi kiểm tra KillyTech trên điện thoại, tôi muốn xác định thành phần và breakpoint gây lỗi giao diện, để sửa mà không làm hỏng kích thước màn hình khác. | Lập trình viên frontend | Dò CSS/breakpoint xung đột khi debug responsive | Xem phan hoi-dap #10 ben duoi |
| 11 | Nguyễn Văn Minh | Khi nhận repo lab có nhiều file hướng dẫn, tôi muốn đối chiếu yêu cầu, cách chấm và cách nộp, để không bỏ sót phần bắt buộc. | Học viên làm lab GitHub | Đối chiếu README, RULES, CHECKPOINTS, RUBRIC, SUBMISSION | Xem phan hoi-dap #11 ben duoi |
| 12 | Nguyễn Văn Minh | Khi ClickHouse trên WSL bị lỗi ghi dữ liệu, tôi muốn xác định quyền hoặc cấu hình gây lỗi, để khôi phục thao tác an toàn. | Lập trình viên sử dụng ClickHouse/WSL | Xác định quyền của service và thư mục dữ liệu | Xem phan hoi-dap #12 ben duoi |


**Phản biện theo từng candidate (người hỏi: Nguyễn Văn Minh).** Cặp #1 là nội dung người dùng xác nhận. Cặp #2–#12 là các câu hỏi và câu trả lời **do AI gợi ý để chuẩn bị và hoàn thiện phần phân tích**, không khẳng định đã diễn ra trong buổi thảo luận. Nếu cần minh chứng CP3, chỉ ghi nhận những trao đổi thực sự đã diễn ra.

**1. Người hỏi: Nguyễn Văn Minh** (đã được cung cấp)

- **Câu hỏi:** Tại sao không dùng AI để làm cho nhanh, tại sao lại dùng tools và code?
- **Trả lời đề xuất:** Dùng tools vì độ chính xác cao và hoàn toàn có thể tự làm được, không cần AI.

**2. Người hỏi: Nguyễn Văn Minh**

- **Câu hỏi:** Vì sao không tìm tư liệu bằng thư viện và từ khóa thay vì AI?
- **Trả lời đề xuất:** Có thể dùng thư viện và bộ lọc trước, vì dễ kiểm tra nguồn và giấy phép. Chỉ cân nhắc AI khi việc tìm kiếm thủ công thật sự tốn thời gian.

**3. Người hỏi: Nguyễn Văn Minh**

- **Câu hỏi:** Có cần tự xây AI tạo phụ đề khi phần mềm dựng video đã có chức năng này?
- **Trả lời đề xuất:** Nên thử tính năng sẵn có trước. Người dựng vẫn cần rà soát sai từ, tên riêng và thời điểm xuất hiện phụ đề.

**4. Người hỏi: Nguyễn Văn Minh**

- **Câu hỏi:** Nếu mục tiêu chỉ là cộng tiền hóa đơn, vì sao không dùng bảng tính?
- **Trả lời đề xuất:** Nếu chỉ cộng tổng, bảng tính hoặc máy tính đã đủ. Nhận diện hóa đơn tự động chỉ hữu ích khi có nhiều hóa đơn và người dùng cần nhập thường xuyên.

**5. Người hỏi: Nguyễn Văn Minh**

- **Câu hỏi:** Chatbot đọc README nội bộ có nguy cơ lộ dữ liệu công ty không?
- **Trả lời đề xuất:** Có, nếu gửi tài liệu sang bên thứ ba khi chưa được phép. Cần kiểm soát quyền truy cập, đồng thời thử cải thiện tài liệu và tìm kiếm nội bộ trước.

**6. Người hỏi: Nguyễn Văn Minh**

- **Câu hỏi:** Có thể dùng changelog và kiểm thử thay cho AI đánh giá tác động nâng cấp không?
- **Trả lời đề xuất:** Có. Đọc changelog, kiểm tra phụ thuộc và chạy test là căn cứ chính; AI chỉ hỗ trợ tóm tắt, không thể thay kết quả kiểm thử.

**7. Người hỏi: Nguyễn Văn Minh**

- **Câu hỏi:** Làm sao biết bài học gợi ý phù hợp nếu chưa có dữ liệu đánh giá trình độ?
- **Trả lời đề xuất:** Cần bài kiểm tra đầu vào và kết quả học tập. Nếu thiếu dữ liệu, nên bắt đầu bằng lộ trình học rõ ràng thay vì để agent tự suy đoán.

**8. Người hỏi: Nguyễn Văn Minh**

- **Câu hỏi:** Dùng lịch và nhắc việc đã đủ, tại sao phải dùng agent để quản lý deadline?
- **Trả lời đề xuất:** Lịch và quy tắc ưu tiên thường đáp ứng được phần lớn nhu cầu. Chỉ cân nhắc agent khi nhiều ràng buộc thay đổi phức tạp và có bằng chứng cách cũ không đủ.

**9. Người hỏi: Nguyễn Văn Minh**

- **Câu hỏi:** Nếu nhóm có bảng phân công chung, còn cần agent theo dõi tiến độ không?
- **Trả lời đề xuất:** Chưa chắc. Một bảng phân công có trách nhiệm rõ ràng và cập nhật đều đặn là giải pháp đơn giản hơn; cần xác minh vấn đề trước.

**10. Người hỏi: Nguyễn Văn Minh**

- **Câu hỏi:** Có chắc tìm lỗi CSS là bước lâu nhất, hay lỗi do thiếu kiểm thử responsive?
- **Trả lời đề xuất:** Chưa thể kết luận khi chưa bấm giờ. Nên đo từng bước và thử checklist breakpoint, DevTools cùng kiểm thử hồi quy trước.

**11. Người hỏi: Nguyễn Văn Minh**

- **Câu hỏi:** Nếu lập checklist theo rubric một lần là đủ thì có cần AI không?
- **Trả lời đề xuất:** Chưa chắc. Checklist thủ công có thể đủ nếu đề ít thay đổi; cần đo thời gian và số mục bị bỏ sót.

**12. Người hỏi: Nguyễn Văn Minh**

- **Câu hỏi:** Có nên để AI tự sửa permission của ClickHouse để nhanh hơn không?
- **Trả lời đề xuất:** Không nên khi chưa xác định nguyên nhân. Cần kiểm tra log, user service và quyền thư mục; con người phê duyệt thay đổi tối thiểu.

**Đối chiếu với báo cáo cá nhân sau khi hợp nhất các branch:** Bảng pitch này là danh sách candidate nhóm do Nguyễn Văn Minh cung cấp và xác nhận. Tuy nhiên, danh sách Top 3 Problem Card trong một số báo cáo cá nhân hiện khác với bảng pitch: Nguyễn Đức Đạt có card nghiên cứu đối thủ/xu hướng thay cho phụ đề; Võ Công Minh có card kiểm tra trợ lý sửa code và đọc repo thay cho cập nhật thư viện; Tạ Tiến Dũng có card ghi biên bản họp, tra cứu tài liệu và chọn tài liệu theo trình độ. **Cần từng thành viên xác nhận** đâu là ba candidate thực sự đã pitch; không nên mặc nhiên coi các gợi ý trong mục 2.1 là phát biểu đã xảy ra. Bản báo cáo cá nhân đã được giữ nguyên phần nội dung khi hợp nhất.

### 2.2. Cluster

Các candidate được gom theo **bối cảnh và pain chung**, không gom theo việc có sử dụng AI hay không. Số thứ tự đối chiếu với bảng pitch ở mục 2.1. Đây là cách phân nhóm được xây dựng từ danh sách đã xác nhận; nhóm có thể điều chỉnh nếu ghi chép thảo luận chi tiết cho kết quả khác.

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| **A — Sản xuất và xuất bản nội dung số** | **#1** Đăng video đa nền tảng; **#2** tìm tư liệu dựng video; **#3** tạo và đồng bộ phụ đề | Người làm nội dung gặp các thao tác thủ công khi chuẩn bị, hoàn thiện và phân phối video. Điểm chung là thời gian thao tác và yêu cầu kiểm tra đầu ra. |
| **B — Quản lý thông tin và công việc cá nhân/nhóm** | **#4** tổng hợp chi tiêu siêu thị; **#7** xác định lộ trình học; **#8** ưu tiên deadline; **#9** theo dõi tiến độ bài tập nhóm | Người dùng phải thu thập nhiều dữ liệu nhỏ, tổng hợp trạng thái và quyết định bước tiếp theo; độ phức tạp khác nhau nên chưa thể kết luận cùng một giải pháp. |
| **C — Tìm hiểu tài liệu và thay đổi kỹ thuật** | **#5** tra cứu README nội bộ; **#6** hiểu tác động cập nhật thư viện; **#11** đối chiếu hướng dẫn lab | Thông tin phân tán qua nhiều tài liệu; người đọc cần tìm đúng phần liên quan, đối chiếu các quy định hoặc thay đổi và tránh bỏ sót. |
| **D — Chẩn đoán lỗi trong phát triển phần mềm** | **#10** tìm nguyên nhân lỗi responsive; **#12** phân tích lỗi quyền ghi ClickHouse/WSL | Người phát triển cần tái hiện lỗi, khoanh vùng nguyên nhân, kiểm tra log/cấu hình và xác minh kết quả sau sửa. |

**Hướng hội tụ:** Theo kết quả nhóm đã ghi ở mục 1, candidate được chọn để đào sâu là **#1 — đăng video trên nhiều nền tảng mạng xã hội** (Cluster A). Lý do phân tích: actor và hành động lặp lại khá cụ thể; có thể mô tả từng bước đăng tải, đo thời gian và so sánh phương án sửa quy trình, Rule/tool với AI. Đây là cơ sở lý giải được đề xuất từ nội dung hiện có, **không phải bảng điểm hay lý do được xác nhận từ biên bản họp**; phần chấm điểm và loại candidate chính thức nằm ở mục 2.4.

### 2.3. Opportunity Solution Tree rút gọn

**Outcome duy nhất (cho candidate #1):** Giảm thời gian và sai sót khi một người đăng cùng một video lên nhiều nền tảng, đồng thời bảo đảm nội dung được đăng đủ kênh và đúng yêu cầu. **Cách đo dự kiến:** số phút từ lúc video sẵn sàng đến khi xác nhận đăng xong; số thao tác lặp; số lỗi/thiếu nền tảng trên mỗi lượt đăng. **Baseline và target:** chưa đo, cần bổ sung từ CP4–CP5.

```text
OUTCOME: Dang cung mot video len nhieu nen tang nhanh hon, it loi hon
|
+-- Opportunity A: Phai nhap lai tieu de, mo ta va thong tin dang tai
|                    nhieu lan cho cung mot video
|
+-- Opportunity B: Yeu cau ve dinh dang, ti le va truong thong tin
|                    khac nhau giua cac nen tang de gay sai sot
|
+-- Opportunity C: Kho kiem tra da dang thanh cong va dung kenh
                     khi phai theo doi tung nen tang rieng
```

Ba nhánh trên đều là **pain/nhu cầu**, không phải tên công cụ hay tính năng. Đây là những **giả thuyết xuất phát từ candidate #1**; cần kiểm chứng bằng quy trình đăng thực tế, log hoặc phỏng vấn người làm nội dung trước khi coi là pain đã được chứng minh.

**Những ý cần gạch khỏi tầng opportunity vì thực chất là solution:**

- “Dùng AI để tự upload video lên mọi nền tảng” — là một phương án giải quyết, không phải vấn đề của người đăng.
- “Viết tool hoặc code đăng video tự động” — là một phương án Rule/automation, không phải opportunity.
- “Xây agent tự quyết định thời điểm và kênh đăng” — là kiến trúc giải pháp, chưa chứng minh cần thiết.

**Liên hệ với quyết định No-Go hiện được ghi trong báo cáo:** Nhóm có thể quyết định **không dùng AI** cho khâu đăng tải nếu các thao tác cố định đã xử lý được bằng tool/code, có thể kiểm thử rõ và ít rủi ro hơn. Điều này **không phủ nhận pain** của người dùng; nó chỉ tách bài toán thực tế khỏi cách giải bằng AI. Quyết định cần được hỗ trợ thêm bằng chứng ở CP4 và phân tích rủi ro ở CP6.

### 2.4. Chấm điểm shortlist (1–5)

**Cách chấm:** Mỗi tiêu chí từ 1 (chưa rõ/yếu) đến 5 (rất rõ/tốt), tổng tối đa 35 điểm. Bảng dưới đây là **đánh giá đề xuất dựa trên 12 candidate ở mục 2.1**, không phải số điểm nhóm đã bỏ phiếu hay ghi lại trong buổi họp. Đặc biệt, ảnh ghi chú xác nhận các chủ đề được thảo luận nhưng **không chứng minh mức độ đau của người dùng**, nên tiêu chí "Pain có bằng chứng" hiện chỉ chấm 1/5 cho cả ba ứng viên. Nhóm cần đối chiếu và điều chỉnh điểm khi có dữ liệu kiểm chứng ở CP4.

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| **#1 — Đăng video lên nhiều mạng xã hội** | 5 | 5 | 1 | 5 | 5 | 5 | 4 | **30/35** |
| **#2 — Tìm tư liệu cho dựng video** | 5 | 4 | 1 | 4 | 4 | 4 | 3 | **25/35** |
| **#5 — Tra cứu nhiều README nội bộ** | 4 | 4 | 1 | 4 | 3 | 4 | 3 | **23/35** |

**Lý giải điểm số:**

- **#1:** Actor và các bước đăng tải rõ; có thể đo thời gian cho mỗi lượt đăng, số thao tác lặp và tỷ lệ đăng đúng kênh. Phạm vi dễ thu hẹp thành 2–3 nền tảng để khảo sát; đặc biệt phù hợp so sánh thao tác thủ công, công cụ/scripting và AI. Tuy nhiên chưa có log hay phỏng vấn chứng minh thời gian mất thực tế.
- **#2:** Người dựng video và pain tìm tư liệu khá cụ thể; có thể đo thời gian tìm được tài nguyên phù hợp. Việc đánh giá mức độ phù hợp, bản quyền, chất lượng và hiệu quả tìm kiếm phức tạp hơn khâu đăng video; chưa có bằng chứng số phút phải tìm.
- **#5:** Nhu cầu tìm thông tin trong README hợp lý với nhân viên kỹ thuật, nhưng phụ thuộc cấu trúc repository, quyền truy cập và bảo mật công ty. Trong phạm vi buổi lab khó có dữ liệu nội bộ hoặc đánh giá đầu ra đầy đủ. Chưa có phỏng vấn xác nhận pain từ nhân viên.

**Candidate được chọn:** **#1 — Rút ngắn và giảm sai sót khi đăng cùng một video lên nhiều nền tảng mạng xã hội.**

**Vì sao chọn:** Đây là candidate mà nhóm đã ghi nhận ở mục 1. Bài toán có hành động lặp lại, actor rõ và quy trình dễ mô tả; có thể phân biệt **vấn đề cần giải quyết** với **giải pháp AI**. Có khả năng kiểm thử một quy trình đăng thủ công rồi đối chiếu công cụ lập lịch hoặc rule/script, trước khi cân nhắc AI. Lựa chọn candidate để nghiên cứu **không đồng nghĩa** với việc chọn xây hệ thống AI. Quyết định **No-Go đối với AI** hiện được ghi ở mục 1 phù hợp với giả thuyết rằng thao tác có thể xử lý bằng tool/code; điều này vẫn cần được chứng minh ở CP4–CP6.

**Vì sao loại các candidate còn lại khỏi shortlist cuối:**

- **#2 — Tìm tư liệu dựng video:** Khó đặt tiêu chí "tư liệu phù hợp" thống nhất giữa các video và còn phải xác minh quyền sử dụng. Chưa có bằng chứng đủ mạnh về tần suất, thời gian và mức độ ưu tiên.
- **#5 — Tra cứu README nội bộ:** Cần quyền truy cập tài liệu công ty và xử lý bảo mật; đánh giá hiệu quả khó tiến hành đầy đủ nếu không có môi trường và người dùng thực tế.
- **Các candidate khác (#3, #4, #6–#12):** Không phủ nhận giá trị của chúng, nhưng trong một buổi lab việc thu thập bằng chứng và so sánh bốn mức can thiệp cho tất cả các chủ đề sẽ quá rộng. Những vấn đề như cộng hóa đơn hoặc quản lý deadline có thể bắt đầu bằng công thức, checklist và lịch; các vấn đề debug phần mềm cần log thực tế để xác định bottleneck.

**Xử lý bất đồng (nếu có):** Chưa có biên bản cụ thể về bất đồng hoặc kết quả bỏ phiếu. Nếu nhóm từng có ý kiến khác nhau, cần bổ sung đúng ý kiến, người tham gia và cách đi đến thống nhất; không giả định nhóm đã biểu quyết theo bảng điểm đề xuất này.

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
