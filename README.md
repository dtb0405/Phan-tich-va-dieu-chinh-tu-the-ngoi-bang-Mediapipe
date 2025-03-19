
🧑‍💻 Hệ thống phát hiện tư thế ngồi thông minh

Đây là một hệ thống phát hiện tư thế ngồi sử dụng Flask, MediaPipe Pose và OpenCV để phân tích và đánh giá tư thế của người dùng thông qua camera. Hệ thống sẽ đưa ra cảnh báo bằng giọng nói khi phát hiện tư thế ngồi sai.

🚀 Tính năng chính

✅ Phát hiện tư thế ngồi thông qua camera.

✅ Đánh giá góc nghiêng của cổ và lưng.

✅ Hiển thị thông tin tư thế theo thời gian thực trên giao diện.

✅ Cảnh báo bằng giọng nói khi phát hiện tư thế ngồi sai.

✅ Giao diện hiện đại, thân thiện với hiệu ứng Glassmorphism.

🏗️ Công nghệ sử dụng: Python, Flask, OpenCV, MediaPipe, gTTS (Google Text-to-Speech), HTML/CSS/JavaScript

🔧 Cài đặt và chạy dự án
1. Clone repo:
git clone https://github.com/your-repo-name.git

3. Cài đặt thư viện cần thiết:
pip install -r requirements.txt

4. Chạy Flask server:
python app.py

5. Truy cập giao diện:

Mở trình duyệt và truy cập:
http://localhost:5000

🖥️ Hướng dẫn sử dụng

Kết nối camera hoặc sử dụng ứng dụng DroidCam để truyền hình ảnh từ điện thoại.

Mở giao diện hệ thống trên trình duyệt.

Theo dõi thông tin về tư thế ngồi trên giao diện.

Khi tư thế sai, hệ thống sẽ hiển thị cảnh báo và phát âm thanh.

🏆 Đánh giá tư thế

![image](https://github.com/user-attachments/assets/bc22d6d1-0385-489b-9b07-a2831243c5cb)


⚠️ Cảnh báo

Hệ thống sẽ phát âm thanh cảnh báo nếu bạn duy trì tư thế sai quá 6 giây.

Khi có lỗi nhận diện, thông báo sẽ hiển thị trên giao diện.
