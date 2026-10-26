# Moonbase – Bộ nhận diện thương hiệu

Website tĩnh, không cần build.

## Deploy lên Vercel

Cách 1 – Vercel CLI:

    npm i -g vercel
    cd moonbase-brand
    vercel          # bản preview
    vercel --prod   # bản chính thức

Cách 2 – GitHub: đẩy thư mục này lên một repo, vào vercel.com → Add New → Project → Import.
Framework Preset: Other. Build Command: để trống. Output Directory: để trống (thư mục gốc).

## Xem thử trên máy

    npx serve .

(Mở trực tiếp index.html bằng file:// cũng chạy, nhưng nên dùng server để font và video tải đúng.)

## Cấu trúc

    index.html                               trang chính
    assets/fonts/                            font Aeonik (cần license webfont khi đưa lên web công khai)
    assets/img/                              ảnh nội dung các trang
    assets/video/                            animation logo
    assets/Moonbase-Bo-nhan-dien-thuong-hieu.pdf   file tải về từ nút trên thanh nav
