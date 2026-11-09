# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).

## 1. Thông tin học viên

- Họ tên: Đào Thị Thu Phương
- MSSV: 2A202603457
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: 4.1
- Link repository: https://github.com/nguyenkhoinguyen07122005-cpu/K5-L3A-DAY02-NguyenKhoiNguyen-2A202603453-DiscoveryProblemFraming.git

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 |Lặp lại |Khi kết thúc mỗi cuộc họp, tôi muốn tự động tổng hợp biên bản, công việc cần thực hiện và người phụ trách để không phải ghi chép thủ công. |BA, Project Manager, Developer, Tester |Có 3 cuộc họp/ngày, mỗi cuộc mất thêm 20–30 phút để tổng hợp. Tốn khoảng 1–1,5 giờ/ngày. |
| 2 |Tốn thời gian |Khi nhận được yêu cầu nghiệp vụ từ khách hàng, tôi muốn nhanh chóng chuyển đổi chúng thành tài liệu BRD/SRS để tiết kiệm thời gian viết tài liệu. |BA, khách hàng, Developer, Tester |Một tài liệu có khoảng 20–30 yêu cầu, mất 5–6 giờ để phân tích và viết đặc tả. |
| 3 |Cần đọc, tổng hợp nhiều thông tin |Khi nhận yêu cầu từ nhiều phòng ban qua email, Excel và Word, tôi muốn tổng hợp thành một danh sách yêu cầu thống nhất để tránh bỏ sót thông tin. |BA, các phòng ban, Project Manager |Phải đọc 15–20 email, 3 file Excel và 2 file Word, mất khoảng 3 giờ cho mỗi lần tổng hợp. |
| 4 |Pain từ người khác |Khi khách hàng đưa ra yêu cầu chưa rõ ràng, tôi muốn xác định những thông tin còn thiếu và đặt câu hỏi phù hợp để tránh hiểu sai yêu cầu. |BA, khách hàng, Developer |Một yêu cầu có thể phải trao đổi 4–5 lượt email hoặc tin nhắn mới làm rõ được. Có thể kéo dài 1–2 ngày. |
| 5 |Lặp lại |Khi có thay đổi yêu cầu trong quá trình phát triển, tôi muốn cập nhật đồng bộ thông tin trên các tài liệu liên quan để tránh sử dụng phiên bản cũ. |BA, Developer, Tester, Project Manager |Trong một sprint có 20 yêu cầu, khoảng 5 yêu cầu thay đổi. Mất khoảng 2 giờ để cập nhật và thông báo cho các bên. |
| 6 |Cần đọc, tổng hợp nhiều thông tin |Khi phải đối chiếu BRD, SRS, User Stories và Test Cases, tôi muốn phát hiện những nội dung không nhất quán để đảm bảo tài liệu không bị sai lệch. |BA, Developer, Tester |Có khoảng 30 yêu cầu cần đối chiếu, mất 2–3 giờ kiểm tra thủ công và có nguy cơ bỏ sót lỗi. |
| 7 |Tốn thời gian |Khi nhận nhiều file Excel từ các phòng ban, tôi muốn tự động làm sạch, đối chiếu và phát hiện dữ liệu bất thường để giảm thời gian xử lý dữ liệu. |BA, Data Analyst, các phòng ban |Nhận 4 file Excel, mỗi file khoảng 1.000 dòng dữ liệu. Mất khoảng 3 giờ để kiểm tra trùng lặp và sai lệch. |
| 8 |Pain từ người khác |Khi Developer hoặc Tester báo cáo lỗi, tôi muốn nhanh chóng đối chiếu lỗi với yêu cầu nghiệp vụ ban đầu để xác định nguyên nhân và hướng xử lý. |BA, Developer, Tester, Project Manager |Nhận khoảng 15 bug trong một đợt kiểm thử, mất 2–3 giờ để kiểm tra và trao đổi với các bên liên quan. |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

