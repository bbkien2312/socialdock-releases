# SOCIALdock 1.1.1 · Windows x64 · 06/11/2026

- Thêm Cập nhật riêng ở cột trái và tab Hồ sơ & tài khoản với tên gợi nhớ, mã hồ sơ, lựa chọn và quản lý cookie/cache có xác nhận.
- Môi trường có Debug ghi thời gian xử lý và vị trí lỗi đã lọc, cùng cổng Thử nghiệm mặc định tắt. Hiện chưa có tính năng thử nghiệm được đăng ký.
- Source có run.bat dùng thư mục dữ liệu đã lưu, tùy chọn Debug/Thử nghiệm/dữ liệu riêng và log launcher.

Đã kiểm tra trực tiếp EXE bằng hồ sơ/cookie tổng hợp, quyền IPC, lưu chế độ, cô lập thao tác xóa và giao diện ở hai kích thước. Lượt này kiểm tập trung các thay đổi trên EXE. Bộ cài chưa ký số. [GitHub Release v1.1.1](https://github.com/bbkien2312/socialdock-releases/releases/tag/v1.1.1)

# SOCIALdock 1.1.0 · Windows x64 · 06/11/2026

- Hiển thị nơi lưu video, đổi/mở thư mục và đặt lại Downloads của hệ điều hành. Giữ đích của các lượt đã xếp và đường dẫn tệp cũ.
- Thêm kiểm tra bản mới trong Môi trường, xem ghi chú và tải bộ cài có xác minh SHA-256. Windows mở NSIS sau khi app lưu tiến độ và thoát.
- Đã kiểm tra EXE/thư mục tải, cài đè từ 1.0.0 và cập nhật trong app lên bản tổng hợp kế tiếp trên Windows runner. Phiên thử và nơi lưu đã chọn được giữ. Phép thử bộ cài tổng hợp loại dấu Internet trong môi trường thử, người dùng xác nhận thông báo Windows khi cập nhật thật.

Bộ cài chưa ký số. Người dùng 1.0.0 tải bộ cài mới một lần. [GitHub Release v1.1.0](https://github.com/bbkien2312/socialdock-releases/releases/tag/v1.1.0)

# SOCIALdock 1.0.0 · Windows x64

Bản 1.0.0 thêm tạo lịch Reel trên Facebook, lịch sử theo đích và mục Môi trường. Nếu chưa xác minh được lịch sau khi gửi, app giữ trạng thái Chưa xác định để đối chiếu và tránh gửi trùng.

Đã kiểm tra cài, mở và gỡ trên Windows x64 bằng dữ liệu thử. Luồng tạo lịch đã xác nhận trên ba video Facebook thật liên tiếp trong một đợt. Bộ cài chưa ký số. Dùng `SHA256SUMS.txt` để kiểm tra tệp tải về. [GitHub Release v1.0.0](https://github.com/bbkien2312/socialdock-releases/releases/tag/v1.0.0)

# SOCIALdock 0.8.0 beta · 12/09/2026

- Bộ cài mang theo Python, yt-dlp, FFmpeg và ffprobe; dữ liệu nằm ngoài thư mục cài.
- Phân biệt Xóa link, Xóa nguồn và Gỡ hồ sơ khỏi app, có ghi chú phạm vi và tùy chọn riêng xóa dữ liệu website.
- Kiểm tra lại danh sách sau preview, chống bấm lặp và phục hồi thao tác gỡ dở khi khởi động lại.
- Giữ thư viện ZIP, Trực tiếp, Nhập link, bộ lọc, chất lượng và lịch sử tải.
- Sửa nhận lại tệp đã đổi tên khi đường dẫn macOS có alias /var và /private/var.

Chọn đúng file theo hệ điều hành và kiến trúc. SHA256SUMS.txt dùng để kiểm tra tệp tải về. Các bộ cài chưa ký số/notarize; Windows/macOS có thể hiển thị cảnh báo hoặc chặn mở. Kết quả kiểm thử fixture không bảo đảm mọi website hoặc nguồn tài khoản thật đều tải được.

| Bộ cài | Kiểm tra đã đạt |
|---|---|
| windows-x64-setup.exe | App đóng gói, GUI và cài/nâng cấp/gỡ NSIS trên Windows; dữ liệu thử ngoài thư mục cài được giữ |
| linux-x86_64.AppImage | Build và mở app đóng gói trên Ubuntu 22.04 qua Xvfb |
| macos-x64.dmg | Build và mở app đóng gói trên macOS 15 Intel |
| macos-arm64.dmg | Build và mở app đóng gói trên macOS 15 Apple Silicon |

Kiểm thử source gồm typecheck/build, 35 bài Node, 61 bài Python và 11 bộ GUI Windows. Bài gỡ hồ sơ kiểm tra hủy, thay đổi phạm vi, lỗi ghi cấu hình, hoàn tác, cookie giả và phục hồi thao tác dở sau restart. Kiểm thử runner chưa thay thế nghiệm thu các cảnh báo bảo mật hệ điều hành hoặc đăng nhập/tải video từ tài khoản thật.

Người đang dùng bản cũ: dùng Thư mục dữ liệu để chọn đúng thư mục data hiện có. Launcher workspace Windows tiếp tục dùng data tại workspace. Không sao chép cookie giữa máy/hệ điều hành. Gỡ cài đặt giữ data.

Xem README và THIRD_PARTY_NOTICES.md để biết cách dùng, phạm vi dữ liệu và giấy phép thành phần.
