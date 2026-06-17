# SQL-Course
Tối ưu hoá cơ sở dữ liệu(SQL):

🔰 Người mới bắt đầu (Tối ưu hóa cơ bản)
🚫 Tránh dùng SELECT *: Chỉ truy xuất (lấy ra) những cột thực sự cần thiết.

📉 Sử dụng LIMIT cho các tập dữ liệu lớn: Cải thiện hiệu suất khi xử lý các truy vấn có lượng dữ liệu khổng lồ.

🔨 Dùng WHERE thay vì HAVING: Lọc dữ liệu trước khi thực hiện các phép gộp/thống kê (aggregation) để đạt hiệu quả cao hơn.

⚡ Trung cấp (Tối ưu hóa cấu trúc truy vấn & Kế hoạch thực thi)
📖 Sử dụng Kế hoạch thực thi truy vấn (Query Execution Plans): Nhận diện các câu truy vấn chậm và tối ưu hóa đường dẫn thực thi của chúng (chính là lệnh EXPLAIN và EXPLAIN ANALYZE mà bạn vừa tìm hiểu).

📌 Giảm thiểu sử dụng GROUP BY: Tránh việc gộp nhóm dữ liệu khi không cần thiết.

🔗 Giảm bớt số lượng lệnh JOIN khi có thể: Tối ưu hóa các mối quan hệ giữa các bảng để ngăn chặn các phép kết nối (join) tốn kém quá nhiều tài nguyên máy chủ.

📊 Tối ưu hóa ORDER BY: Nên sử dụng các cột đã được đánh chỉ mục (indexed) khi cần sắp xếp dữ liệu.

🚀 Nâng cao (Tối ưu hóa cấp độ Cơ sở dữ liệu)
🧠 Sử dụng đúng Kiểu dữ liệu (Data Types): Đảm bảo hiệu quả khi hệ thống phải lọc dữ liệu (ví dụ: bộ lọc xử lý kiểu dữ liệu số luôn nhanh hơn so với kiểu chuỗi/văn bản).

⚡ Đánh chỉ mục (Indexing) hợp lý: Tăng tốc độ các câu truy vấn bằng cách thiết lập chỉ mục có chiến lược (tạo mục lục cho các cột quan trọng).

🗄️ Sử dụng Phân vùng (Partitioning) cho các bảng lớn: Cải thiện hiệu suất xử lý trên các tập dữ liệu quá lớn (chia bảng lớn thành các phần nhỏ hơn để dễ quản lý).
