# Báo cáo cá nhân — 2A202604113_PhamTranQuoc

## 1. Thông tin học viên

- Họ tên: Phạm Trấn Quốc
- MSSV: 2A202604113
- Tên nhóm: Nhóm 12
- Link repo nhóm: https://github.com/WorkOfMinh/K5-L3B-DAY02-Nhom12-DiscoveryProblemFraming

## 2. Scan problem (CP1)

Tôi chọn các tình huống có nhiều bước, nhiều nguồn thông tin hoặc ràng buộc thay đổi. Chúng **có thể** là bài toán cho AI hỗ trợ hoặc Agent, nhưng CP1 chỉ mô tả vấn đề. Sau khi đo và hỏi người thật, nhóm mới quyết định No AI, Rule, Workflow hay Agent.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu quan sát được / giả định ban đầu |
|---:|---|---|---|---|
| 1 | Lặp lại, cần tổng hợp thông tin | Khi chuẩn bị bữa ăn cho vài ngày tới, tôi muốn đối chiếu đồ còn trong nhà, nhu cầu ăn uống và giá thực phẩm, để mua đủ đồ mà không bỏ phí đồ ăn. | Người nấu ăn, người cùng nhà | Có thể quan sát số món cần bổ sung, món mua trùng/bị bỏ phí và các bước kiểm đồ, hỏi nhu cầu, chọn món. **Giả định để hình dung:** khoảng 25 phút/lần, 2 lần/tuần; chưa đo. |
| 2 | Tốn thời gian, nhiều nguồn | Khi đến kỳ thanh toán các khoản sinh hoạt, tôi muốn biết hóa đơn nào đã đến hạn, số tiền đúng và đã thanh toán chưa, để không trả trễ hoặc trả hai lần. | Người quản lý chi tiêu trong nhà | Có thể kiểm tra số khoản và nguồn thông báo, số lần phải mở lại lịch sử thanh toán hoặc hỏi lại. **Giả định để hình dung:** 4–6 khoản/tháng, khoảng 20 phút/kỳ; chưa xác nhận. |
| 3 | Cần tổng hợp nhiều thông tin | Khi phải làm nhiều việc ở các địa điểm khác nhau trong một ngày, tôi muốn sắp thứ tự di chuyển theo giờ mở cửa, thời gian đi và thời hạn từng việc, để không phải đi vòng hoặc lỡ giờ. | Người đi làm việc cá nhân, người đi cùng | Có thể ghi số điểm đến, số lần đổi thứ tự/lộ trình và việc bị lỡ khung giờ. **Tình huống giả định:** khoảng 3 điểm đến; lập lịch khoảng 30 phút, tùy ràng buộc. |
| 4 | Pain từ người khác | Khi thiết bị trong nhà bị hỏng, người cùng nhà muốn biết ai có thể sửa, chi phí dự kiến và khi nào có người ở nhà, để không phải hỏi nhiều nơi rồi chốt lại từ đầu. | Người sống cùng nhà, người phụ trách sửa chữa | Có thể quan sát số nơi cần liên hệ, số lần hỏi lại giá/lịch và số lần phải hẹn lại. **Giả định để hình dung:** so sánh 2–3 nơi; chưa có dữ liệu thực tế. |
| 5 | Tốn thời gian, nhiều nguồn | Khi tổ chức một chuyến đi ngắn cho gia đình hoặc bạn bè, tôi muốn đối chiếu lịch rảnh, ngân sách, đường đi và giờ hoạt động của địa điểm, để chốt kế hoạch phù hợp cho mọi người. | Người tổ chức và người tham gia | Có thể ghi số người/nguồn thông tin, số lần thay đổi lịch trình và việc phải bỏ khỏi kế hoạch. **Tình huống giả định:** 3–4 người, khoảng 30–45 phút chuẩn bị; chưa đo. |

