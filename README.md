# Đánh giá kiểm định chất lượng web bán vé sự kiện Ticketbox
## Mô tả khái quát nội dung đề tài
Đề tài này tập trung vào việc phát triển một ứng dụng web cho phép người dùng tìm kiếm, đặt mua và quản lý vé tham gia các sự kiện trực tuyến. Ứng dụng không chỉ cung cấp nền tảng kết nối giữa nhà tổ chức sự kiện và khách tham dự mà còn tạo ra một hệ sinh thái hiện đại, thuận tiện trong việc khám phá các sự kiện giải trí, hội thảo, triển lãm,... Với giao diện thân thiện, dễ sử dụng cùng các tính năng như đặt vé, thanh toán, đánh giá sự kiện, quản lý vé cá nhân, ứng dụng hướng tới việc xây dựng một cộng đồng năng động yêu thích trải nghiệm sự kiện. Đồng thời, đề tài cũng đề xuất các giải pháp kỹ thuật hiện đại như tích hợp cơ sở dữ liệu linh hoạt, hệ thống phân loại sự kiện thông minh và đảm bảo an toàn dữ liệu, nhằm mang đến trải nghiệm tối ưu cho người dùng.

## Công nghệ sử dụng
- Frontend: HTML, CSS, JavaScript
- Backend: Node.js
- CSDL: MySQL
## Chức năng xây dựng
- Đăng nhập, đăng kí
- Quản lí tài khoản người dùng
- Tạo, quản lý sự kiện
- Đặt vé, lưu vé, lịch sử giao dịch
- Tìm kiếm, phân loại theo loại sự kiện, thời gian, địa điểm
- Bảo mật thông tin cá nhân và thanh toán
- Phân quyền người dùng: người mua vé, nhà tổ chức, quản trị viên
## Mục tiêu và đối tượng hướng tới của ứng dụng
Ứng dụng web bán vé sự kiện được thiết kế với mục tiêu mang đến trải nghiệm đặt vé dễ dàng, nhanh chóng và an toàn cho người dùng. Giao diện thân thiện, hỗ trợ truy cập mọi lúc, mọi nơi trên các thiết bị.
Ứng dụng hướng tới:
- Người dùng muốn tham gia sự kiện giải trí, giáo dục, hội thảo,...
- Các nhà tổ chức sự kiện cần kênh quản lý và phân phối vé hiệu quả
- Cộng đồng yêu thích trải nghiệm trực tiếp và sự kiện xã hội
Các thành phần người dùng bao gồm:
- Khách tham dự (người mua vé)
- Nhà tổ chức sự kiện
- Quản trị viên hệ thống
- Khách truy cập chưa đăng ký
Ứng dụng mang lại lợi ích xã hội như:
- Thúc đẩy văn hóa tham gia sự kiện và giao lưu cộng đồng
- Hỗ trợ các đơn vị tổ chức sự kiện tiếp cận khách hàng dễ dàng
- Đẩy mạnh sự kiện hóa trong các lĩnh vực giáo dục, giải trí, kinh doanh,...
## Kết quả mong muốn
- Ứng dụng web hoàn chỉnh và ổn định
- Hệ thống phân loại, tìm kiếm sự kiện thông minh
- Khả năng mở rộng, tích hợp thanh toán trực tuyến
- Đảm bảo bảo mật thông tin và hiệu năng cao
- Ứng dụng các công nghệ và kỹ thuật hiệu quả

## Kiểm thử
Black-box testing:
- Chức năng đăng nhập / đăng ký
- CRUD sự kiện
- Mua vé, hủy vé, kiểm tra vé
- Phân quyền người dùng (người tham dự / nhà tổ chức / admin)
- Tìm kiếm và phân loại sự kiện

White-box testing:
- Kiểm thử đơn vị (unit test) các module xử lý vé, thanh toán
- Kiểm thử xử lý ngoại lệ (exception)
- Đảm bảo bao phủ điều kiện, vòng lặp trong xử lý logic

Non-functional testing:
- Kiểm thử hiệu năng
- Kiểm thử bảo mật (thanh toán, thông tin cá nhân)
- Kiểm thử khả năng hiển thị tốt trên thiết bị di động (responsive)

