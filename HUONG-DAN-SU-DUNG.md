# HƯỚNG DẪN CÀI ĐẶT & SỬ DỤNG TRÊN FLATSOME UX BUILDER

Tất cả các khối đã được module hóa chuẩn shortcode của Flatsome Theme, tương thích 100% không bị xung đột CSS hay vỡ khung khi xem trên Điện thoại (Mobile), Máy tính bảng (Tablet) hay Máy tính (Desktop).

---

## BƯỚC 1: DÁN CSS TÙY BIẾN VÀO FLATSOME
1. Mở trang quản trị WordPress: Vào **Giao diện (Appearance)** > **Tùy biến (Customize)** > **Custom CSS** (hoặc Advanced > Custom CSS).
2. Mở tệp [`flatsome-custom.css`](file:///c:/Users/HOANG%20SANG/Downloads/stitch_landing_page_h_c_l_i_xe/flatsome-custom.css).
3. Sao chép (Copy) toàn bộ nội dung trong tệp và dán vào ô **Custom CSS**.
4. Bấm **Đăng (Publish)** để lưu lại.

---

## BƯỚC 2: TẠO TRANG & NHẬP NỘI DUNG VÀO UX BUILDER
1. Vào **Trang (Pages)** > **Thêm trang mới (Add New Page)**.
2. Đặt tiêu đề trang (Ví dụ: *Khóa Học Lái Xe Ô Tô TP.HCM*).
3. Bên cột phải phần **Giao diện trang (Page Template)**: Chọn **Page - Full Width** (hoặc Page - No Header/Footer nếu bạn muốn landing page độc lập).
4. Bấm nút xanh **UX Builder** ở thanh trên cùng để mở trình thiết kế trực quan.
5. Trong UX Builder:
   - Cách 1 (Dán toàn bộ trang cùng lúc): Nhìn sang menu bên trái, bấm vào biểu tượng bánh răng cài đặt hoặc bấm tab **Import / Paste Shortcodes** (hoặc chuyển qua trình soạn thảo dạng Text của WordPress). Dán toàn bộ nội dung từ tệp [`ux-builder-blocks.txt`](file:///c:/Users/HOANG%20SANG/Downloads/stitch_landing_page_h_c_l_i_xe/ux-builder-blocks.txt) (bao gồm cả Khối 0: Menu Header).
- Cách 2 (Dán từng khối): Thêm phần tử `[UX Html]` hoặc `[Section]` rồi dán lần lượt từ Khối 0 đến Khối 7.
- Cách 3 (Dùng file XML tự động): Vào **Công cụ > Nhập vào > WordPress**, tải tệp [`ux-blocks-import.xml`](file:///c:/Users/HOANG%20SANG/Downloads/stitch_landing_page_h_c_l_i_xe/ux-blocks-import.xml) lên để tự động tạo đầy đủ 8 blocks trong menu **UX Blocks** của WordPress.

---

## HƯỚNG DẪN MENU LANDING PAGE (ONE-PAGE SCROLL)

Menu landing page đã được thiết lập sẵn hiệu ứng **Sticky (cố định trên đỉnh)** và **Smooth Scroll (cuộn mượt mà)** khi nhấn vào từng mục:
- **Khóa học** -> cuộn đến `#khoa-hoc`
- **Cam kết đào tạo** -> cuộn đến `#cam-ket`
- **Quy trình học** -> cuộn đến `#quy-trinh`
- **Cảm nhận học viên** -> cuộn đến `#cam-nhan`
- **Đăng ký tư vấn** -> cuộn đến `#dang-ky-form`
- **Hotline & Nút Đăng ký ngay**: Tích hợp sẵn nút gọi và nút CTA nhận ưu đãi.
- **Trên Điện thoại**: Tự động chuyển thành nút Hamburger 3 gạch, khi bấm sẽ xổ menu xuống gọn gàng và tự đóng khi chọn mục.

> **Mẹo tùy biến Flatsome Header:**
> Nếu bạn muốn dùng thanh Header mặc định của Flatsome thay vì Khối 0:
> 1. Vào **Giao diện** > **Menu** > Tạo Menu mới (ví dụ: *Menu Landing Page*).
> 2. Thêm các **Liên kết tự tạo (Custom Links)** với URL là `#khoa-hoc`, `#cam-ket`, `#quy-trinh`, `#cam-nhan`, `#dang-ky-form`.
> 3. Chọn vị trí hiển thị là **Main Menu** (hoặc gán trong Flatsome Header Builder).
> 4. Trang Landing Page sẽ tự động cuộn mượt đến các khối tương ứng!
6. Bấm **Apply** > **Update** để lưu.

---

## BƯỚC 3: CHỈNH SỬA TEXT VÀ HÌNH ẢNH TRỰC QUAN

### 1. Thay đổi Text (Nội dung chữ):
- Bạn chỉ cần nhấp đúp (Double-click) trực tiếp vào bất kỳ đoạn chữ, tiêu đề giá, cam kết nào trên màn hình xem trước của UX Builder để gõ lại nội dung bạn muốn.

### 2. Thay đổi Hình ảnh:
- Mặc định các icon sử dụng Google Material Symbols (tải nhanh, sắc nét chuẩn vector).
- Nếu muốn đổi logo hoặc thêm hình ảnh thực tế học viên / xe tập:
  - Chọn phần tử `[ux_image]`.
  - Bấm **Change Media / Select Image** và tải ảnh thật từ máy tính lên Thư viện WordPress.
  - Lưu ý điền thẻ **Alt** cho ảnh (ví dụ: `alt="học lái xe ô tô B2 tphcm"`) để chuẩn SEO.

### 3. Tùy chỉnh Nút bấm & Liên kết (Links):
- Để đổi số điện thoại hotline: Tìm số `0909 123 456` và `tel:0909123456` đổi thành số thật của bạn.
- Để trỏ nút về form: Để nguyên link `#dang-ky-form`.

---

## BƯỚC 4: TỐI ƯU SEO & GOOGLE RICH SNIPPET
1. Thẻ H1 duy nhất đã được đặt ở **Khối 1** (Hero Banner) với từ khóa chính.
2. Các thẻ H2, H3 được phân bổ chuẩn phân cấp ngữ nghĩa (Semantic HTML5).
3. Mở tệp [`schema-seo.json`](file:///c:/Users/HOANG%20SANG/Downloads/stitch_landing_page_h_c_l_i_xe/schema-seo.json):
   - Nếu bạn dùng **Rank Math SEO** hoặc **Yoast SEO**: Vào phần cài đặt Schema của trang và dán mã JSON-LD này vào.
   - Hoặc cài plugin **Insert Headers and Footers** và dán đoạn mã kẹp trong thẻ `<script type="application/ld+json"> ... </script>` vào phần Header của trang.

Chúc bạn có một Landing Page đào tạo lái xe siêu đẹp, tốc độ tải trang nhanh và tối đa tỉ lệ chuyển đổi học viên!

