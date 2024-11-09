# Auto Select Survey Tool For Hutech Students

**Auto Select Survey Tool** là một công cụ tự động giúp sinh viên HUTECH hoàn thành khảo sát giảng viên nhanh chóng bằng cách tự động chọn câu trả lời từ danh sách câu hỏi đánh giá giảng viên trên trang khảo sát của trường. Công cụ này giúp tiết kiệm thời gian cho sinh viên trong việc điền khảo sát.

## Mục Lục

- [Giới Thiệu](#giới-thiệu)
- [Chức Năng](#chức-năng)
- [Cách Cài Đặt](#cách-cài-đặt)
  - [Cài Đặt Qua Git](#cài-đặt-qua-git)
  - [Cài Đặt Qua ZIP](#cài-đặt-qua-zip)
- [Cách Sử Dụng](#cách-sử-dụng)
- [Cập Nhật & Bảo Trì](#cập-nhật--bảo-trì)
- [Liên Hệ](#liên-hệ)

## Giới Thiệu

Công cụ **Auto Select Survey Tool** được phát triển để giúp sinh viên HUTECH thực hiện khảo sát giảng viên tự động. Sau khi truy cập vào trang khảo sát, công cụ sẽ yêu cầu người dùng chọn mức độ hài lòng từ 1 đến 5, sau đó tự động điền vào câu trả lời tương ứng và gửi kết quả.

## Chức Năng

- **Chọn câu trả lời tự động**: Sau khi nhập mức độ hài lòng (1-5), công cụ sẽ tự động chọn câu trả lời tương ứng trong biểu mẫu khảo sát.
- **Tự động nhấn nút "Lưu kết quả"**: Sau khi điền câu trả lời, công cụ sẽ tự động tìm và nhấn nút "Lưu kết quả" để hoàn thành khảo sát.
- **Hỗ trợ trang khảo sát của HUTECH**: Công cụ này chỉ hoạt động trên trang khảo sát giảng viên của trường HUTECH.

## Cách Cài Đặt

Công cụ này được triển khai dưới dạng một tiện ích mở rộng cho Chrome (Chrome Extension).

### Cài Đặt Qua Git

1. **Clone Mã Nguồn Về**:
   ```bash
   git clone https://github.com/hutech/Auto-Select-Survey.git
   ```
   Lệnh này sẽ tạo một thư mục `Auto-Select-Survey` trên máy tính của bạn chứa toàn bộ mã nguồn của công cụ.

2. **Cài Đặt Extension vào Chrome**:
   - Thực hiện các bước cài đặt tiện ích vào Chrome như hướng dẫn trong phần "Cài Đặt Extension vào Chrome" bên dưới.

### Cài Đặt Qua ZIP

Nếu bạn không muốn sử dụng Git, bạn có thể tải tệp ZIP từ release của repository và giải nén.

1. **Tải Tệp ZIP**:
   - Truy cập vào [Trang Releases trên GitHub](https://github.com/hutech/Auto-Select-Survey/releases).
   - Tải tệp ZIP của phiên bản mới nhất (chọn tệp `.zip`).
   
2. **Giải Nén Tệp**:
   - Giải nén tệp ZIP vào một thư mục trên máy tính của bạn.

3. **Cài Đặt Extension vào Chrome**:
   - Mở Chrome và vào trang [Extensions](chrome://extensions/).
   - Bật chế độ **Developer Mode** (Chế độ nhà phát triển).
   - Chọn **Load unpacked** và chọn thư mục đã giải nén từ tệp ZIP.
   - Sau khi thực hiện, tiện ích sẽ được cài vào Chrome và xuất hiện trên thanh công cụ.

### Cài Đặt Extension vào Chrome

1. **Mở Chrome** và vào trang [Extensions](chrome://extensions/).
2. **Bật chế độ Developer Mode**: Ở góc phải trên cùng của trang Extensions, bật **Developer mode** (Chế độ nhà phát triển).
3. **Chọn "Load unpacked"**: Sau khi bật Developer Mode, nhấn nút **Load unpacked (Tiện ích đã giải nén)**.
4. **Chọn thư mục chứa mã nguồn**:
   - Chọn thư mục `Auto-Select-Survey` mà bạn vừa tải về trong bước trước.
   - Thư mục này chứa các file của tiện ích mở rộng Chrome mà bạn sẽ cài vào trình duyệt.

Sau khi thực hiện các bước trên, tiện ích sẽ được cài vào Chrome và xuất hiện trên thanh công cụ của trình duyệt.

## Cách Sử Dụng Extension

1. **Mở trang khảo sát sinh viên**:
   - Truy cập vào `https://sinhvien.hutech.edu.vn/`
   - Chọn Khảo Sát => Hoạt động giảng dạy => Chọn môn học cần khảo sát.
   - Sau khi chọn môn, link khảo sát có dạng (ví dụ: `https://sinhvien.hutech.edu.vn/#/sinhvien/khao-sat-sinh-vien/phieu-khao-sat-detail/...`).
   
2. **Kích hoạt tiện ích**:
   - Khi trang khảo sát đã tải xong, nhấp vào biểu tượng tiện ích trên thanh công cụ của Chrome và tìm `Auto Select Survey Tool`.
   - Tiện ích sẽ hiện popup hỏi, bạn hãy nhấn vào **OK**.
   - Tiện ích sẽ yêu cầu bạn nhập mức độ hài lòng từ 1 đến 5, và tự động điền câu trả lời vào form khảo sát.
   
3. **Tận Hưởng**:
   - Sau khi bạn chọn mức độ hài lòng (ví dụ: 3 - Phân vân), công cụ sẽ tự động đánh dấu câu trả lời và nhấn nút "Lưu kết quả" để gửi khảo sát.
   - Sau đó, nó sẽ tự động quay lại trang chọn phiếu, bạn chỉ cần chọn phiếu tiếp theo và làm lại từ bước 2.

## Cập Nhật & Bảo Trì

- **Cập nhật**: Nếu có thay đổi hoặc cập nhật mới từ repository, bạn có thể cập nhật mã nguồn của công cụ bằng cách sử dụng lệnh `git pull` trong thư mục `Auto-Select-Survey`:
   ```bash
   git pull origin main
   ```

- **Sửa lỗi**: Nếu bạn phát hiện bất kỳ lỗi nào trong quá trình sử dụng, bạn có thể báo cáo qua GitHub Issues hoặc liên hệ với nhóm phát triển để khắc phục.

## Liên Hệ & Hỗ Trợ

- **Email hỗ trợ**: leducanh1290@gmail.com
- **Facebook tác giả**: [Lê Đức Anh (Cà Chua)](https://facebook.com/leducanh1290)
- **Trang web HUTECH**: [HUTECH Official](https://www.hutech.edu.vn)

---

Chúc may mắn và thành công!
```
