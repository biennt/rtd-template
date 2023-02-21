# Cài đặt các công cụ để viết tài liệu
## Cài đặt python
Download bộ cài cho Windows tại đây: 
https://www.python.org/ftp/python/3.11.2/python-3.11.2-amd64.exe

Khi cài, có thể thay đổi một số thiết lập như "Add python.exe to PATH", "Install for all users", cài đặt vào thư mục khác như "C:\Python311"

## Cài đặt git
Download bộ cài cho Windows tại đây:
https://git-scm.com/download/win

(tạo tài khoản trên github.com, về sau sẽ cần khi đẩy tài liệu, mã nguồn lên đó)

## Cài đặt sphinx

Mở Windows Terminal (cmd) và gõ lệnh:

```pip install sphinx```

```pip install sphinx_rtd_theme```

# Bắt đầu viết tài liệu
## Khởi tạo cấu trúc thư mục cho hệ thống tài liệu mới
Mở Windows Terminal (cmd) và gõ lệnh:

```sphinx-quickstart```

## Clone từ hệ thống tài liệu có sẵn
## Tạo tài liệu html
Sau khi soạn tài liệu xong, mở Windows Terminal (cmd) và gõ lệnh:

```make html```

Mở thư mục build/html để xem các file kết quả
