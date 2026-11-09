# Team

> Nhóm điền chung phần **Thông tin nhóm** và **Thành viên**. Mỗi người tự điền phần của mình trong **Cá nhân**. Khi xong, mỗi thành viên copy file này vào repo cá nhân.

## Thông tin nhóm

- Tên nhóm: Nhóm 4.1
- Candidate problem nhóm chọn (1 câu): Sinh viên làm bài ML/DL phải huấn luyện lại nhiều vòng (mỗi vòng 15–60 phút) vì đoán nguyên nhân mô hình cho kết quả kém, thay vì kiểm tra có thứ tự dữ liệu, tiền xử lý và chỉ số.
- Quyết định cuối (Go / Not Yet / No-Go): Go, phạm vi nhỏ (pilot 2 tuần, không xây công cụ mới, có ngưỡng dừng)

## Thành viên

| STT | Họ và tên | MSSV | Vai trò trong nhóm | Repo cá nhân |
|---:|---|---|---|---|
| 1 | Nguyễn Khôi Nguyên | 2A202603453 | Ghi chép; vẽ quy trình; viết Problem Statement v0 | https://github.com/nguyenkhoinguyen07122005-cpu/K5-L3A-DAY02-NguyenKhoiNguyen-2A202603453-DiscoveryProblemFraming |
| 2 | Nguyễn Ngọc Sang | [ĐIỀN] | Điều phối thời gian; phụ trách research; chốt 4 rủi ro và quyết định | [ĐIỀN] |
| 3 | Đào Thị Thu Phương | [ĐIỀN] | Phụ trách kiểm chứng (phỏng vấn/survey); viết Problem Statement v1 và tiêu chí đánh giá | [ĐIỀN] |
| 4 | Nguyễn Trần Tiến | [ĐIỀN] | Người phản biện chính; phụ trách mức can thiệp AI và bộ eval | [ĐIỀN] |

Không ghi email hay số điện thoại vào bảng này, vì repo có thể để public.

Gợi ý vai trò (một người có thể giữ nhiều vai): điều phối thời gian, ghi chép, người phản biện chính, phụ trách kiểm chứng (phỏng vấn/survey), phụ trách research, vẽ quy trình, viết Problem Statement.

## Phân công theo checkpoint

| Checkpoint | Người chính | Người hỗ trợ | Sản phẩm |
|---|---|---|---|
| CP3 — Hội tụ nhóm | Nguyễn Ngọc Sang | Cả nhóm (Nguyễn Khôi Nguyên ghi chép bảng pitch) | Cluster, cây OST, bảng chấm điểm |
| CP4 — Kiểm chứng | Đào Thị Thu Phương | Nguyễn Khôi Nguyên | Assumption map, snapshot hoặc survey (`report/assets/cp4-interview-script.md`) |
| CP4 — Research | Nguyễn Ngọc Sang | Nguyễn Trần Tiến | Bảng research có link |
| CP5 — Quy trình trước/sau | Nguyễn Khôi Nguyên | Nguyễn Trần Tiến | Quy trình + bảng before/after (`report/assets/cp5-workflow-*.png`) |
| CP5 — Problem Statement v0 | Nguyễn Khôi Nguyên | Đào Thị Thu Phương | Problem Statement v0 |
| CP6 — Mức can thiệp + Problem Statement v1 | Nguyễn Trần Tiến (ma trận, 4 mức, AI Canvas, bộ eval) · Đào Thị Thu Phương (Problem Statement v1, tiêu chí đánh giá) | Nguyễn Khôi Nguyên | Ma trận, AI Canvas, eval (`report/assets/cp6-eval-set.md`), Problem Statement v1 |
| CP6 — Quyết định | Nguyễn Ngọc Sang | Cả nhóm | 4 rủi ro + Go/Not Yet/No-Go |

### NguyenKhoiNguyen-2A202603453

**Phần việc phụ trách:**

