# 🔑 Quản lý API

Màn hình **Quản lý API** cho phép bạn quản lý khóa API TradeGrub — được sử dụng để tích hợp an toàn với các dịch vụ bên ngoài như **TradingView** hoặc **API REST tùy chỉnh**.

---

## 📋 Bảng Khóa API

Tất cả các khóa API hiện có được hiển thị trong một bảng đơn giản, dễ đọc.

### Cột trong bảng
- **Tên** → Nhãn bạn chỉ định khi tạo khóa.
- **Khóa** → Mã định danh duy nhất được sử dụng để xác thực.
- **Quyền** → Xác định những gì khóa có thể truy cập (ví dụ: `TradingView`, `REST`).
- **Ngày tạo** → Ngày tạo khóa.
- **Hành động** → Sử dụng biểu tượng 🗑️ **Xóa** để xóa vĩnh viễn khóa API.

> ⚠️ **Quan trọng:** Việc xóa khóa API sẽ ngay lập tức thu hồi quyền truy cập của khóa đó.
> Bất kỳ dịch vụ nào được kết nối (như webhook TradingView) sử dụng khóa đó sẽ ngừng hoạt động.

---

## ➕ Tạo Khóa API Mới

Nhấn vào nút **“+” (Thêm)** ở góc trên bên phải để tạo khóa mới.

Bạn sẽ được nhắc chỉ định:

| Trường | Mô tả |
|--------|--------------|
| **Tên** | Một tên dễ nhớ để nhận dạng khóa này (ví dụ: *Tín hiệu TradingView*). |
| **Quyền** | Chọn một hoặc cả hai: - **TradingView** → Bắt buộc để nhận và xử lý tín hiệu webhook TradingView. - **REST** → Bắt buộc để truy cập API REST của TradeGrub. |

Sau khi tạo, khóa API mới sẽ xuất hiện ngay lập tức trong chế độ xem bảng của bạn.

> 💡 Bạn có thể tạo nhiều khóa — ví dụ: một khóa cho tài khoản TradingView cá nhân và một khóa khác cho tích hợp REST tự động của bạn.

---

## 🔐 Hiển thị Bí mật API

Khi một khóa API mới được tạo, một **bí mật** sẽ được tạo và hiển thị **chỉ một lần** vì lý do bảo mật.

Bạn sẽ có tùy chọn **sao chép** khóa trong quá trình tạo — hãy đảm bảo lưu trữ an toàn.

> ⚠️ **Lưu ý:**
> Bí mật **không thể xem lại sau**.
> Bạn phải lưu khóa một cách an toàn, vì nó sẽ được yêu cầu khi sử dụng khóa API trong tích hợp **TradingView** hoặc **REST API**.

---

## ⚙️ Thực hành tốt nhất

- Giữ khóa API của bạn **riêng tư và an toàn**.
- Sử dụng **các khóa riêng biệt** cho các tích hợp khác nhau.
- Thu hồi (xóa) các khóa không sử dụng hoặc bị xâm phạm ngay lập tức.
- Không bao giờ chia sẻ khóa API của bạn công khai hoặc trong ảnh chụp màn hình.

---

## 🧩 Ví dụ về các trường hợp sử dụng

| Kịch bản | Quyền bắt buộc |
|-----------|---------------------|
| Gửi tín hiệu mua/bán TradingView | TradingView |
| Thực hiện lệnh gọi API REST đến TradeGrub | REST |
| Thiết lập tự động hóa giao dịch kết hợp | TradingView + REST |

---

## 🆘 Mẹo
- Nhấn vào biểu tượng **thông tin (ℹ️)** ở góc trên bên phải để được trợ giúp nhanh chóng.
- Bạn luôn có thể tạo lại khóa nếu vô tình xóa.
- Các thao tác với khóa API được đồng bộ hóa ngay lập tức với tài khoản của bạn — không cần khởi động lại ứng dụng.
