# Báo cáo cá nhân — 2A202604120_NguyenQuocQuangAnh
## 1. Thông tin học viên
- Họ tên: Nguyễn Quốc Quang Anh
- MSSV: 2A202604120
- Tên nhóm: Nhóm 12
- Link repo nhóm: https://github.com/WorkOfMinh/K5-L3B-DAY02-Nhom12-DiscoveryProblemFraming.git

---

## 2. Scan problem (CP1)

### 2.1. Phạm vi và cách tiếp cận

Phạm vi khám phá vấn đề tập trung vào việc học và thực hành của sinh viên Công nghệ thông tin: tiếp nhận yêu cầu từ repository, thiết lập môi trường lập trình, chuẩn bị dữ liệu nghiên cứu, xử lý tài liệu số, tổng hợp kết quả và phối hợp bài tập nhóm. Những hoạt động này có đầu vào, các bước thực hiện và sản phẩm đầu ra tương đối rõ, phù hợp để phân tích theo hướng **problem-first** thay vì bắt đầu bằng một ý tưởng AI.

Sáu vấn đề được mô tả dưới dạng **Job Story** theo bốn lăng kính: lặp lại, tốn thời gian, phải tổng hợp nhiều nguồn thông tin, và khó khăn phát sinh khi phối hợp. Phần *dấu hiệu* phân biệt hai loại thông tin: (a) dữ kiện có thể đối chiếu ngay từ tài liệu hoặc hiện vật; (b) thời gian **ước lượng dùng để hình thành giả thuyết**, không được hiểu là kết quả đo thực nghiệm hay phỏng vấn người dùng.

### 2.2. Bảng scan 6 vấn đề

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu và phạm vi đo lường |
|---:|---|---|---|---|
| **P1** | Cần đọc, tổng hợp nhiều thông tin | Khi nhận một bài lab có yêu cầu nằm ở nhiều file trên GitHub, tôi muốn xác định đầy đủ nhiệm vụ, tiêu chí hoàn thành và file phải nộp, để tránh bỏ sót đầu việc hoặc đọc lại nhiều lần. | Sinh viên làm bài lab từ repository. | **Quan sát kiểm chứng được:** repo Day 02 công bố 8 checkpoint (CP0–CP7), tách hướng dẫn tại `README.md`, `CHECKPOINTS.md`, `RULES.md`, `RUBRIC.md`, `SUBMISSION.md` và `docs/01-worksheet.md`. **Mốc phân tích giả định:** 65 phút để tạo checklist yêu cầu từ đầu. |
| **P2** | Lặp lại | Khi chạy một dự án Python trong môi trường mới, tôi muốn thiết lập đúng phiên bản và thư viện, để chương trình chạy ổn định mà không phải sửa đi sửa lại lỗi cấu hình. | Sinh viên thực hành lập trình. | **Đầu ra kiểm tra được:** phiên bản Python, danh sách gói cài đặt, log lần chạy đầu và số lỗi trước khi chạy thành công. **Mốc phân tích giả định:** 60 phút/lần thiết lập. |
| **P3** | Tốn thời gian | Khi chuẩn bị chạy ResNet18 trên tập ảnh ISIC 2017 trong Google Colab, tôi muốn xác minh dữ liệu, nhãn và đường dẫn đã đúng, để không làm gián đoạn thí nghiệm vì lỗi chuẩn bị. | Sinh viên thực hành học máy. | **Đầu ra kiểm tra được:** cấu trúc thư mục ảnh, tệp nhãn, notebook và traceback nếu có. **Mốc phân tích giả định:** 90 phút cho toàn bộ khâu chuẩn bị/chạy thử, không tính train chính thức. |
| **P4** | Tốn thời gian | Khi có tài liệu PDF scan viết tay cần chuyển sang Word, tôi muốn giữ đúng nội dung gốc, để có bản văn bản chỉnh sửa được mà không phải nhập lại quá nhiều hoặc bỏ sót thông tin. | Sinh viên xử lý tài liệu học tập. | **Đầu ra kiểm tra được:** bản PDF nguồn và bản Word, số trang, số lỗi khi đối chiếu. **Mốc phân tích giả định:** 85 phút/tài liệu cùng độ dài. |
| **P5** | Cần đọc, tổng hợp nhiều thông tin | Khi hoàn thành thí nghiệm học máy, tôi muốn tập hợp đúng các chỉ số đánh giá từ kết quả chạy, để gửi báo cáo rõ ràng và không nhầm lẫn giữa các lần thí nghiệm. | Sinh viên thực hiện nghiên cứu AI. | **Các trường cần đối chiếu:** accuracy, precision, recall, F1-score; kèm tập đánh giá và phiên bản thí nghiệm. **Mốc phân tích giả định:** 70 phút/báo cáo. |
| **P6** | Pain từ người khác | Khi làm bài nhóm có nhiều đầu việc phụ thuộc nhau, tôi muốn biết nhiệm vụ nào đang được phụ trách và nhiệm vụ nào chưa hoàn tất, để hạn chế trùng công việc hoặc bỏ sót trước hạn nộp. | Thành viên nhóm học tập. | **Quan sát kiểm chứng được:** bài Day 02 quy định nhóm 3–4 người và có cả báo cáo cá nhân lẫn báo cáo nhóm. **Giả thuyết cần kiểm chứng với người thật:** việc đối chiếu tiến độ có thể mất 40 phút/tuần. |

**Diễn giải dấu hiệu:** Số lượng checkpoint, loại file và các trường dữ liệu là những đặc điểm của công việc, **không tự chứng minh** đã có người mất đúng thời gian hoặc từng gặp lỗi. Các mốc phút trong bảng là ước lượng để đặt câu hỏi, chọn hướng nghiên cứu và xây dựng metric; không phải số liệu phỏng vấn, khảo sát hay kết quả đo cá nhân. Khi chuyển sang CP4, nhóm phải kiểm chứng bằng hành vi và bằng chứng thực tế.

### 2.3. Nhận xét và lựa chọn sơ bộ

- **P1** nổi bật ở việc thông tin phân tán và cần đối chiếu nhiều tài liệu. Đây là vấn đề có phạm vi nhỏ: từ khi nhận link repo đến khi lập xong checklist các yêu cầu bắt buộc. Dễ phân biệt giữa việc *đọc được nội dung* và *xác định đúng việc cần làm*.
- **P2** và **P3** cùng liên quan đến lỗi kỹ thuật, nhưng P3 cụ thể hơn vì giới hạn trong chuẩn bị dữ liệu và notebook cho một thí nghiệm.
- **P4** khác với việc chỉ rút ngắn thời gian thao tác: chất lượng nội dung sau chuyển đổi phải được giữ ổn định, nếu không giải pháp có thể gây hại hơn lợi.
- **P5** có nguy cơ trộn số liệu từ train, validation và test hoặc từ nhiều lần chạy; điều này phù hợp với một quy trình kiểm tra và chuẩn hóa báo cáo.
- **P6** liên quan đến nhiều thành viên nhưng cần tín hiệu từ chính người tham gia để xác định mức độ thường xuyên và hậu quả của vấn đề, không suy ra từ quy định làm việc nhóm.

Từ các tiêu chí **actor rõ**, **quy trình vẽ được**, **bottleneck cụ thể**, **tác động đo được** và **phạm vi vừa sức**, ba ứng viên được đưa vào CP2 là **P1, P3 và P4**. Đây là quyết định chọn vấn đề để phân tích sâu, **chưa phải quyết định triển khai AI**.

### 2.4. Vai trò của AI trong bước scan

ChatGPT được dùng để rà soát cách diễn đạt, kiểm tra xem Job Story đã nói về khó khăn của người dùng hay đang mô tả sẵn giải pháp, đồng thời nêu các lỗ hổng trong bằng chứng. Các gợi ý được xử lý như sau:

| Gợi ý được xem xét | Xử lý | Lý do |
|---|---|---|
| Tách việc đọc nhiều file và việc đối chiếu yêu cầu của bài lab | Giữ | Hai hoạt động có thể có thời gian và nguyên nhân chậm khác nhau. |
| Giới hạn vấn đề Colab ở chuẩn bị và kiểm tra đầu vào, không gộp cả quá trình nghiên cứu mô hình | Giữ | Làm rõ phạm vi, bottleneck và cách đo. |
| Tạo một trợ lý AI tự làm toàn bộ bài tập, lập trình và nộp bài | Loại | Đây là solution quá rộng, chưa chỉ ra pain thực tế hay giới hạn trách nhiệm. |

**Kết luận CP1:** Có sáu candidate problem theo bốn lăng kính; ba candidate được chuyển sang CP2. Các con số thời gian chỉ là giả định phân tích, còn các nhận định về tần suất và mức độ ảnh hưởng cần được kiểm chứng bằng hành vi thật ở bước nghiên cứu tiếp theo.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### 3.1. Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| **1** | **P1 — Xác định yêu cầu bài lab từ nhiều file GitHub** | Actor cụ thể, quy trình bắt đầu/kết thúc rõ, dễ kiểm tra với repo thật; có thể so sánh hiệu quả checklist với cách đọc thủ công. | Bước nghẽn là tìm file, hiểu câu chữ hay đối chiếu yêu cầu bắt buộc? |
| **2** | **P3 — Chuẩn bị dữ liệu và notebook ResNet18 trên Colab** | Tác vụ kỹ thuật có log và đầu ra rõ; bottleneck có thể cô lập ở khâu cấu hình trước train. | Lỗi xuất hiện do đường dẫn, tập dữ liệu, dependency hay thao tác người dùng? |
| **3** | **P4 — Chuyển PDF scan viết tay sang Word** | Có đầu vào và đầu ra so sánh được; metric cần phản ánh cả thời gian lẫn độ trung thực của nội dung. | Khâu nhập nội dung hay khâu rà soát bản Word mới thực sự mất thời gian nhất? |

**Quy ước thống nhất:** Toàn bộ thời gian ở ba sơ đồ dưới đây là một **kịch bản ước lượng tham chiếu** cho mỗi lần thực hiện công việc, không phải dữ liệu đã đo; mỗi tổng được tính từ thời gian từng bước. **Baseline** là mốc giả định để thiết kế cách đánh giá; **target** là mục tiêu đề xuất, không phải kết quả cải thiện đã đạt.

### 3.2. Problem Card #1 — Xác định đầy đủ yêu cầu bài lab GitHub

