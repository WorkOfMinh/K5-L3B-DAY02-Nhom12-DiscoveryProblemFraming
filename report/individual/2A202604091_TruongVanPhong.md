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
| AI chỉ ra khâu đăng nhập Moodle và crawl Gmail rất dễ bị vướng cơ chế bảo mật (OTP 2 lớp, Captcha, session hết hạn), khiến việc tự động hóa lấy dữ liệu bằng AI/Script rất dễ gãy trong thực tế. | Đồng ý | Đã tách bạch khâu lấy dữ liệu và khâu xử lý: khâu đăng nhập vẫn do người dùng thực hiện (hoặc xuất file iCal/lịch chuẩn), AI chỉ can thiệp vào khâu trích xuất deadline từ text thông báo phi cấu trúc. |
| AI chỉ ra phương án No AI chưa đủ thuyết phục vì bản thân Moodle và Google Classroom đều có sẵn tính năng iCal feed xuất lịch trực tiếp vào Google Calendar, đã giải quyết được 70% vấn đề mà không cần đến AI. | Đồng ý | Đã viết lại phần Success Metric và Phương án không dùng AI: thừa nhận iCal giải quyết tốt bài tập có cấu trúc cố định, còn AI chỉ giải quyết khoảng trống khi thông báo bài tập nằm trong email tự do hoặc tin nhắn Zalo. |
| AI chỉ ra mục tiêu "Tỷ lệ sót deadline: 0%" là phi thực tế và mang tính khẩu hiệu, khó đo đạc kiểm chứng trong thời gian ngắn. | Đồng ý | Đã sửa lại cách đo: theo dõi số bài tập/quiz bị nộp trễ trong 3 tuần liên tiếp và đo thời gian rà soát deadline hàng tuần bằng đồng hồ bấm giờ (mục tiêu rút từ 55 phút xuống dưới 15 phút). |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Pitch Card #1 (Tổng hợp deadline từ Moodle/Classroom/Gmail) và Card #2 (Tóm tắt tài liệu học thuật trước buổi học). Trình bày rõ baseline thời gian (55 phút/tuần) và sơ đồ 6 bước. | Nhóm xếp Card #1 vào Cluster B và đưa vào shortlist top 3 candidate để chấm điểm lựa chọn. |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt:<br>1. Cho bạn Quang Anh (Card #10): "Nếu checklist chuẩn kèm link file gốc đã đủ giúp sinh viên xác định đủ yêu cầu, bước nào thật sự cần can thiệp bằng AI?"<br>2. Cho bạn Quốc (Card #8): "Có thật sự nhiều hóa đơn sinh hoạt khó theo dõi đến mức cần AI, hay tính năng lịch nhắc cố định trên điện thoại đã đủ?" | Giúp Quang Anh làm rõ bottleneck không phải ở việc đọc từng file mà là đối chiếu chéo giữa nhiều tài liệu (Rubric vs Checkpoint); giúp Quốc nhận ra việc theo dõi hóa đơn chỉ cần Rule/nhắc lịch. |
| Nhận phản biện | Câu hỏi tôi nhận được từ nhóm và Quang Anh: "Cổng trường có OTP/chặn crawl thì lấy dữ liệu đầu vào thế nào? iCal/Google Calendar có sẵn đã giải quyết phần lớn rồi, liệu có thực sự cần AI không?" | Tôi đã sửa gì: Tôi thừa nhận rủi ro kỹ thuật ở khâu lấy dữ liệu là quá lớn đối với một bài lab ngắn, và tính năng iCal đã đáp ứng tốt dạng dữ liệu có cấu trúc. Từ đó tôi đồng ý không đẩy Card #1 làm candidate cuối cùng mà chuyển sự ủng hộ sang Candidate A (Đối chiếu yêu cầu bài lab). |
| Gom cluster / cây OST | Cùng nhóm gom 15 candidate thành 4 cụm (A, B, C, D). Góp ý thống nhất 1 Outcome chung: "Sinh viên hoàn thành bài lab/đồ án đúng yêu cầu, đúng hạn với ít thời gian rà soát thủ công hơn". Trực tiếp gạch bỏ các giải pháp đội lốt như "bot nhắc tiến độ", "app Notion". | Cây OST của nhóm đạt chuẩn: gốc là 1 outcome đo được, các nhánh là Opportunity (nhu cầu/nỗi đau) chứ không chứa tên công cụ. |
| Chọn candidate problem | Cùng nhóm chấm điểm 3 candidate theo 7 tiêu chí. Tham gia tranh luận giữa việc chọn Candidate B (Gom deadline - 29 điểm) và Candidate A (Đối chiếu yêu cầu lab - 32 điểm). | Nhóm thống nhất chọn Candidate A vì tính khả thi cao, cả 5 thành viên đều hiểu sâu domain và thử nghiệm được ngay trên repo lab hiện tại. |
| Kiểm chứng / research | Đề xuất áp dụng triệt để 3 quy tắc của The Mom Test khi phỏng vấn sinh viên khác: chỉ hỏi về hành vi đối chiếu bài lab gần nhất, không hỏi "bạn có thích công cụ AI không". Tìm kiếm các giải pháp checklist hiện có. | Đảm bảo kết quả phỏng vấn phản ánh hành vi thực tế, ghi nhận được tín hiệu phản bác về việc sinh viên hay ỷ lại vào checklist mẫu. |
| Quy trình nhóm | Tham gia phân tích quy trình hiện tại (5 bước, bottleneck ở khâu đối chiếu chéo) và quy trình tương lai (Human-in-the-loop: AI trích xuất tiêu chí, con người tick chọn và chịu trách nhiệm). | Xác lập rõ ràng boundary và phương án quay về (fallback plan): nếu AI trích xuất sai hoặc thiếu, sinh viên vẫn dùng checklist markdown thủ công. |
| Problem Statement | Cùng nhóm viết bản v0 và nâng cấp lên v1, tập trung siết chặt Success Metric (giảm thời gian đối chiếu từ 20 phút xuống dưới 5 phút, tỷ lệ sót tiêu chí 0%) và chỉ rõ điểm can thiệp AI. | Bản Problem Statement v1 hoàn chỉnh, đầy đủ các trường bắt buộc, phân biệt rõ giữa mong muốn và ranh giới an toàn. |
| Mức can thiệp AI | Đóng góp ý kiến vào bảng so sánh 4 mức (No AI / Rule / Workflow / Agent). Bảo vệ quan điểm chỉ dừng ở mức Workflow. | Nhóm thống nhất chọn Workflow, bác bỏ ý tưởng làm Autonomous Agent vì bài toán có luồng xác định, không cần máy tự quyết định hành động tiếp theo. |
| Quyết định | Cùng nhóm đánh giá 4 rủi ro (Value, Usability, Feasibility, Viability) và xây dựng ngưỡng dừng pilot. | Ra quyết định "Go ở phạm vi nhỏ" kèm điều kiện dừng rõ ràng nếu sau 3 bài lab thử nghiệm không đạt hiệu quả cam kết. |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Tìm thêm các góc nhìn về các nỗi đau phổ biến của sinh viên CNTT khi học nhiều môn. | Gợi ý thêm góc nhìn về việc tốn thời gian đọc tài liệu học thuật tiếng Anh trước giờ lên lớp. | AI hay đưa ra giải pháp đội lốt vấn đề (ví dụ: "cần chatbot nhắc deadline", "cần app AI xếp lịch"). | Tôi gạt bỏ toàn bộ tên công cụ, chuyển về dạng Job Story thuần túy và tự bổ sung số liệu đo lường thực tế từ bản thân (45–60 phút/tuần). |
| CP2 Problem Card | Đóng vai Product Manager khó tính để tìm lỗ hổng trong 3 Problem Card của tôi. | Chỉ ra rất sắc bén điểm yếu của Card #1: vướng OTP bảo mật cổng trường và sự trùng lặp với tính năng iCal có sẵn. | AI hay khuyên chung chung kiểu "cần tối ưu trải nghiệm người dùng", "nghiên cứu thêm thị trường" mà không chỉ ra cách giải quyết cụ thể. | Tôi tự bổ sung giải pháp không dùng AI (kết hợp iCal feed và template Notion) và khoanh vùng bottleneck chỉ nằm ở khâu đọc thông báo phi cấu trúc. |
| CP4 Research | Tìm kiếm các công cụ và pattern đã có trên thế giới giải quyết bài toán rà soát yêu cầu và rubric. | Liệt kê nhanh các công cụ như Canvas Rubric tool, Gradescope, GitHub Classroom. | AI tự bịa một số tính năng tích hợp AI mà thực tế các công cụ đó chưa có; nhiều liên kết URL bị lỗi 404 (hallucination). | Tôi tự tay mở từng trang tài liệu chính thức của công cụ, đọc tính năng thật và thay thế bằng các liên kết chuẩn xác còn hoạt động. |
| CP5 Quy trình | Gợi ý cấu trúc sơ đồ quy trình trước/sau bằng Mermaid và bảng so sánh before/after. | Tạo khung mã Mermaid nhanh, trình bày trực quan các luồng rẽ nhánh. | AI vẽ quy trình tự động hóa hoàn toàn từ đầu đến cuối, bỏ quên bước con người kiểm duyệt (Human-in-the-loop) và không có đường quay về khi lỗi. | Tôi tự bổ sung bước con người xác nhận trước khi chốt checklist, thiết lập đường fallback quay về quy trình thủ công nếu AI trích xuất sai. |
| CP5–6 Problem Statement | Rà soát các trường trong Problem Statement v0 để tìm chỗ còn mơ hồ. | Nhắc nhở rất tốt về việc Success Metric phải có đủ 3 yếu tố: baseline, target và cách đo cụ thể. | AI đưa ra metric rất sáo rỗng như "tăng sự hài lòng của sinh viên", "tiết kiệm thời gian đáng kể". | Tôi định lượng hóa thành con số đo được: giảm từ 20 phút xuống dưới 5 phút mỗi bài lab, đo bằng đồng hồ bấm giờ trên 3 bài tập liên tiếp. |
| CP6 Mức can thiệp / quyết định | So sánh ưu nhược điểm giữa Workflow và Autonomous Agent cho bài toán của nhóm. | Phân tích rõ sự khác biệt giữa chuỗi bước tiền định (Workflow) và hệ thống tự lập kế hoạch (Agent). | AI có xu hướng "thổi phồng", khuyên nhóm nên dùng Multi-Agent để giải quyết trọn gói bài toán cho hiện đại. | Tôi kiên quyết bảo vệ mức Workflow: bài toán lab có cấu trúc tài liệu cố định, dùng Agent là lạm dụng công nghệ, rủi ro ảo giác cao và lãng phí token. |

