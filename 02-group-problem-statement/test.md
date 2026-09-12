Problem Card — Trợ lý AI thời gian thực hỗ trợ giao tiếp cho người câm điếc
Problem 1 câu:

Người câm điếc gặp rào cản lớn trong việc giao tiếp hai chiều với người nghe bình thường trong đời sống hàng ngày do thiếu một công cụ dịch thuật ngôn ngữ ký hiệu và âm thanh chuẩn xác, theo thời gian thực và có chi phí tiếp cận thấp.

Actor:

Cộng đồng người câm điếc (hoặc người giao tiếp thường xuyên với họ như nhân viên dịch vụ, y tế, giáo dục).

Thời điểm / bối cảnh:

Các tình huống giao tiếp trực tiếp hàng ngày (mua sắm, khám bệnh, làm thủ tục hành chính, trao đổi công việc) đòi hỏi phản hồi nhanh chóng và tự nhiên.

Current workflow:

Plaintext

1. Người câm điếc dùng ký hiệu/chữ viết tay trên điện thoại 

-> 2. Người nghe đọc/quan sát nhưng hiểu lầm hoặc mất nhiều thời gian 

-> 3. Người nghe nói lại 

-> 4. Người câm điếc không nghe được phải nhờ viết ra giấy 

-> 5. Giao tiếp bị đứt quãng, căng thẳng và kém hiệu quả <->
Bottleneck:

Điểm nghẽn nằm ở độ trễ cao của quá trình dịch thuật thủ công (phải gõ chữ qua lại) và sự thiếu hụt các công cụ nhận diện ngôn ngữ ký hiệu (Sign Language) bằng AI chạy mượt mà trên thiết bị di động cá nhân.

Future Workflow
[1 Người câm điếc dùng camera điện thoại hướng về phía mình để ra ký hiệu (Sign Language)] 
→ [2 Computer Vision Model (MediaPipe/Transformer) nhận diện chuyển động tay & ngón tay trên Edge device] 
→ [3 AI dịch chuỗi cử chỉ thành văn bản tiếng Việt & phát âm thanh qua loa điện thoại] 
→ [4 Người nghe nghe/đọc được thông điệp ngay lập tức mà không cần chờ đợi]

Impact:

Gây ra sự cô lập xã hội, khó khăn trong việc tiếp cận các dịch vụ thiết yếu, và tạo áp lực tâm lý lớn cho người câm điếc mỗi khi cần hòa nhập cộng đồng.

Success metric:
Thời gian hoàn thành một phiên giao tiếp ngắn giảm 60%; tỷ lệ hiểu đúng thông điệp giữa hai bên đạt trên 90%; giảm hoàn toàn độ trễ nhờ xử lý bằng AI real-time trên smartphone.

Non-AI alternative:

Sử dụng bảng viết tay mini mang theo người, dùng ứng dụng ghi chú (Notes/Notepad) gõ chữ qua lại, hoặc thuê phiên dịch viên ngôn ngữ ký hiệu chuyên nghiệp (chi phí đắt đỏ và không phải lúc nào cũng có sẵn).

AI hypothesis:

Ứng dụng Computer Vision (nhận diện cử chỉ tay qua camera điện thoại) kết hợp Speech-to-Text / Text-to-Speech để làm cầu nối dịch thuật hai chiều tức thì: Chuyển ký hiệu thành giọng nói/văn bản cho người nghe, và chuyển giọng nói thành văn bản cho người câm điếc.

Quick gut:
[x] Workflow (Tối ưu hóa luồng giao tiếp bằng AI trợ lý thời gian thực)

