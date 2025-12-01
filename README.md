# HƯỚNG DẪN TẠO VÀ CÀI ĐẶT BẢN QUYỀN WINRAR

## I. CÁCH TẠO KEY (SỬ DỤNG GITHUB ACTIONS)

**1. Fork dự án:**
* Nếu đã có file `rarreg.key` thì chuyển sang bước 2.
* Truy cập repository gốc theo link sau: [https://github.com/bitcookies/winrar-keygen](https://github.com/bitcookies/winrar-keygen)
* [cite_start]Nhấn nút "Fork" để tạo bản sao về tài khoản của bạn[cite: 463].

**2. Bật Workflows:**
* Vào tab "Actions" trong repository đã Fork.
* [cite_start]Nhấn nút xác nhận để cho phép chạy Workflows[cite: 464].

**3. Chạy trình tạo Key:**
* Chọn mục "WinRAR Keygen" ở menu bên trái.
* Nhấn "Run workflow".
* [cite_start]Nhập "Name" (Tên người dùng) và "License Type" (Loại giấy phép)[cite: 461].
* Nhấn nút "Run workflow" màu xanh để bắt đầu.

**4. Tải file kết quả:**
* Chờ quá trình chạy hoàn tất (có dấu tích xanh).
* Nhấn vào tên lần chạy (Workflow run).
* [cite_start]Kéo xuống mục "Artifacts" và tải file về máy[cite: 461].

---

## II. CÁCH CÀI ĐẶT (IMPORT) KEY VÀO WINRAR

Sau khi giải nén file tải về, bạn sẽ có file `rarreg.key` hoặc `rarkey.rar`. Hãy chọn 1 trong 3 cách sau để kích hoạt:

### CÁCH 1: KÉO THẢ (NHANH NHẤT)
* Mở phần mềm WinRAR lên.
* [cite_start]Kéo file `rarreg.key` (hoặc `rarkey.rar`) và thả trực tiếp vào cửa sổ WinRAR[cite: 457].
* Nhấn **OK** nếu có thông báo xác nhận.

### CÁCH 2: TỰ ĐỘNG (DÀNH CHO FILE .RAR)
* [cite_start]Nếu bạn nhận được file `rarkey.rar`, chỉ cần nhấp đúp (double-click) vào file này[cite: 458].
* WinRAR sẽ tự động nhận diện và cài đặt giấy phép.

### CÁCH 3: CHÉP THỦ CÔNG (NẾU CÁCH 1 KHÔNG ĐƯỢC)
* Copy file `rarreg.key`.
* Dán (Paste) file này vào đường dẫn thư mục sau:
    ```
    C:\Users\<Tên_User_Của_Bạn>\AppData\Roaming\WinRAR\rarreg.key
    ```
    [cite_start][cite: 460].
* *(Lưu ý: Bạn cũng có thể dán vào thư mục cài đặt gốc, thường là `C:\Program Files\WinRAR`)*.

---

### Kiểm tra
Mở WinRAR -> Chọn menu **Help** -> **About WinRAR** để xem kết quả.
