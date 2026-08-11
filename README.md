<div align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/27/Odoo_logo.svg/60px-Odoo_logo.svg.png" width="200" />
  <h1>🏋️‍♂️ Hệ Thống ERP Quản Lý Phòng Gym KOI FITNESS</h1>
  <p><strong>Đồ án môn học: Hệ Hoạch Định Nguồn Lực Doanh Nghiệp (ERP)</strong></p>
</div>

---

## 📖 Giới Thiệu Dự Án
**KOI Fitness** là doanh nghiệp cung cấp dịch vụ thể dục thể hình (Gym & Fitness) phân khúc trung và cao cấp. Dự án này ứng dụng hệ thống **ERP Odoo** nhằm số hóa toàn bộ quy trình vận hành của phòng Gym, giải quyết triệt để các vấn đề của việc quản lý thủ công (bằng Excel/giấy tờ) như: sai sót dữ liệu, đứt gãy luồng thông tin, mất kiểm soát tồn kho và khó khăn trong đối soát tài chính.

🔗 **[Xem Video Demo Hệ Thống Tại Đây](https://youtu.be/yNVPaE0co0Y?si=W4ijCIS272MkdB7o)**


## 🛠 Công Nghệ & Nền Tảng
* **Nền tảng ERP:** Odoo (Phiên bản Enterprise / Community)
* **Mô hình hóa quy trình:** BPMN (Bizagi Modeler / Draw.io)
* **Nghiệp vụ cốt lõi:** Bán hàng (Sales), Chăm sóc khách hàng (CRM), Điểm bán hàng (POS), Kho vận (Inventory), Mua hàng (Purchase), Kế toán (Invoicing).

## 🚀 Các Quy Trình Nghiệp Vụ Cốt Lõi (BPMN)

Dự án đã thực hiện tái cấu trúc quy trình từ **AS-IS** (Thực trạng thủ công) sang **TO-BE** (Ứng dụng Odoo):

### 1. Quản Lý Đăng Ký Hội Viên (CRM & Sales)
* **Quy trình:** Tiếp nhận Lead -> Chăm sóc khách hàng -> Báo giá -> Xác nhận đơn hàng -> Ghi nhận thanh toán.
* **Thực tế:** Tự động kích hoạt thẻ tập và phân công Huấn luyện viên (PT) ngay khi Kế toán ghi nhận thanh toán thành công, loại bỏ thời gian chờ đợi.

### 2. Bán Lẻ Tại Quầy (POS - Point of Sale)
* **Quy trình:** Khách chọn sản phẩm (Nước suối, Phụ kiện, Thực phẩm bổ sung) -> Quét mã vạch -> Thanh toán -> In biên lai.
* **Thực tế:** Hệ thống tự động trừ tồn kho (Inventory) và cộng doanh thu (Accounting) ngay lập tức theo thời gian thực (Real-time), không cần đối soát Excel cuối ca.

### 3. Cung Ứng & Nhập Kho (Purchase & Inventory)
* **Quy trình:** Cảnh báo tồn kho thấp -> Tạo Yêu cầu báo giá (RFQ) -> Xác nhận Đơn mua hàng (PO) -> Nhận hàng -> Đối chiếu hóa đơn -> Thanh toán.
* **Thực tế:** Tồn kho tăng tự động, dòng tiền chi ra khớp với hóa đơn nhà cung cấp, đảm bảo tính minh bạch.

## 📊 Báo Cáo & Thống Kê (Dashboard)
Hệ thống cung cấp Dashboard trực quan cho Ban Giám Đốc giúp ra quyết định nhanh chóng:
* Thống kê doanh thu theo ngày/tháng/năm.
* Phân tích tỷ lệ chuyển đổi Lead (CRM).
* Báo cáo top 5 sản phẩm bán chạy nhất.
* Theo dõi giá trị tồn kho theo từng chi nhánh (Kho chính, Smart, Flagship).

## 💡 Lợi Ích Mang Lại
✔️ **Đồng bộ dữ liệu:** Mọi dữ liệu tập trung trên một nền tảng duy nhất.<br>
✔️ **Tự động hóa (Real-time):** Trừ kho, cộng doanh thu tự động ngay khi có giao dịch.<br>
✔️ **Nâng cao trải nghiệm:** Khách hàng không phải chờ đợi thủ tục rườm rà.<br>
✔️ **Quản trị thông minh:** Số liệu trực quan giúp ra quyết định kinh doanh chính xác.

---
*Dự án được thực hiện trong khuôn khổ môn học Hệ Hoạch Định Nguồn Lực Doanh Nghiệp (Học kỳ III, Năm học 2025-2026).*
