# 📱 Ứng dụng Bán Laptop Trực Tuyến – App_LapStore

## 📝 Mô tả chung
**App_LapStore** là một ứng dụng Android hỗ trợ người dùng mua sắm laptop trực tuyến một cách tiện lợi. Ứng dụng cho phép duyệt, tìm kiếm, so sánh và đặt mua sản phẩm ngay trên điện thoại di động với giao diện hiện đại và trải nghiệm mượt mà.

## 🎯 Mục tiêu
- Xây dựng một nền tảng bán hàng di động **thân thiện**, **dễ sử dụng** và **hiệu quả**.
- Cung cấp quy trình mua sắm liền mạch từ duyệt sản phẩm đến thanh toán và theo dõi đơn hàng.
- Tích hợp các tính năng hiện đại như xác thực OTP, thông báo đẩy, Dark Mode, đa ngôn ngữ...

## 🔧 Công nghệ sử dụng
| Thành phần     | Công nghệ                 |
|----------------|---------------------------|
| Frontend       | Kotlin + Jetpack Compose  |
| Backend        | PHP                       |
| Cơ sở dữ liệu  | MySQL (XamPP)             |
| Xác thực       | Email + OTP               |
| Thư viện khác  | Retrofit, Coroutines, Firebase Cloud Messaging (FCM) |

## 🚀 Chức năng chính
- ✅ Đăng ký/Đăng nhập bảo mật bằng mã OTP gửi qua email.
- 🖥️ Hiển thị danh sách sản phẩm laptop với hình ảnh, giá, cấu hình, đánh giá.
- 🔍 Tìm kiếm và lọc sản phẩm theo hãng, mức giá, cấu hình.
- 🛒 Giỏ hàng: thêm/xóa sản phẩm, tự động tính tổng tiền.
- ❤️ Danh sách “Yêu thích”: lưu trên server, đồng bộ giữa các thiết bị.
- 📦 Quản lý đơn hàng: theo dõi trạng thái, xem lịch sử giao dịch.
- 🌙 Hỗ trợ **Dark Mode** và giao diện song ngữ **Anh – Việt**.
- 🔔 Nhận thông báo đẩy từ hệ thống (qua Firebase Cloud Messaging).

## 👨‍💻 Vai trò & Kết quả
Toàn bộ ứng dụng được phát triển bởi một cá nhân:
- **Thiết kế UI/UX** với Jetpack Compose.
- **Xây dựng API** bằng Laravel và triển khai với cơ sở dữ liệu MySQL.
- Kết nối frontend–backend qua Retrofit, xử lý bất đồng bộ với Coroutines.
- Ứng dụng đã hoạt động ổn định, có giao diện hiện đại và trải nghiệm người dùng tốt.

## 📂 Cài đặt
```bash
git clone https://github.com/LePhamNhatLe/App_LapStore.git
