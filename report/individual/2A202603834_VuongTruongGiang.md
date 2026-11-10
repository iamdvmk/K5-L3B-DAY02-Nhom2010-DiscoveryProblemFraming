# Báo cáo cá nhân — 2A202603834_VuongTruongGiang

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
| Pitch Problem Card | Tôi trình bày ba Problem Card: trích xuất thông tin tai nạn, kiểm duyệt label Math Expert và chỉnh CV theo JD. | Nhóm đưa bài toán kiểm duyệt label vào shortlist rồi chọn để kiểm chứng. |
| Phản biện bài của bạn khác | Tôi hỏi về tần suất chỉnh CV theo JD, cách người học nhận ra phần chưa hiểu và hạn chế của công cụ tổng hợp tài liệu hiện có. | Các câu hỏi làm rõ tần suất gặp vấn đề, cách nhận biết pain và khoảng trống của giải pháp sẵn có. |
| Nhận phản biện | Tôi nhận câu hỏi: Auditor tốn thời gian nhất ở bước tìm lỗi hay viết feedback, đã đo trên bao nhiêu label và bài có code khác bài thường thế nào? | Tôi bỏ kết luận một bước luôn là bottleneck; ba tình huống Auditor cho thấy thời gian tập trung ở rà code, rà ngữ pháp hoặc viết feedback tùy loại label. Cần bấm giờ từng bước trên label thực tế. |
| Gom cluster / cây OST | Tôi góp ý gom các bài toán có nhu cầu tương đồng và đối chiếu nhánh OST với công việc kiểm duyệt label. | Cây OST của nhóm nêu bốn pain cụ thể |
| Chọn candidate problem | Tôi tham gia chấm điểm và so sánh các candidate trong shortlist. | Nhóm chọn bài toán Math Expert vì có Auditor thật để hỏi và quy trình đủ rõ để kiểm chứng; đây là quyết định của cả nhóm. |
| Kiểm chứng / research | Tôi cung cấp các tình huống Auditor cho ba snapshot, đồng thời phụ trách tìm và đối chiếu STACK, Hypothesis, MathDebugger với label gồm đề, lời giải và code sinh biến. | Mục 3.2 ghi nội dung phỏng vấn, các tín hiệu xác nhận và phản bác; mục 3.3 có bảng research kèm link, nêu rõ phạm vi áp dụng và điều chưa kiểm chứng trên dữ liệu công ty. |
| Quy trình nhóm | Tôi góp ý các bước Auditor đọc đề, rà lời giải, kiểm tra code sinh biến, tìm trường hợp biên và viết feedback; đối chiếu thời gian trong bảng trước/sau với lời kể phỏng vấn. | Quy trình ở mục 4 không cộng các mốc từ ba tình huống khác nhau thành một thời gian trung bình cho mỗi label. |
| Problem Statement | Tôi hỗ trợ Minh Khánh làm rõ v0 từ góc nhìn Auditor: đối tượng được kiểm là label, gồm đề và lời giải có biến do code sinh ra. | Problem Statement mô tả đúng công việc rà lỗi và viết feedback, đồng thời ghi baseline tổng thời gian là phần cần đo. |
| Mức can thiệp AI | Tôi dùng kết quả research để phản biện phạm vi của Rule và Workflow; phần ma trận, AI Canvas và v1 do Quốc Khánh và Vũ phụ trách. | Nhóm giữ Auditor là người kiểm và gửi feedback; mức Workflow được đưa ra để thử, chưa coi là hiệu quả đã chứng minh. |
| Quyết định | Tôi rà lại căn cứ cho kết luận, nhất là số phút tiết kiệm và quyền dùng dữ liệu label nội bộ. | Mục 8 ghi Go cho pilot có điều kiện và ngưỡng dừng; các ngưỡng giảm thời gian, phát hiện lỗi và báo nhầm là mục tiêu thử nghiệm. |

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

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?** Khi chọn vấn đề cần cân nhắc cả mức độ phức tạp và khả năng triển khai. Ví dụ, bài toán phát hiện trộm xe nghe rất thiết thực nhưng cần mô hình có độ chính xác cao. Ngoài ra, dữ liệu để xây dựng và kiểm thử cũng khó tìm, còn chi phí triển khai có thể lớn.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?** Có. Với bài toán ôn tập, ban đầu nhóm nghĩ ngay đến việc dùng AI hỗ trợ người học ôn các phần trọng tâm. Sau đó, nhóm nhận ra chưa làm rõ cách xác định người học đã hiểu phần nào và còn yếu phần nào. Nếu chỉ dựa vào nội dung đã học thì AI khó biết người học thực sự nắm được kiến thức đến đâu. Nhóm cần tìm hiểu thêm cách người học tự đánh giá và theo dõi việc học trước khi chọn giải pháp.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.** Có. Ban đầu tôi đánh giá cao bài toán trích xuất dữ liệu từ báo cáo thực tế vì nghĩ đây là công việc tốn nhiều thời gian và có thể lặp lại với số lượng lớn. Sau khi xem xét lại, tôi nhận ra không có nhiều người phải thực hiện công việc này theo cách thủ công. Điều đó khiến tôi cân nhắc lại quy mô nhu cầu, thay vì chỉ dựa vào việc mỗi báo cáo mất bao lâu để xử lý

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?** Khi tìm hiểu bài toán audit label, tôi thấy dạng dữ liệu mà công ty tôi sử dụng khá đặc thù. Mỗi label gồm đề bài và lời giải, trong đó có code tạo ra nhiều bộ số liệu. Tôi tìm được một số công cụ giải quyết từng phần tương tự, nhưng chưa thấy giải pháp nào phù hợp trực tiếp với toàn bộ quy trình của công ty. Điều này khiến tôi nhận ra giải pháp có thể chỉ phù hợp trong phạm vi nội bộ.