---

## 6. Reflection (CP7)

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

Khi lắng nghe phần pitch của các thành viên trong nhóm, tôi nhận ra một điều thú vị: dù hoàn cảnh xuất phát điểm khác nhau (Quang Anh và tôi tập trung vào việc học đại học, Minh nói về task thực tập tại doanh nghiệp, Quốc nói về sinh hoạt đời sống), nhưng bản chất nỗi đau lại hội tụ về một điểm chung rất rõ ràng. Đó là tình trạng thông tin bị phân mảnh ở quá nhiều kênh (file markdown, Slack, Zalo, cổng trường), khiến người thực hiện mất nhiều thời gian nhất không phải ở khâu làm bài hay giải quyết công việc, mà ở khâu "rà soát xem người ta thực sự yêu cầu mình làm cái gì". Đặc biệt, bài toán của bạn Quang Anh về việc đối chiếu nhiều file trong bài lab GitHub đã chỉ ra một điểm nghẽn mà trước đây tôi vẫn xem là điều hiển nhiên: việc phải mở cùng lúc README, CHECKPOINTS, RUBRIC và SUBMISSION rồi lật qua lật lại mất tới 20 phút mỗi lần. Điều này giúp tôi mở rộng tầm nhìn, không chỉ bó hẹp vấn đề ở việc gom deadline lịch học mà nhìn thấy bức tranh lớn hơn về sự quá tải nhận thức khi tiếp nhận yêu cầu phân tán.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

