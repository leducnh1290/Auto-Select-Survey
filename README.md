# Auto Select Survey Tool For Hutech Student

**Auto Select Survey Tool** là một công cụ tự động giúp sinh viên HUTECH hoàn thành khảo sát giảng viên nhanh chóng bằng cách tự động chọn câu trả lời từ danh sách câu hỏi đánh giá giảng viên trên trang khảo sát của trường. Công cụ này giúp tiết kiệm thời gian cho sinh viên trong việc điền khảo sát.

## Mục Lục

- [Giới Thiệu](#giới-thiệu)
- [Chức Năng](#chức-năng)
- [Cách Cài Đặt](#cách-cài-đặt)
- [Cách Sử Dụng](#cách-sử-dụng)
- [Liên Hệ](#liên-hệ)

## Giới Thiệu

Công cụ **Auto Select Survey Tool** được phát triển để giúp sinh viên HUTECH thực hiện khảo sát giảng viên tự động. Sau khi truy cập vào trang khảo sát, công cụ sẽ yêu cầu người dùng chọn mức độ hài lòng từ 1 đến 5, sau đó tự động điền vào câu trả lời tương ứng và gửi kết quả.

## Chức Năng

- **Chọn câu trả lời tự động**: Sau khi nhập mức độ hài lòng (1-5), công cụ sẽ tự động chọn câu trả lời tương ứng trong biểu mẫu khảo sát.
- **Tự động nhấn nút "Lưu kết quả"**: Sau khi điền câu trả lời, công cụ sẽ tự động tìm và nhấn nút "Lưu kết quả" để hoàn thành khảo sát.
- **Hỗ trợ trang khảo sát của HUTECH**: Công cụ này chỉ hoạt động trên trang khảo sát giảng viên của trường HUTECH.

## Cách Cài Đặt

Công cụ này được triển khai dưới dạng một tiện ích mở rộng cho Chrome (Chrome Extension).

### Các Bước Cài Đặt

1. **Clone repository** (hoặc tải mã nguồn từ GitHub):
   ```bash
   git clone https://github.com/hutech/auto-select-survey.git


Nếu bạn mới chỉ đến bước **Clone repository**, dưới đây là các bước tiếp theo để cài đặt và sử dụng tool **Auto Select Survey Tool** trên Chrome.

## Tiếp theo sau khi Clone Repository

### 1. Tải Mã nguồn về
Sau khi clone repository, bạn cần tải mã nguồn từ GitHub về máy tính của mình.

```bash
git clone https://github.com/hutech/auto-select-survey.git
```

Lệnh này sẽ tạo một thư mục `auto-select-survey` trên máy tính của bạn chứa toàn bộ mã nguồn của công cụ.

### 2. Cài Đặt Extension vào Chrome

1. **Mở Chrome** và vào trang [Extensions](chrome://extensions/).
2. **Bật chế độ Developer Mode**: Ở góc phải trên cùng của trang Extensions, bật **Developer mode** (Chế độ nhà phát triển).
3. **Chọn "Load unpacked"**: Sau khi bật Developer Mode, nhấn nút **Load unpacked**.
4. **Chọn thư mục chứa mã nguồn**:
   - Chọn thư mục `auto-select-survey` mà bạn vừa tải về trong bước trước.
   - Thư mục này chứa các file của tiện ích mở rộng Chrome mà bạn sẽ cài vào trình duyệt.

Sau khi thực hiện các bước trên, tiện ích sẽ được cài vào Chrome và xuất hiện trên thanh công cụ của trình duyệt.

### 3. Cách Sử Dụng Extension

1. **Mở trang khảo sát sinh viên**:
   - Truy cập vào trang khảo sát sinh viên của HUTECH (ví dụ: `https://hutech.edu.vn/khao-sat-sinh-vien/phieu-khao-sat-detail/...`).
   
2. **Kích hoạt tiện ích**:
   - Khi trang khảo sát đã tải xong, nhấp vào biểu tượng tiện ích trên thanh công cụ của Chrome.
   - Tiện ích sẽ yêu cầu bạn nhập mức độ hài lòng từ 1 đến 5, và tự động điền câu trả lời vào form khảo sát.
   
3. **Hoàn thành khảo sát**:
   - Sau khi bạn chọn mức độ hài lòng (ví dụ: 3 - Phân vân), công cụ sẽ tự động đánh dấu câu trả lời và nhấn nút "Lưu kết quả" để gửi khảo sát.

### 4. Các Cập Nhật & Bảo Trì

- **Cập nhật**: Nếu có thay đổi hoặc cập nhật mới từ repository, bạn có thể cập nhật mã nguồn của công cụ bằng cách sử dụng lệnh `git pull` trong thư mục `auto-select-survey`:

   ```bash
   git pull origin main
   ```

- **Sửa lỗi**: Nếu bạn phát hiện bất kỳ lỗi nào trong quá trình sử dụng, bạn có thể báo cáo qua GitHub Issues hoặc liên hệ với nhóm phát triển để khắc phục.

### 5. Liên Hệ & Hỗ Trợ

- **Email hỗ trợ**: leducanh1290@gmail.com
- **Trang web HUTECH**: [HUTECH Official](https://www.hutech.edu.vn)
- **Facebook tác giả**: [Lê Đức Anh (Cà Chua)](https://facebook.com/leducanh1290)

---

Giờ đây, bạn đã hoàn tất việc cài đặt và sử dụng công cụ tự động chọn câu trả lời khảo sát cho HUTECH.