**6.5. Điều khó nhất khi viết Problem Statement là gì?** Khó nhất là mô tả đủ rõ công việc audit label mà người chưa từng làm vẫn hiểu được. Nếu chỉ nói Auditor cần kiểm tra bài Toán thì sẽ thiếu phần code tạo biến và các trường hợp phát sinh khi thay số. Nhưng nếu giải thích quá sâu về kỹ thuật thì câu mô tả vấn đề lại dài và khó theo dõi.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?** Nếu làm lại, tôi sẽ ghi nhận thời gian kiểm tra trên một số label thực tế ngay từ đầu và tách thời gian tìm lỗi với thời gian viết feedback. Khi đó, nhóm có cơ sở rõ hơn để xác định bước nào cần cải thiện.

**6.7. Hiểu bài:** Bài nhóm tôi chọn là việc Auditor mất thời gian kiểm duyệt label Toán của Expert, nhất là khi label có cả đề, lời giải và code sinh ra nhiều bộ số liệu. Hiện Auditor phải đọc đề và lời giải, rà ngữ pháp, kiểm tra code để tìm trường hợp biên rồi viết feedback; qua ba cuộc phỏng vấn, tôi thấy mỗi loại label lại tốn thời gian ở một bước khác nhau. Vì vậy nhóm chưa thể lấy một con số chung làm baseline, mà cần bấm giờ từng bước trên các label thực tế. Khi thử, nhóm sẽ so sánh tổng thời gian với cách làm thủ công, đặt mục tiêu giảm ít nhất 30%, phát hiện từ 90% lỗi đã biết và giữ báo nhầm dưới 20%. Quy trình đề xuất cho script chạy các kiểm tra định sẵn, AI nêu chỗ nghi lỗi và soạn nháp feedback, sau đó Auditor kiểm lại toàn bộ. AI không được tự sửa label, duyệt bài hay gửi feedback cho Expert; quyết định cuối vẫn thuộc về Auditor. Nhóm chọn Go cho một pilot nhỏ, với điều kiện công ty cho phép dùng dữ liệu label nội bộ và có bộ bài tham chiếu để đo kết quả.

---

## 7. Tài liệu tham khảo

- Slide bài giảng *Day02-Xác định bài toán cho AI*.
