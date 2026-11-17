# 06 - Lên bản 1.3.3: việc cần làm trên mỗi máy

> Làm một lần cho mỗi máy, khoảng 15 phút. Tên nút trong «…» đúng như chữ trên màn hình.
> Chỉ dùng **«Tạo giọng»** thì làm phần A là đủ. Dùng **«Auto Edit»** thì làm thêm phần B.

## A. Mọi máy

1. **Chờ việc đang chạy xong.** Giọng đang đọc dở thì để đọc xong, hoặc bấm dừng. Hàng chờ và dự án cũ được giữ nguyên khi cập nhật.
2. **Cập nhật.** Khi app báo có bản mới, bấm cập nhật và chờ app mở lại.
3. **Xem card của máy.** Mở Trình quản lý tác vụ (Ctrl + Shift + Esc) → **Hiệu suất** → **GPU**, đọc tên card.
   - **RTX 30, 40, 50:** có chế độ đọc giọng nhanh, không cần bật gì.
   - **Card cũ hơn** (GTX, RTX 20): đọc như bản 1.3.2. Không phải lỗi.
4. **Biết trước: app giữ card 30 phút sau khi đọc xong**, để bài kế bắt đầu ngay. Nếu sau đó mở CapCut thấy chậm hoặc giật, **đóng TASL Voice** rồi mở lại khi cần.
5. **Nếu bạn vẫn tạo bộ prompt ảnh ở «Tạo giọng»:**
   - Mỗi kịch bản phải chọn **Key** trước khi tạo (Farm, Cowboy, Mountain man, Alien, Homeless, hoặc «Khác»). Máy gợi ý sẵn, bạn xác nhận.
   - Số ảnh sẽ **ít hơn trước** (truyện 2 giờ khoảng 250–320 ảnh thay vì hơn 1 500). Muốn như cũ: mở hộp «Tạo bộ prompt ảnh», tích lại ô **«Mỗi khối giọng một ảnh»**. Máy nhớ lựa chọn.

## B. Máy dùng Auto Edit

6. **Cài G-Labs Studio.** Máy chưa có thì màn Auto Edit hiện nút **«Tải G-Labs Studio»**: bấm để mở trang tải chính thức, cài, rồi bấm **«Kiểm tra lại»**.
7. **Mở G-Labs Studio và đăng nhập** các tài khoản tạo ảnh của bạn. Để G-Labs mở suốt lúc Auto Edit chạy.
8. **Khai số tài khoản G-Labs.** Gõ **đúng số tài khoản bạn đang đăng nhập** (mặc định là 1). Khai nhiều hơn thật thì máy gửi quá nhanh, G-Labs dễ báo lỗi hoặc tạm khoá.
9. **Nối «Kết nối AI».** Trong TASL Voice mở **«Kết nối AI»**, nối một dịch vụ AI chữ. Máy đã nối từ trước thì không cần làm lại.
10. **Chờ phần dựng video tải xong.** Lần đầu vào Auto Edit, app tự tải phần dựng video. Nút **«Bắt đầu sản xuất»** sáng lên khi tải xong.
11. **Kiểm CapCut.** Muốn nhận bản nháp CapCut thì dùng CapCut **9.7** hoặc **9.8**.
12. **Chừa ổ đĩa.** Khoảng 10 GB trống cho mỗi video (số ước). Nên chọn **«Nơi lưu»** ở ổ còn rộng.
13. **Lần đầu bấm «Bắt đầu sản xuất», máy hỏi một câu:** có đồng ý gửi **chữ của kịch bản** cho AI để chia cảnh không. Giọng đọc và tệp âm thanh không gửi đi. Xem ảnh ở [03 - Auto Edit](03-auto-edit.md#lần-đầu-máy-hỏi-một-câu).

## C. Thử nhanh sau khi cập nhật

14. Ở **«Tạo giọng»**, đọc thử một kịch bản ngắn (vài phút). Có MP3 và phụ đề là được.
15. Ở **«Auto Edit»**, nạp **một** kịch bản ngắn, chọn Key và giọng, bấm **«Bắt đầu sản xuất»**, xem tới khi báo **«Đã xong»**. Ổn rồi mới chạy cả lô.

## D. Khi có chuyện

| Thấy gì | Làm gì |
|---|---|
| Nút «Bắt đầu sản xuất» mờ | Đọc dòng chữ vàng cạnh nút: nó nói còn thiếu gì |
| Video báo «Cần xử lý» | Xem [05 - Khắc phục lỗi](05-khac-phuc-loi.md) |
| CapCut chậm sau khi đọc giọng | Đóng TASL Voice (xem việc 4) |
| G-Labs báo lỗi liên tục khi tạo ảnh | Kiểm lại số tài khoản đã khai (việc 8); chọn «Tốc độ tạo ảnh» = Bình thường |
| Làm theo mà vẫn không được | Chụp màn hình và gửi theo [SUPPORT.md](../../SUPPORT.md), kèm số bản và tên card |
