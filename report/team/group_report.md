# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: Nhóm 2010
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu): Auditor mất thời gian kiểm tra đề bài, lời giải và code sinh biến trong label của Math Expert, rồi viết feedback chỉ rõ lỗi cho Expert.
- Quyết định cuối: Go cho pilot có điều kiện (sau khi xác nhận quyền dùng dữ liệu nội bộ)

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
OUTCOME: Giảm thời gian kiểm duyệt label của Math Expert,
đồng thời giữ chất lượng phát hiện lỗi và feedback.
├── Opportunity A:
│   Label có nhiều lỗi khiến Auditor phải mô tả
│   từng lỗi và trao đổi thêm với Expert.
│
├── Opportunity B:
│   Lời giải có vẻ đúng vẫn cần kiểm tra code sinh biến
│   để phát hiện trường hợp biên.
│
└── Opportunity C:
    Việc rà ngữ pháp lặp lại nhiều lần, Auditor vẫn
    có thể bỏ sót lỗi nhỏ dù đã dùng công cụ hỗ trợ.
```

### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| Kiểm duyệt label Math Expert | 5 | 5 | 5 | 4 | 5 | 5 | 5 | 34 |
| Trích xuất thông tin tai nạn | 5 | 5 | 4 | 5 | 4 | 5 | 4 | 32 |
| Đọc hiểu paper nghiên cứu | 5 | 5 | 5 | 4 | 5 | 5 | 5 | 34 |

**Candidate được chọn:** Auditor kiểm duyệt label của Math Expert và viết feedback cho Expert.

**Vì sao chọn:** Actor cụ thể, quy trình rõ ràng, pain có ý nghĩa, impact có thể đo lường

**Lý do loại hai candidate còn lại trong shortlist:**

- Đọc hiểu paper nghiên cứu (34 điểm, bằng candidate được chọn): điểm bằng nhau nhưng bài paper khó kiểm chứng hơn, vì quanh lớp ít người thật sự phải đọc paper thường xuyên nên CP4 khó tìm đủ người phỏng vấn; bài Math Expert có người làm việc này thật sự và có dữ liệu thật để xem.
- Trích xuất thông tin tai nạn giao thông (32 điểm): actor là nhà nghiên cứu xe tự hành, nằm ngoài phạm vi quanh mình nên không tìm được người để phỏng vấn trong buổi; quy mô tới 1000 báo cáo cũng quá lớn so với một buổi lab.

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | Nhiều Auditor gặp khó khăn khi kiểm duyệt label, nhưng bước tốn thời gian có thể khác nhau theo loại label | Value | 5 | 1 | Kiểm chứng trước |
| 2 | Có bộ feedback mẫu kèm lỗi đã xác định trước, đủ để làm bộ bài test đánh giá AI | Feasibility | 4 | 2 | |
| 3 | Công ty cho phép dùng công cụ AI trên dữ liệu label nội bộ | Viability | 4 | 1 | Kiểm chứng trước |
| 4 | Auditor muốn AI hỗ trợ soạn nháp chứ không muốn mất quyền chốt cuối | Value | 4 | 2 | |
| 5 | AI đọc được cấu trúc label gồm đề, lời giải, code và testcase một cách nhất quán | Feasibility | 4 | 2 | |
| 6 | Auditor hiểu và sửa được bản nháp feedback do AI soạn | Usability | 3 | 2 | |

Nhóm đã phỏng vấn ba Auditor để kiểm tra giả định số 1; kết quả cho thấy các điểm tốn thời gian khác nhau, chưa đủ để suy ra một mức thời gian chung. Giả định số 3 về quyền dùng dữ liệu nội bộ chưa được xác nhận và phải kiểm tra trước pilot. Nếu không được phép dùng AI với dữ liệu label, nhóm quay về hướng No AI hoặc Rule phù hợp quy định nội bộ.

### 3.2. Kiểm chứng

Cách đã dùng: **Phỏng vấn 3 Auditor** (theo ba snapshot bên dưới).

Bộ câu hỏi phỏng vấn đã soạn theo ba luật Mom Test (hỏi chuyện đã xảy ra, không hỏi giả định; hỏi cuộc sống của họ, không hỏi ý tưởng của mình; nói ít nghe nhiều):

- Lần gần nhất bạn rà một bài label Math Expert là khi nào? Kể lại từng bước bạn đã làm từ lúc mở bài đến lúc gửi feedback.
- Bước nào mất nhiều thời gian nhất? Một bài bình thường mất khoảng bao lâu, còn bài có code phức tạp thì sao?
- Bạn đã từng bỏ sót lỗi mà về sau mới phát hiện chưa? Lúc đó chuyện gì xảy ra, ai phát hiện ra lỗi đó?
- Bạn đã từng thử cách nào để rà nhanh hơn chưa, ví dụ checklist, script hay nhờ bạn khác review hộ? Kết quả thế nào?

Lưu ý ghi nhận: nếu auditor trả lời bài thường chỉ mất vài phút, đó là tín hiệu phản bác, phải ghi lại và nhóm thu hẹp lại problem hoặc đổi target.

Interview snapshot (mỗi buổi phỏng vấn một bảng, hoặc đặt file trong `report/assets/cp4-interview-snapshot-N.md`):

**Auditor #1:**

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | Auditor |
| Câu nói đáng nhớ nhất (nguyên văn) | Có rất nhiều Label có chất lượng quá tệ, việc tôi phải đưu feedback chi tiết cho từng lỗi còn tốn thời gian hơn việc tôi làm lại label đó từ đầu |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Auditor tốn thêm thời gian trao đổi với Expert qua slack để giải thích thêm về lỗi (10-15 phút)  |
| Hiện đang xử lý bằng cách nào (workaround)? | Auditor vẫn phải đưa feedback chi tiết dựa trên quy trình của công ty |
| Mất bao lâu, bao lần? | 15 phút/lần, 1-2 lần 1 ngày |
| Insight / opportunity rút ra | Với label có nhiều lỗi, việc mô tả lỗi và trao đổi thêm với Expert tốn thời gian. Mức tiết kiệm nhờ công cụ hỗ trợ chưa được đo. |

**Auditor #2:**

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | Auditor |
| Câu nói đáng nhớ nhất (nguyên văn) | “Việc audit cần độ chính xác rất cao, nhiều lúc tôi bỏ sót lỗi nhỏ nhữ ngữ pháp.” |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Label không được duyệt do còn lỗi, sau đó Auditor phải kiểm tra và tự mình sửa lại label đã audit. |
| Hiện đang xử lý bằng cách nào (workaround)? | Auditor sử dụng công cụ kiểm tra ngữ pháp bên ngoài để hỗ trợ rà soát. |
| Mất bao lâu, bao lần? | Khoảng 1–2 phút/lần, thực hiện 20–30 lần/ngày. |
| Insight / opportunity rút ra | Kiểm tra ngữ pháp là công việc lặp lại nhiều lần trong ngày và Auditor vẫn có thể bỏ sót lỗi. |

**Auditor #3**

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | Auditor |
| Câu nói đáng nhớ nhất (nguyên văn) | "Với nhiều label của Expert kỳ cựu, lời giải của họ có flow rất logic, có tính đúng đắn về mặt toán học cao. Các phần này viết bằng ngôn ngữ tự nhiên và chỉ mất khoảng 2 phút để tôi đưa ra nhận định này. Tuy nhiên tôi vẫn cần kiểm tra code của họ rất chi tiết và thời gian này phần lớn không tìm ra lỗi (mất khoảng 5 phút mỗi label)" |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Auditor kiểm tra một bài toán có đáp án đúng và lời giải mượt, dễ hiểu. Sau đó, Auditor đã tìm ra edge case trong khoảng 6 phút kiểm tra. |
| Hiện đang xử lý bằng cách nào (workaround)? | Auditor đọc và rà soát code để tìm các trường hợp biên. |
| Mất bao lâu, bao lần? | Khoảng 5-7 phút cho bước đọc code của bài được kể. |
| Insight / opportunity rút ra | Nhóm có thể tìm cách hỗ trợ Auditor xác định và kiểm thử các trường hợp biên, rồi đo xem cách đó có giảm thời gian rà soát mà vẫn phát hiện được lỗi hay không. |


**Tổng hợp:**

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| Phỏng vấn Auditor 1 | 1 | Label nhiều lỗi khiến Auditor phải viết feedback chi tiết và có lúc trao đổi thêm với Expert; người được hỏi ước tính khoảng 15 phút/lần, gặp 1–2 lần/ngày. | Chưa tách riêng thời gian viết feedback và trao đổi. |
| Phỏng vấn auditor 2 | 1 | Auditor có thể bỏ sót lỗi ngữ pháp và hiện dùng công cụ bên ngoài để hỗ trợ kiểm tra, khoảng 1–2 phút/lần, 20–30 lần/ngày. | Đã có công cụ kiểm tra ngữ pháp. |
| Phỏng vấn auditor 3 |1 | Auditor vẫn dành khoảng 5-7 phút/label để kiểm tra code của Expert kỳ cựu, dù lời giải có vẻ đúng và logic.| Auditor cho biết phần lớn lần kiểm tra code này không phát hiện lỗi|

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

Trước khi kiểm chứng, nhóm bỏ cụm "tự động kiểm tra" khỏi mô tả problem. Ba cuộc phỏng vấn cho thấy thời gian tập trung ở các bước khác nhau tùy loại label: viết feedback khi có nhiều lỗi, rà ngữ pháp lặp lại, hoặc kiểm tra code dù lời giải nhìn qua có vẻ đúng. Nhóm sửa problem thành khó khăn của Auditor khi kiểm duyệt đề, lời giải và code sinh biến rồi viết feedback; bottleneck cần được đo theo loại label, chưa thể gán chung cho một bước.

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| **STACK (kiểm thử các biến thể của một bài Toán)** | [Quy trình tạo bài](https://docs.stack-assessment.org/en/STACK_question_admin/Authoring_workflow/) · [Kiểm thử biến thể](https://docs.stack-assessment.org/en/STACK_question_admin/Deploying/) | Bước 2, 3 và 5. Đối chiếu đề, lời giải mẫu và kết quả khi thay số. | Sát nhất với cấu trúc label. STACK cho phép tạo trước nhiều biến thể, chạy cùng bộ test trên từng biến thể và mở lại trường hợp bị lỗi. | Test chỉ kiểm tra những điều kiện đã khai báo. Auditor vẫn cần đọc lập luận trong lời giải. | Khi gửi feedback, ghi rõ bộ số liệu gây lỗi và dòng lời giải bị sai để Expert tái hiện được. |
| **Hypothesis (kiểm thử code sinh biến)** | [Tài liệu Hypothesis](https://hypothesis.readthedocs.io/en/latest/tutorial/introduction.html) | Bước 5–6. Tìm bộ giá trị khiến một điều kiện của bài toán bị vi phạm. | Có thể tìm phản ví dụ. Chẳng hạn, nếu lời giải luôn chia hai vế cho `a`, cần kiểm tra liệu code có thể sinh `a = 0` hay không. | Đây là thư viện Python. Khả năng dùng trực tiếp phụ thuộc ngôn ngữ nội bộ và điều kiện mà nhóm đưa vào test. | Với mỗi phép biến đổi có điều kiện, đối chiếu điều kiện đó với miền giá trị mà code thực sự có thể sinh. |
| **MathDebugger (phân loại lỗi trong đề và lời giải)** | [Trang nghiên cứu MathDebugger](https://haolpku.github.io/MathDebugger/) | Bước 2, 3 và 6. Xác định lỗi nằm ở giả thiết của đề hay ở một bước suy luận, tính toán hoặc biểu đạt trong lời giải. | Kiểm tra cả chuỗi lập luận, kể cả khi đáp án cuối trông hợp lý. | Đây là bộ đánh giá nghiên cứu trên dữ liệu Toán tổng hợp. Khả năng xử lý code sinh biến của công ty chưa được kiểm chứng. | Feedback nên chỉ ra bước sai đầu tiên, lý do sai và bộ số liệu minh họa nếu lỗi phụ thuộc vào giá trị biến. |

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

```text
[1 Nhận label từ Expert]
→ [2 Kiểm tra tính đúng/sai Toán học]
→ [3 Đọc mạch lập luận của lời giải]
→ [4 Rà ngữ pháp và cách diễn đạt]
→ [5 Kiểm tra code sinh biến và trường hợp biên]
→ [6 Ghi nhận vị trí, mức độ lỗi]
→ [7 Viết feedback cho Expert; trao đổi thêm nếu cần]
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | Auditor | Label gồm đề, lời giải và code sinh biến từ Expert | Label được tiếp nhận để kiểm duyệt | Chưa đo riêng | Xác định thành phần cần kiểm tra. |
| 2 | Auditor | Đề và lời giải | Nhận định về tính đúng/sai Toán học | Chưa đo riêng; bước 2–3 khoảng 2 phút trong tình huống Auditor #3 kể | Đối chiếu giả thiết, phép tính và đáp án. |
| 3 | Auditor | Các bước trong lời giải | Nhận định về mạch lập luận và độ rõ ràng | Gộp với bước 2 trong lời kể trên | Đọc cả lời giải, kể cả khi đáp án có vẻ đúng. |
| 4 | Auditor | Câu chữ trong đề và lời giải | Lỗi ngữ pháp, cách diễn đạt cần sửa | Khoảng 1–2 phút/lần, 20–30 lần/ngày theo Auditor #2 | Có dùng công cụ kiểm tra ngữ pháp bên ngoài. |
| 5 | Auditor | Code sinh biến và các điều kiện của bài | Trường hợp biên hoặc bộ số liệu gây lỗi | Khoảng 5–7 phút trong tình huống Auditor #3 kể | Cần đối chiếu code với đề và lời giải. |
| 6 | Auditor | Các lỗi đã phát hiện | Danh sách vị trí lỗi và hướng sửa sơ bộ | Chưa đo riêng | Tổng hợp bằng chứng để viết feedback. |
| 7 | Auditor | Danh sách lỗi | Feedback gửi Expert; có thể trao đổi thêm | Khoảng 15 phút/lần xử lý label nhiều lỗi theo Auditor #1; chưa tách thời gian viết và trao đổi | Giải thích từng lỗi và hướng sửa. |

