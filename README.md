# Đồ án học máy sử dụng Apache Spark ML và SparkSQL

### Thành viên thực hiện:

| **STT** | **Họ tên**      | **MSSV** | **Ghi chú** |
| ------------- | ----------------------- | -------------- | ------------------ |
| 1             | Nguyễn Quốc Lân      | 21110837       | Nhóm trưởng     |
| 2             | Đinh Đại Hải Đăng | 21110164       |                    |
| 3             | Bùi Quốc Khang        | 21110202       |                    |
| 4             | Đặng Kim Thành       | 21110298       |                    |

### Mô tả

Trong đồ án này, nhóm sử dụng Apache Spark để thực hiện những công việc sau:

- SparkSQL: Dùng để nhập dữ liệu, khám phá dữ liệu, làm sạch dữ liệu
- SparkML: Dùng để chuẩn bị dữ liệu và xây dựng pipeline, huấn luyện mô hình, đánh giá kết quả và hiệu chỉnh mô hình

### Mô hình huấn luyện

Mô hình huấn luyện với mục đích giải quyết bài toán phân loại, cụ thể là để dự đoán chuyến bay có bị trễ khi đáp xuống hay khôngMô hình có đầu vào và đầu ra như sau:

- Đầu vào: Gồm 6 giá trị `(DayOfMonth: INTEGER, DayOfWeek: INTEGER, Carrier: STRING, OriginAirportID: INTEGER, DestAirportID: INTEGER, DepDelay: INTEGER)`
- Đầu ra: 1 giá trị `label: INTEGER` cho biết chuyến bay có đáp trễ hay không, trong đó `1: đáp trễ, 0: không trễ`

### Yêu cầu

`pyspark == 3.4.0`
