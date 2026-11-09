# Báo cáo kết quả hoạt động nhóm 12

## 1. Thông tin và hoàn cảnh bài toán

**Tên thành viên:** Nguyễn Anh Tú  
**Mã SV:** 2A202604088
**Tên nhóm:** Nhóm 12
**Link repo nhóm:** https://github.com/WorkOfMinh/K5-L3B-DAY02-Nhom12-DiscoveryProblemFraming

Là một sinh viên đại học, thường thường ta cần phải xử lý rất là nhiều công việc cùng lúc:

- Học nhiều môn, mỗi môn có tài liệu riêng.
- Có lịch kiểm tra, lịch nộp bài và muôn vàn lịch khác.
- Cần phải chuẩn bị trước giáo trình bài vở ở nhà trước khi lên trường học.
- Có những vấn đề thắc mắc xong không biết tìm ai để hỏi.
- Khó khăn trong việc phân bổ thời gian cho học tập, công việc thêm, tình cảm và đời sống cá nhân.

## 2. Scan problem (CP1)

Giả sử 10 vấn đề trog thực tế

| # | Lăng kính | Job story | Ai chịu ảnh hưởng | Dấu hiệu thật |
| --- | --- | --- | --- | --- |
| 1 | Lặp lại | Khi có bài tập hàng tuần, tôi muốn biết những dạng bài mình thường sai để không phải tự kiểm tra lại từ đầu. | Bản thân tôi, sinh viên | Mất trong khoảng 30p hằng ngày |
| --- | --- | --- | --- | --- |
| 2 | Lặp lại | Trước khi đi học, tôi thường hay bỏ ra thời gian để học trước bài và gạch ra các keywork nhằm bổ trợ cho bài học | Bản thân tôi, sinh viên | Mất khoảng 10-15p hằng ngày |
| --- | --- | --- | --- | --- |
| 3 | Tốn thời gian | Khi học nhóm, tôi và các bạn thường bỏ ra nhiều thời gian trong ngày để ôn tập cùng nhau, nhờ có việc đó mà chúng tôi có thể dễ dàng qua bài kiểm tra của các đợt trong thời sinh viên | Bản thân, bạn bè, sinh viên | Thi thoảng khoảng 2-3 tiếng/ ngày, có khi có thể 4-5 tiếng, xong chỉ vào khi thi thôi |
| --- | --- | --- | --- | --- |
| 4 | Cần tổng hợp thông tin | Khi có nhiều deadline trong tuần, tôi muốn biết việc nào cần ưu tiên để không bị trễ hạn | Bản thân, sinh viên | Thi thoảng khoảng 2-3 tiếng/ ngày, có khi có thể 4-5 tiếng |
| --- | --- | --- | --- | --- |
| 5 | Khó hiểu | Khi học một khái niệm khó, tôi muốn có lời giải thích bằng ví dụ đời thường để hiểu bản chất | Bản thân, sinh viên | Phải hỏi bạn bè hoặc tìm nhiều video |
| --- | --- | --- | --- | --- |
| 6 | Lặp lại | Khi chuẩn bị thi, tôi muốn tự động tạo câu hỏi ôn tập từ tài liệu để không phải tự soạn từng câu | Bản thân, sinh viên | Thường phải đi mua sách, tài liệu tham khảo mới, để lọc ra đề phù hợp có thể mất đến 45 phút tạo bộ câu hỏi |
| --- | --- | --- | --- | --- |
| 7 | Tốn thời gian | Khi cần làm slide thuyết trình, tôi muốn chuyển nội dung tài liệu thành dàn ý để tiết kiệm thời gian chuẩn bị | Bản thân, sinh viên | Mất khoảng 2 giờ cho mỗi bài thuyết trình, đôi khi có thể nhiều hơn |
| --- | --- | --- | --- | --- |
| 8 | Rủi ro sai só |Khi sử dụng AI để giải bài tập, tôi muốn kiểm chứng được đáp án để tránh học sai kiến thức | Bản thân, sinh viên |  Đã từng gặp câu trả lời AI sai nhưng không nhận ra ngay |
| --- | --- | --- | --- | --- |
| 9 | Pain từ người khác |Khi làm bài tập nhóm, tôi muốn các thành viên hiểu thống nhất yêu cầu để tránh sửa đi sửa lại | Bản thân, thành viên nhóm, sinh viên |  Một bài tập phải chỉnh sửa 3 lần, có khi mất đến cả buổi chiều mà chỉ giải quyết được một vấn đề vì các thành viên cứ im lặng và không phản hồi gì trong thời gian trao đổi |
| --- | --- | --- | --- | --- |
| 10 | Khi nhờ bạn bè giải thích bài học, tôi muốn nhận được câu trả lời kịp thời để không bị gián đoạn việc học | Bản thân, bạn bè, sinh viên |  Có lần phải chờ đến ngày hôm sau mới được giải đáp |
| --- | --- | --- | --- | --- |

