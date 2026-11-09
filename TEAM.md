# Team

> Báo cáo nhóm chung. Các vai trò và phần đóng góp dưới đây được tổng hợp từ **file báo cáo cá nhân mới nhất của từng thành viên**, commit trên các branch và `report/team/group_report.md`. Các đoạn "Điều mình học được" được **tóm tắt từ chính phần CP7 mà thành viên đã viết**; không khẳng định họ đã trực tiếp điền file TEAM.md. Các nội dung giữa các branch chưa thống nhất được ghi chú công khai để nhóm kiểm tra trước khi nộp.

## Thông tin nhóm

- **Tên nhóm:** **Lab2Dev**
- **Candidate problem nhóm chọn (1 câu):** Giảm thao tác lặp lại, thời gian và sai sót khi người sáng tạo nội dung đăng cùng một video lên YouTube Shorts, TikTok và Instagram Reels.
- **Quyết định cuối trong báo cáo nhóm hiện tại:** **No-Go đối với việc dùng AI** trong tác vụ đăng tải theo quy tắc; ưu tiên công cụ sẵn có hoặc **Rule-based Automation**, nhưng **Not Yet** đối với triển khai Rule tùy chỉnh trước khi kiểm chứng nhu cầu người dùng và quyền API.
- **Lưu ý bất đồng tài liệu:** Báo cáo riêng của Nguyễn Đức Đạt ghi phương án **Workflow có AI + human-in-the-loop** và quyết định **Go/pilot nhỏ**; phương án này được lưu ở `report/assets/cp5-alternative-ai-proposal.md`. Quyết định ở trên là phiên bản hiện hành của `group_report.md`, **không phải lời xác nhận rằng Đạt đồng ý với quyết định cuối**.

## Thành viên

| STT | Họ và tên | MSSV | Vai trò được thể hiện trong bài làm | Tài khoản GitHub |
|---:|---|---|---|---|
| 1 | Nguyễn Đức Đạt | 2A202603544 | Đề xuất bài toán video; CP5 quy trình trước/sau, Problem Statement v0; nghiên cứu/phương án AI để so sánh | `nguyenducdat298` |
| 2 | Võ Công Minh | 2A202603520 | CP5 quy trình Rule, đối chiếu baseline, kiểm soát duyệt và fallback thủ công | `azirTHEKING` |
| 3 | Tạ Tiến Dũng | 2A202603526 | CP6 so sánh No AI/Rule/Workflow/Agent, Problem Statement v1, 4 rủi ro và quyết định | `tiendung832005` |
| 4 | Nguyễn Văn Minh | 2A202603551 | Tổng hợp CP3: 12 candidate, cluster, OST, shortlist; hỗ trợ tổng hợp CP4 và đồng bộ báo cáo | `killy-mv` |

*GitHub handle Đạt được ghi trong TEAM.md của chính Đạt; Công Minh và Tiến Dũng lấy từ Git author GitHub noreply trên commit của họ; `killy-mv` là chủ tài khoản repo nhóm theo remote hiện tại. Mỗi người nên xác nhận handle của mình.*

## Phân công theo checkpoint

| Checkpoint | Người có đóng góp nổi bật | Người hỗ trợ / giới hạn bằng chứng | Sản phẩm trong repo nhóm |
|---|---|---|---|
| **CP3 — Hội tụ nhóm** | Nguyễn Văn Minh (tổng hợp và chuẩn hóa) | Đạt, Công Minh, Dũng cung cấp candidate và tham gia trao đổi theo báo cáo cá nhân; các phản biện do AI gợi ý không được xem là phát biểu thật | Mục 2: bảng 12 candidate, cluster, cây OST, shortlist; `report/assets/2d7665c9401ac044990b.jpg` |
| **CP4 — Kiểm chứng** | Nguyễn Văn Minh (tổng hợp bản CP4 hiện hành); Nguyễn Đức Đạt có nội dung phỏng vấn được tự thuật trên branch riêng | `main` hiện dùng ba case mô phỏng và nghiên cứu thứ cấp, **không có interview snapshot thực đã xác minh để tính vào yêu cầu CP4**; thông tin Đạt tự thuật chưa được đối chiếu với bằng chứng và bản nhóm cuối | Mục 3.1–3.2; `report/assets/cp4-interview-simulations.md` |
| **CP4 — Research** | Nguyễn Văn Minh (bảng tổng hợp trên main); Nguyễn Đức Đạt (khảo sát giải pháp ở branch riêng) | Dũng đối chiếu các rủi ro API và nền tảng | Mục 3.3: Buffer, Metricool, API YouTube/TikTok/Instagram; ghi nhận phương án khác từ Đạt |
| **CP5 — Quy trình trước/sau** | Võ Công Minh (Rule và fallback); Nguyễn Đức Đạt (quy trình AI/HITL và bản so sánh) | Nguyễn Văn Minh hỗ trợ chuẩn hóa phạm vi và trình bày trong bản báo cáo chung | Mục 4: current/future workflow, before/after, thời gian ước lượng; file phương án AI trong `report/assets/` |
| **CP5 — Problem Statement v0** | Nguyễn Đức Đạt | Võ Công Minh hỗ trợ ranh giới quy trình; Nguyễn Văn Minh đối chiếu metric | Mục 5: 6 trường và phản biện, baseline ước lượng 110 phút và target 85 phút |
| **CP6 — Mức can thiệp + Problem Statement v1** | Tạ Tiến Dũng | Các thành viên khác góp ý về phương án Rule/AI và phạm vi đo | Mục 6–7: ma trận, so sánh bốn mức, v1 và tiêu chí đánh giá |
| **CP6 — Quyết định** | Tạ Tiến Dũng | Nguyễn Văn Minh hỗ trợ đồng bộ cách trình bày No-Go AI / Not Yet Rule; Đạt có đề xuất Go riêng | Mục 8: 4 rủi ro, quyết định hiện hành và ngưỡng dừng |

