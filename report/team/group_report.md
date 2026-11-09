# Báo cáo nhóm — Day 02 Discovery \& Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: \[docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: \[docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1\. Thông tin nhóm

* Tên nhóm: Nhóm 12 (K5-L3B)
* Thành viên: xem `TEAM.md`
* Candidate problem được chọn (1 câu): Khi nhận bài lab/đồ án/task có yêu cầu và tiêu chí chấm rải rác ở nhiều file hoặc kênh, sinh viên muốn biết đủ đầu ra bắt buộc, tiêu chí và hạn nộp mà không phải đối chiếu thủ công.
* Quyết định cuối: Go / Not Yet / No-Go

\---

## 2\. Hội tụ nhóm (CP3)

### 2.1. Pitch

Mỗi thành viên pitch 3 card, tổng cộng 15 candidate. Cột cuối ghi câu hỏi phản biện gắn với card đó.

|#|Người đưa ra|Candidate (Job Story ngắn)|Actor|Bottleneck|Câu hỏi phản biện nhận được (ai hỏi)|
|-:|-|-|-|-|-|
|1|Phong|Khi bắt đầu tuần học, muốn có mọi deadline từ Moodle, Classroom, Gmail ở một nơi|Sinh viên học nhiều môn|Rà soát từng môn trên Moodle và lọc email, khoảng 30 phút trong tổng 55 phút/tuần|Cổng trường có OTP hoặc chặn crawl thì lấy dữ liệu đầu vào thế nào? iCal/Google Calendar đã giải được bao nhiêu phần, có cần AI không?<br>**Quốc hỏi:** Moodle hoặc Classroom đã có lịch và thông báo; bước nào các công cụ đó chưa giải được, và có lần nào việc đối chiếu thủ công khiến sinh viên bỏ sót deadline không?|
|2|Phong|Khi giảng viên đăng tài liệu 30–50 trang, muốn nắm ý chính và câu hỏi thảo luận để chuẩn bị bài|Sinh viên|Đọc chi tiết và tra thuật ngữ, khoảng 135 phút/tài liệu|Làm sao đo được bản tóm tắt đủ sâu để trả lời câu hỏi của giảng viên?|
|3|Phong|Khi làm đồ án nhóm, muốn biết ai làm phần nào và tiến độ ra sao|Nhóm trưởng và các thành viên|Nhắn giục, chờ phản hồi 1–2 ngày, 15–20 tin nhắn/sprint|Thành viên có chịu cập nhật trạng thái nếu dùng công cụ mới không?|
|4|Tú|Khi có bài tập hàng tuần, muốn biết dạng bài hay sai để không tự kiểm tra lại từ đầu|Sinh viên|Tự tìm nguyên nhân sai, khoảng 30 phút/ngày|30 phút đó có thật sự dành để tìm ra lỗi không?|
|5|Tú|Khi chuẩn bị thi, muốn có bộ câu hỏi ôn tập từ tài liệu để không tự soạn từng câu|Sinh viên|Chọn lọc tài liệu và soạn câu hỏi|Câu hỏi có bám đúng trọng tâm đề thi không?|
|6|Tú|Khi làm bài nhóm, muốn các thành viên hiểu thống nhất yêu cầu để không sửa đi sửa lại|Nhóm làm bài|Truyền đạt yêu cầu, chờ phản hồi và thống nhất phương án|Nguyên nhân nằm ở chuyên môn hay ở việc thành viên không phản hồi?<br>**Quốc hỏi:** Nếu mọi thành viên đã đọc cùng một checklist có nguồn, việc hiểu sai còn xảy ra ở đâu? Một Rule hoặc quy trình xác nhận chung có đủ trước khi chọn AI không?|
|7|Quốc|Khi chuẩn bị bữa ăn vài ngày tới, muốn đối chiếu đồ trong nhà, nhu cầu và giá để mua đủ, không bỏ phí|Người nấu ăn trong nhà|Lập danh sách mua, khoảng 25 phút/lần, 2 lần/tuần|Bước tốn thời gian thật là chọn món, kiểm nguyên liệu hay trao đổi với người cùng nhà?|
|8|Quốc|Khi đến kỳ thanh toán, muốn biết hóa đơn nào đến hạn, đúng số tiền, đã trả chưa|Người quản lý chi tiêu trong nhà|Đối chiếu 4–6 khoản/tháng ở nhiều ứng dụng|Có thật nhiều hóa đơn khó theo dõi, hay lịch nhắc đã đủ?|
|9|Quốc|Khi có nhiều việc ở nhiều nơi trong ngày, muốn sắp thứ tự đi theo giờ mở cửa và thời hạn|Người đi làm việc cá nhân|Lập lịch di chuyển cho 3 điểm đến/buổi|Tần suất có đủ cao để đáng giải không?|
|10|Quang Anh|Khi nhận bài lab GitHub, muốn xác định đủ yêu cầu từ nhiều file (README, checkpoint, rubric, submission)|Sinh viên làm lab|Đối chiếu yêu cầu giữa các file, khoảng 20 phút/lần|Nếu checklist chuẩn kèm link file gốc đã đủ, bước nào vẫn cần AI?<br>**Quốc hỏi:** Nếu sinh viên dùng tìm kiếm toàn repo và checklist mẫu, yêu cầu nào vẫn phải mở nhiều file để hiểu đúng? Có ví dụ từ một bài lab cụ thể không?|
|11|Quang Anh|Khi chuẩn bị train ResNet18 trên Colab, muốn dữ liệu và notebook đúng trước khi chạy|Sinh viên làm thí nghiệm|Kiểm tra đầu vào và sửa cấu hình, khoảng 30 phút/lần|Lỗi do đường dẫn, dữ liệu, dependency hay thao tác người dùng?|
|12|Quang Anh|Khi có PDF scan viết tay, muốn chuyển sang Word mà vẫn đúng nội dung|Sinh viên|Đối chiếu và sửa lỗi chữ viết tay, khoảng 30 phút/tài liệu|Metric phải có độ chính xác chứ không chỉ thời gian|
|13|Minh|Khi chuẩn bị nộp bài lớn, muốn biết nội dung đã đáp ứng đủ tiêu chí chưa để khỏi bị trừ điểm|Sinh viên nộp bài|Sửa phần thiếu hoặc chưa đạt tiêu chí, khoảng 20 phút/bài|Làm sao biết bước sửa thật sự là bước chậm nhất, không phải bước đọc tiêu chí?<br>**Quốc hỏi:** Trong lần nộp gần nhất, người học mất công nhất ở bước tìm tiêu chí, hiểu tiêu chí hay sửa sản phẩm sau khi đối chiếu? Bước nào được ghi nhận bằng thời gian hoặc số lần sửa?|
|14|Minh|Khi bài tập và task thực tập cùng hạn, muốn biết việc nào làm trước theo deadline, độ quan trọng, thời gian|Sinh viên đang thực tập|Đánh giá và so sánh mức ưu tiên, khoảng 12 phút/lần lập kế hoạch|12 phút/lần có đủ lớn để cần công cụ, hay một ma trận ưu tiên là xong?|
|15|Minh|Khi nhận task thực tập có yêu cầu rải rác ở Slack, email, tài liệu, họp, muốn hiểu rõ đầu ra, deadline, tiêu chí|Thực tập sinh|Đọc và đối chiếu nhiều nguồn, khoảng 10 phút/task|Pain nằm ở việc tìm thông tin hay ở việc yêu cầu vốn không rõ từ người giao?|

### 2.2. Cluster

