# Báo cáo cá nhân — 2A202603504_NguyenTranTien

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).

## 1. Thông tin học viên

- Họ tên: Nguyễn Trần Tiến
- MSSV: 2A202603504
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm:
- Link repository:

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Tốn thời gian | Khi cài môi trường lập trình mới, tôi muốn các thư viện tương thích và chạy được ngay lần đầu, để không tốn thời gian sửa lỗi xung đột. | Bản thân tôi, team | Cài môi trường ~3–4 lần/tháng; lần gần nhất cài môi trường PyTorch + CUDA cho bài tập mới mất hơn 2 giờ sửa lỗi phiên bản (thực tế ghi nhận). |
| 2 | Cần đọc, tổng hợp nhiều thông tin | Khi đọc bài báo nghiên cứu, tôi muốn nắm ngay các ý chính và kiến trúc mô hình, để không mất nhiều giờ đọc tài liệu dài. | Bản thân tôi, team, thầy hướng dẫn | Đọc ~2–4 bài/tháng; lần gần nhất đọc paper Attention Is All You Need mất khoảng 1.5 giờ để hiểu kiến trúc Transformer (thực tế ghi nhận). |
| 3 | Cần đọc, tổng hợp nhiều thông tin | Khi lựa chọn mô hình lập trình cho dự án, tôi muốn biết ngay mô hình nào tối ưu nhất về chi phí và tài nguyên, để không phải truy cập kiểm tra rời rạc trên từng trang web. | Bản thân tôi | Chọn mô hình ~2–3 lần/tháng; đợt làm đồ án tốt nghiệp về hệ thống báo cháy tích hợp cảnh báo thông minh tốn gần 3 giờ tìm và đối chiếu thông số (thực tế ghi nhận). |
| 4 | Pain từ người khác | Khi hướng dẫn thành viên mới định dạng tệp dữ liệu, tôi muốn tệp dữ liệu của các bạn tự động đúng chuẩn ngay từ đầu, để không phải mất nhiều giờ ngồi kiểm tra và chỉ ra từng dòng lỗi thủ công. | Bản thân tôi, team, thầy hướng dẫn | Hỗ trợ 1–2 lần/tháng; tuần trước mất hơn 1.5 giờ ngồi dò lỗi định dạng JSONL cho 1 thành viên mới trong nhóm (thực tế ghi nhận qua tin nhắn nhóm lab). |
| 5 | Lặp lại | Khi tiến hành lập trình phần cứng cho hệ thống đồ án tốt nghiệp, tôi muốn đọc nhiều lần datasheet, sau đó debug code firmware và phải sửa lại nhiều lần để hệ thống kiểm thử phần cứng đạt hiệu suất tốt nhất và không đo sai thông số. | Bản thân tôi, team, thầy hướng dẫn | Xử lý dữ liệu và debug 3–4 lần/tuần; dự án đồ án tốt nghiệp mất khoảng 10–12h/tuần trong vòng 2 tháng để có thể debug xong và kiểm thử hệ thống. |
| 6 | Cần đọc, tổng hợp nhiều thông tin | Khi lập trình xong phần cứng firmware, tôi muốn đẩy thông tin lên cloud để có thể lấy dữ liệu từ cloud xử lý các bước tiếp theo. | Bản thân tôi, team, thầy hướng dẫn | Tôi mất 2–3 tuần đẩy thông tin cảm biến lên cloud, trong đồ án để phục vụ việc lấy dữ liệu để training hệ thống thông minh thực hiện cảnh báo tôi mất 2–3h/ngày trong hơn 2 tuần để đẩy dữ liệu lên cloud để thực hiện cảnh báo qua web. |
| 7 | | | | |
| 8 | | | | |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

