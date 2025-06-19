# 🍔 Food & Food – Website Bán Đồ Ăn Online

Food & Food là một website thương mại điện tử bán đồ ăn trực tuyến, được xây dựng bằng **React.js**, **Node.js**, **MongoDB** và tích hợp thanh toán qua **PayPal**.

---

## 🔥 Tính Năng

### 👥 Người Dùng

- 🔐 **Xác thực người dùng**  
  - Đăng ký tài khoản  
  - Đăng nhập, đăng xuất

- 🛒 **Mua sắm linh hoạt**  
  - Tìm kiếm và duyệt sản phẩm  
  - Thêm/sửa/xoá sản phẩm trong giỏ hàng  
  - Đặt hàng, theo dõi đơn hàng  
  - Thanh toán qua **PayPal** hoặc **Tiền mặt**

- 👤 **Quản lý tài khoản cá nhân**

---

### 🛠️ Quản Trị Viên

- 📦 Quản lý **sản phẩm**
- 👤 Quản lý **người dùng**
- 📑 Quản lý **đơn hàng**
- 🔄 Cập nhật **trạng thái đơn hàng**
- 📊 Thống kê **doanh thu**

---

## 🧪 Công Nghệ Sử Dụng

### 🚀 Frontend

- React.js
- Redux Toolkit (quản lý trạng thái)
- Ant Design (giao diện hiện đại)
- React Router (điều hướng)
- Axios (kết nối API)
- PayPal SDK

### 🔧 Backend

- Node.js + Express
- MongoDB (Mongoose ODM)
- JWT (xác thực người dùng)
- dotenv (quản lý biến môi trường)
- Bcrypt (mã hoá mật khẩu)

---

## ⚙️ Hướng Dẫn Cài Đặt

### Yêu Cầu Hệ Thống

- Node.js (v14+)
- npm
- MongoDB (cài cục bộ hoặc dùng MongoDB Atlas)

### 📦 Clone và Cài đặt

```bash
# Clone project
git clone https://github.com/your-username/food-and-food.git
cd food-and-food

# Cài đặt backend
cd backend
npm install

# Cài đặt frontend
cd ../frontend
npm install
▶️ Khởi chạy ứng dụng
Backend (port 5000):


# cd backend
npm start


Frontend (port 3000):


# cd frontend
npm start


Ứng dụng sẽ chạy tại: http://localhost:3000

🛠️ Cấu Hình Môi Trường
Tạo file .env trong thư mục backend/ với nội dung:

```
.env
MONGODB_URI=mongodb+srv://<user>:<password>@<cluster>.mongodb.net/?retryWrites=true&w=majority
EMAIL_USER=your_email@gmail.com
EMAIL_PASS=your_app_password
JWT_SECRET_KEY=your_secret_key
PAYPAL_CLIENT_ID=your_paypal_client_id
PAYPAL_CLIENT_SECRET=your_paypal_secret

🛑 Không commit file .env lên GitHub!

👨‍💻 Tác Giả
👤 Phi Hùng – Fullstack Developer
