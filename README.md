Heart Disease Diagnostic Optimization: A Cost-Efficiency & Statistical Perspective
Dự án này tập trung vào việc phân tích dữ liệu bệnh tim (Heart Disease dataset), tối ưu hóa quy trình chẩn đoán lâm sàng bằng cách cân bằng giữa độ chính xác của mô hình máy học và chi phí xét nghiệm thực tế.
📌 Tổng quan case study
Trong y tế, việc yêu cầu bệnh nhân thực hiện tất cả các xét nghiệm không chỉ gây lãng phí tài chính mà còn có thể gây ra các can thiệp xâm lấn không cần thiết. Dự án này giải quyết vấn đề đó thông qua:
Phân tầng chi phí (Diagnostic Tiers): Chia các đặc trưng (features) thành các cấp độ từ rẻ tiền đến đắt tiền/xâm lấn.
Đánh giá tầm quan trọng: Sử dụng Permutation Importance để tìm ra các chỉ số "đáng tiền" nhất.
Kiểm chứng thống kê: Minh họa Định lý Giới hạn Trung tâm (CLT) để đảm bảo tính tin cậy của các ước lượng lâm sàng.
Đề xuất quy trình quyết định: Một sơ đồ luồng (Clinical Flowchart) giúp bác sĩ quyết định khi nào cần làm thêm xét nghiệm.
🛠 Công nghệ sử dụng
Ngôn ngữ: Python (Pandas, Numpy, Scikit-learn, Seaborn).
Mô hình: K-Nearest Neighbors (KNN), Random Forest.
Thống kê: Permutation Test, Bootstrap Resampling (CLT Simulation).