| Trường | Nội dung |
|---|---|
| **Job Story** | Khi nhận một bài lab có yêu cầu nằm trong nhiều file GitHub, tôi muốn xác định đúng các nhiệm vụ, file phải hoàn thành và tiêu chí chấm, để lập kế hoạch thực hiện không bỏ sót việc. |
| **Actor** | Sinh viên CNTT vừa nhận repository hướng dẫn bài lab. |
| **Thời điểm / bối cảnh** | Từ khi mở link repository đến khi có checklist công việc trước khi bắt đầu bài. |
| **Quy trình hiện tại (6 bước)** | (1) Mở repository; (2) đọc `README.md`; (3) tìm các file hướng dẫn liên quan; (4) đối chiếu checkpoint, rubric, submission; (5) ghi checklist; (6) rà soát checklist với nguồn gốc. |
| **Bottleneck** | **Bước 4 — đối chiếu yêu cầu giữa các file: 20 phút/lần (ước lượng)**. Đòi hỏi phân biệt tài liệu tham khảo với đầu ra bắt buộc và điều kiện chấm. |
| **Impact** | Mất thời gian đọc lại tài liệu; có nguy cơ bỏ sót mục bắt buộc hoặc sửa sai file; ảnh hưởng tiến độ và chất lượng nộp bài. |
| **Success metric (baseline → target)** | **Thời gian lập checklist:** 65 → 30 phút/lần (**giả định → mục tiêu**). **Độ bao phủ yêu cầu:** mục tiêu 100% yêu cầu bắt buộc được liệt kê và gắn đúng file. **Cách đo:** bấm giờ từ khi mở repo đến khi checklist hoàn tất; đối chiếu checklist với `CHECKPOINTS.md`, `RUBRIC.md`, `SUBMISSION.md`. |
| **Phương án không dùng AI** | Checklist theo checkpoint và mapping `yêu cầu → tài liệu nguồn → file đầu ra → trạng thái`, liên kết trực tiếp đến vị trí hướng dẫn. |
| **Giả thuyết về AI (nếu có)** | AI có thể hỗ trợ soạn checklist sơ bộ từ tài liệu, nhưng sinh viên phải xác minh từng yêu cầu bằng file nguồn; không tự tạo nội dung bài hay tự nộp. |
| **Cảm nhận nhanh** | **Rule hoặc Workflow, chưa chốt.** Thử checklist có cấu trúc trước, vì có thể đủ giải quyết phần lớn khó khăn. |

**Quy trình nháp hiện tại — tổng 65 phút/lần (ước lượng):**

```mermaid
flowchart TD
    A["1. Mở repository<br/>5 phút"] --> B["2. Đọc README<br/>10 phút"]
    B --> C["3. Tìm file hướng dẫn<br/>15 phút"]
    C --> D["4. Đối chiếu yêu cầu, rubric, submission<br/>20 phút — BOTTLENECK"]
    D --> E["5. Lập checklist<br/>10 phút"]
    E --> F["6. Rà soát checklist<br/>5 phút"]
    style D fill:#ffe2e2,stroke:#b91c1c,stroke-width:2px,color:#111111
```

**Lý do chọn bước nghẽn:** Đọc được từng file không đồng nghĩa đã biết chính xác phải nộp gì. Bước 4 là điểm kết nối các yêu cầu phân tán thành một bộ nhiệm vụ hoàn chỉnh; nếu đối chiếu sai, checklist tạo ở bước sau cũng sai. **Boundary của vấn đề:** chỉ xét việc xác định yêu cầu, không xét việc tự hoàn thành bài bằng công cụ.

### 3.3. Problem Card #2 — Chuẩn bị thí nghiệm ResNet18 trên Google Colab

| Trường | Nội dung |
|---|---|
| **Job Story** | Khi chuẩn bị chạy ResNet18 với dữ liệu ISIC 2017 trên Colab, tôi muốn kiểm tra chính xác cấu trúc dữ liệu, đường dẫn và thiết lập môi trường, để thí nghiệm không bị gián đoạn vì lỗi đầu vào. |
| **Actor** | Sinh viên thực hành huấn luyện mô hình phân loại ảnh trong notebook Colab. |
| **Thời điểm / bối cảnh** | Sau khi có dữ liệu và trước khi bắt đầu huấn luyện đầy đủ. |
| **Quy trình hiện tại (6 bước)** | (1) Kiểm tra các thành phần dataset; (2) tải/giải nén; (3) kết nối nơi lưu trữ và khai báo đường dẫn; (4) kiểm tra ảnh/nhãn, sửa lỗi cấu hình; (5) chạy thử một batch; (6) xác nhận trạng thái sẵn sàng train. |
| **Bottleneck** | **Bước 4 — kiểm tra dữ liệu và sửa lỗi cấu hình: 30 phút/lần (ước lượng)**. Lỗi đường dẫn hoặc không khớp file ảnh/nhãn có thể khiến quy trình dừng. |
| **Impact** | Tăng thời gian chuẩn bị, phải chạy lại notebook; rủi ro sử dụng nhầm đường dẫn hoặc đầu vào không đúng, làm thí nghiệm thiếu tin cậy. |
| **Success metric (baseline → target)** | **Thời gian chuẩn bị và chạy thử:** 90 → 45 phút/lần (**giả định → mục tiêu**), **không bao gồm thời gian train chính thức**. Mục tiêu 0 lỗi cấu trúc/đường dẫn ở lần chạy preflight. **Cách đo:** ghi thời điểm bắt đầu/kết thúc khâu chuẩn bị và đếm lỗi trước khi train. |
| **Phương án không dùng AI** | Notebook mẫu, cấu trúc thư mục thống nhất, cấu hình tập trung, checklist preflight kiểm tra file ảnh/nhãn, split và một batch dữ liệu. |
| **Giả thuyết về AI (nếu có)** | AI giúp diễn giải traceback hoặc gợi ý bước kiểm tra; người dùng xác nhận mọi thay đổi và không để AI tự chạy huấn luyện hoặc xử lý file dữ liệu ngoài phạm vi. |
| **Cảm nhận nhanh** | **Rule** có thể đủ dùng: mã kiểm tra đầu vào tự động trước train. |

**Quy trình nháp hiện tại — tổng 90 phút/lần chuẩn bị (ước lượng):**

```mermaid
flowchart TD
    A["1. Kiểm tra thành phần dataset<br/>10 phút"] --> B["2. Tải và giải nén<br/>15 phút"]
    B --> C["3. Kết nối lưu trữ, khai báo path<br/>15 phút"]
    C --> D["4. Kiểm tra đầu vào và sửa cấu hình<br/>30 phút — BOTTLENECK"]
    D --> E["5. Chạy thử một batch<br/>15 phút"]
    E --> F["6. Xác nhận sẵn sàng train<br/>5 phút"]
    style D fill:#ffe2e2,stroke:#b91c1c,stroke-width:2px,color:#111111
```

**Lý do chọn bước nghẽn:** Một lỗi dữ liệu/cấu hình trước khi train không thể giải quyết bằng việc thay kiến trúc ResNet18. Vì vậy nhiệm vụ cần thu hẹp vào **preflight của notebook**, không đồng nhất với bài toán nâng accuracy, cũng không lấy thời gian GPU train làm thời gian thao tác của người dùng.

### 3.4. Problem Card #3 — Chuyển PDF scan viết tay sang Word mà vẫn đúng nội dung

| Trường | Nội dung |
|---|---|
| **Job Story** | Khi có tài liệu viết tay dưới dạng PDF scan cần chỉnh sửa trong Word, tôi muốn chuyển đổi mà vẫn giữ chính xác nội dung gốc, để giảm nhập lại thủ công và dùng được tài liệu cho học tập. |
| **Actor** | Sinh viên cần chuyển tài liệu scan để soát lỗi, chỉnh sửa hoặc trích xuất nội dung. |
| **Thời điểm / bối cảnh** | Từ lúc có bản PDF scan đến khi tạo xong bản Word đã kiểm tra. |
| **Quy trình hiện tại (5 bước)** | (1) Kiểm tra chất lượng scan; (2) nhập hoặc trích xuất nội dung; (3) đối chiếu và sửa lỗi; (4) định dạng Word; (5) kiểm tra cuối và lưu file. |
| **Bottleneck** | **Bước 3 — đối chiếu và sửa lỗi chữ viết tay: 30 phút/tài liệu (ước lượng)**, nhất là từ khó đọc, con số và ký hiệu. |
| **Impact** | Mất công nhập liệu; lỗi nội dung có thể gây sai lệch khi phân tích; phải rà soát nhiều vòng trước khi sử dụng. |
| **Success metric (baseline → target)** | **Thời gian hoàn tất một tài liệu cùng số trang:** 85 → 45 phút (**giả định → mục tiêu**). **Chất lượng:** mục tiêu tỷ lệ từ sai sau kiểm tra ≤2% trên mẫu so khớp với bản gốc. **Cách đo:** bấm giờ, đếm số từ sai chia cho tổng số từ được kiểm tra, giữ nguyên tài liệu mẫu. |
| **Phương án không dùng AI** | Nhập tay theo từng trang; đánh dấu vị trí khó đọc; checklist soát số, tên riêng, ký hiệu và đoạn bỏ sót; kiểm tra lại với bản gốc. |
| **Giả thuyết về AI (nếu có)** | Nhận dạng chữ viết tay tạo bản nháp, sau đó người dùng kiểm tra thủ công và phê duyệt; các đoạn mơ hồ phải được đánh dấu, không tự đoán nội dung. |
| **Cảm nhận nhanh** | **Workflow có người soát**, chỉ cân nhắc sau khi so với phương án thủ công hoặc công cụ nhận dạng có sẵn. |

**Quy trình nháp hiện tại — tổng 85 phút/tài liệu (ước lượng):**

```mermaid
flowchart TD
    A["1. Xem và chuẩn bị bản scan<br/>10 phút"] --> B["2. Nhập/trích xuất nội dung<br/>20 phút"]
    B --> C["3. Đối chiếu và sửa lỗi<br/>30 phút — BOTTLENECK"]
    C --> D["4. Định dạng Word<br/>15 phút"]
    D --> E["5. Kiểm tra cuối và lưu file<br/>10 phút"]
    style C fill:#ffe2e2,stroke:#b91c1c,stroke-width:2px,color:#111111
```

**Lý do chọn bước nghẽn:** Khả năng chỉnh sửa văn bản không có ý nghĩa nếu tài liệu sau chuyển đổi sai so với bản gốc. Vì thế bottleneck được đặt ở đối chiếu, và metric phải gồm **độ chính xác** chứ không chỉ thời gian. Phạm vi không bao gồm tự diễn giải hoặc viết lại nội dung tác giả.

### 3.5. Card muốn pitch nhất

