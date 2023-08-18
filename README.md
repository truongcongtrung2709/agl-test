AGL || BÀI THI TUYỂN DỤNG

Tôi là Trương Công Trung, Đây là bài thi tuyển dụng của công ty Allgrow Labo. Xin cảm ơn vì đã gửi bài kiểm tra để có cơ hội tham gia vị trí ứng tuyển vào vị trí Kỹ sư Front-End.

Trước khi vào dự án, tôi xin được mô tả về dự án:

- Bố cục dự án:

  - sideBar
  - navbar
  - searchBar
  - FirstSection
  - SecondSection
  - ThirdSection

- Folder:

  - css và scss: Gồm những file tạo style cho dự án
  - images: chứa hình ảnh(icons, logos, images,...)
  - scripts: file chứa javascript của dự án
  - views: chứa file pug dùng để hổ trợ xây dựng file index.pug cho dự án.
    -mixins.pug: Tạo cấu trúc để dễ dàng tái sử dụng HTML.

- Công cụ sử dụng:

  HTML, SCSS, JavaScript, PUG

* Cài Đặt:
  - Cài đặt Pug: công cụ giúp chúng ta tách mã HTML thành các phần nhỏ hơn mà chúng ta có thể sử dụng lại trên nhiều tập tin HTML.
    . $ npm -g install pug
    . $ npm install -g pug-cli
    Sau khi cài đặt, chạy terminal dòng lệnh bên dưới để liên kết index.pug và index.html
    . pug index.pug --watch --pretty
  - Cài đặt SASS:
    . npm install -g sass
    Compile styles.scss với styles.css
    . sass ./scss/styles.scss ./css/styles.css --watch

Sau khi cài đặt, chạy dự án bằng live server.