**Bottleneck theo loại label:** Label nhiều lỗi tốn thời gian viết feedback; label có lời giải tốt vẫn tốn thời gian rà code; rà ngữ pháp lặp lại nhiều lần. Chưa đo tổng thời gian trung bình cho một label.

### 4.2. Quy trình tương lai

```text
[1 Script gom label và chạy các kiểm tra đã định nghĩa] ← RULE
→ [2 AI nêu điểm nghi lỗi trong đề/lời giải, gợi ý trường hợp biên và soạn nháp feedback] ← AI
→ [3 Auditor kiểm tra lại đề, lời giải, code và bản nháp; sửa feedback] ← CON NGƯỜI
→ [4 Auditor quyết định và gửi feedback cho Expert] ← CON NGƯỜI
```

**Boundary:** AI không tự duyệt label, sửa label gốc hoặc gửi feedback. Thời gian từng bước của quy trình đề xuất chưa được đo. Nếu AI soạn nháp kém, bỏ sót lỗi hoặc ngừng chạy, Auditor quay về bảy bước thủ công ở bảng 4.1.

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---|---|---|
| Số bước | 7 | 4 | Quy trình đề xuất gộp các bước hỗ trợ, không bỏ trách nhiệm kiểm tra của Auditor. |
| Tổng thời gian | Chưa có baseline chung; ba lời kể ghi nhận 1–2 phút rà ngữ pháp/lần, 5–7 phút rà code/label và khoảng 15 phút xử lý label nhiều lỗi, gồm feedback/trao đổi | Mục tiêu giảm ít nhất 30% tổng thời gian trên các label cùng loại | Bấm giờ toàn bộ quy trình thủ công và quy trình có hỗ trợ trên bộ label thử nghiệm. |
| Bước con người thực hiện | 7/7 | 2/4 bước chính; Auditor vẫn kiểm tra toàn bộ label trước khi gửi | Chưa thể suy ra thời gian tiết kiệm từ số bước. |
| Điểm tốn thời gian | Khác nhau theo loại label | Có thể chuyển sang kiểm tra và sửa bản nháp AI | Cần đo riêng thời gian kiểm tra code, ngữ pháp và viết feedback. |
| Rủi ro mới phát sinh | Lỗi có thể bị bỏ sót khi rà thủ công | AI có thể báo nhầm hoặc bỏ sót lỗi | Auditor xác minh trước khi gửi; nếu không đạt ngưỡng thì quay về quy trình thủ công. |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | Auditor chịu trách nhiệm kiểm duyệt label của Math Expert và gửi feedback cho Expert. |
| **Quy trình** | Nhận label gồm đề, lời giải và code sinh biến; kiểm tra tính đúng/sai, mạch lập luận, ngữ pháp và trường hợp biên; ghi nhận lỗi rồi viết feedback cho Expert. |
| **Bottleneck** | Auditor phải kiểm tra nhiều thành phần của label. Thời gian tập trung ở khâu khác nhau tùy loại label: rà code, rà ngữ pháp hoặc giải thích lỗi trong feedback. |
| **Impact** | Công việc rà soát và giải thích lỗi chiếm thời gian của Auditor; lỗi nhỏ hoặc trường hợp biên vẫn có thể bị bỏ sót. Tổng thời gian trung bình chưa được đo. |
| **Success Metric** (baseline → target, cách đo) | Baseline: bấm giờ quy trình thủ công trên bộ label thử nghiệm, tách theo loại label. Target đề xuất: giảm ít nhất 30% tổng thời gian mà vẫn phát hiện ít nhất 90% lỗi đã được Auditor xác nhận. So sánh với quy trình có hỗ trợ trên cùng bộ label; ngưỡng cần rà lại sau khi đo baseline. |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | AI chỉ nêu điểm nghi lỗi và soạn nháp feedback; không sửa label gốc, tự duyệt label hoặc gửi feedback. Auditor kiểm tra lại đề, lời giải, code và mọi nhận định của AI trước khi quyết định. |

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
| **No AI** (sửa quy trình) | Chuẩn hóa checklist các tiêu chí và mẫu feedback gồm vị trí, lý do, hướng sửa | Có thể đủ nếu pain chủ yếu do quy trình rời rạc | Chưa biết mức giảm thời gian vì chưa thử trên cùng bộ label | Đối chứng trong pilot |
| **Rule** | Linter chạy check cú pháp code, script chạy testcase cố định, template feedback dựng sẵn | Chỉ đủ cho phần code có điều kiện khai báo trước | Không đọc được lập luận lời giải bằng tiếng tự nhiên, bỏ sót lỗi logic | Không đủ dùng riêng |
| **Workflow** | Các bước định sẵn: script gom template và chạy check cơ bản, AI phân tích lời giải, đối chiếu testcase và soạn nháp feedback, auditor review rồi tự gửi | Các bước kiểm tra cố định từ trước, AI chỉ làm một bước trong chuỗi | AI bỏ sót edge case hoặc hiểu sai logic toán, xử lý bằng boundary và auditor kiểm lại | Có |
| **Agent** | AI tự quyết kiểm gì tiếp theo, tự mở file, tự lặp đến khi xong | Chỉ cần khi các bước không định sẵn được | Khó đặt boundary, khó truy xem AI sai ở đâu, chi phí và độ trễ cao hơn | Không |

