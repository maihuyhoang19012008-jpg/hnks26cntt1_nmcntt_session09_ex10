
# Phần 1 
 **SmartCampus** là ứng dụng di động *đặc biệt hữu ích* dành cho sinh viên PTIT, giúp bạn quản lý thông tin học tập một cách nhanh chóng và thuận tiện.
 -  Tra cứu lịch học theo mã sinh viên - Kết quả hiển thị tuần hiện tại và các tuần sau
 - Xem danh sách phòng trống theo tòa nhà - Lọc theo khung giờ trong ngày [Trang chủ CLB Lập trình PTIT](https://clblaptrinh.ptit.edu.vn) ) >
  **Lưu ý:** Dự án hiện đang trong giai đoạn phát triển thử nghiệm, chưa sẵn sàng sử dụng cho mục đích chính thức. Nội dung và tính năng có thể thay đổi trong các phiên bản sau.
 # Phần 2 
 ## Cài đặt dự án 
 ```bash git clone https://github.com/clb-lap-trinh/smartcampus.git npm install npm start```
  >dự án đang trong quá trình hoàn thiện ,nếu có lỗi xin finback lại 

 **Tính năng web** 
 - Tra lịch học theo mã sinh viên 
 - Xem danh sách phòng chống  ***gợi ý học tập***
 - còn nhiều tính năng cập nhật sau 
 # Phần 3 
 ## Phần 3 – Hỏi AI & Tài liệu giải thích API 
  1. Prompt đầy đủ gửi cho AI ```markdown 

## Tôi là ai / Bối cảnh 
Tôi là thành viên mới của CLB Lập trình PTIT, đang phát triển dự án ứng dụng di động SmartCampus. Tôi mới nghe đến thuật ngữ API trong tài liệu dự án và muốn hiểu rõ hơn để làm việc hiệu quả. 
## Chủ đề / Nội dung cần xử lý 
Giải thích thuật ngữ kỹ thuật **API** một cách dễ hiểu, phù hợp cho người mới bắt đầu. 
## Yêu cầu - Giải thích bằng ngôn ngữ đơn giản, không dùng thuật ngữ quá phức tạp 
- Nêu ví dụ thực tế liên quan đến ứng dụng di động 
- - Giải thích ngắn gọn cách API hoạt động trong dự án SmartCampus - Đưa ra ví dụ về luồng dữ liệu khi gọi API 
## Không cần 
- Không viết định nghĩa theo sách giáo khoa khô khan 
- - Không giải thích các loại API nâng cao hay lịch sử phát triển 
- - Không dùng đoạn mã code dài dòng
## Nguồn Nội dung được giải thích bởi AI theo yêu cầu của thành viên CLB Lập trình PTIT, dự án SmartCampus.
 
 Giải thích **API** là một bộ quy tắc cho phép các ứng dụng giao tiếp với nhau. Nó đóng vai trò là người đưa tin ứng dụng gửi yêu cầu => API chuyển đến máy chủ => máy chủ xử lý và trả kết quả ngược lại qua API. 
### Ví dụ trong SmartCampus Khi bạn nhập mã sinh viên để xem lịch học: 
1. Ứng dụng gửi yêu cầu đến API: *"Xin lịch học của sinh viên PTIT12345"* 
2. API chuyển yêu cầu đến máy chủ dữ liệu của trường 
3. Máy chủ trả về danh sách môn học → API gửi lại cho ứng dụng 
4. Ứng dụng hiển thị kết quả ra màn hình 
 ### Tại sao cần API? 
 - Tách biệt giao diện người dùng và dữ liệu: dễ bảo trì, nâng cấp 
 - Cùng một nguồn dữ liệu có thể dùng cho nhiều ứng dụng (di động, web...) 
- An toàn hơn: không trực tiếp truy cập vào cơ sở dữ liệu
# Phần 4 
## lỗi sai 
- Bảng thiếu dòng phân cách --- ngay sau dòng tiêu đề cột =>Markdown không nhận diện là 
- Task ListThiếu khoảng trắng sau dấu gạch đầu dòng - trước [x] / [ ] → không hiển thị thành danh sách kiểm tra


| Tính năng | Trạng thái |
|-|-|
| Tra cứu lịch học | Xong |
| Push notification |  Đang làm |
 
 - [x] Tra cứu lịch học 
 - [x] - [ ] Push notification
