# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm. Khi chốt bản cuối, **mỗi thành viên copy file này vào repo cá nhân**.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm:
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu):
- Quyết định cuối: Go / Not Yet / No-Go

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 |Nguyễn Ngọc Sang |#1 – So sánh báo giá nhà cung cấp: Khi nhận nhiều báo giá từ các nhà cung cấp, nhân viên mua hàng cần tổng hợp và so sánh giá, số lượng, chiết khấu và điều kiện giao hàng để lựa chọn nhà cung cấp phù hợp. |Nhân viên mua hàng (Procurement Staff), Quản lý mua hàng (Procurement Manager), Kế toán. |Trích xuất, chuẩn hóa và tổng hợp dữ liệu từ nhiều file Excel/PDF có định dạng khác nhau; mất khoảng 35–40 phút. |Quản lý mua hàng: Làm thế nào đảm bảo AI đọc chính xác báo giá từ nhiều định dạng khác nhau? AI có đánh giá được điều kiện giao hàng và thanh toán thay vì chỉ chọn giá thấp nhất không? |
| 2 |Nguyễn Ngọc Sang |#2 – Tra cứu chính sách bảo hành: Khi khách hàng hỏi về bảo hành, nhân viên cần tra cứu thông tin sản phẩm, ngày mua và lịch sử sửa chữa để đưa ra câu trả lời chính xác. |Nhân viên chăm sóc khách hàng (Customer Service), Nhân viên kỹ thuật (Technical Support), Quản lý bảo hành. |Tìm kiếm chính sách và đối chiếu thông tin từ nhiều nguồn; mất khoảng 4–6 phút. |Nhân viên chăm sóc khách hàng: Làm thế nào đảm bảo câu trả lời của AI đúng với chính sách hiện hành? Nếu thông tin sản phẩm hoặc lịch sử sửa chữa không đầy đủ thì AI xử lý thế nào? |
| 3 |Nguyễn Ngọc Sang |#3 – Kiểm tra yêu cầu mua hàng: Khi nhận yêu cầu mua hàng từ các phòng ban, nhân viên cần kiểm tra thông tin, ngân sách và trạng thái phê duyệt trước khi chuyển sang bước xử lý tiếp theo. |Nhân viên mua hàng, Quản lý mua hàng, Nhân viên phòng ban đề xuất, Kế toán. |Kiểm tra ngân sách, trạng thái phê duyệt và xử lý hồ sơ thiếu thông tin; mất khoảng 5–7 phút. |Kế toán: AI dựa vào đâu để xác định yêu cầu vượt ngân sách hoặc chưa được phê duyệt? Làm thế nào tránh việc AI đánh giá sai và chuyển tiếp yêu cầu không hợp lệ? |
| 4 |Đào Thị Thu Phương |Khi nhận yêu cầu từ nhiều phòng ban qua email, Word và Excel, tôi muốn tổng hợp và chuẩn hóa các yêu cầu thành một danh sách thống nhất để tránh bỏ sót thông tin. |Business Analyst, Project Manager, các phòng ban |Đọc, trích xuất và đối chiếu yêu cầu từ nhiều nguồn, mất khoảng 120–180 phút/lần. |AI có thể đọc hiểu chính xác các định dạng tài liệu khác nhau không? Làm thế nào để tránh bỏ sót hoặc hiểu sai yêu cầu? (AI phản biện) |
| 5 |Đào Thị Thu Phương |Khi hoàn thành BRD, SRS, User Stories và Test Cases, tôi muốn kiểm tra tính nhất quán giữa các tài liệu để phát hiện yêu cầu bị thiếu hoặc mâu thuẫn. |Business Analyst, Developer, Tester |Đối chiếu nội dung và phát hiện sai lệch giữa các tài liệu, mất khoảng 120–180 phút/lần. |AI có thể phát hiện chính xác các sai lệch về ngữ nghĩa và quy tắc nghiệp vụ không? (AI phản biện) |
| 6 |Đào Thị Thu Phương |Khi kết thúc cuộc họp với khách hàng và đội phát triển, tôi muốn tự động tạo Meeting Minutes và Action Items để tiết kiệm thời gian ghi chép và tránh bỏ sót công việc. |Business Analyst, Project Manager, Developer, Tester |Nghe lại bản ghi, tổng hợp nội dung và xác định người phụ trách, deadline, mất khoảng 30–45 phút/cuộc họp. |AI có thể nhận diện chính xác người phát biểu, quyết định, người phụ trách và deadline không? (AI phản biện) |
| 7 | Nguyễn Khôi Nguyên | Khi code Python cho kết quả sai, muốn tìm nhanh nguyên nhân để không thử sửa nhiều lần | SV làm bài lập trình | Bước thử sửa theo phỏng đoán (vòng lặp sửa → chạy lại, ~6') | Debugger + unit test đã đủ chưa, cần gì thêm? |
| 8 | Nguyễn Khôi Nguyên | Khi mô hình ML/DL cho kết quả kém, muốn đối chiếu dữ liệu, tiền xử lý, chỉ số để tìm nguyên nhân | SV làm bài ML/DL | Bước đối chiếu chỉ số và đoán nguyên nhân (~10'), mỗi lần đoán sai tốn thêm 1 vòng huấn luyện 15–60' | Nếu không có AI, cách đơn giản nhất để giảm một nửa số vòng là gì? |
| 9 | Nguyễn Khôi Nguyên | Khi chương trình/huấn luyện chạy chậm, muốn tìm đoạn tốn thời gian | SV lập trình, ML/DL | Bước đoán đoạn chậm và thêm lệnh đo giờ (~15') | Chậm do code hay do phần cứng/dữ liệu lớn |
| 10 |Nguyễn Trần Tiến |#1 – Debug firmware phần cứng: Khi lập trình phần cứng cho hệ thống đồ án tốt nghiệp, tôi muốn tra cứu và đồng bộ thông số datasheet với code firmware, để hệ thống kiểm thử đạt hiệu suất tốt nhất và không đọc sai thông số. |Sinh viên làm đồ án tốt nghiệp (bản thân tôi), team, thầy hướng dẫn. |Sửa code firmware và dò lỗi ngoại vi (bước 6 trong 7 bước); mất khoảng 90 phút/lần (ước lượng), tổng ~10–12 giờ/tuần trong khoảng 2 tháng. |Câu hỏi tôi muốn nhóm phản biện: Agent AI có thật sự giúp tự động hóa khâu dò lỗi phần cứng ngoại vi vốn phụ thuộc nhiều vào tính chất vật lý của linh kiện hay không, hay chỉ nên dùng quy trình Rule-based để kiểm tra cú pháp cấu hình thanh ghi? |
| 11 |Nguyễn Trần Tiến |#2 – Đẩy dữ liệu cảm biến lên Cloud: Khi lập trình xong phần cứng firmware, tôi muốn truyền tải dữ liệu cảm biến lên đám mây, để lấy dữ liệu phục vụ huấn luyện hệ thống và cảnh báo qua giao diện web. |Sinh viên làm đồ án tốt nghiệp (bản thân tôi), team, thầy hướng dẫn. |Xử lý mất gói tin và kiểm tra độ ổn định đường truyền (bước 6 trong 7 bước); mất khoảng 120 phút/phiên (ước lượng), tổng 2–3 giờ/ngày trong hơn 2 tuần. |Điều tôi còn chưa chắc: độ ổn định của đường truyền mạng và cơ chế đồng bộ gói tin khi test thực tế. |
| 12 |Nguyễn Trần Tiến |#3 – Hỗ trợ thành viên mới định dạng tệp dữ liệu: Khi hướng dẫn thành viên mới định dạng tệp dữ liệu, tôi muốn tệp dữ liệu của các bạn đúng chuẩn ngay từ đầu, để không phải mất nhiều giờ ngồi kiểm tra và chỉ ra từng dòng lỗi thủ công. |Người hướng dẫn (bản thân tôi), thành viên mới trong lớp lab, team, thầy hướng dẫn. |Mở tệp JSONL dò từng dòng để tìm chỗ sai (bước 5 trong 7 bước); mất khoảng 45 phút/đợt (ước lượng), tổng ~110 phút/đợt, 1–2 lần/tháng. |Điều tôi còn chưa chắc: mức độ tự giác của thành viên mới trong việc chạy công cụ kiểm tra trước khi nhờ hỗ trợ. |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A | | |
| B | | |
| C | | |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: 
├── Opportunity A: 
├── Opportunity B: 
└── Opportunity C: 
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

-

### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| | | | | | | | | |
| | | | | | | | | |
| | | | | | | | | |

**Candidate được chọn:**

**Vì sao chọn:**

**Vì sao loại các candidate còn lại:**

**Xử lý bất đồng (nếu có):**

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
| **Boundary** (AI không được làm gì) | |

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
