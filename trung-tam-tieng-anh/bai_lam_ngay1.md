# BÀI LÀM – ÔN TẬP NGÀY 1

- **Họ tên:** Nguyễn Đức Tài
- **Lớp:** Công nghệ thông tin 2
- **Link repository:** 
- **Hệ điều hành (Windows/macOS):** Windows

## Phần A. Tổ chức thư mục bằng GUI

> Phần A được chấm qua kết quả B1 (tên thư mục gốc) và kết quả liệt kê toàn bộ dự án B8 ở Phần B, không cần ghi thêm ở đây.

## Phần B. Thao tác bằng CLI

### Các lệnh đã chạy (B1–B7)

```shell
pwd
ls -Force
mv lich_hoc.txt docs/
mv logo_trung_tam.png media/
mv anh_lop_hoc.jpg media/
cp media/logo_trung_tam.png archive/
rm temp_201.tmp
rm temp_202.tmp
cd logs
ls
cd ..
cd docs
cp ../media/anh_lop_hoc.jpg ../archive/
cd ..
```

### Kết quả B1 (pwd)

```text
Path
----
C:\Users\Administrator\OneDrive\K26\NMCNTT2\starter-kit\trung-tam-tieng-anh

```

### Kết quả liệt kê toàn bộ dự án – B8 (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

```text
Directory: C:\Users\Administrator\OneDrive\K26\NMCNTT2\starter-kit\trung-tam-tieng-anh

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d----        10/20/2026   3:17 PM                archive
d----        10/20/2026   2:49 PM                data
d----        10/20/2026   3:04 PM                docs
d----        10/20/2026   2:50 PM                logs
d----        10/20/2026   3:05 PM                media
-a---        10/19/2026  10:04 AM             83 .env
-a---        10/19/2026  10:04 AM           1872 access.log
-a---        10/19/2026  10:04 AM            982 bai_lam_ngay1.md
-a---        10/19/2026  10:04 AM           5870 hoc_vien_khoa_3.xlsx


Directory: C:\Users\Administrator\OneDrive\K26\NMCNTT2\starter-kit\trung-tam-tieng-anh\archive

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a---        10/19/2026  10:04 AM          13559 anh_lop_hoc.jpg
-a---        10/19/2026  10:04 AM           5184 logo_trung_tam.png


Directory: C:\Users\Administrator\OneDrive\K26\NMCNTT2\starter-kit\trung-tam-tieng-anh\docs

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a---        10/19/2026  10:04 AM             67 lich_hoc.txt


Directory: C:\Users\Administrator\OneDrive\K26\NMCNTT2\starter-kit\trung-tam-tieng-anh\media

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a---        10/19/2026  10:04 AM          13559 anh_lop_hoc.jpg
-a---        10/19/2026  10:04 AM           5184 logo_trung_tam.png

```

## Tự chấm (điền sau khi có đáp án)

- **Điểm tự chấm:** ..../100
- **Lỗi mình đã mắc và cách sửa:**
