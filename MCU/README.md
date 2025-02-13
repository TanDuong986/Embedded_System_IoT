# Embedded_System_IoT

Trong Project này có thiết kế 2 App Android sử dụng trên điện thoại/Table như sau:

App số 1 - App với Full kết nối có các chức năng:
- Tìm, quét và kết nối thiết bị Module BLE HM-10 có kết nối tới mạch điều khiển STM32.
- Đọc dữ liệu của cảm biến gửi tới App sau khi kết nối BLE.
- Kết nối với Cloud và đẩy dữ liệu đọc được từ cảm biến lên Cloud thông qua mạng Wifi/Di động (Cloud sử dụng Realtime Database của Google Firebase).
- Sau khi kết nối tới Cloud, lấy dữ liệu thời gian thực từ trên Cloud và hiển thị lên App.

App số 2 - App chỉ có chức năng kết nối và hiển thị dữ liệu từ Cloud giúp theo dõi dữ liệu thời gian thực từ xa.
