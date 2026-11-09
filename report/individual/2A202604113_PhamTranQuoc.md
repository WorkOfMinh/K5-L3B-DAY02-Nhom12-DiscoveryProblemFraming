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

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

**Shortlist dự kiến:** #1 lập bữa ăn và mua sắm, #2 theo dõi hóa đơn, #3 sắp lịch nhiều điểm đến. Ba candidate có actor, đầu vào, kết quả và quy trình đủ rõ để mang ra pitch. Phút ở các quy trình là ước lượng minh họa nhằm làm rõ bước nào có thể là bottleneck; không phải số đo, cam kết hiệu quả hay ngưỡng chấm. Các mốc này có thể thay đổi hoặc bỏ nếu CP4 cho thấy giả định không đúng.

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
| CP1 | Gợi ý candidate đời sống và hỗ trợ diễn đạt theo Job Story | Giúp mở rộng danh sách, làm rõ actor, việc cần làm và kết quả | Gợi ý không chứng minh người thật gặp pain; thời gian/tần suất không có nguồn xác nhận | Ghi rõ các candidate và con số là giả định/ước lượng, không mô tả thành trải nghiệm đã kiểm chứng |
| CP2 | Phản biện ba card và chỉ ra thông tin còn thiếu | Nhắc nêu từng bước, bottleneck, metric và phương án Rule/checklist | Chưa thể xác nhận bottleneck hay target chỉ từ mô tả; không nên mặc định cần Agent | Đổi cách ghi từ kết luận sang giả thuyết; giữ baseline dạng tham khảo và để nhóm xác định target sau kiểm chứng |
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
