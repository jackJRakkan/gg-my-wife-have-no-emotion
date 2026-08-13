# Thư mục ảnh

Mỗi ảnh sẽ được đặt trong một thư mục riêng dưới `images/`.
Cấu trúc đề xuất:

images/
  └─ 01-avatar/
      ├─ avatar.png        # (hoặc .jpg/.webp) - file ảnh chính
      ├─ README.md         # mô tả ảnh, nguồn, bản quyền, tag
      └─ metadata.json     # (tùy chọn) metadata về ảnh

Hướng dẫn nhanh:
- Đặt mỗi ảnh vào thư mục riêng (ví dụ `01-avatar/`, `02-scene/`, ...).
- Trong mỗi thư mục ảnh, lưu file ảnh (ví dụ `image.png`) và một `README.md` mô tả tác giả, ngày, và giấy phép.
- Nếu muốn giữ thư mục trống qua Git, thêm file `.gitkeep`.

Nếu bạn muốn, tôi có thể: 
- Tải ảnh bạn vừa gửi vào một thư mục con (ví dụ `images/01-avatar/avatar.png`).
- Tạo nhiều thư mục mẫu nữa.

