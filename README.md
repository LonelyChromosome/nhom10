# ♟️ Web Game Cờ Vua - Dự Án Nhóm 10

## 📝 Tổng quan đề tài

### Lý do lựa chọn
Bọn em quyết định lựa chọn đề tài web game cờ vua vì đây là một sản phẩm độc đáo, giúp **tránh được các yếu tố ngẫu nhiên** để tập trung hoàn toàn vào tư duy logic thuần túy. Dự án còn giúp rèn luyện kỹ năng quản lý trạng thái (*state management*) phức tạp, tạo ra một sản phẩm trực quan, thực chiến và nổi bật hơn hẳn các bài tập quản lý thông thường.

### Hạn chế của đề tài
* **Chưa hỗ trợ kết nối mạng:** Trò chơi chỉ chạy trực tiếp trên một máy (Local), chưa thể kết nối hai người chơi ở hai thiết bị khác nhau qua Internet.

---

## 🚀 Bảng tính năng hệ thống

| Tên tính năng | Chế độ chơi | Mô tả chi tiết |
| :--- | :--- | :--- |
| **Đấu nội bộ** | 2 Người chơi | Hai người ngồi chung một máy, thay phiên nhau đi quân trực tiếp trên cùng một màn hình. |
| **Đấu với máy** | 1 Người chơi | Chơi đơn với máy. Tích hợp engine chuyên nghiệp **Stockfish** hỗ trợ tùy chỉnh nhiều cấp độ khó khác nhau (từ dễ đến khó) để luyện tập chiến thuật. |
| **Kiểm soát luật chơi** | Hệ thống hệ thống | Tự động nhận diện nước đi hợp lệ, bắt tốt qua đường, nhập thành, chiếu tướng, chiếu bí và xử hòa nhờ `Chess.js`. |
| **Giao diện tương tác** | Giao diện | Bàn cờ hiển thị trực quan, hỗ trợ thao tác kéo-thả quân cờ mượt mà nhờ `Chessboard.js`. |
| Đa ngôn ngữ | Giao diện | Hỗ trợ chuyển đổi ngôn ngữ linh hoạt (ví dụ: Tiếng Việt / Tiếng Anh) giúp tối ưu trải nghiệm người dùng. |

---

## 🛠️ Công nghệ sử dụng
* **Frontend:** HTML5, CSS3, JavaScript (jQuery)
* **Thư viện Logic:** [Chess.js](https://github.com)
* **Thư viện Bàn cờ:** [Chessboard.js](https://chessboardjs.com)
* **Chess Engine (AI):** [Stockfish.js](https://github.com) (Phiên bản chạy trực tiếp trên trình duyệt thông qua Web Worker)

---

## 👥 Thành viên thực hiện
* **Thành viên 1:** [Nguyễn Minh Đạo] - MSSV: [24100222] (Trưởng nhóm)
* **Thành viên 2:** [Đặng Văn Nam Khán]  - MSSV: [24100041]
* **Thành viên 3:** [Nguyễn Thanh Hải] - MSSV: [21011491]
