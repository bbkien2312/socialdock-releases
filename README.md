# SOCIALdock

Thư viện ZIP và trình duyệt trong app để tổ chức liên kết, lọc dữ liệu và tải video từ nguồn bạn có quyền truy cập.

- Windows x64: [Tải SOCIALdock 1.1.2](https://github.com/bbkien2312/socialdock-releases/releases/tag/v1.1.2)
- Linux và macOS: [Tải SOCIALdock 0.8.0 beta](https://github.com/bbkien2312/socialdock-releases/releases/tag/v0.8.0)

Repository này chỉ chứa hướng dẫn và bản phát hành. Source được quản lý trong repository private.

Bản 1.1.2 sửa hộp xác nhận mở bộ cài bị ẩn trên Windows. Người đang dùng 1.1.0 hoặc 1.1.1 chạy bộ cài 1.1.2 trực tiếp một lần để nhận bản sửa updater.

## Chọn bộ cài

- Windows x64: file `windows-x64-setup.exe`.
- Linux x64: file `.AppImage`; cấp quyền thực thi rồi mở.
- macOS: `.dmg` cho Intel (x64) hoặc Apple Silicon (arm64).

Chỉ các hệ điều hành ghi đạt trong release notes mới có file phát hành. Bản chưa ký/notarize được đánh dấu prerelease; có thể gặp SmartScreen/Gatekeeper. SHA256SUMS xác minh file, không thay chữ ký số.

Các bộ cài kèm Python, yt-dlp, FFmpeg và ffprobe; không cần cài Node/Python. Bản 0.8.0 đã kiểm tra app đóng gói trên Windows x64, Linux x64 và macOS Intel/Apple Silicon. Windows có thêm kiểm thử GUI và cài/nâng cấp/gỡ bộ cài; Linux/macOS kiểm tra trên runner, chưa bao phủ mọi máy người dùng. Xem [ghi chú phiên bản](RELEASE_NOTES.md).

## Bắt đầu

Chọn hồ sơ → mở website và đăng nhập trực tiếp trên trang chính thức → chọn một trong ba cách:

1. Thư viện ZIP: nhập bản xuất đã tải từ Meta. App chỉ hiển thị dữ liệu thật sự có trong ZIP.
2. Trực tiếp: mở đúng hội thoại/trang video → Đọc link hoặc Lấy thêm liên tục.
3. Nhập link: dán URL hoặc CSV/TXT → xem trước → lưu danh sách.

Lọc và tick link → Tải video đã chọn. Cửa sổ Tải xuống có tiến độ, lỗi, hồ sơ/nguồn/đợt tải và thao tác hủy/thử lại. Chất lượng phụ thuộc các định dạng nguồn cung cấp.

Trong Tải xuống → Video, xem nơi lưu ở đầu cửa sổ và dùng Mở thư mục, Đổi thư mục hoặc Dùng Downloads mặc định. Lượt tải mới mặc định vào Downloads của hệ điều hành. Các lượt đã xếp và tệp đã tải giữ đường dẫn trong lịch sử.

Trong Cập nhật ở cột trái, bấm Kiểm tra cập nhật để xem bản mới và ghi chú. Mục này cũng mở được từ Môi trường. Bản Windows x64 cài bằng NSIS có thể tải, xác minh SHA-256 và mở bộ cài nâng cấp. Windows có thể yêu cầu xác nhận bộ cài chưa ký. Người dùng 1.0.0 tải bộ cài mới một lần để có mục Cập nhật.

Bản Windows 1.1.1 có Hồ sơ & tài khoản để đặt tên, chọn hồ sơ và xem cookie/cache. Dọn cache HTTP và xóa cookie có xác nhận đúng hồ sơ và website. Trong Môi trường có Debug ghi log đã lọc và chế độ Thử nghiệm mặc định tắt. Hiện chưa có tính năng thử nghiệm được đăng ký.

## Dữ liệu hiện có

Bộ cài lưu data ngoài thư mục cài. Dùng nút Thư mục dữ liệu để chọn thư mục `data` của bản cũ rồi khởi động lại. Không chọn thư mục `electron-profile` con. Gỡ cài đặt giữ dữ liệu; không chép cookie giữa các máy/hệ điều hành.

Xóa link/nguồn chuyển vào Thùng rác. Gỡ hồ sơ khỏi app có thể khôi phục; checkbox xóa cả dữ liệu website là lựa chọn riêng, không khôi phục được phiên đã xóa. Xóa trong app không xóa tài khoản trên website. Video, ZIP và lịch sử tải giữ nguyên.

## Quyền riêng tư và hỗ trợ

Mật khẩu/2FA/PIN chỉ nhập trên trang chính thức. Không gửi ZIP cá nhân, database, cookie, token, log chưa lọc hoặc ảnh hội thoại vào issue. Khi báo lỗi, nêu phiên bản app, hệ điều hành, thao tác và mã lỗi đã che dữ liệu riêng.

SOCIALdock không vượt CAPTCHA, quyền truy cập hoặc xác minh tài khoản. Chưa cam kết hỗ trợ Shopee Video/Zalo Video, thu đủ mọi Reels/hội thoại hoặc giữ đăng nhập vĩnh viễn.

Xem [thông báo thành phần bên thứ ba](THIRD_PARTY_NOTICES.md).