-
Sau khi tham khảo các gợi ý từ AI, tôi quyết định giữ lại vấn đề 1 (tự động tạo Meeting Minutes), vấn đề 2 (hỗ trợ viết tài liệu BRD/SRS), vấn đề 3 (tổng hợp yêu cầu từ nhiều nguồn), vấn đề 4 (phát hiện yêu cầu chưa rõ ràng), vấn đề 6 (kiểm tra tính nhất quán giữa các tài liệu) và vấn đề 7 (tự động làm sạch, đối chiếu dữ liệu Excel). Đây là những công việc lặp lại, tốn nhiều thời gian và có khả năng ứng dụng AI để tự động hóa. Tôi cân nhắc thêm vấn đề 5 (đồng bộ tài liệu khi yêu cầu thay đổi) vì cần kiểm soát phiên bản và sự xác nhận của BA. Riêng vấn đề 8 (phân tích nguyên nhân và đề xuất cách sửa bug), tôi quyết định loại bỏ việc để AI tự động đưa ra quyết định vì công việc này đòi hỏi kiến thức chuyên sâu về nghiệp vụ và kỹ thuật, cần có sự đánh giá của con người.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 |Tổng hợp yêu cầu nghiệp vụ từ nhiều nguồn thông tin(#3) |BA thường phải đọc nhiều email, file Excel, Word từ các phòng ban. AI có thể tự động đọc, trích xuất và tổng hợp yêu cầu, giúp tiết kiệm thời gian và hạn chế bỏ sót thông tin. |AI có hiểu đúng ngữ cảnh nghiệp vụ không? Có xử lý tốt các yêu cầu mâu thuẫn hoặc trùng lặp không? |
| 2 |Tự động tạo Meeting Minutes và Action Items(#1) |BA thường xuyên tham gia nhiều cuộc họp và phải ghi chép, tổng hợp nội dung, phân công nhiệm vụ. AI có thể chuyển nội dung cuộc họp thành biên bản có cấu trúc, giúp giảm thời gian xử lý thủ công. |AI có nhận diện chính xác người phát biểu, nội dung thảo luận, người phụ trách và thời hạn công việc không? |
| 3 |Kiểm tra tính nhất quán giữa BRD, SRS, User Stories và Test Cases(#6) |Việc đối chiếu tài liệu thủ công tốn nhiều thời gian và dễ xảy ra sai sót. AI có thể hỗ trợ phát hiện yêu cầu bị thiếu, nội dung không thống nhất và các điểm cần chỉnh sửa. |AI có phát hiện chính xác các sai lệch không? Có bỏ sót những quy tắc nghiệp vụ phức tạp không? |

### Problem Card #1: Tổng hợp yêu cầu nghiệp vụ từ nhiều nguồn thông tin

| Trường | Nội dung |
|---|---|
| Job Story |Khi nhận được yêu cầu từ nhiều phòng ban thông qua email, Excel và Word, tôi muốn tổng hợp và chuẩn hóa các yêu cầu thành một danh sách thống nhất, để tránh bỏ sót thông tin và tiết kiệm thời gian phân tích. |
| Actor |Business Analyst (BA), Project Manager, các phòng ban liên quan. |
| Thời điểm / bối cảnh |Khi bắt đầu dự án mới hoặc khi khách hàng, các phòng ban gửi yêu cầu thay đổi, bổ sung chức năng. |
| Quy trình hiện tại (3–7 bước) |	1. Tiếp nhận yêu cầu qua email, Word, Excel. 2. Đọc và phân loại nội dung theo từng phòng ban. 3. Trích xuất các yêu cầu nghiệp vụ. 4. So sánh, tìm các yêu cầu trùng lặp hoặc mâu thuẫn. 5. Tổng hợp thành danh sách yêu cầu chung. 6. Gửi lại các bên liên quan để xác nhận. |
| Bottleneck (bước nào, mất bao nhiêu phút) |Bước 2–4: Đọc, trích xuất và đối chiếu thông tin từ nhiều nguồn, mất khoảng 120–180 phút cho một lần tổng hợp. |
| Impact (nếu không giải thì sao) |Tốn nhiều thời gian của BA, dễ bỏ sót yêu cầu, thông tin bị trùng lặp hoặc mâu thuẫn, dẫn đến hiểu sai nghiệp vụ và ảnh hưởng tiến độ dự án. |
| Success metric (baseline → target) |Thời gian tổng hợp: 180 phút → 45 phút. 

 Tỷ lệ yêu cầu được trích xuất chính xác: 80% → 95%. |
| Phương án không dùng AI |Sử dụng Excel để quản lý yêu cầu, tạo biểu mẫu chuẩn và phân loại thủ công theo từng phòng ban. |
| Giả thuyết về AI (nếu có) |AI có thể đọc nhiều định dạng tài liệu, tự động trích xuất yêu cầu, phân loại theo nhóm chức năng, phát hiện nội dung trùng lặp và đề xuất các yêu cầu cần làm rõ. |
| Cảm nhận nhanh |Agent – AI có thể tiếp nhận nhiều tài liệu, thực hiện chuỗi công việc đọc, trích xuất, đối chiếu và tổng hợp. BA vẫn cần kiểm tra và xác nhận kết quả. |

Quy trình nháp hiện tại:

```
[1 Tiếp nhận email, Word, Excel: 10'] → [2 Đọc và phân loại tài liệu: 40'] → [3 Trích xuất yêu cầu nghiệp vụ: 45']

→ [4 Đối chiếu yêu cầu trùng lặp, mâu thuẫn: 40'] ← BOTTLENECK

→ [5 Tổng hợp thành danh sách yêu cầu: 30'] → [6 Gửi các bên xác nhận: 15']

Bottleneck: BA phải đọc nhiều tài liệu từ các nguồn khác nhau, tự tìm kiếm và đối chiếu từng yêu cầu, dễ bỏ sót thông tin hoặc hiểu sai nội dung.

```

### Problem Card #2: Kiểm tra tính nhất quán giữa các tài liệu nghiệp vụ

| Trường | Nội dung |
|---|---|
| Job Story |Khi hoàn thành các tài liệu BRD, SRS, User Stories và Test Cases, tôi muốn kiểm tra tính nhất quán giữa chúng, để phát hiện yêu cầu bị thiếu, sai lệch hoặc mâu thuẫn trước khi chuyển cho đội phát triển và kiểm thử. |
| Actor |Business Analyst (BA), Developer, Tester, Project Manager. |
| Thời điểm / bối cảnh |Sau khi hoàn thành tài liệu nghiệp vụ hoặc trước khi bàn giao yêu cầu cho Developer và Tester. |
| Quy trình hiện tại (3–7 bước) |	1. Thu thập các tài liệu BRD, SRS, User Stories và Test Cases. 2. Đọc và xác định các yêu cầu tương ứng giữa các tài liệu. 3. Đối chiếu nội dung và Business Rules. 4. Kiểm tra các yêu cầu bị thiếu hoặc không thống nhất. 5. Ghi nhận các lỗi và vị trí cần chỉnh sửa. 6. Cập nhật tài liệu và gửi các bên xác nhận. |
| Bottleneck (bước nào, mất bao nhiêu phút) |Bước 2–4: Tìm kiếm và đối chiếu yêu cầu giữa nhiều tài liệu, mất khoảng 120–180 phút cho một bộ tài liệu gồm 30 yêu cầu. |
| Impact (nếu không giải thì sao) |Có thể bỏ sót yêu cầu nghiệp vụ, khiến Developer phát triển sai chức năng, Tester kiểm thử thiếu trường hợp và phát sinh chi phí sửa lỗi sau này. |
| Success metric (baseline → target) |Thời gian kiểm tra: 180 phút → 45 phút. 

 Tỷ lệ phát hiện sai lệch: 70% → 95%. |
| Phương án không dùng AI |Sử dụng Requirement Traceability Matrix (RTM) trên Excel để liên kết và đối chiếu thủ công giữa các tài liệu. |
| Giả thuyết về AI (nếu có) |AI có thể đọc và hiểu nội dung các tài liệu, tự động liên kết các yêu cầu tương ứng, phát hiện nội dung thiếu, trùng lặp hoặc mâu thuẫn và đề xuất vị trí cần chỉnh sửa. |
| Cảm nhận nhanh |Workflow – Có thể xây dựng quy trình tự động gồm đọc tài liệu, trích xuất yêu cầu, đối chiếu và xuất báo cáo sai lệch. AI hỗ trợ phân tích ngữ nghĩa ở từng bước. |

Quy trình nháp hiện tại:

```
[1 Thu thập BRD, SRS, User Stories, Test Cases: 15'] → [2 Đọc và xác định yêu cầu tương ứng: 40'] → [3 Đối chiếu nội dung giữa các tài liệu: 50']

→ [4 Phát hiện yêu cầu thiếu, trùng lặp, mâu thuẫn: 35'] ← BOTTLENECK

→ [5 Ghi nhận vị trí sai lệch: 20'] → [6 Cập nhật và gửi xác nhận: 20']

Bottleneck: BA phải kiểm tra thủ công nhiều tài liệu, tìm các yêu cầu tương ứng và xác định sự khác biệt. Một yêu cầu có thể được mô tả ở nhiều tài liệu với cách diễn đạt khác nhau.

```

### Problem Card #3: Tự động tạo Meeting Minutes và Action Items

| Trường | Nội dung |
|---|---|
| Job Story |Khi tham gia các cuộc họp với khách hàng và đội phát triển, tôi muốn tự động chuyển nội dung cuộc họp thành biên bản và danh sách công việc cần thực hiện, để tiết kiệm thời gian ghi chép và tránh bỏ sót các quyết định quan trọng. |
| Actor |Business Analyst (BA), Project Manager, Developer, Tester, khách hàng. |
| Thời điểm / bối cảnh |Sau các cuộc họp lấy yêu cầu, họp trao đổi nghiệp vụ, họp Sprint Planning hoặc họp cập nhật tiến độ dự án. |
| Quy trình hiện tại (3–7 bước) |1. Tham gia cuộc họp và ghi chép nội dung. 2. Nghe lại bản ghi cuộc họp nếu có. 3. Tổng hợp các nội dung đã thảo luận. 4. Xác định các quyết định được thống nhất. 5. Liệt kê công việc cần thực hiện, người phụ trách và deadline. 6. Soạn biên bản và gửi email cho các bên liên quan. |
| Bottleneck (bước nào, mất bao nhiêu phút) |Bước 2–5: Nghe lại, tổng hợp nội dung và xác định Action Items, mất khoảng 30–45 phút cho mỗi cuộc họp 60 phút. |
| Impact (nếu không giải thì sao) |BA mất thời gian xử lý công việc sau cuộc họp, có thể bỏ sót quyết định, nhầm người phụ trách hoặc deadline, khiến các bên hiểu không thống nhất về công việc cần thực hiện. |
| Success metric (baseline → target) |	Thời gian tạo Meeting Minutes: 45 phút → 10 phút. 

 Tỷ lệ thông tin quan trọng được ghi nhận chính xác: 80% → 95%. |
| Phương án không dùng AI |Sử dụng mẫu Meeting Minutes có sẵn trên Word hoặc Google Docs, kết hợp ghi âm và ghi chép thủ công trong cuộc họp. |
| Giả thuyết về AI (nếu có) |AI có thể chuyển giọng nói thành văn bản, tóm tắt nội dung cuộc họp, phân loại quyết định, trích xuất Action Items và xác định người phụ trách, deadline để tạo biên bản tự động. |
| Cảm nhận nhanh |Workflow – Có thể xây dựng quy trình từ ghi âm, chuyển giọng nói thành văn bản, tóm tắt đến tạo biên bản và danh sách công việc. |

Quy trình nháp hiện tại:

```
[1 Tham gia họp và ghi chép: 5'] → [2 Nghe lại bản ghi cuộc họp: 15'] → [3 Tổng hợp nội dung thảo luận: 10']

→ [4 Xác định quyết định, người phụ trách, deadline: 8'] ← BOTTLENECK

→ [5 Soạn và định dạng Meeting Minutes: 5'] → [6 Gửi email cho các bên liên quan: 2']

Bottleneck: BA phải nghe lại nội dung cuộc họp, xác định các quyết định quan trọng và phân loại công việc cần thực hiện. Việc xác định chính xác người phụ trách và deadline có thể mất nhiều thời gian nếu nội dung trao đổi chưa rõ ràng.
```

### Card muốn pitch nhất

- Card số: 1 – Tổng hợp yêu cầu nghiệp vụ từ nhiều nguồn thông tin.
- Vì sao: Đây là công việc BA thường xuyên phải thực hiện khi tiếp nhận yêu cầu từ nhiều phòng ban thông qua email, Word và Excel. Việc đọc, trích xuất, phân loại và đối chiếu thông tin thủ công mất khoảng 180 phút cho mỗi lần tổng hợp. Tôi nhận thấy AI có thể hỗ trợ tự động hóa phần lớn quy trình này, giúp giảm thời gian xử lý, hạn chế bỏ sót và phát hiện các yêu cầu trùng lặp hoặc mâu thuẫn.
- Câu hỏi muốn nhóm phản biện: Liệu AI có thể đọc hiểu chính xác các yêu cầu nghiệp vụ từ nhiều định dạng tài liệu khác nhau và phát hiện được những yêu cầu trùng lặp hoặc mâu thuẫn hay không? Làm thế nào để đảm bảo kết quả AI tổng hợp không làm sai lệch ý nghĩa ban đầu của yêu cầu?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
|Thời gian 180 phút hiện chỉ là số liệu giả định, chưa có khảo sát thực tế từ BA. |Có |Xác định đây là baseline tạm thời và cần khảo sát BA thực tế để xác nhận. |
|Chưa xác định rõ các định dạng tài liệu đầu vào mà hệ thống có thể xử lý. |Có |Bổ sung phạm vi đầu vào dự kiến gồm PDF, Word, Excel và nội dung email. |
|Chưa có tiêu chí cụ thể để đánh giá kết quả AI trích xuất chính xác hay không. |Có |Bổ sung mục tiêu tỷ lệ trích xuất chính xác từ 80% lên 95%, cần kiểm chứng bằng dữ liệu mẫu đã được BA xác nhận. |
|AI có thể hiểu sai ngữ cảnh hoặc tự gộp những yêu cầu có ý nghĩa nghiệp vụ khác nhau. |Có |Bổ sung cơ chế hiển thị nội dung gốc, nguồn trích xuất và yêu cầu BA xác nhận trước khi đưa vào danh sách chính thức. |
|Chưa đề cập đến vấn đề bảo mật thông tin trong tài liệu nghiệp vụ. |Có |Bổ sung yêu cầu phân quyền truy cập, bảo vệ dữ liệu và không đưa tài liệu nhạy cảm lên các dịch vụ AI chưa được phê duyệt. |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card |Đề xuất 3 vấn đề liên quan đến công việc Business Analyst: (1) Tổng hợp yêu cầu từ nhiều nguồn, (2) Kiểm tra tính nhất quán giữa BRD, SRS và Test Cases, (3) Tự động tạo Meeting Minutes và Action Items. Phân tích Job Story, Actor, Bottleneck và thời gian xử lý của từng vấn đề. |Card #4 (tổng hợp yêu cầu từ nhiều nguồn) được đưa vào shortlist vì có mức độ khó khăn cao, mất khoảng 120–180 phút cho mỗi lần tổng hợp. |
| Phản biện bài của bạn khác |Trong quá trình thảo luận, tôi tham gia xem xét và đánh giá các Problem Card của các thành viên, tập trung vào tính thực tế của vấn đề, đối tượng chịu ảnh hưởng và khả năng kiểm chứng. |Góp phần giúp nhóm so sánh các vấn đề và lựa chọn candidate problem phù hợp. Chưa có ghi chép cụ thể về câu hỏi phản biện do tôi trực tiếp đặt. |
| Nhận phản biện |Tôi nhận phản biện về Problem Statement v0, đặc biệt là việc xác định đối tượng sử dụng còn rộng, metric chưa phản ánh đúng vấn đề tốn kém nhất và cần làm rõ phạm vi can thiệp của AI. |Tôi đã sửa: Thu hẹp đối tượng thành sinh viên sử dụng supervised learning có thời gian huấn luyện từ 15 phút trở lên; thay đổi metric chính sang số vòng huấn luyện lại; bổ sung điểm AI can thiệp, rủi ro và vai trò kiểm tra của con người. |
| Gom cluster / cây OST |Tham gia quá trình thảo luận và phân nhóm các vấn đề do thành viên đề xuất. Đóng góp các vấn đề thuộc nhóm tổng hợp và xử lý tài liệu nghiệp vụ. |Giúp nhóm có thêm góc nhìn về các vấn đề liên quan đến tổng hợp thông tin, kiểm tra theo quy tắc và tìm nguyên nhân bằng phương pháp thử–sai. |
| Chọn candidate problem |Đề xuất card #4 về tổng hợp yêu cầu nghiệp vụ từ nhiều nguồn và đưa vào shortlist. Tham gia đánh giá các candidate dựa trên mức độ khó khăn, tần suất và khả năng giải quyết. |Nhóm cuối cùng lựa chọn vấn đề sinh viên ML/DL phải huấn luyện lại nhiều vòng vì mô hình cho kết quả kém, thay vì kiểm tra nguyên nhân có hệ thống. |
| Kiểm chứng / research |Lập Assumption Map gồm 6 giả định, lựa chọn 2 giả định quan trọng nhưng còn thiếu bằng chứng để ưu tiên kiểm chứng. Soạn kịch bản phỏng vấn và survey theo phương pháp The Mom Test, tập trung hỏi về trải nghiệm thực tế của sinh viên khi huấn luyện mô hình. |Giúp nhóm xác định những giả định cần kiểm chứng trước khi triển khai, tránh lựa chọn bài toán chỉ dựa trên cảm nhận. Số lượng người phỏng vấn và kết quả survey cần bổ sung sau khi hoàn thành kiểm chứng. |
| Quy trình nhóm |Tham gia phân tích quy trình hiện tại và hỗ trợ Nguyễn Khôi Nguyên hoàn thiện Problem Statement. Tập trung xác định bottleneck và những bước có thể cải thiện bằng AI. |Góp phần làm rõ vấn đề cốt lõi của nhóm, giúp phân biệt giữa thời gian tìm nguyên nhân và thời gian thực sự bị mất do huấn luyện lại nhiều lần. |
| Problem Statement |Phụ trách viết Problem Statement v1 dựa trên bản v0. Thu hẹp đối tượng sử dụng, làm rõ bối cảnh supervised learning, thời gian huấn luyện tối thiểu 15 phút và vai trò hỗ trợ của AI. |Hoàn thiện Problem Statement v1 rõ ràng và cụ thể hơn, có đối tượng sử dụng, vấn đề, metric đánh giá, điểm can thiệp AI và giới hạn trách nhiệm của AI. |
| Mức can thiệp AI |Phối hợp làm rõ phạm vi AI hỗ trợ trong bài toán, đặc biệt là việc AI đưa ra gợi ý nguyên nhân dựa trên dữ liệu và bằng chứng, thay vì tự động quyết định hoặc thực hiện huấn luyện lại. |Góp phần định hướng giải pháp theo hướng AI hỗ trợ sinh viên phân tích và ra quyết định, không thay thế vai trò kiểm soát của người sử dụng. |
| Quyết định |Tham gia thảo luận và đánh giá tính khả thi của candidate problem, các giả định và rủi ro khi triển khai. |Nhóm thống nhất quyết định Go, phạm vi nhỏ: thực hiện pilot trong 2 tuần, không xây dựng công cụ mới và thiết lập ngưỡng dừng cụ thể. |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan |Sử dụng AI để gợi ý các khó khăn thường gặp trong công việc Business Analyst, đặc biệt là những công việc lặp lại, tốn thời gian và cần tổng hợp nhiều nguồn thông tin. |AI giúp tôi nhanh chóng tìm ra 10 vấn đề tiềm năng, mở rộng góc nhìn và đưa ra các tình huống có số liệu minh họa. |Một số con số về thời gian và tần suất chỉ mang tính giả định, chưa có bằng chứng thực tế từ BA. |Tôi lựa chọn những vấn đề phù hợp với công việc BA, điều chỉnh cách diễn đạt và xác định các số liệu cần kiểm chứng thực tế. |
| CP2 Problem Card |Sử dụng AI để phân loại vấn đề theo các lăng kính, viết Job Story, xác định Actor, Bottleneck và xây dựng 3 Problem Cards. |AI giúp chuẩn hóa cấu trúc Problem Card, mô tả quy trình hiện tại và đề xuất các chỉ số đánh giá. |AI đưa ra một số metric và mục tiêu cải thiện chưa có cơ sở thực tế; một số giải pháp có xu hướng tập trung vào AI quá sớm. |Tôi lựa chọn 3 vấn đề phù hợp nhất, phân biệt rõ vấn đề nghiệp vụ và giải pháp, đồng thời xem các con số là baseline giả định cần kiểm chứng. |
| CP4 Research |Sử dụng AI để hỗ trợ xây dựng Assumption Map gồm 6 giả định, lựa chọn các giả định quan trọng nhưng còn thiếu bằng chứng và soạn kịch bản phỏng vấn, survey theo The Mom Test. |AI giúp tôi hệ thống hóa các giả định, gợi ý câu hỏi phỏng vấn tập trung vào trải nghiệm thực tế thay vì hỏi về mong muốn trong tương lai. |AI có thể đề xuất câu hỏi mang tính dẫn dắt hoặc khiến người được phỏng vấn trả lời theo kỳ vọng của người hỏi. |Tôi điều chỉnh câu hỏi theo hướng hỏi về trải nghiệm đã xảy ra, ví dụ số lần huấn luyện lại, nguyên nhân và thời gian thực tế. Tôi ưu tiên thu thập bằng chứng thay vì chỉ ghi nhận ý kiến. |
| CP5 Quy trình |Sử dụng AI để hỗ trợ mô tả quy trình hiện tại và quy trình tương lai, xác định Bottleneck và xây dựng bảng so sánh Before/After. |AI giúp tôi trình bày quy trình thành các bước rõ ràng, phân bổ thời gian và xác định những công đoạn có thể cải thiện. |AI có thể phân bổ thời gian theo giả định, chưa phản ánh chính xác quy trình thực tế và đôi khi chưa phân biệt rõ bước thủ công với bước có thể tự động hóa. |Tôi cùng nhóm rà soát lại Bottleneck, tập trung vào việc sinh viên phải đoán nguyên nhân mô hình hoạt động kém và huấn luyện lại nhiều vòng. |
| CP5–6 Problem Statement |Sử dụng AI để hỗ trợ viết, chỉnh sửa Problem Statement v0 và v1, làm rõ Actor, bối cảnh, vấn đề, metric và phạm vi giải pháp. |AI giúp tôi cải thiện cách diễn đạt, cấu trúc nội dung và đề xuất các tiêu chí đánh giá có thể đo lường. |Bản Problem Statement ban đầu còn rộng, chưa xác định rõ đối tượng sử dụng và metric chưa phản ánh đúng phần gây tốn kém nhất. |Tôi thu hẹp Actor thành sinh viên sử dụng supervised learning có thời gian huấn luyện từ 15 phút trở lên; thay đổi metric chính sang số vòng huấn luyện lại và bổ sung vai trò kiểm tra của con người. |
| CP6 Mức can thiệp / quyết định |Sử dụng AI để hỗ trợ phân tích các mức can thiệp No AI, Rule, Workflow, Agent và xem xét khả năng áp dụng AI vào bài toán. |AI giúp tôi có thêm góc nhìn về phạm vi tự động hóa, các rủi ro và cách xây dựng tiêu chí đánh giá đầu ra. |AI có thể đề xuất mức tự động hóa cao hơn nhu cầu thực tế, chưa đánh giá đầy đủ rủi ro khi AI đưa ra nguyên nhân sai hoặc thiếu bằng chứng. |Tôi thống nhất với định hướng AI chỉ hỗ trợ gợi ý nguyên nhân dựa trên bằng chứng, không tự quyết định hoặc tự chạy huấn luyện. Nhóm lựa chọn Go với phạm vi pilot 2 tuần, không xây công cụ mới và có ngưỡng dừng. |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**
Khi nghe các thành viên trong nhóm trình bày Top 3 Problems, tôi nhận ra mỗi người có những khó khăn rất khác nhau trong học tập và công việc. Ban đầu, tôi tập trung vào các vấn đề của Business Analyst như tổng hợp yêu cầu từ nhiều nguồn, kiểm tra tính nhất quán giữa các tài liệu và tạo biên bản cuộc họp. Tuy nhiên, khi nghe các bạn trình bày về mua hàng, bảo hành, xử lý dữ liệu ML/DL và debug firmware, tôi hiểu rằng một vấn đề tốt không nhất thiết phải là vấn đề phức tạp nhất. Điều quan trọng là phải xác định được mức độ ảnh hưởng, tần suất xảy ra và thời gian mà người gặp vấn đề phải bỏ ra để xử lý. Tôi cũng học được rằng không phải vấn đề nào cũng cần sử dụng AI, bởi một số công việc có thể giải quyết bằng các quy tắc hoặc công cụ có sẵn. Điều này giúp tôi thay đổi cách nhìn khi lựa chọn một bài toán để phát triển.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**
Theo tôi, nhóm đã có lúc rơi vào tình trạng solution-first khi thảo luận về bài toán chẩn đoán mô hình ML/DL hoạt động kém. Ban đầu, chúng tôi dễ nghĩ ngay đến việc xây dựng một Agent AI có khả năng tự động tìm nguyên nhân và xử lý lỗi cho sinh viên. Tuy nhiên, khi được phản biện bằng câu hỏi liệu bài toán này thực sự cần Agent hay chỉ cần Rule và Workflow, nhóm bắt đầu xem xét lại. Chúng tôi quay về phân tích quy trình hiện tại của sinh viên, từ kiểm tra dữ liệu, tiền xử lý, đánh giá chỉ số đến quyết định huấn luyện lại mô hình. Qua đó, nhóm nhận ra khó khăn chính không nằm ở việc thiếu một công cụ tự động huấn luyện mà là sinh viên thường phải đoán nguyên nhân khi mô hình cho kết quả kém. Vì vậy, nhóm tập trung vào việc hỗ trợ xác định nguyên nhân có hệ thống thay vì xây dựng một công cụ AI tự động làm tất cả.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**
Có. Một lần cụ thể là khi tôi trình bày Problem Card về tổng hợp yêu cầu nghiệp vụ từ nhiều nguồn thông tin. Tôi cho rằng đây là vấn đề có tiềm năng ứng dụng AI cao vì BA thường phải đọc email, file Word và Excel từ nhiều phòng ban, mất khoảng 120–180 phút cho mỗi lần tổng hợp. Tuy nhiên, sau khi nghe các thành viên trình bày và tham gia quá trình đánh giá candidate, tôi nhận ra rằng vấn đề có mức độ khó khăn cao chưa chắc đã là lựa chọn phù hợp nhất với mục tiêu và phạm vi kiểm chứng của nhóm. Bài toán ML/DL được lựa chọn có phạm vi nghiên cứu cụ thể hơn và có thể xác định các bước kiểm tra, metric cũng như giới hạn can thiệp của AI. Vì vậy, tôi đồng ý với quyết định chung của nhóm và chuyển từ việc tập trung vào bài toán BA sang hỗ trợ hoàn thiện bài toán chẩn đoán mô hình ML/DL.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**
Trong quá trình thực hiện CP4, tôi được giao lập Assumption Map gồm 6 giả định và lựa chọn 2 giả định quan trọng nhưng còn thiếu bằng chứng để ưu tiên kiểm chứng. Đó là số vòng huấn luyện lại mà sinh viên thường phải thực hiện và khả năng nguyên nhân mô hình hoạt động kém xuất phát từ dữ liệu. Tôi đã sử dụng AI hỗ trợ xây dựng kịch bản phỏng vấn và survey theo phương pháp The Mom Test, tập trung vào việc tìm hiểu trải nghiệm thực tế thay vì hỏi người tham gia có muốn sử dụng một công cụ AI hay không. Điều khiến tôi chú ý là việc xác định nguyên nhân mô hình hoạt động kém không đơn giản chỉ dựa vào một chỉ số đánh giá. Cần xem xét nhiều yếu tố như dữ liệu, tiền xử lý và cách đánh giá mô hình. Qua quá trình này, tôi hiểu rằng những giả định ban đầu của nhóm cần được kiểm chứng bằng bằng chứng thực tế trước khi đưa ra quyết định.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**
Điều khó nhất đối với tôi khi viết Problem Statement là xác định đúng đối tượng gặp vấn đề và lựa chọn metric phản ánh chính xác mức độ khó khăn. Ở phiên bản đầu, phạm vi đối tượng còn khá rộng, chưa làm rõ sinh viên đang sử dụng phương pháp học máy nào và trong điều kiện nào thì vấn đề xảy ra. Sau khi nhận phản biện, tôi đã thu hẹp đối tượng thành sinh viên sử dụng supervised learning với thời gian huấn luyện từ 15 phút trở lên. Bên cạnh đó, tôi nhận ra rằng nếu chỉ đo thời gian sinh viên ngồi tìm nguyên nhân thì chưa phản ánh đầy đủ mức độ ảnh hưởng của vấn đề. Vì vậy, nhóm chuyển metric chính sang số vòng huấn luyện lại của mô hình. Tôi cũng phải làm rõ giới hạn của AI, cụ thể AI chỉ hỗ trợ gợi ý nguyên nhân và cung cấp bằng chứng để sinh viên kiểm tra, chứ không tự quyết định hoặc thực hiện huấn luyện lại. Qua đó, tôi hiểu rằng một Problem Statement tốt cần cụ thể, có thể đo lường và xác định rõ phạm vi giải quyết.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**
Nếu được thực hiện lại, tôi sẽ dành nhiều thời gian hơn cho việc kiểm chứng vấn đề ngay từ đầu thay vì chủ yếu dựa vào các số liệu ước lượng. Khi xây dựng kịch bản phỏng vấn, tôi sẽ tập trung hơn vào những câu hỏi về trải nghiệm gần nhất của người học, chẳng hạn như lần gần nhất mô hình cho kết quả kém, họ đã kiểm tra những gì và phải huấn luyện lại bao nhiêu lần. Tôi cũng sẽ chủ động yêu cầu các thành viên cung cấp bằng chứng cụ thể cho những bottleneck được đưa ra, tránh việc lựa chọn vấn đề chỉ dựa trên cảm nhận cá nhân. Ngoài ra, tôi muốn phản biện nhóm mạnh hơn về mức độ cần thiết của AI, đặc biệt là phân biệt những công việc có thể giải quyết bằng Rule với những công việc thực sự cần AI phân tích. Tôi cũng sẽ yêu cầu nhóm xác định tiêu chí đánh giá đầu ra AI sớm hơn để biết giải pháp có thực sự hiệu quả hay không. Điều tôi rút ra là cần hiểu rõ vấn đề trước khi nghĩ đến giải pháp.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.
Bài toán nhóm tôi lựa chọn là hỗ trợ sinh viên làm bài ML/DL chẩn đoán nguyên nhân khi mô hình cho kết quả kém, thay vì phải đoán và huấn luyện lại nhiều lần. Quy trình giải quyết bắt đầu từ việc kiểm tra dữ liệu, tiền xử lý, các chỉ số đánh giá và xác định nguyên nhân trước khi quyết định có cần huấn luyện lại hay không. Metric chính được lựa chọn là số vòng huấn luyện lại, với mục tiêu giảm từ 6 vòng xuống còn 3 vòng. Về boundary, AI chỉ được phép đưa ra gợi ý nguyên nhân kèm bằng chứng để sinh viên kiểm tra, không tự đưa ra quyết định cuối cùng hoặc tự chạy huấn luyện. Nhóm lựa chọn mức can thiệp Workflow vì quy trình có các bước tương đối cố định và có thể kết hợp Rule với AI, chưa cần sử dụng Agent. Cuối cùng, nhóm thống nhất quyết định Go với phạm vi pilot trong 2 tuần, không xây dựng công cụ mới và có các ngưỡng dừng cụ thể. Qua bài tập này, tôi hiểu rằng cần lựa chọn mức ứng dụng AI vừa đủ để giải quyết vấn đề thay vì cố gắng tự động hóa toàn bộ quy trình.

---

## 7. Tài liệu tham khảo

-
