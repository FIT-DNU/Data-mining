# Chương 2: 📊 Phân tích dữ liệu khoản vay SBA (Small Business Administration)

## 🧭 Mục tiêu

Notebook này thực hiện phân tích bộ dữ liệu khoản vay được bảo lãnh bởi SBA – cơ quan hỗ trợ doanh nghiệp nhỏ của chính phủ Mỹ. Các bước chính bao gồm:

- 🧹 Làm sạch và chuẩn hóa dữ liệu
- 📈 Trực quan hóa các đặc trưng chính: thời gian, vùng miền, quy mô vay, rủi ro
- 💡 Đưa ra nhận định về hiệu quả và tác động của chương trình

---

## 📦 Dữ liệu sử dụng

- **Tên file:** `SBAnational.csv`  
- **Nguồn:** Kaggle – [Should this loan be approved or denied?](https://www.kaggle.com/datasets/mirbektoktogaraev/should-this-loan-be-approved-or-denied)  
- **Dung lượng:** ~170MB  
- **Số dòng:** ~900,000 khoản vay

### 📥 Cách tải dữ liệu

1. Vào link: [kaggle.com/datasets/mirbektoktogaraev/should-this-loan-be-approved-or-denied](https://www.kaggle.com/datasets/mirbektoktogaraev/should-this-loan-be-approved-or-denied)
2. Đăng nhập tài khoản Kaggle (hoặc đăng ký nếu chưa có)
3. Nhấn nút **Download** để tải file `.zip`
4. Giải nén và đặt `SBAnational.csv` vào thư mục chứa notebook (gợi ý: `./chap2/`)

---

## ⚙️ Yêu cầu môi trường

- Python ≥ 3.7  
- Các thư viện: pandas, matplotlib, seaborn
