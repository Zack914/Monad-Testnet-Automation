Dưới đây là bản dịch tiếng Việt đầy đủ cho tài liệu **Monad Testnet Automation**:

---

# 🚀 Tự Động Hóa Monad Testnet

![Monad-BOT](https://img.shields.io/badge/Monad-BOT-blue.svg) ![License](https://img.shields.io/badge/License-ISC-green.svg) ![Platform](https://img.shields.io/badge/Platform-MacOS%2FLinux%2FWindows-lightgrey.svg)

**Monad-Testnet-Automation** là một công cụ tự động hóa blockchain được thiết kế để tương tác với nhiều dịch vụ tiền mã hóa, bao gồm hoán đổi (swap), stake token và nhiều hơn nữa. Công cụ này cung cấp **bảng điều khiển thời gian thực** để theo dõi hoạt động, ghi lại lịch sử giao dịch và tự động hóa các hành động như **wrap/unwarp** và **stake/unstake** token.

---

## ✨ Tính Năng Nổi Bật

✔️ **Bảng Điều Khiển Tương Tác** - Cập nhật số dư, trạng thái mạng và lịch sử giao dịch theo thời gian thực  
✔️ **Chu Kỳ Tự Động** - Thiết lập chu kỳ để thực hiện các thao tác hoán đổi và stake tự động  
✔️ **Tương Tác Blockchain** - Sử dụng `ethers.js` để thực thi smart contract mượt mà  
✔️ **Hỗ Trợ Nhiều Dịch Vụ** - Tương thích với Rubic Swap, Izumi Swap, Bean Swap và nhiều hơn nữa  
✔️ **Bảo Mật Private Key** - Tải private key từ tệp `private.key` một cách an toàn  
✔️ **Cấu Hình Dễ Dàng** - Tùy chỉnh chu kỳ, RPC, địa chỉ contract theo nhu cầu  
✔️ **Hỗ Trợ Nhiều Ví** - Chạy bot trên nhiều ví cùng lúc bằng cách thêm nhiều private key  

---

## 📦 Hướng Dẫn Cài Đặt

### ✅ Yêu Cầu Trước Khi Cài Đặt

Cần cài đặt sẵn:
- **Node.js** (v16 hoặc mới hơn) – [Tải tại đây](https://nodejs.org/)
- **Git** (tùy chọn, để clone repo)

### 🔧 Các Bước Cài Đặt

#### 🖥️ MacOS & Linux

1️⃣ Mở Terminal và chạy:
```bash
# Clone repository
git clone https://github.com/Zack914/Monad-Testnet-Automation.git
cd Monad-Testnet-Automation

# Cài đặt phụ thuộc
npm install
```

2️⃣ Thêm **private key** của bạn vào file `private.key` (mỗi dòng một key):
```bash
nano private.key
```

3️⃣ Chạy bot:
```bash
npm start
```

#### 🖥️ Windows

1️⃣ Mở **PowerShell** và chạy:
```powershell
# Clone repository
git clone https://github.com/Zack914/Monad-Testnet-Automation.git
cd Monad-Testnet-Automation

# Cài đặt phụ thuộc
npm install
```

2️⃣ Thêm **private key** vào `private.key` (sử dụng Notepad hoặc PowerShell):
```powershell
notepad private.key
```
Dán private key, lưu và đóng Notepad/Notepad++.

3️⃣ Chạy bot:
```powershell
npm start
```

---

## 🛠️ Cấu Hình

Chỉnh sửa file `config/config.json` để tùy chỉnh:

- **Cấu Hình Mạng**: RPC URL và block explorer  
- **API Endpoint**: Endpoint của dịch vụ stake hoặc cung cấp thanh khoản  
- **Địa Chỉ Contract**: Các smart contract sử dụng  
- **Tham Số Chu Kỳ**: Thời gian chờ, thời gian cooldown và độ dài chu kỳ  

---

## 🚀 Hướng Dẫn Sử Dụng

### 📊 Khởi Chạy Bot
- Bắt đầu:
  ```bash
  npm start
  ```

- Bảng điều khiển sẽ hiển thị:
  - ✅ Cập nhật số dư
  - 🔄 Nhật ký giao dịch
  - ⏳ Trạng thái hoán đổi/stake
  - 📊 Tiến độ qua từng chu kỳ
  - 🔄 **Xử lý nhiều ví song song**

### 🔄 Dịch Vụ Hỗ Trợ

Bot hỗ trợ các thao tác sau:

- **Giao Dịch**: Gửi MON ngẫu nhiên đến các ví trong `wallets.txt`, triển khai hợp đồng ngẫu nhiên  
- **Hoán Đổi (Swap)**: Hỗ trợ Uniswap, Rubic Swap, Izumi Swap, Bean Swap, Monorail  
- **Stake**: Magma Staking, aPriori Staking, Kitsu Staking  
- **Token**: Kiểm tra số dư, wrap/unwarp token tự động  
- **Nhiều Ví**: Chạy các thao tác liên tục với nhiều ví khác nhau  

---

