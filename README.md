# DO_AN_HTTT2311
# 🛒 HPH Store – Website Bán Hàng Tiện Lợi

HPH Store là một website thương mại điện tử mini dành cho các cửa hàng tiện lợi, cho phép khách hàng xem sản phẩm, thêm vào giỏ hàng, đặt hàng và quản trị viên quản lý sản phẩm, đơn hàng, khách hàng, doanh thu.

> 🎯 Mục tiêu: Làm bài tập / đồ án môn Lập Trình Web / CSDL với một website bán hàng có đầy đủ các chức năng cơ bản (frontend + backend + database).

---

## 🚀 Chức năng chính

### 👥 Phía khách hàng (User)

- Xem danh sách sản phẩm theo **danh mục** (đồ uống, snack, mì gói, v.v.)
- Tìm kiếm sản phẩm theo tên
- Xem chi tiết sản phẩm (hình ảnh, giá, mô tả, danh mục,…)
- Thêm sản phẩm vào **giỏ hàng**
- Cập nhật giỏ hàng:
  - Tăng/giảm số lượng
  - Xóa sản phẩm khỏi giỏ
- Đặt hàng / thanh toán (nhập thông tin khách hàng, địa chỉ, ghi chú)
- Xem thông báo **"Đặt hàng thành công"** sau khi thanh toán

### 🛠 Phía quản trị viên (Admin)

- Đăng nhập admin
- Quản lý sản phẩm:
  - Thêm / sửa / xóa sản phẩm
  - Quản lý danh mục sản phẩm
- Quản lý đơn hàng:
  - Xem danh sách đơn hàng
  - Xem chi tiết đơn
  - Cập nhật trạng thái đơn (đang xử lý, đã giao,…)
- Thống kê cơ bản (ví dụ: tổng số đơn, tổng doanh thu theo ngày/tháng) — *nếu bạn có làm thì ghi thêm chi tiết*

---

## 🧱 Công nghệ sử dụng

- **Frontend:**
  - HTML5, CSS3, JavaScript
  - Giao diện responsive, màu sắc trẻ trung (đỏ – cam – hồng – vàng neon) phù hợp giới trẻ

- **Backend:**
  - PHP (thuần)

- **Database:**
  - MySQL / MariaDB (chạy qua XAMPP)

- **Môi trường chạy:**
  - XAMPP (Apache + MySQL)
  - Trình duyệt: Chrome / Edge / Firefox

---

## 📁 Cấu trúc thư mục (ví dụ)

```bash
HPH-store/
├── index.php              # Trang chủ
├── product_list.php       # Danh sách sản phẩm
├── product_detail.php     # Chi tiết sản phẩm
├── cart.php               # Giỏ hàng
├── checkout.php           # Thanh toán
├── config.php             # Kết nối database
├── /admin                 # Khu vực admin
│   ├── index.php          # Dashboard admin / login
│   ├── products.php       # Quản lý sản phẩm
│   ├── orders.php         # Quản lý đơn hàng
│   └── ...                
├── /assets
│   ├── /css
│   │   └── style.css      # CSS chính
│   ├── /js
│   │   └── main.js        # JS (nếu có)
│   └── /img               # Hình ảnh sản phẩm, logo, banner
└── README.md
