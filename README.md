# Tokyo Life - E-commerce Website

Tokyo Life là một website bán hàng trực tuyến được xây dựng bằng **React (TypeScript)** cho phần frontend và **Laravel API** cho phần backend. Mục tiêu của dự án là cung cấp trải nghiệm mua sắm mượt mà, thân thiện với người dùng, hỗ trợ quản lý sản phẩm, giỏ hàng, thanh toán và nhiều tính năng khác.

---

## 🌟 Features

### Frontend:
- Giao diện hiện đại, tối ưu UX/UI.
- Tìm kiếm sản phẩm và lọc theo danh mục, giá, màu sắc, v.v.
- Hỗ trợ giỏ hàng và quản lý sản phẩm.
- Hệ thống đăng ký/đăng nhập người dùng.
- Hiển thị chi tiết sản phẩm với hình ảnh và mô tả.
- Thanh toán trực tuyến (VNPay, MoMo, PayPal, COD).

### Backend:
- API RESTful xây dựng bằng Laravel, hỗ trợ đầy đủ các CRUD chức năng:
  - Quản lý sản phẩm, danh mục, và kho hàng.
  - Xử lý giỏ hàng và thanh toán.
  - Xác thực người dùng (JWT Authentication).
- Tích hợp gửi email thông báo đơn hàng.
- Tối ưu hiệu suất và bảo mật.

---

## 🛠️ Tech Stack

### Frontend:
- **React** (với TypeScript)
- **React Router**: Điều hướng các trang.
- **Axios**: Kết nối API.
- **Redux Toolkit**: Quản lý trạng thái ứng dụng.
- **React Hook Form**: Quản lý biểu mẫu.
- **TailwindCSS**: Tùy chỉnh giao diện.

### Backend:
- **Laravel**: Framework backend mạnh mẽ.
- **MySQL**: Hệ quản trị cơ sở dữ liệu.
- **Passport hoặc Sanctum**: Xác thực API.
- **Pusher**: Thông báo thời gian thực.

---

## 📦 Installation

### Prerequisites
- Node.js (>= 16.x)
- PHP (>= 8.1)
- Composer (>= 2.x)
- MySQL (>= 8.x)

### Steps to Install

#### Backend (Laravel API):
1. Clone repository backend:
   ```bash
   git clone <backend-repo-url>
   cd backend
```bash
composer install
```bash
cp .env.example .env
```bash
php artisan migrate --seed
```bash
php artisan key:generate
```bash
php artisan serve
```bash
#### FRONTEND (React TypeScript):
```bash
   cd backend
```bash
npm install
```bash
REACT_APP_API_URL=http://localhost:8000/api
```bash
npm run dev

Dưới đây là nội dung chi tiết cho tệp README.md phù hợp với dự án website bán hàng Tokyo Life sử dụng React (TypeScript) và Laravel API:

markdown
Sao chép mã
# Tokyo Life - E-commerce Website

Tokyo Life là một website bán hàng trực tuyến được xây dựng bằng **React (TypeScript)** cho phần frontend và **Laravel API** cho phần backend. Mục tiêu của dự án là cung cấp trải nghiệm mua sắm mượt mà, thân thiện với người dùng, hỗ trợ quản lý sản phẩm, giỏ hàng, thanh toán và nhiều tính năng khác.

---

## 🌟 Features

### Frontend:
- Giao diện hiện đại, tối ưu UX/UI.
- Tìm kiếm sản phẩm và lọc theo danh mục, giá, màu sắc, v.v.
- Hỗ trợ giỏ hàng và quản lý sản phẩm.
- Hệ thống đăng ký/đăng nhập người dùng.
- Hiển thị chi tiết sản phẩm với hình ảnh và mô tả.
- Thanh toán trực tuyến (VNPay, MoMo, PayPal, COD).

### Backend:
- API RESTful xây dựng bằng Laravel, hỗ trợ đầy đủ các CRUD chức năng:
  - Quản lý sản phẩm, danh mục, và kho hàng.
  - Xử lý giỏ hàng và thanh toán.
  - Xác thực người dùng (JWT Authentication).
- Tích hợp gửi email thông báo đơn hàng.
- Tối ưu hiệu suất và bảo mật.

---

## 🛠️ Tech Stack

### Frontend:
- **React** (với TypeScript)
- **React Router**: Điều hướng các trang.
- **Axios**: Kết nối API.
- **Redux Toolkit**: Quản lý trạng thái ứng dụng.
- **React Hook Form**: Quản lý biểu mẫu.
- **TailwindCSS**: Tùy chỉnh giao diện.

### Backend:
- **Laravel**: Framework backend mạnh mẽ.
- **MySQL**: Hệ quản trị cơ sở dữ liệu.
- **Passport hoặc Sanctum**: Xác thực API.
- **Pusher**: Thông báo thời gian thực.

---

## 📦 Installation

### Prerequisites
- Node.js (>= 16.x)
- PHP (>= 8.1)
- Composer (>= 2.x)
- MySQL (>= 8.x)

### Steps to Install

#### Backend (Laravel API):
1. Clone repository backend:
   ```bash
   git clone <backend-repo-url>
   cd backend
