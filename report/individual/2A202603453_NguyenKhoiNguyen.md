# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).

## 1. Thông tin học viên

- Họ tên: Nguyễn Khôi Nguyên
- MSSV: 2A202603453
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm:
- Link repository: https://github.com/nguyenkhoinguyen07122005-cpu/K5-L3A-DAY02-NguyenKhoiNguyen-2A202603453-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Tốn thời gian | Khi làm bài Python phức tạp, tôi muốn nhanh chóng xác định nguyên nhân khiến code cho kết quả sai, để không phải thử sửa nhiều lần. | Sinh viên làm bài lập trình | Bài Python gần nhất: tìm ra nguyên nhân trong dưới 15 phút, thử sửa khoảng 3–4 lần. |
| 2 | Tốn thời gian | Khi chương trình chạy quá chậm, tôi muốn xác định đoạn code gây tốn tài nguyên, để cải thiện thời gian thực thi. | Sinh viên làm bài lập trình | Chương trình chạy khoảng 20 phút, mất khoảng 15 phút tìm đoạn chậm. |
| 3 | Cần đọc, tổng hợp nhiều thông tin | Khi gặp lỗi trong chương trình có nhiều hàm và bước xử lý, tôi muốn hiểu mối liên hệ giữa các thành phần, để tìm đúng nguyên nhân thay vì sửa từng phần một cách thiếu hệ thống. | Sinh viên làm bài/dự án nhiều hàm | Lần gần nhất chương trình có khoảng 6–8 hàm, mất khoảng 20 phút. |
| 4 | Tốn thời gian | Khi kết quả chương trình chưa đạt yêu cầu, tôi muốn kiểm tra các trường hợp đầu vào khác nhau, để xác định phạm vi mà chương trình đang xử lý sai. | Sinh viên làm bài lập trình | Thử khoảng 5 bộ đầu vào, mất khoảng 10 phút. |
| 5 | Lặp lại | Khi sửa code sau mỗi lần kiểm thử, tôi muốn biết thay đổi mới có ảnh hưởng đến những phần đã chạy đúng hay không, để tránh phát sinh lỗi mới. | Sinh viên làm bài lập trình | 1–2 lần/bài sửa xong lại hỏng phần khác. |
| 6 | Tốn thời gian | Khi thực hiện bài tập ML/DL, tôi muốn đánh giá thời gian chạy của các bước xử lý và huấn luyện, để không mất quá nhiều thời gian chờ kết quả. | Sinh viên làm bài ML/DL | Mỗi lần huấn luyện/chạy bài ML/DL gần đây mất 15–60 phút, chờ khoảng 3–4 lần/tuần. |
| 7 | Cần đọc, tổng hợp nhiều thông tin | Khi kết quả mô hình không như mong đợi, tôi muốn đối chiếu dữ liệu đầu vào, quá trình xử lý và các chỉ số đánh giá, để tìm được nguyên nhân ảnh hưởng đến kết quả. | Sinh viên làm bài ML/DL | Tìm nguyên nhân khi mô hình kém mất dưới 30 phút, gặp khoảng 1–2 lần/tuần. |
| 8 | Pain từ người khác | Khi làm bài tập hoặc dự án nhóm có phần code cần tích hợp, tôi muốn các thành viên hiểu rõ đầu vào, đầu ra và yêu cầu của từng thành phần, để hạn chế lỗi khi kết hợp chương trình. | Thành viên nhóm | Dự án nhóm gần nhất ghép code bị lỗi khoảng 2 lần, 3 người gặp. Bằng chứng: tin nhắn nhóm khi ghép code. |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

