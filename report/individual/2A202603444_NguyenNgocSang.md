# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).

## 1. Thông tin học viên

- Họ tên: Nguyễn Ngọc Sang
- MSSV: 2A202603444
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: Nhóm 4.1
- Link repository: https://github.com/nguyenkhoinguyen07122005-cpu/K5-L3A-DAY02-NguyenKhoiNguyen-2A202603453-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 |Lặp lại |Nhận yêu cầu mua hàng từ các phòng ban, tôi muốn hệ thống tự kiểm tra thông tin, ngân sách và trạng thái phê duyệt, để không phải kiểm tra từng yêu cầu thủ công. |Nhân viên mua hàng, Procurement Manager, Kế toán | Giả định 20–30 yêu cầu/ngày, mỗi yêu cầu mất 5–10 phút kiểm tra.|
| 2 |Tốn thời gian |Nhà cung cấp gửi bảng giá với nhiều định dạng khác nhau, tôi muốn tự động trích xuất và so sánh giá giữa các nhà cung cấp, để lựa chọn phương án phù hợp nhanh hơn. |Nhân viên mua hàng, Procurement Manager |5 nhà cung cấp × 10 sản phẩm, mỗi lần so sánh thủ công mất khoảng 30–60 phút.|
| 3 |Lặp lại |Nhân viên mới gia nhập công ty, tôi muốn hệ thống tự kiểm tra các giấy tờ và thông tin onboarding còn thiếu, để không phải nhắc từng người bổ sung hồ sơ. |HR, HR Admin, nhân viên mới |Giả định 10–20 nhân viên mới/tháng, mỗi hồ sơ mất 5–10 phút kiểm tra. |
| 4 |Dễ bỏ sót |Hợp đồng với đối tác sắp hết hạn, tôi muốn nhận được thông báo trước thời hạn và xem các điều khoản quan trọng, để tránh bỏ lỡ thời gian gia hạn hoặc đàm phán. |Pháp chế, Procurement, quản lý hợp đồng |Giả định doanh nghiệp quản lý 100–200 hợp đồng, phải kiểm tra hạn sử dụng định kỳ. |
| 5 |Tốn thời gian |Khách hàng yêu cầu thay đổi lịch giao hàng, tôi muốn hệ thống kiểm tra lịch vận chuyển, tình trạng hàng hóa và khả năng đáp ứng, để không phải liên hệ nhiều bộ phận để xác nhận. |Nhân viên logistics, Customer Service, Operations Manager |Giả định 10–20 yêu cầu thay đổi/ngày, mỗi yêu cầu cần 10–15 phút xác minh. |
| 6 |Dễ mắc kẹt |Một dự án bị chậm tiến độ, tôi muốn xác định công việc nào đang bị phụ thuộc hoặc chưa hoàn thành, để biết chính xác nguyên nhân gây chậm trễ. |Project Manager, Team Leader, các bộ phận liên quan |Giả định phải kiểm tra 5–10 đầu việc và liên hệ nhiều người cho mỗi lần rà soát. |
| 7 |Tốn thời gian |Khách hàng hỏi về chính sách bảo hành, tôi muốn tra cứu thông tin theo mã sản phẩm, ngày mua và lịch sử sửa chữa, để trả lời chính xác mà không phải tìm kiếm qua nhiều tài liệu. |Customer Service, Technical Support |Giả định 20–40 yêu cầu/ngày, mỗi yêu cầu tra cứu mất 3–7 phút. |
| 8 |Lặp lại |Một chi nhánh có lượng tiêu thụ điện, nước tăng bất thường, tôi muốn hệ thống so sánh dữ liệu với lịch sử và các chi nhánh tương tự, để phát hiện nguyên nhân gây lãng phí. |Facility Manager, Operations Manager, Kế toán |Giả định phải kiểm tra dữ liệu của 10–20 cơ sở mỗi tháng. |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

