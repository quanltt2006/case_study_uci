# Heart Disease Diagnostic Optimization: A Cost-Efficiency & Statistical Perspective



## 📌 Tổng quan dự án

Trong y tế, việc yêu cầu bệnh nhân thực hiện tất cả các xét nghiệm không chỉ gây lãng phí tài chính mà còn có thể dẫn đến các can thiệp xâm lấn không cần thiết. Dự án này giải quyết vấn đề đó thông qua 4 trụ cột chính:

1.  **Phân tầng chi phí (Diagnostic Tiers):** Chia các đặc trưng (features) thành các cấp độ từ sàng lọc rẻ tiền đến chẩn đoán chuyên sâu/xâm lấn.
2.  **Đánh giá tầm quan trọng:** Sử dụng *Permutation Importance* để xác định các chỉ số có giá trị dự báo cao nhất so với chi phí bỏ ra.
3.  **Kiểm chứng thống kê:** Minh họa Định lý Giới hạn Trung tâm (CLT) để đảm bảo tính ổn định và độ tin cậy của các tham số lâm sàng.
4.  **Đề xuất quy trình quyết định:** Xây dựng sơ đồ luồng (Clinical Flowchart) hỗ trợ bác sĩ ra quyết định dựa trên xác suất bệnh.

---

## 🛠 Công nghệ sử dụng

*   **Ngôn ngữ:** ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
*   **Thư viện phân tích:** `Pandas`, `Numpy`, `Matplotlib`, `Seaborn`.
*   **Máy học:** `Scikit-learn` (Mô hình KNN, Random Forest, Permutation Importance).
*   **Thống kê:** Bootstrap Resampling, CLT Simulation.

---