Nhóm tôi bị "solution-first" rất nặng ở giai đoạn đầu của CP3. Hầu hết các ý tưởng khi đưa lên bảng gom nhóm đều gắn liền với một công cụ cụ thể: "cần bot tự nhắc tiến độ Zalo", "cần app gom deadline tích hợp Notion", "cần tool OCR chuyển tài liệu". Mọi người có xu hướng bàn luận xem dùng mô hình nào, làm bot Telegram hay Zalo trước khi làm rõ người dùng thực sự đau ở bước nào. Nhóm chỉ giật mình nhận ra khi bước vào bài tập vẽ Opportunity Solution Tree (OST), nơi quy tắc yêu cầu gạch bỏ toàn bộ các giải pháp đội lốt cơ hội. Khi bị buộc phải trả lời câu hỏi: "Nếu không có con bot đó, nỗi đau thực sự là gì?", nhóm mới bóc tách được: bản chất không phải sinh viên "thiếu một con bot", mà là họ "mất 1–2 ngày chờ đợi phản hồi" hoặc "mất 20 phút lật qua lật lại các file". Việc thẳng tay gạch bỏ các tên công cụ trên cây OST đã giúp nhóm kéo tư duy quay trở lại đúng bản chất của vấn đề.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

Tôi đã có một lần đổi ý mang tính bước ngoặt ở cuối CP3. Ban đầu, tôi rất kiên quyết bảo vệ Candidate #1 của mình (Gom deadline từ Moodle, Classroom, Gmail) vì tôi là người trực tiếp chịu ảnh hưởng hàng tuần, có số liệu đo lường rất cụ thể (mất 55 phút mỗi tối Chủ nhật, từng bị trượt 1 quiz 10%). Tôi cho rằng bài này có baseline thuyết phục nhất nhóm. Tuy nhiên, khi bạn Quang Anh và các thành viên khác phản biện: "Cổng trường có bảo mật 2 lớp OTP và chặn crawl thì làm sao lấy dữ liệu vào?", cùng câu hỏi "Bản thân iCal của Moodle đã đồng bộ được vào Google Calendar, vậy AI giải quyết được thêm bao nhiêu %?", tôi đã phải dừng lại suy ngẫm. Tôi nhận ra mình đang bị thiên vị ý tưởng cá nhân (confirmation bias) mà xem nhẹ tính khả thi kỹ thuật. Khâu lấy dữ liệu từ hệ thống trường là rào cản quá lớn trong phạm vi một bài lab, và phần lớn vấn đề đã giải được bằng Rule (iCal). Tôi đã chủ động đổi ý, rút lui Candidate #1 và dồn toàn bộ sự ủng hộ cho Candidate A (Đối chiếu yêu cầu bài lab) vì bài toán này nằm hoàn toàn trong tầm kiểm soát của nhóm, dữ liệu đầu vào có sẵn và giải quyết đúng nỗi đau chung của cả 5 người.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

