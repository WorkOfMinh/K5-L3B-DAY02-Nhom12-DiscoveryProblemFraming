# Báo cáo cá nhân — 2A202604113_PhamTranQuoc

## 1. Thông tin học viên

- Họ tên: Phạm Trấn Quốc
- MSSV: 2A202604113
- Tên nhóm: Nhóm 12
- Link repo nhóm: https://github.com/WorkOfMinh/K5-L3B-DAY02-Nhom12-DiscoveryProblemFraming

## 2. Scan problem (CP1)

Tôi chọn các tình huống có nhiều bước, nhiều nguồn thông tin hoặc ràng buộc thay đổi. Chúng **có thể** là bài toán cho AI hỗ trợ hoặc Agent, nhưng CP1 chỉ mô tả vấn đề. Sau khi đo và hỏi người thật, nhóm mới quyết định No AI, Rule, Workflow hay Agent.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu cần tự kiểm chứng |
|---:|---|---|---|---|
| 1 | Lặp lại, cần tổng hợp thông tin | Khi chuẩn bị bữa ăn cho vài ngày tới, tôi muốn đối chiếu đồ còn trong nhà, nhu cầu ăn uống và giá thực phẩm, để mua đủ đồ mà không bỏ phí đồ ăn. | Người nấu ăn, người cùng nhà | **Ước tính để kiểm:** 2 lần/tuần, 25 phút/lần lập danh sách; tự bấm giờ và đếm món bị bỏ phí trong tuần tới. |
| 2 | Tốn thời gian, nhiều nguồn | Khi đến kỳ thanh toán các khoản sinh hoạt, tôi muốn biết hóa đơn nào đã đến hạn, số tiền đúng và đã thanh toán chưa, để không trả trễ hoặc trả hai lần. | Người quản lý chi tiêu trong nhà | **Ước tính để kiểm:** 4–6 khoản/tháng từ nhiều ứng dụng; đếm khoản và phút đối chiếu trong kỳ tiếp theo. |
| 3 | Cần tổng hợp nhiều thông tin | Khi phải làm nhiều việc ở các địa điểm khác nhau trong một ngày, tôi muốn sắp thứ tự di chuyển theo giờ mở cửa, thời gian đi và thời hạn từng việc, để không phải đi vòng hoặc lỡ giờ. | Người đi làm việc cá nhân, người đi cùng | **Ước tính để kiểm:** 3 điểm đến trong một buổi; ghi thời gian lập lịch và quãng đường thực tế cho một lần gần nhất. |
| 4 | Pain từ người khác | Khi thiết bị trong nhà bị hỏng, người cùng nhà muốn biết ai có thể sửa, chi phí dự kiến và khi nào có người ở nhà, để không phải hỏi nhiều nơi rồi chốt lại từ đầu. | Người sống cùng nhà, người phụ trách sửa chữa | **Ước tính để kiểm:** liên hệ 2–3 nơi cho một lần sửa; chỉ giữ ý này nếu hỏi người thật đã từng trải qua. |
| 5 | Tốn thời gian, nhiều nguồn | Khi tổ chức một chuyến đi ngắn cho gia đình hoặc bạn bè, tôi muốn đối chiếu lịch rảnh, ngân sách, đường đi và giờ hoạt động của địa điểm, để chốt kế hoạch phù hợp cho mọi người. | Người tổ chức và người tham gia | **Ước tính để kiểm:** 3–4 người, ít nhất 3 nguồn thông tin; đo số lượt sửa kế hoạch của một chuyến đi thật. |

**AI đã gợi ý gì, tôi giữ/bỏ gì:** AI gợi ý cả các việc đơn giản như nhắc mang đồ và chọn món ăn. Tôi bỏ việc nhắc mang đồ vì checklist có thể đủ, không thấy nhu cầu cho một hệ thống tự quyết nhiều bước. Tôi giữ 5 ý trên làm **candidate để kiểm chứng**, chưa khẳng định chúng là pain thật của mình. Với mỗi ý, tôi sẽ thay số ước tính bằng số đo hoặc một sự kiện cụ thể.

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