**Mức chọn:** Workflow

**Lý do thử Workflow:** Rule chỉ kiểm tra được điều kiện và testcase đã định nghĩa; chưa xử lý hết lập luận trong lời giải và nội dung feedback. Checklist và mẫu feedback là phương án đối chứng cần đo, vì nhóm chưa chứng minh Workflow nhanh hơn. Các bước kiểm tra đã xác định trước nên chưa có căn cứ để AI tự quyết chuỗi hành động như Agent.

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | AI đọc đề, lời giải, code và testcase rồi dự đoán chỗ nào nghi ngờ có lỗi logic, ngữ pháp hoặc trường hợp biên, kèm soạn nháp feedback giải thích cho từng chỗ |
| **Judgment** — con người cân nhắc, quyết định gì? | Auditor cân nhắc nhận định của AI có đúng không, lỗi có đáng ghi không, mức độ nghiêm trọng ra sao và cách viết feedback đã rõ ràng chưa |
| **Action** — hành động cuối cùng là gì, ai làm? | Auditor sửa bản nháp và tự tay gửi feedback cho Expert; AI không gửi |
| **Outcome** — đo kết quả bằng gì? | Mục tiêu thử nghiệm: giảm ít nhất 30% tổng thời gian kiểm duyệt trên cùng loại label, phát hiện ít nhất 90% lỗi đã được xác nhận và giữ tỷ lệ báo nhầm dưới 20%; chưa có kết quả đo. |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | Mỗi lần chạy cần template label gồm đề, lời giải mẫu, code, testcase cùng bộ tiêu chí kiểm tra; dữ liệu này có sẵn trong hệ thống label |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | So sánh bản nháp AI với feedback cuối cùng auditor gửi; mỗi chỗ auditor phải sửa là tín hiệu để cải thiện cách soạn nháp |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Ba phỏng vấn cho thấy Auditor đang chịu trách nhiệm kiểm duyệt và gửi feedback; chưa có câu trả lời trực tiếp về mức độ họ muốn giao cho AI. Nhóm chọn hỗ trợ: AI đưa ra nháp, Auditor kiểm tra và quyết định cuối cùng. Cần hỏi thêm mức chấp nhận này trước pilot.
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Bỏ sót có thể khiến lỗi trong label lọt qua kiểm duyệt; báo nhầm khiến Auditor mất thời gian kiểm tra thêm. Cả hai cần được đo. AI phải chỉ ra vị trí và lý do nghi lỗi; Auditor kiểm lại đề, lời giải và code trước khi gửi feedback.

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | Auditor kiểm duyệt label của Math Expert và chịu trách nhiệm cuối cùng về feedback gửi Expert. |
| **Quy trình** | Hiện tại Auditor nhận label, kiểm tra đề, lời giải, ngữ pháp và code sinh biến rồi viết feedback như mục 4.1. Quy trình đề xuất ở mục 4.2 thêm bước Rule và AI trước khi Auditor kiểm tra, quyết định và gửi feedback. |
| **Bottleneck** | Ba phỏng vấn ghi nhận các điểm tốn thời gian khác nhau: rà code sinh biến, rà ngữ pháp lặp lại và viết feedback cho label nhiều lỗi. Chưa xác định bottleneck chung. |
| **Impact** | Auditor phải dành thời gian cho các bước rà soát và giải thích lỗi; ngữ pháp hoặc trường hợp biên vẫn có nguy cơ bị bỏ sót. Chưa đo tổng thời gian trung bình. |
| **Success Metric** (baseline → target, cách đo) | Baseline: bấm giờ tổng thời gian kiểm duyệt thủ công theo từng loại label, chưa có số chung. Target đề xuất: giảm ít nhất 30% tổng thời gian; phát hiện ít nhất 90% tổng số lỗi đã được Auditor xác nhận và giữ báo nhầm dưới 20% số chỗ AI flag. Cách đo: dùng bộ label có lỗi tham chiếu, so sánh hai quy trình trên các label cùng loại và tính cả thời gian Auditor sửa nháp AI. |
| **Boundary** | AI không tự gửi feedback, không tự sửa nội dung feedback gốc, không tự chốt đúng sai khi thiếu dữ liệu; các trường hợp AI không chắc chắn, logic phức tạp, nhiều cách giải hợp lệ đều do auditor quyết. |
| **AI intervention point** | Bước 2 của quy trình tương lai (mục 4.2): AI nêu điểm nghi lỗi trong đề và lời giải, gợi ý trường hợp biên của code và soạn nháp feedback để Auditor kiểm tra. |
| **Mức chọn** | Workflow |
| **Rủi ro & người kiểm tra** | Rủi ro AI bỏ sót lỗi hoặc hiểu sai logic: auditor kiểm lại toàn bộ bản nháp trước khi gửi. Rủi ro dữ liệu nội bộ: nhóm xác nhận quy định công ty về việc dùng AI trên dữ liệu label trước khi pilot, người theo dõi là cả nhóm qua mục 3.1. |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| Success Metric | Đề xuất giảm 30% thời gian nhưng chưa có baseline đo được | Giữ target đề xuất, nêu rõ cách bấm giờ và so sánh theo loại label | Không thể khẳng định cải thiện trước khi có số đo thủ công và pilot. |
| AI intervention point | Không có trường này | Ghi rõ AI chen vào ở bước 2 của quy trình tương lai | CP6 bắt buộc chỉ rõ điểm AI can thiệp trong quy trình |
| Mức chọn | Không có trường này | Workflow để thử và so với No AI/Rule | Cần kiểm tra liệu bước AI có tạo thêm giá trị so với checklist và script. |
| Rủi ro & người kiểm tra | Không có trường này | Ghi rõ rủi ro bỏ sót và rủi ro dữ liệu, auditor là người kiểm cuối | Cần người chịu trách nhiệm cuối cùng rõ ràng trước khi có quyết định |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | Không bịa nhận định | Mọi nhận định lỗi đều chỉ tới vị trí cụ thể trong đề, lời giải hoặc code | Có nhận định không truy ra được nguồn trong dữ liệu đầu vào |
| 2 | Bắt được lỗi đã biết | AI flag ít nhất 90% tổng số lỗi trong bộ label có lỗi được Auditor xác nhận trước | Tỷ lệ phát hiện dưới 90%, gồm cả lỗi Toán và trường hợp biên trong code. |
| 3 | Báo nhầm ở mức chấp nhận được | Số chỗ AI flag mà Auditor xác nhận không có lỗi chiếm dưới 20% tổng số flag | Tỷ lệ báo nhầm từ 20% trở lên. |
| 4 | Nháp đủ định dạng feedback | Mỗi lỗi được soạn đủ ba phần: vị trí, lý do sai, hướng sửa | Thiếu một trong ba phần, hoặc viết chung chung không chỉ được chỗ sai |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | Trung bình | Ba Auditor nêu các bước tốn thời gian khác nhau; chưa đo tổng thời gian hay xác nhận họ muốn dùng workflow đề xuất. |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | Trung bình | AI có thể phân tích sai logic toán phức tạp hoặc bỏ sót edge case của code; Auditor cần có kỹ năng đối chiếu, kiểm tra kỹ trước khi gửi feedback cho Expert |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | Trung bình | Label có đề, lời giải và code sinh biến; nhóm chưa thử đọc định dạng nội bộ, chạy code an toàn hoặc tích hợp các công cụ được research. |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | Cao | Chưa xác nhận quy định công ty về dùng dữ liệu label với AI. Auditor sẽ là người vận hành và duyệt cuối; chi phí cũng chưa được đo. |

