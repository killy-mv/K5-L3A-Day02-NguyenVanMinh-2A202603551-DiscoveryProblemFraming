# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: **[Chưa được cung cấp — cần nhóm điền]**
- Thành viên: xem `TEAM.md`
- Candidate problem nhóm chọn (1 câu): Giảm thao tác lặp lại và sai sót khi đăng cùng một video lên nhiều nền tảng mạng xã hội.
- Quyết định cuối: No-Go

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch
**Ảnh ghi chú thảo luận candidate của nhóm (CP3):**

![Ảnh chụp ghi chú thảo luận các candidate: hóa đơn siêu thị, README nội bộ, đăng video, nguồn dựng video, học tập, deadline và ClickHouse](../assets/2d7665c9401ac044990b.jpg)

*Ảnh ghi lại các **chủ đề** nhóm đã nêu (đặc biệt các ý liên quan #1, #2, #4, #5, #7, #8 và #12). Ảnh không phải biên bản đầy đủ cả 12 Job Story hay bằng chứng phỏng vấn người dùng.*


**Nguồn:** Các ý #1–2, #4–5, #7–8 được người dùng thuật lại từ nhóm; #10–12 là ba candidate của Nguyễn Văn Minh. Các ý bổ sung #3, #6, #9 **đã được Nguyễn Văn Minh xác nhận đưa vào danh sách**. Bước nghẽn là nhận định ban đầu, chưa có số phút đo.

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


**Phản biện theo từng candidate.**

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

**10. Người hỏi: Võ Công Minh**

- **Câu hỏi:** Có chắc tìm lỗi CSS là bước lâu nhất, hay lỗi do thiếu kiểm thử responsive?
- **Trả lời đề xuất:** Chưa thể kết luận khi chưa bấm giờ. Nên đo từng bước và thử checklist breakpoint, DevTools cùng kiểm thử hồi quy trước.

**11. Người hỏi: Võ Công Minh**

- **Câu hỏi:** Nếu lập checklist theo rubric một lần là đủ thì có cần AI không?
- **Trả lời đề xuất:** Chưa chắc. Checklist thủ công có thể đủ nếu đề ít thay đổi; cần đo thời gian và số mục bị bỏ sót.

**12. Người hỏi: Võ Công Minh**

- **Câu hỏi:** Có nên để AI tự sửa permission của ClickHouse để nhanh hơn không?
- **Trả lời đề xuất:** Không nên khi chưa xác định nguyên nhân. Cần kiểm tra log, user service và quyền thư mục; con người phê duyệt thay đổi tối thiểu.


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

**Liên hệ với quyết định No-Go hiện được ghi trong báo cáo:** Nhóm có thể quyết định **không dùng AI** cho khâu đăng tải nếu các thao tác cố định đã xử lý được bằng tool/code, có thể kiểm thử rõ và ít rủi ro hơn. Điều này **không phủ nhận pain** của người dùng; nó chỉ tách bài toán thực tế khỏi cách giải bằng AI.

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


---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

> **Trạng thái bằng chứng (09/11/2026):** Mục này tổng hợp giả định từ CP3, quy trình CP5 và quyết định Rule/No-Go đối với AI ở CP6, đồng thời bổ sung **research từ tài liệu chính thức**.

### 3.1. Assumption Map

Thang điểm 1–5: **Quan trọng** càng cao thì giả định sai càng ảnh hưởng đến quyết định; **Đã có bằng chứng** càng cao thì càng có nguồn thực tế hỗ trợ. Bằng chứng là tài liệu sản phẩm/API **chỉ xác nhận năng lực hoặc giới hạn kỹ thuật**, không xác nhận nhu cầu người dùng.

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | Creator thực sự phải đăng cùng video lên từ hai nền tảng trở lên đủ thường xuyên để thao tác lặp trở thành vấn đề đáng giải quyết. | Value | 5 | **1** — mới có candidate và trao đổi nội bộ, chưa hỏi người dùng đích | **Có — phỏng vấn người đăng video thật** |
| 2 | Bước nghẽn chính là nhập/chỉnh metadata và cấu hình đăng lặp lại, chứ không chủ yếu là sáng tạo caption hoặc chờ tải/xử lý video. | Value | 5 | **1** — CP5 mới có ước lượng, chưa bấm giờ từng bước | **Có — quan sát 2–3 lượt đăng thực tế** |
| 3 | Creator chấp nhận chuẩn bị nội dung một lần, duyệt **riêng từng kênh** và kiểm tra trạng thái sau khi gửi. | Usability | 4 | **1** — phương án thiết kế, chưa thử với người dùng | **Có — thử quy trình mẫu với người dùng** |
| 4 | Có công cụ sẵn giúp quản lý và lên lịch video cho YouTube Shorts, TikTok và Instagram Reels mà không phải tự phát triển AI. | Feasibility | 5 | **3** — tài liệu chính thức của Buffer, Metricool mô tả các kênh/định dạng hỗ trợ; chưa thử tài khoản nhóm | Có — đối chiếu gói và định dạng thực tế |
| 5 | Nếu tự viết Rule/script, nhóm có thể đăng hợp lệ bằng API cho loại tài khoản, quyền và định dạng cần dùng trên ít nhất hai nền tảng. | Feasibility | 5 | **2** — tài liệu API có hướng dẫn nhưng chưa được cấp quyền hoặc thử nghiệm | **Có — kiểm tra quyền và thử đăng trên tài khoản test** |
| 6 | Chi phí phần mềm, bảo mật token, rủi ro đăng sai/trùng và công bảo trì đủ thấp để giải pháp có lợi hơn cách thủ công. | Viability | 4 | **1** — chưa có đối chiếu chi phí và log lỗi | Có — so sánh chi phí/rủi ro sau thử nghiệm |

**Giả định ưu tiên kiểm chứng:** #1 và #2 (có *pain* thật và bottleneck nào cần giải), song song với #5 (quyền đăng bài qua API). Nếu người dùng đăng rất ít hoặc phần lớn thời gian dành cho biên tập nội dung, việc tự xây công cụ đăng video có thể không đáng đầu tư, kể cả khi API cho phép.

**Đã kiểm tra được qua desk research:** Tồn tại giải pháp bên thứ ba cho đăng/lên lịch nhiều kênh; API chính thức hỗ trợ đăng nội dung trong điều kiện nhất định, nhưng quyền, loại tài khoản, định dạng và tính năng riêng của nền tảng có giới hạn. **Chưa kiểm chứng trong buổi này:** nhu cầu, tần suất và thời gian thật của creator; khả năng tích hợp trên tài khoản cụ thể; mức độ chấp nhận của người dùng.

### 3.2. Kiểm chứng — phân tích ba tình huống mô phỏng

**Mục tiêu giả lập:** Thử xem cùng một bài toán “đăng một video lên nhiều mạng xã hội” có gây pain tương tự đối với người đăng ít (học viên), người đăng video giảng dạy (lab coach) và người làm công việc đăng tải thường xuyên (nhân viên văn phòng) hay không. Các câu hỏi dựa trên tinh thần *The Mom Test*: hỏi lần làm gần nhất và cách xử lý thực tế trong **kịch bản giả định**, không hỏi “Bạn có muốn dùng AI không?”.

#### Case 1 — Học viên đăng video demo dự án

| Trường | Nội dung tình huống giả định |
|---|---|
| **Vai trò** | Học viên ngành CNTT; thỉnh thoảng đăng clip demo bài tập lên TikTok và Instagram Reels |
| **Tình huống gần nhất** | Sau khi hoàn thành video demo khoảng một phút, học viên đăng TikTok, sau đó mở Instagram và tải lại cùng file |
| **Quy trình đã giả lập** | Xuất video → lưu caption vào Notes → đăng TikTok → sửa vài hashtag → đăng Instagram → kiểm tra hai bài |
| **Workaround** | Copy/paste caption từ Notes, không dùng công cụ quản lý đa nền tảng |
| **Tần suất / thời gian** | **Số liệu giả định:** 1–2 video/tháng; khoảng 10–15 phút cho thao tác đăng hai kênh, chưa tính dựng |
| **Lời nói minh họa (không phải trích dẫn thật)** | “Mình ít đăng nên làm thủ công vẫn ổn; dựng và chỉnh video lâu hơn nhiều so với upload.” |
| **Insight** | **Tín hiệu phản bác:** Không phải ai đăng nhiều nền tảng cũng cần tool; ở tần suất thấp, lợi ích tự động hóa có thể nhỏ hơn công thiết lập |

- **Hỏi:** “Lần gần nhất bạn đăng cùng video lên nhiều nơi, bạn làm những bước nào?” — **Đáp:** “Đăng TikTok trước, rồi copy caption sang Instagram và tải video lên lần nữa.”
- **Hỏi:** “Phần nào mất thời gian nhất?” — **Đáp:** “Phần dựng và sửa phụ đề; upload lên hai nơi không quá lâu.”

#### Case 2 — Lab coach chia sẻ video hướng dẫn

| Trường | Nội dung tình huống giả định |
|---|---|
| **Vai trò** | Lab coach chuẩn bị clip hướng dẫn sửa lỗi bài thực hành cho học viên |
| **Tình huống gần nhất** | Sau buổi lab, coach đăng video giải thích lỗi thường gặp lên YouTube Shorts và Facebook |
| **Quy trình đã giả lập** | Kiểm tra lại nội dung chuyên môn → soạn tiêu đề/mô tả và liên kết tài liệu → đăng lên hai kênh → kiểm tra link, caption và hiển thị |
| **Workaround** | Template mô tả sẵn, checklist nguồn tham khảo và bước duyệt thủ công |
| **Tần suất / thời gian** | **Số liệu giả định:** 1–2 video/tuần; khoảng 25–40 phút cho chuẩn bị thông tin và đăng, không tính quay/dựng |
| **Lời nói minh họa (không phải trích dẫn thật)** | “Tôi có thể dùng mẫu để đỡ nhập lại, nhưng vẫn phải tự kiểm tra nội dung và đường dẫn trước khi đăng.” |
| **Insight** | **Tín hiệu hỗn hợp:** Có thao tác lặp nhưng độ chính xác là ưu tiên; hệ thống tự đăng khi chưa được duyệt có thể gây hại hơn việc tiết kiệm vài phút |

- **Hỏi:** “Ở lần đăng clip hướng dẫn gần nhất, phần nào bạn phải kiểm tra lại?” — **Đáp:** “Tôi rà nội dung kỹ thuật, tiêu đề và link tài liệu cho mỗi kênh.”
- **Hỏi:** “Bạn đã dùng cách gì để bớt thao tác?” — **Đáp:** “Tôi có mẫu mô tả chung và checklist, nhưng vẫn phải duyệt cuối.”

#### Case 3 — Nhân viên văn phòng phụ trách nội dung

| Trường | Nội dung tình huống giả định |
|---|---|
| **Vai trò** | Nhân viên văn phòng kiêm đăng video truyền thông cho một bộ phận nhỏ |
| **Tình huống gần nhất** | Một tuần cần đăng nhiều video sự kiện lên Facebook Reels, TikTok và YouTube Shorts; một kênh từng bị bỏ sót trong bảng theo dõi |
| **Quy trình đã giả lập** | Nhận file đã duyệt → chuẩn bị caption theo từng kênh → tải video riêng → kiểm tra lịch → cập nhật bảng trạng thái |
| **Workaround** | Google Sheets theo dõi “đã chuẩn bị / đã đăng / cần kiểm tra” và lưu bản nháp caption |
| **Tần suất / thời gian** | **Số liệu giả định:** 3–4 video/tuần; khoảng 30–50 phút/video cho metadata, đăng và kiểm tra ba nền tảng, chưa tính dựng |
| **Lời nói minh họa (không phải trích dẫn thật)** | “Điều làm tôi mệt nhất là không biết chính xác kênh nào đã đăng xong; tôi phải mở từng nơi để rà lại.” |
| **Insight** | **Tín hiệu xác nhận giả định:** Ở tần suất cao, quản lý trạng thái và tránh bỏ sót có thể tạo pain rõ ràng hơn so với việc AI viết caption; Rule/tool có thể phù hợp |

- **Hỏi:** “Lần gần nhất bạn bị thiếu hoặc phải đăng lại một kênh xảy ra thế nào?” — **Đáp:** “Tôi đăng xong hai nơi nhưng quên kênh thứ ba, đến lúc so bảng theo dõi mới phát hiện.”
- **Hỏi:** “Bạn đã xử lý tình huống đó bằng cách nào?” — **Đáp:** “Tôi bổ sung checklist, kiểm tra tài khoản và cập nhật lại trạng thái.”

#### Tổng hợp các case

| Case | Pain nổi bật trong kịch bản | Tín hiệu phản bác / giới hạn | Phương án đơn giản nên so sánh |
|---|---|---|---|
| Học viên | Phải copy và tải lại trên hai kênh | Đăng ít; phần dựng tốn thời gian hơn phần upload | Manual + caption mẫu |
| Lab coach | Chỉnh mô tả, kiểm link, xác nhận đúng chuyên môn | Cần kiểm duyệt trước khi đăng; đã có template | Template + checklist + duyệt |
| Nhân viên văn phòng | Bỏ sót nền tảng, khó xác nhận trạng thái và lịch | Phải xem loại tài khoản, quyền API và tần suất thật | Công cụ sẵn có hoặc Rule + log trạng thái |

**Giả thuyết rút ra:** Không nên định nghĩa vấn đề là “cần AI đăng video”. Nhóm nên tập trung kiểm chứng liệu **người đăng nhiều nền tảng với tần suất cao có thực sự mất thời gian vì thao tác và theo dõi trạng thái hay không**. Kịch bản học viên cho tín hiệu phản bác về giá trị; kịch bản lab coach nhấn mạnh việc duyệt nội dung; kịch bản nhân viên văn phòng gợi ý cơ hội Rule-based Automation.

**Tư liệu tham khảo nội bộ:** [Bản mô phỏng chi tiết ba vai trò](../assets/cp4-interview-simulations.md).


### Tư liệu từ người dùng thật trên diễn đàn công khai (secondary research, KHÔNG PHẢI phỏng vấn)

Các trường hợp dưới đây xuất phát từ **bài viết/bình luận công khai của người dùng tự mô tả trải nghiệm**, có đường dẫn gốc. Đây không phải người được nhóm liên hệ hoặc phỏng vấn, không có cách xác minh độc lập danh tính hay số phút họ tự báo cáo. **Số cuộc phỏng vấn trực tiếp vẫn là 0**, không dùng bốn trường hợp này để thay yêu cầu phỏng vấn 2–3 người hoặc khảo sát 5–10 người.

| Nguồn và vai trò người tự thuật | Sự việc đã kể và cách xử lý | Tín hiệu xác nhận / phản bác | Hàm ý cần kiểm chứng |
|---|---|---|---|
| **Trường hợp công khai A — Influencer đăng TikTok** ([r/SocialMediaMarketing, 21/12/2025](https://www.reddit.com/r/SocialMediaMarketing/comments/1pshp39/how_to_cross_post/)) | Người đăng nói muốn tự động đưa video từ TikTok sang YouTube/Instagram vì mệt mỏi khi upload thủ công. Trong phần trả lời, họ cho biết **đăng 3 lần/ngày**; khi một người khác mô tả việc chuẩn bị master video và upload theo lô, họ nói từng làm gần giống vậy. | **Xác nhận một dạng pain:** người đăng thường xuyên muốn giảm tải thủ công; **phản bác một phần:** phương án batching có thể giải quyết mà chưa cần tự xây AI. | Hỏi người đăng video thật số lượt/tuần, số kênh và mức độ hiệu quả của cách làm theo lô. |
| **Trường hợp công khai B — Solo builder tự đăng nội dung cho 5 ứng dụng** ([r/buildinpublic, 11/09/2026](https://www.reddit.com/r/buildinpublic/comments/1wd7cmb/how_do_you_handle_social_media_postings/)) | Người viết nói đang cố đăng **15 short/ngày**, thường chuyển clip từ máy tính sang điện thoại, soạn caption rồi đăng từng nền tảng; **tự ước tính khoảng 2 giờ hoặc hơn mỗi ngày** chỉ cho công việc này. | **Xác nhận có điều kiện:** tải lại và điều chỉnh metadata có thể rất tốn thời gian ở người đăng khối lượng lớn. **Giới hạn:** tần suất và số giờ do chính tác giả tự thuật, chưa được bấm giờ độc lập; khối lượng này không đại diện học viên đăng thỉnh thoảng. | Phân nhóm đối tượng theo tần suất thực tế; không lấy 2 giờ/ngày làm baseline chung cho nhóm. |
| **Trường hợp công khai C — Người dùng Metricool chia sẻ trải nghiệm** ([r/SmallYTChannel, 11/12/2023](https://www.reddit.com/r/SmallYTChannel/comments/18fx4il)) | Người bình luận cho biết đã dùng **Metricool** để đăng Shorts lên Instagram, Facebook, TikTok và Pinterest; họ không nhận thấy vấn đề giảm chất lượng âm thanh, nhưng thấy **chờ upload/xử lý từng video mất thời gian**, nhất là khi không dùng mẫu nhập hàng loạt CSV. | **Tín hiệu phản bác quan trọng:** Dù đã dùng công cụ đa kênh, bottleneck có thể chuyển sang **thời gian chờ upload và xử lý**, không nhất thiết là nhập lại caption. | Đo riêng thời gian thao tác của người dùng và thời gian nền tảng tải/xử lý video; so sánh công cụ sẵn có trước khi xây Rule. |
| **Trường hợp công khai D — Người thử tái sử dụng video nhiều nền tảng** ([r/NewTubers, 05/03/2026](https://www.reddit.com/r/NewTubers/comments/1rlnt9a/does_anyone_actually_repurpose_their_videos_for/)) | Người viết nói việc chỉnh hook, tỷ lệ và văn phong cho mỗi nền tảng làm **khối lượng công việc gần gấp đôi**; một người tham gia khác còn cho rằng không đáng tốn công đăng khắp nơi nếu lợi ích mang lại thấp. | **Phản bác việc chỉ tập trung upload:** khó khăn có thể nằm ở biên tập nội dung hoặc **ROI thấp** của việc phân phối thêm kênh; tự động upload không giải quyết phần này. | Hỏi cụ thể thời gian chỉnh nội dung so với thao tác đăng và mức giá trị của mỗi kênh đối với người đăng. |

**Insight từ tư liệu thứ cấp:** Có tín hiệu pain thật ở người đăng nhiều lần/ngày, nhưng **không có một bottleneck thống nhất**: có người mệt vì lặp thao tác, người khác mất thời gian chờ video upload, và người khác tốn công chỉnh nội dung hoặc không thấy lợi ích của việc đăng nhiều nền tảng. Đây là **điểm phản bác giả định ban đầu**, không nên chỉ tìm thông tin xác nhận. Điều chỉnh đề xuất cho CP5: đo tách biệt (a) chuẩn bị/chỉnh metadata, (b) tương tác với giao diện và API, (c) chờ upload/xử lý, (d) kiểm tra kết quả trước khi chọn mức tự động hóa.

**Không được ghi những nội dung này là câu trả lời phỏng vấn do nhóm hỏi.** Để đáp ứng yêu cầu CP4, nhóm vẫn cần phỏng vấn trực tiếp người dùng ngoài nhóm hoặc làm survey thật.

### 3.3. Research giải pháp đã có

Đã đối chiếu tài liệu hướng dẫn chính thức thay vì giả định rằng phải tự xây AI/Agent. Các nguồn được truy cập ngày **09/11/2026**; tính năng và điều kiện sử dụng cần kiểm tra lại trước pilot.

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| **Buffer — công cụ quản lý/lên lịch đa kênh** | [Supported channels](https://support.buffer.com/articles/supported-channels-LM3P7Y4zsp); [Scheduling posts](https://support.buffer.com/articles/scheduling-posts-4Qdld7giAZ) | Soạn bài tập trung, chọn nhiều kênh, chỉnh nội dung theo kênh và hẹn lịch; tài liệu có liệt kê Instagram Professional, TikTok và YouTube Shorts | Giảm chuyển qua lại giữa các giao diện và thao tác đăng thủ công; không yêu cầu nhóm xây AI | Một số loại tài khoản/tính năng dùng **notification publishing** thay vì tự đăng; bài đã lên lịch phải sửa riêng theo từng kênh; giới hạn theo API/gói sản phẩm | **Thử công cụ có sẵn trước khi tự lập trình**; không hứa tự động hoàn toàn |
| **Metricool — lập lịch video với tùy chọn đăng thủ công khi cần** | [Supported formats](https://help.metricool.com/scheduling-and-posting-options-by-social-network-cwmb3); [Manual publishing](https://help.metricool.com/how-to-set-up-notifications-for-manual-publishing-ybhgw) | Chuẩn bị, lên lịch và phân phối video/Reels/Shorts; cho biết định dạng hỗ trợ theo từng nền tảng | Có bảng so sánh rõ tính năng theo kênh và hỗ trợ tình huống phải hoàn tất đăng trong app gốc | Một số hiệu ứng, nhạc hoặc tính năng chỉ dùng được trong app; có giới hạn định dạng/loại tài khoản; chưa thử với tài khoản thật | Thiết kế **fallback đăng thủ công riêng từng kênh** thay vì giả định tất cả tác vụ đều gọi API được |
| **Rule/script dùng API chính thức (không AI)** | [YouTube videos.insert](https://developers.google.com/youtube/data/reference/rest/v3/videos/insert); [TikTok Direct Post](https://developers.tiktok.com/docs/en/content-posting-api-get-started); [Instagram API — Meta](https://www.postman.com/meta/instagram/documentation/6yqw8pt/instagram-api) | Upload/publish video sau khi người dùng chọn nội dung, cấp quyền và xác nhận; lưu trạng thái cho từng nền tảng | Quy trình rõ ràng, có thể kiểm thử và theo dõi trạng thái; không cần AI quyết định nội dung | YouTube cần OAuth; TikTok cần quyền `video.publish` và app chưa qua audit bị giới hạn hiển thị riêng tư; Instagram API yêu cầu loại tài khoản/quyền hợp lệ. Chưa xác minh việc tích hợp thật và nguy cơ token hết hạn/đăng trùng | Nếu tự xây, **giới hạn phạm vi theo API/quyền đã thử thành công**, kiểm tra trạng thái trước retry và luôn có người duyệt |

**Kết luận từ research (không phải kết quả thử nghiệm):**

- **Không cần AI để thực hiện thao tác đăng tải có quy tắc rõ.** Những công cụ hiện có đã hỗ trợ nhiều phần của quy trình; tự xây hệ thống chỉ có giá trị nếu sau thử nghiệm vẫn còn pain đáng kể mà công cụ sẵn có không giải quyết.
- **Rule có điều kiện triển khai**, không đồng nghĩa API có thể đăng mọi video, nhạc, hiệu ứng hoặc loại tài khoản. Bảo đảm người dùng kiểm tra nội dung và xử lý các kênh lỗi.
- **Ưu tiên thử theo thứ tự:** (1) template + checklist/đăng thủ công, (2) Buffer hoặc Metricool với tài khoản và video phù hợp, (3) Rule/script tùy biến **chỉ nếu** hai mức trước chưa đủ và đã xác minh quyền API.
- Kết quả này phù hợp với **No-Go đối với AI** và **Not Yet đối với việc xây Rule tùy biến** cho đến khi có đo lường người dùng và thử API, như phần CP6.

---

## 4. Quy trình trước/sau (CP5)

**Bài toán phân tích:** Phân phối video Education Animation lên YouTube Shorts, TikTok và Instagram Reels, giảm thao tác nhập và cấu hình lặp lại.

**Trạng thái dữ liệu:** Các thời gian hiện tại do học viên cung cấp đều là ước lượng, chưa bấm giờ. Quy trình tương lai là phương án đề xuất, chưa thử nghiệm. Chưa xác định tần suất xuất bản. Nội dung phần này chưa thay thế kết quả chọn problem ở CP3 hoặc kiểm chứng ở CP4.

**Phạm vi so sánh:** Từ khi đã có file video hoàn chỉnh, được kiểm tra chất lượng, đến khi kiểm tra xong nội dung và trạng thái đăng/hẹn giờ trên cả ba nền tảng. Loại 10 phút xuất và kiểm tra video khỏi cả hai quy trình. Vì vậy, baseline trong phạm vi này là **110 phút/lần**, thay vì 120 phút của quy trình ban đầu có cả bước xuất video.

**Mục tiêu ưu tiên:** Chuẩn bị dữ liệu tại một nơi và giảm thao tác lặp; không bắt buộc ba nền tảng công khai cùng một thời điểm. Creator duyệt riêng nội dung và lịch đăng của từng nền tảng.

### 4.1. Quy trình hiện tại

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

### 4.2. Quy trình tương lai

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

### 4.3. Before / after

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

**Nguồn hợp nhất:** Đạt đã viết Problem Statement v0 theo kịch bản Solo Creator / Education Animation; Công Minh bổ sung giới hạn phạm vi, chỉ ra thời gian chưa được đo và thiết kế quy trình Rule. Bản v0 dưới đây dùng cùng phạm vi với mục 4 (từ lúc video đã hoàn thiện tới khi kiểm tra đăng trên ba nền tảng), để có thể đối chiếu hợp lệ với v1 ở mục 7. Bản đề xuất có AI của Đạt được lưu riêng trong `report/assets/cp5-alternative-ai-proposal.md` để giữ lại đóng góp và phản biện, **không coi đó là giải pháp đã chốt**.

| Trường | Nội dung |
|---|---|
| **Actor** | Người sáng tạo video ngắn tự quản lý nội dung và đăng bài trên nhiều nền tảng, ví dụ kênh Education Animation đăng YouTube Shorts, TikTok và Instagram Reels. |
| **Quy trình** | Khi video đã hoàn chỉnh: soạn bộ thông tin đăng → truy cập và cấu hình lần lượt YouTube, TikTok, Instagram → điều chỉnh caption, hashtag hoặc cover theo kênh → kiểm tra trạng thái đăng và hiển thị. |
| **Bottleneck** | Thao tác cấu hình và điều chỉnh nội dung lặp lại ở các giao diện khác nhau; vùng TikTok/Instagram đang bị nghi ngờ là nơi tốn nhiều thời gian, nhưng **chưa tách được thời gian chỉnh nội dung, thao tác giao diện và chờ upload**. |
| **Impact** | Tốn công thao tác, có khả năng đăng thiếu kênh, sai caption, sai lịch hoặc phải kiểm tra thủ công nhiều nơi. Mức độ và tần suất chưa được kiểm chứng qua phỏng vấn hoặc log đo. |
| **Success Metric** (baseline → target, cách đo) | **Baseline tạm tính:** khoảng 110 phút/lần đăng ba nền tảng, chỉ là ước lượng từ quy trình ở mục 4 (không tính 10 phút xuất video). **Target cần xác lập sau đo thực tế**, ưu tiên giảm thời gian thao tác thủ công mà không tăng sai nội dung hoặc đăng nhầm/trùng. **Cách đo:** bấm giờ từng bước trên nhiều lượt đăng, tách thời gian chờ tải/xử lý và kiểm tra lỗi trên từng kênh. |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | Đây là mô tả vấn đề trước khi lựa chọn giải pháp. Với mọi phương án có tự động hóa: người dùng phải duyệt file, caption, nền tảng, tài khoản và lịch trước khi gửi; không được tự xuất bản bản chưa duyệt, tự sửa nội dung hoặc bỏ qua giới hạn API và quyền riêng tư; cần người kiểm tra kết quả và xử lý ngoại lệ. |

**Các phản biện được nhóm đưa vào phạm vi phân tích (tổng hợp từ bản của Đạt và Công Minh):**

- **Không đồng nhất thời gian render với thời gian đăng:** Quy trình trong tài liệu của Đạt tính 120 phút gồm 10 phút xuất/kiểm tra video; phần của Công Minh giới hạn sau khi video đã hoàn thiện, còn 110 phút. Hai số này **khác phạm vi, không phải hai baseline đo được**.
- **Không suy ra 50 phút là thời gian AI chắc chắn tiết kiệm được:** Cần tách phần viết lại caption, thao tác cấu hình và thời gian chờ nền tảng.
- **Không chọn AI trước khi thử Rule:** Kiểm tra công cụ có sẵn và khả năng API chính thức; không giả định có thể đăng mọi định dạng hay mọi loại tài khoản.
- **Con người kiểm soát:** Người đăng chịu trách nhiệm xem lại nội dung, phê duyệt riêng từng kênh và xác nhận kết quả.

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
| **Success Metric** (baseline → target, cách đo) | **Baseline tạm tính:** khoảng 110 phút/lần đăng ba nền tảng, chỉ là ước lượng từ quy trình ở mục 4 (không tính 10 phút xuất video). **Target cần xác lập sau đo thực tế**, ưu tiên giảm thời gian thao tác thủ công mà không tăng sai nội dung hoặc đăng nhầm/trùng. **Cách đo:** bấm giờ từng bước trên nhiều lượt đăng, tách thời gian chờ tải/xử lý và kiểm tra lỗi trên từng kênh. |
| **Boundary** | Chỉ hỗ trợ nền tảng, loại tài khoản và định dạng có API cùng quyền đăng bài hợp lệ. Không tự tạo nội dung, không tự quyết định đăng bài, không vượt qua giới hạn của nền tảng. Người dùng phải xác nhận trước khi đăng. |
| **AI intervention point** | Không có điểm can thiệp AI. Công cụ tự động hóa các bước đăng tải sau khi người dùng chọn nội dung và nền tảng đích. |
| **Mức chọn** | **Rule — không sử dụng AI.** |
| **Rủi ro & người kiểm tra** | Rủi ro API, quyền truy cập, định dạng, bảo mật, đăng sai hoặc đăng trùng. Người dùng kiểm tra nội dung và kết quả; nhóm phát triển kiểm tra lỗi kỹ thuật và tính ổn định của hệ thống. |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| Actor | Người sáng tạo video ngắn quản lý nhiều kênh. | Tập trung vào creator / người quản lý nội dung nhiều nền tảng. | Giữ phạm vi phù hợp với người trực tiếp thao tác. |
| Quy trình | Ghi nhận các thao tác tải và cấu hình lặp lại. | Chỉ ra bước người dùng duyệt, Rule gửi, kiểm tra và xử lý lỗi. | Xác định nơi có thể tự động hóa mà không đổi nội dung. |
| Bottleneck | Nghi ngờ phần cấu hình TikTok/Instagram và thao tác lặp. | Tiếp tục coi là giả thuyết, cần đo phần thao tác so với chờ tải. | Không kết luận sai rằng toàn bộ 50 phút đều được tự động hóa. |
| Success Metric | Baseline ước lượng 110 phút/lần, chưa đo. | Baseline vẫn **110 phút/lần (ước lượng, cùng phạm vi)**; target giảm thời gian thao tác sẽ chốt sau đo thực tế, theo dõi tỉ lệ đăng đúng, trùng và thành công. | Tránh đổi baseline sang 15 phút không cùng quy trình; chưa có bằng chứng để cam kết 5 phút. |
| Boundary | Người dùng phải duyệt và không được tự xuất bản bản chưa duyệt. | Quy định thêm quyền API, nền tảng/loại tài khoản được hỗ trợ, duyệt riêng từng kênh, xử lý trạng thái không rõ. | Giảm nguy cơ vượt quyền, đăng sai và trùng. |
| Mức can thiệp | Chưa chốt ở v0. | **Rule, không AI**; AI intervention point: **không có**. | Quy trình có thể xác định trước, không cần mô hình tự quyết. |


**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

Do nhóm **không sử dụng AI**, các tiêu chí được thay bằng tiêu chí đánh giá đầu ra của công cụ tự động hóa.

Các ngưỡng dưới đây là mục tiêu thử nghiệm giả định.

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | Thời gian thao tác đăng bài | Giảm ít nhất 20% thời gian con người thao tác so với baseline **đo được** ở cùng phạm vi (mục tiêu pilot đề xuất). | Không đạt ngưỡng cải thiện hoặc không có dữ liệu đo tin cậy. |
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

**Quyết định của nhóm: NO-GO đối với việc sử dụng AI để đăng video đa nền tảng.**

**Mức can thiệp được ưu tiên để tiếp tục nghiên cứu:** **Rule-based Automation (không AI)**. Tuy nhiên, **việc triển khai công cụ Rule ở trạng thái NOT YET**, vì chưa xác minh đầy đủ quyền đăng qua API và chưa có đo lường tác vụ thực tế. Đây là hai quyết định ở hai phạm vi khác nhau, không mâu thuẫn: *không triển khai AI* và *chưa triển khai ngay công cụ tự động hóa*.

**Lý do không chọn AI:** Các hành động tải file, chọn tài khoản, đặt lịch, ghi trạng thái và kiểm tra trường bắt buộc đều có trình tự rõ ràng, phù hợp hơn với quy tắc hoặc công cụ đã có. AI tạo caption/hashtag là một nhu cầu khác; chưa có bằng chứng cho thấy cần tích hợp để giải quyết bottleneck của thao tác đăng tải. Việc dùng AI làm tăng rủi ro sửa sai nội dung hoặc hành động ngoài ý muốn.

**Nếu triển khai Rule — pilot nhỏ nhất sau khi xác minh:** Chọn 2 nền tảng có API và quyền truy cập hợp lệ; thử một loại nội dung được hỗ trợ; người dùng tự chọn và duyệt nội dung/lịch cho từng kênh; công cụ chỉ gửi phiên bản đã duyệt, lưu trạng thái riêng từng kênh, không tự đăng lại khi chưa kiểm tra khả năng trùng bài.

**Trước khi Go với Rule, cần kiểm chứng:**

1. Phỏng vấn/quan sát người đăng video thật, ghi thời gian cho từng bước và tần suất đăng.
2. Kiểm tra API chính thức, loại tài khoản, quyền đăng, quyền lưu trữ token và hạn chế của ít nhất 2 nền tảng.
3. Thử thao tác đăng hợp lệ lên tài khoản thử nghiệm; đo thời gian con người thao tác tách khỏi thời gian mạng/tải video.
4. Xác minh người dùng chấp nhận quy trình duyệt trước khi đăng; kiểm tra tình huống lỗi và đăng trùng.
5. Đối chiếu chi phí, bảo mật và khả năng duy trì kết nối.

**Nếu không đạt điều kiện cho Rule:** Dùng bảng nội dung tập trung, checklist theo nền tảng và lịch đăng thủ công để giảm thiếu sót mà không cần tích hợp API.

**Ngưỡng dừng đề xuất (chưa phải kết quả thử nghiệm):** Sau **2 tuần** kiểm chứng kỹ thuật, nếu không có cách đăng hợp lệ và kiểm soát được trạng thái ở **ít nhất 2 nền tảng**, dừng phương án tự động đăng và quay về template + checklist. Nếu trong pilot xuất hiện đăng sai tài khoản, đăng trùng không kiểm soát hoặc rủi ro lộ token, dừng thử nghiệm tài khoản thật ngay; nếu thời gian thao tác không giảm sau thử nghiệm có kiểm soát, cần xác định lại bottleneck trước khi phát triển thêm.

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
