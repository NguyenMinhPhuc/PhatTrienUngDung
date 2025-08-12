\# Quy trình chi tiết Giai đoạn 1 \& 2: Phát triển Ứng dụng



---



\## \*\*Giai đoạn 1: Phân tích Yêu cầu \& Lên Kế hoạch (Requirement Analysis \& Planning)\*\*



\*\*Mục tiêu:\*\* Trả lời câu hỏi: "Chúng ta sẽ xây dựng cái gì và cho ai?". Đây là bước khám phá và xác định phạm vi dự án.



\### \*\*Bước 1.1: Xác định Ý tưởng và Mục tiêu Sản phẩm\*\*



\* \*\*Mục đích:\*\* Làm rõ giá trị cốt lõi mà ứng dụng của bạn mang lại.

\* \*\*Hành động:\*\*

&nbsp;   \* Brainstorm ý tưởng: Nghĩ về một vấn đề bạn hoặc bạn bè hay gặp phải.

&nbsp;   \* Viết Tuyên bố Tầm nhìn (Vision Statement).

\* \*\*Kết quả cần đạt:\*\* Một đoạn văn ngắn gọn, súc tích mô tả chính xác về ứng dụng.



\*\*Template: Tuyên bố Tầm nhìn\*\*



> \*\*Ví dụ: Ứng dụng "Course Picker"\*\*

>

> \* \*\*DÀNH CHO\*\* sinh viên đại học.

> \* \*\*AI CÓ\*\* nhu cầu tìm kiếm và đánh giá các khóa học tự chọn một cách dễ dàng.

> \* \*\*ỨNG DỤNG CỦA CHÚNG TÔI LÀ\*\* "Course Picker", một nền tảng đánh giá khóa học.

> \* \*\*CUNG CẤP\*\* thông tin tổng hợp, review từ các sinh viên đi trước và gợi ý khóa học phù hợp.

> \* \*\*KHÁC VỚI\*\* việc hỏi thông tin trên các group Facebook hoặc từ bạn bè.

> \* \*\*Ở CHỖ\*\* thông tin được hệ thống hóa, đáng tin cậy và có công cụ tìm kiếm thông minh.



---



\### \*\*Bước 1.2: Phân tích Người dùng \& Đối thủ\*\*



\* \*\*Mục đích:\*\* Hiểu người dùng để thiết kế cho đúng người, học hỏi từ đối thủ để làm tốt hơn.

\* \*\*Hành động:\*\*

&nbsp;   \* Phác thảo Chân dung Người dùng (User Persona).

&nbsp;   \* Phân tích Đối thủ cạnh tranh.

\* \*\*Kết quả cần đạt:\*\*

&nbsp;   \* 1-2 bản phác thảo User Persona.

&nbsp;   \* Bảng phân tích đối thủ cạnh tranh.



\*\*Template: User Persona (Chân dung Người dùng)\*\*



> \* \*\*Tên:\*\* Nguyễn Văn An

> \* \*\*Tuổi:\*\* 20

> \* \*\*Nghề nghiệp:\*\* Sinh viên năm 2, ĐH Bách Khoa

> \* \*\*Tiểu sử:\*\* An là một sinh viên năng động nhưng luôn gặp khó khăn mỗi khi đến kỳ đăng ký tín chỉ. Cậu không biết môn tự chọn nào hay, giảng viên nào dạy tốt.

> \* \*\*Mục tiêu:\*\* Tìm được môn học phù hợp với sở thích, không quá khó để qua môn và có thể sắp xếp thời khóa biểu hợp lý.

> \* \*\*Khó khăn:\*\* Thông tin về các môn học quá rời rạc, khó kiểm chứng.



\*\*Template: Bảng Phân tích Đối thủ\*\*



| Tên Ứng dụng Đối thủ | Điểm Mạnh | Điểm Yếu | Cơ hội cho ứng dụng của mình |

| :--- | :--- | :--- | :--- |

| \*\*Reviewdanhgia.com\*\* | - Nhiều review chi tiết.<br>- Cộng đồng lớn. | - Giao diện cũ, khó dùng.<br>- Không có trên di động.<br>- Nhiều quảng cáo. | - Phát triển ứng dụng di động.<br>- Giao diện hiện đại, tập trung vào UX.<br>- Thêm tính năng gợi ý thông minh. |

| \*\*Group FB trường\*\* | - Miễn phí.<br>- Thông tin nhanh. | - Thông tin trôi, khó tìm lại.<br>- Không có hệ thống, không đáng tin cậy. | - Hệ thống hóa và xác thực thông tin.<br>- Xây dựng bộ lọc và tìm kiếm mạnh mẽ. |



---



\### \*\*Bước 1.3: Xác định Tính năng và Tạo Product Backlog\*\*



\* \*\*Mục đích:\*\* Liệt kê tất cả các "viên gạch" cần xây cho ứng dụng.

\* \*\*Hành động:\*\*

&nbsp;   \* Viết User Story (Câu chuyện người dùng).

&nbsp;   \* Xác định MVP (Minimum Viable Product - Sản phẩm Khả dụng Tối thiểu).

\* \*\*Kết quả cần đạt:\*\*

&nbsp;   \* Một danh sách các User Story (Product Backlog), được sắp xếp ưu tiên.

&nbsp;   \* Danh sách các tính năng thuộc phạm vi MVP được đánh dấu rõ ràng.



\*\*Template: Product Backlog (với User Story)\*\*



> \*\*Tên ứng dụng: Course Picker\*\*



| ID | User Story | Mức ưu tiên | Ghi chú (MVP/Không) |

| :-- | :--- | :--- | :--- |

