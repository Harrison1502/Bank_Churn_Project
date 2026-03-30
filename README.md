# Dự báo Tỷ lệ Khách hàng Rời bỏ (Bank Customer Churn Prediction)

## Giới thiệu Dự án
Dự án này sử dụng các kỹ thuật **Phân tích Dữ liệu Khám phá (EDA)** và mô hình Học máy **Random Forest** để phân tích hành vi khách hàng và dự đoán khả năng rời bỏ dịch vụ (Churn) của một ngân hàng. 

Mục tiêu cốt lõi không chỉ là xây dựng mô hình có độ chính xác cao, mà còn rút ra các **Business Insights (Ghi nhận Kinh doanh)** nhằm giúp ngân hàng tối ưu hóa chiến dịch giữ chân khách hàng.

---

## Công cụ & Thư viện sử dụng
* **Ngôn ngữ:** Python
* **Xử lý dữ liệu:** Pandas, NumPy
* **Trực quan hóa:** Matplotlib, Seaborn
* **Mô hình Machine Learning:** Scikit-learn (Random Forest Classifier)

---
![dashboard](https://github.com/Harrison1502/Bank_Churn_Project/blob/main/dashboard.png?raw=true)
## Kết luận & Đề xuất Kinh doanh (Business Insights)

### 1. Tỷ lệ rời bỏ tổng thể & Trạng thái hoạt động
* **Quan sát:** Tỷ lệ khách hàng rời bỏ ngân hàng hiện đang ở mức khá cao: **20.4%**. Đặc biệt, nhóm khách hàng không thường xuyên hoạt động (Inactive) có tỷ lệ rời bỏ lên tới **26.9%**, gần gấp đôi so với nhóm đang hoạt động (14.3%).
* **Ý nghĩa:** Việc mất đi 1/5 lượng khách hàng là một "báo động đỏ" ảnh hưởng trực tiếp đến doanh thu. Sự thiếu gắn kết với hệ sinh thái của ngân hàng là nguyên nhân trực tiếp dẫn đến việc khách hàng đóng tài khoản.
* **Đề xuất:** Cần triển khai ngay các chiến dịch Marketing tự động (Gửi email nhắc nhở, tặng voucher qua thông báo đẩy - Push Notifications) nhằm kích hoạt lại các khách hàng đang "ngủ đông" trước khi họ thực sự rời đi.

### 2. Điểm nóng về Địa lý (Vấn đề tại thị trường Đức)
* **Quan sát:** Mặc dù tệp khách hàng tại Đức nhỏ hơn Pháp, nhưng tỷ lệ rời bỏ tại thị trường này lại cao đột biến, chạm mức **32.4%** (gấp đôi so với mức ~16% của Pháp và Tây Ban Nha).
* **Ý nghĩa:** Đang có một vấn đề cục bộ xảy ra riêng tại thị trường Đức. Nguyên nhân có thể đến từ sự cạnh tranh gắt gao của các ngân hàng nội địa, chất lượng dịch vụ chăm sóc khách hàng, hoặc chính sách phí không phù hợp với người Đức.
* **Đề xuất:** Thực hiện ngay một cuộc khảo sát chuyên sâu (Deep-dive qualitative analysis) nhằm vào nhóm khách hàng Đức đã rời đi. Đồng thời rà soát lại các gói dịch vụ của đối thủ cạnh tranh trực tiếp tại khu vực này.

### 3. Sự dịch chuyển Nhân khẩu học (Tuổi tác & Giới tính)
* **Quan sát:** Độ tuổi trung bình của khách hàng rời đi là khoảng **45 tuổi**, cao hơn rõ rệt so với nhóm ở lại (khoảng 37 tuổi). Thêm vào đó, khách hàng Nữ có tỷ lệ rời bỏ (**25.1%**) cao hơn đáng kể so với Nam giới (16.5%).
* **Ý nghĩa:** Hệ sinh thái sản phẩm tài chính hiện tại có vẻ đang phục vụ rất tốt cho tệp khách hàng Nam, trẻ tuổi. Tuy nhiên, nó lại đang thất bại trong việc đáp ứng nhu cầu quản lý tài sản của nhóm khách hàng Nữ giới và độ tuổi trung niên.
* **Đề xuất:** Đa dạng hóa danh mục sản phẩm. Nghiên cứu và tung ra các gói dịch vụ tài chính được thiết kế riêng cho nhu cầu của độ tuổi trung niên và phái nữ (Ví dụ: Các gói tiết kiệm hưu trí, bảo hiểm sức khỏe gia đình, hoặc quỹ đầu tư an toàn).

Contact me: https://www.linkedin.com/in/harrison1502/
