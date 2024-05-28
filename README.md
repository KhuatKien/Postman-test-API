# Postman-test-API\
## 1. Giới thiệu về Postman:
Postman là một công cụ mạnh mẽ được sử dụng để kiểm thử, phát triển và quản lý API. Nó cung cấp một giao diện người dùng trực quan cho phép bạn dễ dàng gửi các yêu cầu HTTP, kiểm tra phản hồi và gỡ lỗi các vấn đề API. Postman hỗ trợ nhiều loại yêu cầu HTTP khác nhau, bao gồm GET, POST, PUT, DELETE và PATCH. Nó cũng cung cấp các tính năng để xác thực API, quản lý dữ liệu thử nghiệm và viết các kịch bản kiểm thử tự động.
Các tính năng chính của Postman:
- Gửi và nhận các yêu cầu HTTP.
- Kiểm tra mã trạng thái HTTP và nội dung phản hồi.
- Sử dụng các biến và bộ sưu tập dữ liệu.
- Xác minh tính hợp lệ của JSON.
- Xác thực API.
- Kiểm tra hiệu suất API.
- Kiểm tra bảo mật API.
- Viết các kịch bản kiểm thử tự động.

## 2. Kiểm thử API cơ bản:

- Gửi các yêu cầu HTTP (GET, POST, PUT, DELETE) đến API:
Postman cho phép bạn dễ dàng gửi các yêu cầu HTTP đến các API. Để thực hiện việc này, bạn chỉ cần tạo một yêu cầu mới, chọn phương thức HTTP mong muốn (GET, POST, PUT, DELETE), nhập URL API và nhấp vào nút "Gửi". Postman sẽ gửi yêu cầu đến API và hiển thị phản hồi.

- Kiểm tra mã trạng thái HTTP và nội dung phản hồi:
Mã trạng thái HTTP cho biết liệu yêu cầu của bạn có thành công hay không. Một số mã trạng thái HTTP phổ biến bao gồm 200 (Thành công), 404 (Không tìm thấy) và 500 (Lỗi máy chủ nội bộ). Nội dung phản hồi là dữ liệu được API trả về. Bạn có thể xem nội dung phản hồi trong tab "Trình phản hồi" của Postman.

- Sử dụng các biến và bộ sưu tập dữ liệu trong Postman:
Biến cho phép bạn lưu trữ và truy cập dữ liệu trong Postman. Bạn có thể sử dụng các biến trong các yêu cầu HTTP, tiêu đề và phản hồi. Bộ sưu tập dữ liệu là một tập hợp các biến và yêu cầu. Bạn có thể sử dụng bộ sưu tập dữ liệu để tổ chức và quản lý các trường hợp kiểm thử của mình.

- Xác minh tính hợp lệ của JSON:
Postman có một công cụ tích hợp để xác minh tính hợp lệ của JSON. Bạn có thể sử dụng công cụ này để đảm bảo rằng dữ liệu JSON của bạn được định dạng chính xác.

## 3. Kiểm thử API nâng cao:

- Kiểm tra xác thực và ủy quyền:
Nhiều API yêu cầu xác thực và ủy quyền để truy cập. Postman hỗ trợ nhiều phương thức xác thực khác nhau, bao gồm API key, mã thông báo Bearer và xác thực cơ bản. Bạn có thể sử dụng Postman để gửi các yêu cầu HTTP bao gồm thông tin xác thực và ủy quyền.

- Kiểm tra hiệu suất API:
Postman cho phép bạn đo thời gian phản hồi của API. Điều này có thể hữu ích để xác định các điểm nghẽn hiệu suất và cải thiện hiệu suất API.

- Kiểm tra bảo mật API:
Postman cung cấp các công cụ để giúp bạn kiểm tra bảo mật API của mình. Bạn có thể sử dụng các công cụ này để tìm kiếm các lỗ hổng bảo mật phổ biến, chẳng hạn như tấn công tiêm SQL và tấn công chéo trang (XSS).

- Viết các kịch bản kiểm thử tự động bằng Postman:
Postman hỗ trợ các kịch bản kiểm thử tự động, cho phép bạn tự động hóa các trường hợp kiểm thử của mình. Điều này có thể giúp bạn tiết kiệm thời gian và cải thiện độ bao phủ thử nghiệm của mình.

## 4. Thực hành

- Kịch bản 1:
  
Tên Kịch Bản: Kiểm thử cơ bản của 1 URL

Mục Đích: Test khả năng hoạt động của URL và phần mềm Postman

Phương Thức HTTP: GET

URL: https://pokeapi.co/api/v2/pokemon

Tham Số: ditto

Kết Quả Mong Đợi: Gửi yêu cầu thành công

Kết Quả Thực Tế: Đã gửi yêu cầu thành công

Trạng Thái: Thành công

Kết quả sau khi kiểm thử:
![image](https://github.com/KhuatKien/Postman-test-API/assets/91423106/c5f4df6a-103a-4819-b5a0-e9533594cd3c)


- Kịch bản 2:
  
Tên Kịch Bản: Kiểm thử cơ bản của 1 URL

Mục Đích: Test khả năng hoạt động của URL và phần mềm Postman

Phương Thức HTTP: POST

URL: https://pokeapi.co/api/v2/pokemon

Tham Số: ditto

Kết Quả Mong Đợi: Gửi yêu cầu thành công

Kết Quả Thực Tế: Đã gửi yêu cầu thành công

Trạng Thái: Thành công

Kết quả sau khi kiểm thử:
![image](https://github.com/KhuatKien/Postman-test-API/assets/91423106/7f95b0e3-79f6-4e27-8cc9-271288ca9e0c)