**Shortlist dự kiến:** #1 lập bữa ăn và mua sắm, #2 theo dõi hóa đơn, #3 sắp lịch nhiều điểm đến. Ba việc này có actor, input và kết quả rõ; đồng thời cho phép so sánh cách thủ công, Rule, Workflow và Agent. Các phút dưới đây là **ước tính minh họa, không phải baseline đã đo**.

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Lập bữa ăn và danh sách mua sắm (#1) | Lặp lại, nhiều ràng buộc; có thể đo thời gian và lượng đồ bỏ phí | Việc khó nhất là chọn món hay kiểm đồ còn trong nhà? |
| 2 | Theo dõi hóa đơn sinh hoạt (#2) | Hậu quả thanh toán trễ rõ; có thể bắt đầu từ lịch nhắc và Rule | Có thật nhiều hóa đơn khó theo dõi, hay lịch nhắc đã đủ? |
| 3 | Sắp thứ tự nhiều điểm đến (#3) | Giờ mở cửa, thời gian di chuyển và việc phát sinh có thể thay đổi | Tần suất xảy ra có đủ cao để đáng giải không? |

### Problem Card #1 — Lập bữa ăn và mua sắm

| Trường | Nội dung |
|---|---|
| Job Story | Khi chuẩn bị bữa ăn cho vài ngày tới, tôi muốn đối chiếu đồ còn trong nhà, nhu cầu ăn uống và giá thực phẩm, để mua đủ đồ mà không bỏ phí đồ ăn. |
| Actor | Người nấu ăn và mua thực phẩm cho gia đình |
| Bối cảnh | Trước một lần đi chợ hoặc đặt thực phẩm cho 2–3 ngày |
| Quy trình hiện tại | Kiểm đồ còn → hỏi người cùng nhà muốn ăn gì → chọn món → xem nguyên liệu/giá → lập danh sách → mua |
| Bottleneck | Ghép món với nguyên liệu còn, khẩu vị và ngân sách; **ước tính 10 phút** |
| Impact | Mua thiếu, mua trùng hoặc để hỏng nguyên liệu; cần đo số món bỏ phí |
| Success metric | **Giả định:** 25 phút/lần lập danh sách → mục tiêu dưới 12 phút; bấm giờ 3 lần và đếm món bị bỏ phí |
| Phương án không dùng AI | Danh sách nguyên liệu cố định, thực đơn luân phiên và checklist trước khi mua |
| Giả thuyết về AI | Augment: gợi ý vài thực đơn dựa trên đồ còn; người dùng duyệt món và danh sách. Agent chỉ đáng cân nhắc nếu phải tự điều chỉnh nhiều bước theo giá, tồn kho và thay đổi của người dùng |
| Cảm nhận nhanh | Workflow trước; chưa đủ bằng chứng chọn Agent |

```text
[Kiểm đồ còn: 4'] → [Hỏi nhu cầu: 3'] → [Chọn món: 10'] ← nghẽn dự kiến
→ [Xem giá/nguyên liệu: 5'] → [Lập danh sách: 3']
Tổng ước tính: 25 phút; phải đo lại.
```

### Problem Card #2 — Theo dõi hóa đơn

| Trường | Nội dung |
|---|---|
| Job Story | Khi đến kỳ thanh toán các khoản sinh hoạt, tôi muốn biết hóa đơn nào đã đến hạn, số tiền đúng và đã thanh toán chưa, để không trả trễ hoặc trả hai lần. |
| Actor | Người quản lý chi tiêu trong nhà |
| Bối cảnh | Đầu hoặc cuối tháng, khi nhiều thông báo thanh toán đến từ ứng dụng khác nhau |
| Quy trình hiện tại | Mở từng ứng dụng/tin nhắn → ghi hạn và số tiền → đối chiếu lịch sử → sắp thứ tự hạn → thanh toán → lưu bằng chứng |
| Bottleneck | Đối chiếu thông báo với khoản đã trả; **ước tính 8 phút/kỳ** |
| Impact | Trả trễ hoặc nhầm khoản; cần hỏi người thật xem đã từng xảy ra chưa |
| Success metric | **Giả định:** 20 phút/kỳ → mục tiêu dưới 10 phút; đo 2 kỳ và đếm khoản bị bỏ sót/trùng |
| Phương án không dùng AI | Lịch nhắc cố định, bảng theo dõi và Rule đánh dấu khoản đến hạn |
| Giả thuyết về AI | Augment việc đọc thông báo không đồng nhất, nhưng con người xác nhận số tiền. Automate nhắc hạn có thể dùng Rule; **không tự thanh toán** |
| Cảm nhận nhanh | Rule có thể đủ; chưa thấy lý do dùng Agent |

```text
[Mở nguồn: 4'] → [Ghi khoản: 3'] → [Đối chiếu đã trả: 8'] ← nghẽn dự kiến
→ [Sắp hạn: 2'] → [Thanh toán/lưu chứng từ: 3']
Tổng ước tính: 20 phút; phải đo lại.
```

### Problem Card #3 — Sắp việc ở nhiều địa điểm

| Trường | Nội dung |
|---|---|
| Job Story | Khi phải làm nhiều việc ở các địa điểm khác nhau trong một ngày, tôi muốn sắp thứ tự di chuyển theo giờ mở cửa, thời gian đi và thời hạn từng việc, để không phải đi vòng hoặc lỡ giờ. |
| Actor | Người có nhiều việc cá nhân cần hoàn thành trong một buổi |
| Bối cảnh | Trước khi ra ngoài và khi có địa điểm đóng cửa hoặc lịch đổi bất ngờ |
| Quy trình hiện tại | Liệt kê việc → kiểm giờ mở cửa → tra đường → ước tính thời gian ở mỗi nơi → xếp thứ tự → điều chỉnh khi có thay đổi |
| Bottleneck | Xếp thứ tự khi giờ mở cửa và di chuyển ràng buộc nhau; **ước tính 12 phút** |
| Impact | Đi vòng, phải quay lại hoặc bỏ lỡ một việc |
| Success metric | **Giả định:** 30 phút lập lịch → mục tiêu dưới 15 phút; đo số lần phải quay lại và thời gian di chuyển thực tế |
| Phương án không dùng AI | Bản đồ có nhiều điểm dừng, lịch giờ mở cửa và bảng ưu tiên thủ công |
| Giả thuyết về AI | Augment bằng cách đề xuất lộ trình và giải thích ràng buộc; chỉ automate cập nhật lịch khi người dùng xác nhận. Agent có thể hữu ích nếu phải tự lập lại kế hoạch theo sự kiện mới, nhưng không tự đặt chỗ hay chi tiền |
| Cảm nhận nhanh | Workflow; cân nhắc Agent sau kiểm chứng |

```text
[Liệt kê việc: 3'] → [Kiểm giờ: 5'] → [Tra đường: 5']
→ [Xếp thứ tự: 12'] ← nghẽn dự kiến → [Rà lại lịch: 5']
Tổng ước tính: 30 phút; phải đo lại.
```

### Card muốn pitch nhất

- Card số: 1, tôi xác nhận mình hoặc người cùng nhà thực sự gặp việc này thường xuyên.
- Vì sao: Quy trình lặp lại và có nhiều ràng buộc; vẫn có phương án không dùng AI để so sánh.
- Câu hỏi muốn nhóm phản biện: “Bước tốn thời gian thật là chọn món, kiểm nguyên liệu, hay trao đổi với người cùng nhà?”

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Tôi cần sửa gì |
|---|---|---|
| Chưa có số phút thật nên chưa biết bottleneck | Đồng ý | Bấm giờ ít nhất 2 lần, ghi từng bước |
| Việc lập thực đơn có thể giải bằng template | Đồng ý | So sánh template/Rule trước khi chọn AI |
| Chưa biết người cùng nhà có muốn máy tự quyết món hay chỉ gợi ý | Đồng ý | Hỏi hành vi và mức tự chủ mong muốn; phân biệt Augment với Automate |

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

**Chưa có hoạt động nhóm được ghi nhận trong `TEAM.md` và `group_report.md`.** Sau buổi nhóm, tôi tự điền câu hỏi đã đặt, câu hỏi nhận được, candidate được chọn, thay đổi sau phản biện và bằng chứng đóng góp. Không ghi tình huống dự đoán thành việc đã diễn ra.

| Hoạt động | Điều tôi phải ghi sau khi thực hiện | Bằng chứng |
|---|---|---|
| Pitch và phản biện | Card đã pitch; câu hỏi nguyên văn mình đặt cho người khác và nhận từ họ; mình đã sửa gì | Bảng pitch CP3 |
| Chọn candidate | Lý do chọn và lý do loại ít nhất hai ý | OST, bảng chấm điểm |
| Kiểm chứng | Vai trò người được hỏi, thời điểm, hành vi họ kể, tín hiệu phản bác | Snapshot/survey CP4 |
| Quy trình, Problem Statement | Bước tôi sửa, metric/boundary tôi góp ý | Mục 4–7 báo cáo nhóm |
| Quyết định | Lập luận của tôi về Augment/Automate, No AI/Rule/Workflow/Agent và bốn rủi ro | Mục 6–8 báo cáo nhóm, TEAM.md |

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc thiếu ở đâu? | Tôi sửa gì? |
|---|---|---|---|---|
| CP1 | Sử dụng năm tình huống đời sống tôi đề xuất để viết lại theo Job Story | Giúp mở rộng phạm vi khỏi một bài lab | Các số phút AI gợi ý không phải bằng chứng | Đánh dấu tất cả là ước tính; chỉ giữ tình huống tôi xác nhận |
| CP2 | Phản biện ba card, so sánh cách đơn giản với AI | Nêu câu hỏi về bottleneck và quyền tự quyết | Có thể kết luận Agent quá sớm | Giữ mức can thiệp là giả thuyết, yêu cầu đo và hỏi người thật |
| CP3 và CP4 phỏng vấn | Không dùng AI | — | — | Tự pitch, tự phản biện và hỏi người thật |
| CP4 research, CP5–CP6 | Chưa thực hiện | — | — | Nếu dùng AI, ghi prompt, tự kiểm link và ghi sửa đổi thực tế |

## 6. Reflection (CP7)

**Tôi phải tự viết phần này sau khi làm nhóm.** Rubric quy định reflection do AI viết thay được 0 điểm C4. Mục 6.1–6.6 cần tối thiểu 200 từ về trải nghiệm thật; dưới đây là câu hỏi để tôi tự ghi, không phải câu trả lời nộp bài.

**6.1.** Card nào của bạn khác khiến tôi hiểu thêm về actor hoặc bottleneck?  
**6.2.** Nhóm có chọn giải pháp quá sớm không? Nhóm quay về pain bằng cách nào?  
**6.3.** Câu hỏi phản biện nào khiến tôi đổi ý? Tôi đã sửa cụ thể điều gì?  
**6.4.** Người được hỏi đã làm gì trong lần gần nhất? Có tín hiệu nào bác bỏ giả định?  
**6.5.** Trường nào của Problem Statement khó viết nhất và vì sao?  
**6.6.** Nếu làm lại, tôi sẽ đo hoặc hỏi điều gì sớm hơn?  
**6.7.** Sau khi nhóm chốt, tôi tự giải thích trong 5–8 câu: problem → quy trình → metric có baseline/target/cách đo → boundary → mức can thiệp → Go/Not Yet/No-Go.

## 7. Tài liệu tham khảo

- [README](../../README.md)
- [Worksheet](../../docs/01-worksheet.md)
- [Rules](../../RULES.md)