### 8.2. Kết luận

**Quyết định:** Go cho pilot có điều kiện.

**Lý do:** Ba cuộc phỏng vấn xác nhận công việc rà soát và viết feedback có phần tốn thời gian, nhưng chưa chứng minh được workflow tiết kiệm thời gian hay phát hiện lỗi tốt hơn. Pilot nhỏ giúp đo hai điều này; Auditor vẫn giữ quyết định cuối.

**Điều kiện trước pilot:** Xác nhận công ty cho phép dùng dữ liệu label với công cụ AI được chọn; nếu chưa được phép thì chưa chạy AI trên dữ liệu nội bộ. Chuẩn bị bộ label có lỗi tham chiếu và bấm giờ quy trình thủ công. Sau đó thử trong 4 tuần với 1 Auditor trên label Toán có code sinh biến, ghi thời gian từng bước, lỗi phát hiện và báo nhầm.

**Ngưỡng dừng:** Sau 4 tuần, nếu tổng thời gian không giảm ít nhất 30% trên các label cùng loại, tỷ lệ phát hiện dưới 90% lỗi tham chiếu hoặc tỷ lệ báo nhầm từ 20% trở lên, dừng Workflow và quay về quy trình thủ công; xem xét checklist/Rule như phương án tiếp theo.

---