- **Card số:** **#1 — Xác định yêu cầu bài lab từ nhiều file GitHub.**
- **Vì sao chọn:** Có actor và thời điểm rõ, có thể kiểm tra trực tiếp trên một repo công khai và đánh giá checklist theo hai chỉ số độc lập: thời gian tạo và độ bao phủ yêu cầu. Chi phí kiểm chứng thấp, đồng thời có phương án No AI đủ mạnh để so sánh trước khi tăng mức tự động hóa.
- **Câu hỏi muốn nhóm phản biện:** **“Nếu checklist chuẩn kèm liên kết đến các file gốc đã giúp sinh viên xác định đủ yêu cầu, bước nào vẫn thật sự cần can thiệp bằng AI?”**

### 3.6. AI đã phản biện card thế nào?

**Công cụ:** ChatGPT. **Vai trò phản biện:** Product Manager hoài nghi. **Trọng tâm:** Tính cụ thể của actor, tính thực tế của bước nghẽn, sự nhất quán của metric và khả năng giải quyết không cần AI. Đây là phần ghi nhận phản biện đối với **bản phân tích**, không thay cho khảo sát hay phỏng vấn người dùng.

**Prompt phản biện đã dùng để xây dựng bản chỉnh lý:**

> Hãy đóng vai Product Manager hoài nghi. Với ba Problem Card về (1) đọc yêu cầu lab GitHub, (2) chuẩn bị dữ liệu/Colab trước khi train ResNet18 và (3) chuyển PDF scan viết tay sang Word, hãy tìm lỗ hổng trong actor, quy trình, bottleneck, tác động, baseline, target, cách đo và phương án không dùng AI. Chỉ nêu điểm yếu; không tự tạo người dùng hoặc số liệu đo đạc.

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì trong bản này |
|---|---|---|
| Dùng số phút ước lượng như dữ liệu thực đo sẽ tạo bằng chứng không trung thực. | Có | Thống nhất nhãn **giả định → mục tiêu**, nêu rõ cách đo và không tuyên bố đã đạt target. |
| Card #1 dễ gộp việc đọc file với việc đối chiếu yêu cầu giữa nhiều nguồn. | Có | Tách bước tìm tài liệu (**bước 3**) và bước đối chiếu (**bước 4**); xác định bước 4 là bottleneck giả định. |
| Card #2 có thể tính nhầm cả thời gian huấn luyện GPU vào pain của người chuẩn bị. | Có | Giới hạn baseline/target ở **khâu chuẩn bị và chạy thử**. |
| Card #3 chỉ rút ngắn thời gian mà không kiểm soát lỗi là success metric chưa đầy đủ. | Có | Bổ sung tỷ lệ từ sai ≤2% sau kiểm tra trên mẫu cố định. |
| Việc đề xuất AI sớm có thể che khuất giải pháp đơn giản hơn. | Có | Nêu phương án **No AI** cho cả ba, chỉ để AI ở dạng giả thuyết và chưa chọn Agent. |

**Đánh giá sau phản biện:** Các card đã tách rõ nhu cầu, quy trình, bottleneck, tác động, thước đo và giải pháp không dùng AI. Điều chỉnh đáng kể nhất là chuyển **bước đối chiếu yêu cầu** thành bottleneck giả định của P1, thay vì gọi chung việc “đọc GitHub” là bước chậm; đồng thời bổ sung ràng buộc chất lượng cho P4.## 2. Scan problem (CP1)

### 2.1. Phạm vi và cách tiếp cận

Phạm vi khám phá vấn đề tập trung vào việc học và thực hành của sinh viên Công nghệ thông tin: tiếp nhận yêu cầu từ repository, thiết lập môi trường lập trình, chuẩn bị dữ liệu nghiên cứu, xử lý tài liệu số, tổng hợp kết quả và phối hợp bài tập nhóm. Những hoạt động này có đầu vào, các bước thực hiện và sản phẩm đầu ra tương đối rõ, phù hợp để phân tích theo hướng **problem-first** thay vì bắt đầu bằng một ý tưởng AI.

Sáu vấn đề được mô tả dưới dạng **Job Story** theo bốn lăng kính: lặp lại, tốn thời gian, phải tổng hợp nhiều nguồn thông tin, và khó khăn phát sinh khi phối hợp. Phần *dấu hiệu* phân biệt hai loại thông tin: (a) dữ kiện có thể đối chiếu ngay từ tài liệu hoặc hiện vật; (b) thời gian **ước lượng dùng để hình thành giả thuyết**, không được hiểu là kết quả đo thực nghiệm hay phỏng vấn người dùng.

### 2.2. Bảng scan 6 vấn đề

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu và phạm vi đo lường |
|---:|---|---|---|---|
| **P1** | Cần đọc, tổng hợp nhiều thông tin | Khi nhận một bài lab có yêu cầu nằm ở nhiều file trên GitHub, tôi muốn xác định đầy đủ nhiệm vụ, tiêu chí hoàn thành và file phải nộp, để tránh bỏ sót đầu việc hoặc đọc lại nhiều lần. | Sinh viên làm bài lab từ repository. | **Quan sát kiểm chứng được:** repo Day 02 công bố 8 checkpoint (CP0–CP7), tách hướng dẫn tại `README.md`, `CHECKPOINTS.md`, `RULES.md`, `RUBRIC.md`, `SUBMISSION.md` và `docs/01-worksheet.md`. **Mốc phân tích giả định:** 65 phút để tạo checklist yêu cầu từ đầu. |
| **P2** | Lặp lại | Khi chạy một dự án Python trong môi trường mới, tôi muốn thiết lập đúng phiên bản và thư viện, để chương trình chạy ổn định mà không phải sửa đi sửa lại lỗi cấu hình. | Sinh viên thực hành lập trình. | **Đầu ra kiểm tra được:** phiên bản Python, danh sách gói cài đặt, log lần chạy đầu và số lỗi trước khi chạy thành công. **Mốc phân tích giả định:** 60 phút/lần thiết lập. |
| **P3** | Tốn thời gian | Khi chuẩn bị chạy ResNet18 trên tập ảnh ISIC 2017 trong Google Colab, tôi muốn xác minh dữ liệu, nhãn và đường dẫn đã đúng, để không làm gián đoạn thí nghiệm vì lỗi chuẩn bị. | Sinh viên thực hành học máy. | **Đầu ra kiểm tra được:** cấu trúc thư mục ảnh, tệp nhãn, notebook và traceback nếu có. **Mốc phân tích giả định:** 90 phút cho toàn bộ khâu chuẩn bị/chạy thử, không tính train chính thức. |
| **P4** | Tốn thời gian | Khi có tài liệu PDF scan viết tay cần chuyển sang Word, tôi muốn giữ đúng nội dung gốc, để có bản văn bản chỉnh sửa được mà không phải nhập lại quá nhiều hoặc bỏ sót thông tin. | Sinh viên xử lý tài liệu học tập. | **Đầu ra kiểm tra được:** bản PDF nguồn và bản Word, số trang, số lỗi khi đối chiếu. **Mốc phân tích giả định:** 85 phút/tài liệu cùng độ dài. |
| **P5** | Cần đọc, tổng hợp nhiều thông tin | Khi hoàn thành thí nghiệm học máy, tôi muốn tập hợp đúng các chỉ số đánh giá từ kết quả chạy, để gửi báo cáo rõ ràng và không nhầm lẫn giữa các lần thí nghiệm. | Sinh viên thực hiện nghiên cứu AI. | **Các trường cần đối chiếu:** accuracy, precision, recall, F1-score; kèm tập đánh giá và phiên bản thí nghiệm. **Mốc phân tích giả định:** 70 phút/báo cáo. |
| **P6** | Pain từ người khác | Khi làm bài nhóm có nhiều đầu việc phụ thuộc nhau, tôi muốn biết nhiệm vụ nào đang được phụ trách và nhiệm vụ nào chưa hoàn tất, để hạn chế trùng công việc hoặc bỏ sót trước hạn nộp. | Thành viên nhóm học tập. | **Quan sát kiểm chứng được:** bài Day 02 quy định nhóm 3–4 người và có cả báo cáo cá nhân lẫn báo cáo nhóm. **Giả thuyết cần kiểm chứng với người thật:** việc đối chiếu tiến độ có thể mất 40 phút/tuần. |

**Diễn giải dấu hiệu:** Số lượng checkpoint, loại file và các trường dữ liệu là những đặc điểm của công việc, **không tự chứng minh** đã có người mất đúng thời gian hoặc từng gặp lỗi. Các mốc phút trong bảng là ước lượng để đặt câu hỏi, chọn hướng nghiên cứu và xây dựng metric; không phải số liệu phỏng vấn, khảo sát hay kết quả đo cá nhân. Khi chuyển sang CP4, nhóm phải kiểm chứng bằng hành vi và bằng chứng thực tế.

### 2.3. Nhận xét và lựa chọn sơ bộ

- **P1** nổi bật ở việc thông tin phân tán và cần đối chiếu nhiều tài liệu. Đây là vấn đề có phạm vi nhỏ: từ khi nhận link repo đến khi lập xong checklist các yêu cầu bắt buộc. Dễ phân biệt giữa việc *đọc được nội dung* và *xác định đúng việc cần làm*.
- **P2** và **P3** cùng liên quan đến lỗi kỹ thuật, nhưng P3 cụ thể hơn vì giới hạn trong chuẩn bị dữ liệu và notebook cho một thí nghiệm.
- **P4** khác với việc chỉ rút ngắn thời gian thao tác: chất lượng nội dung sau chuyển đổi phải được giữ ổn định, nếu không giải pháp có thể gây hại hơn lợi.
- **P5** có nguy cơ trộn số liệu từ train, validation và test hoặc từ nhiều lần chạy; điều này phù hợp với một quy trình kiểm tra và chuẩn hóa báo cáo.
- **P6** liên quan đến nhiều thành viên nhưng cần tín hiệu từ chính người tham gia để xác định mức độ thường xuyên và hậu quả của vấn đề, không suy ra từ quy định làm việc nhóm.

Từ các tiêu chí **actor rõ**, **quy trình vẽ được**, **bottleneck cụ thể**, **tác động đo được** và **phạm vi vừa sức**, ba ứng viên được đưa vào CP2 là **P1, P3 và P4**. Đây là quyết định chọn vấn đề để phân tích sâu, **chưa phải quyết định triển khai AI**.

### 2.4. Vai trò của AI trong bước scan

ChatGPT được dùng để rà soát cách diễn đạt, kiểm tra xem Job Story đã nói về khó khăn của người dùng hay đang mô tả sẵn giải pháp, đồng thời nêu các lỗ hổng trong bằng chứng. Các gợi ý được xử lý như sau:

