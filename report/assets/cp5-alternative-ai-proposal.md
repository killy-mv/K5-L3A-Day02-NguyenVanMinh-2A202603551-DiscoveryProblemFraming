# CP5 — Phương án AI được cân nhắc trước khi chọn Rule

> Lưu trữ phần đóng góp từ branch `NguyenDucDat` để không mất phương án ban đầu. Đây là **phương án so sánh**, không phải giải pháp cuối đã thống nhất. Các thời gian và tần suất được nêu trong bản gốc chưa có bằng chứng bấm giờ được lưu trong repo; không dùng như kết quả kiểm chứng. Báo cáo chính lấy phạm vi và quy trình Rule của Võ Công Minh, kết luận không sử dụng AI của nhóm. Cần đánh giá thật nếu muốn dùng các giả thuyết ở bản này.

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

