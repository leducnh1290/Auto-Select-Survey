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


### Giải thích về code

1. **Kiểm tra URL**: Công cụ chỉ hoạt động trên trang khảo sát sinh viên của HUTECH. Nếu URL không đúng, nó sẽ dừng và hiển thị cảnh báo.
2. **Chọn câu trả lời**: Công cụ yêu cầu người dùng nhập một số từ 1 đến 5 để chọn mức độ hài lòng, sau đó tự động chọn câu trả lời tương ứng trong form khảo sát.
3. **Lưu kết quả**: Sau khi chọn câu trả lời, công cụ tìm nút "Lưu kết quả" và nhấn nút này để hoàn tất quá trình khảo sát.

### Lưu ý

- Công cụ này chỉ hoạt động trên trang khảo sát của HUTECH, vì vậy nếu bạn sử dụng nó trên trang khác, nó sẽ không hoạt động đúng cách.

