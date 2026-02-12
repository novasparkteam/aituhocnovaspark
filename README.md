# 📖 Hướng Dẫn Sử Dụng Nova Spark

---

## 🌟 Giới Thiệu

**Nova Spark** là hệ sinh thái hỗ trợ tự học toàn diện dành cho **học sinh THPT Việt Nam**, được phát triển bởi:

- 👑 **Mai Đỗ Hà My** — Đội trưởng
- 💻 **Trần Đình Mạnh Phong** — Thành viên

### Nova Spark bao gồm gì?

| Tính năng | Mô tả |
|-----------|-------|
| 📊 **Thực trạng** | 10 thách thức tự học của HS THPT Việt Nam |
| 📚 **Giải pháp** | 11 phương pháp học tập có nghiên cứu khoa học |
| 📂 **Kho tài nguyên** | 22+ tài nguyên theo 8 môn học |
| 💰 **Quản lý chi tiêu** | Theo dõi chi tiêu hàng ngày, biểu đồ thống kê |
| 📅 **Thời khóa biểu** | Lịch học trong tuần, hỗ trợ xuất/in |
| 🎓 **Xếp loại học lực** | Tính điểm TB & xếp loại tự động |
| 🍅 **Pomodoro Timer** | Đếm ngược 25/5, theo dõi phiên học |
| 📝 **Study Planner** | Lập kế hoạch & deadline, ưu tiên mục tiêu |
| 📊 **Đánh giá tự học** | Bài trắc nghiệm 20 câu, biểu đồ radar 7 năng lực |
| 🤖 **Trợ lý AI** | Chatbot Gemini 3 Flash — hỏi đáp, phân tích ảnh bài tập |
| 🎵 **Study Music** | 5 kênh nhạc lofi/study từ YouTube |
| 🌙 **Dark Mode** | Chế độ sáng/tối tự động |

### Công nghệ sử dụng
- HTML, CSS (Tailwind CSS), JavaScript thuần
- Google Gemini 3 Flash API (chatbot AI)
- localStorage (lưu dữ liệu trên trình duyệt)
- Không cần backend, server, hay database

---

## 🌐 PHẦN 1: Sử dụng trên Web (GitHub Pages)

> Dành cho người dùng truy cập qua link website đã deploy.

### Truy cập
Mở link website được cung cấp bằng trình duyệt (Chrome, Edge, Firefox, Safari).

### Sử dụng các tính năng

#### 🧭 Điều hướng
- Sử dụng **thanh menu** phía trên để chuyển trang
- Nhấn **✨** (góc dưới phải) để mở chatbot AI
- Nhấn **🎵** (góc dưới trái) để mở nhạc study
- Nhấn **☀️/🌙** để đổi chế độ sáng/tối

#### 🤖 Chatbot AI
1. Nhấn nút **✨** → cửa sổ chatbot mở ra
2. Nhập câu hỏi hoặc chọn gợi ý nhanh (Toán THPT, Giảm stress, Kỹ thuật học)
3. Có thể **đính kèm ảnh bài tập** bằng nút 📎 → AI sẽ phân tích
4. Chatbot nhớ ngữ cảnh cuộc trò chuyện