| Gợi ý được xem xét | Xử lý | Lý do |
|---|---|---|
| Tách việc đọc nhiều file và việc đối chiếu yêu cầu của bài lab | Giữ | Hai hoạt động có thể có thời gian và nguyên nhân chậm khác nhau. |
| Giới hạn vấn đề Colab ở chuẩn bị và kiểm tra đầu vào, không gộp cả quá trình nghiên cứu mô hình | Giữ | Làm rõ phạm vi, bottleneck và cách đo. |
| Tạo một trợ lý AI tự làm toàn bộ bài tập, lập trình và nộp bài | Loại | Đây là solution quá rộng, chưa chỉ ra pain thực tế hay giới hạn trách nhiệm. |

**Kết luận CP1:** Có sáu candidate problem theo bốn lăng kính; ba candidate được chuyển sang CP2. Các con số thời gian chỉ là giả định phân tích, còn các nhận định về tần suất và mức độ ảnh hưởng cần được kiểm chứng bằng hành vi thật ở bước nghiên cứu tiếp theo.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### 3.1. Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| **1** | **P1 — Xác định yêu cầu bài lab từ nhiều file GitHub** | Actor cụ thể, quy trình bắt đầu/kết thúc rõ, dễ kiểm tra với repo thật; có thể so sánh hiệu quả checklist với cách đọc thủ công. | Bước nghẽn là tìm file, hiểu câu chữ hay đối chiếu yêu cầu bắt buộc? |
| **2** | **P3 — Chuẩn bị dữ liệu và notebook ResNet18 trên Colab** | Tác vụ kỹ thuật có log và đầu ra rõ; bottleneck có thể cô lập ở khâu cấu hình trước train. | Lỗi xuất hiện do đường dẫn, tập dữ liệu, dependency hay thao tác người dùng? |
| **3** | **P4 — Chuyển PDF scan viết tay sang Word** | Có đầu vào và đầu ra so sánh được; metric cần phản ánh cả thời gian lẫn độ trung thực của nội dung. | Khâu nhập nội dung hay khâu rà soát bản Word mới thực sự mất thời gian nhất? |

**Quy ước thống nhất:** Toàn bộ thời gian ở ba sơ đồ dưới đây là một **kịch bản ước lượng tham chiếu** cho mỗi lần thực hiện công việc, không phải dữ liệu đã đo; mỗi tổng được tính từ thời gian từng bước. **Baseline** là mốc giả định để thiết kế cách đánh giá; **target** là mục tiêu đề xuất, không phải kết quả cải thiện đã đạt.

### 3.2. Problem Card #1 — Xác định đầy đủ yêu cầu bài lab GitHub

| Trường | Nội dung |
|---|---|
| **Job Story** | Khi nhận một bài lab có yêu cầu nằm trong nhiều file GitHub, tôi muốn xác định đúng các nhiệm vụ, file phải hoàn thành và tiêu chí chấm, để lập kế hoạch thực hiện không bỏ sót việc. |
| **Actor** | Sinh viên CNTT vừa nhận repository hướng dẫn bài lab. |
| **Thời điểm / bối cảnh** | Từ khi mở link repository đến khi có checklist công việc trước khi bắt đầu bài. |
| **Quy trình hiện tại (6 bước)** | (1) Mở repository; (2) đọc `README.md`; (3) tìm các file hướng dẫn liên quan; (4) đối chiếu checkpoint, rubric, submission; (5) ghi checklist; (6) rà soát checklist với nguồn gốc. |
| **Bottleneck** | **Bước 4 — đối chiếu yêu cầu giữa các file: 20 phút/lần (ước lượng)**. Đòi hỏi phân biệt tài liệu tham khảo với đầu ra bắt buộc và điều kiện chấm. |
| **Impact** | Mất thời gian đọc lại tài liệu; có nguy cơ bỏ sót mục bắt buộc hoặc sửa sai file; ảnh hưởng tiến độ và chất lượng nộp bài. |
| **Success metric (baseline → target)** | **Thời gian lập checklist:** 65 → 30 phút/lần (**giả định → mục tiêu**). **Độ bao phủ yêu cầu:** mục tiêu 100% yêu cầu bắt buộc được liệt kê và gắn đúng file. **Cách đo:** bấm giờ từ khi mở repo đến khi checklist hoàn tất; đối chiếu checklist với `CHECKPOINTS.md`, `RUBRIC.md`, `SUBMISSION.md`. |
| **Phương án không dùng AI** | Checklist theo checkpoint và mapping `yêu cầu → tài liệu nguồn → file đầu ra → trạng thái`, liên kết trực tiếp đến vị trí hướng dẫn. |
| **Giả thuyết về AI (nếu có)** | AI có thể hỗ trợ soạn checklist sơ bộ từ tài liệu, nhưng sinh viên phải xác minh từng yêu cầu bằng file nguồn; không tự tạo nội dung bài hay tự nộp. |
| **Cảm nhận nhanh** | **Rule hoặc Workflow, chưa chốt.** Thử checklist có cấu trúc trước, vì có thể đủ giải quyết phần lớn khó khăn. |

**Quy trình nháp hiện tại — tổng 65 phút/lần (ước lượng):**

```mermaid
flowchart TD
    A["1. Mở repository<br/>5 phút"] --> B["2. Đọc README<br/>10 phút"]
    B --> C["3. Tìm file hướng dẫn<br/>15 phút"]
    C --> D["4. Đối chiếu yêu cầu, rubric, submission<br/>20 phút — BOTTLENECK"]
    D --> E["5. Lập checklist<br/>10 phút"]
    E --> F["6. Rà soát checklist<br/>5 phút"]
    style D fill:#ffe2e2,stroke:#b91c1c,stroke-width:2px,color:#111111
```

**Lý do chọn bước nghẽn:** Đọc được từng file không đồng nghĩa đã biết chính xác phải nộp gì. Bước 4 là điểm kết nối các yêu cầu phân tán thành một bộ nhiệm vụ hoàn chỉnh; nếu đối chiếu sai, checklist tạo ở bước sau cũng sai. **Boundary của vấn đề:** chỉ xét việc xác định yêu cầu, không xét việc tự hoàn thành bài bằng công cụ.

### 3.3. Problem Card #2 — Chuẩn bị thí nghiệm ResNet18 trên Google Colab

| Trường | Nội dung |
|---|---|
| **Job Story** | Khi chuẩn bị chạy ResNet18 với dữ liệu ISIC 2017 trên Colab, tôi muốn kiểm tra chính xác cấu trúc dữ liệu, đường dẫn và thiết lập môi trường, để thí nghiệm không bị gián đoạn vì lỗi đầu vào. |
| **Actor** | Sinh viên thực hành huấn luyện mô hình phân loại ảnh trong notebook Colab. |
| **Thời điểm / bối cảnh** | Sau khi có dữ liệu và trước khi bắt đầu huấn luyện đầy đủ. |
| **Quy trình hiện tại (6 bước)** | (1) Kiểm tra các thành phần dataset; (2) tải/giải nén; (3) kết nối nơi lưu trữ và khai báo đường dẫn; (4) kiểm tra ảnh/nhãn, sửa lỗi cấu hình; (5) chạy thử một batch; (6) xác nhận trạng thái sẵn sàng train. |
| **Bottleneck** | **Bước 4 — kiểm tra dữ liệu và sửa lỗi cấu hình: 30 phút/lần (ước lượng)**. Lỗi đường dẫn hoặc không khớp file ảnh/nhãn có thể khiến quy trình dừng. |
| **Impact** | Tăng thời gian chuẩn bị, phải chạy lại notebook; rủi ro sử dụng nhầm đường dẫn hoặc đầu vào không đúng, làm thí nghiệm thiếu tin cậy. |
| **Success metric (baseline → target)** | **Thời gian chuẩn bị và chạy thử:** 90 → 45 phút/lần (**giả định → mục tiêu**), **không bao gồm thời gian train chính thức**. Mục tiêu 0 lỗi cấu trúc/đường dẫn ở lần chạy preflight. **Cách đo:** ghi thời điểm bắt đầu/kết thúc khâu chuẩn bị và đếm lỗi trước khi train. |
| **Phương án không dùng AI** | Notebook mẫu, cấu trúc thư mục thống nhất, cấu hình tập trung, checklist preflight kiểm tra file ảnh/nhãn, split và một batch dữ liệu. |
| **Giả thuyết về AI (nếu có)** | AI giúp diễn giải traceback hoặc gợi ý bước kiểm tra; người dùng xác nhận mọi thay đổi và không để AI tự chạy huấn luyện hoặc xử lý file dữ liệu ngoài phạm vi. |
| **Cảm nhận nhanh** | **Rule** có thể đủ dùng: mã kiểm tra đầu vào tự động trước train. |

**Quy trình nháp hiện tại — tổng 90 phút/lần chuẩn bị (ước lượng):**

```mermaid
flowchart TD
    A["1. Kiểm tra thành phần dataset<br/>10 phút"] --> B["2. Tải và giải nén<br/>15 phút"]
    B --> C["3. Kết nối lưu trữ, khai báo path<br/>15 phút"]
    C --> D["4. Kiểm tra đầu vào và sửa cấu hình<br/>30 phút — BOTTLENECK"]
    D --> E["5. Chạy thử một batch<br/>15 phút"]
    E --> F["6. Xác nhận sẵn sàng train<br/>5 phút"]
    style D fill:#ffe2e2,stroke:#b91c1c,stroke-width:2px,color:#111111
```

**Lý do chọn bước nghẽn:** Một lỗi dữ liệu/cấu hình trước khi train không thể giải quyết bằng việc thay kiến trúc ResNet18. Vì vậy nhiệm vụ cần thu hẹp vào **preflight của notebook**, không đồng nhất với bài toán nâng accuracy, cũng không lấy thời gian GPU train làm thời gian thao tác của người dùng.

### 3.4. Problem Card #3 — Chuyển PDF scan viết tay sang Word mà vẫn đúng nội dung

