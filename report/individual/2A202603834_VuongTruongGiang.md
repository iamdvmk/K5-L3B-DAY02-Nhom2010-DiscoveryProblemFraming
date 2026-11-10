# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Vương Trường Giang 
- MSSV: 2A202603834
- Email trường (không bắt buộc, repo có thể để public): 26ai.giangvt@vinuni.edu.vn
- Tên nhóm: Nhóm 2010
- Link repo nhóm: https://github.com/iamdvmk/K5-L3B-DAY02-Nhom2010-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Cần đọc, tổng hợp nhiều thông tin|Khi nghiên cứu một chủ đề, tôi muốn rút ra ý chính và so sánh các giải pháp hiện có để lựa chọn hướng nghiên cứu phù hợp. |Người nghiên cứu |Cần đọc 4-10 bài báo, mỗi bài mất 30 phút đến 2 tiếng để đọc và tổng hợp. Thường phải đọc lại 2-3 lần những phần quan trọng |
| 2 | Pain từ người khác | Khi học sinh cần luyện tập thêm các dạng Toán tương tự, tôi muốn tạo nhanh nhiều đề mẫu dựa trên ma trận đề hoặc phiếu bài tập đã có để đáp ứng nhu cầu luyện tập mà không phải soạn từng đề từ đầu. | Gia sư, học sinh| Mỗi lần soạn đề khoảng 60 phút, mỗi tuần cần tạo 2-3 đề mới |
| 3 | Tốn thời gian |Khi muốn ứng tuyển một vị trí, tôi muốn điều chỉnh CV phù hợp với yêu cầu trong JD để làm nổi bật những kỹ năng và kinh nghiệm liên quan, tăng mức độ phù hợp của hồ sơ với vị trí ứng tuyển. | Người tìm việc, đặc biệt là sinh viên mới ra trường | Số JD đọc mỗi tuần 10-15, thời gian đọc JD và chỉnh sửa CV 15–30 phút cho mỗi vị trí |
| 4 | Cần đọc, tổng hợp nhiều thông tin | Khi đưa feed back cho các label của Math Expert, tôi muốn tự động kiểm tra tính đúng sai, logic của lời giải, ngữ pháp và các trường hợp biên trong code để phát hiện lỗi nhanh chóng, giảm thời gian đọc và rà soát thủ công. | Auditor | Mỗi bài được kiểm tra tính đúng và logic của lời giải, ngôn ngữ và code nếu có; mất khoảng 10 phút với bài thông thường và có thể 20-30 phút với bài toán có code hoặc lập luận phức tạp |
| 5 | Tốn thời gian | Khi phân tích các báo cáo tai nạn giao thông, tôi muốn trích xuất 11 trường thông tin quan trọng (về điều kiện môi trường, hạ tầng giao thông và các phương tiện liên quan), đồng thời gán cho mỗi trường một giá trị thuộc tập giá trị định trước để chuyển đổi nội dung báo cáo thành dữ liệu có cấu trúc và nhất quán. | Sinh viên nghiên cứu, nhà nghiên cứu xe tự hành | Mỗi báo cáo cần 12-15 phút để đọc và trích xuất. Quy mô nghiên cứu có thể cần tới 1000 báo cáo. |

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 |Trích xuất thông tin từ báo cáo tai nạn (#5) | Có dữ liệu cụ thể, quy trình lặp lại, 11 trường thông tin với tập giá trị định trước. Có thể đo độ chính xác và thời gian xử lý.| Xử lý báo cáo thiếu thông tin hoặc diễn đạt mơ hồ như thế nào? |
| 2 | Audit và đưa feedback cho Expert (#4) | Pain thực tế từ kinh nghiệm làm Auditor. Có nhiều tiêu chí kiểm tra và quy trình feedback, chỉnh sửa rõ ràng. | Feedback do AI tạo ra có đủ chính xác và hữu ích để Expert sửa lỗi không? |
| 3 | Cá nhân hóa CV theo JD (#3)| Pain trực tiếp khi tìm việc, nhiều sinh viên mới tốt nghiệp có thể gặp phải. Dễ đo thời gian và chất lượng đầu ra. | Thế nào là một CV thực sự phù hợp với JD? |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi phân tích các báo cáo tai nạn giao thông, tôi muốn trích xuất 11 trường thông tin quan trọng và gán cho mỗi trường một giá trị thuộc tập giá trị định trước, để chuyển đổi báo cáo dạng văn bản thành dữ liệu có cấu trúc phục vụ nghiên cứu xe tự hành. |
| Actor | Nhà nghiên cứu xe tự hành, sinh viên nghiên cứu, kỹ sư phân tích dữ liệu tai nạn. |
| Thời điểm / bối cảnh | 	Khi xây dựng bộ dữ liệu tai nạn từ các báo cáo của cảnh sát để phục vụ nghiên cứu và kiểm thử xe tự hành. |
| Quy trình hiện tại (3–7 bước) | 	1. Mở và đọc báo cáo tai nạn. · 2. Xác định các thông tin liên quan đến điều kiện môi trường, hạ tầng giao thông và phương tiện. · 3. Đối chiếu nội dung với 11 trường thông tin cần trích xuất. · 4. Gán giá trị phù hợp từ tập giá trị định trước. · 5. Đánh dấu thông tin thiếu hoặc không rõ ràng. · 6. Kiểm tra lại dữ liệu đã trích xuất với báo cáo gốc. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 4, khoảng 5 phút. |
| Impact (nếu không giải thì sao) | Giả định bộ dữ liệu nghiên cứu gồm 150 báo cáo, mỗi báo cáo có 11 trường cần xử lý, tương ứng 1.650 lượt xác định và gán giá trị. Với ước tính ban đầu 12–15 phút/báo cáo, tổng thời gian khoảng 30–37,5 giờ; cần đo lại trên mẫu thực tế.|
| Success metric (baseline → target) | Baseline ước tính: 12–15 phút/báo cáo. Mục tiêu: giảm ít nhất 50% thời gian trung bình, bao gồm thời gian người kiểm tra; đo tỷ lệ gán đúng và bỏ sót trên cùng bộ báo cáo có đáp án tham chiếu, so sánh với quy trình thủ công. Cần xác lập baseline chất lượng trước khi đặt ngưỡng cụ thể. |
| Phương án không dùng AI | Xây dựng biểu mẫu nhập liệu cố định, danh sách giá trị hợp lệ và checklist hướng dẫn trích xuất. Giúp chuẩn hóa đầu ra nhưng vẫn cần người đọc và phân loại từng báo cáo. |
| Giả thuyết về AI (nếu có) | 	LLM đọc báo cáo, trích xuất 11 trường, ánh xạ sang các giá trị định trước và trả về dữ liệu có cấu trúc. Những trường không đủ bằng chứng sẽ được đánh dấu để con người xác minh. |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```
[1. Đọc báo cáo]
       ↓
[2. Tìm thông tin liên quan]
       ↓
[3. Xác định 11 trường dữ liệu]
       ↓
[4. Ánh xạ sang giá trị định trước]  ← BOTTLENECK
       ↓
[5. Đánh dấu thông tin thiếu/mơ hồ]
       ↓
[6. Kiểm tra lại kết quả]
       ↓
[7. Lưu dữ liệu có cấu trúc]

```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi kiểm duyệt một bài tập hoặc template Toán do Expert biên soạn, tôi muốn nhanh chóng phát hiện lỗi và đưa ra feedback cụ thể, có dẫn chứng và hướng sửa để Expert có thể chỉnh sửa nội dung chính xác hơn. |
| Actor | 	Auditor, Expert |
| Thời điểm / bối cảnh | Khi nhận các template hoặc bài tập cần kiểm duyệt trước khi được đưa vào hệ thống giáo dục. |
| Quy trình hiện tại (3–7 bước) | 	1. Nhận bài tập và lời giải từ Expert. · 2. Đọc và tự kiểm tra tính đúng sai về mặt Toán học. · 3. Kiểm tra flow và tính logic của lời giải. · 4. Kiểm tra ngữ pháp và cách diễn đạt. · 5. Đọc và soi code để tìm lỗi logic, các trường hợp biên chưa được xử lý. · 6. Ghi nhận lỗi và vị trí xuất hiện. · 7. Viết feedback giải thích vấn đề và đề xuất hướng sửa cho Expert. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 7, khoảng 7 phút |
| Impact (nếu không giải thì sao) | Ước tính công đoạn tìm lỗi và viết feedback mất 8–12 phút/template thông thường, so với ước tính tổng khoảng 10 phút/template; các con số này cần được đo lại; bài có code hoặc lập luận phức tạp có thể mất 20–30 phút. Nếu kiểm duyệt 10 template/ngày, riêng công đoạn này tiêu tốn khoảng 80–120 phút/ngày. |
| Success metric (baseline → target) | Với template thông thường, giảm thời gian tìm lỗi và viết feedback từ 8–12 phút xuống 3–5 phút/template, tính cả thời gian kiểm tra lại; so sánh tỷ lệ bỏ sót lỗi và feedback sai với baseline thủ công trên cùng bộ mẫu có đáp án tham chiếu. Cần đo baseline trước khi đánh giá mục tiêu. |
| Phương án không dùng AI | Dùng checklist kiểm duyệt, mẫu feedback theo loại lỗi và bộ kiểm thử code cho các trường hợp biên. |
| Giả thuyết về AI (nếu có) | AI đề xuất lỗi, vị trí và feedback kèm căn cứ; Auditor kiểm tra tính đúng đắn và quyết định nội dung gửi Expert. |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```
[1. Nhận template từ Expert]
          ↓
[2. Check đúng/sai Toán học]
          ↓
[3. Check solution flow]
          ↓
[4. Check grammar]
          ↓
[5. Đọc và soi code, tìm edge cases]
          ↓
[6. Xác định vị trí và đánh giá lỗi]
          ↓
[7. Viết feedback cho Expert]  ← BOTTLENECK

```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi muốn ứng tuyển một vị trí, tôi muốn phân tích yêu cầu trong JD và điều chỉnh CV dựa trên những kỹ năng, kinh nghiệm thực tế của mình để làm nổi bật mức độ phù hợp với vị trí ứng tuyển. |
| Actor | Người tìm việc, sinh viên mới tốt nghiệp, ứng viên chuyển hướng nghề nghiệp. |
| Thời điểm / bối cảnh |Khi tìm kiếm và ứng tuyển nhiều vị trí có yêu cầu kỹ năng khác nhau. |
| Quy trình hiện tại (3–7 bước) | 1. Tìm và đọc JD. · 2. Xác định kỹ năng và kinh nghiệm nhà tuyển dụng yêu cầu. · 3. Đối chiếu với CV hiện tại. · 4. Xác định dự án, kinh nghiệm phù hợp cần nhấn mạnh. · 5. Viết lại hoặc điều chỉnh nội dung CV. · 6. Kiểm tra tính chính xác và định dạng. · 7. Gửi hồ sơ. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 5, mất khoảng 10 phút |
| Impact (nếu không giải thì sao) | Giả định tìm được 10–15 JD phù hợp mỗi tuần; dành 15–30 phút để phân tích yêu cầu và điều chỉnh CV cho mỗi vị trí. Có thể mất khoảng 2,5–7,5 giờ/tuần nếu thực hiện với tất cả các JD. |
| Success metric (baseline → target) | Baseline ước tính: 15–30 phút/vị trí cho việc đọc JD và điều chỉnh CV. Mục tiêu: dưới 10 phút/vị trí cho cùng phạm vi, bao gồm kiểm tra; người dùng đối chiếu từng đề xuất với CV gốc để bảo đảm không thêm kỹ năng hoặc kinh nghiệm không có thật. |
| Phương án không dùng AI | Xây dựng nhiều phiên bản CV theo từng nhóm công việc như Backend, AI/ML, Software Engineer; sử dụng checklist đối chiếu kỹ năng với JD. |
| Giả thuyết về AI (nếu có) | AI phân tích JD, đối chiếu với CV gốc, xác định những kỹ năng và dự án phù hợp, đề xuất nội dung cần thay đổi và tạo bản CV tùy chỉnh. Người dùng kiểm tra và xác nhận trước khi sử dụng. |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```
[1 Tìm và đọc JD]
       ↓
[2 Trích xuất yêu cầu tuyển dụng]
       ↓
[3 Đối chiếu với CV hiện tại]
       ↓
[4 Chọn kinh nghiệm phù hợp]  
       ↓
[5 Viết lại nội dung CV] ← BOTTLENECK
       ↓
[6 Kiểm tra và định dạng]
       ↓
[7 Gửi hồ sơ]
```

### Card muốn pitch nhất

- Card số: 1
- Vì sao: Quy trình có đầu ra gồm 11 trường và tập giá trị định trước, thuận tiện để kiểm tra chất lượng và thời gian xử lý.
- Câu hỏi muốn nhóm phản biện: Có đủ báo cáo và đáp án tham chiếu để đánh giá chất lượng, đặc biệt với thông tin thiếu hoặc mơ hồ, không?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Thời gian xử lý và quy mô 150 báo cáo chưa có bằng chứng đo thực tế.| Đồng ý| Ghi rõ đây là giả định; bổ sung việc cần đo lại trên mẫu báo cáo thực tế.  |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Tôi trình bày ba Problem Card cá nhân và giải thích lý do chọn từng vấn đề. | Sau khi thảo luận, nhóm đánh giá việc kiểm duyệt label của Math Expert là một vấn đề tiềm năng. |
| Phản biện bài của bạn khác | Tôi hỏi về tần suất ứng viên phải chỉnh CV theo từng JD, cách người học nhận ra phần kiến thức chưa hiểu và hạn chế của các công cụ tổng hợp tài liệu hiện có. | Các câu hỏi làm rõ điều cần kiểm chứng ở từng bài toán, gồm tần suất gặp vấn đề, dấu hiệu nhận biết và hạn chế của cách làm hiện tại. |
| Nhận phản biện | Bước nào tốn nhiều thời gian hơn, tìm lỗi hay viết feedback? | Tôi trình bày thời gian trung bình của từng bước, đồng thời làm rõ khi viết feedback cần gợi ý Expert cách sửa lỗi. |
| Gom cluster / cây OST | Tôi góp ý cách gom các vấn đề có nhu cầu tương đồng vào cùng một cụm. | Ý kiến của tôi giúp nhóm làm rõ căn cứ gom các vấn đề vào cùng một nhánh của cây OST. |
| Chọn candidate problem | Tôi tham gia chấm điểm từng bài toán trong danh sách của nhóm. | Điểm đánh giá của tôi được dùng cùng đánh giá của các thành viên khác để so sánh các bài toán ứng viên. |
| Kiểm chứng / research | Tôi tìm các giải pháp liên quan đến label gồm đề bài và lời giải có biến do code sinh ra, rồi đối chiếu từng giải pháp với các bước audit. | Bảng research có link đến STACK, Hypothesis và MathDebugger, giúp nhóm định hình các giải pháp hiện có |
| Quy trình nhóm | Tôi được phân công hỗ trợ Vũ mô tả quy trình kiểm duyệt trước và sau khi có công cụ hỗ trợ. | Phần tôi phụ trách hỗ trợ là đối chiếu các bước Auditor kiểm tra đề, lời giải và bộ số liệu do code sinh ra trong bảng before/after. |
| Problem Statement | Tôi được phân công hỗ trợ Minh Khánh viết Problem Statement v0 từ góc nhìn của Auditor. | Nội dung cần làm rõ trong v0 là khó khăn của Auditor khi xác minh cùng một mẫu lời giải trên nhiều bộ số liệu và chỉ ra trường hợp sai để Expert sửa. |
| Mức can thiệp AI | Tôi cung cấp bảng research từ CP4. Quốc Khánh và Vũ phụ trách đánh giá mức can thiệp AI ở CP6. | Bảng research là đầu vào để đối chiếu bước có thể kiểm tra bằng code với bước cần Auditor đánh giá lập luận. |
| Quyết định | Thảo luận về quyết định của nhóm. | Đảm bảo cả nhóm thống nhất ý kiến. |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Tôi dùng AI để rà soát lại các ý tưởng và Job Story của các thành viên. | AI giúp kiểm tra xem mỗi ý tưởng đã nêu rõ người gặp vấn đề, bối cảnh và nhu cầu hay chưa. | Không có | Tôi đối chiếu góp ý với nội dung và bối cảnh thực tế của từng bạn trước khi đề xuất chỉnh sửa. |
| CP2 Problem Card | Tôi nhờ AI tạo sườn Problem Card cho 3 bài toán. | AI giúp tôi tổ chức Job Story, quy trình hiện tại, tác động và chỉ số đánh giá. | AI tự xác định bottleneck khi chưa hiểu rõ bối cảnh và công việc thực tế. | Tôi điều chỉnh lại quy trình theo trải nghiệm của mình, ghi rõ bottleneck còn là giả định và cần đo thời gian từng bước để xác nhận. |
| CP4 Research | Tôi dùng AI để rà soát bảng research và đối chiếu các công cụ với bài toán nhóm. | AI giúp tìm thêm nguồn và gợi ý so sánh phạm vi áp dụng của từng công cụ. | Một số gợi ý ban đầu còn chung, chưa chú ý label gồm đề bài và lời giải có biến được lập trình để tạo nhiều bộ số liệu. | Tôi làm rõ cấu trúc label và kiểm tra lại nguồn để chọn các ví dụ sát hơn như STACK, Hypothesis và MathDebugger. |
| CP5 Quy trình | Tôi dùng AI để rà soát quy trình kiểm duyệt và gợi ý các cách hỗ trợ từng bước. | AI giúp liệt kê các bước có thể kiểm tra thêm và gợi ý những trường hợp biên của biến. | AI liệt kê nhiều phương pháp chưa phù hợp hoặc chưa đủ căn cứ để áp dụng. Chẳng hạn, AI có thể gợi ý kiểm thử bằng Hypothesis dù chưa xác định code của công ty có dùng Python và có môi trường tương thích hay không. | Tôi kiểm định lại từng gợi ý với cấu trúc label và quy trình thực tế, chỉ giữ những phương pháp phù hợp hoặc ghi rõ điều kiện cần kiểm tra trước khi áp dụng. |
| CP5–6 Problem Statement | Tôi dùng AI để rà soát Problem Statement do các thành viên xây dựng. | AI giúp kiểm tra câu mô tả đã nêu rõ người gặp vấn đề, bối cảnh, khó khăn và tác động chưa. | Không có | Tôi đối chiếu góp ý với vấn đề nhóm đã chọn và đề xuất chỉnh sửa khi cần. |
| CP6 Mức can thiệp / quyết định | Tôi dùng AI để kiểm tra lại lập luận của nhóm về mức can thiệp và quyết định. | AI giúp rà soát sự nhất quán giữa vấn đề, quy trình, rủi ro và mức can thiệp được đề xuất. | Không có | Tôi đối chiếu các góp ý với phần nghiên cứu và nội dung thảo luận của nhóm trước khi đưa ra nhận xét. |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác? Khi chọn vấn đề cần cân nhắc cả mức độ phức tạp và khả năng triển khai. Ví dụ, bài toán phát hiện trộm xe nghe rất thiết thực nhưng cần mô hình có độ chính xác cao. Ngoài ra, dữ liệu để xây dựng và kiểm thử cũng khó tìm, còn chi phí triển khai có thể lớn.**

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào? Có. Với bài toán ôn tập, ban đầu nhóm nghĩ ngay đến việc dùng AI hỗ trợ người học ôn các phần trọng tâm. Sau đó, nhóm nhận ra chưa làm rõ cách xác định người học đã hiểu phần nào và còn yếu phần nào. Nếu chỉ dựa vào nội dung đã học thì AI khó biết người học thực sự nắm được kiến thức đến đâu. Nhóm cần tìm hiểu thêm cách người học tự đánh giá và theo dõi việc học trước khi chọn giải pháp.**

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể. Có. Ban đầu tôi đánh giá cao bài toán trích xuất dữ liệu từ báo cáo thực tế vì nghĩ đây là công việc tốn nhiều thời gian và có thể lặp lại với số lượng lớn. Sau khi xem xét lại, tôi nhận ra không có nhiều người phải thực hiện công việc này theo cách thủ công. Điều đó khiến tôi cân nhắc lại quy mô nhu cầu, thay vì chỉ dựa vào việc mỗi báo cáo mất bao lâu để xử lý**

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì? Khi tìm hiểu bài toán audit label, tôi thấy dạng dữ liệu mà công ty tôi sử dụng khá đặc thù. Mỗi label gồm đề bài và lời giải, trong đó có code tạo ra nhiều bộ số liệu. Tôi tìm được một số công cụ giải quyết từng phần tương tự, nhưng chưa thấy giải pháp nào phù hợp trực tiếp với toàn bộ quy trình của công ty. Điều này khiến tôi nhận ra giải pháp có thể chỉ phù hợp trong phạm vi nội bộ.**

**6.5. Điều khó nhất khi viết Problem Statement là gì? Khó nhất là mô tả đủ rõ công việc audit label mà người chưa từng làm vẫn hiểu được. Nếu chỉ nói Auditor cần kiểm tra bài Toán thì sẽ thiếu phần code tạo biến và các trường hợp phát sinh khi thay số. Nhưng nếu giải thích quá sâu về kỹ thuật thì câu mô tả vấn đề lại dài và khó theo dõi.**

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào? Nếu làm lại, tôi sẽ ghi nhận thời gian kiểm tra trên một số label thực tế ngay từ đầu và tách thời gian tìm lỗi với thời gian viết feedback. Khi đó, nhóm có cơ sở rõ hơn để xác định bước nào cần cải thiện.**

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

---

## 7. Tài liệu tham khảo

-