## Cá nhân

> Nội dung dưới đây thể hiện công việc và bài học **do thành viên trình bày trong báo cáo cá nhân**; phần việc nhóm dựa trên sản phẩm có trong repo. Theo RULES.md, mỗi thành viên vẫn có trách nhiệm đọc lại và xác nhận phần này bằng trải nghiệm thật trước khi nộp.

### NguyenDucDat-2A202603544

**Phần việc phụ trách:** Đề xuất các bài toán trong quy trình sáng tạo video; CP5 quy trình trước/sau và Problem Statement v0; nghiên cứu các giải pháp đăng đa kênh.

**Đóng góp cụ thể:** Cung cấp phân tích quy trình upload và chỉnh metadata, các số thời gian ước lượng ban đầu; xây dựng phương án Workflow có AI hỗ trợ caption và bước người dùng phê duyệt (HITL). Đề xuất dùng Metricool, Repurpose.io và Make.com làm phương án đối chiếu. Bản chung đang chọn phương án Rule không AI nhưng vẫn lưu đóng góp AI của Đạt.

**Bằng chứng:** `origin/NguyenDucDat` (commit `1218db3`, `263d96d`, `3f8257f`); `report/team/group_report.md` mục 4–5; `report/assets/cp5-alternative-ai-proposal.md`; `report/individual/2A202603544_NguyenDucDat.md`.

**Điều mình học được từ phần nhóm (tổng hợp từ CP7 cá nhân):** Cần phân biệt pain với ý tưởng công nghệ, tránh tự động hóa hoàn toàn khi nội dung cần kiểm duyệt; phải chú ý bản quyền, sự khác biệt giữa các nền tảng và giới hạn của dữ liệu, công cụ.

### VoCongMinh-2A202603520

**Phần việc phụ trách:** CP5 quy trình đăng đa nền tảng, so sánh before/after và phương án sử dụng Rule, giữ con người duyệt nội dung.

**Đóng góp cụ thể:** Xác định phạm vi đo sau khi video đã hoàn chỉnh (loại 10 phút xuất video khỏi baseline 120 phút để còn 110 phút ước lượng); đề xuất bộ nội dung tập trung, Rule gửi theo kênh, người dùng duyệt và kiểm tra, phương án fallback đăng thủ công và phòng tránh đăng trùng.

**Bằng chứng:** `origin/VoCongMinh` (commit `dbaca00`, `114c78f`); `report/team/group_report.md` mục 4–5; `report/individual/2A202603520_VoCongMinh.md`.

**Điều mình học được từ phần nhóm (tổng hợp từ CP7 cá nhân):** Trước khi chọn công cụ phải hiểu actor và quy trình thực tế; cần thống nhất phạm vi baseline/target, đo riêng phần nhập/chỉnh nội dung và phần chờ upload; Rule không được bỏ qua sự kiểm soát của người dùng.

### TaTienDung-2A202603526

**Phần việc phụ trách:** CP6 mức can thiệp, Problem Statement v1, tiêu chí đánh giá và quyết định dựa trên bốn nhóm rủi ro.

**Đóng góp cụ thể:** So sánh No AI, Rule, Workflow và Agent; lập luận chọn Rule cho công việc có bước cố định, mô tả giới hạn API, quyền tài khoản và người duyệt. Bổ sung đánh giá Value/Usability/Feasibility/Viability và hướng Not Yet trước khi triển khai Rule.

**Bằng chứng:** `origin/TaTienDung` (commit `d2fdd6e`, `c0a1aa9`); `report/team/group_report.md` mục 6–8; `report/individual/2A202603526_TaTienDung.md`.

**Điều mình học được từ phần nhóm (tổng hợp từ CP7 cá nhân):** Vấn đề tốt có thể đến từ thao tác nhỏ nhưng lặp lại; xác định problem, bottleneck và ranh giới trước khi chọn AI; không nên xây công cụ mới khi chưa đối chiếu các giải pháp đã có và chưa kiểm tra API thực tế.

### NguyenVanMinh-2A202603551

**Phần việc phụ trách:** Tổng hợp CP3 và CP4 trên báo cáo nhóm, liên kết tài liệu nghiên cứu, đồng bộ các bản đóng góp của thành viên và success metric.

**Đóng góp cụ thể:** Tập hợp 12 candidate thành 4 cluster; tạo cây OST và shortlist 3 candidate theo 7 tiêu chí; đưa ảnh ghi chú nhóm vào báo cáo; tập hợp 6 giả định Assumption Map, nguồn nghiên cứu công cụ/API và các case phỏng vấn mô phỏng có gắn nhãn rõ ràng. Hỗ trợ đồng bộ quyết định Rule/No AI và target ước lượng 110 → ≤85 phút/lượt.

**Bằng chứng:** `nguyenvanminh` (commit `b5f8d47`, `af7f0fe`, `8ce0828`); `report/team/group_report.md` mục 2–3, 4–8; `report/assets/2d7665c9401ac044990b.jpg`, `report/assets/cp4-interview-simulations.md`; `report/individual/2A202603551_NguyenVanMinh.md`.

**Điều mình học được từ phần nhóm (tổng hợp từ CP7 cá nhân):** Phân biệt vấn đề với lời đề xuất giải pháp, xem xét nhu cầu theo từng actor và tần suất thực tế; tool/code có thể phù hợp hơn AI với thao tác có quy tắc; khi viết metric và kết luận cần tách dữ liệu đo được khỏi những ước lượng chưa kiểm chứng.
