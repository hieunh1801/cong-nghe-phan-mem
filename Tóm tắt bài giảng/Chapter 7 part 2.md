## II - Detaited Design
- 
- Mức độ chi tiết?
VD: Tên hàm, tham số đầu vào, đầu ra
--> Chi tiết hơn: chỉ ra cả phần logic của hàm
- Mức độ hình thức

### 1. Functional decomposition[phân rã]
- Áp dụng cho các chương trình viết dưới dạng thủ tục.
+ Có 1 hàm main, trong main gọi các funtion khác
- Phân rã module thành các chức năng con

### 2. Relational Database Design
- Relations (tables)
+ Two-dimensional[chiều] (row and column)
#### 2.1 - Các bước thiết kế CSDL
- Mô hình hóa ở bước khái niệm => kết quả là Diagram
- Thiết kế logic. 
- Thiết kế vật lý. Chuẩn hóa dữ liệu. Đôi khi chấp nhận việc dư thừa dữ liệu
- Triển khai và bảo trì: ổ đĩa nào để lưu trữ CSDL, Điều chỉnh các chỉ mục để tiện cho việc lưu trữ
#### 2.2 - OO design - thiết kế hướng đối tượng
- Xây dựng mô hình USE case __(*)__
- Thiết kế các lớp. UML class Digaram __(*)__
- Quan hệ liên kết: Association,
- Quan hệ cấu thành - composition: một lớp là thành phần hay thuộc tính của đối tượng lớp còn lại
VD: Class Address là một phần của class student
- Quan hệ thừa kế: Inheritance.
- Mô hình trạng thái - thể hiện sự thay đổi trạng thái của đối tượng của một lớp nào đó. Rất có ích khi viết test case, để không bỏ lỡ trạng thái của nó.
VD: __State Diagram__
- Mô hình tương tác:__(*)__ thể hiện sự tương tác giữa các đối tượng trong một USE case để thực hiện được một mục tiêu của một use case.
VD: __UML Sequence diagrams__

#### 2.4: UI design
- Quyết định sự thành công của phần mềm
- Là phần mà người dùng có thể đánh giá được phần mềm
- Quan tâm tới các điều sau
+ Luồng tương tác giữa người dùng và hệ thống
+ Nhìn và cảm nhận

- Kiểu giao diện
+ Command-line
+ Text Menus
+ GUI

- Mô hình tiêu biểu GOMs
+ Mục tiêu
+ Thao tác
+ Phương pháp
+ Thao tác lựa chọn

- Heuristics - tri thức kinh nghiệm
- Consistency: Thống nhất - giữa các nền tảng
- User in control: người dùng điều khiển ở thế chủ động
- Reducing memory load: một màn hình thì không nên quá nhiều thông tin
- System status visible: hiển thị trạng thái của hệ thống.

