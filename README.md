# Mô hình nhà — GitHub Pages

Trang tĩnh, không cần npm hoặc bước build. HTML tự chứa mô hình, shader và ảnh tham chiếu. Không dùng CDN. Giao diện 3D hỗ trợ kéo một ngón và chụm hai ngón.

## Đưa lên GitHub Pages

1. Tạo một repository trên GitHub (ví dụ `mo-hinh-nha`).
2. Upload NỘI DUNG thư mục này vào gốc repository: `index.html`, `nha-3d.html`, `mat-bang.html`, `.nojekyll` và README này. Không upload cả thư mục lồng thêm một cấp; `index.html` phải ở gốc.
3. Commit lên nhánh `main`.
4. Trong repository vào **Settings → Pages**.
5. Ở **Build and deployment → Source**, chọn **Deploy from a branch**.
6. Chọn nhánh **main**, thư mục **/(root)** rồi **Save**.
7. Khi GitHub thông báo đã xuất bản, mở đường dẫn được cung cấp, thường dạng `https://TEN-TAI-KHOAN.github.io/TEN-REPO/` và gửi cho người khác.

Nếu repository của bạn dùng nhánh khác, chọn nhánh thực tế chứa các file. Cập nhật mô hình về sau bằng cách thay hai file HTML và commit lại; index và liên kết tương đối giữ nguyên.

## Điện thoại

- Kéo một ngón trên mô hình: xoay.
- Chụm/tách hai ngón: thu/phóng.
- Thanh trên mô hình: Tầng 1, Tầng lửng, Hai tầng.
- Nút Tùy chỉnh: cuộn đến bảng bật/tắt sàn, tường và nội thất.
- Nút đầu trang: chuyển qua lại giữa bản 2D và 3D trong cùng tab.
- Trình duyệt cần WebGL; có thể dùng Chrome/Edge trên Android hoặc Safari trên iPhone.

## Dữ liệu và phạm vi bản dựng

Đây là bản phác dựng theo ảnh và các xác nhận trong cuộc trao đổi. Mặt dưới sàn lửng +2,50 m; đỉnh nhà +4,50 m. Sàn tạm dày 0,12 m. Khu phơi trên gác có sàn, chừa ô cầu thang. Kích thước WC, hình mái và nhiều chi tiết vẫn cần xác nhận. Ảnh gốc được nhúng trong trang 2D; người truy cập trang sẽ xem được các ảnh này.

Tài liệu GitHub: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
