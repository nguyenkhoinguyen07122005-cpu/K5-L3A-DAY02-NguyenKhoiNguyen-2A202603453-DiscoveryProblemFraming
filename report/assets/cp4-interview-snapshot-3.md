# CP4 — Interview snapshot 2


| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) |Sinh viên năm 3 ngành Trí tuệ nhân tạo, thường xuyên xử lý dataset bằng Python |
| Thời điểm, kênh (trực tiếp / online) |09/11/2026, phỏng vấn online |
| Người phỏng vấn |Đào Thị Thu Phương|
| Câu nói đáng nhớ nhất (nguyên văn) |“Có những dataset không quá lớn nhưng xử lý vẫn rất chậm, nhiều khi phải thử tối ưu từng đoạn code.”|
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? |Khi tiền xử lý dữ liệu cho bài toán Machine Learning, các bước đọc file, làm sạch và biến đổi dữ liệu mất nhiều thời gian |
| Hiện đang xử lý bằng cách nào (workaround)? |Đo thời gian từng đoạn code, thử vectorization bằng Pandas/NumPy và loại bỏ các vòng lặp không cần thiết |
| Mất bao lâu, bao nhiêu lần huấn luyện lại? |khoảng 30–60 phút để tìm và tối ưu đoạn code; huấn luyện lại 1–2 lần để kiểm tra kết quả|
| Lần đầu sửa cái gì? Nguyên nhân thật cuối cùng là gì? |Ban đầu thử giảm số vòng lặp. Nguyên nhân chính là xử lý dữ liệu bằng các thao tác lặp trên từng dòng thay vì vectorization|
| Tín hiệu xác nhận |Thời gian xử lý dữ liệu có thể ảnh hưởng đáng kể đến toàn bộ thời gian thử nghiệm mô hình|
| Tín hiệu phản bác |Nếu dataset nhỏ hoặc pipeline đã được tối ưu, vấn đề hiệu năng có thể không đủ nghiêm trọng để cần một công cụ hỗ trợ riêng|
| Insight / opportunity rút ra |Có thể xây dựng công cụ phân tích profiling, xác định bước xử lý chậm và đề xuất phương án tối ưu có thể kiểm chứng|

