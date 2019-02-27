**Câu 1: Trí tuệ là gì? Đọc thêm bài viết 9 loại trí thông minh, có thể xem thêm bài giảng của Ted Ed và làm quiz (tiếng Anh).**

Trí tuệ là khả năng học và áp dụng các kiến thức, kỹ năng trong cuộc sống. Trong cuộc sống là tập hợp các kiến thức và kỹ năng có được theo thời gian.

Có 9 loại trí thông minh bao gồm:
1. Vận động: Khả năng trí não điều khiển các hoạt động thể chất
2. Ngôn ngữ: Khả năng sử dụng ngôn ngữ để diễn đạt
3. Nội tâm: Khả năng nắm bắt tâm lý, cảm xúc của bản thân
4. Không gian: Khả hình dung được không gian 3 chiều xung quanh, như khả năng nhớ lộ trình đường đi, khả năng hình dung được phương hướng, địa hình một cách nhanh chóng
5. Tự nhiên: Khả năng khám phá, tìm hiểu về thiên nhiên, các sinh vật trong tự nhiên
6. Âm nhạc: Khả năng cảm nhận được các âm điệu, cao độ và nhịp điệu âm thanh
7. Logic-Toán học: Khả năng xem xét vấn đề một cách logic, biện chứng, các giả thuyết chứng minh toán học, chứng minh các mệnh đề, định lý.
8. Hiện sinh: Khả năng tìm hiểu các vấn đề với các câu hỏi tại sao?
9. Hướng ngoại: Năng lực làm việc với những người khác, có khả năng tạo cảm hứng, dẫn dắt người khác. Hiểu được tâm lý của người khác.

**Câu 2: Trí tuệ nhân tạo (artificial intelligence, AI) là gì? Những tiến bộ nào góp phần dẫn đến cuộc cách mạng AI?**


**Câu 3: Học là gì? Học máy (machine learning; ML) là gì? Vị trí của ML trong AI? Kiến thức kỹ năng có thể được biểu diễn trong máy tính ra sao?**


**Câu 4: Các thành phần cơ bản (TEFPA như trong bài giảng) cần được mô tả và cung cấp để máy tính tự học cách giải quyết một tác vụ là gì?**

TEFPA là từ viết tắt của 5 bước:

1. **Task (T)** : mô tả tác vụ, đầu vào và đầu ra của ứng dụng
2. **Experience (E)** : tập dữ liệu thể hiện của tác vụ. Là tập hợp các bộ dữ liệu đầu vào và đầu ra trong thực tế.
3. **Function Space (F)** : không gian các hàm số
4. **Perfomance Measure (P)** : Đánh giá chất lượng, kết quả
5. **Search Algorithm (A)** : Tìm kiếm thuật toán. Tìm kiếm hàm biểu diễn sao cho dữ liệu đưa vào qua hàm tìm kiếm được cho đầu ra có kết quả gần nhất với dữ liệu thực tế.


**Câu 5. Mô tả tác vụ, kinh nghiệm/ dữ liệu cần chuẩn bị một số ứng dụng**

a) Máy tính chuyển 1 tấm ảnh chất lượng kém (mờ, low-resolution) lên thành ảnh rõ nét (high-resolution)

* Tác vụ đầu vào:

      Đầu vào là các dữ liệu hình ảnh, đầu ra là dữ liệu các hình ảnh đã được xử lý.Dữ liệu cần chuẩn bị là số lượng lớn các cặp ảnh low-resolution và ảnh high-resolution tương ứng.

* Dữ liệu chuẩn bị:

      Hiện tại chưa xác định được cách tìm nguồn dữ liệu là các cặp ảnh low-resolution và high resolution tương ứng.
   
b) Máy tính xử lý ảnh chụp X-quang và dự đoán bệnh

* Tác vụ đầu vào:

      Đầu vào là các bức hình X-quang và đầu ra là các đoạn văn bản có nội dung về dự đoán bệnh có khả năng. Có thể mong muốn là dự đoán một số dầu hiệu bệnh kèm theo chỉ số khả năng bao nhiêu phần trăm là bệnh A, bao nhiêu phần trăm là bệnh B
   
* Dữ liệu chuẩn bị:

      Các ảnh chụp x-quang và các bệnh thực tế của các đối tượng được chụp các bức hình x-quang đấy.

* Nguồn thu thập dữ liệu:
      
      Từ các bệnh viện, phòng khám. Tuy nhiên hồ sơ bệnh án là các dự liệu vô cùng nhạy càm, cần sự hợp tác của các bệnh viện, phòng khám về thông tin dữ liệu.
      Bảo vệ thông tin cá nhân, dữ liệu chỉ cần random các cặp ảnh chụp và bệnh thực tế của người chụp, không lấy thông tin cá nhân bất kỳ được asign vào cho các bức hình đấy.
   
c) Máy tính đọc một email của khách hàng và tự chuyển tới các mục tương ứng như "cảm ơn", "khiếu nại", "hỏi thông tin",....

* Tác vụ đầu vào:

      Đầu vào các đoạn văn bản email, đầu ra là mảng các nhóm chỉ số phù hợp với danh sách các category cho trước. Ví dụ mình sẽ có các nhóm category như trên là "cảm ơn", "khiếu nại", "hỏi thông tin", "khác". Vậy đầu ra của ứng dụng này sẽ là 1 mảng dữ liệu cho biết email này phù hợp với "cảm ơn" là bao nhiêu phần trăm, "khiếu nại" bao nhiêu phần trăm?,...

* Dữ liệu chuẩn bị:
      
      Các cặp email và kết quả đã được đánh dấu theo các nhóm nội dung tương ứng. Việc có dữ liệu này khó khăn trong thực tế vì nội dung email hoàn toàn mang tính riêng tư nên khó có thể được can thiệp. Có thể đề xuất bằng cách tạo ra một số lượng các đoạn email và đánh dấu nhóm nội dung tương ứng, tuy nhiên việc này sẽ rất hạn chế số lượng data có được và tốn chi phí thực hiện hiện.


**Câu 6: Ý nghĩa câu phát biểu sau: Máy tính `học` bằng cách tìm kiếm trong không gian các hàm số (chương trình máy tính).**

Như chúng ta đã biết, mọi kiến thức đều có thể được biểu diễn bằng một hàm số nào đó. Vậy nên để `học` hay thu nạp kiến thức chính là tìm kiếm hàm số biểu diễn kiến thức đó trong thế giới kiến thức hay có thể hiểu là không gian các hàm số.

**Câu 7: Hai vấn đề chính về không gian hàm mà ta cần đặc biệt chú ý để giúp máy tính tự tìm kiếm hàm có độ khái quát hoá cao là gì?**


