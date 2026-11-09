# CP4 — Interview snapshot 1


| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) |Sinh viên năm 3 ngành Công nghệ thông tin, có kinh nghiệm làm bài tập Machine Learning |
| Thời điểm, kênh (trực tiếp / online) | 09/11/2026, phỏng vấn online|
| Người phỏng vấn |Nguyễn Khôi Nguyên |
| Câu nói đáng nhớ nhất (nguyên văn) |“Có những lúc model chạy được nhưng kết quả lại không như mong đợi, mình phải kiểm tra từng bước mới biết lỗi nằm ở đâu.” |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Khi huấn luyện mô hình phân loại, kết quả đánh giá thấp hơn kỳ vọng dù chương trình không báo lỗi|
| Hiện đang xử lý bằng cách nào (workaround)? | Kiểm tra dữ liệu đầu vào, nhãn, preprocessing, tham số mô hình và thử chạy lại với cấu hình khác|
| Mất bao lâu, bao nhiêu lần huấn luyện lại? |khoảng 1–2 giờ, chạy lại mô hình 3–5 lần |
| Lần đầu sửa cái gì? Nguyên nhân thật cuối cùng là gì? |Ban đầu kiểm tra learning rate và số epoch. Nguyên nhân là preprocessing dữ liệu chưa nhất quán giữa tập train và validation |
| Tín hiệu xác nhận |Phải kiểm tra nhiều thành phần trước khi xác định nguyên nhân; quá trình debug tốn thời gian|
| Tín hiệu phản bác |Nếu có logging, baseline và pipeline kiểm tra tốt, một số lỗi có thể được phát hiện nhanh mà không cần AI |
| Insight / opportunity rút ra |Có thể hỗ trợ người dùng kiểm tra tuần tự dữ liệu, preprocessing, cấu hình và metric để thu hẹp phạm vi nguyên nhân |

