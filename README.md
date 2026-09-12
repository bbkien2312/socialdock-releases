# SOCIALdock

Thư viện ZIP và trình duyệt trong app để tổ chức liên kết, lọc dữ liệu và tải video từ nguồn bạn có quyền truy cập.

[Tải bộ cài và xem phiên bản](https://github.com/bbkien2312/socialdock-releases/releases)

Repository này chỉ chứa hướng dẫn và bản phát hành. Source được quản lý trong repository private.

## Chọn bộ cài

- Windows x64: file `windows-x64-setup.exe`.
- Linux x64: file `.AppImage`; cấp quyền thực thi rồi mở.
- macOS: `.dmg` cho Intel (x64) hoặc Apple Silicon (arm64).

Chỉ các hệ điều hành ghi đạt trong release notes mới có file phát hành. Bản chưa ký/notarize được đánh dấu prerelease; có thể gặp SmartScreen/Gatekeeper. SHA256SUMS xác minh file, không thay chữ ký số.

## Bắt đầu

Chọn hồ sơ → mở website và đăng nhập trực tiếp trên trang chính thức → chọn một trong ba cách:

1. Thư viện ZIP: nhập bản xuất đã tải từ Meta. App chỉ hiển thị dữ liệu thật sự có trong ZIP.
2. Trực tiếp: mở đúng hội thoại/trang video → Đọc link hoặc Lấy thêm liên tục.
3. Nhập link: dán URL hoặc CSV/TXT → xem trước → lưu danh sách.

Lọc và tick link → Tải video đã chọn. Cửa sổ Tải xuống có tiến độ, lỗi, hồ sơ/nguồn/đợt tải và thao tác hủy/thử lại. Chất lượng phụ thuộc các định dạng nguồn cung cấp.

## Dữ liệu hiện có

Bộ cài lưu data ngoài thư mục cài. Dùng nút Thư mục dữ liệu để chọn thư mục `data` của bản cũ rồi khởi động lại. Không chọn thư mục `electron-profile` con. Gỡ cài đặt giữ dữ liệu; không chép cookie giữa các máy/hệ điều hành.

Xóa link/nguồn chuyển vào Thùng rác. Gỡ hồ sơ khỏi app có thể khôi phục; checkbox xóa cả dữ liệu website là lựa chọn riêng, không khôi phục được phiên đã xóa. Xóa trong app không xóa tài khoản trên website. Video, ZIP và lịch sử tải giữ nguyên.

## Quyền riêng tư và hỗ trợ

Mật khẩu/2FA/PIN chỉ nhập trên trang chính thức. Không gửi ZIP cá nhân, database, cookie, token, log chưa lọc hoặc ảnh hội thoại vào issue. Khi báo lỗi, nêu phiên bản app, hệ điều hành, thao tác và mã lỗi đã che dữ liệu riêng.

SOCIALdock không vượt CAPTCHA, quyền truy cập hoặc xác minh tài khoản. Chưa cam kết hỗ trợ Shopee Video/Zalo Video, thu đủ mọi Reels/hội thoại hoặc giữ đăng nhập vĩnh viễn.

Xem [thông báo thành phần bên thứ ba](THIRD_PARTY_NOTICES.md).