| \*\*F01\*\* | Là một người dùng, tôi muốn \*\*đăng ký/đăng nhập\*\* bằng tài khoản sinh viên để bảo mật thông tin. | \*\*Cao\*\* | \*\*MVP\*\* |

| \*\*F02\*\* | Là một người dùng, tôi muốn \*\*tìm kiếm\*\* khóa học theo tên hoặc mã môn học. | \*\*Cao\*\* | \*\*MVP\*\* |

| \*\*F03\*\* | Là một người dùng, tôi muốn \*\*xem chi tiết\*\* một khóa học, bao gồm mô tả, số tín chỉ và các đánh giá. | \*\*Cao\*\* | \*\*MVP\*\* |

| \*\*F04\*\* | Là một người dùng, tôi muốn \*\*gửi một đánh giá\*\* (review) cho một khóa học tôi đã tham gia. | \*\*Cao\*\* | \*\*MVP\*\* |

| \*\*F05\*\* | Là một người dùng, tôi muốn \*\*lọc\*\* các khóa học theo khoa hoặc giảng viên. | \*\*Trung bình\*\* | Không |

| \*\*F06\*\* | Là một người dùng, tôi muốn \*\*lưu lại\*\* các khóa học yêu thích để xem lại sau. | \*\*Trung bình\*\* | Không |

| \*\*F07\*\* | Là quản trị viên, tôi muốn \*\*quản lý\*\* danh sách các khóa học và các đánh giá. | \*\*Thấp\*\* | Không |



---

---



\## \*\*Giai đoạn 2: Thiết kế (Design)\*\*



\*\*Mục tiêu:\*\* Trả lời câu hỏi: "Ứng dụng sẽ trông như thế nào và hoạt động ra sao?". Đây là lúc biến ý tưởng thành bản vẽ chi tiết.



\### \*\*Bước 2.1: Thiết kế Luồng người dùng (User Flow)\*\*



\* \*\*Mục đích:\*\* Vẽ ra các con đường mà người dùng sẽ đi trong ứng dụng để hoàn thành một tác vụ.

\* \*\*Hành động:\*\* Vẽ một sơ đồ gồm các hộp (đại diện cho màn hình) và các mũi tên (đại diện cho hành động) để mô tả luồng.

\* \*\*Kết quả cần đạt:\*\* Sơ đồ luồng người dùng cho các tính năng chính.



\*\*Template: Sơ đồ User Flow (dạng văn bản)\*\*



> \*\*Luồng: Tìm kiếm và xem đánh giá khóa học\*\*

>

> 1.  \*\*\[Màn hình Trang chủ]\*\* -> Người dùng nhấn vào thanh tìm kiếm.

> 2.  \*\*\[Màn hình Tìm kiếm]\*\* -> Người dùng gõ "Phát triển ứng dụng" -> Nhấn "Tìm".

> 3.  \*\*\[Màn hình Kết quả Tìm kiếm]\*\* -> Hiển thị danh sách các khóa học liên quan -> Người dùng nhấn vào "Phát triển ứng dụng Web".

> 4.  \*\*\[Màn hình Chi tiết Khóa học]\*\* -> Hiển thị thông tin và tất cả đánh giá của khóa học đó.



\### \*\*Bước 2.2: Thiết kế Wireframe\*\*



\* \*\*Mục đích:\*\* Dựng "khung xương" cho từng màn hình, chỉ tập trung vào bố cục, vị trí các thành phần.

\* \*\*Hành động:\*\* Dùng giấy bút hoặc các công cụ online (như Figma, Balsamiq) để vẽ các màn hình chính.

\* \*\*Kết quả cần đạt:\*\* Một bộ Wireframe cho tất cả các màn hình trong phạm vi MVP.



\*\*Template: Wireframe (mô tả bằng văn bản)\*\*



> \*\*Màn hình: Chi tiết Khóa học\*\*

>

> \* \*\*Trên cùng:\*\* Tên Khóa học (chữ to).

> \* \*\*Dưới tên:\*\* Mã môn học, Số tín chỉ, Tên giảng viên.

> \* \*\*Khu vực chính:\*\*

>     \* Tab "Mô tả": Hiển thị nội dung mô tả chi tiết của môn học.

>     \* Tab "Đánh giá": Hiển thị danh sách các bài đánh giá. Mỗi bài đánh giá gồm:

>         \* Tên người đánh giá.

>         \* Số sao (1-5 sao).

>         \* Nội dung bình luận.

> \* \*\*Dưới cùng (nút nổi):\*\* Nút "Viết đánh giá".



\### \*\*Bước 2.3: Thiết kế Giao diện Người dùng (UI Mockup)\*\*



\* \*\*Mục đích:\*\* "Tô màu" và làm đẹp cho Wireframe, tạo ra một bản thiết kế cuối cùng trông giống hệt sản phẩm thật.

\* \*\*Hành động:\*\*

&nbsp;   \* Tạo Bảng màu \& Font chữ (Style Guide).

&nbsp;   \* Thiết kế Mockup hoàn chỉnh.

\* \*\*Kết quả cần đạt:\*\*

&nbsp;   \* Một bản Style Guide đơn giản.

&nbsp;   \* Bộ Mockup hoàn chỉnh cho các màn hình MVP.



\*\*Template: Style Guide đơn giản\*\*



> \* \*\*Màu chủ đạo (Primary):\*\* #4A90E2 (Xanh dương)

> \* \*\*Màu phụ (Secondary):\*\* #F5A623 (Vàng cam)

> \* \*\*Màu văn bản:\*\* #4A4A4A (Xám đậm)

> \* \*\*Màu nền:\*\* #FFFFFF (Trắng)

> \* \*\*Font chữ chính:\*\* Inter (cho tiêu đề và nội dung) chuyển nội dung sang file word

