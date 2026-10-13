# UEH Incubation Features

Đặc tả và giao diện minh họa: Incubation Program & Cohort Dashboard, Shared Service Management, AI Screening.

## Đưa lên GitHub Pages bằng giao diện web

1. Mở https://github.com/new và đăng nhập.
2. Repository name: `ueh-incubation-features`.
3. Description: `UEH Innovation Platform – Incubation Dashboard, Shared Services & AI Screening`.
4. Chọn Public để dùng GitHub Pages trên tài khoản Free. Bật Add README, bấm Create repository.
5. Giải nén ZIP. Mở thư mục chứa index.html, style.css, app.js, data.js, README.md.
6. Trong repository, chọn Add file → Upload files. Kéo CÁC FILE bên trong thư mục vào, không tải nguyên ZIP hoặc thư mục cha.
7. Nhập commit message: `Add incubation feature guide`. Chọn commit vào main và xác nhận Commit changes. Nếu giao diện yêu cầu pull request, tạo rồi merge vào main.
8. Settings → Pages → Build and deployment → Source: Deploy from a branch.
9. Branch: main. Folder: /(root). Bấm Save.
10. Đợi triển khai xong, quay lại Settings → Pages → Visit site.

Địa chỉ: https://TEN_TAI_KHOAN.github.io/ueh-incubation-features/

Nếu GitHub của bạn là maiducphat1703 thì địa chỉ là:
https://maiducphat1703.github.io/ueh-incubation-features/

## File trong gói

- index.html: trang chính.
- style.css: giao diện.
- data.js: đặc tả và luồng sử dụng.
- app.js: tương tác và dữ liệu mẫu.
- README.md: hướng dẫn.

Không cần Node.js, npm, build hoặc máy chủ ứng dụng. Có thể mở index.html để xem nhanh hoặc dùng máy chủ web cục bộ.

Dữ liệu startup là minh họa. Shared Services lưu thay đổi trên trình duyệt; các phần khác chủ yếu lưu trong phiên mở trang. AI Screening dùng kịch bản mẫu, chưa gọi AI thật. Phân quyền trên demo chỉ là nội dung mô tả, chưa có đăng nhập hay kiểm soát truy cập. Website trên GitHub Pages là công khai.

## Khi cần cập nhật

Add file → Upload files, tải file mới cùng tên để thay thế, commit vào main. GitHub Pages sẽ triển khai lại.

## Nếu gặp lỗi

- 404: kiểm tra Pages đã chọn main và /(root); index.html nằm ngay ở thư mục gốc repository.
- Mất CSS/JS: kiểm tra cả style.css, data.js, app.js nằm cùng cấp index.html.
- Chưa hiện thay đổi: kiểm tra tab Actions và tải lại bằng Ctrl+F5.

Hướng dẫn chính thức: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
