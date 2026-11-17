<div align="center">

# TASL Voice

**Biến kịch bản thành giọng đọc, phụ đề và video — ngay trên máy Windows của bạn.**

[![Tải bản mới nhất](https://img.shields.io/badge/T%E1%BA%A3i%20b%E1%BA%A3n%20m%E1%BB%9Bi%20nh%E1%BA%A5t-Windows%2064--bit-0b6bcb?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/anhql77/tasl-voice-ban-phat-hanh/releases/latest)
[![Hướng dẫn cài](https://img.shields.io/badge/H%C6%B0%E1%BB%9Bng%20d%E1%BA%ABn-C%C3%A0i%20%C4%91%E1%BA%B7t-2e9e5b?style=for-the-badge)](docs/huong-dan/01-cai-dat.md)
[![English](https://img.shields.io/badge/English-README-555?style=for-the-badge)](docs/readme/README.en.md)

Phiên bản mới nhất: **1.3.3** (17/11/2026) — có **Auto Edit**

</div>

---

## TASL Voice làm được gì?

- Đọc kịch bản thành **giọng nói (MP3) và phụ đề (SRT)**.
- Có **thư viện giọng** dùng đi dùng lại, và gán **giọng riêng cho từng nhân vật**.
- Có hàng chờ: **dừng, làm tiếp, làm lại** khi cần.
- Có tín hiệu **kiểm chất lượng** giọng vừa đọc.
- Tăng tốc bằng **card đồ hoạ NVIDIA** trên máy bạn.
- Tự báo khi có bản mới, và có đường **quay về bản cũ** nếu cần.

> Bản 1.3.3 thêm mục **Auto Edit**: nạp nhiều kịch bản một lượt, bấm một nút, máy làm ra video. Xem [Có gì mới ở 1.3.3](#có-gì-mới-ở-133).

## Tải về

1. Bấm nút **Tải bản mới nhất** ở đầu trang.
2. Trong trang mở ra, kéo xuống mục **Assets** và tải tệp cài đặt.
3. Chạy tệp vừa tải và làm theo [hướng dẫn cài đặt](docs/huong-dan/01-cai-dat.md).

## Máy của bạn có hợp không?

| Mục | Cần | Ghi chú |
|---|---|---|
| Hệ điều hành | Windows 10 hoặc Windows 11, 64-bit | |
| Card đồ hoạ | NVIDIA (nên có) | Để chạy nhanh trong thực tế. Chế độ đọc giọng nhanh của bản 1.3.3 cần RTX 30 trở lên |
| Bộ nhớ card đồ hoạ | Từ 8 GB trở lên (nên có) | |
| Ổ đĩa trống | Từ 15 GB trở lên (nên có) | Auto Edit cần thêm khoảng 10 GB cho mỗi video (số ước, chưa đo thật) |
| Mạng | Cần khi cài | |

## Cài từng bước (tóm tắt)

1. Tải tệp cài đặt từ trang [Releases](https://github.com/anhql77/tasl-voice-ban-phat-hanh/releases/latest).
2. Chạy tệp, làm theo các bước trên màn hình.
3. Mở TASL Voice, tạo giọng đầu tiên ở mục **Tạo giọng**.

Chi tiết: [01 - Cài đặt](docs/huong-dan/01-cai-dat.md).

## Có gì mới ở 1.3.3


- **Auto Edit**: nạp nhiều kịch bản một lượt, máy làm ra video MP4 và/hoặc bản nháp CapCut. Một video lỗi thì chỉ video đó dừng, các video khác vẫn chạy.
- **Nhanh hơn** ở khâu đọc giọng (card RTX 30 trở lên), xử lý âm thanh và dựng hình.
- **Hình đều hơn**: mỗi nhân vật có ảnh mẫu làm trước; mỗi kịch bản có một **Key** quyết định thế giới, màu và ánh sáng của ảnh.
- **Sửa từng cảnh** ở bước Duyệt & chỉnh, chỉ dựng lại khúc có cảnh đổi.
- Máy chưa có G-Labs Studio: app hiện nút **«Tải G-Labs Studio»**.

Chi tiết: [Ghi chú phát hành 1.3.3](docs/phat-hanh/v1.3.3.md). Đang dùng bản cũ: [việc cần làm khi lên 1.3.3](docs/huong-dan/06-len-ban-1.3.3.md).

## Hướng dẫn sử dụng

| Bài | Nội dung |
|---|---|
| [01 - Cài đặt](docs/huong-dan/01-cai-dat.md) | Tải, cài, mở lần đầu |
| [02 - Tạo giọng](docs/huong-dan/02-tao-giong.md) | Từ kịch bản ra MP3 + phụ đề |
| [03 - Auto Edit](docs/huong-dan/03-auto-edit.md) | Nạp kịch bản, thiết lập, sản xuất (bản 1.3.3) |
| [04 - Duyệt và chỉnh](docs/huong-dan/04-duyet-va-chinh.md) | Đổi ảnh từng cảnh, dựng lại |
| [05 - Khắc phục lỗi](docs/huong-dan/05-khac-phuc-loi.md) | Khi video báo «Cần xử lý» |
| [06 - Lên bản 1.3.3](docs/huong-dan/06-len-ban-1.3.3.md) | Việc làm một lần trên mỗi máy khi cập nhật |

<details>
<summary><b>Câu hỏi thường gặp</b></summary>

**Có cần tạo giọng trước khi dùng Auto Edit không?** Không. Auto Edit tự tạo giọng. Kịch bản đã có giọng thì máy dùng lại.

**Đọc giọng xong, CapCut chạy chậm?** App giữ bộ nhớ card 30 phút sau khi đọc để bài kế bắt đầu ngay. Đóng TASL Voice là hết.

**Đổi một ảnh có phải dựng lại cả video không?** Không. Máy chỉ dựng lại khúc 10 phút có cảnh đó.

**Auto Edit nhận loại tệp nào?** Tệp kịch bản `.txt` và `.docx`.

**Tắt app giữa chừng có mất việc không?** Không. Phần đã làm được giữ; mở lại app và bấm «Tiếp tục».

</details>

<details>
<summary><b>Kiểm tra tệp tải về</b></summary>

Mã kiểm tra (SHA-256) của từng bản, nếu có, nằm trong ghi chú của bản đó ở trang Releases.

</details>

## Cần giúp?

Xem [SUPPORT.md](SUPPORT.md) và [Lịch sử thay đổi](CHANGELOG.md).

## Về TASL

TASL Voice là mô-đun giọng nói của hệ thống TA Studio Loop (TASL), do YVN Studio phát triển tại Việt Nam.
Trang web: https://tastudioloop.com · Sản phẩm lõi: https://github.com/anhql77/TA-Studio-Loop

> Mã nguồn TASL Voice được giữ riêng. Kho này chỉ dùng để phát hành bản cài và hướng dẫn sử dụng.
