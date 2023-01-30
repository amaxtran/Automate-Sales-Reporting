# Automate_Sales_Reporting

Giới thiệu về dự án
---------------------
 - Bạn đang đang giữ vai trò là 1 Sale Analyst cho một doanh nghiệp thương mại điện tử, hiện giờ đang là thời điểm cuối năm bạn cần phải làm rất nhiều báo cáo. Bạn được trao cho một danh sách dữ liệu bán hàng thu thập trong một năm qua với số lượng từ 15.000 đến 20.000 giao dịch mỗi tháng, nhiệm vụ của bạn là làm một báo cáo cuối năm cho doanh nghiệp. Trong báo cáo bạn cần phải trả lời các câu hỏi quen thuộc sau:
Question:
---------------------
- What the best month for sales? How much was earned that months?
- What city has the best sales?
- What time should we display ads to maximize the likelihood of customer's buying product?
- What products are most often sold together?
- What product sold the most? Why do you think it sold the most?

Mỗi cuối tháng cuối năm bạn đều phải làm đi làm lại với các câu hỏi lặp đi lặp lại như thế này và đó tốn của bạn kha khá thời gian, chưa dự tính đến sai sót trong quá trình xử lý dữ liệu.
Vì thế chương trình Automate Sales Reporting sẽ giúp các bạn xử lý nhanh chống và chính xác.

**************************************************************************************************************************************
Giải quyết vấn đề:
---------------------
Bạn nhận được file dữ liệu của bán hàng trong năm 2019 với 12 file tương ứng với từng tháng, mỗi tháng từ 15.000 đến 20.000 giao dịch
Bước đầu tiền: Bạn phải xử lý gộp 12 file này thành 1 file annualSales2019.csv với tổng gần 200.000 giao dịch
- Câu 1: Để trả lời cho câu hỏi "What the best month for sales? How much was earned that months?" bạn chỉ cần tách tháng ra và sử dụng plot bar chart trên Matplotlib là sẽ có kết quả.
- Câu 2: Để trả lời cho câu hỏi "What city has the best sales?" làm tương tự câu câu 1 tách thành phố ra và sử dụng plot bar chart trên Matplotlib là sẽ có kết quả.
- Câu 3: Câu hỏi "What time should we display ads to maximize the likelihood of customer's buying product?" bạn cần xuất ra dữ liệu giờ và sử dụng plot bar chart trên Matplotlib là sẽ có kết quả. 
- Câu 4: Câu hỏi "What products are most often sold together?" bạn cần tìm ra các order ID giống nhau và tổng hợp các product của cùng order ID lại với nhau.
- Câu 5: Để trả lời câu "What product sold the most? Why do you think it sold the most?" ta cần tổng hợp tất cả các sản giống nhau lại.

**************************************************************************************************************************************
Phân tích kết quả:
---------------------
 - Câu 1: Tháng 12 với danh số cao nhất, lý do có thể do ngày cuối năm có những ngày lễ lớn, và các sản phẩm công nghệ thường tung ra sản phẩm mới dịp cuối năm.
 - Câu 2: Thành phố San Francisco có doanh số cao nhất, lý do có thể ở đây là nơi tập trung nhiều silicons valley và có nhiều kỹ sư sử dụng công nghệ.
 - Câu 3: Thời gian order nhiều nhất là 11am - 12am và 7pm, chúng ta cần chạy quảng cáo trước 30 - 60 phút 2 khung giờ trên.
 - Câu 4: Có được thông tin những sản phẩm bán chạy, doanh nghiệp có thể bán combo các sản phẩm bán chạy kèm theo 1 sản phẩm ít bán chạy hơn để đẩy nhanh doanh số của sản phẩm ít bán chạy hơn, hoặc đính kèm giảm giá 2 sản phẩm này để kích cầu tiêu dùng.
 - Câu 5: Ta có được kết quả sản phẩm có giá thành thấp sẽ bán được nhiều sản phẩm hơn và ngược lại sản phảm giá có sẽ có doanh thu tương đối thấp.

