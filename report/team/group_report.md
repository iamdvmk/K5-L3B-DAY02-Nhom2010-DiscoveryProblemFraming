# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: Nhóm 2010
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu): Tự động kiểm tra chất lượng feedback cho các label của Math Expert
- Quyết định cuối: Not Yet (chuyển Go sau khi kiểm chứng xong giả định số 1 và số 3 ở mục 3.1)

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | Minh Khánh | Khi chuẩn bị CV để ứng tuyển nhiều vị trí, tôi muốn chỉnh sửa CV nhanh theo từng JD để không phải viết lại gần như từ đầu cho mỗi công việc. | Người ứng tuyển nhiều công ty trong cùng một khoảng thời gian. | Tốn 15-20 phút sửa mỗi CV | Ứng viên có thường xuyên chỉnh CV cho từng JD không? Mỗi tuần họ làm việc này bao nhiêu lần? |
| 2 | Minh Khánh | Khi muốn mua một sản phẩm, tôi muốn hiểu nhanh sản phẩm nào phù hợp với nhu cầu để không phải đọc hàng chục bài review. | Người tiêu dùng thường xuyên mua hàng qua mạng | Tốn 15-20 phút đọc, xem review qua nhiều kênh khác nhau | |
| 3 | Minh Khánh | Khi tự học một môn có nhiều kiến thức và deadline, tôi muốn có cách theo dõi những nội dung đã học và chưa hiểu để không phải liên tục xem lại toàn bộ tài liệu. | Người học đang ôn tập, chuẩn bị lượng lớn kiến thức | Tốn 5-15 phút tùy nội dung cần ôn tập | Người học hiện xác định phần mình chưa hiểu bằng cách nào? |
| 4 | Vũ | Khi làm dự án, tôi muốn tổng hợp tài liệu để hiểu cách làm sản phẩm. | Intern tìm thông tin, Senior/Lead đưa tài liệu | 40-85 phút / dự án | Intern đang dùng công cụ hoặc cách nào để tổng hợp tài liệu? Những cách đó còn bất tiện ở đâu? |
| 5 | Vũ | Khi tài liệu công ty được cập nhật, tôi muốn biết phần nào thay đổi so với bản cũ, để không làm theo thông tin lỗi thời.| Intern và Developers được quan sát kiểm tra thông tin | "35 - 60 phút / mỗi lần công ty thay đổi thông tin"| |
| 6 | Vũ | Khi được giao một tài liệu dài, tôi muốn nắm phần liên quan đến task của mình, để bắt tay làm mà không phải đọc hết. | Các Intern khi tìm hiểu tài liệu được giao | khoảng 30-60 phút / lần | |
| 7 | Quốc Khánh | Khi nhận đề tài nghiên cứu khoa học, tôi muốn nắm được ý chính và cách làm của paper tiếng Anh dài hàng chục trang, để biết được phương pháp và kết quả mà không phải đọc dính từng trang một| Sinh viên làm nghiên cứu khoa học hoặc tự tìm hiểu chủ đề mới | Một paper 10 đến 20 trang mất khoảng 1 đến 2 tiếng mới đọc hiểu, mỗi tuần phải đọc vài paper, nhiều bài phải đọc lại 2 đến 3 lần vì quên mất chi tiết | Các công cụ tóm tắt paper hiện có giúp người đọc hiểu phương pháp và kết quả đến mức nào? Phần nào vẫn phải tự đọc kỹ? |
| 8 | Quốc Khánh |  Khi kỳ thi kết thúc môn học sắp đến, tôi muốn chọn lọc được những phần quan trọng nhất đã học trong kỳ về cùng một chỗ, để ôn thi có trọng tâm thay vì mở lại từng slide từ đầu| Sinh viên ôn thi cuối kỳ | Mỗi môn thi mất khoảng 3 đến 4 buổi tối để gom và chép lại phần quan trọng; bước nặng nhất là đọc lại toàn bộ slide để tự đoán phần nào ra thi rồi gõ lại hết, chiếm 3 tiếng rưỡi trong 5 tiếng chuẩn bị một môn | Câu hỏi nhận được: phần "quan trọng" do ai quyết và sai sót đo thế nào (Minh Khánh hỏi) |
| 9 | Quốc Khánh | Khi giữa tuần mà các thành viên trong nhóm project chưa báo tiến độ, tôi muốn biết phần của ai đã xong đến đâu, để không phải nhắn tin hỏi từng người nhiều lần | Trưởng nhóm project | Trong đợt project vừa rồi tuần nào mình cũng mất 30 đến 45 phút nhắn tin đuổi tiến độ, có tuần phải nhắc 2 lần | |
| 10 | Giang | Khi phân tích các báo cáo tai nạn giao thông, tôi muốn trích xuất 11 trường thông tin quan trọng (về điều kiện môi trường, hạ tầng giao thông và các phương tiện liên quan), đồng thời gán cho mỗi trường một giá trị thuộc tập giá trị định trước để chuyển đổi nội dung báo cáo thành dữ liệu có cấu trúc và nhất quán. | Sinh viên nghiên cứu, nhà nghiên cứu xe tự hành | Mỗi báo cáo cần 12-15 phút để đọc và trích xuất. Quy mô nghiên cứu có thể cần tới 1000 báo cáo. | |
| 11 | Giang | Khi đưa feed back cho các label của Math Expert, tôi muốn tự động kiểm tra tính đúng sai, logic của lời giải, ngữ pháp và các trường hợp biên trong code để phát hiện lỗi nhanh chóng, giảm thời gian đọc và rà soát thủ công.| Auditor | Mỗi bài kiểm tra 3 tiêu chí, mất khoảng 10 phút với bài thông thường và có thể 20-30 phút với bài toán có code hoặc lập luận phức tạp | Câu hỏi nhận được: chữ "tự động kiểm tra" trong job story là giải pháp đội lốt, phải mô tả lại bằng nỗi đau; actor auditor có người thật để phỏng vấn không (Quốc Khánh hỏi) |
| 12 | Giang | Khi muốn ứng tuyển một vị trí, tôi muốn điều chỉnh CV phù hợp với yêu cầu trong JD để làm nổi bật những kỹ năng và kinh nghiệm liên quan, tăng mức độ phù hợp của hồ sơ với vị trí ứng tuyển. | Người tìm việc, đặc biệt là sinh viên mới ra trường | Số JD đọc mỗi tuần 10-15, thời gian đọc và chỉnh sửa CV 15-30 phút | |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A | #1, #12 | Chỉnh CV theo yêu cầu từng JD để ứng tuyển nhiều nơi cùng lúc |
| B | #2, #4, #5, #6, #7, #8 | Đọc nhiều tài liệu/nguồn để nắm đúng phần mình cần (review sản phẩm, tài liệu dự án, tài liệu công ty, paper, bài ôn thi) |
| C | #10, #11 | Xử lý nội dung theo tập tiêu chí định trước (trích xuất 11 trường từ báo cáo, chấm bài theo 3 tiêu chí)|
| D | #3, #9 | Theo dõi trạng thái để không phải xem lại toàn bộ (đã học/chưa hiểu, tiến độ từng người) |
### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: Giảm thời gian kiểm tra chất lượng feedback cho
các label của Math Expert, đồng thời đảm bảo
feedback chính xác, logic và nhất quán.
├── Opportunity A:
│   Feedback cần được kiểm tra trên nhiều khía cạnh
│   như tính đúng sai, logic lời giải, ngữ pháp và
│   các trường hợp biên trong code, khiến Auditor
│   phải dành nhiều thời gian rà soát thủ công.
│
├── Opportunity B:
│   Một số lỗi trong lời giải hoặc code khó phát hiện
│   khi chỉ đọc feedback thông thường, đặc biệt là
│   lỗi logic, trường hợp biên và các bước suy luận
│   chưa đầy đủ.
│
└── Opportunity C:
    Việc đánh giá feedback có thể phụ thuộc vào
    kinh nghiệm và cách nhìn nhận của từng Auditor,
    dẫn đến kết quả kiểm tra thiếu nhất quán
    giữa những người đánh giá khác nhau.
