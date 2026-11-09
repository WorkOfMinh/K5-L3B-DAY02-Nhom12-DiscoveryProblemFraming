# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: Nhóm 12 (K5-L3B)
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu): Khi nhận bài lab/đồ án/task có yêu cầu và tiêu chí chấm rải rác ở nhiều file hoặc kênh, sinh viên muốn biết đủ đầu ra bắt buộc, tiêu chí và hạn nộp mà không phải đối chiếu thủ công.
- Quyết định cuối: Go / Not Yet / No-Go

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

Mỗi thành viên pitch 3 card, tổng cộng 15 candidate. Cột cuối ghi câu hỏi phản biện gắn với card đó.

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | Phong | Khi bắt đầu tuần học, muốn có mọi deadline từ Moodle, Classroom, Gmail ở một nơi | Sinh viên học nhiều môn | Rà soát từng môn trên Moodle và lọc email, khoảng 30 phút trong tổng 55 phút/tuần | Cổng trường có OTP hoặc chặn crawl thì lấy dữ liệu đầu vào thế nào? iCal/Google Calendar đã giải được bao nhiêu phần, có cần AI không? |
| 2 | Phong | Khi giảng viên đăng tài liệu 30–50 trang, muốn nắm ý chính và câu hỏi thảo luận để chuẩn bị bài | Sinh viên | Đọc chi tiết và tra thuật ngữ, khoảng 135 phút/tài liệu | Làm sao đo được bản tóm tắt đủ sâu để trả lời câu hỏi của giảng viên? |
| 3 | Phong | Khi làm đồ án nhóm, muốn biết ai làm phần nào và tiến độ ra sao | Nhóm trưởng và các thành viên | Nhắn giục, chờ phản hồi 1–2 ngày, 15–20 tin nhắn/sprint | Thành viên có chịu cập nhật trạng thái nếu dùng công cụ mới không? |
| 4 | Tú | Khi có bài tập hàng tuần, muốn biết dạng bài hay sai để không tự kiểm tra lại từ đầu | Sinh viên | Tự tìm nguyên nhân sai, khoảng 30 phút/ngày | 30 phút đó có thật sự dành để tìm ra lỗi không? |
| 5 | Tú | Khi chuẩn bị thi, muốn có bộ câu hỏi ôn tập từ tài liệu để không tự soạn từng câu | Sinh viên | Chọn lọc tài liệu và soạn câu hỏi | Câu hỏi có bám đúng trọng tâm đề thi không? |
| 6 | Tú | Khi làm bài nhóm, muốn các thành viên hiểu thống nhất yêu cầu để không sửa đi sửa lại | Nhóm làm bài | Truyền đạt yêu cầu, chờ phản hồi và thống nhất phương án | Nguyên nhân nằm ở chuyên môn hay ở việc thành viên không phản hồi? |
| 7 | Quốc | Khi chuẩn bị bữa ăn vài ngày tới, muốn đối chiếu đồ trong nhà, nhu cầu và giá để mua đủ, không bỏ phí | Người nấu ăn trong nhà | Lập danh sách mua, khoảng 25 phút/lần, 2 lần/tuần | Bước tốn thời gian thật là chọn món, kiểm nguyên liệu hay trao đổi với người cùng nhà? |
| 8 | Quốc | Khi đến kỳ thanh toán, muốn biết hóa đơn nào đến hạn, đúng số tiền, đã trả chưa | Người quản lý chi tiêu trong nhà | Đối chiếu 4–6 khoản/tháng ở nhiều ứng dụng | Có thật nhiều hóa đơn khó theo dõi, hay lịch nhắc đã đủ? |
| 9 | Quốc | Khi có nhiều việc ở nhiều nơi trong ngày, muốn sắp thứ tự đi theo giờ mở cửa và thời hạn | Người đi làm việc cá nhân | Lập lịch di chuyển cho 3 điểm đến/buổi | Tần suất có đủ cao để đáng giải không? |
| 10 | Quang Anh | Khi nhận bài lab GitHub, muốn xác định đủ yêu cầu từ nhiều file (README, checkpoint, rubric, submission) | Sinh viên làm lab | Đối chiếu yêu cầu giữa các file, khoảng 20 phút/lần | Nếu checklist chuẩn kèm link file gốc đã đủ, bước nào vẫn cần AI? |
| 11 | Quang Anh | Khi chuẩn bị train ResNet18 trên Colab, muốn dữ liệu và notebook đúng trước khi chạy | Sinh viên làm thí nghiệm | Kiểm tra đầu vào và sửa cấu hình, khoảng 30 phút/lần | Lỗi do đường dẫn, dữ liệu, dependency hay thao tác người dùng? |
| 12 | Quang Anh | Khi có PDF scan viết tay, muốn chuyển sang Word mà vẫn đúng nội dung | Sinh viên | Đối chiếu và sửa lỗi chữ viết tay, khoảng 30 phút/tài liệu | Metric phải có độ chính xác chứ không chỉ thời gian |
| 13 | Minh | Khi chuẩn bị nộp bài lớn, muốn biết nội dung đã đáp ứng đủ tiêu chí chưa để khỏi bị trừ điểm | Sinh viên nộp bài | Sửa phần thiếu hoặc chưa đạt tiêu chí, khoảng 20 phút/bài | Làm sao biết bước sửa thật sự là bước chậm nhất, không phải bước đọc tiêu chí? |
| 14 | Minh | Khi bài tập và task thực tập cùng hạn, muốn biết việc nào làm trước theo deadline, độ quan trọng, thời gian | Sinh viên đang thực tập | Đánh giá và so sánh mức ưu tiên, khoảng 12 phút/lần lập kế hoạch | 12 phút/lần có đủ lớn để cần công cụ, hay một ma trận ưu tiên là xong? |
| 15 | Minh | Khi nhận task thực tập có yêu cầu rải rác ở Slack, email, tài liệu, họp, muốn hiểu rõ đầu ra, deadline, tiêu chí | Thực tập sinh | Đọc và đối chiếu nhiều nguồn, khoảng 10 phút/task | Pain nằm ở việc tìm thông tin hay ở việc yêu cầu vốn không rõ từ người giao? |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A. Yêu cầu và tiêu chí nằm rải rác nhiều nguồn | #6, #10, #13, #15 | Người làm phải tự đọc và đối chiếu nhiều file hoặc kênh để biết đầu ra cần gì, chấm theo gì, hạn khi nào. Sót thì phải sửa lại hoặc bị trừ điểm |
| B. Gom và xếp ưu tiên deadline, lịch từ nhiều kênh | #1, #3, #7, #8, #9, #14 | Thông tin lặp lại hằng tuần, nằm ở nhiều nơi, người dùng gom và sắp thứ tự bằng tay. Sót thì trễ hạn hoặc trả trễ |
| C. Biến học liệu dài thành ý chính, câu hỏi ôn tập | #2, #4, #5 | Đọc nhiều, mất hàng giờ để rút ý chính, tạo câu hỏi và tìm chỗ chưa vững |
| D. Việc kỹ thuật đơn lẻ | #11, #12 | Bài toán riêng của từng công cụ (Colab, chuyển PDF viết tay), ít người gặp, không cùng pattern với A–C |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: Sinh viên hoàn thành bài lab, đồ án, task đúng yêu cầu và đúng hạn, với ít thời gian rà soát thủ công hơn
├── Opportunity A: Khó biết đầy đủ "cần nộp gì, chấm theo tiêu chí nào" vì yêu cầu nằm rải rác ở nhiều file, kênh; đối chiếu tốn thời gian và dễ sót
├── Opportunity B: Mất công gom deadline từ nhiều kênh và tự quyết định việc nào làm trước; dễ trễ hoặc bỏ sót
└── Opportunity C: Tốn nhiều giờ đọc học liệu dài để rút ý chính và biết mình đã hiểu đến đâu
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

