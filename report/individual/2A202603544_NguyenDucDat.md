# Báo cáo cá nhân — 2A202603544_NguyenDucDat

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Nguyễn Đức Đạt
- MSSV: 2A202603544
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm:
- Link repo nhóm: https://github.com/killy-mv/K5-L3A-Day02-NguyenVanMinh-2A202603551-DiscoveryProblemFraming

### Bối cảnh & Nhân vật (Persona)

- **Nhân vật:** Tôi là một YouTuber đang vận hành kênh về **Education Animation**.

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Tốn thời gian | Khi dựng xong một video education animation, tôi muốn upload cùng một lúc lên các nền tảng (TikTok, YouTube Shorts, Instagram Reels), để video được công khai sớm cho khán giả mà không phải đăng nhập và copy-paste thủ công từng nơi | YouTuber kênh Education Animation | Mất 2 tiếng chỉ để upload, cấu hình và điền thông tin lên 3 nền tảng (TikTok, YouTube, Instagram) cho mỗi video xuất bản |
| 2 | Tốn thời gian | Khi bắt tay vào dựng một video ngắn education animation (20s), tôi muốn tìm nhanh các đoạn footage/b-roll minh họa trực quan khớp với từng câu kịch bản kiến thức, để hoàn thiện video đúng hạn mà không phải tìm kiếm và lọc qua hàng trăm video tư liệu | Video Editor, Solo Creator kênh Education Animation | Thường tốn đến 4 tiếng chỉ để tìm kiếm và lọc footage ghép cho 1 video ngắn 20 giây |
| 3 | Lặp lại | Khi thực hiện công đoạn hậu kỳ/edit video animation, tôi muốn tự động áp dụng các bộ preset hiệu ứng hoạt họa quen thuộc (zoom in/out, sound effect pop/whoosh, text title highlight), để video chuẩn nhận diện kênh mà không phải kéo thả, căn chỉnh thủ công lặp đi lặp lại | Video Editor, YouTuber | Phải thêm rất nhiều hiệu ứng hoạt họa lặp đi lặp lại mỗi lần edit video (mất trung bình 1–2 tiếng thao tác lặp lại cho mỗi video) |
| 4 | Cần đọc, tổng hợp nhiều thông tin | Khi lên ý tưởng và nghiên cứu chủ đề giáo dục mới, tôi muốn tổng hợp nhanh các góc nhìn tiếp cận, tài liệu tham khảo và phản hồi khán giả từ các kênh education animation khác, để định hình góc nhìn độc đáo mà không bị ngập trong khối lượng thông tin khổng lồ | YouTuber, Biên kịch nội dung kênh Giáo dục | Phải đọc và xem quá nhiều kênh đối thủ, tốn nhiều thời gian đọc bài báo khoa học, mô tả và hàng trăm comment tranh luận |
| 5 | Cần đọc, tổng hợp nhiều thông tin | Khi phân tích hiệu quả kênh định kỳ, tôi muốn nắm bắt được ngay các chỉ số giữ chân người xem (retention) và drop-off point từ YouTube Analytics, để cải thiện nhịp điệu video animation tiếp theo mà không bị ngợp hay tốn thời gian bóc tách các tập dữ liệu quá lớn | YouTuber, Quản lý kênh | Số liệu trong phần YouTube Analytics quá lớn, dữ liệu rời rạc, rất khó để đọc hiểu và tổng hợp hết cùng một lúc |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

