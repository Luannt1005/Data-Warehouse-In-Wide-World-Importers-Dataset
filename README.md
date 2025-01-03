# README: Data Warehouse for Wide World Importers (WWI)

## Mô tả Dự án

Dự án này tập trung vào việc xây dựng Kho Dữ liệu (Data Warehouse) từ module Sales của bộ dữ liệu **Wide World Importers**. Mục tiêu chính là chuyển đổi dữ liệu từ các nguồn khác nhau thành một hệ thống kho dữ liệu chất lượng cao, sẵn sàng cho việc phân tích và báo cáo.

Chúng tôi sử dụng các công cụ như **SQL Server**, **SQL Server Integration Services (SSIS)** và **Power BI** để thực hiện các quy trình **Extract, Transform, Load (ETL)** một cách hiệu quả và trực quan hóa dữ liệu qua các dashboard hỗ trợ ra quyết định.

---

## Nội dung Chính

### 1. Tổng quan Dự án
- Đánh giá tình hình kinh doanh hiện tại.
- Đặt ra các câu hỏi trọng tâm về doanh thu, sản phẩm bán chạy, và phân tích khách hàng.

### 2. Nghiên cứu Liên quan và Cơ sở Lý thuyết
- Áp dụng lý thuyết về **Data Warehouse** và phương pháp **ETL**.
- Tham khảo các nghiên cứu liên quan.

### 3. Phân tích Yêu cầu Kinh doanh
- Xác định các yêu cầu kinh doanh và dữ liệu cần thiết để đáp ứng chúng.

### 4. Xây dựng Kho Dữ liệu và Tích hợp Dữ liệu
- Thiết kế schema dạng **Star Schema**, thực hiện các bước **ETL** với **SSIS**.
- Quản lý lịch sử dữ liệu với **Slowly Changing Dimensions (SCD)** loại 1 và 2.

### 5. Phân tích và Đề xuất Kinh doanh
- Tạo các báo cáo và dashboard với **Power BI** để trả lời các câu hỏi kinh doanh cụ thể.

---

## Công cụ Sử dụng

- **Microsoft SQL Server**: Quản lý dữ liệu và viết câu lệnh SQL để xử lý ETL.
- **SSIS**: Tự động hóa quy trình ETL và tích hợp dữ liệu từ nhiều nguồn.
- **Power BI**: Tạo báo cáo và dashboard trực quan.

---

## Hướng Dẫn Sử Dụng

### 1. Chuẩn Bị Dữ Liệu
- Sử dụng **SQL Server** để tải dữ liệu từ các bảng liên quan trong bộ dữ liệu **Wide World Importers**.
- Tích hợp và làm sạch dữ liệu qua **SSIS**, lưu kết quả vào các bảng **staging** và **dimension**.

### 2. Thiết Kế và Tích Hợp Dữ Liệu
- Xây dựng mô hình **Star Schema**, bao gồm các bảng **Fact** và **Dimension**.
- Áp dụng quy trình **ETL**, đảm bảo dữ liệu nhất quán và phù hợp với mục tiêu phân tích.

### 3. Phân Tích và Báo Cáo
- Sử dụng **Power BI** để tạo các báo cáo, dashboard trực quan dựa trên dữ liệu trong kho.

---

## Kết quả Dự Án

- **Tổng doanh thu**: 172.26M.
- **Tỷ lệ lợi nhuận**: 49.8%.
- Các sản phẩm bán chạy và khách hàng tiềm năng được nhận diện qua báo cáo.

---