Cài đặt các package PHP:
bash
Sao chép mã
composer install
Tạo tệp .env:
bash
Sao chép mã
cp .env.example .env
Cấu hình cơ sở dữ liệu trong .env.
Tạo bảng và dữ liệu giả:
bash
Sao chép mã
php artisan migrate --seed
Tạo key ứng dụng:
bash
Sao chép mã
php artisan key:generate
Chạy server Laravel:
bash
Sao chép mã
php artisan serve
Frontend (React TS):
Clone repository frontend:
bash
Sao chép mã
git clone <frontend-repo-url>
cd frontend
Cài đặt các package npm:
bash
Sao chép mã
npm install
Tạo tệp .env và cấu hình URL API:
env
Sao chép mã
REACT_APP_API_URL=http://localhost:8000/api
Chạy ứng dụng React:
bash
Sao chép mã
npm run dev
🚀 Usage
1Truy cập backend Laravel tại: http://localhost:8000.
2Truy cập frontend React tại: http://localhost:5173.
🧪 Testing
Frontend:

Sử dụng Jest và React Testing Library để viết và chạy các bài kiểm tra giao diện.
bash
Sao chép mã
npm test
Backend:

Sử dụng PHPUnit để kiểm tra các endpoint API.
bash
Sao chép mã
php artisan test
📂 Project Structure
Frontend (React TS):
csharp
Sao chép mã
frontend/
├── public/          # Tệp tĩnh (favicon, index.html)
├── src/
│   ├── api/         # Các hàm gọi API (Axios)
│   ├── components/  # Các component giao diện
│   ├── pages/       # Các trang chính (Home, Product, Cart)
│   ├── redux/       # Quản lý trạng thái
│   ├── utils/       # Hàm tiện ích
│   └── App.tsx      # Điểm khởi đầu của ứng dụng
├── package.json     # Cấu hình npm
└── tsconfig.json    # Cấu hình TypeScript
Backend (Laravel):
bash
Sao chép mã
backend/
├── app/             # Code chính
├── config/          # Các file cấu hình
├── database/        # Migration và seeders
├── public/          # Thư mục công khai
├── routes/          # File định tuyến (api.php)
├── storage/         # File cache, log
├── tests/           # Test PHPUnit
└── .env             # File cấu hình môi trường
🙏 Acknowledgments
React và Laravel vì công cụ tuyệt vời.
Cộng đồng mã nguồn mở vì tài nguyên hữu ích.
Đội ngũ phát triển Tokyo Life đã làm việc chăm chỉ.
📧 Contact
Email: support@tokyolife.com
Website: tokyolife.com
Facebook: Tokyo Life Official
Chúc bạn thành công với dự án Tokyo Life! 🎉


