# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Nguyễn Long Vũ
- MSSV: 2A202603842
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: Nhom2010
- Link repo nhóm: https://github.com/iamdvmk/K5-L3B-DAY02-Nhom2010-DiscoveryProblemFraming.git

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Cần đọc | Khi được giao một tài liệu dài, tôi muốn nắm phần liên quan đến task của mình, để bắt tay làm mà không phải đọc hết | Intern, Team | khoảng 10-30 phút / lần |
| 2 | Tổng hợp nhiều thông tin | Khi làm dự án, tôi muốn tổng hợp tài liệu để hiểu cách làm sản phẩm | Senior, Intern, Team | 30'-1 tiếng / 2-3 lần / mỗi ngày |
| 3 | Tốn thời gian | Khi bị kẹt ở một lỗi hoặc khái niệm lạ, tôi muốn biết mình nên tự tìm tiếp hay hỏi người khác, để không mất cả buổi mà không tiến triển | Intern, Senior | 30 phút mỗi lần / 2-3 lần / ngày|
| 4 | Pain từ người khác | Khi senior phải giải thích kiến thức nền cho tôi, tôi muốn nắm phần cơ bản trước, để buổi trao đổi chỉ tập trung vào phần khó | Senior, Intern | 15-20 phút / ngày |
| 5 | Cần đọc | Khi tài liệu công ty được cập nhật, tôi muốn biết phần nào thay đổi so với bản cũ, để không làm theo thông tin lỗi thời | Intern, Team | 10-30 phút / 1-2 lần / tuần |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- Ý 1, 3, 4, 5. Vì mình cũng đã gặp các vấn đề này.
- Những ý bỏ là do phạm vi quá nhỏ hay vấn đề trùng lặp.
---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | #2 Tìm tổng hợp tài liệu | Tốn nhiều thời gian | Nếu tổng hợp sai sẽ phải tổng hợp lại |
| 2 | #1 Tìm thông tin chính | Tốn thời gian | Cần hiểu sâu task của mình để biết thông tin cần tìm |
| 3 | #5 Review thay đổi | Pain thật, nhiều người đau | Có thể gây conflict, ảnh hưởng lớn đến nhiều người  |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi làm dự án, tôi muốn tổng hợp tài liệu để hiểu cách làm sản phẩm |
| Actor | Intern tìm thông tin, Senior/Lead đưa tài liệu |
| Thời điểm / bối cảnh | Mỗi khi được giao dự án |
| Quy trình hiện tại (3–7 bước) | 1. Tìm thông tin sản phẩm -> 2. Tìm các tài liệu liên quan -> 3. Hỏi Senior cung cấp thêm tài liệu -> 4. Tổng hợp các tài liệu tìm được -> 5. Thu thêm dựa theo yêu cầu mới trong lúc thực hiện |
| Bottleneck (bước nào, mất bao nhiêu phút) | Thu thêm dựa theo yêu cầu mới trong lúc thực hiện - 30' |
| Impact (nếu không giải thì sao) | Tốn nhiều thời gian để bắt đầu dự án |
| Success metric (baseline → target) | giảm thời gian xuống còn 10-20' |
| Phương án không dùng AI | Công ty tổng hợp sẵn các tài liệu chung liên quan đến sản phẩm: Các sản phẩm phổ biến sẽ dễ tìm thông tin, các sản phẩm mới vẫn hiếm thông tin |
| Giả thuyết về AI (nếu có) | AI phân tích thông tin quan trọng của sản phẩm và gợi ý thông tin liên quan; Senior/Lead review |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
HIỆN TẠI - 85 phút / dự án:
[Tìm thông tin sản phẩm: 15'] -> [Tìm các tài liệu liên quan: 20'] -> [Hỏi Senior cung cấp thêm tài liệu: 10'] -> [Tổng hợp các tài liệu tìm được: 10'] -> [Thu thêm dựa theo yêu cầu mới trong lúc thực hiện: 30']
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi được giao một tài liệu dài, tôi muốn nắm phần liên quan đến task của mình, để bắt tay làm mà không phải đọc hết |
| Actor | Các Intern khi tìm hiểu |
| Thời điểm / bối cảnh | Mỗi lần tìm hiểu chi tiết sản phẩm |
| Quy trình hiện tại (3–7 bước) | 1. Tìm hiểu task -> 2. Kiểm tra thông tin trên tài liệu -> 3. Thu hẹp phạm vi tìm kiếm |
| Bottleneck (bước nào, mất bao nhiêu phút) | Kiểm tra thông tin trên tài liệu - 15' |
| Impact (nếu không giải thì sao) | Tốn thời gian mỗi lần tìm kiếm thông tin tài liệu |
| Success metric (baseline → target) | giảm thời gian 10' mỗi lần kiểm tra |
| Phương án không dùng AI | Tài liệu được phân chia mục lục và index rõ ràng, hỏi Senior: Các phần vẫn có thể liên quan tới nhau, vẫn cần lướt qua các phần |
| Giả thuyết về AI (nếu có) | AI scan qua tài liệu và tổng hợp thông tin hộ |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
HIỆN TẠI - 35 phút / mỗi lần kiểm tra chi tiết sản phẩm:
[Tìm hiểu task: 10'] -> [Kiểm tra thông tin trên tài liệu: 20'] -> [Thu hẹp phạm vi tìm kiếm: 5']
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi tài liệu công ty được cập nhật, tôi muốn biết phần nào thay đổi so với bản cũ, để không làm theo thông tin lỗi thời |
| Actor | Intern và Developers được quan sát kiểm tra thông tin |
| Thời điểm / bối cảnh | Mối lần công ty cập nhật thông tin tài liệu/sản phẩm |
| Quy trình hiện tại (3–7 bước) | 1. Kiểm tra chi tiết cập nhật -> 2. So sánh với công việc hiện tại -> 3. Tuỳ chỉnh công việc sao cho phù hợp |
| Bottleneck (bước nào, mất bao nhiêu phút) | Tuỳ chỉnh công việc sao cho phù hợp - 30-45' |
| Impact (nếu không giải thì sao) | Tốn nhiều thời gian chỉnh sửa, khả năng xảy ra lỗi và conflict |
| Success metric (baseline → target) | Giảm thời gian kiểm tra và chỉnh sửa, giảm thiểu lỗi |
| Phương án không dùng AI | Xác định rõ các thành phần có thể thay đổi của tài liệu/sản phẩm: Conflict sẽ giảm nhưng thời gian review vẫn còn |
| Giả thuyết về AI (nếu có) | AI so sánh và cảnh báo về sự thay đổi cho Devs |
| Cảm nhận nhanh | Rule |

Quy trình nháp hiện tại:

```text
HIỆN TẠI - 35 - 60 phút / mỗi lần công ty thay đổi thông tin:
[Kiểm tra chi tiết cập nhật: 15'] -> [So sánh với công việc hiện tại: 20'] -> [Tuỳ chỉnh công việc sao cho phù hợp: 1'-30']
```

### Card muốn pitch nhất

- Card số: 3
- Vì sao: Vì vấn đề này có nhiều người bị đau, và thường gây phiền phức lớn tới người bị ảnh hưởng.
- Câu hỏi muốn nhóm phản biện: Vấn đề này đã có những giải pháp gì?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Actor chưa đủ cụ thể | Đồng ý | Card #3 ghi + “Developer được quan sát” |
| Có dấu hiệu nhảy sang AI hơi sớm | Đồng ý | |
| Sửa quy trình hoặc dùng rule có lẽ đã đủ ở vài chỗ | Đồng ý | Card #3: changelog, diff của tài liệu, hoặc thông báo thay đổi có cấu trúc là rule thuần túy thừa nhận conflict sẽ giảm.
Card #2: mục lục và index tốt, hoặc hỏi senior “đọc phần nào”, cần được cân nhắc nghiêm túc. |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Pitch 3 problem mình đã lựa chọn | |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: "Với" | |
| Nhận phản biện | Câu hỏi tôi nhận được: Đã có giải pháp cho vấn đề tổng hợp tư liệu | Tôi đã sửa gì: Thêm bước research công cụ có sẵn |
| Gom cluster / cây OST | Tham gia gom 12 candidate thành 4 cluster | |
| Chọn candidate problem | | |
| Kiểm chứng / research | | |
| Quy trình nhóm | Vẽ quy trình hiện tại và tương lai cho vấn đề tổng hợp tài liệu khi bắt đầu dự án | Quy trình tương lai gồm 5 bước, khoảng 35'/dự án (giảm khoảng 50') |
| Problem Statement | | |
| Mức can thiệp AI | | |
| Quyết định | | |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | AI đưa thêm các vấn đề | AI đưa thêm ý tưởng | AI chưa được các vấn đề phức tạp hơn | Tôi giữ các dòng khớp việc mình làm và bỏ các dòng không có trải nghiệm thật |
| CP2 Problem Card | AI đưa ra các phản biện | AI ra những lời nhận xét đáng suy nghĩ | Nhiều lời phản biện chỉ là soi mói lỗi sai | Tôi phân loại phản biện thành hai nhóm: đáng sửa và chỉ là soi chi tiết |
| CP4 Research | | | | |
| CP5 Quy trình | Tạo sơ đồ dựa trên thông tin | Làm công việc nhàm chán | Sơ đồ chỉ đẹp trên giấy: các con số "sau" là ước lượng, chưa ai bấm giờ, và AI chưa biết bước nào trong công ty thật sự không đổi được | Tôi đối chiếu từng bước với cách làm thật, sửa số phút theo số đã bấm giờ |
| CP5–6 Problem Statement | AI đưa ra phản biện | Phản biện được sử dụng | | |
| CP6 Mức can thiệp / quyết định | | | | |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**
- Top 3 problems của các bạn sâu sắc hơn, yêu cầu giải pháp phức tạp hơn. đồng thời trải rộng qua nhiều trường hợp không chỉ 1 môi trường.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

---

## 7. Tài liệu tham khảo

-