- Pitch 3 card (#7, #8, #9 trong bảng nhóm); card #8 (chẩn đoán mô hình ML/DL kém) được nhóm chọn.
- Ghi chép bảng pitch và câu hỏi phản biện (CP3).
- Vẽ quy trình hiện tại và tương lai, lập bảng before/after (CP5).
- Viết Problem Statement v0 (CP5); hỗ trợ Phương sửa lên v1 (CP6).
- Hỗ trợ kiểm chứng: soạn kịch bản phỏng vấn và form survey theo The Mom Test (CP4).

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Card #8 trở thành candidate của nhóm; lập luận loại #7 và #9 (đã có debugger/profiler giải).
- Sơ đồ quy trình trước/sau: chốt bottleneck ở bước đoán nguyên nhân, đặt boundary và phương án quay về checklist.
- Bảng before/after: ~190' → ~112', 6 → 3 bước thủ công.
- Problem Statement v0 và bảng thay đổi v0 → v1 (đổi metric chính sang số vòng huấn luyện lại).
- Kịch bản phỏng vấn + form survey.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `group_report.md`: mục 2.1 (dòng 7–9), mục 2.4 (lý do loại #7, #9), mục 4, mục 5, mục 7 (bảng v0 → v1).
- `report/assets/cp4-interview-script.md`, `cp5-workflow-current.png`, `cp5-workflow-future.png`

**Điều mình học được từ phần nhóm:**

- Một problem nghe hợp lý vẫn có thể không cần AI: card #1 và #3 của mình giải được bằng debugger và profiler.
- Metric nên đo đúng chỗ tốn nhất: số vòng huấn luyện lại quan trọng hơn thời gian ngồi đoán nguyên nhân.
- Phải tách rõ phần Rule làm được và phần thật sự cần AI, rồi đặt boundary để sinh viên vẫn là người quyết định.

### NguyenNgocSang-[MSSV]

**Phần việc phụ trách:**

- Pitch 3 card (#1, #2, #3 trong bảng nhóm).
- Điều phối thời gian và dẫn buổi hội tụ: gom cluster, cây OST, chấm điểm shortlist (CP3).
- Research giải pháp đã có, tự mở và kiểm từng link (CP4).
- Chốt 4 rủi ro, quyết định Go/Not Yet/No-Go và ngưỡng dừng (CP6).

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- 3 card về mua hàng và bảo hành (so sánh báo giá, tra chính sách bảo hành, kiểm tra yêu cầu mua hàng), kèm sơ đồ quy trình có số phút và bottleneck cho cả 3 card.
- Dẫn buổi hội tụ: gom 12 candidate thành 3 cluster (tổng hợp tài liệu, kiểm tra theo quy tắc, tìm lỗi bằng thử–sai), giữ thời gian từng bước.
- Đề xuất chọn shortlist mỗi cluster 1 candidate để so sánh công bằng; lập luận loại #2, #3 của mình vì Rule đã đủ cho đa số trường hợp và cần quyền truy cập hệ thống nội bộ.
- Research 3 nguồn (Deepchecks, Cleanlab, bài của Karpathy), tự mở và kiểm từng link; rút ra kết luận phần kiểm tra dữ liệu làm được bằng Rule, khoảng trống còn lại là xếp hạng nguyên nhân.
- Chấm 4 rủi ro, đề xuất quyết định "Go, phạm vi nhỏ": pilot không xây công cụ mới, kèm 4 ngưỡng dừng đo được.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `group_report.md`: mục 2.1 (dòng 1–3), mục 2.2–2.4, mục 3.3, mục 8.

**Điều mình học được từ phần nhóm:**

- Pain lớn nhất chưa chắc là candidate tốt nhất: nếu nhóm không kiểm chứng được trong buổi lab hoặc dữ liệu là tài liệu nội bộ thì rủi ro Viability quá cao.
- Research giải pháp có sẵn giúp nhóm không tự xây lại thứ đã có: Deepchecks đã làm phần kiểm tra, nhóm chỉ cần lo phần còn trống.
- Quyết định "Go" vẫn cần ngưỡng dừng cụ thể, nếu không sẽ không biết lúc nào nên quay về phương án đơn giản hơn.

### DaoThiThuPhuong-[MSSV]

**Phần việc phụ trách:**

- Pitch 3 card (#4, #5, #6 trong bảng nhóm).
- Phụ trách kiểm chứng: phỏng vấn 2–3 học viên nhóm khác hoặc gửi survey, ghi interview snapshot (CP4).
- Viết Problem Statement v1 và tiêu chí đánh giá đầu ra AI (CP6).

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- 3 card về công việc Business Analyst (tổng hợp yêu cầu từ nhiều phòng ban, kiểm tra nhất quán BRD/SRS/test case, biên bản họp); card #4 vào shortlist với pain lớn nhất nhóm (120–180 phút/lần).
- Lập Assumption Map 6 giả định, chọn ra 2 giả định "quan trọng nhưng ít bằng chứng" để kiểm chứng trước (#1 số vòng huấn luyện lại, #2 nguyên nhân nằm ở dữ liệu).
- Phỏng vấn [ĐIỀN số] học viên nhóm khác và/hoặc gửi survey cho [ĐIỀN số] người theo kịch bản The Mom Test; ghi interview snapshot và bảng tổng hợp, gồm cả tín hiệu phản bác.
- Viết Problem Statement v1: thu hẹp actor sang supervised learning có thời gian huấn luyện ≥ 15 phút, thêm AI intervention point, rủi ro và người kiểm tra; lập bảng thay đổi v0 → v1.
- Viết 4 tiêu chí đánh giá đầu ra AI (đúng nguyên nhân, có bằng chứng, kiểm tra được, giữ boundary) theo dạng "đạt / không đạt".

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `group_report.md`: mục 2.1 (dòng 4–6), mục 3.1–3.2, mục 7.
- `report/assets/cp4-interview-snapshot-*.md` hoặc `cp4-survey-result.png` (sau khi kiểm chứng)

**Điều mình học được từ phần nhóm:**

- Hỏi về chuyện đã xảy ra ("lần gần nhất bạn huấn luyện lại mấy lần?") cho câu trả lời đáng tin hơn nhiều so với hỏi "bạn có muốn…".
- Tiêu chí đánh giá AI giống tiêu chí nghiệm thu trong BA: nếu không viết được "thế nào là đạt" thì chưa hiểu đủ bài toán.
- Problem Statement v1 tốt hơn v0 nhờ thu hẹp actor; viết cho "mọi sinh viên ML" thì metric không đo được.

### NguyenTranTien-[MSSV]

**Phần việc phụ trách:**

- Pitch 3 card (#10, #11, #12 trong bảng nhóm).
- Người phản biện chính: đặt câu hỏi cho từng card trong buổi pitch; phản biện Problem Statement v0 (CP3, CP5).
- Phụ trách mức can thiệp AI: ma trận, so sánh No AI/Rule/Workflow/Agent, AI Canvas, câu hỏi PAIR (CP6).
- Chạy và chấm bộ eval 10 ca (CP6).

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- 3 card từ đồ án tốt nghiệp (debug firmware, đẩy dữ liệu cảm biến lên Cloud, kiểm tra định dạng JSONL cho thành viên mới), kèm số phút và bottleneck theo từng bước.
- Phản biện chính trong buổi pitch; đặt câu hỏi "Agent hay Rule là đủ?" giúp nhóm gạch ý "Agent tự dò lỗi" khỏi cây OST vì là solution đội lốt opportunity.
- Phản biện Problem Statement v0: chỉ ra metric bỏ qua phần tốn nhất là các vòng huấn luyện lại, và boundary chưa nói AI có được tự chạy huấn luyện hay không.
- Đặt bài toán vào ma trận (mơ hồ cao × phức tạp thấp), so sánh 4 mức No AI/Rule/Workflow/Agent, lập luận vì sao chọn Workflow mà không lên Agent; điền AI Canvas và 2 câu hỏi PAIR.
- Chạy prompt chuẩn trên bộ eval 10 ca và chấm theo 4 tiêu chí: đạt [ĐIỀN]/10.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `group_report.md`: mục 2.1 (dòng 10–12), mục 2.3 (ý bị gạch), mục 5 (phản biện v0), mục 6.
- `report/assets/cp6-eval-set.md` (bảng chấm)

**Điều mình học được từ phần nhóm:**

- Chọn mức đơn giản nhất đủ dùng: các bước đã cố định thì Workflow là đủ, Agent chỉ thêm chi phí và cách hỏng mới.
- Card #12 của mình (kiểm tra JSONL) là ví dụ rõ nhất cho "không cần AI": một script kiểm schema là giải quyết xong.
- AI sai kiểu bỏ sót nguy hiểm hơn báo nhầm, nên phần Rule phải chạy độc lập và luôn hiển thị cảnh báo.