Điều làm tôi bất ngờ nhất khi tìm hiểu các giải pháp hiện có trên thị trường là sự "lệch pha" giữa tính năng của các hệ thống LMS lớn và trải nghiệm thực tế của người học. Các nền tảng như Canvas hay Moodle đầu tư rất nhiều vào bộ chấm điểm Rubric cho giảng viên (giúp giảng viên click chấm điểm nhanh và minh bạch), nhưng lại hoàn toàn bỏ quên trải nghiệm của sinh viên ở khâu chuẩn bị bài. Sinh viên không hề có một giao diện trực quan nào để tự đối chiếu bài làm của mình với rubric trước khi nộp, ngoài việc phải tự mở file PDF rubric ra và đọc bằng mắt. Điều bất ngờ thứ hai khi nhóm phỏng vấn thử bạn học là: nhiều sinh viên thậm chí không đọc Rubric trước khi làm bài, chỉ đến khi bị trừ điểm mới mở ra xem vì các file quá dài và rải rác. Điều này củng cố niềm tin của tôi rằng khoảng trống giải pháp là có thật, và nếu có một công cụ giúp tự động trích xuất checklist đối chiếu ngay từ đầu, giá trị mang lại cho sinh viên là rất lớn.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

Điều khó nhất đối với tôi và cả nhóm khi viết Problem Statement là việc xác lập Ranh giới (Boundary) và Tiêu chí thành công (Success Metric) có thể định lượng được. Ban đầu, nhóm viết metric rất chung chung theo cảm xúc như "giúp sinh viên nộp bài tự tin hơn" hoặc "tiết kiệm thời gian đáng kể". Phải mất rất nhiều lần chỉnh sửa, nhóm mới ép được metric về dạng chuẩn mực: baseline là gì (20 phút đối chiếu thủ công), target là bao nhiêu (dưới 5 phút), và cách đo cụ thể ra sao (bấm giờ trong 3 bài lab liên tiếp). Về phần Boundary, việc xác định "AI KHÔNG ĐƯỢC LÀM GÌ" khó hơn nhiều so với việc nghĩ ra tính năng AI. Nhóm đã phải tranh luận gay gắt để đi đến ranh giới rõ ràng: AI chỉ trích xuất tiêu chí và hiển thị checkbox đối chiếu, tuyệt đối không được tự ý sửa nội dung bài làm hay tự bấm nút nộp bài thay cho sinh viên. Quyền kiểm tra và chịu trách nhiệm cuối cùng bắt buộc phải thuộc về con người (Human-in-the-loop).

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