| Trường | Nội dung |
|---|---|
| **Job Story** | Khi có tài liệu viết tay dưới dạng PDF scan cần chỉnh sửa trong Word, tôi muốn chuyển đổi mà vẫn giữ chính xác nội dung gốc, để giảm nhập lại thủ công và dùng được tài liệu cho học tập. |
| **Actor** | Sinh viên cần chuyển tài liệu scan để soát lỗi, chỉnh sửa hoặc trích xuất nội dung. |
| **Thời điểm / bối cảnh** | Từ lúc có bản PDF scan đến khi tạo xong bản Word đã kiểm tra. |
| **Quy trình hiện tại (5 bước)** | (1) Kiểm tra chất lượng scan; (2) nhập hoặc trích xuất nội dung; (3) đối chiếu và sửa lỗi; (4) định dạng Word; (5) kiểm tra cuối và lưu file. |
| **Bottleneck** | **Bước 3 — đối chiếu và sửa lỗi chữ viết tay: 30 phút/tài liệu (ước lượng)**, nhất là từ khó đọc, con số và ký hiệu. |
| **Impact** | Mất công nhập liệu; lỗi nội dung có thể gây sai lệch khi phân tích; phải rà soát nhiều vòng trước khi sử dụng. |
| **Success metric (baseline → target)** | **Thời gian hoàn tất một tài liệu cùng số trang:** 85 → 45 phút (**giả định → mục tiêu**). **Chất lượng:** mục tiêu tỷ lệ từ sai sau kiểm tra ≤2% trên mẫu so khớp với bản gốc. **Cách đo:** bấm giờ, đếm số từ sai chia cho tổng số từ được kiểm tra, giữ nguyên tài liệu mẫu. |
| **Phương án không dùng AI** | Nhập tay theo từng trang; đánh dấu vị trí khó đọc; checklist soát số, tên riêng, ký hiệu và đoạn bỏ sót; kiểm tra lại với bản gốc. |
| **Giả thuyết về AI (nếu có)** | Nhận dạng chữ viết tay tạo bản nháp, sau đó người dùng kiểm tra thủ công và phê duyệt; các đoạn mơ hồ phải được đánh dấu, không tự đoán nội dung. |
| **Cảm nhận nhanh** | **Workflow có người soát**, chỉ cân nhắc sau khi so với phương án thủ công hoặc công cụ nhận dạng có sẵn. |

**Quy trình nháp hiện tại — tổng 85 phút/tài liệu (ước lượng):**

```mermaid
flowchart TD
    A["1. Xem và chuẩn bị bản scan<br/>10 phút"] --> B["2. Nhập/trích xuất nội dung<br/>20 phút"]
    B --> C["3. Đối chiếu và sửa lỗi<br/>30 phút — BOTTLENECK"]
    C --> D["4. Định dạng Word<br/>15 phút"]
    D --> E["5. Kiểm tra cuối và lưu file<br/>10 phút"]
    style C fill:#ffe2e2,stroke:#b91c1c,stroke-width:2px,color:#111111
```

**Lý do chọn bước nghẽn:** Khả năng chỉnh sửa văn bản không có ý nghĩa nếu tài liệu sau chuyển đổi sai so với bản gốc. Vì thế bottleneck được đặt ở đối chiếu, và metric phải gồm **độ chính xác** chứ không chỉ thời gian. Phạm vi không bao gồm tự diễn giải hoặc viết lại nội dung tác giả.

### 3.5. Card muốn pitch nhất

- **Card số:** **#1 — Xác định yêu cầu bài lab từ nhiều file GitHub.**
- **Vì sao chọn:** Có actor và thời điểm rõ, có thể kiểm tra trực tiếp trên một repo công khai và đánh giá checklist theo hai chỉ số độc lập: thời gian tạo và độ bao phủ yêu cầu. Chi phí kiểm chứng thấp, đồng thời có phương án No AI đủ mạnh để so sánh trước khi tăng mức tự động hóa.
- **Câu hỏi muốn nhóm phản biện:** **“Nếu checklist chuẩn kèm liên kết đến các file gốc đã giúp sinh viên xác định đủ yêu cầu, bước nào vẫn thật sự cần can thiệp bằng AI?”**

### 3.6. AI đã phản biện card thế nào?

**Công cụ:** ChatGPT. **Vai trò phản biện:** Product Manager hoài nghi. **Trọng tâm:** Tính cụ thể của actor, tính thực tế của bước nghẽn, sự nhất quán của metric và khả năng giải quyết không cần AI. Đây là phần ghi nhận phản biện đối với **bản phân tích**, không thay cho khảo sát hay phỏng vấn người dùng.

**Prompt phản biện đã dùng để xây dựng bản chỉnh lý:**

> Hãy đóng vai Product Manager hoài nghi. Với ba Problem Card về (1) đọc yêu cầu lab GitHub, (2) chuẩn bị dữ liệu/Colab trước khi train ResNet18 và (3) chuyển PDF scan viết tay sang Word, hãy tìm lỗ hổng trong actor, quy trình, bottleneck, tác động, baseline, target, cách đo và phương án không dùng AI. Chỉ nêu điểm yếu; không tự tạo người dùng hoặc số liệu đo đạc.

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì trong bản này |
|---|---|---|
| Dùng số phút ước lượng như dữ liệu thực đo sẽ tạo bằng chứng không trung thực. | Có | Thống nhất nhãn **giả định → mục tiêu**, nêu rõ cách đo và không tuyên bố đã đạt target. |
| Card #1 dễ gộp việc đọc file với việc đối chiếu yêu cầu giữa nhiều nguồn. | Có | Tách bước tìm tài liệu (**bước 3**) và bước đối chiếu (**bước 4**); xác định bước 4 là bottleneck giả định. |
| Card #2 có thể tính nhầm cả thời gian huấn luyện GPU vào pain của người chuẩn bị. | Có | Giới hạn baseline/target ở **khâu chuẩn bị và chạy thử**. |
| Card #3 chỉ rút ngắn thời gian mà không kiểm soát lỗi là success metric chưa đầy đủ. | Có | Bổ sung tỷ lệ từ sai ≤2% sau kiểm tra trên mẫu cố định. |
| Việc đề xuất AI sớm có thể che khuất giải pháp đơn giản hơn. | Có | Nêu phương án **No AI** cho cả ba, chỉ để AI ở dạng giả thuyết và chưa chọn Agent. |

**Đánh giá sau phản biện:** Các card đã tách rõ nhu cầu, quy trình, bottleneck, tác động, thước đo và giải pháp không dùng AI. Điều chỉnh đáng kể nhất là chuyển **bước đối chiếu yêu cầu** thành bottleneck giả định của P1, thay vì gọi chung việc “đọc GitHub” là bước chậm; đồng thời bổ sung ràng buộc chất lượng cho P4.## 2. Scan problem (CP1)

### 2.1. Phạm vi và cách tiếp cận

Phạm vi khám phá vấn đề tập trung vào việc học và thực hành của sinh viên Công nghệ thông tin: tiếp nhận yêu cầu từ repository, thiết lập môi trường lập trình, chuẩn bị dữ liệu nghiên cứu, xử lý tài liệu số, tổng hợp kết quả và phối hợp bài tập nhóm. Những hoạt động này có đầu vào, các bước thực hiện và sản phẩm đầu ra tương đối rõ, phù hợp để phân tích theo hướng **problem-first** thay vì bắt đầu bằng một ý tưởng AI.

Sáu vấn đề được mô tả dưới dạng **Job Story** theo bốn lăng kính: lặp lại, tốn thời gian, phải tổng hợp nhiều nguồn thông tin, và khó khăn phát sinh khi phối hợp. Phần *dấu hiệu* phân biệt hai loại thông tin: (a) dữ kiện có thể đối chiếu ngay từ tài liệu hoặc hiện vật; (b) thời gian **ước lượng dùng để hình thành giả thuyết**, không được hiểu là kết quả đo thực nghiệm hay phỏng vấn người dùng.

### 2.2. Bảng scan 6 vấn đề

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu và phạm vi đo lường |
|---:|---|---|---|---|
| **P1** | Cần đọc, tổng hợp nhiều thông tin | Khi nhận một bài lab có yêu cầu nằm ở nhiều file trên GitHub, tôi muốn xác định đầy đủ nhiệm vụ, tiêu chí hoàn thành và file phải nộp, để tránh bỏ sót đầu việc hoặc đọc lại nhiều lần. | Sinh viên làm bài lab từ repository. | **Quan sát kiểm chứng được:** repo Day 02 công bố 8 checkpoint (CP0–CP7), tách hướng dẫn tại `README.md`, `CHECKPOINTS.md`, `RULES.md`, `RUBRIC.md`, `SUBMISSION.md` và `docs/01-worksheet.md`. **Mốc phân tích giả định:** 65 phút để tạo checklist yêu cầu từ đầu. |
| **P2** | Lặp lại | Khi chạy một dự án Python trong môi trường mới, tôi muốn thiết lập đúng phiên bản và thư viện, để chương trình chạy ổn định mà không phải sửa đi sửa lại lỗi cấu hình. | Sinh viên thực hành lập trình. | **Đầu ra kiểm tra được:** phiên bản Python, danh sách gói cài đặt, log lần chạy đầu và số lỗi trước khi chạy thành công. **Mốc phân tích giả định:** 60 phút/lần thiết lập. |
| **P3** | Tốn thời gian | Khi chuẩn bị chạy ResNet18 trên tập ảnh ISIC 2017 trong Google Colab, tôi muốn xác minh dữ liệu, nhãn và đường dẫn đã đúng, để không làm gián đoạn thí nghiệm vì lỗi chuẩn bị. | Sinh viên thực hành học máy. | **Đầu ra kiểm tra được:** cấu trúc thư mục ảnh, tệp nhãn, notebook và traceback nếu có. **Mốc phân tích giả định:** 90 phút cho toàn bộ khâu chuẩn bị/chạy thử, không tính train chính thức. |
| **P4** | Tốn thời gian | Khi có tài liệu PDF scan viết tay cần chuyển sang Word, tôi muốn giữ đúng nội dung gốc, để có bản văn bản chỉnh sửa được mà không phải nhập lại quá nhiều hoặc bỏ sót thông tin. | Sinh viên xử lý tài liệu học tập. | **Đầu ra kiểm tra được:** bản PDF nguồn và bản Word, số trang, số lỗi khi đối chiếu. **Mốc phân tích giả định:** 85 phút/tài liệu cùng độ dài. |
| **P5** | Cần đọc, tổng hợp nhiều thông tin | Khi hoàn thành thí nghiệm học máy, tôi muốn tập hợp đúng các chỉ số đánh giá từ kết quả chạy, để gửi báo cáo rõ ràng và không nhầm lẫn giữa các lần thí nghiệm. | Sinh viên thực hiện nghiên cứu AI. | **Các trường cần đối chiếu:** accuracy, precision, recall, F1-score; kèm tập đánh giá và phiên bản thí nghiệm. **Mốc phân tích giả định:** 70 phút/báo cáo. |
| **P6** | Pain từ người khác | Khi làm bài nhóm có nhiều đầu việc phụ thuộc nhau, tôi muốn biết nhiệm vụ nào đang được phụ trách và nhiệm vụ nào chưa hoàn tất, để hạn chế trùng công việc hoặc bỏ sót trước hạn nộp. | Thành viên nhóm học tập. | **Quan sát kiểm chứng được:** bài Day 02 quy định nhóm 3–4 người và có cả báo cáo cá nhân lẫn báo cáo nhóm. **Giả thuyết cần kiểm chứng với người thật:** việc đối chiếu tiến độ có thể mất 40 phút/tuần. |

