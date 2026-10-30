## 1. Vấn đề là gì?

Danh sách CV chứa số điện thoại và mức lương ứng viên bị chia sẻ nhầm với quyền Editor cho người bên ngoài, gây nguy cơ rò rỉ và chỉnh sửa dữ liệu.

## 2. Yêu cầu là gì?
-   Bảng thiết kế phân quyền cho từng đối tượng tưng ứng
-   Kịnh bản xử lý sự cố , quy trình 3 bước xử lý
## 3. Cách làm ra sao?

### Bảng phân quyền

| Đối tượng | Quyền |
|---|---|
| Trưởng phòng nhân sự | Editor |
| Trưởng các bộ phận | Commenter |
| Nhân viên không liên quan | Không cấp quyền |
| Ứng viên bên ngoài | Không cấp quyền |

### Quy trình xử lý sự cố (3 bước)

**Bước 1: Thu hồi quyền:** Xóa quyền Editor của ứng viên, chuyển chế độ chia sẻ về Restricted.

**Bước 2: Kiểm tra nhật ký:** Xem lịch sử truy cập, chỉnh sửa và tải xuống nếu hệ thống có ghi nhận.

**Bước 3: Khắc phục:** Khôi phục dữ liệu nếu bị sửa đổi, cấp lại quyền phù hợp và sử dụng Suggesting Mode để trưởng bộ phận góp ý.

**Lưu ý:** Thu hồi quyền không thể xóa dữ liệu mà người nhận đã tải xuống hoặc sao chép trước đó.