**AI đã gợi ý gì, tôi giữ/bỏ gì:** AI gợi ý cả các việc đơn giản như nhắc mang đồ và chọn món ăn. Tôi bỏ việc nhắc mang đồ vì checklist có thể đủ, không thấy nhu cầu cho một hệ thống tự quyết nhiều bước. Tôi giữ 5 ý trên làm **candidate để kiểm chứng**, chưa khẳng định chúng là pain thật của mình. Với mỗi ý, tôi sẽ thay số ước tính bằng số đo hoặc một sự kiện cụ thể.

Năm vấn đề này không cùng một kiểu khó khăn. Lập bữa ăn và theo dõi hóa đơn là việc lặp lại; sắp nhiều điểm đến và chuyến đi ngắn cần ghép lịch, địa điểm, ngân sách; sửa đồ trong nhà còn có bước phối hợp với người khác. Tôi không xếp hạng bằng số phút ước lượng, vì một việc chỉ mất ít phút vẫn có thể gây hậu quả lớn nếu bỏ sót hạn thanh toán hoặc lỡ giờ hẹn. Khi chọn tiếp, tôi nhìn vào người chịu ảnh hưởng, bước nghẽn có thể chỉ ra được, hậu quả và khả năng kiểm chứng trong phạm vi bài lab.

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