**Diễn giải dấu hiệu:** Số lượng checkpoint, loại file và các trường dữ liệu là những đặc điểm của công việc, **không tự chứng minh** đã có người mất đúng thời gian hoặc từng gặp lỗi. Các mốc phút trong bảng là ước lượng để đặt câu hỏi, chọn hướng nghiên cứu và xây dựng metric; không phải số liệu phỏng vấn, khảo sát hay kết quả đo cá nhân. Khi chuyển sang CP4, nhóm phải kiểm chứng bằng hành vi và bằng chứng thực tế.

### 2.3. Nhận xét và lựa chọn sơ bộ

- **P1** nổi bật ở việc thông tin phân tán và cần đối chiếu nhiều tài liệu. Đây là vấn đề có phạm vi nhỏ: từ khi nhận link repo đến khi lập xong checklist các yêu cầu bắt buộc. Dễ phân biệt giữa việc *đọc được nội dung* và *xác định đúng việc cần làm*.
- **P2** và **P3** cùng liên quan đến lỗi kỹ thuật, nhưng P3 cụ thể hơn vì giới hạn trong chuẩn bị dữ liệu và notebook cho một thí nghiệm.
- **P4** khác với việc chỉ rút ngắn thời gian thao tác: chất lượng nội dung sau chuyển đổi phải được giữ ổn định, nếu không giải pháp có thể gây hại hơn lợi.
- **P5** có nguy cơ trộn số liệu từ train, validation và test hoặc từ nhiều lần chạy; điều này phù hợp với một quy trình kiểm tra và chuẩn hóa báo cáo.
- **P6** liên quan đến nhiều thành viên nhưng cần tín hiệu từ chính người tham gia để xác định mức độ thường xuyên và hậu quả của vấn đề, không suy ra từ quy định làm việc nhóm.

Từ các tiêu chí **actor rõ**, **quy trình vẽ được**, **bottleneck cụ thể**, **tác động đo được** và **phạm vi vừa sức**, ba ứng viên được đưa vào CP2 là **P1, P3 và P4**. Đây là quyết định chọn vấn đề để phân tích sâu, **chưa phải quyết định triển khai AI**.

### 2.4. Vai trò của AI trong bước scan

ChatGPT được dùng để rà soát cách diễn đạt, kiểm tra xem Job Story đã nói về khó khăn của người dùng hay đang mô tả sẵn giải pháp, đồng thời nêu các lỗ hổng trong bằng chứng. Các gợi ý được xử lý như sau:

| Gợi ý được xem xét | Xử lý | Lý do |
|---|---|---|
| Tách việc đọc nhiều file và việc đối chiếu yêu cầu của bài lab | Giữ | Hai hoạt động có thể có thời gian và nguyên nhân chậm khác nhau. |
| Giới hạn vấn đề Colab ở chuẩn bị và kiểm tra đầu vào, không gộp cả quá trình nghiên cứu mô hình | Giữ | Làm rõ phạm vi, bottleneck và cách đo. |
| Tạo một trợ lý AI tự làm toàn bộ bài tập, lập trình và nộp bài | Loại | Đây là solution quá rộng, chưa chỉ ra pain thực tế hay giới hạn trách nhiệm. |

**Kết luận CP1:** Có sáu candidate problem theo bốn lăng kính; ba candidate được chuyển sang CP2. Các con số thời gian chỉ là giả định phân tích, còn các nhận định về tần suất và mức độ ảnh hưởng cần được kiểm chứng bằng hành vi thật ở bước nghiên cứu tiếp theo.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### 3.1. Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| **1** | **P1 — Xác định yêu cầu bài lab từ nhiều file GitHub** | Actor cụ thể, quy trình bắt đầu/kết thúc rõ, dễ kiểm tra với repo thật; có thể so sánh hiệu quả checklist với cách đọc thủ công. | Bước nghẽn là tìm file, hiểu câu chữ hay đối chiếu yêu cầu bắt buộc? |
| **2** | **P3 — Chuẩn bị dữ liệu và notebook ResNet18 trên Colab** | Tác vụ kỹ thuật có log và đầu ra rõ; bottleneck có thể cô lập ở khâu cấu hình trước train. | Lỗi xuất hiện do đường dẫn, tập dữ liệu, dependency hay thao tác người dùng? |
| **3** | **P4 — Chuyển PDF scan viết tay sang Word** | Có đầu vào và đầu ra so sánh được; metric cần phản ánh cả thời gian lẫn độ trung thực của nội dung. | Khâu nhập nội dung hay khâu rà soát bản Word mới thực sự mất thời gian nhất? |

**Quy ước thống nhất:** Toàn bộ thời gian ở ba sơ đồ dưới đây là một **kịch bản ước lượng tham chiếu** cho mỗi lần thực hiện công việc, không phải dữ liệu đã đo; mỗi tổng được tính từ thời gian từng bước. **Baseline** là mốc giả định để thiết kế cách đánh giá; **target** là mục tiêu đề xuất, không phải kết quả cải thiện đã đạt.

### 3.2. Problem Card #1 — Xác định đầy đủ yêu cầu bài lab GitHub

| Trường | Nội dung |
|---|---|
| **Job Story** | Khi nhận một bài lab có yêu cầu nằm trong nhiều file GitHub, tôi muốn xác định đúng các nhiệm vụ, file phải hoàn thành và tiêu chí chấm, để lập kế hoạch thực hiện không bỏ sót việc. |
| **Actor** | Sinh viên CNTT vừa nhận repository hướng dẫn bài lab. |
| **Thời điểm / bối cảnh** | Từ khi mở link repository đến khi có checklist công việc trước khi bắt đầu bài. |
| **Quy trình hiện tại (6 bước)** | (1) Mở repository; (2) đọc `README.md`; (3) tìm các file hướng dẫn liên quan; (4) đối chiếu checkpoint, rubric, submission; (5) ghi checklist; (6) rà soát checklist với nguồn gốc. |
| **Bottleneck** | **Bước 4 — đối chiếu yêu cầu giữa các file: 20 phút/lần (ước lượng)**. Đòi hỏi phân biệt tài liệu tham khảo với đầu ra bắt buộc và điều kiện chấm. |
| **Impact** | Mất thời gian đọc lại tài liệu; có nguy cơ bỏ sót mục bắt buộc hoặc sửa sai file; ảnh hưởng tiến độ và chất lượng nộp bài. |
| **Success metric (baseline → target)** | **Thời gian lập checklist:** 65 → 30 phút/lần (**giả định → mục tiêu**). **Độ bao phủ yêu cầu:** mục tiêu 100% yêu cầu bắt buộc được liệt kê và gắn đúng file. **Cách đo:** bấm giờ từ khi mở repo đến khi checklist hoàn tất; đối chiếu checklist với `CHECKPOINTS.md`, `RUBRIC.md`, `SUBMISSION.md`. |
| **Phương án không dùng AI** | Checklist theo checkpoint và mapping `yêu cầu → tài liệu nguồn → file đầu ra → trạng thái`, liên kết trực tiếp đến vị trí hướng dẫn. |
| **Giả thuyết về AI (nếu có)** | AI có thể hỗ trợ soạn checklist sơ bộ từ tài liệu, nhưng sinh viên phải xác minh từng yêu cầu bằng file nguồn; không tự tạo nội dung bài hay tự nộp. |
| **Cảm nhận nhanh** | **Rule hoặc Workflow, chưa chốt.** Thử checklist có cấu trúc trước, vì có thể đủ giải quyết phần lớn khó khăn. |

**Quy trình nháp hiện tại — tổng 65 phút/lần (ước lượng):**

```mermaid
flowchart TD
    A["1. Mở repository<br/>5 phút"] --> B["2. Đọc README<br/>10 phút"]
    B --> C["3. Tìm file hướng dẫn<br/>15 phút"]
    C --> D["4. Đối chiếu yêu cầu, rubric, submission<br/>20 phút — BOTTLENECK"]
    D --> E["5. Lập checklist<br/>10 phút"]
    E --> F["6. Rà soát checklist<br/>5 phút"]
    style D fill:#ffe2e2,stroke:#b91c1c,stroke-width:2px,color:#111111
```

**Lý do chọn bước nghẽn:** Đọc được từng file không đồng nghĩa đã biết chính xác phải nộp gì. Bước 4 là điểm kết nối các yêu cầu phân tán thành một bộ nhiệm vụ hoàn chỉnh; nếu đối chiếu sai, checklist tạo ở bước sau cũng sai. **Boundary của vấn đề:** chỉ xét việc xác định yêu cầu, không xét việc tự hoàn thành bài bằng công cụ.

### 3.3. Problem Card #2 — Chuẩn bị thí nghiệm ResNet18 trên Google Colab

| Trường | Nội dung |
|---|---|
| **Job Story** | Khi chuẩn bị chạy ResNet18 với dữ liệu ISIC 2017 trên Colab, tôi muốn kiểm tra chính xác cấu trúc dữ liệu, đường dẫn và thiết lập môi trường, để thí nghiệm không bị gián đoạn vì lỗi đầu vào. |
| **Actor** | Sinh viên thực hành huấn luyện mô hình phân loại ảnh trong notebook Colab. |
| **Thời điểm / bối cảnh** | Sau khi có dữ liệu và trước khi bắt đầu huấn luyện đầy đủ. |
| **Quy trình hiện tại (6 bước)** | (1) Kiểm tra các thành phần dataset; (2) tải/giải nén; (3) kết nối nơi lưu trữ và khai báo đường dẫn; (4) kiểm tra ảnh/nhãn, sửa lỗi cấu hình; (5) chạy thử một batch; (6) xác nhận trạng thái sẵn sàng train. |
| **Bottleneck** | **Bước 4 — kiểm tra dữ liệu và sửa lỗi cấu hình: 30 phút/lần (ước lượng)**. Lỗi đường dẫn hoặc không khớp file ảnh/nhãn có thể khiến quy trình dừng. |
| **Impact** | Tăng thời gian chuẩn bị, phải chạy lại notebook; rủi ro sử dụng nhầm đường dẫn hoặc đầu vào không đúng, làm thí nghiệm thiếu tin cậy. |
| **Success metric (baseline → target)** | **Thời gian chuẩn bị và chạy thử:** 90 → 45 phút/lần (**giả định → mục tiêu**), **không bao gồm thời gian train chính thức**. Mục tiêu 0 lỗi cấu trúc/đường dẫn ở lần chạy preflight. **Cách đo:** ghi thời điểm bắt đầu/kết thúc khâu chuẩn bị và đếm lỗi trước khi train. |
| **Phương án không dùng AI** | Notebook mẫu, cấu trúc thư mục thống nhất, cấu hình tập trung, checklist preflight kiểm tra file ảnh/nhãn, split và một batch dữ liệu. |
| **Giả thuyết về AI (nếu có)** | AI giúp diễn giải traceback hoặc gợi ý bước kiểm tra; người dùng xác nhận mọi thay đổi và không để AI tự chạy huấn luyện hoặc xử lý file dữ liệu ngoài phạm vi. |
| **Cảm nhận nhanh** | **Rule** có thể đủ dùng: mã kiểm tra đầu vào tự động trước train. |

