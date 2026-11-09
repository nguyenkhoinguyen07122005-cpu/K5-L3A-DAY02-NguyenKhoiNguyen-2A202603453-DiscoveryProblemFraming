# CP4 — Interview snapshot 2


| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) |Sinh viên năm 4 ngành Công nghệ thông tin, có kinh nghiệm làm dự án Python theo nhóm|
| Thời điểm, kênh (trực tiếp / online) |09/11/2026, phỏng vấn online |
| Người phỏng vấn |Nguyễn Trần Tiến|
| Câu nói đáng nhớ nhất (nguyên văn) |“Mỗi lần sửa code xong mình vẫn phải chạy lại những phần trước đó, vì đôi khi lỗi mới lại xuất hiện ở chỗ khác.”|
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? |Khi thay đổi một hàm xử lý dữ liệu, kết quả đầu ra của một số hàm phía sau không còn đúng như trước|
| Hiện đang xử lý bằng cách nào (workaround)? |Chạy lại notebook từ đầu, so sánh output trước và sau khi sửa, kiểm tra Git diff và sửa từng lỗi phát sinh|
| Mất bao lâu, bao nhiêu lần huấn luyện lại? |khoảng 1–2 giờ để kiểm tra và sửa lỗi; chạy lại chương trình hoặc mô hình khoảng 2–3 lần|
| Lần đầu sửa cái gì? Nguyên nhân thật cuối cùng là gì? |Ban đầu sửa hàm xử lý dữ liệu. Nguyên nhân là thay đổi kiểu dữ liệu đầu ra khiến một thành phần phía sau không xử lý đúng|
| Tín hiệu xác nhận |Một thay đổi nhỏ có thể ảnh hưởng đến nhiều thành phần khác; kiểm thử hồi quy giúp phát hiện lỗi sớm|
| Tín hiệu phản bác |Nếu dự án có unit test và integration test đầy đủ, việc phát hiện lỗi phát sinh có thể không mất quá nhiều thời gian|
| Insight / opportunity rút ra |Có thể hỗ trợ xác định các thành phần bị ảnh hưởng bởi thay đổi code và đề xuất test case cần chạy lại|

