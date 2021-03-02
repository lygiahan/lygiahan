# Hướng dẫn đóng góp cho dự án
Cảm ơn bạn đã tham gia hỗ trợ dự án. Dưới đây là hướng dẫn chi tiết về cách mà bạn có thể đóng góp cho dự án, mời bạn xem kỹ nội dung này nhé.

## Tổng quan
Dự án được chia thành 3 service chính, hoạt động độc lập nhau để việc phát triển và cài đặt được dễ dàng hơn:

* Service quét bài viết: sử dụng bộ quét Đọc báo
* Service phát hiện bài trùng lặp: lấy dữ liệu từ service quét bài viết thông qua RabbitMQ. Nhiều service có thể cùng lấy bài từ service quét bài viết để thử nghiệm nhiều thuật toán khác nhau.
* Service frontend: hiển thị dữ liệu, giúp chủ blog, website dễ dàng kiểm tra bài viết có bị sao chép trái phép hay không
## Tôi có thể đóng góp cho dự án này như thế nào ?
*Tham gia Slack cuả dự án để cùng thảo luận về giải pháp
* Tham gia tạo file cấu hình để service quét bài viết có thể thu thập được nhiều dữ liệu hơn
* Tự xây dựng service phát hiện bài trùng lặp bằng thuật toán và mô hình cuả riêng bạn
* Tham gia xây dựng frontend cho dự án (khuyến khích sử dụng React và lấy dữ liệu qua API)
* Xin phép chủ website/blog cho phép dự án được thu thập dữ liệu để cùng bảo vệ bản quyền bài viết
* Star github repo của dự án
* Chia sẻ dự án tới nhiều người hơn