|Cluster|Các candidate|Pattern chung|
|-|-|-|
|A. Yêu cầu và tiêu chí nằm rải rác nhiều nguồn|#6, #10, #13, #15|Người làm phải tự đọc và đối chiếu nhiều file hoặc kênh để biết đầu ra cần gì, chấm theo gì, hạn khi nào. Sót thì phải sửa lại hoặc bị trừ điểm|
|B. Gom và xếp ưu tiên deadline, lịch từ nhiều kênh|#1, #3, #7, #8, #9, #14|Thông tin lặp lại hằng tuần, nằm ở nhiều nơi, người dùng gom và sắp thứ tự bằng tay. Sót thì trễ hạn hoặc trả trễ|
|C. Biến học liệu dài thành ý chính, câu hỏi ôn tập|#2, #4, #5|Đọc nhiều, mất hàng giờ để rút ý chính, tạo câu hỏi và tìm chỗ chưa vững|
|D. Việc kỹ thuật đơn lẻ|#11, #12|Bài toán riêng của từng công cụ (Colab, chuyển PDF viết tay), ít người gặp, không cùng pattern với A–C|

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: Sinh viên hoàn thành bài lab, đồ án, task đúng yêu cầu và đúng hạn, với ít thời gian rà soát thủ công hơn
├── Opportunity A: Khó biết đầy đủ "cần nộp gì, chấm theo tiêu chí nào" vì yêu cầu nằm rải rác ở nhiều file, kênh; đối chiếu tốn thời gian và dễ sót
├── Opportunity B: Mất công gom deadline từ nhiều kênh và tự quyết định việc nào làm trước; dễ trễ hoặc bỏ sót
└── Opportunity C: Tốn nhiều giờ đọc học liệu dài để rút ý chính và biết mình đã hiểu đến đâu
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

