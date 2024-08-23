Ứng dụng thi trắc nghiệm online.
- Sản phẩm cuối kỳ môn "Công Nghệ Phần Mềm Nâng Cao" của Nhóm 2

1. Phân quyền:
- 1.1. Giáo viên
- 1.2. Sinh viên
2. Chức năng:
- 2.1. Giáo viên:
    - Đăng nhập + Đăng xuất
    - Quản lý lớp học (crud)
    - Quản lý kỳ thi (crud), thêm kỳ thi vào lớp học
    - Quản lý tài khoản sinh viên (crud), thêm sinh viên vào lớp học
    - Quản lý ngân hàng câu hỏi (crud), thêm câu hỏi vào kỳ thi
    - Thiết lập thời gian đếm ngược trong kỳ thi và tự động submit bài thi
    - Thống kê kết quả kỳ thi
- 2.2. Sinh viên:
    - Đăng nhập và đăng xuất
    - Chọn tham gia kỳ thi đã được giáo viên thêm vào
    - Trong bài thi, hết thời gian đếm ngược sẽ tự động nộp bài, submit bài trước khi hết thời gian sẽ hiển thị cảnh báo nếu có câu hỏi chưa hoàn thành
    - Xem kết quả bài thi đã làm
3. Thông tin sản phẩm:
- Ngôn ngữ lập trình: PHP, HTML, JavaScript
- Cơ sở dữ liệu: MySQL
- Thiết kế: CSS, Bootstrap
- Type: Web Application
4. Cài đặt
- Bước 1: Cài đặt XAMPP
  https://www.apachefriends.org/download.html
- Bước 2: Tải mã nguồn và giải nén
- Bước 3: Copy folder mã nguồn vào folder gốc xampp/htdocs
- Bước 4: Chạy phần mềm XAMPP và start Apache và MySQL
- Bước 5: Mở trình duyệt web, truy cập http://localhost/phpmyadmin/
- Bước 6: Tạo CSDL mới, đặt tên "oes_db"
- Bước 7: Chọn import, chọn browse file, chọn "oes_db.sql" trong folder "database" trong folder mã nguồn
- Bước 8: Chọn go để kết thức.
5. Web application
- Teacher: 
  + url: http://localhost/CNPM_NC_nhom2/adminpanel/admin/
  + acc: admin@mail.com
  + pass: 123456
- Student:
  + url: http://localhost/CNPM_NC_nhom2/
  + acc: dave@gmail.com
  + pass: dave
