# USING RFM METHOD TO GROUP CUSTOMER SEGMENTATIONS BASED ON SALE DATA

## Giới thiệu
Dự án này sử dụng mô hình RFM để phân tích và phân loại khách hàng dựa trên hành vi mua sắm. Thông qua thuật toán K-Means và các phương pháp trực quan hóa, hệ thống giúp doanh nghiệp xác định nhóm khách hàng tiềm năng và đề xuất chiến lược tiếp thị phù hợp.

## Cài đặt
Trước khi chạy dự án, hãy cài đặt các thư viện cần thiết bằng lệnh sau:
```sh
pip install pandas matplotlib seaborn scikit-learn

## Hướng dẫn sử dụng
1. **Chuẩn bị dữ liệu**: Đảm bảo có file dữ liệu CSV với các thông tin cần thiết như mã khách hàng, ngày giao dịch, số lần mua hàng, tổng chi tiêu, v.v.
2. **Chạy script phân tích**: python main.py
3. **Xem kết quả**: Các biểu đồ trực quan sẽ được tạo ra để hỗ trợ phân tích dữ liệu.

## Các bước thực hiện
1. Đọc và tiền xử lý dữ liệu CSV.
2. Tính toán các chỉ số RFM.
3. Chuẩn hóa dữ liệu.
4. Phân cụm khách hàng bằng K-Means.
5. Đánh giá kết quả phân cụm.
6. Trực quan hóa dữ liệu.

## Kết quả mong đợi
- Xác định được nhóm khách hàng tiềm năng dựa trên chỉ số RFM.
- Cung cấp dữ liệu hỗ trợ các chiến lược tiếp thị hiệu quả hơn.
- Trực quan hóa dữ liệu giúp dễ dàng đưa ra quyết định.

## Liên hệ
Nếu có bất kỳ câu hỏi hoặc góp ý nào, vui lòng liên hệ qua email hoặc diễn đàn thảo luận của nhóm.