-

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Tìm nguyên nhân code Python sai (gộp #1, #3, #4) | Ba dòng cùng một pattern, quy trình vẽ được | Baseline mới là ước lượng (<15 phút) nên pain có thể nhỏ; chưa rõ bottleneck nằm ở bước đọc code hay bước thử sửa; debugger + test có thể đã đủ giải quyết |
| 2 | Tìm nguyên nhân mô hình ML/DL cho kết quả kém (#7) | Cần đối chiếu nhiều nguồn: dữ liệu, xử lý, chỉ số | Chưa rõ tần suất gặp (mấy lần/tuần); nguyên nhân thường nằm ở dữ liệu hay ở tham số; mỗi bài/mô hình khác nhau nên khó chuẩn hóa quy trình |
| 3 | Tìm đoạn code/bước chạy chậm (#2, #6) | Có thể đo được thời gian trước và sau | Chậm có thể do phần cứng/kích thước dữ liệu chứ không do code; profiler có sẵn có thể đã giải quyết bước "tìm đoạn chậm" mà không cần AI |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi làm bài Python phức tạp, tôi muốn nhanh chóng xác định nguyên nhân khiến code cho kết quả sai, để không phải thử sửa nhiều lần. |
| Actor | Sinh viên làm bài lập trình Python |
| Thời điểm / bối cảnh | Khi làm bài tập lập trình Python có nhiều hàm, thường trong 1–2 ngày trước hạn nộp, lúc output không khớp với output mẫu hoặc test case. |
| Quy trình hiện tại (3–7 bước) | 1. Chạy code, thấy kết quả sai · 2. Đọc lại code · 3. In giá trị trung gian · 4. Thử sửa · 5. Chạy lại · 6. Lặp lại đến khi đúng |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 4 "Thử sửa" và vòng lặp 4 → 5 → 6: sửa theo phỏng đoán khi chưa có giả thuyết rõ, nên phải chạy lại nhiều lần. Ước lượng khoảng 6 phút cho vòng lặp này / tổng khoảng 13 phút. |
| Impact (nếu không giải thì sao) | Tốn thời gian sát hạn nộp; sửa sai chỗ dễ làm hỏng phần đang chạy đúng (liên quan #5); ít thời gian kiểm tra kỹ phần khác, tăng rủi ro nộp bài còn lỗi. |
| Success metric (baseline → target) | Baseline: ~13 phút và 3–4 lần thử sửa cho mỗi lỗi (tự ước lượng bài gần nhất). Target: ≤ 7 phút và ≤ 2 lần thử sửa/lỗi. Cách đo: tự bấm giờ và đếm số lần chạy lại cho mỗi lỗi trong 1–2 tuần |
| Phương án không dùng AI | Debugger từng bước, kiểm thử nhỏ cho từng hàm, checklist tìm lỗi |
| Giả thuyết về AI (nếu có) | Nếu đưa code + input + output mong đợi/thực tế cho LLM, AI có thể đề xuất 2–3 giả thuyết nguyên nhân kèm vị trí nghi ngờ, giúp bỏ bớt các vòng thử sửa "mù". Người vẫn tự xác minh bằng debugger/test trước khi sửa. |
| Cảm nhận nhanh | Chưa biết, nghiêng về No AI (debugger + unit test có thể đã đủ) |

Quy trình nháp hiện tại:

```text
[1 Chạy code: 1'] → [2 Đọc lại code: 3'] → [3 In giá trị trung gian: 3']
→ [4 Thử sửa: 5'] ← BOTTLENECK → [5 Chạy lại: 1'] → lặp 3–4 lần
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi kết quả mô hình không như mong đợi, tôi muốn đối chiếu dữ liệu đầu vào, quá trình xử lý và các chỉ số đánh giá, để tìm được nguyên nhân ảnh hưởng đến kết quả. |
| Actor | Sinh viên làm bài tập ML/DL |
| Thời điểm / bối cảnh | Khi làm assignment/project ML/DL, ngay sau lần huấn luyện đầu tiên cho chỉ số (accuracy, loss, F1…) thấp hơn kỳ vọng hoặc chênh lệch lớn giữa train và validation. |
| Quy trình hiện tại (3–7 bước) | 1. Huấn luyện và xem chỉ số · 2. Kiểm tra dữ liệu đầu vào · 3. Kiểm tra bước tiền xử lý · 4. Đối chiếu chỉ số, đoán nguyên nhân · 5. Đổi tham số hoặc dữ liệu · 6. Huấn luyện lại, lặp từ bước 2 |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 4, đối chiếu chỉ số và đoán nguyên nhân: ~10 phút/vòng. Bước này chỉ cho ra một giả thuyết và không có cách xác nhận rẻ, nên mỗi lần đoán sai phải trả bằng một vòng huấn luyện lại 15–60 phút. Ước lượng: huấn luyện lại khoảng 3 lần trước khi tìm ra nguyên nhân. |
| Impact (nếu không giải thì sao) | Mỗi giả thuyết sai tốn một vòng huấn luyện; dễ chỉnh tham số ngẫu nhiên trong khi lỗi thật nằm ở dữ liệu (rò rỉ dữ liệu, sai nhãn, chuẩn hóa sai, mất cân bằng lớp); kết quả cuối kém và khó giải thích trong báo cáo. |
| Success metric (baseline → target) | Baseline: ~30 phút chẩn đoán và ~3 lần huấn luyện lại mỗi bài (tự ước lượng). Target: thời gian chẩn đoán ≤ 15 phút và ≤ 2 lần huấn luyện lại trước khi tìm ra nguyên nhân. Cách đo: tự bấm giờ và ghi log mỗi lần huấn luyện (tham số, chỉ số, lý do chạy lại) |
| Phương án không dùng AI | Checklist chẩn đoán (dữ liệu → tiền xử lý → chỉ số), ghi log mỗi lần chạy |
| Giả thuyết về AI (nếu có) | Nếu đưa log huấn luyện, thống kê mô tả dữ liệu và code tiền xử lý cho LLM, AI có thể liệt kê các nguyên nhân khả dĩ theo checklist (overfit/underfit, rò rỉ dữ liệu, mất cân bằng lớp, sai scale) và gợi ý kiểm tra rẻ nhất cần làm **trước** khi huấn luyện lại. Người quyết định có huấn luyện lại hay không. |
| Cảm nhận nhanh | Workflow (checklist dạng Rule + LLM tóm tắt, đối chiếu và xếp hạng giả thuyết) |

Quy trình nháp hiện tại:

```text
[1 Huấn luyện + xem chỉ số: 30'] → [2 Kiểm tra dữ liệu: 5'] → [3 Kiểm tra tiền xử lý: 5']
→ [4 Đối chiếu chỉ số, đoán nguyên nhân: 10'] ← BOTTLENECK → [5 Đổi tham số: 3'] → [6 Huấn luyện lại: 30']
→ chưa tốt: quay lại bước 2, lặp ~3 vòng (≈ 30' + 3 × 53' ≈ 190')
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi chương trình hoặc quá trình huấn luyện chạy quá chậm, tôi muốn xác định đoạn gây tốn thời gian, để giảm thời gian chờ kết quả. |
| Actor | Sinh viên làm bài lập trình và ML/DL |
| Thời điểm / bối cảnh | Khi chạy tiền xử lý hoặc huấn luyện trên laptop/Colab, đặc biệt khi dữ liệu thật lớn hơn dữ liệu mẫu của bài. |
| Quy trình hiện tại (3–7 bước) | 1. Chạy và chờ · 2. Đoán đoạn chậm · 3. Thêm lệnh đo giờ · 4. Sửa · 5. Chạy lại |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2–3: đoán đoạn chậm rồi thêm lệnh đo giờ; đoán sai thì phải thêm đo giờ và chạy lại toàn bộ nhiều lần. Ước lượng khoảng 15 phút. |
| Impact (nếu không giải thì sao) | Thời gian chờ chiếm phần lớn buổi làm bài, số lần thử nghiệm được ít đi, dễ hết quota GPU/Colab. |
| Success metric (baseline → target) | Baseline: ~15 phút tìm đoạn chậm, chương trình chạy ~20 phút (tự ước lượng). Target: tìm đoạn chậm ≤ 10 phút; thời gian chạy ≤ 14 phút (giảm ≥ 30%). Cách đo: ghi thời gian tìm và thời gian chạy mỗi lần |
| Phương án không dùng AI | Công cụ profiling có sẵn (ví dụ cProfile), đo giờ từng bước |
| Giả thuyết về AI (nếu có) | Profiler đã chỉ ra đoạn chậm, nên AI chỉ có giá trị ở bước gợi ý cách tối ưu (vector hóa, cache, batch, tăng `num_workers` của DataLoader…) dựa trên output profiler. |
| Cảm nhận nhanh | No AI / Rule (dùng profiler là chính) |

Quy trình nháp hiện tại:

```text
[1 Chạy và chờ: 20'] → [2 Đoán đoạn chậm: 5'] → [3 Thêm lệnh đo giờ: 10'] ← BOTTLENECK → [4 Sửa: 5'] → [5 Chạy lại: 20']
```

### Card muốn pitch nhất

- Card số: 2
- Vì sao: Đây là card cần tổng hợp nhiều nguồn thông tin nhất (dữ liệu, tiền xử lý, chỉ số, log) và mỗi giả thuyết sai rất đắt (một lần huấn luyện lại 15–60 phút). Lúc xếp hạng ban đầu tôi để card #1 lên đầu vì quy trình dễ vẽ nhất, nhưng sau phản biện (bảng dưới) thấy card #1 có pain nhỏ (~13 phút) và debugger có thể đã đủ, còn card #3 phần lớn giải được bằng profiler, nên chuyển sang pitch card #2.
- Câu hỏi muốn nhóm phản biện: Các bạn thường phải huấn luyện lại bao nhiêu lần trước khi tìm ra nguyên nhân mô hình kém? Một checklist chẩn đoán không dùng AI có đủ không, hay bước đối chiếu nhiều nguồn thật sự cần AI?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Mọi baseline đều là tự ước lượng, chưa bấm giờ thật → success metric chưa đáng tin | Đồng ý | Ghi rõ "tự ước lượng" ở mọi baseline; thêm cách đo (bấm giờ + log mỗi lần chạy trong 1–2 tuần) |
| Card #1 baseline < 15 phút, pain có thể quá nhỏ để cần AI; debugger + unit test có thể đã đủ | Đồng ý | Không chọn #1 để pitch; đổi cảm nhận nhanh sang "Chưa biết, nghiêng No AI" |
| Card #2 bottleneck ghi "bước 4–5" là hai bước, chưa phải một bước cụ thể | Đồng ý | Chốt bottleneck ở bước 4 (đối chiếu, đoán nguyên nhân) và ghi rõ vì sao bước 10' lại gây tốn 30'/vòng |
| Card #2 job story còn rộng ("kết quả không như mong đợi"), chưa rõ loại bài/mô hình nên khó đo | Đồng ý một phần | Bổ sung bối cảnh cụ thể (sau lần huấn luyện đầu, chỉ số thấp hoặc lệch train/val) và metric "số lần huấn luyện lại" |
| Card #3: profiler đã giải bước "tìm đoạn chậm", phần AI mỏng | Đồng ý | Đổi cảm nhận nhanh sang No AI / Rule |
| Actor đều là bản thân tôi, chưa có bằng chứng từ người khác | Đồng ý | Ghi vào "Điều còn chưa chắc"; cần hỏi 3–5 bạn cùng lớp ở CP4 |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Pitch 3 card (#7, #8, #9 trong bảng pitch nhóm), nhấn mạnh card #2 của tôi (#8, chẩn đoán mô hình ML/DL kém) | Card #8 vào shortlist cùng #4 và #10, được nhóm chọn làm candidate |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: AI sai thì sao /có checklist làm phương án quay về  |
| Nhận phản biện | Câu hỏi tôi nhận được: (1) Card #1: "Debugger + unit test đã đủ chưa, cần gì thêm?"; (2) Card #2: "Nếu không có AI, cách đơn giản nhất để giảm một nửa số vòng là gì?"; (3) Card #3: "Chậm do code hay do phần cứng/dữ liệu lớn?"| Tôi đã sửa gì: (1) thừa nhận debugger gần đủ, card #1 bị loại; (2) thêm checklist chẩn đoán theo thứ tự làm phương án No AI và phương án quay về trong quy trình tương lai; (3) ghi vào "Điều còn chưa chắc" của card #3 |
| Gom cluster / cây OST | Ghi chép bảng pitch 12 candidate; đề xuất gom #7–#11 thành cluster "tìm nguyên nhân lỗi bằng thử–sai" vì cùng pattern đoán rồi chạy lại | Cluster C trở thành gốc của cây OST; 3 opportunity đều có candidate của ít nhất 2 thành viên |
| Chọn candidate problem | Giải thích vì sao loại card #1 và #3 của mình (#7, #9: debugger, unit test, profiler đã giải) | Nhóm loại #7, #9 và chọn #8 |
| Kiểm chứng / research | Hỗ trợ Phương: soạn kịch bản phỏng vấn 8 câu và form survey 7 câu theo The Mom Test, bỏ hết câu dạng "Bạn có muốn…" | Nhóm dùng kịch bản này khi hỏi học viên nhóm khác (`report/assets/cp4-interview-script.md`) |
| Quy trình nhóm | Vẽ quy trình hiện tại và tương lai, tính bảng before/after | Bottleneck chốt ở bước đoán nguyên nhân; metric chính đổi sang số vòng huấn luyện lại |
| Problem Statement | Viết v0 (6 trường); nhận phản biện của Tiến về metric và boundary, cùng Phương sửa lên v1 | v1 thu hẹp actor, đổi metric chính sang số vòng huấn luyện lại, mở rộng boundary |
| Mức can thiệp AI | Hỗ trợ Tiến: dùng quy trình tương lai để chỉ rõ bước nào Rule, bước nào AI, bước nào con người | Nhóm chọn Workflow; bước kiểm tra dữ liệu tách thành Rule, AI chỉ làm bước xếp hạng giả thuyết |
| Quyết định | Tham gia chấm 4 rủi ro cùng nhóm; đề xuất thêm ngưỡng dừng theo tỷ lệ "sửa mà không chạy kiểm tra xác nhận" | Quyết định "Go, phạm vi nhỏ" có 4 ngưỡng dừng, trong đó có ngưỡng cho rủi ro Usability |
---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | | | | |
| CP2 Problem Card | Đóng vai PM hoài nghi, phản biện 3 card (chỉ hỏi điểm yếu, không viết lại) | Chỉ ra mọi baseline mới là ước lượng; chỉ ra card #3 giải được bằng profiler; chỉ ra bottleneck card #2 đang gộp 2 bước | Góp ý card #2 "job story quá rộng" nhưng không nói nên thu hẹp theo hướng nào | Tự thu hẹp bằng bối cảnh cụ thể (ngay sau lần huấn luyện đầu, chỉ số thấp hoặc lệch train/val) và thêm metric "số lần huấn luyện lại" |
| CP4 Research | | | | |
| CP5 Quy trình | | | | |
| CP5–6 Problem Statement | | | | |
| CP6 Mức can thiệp / quyết định | | | | |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**
Khi nghe các bạn trình bày top 3 problems, em nhận ra rằng mỗi người có thể gặp những khó khăn rất khác nhau dù cùng học tập và làm việc trong lĩnh vực công nghệ. Có những vấn đề ban đầu nghe khá đơn giản nhưng khi phân tích sâu hơn lại liên quan đến nhiều bước trong một quy trình. Điều này giúp em hiểu rằng một problem tốt không chỉ cần có tính thực tế mà còn phải xác định được ai là người gặp vấn đề, vấn đề xuất hiện ở đâu và ảnh hưởng cụ thể như thế nào.

Đối với bản thân, em thường tập trung vào các vấn đề kỹ thuật như mô hình ML/DL cho kết quả không như kỳ vọng, xử lý dữ liệu chậm hoặc phát sinh lỗi sau khi sửa code. Tuy nhiên, qua hoạt động này, em hiểu rằng không nên mặc định vấn đề kỹ thuật nào cũng cần giải quyết bằng AI. Đôi khi việc tổ chức lại quy trình, bổ sung logging hoặc sử dụng các công cụ kiểm thử cơ bản đã có thể giải quyết phần lớn khó khăn. Em cũng học được cách nhìn problem từ góc độ người sử dụng thay vì chỉ tập trung vào công nghệ mình muốn xây dựng.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**
Em nhận thấy nhóm có nguy cơ đi theo hướng solution-first khi bắt đầu nghĩ đến việc sử dụng AI hoặc xây dựng một công cụ để giải quyết vấn đề trước khi mô tả đầy đủ quy trình hiện tại. Đây là một xu hướng khá dễ gặp, đặc biệt khi các thành viên đều quan tâm đến công nghệ và muốn tạo ra một sản phẩm có nhiều tính năng.

Điều quan trọng em rút ra là cần phân biệt giữa problem và solution. Ví dụ, thay vì bắt đầu bằng ý tưởng xây dựng một AI Agent, nhóm cần làm rõ người dùng đang thực hiện công việc gì, gặp khó khăn ở bước nào, mất bao nhiêu thời gian và hậu quả của vấn đề là gì. Sau đó mới xem xét liệu AI có thực sự cần thiết hay không. Cách tiếp cận này giúp tránh việc lựa chọn công nghệ chỉ vì nó mới hoặc hấp dẫn mà không giải quyết đúng nhu cầu.
**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**
Em nhận ra rằng việc có một ý tưởng kỹ thuật tốt không đồng nghĩa với việc đó là phương án phù hợp nhất để giải quyết vấn đề. Ban đầu, khi nghĩ đến việc hỗ trợ debug mô hình ML/DL, em có xu hướng chú ý nhiều đến khả năng sử dụng AI để phân tích code và tìm nguyên nhân gây lỗi. Tuy nhiên, khi xem xét kỹ hơn các bước trong quy trình, em thấy rằng một số vấn đề có thể được xử lý bằng những phương pháp đơn giản hơn như kiểm tra dữ liệu đầu vào, lưu log, theo dõi metric và kiểm thử từng thành phần.

Điều này khiến em thay đổi cách đánh giá giải pháp: thay vì mặc định cần một hệ thống AI phức tạp, cần chứng minh rằng các phương án không dùng AI hoặc dùng rule chưa đủ hiệu quả.
**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**
Qua việc tìm hiểu cách kiểm chứng một problem, em hiểu rằng nhận định ban đầu của nhóm chỉ là giả thuyết và cần được đối chiếu với bằng chứng thực tế. Một vấn đề có thể nghe rất nghiêm trọng khi nhìn từ góc độ của người thực hiện, nhưng mức độ ảnh hưởng, tần suất xuất hiện và cách người dùng xử lý thực tế có thể khác với dự đoán ban đầu.

Đối với những vấn đề kỹ thuật như debug mô hình hoặc tối ưu xử lý dữ liệu, em cho rằng chỉ hỏi người dùng có gặp khó khăn hay không là chưa đủ. Cần tìm hiểu lần gần nhất vấn đề xảy ra, họ đã xử lý như thế nào, mất bao lâu và kết quả cuối cùng ra sao. 
**6.5. Điều khó nhất khi viết Problem Statement là gì?**
Điều khó nhất đối với em là diễn đạt vấn đề đủ cụ thể nhưng không biến Problem Statement thành mô tả giải pháp. Khi mới tiếp cận, thường có xu hướng nói về công cụ hoặc công nghệ có thể sử dụng, thay vì tập trung vào nhu cầu thực tế của actor. Ngoài ra, việc xác định bottleneck cũng không đơn giản vì một quy trình có thể gồm nhiều bước liên quan đến nhau, nhưng không phải bước nào cũng gây ra ảnh hưởng lớn nhất.

Một khó khăn khác là xây dựng success metric có thể đo lường được. Nếu chỉ viết rằng giải pháp giúp tiết kiệm thời gian hoặc cải thiện hiệu quả thì rất khó đánh giá thành công. Cần có baseline, target và cách đo cụ thể. 
**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**
Nếu được thực hiện lại, em sẽ dành nhiều thời gian hơn cho việc thu thập bằng chứng trước khi nhóm lựa chọn candidate problem. Thay vì nhanh chóng thống nhất một ý tưởng vì cảm thấy nó phù hợp với chuyên ngành AI, em yêu cầu làm rõ tần suất xuất hiện, thời gian xử lý, mức độ ảnh hưởng và những giải pháp người dùng đang sử dụng. 

Trong quá trình phản biện, em muốn tập trung nhiều hơn vào các điều như sau. Thứ nhất, actor đã được xác định đủ rõ chưa và có thực sự gặp vấn đề đó không? Thứ hai, bottleneck đã được chứng minh bằng dữ liệu hay mới chỉ là nhận định? Thứ ba, nhóm đã xem xét phương án No AI và Rule trước khi lựa chọn Workflow hoặc Agent chưa? 
**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.
Problem của nhóm là người thực hiện mô hình ML/DL gặp khó khăn khi kết quả đầu ra không như kỳ vọng và chưa dễ dàng xác định nguyên nhân. Quy trình hiện tại gồm chạy mô hình, kiểm tra kết quả, rà soát dữ liệu và cấu hình, điều chỉnh từng thành phần rồi chạy thử lại. Metric cần theo dõi là thời gian debug, số vòng thử nghiệm và chất lượng đầu ra của mô hình, với baseline phải được đo trước khi đánh giá mức cải thiện. Boundary là AI chỉ hỗ trợ phân tích code, log và đề xuất hướng kiểm tra, không tự ý thay đổi code chính hoặc quyết định kết quả cuối cùng. Mức can thiệp phù hợp để thử nghiệm là Workflow có AI hỗ trợ, kết hợp các bước kiểm tra theo quy tắc và sự xác nhận của con người. Nhóm chỉ nên đưa ra quyết định Go khi có bằng chứng cho thấy giải pháp thực sự giảm thời gian xử lý mà vẫn đảm bảo chất lượng kết quả; nếu chưa đủ dữ liệu thì nên chọn Not Yet và tiếp tục kiểm chứng.
---

## 7. Tài liệu tham khảo
- Python docs — The Python Profilers (cProfile): https://docs.python.org/3/library/profile.html
- Andrej Karpathy, A Recipe for Training Neural Networks (2019): http://karpathy.github.io/2019/04/25/recipe/
