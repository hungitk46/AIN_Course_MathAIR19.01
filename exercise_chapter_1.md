# Câu hỏi:

   1. Trí tuệ là gì? Đọc thêm bài viết 9 loại trí thông minh, có thể xem thêm bài giảng của Ted Ed và làm quiz (tiếng Anh). 

   2. Trí tuệ nhân tạo (artificial intelligence, AI) là gì? Những tiến bộ nào góp phần dẫn đến cuộc cách mạng AI?

   3. Học là gì? Học máy (machine learning; ML) là gì? Vị trí của ML trong AI? Kiến thức kỹ năng có thể được biểu diễn trong máy tính ra sao?


# Câu trả lời:



**Câu 4: Các thành phần cơ bản (TEFPA như trong bài giảng) cần được mô tả và cung cấp để máy tính tự học cách giải quyết một tác vụ là gì?**

TEFPA là từ viết tắt của 5 bước

1. **Task (T)** : mô tả tác vụ, đầu vào và đầu ra của ứng dụng
2. **Experience (E)** : tập dữ liệu thể hiện của tác vụ. Là tập hợp các bộ dữ liệu đầu vào và đầu ra trong thực tế.
3. **Function Space (F)** : không gian các hàm số
4. **Perfomance Measure (P)** : Đánh giá chất lượng, kết quả
5. **Search Algorithm (A)** : Tìm kiếm thuật toán. Tìm kiếm hàm biểu diễn


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


