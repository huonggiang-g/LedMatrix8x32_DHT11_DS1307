**GIỚI THIỆU VỀ HỆ THỐNG **
Hệ thống ma trận LED quang báo là một thiết bị hiển thị thông tin sử dụng các đi-ốt phát quang (LED) sắp xếp theo dạng hàng và cột tạo thành ma trận điểm ảnh. Nhờ khả năng bật/tắt từng LED theo thời gian thực, hệ thống có thể hiển thị văn bản, số liệu, ký hiệu và hình ảnh đơn giản một cách rõ ràng và sinh động. Nội dung hiển thị có thể thay đổi linh hoạt thông qua lập trình, giúp phù hợp với nhiều mục đích sử dụng. Với ưu điểm tiết kiệm điện năng, độ bền cao và khả năng hiển thị tốt cả ban ngày lẫn ban đêm, hệ thống này ngày càng được ứng dụng rộng rãi. Các thành phần chính của hệ thống bao gồm: module ma trận LED, vi điều khiển hoặc máy tính điều khiển, bộ giải mã tín hiệu, phần mềm điều khiển và nguồn điện. Nhờ cấu trúc mô-đun, người dùng có thể dễ dàng mở rộng quy mô bảng hiển thị theo nhu cầu. Hệ thống ma trận LED thường được sử dụng trong các lĩnh vực như giao thông, quảng cáo, thông báo công cộng, và tự động hóa nhà máy. Đây là một giải pháp hiển thị hiện đại, hiệu quả và dễ tùy biến trong kỷ nguyên số.

**MỤC ĐÍCH**
Thiết kế, cài đặt ma trận Led cho phép hiển thị thông tin.

**CHỨC NĂNG**
Sử dụng nút nhấn để chuyển đổi chế độ hoạt động:
•	Chế độ thủ công: nhấn nút để thay đổi kịch bản.
•	Chế độ tự động: các kịch bản tự hoạt động luân phiên (hiển thị thời gian, nhiệt độ, độ ẩm, thông điệp).
•	Hiển thị thời gian thực: đọc và hiển thị dữ liệu từ đồng hồ thời gian thực.
•	Hiển thị nhiệt độ, độ ẩm: đọc và hiển thị dữ liệu từ cảm biến.
•	Hiển thị thông tin mặc định: 1 dòng text cài đặt từ trước.

**CÁC THIẾT BỊ SỬ DỤNG**
Arduino Uno: có vai trò là 1 vi xử lý, nhận tín hiệu từ các module đầu vào, xử lý dữ liệu và điều khiển các module đầu ra.
Các module đầu vào: DHT11 (cảm biến nhiệt độ, độ ẩm), DS1307 (đồng hồ thời gian thực), nút nhấn.
Các module đầu ra: IC 74HC595, 4 ma trận led 8x8
