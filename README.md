# Portfolio Cá Nhân — Trung Ton (Full-stack Developer)

Website portfolio cá nhân hoàn chỉnh, chuyên nghiệp, chuẩn UI/UX và conversion copywriting dành cho lập trình viên **Full-stack Developer (React/Next.js, TypeScript, Node.js, PostgreSQL)**. Sẵn sàng publish và deploy ngay lập tức lên Vercel, Netlify hoặc GitHub Pages mà không cần bước build phức tạp.

---

## 🚀 Tính năng Nổi bật

### 1. Trải nghiệm UI/UX Hiện đại & Chuẩn Accessibility (a11y)
- **Tối giản, phong cách Developer:** Thiết kế sắc nét, nhiều khoảng trắng, sử dụng typography tiêu chuẩn ngành: **Inter** (tiêu đề & nội dung) và **JetBrains Mono** (mã nguồn, badges, số liệu kỹ thuật).
- **Dark / Light Mode:** Tự động phát hiện cài đặt hệ thống người dùng, hỗ trợ chuyển đổi mượt mà với 1 click và ghi nhớ trạng thái qua `localStorage`. Độ tương phản chuẩn WCAG AAA/AA (>4.5:1).
- **Hỗ trợ Song ngữ Toàn diện (VI / EN):** Tích hợp bộ từ điển song ngữ với nút chuyển đổi ngay trên thanh điều hướng; chuyển ngữ tức thì toàn bộ nội dung từ tiêu đề, mô tả đến chi tiết 4 bài toán kỹ thuật chuyên sâu (deep-dives).
- **Thân thiện với mọi thiết bị (Responsive Mobile-first):** Bố cục tối ưu trên màn hình từ 375px (mobile) đến 1440px (desktop), menu trượt di động chuẩn thao tác ngón tay cái, kích thước vùng chạm (touch target) tối thiểu 44x44px.
- **Tôn trọng `prefers-reduced-motion`:** Giảm thiểu hoặc tắt hoàn toàn chuyển động khi người dùng kích hoạt tùy chọn giảm chuyển động trên hệ điều hành.
- **Không dùng emoji cho UI Icons:** Toàn bộ biểu tượng là vector SVG sắc nét (chuẩn Lucide/Heroicons), không phụ thuộc font bên ngoài.

### 2. Copywriting Chuẩn Kỹ thuật & Khiêm tốn, Thuyết phục
- **Giọng văn tự tin, trung thực, tránh phóng đại:** Tuyệt đối không dùng các từ ngữ rỗng ("xuất sắc", "banking-grade", "tuyệt đối", "100%").
- **Nhấn mạnh tư duy giải quyết bài toán & đánh đổi kỹ thuật (Engineering Trade-offs):**
  - Trình bày rõ ràng bài toán tồn kho ảo (ghost inventory) và đánh đổi oversell hy hữu trong giao dịch thanh toán trực tuyến.
  - Tư duy zero-trust: không tin tưởng giá từ client, tự tính toán trên server để chống gian lận.
  - Bảo mật webhook bằng thuật toán so sánh thời gian hằng số (`crypto.timingSafeEqual`) chống timing attacks.
  - Lộ trình kỹ thuật rõ ràng: rate limiting in-memory sang Redis cluster khi mở rộng.