```

### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| Kiểm tra feedback Math Expert | 5 | 5 | 5 | 4 | 5 | 5 | 5 | 34 |
| Trích xuất thông tin tai nạn | 5 | 5 | 4 | 5 | 4 | 5 | 4 | 32 |
| Đọc hiểu paper nghiên cứu | 5 | 5 | 5 | 4 | 5 | 5 | 5 | 34 |

**Candidate được chọn:**Tự động kiểm tra chất lượng feedback cho các label của Math Expert.

**Vì sao chọn:** Actor cụ thể, quy trình rõ ràng, pain có ý nghĩa, impact có thể đo lường

**Lý do loại hai candidate còn lại trong shortlist:**

- Đọc hiểu paper nghiên cứu (34 điểm, bằng candidate được chọn): điểm bằng nhau nhưng bài paper khó kiểm chứng hơn, vì quanh lớp ít người thật sự phải đọc paper thường xuyên nên CP4 khó tìm đủ người phỏng vấn; bài Math Expert có người làm việc này thật sự và có dữ liệu thật để xem.
- Trích xuất thông tin tai nạn giao thông (32 điểm): actor là nhà nghiên cứu xe tự hành, nằm ngoài phạm vi quanh mình nên không tìm được người để phỏng vấn trong buổi; quy mô tới 1000 báo cáo cũng quá lớn so với một buổi lab.

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | Nhiều auditor ngoài người kể ban đầu cũng mất khoảng 10-30 phút cho một bài, pain không phải của riêng một người | Value | 5 | 1 | Kiểm chứng trước |
| 2 | Có bộ feedback mẫu kèm lỗi đã xác định trước, đủ để làm bộ bài test đánh giá AI | Feasibility | 4 | 2 | |
| 3 | Công ty cho phép dùng công cụ AI trên dữ liệu label nội bộ | Viability | 4 | 1 | Kiểm chứng trước |
| 4 | Auditor muốn AI hỗ trợ soạn nháp chứ không muốn mất quyền chốt cuối | Value | 4 | 2 | |
| 5 | AI đọc được cấu trúc label gồm đề, lời giải, code và testcase một cách nhất quán | Feasibility | 4 | 2 | |
| 6 | Auditor hiểu và sửa được bản nháp feedback do AI soạn | Usability | 3 | 2 | |

*Điền 4–6 giả định; xóa dòng thừa.*

Giả định nhóm kiểm chứng trong buổi này: giả định số 1 (pain thật và phổ biến giữa các auditor) và giả định số 3 (được phép dùng AI trên dữ liệu nội bộ), vì đây là hai giả định quan trọng nhất mà bằng chứng hiện có mỏng nhất. Nếu giả định số 3 sai thì cả bài quay về hướng No AI hoặc Rule chạy nội bộ, không dùng AI.

### 3.2. Kiểm chứng

Cách đã dùng: **Phỏng vấn** (dự kiến 2-3 auditor thật, không phỏng vấn thành viên nhóm mình theo quy định của lab)

Bộ câu hỏi phỏng vấn đã soạn theo ba luật Mom Test (hỏi chuyện đã xảy ra, không hỏi giả định; hỏi cuộc sống của họ, không hỏi ý tưởng của mình; nói ít nghe nhiều):

- Lần gần nhất bạn rà một bài label Math Expert là khi nào? Kể lại từng bước bạn đã làm từ lúc mở bài đến lúc gửi feedback.
- Bước nào mất nhiều thời gian nhất? Một bài bình thường mất khoảng bao lâu, còn bài có code phức tạp thì sao?
- Bạn đã từng bỏ sót lỗi mà về sau mới phát hiện chưa? Lúc đó chuyện gì xảy ra, ai phát hiện ra lỗi đó?
- Bạn đã từng thử cách nào để rà nhanh hơn chưa, ví dụ checklist, script hay nhờ bạn khác review hộ? Kết quả thế nào?

Lưu ý ghi nhận: nếu auditor trả lời bài thường chỉ mất vài phút, đó là tín hiệu phản bác, phải ghi lại và nhóm thu hẹp lại problem hoặc đổi target.

Interview snapshot (mỗi buổi phỏng vấn một bảng, hoặc đặt file trong `report/assets/cp4-interview-snapshot-N.md`):

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | |
| Câu nói đáng nhớ nhất (nguyên văn) | |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | |
| Hiện đang xử lý bằng cách nào (workaround)? | |
| Mất bao lâu, bao lần? | |
| Insight / opportunity rút ra | |

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| Phỏng vấn auditor | | | |
| Phỏng vấn auditor | | | |
| Phỏng vấn auditor | | | |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

Trước khi kiểm chứng, problem đã được viết lại từ cụm "tự động kiểm tra" (solution đội lốt) thành nỗi đau thật là auditor mất nhiều thời gian rà từng bài để tìm lỗi logic, ngữ pháp và trường hợp biên, theo phản biện ở CP3. Phần thay đổi sau khi phỏng vấn xong sẽ cập nhật tại đây.

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| **STACK (kiểm thử các biến thể của một bài Toán)** | [Quy trình tạo bài](https://docs.stack-assessment.org/en/STACK_question_admin/Authoring_workflow/) · [Kiểm thử biến thể](https://docs.stack-assessment.org/en/STACK_question_admin/Deploying/) | Bước 2, 3 và 5. Đối chiếu đề, lời giải mẫu và kết quả khi thay số. | Sát nhất với cấu trúc label. STACK cho phép tạo trước nhiều biến thể, chạy cùng bộ test trên từng biến thể và mở lại trường hợp bị lỗi. | Test chỉ kiểm tra những điều kiện đã khai báo. Auditor vẫn cần đọc lập luận trong lời giải. | Khi gửi feedback, ghi rõ bộ số liệu gây lỗi và dòng lời giải bị sai để Expert tái hiện được. |
| **Hypothesis (kiểm thử code sinh biến)** | [Tài liệu Hypothesis](https://hypothesis.readthedocs.io/en/latest/tutorial/introduction.html) | Bước 5–6. Tìm bộ giá trị khiến một điều kiện của bài toán bị vi phạm. | Có thể tìm phản ví dụ. Chẳng hạn, nếu lời giải luôn chia hai vế cho `a`, cần kiểm tra liệu code có thể sinh `a = 0` hay không. | Đây là thư viện Python. Khả năng dùng trực tiếp phụ thuộc ngôn ngữ nội bộ và điều kiện mà nhóm đưa vào test. | Với mỗi phép biến đổi có điều kiện, đối chiếu điều kiện đó với miền giá trị mà code thực sự có thể sinh. |
| **MathDebugger (phân loại lỗi trong đề và lời giải)** | [Trang nghiên cứu MathDebugger](https://haolpku.github.io/MathDebugger/) | Bước 2, 3 và 6. Xác định lỗi nằm ở giả thiết của đề hay ở một bước suy luận, tính toán hoặc biểu đạt trong lời giải. | Kiểm tra cả chuỗi lập luận, kể cả khi đáp án cuối trông hợp lý. | Đây là bộ đánh giá nghiên cứu trên dữ liệu Toán tổng hợp. Khả năng xử lý code sinh biến của công ty chưa được kiểm chứng. | Feedback nên chỉ ra bước sai đầu tiên, lý do sai và bộ số liệu minh họa nếu lỗi phụ thuộc vào giá trị biến. |

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```text
  [1 Nhận template từ Expert: 1'] 
→ [2 Check đúng/sai Toán học: 2'] 
→ [3 Check solution flow: 2'] 
→ [4 Check grammar: 1'] 
→ [5 Đọc và soi code, tìm edge cases: 2'] 
→ [6 Xác định vị trí và đánh giá lỗi: 1'] 
→ [7 Viết feedback cho Expert: 7'] ← BOTTLENECK
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---:|---|
| 1 | Auditor | Bài tập và lời giải từ Expert | Bài tập được tiếp nhận trên hệ thống | 1 phút / template | Check công thức, tính toán, kết quả |
| 2 | Auditor | Lời giải toán học | Xác định tính đúng/sai về mặt Toán học | 2 phút / template | Kiểm tra mạch lập luận, các bước suy luận |
| 3 | Auditor | Lời giải và cấu trúc bài | Đánh giá solution flow và tính logic | 2 phút / template | Đảm bảo văn phong rõ ràng, chuẩn xác |
| 4 | Auditor | Ngôn ngữ và văn bản lời giải | Phát hiện lỗi ngữ pháp, cách diễn đạt | 1 phút / template | Soi kỹ các nhánh điều kiện, input đặc biệt |
| 5 | Auditor | Code và testcase đi kèm | Tìm lỗi logic và các trường hợp biên chưa xử lý | 2 phút / template | Tổng hợp các vấn đề cần feedback |
| 6 | Auditor | Toàn bộ lỗi đã phát hiện từ các bước trên | Danh sách vị trí xuất hiện lỗi và hướng sửa sơ bộ | 1 phút / template | Tổng hợp các vấn đề cần feedback |
| 7 | Auditor | Danh sách lỗi và đề xuất sửa | Feedback chi tiết gửi lại cho Expert | 7 phút / template | Viết nội dung giải thích và hướng dẫn sửa lỗi | 

**Bottleneck chính:** Viết feedback cho Expert

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text
[1 Hệ thống tự động gom template, chạy linter check code/edge cases cơ bản: 0.5'] ← RULE (script)
→ [2 AI phân tích lời giải Toán học, kiểm tra logic flow, ngữ pháp và đối chiếu testcase code: 1.5'] ← AI
→ [3 Auditor review bản nháp, đối chiếu code và tinh chỉnh feedback: 2'] ← CON NGƯỜI (Boundary: AI không được tự ý gửi feedback hay trực tiếp duyệt/sửa bài của Expert).
→ [4 Auditor gửi feedback hoàn chỉnh: 0.5'] ← CON NGƯỜI
```

Phương án quay về: nếu AI soạn nháp kém, bỏ sót nhiều lỗi hoặc ngừng chạy thì auditor quay về quy trình bảy bước thủ công ở bảng 4.1, ưu tiên xử lý các template đến hạn gần nhất trước để không trễ tiến độ.

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | 7 | 4 | Tinh gọn các thao tác kiểm tra lặp lại |
| Tổng thời gian | 8-12 phút/template | 3-5 phút/template | Target: giảm thời gian tìm lỗi và viết feedback |
| Số bước thủ công | 7/7 | 2/4 | Auditor giữ vai trò kiểm soát cuối cùng |
| Bottleneck chính | Viết feedback (Bước 7) | Auditor review + tinh chỉnh | Tập trung vào việc đánh giá chất lượng thay vì gõ văn bản |
| Rủi ro mới phát sinh | | AI bỏ sót edge case của code hoặc hiểu sai logic Toán | Xử lý bằng boundary + Auditor check kỹ phần code |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | Auditor – người chịu trách nhiệm kiểm tra và đánh giá chất lượng feedback cho các label của Math Expert. |
| **Quy trình** | 1. Nhận feedback từ các label của Math Expert. 2. Đọc và kiểm tra tính đúng sai của lời giải. 3. Đánh giá tính logic và nhất quán trong các bước giải. 4. Kiểm tra ngữ pháp, cách diễn đạt. 5. Kiểm tra code và các trường hợp biên (edge cases) nếu có. 6. Tổng hợp lỗi và đưa ra feedback hoặc kết luận đánh giá.|
| **Bottleneck** | 	Auditor phải kiểm tra thủ công nhiều tiêu chí khác nhau trên từng feedback. Việc rà soát từng bước suy luận, tính đúng sai và các trường hợp biên trong code tốn thời gian, đồng thời có nguy cơ bỏ sót lỗi hoặc đánh giá thiếu nhất quán. |
| **Impact** | 	Giảm thời gian kiểm tra feedback cho Auditor; tăng khả năng phát hiện lỗi; nâng cao độ chính xác và tính nhất quán trong quá trình đánh giá chất lượng label của Math Expert. |
| **Success Metric** (baseline → target, cách đo) | - Review Time: Đo thời gian trung bình kiểm tra một feedback trước và sau khi có AI hỗ trợ. Error Detection Rate: Tỷ lệ lỗi được phát hiện trên tổng số lỗi đã được xác định trong bộ dữ liệu chuẩn. Accuracy: Tỷ lệ kết quả đánh giá đúng so với kết quả tham chiếu do Auditor có kinh nghiệm xác nhận. Baseline: Đo bằng quy trình kiểm tra thủ công hiện tại. Target đề xuất: Giảm 30% thời gian review, đồng thời duy trì độ chính xác phát hiện lỗi từ 90% trở lên. Các target cần được điều chỉnh sau khi đo baseline và thử nghiệm. |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | - AI chỉ đóng vai trò hỗ trợ kiểm tra và đưa ra cảnh báo, không tự quyết định cuối cùng về chất lượng feedback. Không tự ý sửa hoặc thay đổi nội dung feedback gốc. Không tự đưa ra kết luận đúng/sai khi không đủ dữ liệu hoặc không có cơ sở kiểm chứng. Không tự động phê duyệt hoặc loại bỏ label. HITL: Auditor phải kiểm tra lại các trường hợp AI không chắc chắn, phát hiện lỗi logic phức tạp, có nhiều cách giải hợp lệ, lỗi liên quan đến kiến thức toán chuyên sâu hoặc các trường hợp AI và đáp án tham chiếu không thống nhất. |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

-Làm thế nào xác định AI thực sự tốt hơn quy trình thủ công? Đồng ý. Cần thiết kế bộ test có đáp án tham chiếu, đo thời gian và độ chính xác của cả quy trình thủ công lẫn quy trình có AI hỗ trợ.

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô: độ mơ hồ thấp nhân độ phức tạp cao.

Vì sao: đầu ra có đúng sai rõ theo bộ tiêu chí cố định (đúng sai toán học, logic lời giải, ngữ pháp, trường hợp biên của code), không phải kiểu bài chấp nhận nhiều phiên bản như viết văn. Nhưng quy trình gồm nhiều bước nối tiếp và nhiều loại đầu vào khác nhau (lời giải tiếng tự nhiên, code, testcase), nên độ phức tạp cao. Theo ma trận, ô này thường đủ với Workflow nhiều bước rõ ràng, chưa chắc cần Agent.

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | Chuẩn hóa checklist ba tiêu chí, dùng mẫu feedback có sẵn các ô vị trí, lý do, hướng sửa | Đủ khi pain chủ yếu do quy trình rời rạc | Không giảm được phần đọc và viết feedback, vốn là bottleneck chính | Không |
| **Rule** | Linter chạy check cú pháp code, script chạy testcase cố định, template feedback dựng sẵn | Chỉ đủ cho phần code có điều kiện khai báo trước | Không đọc được lập luận lời giải bằng tiếng tự nhiên, bỏ sót lỗi logic | Không đủ dùng riêng |
| **Workflow** | Các bước định sẵn: script gom template và chạy check cơ bản, AI phân tích lời giải, đối chiếu testcase và soạn nháp feedback, auditor review rồi tự gửi | Các bước kiểm tra cố định từ trước, AI chỉ làm một bước trong chuỗi | AI bỏ sót edge case hoặc hiểu sai logic toán, xử lý bằng boundary và auditor kiểm lại | Có |
| **Agent** | AI tự quyết kiểm gì tiếp theo, tự mở file, tự lặp đến khi xong | Chỉ cần khi các bước không định sẵn được | Khó đặt boundary, khó truy xem AI sai ở đâu, chi phí và độ trễ cao hơn | Không |

**Mức chọn:** Workflow

**Vì sao không chọn mức đơn giản hơn:** Rule chỉ xử lý được phần code theo điều kiện khai báo trước, còn bottleneck thật là bước đọc lập luận lời giải và viết feedback bằng tiếng tự nhiên, phần đó Rule không làm được. No AI đã thử qua dạng checklist ba tiêu chí như hiện tại nhưng tổng thời gian 8-12 phút một template vẫn nằm ở bước đọc và viết, chưa giảm được. Còn Agent không cần thiết vì các bước kiểm tra đã cố định từ trước, không có bước nào cần AI tự quyết làm gì tiếp theo; mỗi mức lên thêm là thêm chi phí, độ trễ và cách hỏng mới.

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | AI đọc đề, lời giải, code và testcase rồi dự đoán chỗ nào nghi ngờ có lỗi logic, ngữ pháp hoặc trường hợp biên, kèm soạn nháp feedback giải thích cho từng chỗ |
| **Judgment** — con người cân nhắc, quyết định gì? | Auditor cân nhắc nhận định của AI có đúng không, lỗi có đáng ghi không, mức độ nghiêm trọng ra sao và cách viết feedback đã rõ ràng chưa |
| **Action** — hành động cuối cùng là gì, ai làm? | Auditor sửa bản nháp và tự tay gửi feedback cho Expert; AI không gửi |
| **Outcome** — đo kết quả bằng gì? | Thời gian trung bình một template giảm từ 8-12 phút xuống dưới 5 phút, tỷ lệ bắt được lỗi trong bộ bài có lỗi đã biết trước giữ từ 90% trở lên |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | Mỗi lần chạy cần template label gồm đề, lời giải mẫu, code, testcase cùng bộ tiêu chí kiểm tra; dữ liệu này có sẵn trong hệ thống label |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | So sánh bản nháp AI với feedback cuối cùng auditor gửi; mỗi chỗ auditor phải sửa là tín hiệu để cải thiện cách soạn nháp |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng: nhóm chọn augment, thể hiện ngay ở boundary trong PS v0 và quy trình tương lai là AI không tự gửi, auditor chốt cuối cùng. Giả định auditor muốn giảm thời gian chứ không muốn mất kiểm soát chất lượng sẽ được chốt qua phỏng vấn ở CP4.
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào: bỏ sót tệ hơn, vì feedback có lỗi đi thẳng xuống người học bên dưới label, còn báo nhầm chỉ làm auditor tốn thêm vài phút kiểm lại. Thiết kế xử lý: AI nghi ngờ chỗ nào thì flag kèm vị trí cụ thể thay vì im lặng bỏ qua, và auditor bắt buộc kiểm kỹ phần code cùng các chỗ AI không chắc chắn trước khi gửi.

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | Auditor của Math Expert, người chịu trách nhiệm cuối cùng về chất lượng feedback cho các label. |
| **Quy trình** | Bốn bước ở mục 4.2: script gom template và chạy check cơ bản, AI phân tích lời giải đối chiếu testcase và soạn nháp feedback, auditor review và chỉnh, auditor tự gửi. |
| **Bottleneck** | Đọc lập luận lời giải và viết feedback, hai phần chiếm phần lớn thời gian 8-12 phút hiện tại cho một template. |
| **Impact** | Nếu không giải thì thời gian một template giữ nguyên ở mức 8-12 phút, chất lượng feedback phụ thuộc vào thể trạng và kinh nghiệm từng auditor tại thời điểm rà bài. |
| **Success Metric** (baseline → target, cách đo) | Baseline: 8-12 phút một template, lấy từ bảng before/after ở mục 4. Target: dưới 5 phút một template, tỷ lệ bắt được lỗi trong bộ bài có lỗi đã xác định trước từ 90% trở lên. Cách đo: bấm giờ và chấm kết quả trên 10 template thử nghiệm, so với thời gian auditor làm thủ công cùng bộ bài đó. |
| **Boundary** | AI không tự gửi feedback, không tự sửa nội dung feedback gốc, không tự chốt đúng sai khi thiếu dữ liệu; các trường hợp AI không chắc chắn, logic phức tạp, nhiều cách giải hợp lệ đều do auditor quyết. |
| **AI intervention point** | Bước 2 của quy trình tương lai (mục 4.2): AI phân tích lời giải, đối chiếu testcase và soạn nháp feedback cho auditor review. |
| **Mức chọn** | Workflow |
| **Rủi ro & người kiểm tra** | Rủi ro AI bỏ sót lỗi hoặc hiểu sai logic: auditor kiểm lại toàn bộ bản nháp trước khi gửi. Rủi ro dữ liệu nội bộ: nhóm xác nhận quy định công ty về việc dùng AI trên dữ liệu label trước khi pilot, người theo dõi là cả nhóm qua mục 3.1. |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| Success Metric | Baseline ghi chung chung là "quy trình thủ công hiện tại", chưa có số cụ thể | Baseline có số là 8-12 phút một template, cách đo cụ thể là bấm giờ trên 10 template | Metric không có số thì không biết pilot thành hay không, không đo được |
| AI intervention point | Không có trường này | Ghi rõ AI chen vào ở bước 2 của quy trình tương lai | CP6 bắt buộc chỉ rõ điểm AI can thiệp trong quy trình |
| Mức chọn | Không có trường này | Workflow | Sau khi so sánh bốn mức ở mục 6, mức đơn giản hơn không đủ, Agent là thừa |
| Rủi ro & người kiểm tra | Không có trường này | Ghi rõ rủi ro bỏ sót và rủi ro dữ liệu, auditor là người kiểm cuối | Cần người chịu trách nhiệm cuối cùng rõ ràng trước khi có quyết định |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | Không bịa nhận định | Mọi nhận định lỗi đều chỉ tới vị trí cụ thể trong đề, lời giải hoặc code | Có nhận định không truy ra được nguồn trong dữ liệu đầu vào |
| 2 | Bắt được lỗi đã biết | Trong bộ 10 bài có lỗi đã xác định trước, AI flag từ 9 lỗi trở lên | Bỏ sót lỗi logic hoặc trường hợp biên có trong bộ bài |
| 3 | Báo nhầm ở mức chấp nhận được | Số chỗ AI flag mà auditor xác nhận không có lỗi chiếm dưới 20% số flag | Quá nửa số flag là báo nhầm, khiến auditor phải đi kiểm lại gần như toàn bộ bài |
| 4 | Nháp đủ định dạng feedback | Mỗi lỗi được soạn đủ ba phần: vị trí, lý do sai, hướng sửa | Thiếu một trong ba phần, hoặc viết chung chung không chỉ được chỗ sai |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | Thấp | Auditor mất 8-12 phút/template cho công việc rà soát thủ công lặp đi lặp lại; nhu cầu tự động hóa tìm lỗi và soạn feedback là rất thực tế |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | Trung bình | AI có thể phân tích sai logic toán phức tạp hoặc bỏ sót edge case của code; Auditor cần có kỹ năng đối chiếu, kiểm tra kỹ trước khi gửi feedback cho Expert |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | Thấp | Template, lời giải toán học và code đều ở định dạng văn bản có sẵn, dễ dàng tích hợp script kiểm tra logic cơ bản và prompt AI chuyên biệt |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | Thấp | Không vi phạm quy định dữ liệu nội bộ; AI chỉ đóng vai trò trợ lý soạn nháp, Auditor trực tiếp chịu trách nhiệm vận hành và duyệt cuối cùng. |

### 8.2. Kết luận

**Quyết định:** Go

**Lý do:** Giải quyết đúng điểm nghẽn ở khâu rà soát và viết feedback, giúp giảm 50-70% thời gian xử lý mà vẫn giữ quyền kiểm soát chất lượng hoàn toàn thuộc về con người.

**Nếu Go — pilot nhỏ nhất:** Chạy pilot trong 4 tuần với 1 Auditor, áp dụng cho việc kiểm duyệt template Toán có kèm code, tự ghi lại thời gian xử lý và tỷ lệ chính xác của feedback.

**Ngưỡng dừng** (nếu sau … mà … thì quay về …): Nếu sau 4 tuần pilot mà tỷ lệ feedback sai sót do AI tăng lên hoặc thời gian review/sửa nháp không giảm so với thủ công, thì quay về quy trình thủ công hoàn toàn.

---

## 9. Hạn chế và hướng tiếp theo

- Kiểm chứng bằng phỏng vấn chưa chạy xong tại thời điểm chốt bài, còn hai giả định quan trọng chưa có bằng chứng, nên quyết định dừng ở Not Yet thay vì Go
- Bộ eval mới có tiêu chí, chưa xây bộ 10 cặp input và đầu ra mẫu để chấm thử (thiếu phần này nên chưa đạt mức bonus B3)
- Các con số thời gian 8-12 phút một template và 10-30 phút một bài phức tạp lấy từ quan sát của một auditor duy nhất, chưa đại diện cho nhiều người
- Nhóm chưa kiểm tra được quy định pháp lý và bảo mật của công ty về việc dùng AI trên dữ liệu label, đây là điều kiện tiên quyết trước khi pilot

## 10. Tài liệu tham khảo

Các framework trong bài lấy từ tài liệu nguồn của lab, xem bản tổng hợp kèm tóm tắt tại docs/03-international-frameworks.md:

- Design Council, Double Diamond, Framework for Innovation: https://www.designcouncil.org.uk/resources/framework-for-innovation/
- Intercom, How we accidentally invented Job Stories: https://www.intercom.com/blog/accidentally-invented-job-stories/
- Teresa Torres, Opportunity Solution Trees: https://www.producttalk.org/opportunity-solution-trees/
- David Bland, Assumptions Mapping (Strategyzer): https://www.strategyzer.com/library/how-assumptions-mapping-can-focus-your-teams-on-running-experiments-that-matter
- Rob Fitzpatrick, The Mom Test: https://www.momtestbook.com/
- Teresa Torres, The Interview Snapshot: https://www.producttalk.org/interview-snapshot/
- Jeff Gothelf, Business Problem Statement vs Opportunity Statement: https://jeffgothelf.com/blog/business-problem-statement-opportunity-statement/
- Google PAIR Guidebook, User Needs: https://pair.withgoogle.com/chapter/user-needs/
- Anthropic, Building Effective Agents: https://www.anthropic.com/research/building-effective-agents
- Harvard Business Review, A Simple Tool to Start Making Decisions with the Help of AI (AI Canvas): https://hbr.org/2018/04/a-simple-tool-to-start-making-decisions-with-the-help-of-ai
- Marty Cagan, SVPG, The Four Big Risks: https://www.svpg.com/four-big-risks/
- Microsoft Research, Guidelines for Human-AI Interaction: https://www.microsoft.com/en-us/research/publication/guidelines-for-human-ai-interaction/
- NIST AI RMF Playbook, MAP: https://airc.nist.gov/airmf-resources/playbook/map/

Nguồn trong bảng research ở mục 3.3:

- STACK Question authoring workflow và Deploying: https://docs.stack-assessment.org/en/STACK_question_admin/Authoring_workflow/ và https://docs.stack-assessment.org/en/STACK_question_admin/Deploying/
- Hypothesis, Introduction to Hypothesis: https://hypothesis.readthedocs.io/en/latest/tutorial/introduction.html
- MathDebugger, Type-Aware Error Detection for Synthetic Math Data: https://haolpku.github.io/MathDebugger/
