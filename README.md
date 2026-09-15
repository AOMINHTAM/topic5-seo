# BÁO CÁO THỰC HÀNH MÔN SEO - TOPIC 5
## Tối Ưu Dữ Liệu Có Cấu Trúc (Schema Markup) & On-Page SEO

---

### 1. Thông Tin Nhóm Thực Hiện
* **Sinh viên 1:** Trần Mạnh Hùng - MSSV: `1350080086` (Nhóm trưởng)
* **Sinh viên 2:** Ao Minh Tâm - MSSV: `1350080240`
* **Sinh viên 3:** Nguyễn Thành Đạt - MSSV: `1350080054`

---

### 2. Giới Thiệu Dự Án
Website được xây dựng dưới dạng **Analytics Report Hub**, trực quan hóa kết quả nghiên cứu: *"Phân tích Hiệu suất Marketing trên Mạng xã hội"* dựa trên tập dữ liệu thực nghiệm 5.000 bài đăng qua 6 nền tảng và 8 khu vực quốc tế.

* **Live Demo (GitHub Pages):** https://aominhtam.github.io/topic5-seo/
* **Source Code (Repository):** https://github.com/AOMINHTAM/topic5-seo
* **Công nghệ sử dụng:** HTML5 Semantic, CSS3 Custom Properties (Dark/Light Theme), Vanilla JS, SVG Data URI Favicon.

---

### 3. Các Hạng Mục Kỹ Thuật SEO Đã Triển Khai

#### A. Cấu trúc dữ liệu nâng cao (Structured Data - Multi-Schema JSON-LD)
Dự án ứng dụng kỹ thuật lồng ghép `@graph` để khai báo đồng thời 3 thực thể dữ liệu có cấu trúc:
1. **TechArticle Schema:** Định danh bài báo cáo kỹ thuật, liên kết tác giả, tổ chức phát hành và thời gian xuất bản/cập nhật.
2. **FAQPage Schema:** Tối ưu hóa các đoạn trích nổi bật (Rich Snippets) cho câu hỏi thường gặp về khung giờ vàng, thuật toán và phân bổ ROI.
3. **BreadcrumbList Schema:** Định vị đường dẫn phân cấp website nhằm tối ưu cấu trúc thu thập dữ liệu của công cụ tìm kiếm.

#### B. Tối ưu On-Page & Semantic HTML
* Sử dụng chuẩn thẻ ngữ nghĩa: `<header>`, `<main>`, `<article>`, `<section>`, thẻ đề mục phân cấp rõ ràng từ `<h1>` đến `<h3>`.
* Tối ưu thẻ meta thiết yếu: `<meta name="description">`, `viewport`, và bộ thẻ chia sẻ mạng xã hội Open Graph (`og:title`, `og:description`, `og:type`).
* Favicon vector định dạng SVG chuẩn nhận diện thương hiệu cá nhân (**AT**).

#### C. Trải nghiệm người dùng (UX/UI Signals)
* Tích hợp bộ chuyển đổi giao diện **Light/Dark Mode** với màu chủ đạo Cyber Amber.
* Lưu trữ trạng thái giao diện người dùng qua `localStorage` giúp tăng thời gian on-site và giảm tỷ lệ thoát (Bounce Rate).

---

### 4. Quy Trình Kiểm Thử (Testing & Verification)
1. Kiểm tra tính hợp lệ của dữ liệu có cấu trúc qua công cụ **Google Rich Results Test**.
2. **Kết quả đạt được:** 
   * Trạng thái: **Đã phát hiện 3 mục hợp lệ** (Không có lỗi hoặc cảnh báo nghiêm trọng).
   * Đủ điều kiện xuất hiện trên trang kết quả tìm kiếm nhiều định dạng của Google.
