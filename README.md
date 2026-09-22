# 📱 Better Phenikaa - Dự Án Nhóm 10

## 📝 Tổng quan đề tài

**Better Phenikaa** là ứng dụng hỗ trợ sinh viên Phenikaa theo dõi lịch học, lịch thi và các thông tin học tập cần thiết một cách nhanh chóng, trực quan và thuận tiện hơn trên thiết bị Android.

Ứng dụng được xây dựng theo hướng đơn giản hóa quá trình truy cập thông tin từ hệ thống QLĐT, đồng thời đưa các thông tin quan trọng như lịch học ra ngay màn hình chính thông qua widget.

---

## 💡 Lý do lựa chọn đề tài

Nhóm lựa chọn phát triển Better Phenikaa với mong muốn **thử sức với một dự án ứng dụng di động có tính thực tế cao**, thay vì chỉ dừng lại ở các bài tập mô phỏng.

Bên cạnh mục tiêu học tập, đề tài còn hướng tới việc giúp đời sống sinh viên thuận tiện hơn trong quá trình sử dụng hệ thống học tập hằng ngày. Sinh viên có thể đăng nhập, theo dõi lịch học, lịch thi và xem nhanh thông tin cần thiết mà không phải thực hiện lại nhiều thao tác thủ công.

Thông qua dự án, nhóm có cơ hội thực hành nhiều nội dung quan trọng như xây dựng giao diện ứng dụng, xử lý dữ liệu, tích hợp WebView, duy trì trạng thái ứng dụng, làm việc với Android Widget và tổ chức một ứng dụng Flutter hoàn chỉnh.

---

## 🚀 Chức năng chính

| Chức năng | Mô tả |
| :--- | :--- |
| **Đăng nhập QLĐT** | Hỗ trợ sinh viên truy cập hệ thống QLĐT trực tiếp từ ứng dụng. |
| **Lấy dữ liệu học tập** | Tiếp nhận và xử lý các thông tin cần thiết từ phiên đăng nhập QLĐT. |
| **Lịch học** | Hiển thị lịch học theo giao diện trực quan, dễ theo dõi trên điện thoại. |
| **Lịch thi** | Hiển thị thông tin lịch thi phục vụ quá trình học tập. |
| **Đồng bộ dữ liệu** | Cập nhật dữ liệu để ứng dụng và widget sử dụng thông tin mới nhất đã lấy được. |
| **Widget Android** | Hiển thị nhanh lịch học và thông tin cần thiết ngay trên màn hình chính mà không cần mở ứng dụng. |
| **Giao diện ứng dụng** | Thiết kế giao diện thống nhất, tối ưu cho quá trình sử dụng hằng ngày của sinh viên. |
| **Lưu trạng thái cục bộ** | Lưu các thiết lập và dữ liệu cần thiết trên thiết bị để cải thiện trải nghiệm sử dụng. |

---

## ⚠️ Hạn chế

* Ứng dụng hiện **chỉ hỗ trợ Android**, chưa có phiên bản chính thức cho iOS.
* Do sự khác biệt giữa các phiên bản Android, launcher, nhà sản xuất thiết bị và cơ chế quản lý widget, ứng dụng **vẫn có thể phát sinh lỗi trên một số thiết bị chưa tương thích hoàn toàn**.
* Một số chức năng phụ thuộc vào cấu trúc và khả năng truy cập của hệ thống QLĐT, vì vậy có thể cần điều chỉnh nếu hệ thống phía QLĐT thay đổi.

---

## 🛠️ Công nghệ sử dụng

* **Ngôn ngữ lập trình:** Dart
* **Framework:** Flutter
* **Nền tảng triển khai:** Android
* **WebView / kết nối QLĐT:** `flutter_inappwebview`
* **Android Home Screen Widget:** `home_widget`
* **Xử lý nội dung HTML:** `html`
* **Lưu trữ cục bộ và thiết lập ứng dụng:** `shared_preferences`
* **UI:** Flutter Material Design
* **Kiểm thử:** Flutter Test
* **Phân tích chất lượng mã nguồn:** `very_good_analysis`

---

## 👥 Phân công thành viên

| Thành viên | MSSV | Phân công |
| :--- | :--- | :--- |
| **Nguyễn Minh Đạo** *(Trưởng nhóm)* | **24100222** | Phụ trách logic vận hành tổng thể của ứng dụng, đồng bộ dữ liệu, tích hợp và vận hành **Android Widget**. |
| **Đặng Văn Nam Khán** | **24100041** | Phụ trách **trang đăng nhập**, kết nối và xử lý luồng truy cập **QLĐT**, phục vụ việc lấy dữ liệu cho ứng dụng. |
| **Nguyễn Thanh Hải** | **21011491** | Phụ trách thiết kế và hoàn thiện **toàn bộ giao diện UI** của ứng dụng, bảo đảm tính thống nhất và thuận tiện khi sử dụng. |

---

## 🎯 Mục tiêu của dự án

Dự án hướng tới việc tạo ra một ứng dụng hỗ trợ sinh viên có thể sử dụng trong thực tế, đồng thời giúp các thành viên trong nhóm rèn luyện kỹ năng phát triển ứng dụng bằng Flutter, phối hợp nhiều thành phần của hệ thống và giải quyết các vấn đề phát sinh trên thiết bị Android thực tế.
