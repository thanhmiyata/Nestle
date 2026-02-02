**Slide 1 – Tiêu đề**
Số hoá và liên thông vận hành nhà máy Nestlé Việt Nam
*Chủ đề: Từ các mảng rời rạc đến hệ thống vận hành số thống nhất*

---

**Slide 2 – Bối cảnh & Thách thức**

* **Quy mô:** Nhà máy Nestlé Bông Sen (~1.000 nhân sự, 10-12 line sản xuất vận hành 24/7).
* **Thực trạng:** Dữ liệu nằm rải rác (Giấy tờ, Excel, hệ thống rời), sự phối hợp giữa các bộ phận phụ thuộc vào liên lạc thủ công.
* **Thách thức:** Với 12 line sản xuất, việc chậm trễ thông tin gây lãng phí nguồn lực và khó truy xuất nguồn gốc.

---

**Slide 3 – Từ "Số hoá rời rạc" đến "Dòng chảy dữ liệu thông suốt"**
*(Thiết kế dạng so sánh Before/After)*

* **Trước đây (Silos):** Mỗi phòng ban dùng một công cụ riêng (Excel, giấy). Dữ liệu bị "đứt gãy" tại các điểm giao.
* **Cách tiếp cận của Team:** Không tập trung số hoá tính năng đơn lẻ. Tập trung thiết kế lại **Dòng chảy vận hành End-to-End**.
* **Giá trị tạo ra:** Một trục dữ liệu chung - nơi dữ liệu của bộ phận này là đầu vào tự động cho bộ phận kia.

---

**Slide 4 – Nền tảng triển khai (The Platform)**

* Trái tim hệ thống: **Microsoft Power Platform** (Power Apps, Power Automate, Power BI).
* **Tính tuân thủ:** Đã được IT tập đoàn Nestlé Global phê duyệt về bảo mật và tiêu chuẩn hạ tầng.
* **Lợi thế:** Triển khai nhanh, linh hoạt theo đặc thù riêng của từng xưởng sản xuất.

---

**Slide 5 – Kiến trúc "Trục vận hành số"**
*(Hình ảnh minh hoạ: Một vòng tròn trung tâm kết nối các phòng ban)*

* **Lớp thu thập:** Mobile App cho nhân viên hiện trường, tích hợp mã vạch (Barcode).
* **Lớp xử lý:** Luồng phê duyệt tự động (Automation).
* **Lớp hiển thị:** Dashboard báo cáo thời gian thực cho Quản lý & Supervisor.

---

**Slide 6 – Luồng liên thông #1: Nguyên liệu & QA (Warehouse ↔ QA ↔ Prodn)**
*(Minh hoạ: Sơ đồ luồng dữ liệu)*

* **Hoạt động:** Quét barcode nhập kho -> Tự động tạo phiếu kiểm định QA -> QA xác nhận trên App -> Nguyên liệu tự động "mở khoá" cho sản xuất.
* **Giá trị:** 100% nguyên liệu được kiểm soát trạng thái trên hệ thống. Loại bỏ rủi ro dùng nhầm nguyên liệu chưa kiểm định.

---

**Slide 7 – Luồng liên thông #2: Theo dõi sản xuất Real-time**
*(Minh hoạ: Một mẫu Dashboard minh hoạ với dữ liệu giả)*

* **Hoạt động:** Supervisor cập nhật tiến độ line ngay tại hiện trường.
* **Giá trị:** Nhìn thấy bức tranh toàn cảnh 12 line đang chạy trên 1 màn hình duy nhất. Không còn chờ đợi báo cáo cuối ca.

---

**Slide 8 – Luồng liên thông #3: Nhân sự & Dịch vụ (HR ↔ Canteen ↔ Bus)**
*(Minh hoạ: Icon con người và sự dịch chuyển dữ liệu)*

* **Hoạt động:** Nhân viên đăng ký tăng ca/nghỉ phép -> Dữ liệu đẩy thẳng đến Bếp ăn và đội Xe đưa đón.
* **Giá trị:** Tối ưu hoá suất ăn và số lượng xe, giảm lãng phí chi phí vận hành từ 5-10%.

---

**Slide 9 – Luồng liên thông #4: Văn hoá An toàn (SHE)**
*(Minh hoạ: Icon cảnh báo và luồng xử lý sự cố)*

* **Hoạt động:** Checklist an toàn số hoá & Gửi cảnh báo mất an toàn (Near-miss) kèm hình ảnh ngay lập tức.
* **Giá trị:** Chuyển từ "ghi chép an toàn" sang "hành động an toàn". Mọi sự cố được theo dõi cho đến khi đóng hẳn.

---

**Slide 10 – Kết quả & Giá trị mang lại (ROI)**

* **Tốc độ:** Giảm thời gian tổng hợp báo cáo và truy xuất dữ liệu từ vài tiếng xuống còn vài phút.
* **Chính xác:** Loại bỏ hoàn toàn sai số do nhập liệu tay và thất lạc giấy tờ.
* **Kết nối:** Xây dựng văn hoá làm việc dựa trên dữ liệu (Data-driven culture).
* **Chi phí:** Tối ưu hoá vận hành và giảm lãng phí tài nguyên nhà máy.

---

**Slide 11 – Khả năng mở rộng & Kết luận**

* Giải pháp mang tính **Module**: Có thể triển khai từng phần hoặc toàn diện.
* Sẵn sàng chuẩn hoá và nhân rộng cho các nhà máy trong cùng hệ thống hoặc các ngành hàng sản xuất khác.
* **Thông điệp:** Chúng tôi không chỉ xây dựng App, chúng tôi xây dựng hệ thống vận hành hiệu quả hơn.
