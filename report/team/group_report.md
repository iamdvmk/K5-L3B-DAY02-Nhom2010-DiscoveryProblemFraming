# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm:
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu):
- Quyết định cuối: Go / Not Yet / No-Go

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |
| 6 | | | | | |
| 7 | | | | | |
| 8 | | | | | |
| 9 | | | | | |
| 10 | | | | | |
| 11 | | | | | |
| 12 | | | | | |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A | | |
| B | | |
| C | | |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: 
├── Opportunity A: 
├── Opportunity B: 
└── Opportunity C: 
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

-

### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| | | | | | | | | |
| | | | | | | | | |
| | | | | | | | | |

**Candidate được chọn:**

**Vì sao chọn:**

**Vì sao loại các candidate còn lại:**

**Xử lý bất đồng (nếu có):**

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |
| 6 | | | | | |

*Điền 4–6 giả định; xóa dòng thừa.*

Giả định nhóm kiểm chứng trong buổi này:

### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn / Survey / Log, ticket, review

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
| | | | |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

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
|---:|---|---|---|---|---|
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
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

-

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô:

Vì sao:

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | | | | |
| **Rule** | | | | |
| **Workflow** | | | | |
| **Agent** | | | | |

**Mức chọn:**

**Vì sao không chọn mức đơn giản hơn:**

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | |
| **Judgment** — con người cân nhắc, quyết định gì? | |
| **Action** — hành động cuối cùng là gì, ai làm? | |
| **Outcome** — đo kết quả bằng gì? | |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng:
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào:

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** | |
| **AI intervention point** | |
| **Mức chọn** | No AI / Rule / Workflow / Agent |
| **Rủi ro & người kiểm tra** | |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| | | | |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | | | |
| 2 | | | |
| 3 | | | |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | | |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | | |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | | |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | | |

### 8.2. Kết luận

**Quyết định:** Go / Not Yet / No-Go

**Lý do:**

**Nếu Go — pilot nhỏ nhất:**

**Nếu Not Yet — cần kiểm chứng gì trước:**

**Nếu No-Go — nên làm gì thay AI:**

**Ngưỡng dừng** (nếu sau … mà … thì quay về …):

---

## 9. Hạn chế và hướng tiếp theo

-

## 10. Tài liệu tham khảo

-
