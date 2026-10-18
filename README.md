# Thực hành CSS: flex-basis Property

Bài thực hành minh họa thuộc tính `flex-basis` với các trường hợp:

1. Kích thước cơ sở bằng `px` (`200px`, `100px`, `150px`).
2. `flex-direction: column` để thấy `flex-basis` tác động trên trục chính theo chiều dọc.
3. Giá trị `50%` trong Flex Container.
4. Kết hợp `flex-basis` với `flex-grow` theo tỷ lệ `1:2:1`.
5. So sánh `auto`, `initial` và `inherit`.

## Chạy bài

- Mở `index.html` trực tiếp bằng trình duyệt.
- Hoặc dùng extension Live Server trong VS Code.
- Thay đổi kích thước trình duyệt để xem cách bố cục thích ứng trên màn hình nhỏ.

## File trong thư mục

- `index.html`: cấu trúc HTML và các ví dụ.
- `style.css`: định dạng Flexbox và responsive.
- `screenshots/`: ảnh chụp kết quả trên trình duyệt.

## Ghi chú kiến thức

- Với `flex-direction: row`, main axis là chiều ngang.
- Với `flex-direction: column`, main axis là chiều dọc.
- `flex-basis` xác định kích thước cơ sở; `flex-grow` phân phối không gian dương còn lại và `flex-shrink` có thể làm item co lại khi thiếu chỗ.
- `initial` đặt `flex-basis` về giá trị ban đầu `auto`.
- `inherit` lấy giá trị `flex-basis` từ phần tử cha.