Nếu được làm lại buổi thảo luận từ đầu, tôi sẽ yêu cầu các thành viên thực hiện việc bấm giờ thực tế ngay từ CP1 thay vì chấp nhận các con số ước lượng cảm tính trong bảng scan. Việc thiếu số liệu đo đạc chính xác khiến nhóm mất khá nhiều thời gian tranh cãi ở CP3 về việc bài nào tốn thời gian hơn. Bên cạnh đó, tôi sẽ phản biện quyết liệt hơn đối với các ý tưởng của bạn Quốc về việc quản lý chi tiêu và bữa ăn gia đình ngay từ đầu. Mặc dù các bài toán đó rất thực tế trong đời sống, nhưng chúng quá phân tán, đối tượng người dùng không đồng nhất và nhóm không thể trực tiếp kiểm chứng trong khuôn khổ thời gian của buổi lab. Nếu gạt bỏ sớm những ý tưởng ngoài phạm vi, nhóm sẽ dành được thêm nhiều thời gian để hoàn thiện sâu hơn các kịch bản kiểm thử (eval criteria) cho bài toán bài lab được chọn.

**6.7. Hiểu bài:**

Vấn đề cốt lõi của nhóm là sinh viên mất quá nhiều thời gian (khoảng 20 phút) và rất dễ bỏ sót các tiêu chí chấm điểm quan trọng khi phải đối chiếu thủ công giữa nhiều file tài liệu phân tán (README, Rubric, Checkpoints, Submission) trước khi làm và nộp bài lab. Quy trình giải quyết là xây dựng một luồng làm việc mà công cụ sẽ tự động đọc các file markdown của bài lab, trích xuất toàn bộ các đầu việc bắt buộc và tiêu chí chấm thành một checklist tập trung, sau đó sinh viên trực tiếp rà soát từng mục và xác nhận hoàn thành. Thước đo thành công được lượng hóa cụ thể: giảm thời gian đối chiếu từ 20 phút xuống dưới 5 phút mỗi bài lab và đạt tỷ lệ bỏ sót tiêu chí bằng 0%. Ranh giới an toàn được thiết lập nghiêm ngặt: hệ thống chỉ đóng vai trò trích xuất và hiển thị danh sách đối chiếu (Augment), tuyệt đối không tự ý chỉnh sửa nội dung bài nộp hay tự động submit thay người dùng; nếu AI trích xuất sai hoặc thiếu, sinh viên vẫn có phương án quay về sử dụng bảng checklist mẫu thủ công. Mức can thiệp được lựa chọn là Workflow (chuỗi các bước xác định kết hợp mô hình trích xuất thông tin) chứ không sử dụng Autonomous Agent vì quy trình hoàn toàn cố định và không đòi hỏi máy phải tự lập kế hoạch hành động. Quyết định cuối cùng của nhóm là Go ở phạm vi pilot nhỏ, thử nghiệm trực tiếp trên các bài lab tiếp theo với ngưỡng dừng đo được: nếu sau 3 bài lab mà thời gian rà soát không giảm được ít nhất 50% hoặc tỷ lệ trích xuất sai tiêu chí vượt quá 10%, nhóm sẽ lập tức dừng dự án và quay về phương án checklist thủ công.

---

## 7. Tài liệu tham khảo

- Google PAIR (People + AI Research) Guidebook: Thiết kế tương tác AI lấy con người làm trung tâm, mẫu thiết kế Augment vs. Automate và phân tích chi phí lỗi sai.
- Rob Fitzpatrick, *The Mom Test: How to talk to customers & learn if your business is a good idea when everyone is lying to you*, 2013 (Nguyên tắc phỏng vấn kiểm chứng hành vi quá khứ).
- Teresa Torres, *Continuous Discovery Habits*, 2021 (Mô hình Opportunity Solution Tree - OST).
- Tài liệu học phần: `docs/01-worksheet.md`, `docs/02-deliverable-example.md`, `docs/03-international-frameworks.md`.
- Quy chuẩn đánh giá và tiêu chí bài nộp: `RUBRIC.md`, `RULES.md`, `CHECKPOINTS.md`.