* "Cần chatbot tóm tắt tài liệu" (#2, #5): là công cụ. Pain thật là đọc 100–150 trang tốn 3–4 giờ/tuần.
* "Cần bot nhắc tiến độ nhóm" (#3): là tính năng. Pain thật là phải nhắn giục và chờ 1–2 ngày.
* "Cần Notion/Trello hoặc dashboard deadline" (#1, #14): là công cụ. Pain thật là gom thủ công từ 3–4 nơi.
* "Cần công cụ OCR" (#12) và "cần notebook mẫu Colab" (#11): là công cụ, đồng thời nằm ngoài outcome chung nên không đưa vào cây.

### 2.4. Chấm điểm shortlist (1–5)

Shortlist gồm 3 candidate, mỗi cluster A, B, C một đại diện.

|Candidate|Actor rõ|Quy trình rõ|Pain có bằng chứng|Impact đo được|Vừa sức lab|So sánh được No AI/Rule/Workflow/Agent|Nhóm hiểu domain|Tổng|
|-|-:|-:|-:|-:|-:|-:|-:|-:|
|A. Đối chiếu yêu cầu, tiêu chí từ nhiều nguồn khi nhận bài (#10, #13, #15)|5|5|3|4|5|5|5|32|
|B. Gom deadline từ nhiều kênh vào một nơi (#1, #14)|5|5|4|4|3|4|4|29|
|C. Rút ý chính từ học liệu dài trước buổi học (#2, #5)|4|4|3|3|4|3|3|24|

Giải thích điểm:

* **A:** cả nhóm đang gặp đúng việc này ngay trong bài lab. Hai người (Quang Anh, Minh) tự vẽ quy trình và cùng chỉ ra bước đối chiếu là chỗ nghẽn. Dễ so sánh checklist cố định (Rule) với workflow đọc file. Bằng chứng mới là số phút tự ghi nhận (10–20 phút/lần), chưa có log, nên "pain có bằng chứng" chỉ 3 và là việc cần kiểm ở CP4.
* **B:** baseline rõ nhất (45–60 phút/tuần, từng sót một quiz chiếm 10% điểm) nhưng cổng trường có OTP, chặn API nên khó lấy dữ liệu trong khuôn khổ lab. iCal/Google Calendar đã giải phần lớn bằng Rule.
* **C:** pain lớn (3–4 giờ/tuần) nhưng khó đo chất lượng tóm tắt, và mỗi môn một nội dung nên nhóm khó tự kiểm độ đúng.

**Candidate được chọn:** Khi nhận bài lab, đồ án hoặc task có yêu cầu và tiêu chí chấm rải rác ở nhiều file hoặc kênh, sinh viên muốn biết đủ đầu ra bắt buộc, tiêu chí chấm và hạn nộp, để không phải đối chiếu thủ công và không bị sót hay trừ điểm.

**Vì sao chọn:** Actor và quy trình rõ nhất, cả 5 thành viên là người dùng thật nên hiểu domain tốt nhất. Bottleneck là một bước cụ thể (đối chiếu giữa các nguồn) và có hai quy trình nháp độc lập cùng trỏ vào. Có thể thử ngay trên repo lab này, và có đủ phương án để so sánh No AI, Rule, Workflow.

**Vì sao loại các candidate còn lại:**

* **B (gom deadline):** khâu lấy dữ liệu bị cổng trường chặn, ngoài tầm lab; iCal/Calendar có sẵn đã xử lý phần lớn nên gần như là bài No AI/Rule.
* **C (tóm tắt học liệu):** impact khó đo vì phải chấm chất lượng tóm tắt, cần chuyên môn từng môn để kiểm tra; điểm thấp nhất (24).
* **D (#11, #12):** không cùng pattern với cluster nào, chỉ một người gặp, nằm ngoài outcome chung.
* **#3, #6, #4, #7, #8, #9:** bằng chứng chủ yếu là số tự ước tính, hoặc bottleneck nằm ở hành vi con người (phản hồi chậm) hay tần suất thấp, nên quy trình nhóm hoặc Rule đã đủ.

**Xử lý bất đồng (nếu có):** Điểm cần cân nhắc là A và B. B có baseline rõ hơn nhưng bị chặn ở khâu lấy dữ liệu; A có baseline yếu hơn nhưng vừa sức lab và nhóm hiểu domain. Nhóm chọn A và chuyển việc kiểm baseline của A sang CP4.

\---

## 3\. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

**Quy ước:** *Quan trọng* 1 = ít ảnh hưởng, 5 = nếu sai thì problem/giải pháp khó đứng vững; *đã có bằng chứng* 1 = chưa có chứng cứ trực tiếp, 5 = đã có dữ liệu phù hợp và kiểm tra được. Đây là **điểm đánh giá mức chắc chắn của giả định**, không phải kết quả survey. Mức ưu tiên tăng khi quan trọng cao nhưng bằng chứng thấp.

|#|Giả định cần kiểm chứng|Loại|Quan trọng (1–5)|Đã có bằng chứng (1–5)|Kiểm chứng trước?|
|-:|-|-|-:|-:|-|
|1|Sinh viên **ngoài Nhóm 12** từng phải đối chiếu từ hai nguồn yêu cầu trở lên trong một bài lab/task gần đây và có công sức đáng kể cho việc này.|Value|5|1|**Ưu tiên 1**: hỏi sự kiện gần nhất|
|2|Bước tốn công nhất là **tìm/đối chiếu yêu cầu giữa các nguồn**, không phải hiểu chuyên môn, làm bài hay sửa sản phẩm.|Value|5|2|**Ưu tiên 2**: yêu cầu kể từng bước, đối chiếu thời lượng|
|3|Người dùng có thể kiểm tra checklist có **đường dẫn về đúng tài liệu và đúng tiêu chí gốc** mà không phải đọc lại toàn bộ hồ sơ.|Usability|4|1|**Ưu tiên 3**: kiểm tra với một bộ yêu cầu thật|
|4|Với **repository có quyền truy cập**, có thể truy xuất tối thiểu README, hướng dẫn checkpoint, rubric và hướng dẫn nộp để đối chiếu.|Feasibility|5|4|Đã thấy với repo này; thử trên repo khác|
|5|Một bản tổng hợp dựa trên **từ khóa hoặc AI** không được làm sót yêu cầu rải rác, và luôn phải chỉ ra nguồn khi có kết luận.|Feasibility|5|2|Kiểm trên các trường hợp yêu cầu nằm ở 2–4 file|
|6|Việc thu thập tài liệu và dùng công cụ hỗ trợ tuân thủ quyền truy cập, bảo mật; không cần lấy tài liệu riêng tư hoặc tài khoản học tập của người khác.|Viability|4|2|Kiểm với loại nguồn mà người dùng thực tế sử dụng|

**Lý do chọn ưu tiên:** Giả định #1 và #2 quyết định **vấn đề có phổ biến, thực sự gây đau hay không**; giả định #3 và #5 quyết định **kết quả tổng hợp có đáng tin và kiểm tra được hay không**. Giả định #4 đã có tín hiệu về khả năng truy cập từ chính ZIP bài lab, nhưng việc mở được một repository không chứng minh mọi bài học hay nguồn bên ngoài đều truy cập được.

**Giả định trọng tâm đưa vào kiểm chứng người dùng:** #1 và #2; nếu thời gian cho khâu đối chiếu không đáng kể hoặc người học đã có workaround đủ tốt, cần cân nhắc thu hẹp vấn đề hoặc chọn giải pháp No AI/Rule.

### 3.2. Kiểm chứng

#### 3.2.1. Kiểm chứng tài liệu (desk review — đã thực hiện)

Nhóm có thể trực tiếp quan sát **cấu trúc yêu cầu** trong ZIP repository được cung cấp. Đây là kiểm tra **sự phân tán thông tin**, **không phải bằng chứng người ngoài nhóm gặp pain**.

|Nguồn trong repository|Thông tin có thể đối chiếu|Điều quan sát được|Giới hạn kết luận|
|-|-|-|-|
|[`README.md`](../../README.md)|Bối cảnh, thứ tự đọc, cấu trúc repo, hướng dẫn bắt đầu|Có file dẫn nhập riêng cho người làm lab|Chưa đo được sinh viên mất bao lâu để đọc|
|[`CHECKPOINTS.md`](../../CHECKPOINTS.md)|CP0–CP7, yêu cầu công việc và tự kiểm tra từng checkpoint|Chi tiết việc phải làm được tách sang file checkpoint|Không cho biết tỷ lệ người học làm thiếu|
|[`RUBRIC.md`](../../RUBRIC.md)|Tiêu chí chấm, điểm, lỗi bị trừ và điều kiện chấm|Quy tắc đánh giá nằm ở tài liệu riêng|Không chứng minh bản rubric là khó hiểu|
|[`SUBMISSION.md`](../../SUBMISSION.md)|Cấu trúc file, nơi nộp, deadline, checklist nộp bài|Quy định nộp xuất hiện trong tài liệu riêng|Không chứng minh ai đã nộp sai hoặc trễ|

**Kết quả quan sát hợp lệ:** Với chính bài lab này, để kiểm tra đầy đủ *cần làm gì — chấm như thế nào — nộp ở đâu*, người học cần tham chiếu nội dung từ **nhiều file có vai trò khác nhau**. Đây là ví dụ đầu vào đủ rõ cho việc thử đối chiếu hoặc lập checklist. **Không kết luận** rằng đã xảy ra bỏ sót, mất một số phút xác định, hay đa số sinh viên đều gặp vấn đề.

**Ba tình huống đối chiếu cụ thể từ bộ tài liệu Day 02:**

|Tình huống|Các nguồn cần đối chiếu|Kết quả người học cần rút ra|
|-|-|-|
|Xác định việc cá nhân và nơi nộp|[`README.md`](../../README.md) nêu CP1, CP2, CP7 làm cá nhân; [`SUBMISSION.md`](../../SUBMISSION.md) quy định báo cáo cá nhân nằm trong repo nhóm và mỗi người nộp cùng link repo trên LMS|Không tạo repo riêng; mỗi người có file cá nhân đúng tên và tự nộp link repo nhóm|
|Phân biệt dùng AI ở từng checkpoint|[`RULES.md`](../../RULES.md) nêu AI được dùng để phản biện CP5–CP6 nhưng không viết reflection thay; [`RUBRIC.md`](../../RUBRIC.md) nêu điều kiện chấm C4|Nhật ký AI phải ghi đúng phần đã dùng; reflection CP7 do cá nhân tự viết|
|Kiểm tra đủ sản phẩm nhóm và trách nhiệm|[`CHECKPOINTS.md`](../../CHECKPOINTS.md) liệt kê sản phẩm CP3–CP6; [`SUBMISSION.md`](../../SUBMISSION.md) yêu cầu `group\_report.md` và `TEAM.md`; [`RUBRIC.md`](../../RUBRIC.md) quy định điểm phần nhóm phụ thuộc hai file này và đóng góp thật|Checklist cần có cả báo cáo nhóm, TEAM, nội dung theo checkpoint và phần việc của từng thành viên|



**Tín hiệu trong báo cáo nhóm CP3 (chỉ là dữ liệu nội bộ):** các candidate #10, #13, #15 liên quan đến đối chiếu yêu cầu/tiêu chí giữa các nguồn. Điều này hỗ trợ lý do **nhóm chọn hướng nghiên cứu**, nhưng không được tính là phỏng vấn độc lập: quy định CP4 không sử dụng thành viên cùng nhóm để thay cho người dùng bên ngoài.

#### 3.2.2. Phỏng vấn người dùng / khảo sát (chưa thực hiện)

**Trạng thái thực tế của tài liệu đầu vào:** ZIP chưa chứa bản ghi phỏng vấn, kết quả poll/survey hoặc log thời gian từ người dùng ngoài nhóm. Do đó:

* **Phỏng vấn đã thực hiện có thể kiểm chứng:** 0 người.
* **Phiếu khảo sát có phản hồi được cung cấp:** 0 người.
* **Tín hiệu xác nhận pain từ người dùng ngoài nhóm:** chưa có.
* **Tín hiệu phản bác từ người dùng ngoài nhóm:** chưa có.

**Cách thu thập phù hợp rubric:** Chọn **2–3 sinh viên ngoài nhóm** đã làm lab có nhiều tài liệu, phỏng vấn ngắn về **lần gần nhất đã diễn ra**; hoặc làm micro survey **5–10 sinh viên** có trải nghiệm tương tự. Không phỏng vấn thành viên Nhóm 12 để đủ mẫu. Chỉ ghi vai trò và thời điểm, không công khai họ tên, email hay số điện thoại.

**Bộ câu hỏi hành vi cho người phỏng vấn (theo The Mom Test):**

1. Trong bài lab/task gần nhất, bạn nhận hướng dẫn từ những nguồn hoặc file nào?
2. Hãy kể từ lúc mở đề đến lúc bạn có danh sách việc phải nộp: bạn đã làm những bước nào?
3. Lần đó có bước nào bạn phải mở lại tài liệu hoặc đối chiếu hai nguồn không? Hãy kể một ví dụ cụ thể.
4. Bạn ước lượng đã mất bao nhiêu phút cho **riêng việc tìm và đối chiếu yêu cầu**? Có ghi chép hay thời điểm nào giúp kiểm lại không?
5. Bạn đã dùng checklist, Ctrl+F, tìm kiếm trong editor hoặc nhờ người khác giải thích chưa? Cách đó xử lý được gì, còn vướng gì?
6. Trong bài gần nhất, bạn có bỏ sót hoặc hiểu sai một yêu cầu nào không? Nếu có, hậu quả cụ thể là gì; nếu không, điều gì giúp bạn tránh được?

Các câu hỏi này tránh giả định rằng ai cũng có pain, không hỏi kiểu “Bạn có muốn một chatbot không?”.



|Trường|Nội dung cần ghi từ người thật|
|-|-|
|Nguồn/mã ẩn danh, vai trò và thời điểm|Sinh viên ngoài Nhóm 12; hình thức và ngày phỏng vấn thực tế|
|Câu nói đáng nhớ (nguyên văn)|Chỉ chép sau khi đã nghe người đó nói|
|Lần gần nhất gặp vấn đề|Bài lab/task cụ thể và chuyện đã xảy ra|
|Quy trình/workaround hiện tại|Người đó đã làm gì để xử lý|
|Thời gian/tần suất|Số do người được hỏi cung cấp hoặc log có căn cứ; ghi rõ nguồn|
|Insight và tín hiệu phản bác (nếu có)|Kết luận rút ra trực tiếp từ lời kể/hành vi|

**Nếu dùng survey thay phỏng vấn**, phiếu nên thu thập: (1) lần làm lab gần nhất, (2) số nguồn hướng dẫn, (3) có phải đối chiếu không, (4) bước tốn thời gian nhất, (5) khoảng phút dùng để đọc/đối chiếu, (6) cách hiện đang xử lý, (7) có bỏ sót yêu cầu không. Không lấy câu trả lời giả định “sẽ dùng công cụ nếu có”.

*phỏng vấn phân tích (dữ liệu mô phỏng, không tính là mẫu CP4):*\*

|Mã và vai trò giả định|Lần làm bài được mô phỏng|Câu trả lời giả định|Workaround / thời gian giả định|Tín hiệu rút ra nếu gặp ngoài thực tế|
|-|-|-|-|-|
|S1 — sinh viên nhận lab qua repo GitHub|Bài có README, rubric và hướng dẫn nộp ở các file khác nhau|“Mình ghi xong danh sách việc cần làm rồi vẫn phải mở rubric để xem phần nào có điểm và mở hướng dẫn nộp để kiểm tên file.”|Ghi checklist bằng tay; khoảng 18 phút, mở lại hai file khi kiểm|Ủng hộ giả thuyết đối chiếu nhiều nguồn gây thêm công; cần hỏi tiếp có mục nào từng bị sót và thời gian lấy từ đâu|
|S2 — sinh viên quen dùng VS Code Search|Bài có bốn file Markdown hướng dẫn|“Mình tìm `deadline`, `submission`, `rubric` rồi ghi vào checklist; lần đó không thiếu mục nào.”|Tìm kiếm toàn thư mục và dùng checklist cá nhân; khoảng 7 phút|**Phản bác** giả thuyết công cụ hiện có chưa đủ; có thể No AI/Rule đã giải được với người dùng thành thạo|
|S3 — sinh viên hiểu sai tiêu chí dù tìm đúng file|Bài có một tiêu chí chấm diễn đạt ngắn trong rubric|“Mình thấy đúng đoạn rubric, nhưng không biết ví dụ trong README có bắt buộc làm theo không nên phải hỏi bạn cùng lớp.”|Đọc lại ngữ cảnh và hỏi người khác; khoảng 15 phút, chưa rõ riêng bước đối chiếu mất bao lâu|Pain có thể nằm ở **diễn giải yêu cầu**, không phải tìm file; cần tách hai bước khi phỏng vấn thật|

**Bảng tổng hợp bằng chứng tại thời điểm soạn CP4:**

|Nguồn|Số người / số mẫu|Tín hiệu xác nhận|Tín hiệu phản bác hoặc giới hạn|
|-|-:|-|-|
|Kiểm tra cấu trúc tài liệu lab trong ZIP|4 file tài liệu chính|Yêu cầu làm bài, chấm điểm, nộp bài nằm ở các file có chức năng khác nhau|Chỉ cho thấy **nhiều nguồn thông tin**; không xác nhận pain, thời gian hay tỷ lệ bỏ sót|
|Báo cáo CP3 của nhóm|3 candidate cùng hướng (#10, #13, #15)|Nhóm có ví dụ pain để nghiên cứu sâu|Không độc lập; **không được tính** thay phỏng vấn/survey|
|Người dùng ngoài nhóm|0|Chưa có bằng chứng xác nhận|Chưa có bằng chứng phản bác; cần thu thập thật|
|Nghiên cứu công cụ hiện có (mục 3.3)|3 tài liệu chính thức|Đã có công cụ tìm kiếm/làm việc với ngữ cảnh repository|Có thể vấn đề được giải quyết **một phần mà không cần xây công cụ mới**|

**Tín hiệu phản bác hiện có từ research (không phải phỏng vấn):** VS Code và GitHub đã hỗ trợ tìm kiếm tài liệu; GitHub Copilot hỗ trợ trả lời theo ngữ cảnh. Vì vậy, giả định “chưa có cách nào hỗ trợ đối chiếu” **không đúng**. Điều cần kiểm tiếp là các công cụ sẵn có đã đủ cho người dùng mục tiêu hay chưa.

#### 3.2.3. Nhóm đã sửa problem thế nào sau bước rà soát hiện có?

|Phiên bản|Cách phát biểu|Cơ sở thay đổi|
|-|-|-|
|CP3 — phạm vi rộng|Sinh viên/ thực tập sinh nhận bài lab, đồ án hoặc task từ nhiều file, email, Slack... và muốn biết đủ yêu cầu, tiêu chí, hạn nộp.|Hợp nhất nhiều candidate có pattern tương tự trong CP3.|
|CP4 — **phạm vi thử nghiệm đề xuất**|Sinh viên **đang làm bài lab có repository GitHub nhiều file hướng dẫn** cần lập checklist đầy đủ yêu cầu và tiêu chí, với **đường dẫn về đúng nguồn**, trước khi thực hiện/nộp bài.|Repo này có đủ nhiều loại tài liệu có thể đối chiếu; không cần truy cập dữ liệu lớp học, email hay Slack riêng tư. Các công cụ tìm kiếm hiện có là baseline No AI/Rule để so sánh.|

**Nhận định hiện tại:** Việc thu hẹp trên là **kết quả desk review và đánh giá khả thi**, chưa phải quyết định được xác nhận bởi phỏng vấn người dùng. Do chưa có phản hồi người ngoài nhóm, chưa được khẳng định người dùng thực sự cần sản phẩm mới. Nhóm chỉ nên chốt thay đổi cuối cùng sau khi phỏng vấn/survey thật, có ít nhất một tín hiệu phản bác được ghi nhận (nếu xuất hiện).

### 3.3. Research giải pháp đã có

Nghiên cứu ba hướng hỗ trợ **có thật**, so sánh với thao tác thủ công (No AI) để tránh mặc định phải xây Agent. Các nhận định tính năng dựa trên tài liệu chính thức, **không phải kết quả thử nghiệm hiệu suất trên người dùng của nhóm**.

|Công cụ / case / pattern|Link nguồn chính thức|Giải bước nào trong quy trình?|Điểm mạnh đã được mô tả|Khoảng trống / rủi ro trong bài toán của nhóm|Bài học cho nhóm|
|-|-|-|-|-|-|
|**GitHub Code Search**|[GitHub Docs — Code Search syntax](https://docs.github.com/en/search-github/github-code-search/understanding-github-code-search-syntax)|Tìm nhanh file/đoạn có từ khóa như `submission`, `rubric`, `deadline` hoặc lọc trong một repo bằng `repo:`|Có toán tử, tìm cụm chính xác và qualifier `repo:` / `path:`; không cần viết công cụ mới|Từ khóa có thể không trùng cách diễn đạt; người dùng vẫn cần đọc ngữ cảnh và tự tổng hợp các mục liên quan|Đặt làm baseline **No AI/Rule**; tiêu chí thành công không thể chỉ là “tìm được từ khóa”|
|**Visual Studio Code — Search across files**|[VS Code — Basic editing, Search across files](https://code.visualstudio.com/docs/editing/codebasics#_search-across-files)|Tìm thông tin đồng thời trong các file Markdown sau khi mở thư mục repo|Tìm kiếm toàn workspace, hiện kết quả theo file/vị trí; có thể lọc phạm vi tìm kiếm|Yêu cầu mở/clone thư mục; vẫn là tìm chuỗi, chưa tự suy ra mục bắt buộc, phân biệt ngoại lệ và ngữ cảnh|Một checklist có liên kết file/đoạn nguồn chỉ có giá trị nếu cải thiện được việc rà soát thủ công bằng VS Code|
|**GitHub Copilot Chat (repo/file context)**|[GitHub Docs — Copilot Chat responsible use](https://docs.github.com/en/copilot/responsible-use/chat)|Hỗ trợ hỏi-đáp, diễn giải và tóm tắt nội dung file/repository theo ngữ cảnh được cấp|Có thể dùng nội dung file hoặc repo làm ngữ cảnh để tạo phản hồi tự nhiên|Mô hình có thể trả lời sai hoặc thiếu; ngữ cảnh có giới hạn, không bảo đảm mọi file đều được xem; cần kiểm tra đầu ra với nguồn gốc|Nếu thử Workflow có AI, đầu ra chỉ là **bản nháp có dẫn nguồn**; con người kiểm từng yêu cầu và không để AI tự quyết định “đã đủ để nộp”|

**So sánh mức giải quyết vấn đề (đánh giá định tính):**

|Tiêu chí|GitHub Search|VS Code Search|Copilot Chat|
|-|-|-|-|
|Tìm cụm/từ khóa trong file|Có|Có|Có thể hỗ trợ qua ngữ cảnh và truy xuất phù hợp|
|Tự tạo checklist diễn giải bằng ngôn ngữ tự nhiên|Không phải chức năng trọng tâm|Không phải chức năng tìm kiếm cơ bản|Có thể hỗ trợ tạo bản nháp, cần kiểm chứng|
|Bảo đảm không bỏ sót mọi yêu cầu|Không thể khẳng định|Không thể khẳng định|Không thể khẳng định|
|Cần con người kiểm đối chiếu nguồn|Có|Có|**Bắt buộc**, vì có rủi ro trả lời thiếu/sai|
|Phù hợp làm baseline không dùng AI|**Có**|**Có**|Không|

**Khoảng trống cần kiểm bằng thử nghiệm:** Vấn đề không phải là “không có công cụ tìm kiếm”, mà là liệu người học có thể tạo **một checklist đủ mục bắt buộc, đúng nguồn và rà soát nhanh hơn** khi yêu cầu trải rộng trên nhiều file. Giải pháp phải được đánh giá với cùng một bộ tài liệu, so sánh số mục bỏ sót, số mục gán sai nguồn và thời gian thực hiện; không được công bố cải thiện khi chưa đo.

**Kết luận CP4 ở trạng thái hiện có:** Assumption Map và nghiên cứu giải pháp đã có đã được hoàn thành ở mức **phân tích tài liệu**. Điều kiện về **phỏng vấn thật 2–3 người hoặc survey 5–10 người chưa đạt**, vì ZIP chưa có dữ liệu. Do vậy, phần xác nhận Value và kết luận nhóm đã điều chỉnh problem **sau kiểm chứng người dùng** chưa thể hoàn tất một cách trung thực. Dữ liệu này cần được nhóm thu thập trực tiếp trước khi chốt CP4 chính thức và chuyển sang lập metric baseline ở CP5.

\---



## 4\. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

**Phạm vi:** Một sinh viên nhận repository lab có `README.md`, `CHECKPOINTS.md`, `RUBRIC.md`, `SUBMISSION.md`; đầu ra là checklist cá nhân trước khi bắt đầu làm bài. Các phút dưới đây là **ước lượng để vẽ quy trình**. Không tính thời gian thực hiện bài lab.

```text
\[1 Mở repo, xác định các file hướng dẫn: 2']
→ \[2 Đọc README và checkpoint: 3']
→ \[3 Tìm đầu ra bắt buộc, deadline trong submission: 4']
→ \[4 Đối chiếu từng đầu ra với rubric/rules: 6'] ← BOTTLENECK GIẢ ĐỊNH
→ \[5 Ghi checklist kèm file nguồn: 3']
→ \[6 Rà lại trước khi làm bài: 2']
Tổng: khoảng 20 phút/lần (ước lượng, chưa đo).
```

|Bước|Actor|Input|Output|Thời gian / tần suất|Ghi chú|
|-:|-|-|-|-|-|
|1|Sinh viên|Link repo lab|Danh sách file cần đọc|\~2 phút/lần nhận bài|Các file nằm trong cùng repo nhưng có chức năng khác nhau|
|2|Sinh viên|`README.md`, `CHECKPOINTS.md`|Danh sách checkpoint và thứ tự làm|\~3 phút/lần|Handoff: đưa các mục cần làm sang bước đối chiếu|
|3|Sinh viên|`SUBMISSION.md`|Danh sách file nộp, nơi nộp, hạn nộp|\~4 phút/lần|Cần phân biệt sản phẩm cá nhân và nhóm|
|4|Sinh viên|Danh sách bước 2–3, `RUBRIC.md`, `RULES.md`|Yêu cầu bắt buộc ghép với tiêu chí và giới hạn dùng AI|\~6 phút/lần|Nhiều nguồn, cách diễn đạt khác nhau; bottleneck giả định|
|5|Sinh viên|Các yêu cầu đã đối chiếu|Checklist có tên file/đường dẫn nguồn|\~3 phút/lần|Handoff: checklist dùng trong lúc làm bài|
|6|Sinh viên|Checklist và file gốc|Danh sách đã rà lại|\~2 phút/lần|Người làm bài chịu trách nhiệm xác nhận|

**Bottleneck chính (giả thuyết cần kiểm ở CP4):** Bước 4, đối chiếu một yêu cầu với tiêu chí ở file khác và phân biệt mục bắt buộc với ví dụ/hướng dẫn. Ước lượng \~6 phút; hậu quả đáng chú ý hơn số phút là **bỏ sót hoặc gán sai yêu cầu**. Desk review CP4 xác nhận thông tin nằm ở nhiều file, chưa xác nhận bước 4 thật sự tốn nhất với người ngoài nhóm.

### 4.2. Quy trình tương lai

Đây là **kịch bản thử nghiệm**, chưa chốt mức can thiệp ở CP6. Chỉ dùng các tài liệu mà sinh viên có quyền truy cập. Checklist sinh ra phải gắn nguồn để người dùng kiểm lại.

```text
\[1 Người dùng chọn repo/bộ file được phép đọc: \~1']        ← CON NGƯỜI
→ \[2 Liệt kê file, tìm mục tiêu đề/keyword: \~1']           ← RULE/script
→ \[3 Trích yêu cầu thành checklist nháp có nguồn: \~3']     ← AI hỗ trợ
→ \[4 Đối chiếu từng mục với file gốc, sửa/bổ sung: \~5']   ← CON NGƯỜI; điểm kiểm soát
→ \[5 Lưu checklist đã duyệt và tự thực hiện bài: \~2']     ← CON NGƯỜI
Tổng phần lập checklist: khoảng 12 phút/lần (kỳ vọng để thử, chưa đo).

BOUNDARY: AI không tự đánh dấu bài đã đạt rubric, không tự nộp bài,
không suy ra deadline/điểm khi tài liệu không nói rõ, không đọc nguồn ngoài quyền truy cập.
PHƯƠNG ÁN QUAY VỀ: thiếu nguồn, trích xuất sai hoặc công cụ ngừng hoạt động
→ bỏ checklist nháp; dùng tìm kiếm GitHub/VS Code và checklist thủ công, đối chiếu file gốc.
```

**Handoff và kiểm tra:** Rule chuyển danh sách file cho bước trích xuất; AI trả checklist nháp gồm nội dung, loại yêu cầu và đường dẫn file/đoạn nguồn; sinh viên mở nguồn, xác nhận từng mục rồi mới sử dụng. Nếu hai file mâu thuẫn, người dùng đánh dấu “cần hỏi coach”, không để AI tự chọn quy định.

### 4.3. Before / after

|Chỉ số|Trước|Sau (kỳ vọng)|Ghi chú|
|-|-:|-:|-|
|Số bước|6|5|Chỉ tính bước lập checklist|
|Tổng thời gian|\~20 phút/lần|\~12 phút/lần|Cả hai là giả định thử nghiệm; cần đo trên cùng bộ tài liệu|
|Số bước thủ công|6/6|3/5|Bước chọn nguồn, duyệt, lưu vẫn do người làm|
|Bottleneck chính|Đối chiếu yêu cầu với rubric/rules|Kiểm nguồn và sửa checklist nháp|Giữ bước kiểm vì bỏ sót yêu cầu có thể gây trừ điểm|
|Rủi ro mới phát sinh|Bỏ sót khi đọc thủ công|AI bỏ sót, hiểu sai ngoại lệ hoặc dẫn sai nguồn|Người dùng đối chiếu file gốc; quay về quy trình thủ công khi nháp không đáng tin|

\---

## 5\. Problem Statement v0 (CP5)

|Trường|Nội dung|
|-|-|
|**Actor**|Sinh viên nhận bài lab có nhiều file hướng dẫn trong một repository GitHub|
|**Quy trình**|Mở repo → đọc hướng dẫn/checkpoint → tìm yêu cầu nộp → đối chiếu rubric/rules → lập checklist có nguồn → rà lại trước khi làm bài|
|**Bottleneck**|Đối chiếu một yêu cầu giữa nhiều file và xác định mục nào thật sự bắt buộc; bước 4 được giả định là nghẽn, cần kiểm bằng hành vi người dùng ngoài nhóm|
|**Impact**|Tốn công rà soát; có nguy cơ lập checklist thiếu mục, hiểu sai tiêu chí hoặc nộp thiếu file. Repo mẫu chỉ chứng minh thông tin phân tán, chưa chứng minh tần suất lỗi|
|**Success Metric** (baseline → target, cách đo)|**Baseline tạm tính:** \~20 phút/lần lập checklist trên bộ tài liệu mẫu, chưa đo; số mục bỏ sót/gán sai nguồn chưa có baseline. **Target pilot đề xuất:** ≤12 phút và không bỏ sót mục bắt buộc, mỗi mục có đúng nguồn. **Cách đo:** cùng bộ file, người tham gia ngoài nhóm lập checklist bằng cách hiện tại và cách thử; ghi thời gian từ lúc mở repo đến lúc checklist được duyệt; đối chiếu với danh mục chuẩn do nhóm rà từ file gốc, đếm mục thiếu/sai nguồn. Chỉ chốt target sau CP4 và thử pilot|
|**Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL)|Người dùng chỉ cấp file có quyền truy cập. Mọi checklist nháp cần dẫn về file gốc; sinh viên kiểm từng mục trước khi dùng. AI không tự nộp, không xác nhận bài đạt rubric và không tự quyết khi tài liệu mâu thuẫn|

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

* **AI phản biện bản nháp CP5:** “Giảm thời gian mà bỏ sót yêu cầu thì không giải được problem; baseline 20 phút cũng chưa được đo.” **Hướng chỉnh trong bản nháp:** bổ sung số mục bắt buộc bị bỏ sót/gán sai nguồn và cách lập danh mục chuẩn, đồng thời gắn nhãn các phút là giả định. Nhóm cần tự xem và xác nhận lập luận trước khi chốt.
* **Cần nhóm xác nhận sau CP4:** Nếu người ngoài nhóm nói tìm kiếm có sẵn đã đủ hoặc bottleneck nằm ở hiểu chuyên môn thay vì đối chiếu file, sửa lại actor/bottleneck và cân nhắc No AI/Rule ở CP6.

\---

## 6\. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

**Ô đề xuất:** Độ mơ hồ **trung bình–cao**, độ phức tạp **trung bình**. Người học cần phân biệt yêu cầu bắt buộc, ví dụ minh họa, ngoại lệ và sự khác nhau giữa các file; một câu có thể cần đọc ngữ cảnh mới hiểu đúng. Quy trình xử lý vẫn gồm các bước cố định: chọn file → tìm/trích mục → ghép tiêu chí → người kiểm → lập checklist. Vì vậy có thể thử Workflow có một bước AI; chưa có lý do để AI tự chọn công cụ hoặc tự lặp như Agent. Đây là đánh giá cấu trúc bài toán từ desk review CP4, chưa phải kết quả thử nghiệm với người dùng.

### 6.2. So sánh 4 mức

|Mức|Phương án cho bài của nhóm|Đủ khi nào|Rủi ro|Chọn?|
|-|-|-|-|-|
|**No AI** (sửa quy trình)|Sinh viên dùng mẫu checklist và tìm kiếm GitHub/VS Code để tự điền, gắn link nguồn|File ít, yêu cầu rõ, người học lập checklist đủ nhanh và không bỏ sót|Tự đọc/ghép các file; dễ quên điều kiện nằm ở file khác|Baseline bắt buộc để so sánh|
|**Rule**|Script liệt kê file, tiêu đề và các từ khóa như `phải`, `nộp`, `deadline`, `rubric`|Cấu trúc tài liệu ổn định và mục bắt buộc có mẫu diễn đạt rõ|Bỏ sót cách diễn đạt khác, dễ lấy cả ví dụ minh họa|Thử cho bước thu thập, không tự kết luận|
|**Workflow**|Rule lấy các đoạn liên quan → AI tạo checklist nháp kèm nguồn → sinh viên đối chiếu và duyệt|Khi Rule tìm được nguồn nhưng chưa ghép/diễn giải được yêu cầu nằm ở nhiều file; đầu ra kiểm tra được|AI có thể thiếu mục, sai nguồn, hiểu sai ngoại lệ; cần người duyệt|**Đề xuất thử trong pilot**, chưa khẳng định hiệu quả|
|**Agent**|AI tự duyệt repo, tự chọn file/công cụ, tự quyết bước tiếp theo và hoàn tất checklist|Chỉ cần khi nguồn và nhánh xử lý thay đổi khó viết trước thành quy trình|Quyền truy cập và hành động rộng hơn, khó truy vết, thêm chi phí|Không chọn cho phạm vi repo Markdown hiện tại|

**Mức đề xuất cho pilot:** Workflow có người duyệt. Quyết định cuối ở mục 8 phải xét kết quả kiểm chứng người dùng và bốn rủi ro; ở trạng thái hiện tại chưa thể công bố Workflow tốt hơn baseline.

**Vì sao cần thử vượt No AI/Rule:** Ba tình huống ở CP4 cho thấy thông tin cần ghép từ hai hoặc ba file để thành một mục checklist. Tìm kiếm và Rule giúp định vị đoạn văn, nhưng vẫn để người học phân biệt quy định, ví dụ và ngoại lệ. Pilot phải so sánh trên cùng bộ file; nếu checklist thủ công/Rule đã đủ mục và nhanh tương đương, giữ mức đơn giản hơn. Không chọn Agent vì thứ tự các bước đã xác định được và người học phải duyệt kết quả.

### 6.3. AI Canvas rút gọn

|Thành phần|Nội dung|
|-|-|
|**Prediction** — AI dự đoán / tạo ra gì?|Checklist nháp gồm yêu cầu, loại mục (bắt buộc/khuyến nghị/điều kiện), đối tượng áp dụng và đường dẫn file/đoạn nguồn|
|**Judgment** — con người cân nhắc, quyết định gì?|Sinh viên kiểm từng mục với file gốc, giải quyết trùng lặp và đánh dấu chỗ mâu thuẫn để hỏi coach|
|**Action** — hành động cuối cùng là gì, ai làm?|Sinh viên sửa, lưu checklist đã duyệt và tự làm/nộp bài; AI không nộp thay|
|**Outcome** — đo kết quả bằng gì?|Thời gian lập checklist; số yêu cầu bắt buộc bị bỏ sót, số mục sai nguồn/sai điều kiện so với danh mục chuẩn|
|**Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không?|Nội dung các file hướng dẫn trong repo được cấp quyền, phiên bản/commit đang xét và đường dẫn từng đoạn; bộ file Day 02 hiện có trong repo, các repo khác cần kiểm quyền và khả năng đọc|
|**Feedback** — lấy phản hồi ở đâu để cải thiện?|Những mục sinh viên sửa/xóa/thêm khi duyệt và lỗi đối chiếu với danh mục chuẩn; không dùng dữ liệu riêng tư khi chưa được phép|

### 6.4. Hai câu hỏi của Google PAIR

* **Augment hay automate?** Đề xuất augment: AI soạn nháp, sinh viên duyệt trước khi dùng. Desk review cho thấy có thể kiểm nguồn từng mục, nhưng CP4 chưa có phỏng vấn nên **chưa có bằng chứng về mức tự chủ người dùng mong muốn**. Cần hỏi người dùng ngoài nhóm và kiểm hành vi khi họ duyệt checklist.
* **Báo nhầm hay bỏ sót?** Bỏ sót một yêu cầu bắt buộc có thể dẫn đến thiếu đầu ra hoặc bị trừ điểm, nên nguy hiểm hơn báo thêm một mục để người học rà lại. Thiết kế ưu tiên độ bao phủ, dẫn nguồn từng mục và buộc người dùng kiểm với file gốc. Báo nhầm vẫn phải đo vì làm tăng thời gian rà soát.

\---

## 7\. Problem Statement v1 + tiêu chí đánh giá (CP6)

|Trường|Nội dung|
|-|-|
|**Actor**|Sinh viên nhận bài lab có repository GitHub và nhiều file hướng dẫn; phạm vi pilot chỉ gồm file mà sinh viên được quyền đọc|
|**Quy trình**|Hiện tại sinh viên mở repo → đọc hướng dẫn/checkpoint → tìm yêu cầu nộp → đối chiếu rubric/rules → lập checklist có nguồn → rà lại trước khi làm bài|
|**Bottleneck**|Ghép yêu cầu nằm ở nhiều file, phân biệt bắt buộc với ví dụ/ngoại lệ; hiện là giả thuyết từ desk review, chưa xác nhận bằng phỏng vấn|
|**Impact**|Có nguy cơ mất công rà soát, thiếu mục nộp hoặc hiểu sai tiêu chí; mức độ và tần suất thực tế chưa đo|
|**Success Metric** (baseline → target, cách đo)|Baseline thời gian **tạm ước lượng** \~20 phút/lần; baseline lỗi chưa có. Target pilot đề xuất ≤12 phút, 0 mục bắt buộc bị bỏ sót và 0 nguồn/điều kiện sai sau khi người dùng duyệt. Đo trên cùng bộ file và cùng danh mục chuẩn: ghi thời gian, đếm mục thiếu/sai cho cách thủ công/Rule và Workflow; chỉ kết luận khi có dữ liệu thật|
|**Boundary**|AI chỉ đọc file được cấp quyền và tạo nháp có dẫn nguồn; không tự xác nhận đạt rubric, không tự nộp, không tự chọn quy định khi file mâu thuẫn. Sinh viên duyệt từng mục; thiếu nguồn thì quay về tìm kiếm và checklist thủ công|
|**AI intervention point**|Sau bước Rule tìm đoạn liên quan, trước bước sinh viên kiểm: AI ghép và diễn giải thành checklist nháp|
|**Mức chọn**|Workflow **đề xuất để thử**, chưa chốt triển khai rộng|
|**Rủi ro \& người kiểm tra**|Bỏ sót yêu cầu, gán nhầm nguồn hoặc hiểu sai ngoại lệ; sinh viên đối chiếu file gốc, coach làm rõ trường hợp tài liệu mâu thuẫn|

**Thay đổi so với v0 và lý do:**

|Trường|v0|v1|Vì sao đổi|
|-|-|-|-|
|Phạm vi actor|Sinh viên nhận bài lab có nhiều file hướng dẫn|Giới hạn pilot vào repo GitHub và file có quyền đọc|CP4 desk review mới xác nhận được cấu trúc repo này; không suy rộng sang email/Slack|
|AI intervention point|v0 chưa chọn cách can thiệp|Rule định vị đoạn, AI ghép yêu cầu thành checklist nháp, sinh viên duyệt|Chỉ rõ bước thử nghiệm mà không lẫn giải pháp vào mô tả quy trình hiện tại|
|Success Metric|Ước lượng thời gian và dự kiến đếm lỗi|Nêu target pilot về thời gian và 0 lỗi thiếu/sai nguồn sau duyệt|Rút từ phản biện v0: nhanh hơn nhưng sai nhiều hơn thì không đạt|
|Boundary|Người dùng kiểm nguồn, AI không tự nộp|Bổ sung cách xử lý nguồn thiếu/mâu thuẫn và quay về thủ công|Giảm nguy cơ checklist trông đầy đủ nhưng không kiểm được|

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

|#|Tiêu chí|Đạt khi|Không đạt khi|
|-:|-|-|-|
|1|Bao phủ yêu cầu bắt buộc|Bản nháp nêu mọi mục trong danh mục chuẩn của bộ file thử nghiệm|Thiếu dù chỉ một mục bắt buộc|
|2|Đúng nguồn và điều kiện|Mỗi mục có link đúng file/đoạn, ghi đúng đối tượng áp dụng và điều kiện/ngoại lệ|Dẫn sai nguồn, bỏ điều kiện hoặc biến ví dụ thành quy định|
|3|Không tự thêm quy định|Mọi deadline, tên file, tiêu chí và điểm đều truy được về nội dung đầu vào|Có một thông tin tự suy ra nhưng trình bày như quy định|
|4|Xử lý chỗ chưa rõ|Bản nháp đánh dấu yêu cầu thiếu nguồn, mâu thuẫn hoặc có nhiều cách hiểu để người dùng kiểm|Tự chốt một cách hiểu khi các file chưa thống nhất|
|5|Đầu ra dùng được|Mỗi dòng checklist có việc cần làm, nguồn và đối tượng áp dụng; mục trùng được gộp nhưng vẫn giữ đủ nguồn|Dòng quá chung chung, thiếu nguồn hoặc gộp làm mất điều kiện|

\---

## 8\. Quyết định (CP6)

### 8.1. Bốn rủi ro

|Rủi ro|Câu hỏi|Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm)|Lý do / bằng chứng|
|-|-|-|-|
|**Value**|Người dùng có thật sự cần và sẽ dùng không?|Cao|Chưa có phỏng vấn hoặc survey có phản hồi từ đủ số người dùng. Desk review chỉ xác nhận yêu cầu của bài lab nằm ở nhiều file; chưa chứng minh tần suất gặp pain, thời gian thực tế hoặc mức sẵn sàng sử dụng. Vì vậy giá trị với người dùng bên ngoài nhóm vẫn là giả định cần kiểm chứng.|
|**Usability**|Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không?|Trung bình	|Checklist có cấu trúc và đường dẫn về file/đoạn nguồn nên có thể kiểm tra, nhưng nhóm chưa thử với đủ nhiều người dùng. Người học vẫn phải hiểu các mục, xác nhận điều kiện và xử lý trường hợp tài liệu mâu thuẫn; chưa có dữ liệu về mức dễ dùng hoặc công sức chỉnh bản nháp.|
|**Feasibility**|Có đủ dữ liệu, công cụ, kỹ năng để làm không?|Trung bình	|Phạm vi pilot giới hạn ở các file Markdown trong repository GitHub mà người dùng được quyền đọc; nhóm đã xác định được các nguồn như README, CHECKPOINTS, RUBRIC, SUBMISSION và RULES, đồng thời research GitHub Search, VS Code Search và Copilot Chat. Tuy nhiên, nhóm chưa triển khai và đo độ bao phủ/độ chính xác của việc trích yêu cầu trên nhiều repository; AI vẫn có thể bỏ sót, hiểu sai ngoại lệ hoặc dẫn sai nguồn.|
|**Viability**|Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành?|Trung bình	|Pilot nhỏ có thể dùng bộ tài liệu được cấp quyền, không cần truy cập tài khoản học tập, email hay dữ liệu riêng tư của người khác. Tuy nhiên, nhóm chưa đánh giá chi phí sử dụng AI, giới hạn dữ liệu/ngữ cảnh, công sức duy trì và quy định khi áp dụng ở quy mô rộng. Trong pilot, sinh viên là người chọn nguồn, kiểm tra kết quả và quyết định sử dụng checklist.|

### 8.2. Kết luận

**Quyết định:** Quyết định: Go (phạm vi pilot nhỏ).



* Lý do:

\- Candidate A đạt 32/35 điểm trong bảng shortlist CP3; actor, quy trình và phạm vi thử nghiệm trên repository GitHub tương đối rõ. Nhóm có thể sử dụng chính bộ tài liệu lab để dựng danh mục yêu cầu chuẩn và kiểm tra từng kết quả.

\- Desk review đã xác nhận các thông tin cần làm bài, tiêu chí chấm và hướng dẫn nộp được phân bố ở nhiều file. Research cũng cho thấy GitHub Search và VS Code Search đã hỗ trợ tìm kiếm, nên pilot phải so sánh với No AI/Rule thay vì mặc định AI tốt hơn.

\- Workflow là mức can thiệp đề xuất để thử, không phải kết luận đã hiệu quả. Rủi ro Value vẫn cao vì chưa có dữ liệu phỏng vấn/survey ngoài nhóm; do đó quyết định Go chỉ cho phép pilot có kiểm soát, không phải triển khai rộng hoặc khẳng định đã xác nhận nhu cầu.


**Nếu Go — pilot nhỏ nhất:**

1. Phạm vi: dùng một repository lab cố định, chỉ gồm các file Markdown người tham gia được phép đọc (ví dụ README, CHECKPOINTS, RUBRIC, SUBMISSION và RULES). Không kết nối LMS, email, Slack hoặc tài khoản cá nhân.
2. Người tham gia: mời 2–3 sinh viên ngoài Nhóm 12 đã từng làm bài lab có nhiều file hướng dẫn, phù hợp với kế hoạch phỏng vấn người dùng ở CP4. Trước khi thử, hỏi ngắn về lần làm lab gần nhất để ghi nhận cách họ đang tìm và đối chiếu yêu cầu; không coi thành viên nhóm là mẫu xác nhận độc lập.
3. Ba cách làm để so sánh trên cùng bộ tài liệu: (a) No AI — đọc file và tự lập checklist; (b) Rule — tìm kiếm GitHub/VS Code theo từ khóa và dùng checklist mẫu; (c) Workflow — Rule định vị đoạn liên quan, AI tạo checklist nháp có dẫn nguồn, sinh viên kiểm tra và duyệt.
4. Danh mục chuẩn: nhóm đối chiếu trực tiếp file gốc để lập danh sách các yêu cầu bắt buộc, điều kiện/ngoại lệ và nguồn tương ứng. Dùng danh mục này làm chuẩn chấm cả ba cách làm.
5. Chỉ số ghi nhận: thời gian từ lúc mở repo đến khi checklist được duyệt; số yêu cầu bắt buộc bị bỏ sót; số mục gán sai nguồn/điều kiện; số chỉnh sửa người dùng phải thực hiện. Ghi riêng lỗi của bản nháp AI và lỗi còn lại sau khi người dùng duyệt.
6. Ngưỡng mục tiêu ban đầu: Workflow hướng tới thời gian không quá 12 phút/lần (so với baseline tạm ước lượng khoảng 20 phút/lần) và 0 yêu cầu bắt buộc bị bỏ sót, 0 nguồn/điều kiện sai trong checklist cuối đã duyệt. Đây là target pilot, không phải kết quả đã đạt; cần báo cáo kết quả thực đo và đối chiếu với No AI/Rule.
7. Kiểm soát: người dùng kiểm từng mục với file gốc; AI không tự xác nhận bài đạt rubric, không tự nộp bài và không tự quyết khi tài liệu mâu thuẫn. Nếu thiếu nguồn hoặc trích xuất không đáng tin, quay về tìm kiếm và checklist thủ công




**Nếu Not Yet — cần kiểm chứng gì trước:**

* Nếu chưa tuyển được người tham gia ngoài nhóm hoặc chưa có danh mục chuẩn đáng tin, tạm hoãn đánh giá hiệu quả Workflow. Trước hết thực hiện 2–3 phỏng vấn ngắn hoặc survey 5–10 sinh viên ngoài nhóm theo câu hỏi CP4, tập trung vào bài lab gần nhất, các nguồn đã dùng, bước đối chiếu, thời gian và workaround hiện tại. Chỉ tiếp tục pilot sau khi có dữ liệu đủ để xác định pain có tồn tại ngoài nhóm.

**Nếu No-Go — nên làm gì thay AI:**

* Dùng checklist cố định kèm đường dẫn đến file nguồn, kết hợp GitHub Code Search hoặc VS Code Search để tìm các từ khóa như submission, rubric, deadline và checkpoint. Người học tự đối chiếu các đoạn liên quan và xác nhận checklist. Đây là phương án đơn giản hơn, phù hợp nếu No AI/Rule đạt độ bao phủ và thời gian tương đương Workflow.

**Ngưỡng dừng** (nếu sau … mà … thì quay về …):

* Sau một vòng pilot trên cùng repository, dừng thử Workflow và quay về No AI/Rule nếu checklist cuối vẫn bỏ sót yêu cầu bắt buộc hoặc còn dẫn sai nguồn/điều kiện sau khi người dùng kiểm tra; hoặc nếu thời gian hoàn thành không đạt mục tiêu 12 phút và không tốt hơn cách Rule. Dừng ngay việc dùng AI cho trường hợp có tài liệu mâu thuẫn mà không xác định được nguồn quyết định. Không mở rộng sang repository khác trước khi xử lý được các lỗi này và hoàn tất kiểm chứng người dùng.

\---

## 9\. Hạn chế và hướng tiếp theo

* Hạn chế hiện tại:
- Thiếu xác nhận từ người dùng ngoài nhóm: tại thời điểm lập báo cáo, nhóm chưa có phỏng vấn hoặc survey có phản hồi từ sinh viên ngoài Nhóm 12. Các candidate nội bộ và cấu trúc repository chỉ giúp hình thành giả thuyết, chưa chứng minh pain phổ biến.
- Baseline chưa được đo thực nghiệm: mốc khoảng 20 phút/lần và mục tiêu 12 phút/lần là ước lượng/kỳ vọng để thiết kế pilot. Nhóm chưa có log thời gian so sánh No AI, Rule và Workflow; số mục bỏ sót hoặc sai nguồn cũng chưa có baseline thực tế.
- Phạm vi dữ liệu hẹp: desk review tập trung vào repository lab với các file hướng dẫn dạng Markdown. Chưa thể suy rộng kết quả sang LMS, email, Slack, PDF scan, repository có cấu trúc khác hoặc tài liệu người dùng không có quyền truy cập.
- Research mới ở mức tài liệu: nhóm đã đọc tài liệu chính thức về GitHub Search, VS Code Search và Copilot Chat nhưng chưa benchmark trực tiếp các công cụ trên cùng bộ tài liệu và chưa kiểm tra với người dùng. Vì vậy chưa có căn cứ nói Workflow tốt hơn tìm kiếm hoặc checklist.
- Rủi ro chất lượng và vận hành: AI có thể bỏ sót yêu cầu, biến ví dụ thành quy định, bỏ điều kiện/ngoại lệ hoặc dẫn sai nguồn. Chi phí, giới hạn ngữ cảnh, khả năng duy trì và quy định triển khai rộng chưa được đánh giá.

* Hướng tiếp theo:
1. Thu thập bằng chứng từ 2–3 sinh viên ngoài nhóm qua phỏng vấn hoặc 5–10 sinh viên qua survey; ghi nhận một bài lab gần nhất, quy trình thực tế, thời gian, workaround và cả tín hiệu phản bác.
2. Xây dựng danh mục chuẩn từ file gốc của một repository cố định, ghi rõ yêu cầu bắt buộc, điều kiện/ngoại lệ và nguồn để làm tiêu chí đối chiếu.
3. Chạy pilot so sánh No AI, Rule và Workflow trên cùng bộ tài liệu; đo thời gian đến checklist được duyệt, yêu cầu bị bỏ sót, nguồn/điều kiện sai và công sức chỉnh sửa.
4. Phân loại lỗi AI và cập nhật checklist/quy tắc tìm kiếm. Nếu Rule đã đạt kết quả tương đương thì ưu tiên Rule; chỉ giữ Workflow khi có cải thiện đo được mà không làm giảm độ chính xác.
5. Chỉ cân nhắc mở rộng sang repository hoặc định dạng khác sau khi pilot nhỏ đạt ngưỡng, người dùng ngoài nhóm xác nhận được giá trị và các giới hạn quyền truy cập/bảo mật được kiểm tra.

## 10\. Tài liệu tham khảo

* 