## 3. Top 3 Problem Cards (CP2)

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc chắn |
| --- | --- | --- | --- |
| 1 | Nhận diện dạng bài thường sai (#1) | Có tính lặp lại, mất 30p/ ngày, Nếu không nhận diện được lỗi sai, sinh viên có thể tiếp tục mắc cùng một lỗi trong những bài tập tiếp theo | 30 phút đó có thực sự dành cho việc tìm ra lỗi sai hay bao gồm cả thời gian làm bài?, Những lỗi sai có lặp lại theo một quy luật nhất định không? Sinh viên có thực sự muốn một hệ thống theo dõi lỗi sai cá nhân hay chỉ cần đáp án và lời giải?|
| 2 | Tạo câu hỏi ôn tập từ tài liệu học tập (#6) | Đây là công việc khá phổ biến trong quá trình học đại học, đặc biệt trước các kỳ thi, Sinh viên thường phải tìm kiếm sách, tài liệu tham khảo và lọc ra những câu hỏi phù hợp | 45 phút là thời gian tạo câu hỏi hay bao gồm cả việc tìm kiếm và chọn tài liệu?, Câu hỏi do AI tạo ra có bám sát nội dung giảng viên dạy và cấu trúc đề thi không?, Sinh viên có sẵn sàng sử dụng câu hỏi do AI tạo thay vì câu hỏi từ sách và giảng viên không? |
| 3 | Khó khăn trong trao đổi và thống nhất khi làm bài tập nhóm (#9) | Đây không chỉ là vấn đề cá nhân mà còn ảnh hưởng đến hiệu quả làm việc của cả nhóm, Nguyên nhân không chỉ nằm ở chuyên môn mà còn ở việc thành viên không phản hồi, không thống nhất cách hiểu và thiếu phân công rõ ràng. | Việc sửa đi sửa lại xuất phát từ hiểu sai yêu cầu, thiếu kiến thức hay thiếu trách nhiệm của thành viên?, Các thành viên im lặng vì không hiểu vấn đề, không quan tâm hay đơn giản là bận?, AI có thực sự cải thiện được sự phối hợp giữa con người hay chỉ hỗ trợ tổng hợp thông tin? |

### Problem Card #1 — Nhận diện lỗi sai và ôn tập cá nhân hóa
| Trường | Nội dung |
| --- | --- |
| Job Story | Khi có bài tập hàng tuần, tôi muốn biết những dạng bài mình thường sai để không phải tự kiểm tra lại từ đầu. |
| Actor | Sinh viên đại học, người trực tiếp làm bài tập và tự đánh giá kết quả học tập. |
| Thời điểm / bối cảnh | Trong quá trình học tập hằng ngày, đặc biệt sau khi hoàn thành bài tập hoặc bài kiểm tra. |
| Quy trình hiện tại | 1. Nhận bài tập từ giảng viên · 2. Tự làm bài · 3. Kiểm tra đáp án · 4. Đối chiếu câu sai · 5. Tìm hiểu nguyên nhân sai · 6. Ghi nhớ kiến thức và tự ôn tập lại. |
| Bottleneck | Bước 4–5: Tự nhận diện và phân loại lỗi sai. Sinh viên phải tự xem lại bài, tìm nguyên nhân và xác định kiến thức chưa vững. |
| Impact | Mất khoảng 30 phút hằng ngày cho hoạt động kiểm tra và nhận diện lỗi sai (cần xác minh chính xác 30 phút bao gồm những công đoạn nào). Nếu lặp lại trong 7 ngày, tương đương khoảng 210 phút/tuần. |
| Success metric | Giảm thời gian nhận diện và phân loại lỗi sai từ 30 phút xuống dưới 10 phút/ngày; khả năng nhận diện đúng lỗi sai không giảm; kết quả làm lại các dạng bài từng sai được cải thiện. |
| Phương án không dùng AI | Sử dụng bảng Excel hoặc sổ ghi chép để lưu câu sai, phân loại theo chương và dạng bài, sau đó tự thống kê những nội dung thường mắc lỗi. |
| Giả thuyết về AI | AI phân tích lịch sử làm bài, nhận diện các dạng bài thường sai, phân loại nguyên nhân và đề xuất bài tập tương ứng để sinh viên luyện tập. |
| Cảm nhận nhanh | Workflow + Personalization |

**Workflow hiện tại — Quy trình tự nhận diện lỗi sai**

```text
[1 Nhận bài tập]
       ↓
[2 Tự làm bài]
       ↓
[3 Kiểm tra đáp án]
       ↓
[4 Đối chiếu câu sai]
       ↓
[5 Tìm nguyên nhân sai] ← BOTTLENECK
       ↓
[6 Ghi nhớ và ôn tập lại]
```

### Problem Card #2 — Tạo bộ câu hỏi ôn tập từ tài liệu
| Trường | Nội dung |
| --- | --- |
| Job Story | Khi chuẩn bị thi, tôi muốn tự động tạo câu hỏi ôn tập từ tài liệu để không phải tự soạn từng câu. |
| Actor | Sinh viên đại học đang chuẩn bị cho các bài kiểm tra giữa kỳ, cuối kỳ hoặc kiểm tra thường xuyên. |
| Thời điểm / bối cảnh | Trước các kỳ kiểm tra, khi sinh viên cần hệ thống hóa kiến thức và luyện tập theo nội dung giảng viên cung cấp. |
| Quy trình hiện tại | 1. Tìm kiếm sách và tài liệu tham khảo · 2. Tìm tài liệu phù hợp với môn học · 3. Đọc và lọc nội dung quan trọng · 4. Chọn câu hỏi phù hợp · 5. Tự soạn câu hỏi hoặc tổng hợp câu hỏi có sẵn · 6. Kiểm tra đáp án và sử dụng để ôn tập. |
| Bottleneck | Bước 2–5: Tìm kiếm, chọn lọc tài liệu và xây dựng bộ câu hỏi phù hợp với nội dung cần thi. |
| Impact | Mất khoảng 45 phút để tạo bộ câu hỏi theo mô tả ban đầu. Ngoài ra, sinh viên còn phải tìm mua sách hoặc tài liệu tham khảo để có nguồn câu hỏi phù hợp. Chưa xác định được tần suất thực hiện trong một học kỳ. |
| Success metric | Giảm thời gian tạo bộ câu hỏi từ 45 phút xuống dưới 10 phút; ít nhất 80% câu hỏi được người học đánh giá là phù hợp với tài liệu; đáp án và lời giải không có lỗi nghiêm trọng sau khi kiểm chứng. |
| Phương án không dùng AI | Sử dụng ngân hàng câu hỏi có sẵn, đề thi các năm trước, flashcard hoặc tự tạo câu hỏi bằng template trong Word/Excel. |
| Giả thuyết về AI | AI đọc tài liệu PDF, Word hoặc slide bài giảng, trích xuất kiến thức trọng tâm và tự động tạo câu hỏi trắc nghiệm, tự luận kèm đáp án, giải thích và mức độ khó. |
| Cảm nhận nhanh | Workflow + Content Generation |

**Workflow hiện tại — Quy trình tạo bộ câu hỏi ôn tập**

```text
[1 Tìm kiếm sách/tài liệu]
          ↓
[2 Chọn tài liệu phù hợp]
          ↓
[3 Đọc và lọc kiến thức]
          ↓
[4 Chọn câu hỏi phù hợp]
          ↓
[5 Tự soạn/tổng hợp câu hỏi] ← BOTTLENECK
          ↓
[6 Kiểm tra đáp án]
          ↓
[7 Sử dụng để ôn tập]
```

### Problem Card #3 — Khó khăn trong trao đổi và thống nhất khi làm bài tập nhóm
| Trường | Nội dung |
| --- | --- |
| Job Story | Khi làm bài tập nhóm, tôi muốn các thành viên hiểu thống nhất yêu cầu để tránh sửa đi sửa lại. |
| Actor | Sinh viên tham gia làm việc nhóm, đặc biệt là nhóm trưởng và các thành viên chịu trách nhiệm thực hiện bài tập. |
| Thời điểm / bối cảnh | Trong quá trình thảo luận, phân chia công việc, triển khai và hoàn thiện bài tập nhóm hoặc bài thuyết trình. |
| Quy trình hiện tại | 1. Nhận yêu cầu bài tập · 2. Nhóm trưởng phổ biến yêu cầu · 3. Các thành viên thảo luận · 4. Phân chia công việc · 5. Các thành viên thực hiện · 6. Tổng hợp kết quả · 7. Phát hiện điểm chưa thống nhất · 8. Trao đổi và chỉnh sửa lại. |
| Bottleneck | Bước 2–4 và 7–8: Truyền đạt yêu cầu, phản hồi ý kiến và thống nhất phương án. Một số thành viên không phản hồi hoặc hiểu yêu cầu khác nhau khiến nhóm phải trao đổi và chỉnh sửa nhiều lần. |
| Impact | Một bài tập có thể phải chỉnh sửa khoảng 3 lần. Có trường hợp mất cả buổi chiều nhưng chỉ giải quyết được một vấn đề do các thành viên im lặng hoặc không phản hồi trong quá trình trao đổi. |
| Success metric | Giảm số lần chỉnh sửa từ khoảng 3 lần xuống tối đa 1–2 lần; giảm thời gian thống nhất yêu cầu; các thành viên xác nhận rõ nhiệm vụ và thời hạn hoàn thành. |
| Phương án không dùng AI | Sử dụng Google Docs, Trello hoặc nhóm chat để ghi lại yêu cầu, phân công nhiệm vụ, đặt thời hạn và yêu cầu từng thành viên xác nhận trước khi triển khai. |
| Giả thuyết về AI | AI phân tích yêu cầu bài tập, tổng hợp ý kiến trao đổi, phát hiện những điểm chưa thống nhất, đề xuất phân công nhiệm vụ và nhắc nhở các thành viên phản hồi. |
| Cảm nhận nhanh | Workflow + Collaboration Agent |

**Workflow hiện tại — Quy trình làm việc nhóm**

```text
[1 Nhận yêu cầu bài tập]
          ↓
[2 Nhóm trưởng phổ biến yêu cầu]
          ↓
[3 Các thành viên thảo luận]
          ↓
[4 Phân chia công việc]
          ↓
[5 Thành viên thực hiện]
          ↓
[6 Tổng hợp kết quả]
          ↓
[7 Phát hiện điểm chưa thống nhất]
          ↓
[8 Trao đổi và chỉnh sửa] ← BOTTLENECK
          ↓
[9 Hoàn thiện bài tập]
```
** Card muốn pitch nhất

** AI đã phản biện card thế nào

## 4. Báo cáo đóng góp cá nhân (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Trình bày các vấn đề thực tế đã ghi nhận ở giai đoạn trước, gồm nhận diện lỗi sai trong học tập, tạo câu hỏi ôn tập từ tài liệu và khó khăn khi trao đổi, thống nhất khi làm bài tập nhóm. | Cung cấp các candidate problem để nhóm thảo luận, so sánh và xem xét mức độ phù hợp. |
| Phản biện bài của bạn khác | **Cần bổ sung bằng chứng thực tế:** ghi lại câu hỏi cụ thể đã đặt cho nhóm/bạn khác. Có thể tập trung vào bằng chứng về vấn đề, tần suất xảy ra, bottleneck hoặc lý do cần AI. | Chưa đủ thông tin để kết luận ảnh hưởng cụ thể của hoạt động phản biện. |
| Nhận phản biện | **Cần bổ sung:** ghi câu hỏi/góp ý thực tế đã nhận và thay đổi đã thực hiện sau góp ý. Không nên ghi đã sửa nếu chưa có thay đổi tương ứng. | Khi được bổ sung, phần này sẽ thể hiện khả năng tiếp nhận phản hồi và cải tiến bài toán. |
| Gom cluster / cây OST | Tổng hợp các vấn đề có điểm chung về nhu cầu, bối cảnh hoặc khó khăn của người học; sử dụng các nhóm vấn đề để hỗ trợ quá trình thu hẹp phạm vi. | Hỗ trợ nhìn thấy mối liên hệ giữa các vấn đề và tránh lựa chọn một ý tưởng chỉ vì cảm tính. **Cần đối chiếu với cây OST thực tế của nhóm.** |
| Chọn candidate problem | Tài liệu CP1–CP2 hiện ghi nhận ba candidate: nhận diện lỗi sai, tạo câu hỏi ôn tập và khó khăn phối hợp làm bài tập nhóm. | Tạo cơ sở so sánh các vấn đề. Tuy nhiên, cần xác nhận candidate cuối cùng của nhóm, đặc biệt vì nội dung CP6 hiện chuyển sang bài toán tổng hợp yêu cầu từ repo Markdown. |
| Kiểm chứng / research | Với hướng bài toán ở CP6, thực hiện desk review các tình huống phải kết hợp thông tin từ hai hoặc ba file để hình thành một mục checklist; xem xét việc phân biệt yêu cầu bắt buộc, ví dụ minh họa, ngoại lệ và khác biệt giữa các file. | Làm rõ rằng khó khăn không chỉ là tìm kiếm đoạn văn mà còn là đọc ngữ cảnh và ghép các tiêu chí. Đây là nhận định từ desk review, chưa phải kết quả thử nghiệm người dùng. |
| Quy trình nhóm | Mô tả quy trình xử lý repo Markdown: chọn file → tìm/trích mục → ghép tiêu chí → người kiểm → lập checklist. | Giúp xác định các bước tương đối cố định và vị trí có thể thử nghiệm AI hỗ trợ. |
| Problem Statement | Với hướng CP6, xác định đối tượng là sinh viên cần đọc nhiều file Markdown trong GitHub/VS Code và tổng hợp các yêu cầu thành checklist. | Giới hạn phạm vi ở việc đọc, tìm, trích và tổng hợp yêu cầu trong repo Markdown; không mở rộng thành một agent xử lý mọi loại tài liệu. **Cần xác nhận đây có phải Problem Statement đã được nhóm chốt hay chưa.** |
| Mức can thiệp AI (CP6) | Xây dựng ma trận độ mơ hồ × độ phức tạp; so sánh No AI, Rule, Workflow và Agent; đề xuất thử nghiệm Workflow có người duyệt. | Đưa ra phương án pilot có thể so sánh với baseline, đồng thời tránh khẳng định trước rằng AI chắc chắn hiệu quả hơn. |
| Quyết định | Đề xuất Workflow có người duyệt cho pilot: Rule tìm và trích các đoạn liên quan; AI tạo checklist nháp kèm nguồn; sinh viên kiểm tra và duyệt kết quả. | Có phương án thử nghiệm cụ thể. Quyết định cuối cùng cần dựa trên kết quả pilot và so sánh với No AI/Rule, không chỉ dựa trên nhận định ban đầu. |

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

**Ô đề xuất:** Độ mơ hồ **trung bình–cao**, độ phức tạp **trung bình**.

Người học cần phân biệt yêu cầu bắt buộc, ví dụ minh họa, ngoại lệ và sự khác nhau giữa các file; một câu có thể cần đọc ngữ cảnh mới hiểu đúng. Quy trình xử lý vẫn gồm các bước cố định: chọn file → tìm/trích mục → ghép tiêu chí → người kiểm → lập checklist.

Vì vậy, có thể thử Workflow có một bước AI; chưa có lý do để AI tự chọn công cụ hoặc tự lặp như Agent. Đây là đánh giá cấu trúc bài toán từ desk review CP4, chưa phải kết quả thử nghiệm với người dùng.

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | Sinh viên dùng mẫu checklist và tìm kiếm GitHub/VS Code để tự điền, gắn link nguồn. | File ít, yêu cầu rõ, người học lập checklist đủ nhanh và không bỏ sót. | Tự đọc/ghép các file; dễ quên điều kiện nằm ở file khác. | Baseline bắt buộc để so sánh. |
| **Rule** | Script liệt kê file, tiêu đề và các từ khóa như `phải`, `nộp`, `deadline`, `rubric`. | Cấu trúc tài liệu ổn định và mục bắt buộc có mẫu diễn đạt rõ. | Bỏ sót cách diễn đạt khác, dễ lấy cả ví dụ minh họa. | Thử cho bước thu thập, không tự kết luận. |
| **Workflow** | Rule lấy các đoạn liên quan → AI tạo checklist nháp kèm nguồn → sinh viên đối chiếu và duyệt. | Khi Rule tìm được nguồn nhưng chưa ghép/diễn giải được yêu cầu nằm ở nhiều file; đầu ra kiểm tra được. | AI có thể thiếu mục, sai nguồn, hiểu sai ngoại lệ; cần người duyệt. | **Đề xuất thử trong pilot**, chưa khẳng định hiệu quả. |
| **Agent** | AI tự duyệt repo, tự chọn file/công cụ, tự quyết bước tiếp theo và hoàn tất checklist. | Chỉ cần khi nguồn và nhánh xử lý thay đổi khó viết trước thành quy trình. | Quyền truy cập và hành động rộng hơn, khó truy vết, thêm chi phí. | Không chọn cho phạm vi repo Markdown hiện tại. |

### 6.3. Mức đề xuất cho pilot

**Mức đề xuất:** Workflow có người duyệt.

Quyết định cuối ở mục 8 cần xét kết quả kiểm chứng người dùng và bốn rủi ro; ở trạng thái hiện tại chưa thể công bố Workflow tốt hơn baseline.

**Vì sao cần thử vượt No AI/Rule:** Ba tình huống ở CP4 cho thấy thông tin cần ghép từ hai hoặc ba file để thành một mục checklist. Tìm kiếm và Rule giúp định vị đoạn văn, nhưng vẫn để người học phân biệt quy định, ví dụ và ngoại lệ.

Pilot phải so sánh trên cùng bộ file; nếu checklist thủ công/Rule đã đủ mục và nhanh tương đương, giữ mức đơn giản hơn. Không chọn Agent vì thứ tự các bước đã xác định được và người học phải duyệt kết quả.

