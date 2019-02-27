# Câu hỏi:

   1. Trí tuệ là gì? Đọc thêm bài viết 9 loại trí thông minh, có thể xem thêm bài giảng của Ted Ed và làm quiz (tiếng Anh). 

   2. Trí tuệ nhân tạo (artificial intelligence, AI) là gì? Những tiến bộ nào góp phần dẫn đến cuộc cách mạng AI?

   3. Học là gì? Học máy (machine learning; ML) là gì? Vị trí của ML trong AI? Kiến thức kỹ năng có thể được biểu diễn trong máy tính ra sao?

   4. Các thành phần cơ bản (TEFPA như trong bài giảng) cần được mô tả và cung cấp để máy tính tự học cách giải quyết một tác vụ là gì?

   5. Mô tả:

      tác vụ (đầu vào và đầu ra là gì)
      kinh nghiệm/dữ liệu cần chuẩn bị (cần thu thập dữ liệu gì, cách thu thập ra sao, trong bao lâu, cần ai giúp đỡ việc gì, mức độ khó khăn về thời gian công sức trang thiết bị v.v.) 
      cách thức đánh giá chất lượng đầu ra 
         cho các ứng dụng sau: 

      a) máy tính chuyển 1 tấm ảnh chất lượng kém (mờ, low-resolution) lên thành ảnh rõ nét (high-resolution); 

      b) máy tính xử lý ảnh chụp X-quang và dự đoán bệnh; 

      c) máy tính đọc một email của khách hàng và tự chuyển đến thư mục tương ứng như "cảm ơn", "khiếu nại", "hỏi thông tin", "xin việc", v.v. 

   6. Ý nghĩa câu phát biểu sau: Máy tính "học'' bằng cách tìm kiếm trong không gian các hàm số (chương trình máy tính).

   7. Hai vấn đề chính về không gian hàm mà ta cần đặc biệt chú ý để giúp máy tính tự tìm kiếm hàm có độ khái quát hoá cao là gì?

   8. Chia sẻ với bạn bè về các điều mà học viên thấy lý thú qua bài giảng này.

# Câu trả lời:
   5. Mô tả tác vụ (đầu vào, đầu ra của một số ứng dụng
   a) máy tính chuyển 1 tấm ảnh chất lượng kém (mờ, low-resolution) lên thành ảnh rõ nét (high-resolution)
      Đầu vào là các dữ liệu hình ảnh, đầu ra là dữ liệu các hình ảnh đã được xử lý.
      Dữ liệu cần chuẩn bị là số lượng lớn các cặp ảnh low-resolution và ảnh high-resolution tương ứng. Hiện tại chưa xác định được cách tìm nguồn dữ liệu là các cặp ảnh low-resolution và high resolution tương ứng.
   b) Máy tính xử lý ảnh chụp X-quang và dự đoán bệnh
      Đầu vào là các bức hình X-quang và đầu ra là các đoạn văn bản có nội dung về dự đoán bệnh có khả năng. Có thể mong muốn là dự đoán một số dầu hiệu bệnh kèm theo chỉ số khả năng bao nhiêu phần trăm là bệnh A, bao nhiêu phần trăm là bệnh B
      - Dữ liệu chuẩn bị:
      Các ảnh chụp x-quang và các bệnh thực tế của các đối tượng được chụp các bức hình x-quang đấy.
      - Nguồn thu thập dữ liệu:
      Từ các bệnh viện, phòng khám. Tuy nhiên hồ sơ bệnh án là các dự liệu vô cùng nhạy càm, cần sự hợp tác của các bệnh viện, phòng khám về thông tin dữ liệu. Bảo vệ thông tin cá nhân, dữ liệu chỉ cần random các cặp ảnh chụp và bệnh thực tế của người chụp, không lấy thông tin cá nhân bất kỳ được asign vào cho các bức hình đấy.
   c) Máy tính đọc một email của khách hàng và tự chuyển tới các mục tương ứng như "cảm ơn", "khiếu nại", "hỏi thông tin",....
      Đầu vào các đoạn văn bản email, đầu ra là mảng các nhóm chỉ số phù hợp với danh sách các category cho trước. Ví dụ mình sẽ có các nhóm category như trên là "cảm ơn", "khiếu nại", "hỏi thông tin", "khác". Vậy đầu ra của ứng dụng này sẽ là 1 mảng dữ liệu cho biết email này phù hợp với "cảm ơn" là bao nhiêu phần trăm, "khiếu nại" bao nhiêu phần trăm?,...
      Dữ liệu chuẩn bị:
      Các cặp email và kết quả đã được đánh dấu theo các nhóm nội dung tương ứng. Việc có dữ liệu này khó khăn trong thực tế vì nội dung email hoàn toàn mang tính riêng tư nên khó có thể được can thiệp. Có thể đề xuất bằng cách tạo ra một số lượng các đoạn email và đánh dấu nhóm nội dung tương ứng, tuy nhiên việc này sẽ rất hạn chế số lượng data có được và tốn chi phí thực hiện hiện.
