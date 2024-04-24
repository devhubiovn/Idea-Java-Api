# TỔNG QUAN
## ĐẶT VẤN ĐỀ
- Tôi là một sinh viên trường đại học từ xa, tôi nhận được thời khóa biểu của các môn học kèm theo thời gian và đường link để truy cập lớp học online.
## Ý TƯỞNG
- Tôi có ý tưởng viết một dự án Java để nhận lịch học này qua Telegram, Gmail, v.v.
## KINH PHÍ
- Dự án này không cần phải dùng tới dịch vụ sever, nên sẽ không cần tốn phí mua vps, hay hosting
- Tốn 1 mini pc để work liên tục 24/24 để chạy cronjob tới giờ là thông báo
## ĐIỂM NHẤN
- Dự án này sẽ không sử dụng các dịch vụ database hay lưu trữ trên server.
- Tôi sẽ dùng dịch vụ bên thứ 3 như Firebase để lưu các cấu hình ban đầu, API key, token Trello, v.v. Hoặc có thể sử dụng OAuth2 để sử dụng cho các dịch vụ API của Trello, Telegram, Email, v.v.
# KẾ HOẠCH
## Xác định nhu cầu cơ bản:
- [ ] Nhận lịch học từ tài khoản Firebase hoặc Trello.
- [ ] Gửi thông báo thông qua Telegram và Gmail.
## Tạo cấu trúc dự án Java:
- [ ] Tạo Maven hoặc Gradle project.
## Thiết lập Firebase hoặc Trello:
- [ ] Sử dụng Firebase hoặc Trello để lưu trữ thông tin lịch học và cấu hình ban đầu.
- [ ] Firebase có thể cung cấp Cloud Firestore cho dữ liệu và Firebase Authentication để xác thực người dùng.
## Sử dụng API của Trello và Telegram:
- [ ] Sử dụng API của Trello để lấy thông tin về lịch học.
- [ ] Sử dụng API của Telegram để gửi thông báo tới người dùng.
- [ ] Xác thực qua OAuth2 để sử dụng API của Trello.
## Xây dựng tính năng nhận lịch học:
- [ ] Tạo một phương thức để lấy thông tin lịch học từ Firebase hoặc Trello.
- [ ] Xây dựng chức năng để gửi thông báo về lịch học qua Telegram và Gmail.
## Xác thực và bảo mật:
- [ ] Sử dụng OAuth2 để xác thực với Trello API.
- [ ] Bảo vệ thông tin đăng nhập và token.
## Thiết lập kết nối với Firebase hoặc Trello:
- [ ] Sử dụng Firebase SDK hoặc thư viện Java để kết nối và truy xuất dữ liệu từ Firebase.
- [ ] Sử dụng Trello Java API để kết nối và lấy dữ liệu từ Trello.
## Xây dựng giao diện dòng lệnh hoặc giao diện đồ họa (GUI):
- [ ] Chưa rõ nên sử dụng giao diện dòng lệnh hay đồ họa.
## Lưu trữ cấu hình và token:
- [ ] Lưu trữ cấu hình ban đầu, API key, token Trello và thông tin khác trong một file cấu hình địa phương.