**Quy trình nháp hiện tại — tổng 90 phút/lần chuẩn bị (ước lượng):**

```mermaid
flowchart TD
    A["1. Kiểm tra thành phần dataset<br/>10 phút"] --> B["2. Tải và giải nén<br/>15 phút"]
    B --> C["3. Kết nối lưu trữ, khai báo path<br/>15 phút"]
    C --> D["4. Kiểm tra đầu vào và sửa cấu hình<br/>30 phút — BOTTLENECK"]
    D --> E["5. Chạy thử một batch<br/>15 phút"]
    E --> F["6. Xác nhận sẵn sàng train<br/>5 phút"]
    style D fill:#ffe2e2,stroke:#b91c1c,stroke-width:2px,color:#111111
```

**Lý do chọn bước nghẽn:** Một lỗi dữ liệu/cấu hình trước khi train không thể giải quyết bằng việc thay kiến trúc ResNet18. Vì vậy nhiệm vụ cần thu hẹp vào **preflight của notebook**, không đồng nhất với bài toán nâng accuracy, cũng không lấy thời gian GPU train làm thời gian thao tác của người dùng.

### 3.4. Problem Card #3 — Chuyển PDF scan viết tay sang Word mà vẫn đúng nội dung

| Trường | Nội dung |
|---|---|
| **Job Story** | Khi có tài liệu viết tay dưới dạng PDF scan cần chỉnh sửa trong Word, tôi muốn chuyển đổi mà vẫn giữ chính xác nội dung gốc, để giảm nhập lại thủ công và dùng được tài liệu cho học tập. |
| **Actor** | Sinh viên cần chuyển tài liệu scan để soát lỗi, chỉnh sửa hoặc trích xuất nội dung. |
| **Thời điểm / bối cảnh** | Từ lúc có bản PDF scan đến khi tạo xong bản Word đã kiểm tra. |
| **Quy trình hiện tại (5 bước)** | (1) Kiểm tra chất lượng scan; (2) nhập hoặc trích xuất nội dung; (3) đối chiếu và sửa lỗi; (4) định dạng Word; (5) kiểm tra cuối và lưu file. |
| **Bottleneck** | **Bước 3 — đối chiếu và sửa lỗi chữ viết tay: 30 phút/tài liệu (ước lượng)**, nhất là từ khó đọc, con số và ký hiệu. |
| **Impact** | Mất công nhập liệu; lỗi nội dung có thể gây sai lệch khi phân tích; phải rà soát nhiều vòng trước khi sử dụng. |
| **Success metric (baseline → target)** | **Thời gian hoàn tất một tài liệu cùng số trang:** 85 → 45 phút (**giả định → mục tiêu**). **Chất lượng:** mục tiêu tỷ lệ từ sai sau kiểm tra ≤2% trên mẫu so khớp với bản gốc. **Cách đo:** bấm giờ, đếm số từ sai chia cho tổng số từ được kiểm tra, giữ nguyên tài liệu mẫu. |
| **Phương án không dùng AI** | Nhập tay theo từng trang; đánh dấu vị trí khó đọc; checklist soát số, tên riêng, ký hiệu và đoạn bỏ sót; kiểm tra lại với bản gốc. |
| **Giả thuyết về AI (nếu có)** | Nhận dạng chữ viết tay tạo bản nháp, sau đó người dùng kiểm tra thủ công và phê duyệt; các đoạn mơ hồ phải được đánh dấu, không tự đoán nội dung. |
| **Cảm nhận nhanh** | **Workflow có người soát**, chỉ cân nhắc sau khi so với phương án thủ công hoặc công cụ nhận dạng có sẵn. |

**Quy trình nháp hiện tại — tổng 85 phút/tài liệu (ước lượng):**

```mermaid
flowchart TD
    A["1. Xem và chuẩn bị bản scan<br/>10 phút"] --> B["2. Nhập/trích xuất nội dung<br/>20 phút"]
    B --> C["3. Đối chiếu và sửa lỗi<br/>30 phút — BOTTLENECK"]
    C --> D["4. Định dạng Word<br/>15 phút"]
    D --> E["5. Kiểm tra cuối và lưu file<br/>10 phút"]
    style C fill:#ffe2e2,stroke:#b91c1c,stroke-width:2px,color:#111111
```

**Lý do chọn bước nghẽn:** Khả năng chỉnh sửa văn bản không có ý nghĩa nếu tài liệu sau chuyển đổi sai so với bản gốc. Vì thế bottleneck được đặt ở đối chiếu, và metric phải gồm **độ chính xác** chứ không chỉ thời gian. Phạm vi không bao gồm tự diễn giải hoặc viết lại nội dung tác giả.

### 3.5. Card muốn pitch nhất

- **Card số:** **#1 — Xác định yêu cầu bài lab từ nhiều file GitHub.**
- **Vì sao chọn:** Có actor và thời điểm rõ, có thể kiểm tra trực tiếp trên một repo công khai và đánh giá checklist theo hai chỉ số độc lập: thời gian tạo và độ bao phủ yêu cầu. Chi phí kiểm chứng thấp, đồng thời có phương án No AI đủ mạnh để so sánh trước khi tăng mức tự động hóa.
- **Câu hỏi muốn nhóm phản biện:** **“Nếu checklist chuẩn kèm liên kết đến các file gốc đã giúp sinh viên xác định đủ yêu cầu, bước nào vẫn thật sự cần can thiệp bằng AI?”**

### 3.6. AI đã phản biện card thế nào?

**Công cụ:** ChatGPT. **Vai trò phản biện:** Product Manager hoài nghi. **Trọng tâm:** Tính cụ thể của actor, tính thực tế của bước nghẽn, sự nhất quán của metric và khả năng giải quyết không cần AI. Đây là phần ghi nhận phản biện đối với **bản phân tích**, không thay cho khảo sát hay phỏng vấn người dùng.

**Prompt phản biện đã dùng để xây dựng bản chỉnh lý:**

> Hãy đóng vai Product Manager hoài nghi. Với ba Problem Card về (1) đọc yêu cầu lab GitHub, (2) chuẩn bị dữ liệu/Colab trước khi train ResNet18 và (3) chuyển PDF scan viết tay sang Word, hãy tìm lỗ hổng trong actor, quy trình, bottleneck, tác động, baseline, target, cách đo và phương án không dùng AI. Chỉ nêu điểm yếu; không tự tạo người dùng hoặc số liệu đo đạc.

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì trong bản này |
|---|---|---|
| Dùng số phút ước lượng như dữ liệu thực đo sẽ tạo bằng chứng không trung thực. | Có | Thống nhất nhãn **giả định → mục tiêu**, nêu rõ cách đo và không tuyên bố đã đạt target. |
| Card #1 dễ gộp việc đọc file với việc đối chiếu yêu cầu giữa nhiều nguồn. | Có | Tách bước tìm tài liệu (**bước 3**) và bước đối chiếu (**bước 4**); xác định bước 4 là bottleneck giả định. |
| Card #2 có thể tính nhầm cả thời gian huấn luyện GPU vào pain của người chuẩn bị. | Có | Giới hạn baseline/target ở **khâu chuẩn bị và chạy thử**. |
| Card #3 chỉ rút ngắn thời gian mà không kiểm soát lỗi là success metric chưa đầy đủ. | Có | Bổ sung tỷ lệ từ sai ≤2% sau kiểm tra trên mẫu cố định. |
| Việc đề xuất AI sớm có thể che khuất giải pháp đơn giản hơn. | Có | Nêu phương án **No AI** cho cả ba, chỉ để AI ở dạng giả thuyết và chưa chọn Agent. |

**Đánh giá sau phản biện:** Các card đã tách rõ nhu cầu, quy trình, bottleneck, tác động, thước đo và giải pháp không dùng AI. Điều chỉnh đáng kể nhất là chuyển **bước đối chiếu yêu cầu** thành bottleneck giả định của P1, thay vì gọi chung việc “đọc GitHub” là bước chậm; đồng thời bổ sung ràng buộc chất lượng cho P4.

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

Sau khi nhóm tổng hợp các Problem Card ở CP3, bài toán chung được ưu tiên là **đối chiếu yêu cầu và tiêu chí bài lab từ nhiều file trong repository GitHub**. Trong nhóm, phần việc tôi được phân công là **CP4 – Kiểm chứng vấn đề và nghiên cứu giải pháp hiện có**. Tôi không phụ trách chính việc lập bảng Pitch, OST ở CP3; xây dựng quy trình và Problem Statement ở CP5; hoặc lựa chọn mức can thiệp AI ở CP6. Phạm vi đóng góp được mô tả dưới đây dựa trên những nội dung CP4 hiện có trong báo cáo nhóm.

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Báo cáo cá nhân ở mục 3 có ba card: tổng hợp yêu cầu lab trên GitHub, chuẩn bị dữ liệu/môi trường Colab, chuyển PDF scan sang Word. Các card này là đầu vào cho quá trình hội tụ vấn đề của nhóm; tôi không nhận phần tổng hợp bảng Pitch là công việc mình phụ trách. | Nhóm có thêm candidate về việc tổng hợp và đối chiếu yêu cầu từ nhiều nguồn; xem `report/team/group_report.md` mục 2.1. |
| Chọn candidate problem | Tôi theo bài toán chung được trình bày trong CP3 để xây dựng nội dung kiểm chứng CP4, không ghi mình là người đơn phương quyết định. | CP4 tập trung vào sinh viên đọc và đối chiếu yêu cầu bài lab từ các file GitHub. |
| Kiểm chứng / research | **Phần phụ trách CP4:** xây dựng Assumption Map sáu giả định; rà soát các file hướng dẫn lab; chuẩn bị bộ câu hỏi phỏng vấn và mẫu Interview Snapshot; nghiên cứu GitHub Code Search, VS Code Search và GitHub Copilot Chat. | Báo cáo nhóm mục 3.1–3.3 gồm bảng giả định, kế hoạch kiểm chứng, bằng chứng tài liệu và so sánh ba giải pháp hiện có. |
| Mức can thiệp AI | Không phụ trách CP6. Trong CP4 tôi chỉ so sánh công cụ hiện có với cách tìm kiếm/checklist không dùng AI. | Nhóm có cơ sở đánh giá No AI/Rule trước khi quyết định Workflow hay Agent. |

