# [Vận dụng cơ bản - 2] PHÂN LOẠI VÀ SỬA BIÊN BẢN SPRINT RETROSPECTIVE

> 👤 **Học viên:** Đỗ Hoàng Sơn | **Mã SV:** PTIT-HCM-066
> 🏫 **Môn học:** IT206-K25-Agile-va-Scrum

---

## Phần 1: Phân loại ý kiến

Trong buổi Sprint Retrospective của Sprint 11, nhóm đã tổng hợp các ý kiến Start-Stop-Continue nhưng có sự nhầm lẫn giữa phản hồi về sản phẩm (tính năng, chỉ số) và cách thức làm việc của đội ngũ. Dưới đây là bảng phân loại chi tiết và phương án xử lý cho từng ý kiến từ R-01 đến R-07:

| Mã | Cách làm việc / Phản hồi sản phẩm / Cần làm rõ | Hướng xử lý và Viết lại |
| --- | --- | --- |
| R-01 | Phản hồi sản phẩm | Chuyển nơi xử lý: Đưa ý kiến này vào Product Backlog để Product Owner và khách hàng xem xét tính năng tự hủy đơn trên mạng xã hội. |
| R-02 | Cần làm rõ | Viết lại: Mơ hồ, cần cụ thể hóa thành hành động đo lường được trong giao tiếp hàng ngày. |
| R-03 | Cách làm việc | Viết lại: 'Khi cần thay đổi quy tắc chuyển người, nhóm cần thảo luận chung trong Daily Standup hoặc qua kênh chat nhóm trước khi áp dụng, tránh việc một cá nhân tự thay đổi khiến người khác bị động.' |
| R-04 | Cách làm việc | Giữ lại ở cột Stop: Việc thay đổi quy tắc qua tin nhắn riêng gây khó khăn cho việc tra cứu; cần dừng cách làm này và quy định mọi thay đổi phải đi kèm cập nhật tài liệu chung ngay lập tức. |
| R-05 | Cách làm việc | Giữ lại ở cột Continue: Đây là cách làm việc rất tốt trong việc phối hợp giữa Tester (Khánh Vy) và Developer (Nam) khi tái hiện lỗi, nhóm cần tiếp tục phát huy. |
| R-06 | Phản hồi sản phẩm | Chuyển nơi xử lý: Tỷ lệ AI tự trả lời 90% là chỉ số chất lượng sản phẩm (KPIs của PO và đội AI), không phải hành vi cải tiến cách làm việc của Scrum Team trong Sprint tới. |
| R-07 | Cần làm rõ | Chuyển nơi xử lý hoặc viết lại: Viết tắt bỏ tiêu chí Definition of Done chỉ để chạy theo tiến độ là vi phạm quy tắc Scrum (hạ chuẩn chất lượng). Cần đưa vào Product Backlog để cân nhắc lại phạm vi công việc thay vì bớt tiêu chí chất lượng. |

## Phần 2: Sửa Improvement

Rà soát 4 Improvement được đề xuất ban đầu (IM-11-01 đến IM-11-04), nhóm đã lọc ra và chuẩn hóa lại các hành động cải tiến đảm bảo đủ các tiêu chí: cụ thể, có người theo dõi, có thời điểm kiểm tra và có bằng chứng rõ ràng.

Dưới đây là bảng 2 Improvement chính thức được chọn để thực hiện trong Sprint tới:

Cách xử lý Improvement cũ (IM-10-02): Ở Sprint 10, việc chạy Integration Test vào Ngày 8 thay vì Ngày 4 chưa hoàn thành do thiếu chuẩn bị. Nhóm không được bỏ qua cũng không được chỉ đơn thuần gia hạn sang Sprint sau. Cụ thể, nhóm thống nhất đưa tác vụ viết kịch bản Integration Test lên đầu Sprint 11, đồng thời Khánh Vy sẽ tham gia từ Ngày 2 để gỡ vướng về quyền truy cập môi trường thử nghiệm.

| Hành động | Người/nhóm theo dõi | Khi kiểm tra | Bằng chứng |
| --- | --- | --- | --- |
| IM-11-04: Khi đổi quy tắc chuyển người, nhóm phải cập nhật tài liệu chung trước khi triển khai chính thức. | Nam | Ngày cuối Sprint 11 | Đường dẫn phiên bản tài liệu chung đã được cập nhật lịch sử chỉnh sửa. |
| IM-11-05: Chạy Integration Test không muộn hơn Ngày 4 của Sprint, dựa trên việc kế thừa và hoàn thành dở dang IM-10-02. | Khánh Vy | Ngày 4 của Sprint 11 | Báo cáo kết quả chạy Integration Test trên hệ thống CI/CD. |

## Phần 3: Nhận xét cách điều phối

Qua quan sát cách thức diễn ra buổi Sprint Retrospective, cách điều phối của Scrum Master và Product Owner tồn tại hai điểm bất hợp lý lớn ảnh hưởng trực tiếp đến tinh thần cởi mở và quyền tự quyết của đội ngũ:

1. Scrum Master mở đầu bằng câu hỏi mang tính quy chụp và tìm thủ phạm: 'Ai đã làm sáu khiếu nại bị phân loại sai?'. Cách đặt câu hỏi này vi phạm nghiêm trọng nguyên tắc cốt lõi của Scrum Retrospective là hướng đến cải tiến quy trình và hệ thống chứ không đổ lỗi cá nhân. Hậu quả là ngay sau khi tên một thành viên xuất hiện trên bảng, các thành viên còn lại sợ hãi và ngừng phát biểu hoàn toàn.

2. Product Owner lấn quyền tự quyết của Scrum Team bằng cách tự mình trả lời từng ý kiến và tự chọn giải pháp thay vì để nhóm thảo luận và đồng thuận. Điều này làm mất đi quyền làm chủ (ownership) của Developers đối với quy trình làm việc của chính họ, khiến buổi họp mất đi ý nghĩa cải tiến nội bộ.

- Tác động tiêu cực: Tạo tâm lý phòng thủ, sợ sai, sợ bị chỉ trích, dẫn đến việc giấu lỗi trong các Sprint sau.
- Tác động tiêu cực: Làm giảm động lực làm việc và sự cam kết của Scrum Team đối với các hành động cải tiến.

---

## 📁 Danh sách tệp tin nộp bài trong Repository
- 📝 `bt2.docx`: Báo cáo tài liệu phân tích nghiệp vụ hoàn chỉnh.