| Ý AI gợi ý | Quyết định | Lý do |
|---|---|---|
| Tóm tắt nhanh kiến trúc paper nghiên cứu | Giữ lại (Dòng 2) | Đọc paper tốn thời gian thực tế (khoảng 1.5 giờ/bài, 2–4 bài/tháng theo dòng 2), phù hợp với nhu cầu học tập thường xuyên. |
| Các vấn đề hạ tầng server | Bỏ | Quá tầm cá nhân (theo mục 5). |

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Card 5: Debug firmware phần cứng | Actor rõ, số liệu thời gian thực tế rất lớn (10–12h/tuần), bottleneck tại bước sửa code firmware và dò lỗi ngoại vi (Bước 6) rõ ràng, vừa sức trong một buổi lab đồ án. | Chưa chắc việc dùng agent hay rule-based sẽ giải quyết được triệt để lỗi ngoại vi phần cứng do yếu tố nhiễu tín hiệu thực tế. |
| 2 | Card 6: Đẩy dữ liệu lên Cloud và Web | Thời gian lãng phí lớn (2–3h/ngày trong hơn 2 tuần), quy trình thao tác nhiều bước lặp đi lặp lại khi cấu hình JSON payload. | Chưa chắc chắn về độ ổn định của đường truyền mạng và cơ chế đồng bộ gói tin khi test thực tế. |
| 3 | Card 4: Hỗ trợ người mới định dạng dữ liệu | Phản ánh chính xác pain point từ người khác, có bằng chứng tin nhắn lab rõ ràng, dễ chuẩn hóa thành quy trình kiểm tra tự động. | Chưa rõ mức độ tự giác của thành viên mới trong việc chạy công cụ kiểm tra trước khi nhờ hỗ trợ. |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi tiến hành lập trình phần cứng cho hệ thống đồ án tốt nghiệp, tôi muốn tra cứu và đồng bộ thông số datasheet với code firmware, để hệ thống kiểm thử đạt hiệu suất tốt nhất và không bị lỗi đọc sai thông số. |
| Actor | Bản thân tôi |
| Thời điểm / bối cảnh | Trong giai đoạn kiểm thử phần cứng và nạp code firmware cho mạch vi điều khiển (STM32/ESP32) tại phòng lab đồ án. |
| Quy trình hiện tại (3–7 bước) | 1. Mở datasheet đọc cấu hình thanh ghi ngoại vi (15 phút).<br>2. Viết mã nguồn khởi tạo (Init code) thủ công trong IDE (30 phút).<br>3. Biên dịch và nạp code xuống mạch phần cứng (10 phút).<br>4. Đo đạc tín hiệu thực tế bằng thiết bị đo/oscilloscope (25 phút).<br>5. So sánh thông số thực tế với tài liệu kỹ thuật (20 phút).<br>6. Sửa lại code firmware khi phát hiện lệch thông số (90 phút — Bottleneck, con số ước lượng).<br>7. Lặp lại toàn bộ quá trình kiểm tra (20 phút).<br>(Tổng thời gian cho 1 chu trình xử lý lỗi: ~210 phút / lần, ước lượng; theo CP1, tần suất 3–4 lần/tuần và tổng cộng tiêu tốn ~10–12 giờ/tuần, tức trung bình khoảng 150–240 phút/lần, nên 210 phút nằm trong khoảng này). |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 6: Sửa lại code firmware và dò lỗi ngoại vi — mất khoảng 90 phút cho mỗi lần phát hiện lệch thông số (ước lượng dựa trên nhật ký ghi nhớ cá nhân trong đợt làm đồ án; 90 phút bao gồm cả thời gian tra lại tài liệu datasheet khi phát hiện lệch thông số). |
| Impact (nếu không giải thì sao) | Tiêu tốn khoảng 10–12 giờ mỗi tuần, kéo dài khoảng 2 tháng (theo CP1), làm chậm tiến độ hoàn thành đồ án tốt nghiệp và gây áp lực lớn khi test phần cứng. |
| Success metric (baseline → target) | Giảm thời gian tổng từ 10–12 giờ/tuần xuống dưới 4 giờ/tuần; đo bằng cách tự ghi lại nhật ký số giờ bấm giờ thực tế trên bảng tracking cá nhân mỗi tuần. |
| Phương án không dùng AI | In sẵn tài liệu datasheet ra giấy để tra cứu trực tiếp và dùng bộ template code mẫu có sẵn trên GitHub. |
| Giả thuyết về AI (nếu có) | Sử dụng Agent AI có khả năng phân tích log lỗi từ thiết bị đo (do người đo ở Bước 4 cung cấp), đối chiếu trực tiếp với đoạn mã cấu hình ngoại vi ở bước 6 để tự động đề xuất và vá lỗi dòng code sai, thay vì chỉ sinh mã khởi tạo ban đầu. Phạm vi Agent chỉ tập trung vào khâu phân tích log lỗi phần mềm và đối chiếu cú pháp thanh ghi với datasheet ở Bước 6; không thay thế thao tác đo đạc vật lý ở Bước 4 (cắm dây đo, oscilloscope). |
| Cảm nhận nhanh | Agent (Lý do chọn Agent thay vì Workflow: Quá trình dò lỗi ở bước 6 là một vòng lặp ra quyết định nhiều bước — AI cần đọc log lỗi và kết quả đo thực tế do người cung cấp, phân tích nguyên nhân lệch thông số, đề xuất sửa code; người nạp mạch và đo lại (Bước 3–4, thao tác vật lý) rồi đưa kết quả mới cho AI, lặp lại cho đến khi đạt thông số chuẩn, vượt quá khả năng tuyến tính của Workflow thông thường). |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — ~210 phút / lần xử lý lỗi, 3–4 lần/tuần

