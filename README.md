# Nhập hồ sơ thừa kế – Lãnh Ngọc

Trang web nhập thông tin hồ sơ thừa kế và xuất các văn bản Word (.docx). Chạy hoàn toàn trên trình duyệt, không có máy chủ.

## Đưa lên GitHub Pages

1. Vào github.com, tạo repository mới (ví dụ `ho-so-thua-ke`).
2. Bấm **Add file → Upload files**, kéo `index.html` (và `README.md`) vào, bấm **Commit changes**.
3. Vào **Settings → Pages**. Ở mục *Build and deployment*, chọn **Deploy from a branch**, branch **main**, thư mục **/ (root)**, bấm **Save**.
4. Chờ 1–2 phút, địa chỉ dùng chung có dạng `https://<tên-tài-khoản>.github.io/ho-so-thua-ke/`.

## Lưu ý khi dùng chung

- **Dữ liệu chỉ lưu trên trình duyệt của từng máy** (localStorage). Mỗi người nhập hồ sơ riêng, không ai nhìn thấy hồ sơ của người khác, và không có dữ liệu cá nhân nào nằm trên GitHub.
- Muốn chuyển hồ sơ sang máy khác: bấm **Xuất file** (tải `sao-luu-ho-so.json`), sang máy kia bấm **Nhập file**.
- Xóa dữ liệu duyệt web hoặc dùng chế độ ẩn danh sẽ làm mất hồ sơ chưa sao lưu.
- Nếu repository để **Public** thì ai có đường link cũng mở được trang (nhưng không thấy dữ liệu nhập). Muốn hạn chế, dùng repository Private (cần gói GitHub hỗ trợ Pages cho repo private).

## Mẫu tờ khai (tùy chọn)

Trang tự tạo tờ khai bằng mẫu dựng sẵn. Nếu có file mẫu tờ khai dạng `mau-to-khai.b64` đặt cùng thư mục với `index.html`, trang sẽ dùng mẫu đó; không có thì tự chuyển về mẫu dựng sẵn.

## Yêu cầu

Cần kết nối mạng khi mở trang lần đầu để tải thư viện tạo Word (docx, jszip) và phông chữ.
