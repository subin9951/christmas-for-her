🎄 Grand Luxury Tree - Christmas Edition
Xin chào! 👋 Đây là một dự án nhỏ mình viết để chào mừng Giáng Sinh. ✨

Ban đầu mình chỉ định vẽ một cây thông 3D bình thường, nhưng thấy chưa đủ "ngầu", nên mình đã tích hợp thêm Nhận diện cử chỉ tay (AI) và Hiệu ứng hạt (Particles). Bây giờ, bạn có thể điều khiển cây thông này "không chạm" qua webcam và treo những bức ảnh kỷ niệm lên đó.

Code tuy không quá đồ sộ nhưng hiệu ứng thị giác thì "hết nước chấm" (đặc biệt là khi xem trên màn hình lớn).

🌟 Trải nghiệm ngay tại đây (Demo): Grand Luxury Tree - Christmas Edition (Lưu ý: Nhớ thay link trên bằng link GitHub Pages thực tế của bạn sau khi deploy)

<img width="2559" height="1439" alt="image" src="[https://github.com/user-attachments/assets/45f3ec57-00b5-4989-b3b2-484772ad95cf](https://subin9951.github.io/christmas-for-her/)" />

🤔 Dự án này là gì? (Intro)
Đây không phải là một tấm thiệp web tĩnh nhàm chán. Đây là một cây thông động được tạo thành từ hàng nghìn hạt ánh sáng. Mình sử dụng Google MediaPipe để giúp trình duyệt có thể "nhìn" và hiểu cử chỉ tay của bạn.

Hiệu ứng hạt (Particles): Cây biết "thở", xoay tròn và có thể bùng nổ thành dải ngân hà.

Điều khiển không chạm: Không cần chuột, chỉ cần vẫy tay trước camera để điều khiển (cảm giác như Iron Man vậy).

Lưu giữ kỷ niệm: Tự động tải ảnh từ thư mục, hiển thị dưới dạng khung tranh mạ vàng/bạc bay lơ lửng.

Giao diện Luxury: Tông màu Đen - Vàng (Xmas) hoặc Xanh Băng (Ice), Hồng (Lovely), tập trung vào sự sang trọng, tinh tế.

Tâm thư bí mật: Một bức thư đầy cảm xúc sẽ hiện ra khi bạn xem hết các bức ảnh.

<img width="2557" height="1291" alt="image" src="https://github.com/user-attachments/assets/d7d31b4c-bf4d-49b2-b922-79813bbddba5" /> <img width="2559" height="1294" alt="image" src="https://github.com/user-attachments/assets/d7e4e982-3042-449d-8898-105048aeac1d" />

🛠️ Công nghệ sử dụng (Tech)
Dự án này sử dụng "ma thuật" Front-end thuần túy, không dùng Framework nặng nề:

Three.js - Xử lý render 3D và hệ thống hạt (Particle System).

MediaPipe - Xử lý nhận diện cử chỉ tay (Hand Tracking) siêu nhạy.

Vanilla JS (ES Modules) - Tự tay xử lý toàn bộ logic cốt lõi.

🎮 Cách chơi (Controls)
💡 Mẹo: Lần đầu mở lên, hãy nhớ bật âm thanh (nút loa góc phải) để tận hưởng không khí Giáng Sinh nhé! 🎵

🖐️ Chế độ Cử chỉ tay (Hand Gestures)
Hãy đảm bảo bạn đã cấp quyền truy cập Camera cho trình duyệt.

Xòe bàn tay (🖐️): Chế độ "Bùng nổ" (Scatter)! Cây thông sẽ tan biến thành các vì sao, bạn có thể di chuyển tay để xoay góc nhìn.

Nắm bàn tay (✊): Chế độ "Hội tụ" (Tree)! Các hạt sẽ bay về và ghép lại thành cây thông.

Chụm ngón tay (🤏) (Ngón cái & Ngón trỏ): Chế độ "Xem ảnh" (Focus). Hệ thống sẽ tự động zoom vào một bức ảnh kỷ niệm.

Đặc biệt: Nếu đã xem hết ảnh, khi chụm tay lần nữa, một bức thư bí mật sẽ hiện ra.

Giơ 1 ngón trỏ (☝️) (Giữ yên khoảng 1 giây): Công tắc đổi Theme!

Chuyển đổi qua lại giữa: Xmas (Vàng ấm) ↔ Ice (Băng giá) ↔ Lovely (Hồng lãng mạn).


🚀 Cài đặt & Chạy (How to Run)
⚠️ Lưu ý quan trọng: Vì dự án sử dụng ES Modules và cần quyền truy cập Camera, bạn KHÔNG THỂ mở trực tiếp file index.html bằng cách click đúp (sẽ bị lỗi CORS). Bạn cần chạy trên một Local Server.

Cách 1: Dùng VS Code (Khuyên dùng)

Cài đặt Extension Live Server.

Chuột phải vào file index.html -> Chọn "Open with Live Server".

Xong!

Cách 2: Dùng Python Mở terminal tại thư mục dự án và gõ:

Bash

python -m http.server 8000
Sau đó truy cập http://localhost:8000 trên trình duyệt.

Cách 3: Dùng Node.js

Bash

npx http-server .
🖼️ Cách thay đổi ảnh
Để thay ảnh của chính bạn:

Vào thư mục images/.

Xóa các ảnh cũ đi.

Copy ảnh của bạn vào và đổi tên lần lượt thành (1).jpg, (2).jpg, (3).jpg... (hoặc .png).

Code sẽ tự động quét và hiển thị ảnh của bạn.

Merry Christmas! 🎅 Chúc bạn và người thương một mùa Giáng Sinh an lành và ấm áp! Nếu thấy dự án thú vị, hãy tặng mình 1 ⭐️ Star trên GitHub nhé!

Contributors ✨
Cảm ơn tác giả gốc và các đóng góp:

<a href="https://github.com/electronicminer/gesture-Christmas_tree-3d_with_photo/graphs/contributors"> <img src="https://contrib.rocks/image?repo=electronicminer/gesture-Christmas_tree-3d_with_photo" /> </a>

📊 Star History