-

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | **Tìm và lọc footage cho video ngắn** (#2) | Pain lớn nhất và tốn thời gian khủng khiếp (4 tiếng cho video 20s education animation); quy trình có bước nghẽn rất rõ ở khâu xem lướt từng clip để khớp với khái niệm khoa học; đo lường được baseline cụ thể | Khả năng AI hiểu được "mood" và tính trừu tượng của khái niệm kiến thức có đủ chuẩn xác không |
| 2 | **Upload và tối ưu hóa nội dung đa nền tảng** (#1) | Quy trình tuần tự lặp lại đều đặn mỗi lần ra video; mất 2 tiếng chỉ để sửa format và up lên 3 nền tảng; đo được thời gian chính xác | Chính sách API và hạn chế tài khoản cá nhân của TikTok / Instagram |
| 3 | **Nghiên cứu đối thủ và xu hướng nội dung giáo dục** (#4) | Khối lượng thông tin cần đọc và phân tích rất lớn (tài liệu chuyên môn + video đối thủ); AI có thế mạnh vượt trội trong việc tóm tắt transcript và phân loại comment phản biện của người xem | Phạm vi dễ bị mở rộng quá mức nếu không giới hạn ngách nội dung cụ thể |

### Problem Card #1 — Tìm và lọc footage cho video ngắn

| Trường | Nội dung |
|---|---|
| Job Story | Khi bắt tay vào dựng một video ngắn education animation (Shorts/Reels 20s–60s), tôi muốn tìm nhanh các đoạn footage/b-roll minh họa chuẩn xác cho từng khái niệm trong kịch bản, để hoàn thiện video đúng deadline mà không phải lọc thủ công qua hàng trăm clip tư liệu |
| Actor | Solo Creator kiêm Video Editor kênh YouTube Animation Giáo Dục (Education Animation) |
| Thời điểm / bối cảnh | Giai đoạn dựng hình trên Premiere / CapCut sau khi đã thu âm giọng đọc và có kịch bản timestamp phân cảnh |
| Quy trình hiện tại (3–7 bước) | 1. Đọc voice kịch bản và liệt kê từ khóa b-roll cần tìm cho từng khái niệm (15')<br>2. Tìm kiếm trên các kho stock (Pexels, Storyblocks, Envato) và ổ cứng cá nhân (90')<br>3. Tải về và xem lướt từng clip để chọn đúng góc máy, hình ảnh minh họa phù hợp (100')<br>4. Cắt tỉa (trim) lấy đoạn 1–3 giây vừa khớp câu nói (25')<br>5. Kéo vào timeline và căn chỉnh nhịp điệu (10') |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3 (xem lướt và lọc footage): mất khoảng 100 phút (trong tổng số ~240 phút tìm footage), vì phải mở xem từng video xem có khớp chính xác ý nghĩa câu nói giải thích kiến thức hay không |
| Impact (nếu không giải thì sao) | Mất 240 phút (4 tiếng) chỉ để chuẩn bị tư liệu cho một video 20 giây; mỗi tuần dựng 3 video mất tới 12 tiếng riêng cho việc tìm footage; dẫn đến kiệt sức và trễ lịch đăng |
| Success metric (baseline → target) | Tổng thời gian tìm và lọc footage giảm từ 240 phút xuống dưới 60 phút/video; tỷ lệ footage dùng được trong lần chọn đầu tiên đạt ≥ 80% |
| Phương án không dùng AI | Xây dựng thư mục b-roll cá nhân có gắn tag chi tiết theo chủ đề kiến thức (ví dụ: `vũ trụ`, `não bộ`, `tế bào`) + dùng phím tắt xem trước nhanh: giảm thời gian tìm kiếm nhưng tốn nhiều công sức phân loại ban đầu và không áp dụng được cho kho stock mới |
| Giả thuyết về AI (nếu có) | AI đọc transcript kịch bản có timestamp → phân tích ngữ cảnh câu nói kiến thức để đề xuất 3–5 ứng viên footage phù hợp nhất từ thư viện; editor chỉ việc xem lướt danh sách chọn lọc và kéo thả vào timeline |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — 240 phút (4 tiếng cho 1 video education animation ngắn 20s)

[1 Đọc kịch bản & liệt kê từ khóa: 15']
→ [2 Tìm trên các kho stock & ổ cứng: 90']
→ [3 Xem lướt & lọc clip phù hợp: 100'] ← BOTTLENECK (phải bấm xem từng video một)
→ [4 Cắt tỉa (trim) lấy đoạn 2-3s: 25']
→ [5 Kéo vào timeline & căn khớp nhịp: 10']
```

### Problem Card #2 — Upload và tối ưu hóa nội dung đa nền tảng

| Trường | Nội dung |
|---|---|
| Job Story | Khi dựng xong video education animation, tôi muốn upload cùng một lúc lên 3 nền tảng (YouTube Shorts, TikTok, Instagram Reels), để nội dung phân phối nhanh nhất đến khán giả mà không phải đăng nhập và copy-paste thủ công từng nơi |
| Actor | YouTuber / Creator kênh Education Animation tự vận hành phân phối đa kênh (solopreneur) |
| Thời điểm / bối cảnh | Ngay sau khi render xong bản video hoàn chỉnh, thường vào buổi tối (19h–21h) trước khung giờ vàng |
| Quy trình hiện tại (3–7 bước) | 1. Xuất file video từ phần mềm edit và kiểm tra chất lượng (10')<br>2. Viết tiêu đề kích thích trí tò mò, caption giải thích ngắn, bộ hashtag và chọn ảnh bìa (30')<br>3. Mở YouTube Studio, tải video lên, chỉnh thẻ tag, danh sách phát, hẹn giờ (25')<br>4. Mở TikTok Web/App, tải video, chỉnh lại hashtag trending TikTok, căn lại nhạc nền (30')<br>5. Mở Instagram Creator, tải video, sửa lại format caption (thêm tag, link bio), chọn cover (20')<br>6. Kiểm tra lại hiển thị trên cả 3 ứng dụng sau khi đăng (5') |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 4 & 5 (viết lại caption và điều chỉnh định dạng riêng cho từng nền tảng): mất khoảng 50 phút vì mỗi nền tảng có thói quen hashtag, độ dài caption và thuật ngữ khác nhau, phải sửa tay lặp lại |
| Impact (nếu không giải thì sao) | Mất 120 phút (2 tiếng) mỗi lần xuất bản video; làm lỡ khung giờ vàng tiếp cận người xem; dễ sai sót nhầm lẫn link hoặc hashtag giữa các kênh |
| Success metric (baseline → target) | Giảm tổng thời gian từ 120 phút xuống dưới 25 phút; không bị lỗi sai format caption hay hashtag trên bất kỳ nền tảng nào |
| Phương án không dùng AI | Dùng bảng Google Sheets mẫu chứa sẵn các khung tiêu đề/hashtag theo chủ đề + công cụ hẹn giờ đăng tự động (Buffer/Metricool): giảm thời gian đăng nhập nhưng vẫn phải viết và chỉnh sửa định dạng thủ công |
| Giả thuyết về AI (nếu có) | Từ 1 bản mô tả gốc của video kiến thức, AI tự động thích ứng thành 3 phong cách caption & bộ hashtag tối ưu cho YouTube, TikTok, Instagram; kết hợp webhook/API đăng tự động sau khi creator bấm duyệt |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — 120 phút (2 tiếng/lần đăng)

[1 Xuất video & check lỗi: 10']
→ [2 Soạn tiêu đề & caption gốc: 30']
→ [3 Đăng YouTube Shorts & cấu hình: 25']
→ [4 Chỉnh caption/hashtag & đăng TikTok: 30'] ← BOTTLENECK (sửa format theo từng kênh)
→ [5 Sửa format & đăng Instagram Reels: 20']
→ [6 Kiểm tra hiển thị 3 nền tảng: 5']
```

### Problem Card #3 — Nghiên cứu đối thủ và xu hướng nội dung

| Trường | Nội dung |
|---|---|
| Job Story | Khi lên ý tưởng và kịch bản cho video giáo dục mới, tôi muốn tổng hợp nhanh các chủ đề nổi bật, góc nhìn tiếp cận và phản hồi của người xem từ các kênh cùng ngách, để tìm ra khoảng trống nội dung (content gap) mà không phải tự lướt và xem hàng chục video dài |
| Actor | Creator / Biên kịch nội dung kênh YouTube Education Animation |
| Thời điểm / bối cảnh | Đầu tuần (thứ Hai hoặc thứ Ba), trước khi bắt tay vào viết kịch bản chi tiết cho video tiếp theo |
| Quy trình hiện tại (3–7 bước) | 1. Lướt tab thịnh hành và tìm kiếm từ khóa ngách kiến thức trên YouTube (20')<br>2. Chọn ra 5–7 video của đối thủ có lượng view cao đột biến (15')<br>3. Xem lướt từng video, ghi chú các luận điểm chính và cách họ minh họa hình ảnh (90')<br>4. Đọc 100+ bình luận ở mỗi video để tìm thắc mắc, câu hỏi hoặc hiểu lầm mà người xem chưa thỏa mãn (60')<br>5. Tổng hợp lại thành danh sách ý tưởng và góc nhìn khác biệt cho video của mình (30') |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3 & 4 (xem và đọc thủ công hàng tá video cùng hàng trăm bình luận): mất hơn 150 phút, thông tin bị tản mát, dễ sa đà vào việc xem giải trí thay vì phân tích |
| Impact (nếu không giải thì sao) | Mất hơn 215 phút (~3.5 tiếng) mỗi buổi research; ý tưởng đưa ra thường bị trùng lặp hoặc bỏ sót những pain point thật sự của khán giả trong phần comment |
| Success metric (baseline → target) | Thời gian tổng hợp giảm từ 215 phút xuống dưới 45 phút; trích xuất được ít nhất 3 insight/câu hỏi lớn chưa được giải quyết từ khán giả kênh đối thủ |
| Phương án không dùng AI | Sử dụng extension (VidIQ / TubeBuddy) để lọc các video có VPH (views per hour) cao + đọc lướt các comment nhiều like nhất: giúp lọc video nhanh hơn nhưng vẫn phải đọc thủ công từng video |
| Giả thuyết về AI (nếu có) | Trích xuất transcript của 5 video đối thủ và danh sách comment → AI phân tích và đưa ra: (1) Bản tóm tắt các luận điểm chính, (2) Top 5 câu hỏi/phàn nàn của khán giả mà video chưa trả lời thỏa đáng → gợi ý góc tiếp cận mới |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — 215 phút (~3.5 tiếng)

[1 Tìm từ khóa ngách: 20']
→ [2 Chọn 5-7 video view đột biến: 15']
→ [3 Xem lướt & ghi chép luận điểm đối thủ: 90'] ← BOTTLENECK (phải xem nhiều video dài)
→ [4 Đọc 100+ bình luận tìm thắc mắc của người xem: 60']
→ [5 Tổng hợp ý tưởng & góc nhìn mới: 30']
```

### Card muốn pitch nhất

- Card số: **Card #1 (Tìm và lọc footage cho video ngắn)**
- Vì sao: Đây là nút thắt gây tốn nhiều thời gian nhất (4 tiếng cho một video education animation chỉ dài 20 giây), là nỗi ám ảnh lặp đi lặp lại của mọi solo creator làm dạng kiến thức trực quan. Vấn đề có ranh giới rõ ràng, quy trình thao tác cụ thể, và có thể giải quyết thực tế bằng Workflow AI kết hợp semantic search hoặc tagging.
- Câu hỏi muốn nhóm phản biện:
  1. Liệu AI có hiểu được "ngữ cảnh trừu tượng" của các khái niệm khoa học/kiến thức để đề xuất footage phù hợp, hay vẫn chỉ dừng lại ở việc tìm theo từ khóa chữ thô?
  2. Có cách nào không dùng AI (như tự chuẩn hóa thư mục tư liệu cá nhân) mà vẫn cắt giảm được một nửa thời gian hay không?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Mức thời gian 4 tiếng cho video 20s nghe có vẻ là con số cảm tính hoặc trường hợp cá biệt | Đồng ý | Đã bóc tách rõ thời gian: 100 phút xem lọc clip, 90 phút tìm kiếm, 25 phút cắt ghép, và ghi rõ áp dụng cho video education animation có mật độ b-roll minh họa dày đặc |
| Việc chọn footage minh họa kiến thức đòi hỏi tính chính xác khoa học và phong cách visual riêng của kênh, nếu để AI tự chèn sẽ dễ sai lệch thông tin | Đồng ý hoàn toàn | Đặt boundary rõ ràng: AI chỉ đóng vai trò trợ lý gợi ý 3–5 footage ứng viên theo từng câu thoại, quyền quyết định chọn clip và cắt ghép cuối cùng vẫn thuộc về Editor (Augment chứ không Automate) |
| Nguy cơ vi phạm bản quyền khi AI tự động lấy footage stock trôi nổi | Đồng ý | Giới hạn nguồn tìm kiếm: chỉ tìm trong thư viện footage bản quyền cá nhân đã mua (Envato/Storyblocks) hoặc các nguồn Creative Commons được cấp phép thương mại |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | | |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: | |
| Nhận phản biện | Câu hỏi tôi nhận được: | Tôi đã sửa gì: |
| Gom cluster / cây OST | | |
| Chọn candidate problem | | |
| Kiểm chứng / research | | |
| Quy trình nhóm | | |
| Problem Statement | | |
| Mức can thiệp AI | | |
| Quyết định | | |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | | | | |
| CP2 Problem Card | | | | |
| CP4 Research | | | | |
| CP5 Quy trình | | | | |
| CP5–6 Problem Statement | | | | |
| CP6 Mức can thiệp / quyết định | | | | |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

---

## 7. Tài liệu tham khảo

-
