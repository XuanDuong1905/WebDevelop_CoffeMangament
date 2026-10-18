# AI-LOG.md — Hệ thống đặt món tại quán cà phê (CSC13008)

## 2026-10-15 — TV1: Xây dựng bối cảnh giả định cho bài toán

- **Member:** Cao Xuân Dương — 24120292
- **Tool:** ChatGPT
- **Asked for:** Từ chủ đề quản lý quán cà phê đã chọn, đề xuất bối cảnh giả định và những khó khăn trong quy trình gọi món tại quán.
- **Kept:** Bối cảnh nhân viên ghi món thủ công, dễ thất lạc phiếu hoặc ghi thiếu món trong giờ cao điểm.
- **Changed:** Điều chỉnh nội dung để tập trung vào việc đặt món và phối hợp xử lý đơn tại bàn.
- **Rejected:** Đề xuất mở rộng sang giải quyết thêm vấn đề thanh toán vì vượt quá trọng tâm bài toán tôi muốn khai thác.
- **By hand:** Chọn chủ đề, xác định trọng tâm và quyết định những vấn đề được giữ trong bài toán.

## 2026-10-15 — TV1: Phân công công việc cho nhóm

- **Member:** Cao Xuân Dương — 24120292
- **Tool:** ChatGPT
- **Asked for:** Gợi ý chia việc để các thành viên có thể làm độc lập và hạn chế phải chờ đầu ra của nhau.
- **Kept:** Giao mỗi phần thiết kế màn hình kèm phần giải thích cho cùng một người, giúp thành viên chủ động hoàn thành đầu ra của mình.
- **Changed:** Chuyển nhiệm vụ tổng hợp và review bài về cho nhóm trưởng thực hiện.
- **Rejected:** Cách chia người thiết kế giao diện và người viết giải thích riêng vì tạo phụ thuộc giữa hai công việc.
- **By hand:** Điều chỉnh và chốt phân công cuối cùng; xác định trách nhiệm tổng hợp, kiểm tra bài của nhóm trưởng.

## 2026-10-15 — TV1: Lựa chọn luồng để thiết kế wireframe

- **Member:** Cao Xuân Dương — 24120292
- **Tool:** ChatGPT
- **Asked for:** Từ các luồng chính tôi đưa ra, gợi ý lựa chọn luồng quan trọng nhất để thể hiện bằng wireframe theo yêu cầu bài tập.
- **Kept:** Luồng khách xem thực đơn → kiểm tra và gửi đơn → theo dõi đơn, thể hiện qua ba màn hình liên tiếp.
- **Changed:** Thống nhất cách thể hiện luồng được chọn thành ba màn hình để phân công cho các thành viên.
- **Rejected:** Không sử dụng phương án chia thành hai luồng riêng, mỗi luồng ba màn hình, vì không phù hợp với cấu trúc bài nộp nhóm đang triển khai.
- **By hand:** Đưa ra các luồng nghiệp vụ ban đầu và quyết định luồng cuối cùng dùng cho wireframe.

## 2026-10-15 — TV1: Tạo template báo cáo chung

- **Member:** Cao Xuân Dương — 24120292
- **Tool:** ChatGPT
- **Asked for:** Từ phần mẫu tôi đã chuẩn bị và yêu cầu bài tập, tạo template Markdown để các thành viên bổ sung nội dung.
- **Kept:** Khung `PROPOSAL.md`, `AI-LOG.md` và `SELF_ASSESSMENT_REPORT.md`, gồm các mục cần điền và vị trí dẫn chứng.
- **Changed:** Yêu cầu điều chỉnh template theo phân công của nhóm, xác định phần mỗi thành viên cần hoàn thiện.
- **Rejected:** Thư mục `working/` và mục quy ước làm việc trong README vì tôi muốn cấu trúc repo ngắn gọn.
- **By hand:** Chuẩn bị phần mẫu, đưa ra yêu cầu chỉnh sửa, tạo base repository và push phiên bản đầu để các thành viên cùng làm.

## 2026-10-17 — TV2: S1 — Thực đơn

- **Member:** Trần Thiên Ân — 24120255
- **Tool:** Claude
- **Asked for:** Dựng wireframe HTML cho màn hình thực đơn (khổ 390×844) và viết đoạn giải thích S1 cho mục 4 và 6.
- **Kept:** Thanh tab nhóm món, nút + và bộ chỉnh −/+, khung chọn size/đá/đường/ghi chú, thanh giỏ hàng cố định ở đáy, nút "Theo dõi đơn" sang S3.
- **Changed:** Không có.
- **Rejected:** Bỏ giao diện hiển thị không cần thiết như bàn, các khung che.
- **By hand:** Đối chiếu hình với S3, kiểm tra mọi nút có đích đến và có trong văn bản.

## 2026-10-17 — TV2: S2 — Kiểm tra và gửi đơn

- **Member:** Trần Thiên Ân — 24120255
- **Tool:** Claude
- **Asked for:** Dựng wireframe HTML cho màn hình kiểm tra đơn và viết đoạn giải thích S2 cho mục 4 và 6.
- **Kept:** Danh sách món có −/+ và nút Xóa, ghi chú từng món và cả đơn, tổng tiền, nút "Gửi đơn", khung trạng thái giỏ trống.
- **Changed:** Thêm nút quay lại giỏ hàng của bạn.
- **Rejected:** Không có.
- **By hand:** Kiểm tra tổng tiền S2 khớp S1 (61.000đ), hỏi nhóm về bước duyệt đơn.

## 2026-10-17 — TV3: S3 — Theo dõi đơn (Screen in main flow)

- **Member:** Nguyễn Huỳnh Huy Phát — 24120406
- **Tool:** Gemini
- **Asked for:** Yêu cầu hỗ trợ thiết kế giao diện cho Màn hình Theo dõi đơn (S3).
- **Kept:** Toàn bộ cấu trúc và thiết kế mẫu ban đầu.
- **Changed:** Cập nhật và thay thế các đường dẫn hình ảnh bị lỗi hiển thị (lỗi 404).
- **Rejected:** Không có.
- **By hand:** Tự bổ sung thêm nút "←" ở góc trên để người dùng có thể điều hướng quay lại màn hình Menu.

## 2026-10-17 — TV3: S3 — Theo dõi đơn (Luồng hoạt động)

- **Member:** Nguyễn Huỳnh Huy Phát — 24120406
- **Tool:** ChatGPT
- **Asked for:** Yêu cầu chỉnh sửa lời văn cho phần luồng hoạt động và giải thích giao diện đã viết.
- **Kept:** Toàn bộ nội dung và ý chính đã được tạo ra.
- **Changed:** Không có.
- **Rejected:** Lược bỏ các chi tiết mô tả tương tác không cần thiết giữa nhân viên pha chế và nhân viên phục vụ trong luồng hoạt động.
- **By hand:** Không có.