### 3. Case Study Chuyên sâu theo Chuẩn Portfolio Quốc tế
- **Tingo (https://tingo.vietqr.vn):**
  - Sơ đồ kiến trúc hệ thống trực quan dạng **SVG** (Client Tiers → Next.js 16 Presentation & Route Handlers → PostgreSQL ~16 bảng với Connection Pool & Transactions → Dịch vụ bên ngoài VietQR, Vận chuyển, Telegram Alerting).
  - Khung xem trước (preview mockup) kèm liên kết truy cập hệ thống đang chạy thật trên production.
  - Phân tích 4 thách thức kỹ thuật cốt lõi theo cấu trúc: **Vấn đề → Giải pháp kỹ thuật → Đánh đổi & Bài học**.
- **Bluecom (https://bluecom.vn):**
  - Case study landing page doanh nghiệp song ngữ (18 sections, 7 tài liệu kỹ thuật).
  - 3 bài học tối ưu: giải pháp giữ keyframe Tailwind v4 production, định tuyến đa ngôn ngữ `localePrefix: 'as-needed'`, xử lý `scroll-margin-top` cho fixed header.
- **Oboe (Team 5 người — PM & Team Leader):**
  - Dự án nền tảng học tiếng Nhật; minh chứng năng lực dẫn dắt đội ngũ, quản lý tiến độ và code backend Java + MySQL.
- **Herbal Tea Website:**
  - Dự án độc lập tối ưu hiệu năng với HTML5/CSS3/JavaScript thuần túy.

### 4. Tiện ích Tương tác Bổ trợ
- **Bộ lọc kỹ năng tương tác (Interactive Skills Filter):** Lọc nhanh kỹ năng theo danh mục: Tất cả, Frontend, Backend & API, Database & DevOps, Nền tảng & Kỹ năng mềm.
- **Modal Tải / Xem trước CV:** Hỗ trợ in trực tiếp ra file PDF tiêu chuẩn (`Ctrl+P` / `Cmd+P`) nhờ CSS `@media print` được tinh chỉnh riêng (tự động ẩn thanh điều hướng và nền tối).
- **Sao chép Email 1-click:** Nút copy nhanh `trungton883@gmail.com` kèm thông báo toast phản hồi trực quan.
- **Form liên hệ tích hợp Honeypot:** Chống bot spam và tự động kích hoạt soạn thư gửi đến email cá nhân.

---

## 📁 Cấu trúc Thư mục

```text
Portfolio/
├── index.html         # Toàn bộ mã nguồn website (HTML5, Tailwind CSS, SVG, JS & Từ điển Song ngữ)
├── README.md          # Hướng dẫn chi tiết triển khai và tùy biến
└── .claude/           # Tài liệu kỹ năng tham khảo (UI/UX Pro Max & Copywriting)
```

---

## 🌐 Hướng dẫn Triển khai (Deploy) Ngay

Portfolio được tối ưu ở dạng file tĩnh hiệu năng cực cao, không đòi hỏi `node_modules` hay bước build nặng nề:

### Cách 1: Triển khai qua Vercel (Khuyên dùng — 30 giây)
1. Cài đặt Vercel CLI (nếu chưa có):
   ```bash
   npm i -g vercel
   ```
2. Đứng tại thư mục `Portfolio` và chạy:
   ```bash
   vercel
   ```
   (Bấm Enter chấp nhận các giá trị mặc định).
3. Hoặc đẩy mã nguồn lên GitHub, truy cập [vercel.com](https://vercel.com), bấm **Add New Project** → Chọn repo của bạn → Bấm **Deploy**.

### Cách 2: Triển khai qua Netlify
1. Truy cập [app.netlify.com/drop](https://app.netlify.com/drop).
2. Kéo thả thư mục chứa file `index.html` vào trình duyệt. Website sẽ được publish ngay với link HTTPS miễn phí.

### Cách 3: Triển khai qua GitHub Pages
1. Tạo một repository mới trên GitHub (ví dụ: `portfolio` hoặc `<username>.github.io`).
2. Đẩy toàn bộ file trong thư mục này lên branch `main`:
   ```bash
   git init
   git add .
   git commit -m "feat: initial release portfolio Trung Ton"
   git branch -M main
   git remote add origin https://github.com/<username>/portfolio.git
   git push -u origin main
   ```
3. Trên GitHub, vào mục **Settings** → **Pages** → Tại mục **Branch**, chọn `main` / `root` → Bấm **Save**. Website sẽ chạy tại `https://<username>.github.io/portfolio/`.

---

## 🛠️ Hướng dẫn Tùy biến Nhanh

1. **Thay đổi liên kết GitHub & LinkedIn:**
   Trong file `index.html`, tìm kiếm `https://github.com/trungton883` hoặc `https://linkedin.com/in/trungton` và thay bằng URL tài khoản của bạn.
2. **Gắn file PDF CV thực tế:**
   Nếu bạn đã xuất sẵn file `Trung_Ton_CV.pdf`, hãy đặt file đó cùng cấp với `index.html`. Trong `cv-modal`, đổi nút `Yêu cầu bản PDF qua Email` thành:
   ```html
   <a href="./Trung_Ton_CV.pdf" download="Trung_Ton_CV.pdf" class="...">
     Tải xuống bản PDF
   </a>
   ```
3. **Cập nhật số liệu thực tế (khi có):**
   Trong các case study, khi dự án đạt các mốc số liệu cụ thể (doanh số, số lượng đơn hàng, số CTV...), bạn có thể bổ sung vào phần thẻ số liệu để tăng tính thuyết phục.

---

## 📄 Bản quyền
&copy; 2026 Trung Ton. Thiết kế và xây dựng hướng tới tiêu chuẩn kỹ thuật cao, tốc độ tải tức thì và trải nghiệm tuyển dụng thuận tiện nhất.