## 9. Hạn chế và hướng tiếp theo

- Nhóm mới ghi nhận ba cuộc phỏng vấn Auditor. Mỗi người nêu một bước tốn thời gian khác nhau: viết feedback cho label nhiều lỗi, rà ngữ pháp, hoặc kiểm tra code của label có lời giải tốt. Mẫu này chưa đủ để xác định một bottleneck chung cho mọi loại label. Bước tiếp theo là bấm giờ từng công đoạn trên các label thực tế, tách theo loại lỗi và độ phức tạp.
- Các mốc 1–2, 5–7 và khoảng 15 phút trong mục 4.1 là lời kể cho những tình huống khác nhau, không cộng lại thành thời gian trung bình/label. Pilot cần đo cả thời gian đọc, kiểm tra code, sửa nháp AI, trao đổi thêm với Expert và gửi feedback trước khi kết luận có tiết kiệm thời gian.
- Nhóm chưa thử workflow trên bộ label có đáp án tham chiếu. Các ngưỡng phát hiện từ 90% lỗi và báo nhầm dưới 20% là mục tiêu đề xuất, chưa phải kết quả đã đạt. Cần chuẩn bị các label có lỗi đã được Auditor xác nhận, gồm lỗi Toán, ngữ pháp và trường hợp biên do code sinh biến, rồi so sánh quy trình thủ công với quy trình có hỗ trợ trên cùng bộ bài.
- STACK, Hypothesis và MathDebugger cho thấy những cách kiểm tra từng phần của bài toán. Nhóm chưa xác nhận khả năng tích hợp với định dạng label, ngôn ngữ code và hệ thống nội bộ. Cần thử trên một số label được phép sử dụng và kiểm tra chính sách công ty về xử lý dữ liệu trước khi chạy pilot.

## 10. Tài liệu tham khảo

- STACK Docs, [Question authoring workflow](https://docs.stack-assessment.org/en/STACK_question_admin/Authoring_workflow/) và [Deploying question variants](https://docs.stack-assessment.org/en/STACK_question_admin/Deploying/). Tham khảo cấu trúc đề có biến và cách kiểm thử các biến thể trước khi sử dụng.
- Hypothesis, [Introduction to Hypothesis](https://hypothesis.readthedocs.io/en/latest/tutorial/introduction.html). Tham khảo cách tạo đầu vào và tìm trường hợp biên khi kiểm thử code.
- MathDebugger, [A Benchmark for Type-Aware Error Detection in Synthetic Math Data](https://haolpku.github.io/MathDebugger/). Tham khảo cách phân biệt lỗi ở đề và ở lời giải Toán.