### Phần tôi tập trung khi làm CP4

| Nội dung CP4 | Tôi tập trung làm rõ điều gì? | Bằng chứng trong báo cáo nhóm |
|---|---|---|
| Assumption Map | Phân loại sáu giả định về giá trị, khả năng sử dụng, khả thi và tính bền vững; xác định giả định nào cần kiểm chứng trước. | Mục 3.1 – bảng sáu giả định và độ ưu tiên. |
| Desk review | Đối chiếu `README.md`, `CHECKPOINTS.md`, `RUBRIC.md`, `SUBMISSION.md` để xác định những thông tin nằm ở các tài liệu khác nhau. | Mục 3.2 – bảng kiểm tra cấu trúc và nguồn tài liệu. |
| Kế hoạch kiểm chứng | Chuẩn bị câu hỏi hỏi về **lần làm lab gần nhất**, quy trình hiện tại, thời gian, việc bỏ sót và công cụ đang sử dụng; chuẩn bị mẫu Interview Snapshot. | Mục 3.2 – bộ câu hỏi và mẫu snapshot. |
| Giới hạn bằng chứng | Không dùng thời gian ước lượng trong CP2 như kết quả phỏng vấn; không suy diễn rằng tài liệu nằm ở nhiều file tức là sinh viên chắc chắn gặp khó khăn. | Mục 3.2 – bảng tổng hợp bằng chứng và ghi chú thiếu dữ liệu người dùng ngoài nhóm. |
| Nghiên cứu giải pháp | So sánh GitHub Code Search, VS Code Search, GitHub Copilot Chat; xác định khâu công cụ hỗ trợ và khâu người học vẫn phải tự đối chiếu. | Mục 3.3 – bảng research, đường dẫn tài liệu và giới hạn giải pháp. |

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Hỗ trợ diễn đạt các vấn đề theo Job Story và phân biệt vấn đề với giải pháp. | Gợi ý mô tả rõ actor, tình huống, mục tiêu và tác động có thể quan sát. | AI không biết số lần hoặc thời gian thực tế xảy ra vấn đề của cá nhân. | Giữ các mốc phút ở trạng thái **ước lượng**, không ghi là bằng chứng đã đo. |
| CP2 Problem Card | Rà soát ba Problem Card; đề xuất tách bước, làm rõ bottleneck, metric và phương án không AI. | Nhận ra cần tách tìm file với đối chiếu tiêu chí; phải đo cả chất lượng bên cạnh thời gian. | AI có thể kết luận quá sớm về bottleneck hoặc gợi ý dùng Agent khi chưa có dữ liệu. | Chỉ ghi bottleneck là giả thuyết; bổ sung checklist/Rule như phương án đối chứng. |
| CP4 Research | Hỗ trợ sắp xếp Assumption Map, xây dựng câu hỏi phỏng vấn và hệ thống tiêu chí so sánh ba công cụ. | Giúp định nghĩa rõ điều gì có thể đọc từ tài liệu và điều gì bắt buộc hỏi người dùng. | Không thể giả lập phản hồi phỏng vấn thật; đánh giá tính năng công cụ không đồng nghĩa với đo được hiệu quả thực tế. | Chỉ ghi nhận nghiên cứu tài liệu và kế hoạch kiểm chứng; đối chiếu nguồn chính thức và không tự tạo dữ liệu người tham gia. |
| CP5 Quy trình | Không phụ trách CP5 và không nhận là phần việc sử dụng AI của mình. | — | — | Để thành viên phụ trách ghi lại cách họ dùng AI. |
| CP5–6 Problem Statement | Không phụ trách viết Problem Statement v0/v1. | — | — | Không nhận đóng góp của thành viên khác. |
| CP6 Mức can thiệp / quyết định | Không phụ trách lựa chọn AI hoặc quyết định Go / Not Yet / No-Go. | — | — | CP4 chỉ cung cấp dữ kiện và giới hạn kiểm chứng để nhóm tham khảo. |


## 6. Reflection (CP7)

### 6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?

Qua việc tìm hiểu các Problem Card của các thành viên trong nhóm, tôi nhận ra rằng mỗi người có cách nhìn nhận và xác định vấn đề khác nhau. Có những vấn đề liên quan đến quản lý thời gian, theo dõi deadline, kiểm tra bài nộp và tổng hợp thông tin từ nhiều nguồn.

Tôi hiểu rằng một vấn đề đáng giải quyết không nhất thiết phải phức tạp mà quan trọng là xác định đúng người gặp khó khăn, nguyên nhân và tác động thực tế. Việc so sánh các vấn đề giúp tôi học được cách đánh giá tính khả thi, mức độ ảnh hưởng và khả năng kiểm chứng trước khi lựa chọn bài toán chung.

### 6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?

Trong quá trình phân tích bài toán tổng hợp yêu cầu bài Lab từ nhiều nguồn, tôi nhận thấy rất dễ nghĩ ngay đến việc sử dụng AI hoặc chatbot để giải quyết. Tuy nhiên, việc lựa chọn công nghệ quá sớm có thể khiến nhóm bỏ qua nguyên nhân thực sự của vấn đề.

Vì vậy, hướng phân tích phù hợp là tập trung vào quy trình hiện tại, xác định bước gây khó khăn và xem xét các phương án đơn giản như checklist hoặc công cụ tìm kiếm trước. Điều này giúp tách biệt việc xác định vấn đề với việc lựa chọn giải pháp.

### 6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.

Một điểm khiến tôi cần xem xét lại là giả định sinh viên mất nhiều thời gian chủ yếu vì phải đọc nhiều file hướng dẫn trên GitHub.

Khi phân tích sâu hơn, tôi nhận thấy việc đọc nhiều file chưa chắc là bottleneck chính; khó khăn cũng có thể nằm ở bước đối chiếu yêu cầu giữa README, tài liệu hướng dẫn và tiêu chí chấm điểm.

Vì vậy, thay vì mặc định bước đọc tài liệu là nguyên nhân, tôi chuyển sang xem xét riêng từng bước trong quy trình và xác định những thông tin cần kiểm chứng. Điều này giúp giả định trở nên cụ thể và có khả năng đo lường hơn.

### 6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?

Điểm đáng chú ý nhất khi thực hiện nghiên cứu CP4 là đã có những công cụ hỗ trợ tìm kiếm và tổng hợp thông tin, chẳng hạn như GitHub Search, VS Code Search và GitHub Copilot Chat.

Ban đầu, việc thông tin phân tán trong nhiều file có vẻ là lý do để xây dựng thêm một công cụ AI. Tuy nhiên, các giải pháp hiện có cho thấy nhóm cần làm rõ những hạn chế chưa được giải quyết trước khi đề xuất hệ thống mới.

Phần research giúp tôi hiểu rằng không phải vấn đề nào liên quan đến nhiều thông tin cũng cần Agent. Với dữ liệu hiện có, nhóm chưa thể dùng kết quả phỏng vấn hoặc khảo sát để khẳng định mức độ phổ biến của vấn đề.

### 6.5. Điều khó nhất khi viết Problem Statement là gì?

Theo tôi, khó khăn lớn nhất là xác định chính xác bottleneck và xây dựng Success Metric có thể đo lường.

Nếu chỉ mô tả rằng sinh viên mất nhiều thời gian đọc tài liệu thì vấn đề vẫn còn chung chung và khó đánh giá. Cần chỉ rõ sinh viên gặp khó khăn ở bước nào, hậu quả là gì và thế nào được xem là cải thiện.

Qua phần CP4, tôi cũng nhận thấy các số liệu ước lượng không thể thay thế bằng chứng thực tế. Vì vậy, Problem Statement cần được xây dựng trên các giả định rõ ràng, sau đó cập nhật khi có kết quả kiểm chứng đáng tin cậy.

### 6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?

Nếu thực hiện lại, tôi sẽ ưu tiên xây dựng kế hoạch kiểm chứng ngay sau khi nhóm lựa chọn vấn đề.

Tôi sẽ tập trung tìm hiểu trải nghiệm gần nhất của người dùng, cách họ đang xử lý công việc và những khó khăn thực sự phát sinh.

Ngoài ra, tôi sẽ đặt nhiều câu hỏi hơn về tính cần thiết của AI, chẳng hạn:

- Các công cụ hiện có đã giải quyết được phần nào?
- Có thể sử dụng checklist hoặc Rule thay thế không?
- Nếu dùng AI thì rủi ro bỏ sót hoặc hiểu sai yêu cầu được kiểm soát như thế nào?

Điều này sẽ giúp nhóm đưa ra quyết định dựa trên bằng chứng thay vì cảm nhận.

### 6.7. Hiểu bài: Giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi problem → quy trình → metric → boundary → mức can thiệp AI → quyết định của bài nhóm mình.

Bài toán nhóm lựa chọn là sinh viên gặp khó khăn khi tổng hợp và đối chiếu yêu cầu bài Lab từ nhiều file tài liệu trên GitHub.

Quy trình hiện tại gồm đọc các file hướng dẫn, tìm yêu cầu bắt buộc, đối chiếu tiêu chí và tự lập checklist trước khi thực hiện.

Hiệu quả của quy trình có thể đánh giá thông qua thời gian hoàn thành checklist, số yêu cầu bị bỏ sót và độ chính xác của thông tin được tổng hợp.

Boundary cần bảo đảm rằng AI chỉ hỗ trợ trích xuất và gợi ý yêu cầu, còn sinh viên phải kiểm tra nguồn và chịu trách nhiệm quyết định cuối cùng.

Về mức can thiệp, nhóm có thể ưu tiên thử nghiệm Workflow với các bước cố định thay vì sử dụng Agent tự chủ.

Việc lựa chọn giải pháp phải được so sánh với No AI và Rule để xác định lợi ích thực tế.

Khi chưa có đủ dữ liệu kiểm chứng từ người dùng, quyết định phù hợp là tiếp tục thử nghiệm và đánh giá trước khi triển khai rộng rãi.


## 7. Tài liệu tham khảo

- [README](../../README.md)
- [Worksheet](../../docs/01-worksheet.md)
- [Rules](../../RULES.md)
