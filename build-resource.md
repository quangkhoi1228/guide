---
description: >-
  Build resource là một phần liên quan đến việc tăng trải nghiệm người dùng ở
  phía giao diện
---

# Build resource

## Giới thiệu

### Lý do&#x20;

Khi tải trang, website luôn luôn tải về các resource tĩnh như JS, CSS, image, ... và tốc độ tải trang phụ thuộc vào tốc độ tải các file này có nhanh hay không. Ngoài các vấn đề như tốc độ mạng, độ mạnh của máy tính chúng ta không thể thay đổi thì kích thước của các file này là 1 trong những thứ chúng ta có thể can thiệp và tối ưu.&#x20;

### Nguyên lý tối ưu

* Loại bỏ các khoảng trắng, xuống dòng&#x20;
* Chuyển đổi các đoạn code dài thành các đoạn code ngắn hơn nhưng có cùng tác dụng
* Phân code các module code nhỏ hơn và chỉ load những module cần thiết cho trang

## Setup build resource

_Xem thêm_ [_cấu trúc project_](setup-project/cau-truc-project.md) _thư mục `static` để hiểu rõ các folder trước khi vào mục này_

__