- "Cần chatbot tóm tắt tài liệu" (#2, #5): là công cụ. Pain thật là đọc 100–150 trang tốn 3–4 giờ/tuần.
- "Cần bot nhắc tiến độ nhóm" (#3): là tính năng. Pain thật là phải nhắn giục và chờ 1–2 ngày.
- "Cần Notion/Trello hoặc dashboard deadline" (#1, #14): là công cụ. Pain thật là gom thủ công từ 3–4 nơi.
- "Cần công cụ OCR" (#12) và "cần notebook mẫu Colab" (#11): là công cụ, đồng thời nằm ngoài outcome chung nên không đưa vào cây.

### 2.4. Chấm điểm shortlist (1–5)

Shortlist gồm 3 candidate, mỗi cluster A, B, C một đại diện.

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| A. Đối chiếu yêu cầu, tiêu chí từ nhiều nguồn khi nhận bài (#10, #13, #15) | 5 | 5 | 3 | 4 | 5 | 5 | 5 | 32 |
| B. Gom deadline từ nhiều kênh vào một nơi (#1, #14) | 5 | 5 | 4 | 4 | 3 | 4 | 4 | 29 |
| C. Rút ý chính từ học liệu dài trước buổi học (#2, #5) | 4 | 4 | 3 | 3 | 4 | 3 | 3 | 24 |

Giải thích điểm:

- **A:** cả nhóm đang gặp đúng việc này ngay trong bài lab. Hai người (Quang Anh, Minh) tự vẽ quy trình và cùng chỉ ra bước đối chiếu là chỗ nghẽn. Dễ so sánh checklist cố định (Rule) với workflow đọc file. Bằng chứng mới là số phút tự ghi nhận (10–20 phút/lần), chưa có log, nên "pain có bằng chứng" chỉ 3 và là việc cần kiểm ở CP4.
- **B:** baseline rõ nhất (45–60 phút/tuần, từng sót một quiz chiếm 10% điểm) nhưng cổng trường có OTP, chặn API nên khó lấy dữ liệu trong khuôn khổ lab. iCal/Google Calendar đã giải phần lớn bằng Rule.
- **C:** pain lớn (3–4 giờ/tuần) nhưng khó đo chất lượng tóm tắt, và mỗi môn một nội dung nên nhóm khó tự kiểm độ đúng.

**Candidate được chọn:** Khi nhận bài lab, đồ án hoặc task có yêu cầu và tiêu chí chấm rải rác ở nhiều file hoặc kênh, sinh viên muốn biết đủ đầu ra bắt buộc, tiêu chí chấm và hạn nộp, để không phải đối chiếu thủ công và không bị sót hay trừ điểm.

**Vì sao chọn:** Actor và quy trình rõ nhất, cả 5 thành viên là người dùng thật nên hiểu domain tốt nhất. Bottleneck là một bước cụ thể (đối chiếu giữa các nguồn) và có hai quy trình nháp độc lập cùng trỏ vào. Có thể thử ngay trên repo lab này, và có đủ phương án để so sánh No AI, Rule, Workflow.

**Vì sao loại các candidate còn lại:**

- **B (gom deadline):** khâu lấy dữ liệu bị cổng trường chặn, ngoài tầm lab; iCal/Calendar có sẵn đã xử lý phần lớn nên gần như là bài No AI/Rule.
- **C (tóm tắt học liệu):** impact khó đo vì phải chấm chất lượng tóm tắt, cần chuyên môn từng môn để kiểm tra; điểm thấp nhất (24).
- **D (#11, #12):** không cùng pattern với cluster nào, chỉ một người gặp, nằm ngoài outcome chung.
- **#3, #6, #4, #7, #8, #9:** bằng chứng chủ yếu là số tự ước tính, hoặc bottleneck nằm ở hành vi con người (phản hồi chậm) hay tần suất thấp, nên quy trình nhóm hoặc Rule đã đủ.

**Xử lý bất đồng (nếu có):** Điểm cần cân nhắc là A và B. B có baseline rõ hơn nhưng bị chặn ở khâu lấy dữ liệu; A có baseline yếu hơn nhưng vừa sức lab và nhóm hiểu domain. Nhóm chọn A và chuyển việc kiểm baseline của A sang CP4.

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
| | | | | | |
| | | | | | |
| | | | | | |

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```text

```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |

**Bottleneck chính:**

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text

```

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | | | |
| Tổng thời gian | | | |
| Số bước thủ công | | | |
| Bottleneck chính | | | |
| Rủi ro mới phát sinh | | | |

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