**Khi hết lượt sử dụng (quota):**
1. Nhấn **⚙️** trong chatbot
2. Truy cập [aistudio.google.com/apikey](https://aistudio.google.com/apikey)
3. Đăng nhập Google → nhấn "Create API Key"
4. Dán key vào ô → nhấn "Lưu"
5. API key Gemini **hoàn toàn miễn phí** (15 req/phút)

#### 💰 Quản lý chi tiêu
1. Vào **Ứng dụng** → **Chi tiêu**
2. Nhập số tiền, chọn danh mục, ngày, ghi chú → nhấn **Thêm**
3. Xem biểu đồ tròn (theo danh mục) và biểu đồ cột (7 ngày)
4. **Xuất JSON** để backup, **Nhập JSON** để khôi phục

#### 📅 Thời khóa biểu
1. Vào **Ứng dụng** → **Thời khóa biểu**
2. Nhấn vào ô trống → nhập môn, phòng, giáo viên, chọn màu → **Lưu**
3. Nhấn ô có sẵn để sửa/xóa
4. Hỗ trợ **In** và **Xuất JSON**

#### 🎓 Xếp loại học lực
1. Vào **Ứng dụng** → **Xếp loại**
2. Nhập điểm HK1, HK2 cho từng môn (thang 10)
3. Chọn xem Kỳ 1 / Kỳ 2 / Cả năm
4. Hệ thống tự xếp loại: Giỏi / Khá / TB / Yếu / Kém

#### 🍅 Pomodoro Timer
1. Vào **Ứng dụng** → **Pomodoro**
2. Cấu hình thời gian (mặc định 25/5/15 phút)
3. Nhấn ▶️ để bắt đầu, hệ thống tự chuyển đổi tập trung ↔ nghỉ
4. Xem biểu đồ phiên hoàn thành 7 ngày

#### 📝 Study Planner
1. Vào **Ứng dụng** → **Study Planner**
2. Nhập tiêu đề, deadline, mức ưu tiên → **Thêm**
3. Tick ✅ khi hoàn thành, lọc theo trạng thái
4. Mục tiêu quá hạn tự đánh dấu đỏ

#### 📊 Đánh giá năng lực tự học
1. Vào **Đánh giá** từ menu hoặc nút trên trang chủ
2. Trả lời 20 câu (thang 1–5)
3. Xem biểu đồ radar 7 nhóm năng lực + gợi ý cải thiện

### 🔒 Lưu ý về dữ liệu
- Dữ liệu lưu **trên trình duyệt** của bạn (localStorage)
- Mỗi trình duyệt/máy tính có dữ liệu **riêng biệt** — không ai thấy
- Dữ liệu **không mất** khi tắt trình duyệt hay reload trang
- **Chỉ mất** khi xóa dữ liệu duyệt web → nên **Xuất JSON** backup thường xuyên

---

## 💻 PHẦN 2: Clone về máy (dành cho developer)

> Dành cho người muốn tải mã nguồn về tùy chỉnh hoặc chạy offline.

### Bước 1: Clone mã nguồn
```bash
git clone https://github.com/<username>/aituhocnovaspark.git
cd aituhocnovaspark
```

### Bước 2: Mở trang web
Mở file `index.html` bằng trình duyệt — **không cần cài thêm gì!**

Hoặc dùng Live Server (nếu dùng VS Code):
1. Cài extension **Live Server**
2. Chuột phải `index.html` → **Open with Live Server**

### Bước 3: Cấu hình API key (tùy chọn)
Mở `nova-spark.js`, tìm dòng ~272:
```javascript
const NS_DEFAULT_API_KEY = 'AIza...';
```
- **Giữ nguyên**: tất cả người dùng dùng key sẵn có
- **Thay key riêng**: lấy key tại [aistudio.google.com/apikey](https://aistudio.google.com/apikey)
- **Xóa trống** (`''`): người dùng tự nhập key khi dùng chatbot

### Bước 4: Tùy chỉnh (tùy chọn)

| File | Vai trò |
|------|---------|
| `nova-spark.js` | Cấu hình API, theme, chatbot, nhạc, data isolation |
| `nova-spark.css` | Giao diện, animation, font size |
| `index.html` | Trang chủ, chatbot modal |
| `apps/*.html` | 5 ứng dụng học tập |
| `1.png` | Ảnh hero trang chủ (thay ảnh trường bạn) |

### Bước 5: Deploy lên GitHub Pages
```bash
git add .
git commit -m "Nova Spark update"
git push origin main
```
Sau đó vào **Settings** → **Pages** → chọn branch `main` → **Save**.

### Cấu trúc dự án
```
aituhocnovaspark/
├── index.html              ← Trang chủ + Chatbot
├── thuctrang.html           ← Thực trạng
├── giaiphap.html            ← Giải pháp & Phương pháp
├── portal_tai_nguyen.html   ← Kho tài nguyên
├── about.html               ← Về Nova Spark
├── apps.html                ← Hub ứng dụng
├── assessment.html          ← Đánh giá năng lực
├── nova-spark.css           ← CSS chung
├── nova-spark.js            ← JS chung (AI, theme, nhạc, storage)
├── 1.png                    ← Ảnh hero
├── HUONG_DAN.md             ← File này
└── apps/
    ├── chi-tieu.html        ← Quản lý chi tiêu
    ├── thoi-khoa-bieu.html  ← Thời khóa biểu
    ├── xep-loai.html        ← Xếp loại học lực
    ├── pomodoro.html        ← Pomodoro Timer
    └── study-planner.html   ← Study Planner
```

---

## ❓ Câu Hỏi Thường Gặp

**Dữ liệu có bị mất khi đổi máy không?**
→ Có. Dùng **Xuất JSON** để backup và **Nhập JSON** trên máy mới.

**Chatbot có miễn phí không?**
→ Có! Gemini API free tier cho 15 requests/phút.

**Cần internet không?**
→ Các app (chi tiêu, TKB, điểm, planner) hoạt động **offline**. Chatbot AI và nhạc cần internet.

**Muốn đóng góp?**
→ Fork → tạo branch → commit → Pull Request!

---

> **Nova Spark** © 2026 — Dành cho học sinh THPT Việt Nam 💜
