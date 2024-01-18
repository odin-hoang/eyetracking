# Đồ án môn học: Xử lý ảnh và ứng dụng (CS406.O11)

> Xây dựng website đọc sách thông minh thông qua chuyển động của mắt.

## Danh sách thành viên

| MSSV     | Họ và tên             |
| -------- | --------------------- |
| 21520952 | Hoàng Quang Khải      |
| 21520486 | Nguyễn Đình Minh Toàn |
| 21520705 | Nguyễn Thành Đạt      |

## Live demo

Bản demo có sẵn trên nền web tại:  
[Smart Reading App](https://eyetracking-ruddy.vercel.app)

## Cài đặt trên localhost

### Hướng dẫn cài đặt:

Để chạy ứng dụng trên localhost, thực hiện các bước sau:

1. Clone repository từ github

```bash
git clone https://github.com/khaifade/eyetracking
```

2. Mở trang web trong trình duyệt bằng cách mở tệp `index.html`

### Hiệu chỉnh mô hình:

Sau khi cài đặt thành công, **cho phép mở camera** và chờ mô hình nhận diện khuôn mặt, sau đó hiệu chỉnh bằng cách click vào điểm màu xanh trên màn hình cho đến khi biến mất hoàn toàn.

> Việc click vào điểm màu xanh là để làm dữ liệu đầu vào cho mô hình dự đoán đồng tử và ánh xạ toạ độ màn hình, _độ chính xác của mô hình sẽ tương đối cao sau quá trình hiệu chỉnh._

### Tải file PDF và sử dụng ứng dụng đọc sách thông minh

Sau khi hiệu chỉnh có thể tải file PDF lên và sử dụng ứng dụng đọc sách thông minh chỉ bằng chuyển động mắt.

## Tham khảo

```
@inproceedings{papoutsaki2016webgazer,
	author     = {Alexandra Papoutsaki and Patsorn Sangkloy and James Laskey and Nediyana Daskalova and Jeff Huang and James Hays},
	title      = {{WebGazer}: Scalable Webcam Eye Tracking Using User Interactions},
    booktitle  = {Proceedings of the 25th International Joint Conference on Artificial Intelligence (IJCAI-16)},
    pages      = {3839--3845},
	year       = {2016},
	organization={AAAI}
	}
```
