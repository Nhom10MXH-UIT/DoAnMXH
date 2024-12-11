# GPA Prediction Application

## Giới thiệu

Ứng dụng Dự đoán Điểm GPA (Grade Point Average) là một công cụ giúp sinh viên dự đoán điểm GPA của mình dựa trên các môn học và điểm số đã đạt được. Ứng dụng tính toán GPA theo công thức sau:

\[
GPA = \frac{\sum(\text{Điểm số} \times \text{Tín chỉ})}{\sum(\text{Tín chỉ})}
\]

Ứng dụng hỗ trợ sinh viên theo dõi kết quả học tập và đưa ra các gợi ý để cải thiện điểm số.

## Mục tiêu

- Dự đoán GPA của sinh viên dựa trên các môn học và điểm số.
- Giúp sinh viên theo dõi tiến trình học tập.
- Cung cấp các gợi ý cải thiện GPA dựa trên kết quả hiện tại.

## Tính năng chính

- **Nhập thông tin môn học**: Cho phép người dùng nhập tên môn học, số tín chỉ và điểm số.
- **Tính toán GPA**: Tính toán GPA dựa trên các môn học đã nhập và hiển thị kết quả.
- **Lịch sử GPA**: Xem lại lịch sử GPA qua các học kỳ.
- **Gợi ý cải thiện GPA**: Dựa trên điểm số, ứng dụng sẽ gợi ý các môn học hoặc chiến lược học tập để cải thiện điểm số.
- **Cập nhật môn học**: Thêm hoặc chỉnh sửa thông tin các môn học và tự động cập nhật GPA.

## Hướng dẫn sử dụng

1. **Màn hình chính**:

   - **Thông tin người dùng**: Nhập họ tên, khoa và năm học.
   - **Các môn học**: Nhập tên môn học, số tín chỉ và điểm số của các môn học mà bạn đã hoàn thành.
   - **Nút "Dự đoán GPA"**: Nhấn vào nút này để tính toán GPA.

2. **Nhập thông tin môn học**:

   - Ví dụ:

     - Môn học 1: Toán
     - Số tín chỉ: 3
     - Điểm số: 8

   - Tiếp tục nhập các môn học khác nếu có.

3. **Tính toán GPA**:

   - Sau khi nhập thông tin các môn học, nhấn nút **Dự đoán GPA** để ứng dụng tính toán GPA.
   - Công thức tính GPA:

     \[
     GPA = \frac{\sum(\text{Điểm số} \times \text{Tín chỉ})}{\sum(\text{Tín chỉ})}
     \]

   - Ứng dụng sẽ hiển thị GPA dự đoán và phân loại học lực của bạn.

   Ví dụ, nếu bạn nhập các môn học như sau:

   - Toán: 3 tín chỉ, điểm 8
   - Lý: 4 tín chỉ, điểm 7
   - Hóa: 2 tín chỉ, điểm 9

   GPA dự đoán sẽ là 8.0 và phân loại học lực là "Khá".

4. **Chức năng bổ sung**:
   - **Lịch sử GPA**: Bạn có thể xem lại lịch sử GPA của mình qua các học kỳ đã học.
   - **Gợi ý cải thiện GPA**: Ứng dụng sẽ đưa ra gợi ý về các môn học hoặc chiến lược học tập giúp bạn cải thiện GPA.
   - **Cập nhật môn học**: Bạn có thể thay đổi hoặc thêm môn học vào danh sách và ứng dụng sẽ tự động tính lại GPA.

## Cài đặt

Để cài đặt và chạy ứng dụng này, vui lòng làm theo các bước sau:

1. **Cài đặt môi trường**:

   - Cài đặt Python (nếu chưa có).
   - Cài đặt các thư viện yêu cầu như Flask (nếu ứng dụng chạy trên nền tảng web) hoặc các thư viện GUI như Tkinter (nếu ứng dụng chạy trên máy tính để bàn).

2. **Chạy ứng dụng**:

   - Clone dự án về máy tính của bạn.
   - Mở terminal/command prompt và điều hướng đến thư mục chứa dự án.
   - Chạy ứng dụng bằng lệnh:
     ```bash
     python app.py
     ```

3. **Truy cập ứng dụng**:
   - Nếu sử dụng nền tảng web, mở trình duyệt và truy cập địa chỉ: `http://localhost:5000`.

## Liên hệ

Nếu bạn gặp bất kỳ vấn đề nào khi sử dụng ứng dụng hoặc có câu hỏi, vui lòng liên hệ với chúng tôi qua email: support@gpapredictor.com.

Cảm ơn bạn đã sử dụng ứng dụng Dự đoán GPA!

## Lưu ý

Ứng dụng này chỉ dựa trên thông tin điểm số và tín chỉ mà bạn nhập. Nó không thay thế cho các công cụ chính thức của trường học và chỉ mang tính chất tham khảo.
