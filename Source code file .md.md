# Hướng dẫn cài đặt cảm biến độ ẩm cho trang trại Lan

## 1. Chuẩn bị

Cài đặt Python và kiểm tra phiên bản bằng lệnh `python --version`.

Tên biến `humidity` dùng để lưu độ ẩm đất. Nếu độ ẩm thấp hơn 30%, hệ thống sẽ bật máy bơm.

## 2. Code Python điều khiển máy bơm

```
humidity = 25

if humidity < 30:
    print("Độ ẩm thấp, bật máy bơm")
else:
    print("Độ ẩm ổn định, tắt máy bơm")
```

## 3. Bảng so sánh cảm biến

Tiêu chí

Cảm biến cũ

Cảm biến mới

Độ chính xác

Thấp

Cao

Độ bền

Trung bình

Tốt

Chi phí

Thấp

Cao

Khả năng sử dụng

Cơ bản

Ổn định hơn

## 4. Danh sách kiểm tra thiết bị

-   Kiểm tra cảm biến độ ẩm.
    
-   Kết nối cảm biến với bộ điều khiển.
    
-   Kiểm tra nguồn điện máy bơm.
    
-   Chạy thử chương trình Python.
    
-   Kiểm tra máy bơm hoạt động đúng.
    

## 5. Lưu ý

Ký tự `\*` giúp hiển thị dấu sao mà không biến nó thành định dạng Markdown.

Kết thúc hướng dẫn.