**Shortlist dự kiến:** #1 lập bữa ăn và mua sắm, #2 theo dõi hóa đơn, #3 sắp lịch nhiều điểm đến. Ba candidate có actor, đầu vào, kết quả và quy trình đủ rõ để mang ra pitch. Phút ở các quy trình là ước lượng minh họa nhằm làm rõ bước nào có thể là bottleneck; không phải số đo, cam kết hiệu quả hay ngưỡng chấm. Các mốc này có thể thay đổi hoặc bỏ nếu CP4 cho thấy giả định không đúng.

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Lập bữa ăn và danh sách mua sắm (#1) | Lặp lại, nhiều ràng buộc; có thể đo thời gian và lượng đồ bỏ phí | Việc khó nhất là chọn món hay kiểm đồ còn trong nhà? |
| 2 | Theo dõi hóa đơn sinh hoạt (#2) | Hậu quả thanh toán trễ rõ; có thể bắt đầu từ lịch nhắc và Rule | Có thật nhiều hóa đơn khó theo dõi, hay lịch nhắc đã đủ? |
| 3 | Sắp thứ tự nhiều điểm đến (#3) | Giờ mở cửa, thời gian di chuyển và việc phát sinh có thể thay đổi | Tần suất xảy ra có đủ cao để đáng giải không? |

Tôi chưa đưa việc sửa thiết bị (#4) vào top 3 vì nó có thể xảy ra không thường xuyên và cần thêm thông tin từ người thật về số lần phải hỏi lại hoặc hẹn lại. Chuyến đi ngắn (#5) có nhiều ràng buộc nhưng việc chốt lịch còn phụ thuộc sở thích và sự đồng thuận của cả nhóm, nên khó quy một bước làm nghẽn cho mọi trường hợp. Ba card được chọn cũng chưa chứng minh cần AI: mỗi card đều có cách xử lý bằng checklist, lịch nhắc, bản đồ hoặc Rule để so sánh trước.

### Problem Card #1 — Lập bữa ăn và mua sắm

| Trường | Nội dung |
|---|---|
| Job Story | Khi chuẩn bị bữa ăn cho vài ngày tới, tôi muốn đối chiếu đồ còn trong nhà, nhu cầu ăn uống và giá thực phẩm, để mua đủ đồ mà không bỏ phí đồ ăn. |
| Actor | Người nấu ăn và mua thực phẩm cho gia đình |
| Bối cảnh | Trước một lần đi chợ hoặc đặt thực phẩm cho 2–3 ngày |
| Quy trình hiện tại | Kiểm đồ còn → hỏi người cùng nhà muốn ăn gì → chọn món → xem nguyên liệu/giá → lập danh sách → mua |
| Bottleneck | Ghép món với nguyên liệu còn, khẩu vị và ngân sách; **ước lượng khoảng 10 phút** |
| Impact | Mua thiếu, mua trùng hoặc để hỏng nguyên liệu |
| Success metric | Mốc tham khảo: khoảng 25 phút/lần (ước lượng, chưa đo). Khi kiểm chứng, có thể theo dõi thời gian hoàn tất và số món mua thiếu/trùng/bị bỏ phí; target sẽ được nhóm chốt dựa trên baseline có căn cứ |
| Phương án không dùng AI | Danh sách nguyên liệu cố định, thực đơn luân phiên và checklist trước khi mua |
| Giả thuyết về AI | Augment: gợi ý vài thực đơn dựa trên đồ còn; người dùng duyệt món và danh sách. Agent chỉ đáng cân nhắc nếu phải tự điều chỉnh nhiều bước theo giá, tồn kho và thay đổi của người dùng |
| Cảm nhận nhanh | Workflow trước; chưa đủ bằng chứng chọn Agent |

```text
[Kiểm đồ còn: 4'] → [Hỏi nhu cầu: 3'] → [Chọn món: 10'] ← nghẽn dự kiến
→ [Xem giá/nguyên liệu: 5'] → [Lập danh sách: 3']
Tổng baseline ước lượng: 25 phút/lần.
```

### Problem Card #2 — Theo dõi hóa đơn

| Trường | Nội dung |
|---|---|
| Job Story | Khi đến kỳ thanh toán các khoản sinh hoạt, tôi muốn biết hóa đơn nào đã đến hạn, số tiền đúng và đã thanh toán chưa, để không trả trễ hoặc trả hai lần. |
| Actor | Người quản lý chi tiêu trong nhà |
| Bối cảnh | Đầu hoặc cuối tháng, khi nhiều thông báo thanh toán đến từ ứng dụng khác nhau |
| Quy trình hiện tại | Mở từng ứng dụng/tin nhắn → ghi hạn và số tiền → đối chiếu lịch sử → sắp thứ tự hạn → thanh toán → lưu bằng chứng |
| Bottleneck | Đối chiếu thông báo với khoản đã trả; **ước lượng khoảng 8 phút/kỳ** |
| Impact | Có thể trả trễ hoặc nhầm khoản |
| Success metric | Mốc tham khảo: khoảng 20 phút/kỳ (ước lượng, chưa đo). Có thể theo dõi thời gian đối chiếu và số khoản bỏ sót/thanh toán trùng; target cần được nhóm chốt sau khi biết baseline thực tế |
| Phương án không dùng AI | Lịch nhắc cố định, bảng theo dõi và Rule đánh dấu khoản đến hạn |
| Giả thuyết về AI | Augment việc đọc thông báo không đồng nhất, nhưng con người xác nhận số tiền. Automate nhắc hạn có thể dùng Rule; **không tự thanh toán** |
| Cảm nhận nhanh | Rule có thể đủ; chưa thấy lý do dùng Agent |

```text
[Mở nguồn: 4'] → [Ghi khoản: 3'] → [Đối chiếu đã trả: 8'] ← nghẽn dự kiến
→ [Sắp hạn: 2'] → [Thanh toán/lưu chứng từ: 3']
Tổng baseline ước lượng: 20 phút/kỳ.
```

### Problem Card #3 — Sắp việc ở nhiều địa điểm

| Trường | Nội dung |
|---|---|
| Job Story | Khi phải làm nhiều việc ở các địa điểm khác nhau trong một ngày, tôi muốn sắp thứ tự di chuyển theo giờ mở cửa, thời gian đi và thời hạn từng việc, để không phải đi vòng hoặc lỡ giờ. |
| Actor | Người có nhiều việc cá nhân cần hoàn thành trong một buổi |
| Bối cảnh | Trước khi ra ngoài và khi có địa điểm đóng cửa hoặc lịch đổi bất ngờ |
| Quy trình hiện tại | Liệt kê việc → kiểm giờ mở cửa → tra đường → ước tính thời gian ở mỗi nơi → xếp thứ tự → điều chỉnh khi có thay đổi |
| Bottleneck | Xếp thứ tự khi giờ mở cửa và di chuyển ràng buộc nhau; **ước lượng khoảng 12 phút** |
| Impact | Đi vòng, phải quay lại hoặc bỏ lỡ một việc |
| Success metric | **Giả định:** 30 phút lập lịch → mục tiêu dưới 15 phút; đo số lần phải quay lại và thời gian di chuyển thực tế |
| Phương án không dùng AI | Bản đồ có nhiều điểm dừng, lịch giờ mở cửa và bảng ưu tiên thủ công |
| Giả thuyết về AI | Augment bằng cách đề xuất lộ trình và giải thích ràng buộc; chỉ automate cập nhật lịch khi người dùng xác nhận. Agent có thể hữu ích nếu phải tự lập lại kế hoạch theo sự kiện mới, nhưng không tự đặt chỗ hay chi tiền |
| Cảm nhận nhanh | Workflow; cân nhắc Agent sau kiểm chứng |

```text
[Liệt kê việc: 3'] → [Kiểm giờ: 5'] → [Tra đường: 5']
→ [Xếp thứ tự: 12'] ← nghẽn dự kiến → [Rà lại lịch: 5']
Tổng baseline ước tính: 30 phút/lần.
```

### Card muốn pitch nhất

- Card số: 1, tôi xác nhận mình hoặc người cùng nhà thực sự gặp việc này thường xuyên.
- Vì sao: Quy trình lặp lại và có nhiều ràng buộc; vẫn có phương án không dùng AI để so sánh.
- Câu hỏi muốn nhóm phản biện: “Bước tốn thời gian thật là chọn món, kiểm nguyên liệu, hay trao đổi với người cùng nhà?”

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Tôi đã chỉnh trong bản này |
|---|---|---|
| Các mốc thời gian chưa phải dữ liệu đo nên chưa thể kết luận bottleneck | Đồng ý | Gắn nhãn toàn bộ số phút là ước lượng; mô tả bottleneck như giả thuyết, không dùng mốc phút làm tiêu chuẩn đánh giá. Nếu candidate được chọn, nhóm sẽ hỏi về lần gần nhất và xác định metric phù hợp ở CP4–CP5 |
| Lập thực đơn có thể xử lý bằng checklist hoặc mẫu cố định | Đồng ý | Bổ sung phương án không dùng AI trước khi cân nhắc AI; chưa kết luận cần Agent |
| Chưa biết người dùng muốn hệ thống tự quyết món/lịch hay chỉ đề xuất | Đồng ý | Giữ quyền quyết định ở người dùng trong giả thuyết ban đầu; ghi rõ mức can thiệp cần được kiểm chứng thay vì xem đây là yêu cầu đã xác nhận |

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

Sau khi so sánh các candidate ở CP3, nhóm chọn bài toán **đối chiếu yêu cầu và tiêu chí từ nhiều file trong repository lab**. Ba card đời sống tôi đưa vào bảng pitch giúp nhóm nhìn thêm các kiểu pain liên quan đến việc tổng hợp thông tin, nhưng candidate về bài lab có phạm vi rõ hơn và có bộ tài liệu chung để phân tích. Theo phân công trong `TEAM.md`, tôi phụ trách CP5: chuyển problem đã chọn thành quy trình có từng bước, xác định chỗ cần đối chiếu và viết Problem Statement v0. Tôi tập trung giữ cho metric, boundary và phương án quay về nhất quán với quy trình trước/sau của nhóm.

| Hoạt động | Điều tôi phải ghi sau khi thực hiện | Bằng chứng |
|---|---|---|
| Pitch và phản biện | Đưa ba card đời sống vào bảng pitch và đặt bốn câu hỏi dưới đây để kiểm tra bottleneck, bằng chứng và mức can thiệp của các candidate khác | Báo cáo nhóm mục 2.1; báo cáo cá nhân mục 3 và mục 4 |
| Chọn candidate | Nhóm chọn bài toán đối chiếu yêu cầu lab, không chọn ba card của tôi; lý do chọn/loại nằm trong OST và bảng chấm điểm | Báo cáo nhóm mục 2.3–2.4 |
| Kiểm chứng | Đối chiếu cấu trúc các file hướng dẫn của bài Day 02 và phân biệt dữ kiện từ tài liệu với giả định về trải nghiệm của sinh viên | Báo cáo nhóm mục 3.2 |
| Quy trình, Problem Statement | Tôi phụ trách CP5: dựng quy trình hiện tại và đề xuất, chỉ ra bước nghẽn, lập bảng before/after và viết Problem Statement v0. Tôi giữ số phút ở mức ước lượng và yêu cầu người học kiểm nguồn trước khi dùng checklist | Báo cáo nhóm mục 4–5; `TEAM.md` |
| Quyết định | CP6 do thành viên khác phụ trách chính; tôi sẽ phản biện khi nhóm có dữ liệu CP4 và bản CP6 | Báo cáo nhóm mục 6–8 khi hoàn tất |

**Bốn câu hỏi tôi đã đặt khi phản biện các card của nhóm:**

1. **Với card đối chiếu yêu cầu bài lab của Quang Anh:** Nếu sinh viên dùng tìm kiếm toàn repo và checklist mẫu, yêu cầu nào vẫn phải mở nhiều file để hiểu đúng? Có ví dụ từ một bài lab cụ thể không?
2. **Với card gom deadline của Phong:** Moodle hoặc Classroom đã có lịch và thông báo; bước nào các công cụ đó chưa giải được, và có lần nào việc đối chiếu thủ công khiến sinh viên bỏ sót deadline không?
3. **Với card kiểm tra bài nộp của Minh:** Trong lần nộp gần nhất, người học mất công nhất ở bước tìm tiêu chí, hiểu tiêu chí hay sửa sản phẩm sau khi đối chiếu? Bước nào được ghi nhận bằng thời gian hoặc số lần sửa?
4. **Với card thống nhất yêu cầu khi làm nhóm của Anh Tú:** Nếu mọi thành viên đã đọc cùng một checklist có nguồn, việc hiểu sai còn xảy ra ở đâu? Một Rule hoặc quy trình xác nhận chung có đủ trước khi chọn AI không?

Các câu hỏi này gắn với bốn card trong bảng pitch CP3. Câu hỏi nhóm đặt cho card lập bữa ăn của tôi và thay đổi sau đó đã được ghi ở mục 3 và mục 6.3; nội dung phản hồi cụ thể cho bốn câu hỏi trên chưa được ghi lại trong báo cáo.

### Phần tôi tập trung khi làm CP5

| Quyết định trong bản CP5 | Vì sao cần làm rõ | Thể hiện ở báo cáo nhóm |
|---|---|---|
| Giới hạn actor là sinh viên nhận bài lab qua repo GitHub | Phạm vi CP3 còn rộng, gồm cả đồ án và task từ email/Slack; repo Day 02 là bộ tài liệu nhóm có thể đối chiếu ngay | Mục 4.1 và trường Actor ở mục 5 |
| Tách bước tìm file khỏi bước đối chiếu yêu cầu | Tìm đúng đoạn văn chưa có nghĩa đã biết mục đó bắt buộc, áp dụng cho ai và được chấm thế nào | Bước 2–4 của quy trình hiện tại; bước 4 được đánh dấu là bottleneck giả định |
| Đo chất lượng checklist cùng với thời gian | Checklist lập nhanh nhưng thiếu một file phải nộp vẫn không giải được vấn đề | Success Metric: thời gian, số mục thiếu và số mục gán sai nguồn; cách đo trên cùng bộ file |
| Giữ người học ở bước kiểm cuối | Tài liệu có thể có ngoại lệ hoặc hai chỗ diễn đạt khác nhau; AI không nên tự kết luận bài đã đạt hay tự nộp | Quy trình tương lai, Boundary và phương án quay về tìm kiếm/checklist thủ công |

Các bước hiện tại cộng lại thành khoảng 20 phút và quy trình đề xuất khoảng 12 phút, nhưng đây là hai mốc để thiết kế phép so sánh. Tôi không dùng chênh lệch 8 phút làm kết quả cải thiện khi nhóm chưa chạy thử trên người dùng. Với candidate của nhóm, chất lượng đầu ra cần được kiểm bằng danh mục yêu cầu lấy từ file gốc, còn thời gian chỉ có ý nghĩa nếu checklist vẫn đủ và đúng nguồn.

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc thiếu ở đâu? | Tôi sửa gì? |
|---|---|---|---|---|
| CP1 | Gợi ý candidate đời sống và hỗ trợ diễn đạt theo Job Story | Giúp mở rộng danh sách, làm rõ actor, việc cần làm và kết quả | Gợi ý không chứng minh người thật gặp pain; thời gian/tần suất không có nguồn xác nhận | Ghi rõ các candidate và con số là giả định/ước lượng, không mô tả thành trải nghiệm đã kiểm chứng |
| CP2 | Phản biện ba card và chỉ ra thông tin còn thiếu | Nhắc nêu từng bước, bottleneck, metric và phương án Rule/checklist | Chưa thể xác nhận bottleneck hay target chỉ từ mô tả; không nên mặc định cần Agent | Đổi cách ghi từ kết luận sang giả thuyết; giữ baseline dạng tham khảo và để nhóm xác định target sau kiểm chứng |
| CP3 và CP4 phỏng vấn | Không dùng AI | — | — | Tự pitch, tự phản biện và hỏi người thật |
| CP5 | Tôi phụ trách phân tích quy trình và Problem Statement v0; dùng AI để rà lại lập luận và tìm chỗ còn thiếu | Gợi ý tách rõ đầu vào, đầu ra, bước bàn giao và người kiểm checklist | AI dễ xem thời gian ước lượng như số đã đo, hoặc đánh giá quá sớm rằng Workflow sẽ hiệu quả | Tôi giữ thời gian là mốc tham khảo, bổ sung cách đếm yêu cầu bị bỏ sót/sai nguồn và phương án quay về quy trình thủ công |

## 6. Reflection (CP7)

**6.1. Card của bạn khác khiến tôi hiểu thêm về bài toán.** Tôi chú ý đến card của Quang Anh về việc đọc nhiều file hướng dẫn khi nhận bài lab. Card đó chỉ rõ người gặp khó là sinh viên cần lập danh sách việc phải làm, chứ không phải bất cứ ai dùng GitHub. Nó cũng khiến tôi nhìn lại các card đời sống của mình: chỉ nói một việc “mất thời gian” thì chưa đủ, phải chỉ ra người làm đang dừng ở bước nào và đầu ra họ cần là gì. Với bài nhóm, bước đáng xem xét là đối chiếu một yêu cầu giữa README, checkpoint, rubric và hướng dẫn nộp.

**6.2. Nhóm có chọn giải pháp quá sớm không?** Lúc xem các candidate, việc nghĩ ngay đến một chatbot hay Agent khá dễ vì bài toán có nhiều tài liệu. Tuy nhiên, cây OST và bảng chấm điểm của nhóm vẫn đặt nhu cầu của sinh viên ở trước: biết đủ đầu ra, tiêu chí và hạn nộp. Khi viết CP5, tôi giữ quy trình hiện tại riêng với quy trình đề xuất. Nhờ vậy nhóm còn có thể so sánh tìm kiếm thủ công, checklist cố định, Rule và Workflow; việc chọn công cụ không thay thế cho việc mô tả đúng pain.

**6.3. Phản biện làm tôi sửa gì?** Ở card lập bữa ăn, câu hỏi được ghi trong bảng pitch là: “Bước tốn thời gian thật là chọn món, kiểm nguyên liệu hay trao đổi với người cùng nhà?” Tôi thấy mình đã gom nhiều thao tác thành một bottleneck và gán số phút khi chưa đo. Vì vậy, trong card cá nhân tôi đổi số phút thành ước lượng, ghi rõ bước nghẽn chỉ là dự kiến và nêu phương án checklist/thực đơn cố định trước khi nghĩ đến AI. Tôi áp dụng cùng cách nhìn khi làm CP5: 20 phút lập checklist là mốc để vẽ quy trình, còn bước đối chiếu có thật sự nghẽn nhất hay không vẫn cần kiểm.

**6.4. Điều CP4 cho thấy và chưa cho thấy.** Nhóm đã đối chiếu tài liệu của chính bài Day 02 và thấy yêu cầu làm bài, tiêu chí chấm và cách nộp nằm ở nhiều file. Ba tình huống trong báo cáo nhóm giúp chỉ ra những chỗ người học phải ghép thông tin từ hai hoặc ba nguồn. Tuy vậy, CP4 chưa có phỏng vấn hoặc survey người ngoài nhóm được ghi nhận, nên tôi không xem những ví dụ tài liệu hay các bản ghi phỏng vấn giả là bằng chứng sinh viên đã mất 20 phút hoặc từng nộp thiếu. Một tín hiệu phản bác đáng chú ý từ phần research là GitHub Search và VS Code Search đã giúp tìm nội dung trong nhiều file; nếu người học dùng chúng hiệu quả thì chưa chắc cần thêm AI.

**6.5. Trường khó viết nhất của Problem Statement.** Với tôi, Success Metric khó nhất vì phải vừa đo thời gian, vừa giữ chất lượng checklist. Nếu chỉ đặt mục tiêu từ 20 xuống 12 phút, hệ thống có thể làm nhanh hơn nhưng bỏ sót một yêu cầu bị trừ điểm. Tôi đã ghi baseline thời gian là ước lượng, chưa coi đó là kết quả đo; baseline lỗi thiếu mục hoặc sai nguồn hiện cũng chưa có. Cách đo đề xuất là cho người dùng lập checklist trên cùng một bộ file bằng cách hiện tại và cách thử, bấm thời gian từ lúc mở repo đến khi duyệt xong, rồi đối chiếu từng mục với danh mục chuẩn lấy từ file gốc. Boundary cũng quan trọng: AI được tạo nháp có nguồn, còn sinh viên kiểm và tự quyết trước khi dùng hoặc nộp bài.

**6.6. Nếu làm lại, tôi sẽ làm gì sớm hơn?** Tôi sẽ kiểm tra pain với sinh viên ngoài nhóm trước khi đặt target thời gian hoặc nghiêng về Workflow. Tôi muốn hỏi về lần làm lab gần nhất: họ đã mở những file nào, phải quay lại file nào, bước tìm nguồn và bước hiểu yêu cầu mất bao lâu, và có mục nào thực sự bị bỏ sót hay không. Tôi cũng sẽ quan sát một người lập checklist bằng công cụ tìm kiếm sẵn có. Nếu cách đó đã đủ nhanh và đủ chính xác, nhóm nên giữ No AI hoặc Rule; nếu vẫn phải ghép và diễn giải nhiều điều kiện giữa các file, khi ấy mới có cơ sở thử bước AI.

**6.7. Tôi hiểu chuỗi quyết định của nhóm như sau.** Sinh viên nhận một repo lab có yêu cầu nằm ở nhiều file và cần một checklist đủ mục, đúng tiêu chí, đúng hạn nộp. Quy trình hiện tại là đọc từng file, đối chiếu các quy định rồi tự ghi và rà lại checklist; bước đối chiếu được xem là bottleneck giả định. Nhóm sẽ đo thời gian lập checklist và đếm mục bắt buộc bị thiếu hoặc gán sai nguồn; mốc 20 phút hiện chỉ là ước lượng, còn target pilot là không bỏ sót mục và hoàn tất trong khoảng 12 phút. Boundary là AI chỉ tạo nháp có dẫn nguồn, sinh viên kiểm từng mục và tự nộp bài. Mức can thiệp đề xuất để thử là Workflow vì các bước cố định, AI chỉ hỗ trợ ghép yêu cầu; Agent không cần thiết trong phạm vi này. `TEAM.md` đang ghi Go cho pilot nhỏ, nhưng kết luận đó cần được đối chiếu với bốn rủi ro và ngưỡng dừng ở mục 8 báo cáo nhóm trước khi coi là quyết định đã hoàn tất.

## 7. Tài liệu tham khảo

- [README](../../README.md)
- [Worksheet](../../docs/01-worksheet.md)
- [Rules](../../RULES.md)