-

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 |So sánh báo giá giữa các nhà cung cấp (#2) |Tốn thời gian, xử lý nhiều file, có thể tự động hóa trích xuất giá |Mỗi tháng có bao nhiêu yêu cầu, giá thấp chưa chắc chắn là tốt mà còn phụ thuộc vào chất lượng |
| 2 |Tra cứu chính sách bảo hành (#7) |Thông tin nằm rải rác nhiều file, phát sinh nhiều lần trong ngày |Dữ liệu lịch sử mua hàng, chính sách bảo hành mỗi sản phẩm khác nhau |
| 3 |Kiểm tra yêu cầu mua hàng (#1) |Tần suất xử lý cao, tiết kiệm thời gian |Bao nhiêu yêu cầu mỗi ngày |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi nhận báo giá từ nhiều nhà cung cấp dưới dạng Excel, PDF hoặc email, tôi muốn tự động trích xuất, chuẩn hóa và so sánh thông tin, để lựa chọn nhà cung cấp phù hợp mà không phải nhập liệu thủ công.|
| Actor |Nhân viên mua hàng (Procurement Staff), Procurement Manager, Kế toán. |
| Thời điểm / bối cảnh |Khi doanh nghiệp phát sinh nhu cầu mua nguyên vật liệu, thiết bị hoặc dịch vụ; cần thu thập và so sánh báo giá từ 3–5 nhà cung cấp trước khi trình phê duyệt. |
| Quy trình hiện tại (3–7 bước) |1. Tiếp nhận báo giá qua email hoặc file đính kèm. 2. Mở từng file Excel/PDF để kiểm tra thông tin. 3. Trích xuất tên sản phẩm, số lượng, đơn giá và chiết khấu. 4. Chuẩn hóa dữ liệu về cùng định dạng. 5. Tổng hợp vào bảng Excel chung. 6. Đối chiếu giá, vận chuyển và điều kiện thanh toán. 7. Gửi bảng so sánh cho quản lý. |
| Bottleneck (bước nào, mất bao nhiêu phút) |- Đọc và trích xuất báo giá: 10–15 phút. - Chuẩn hóa tên sản phẩm, đơn vị: 10–15 phút. - Tổng hợp bảng so sánh: 10–15 phút. - Đối chiếu điều kiện: 10–15 phút. Tổng: 40–60 phút/bộ báo giá. |
| Impact (nếu không giải thì sao) |Mất thời gian nhập liệu; dễ nhầm giá hoặc bỏ sót điều kiện; chậm quá trình lựa chọn nhà cung cấp; khó kiểm soát lịch sử thay đổi báo giá. |
| Success metric (baseline → target) |- Thời gian xử lý: 45–60 → 10–15 phút/bộ. - Độ chính xác trích xuất dữ liệu: chưa đo → ≥95%. - Tỷ lệ trường thông tin được trích xuất đầy đủ: chưa đo → ≥95%. |
| Phương án không dùng AI |Sử dụng Excel Template, Power Query để hợp nhất dữ liệu; công thức Excel để tính toán và so sánh giá; quy tắc kiểm tra dữ liệu đầu vào. |
| Giả thuyết về AI (nếu có) |OCR/Document AI đọc nội dung PDF; LLM trích xuất thông tin; AI Mapping chuẩn hóa tên sản phẩm; tự động tạo bảng so sánh và đánh dấu thông tin thiếu. |
| Cảm nhận nhanh | AI / Workflow |

Quy trình nháp hiện tại:

```text
Khoảng 55-60 phút/yêu cầu
[1 Nhận báo giá: 3'] → [2 Mở và kiểm tra file: 12'] → [3 Trích xuất dữ liệu: 12']
→ [4 Chuẩn hóa và tổng hợp Excel: 12'] → [5 So sánh giá và điều kiện: 15'] ← BOTTLENECK
→ [6 Gửi quản lý xem xét: 5']
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi khách hàng liên hệ hỏi về chính sách bảo hành, tôi muốn tra cứu thông tin dựa trên mã sản phẩm, ngày mua và lịch sử sửa chữa, để trả lời chính xác mà không phải tìm kiếm qua nhiều tài liệu hoặc chờ bộ phận kỹ thuật xác nhận.|
| Actor |Nhân viên chăm sóc khách hàng (Customer Service), Technical Support, Warranty Manager, khách hàng. |
| Thời điểm / bối cảnh |Khi khách hàng muốn kiểm tra thời hạn bảo hành, điều kiện bảo hành miễn phí, tình trạng sửa chữa hoặc quyền lợi bảo hành của sản phẩm. |
| Quy trình hiện tại (3–7 bước) |1. Tiếp nhận câu hỏi từ khách hàng qua hotline, email hoặc ứng dụng. 2. Thu thập mã sản phẩm và thông tin mua hàng. 3. Tìm kiếm chính sách bảo hành tương ứng. 4. Kiểm tra ngày mua và thời hạn bảo hành. 5. Tra cứu lịch sử sửa chữa của sản phẩm. 6. Đối chiếu điều kiện bảo hành. 7. Phản hồi khách hàng hoặc chuyển bộ phận kỹ thuật. |
| Bottleneck (bước nào, mất bao nhiêu phút) |- Tìm thông tin sản phẩm: 1–2 phút. - Tra cứu chính sách: 2–3 phút. - Kiểm tra thời hạn: 1–2 phút. - Tra cứu lịch sử sửa chữa: 2–3 phút. - Tổng hợp phản hồi: 1–2 phút. Tổng: 7–12 phút/yêu cầu. |
| Impact (nếu không giải thì sao) |Khách hàng phải chờ lâu; nhân viên phụ thuộc vào kinh nghiệm cá nhân; dễ cung cấp sai thông tin; tăng số lượng yêu cầu phải chuyển sang bộ phận kỹ thuật. |
| Success metric (baseline → target) |- Thời gian tra cứu: 7–12 → 2–3 phút/yêu cầu. - Độ chính xác câu trả lời: chưa đo → ≥95%. - Tỷ lệ câu trả lời có nguồn tham chiếu: chưa đo → 100%. - Tỷ lệ yêu cầu phải chuyển kỹ thuật: baseline cần đo → giảm 20%. |
| Phương án không dùng AI |Xây dựng cơ sở dữ liệu chính sách bảo hành tập trung; tạo bảng tra cứu theo mã sản phẩm; sử dụng SQL/CRM để kiểm tra thời hạn và lịch sử sửa chữa; xây dựng FAQ cho nhân viên. |
| Giả thuyết về AI (nếu có) |RAG tìm kiếm thông tin trong tài liệu bảo hành; LLM hiểu câu hỏi tự nhiên; AI Assistant tổng hợp câu trả lời kèm nguồn tham chiếu; tự động nhận diện các trường hợp cần chuyển chuyên viên. |
| Cảm nhận nhanh | Agent / RAG|

Quy trình nháp hiện tại:

```text
Khoảng 10 phút/yêu cầu
[1 Tiếp nhận câu hỏi: 1'] → [2 Thu thập thông tin sản phẩm: 2'] → [3 Tìm chính sách bảo hành: 3']
→ [4 Kiểm tra thời hạn và điều kiện: 2'] → [5 Đối chiếu lịch sử sửa chữa: 1']
→ [6 Phản hồi khách hàng: 1'] ← BOTTLENECK: Tìm kiếm chính sách
```

### Problem Card #3
| Trường | Nội dung |
|---|---|
| Job Story | Khi …, tôi muốn …, để … |
| Actor |Nhân viên mua hàng (Procurement Staff), Procurement Manager, nhân viên các phòng ban, Finance/Accounting. |
| Thời điểm / bối cảnh |Khi phòng ban gửi yêu cầu mua sắm thiết bị, vật tư hoặc dịch vụ; đặc biệt khi số lượng yêu cầu lớn hoặc hồ sơ có thông tin chưa đầy đủ. |
| Quy trình hiện tại (3–7 bước) |1. Tiếp nhận phiếu yêu cầu mua hàng. 2. Kiểm tra tên hàng hóa, số lượng và mục đích mua. 3. Kiểm tra thông tin phòng ban yêu cầu. 4. Đối chiếu chi phí với ngân sách được phân bổ. 5. Xác minh trạng thái phê duyệt. 6. Liên hệ bổ sung nếu hồ sơ thiếu thông tin. 7. Chuyển yêu cầu hợp lệ sang bộ phận mua hàng tiếp theo. |
| Bottleneck (bước nào, mất bao nhiêu phút) |- Kiểm tra thông tin: 2–3 phút. - Đối chiếu ngân sách: 2–3 phút. - Xác minh phê duyệt: 1–2 phút. - Xử lý thông tin thiếu: 3–5 phút. Tổng: 8–13 phút/yêu cầu. |
| Impact (nếu không giải thì sao) |Nhân viên phải kiểm tra từng hồ sơ; yêu cầu thiếu thông tin bị trả lại nhiều lần; có nguy cơ xử lý yêu cầu vượt ngân sách; quy trình mua hàng bị chậm trễ. |
| Success metric (baseline → target) |	- Thời gian kiểm tra: 8–13 → 3–5 phút/yêu cầu. - Tỷ lệ phát hiện hồ sơ thiếu: chưa đo → ≥95%. - Tỷ lệ yêu cầu phải xử lý lại: baseline cần đo → giảm 30%. - Độ chính xác xác minh trạng thái phê duyệt: chưa đo → 100%. |
| Phương án không dùng AI |Sử dụng Google Forms/Microsoft Forms để chuẩn hóa biểu mẫu; Excel/SQL kiểm tra dữ liệu; thiết lập IF/ELSE để xác minh điều kiện; Power Automate gửi thông báo khi hồ sơ thiếu. |
| Giả thuyết về AI (nếu có) |LLM đọc và phân loại yêu cầu bằng văn bản tự do; AI Classification nhận diện loại hàng hóa; Anomaly Detection phát hiện số lượng hoặc chi phí bất thường; Workflow tự động chuyển yêu cầu đến đúng bộ phận. |
| Cảm nhận nhanh |Workflow |


Quy trình nháp hiện tại:

```text
Khảong 12 phút/yêu cầu
[1 Tiếp nhận yêu cầu: 1'] → [2 Kiểm tra thông tin hàng hóa: 3'] → [3 Kiểm tra ngân sách: 3']
→ [4 Kiểm tra phê duyệt: 2'] → [5 Yêu cầu bổ sung hồ sơ: 2'] ← BOTTLENECK
→ [6 Chuyển yêu cầu hợp lệ: 1']
```

### Card muốn pitch nhất

- Card số: #1 - So sánh báo giá nhà cung cấp.
- Vì sao: Đây là công việc lặp lại, tốn thời gian do nhân viên phải mở nhiều file Excel/PDF, nhập và chuẩn hóa dữ liệu thủ công sau đó đối chiếu giá, số lượng, chiết khấu và điều kiện giao hàng. AI có thể hỗ trợ trích xuất và tổng hợp thông tin, giúp rút ngắn thời gian xử lý, hạn chế sai sót và hỗ trợ bộ phận mua hàng đưa ra quyết định nhanh hơn.
- Câu hỏi muốn nhóm phản biện: Đây là công việc lặp lại, tốn thời gian do nhân viên phải mở nhiều file Excel/PDF, nhập và chuẩn hóa dữ liệu thủ công rồi đối chiếu giá, số lượng, chiết khấu và điều kiện giao hàng. AI có thể hỗ trợ trích xuất và tổng hợp thông tin, giúp rút ngắn thời gian xử lý, hạn chế sai sót và hỗ trợ bộ phận mua hàng đưa ra quyết định nhanh hơn.

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
|Báo giá từ nhà cung cấp có nhiều định dạng khác nhau, dễ gây sai lệch khi trích xuất dữ liệu. |Đồng ý |Bổ sung bước chuẩn hóa tên sản phẩm, đơn vị tính, số lượng và giá trước khi so sánh. |
|Chỉ so sánh giá có thể dẫn đến lựa chọn nhà cung cấp không phù hợp.|Đồng ý | Bổ sung các tiêu chí như chiết khấu, thời gian giao hàng và điều kiện thanh toán.|
|Chưa có số liệu thực tế chứng minh thời gian xử lý và tần suất công việc. |Đồng ý | Ghi rõ thời gian ước tính 45–60 phút/gói báo giá là giả định ban đầu, cần khảo sát để xác thực.|
|AI không nên tự quyết định nhà cung cấp được chọn.|Đồng ý |Xác định AI chỉ hỗ trợ tổng hợp, so sánh và đưa ra gợi ý; quyết định cuối cùng thuộc về nhân viên mua hàng/quản lý.|

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
|Pitch Problem Card |Đề xuất 3 candidate: so sánh báo giá nhà cung cấp, tra cứu chính sách bảo hành và kiểm tra yêu cầu mua hàng. Phân tích actor, bottleneck, thời gian và câu hỏi phản biện cho từng card. |Đóng góp 3 candidate vào bảng 12 vấn đề của nhóm. |
|Phản biện bài của bạn khác |Tham gia thảo luận và đánh giá các candidate của thành viên khác theo mức độ rõ ràng của pain point, khả năng kiểm chứng, tính khả thi và mức độ cần thiết của AI. |Góp phần so sánh các vấn đề trên cùng tiêu chí, tránh chọn chỉ vì ý tưởng nghe hấp dẫn. |
|Nhận phản biện |Nhận câu hỏi phản biện về card so sánh báo giá: AI có đọc chính xác nhiều định dạng không, có đánh giá được điều kiện giao hàng và thanh toán hay chỉ chọn giá thấp nhất không? |Làm rõ rằng AI chỉ hỗ trợ trích xuất, chuẩn hóa và so sánh; nhân viên mua hàng vẫn xác nhận dữ liệu và quyết định nhà cung cấp. |
|Gom cluster / cây OST |Tham gia gom 12 candidate thành 3 cluster: tổng hợp thông tin từ nhiều tài liệu, kiểm tra theo quy tắc có sẵn và tìm nguyên nhân lỗi bằng thử–sai. Tham gia xây dựng Opportunity Solution Tree. |Nhóm nhận ra candidate #8 thuộc cluster tìm nguyên nhân lỗi kỹ thuật và có pain liên quan đến nhiều vòng thử–sai. |
|Chọn candidate problem |Điều phối thời gian thảo luận, tham gia shortlist và chấm điểm các candidate. Đề xuất đánh giá theo actor, quy trình, pain, impact, tính khả thi và khả năng so sánh các mức AI. |Nhóm chọn #8 – Chẩn đoán nguyên nhân khi mô hình ML/DL cho kết quả kém, với tổng điểm 29. |
|Kiểm chứng / research |Phụ trách research giải pháp có sẵn; tìm hiểu và trực tiếp mở, kiểm tra Deepchecks, Cleanlab và bài viết của Andrej Karpathy. |Xác định phần kiểm tra dữ liệu có thể giải quyết bằng Rule; khoảng trống còn lại là xếp hạng và giải thích các nguyên nhân có khả năng gây lỗi. |
|Quy trình nhóm |Xây dựng quy trình cho 3 candidate do mình đề xuất, xác định thời gian từng bước và bottleneck. Tham gia thảo luận quy trình hiện tại/tương lai của candidate #8. |Cung cấp sơ đồ quy trình và thời gian ước tính cho 3 card; hỗ trợ nhóm nhận diện bottleneck và phân biệt phần Rule với phần AI. |
|Problem Statement |Tham gia thảo luận và góp ý về impact, metric và tính khả thi của problem đã chọn. |Góp phần làm rõ lý do chọn candidate #8 và liên hệ pain với số vòng huấn luyện lại, thay vì chỉ nhìn thời gian chẩn đoán. |
|Mức can thiệp AI |Tham gia đánh giá No AI, Rule, Workflow và Agent thông qua kết quả research và khả năng áp dụng thực tế. |Củng cố lựa chọn Workflow: Rule kiểm tra dữ liệu, AI xếp hạng giả thuyết, sinh viên xác nhận và quyết định. |
|Quyết định |Phụ trách tổng hợp và chốt 4 nhóm rủi ro Value, Usability, Feasibility, Viability; đề xuất quyết định Go và ngưỡng dừng. |Nhóm thống nhất Go, phạm vi nhỏ: pilot 2 tuần, không xây công cụ mới, có tiêu chí đánh giá và điều kiện dừng cụ thể. |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan |Brainstorm các vấn đề có thể ứng dụng AI trong hoạt động doanh nghiệp và tìm pain point. |Gợi ý nhiều tình huống, actor và công việc có thể cải thiện bằng công nghệ. |Một số ý tưởng còn chung chung, chưa chứng minh được vấn đề xảy ra thường xuyên hoặc gây thiệt hại đáng kể. |Lọc lại candidate theo actor, quy trình thực tế, bottleneck và khả năng đo lường. |
| CP2 Problem Card |Hỗ trợ viết Job Story, xác định actor, quy trình hiện tại, bottleneck và câu hỏi phản biện. |Giúp cấu trúc vấn đề rõ ràng, dễ so sánh giữa các candidate. |Thời gian xử lý và tần suất công việc có thể chỉ là ước lượng; một số đề xuất đã đi quá nhanh sang giải pháp AI. |Ghi rõ thời gian là giả định cần kiểm chứng, tách pain point khỏi solution và bổ sung các tiêu chí đánh giá. |
| CP4 Research |Hỗ trợ tìm hiểu các công cụ, giải pháp có sẵn như Deepchecks, Cleanlab và phương pháp kiểm tra mô hình. |Giúp tổng hợp chức năng, điểm mạnh, hạn chế và khả năng áp dụng của từng công cụ. |Mô tả tổng quan chưa đủ để chứng minh công cụ thực sự giải quyết được bottleneck của nhóm. |Trực tiếp mở và kiểm tra các nguồn, đối chiếu chức năng với quy trình chẩn đoán ML/DL và xác định khoảng trống còn lại. |
| CP5 Quy trình |Hỗ trợ mô tả các bước hiện tại/tương lai, tính thời gian và xác định bottleneck. |Giúp chuyển quy trình thành các bước tuần tự, dễ hình dung và so sánh. |Thời gian từng bước có thể chưa chính xác; nếu chỉ cộng thời gian thao tác sẽ bỏ qua thời gian chờ huấn luyện. |Phân biệt thời gian thao tác với thời gian chờ, nhấn mạnh chi phí của mỗi vòng huấn luyện lại và đặt bottleneck đúng vào bước đoán nguyên nhân. |
| CP5–6 Problem Statement |Hỗ trợ diễn đạt Problem Statement, impact, success metric và boundary. |Gợi ý cách chuyển vấn đề rộng thành một problem cụ thể, có actor và metric. |Nếu không kiểm soát, nội dung dễ chung chung như “giúp sinh viên cải thiện mô hình” và chưa phản ánh chi phí thực tế. |Thu hẹp phạm vi sang supervised learning với thời gian huấn luyện từ 15 phút trở lên; ưu tiên số vòng huấn luyện lại và tổng thời gian. |
| CP6 Mức can thiệp / quyết định |Hỗ trợ phân tích No AI, Rule, Workflow, Agent và các rủi ro. |Giúp nhóm nhìn rõ ưu, nhược điểm và mức độ tự động hóa của từng phương án. |AI có thể đề xuất Agent quá mức trong khi quy trình đã có thứ tự cố định và không cần tự ra quyết định. |Chọn Workflow: Rule kiểm tra dữ liệu, AI xếp hạng 3 giả thuyết, con người xác nhận. Bổ sung boundary và ngưỡng dừng cho pilot. |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

Khi nghe các thành viên trình bày top 3 problems, tôi nhận thấy mỗi người có góc nhìn khác nhau. Các vấn đề của Phương liên quan đến nghiệp vụ BA như tổng hợp yêu cầu, kiểm tra tính nhất quán giữa BRD/SRS và Test Cases. Trong khi đó, Nguyên và Tiến tập trung vào các vấn đề kỹ thuật như debug code, chẩn đoán mô hình ML/DL, firmware và xử lý dữ liệu.

Tôi học được rằng một vấn đề mất nhiều thời gian chưa chắc là candidate tốt nhất để ứng dụng AI. Cần xem xét thêm mức độ nghiêm trọng, khả năng tiếp cận dữ liệu, khả năng kiểm chứng và sự cần thiết của AI. Ví dụ, kiểm tra định dạng JSONL có thể được giải quyết bằng script thay vì AI. Qua đó, tôi hiểu rằng cần lựa chọn problem dựa trên giá trị thực tế và tính khả thi, không chỉ dựa vào mức độ phức tạp của công việc.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

Theo tôi, nhóm từng có lúc tiếp cận theo hướng solution-first. Ban đầu, một số ý tưởng được mô tả bằng công cụ muốn xây dựng, chẳng hạn như Agent AI tự động dò lỗi phần cứng hoặc chatbot hỗ trợ debug. Tuy nhiên, những ý tưởng này chưa làm rõ người dùng thực sự gặp khó khăn ở đâu.

Sau đó, nhóm chuyển từ câu hỏi “Xây dựng công cụ gì?” sang “Người dùng đang gặp vấn đề ở bước nào?”. Chúng tôi phân tích quy trình hiện tại, xác định bottleneck và tác động trước khi lựa chọn giải pháp. Opportunity Solution Tree cũng giúp phân biệt opportunity với solution. Tôi nhận ra rằng cần hiểu đúng vấn đề trước khi quyết định sử dụng AI, vì không phải công việc nào cũng cần một giải pháp AI phức tạp.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

Có. Với candidate so sánh báo giá nhà cung cấp, ban đầu tôi chủ yếu tập trung vào việc tự động đọc và so sánh giá từ nhiều file Excel hoặc PDF. Tuy nhiên, sau khi thảo luận, tôi nhận ra giá thấp nhất chưa chắc là lựa chọn tốt nhất.

Việc so sánh còn cần xét đến chiết khấu, điều kiện thanh toán và thời gian giao hàng. Ngoài ra, dữ liệu trích xuất từ các báo giá cần được kiểm tra để tránh sai lệch. Vì vậy, tôi điều chỉnh ý tưởng theo hướng AI hỗ trợ tổng hợp và so sánh nhiều tiêu chí, trong khi nhân viên mua hàng vẫn xác nhận thông tin và đưa ra quyết định cuối cùng. Qua đó, tôi học được cách nhìn vấn đề toàn diện hơn thay vì chỉ tập trung vào chức năng ban đầu.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

Điều khiến tôi chú ý là nhiều vấn đề có thể được giải quyết bằng công cụ No AI hoặc Rule-based system. Ví dụ, script có thể kiểm tra định dạng dữ liệu, Deepchecks hỗ trợ kiểm tra chất lượng dữ liệu và Cleanlab hỗ trợ phát hiện nhãn sai.

Điều này giúp tôi nhận ra AI không nhất thiết phải thay thế toàn bộ quy trình. Với problem nhóm lựa chọn, Rule có thể kiểm tra các lỗi dữ liệu rõ ràng, còn AI hỗ trợ tổng hợp metrics và xếp hạng các giả thuyết về nguyên nhân mô hình hoạt động kém. Người học vẫn cần kiểm chứng trước khi chỉnh sửa và retrain.

Tôi cũng nhận ra rằng nghiên cứu công cụ hiện có chưa đủ để chứng minh mức độ nghiêm trọng của pain point. Các con số về thời gian và số vòng retrain vẫn cần được xác thực bằng dữ liệu thực tế.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

Điều khó nhất với tôi là xác định bottleneck và lựa chọn metric phù hợp. Ban đầu, tôi nghĩ thời gian chẩn đoán là yếu tố quan trọng nhất. Tuy nhiên, khi phân tích workflow, nhóm nhận ra vấn đề lớn hơn là người học phải thử nhiều giả thuyết và retrain khi phỏng đoán sai nguyên nhân.

Mỗi lần retrain có thể mất 15–60 phút. Vì vậy, nhóm chọn số vòng retrain và tổng thời gian xử lý làm metric chính. Mục tiêu là giảm từ khoảng 3 xuống tối đa 2 vòng và từ khoảng 190 xuống tối đa 120 phút.

Tuy nhiên, đây mới là số liệu ước lượng và mục tiêu thử nghiệm. Tôi cũng học được rằng Problem Statement cần xác định rõ người dùng, phạm vi và giới hạn của AI. AI chỉ đề xuất giả thuyết, không tự sửa code hoặc kết luận nguyên nhân khi chưa được con người xác nhận.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

Nếu làm lại, tôi sẽ kiểm chứng pain point sớm hơn. Khi đề xuất ba candidate về mua hàng và bảo hành, tôi chủ yếu dựa vào quy trình và thời gian ước lượng. Tôi sẽ thu thập số liệu từ người trực tiếp làm nghiệp vụ, chẳng hạn như thời gian xử lý báo giá, số lượng yêu cầu bảo hành và tỷ lệ hồ sơ bị trả lại.

Tôi cũng sẽ phản biện mạnh hơn về việc liệu AI có thực sự cần thiết hay không. Một số công việc có thể được giải quyết bằng Excel, SQL hoặc Rule-based system mà không cần mô hình AI.

Đối với problem nhóm lựa chọn, tôi sẽ yêu cầu làm rõ cơ sở của ước lượng 3 vòng retrain và 190 phút, vì đây chưa phải số liệu đại diện cho nhiều người dùng. Tôi cũng muốn nhóm xác định cách đo hiệu quả và điều kiện dừng thử nghiệm ngay từ đầu. Qua đó, tôi hiểu rằng phản biện không chỉ nhằm tìm lỗi trong ý tưởng mà còn giúp nhóm đưa ra quyết định dựa trên bằng chứng thực tế.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

Bài toán nhóm lựa chọn là hỗ trợ sinh viên làm supervised learning tìm nguyên nhân khi mô hình cho kết quả kém, thay vì phải đoán và huấn luyện lại nhiều lần. Quy trình hiện tại gồm huấn luyện mô hình, kiểm tra dữ liệu và tiền xử lý, đối chiếu chỉ số, đoán nguyên nhân, sửa và huấn luyện lại. Bottleneck nằm ở bước đối chiếu chỉ số và đoán nguyên nhân, vì mỗi giả thuyết sai có thể khiến sinh viên mất thêm 15–60 phút cho một vòng huấn luyện. Nhóm đặt mục tiêu giảm số vòng huấn luyện lại từ khoảng 3 xuống tối đa 2, đồng thời giảm tổng thời gian từ khoảng 190 phút xuống không quá 120 phút mỗi bài. AI không được tự sửa code, tự chạy huấn luyện hoặc kết luận nguyên nhân khi chưa có kiểm tra xác nhận. Nhóm chọn Workflow: Rule thực hiện kiểm tra dữ liệu, AI xếp hạng ba giả thuyết kèm bằng chứng và cách xác nhận, còn sinh viên là người quyết định và thực hiện sửa lỗi. Cuối cùng, nhóm quyết định Go với phạm vi nhỏ, triển khai pilot trong hai tuần mà chưa xây dựng công cụ mới, đồng thời đặt các ngưỡng dừng nếu kết quả không đạt yêu cầu.

## 7. Tài liệu tham khảo
- Andrej Karpathy – A Recipe for Training Neural Networks (2019)
- Google – Rules of Machine Learning
- Google Research – Data Validation for Machine Learning (2019)
