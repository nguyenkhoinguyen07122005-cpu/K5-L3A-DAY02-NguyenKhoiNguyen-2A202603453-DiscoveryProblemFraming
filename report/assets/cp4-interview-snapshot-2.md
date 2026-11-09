# CP4 — Interview snapshot 2


| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) |Sinh viên năm 4 ngành Khoa học dữ liệu, từng thực hiện dự án Deep Learning |
| Thời điểm, kênh (trực tiếp / online) |09/11/2026, phỏng vấn online |
| Người phỏng vấn |Nguyễn Ngọc Sang |
| Câu nói đáng nhớ nhất (nguyên văn) |“Sửa được một lỗi đôi khi lại phát sinh lỗi khác, nhất là khi thay đổi phần xử lý dữ liệu hoặc cấu hình model.”|
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? |Khi thay đổi bước chuẩn hóa dữ liệu để cải thiện kết quả mô hình, một số lần chạy sau cho kết quả không ổn định |
| Hiện đang xử lý bằng cách nào (workaround)? |So sánh code cũ và mới, kiểm tra log, chạy lại notebook và kiểm tra kết quả từng bước |
| Mất bao lâu, bao nhiêu lần huấn luyện lại? |khoảng 1–3 giờ, chạy lại 2–4 lần |
| Lần đầu sửa cái gì? Nguyên nhân thật cuối cùng là gì? |Ban đầu sửa phần model configuration. Nguyên nhân cuối cùng là thay đổi preprocessing làm dữ liệu đầu vào không còn tương thích với pipeline trước đó |
| Tín hiệu xác nhận |Thay đổi ở một bước có thể ảnh hưởng đến những bước phía sau; cần kiểm thử lại sau mỗi lần sửa |
| Tín hiệu phản bác |Unit test, version control và lưu cấu hình thí nghiệm có thể hạn chế đáng kể lỗi phát sinh |
| Insight / opportunity rút ra |Xây dựng quy trình kiểm tra regression, so sánh kết quả trước và sau thay đổi; AI có thể gợi ý những thành phần cần kiểm thử dựa trên phần code được sửa|

