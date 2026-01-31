# CASE STUDY

## Số hoá và kết nối vận hành nhà máy Nestlé Bông Sen – Hưng Yên

### Thông tin chung

* **Khách hàng**: Nestlé Việt Nam
* **Nhà máy**: Nestlé Bông Sen – Hưng Yên
* **Quy mô**: ~1.000 nhân sự
* **Sản xuất**: 10–12 line sản xuất vận hành song song
* **Vai trò của bên team của Thành**:
  Thiết kế và triển khai **hệ thống số hoá vận hành nội bộ**, tập trung vào **kết nối dòng chảy dữ liệu giữa các phòng ban**, không chỉ số hoá từng bộ phận riêng lẻ.

---

## 1. Bài toán thực tế trước dự án

Trước khi triển khai dự án, nhà máy Nestlé Bông Sen vận hành theo mô hình quen thuộc của nhiều nhà máy lớn:

* **Kế hoạch sản xuất**, **kho**, **QA**, **HR**, **SHE** hoạt động theo từng mảng riêng
* Nhiều quy trình vẫn xử lý bằng **giấy tờ, file rời, hoặc nhập tay**
* Dữ liệu nằm rải rác:

  * giấy tờ
  * Sharp
  * Office 365
* Việc tổng hợp báo cáo phụ thuộc rất nhiều vào **con người và kinh nghiệm cá nhân**

Ở quy mô **10–12 line sản xuất**, các vấn đề bắt đầu lộ rõ:

* Thông tin chậm
* Khó truy vết
* Quản lý khó có cái nhìn tổng thể theo thời gian thực
* Mỗi phòng ban àm đúng phần mình nhưng không nhất quán trên toàn hệ thống => xung đột, mất thời gian

---

## 2. Những điểm gãy trong dòng chảy vận hành

Một số tình huống thực tế diễn ra hằng ngày:

* **Kế hoạch sản xuất thay đổi**, nhưng **warehouse không nắm kịp nhu cầu nguyên liệu**
* **QA kiểm định xong**, nhưng kết quả **không gắn chặt với lô nguyên liệu và line sản xuất**
* **Supervisor** muốn biết tình trạng sản xuất:
  → phải hỏi từng bộ phận
  → tổng hợp thủ công
  → chỉ có báo cáo sau ca
* **HR và SHE** xử lý thủ tục, checklist, cảnh báo an toàn:
  → chủ yếu bằng giấy
  → khó theo dõi trạng thái xử lý

👉 Vấn đề cốt lõi **không nằm ở từng phòng ban**, mà nằm ở việc **thiếu một trục dữ liệu chung cho toàn bộ vận hành nhà máy**.

---

## 3. Cách tiếp cận của bên anh / đội Thành

Bên anh **không chọn cách số hoá từng phòng ban độc lập**.

Thay vào đó:

* Thiết kế lại **dòng chảy vận hành end-to-end** của nhà máy
* Xác định các **điểm giao giữa các bộ phận**:

  * Kế hoạch sản xuất ↔ Warehouse
  * Warehouse ↔ QA
  * QA ↔ Production
  * Production ↔ Supervisor / Quản lý
* Xây dựng **một hệ thống chung**, trong đó:

  * mỗi bộ phận làm đúng nghiệp vụ của mình
  * nhưng dữ liệu được **liên thông và kế thừa**

---

## 4. Những gì đã được triển khai (theo dòng chảy thực tế)

### 4.1. Từ kế hoạch sản xuất đến kho

* Khi lập kế hoạch sản xuất:

  * hệ thống phản ánh ngay **nhu cầu nguyên liệu**
* Warehouse:

  * nhập hàng & xác nhận bằng **barcode**
  * kiểm tồn kho bằng quét barcode, **không còn đếm tay**
  * quản lý vị trí lưu trữ trên **warehouse map**
  * biết rõ:

    * hàng đang ở đâu
    * phục vụ line nào
    * ngày nhập, hạn sử dụng

👉 Kho không còn là bộ phận “ghi chép”, mà trở thành **nguồn dữ liệu phục vụ sản xuất và QA**.

---

### 4.2. QA gắn chặt với kho và sản xuất

* Mỗi lượt kiểm định:

  * gắn trực tiếp với **lô nguyên liệu** trong kho
  * và **mẻ sản xuất** cụ thể
* Kết quả QA không còn là hồ sơ rời
* Khi cần truy vết:
  → có thể đi ngược từ thành phẩm → mẻ sản xuất → nguyên liệu

---

### 4.3. Theo dõi sản xuất & supervisor

* Supervisor theo dõi được:

  * tình trạng từng line trong **10–12 line**
  * tiến độ, công suất theo thời gian gần realtime
* Không cần đợi báo cáo cuối ca
* Không cần hỏi từng bộ phận

👉 Vai trò supervisor chuyển từ “tổng hợp thủ công” sang **theo dõi và điều phối**.

---

### 4.4. HR & SHE bám theo vận hành thực tế

* HR:

  * đăng ký OT, nghỉ phép, xe đưa đón
  * dữ liệu tự động liên thông với bếp & hệ thống xe
* SHE:

  * checklist kiểm tra an toàn theo khu vực
  * tạo phiếu cảnh báo mất an toàn
  * nhân viên trong nhà máy có thể chủ động báo cáo
* Trạng thái xử lý được theo dõi tập trung

---

## 5. Kết quả thực tế sau triển khai

Những thay đổi **nhìn thấy được trong vận hành hằng ngày**:

* Không còn:

  * kiểm kho bằng đếm tay
  * QA ghi chép rời rạc
  * tổng hợp báo cáo thủ công cuối ca
* Các bộ phận:

  * làm việc trên **cùng một hệ thống**
  * dùng chung dữ liệu
* Quản lý:

  * nhìn được bức tranh tổng thể của **10–12 line sản xuất**
  * truy vết được luồng:
    **nguyên liệu → sản xuất → QA → thành phẩm**
* Giảm phụ thuộc vào:

  * giấy tờ
  * kinh nghiệm cá nhân
* Tăng khả năng:

  * kiểm soát
  * truy vết
  * ra quyết định

---

## 6. Giá trị cốt lõi của dự án

Dự án **không đơn thuần là số hoá từng quy trình**.

Giá trị lớn nhất là:

> **Biến vận hành nhà máy từ các mảng rời rạc
> thành một hệ thống liên mạch, có thể quan sát và kiểm soát.**

Bên team của Thành đóng vai trò:

* **kiến trúc sư hệ thống vận hành số**
* kết nối các phòng ban
* thiết kế lại cách nhà máy vận hành trên dữ liệu

---

## 7. Kết luận

Case Nestlé Bông Sen cho thấy:

* Ở quy mô nhà máy FMCG lớn (~1.000 nhân sự, 10–12 line),
* vấn đề không nằm ở từng phòng ban làm tốt hay không,
* mà nằm ở việc **toàn bộ hệ thống có vận hành như một thể thống nhất hay không**.