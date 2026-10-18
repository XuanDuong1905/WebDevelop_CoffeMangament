# AI-LOG.md — Hệ thống đặt món tại quán cà phê (CSC13008)

> Ghi một entry cho mỗi nhiệm vụ có sử dụng AI và cập nhật trong quá trình làm. Điền đúng thực tế, không ghi nhận nội dung chưa thực hiện. Có thể sao chép entry để bổ sung nhiệm vụ mới; xóa hướng dẫn và các entry chưa dùng trước khi nộp.
>
> Giữ nguyên các nhãn bên dưới. Nêu cụ thể nội dung tự làm và nội dung đã loại bỏ; nếu không có, ghi rõ “Không có”. Không đưa API key, dữ liệu người dùng thật hoặc bài của bạn học vào prompt.

## <YYYY-MM-DD> — TV1: Phân công và cấu trúc bài nộp

Member: <Họ tên — MSSV>
Tool: <Tên công cụ>
Asked for: <Yêu cầu hỗ trợ phân công hoặc tổ chức các file bài nộp.>
Kept: <Cấu trúc hoặc cách chia việc thực tế đã giữ lại.>
Changed: <Nội dung đã yêu cầu sửa hoặc tự sửa và lý do.>
Rejected: <Phương án đã loại bỏ và lý do.>
By hand: <Quyết định, nội dung hoặc thao tác tự thực hiện.>

## <YYYY-MM-DD> — TV1: Bài toán, người dùng và scope

Member: <Họ tên — MSSV>
Tool: <Tên công cụ hoặc none>
Asked for: <Yêu cầu hỗ trợ cụ thể đối với mục 1, 2, 3, 5 của PROPOSAL.md hoặc tạo khung proposal.>
Kept: <Nội dung AI đề xuất thực tế được sử dụng.>
Changed: <Nội dung đã chỉnh để phù hợp bài toán và nguồn lực nhóm; nêu lý do.>
Rejected: <Nội dung hoặc chức năng đề xuất đã loại bỏ; nêu lý do.>
By hand: <Phần tự viết, tự xác định hoặc tự kiểm tra.>

## 2026-10-17 — TV2: S1 — Thực đơn

Member: <Trần Thiên Ân — 24120255>
Tool: Claude
Asked for: Dựng wireframe HTML cho màn hình thực đơn (khổ 390×844) và viết đoạn giải thích S1 cho mục 4 và 6.
Kept: Thanh tab nhóm món, nút + và bộ chỉnh −/+, khung chọn size/đá/đường/ghi chú, thanh giỏ hàng cố định ở đáy, nút "Theo dõi đơn" sang S3.
Changed: Không có.
Rejected: Bỏ giao diện hiển thị không cần thiết như bàn, các khung che.
By hand: đối chiếu hình với S3, kiểm tra mọi nút có đích đến và có trong văn bản

## 2026-10-17 — TV2: S2 — Kiểm tra và gửi đơn

Member: <Trần Thiên Ân — 24120255>
Tool: Claude
Asked for: Dựng wireframe HTML cho màn hình kiểm tra đơn và viết đoạn giải thích S2 cho mục 4 và 6.
Kept: Danh sách món có −/+ và nút Xóa, ghi chú từng món và cả đơn, tổng tiền, nút "Gửi đơn", khung trạng thái giỏ trống.
Changed: Thêm nút quay lại giỏ hàng của bạn
Rejected: Không có
By hand: kiểm tra tổng tiền S2 khớp S1 (61.000đ), hỏi nhóm về bước duyệt đơn.

## 2026-10-17 — TV3: S3 — Theo dõi đơn (Screen in main flow)

Member: Nguyễn Huỳnh Huy Phát - 24120406  
Tool: Gemini  
Asked for: Yêu cầu hỗ trợ thiết kế giao diện cho Màn hình Theo dõi đơn (S3)  
Kept: Toàn bộ cấu trúc và thiết kế mẫu ban đầu  
Changed: Cập nhật và thay thế các đường dẫn hình ảnh bị lỗi hiển thị (lỗi 404)  
Rejected: Không có  
By hand: Tự bổ sung thêm nút "←" ở góc trên để người dùng có thể điều hướng quay lại màn hình Menu  

## 2026-10-17 — TV3: S3 — Theo dõi đơn (Luồng hoạt động)

Member: Nguyễn Huỳnh Huy Phát - 24120406  
Tool: ChatGPT  
Asked for: Yêu cầu chỉnh sửa lời văn cho phần luồng hoạt động và giải thích giao diện đã viết  
Kept: Toàn bộ nội dung và ý chính đã được tạo ra  
Changed: Không có  
Rejected: Lượt bỏ các chi tiết mô tả tương tác không cần thiết giữa nhân viên pha chế và nhân viên phục vụ trong luồng hoạt động  
By hand: Không có  

## <YYYY-MM-DD> — <TV phụ trách>: AI log, tự đánh giá hoặc kiểm tra bài nộp

Member: <Họ tên — MSSV>
Tool: <Tên công cụ hoặc none>
Asked for: <Nhiệm vụ cụ thể, chẳng hạn tạo template AI-LOG.md hoặc đối chiếu bài nộp với rubric.>
Kept: <Cấu trúc, nội dung hoặc nhận xét thực tế đã sử dụng.>
Changed: <Nội dung đã sửa sau khi kiểm tra sản phẩm thực tế và lý do.>
Rejected: <Nhận xét hoặc đề xuất đã loại bỏ và lý do.>
By hand: <Dẫn chứng, đánh giá hoặc thao tác tự thực hiện.>

<!-- Nếu một nhiệm vụ hoàn toàn không dùng AI, có thể thay entry tương ứng bằng dạng ngắn:
## YYYY-MM-DD — Tên nhiệm vụ
Member: Họ tên — MSSV
Tool: none. Tự thực hiện [nội dung cụ thể].
-->
