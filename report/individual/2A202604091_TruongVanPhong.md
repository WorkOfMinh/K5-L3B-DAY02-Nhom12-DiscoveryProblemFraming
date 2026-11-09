# Báo cáo cá nhân — 2A202604091_TruongVanPhong

## 1. Thông tin học viên

- Họ tên: Trương Văn Phong
- MSSV: 2A202604091
- Email trường: 26ai.phongtv@vinuni.edu.vn
- Tên nhóm: Nhóm 12 (Lớp K5-L3B)
- Link repo nhóm: https://github.com/WorkOfMinh/K5-L3B-DAY02-Nhom12-DiscoveryProblemFraming
- Bối cảnh nhân vật: Lan, sinh viên năm 3 ngành Công nghệ Thông tin tại Đại học Bách Khoa TP.HCM. Lan học 7 môn trong học kỳ này, sử dụng Moodle (BKeL), Google Classroom, Gmail và Zalo để theo dõi bài tập, thông báo từ giảng viên và hoạt động nhóm. Mỗi tuần Lan phải tổng hợp deadline từ nhiều nguồn để tránh nộp bài muộn.

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Lặp lại | Khi bắt đầu một tuần học mới, tôi muốn có tất cả deadline từ Moodle, Google Classroom và Gmail ở một nơi, để không phải tự ghi chép lại vào sổ tay | Lan, các bạn cùng nhóm học tập | Mỗi tối Chủ nhật mất 45–60 phút rà soát 7 môn học trên 3 nền tảng khác nhau |
| 2 | Tốn thời gian | Khi giảng viên đăng tài liệu 30–50 trang trước buổi học, tôi muốn có bản tóm tắt các ý chính và câu hỏi thảo luận, để chuẩn bị bài nhanh hơn | Lan, sinh viên trong lớp | Mỗi tuần đọc khoảng 100–150 trang tài liệu cho 3 môn lý thuyết; thường mất 3–4 giờ chuẩn bị trước giờ lên lớp |
| 3 | Cần đọc, tổng hợp nhiều thông tin | Khi sắp đến kỳ thi giữa kỳ, tôi muốn biết chính xác môn nào cần ưu tiên ôn tập trước, để không bỏ sót môn quan trọng | Lan | Học kỳ trước bỏ sót 1 bài quiz trên Moodle chiếm 10% điểm môn học do không nắm rõ lịch mở đề |
| 4 | Pain từ người khác | Khi làm bài tập nhóm, tôi muốn biết ai đang làm phần nào và tiến độ ra sao, để không phải nhắn tin hỏi từng thành viên | Lan (trưởng nhóm) và 4 thành viên trong nhóm | Trung bình mỗi sprint/bài tập nhóm có 15–20 tin nhắn Zalo chỉ để tag tên hỏi "làm đến đâu rồi", gây phiền hà |
| 5 | Cần đọc, tổng hợp nhiều thông tin | Khi tìm tài liệu tham khảo cho đồ án môn học, tôi muốn được gợi ý nguồn phù hợp từ nhiều website học thuật, để không phải tìm thủ công từng nơi | Lan | Mất khoảng 2 giờ để tìm đủ 5–7 tài liệu tham khảo uy tín (IEEE, Google Scholar) cho một bài báo cáo đồ án |

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Tổng hợp deadline tuần (#1) | Quy trình lặp lại hàng tuần rất rõ ràng; bottleneck cụ thể (đăng nhập và rà soát nhiều cổng thông tin); baseline đo được ngay (45–60 phút/tuần); dễ so sánh No AI vs AI | Có cổng trường chặn API / CAPTCHA cần xử lý thủ công không |
| 2 | Tóm tắt tài liệu đọc trước (#2) | Pain tốn thời gian rất lớn (3–4 giờ/tuần đọc 150 trang); sinh viên thường xuyên bị quá tải thông tin trước giờ lên lớp | Làm sao đo được chất lượng bản tóm tắt có đủ sâu để trả lời câu hỏi của giảng viên không |
| 3 | Theo dõi tiến độ bài tập nhóm (#4) | Pain từ người khác rõ rệt (15–20 tin nhắn giục giã/tuần); ảnh hưởng trực tiếp đến kết quả đồ án nhóm | Thành viên nhóm có chịu duy trì cập nhật trạng thái nếu dùng công cụ mới không |

### Problem Card #1 — Tổng hợp deadline đa nền tảng

| Trường | Nội dung |
|---|---|
| Job Story | Khi bắt đầu một tuần học mới, tôi muốn có tất cả deadline từ Moodle, Google Classroom và Gmail ở một nơi, để không phải tự ghi chép lại vào sổ tay và không bao giờ trễ hạn |
| Actor | Lan (sinh viên năm 3 ngành CNTT học 7 môn) và các sinh viên đại học học nhiều môn song song |
| Thời điểm / bối cảnh | Tối Chủ nhật hàng tuần hoặc sáng thứ Hai trước khi tuần học mới bắt đầu |
| Quy trình hiện tại (3–7 bước) | 1. Mở laptop, đăng nhập Moodle BKeL của 7 môn học<br>2. Kiểm tra từng môn xem có bài tập mới/quiz mở trong tuần không<br>3. Mở Google Classroom kiểm tra các bài tập thực hành<br>4. Tìm kiếm từ khóa "deadline", "bài tập" trong hộp thư Gmail trường<br>5. Lướt các nhóm Zalo môn học xem có thông báo bổ sung từ lớp trưởng/giảng viên không<br>6. Ghi chép thủ công các mốc thời gian vào sổ tay / app Notion cá nhân<br>7. Đặt báo thức điện thoại nhắc nhở trước hạn nộp |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2 + Bước 4: Đăng nhập từng khóa học trên Moodle và đọc lướt email để lọc deadline (mất 30–35 phút/lần vì giao diện rời rạc, thông báo phân tán) |
| Impact (nếu không giải thì sao) | Mất 45–60 phút mỗi tuần; nguy cơ bỏ sót bài tập/quiz (chiếm 10–20% trọng số môn); gây tâm lý căng thẳng, lo sợ nộp bài muộn |
| Success metric (baseline → target) | - Baseline: 45–60 phút/tuần tổng hợp thủ công.<br>- Target: Giảm xuống dưới 10 phút/tuần.<br>- Tỷ lệ sót deadline: 0%. |
| Phương án không dùng AI | Dùng tính năng RSS feed / iCal export sẵn có của Moodle và Classroom đồng bộ trực tiếp vào Google Calendar + lập checklist Notion theo mẫu cố định |
| Giả thuyết về AI (nếu có) | AI (LLM / Script parser) quét nội dung email và thông báo Zalo dạng tự do, trích xuất cấu trúc: `Tên môn - Nhiệm vụ - Deadline - Link nộp` vào lịch |
| Cảm nhận nhanh | Rule hoặc Workflow (Chưa cần đến Agent phức tạp) |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — Tổng thời gian: 55 phút/tuần

[1 Đăng nhập Moodle: 5'] 
→ [2 Rà soát 7 môn trên Moodle: 20'] ← BOTTLENECK 1 (nhiều tab, giao diện chậm)
→ [3 Check Google Classroom: 10']
→ [4 Tìm lọc email trường: 10'] ← BOTTLENECK 2 (email lẫn lộn thông báo trường)
→ [5 Đọc lướt Zalo nhóm môn: 5']
→ [6 Ghi chép vào sổ/Notion + Đặt báo thức: 5']
```

---

### Problem Card #2 — Tóm tắt tài liệu học thuật trước buổi học

| Trường | Nội dung |
|---|---|
| Job Story | Khi giảng viên đăng tài liệu 30–50 trang trước buổi học, tôi muốn có bản tóm tắt các ý chính và câu hỏi thảo luận, để chuẩn bị bài nhanh hơn |
| Actor | Lan (sinh viên CNTT) và sinh viên các khối ngành cần đọc nhiều tài liệu lý thuyết |
| Thời điểm / bối cảnh | 1–2 ngày trước buổi học trên lớp, khi giảng viên tải slide/PDF lên hệ thống |
| Quy trình hiện tại (3–7 bước) | 1. Tải file tài liệu (PDF/PPTX) từ Moodle về máy<br>2. Đọc lướt qua mục lục và các tiêu đề chính<br>3. Đọc chi tiết từng trang, vừa đọc vừa dùng bút highlight ý quan trọng<br>4. Tra cứu các thuật ngữ tiếng Anh chuyên ngành chưa hiểu trên Google<br>5. Tự ghi chú lại dàn ý (outline) 1–2 trang ra vở hoặc Notion<br>6. Soạn sẵn 1–2 câu hỏi thắc mắc chuẩn bị hỏi giảng viên |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3 + Bước 4: Đọc chi tiết và tra cứu thuật ngữ chuyên ngành mất 120–150 phút/tài liệu |
| Impact (nếu không giải thì sao) | Mất 3–4 giờ/tuần; thường xuyên không đọc kịp tài liệu dẫn đến lên lớp nghe giảng thụ động, không tham gia phát biểu xây dựng bài |
| Success metric (baseline → target) | - Baseline: 180 phút/tuần đọc và ghi chú.<br>- Target: Giảm xuống dưới 45 phút/tuần.<br>- Vẫn trả lời được các câu hỏi kiểm tra bài cũ trên lớp. |
| Phương án không dùng AI | Đọc phần tóm tắt chương (Summary) và câu hỏi cuối chương trong sách giáo trình gốc; chia nhóm bạn mỗi người đọc 1 phần rồi trao đổi |
| Giả thuyết về AI (nếu có) | AI đọc file PDF, trích xuất cấu trúc chương, tóm tắt ý chính theo dạng bullet points kèm thuật ngữ cốt lõi và 3 câu hỏi gợi mở thảo luận |
| Cảm nhận nhanh | Workflow (Dùng mô hình ngôn ngữ tóm tắt theo template định sẵn) |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — Tổng thời gian: 180 phút/tuần (cho 1 tài liệu 40 trang)

[1 Tải PDF về máy: 5']
→ [2 Đọc lướt mục lục: 10']
→ [3 Đọc chi tiết & highlight: 100'] ← BOTTLENECK CHÍNH (tốn thời gian đọc chữ)
→ [4 Tra cứu thuật ngữ chuyên ngành: 35'] ← BOTTLENECK PHỤ
→ [5 Tóm tắt dàn ý vào Notion: 20']
→ [6 Nghĩ câu hỏi chuẩn bị lên lớp: 10']
```

---

### Problem Card #3 — Theo dõi tiến độ bài tập nhóm

| Trường | Nội dung |
|---|---|
| Job Story | Khi làm bài tập nhóm đồ án, tôi muốn biết ai đang làm phần nào và tiến độ ra sao, để không phải nhắn tin hỏi từng thành viên và kịp nộp bài đúng hạn |
| Actor | Lan (nhóm trưởng đồ án) và 4 thành viên trong nhóm sinh viên |
| Thời điểm / bối cảnh | Trong suốt thời gian 4–6 tuần thực hiện đồ án môn học, đặc biệt là giai đoạn 3 ngày trước deadline nộp bài |
| Quy trình hiện tại (3–7 bước) | 1. Nhóm họp phân chia task qua Google Meet/Zalo<br>2. Tạo group chat Zalo riêng cho nhóm đồ án<br>3. Đến giữa tuần, nhóm trưởng nhắn tin tag từng thành viên hỏi tiến độ<br>4. Chờ các thành viên phản hồi tin nhắn (có người trả lời ngay, có người quên/trễ)<br>5. Nhóm trưởng tổng hợp lại ai đã làm xong, ai bị kẹt (blocker)<br>6. Nhắc nhở thành viên trễ hạn hoặc hỗ trợ giải quyết blocker<br>7. Ghép bài làm của các thành viên trước hạn nộp 24h |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3 + Bước 4: Nhắn tin giục và chờ đợi phản hồi từ từng cá nhân (mất 1–2 ngày chờ đợi, 15–20 tin nhắn giục giã gây ức chế) |
| Impact (nếu không giải thì sao) | Bài tập nhóm hay bị dồn vào đêm chót; sản phẩm ghép nối rời rạc; rạn nứt mối quan hệ giữa các thành viên trong nhóm |
| Success metric (baseline → target) | - Baseline: 15–20 tin nhắn hỏi tiến độ mỗi sprint; trễ deadline ghép bài 1–2 ngày.<br>- Target: Dưới 3 tin nhắn giục; 100% thành viên cập nhật trạng thái trước 24h; nộp bài trước hạn ít nhất 6 tiếng. |
| Phương án không dùng AI | Sử dụng bảng Kanban Trello / Notion Board + quy định giờ standup online 10 phút cố định vào tối thứ Tư hàng tuần |
| Giả thuyết về AI (nếu có) | Bot tự động nhắc nhở thành viên vào khung giờ cố định và ghi nhận báo cáo tiến độ dạng chat ngắn để cập nhật vào bảng chung |
| Cảm nhận nhanh | No AI hoặc Rule (Chỉ cần siết quy trình và dùng Rule thông báo tự động) |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — Chu kỳ 1 tuần làm đồ án nhóm

[1 Phân chia task: 30'] 
→ [2 Làm bài độc lập: 3-4 ngày]
→ [3 Nhắn tin tag Zalo hỏi tiến độ: 15']
→ [4 Chờ phản hồi & giục lần 2, lần 3: 1-2 ngày] ← BOTTLENECK (chờ đợi, lo lắng)
→ [5 Nhóm trưởng tổng hợp tình hình: 30']
→ [6 Hối hả ghép code / bài báo cáo đêm chót: 120']
```

---

### Card muốn pitch nhất

- **Card số:** Card #1 — Tổng hợp deadline đa nền tảng
- **Vì sao:** Đây là vấn đề có tần suất lặp lại cao nhất (hàng tuần), ảnh hưởng trực tiếp đến kết quả học tập của Lan và tất cả sinh viên. Quy trình hiện tại rất rõ ràng, baseline thời gian đo lường được ngay (55 phút/tuần), và ranh giới bài toán vừa sức giải quyết trong khuôn khổ lab.
- **Câu hỏi muốn nhóm phản biện:** 
  1. Nếu các nền tảng trường học (như Moodle) có cơ chế bảo mật (OTP/chặn crawl dữ liệu), làm sao giải quyết khâu lấy dữ liệu đầu vào mà không cần sinh viên copy tay?
  2. Việc đồng bộ iCal/Google Calendar có sẵn đã giải quyết được bao nhiêu % vấn đề này rồi, liệu có thực sự cần đến AI không hay chỉ cần Rule/Script tự động hóa?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| (TODO: tự điền nếu bạn có dùng AI phản biện card) | | |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | | |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: | |
| Nhận phản biện | Câu hỏi tôi nhận được: | Tôi đã sửa gì: |
| Gom cluster / cây OST | | |
| Chọn candidate problem | | |
| Kiểm chứng / research | | |
| Quy trình nhóm | | |
| Problem Statement | | |
| Mức can thiệp AI | | |
| Quyết định | | |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | | | | |
| CP2 Problem Card | | | | |
| CP4 Research | | | | |
| CP5 Quy trình | | | | |
| CP5–6 Problem Statement | | | | |
| CP6 Mức can thiệp / quyết định | | | | |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

---

## 7. Tài liệu tham khảo

-