[1 Đọc datasheet, cấu hình thanh ghi: 15'] → [2 Viết Init code thủ công: 30']
→ [3 Biên dịch + nạp code xuống mạch: 10'] → [4 Đo tín hiệu bằng oscilloscope: 25']
→ [5 So sánh thông số thực tế với tài liệu: 20']
→ [6 Sửa lại code firmware: 90'] ← BOTTLENECK
→ [7 Lặp lại kiểm tra: 20']
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi lập trình xong phần cứng firmware, tôi muốn truyền tải dữ liệu cảm biến lên đám mây trực tuyến, để có thể lấy dữ liệu phục vụ việc huấn luyện hệ thống thông minh cảnh báo qua giao diện web. |
| Actor | Bản thân tôi (Sinh viên làm đồ án tốt nghiệp) |
| Thời điểm / bối cảnh | Giai đoạn tích hợp hệ thống IoT lên Cloud (HiveMQ/MQTT Broker) để xử lý dữ liệu cho dashboard web tại phòng lab; diễn ra sau khi đã lập trình xong phần cứng firmware (nối tiếp sau Card #1) và kéo dài hơn 2 tuần (theo CP1). |
| Quy trình hiện tại (3–7 bước) | 1. Cấu hình giao thức truyền thông mạng trên firmware (20 phút).<br>2. Thiết lập định dạng gói tin JSON payload truyền tải dữ liệu (30 phút).<br>3. Kết nối và cấu hình API endpoint trên Cloud (30 phút).<br>4. Gửi dữ liệu thử nghiệm từ vi điều khiển lên Cloud (20 phút).<br>5. Kiểm tra log dữ liệu trên giao diện đám mây (30 phút).<br>6. Xử lý sự cố mất gói tin và kiểm tra độ ổn định của đường truyền mạng khi đồng bộ gói tin test thực tế (120 phút — Bottleneck, con số ước lượng).<br>7. Đổ dữ liệu vào cơ sở dữ liệu để phục vụ huấn luyện hệ thống và hiển thị cảnh báo trên web (30 phút).<br>(Tổng thời gian cho một phiên đầy đủ 7 bước: ~280 phút, ước lượng. Theo CP1, tổng thời gian đẩy dữ liệu lên Cloud là 2–3 giờ/ngày trong hơn 2 tuần, nên không phải ngày nào cũng chạy trọn cả 7 bước). |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 6: Xử lý sự cố mất gói tin và kiểm tra độ ổn định của đường truyền mạng khi đồng bộ gói tin test thực tế — mất khoảng 120 phút cho mỗi phiên lỗi (ước lượng; nằm trong tổng 2–3 giờ/ngày đẩy dữ liệu lên Cloud theo CP1). |
| Impact (nếu không giải thì sao) | Tiêu tốn khoảng 2–3 giờ/ngày trong hơn 2 tuần (theo CP1), tức khoảng 20–40 giờ, làm chậm trễ nghiêm trọng tiến độ hoàn thành giao diện web cảnh báo của đồ án. |
| Success metric (baseline → target) | Giảm tổng thời gian đẩy dữ liệu lên Cloud từ 2–3 giờ/ngày (baseline theo CP1) xuống dưới 30 phút/ngày; đo lường bằng bảng tracking thời gian cá nhân. |
| Phương án không dùng AI | Sử dụng các thư viện mẫu có sẵn trên GitHub, tra cứu tài liệu MQTT protocol và debug thủ công từng dòng log kết nối mạng trên terminal. |
| Giả thuyết về AI (nếu có) | Sử dụng mức độ Workflow (kết hợp Rule kiểm tra schema JSON payload và tự động phân tích mã lỗi mạng cơ bản). Phản biện CP6: Tại sao không dùng thuần Rule? Vì Rule chỉ bắt được lỗi cấu trúc tĩnh, trong khi bottleneck ở bước 6 liên quan đến độ ổn định đường truyền bất định và đồng bộ gói tin thực tế — cần Workflow để chạy các kịch bản kiểm tra kết nối tuần tự tự động. |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — ~280 phút / phiên đầy đủ (ước lượng); tổng đẩy dữ liệu lên Cloud 2–3 giờ/ngày trong hơn 2 tuần (CP1)

[1 Cấu hình giao thức mạng trên firmware: 20'] → [2 Thiết lập định dạng gói tin JSON: 30']
→ [3 Kết nối + cấu hình API endpoint Cloud: 30'] → [4 Gửi dữ liệu thử lên Cloud: 20']
→ [5 Kiểm tra log trên giao diện Cloud: 30']
→ [6 Xử lý mất gói tin + kiểm tra độ ổn định mạng: 120'] ← BOTTLENECK
→ [7 Đổ dữ liệu vào CSDL cho huấn luyện + web cảnh báo: 30']
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi hướng dẫn thành viên mới định dạng tệp dữ liệu, tôi muốn tệp dữ liệu của các bạn tự động đúng chuẩn ngay từ đầu, để không phải mất nhiều giờ ngồi kiểm tra và chỉ ra từng dòng lỗi thủ công. |
| Actor | Bản thân tôi (Người hướng dẫn thành viên mới trong lớp lab) |
| Thời điểm / bối cảnh | Khi tiếp nhận bộ dữ liệu định dạng JSONL từ các thành viên mới tham gia vào các đợt làm đồ án tập trung tại phòng lab đại học. |
| Quy trình hiện tại (3–7 bước) | 1. Nhận tệp dữ liệu từ thành viên mới qua nhóm chat Zalo/Messenger lab (5 phút).<br>2. Tải tệp xuống môi trường lập trình cá nhân (5 phút).<br>3. Chạy thử nghiệm chương trình đọc dữ liệu (10 phút).<br>4. Nhận thông báo lỗi cú pháp chung từ màn hình dòng lệnh CLI, chưa chỉ rõ toàn bộ vị trí dòng sai (10 phút).<br>5. Mở tệp kiểm tra thủ công từng dòng để tìm vị trí sai (45 phút — Bottleneck, con số ước lượng).<br>6. Khoanh vùng và chỉ ra chính xác vị trí dòng bị sai định dạng dựa trên tin nhắn lab (15 phút).<br>7. Gửi lại hướng dẫn sửa lỗi và chờ thành viên phản hồi (20 phút).<br>(Tổng thời gian: ~110 phút/đợt nhận file, khớp CP1 "tuần trước mất hơn 1.5 giờ" cho 1 thành viên mới; tần suất 1–2 lần/tháng). |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 5: Mở tệp kiểm tra thủ công từng dòng để tìm vị trí sai — mất khoảng 45 phút (ước lượng) trong tổng ~110 phút cho mỗi đợt nhận file; có bằng chứng tin nhắn lab từ các thành viên mới gặp lỗi cấu trúc (theo CP1). |
| Impact (nếu không giải thì sao) | Lãng phí thời gian cá nhân của người hướng dẫn, gây gián đoạn tiến độ chung của toàn nhóm lab, đồng thời chưa rõ mức độ tự giác của thành viên mới trong việc chủ động chạy công cụ kiểm tra trước khi nhờ hỗ trợ. |
| Success metric (baseline → target) | Giảm thời gian người hướng dẫn bỏ ra để kiểm tra và chỉ ra lỗi cho mỗi đợt nhận file từ hơn 1.5 giờ (baseline theo CP1; ~110 phút cả đợt) xuống dưới 5 phút; đo lường bằng cách tự bấm giờ thời gian xử lý mỗi đợt. |
| Phương án không dùng AI | Viết một đoạn script Python ngắn dùng thư viện json để bắt ngoại lệ (try-except) và in ra số dòng lỗi thô trên màn hình console. |
| Giả thuyết về AI (nếu có) | Sử dụng mức độ Rule kết hợp quy trình kiểm tra tự động để khi thành viên tải file lên cổng chung, hệ thống tự động quét cú pháp, chỉ rõ dòng lỗi và ép buộc các bạn tự fix trước khi gửi nhờ hỗ trợ. |
| Cảm nhận nhanh | Rule |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — ~110 phút / đợt nhận file, 1–2 lần/tháng

[1 Nhận tệp qua nhóm chat lab: 5'] → [2 Tải tệp xuống môi trường cá nhân: 5']
→ [3 Chạy thử chương trình đọc dữ liệu: 10'] → [4 Nhận thông báo lỗi chung từ CLI (chưa chỉ rõ dòng): 10']
→ [5 Mở tệp dò từng dòng để tìm chỗ sai: 45'] ← BOTTLENECK
→ [6 Khoanh vùng, chỉ ra dòng sai định dạng: 15']
→ [7 Gửi hướng dẫn sửa lỗi, chờ phản hồi: 20']
```

### Card muốn pitch nhất

- Card số: Card #1 (Tra cứu datasheet và sửa lỗi firmware phần cứng)
- Vì sao: Đây là vấn đề cốt lõi gắn liền trực tiếp với chuyên ngành Kỹ thuật Điều khiển & Tự động hóa của tôi. Tổng thời gian lãng phí lớn nhất trong cả đồ án (10–12h/tuần, kéo dài khoảng 2 tháng theo CP1) và bottleneck ở bước sửa code/dò lỗi được thể hiện rõ ràng, cụ thể qua quá trình thực nghiệm tại phòng lab.
- Câu hỏi muốn nhóm phản biện: "Liệu việc ứng dụng Agent AI có thực sự giúp tự động hóa khâu dò lỗi phần cứng ngoại vi vốn phụ thuộc nhiều vào tính chất vật lý của linh kiện hay không, hay chúng ta chỉ nên dùng quy trình Rule-based để kiểm tra cú pháp cấu hình thanh ghi sẽ tối ưu hơn?"

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| AI (PM hoài nghi) chỉ ra rằng bước đo đạc tín hiệu bằng oscilloscope thuộc về thao tác vật lý bên ngoài, AI không thể cắm dây đo hay can thiệp trực tiếp vào phần cứng để phát hiện nhiễu thực tế. | Đồng ý một phần | Đã sửa: Khoanh vùng phạm vi của Agent AI chỉ tập trung vào khâu phân tích log lỗi phần mềm, đối chiếu cú pháp thanh ghi với datasheet ở Bước 6 để vá code firmware, loại bỏ ảo tưởng AI có thể thay thế thao tác đo đạc vật lý ở Bước 4. |
| AI cho rằng 90 phút cho một lần sửa lỗi là quá cao và nghi ngờ tính thực tế của con số. | Không đồng ý | Đã sửa (bổ sung giải trình): Giữ nguyên số phút nhưng thêm chú thích "ước lượng dựa trên nhật ký ghi nhớ cá nhân trong đợt làm đồ án" để làm rõ nguồn gốc con số, giải thích rõ 90 phút bao gồm cả thời gian tra lại tài liệu datasheet khi phát hiện lệch thông số. |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Pitch 3 card từ đồ án tốt nghiệp (#10 debug firmware, #11 đẩy dữ liệu cảm biến lên Cloud, #12 kiểm tra định dạng JSONL) | Card #10 vào shortlist; #10, #11 cùng cluster C với card của Nguyên |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: [ĐIỀN: câu hỏi thật, hỏi ai, về card nào] | [ĐIỀN] |
| Nhận phản biện | Câu hỏi tôi nhận được từ Nguyên: "Lỗi ở Card #10 phụ thuộc vào đo đạc vật lý (oscilloscope), AI làm sao tự phát hiện nhiễu tín hiệu thực tế trên vi điều khiển?" | Tôi đã sửa: Thu hẹp phạm vi của AI chỉ tập trung vào khâu phân tích log phần mềm và đối chiếu cú pháp thanh ghi với datasheet ở Bước 6, loại bỏ ảo tưởng AI can thiệp vào khâu đo đạc vật lý. |
| Gom cluster / cây OST | Đưa câu hỏi "Agent hay Rule là đủ?" vào thảo luận | Nhóm gạch "Agent AI tự dò lỗi phần cứng" khỏi cây OST vì là solution đội lốt opportunity |
| Chọn candidate problem | Đồng ý loại #10 của mình vì lỗi phụ thuộc phần cứng vật lý, khó kiểm trong buổi lab; nêu #12 là ví dụ "chỉ cần Rule". | Lý do loại #10, #12 được làm rõ và ghi vào mục 2.4 của bài báo cáo nhóm. |
| Kiểm chứng / research | Hỗ trợ Nguyễn Ngọc Sang phần research (theo TEAM.md): Tự mở kiểm tra link tài liệu cấu trúc JSONL, tìm thêm tài liệu về thư viện Pydantic và Deepchecks để xác minh khả năng kiểm thử dữ liệu tĩnh. | Bảng research mục 3.3 (Deepchecks, Cleanlab, bài của Karpathy): nhóm kết luận phần kiểm tra dữ liệu làm được bằng Rule, AI chỉ cần ở bước xếp hạng nguyên nhân. |
| Quy trình nhóm | Hỗ trợ Nguyên kiểm từng bước quy trình tương lai | Quy trình tương lai (mục 4.2) tách rõ bước Rule, AI, con người, có boundary và phương án quay về checklist; before/after ~190' → ~112' |
| Problem Statement | Phản biện v0: metric bỏ qua các vòng huấn luyện lại; boundary chưa nói AI có được tự chạy huấn luyện không | Nhóm đổi metric và mở rộng boundary ở v1 |
| Mức can thiệp AI | Đặt bài vào ma trận, so sánh 4 mức, lập luận chọn Workflow chứ không lên Agent; điền AI Canvas, 2 câu hỏi PAIR | Mục 6 báo cáo nhóm |
| Quyết định | Chạy và chấm bộ eval 10 ca: đạt 8/10 (80% ca test đạt kết quả phân tích chính xác và đưa ra gợi ý chuẩn). | Kết quả eval quyết định có bắt đầu pilot không. |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Gợi ý và mở rộng danh sách các tình huống/vấn đề (problem candidate) theo 4 lăng kính. | Mở rộng góc nhìn về các vấn đề tốn thời gian trong học tập (như tóm tắt paper). | Đưa ra các ý quá chung chung, nhầm lẫn việc nêu công cụ/giải pháp vào cột Job Story (như viết script, dùng tool) và gợi ý các vấn đề hạ tầng server quá tầm cá nhân. | Loại bỏ tên công cụ/giải pháp ra khỏi Job Story, đưa câu về đúng form "Khi... tôi muốn... để...", điều chỉnh số liệu và bổ sung dấu hiệu thật/bằng chứng thực tế từ lớp lab và bài tập dự án. |
| CP2 Problem Card | Đóng vai "PM hoài nghi" để phản biện tính khả thi, logic thời gian và giả thuyết công nghệ của các Problem Cards. | Chỉ ra điểm vô lý khi kỳ vọng AI can thiệp vào các bước vật lý (đo oscilloscope phần cứng) và nhắc nhở việc chuẩn hóa phân loại mức độ AI (Rule / Workflow / Agent). | AI hoài nghi số phút thực tế quá mức (90 phút cho một lần sửa lỗi). | Thu hẹp phạm vi can thiệp của AI vào đúng bước xử lý phần mềm/log, bổ sung chú thích nguồn gốc con số "ước lượng", và điều chỉnh phương án AI bám sát đúng bước nghẽn. |
| CP4 Research | Tìm kiếm các thư viện mã nguồn mở, tài liệu giao thức MQTT/JSON schema và các công cụ hỗ trợ phân tích log tự động cho vi điều khiển STM32/ESP32. | Gợi ý nhanh danh sách các thư viện Python/C++ và các bài viết kỹ thuật liên quan đến xử lý ngoại vi và đồng bộ cloud. | Đưa ra một số liên kết tài liệu không chính xác hoặc giới thiệu các công cụ vượt quá khả năng tương thích của phần cứng hiện tại. | Tự kiểm tra lại tính năng của từng thư viện qua documentation chính thức, loại bỏ các công cụ không phù hợp và chỉ giữ lại các mã nguồn thực tế có thể tích hợp vào đồ án. |
| CP5 Quy trình | Nhờ AI cấu trúc lại mô tả tuần tự các bước xử lý lỗi và gợi ý cách vẽ sơ đồ quy trình chi tiết cho 3 Problem Cards. | Sắp xếp các bước thao tác tại phòng lab thành một chuỗi logic rõ ràng, rành mạch từng công đoạn. | AI có xu hướng gộp chung các bước tra cứu datasheet thủ công với bước viết code khởi tạo làm mờ nhạt điểm nghẽn thực tế. | Tự tách rời các bước, xác định lại chính xác thời gian (số phút) cho từng hành động nhỏ và đánh dấu đúng bước Bottleneck theo nhật ký thực tế. |
| CP5–6 Problem Statement | Nhờ AI đọc và chỉ ra các điểm yếu, lỗ hổng logic hoặc tính chưa chặt chẽ trong các tuyên bố vấn đề (Problem Statement) của giao diện nguyên mẫu (v0/prototype). | Phát hiện nhanh các câu chữ diễn đạt còn lan man hoặc thiếu tập trung vào đối tượng sử dụng chính (actor). | AI thường đưa ra các câu sửa mẫu mang tính chung chung, bóng bảy hoặc tự ý viết lại toàn bộ cấu trúc thay vì chỉ đúng điểm hổng cần khắc phục. | Giữ lại cấu trúc cốt lõi mang đặc thù kỹ thuật phần cứng của bản thân, chỉ chỉnh sửa lại phần câu chữ cho sắc bén và bám sát vào Job Story đã định hình. |
| CP6 Mức can thiệp / quyết định | Nhờ AI so sánh ranh giới giữa 4 mức độ can thiệp (No AI, Rule, Workflow, Agent) đối với 3 bài toán phần cứng và cloud. | Phân tích rõ các đặc điểm kỹ thuật để cân nhắc khi nào nên dùng Rule tĩnh, khi nào cần Workflow tuyến tính hay vòng lặp Agent. | AI có xu hướng mặc định đề xuất mức Agent cho mọi bài toán để tỏ ra thông minh, đồng thời đưa ra các nhận xét đánh giá (eval) khá chung chung (ví dụ chỉ nói "hệ thống có thể gặp lỗi kết nối" mà không dẫn số liệu cụ thể). | Tự hạ mức độ can thiệp của AI xuống mức Rule/Workflow đối với các bài toán kiểm tra cú pháp JSON hoặc xử lý luồng tuần tự, giữ nguyên nhận định thực tế dựa trên năng lực hệ thống phần cứng. |

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
