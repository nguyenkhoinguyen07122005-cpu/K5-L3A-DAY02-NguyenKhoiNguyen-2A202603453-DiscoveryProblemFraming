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
| 1 | Tìm nguyên nhân code Python sai | Ba dòng cùng một pattern, quy trình vẽ được | Baseline mới là ước lượng (<15 phút) nên pain có thể nhỏ; chưa rõ bottleneck nằm ở bước đọc code hay bước thử sửa; debugger + test có thể đã đủ giải quyết |
| 2 | Tìm nguyên nhân mô hình ML/DL cho kết quả kém | Cần đối chiếu nhiều nguồn: dữ liệu, xử lý, chỉ số | Chưa rõ tần suất gặp; nguyên nhân thường nằm ở dữ liệu hay ở tham số; mỗi bài/mô hình khác nhau nên khó chuẩn hóa quy trình |
| 3 | Tìm đoạn code/bước chạy chậm | Có thể đo được thời gian trước và sau | Chậm có thể do phần cứng hoặc kích thước dữ liệu chứ không do code; profiler có sẵn có thể đã giải quyết bước "tìm đoạn chậm" mà không cần AI |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi làm bài Python phức tạp, tôi muốn nhanh chóng xác định nguyên nhân khiến code cho kết quả sai, để không phải thử sửa nhiều lần. |
| Actor | Sinh viên làm bài lập trình Python |
| Thời điểm / bối cảnh | Khi làm bài tập lập trình Python có nhiều hàm, thường trong 1–2 ngày trước hạn nộp, lúc output không khớp với output mẫu hoặc test case. |
| Quy trình hiện tại (3–7 bước) | 1. Chạy code, thấy kết quả sai · 2. Đọc lại code · 3. In giá trị trung gian · 4. Thử sửa · 5. Chạy lại · 6. Lặp lại đến khi đúng |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 4 "Thử sửa" và vòng lặp 4 → 5 → 6: sửa theo phỏng đoán khi chưa có giả thuyết rõ, nên phải chạy lại nhiều lần. Ước lượng khoảng 6 phút cho vòng lặp này / tổng khoảng 13 phút. |
| Impact (nếu không giải thì sao) | Tốn thời gian sát hạn nộp; sửa sai chỗ dễ làm hỏng phần đang chạy đúng (liên quan #5); ít thời gian kiểm tra kỹ phần khác, tăng rủi ro nộp bài còn lỗi. |
| Success metric (baseline → target) | Baseline: dưới 15 phút/lần (tự ước lượng, cần bấm giờ lại để chính xác). Target: giảm ≥ 50% thời gian tìm nguyên nhân và số lần thử sửa ≤ 2 lần/lỗi. Cách đo: tự bấm giờ và đếm số lần chạy lại cho mỗi lỗi trong 1–2 tuần |
| Phương án không dùng AI | Debugger từng bước, kiểm thử nhỏ cho từng hàm, checklist tìm lỗi |
| Giả thuyết về AI (nếu có) | Nếu đưa code + input + output mong đợi/thực tế cho LLM, AI có thể đề xuất 2–3 giả thuyết nguyên nhân kèm vị trí nghi ngờ, giúp bỏ bớt các vòng thử sửa "mù". Người vẫn tự xác minh bằng debugger/test trước khi sửa. |
| Cảm nhận nhanh | Workflow — nhưng phải so sánh kỹ với No AI (debugger + unit test) vì có thể đã đủ |

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
| Quy trình hiện tại (3–7 bước) | 1. Huấn luyện và xem chỉ số · 2. Kiểm tra dữ liệu đầu vào · 3. Kiểm tra bước tiền xử lý · 4. Xem lại chỉ số · 5. Đổi tham số hoặc dữ liệu · 6. Huấn luyện lại |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 4–5: đối chiếu chỉ số với dữ liệu/tiền xử lý để đoán nguyên nhân rồi đổi tham số. Mỗi giả thuyết sai phải trả giá bằng một lần huấn luyện lại 15–60 phút. Ước lượng: khoảng 10 phút đối chiếu, huấn luyện lại khoảng 3 lần trước khi tìm ra nguyên nhân. |
| Impact (nếu không giải thì sao) | Mỗi giả thuyết sai tốn một vòng huấn luyện; dễ chỉnh tham số ngẫu nhiên trong khi lỗi thật nằm ở dữ liệu (rò rỉ dữ liệu, sai nhãn, chuẩn hóa sai, mất cân bằng lớp); kết quả cuối kém và khó giải thích trong báo cáo. |
| Success metric (baseline → target) | Baseline: dưới 30 phút/lần (tự ước lượng). Target: thời gian chẩn đoán ≤ 15 phút và số lần huấn luyện lại trước khi tìm ra nguyên nhân ≤ 2. Cách đo: tự bấm giờ mỗi lần và ghi log mỗi lần huấn luyện (tham số, chỉ số, lý do chạy lại) |
| Phương án không dùng AI | Checklist chẩn đoán (dữ liệu → tiền xử lý → chỉ số), ghi log mỗi lần chạy |
| Giả thuyết về AI (nếu có) | Nếu đưa log huấn luyện, thống kê mô tả dữ liệu và code tiền xử lý cho LLM, AI có thể liệt kê các nguyên nhân khả dĩ theo checklist (overfit/underfit, rò rỉ dữ liệu, mất cân bằng lớp, sai scale) và gợi ý kiểm tra rẻ nhất cần làm **trước** khi huấn luyện lại. Người quyết định có huấn luyện lại hay không. |
| Cảm nhận nhanh | Workflow (checklist dạng Rule + LLM tóm tắt, đối chiếu và xếp hạng giả thuyết) |

Quy trình nháp hiện tại:

```text
[1 Huấn luyện + xem chỉ số: 30'] → [2 Kiểm tra dữ liệu: 5'] → [3 Kiểm tra tiền xử lý: 5']
→ [4 Đối chiếu chỉ số: 10'] ← BOTTLENECK → [5 Đổi tham số: 3'] → [6 Huấn luyện lại: 30']
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
| Success metric (baseline → target) | Baseline: 15–60 phút/lần chạy (tự ước lượng). Target: giảm ≥ 30% thời gian chạy; thời gian tìm đoạn chậm ≤ 10 phút. Cách đo: ghi thời gian chạy mỗi lần |
| Phương án không dùng AI | Công cụ profiling có sẵn (ví dụ cProfile), đo giờ từng bước |
| Giả thuyết về AI (nếu có) | Profiler đã chỉ ra đoạn chậm, nên AI chỉ có giá trị ở bước gợi ý cách tối ưu (vector hóa, cache, batch, tăng `num_workers` của DataLoader…) dựa trên output profiler. |
| Cảm nhận nhanh | No AI / Rule (dùng profiler là chính) |

Quy trình nháp hiện tại:

```text
[1 Chạy và chờ: 20'] → [2 Đoán đoạn chậm: 5'] → [3 Thêm lệnh đo giờ: 10'] ← BOTTLENECK → [4 Sửa: 5'] → [5 Chạy lại: 20']
```

### Card muốn pitch nhất

- Card số: 2
- Vì sao: Đây là card cần tổng hợp nhiều nguồn thông tin nhất (dữ liệu, tiền xử lý, chỉ số, log) và mỗi giả thuyết sai rất đắt (một lần huấn luyện lại 15–60 phút). Card #1 có baseline nhỏ (<15 phút) và debugger có thể đã đủ; card #3 phần lớn giải được bằng profiler, không cần AI.
- Câu hỏi muốn nhóm phản biện: Các bạn thường phải huấn luyện lại bao nhiêu lần trước khi tìm ra nguyên nhân mô hình kém? Một checklist chẩn đoán không dùng AI có đủ không, hay bước đối chiếu nhiều nguồn thật sự cần AI?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Mọi baseline đều là tự ước lượng, chưa bấm giờ thật → success metric chưa đáng tin | Đồng ý | Ghi rõ "tự ước lượng" ở mọi baseline; thêm cách đo (bấm giờ + log mỗi lần chạy trong 1–2 tuần) |
| Card #1 baseline < 15 phút, pain có thể quá nhỏ để cần AI; debugger + unit test có thể đã đủ | Đồng ý | Không chọn #1 để pitch; ghi No AI là phương án so sánh chính |
| Card #2 job story còn rộng ("kết quả không như mong đợi"), chưa rõ loại bài/mô hình nên khó đo | Đồng ý một phần | Bổ sung bối cảnh cụ thể (sau lần huấn luyện đầu, chỉ số thấp hoặc lệch train/val) và metric "số lần huấn luyện lại" |
| Card #3: profiler đã giải bước "tìm đoạn chậm", phần AI mỏng | Đồng ý | Đổi cảm nhận nhanh sang No AI / Rule |
| Actor đều là bản thân tôi, chưa có bằng chứng từ người khác | Đồng ý | Ghi vào "Điều còn chưa chắc"; cần hỏi 3–5 bạn cùng lớp ở CP4 |

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
| CP2 Problem Card | Paraphrase lại các ý tưởng của tôi; phản biện điểm yếu của từng card | Chỉ ra card #3 giải được bằng profiler, card #1 có thể chỉ cần debugger | Số liệu ước lượng AI đề xuất là con số điển hình, chưa chắc khớp trải nghiệm thật của tôi | Đối chiếu lại với bài gần nhất, chỉnh số cho đúng|
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
