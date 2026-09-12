# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: 
- Mã học viên: 
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...):
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

| # | Lăng kính | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật |
|---|---|---|---|---|
| 1 | AI có thể tốt hơn | Lừa đảo tài chính qua cuộc gọi mạo danh đang rất tinh vi để ép chuyển tiền, hệ thống phòng vệ truyền thống bất lực trước SIM rác, VoIP. Cần một trợ lý AI chạy thời gian thực (Speech-to-Text, NLP/LLM) để phân tích ngữ cảnh, tính Risk Score và cảnh báo tự động. | Người dùng điện thoại, người thân có đăng ký nhận thông báo | Bị áp lực tâm lý, lộ OTP và mất tiền; các thủ đoạn mới thay đổi liên tục khiến bộ lọc từ khóa/danh sách đen vô dụng |
| 2 | Tốn thời gian | Tổng hợp các bài báo để tìm vấn đề. | Sinh viên, người làm nghiên cứu | Mất 2-3 tiếng/paper chỉ để tóm tắt và tìm ra limitation của bài báo. |
| 3 | Lặp lại | Tìm lại quyết định/câu trả lời cũ trong Discord hoặc group chat về việc phân công task đồ án hoặc cách thiết lập mạng riêng ảo (VPN)/kết nối server. | Các thành viên trong nhóm làm đồ án chung | Mất 10-15 phút lướt lại tin nhắn cũ mỗi khi cần cấu hình môi trường lập trình mới |
| 4 | Lặp lại | Nhắc việc định kỳ nhưng hay quên context, cụ thể là thao tác nhớ lịch và tiến hành gia hạn vé tháng xe buýt điện tử. | Người đi học/đi làm bằng phương tiện công cộng | Diễn ra đều đặn mỗi tháng một lần nhưng thỉnh thoảng vẫn bị trễ hạn, phải tốn tiền mua vé lượt |
| 5 | Tốn thời gian | Tổng hợp báo cáo tuần về các chỉ số độ chính xác, hiệu suất của mô hình đang huấn luyện từ nhiều bảng log hoặc nền tảng thử nghiệm khác nhau. | Người huấn luyện mô hình học máy | Mất 30-45 phút mỗi cuối tuần để copy/paste thủ công dữ liệu rời rạc vào một định dạng báo cáo chuẩn |
| 6 | Pain từ người khác | Hiểu task từ nhiều thread/tài liệu khi tiếp nhận các thiết bị phần cứng mới (như board mạch nhúng để chạy mô hình), do tài liệu cấu hình rải rác. | Sinh viên thực tập, kỹ sư phát triển | Tốn nửa ngày để setup xong môi trường; đồng đội thường xuyên phải hỗ trợ lại các bước cơ bản |
| 7 | AI có thể tốt hơn | Search kém trên documentation của các framework lập trình, kết quả trả về thường mập mờ, không khớp ngữ cảnh của đoạn code đang viết. | Lập trình viên | Mất 15 phút liên tục đổi từ khóa, phải thoát ra dùng công cụ tìm kiếm bên ngoài thay thế |
| 8 | Tốn thời gian | Gửi CV cho nhiều nơi, mỗi vị trí yêu cầu một trọng tâm khác nhau nên phải tìm hiểu mô tả công việc (JD) và tinh chỉnh, viết lại CV cho phù hợp với từng nơi. | Sinh viên, ứng viên tìm việc | Mất 45 phút - 1 tiếng cho mỗi lần nộp đơn chỉ để đối chiếu JD, chọn lọc lại các dự án/kỹ năng từ CV gốc và sửa cách diễn đạt; dễ bị sót các từ khóa quan trọng mà nhà tuyển dụng yêu cầu. |

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi: Đưa ra 8 vấn đề liên quan tới các lĩnh vực lừa đảo, học tập, công việc, thực tập
- Ý dùng được: Hầu hết các ý đều dùng được
- Ý bỏ vì không phải pain thật: Bỏ ý liên quan tới nộp hồ sơ dự giải.

**Self-check Phase 1:**
- [x] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [x] Dùng ít nhất 3/4 lăng kính
- [x] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Gửi CV cho nhiều nơi, mỗi vị trí yêu cầu một trọng tâm khác nhau nên phải tìm hiểu mô tả công việc (JD) và tinh chỉnh, viết lại CV cho phù hợp với từng nơi. | - Actor (ứng viên) và workflow rất rõ ràng (Đọc JD -> Lọc kỹ năng/dự án -> Viết lại diễn đạt -> Lưu PDF).<br>- Điểm nghẽn cực kỳ cụ thể (mất 45-60 phút chỉ để tinh chỉnh từ khóa cho 1 CV).<br>- Bài toán có scope gọn, dễ dàng so sánh giữa việc tự làm (No AI) và dùng AI đối chiếu JD. | AI có thể bịa (hallucinate) kỹ năng hoặc kinh nghiệm mà người dùng không có nếu đầu vào không được giới hạn chặt chẽ; khó đo lường ngay lập tức xem CV có tăng tỷ lệ qua vòng lọc hay không. |
| 2 | Lừa đảo tài chính qua cuộc gọi mạo danh đang rất tinh vi. Cần một trợ lý AI chạy thời gian thực để phân tích ngữ cảnh, tính Risk Score và cảnh báo tự động. | - Có giá trị thực tiễn và impact xã hội rất cao.<br>- Thể hiện cực kỳ rõ ranh giới giới hạn của hệ thống cũ (Rule-based/danh sách đen) và sự cần thiết của phân tích ngữ cảnh (Agent/AI). | Bài toán có scope khá rộng và phức tạp đối với một buổi lab; vấn đề độ trễ (latency) khi xử lý Speech-to-Text và LLM theo thời gian thực có thể là rào cản kỹ thuật. |
| 3 | Tổng hợp các bài báo để tìm vấn đề (Mất 2-3 tiếng/paper chỉ để tóm tắt và tìm ra limitation của bài báo). | - Nỗi đau có thật và lặp lại liên tục với tần suất cao.<br>- Workflow trích xuất thông tin rõ (Đọc Abstract -> Tìm kiếm phương pháp -> Rút trích Limitation).<br>- Có thể đo lường impact trực tiếp thông qua thời gian tiết kiệm được trên mỗi paper. | Khi đối mặt với các bài báo chuyên sâu có nhiều công thức toán học hoặc kiến trúc mô hình học máy phức tạp, AI đọc PDF có thể hiểu sai ngữ cảnh hoặc trích xuất sai bản chất của limitation. |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — [CV]

```text
Problem 1 câu: Gửi CV cho nhiều nơi tốn quá nhiều thời gian vì phải tinh chỉnh thủ công từng từ khóa, kỹ năng để khớp với mô tả công việc (JD) của từng vị trí.

Actor: Sinh viên năm 3-4 / mới tốt nghiệp ngành CNTT (Data/AI/Backend), đã có ít nhất 1-2 dự án hoặc kỳ thực tập để đưa vào CV.

Thời điểm / bối cảnh: Khi nộp hồ sơ xin việc, thực tập, cần tùy biến CV gốc cho phù hợp với yêu cầu cụ thể của từng công ty để vượt qua vòng lọc hồ sơ.

Current workflow 3-7 bước:
1. Đọc kỹ JD để xác định các từ khóa, kỹ năng và kinh nghiệm trọng tâm.
2. Mở file CV gốc (Word/Canva).
3. Rà soát lại toàn bộ dự án, kinh nghiệm đã làm để chọn lọc những ý liên quan đến JD.
4. Chỉnh sửa cách diễn đạt, viết lại các gạch đầu dòng (bullet points) để chứa các từ khóa từ JD.
5. Kiểm tra lại format và lưu thành file PDF mới.

Bottleneck: 
- Bottleneck chính (AI xử lý được): diễn đạt lại ý đã có sẵn cho khớp từ khóa JD.
- Rủi ro cần kiểm soát (AI không được tự xử lý): khi ứng viên thực sự thiếu kinh nghiệm khớp JD, AI dễ suy diễn/bịa — phải chặn bằng bước xác nhận của người dùng trước khi xuất.

Impact: Rút ngắn thời gian chuẩn bị một bộ hồ sơ, giúp ứng viên nộp được nhiều công ty hơn với chất lượng CV cao hơn.

Success metric: Giảm thời gian tạo CV từ 45-60' xuống <15', và tỷ lệ bullet do AI đề xuất được giữ nguyên/chỉnh nhẹ (không viết lại hoàn toàn) đạt >70% ở bước review.

Non-AI alternative: Tạo sẵn 3-4 phiên bản CV khác nhau cho các hướng công việc chung (ví dụ: một bản thiên về Data, một bản thiên về AI, một bản thiên về Backend), khi nộp chỉ cần chọn bản gần giống nhất (Rule/Process fix). Ngoài ra so sánh 2-3 JD thật cùng hướng (vd Data Analyst ở 3 công ty) → % từ khóa trùng nhau là bao nhiêu? Nếu overlap thấp (<50%) → xác nhận rule/process không đủ. Nếu cao → cân nhắc dừng ở non-AI fix.

AI hypothesis: AI có thể đối chiếu nội dung CV gốc và JD, tự động đề xuất những bullet points cần viết lại, và tạo bản nháp chứa các từ khóa phù hợp.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết

```text
CURRENT STATE — 50 phút

[Đọc JD: 5']
→ [Mở CV gốc: 2']
→ [Lọc dự án liên quan: 15']
→ [Viết lại gạch đầu dòng: 25']  <-- bottleneck
→ [Review & Xuất PDF: 3']

FUTURE STATE — 14 phút

[Input JD & CV gốc vào AI: 1']
→ [AI phân tích JD + CV gốc → xuất bullet đã viết lại, kèm chú thích từ khóa match từ JD: 5']
→ [Ứng viên review & edit: 7']  <-- human boundary
→ [Xuất PDF: 1']

Fallback: nếu AI draft sai ngữ cảnh hoặc "bịa" kỹ năng, ứng viên phải tự sửa lại nội dung hoặc dùng bản CV gốc.
```
---

#### Problem Card #2 — [Lừa đảo qua điện thoại]

```text
Problem 1 câu: Lừa đảo tài chính qua điện thoại sử dụng kịch bản mạo danh liên tục thay đổi, ép người dùng chuyển tiền hoặc cung cấp OTP, vượt qua các bộ lọc số điện thoại truyền thống.

Actor: Người dùng điện thoại (đặc biệt là người lớn tuổi, ít am hiểu công nghệ).

Thời điểm / bối cảnh: Nghe các cuộc gọi lạ, bị kẻ gian dọa nạt, tạo áp lực thời gian (giả danh công an, nhân viên ngân hàng, v.v.).

Current workflow 3-7 bước (Workflow phòng vệ hiện tại):
1. Nhận cuộc gọi từ số lạ.
2. Nghe nội dung cuộc gọi.
3. Người dùng tự đánh giá mức độ tin cậy dựa trên kinh nghiệm cá nhân.
4. Nếu nghi ngờ, cúp máy hoặc tìm cách tra cứu thông tin (tốn thời gian, lúc bị áp lực thường quên).
5. Nếu bị thuyết phục, thực hiện chuyển tiền/cung cấp OTP.
6. (Hệ thống) Các app chặn cuộc gọi chỉ cảnh báo dựa trên danh sách đen (Blacklist) đã bị báo cáo từ trước.

Bottleneck: Bước 3 (Tự đánh giá) phụ thuộc hoàn toàn vào tâm lý người dùng tại thời điểm đó, và bước 6 (Chặn theo Blacklist) luôn đi sau kẻ lừa đảo (không chặn được số mới/VoIP).

Impact: Ngăn chặn kịp thời các giao dịch lừa đảo, bảo vệ tài sản cho người dùng ngay tại thời điểm cuộc gọi diễn ra.

Success metric: Cảnh báo đúng các cuộc gọi lừa đảo kịch bản mới (chưa có trong blacklist) trong vòng 30-60 giây đầu tiên.

Non-AI alternative: Chặn hoàn toàn số lạ không có trong danh bạ (Rule) -> Ảnh hưởng đến các cuộc gọi giao hàng, công việc hợp lệ.

AI hypothesis: Chạy Speech-to-Text cục bộ để nghe hội thoại, dùng LLM phân tích ngữ cảnh (nhận diện các mẫu câu đe dọa, đòi OTP, đòi chuyển khoản), tính điểm rủi ro và cảnh báo trực tiếp trên màn hình cuộc gọi.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[ ] Workflow
[x] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — (Hệ thống phòng vệ hiện tại - Thụ động)

[Nhận cuộc gọi lạ]
→ [App check Blacklist (nếu có): 1']
→ [Người dùng nghe máy & bị thao túng tâm lý: 5-10']  <-- bottleneck (điểm mù bảo mật)
→ [Thực hiện giao dịch mất tiền]

FUTURE STATE — (Bảo vệ thời gian thực)

[Nhận cuộc gọi]
→ [AI Speech-to-Text & phân tích liên tục: 1-2']
→ [Phát hiện yếu tố đe dọa/OTP]
→ [AI phát cảnh báo trên màn hình/âm thanh: 0.1']  <-- AI boundary
→ [Người dùng quyết định cúp máy]

Fallback: Nếu AI sai (False Positive - cảnh báo nhầm cuộc gọi bình thường), người dùng vẫn có thể tiếp tục cuộc trò chuyện và tắt cảnh báo.
```

---

#### Problem Card #3 — [Đọc paper]

```text
Problem 1 câu: Đọc và tổng hợp tài liệu, bài báo nghiên cứu chuyên sâu mất quá nhiều thời gian chỉ để nắm bắt được kiến trúc mô hình và các điểm hạn chế (limitation) của nghiên cứu đó.

Actor: Sinh viên, người làm nghiên cứu.

Thời điểm / bối cảnh: Đọc tài liệu tham khảo để chuẩn bị làm tiểu luận, khóa luận, hoặc tạo slide báo cáo seminar.

Current workflow 3-7 bước:
1. Đọc phần Abstract và Introduction.
2. Đọc lướt phần Related Work.
3. Đọc kỹ phần Methodology (kiến trúc, phương pháp).
4. Tìm và đọc phần Conclusion / Future Work để rút ra limitation.
5. Ghi chú tóm tắt lại vào Notion/Word để đưa lên slide.

Bottleneck: Bước 3 (Đọc hiểu phương pháp) và Bước 4 (Tìm limitation) thường bị viết rải rác, ẩn ý trong bài, tốn nhiều thời gian đọc kỹ.

Impact: Tăng tốc độ duyệt tài liệu nghiên cứu, giúp sinh viên tập trung thời gian vào việc suy nghĩ giải pháp thay vì việc trích xuất thông tin.

Success metric: Giảm thời gian tổng hợp ý chính và limitation của một bài báo từ 120-180 phút xuống còn 20-30 phút.

Non-AI alternative: Chỉ đọc Abstract và Conclusion, bỏ qua phần phương pháp (Cách này làm giảm chất lượng hiểu biết).

AI hypothesis: AI có thể "đọc" toàn bộ PDF, trích xuất cấu trúc phương pháp và tóm tắt rõ ràng các limitation mà bài báo đã nêu hoặc ẩn ý.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — 150 phút

[Đọc Abstract/Intro: 15']
→ [Đọc Methodology: 90']  <-- bottleneck (đọc hiểu cấu trúc phức tạp)
→ [Tìm/Đọc Limitation: 30']
→ [Ghi chú tóm tắt: 15']

FUTURE STATE — 35 phút

[Upload PDF cho AI: 1']
→ [AI trích xuất Methodology & Limitation: 4']
→ [Sinh viên đọc bản tóm tắt của AI: 10']
→ [Sinh viên kiểm chứng lại bằng cách đọc nhanh các phần AI chỉ ra trong PDF: 15'] <-- human boundary
→ [Ghi chú lại ý cần thiết: 5']

Fallback: Nếu AI tóm tắt sai kiến trúc phương pháp hoặc hallucinate limitation không có trong bài, sinh viên phải quay về cách đọc truyền thống.
```
---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Card số 1
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Bài toán tùy biến CV có workflow rất thực tế (Đọc JD → Tìm ý → Viết lại) và điểm nghẽn (bottleneck) dễ định lượng: ứng viên thường mất khoảng 45-60 phút để chỉnh sửa từ khóa và cách diễn đạt cho một bản CV. Impact mang lại cực kỳ rõ rệt: giảm thiểu rủi ro bị loại bởi hệ thống lọc hồ sơ (ATS) và giúp ứng viên nộp được nhiều công ty hơn với chất lượng CV đồng đều trong thời gian ngắn.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
Câu 1: Ranh giới (boundary) giữa việc "AI giúp viết lại diễn đạt" và "AI bịa ra kỹ năng (hallucinate) mà ứng viên không có" nằm ở đâu, và làm sao để kiểm soát điều này trong thiết kế giải pháp?

Câu 2: Việc giảm thời gian chỉnh sửa CV (từ 60 phút xuống 15 phút) có thực sự dẫn đến việc tăng tỷ lệ đỗ phỏng vấn không, hay chỉ dẫn đến việc nộp rác (spam) nhiều CV hơn?
```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra: Actor quá rộng; CV gốc chưa rõ; bottleneck gộp vấn đề diễn đạt và nguy cơ AI bịa kinh nghiệm; metric chỉ đo thời gian; chưa có số liệu chứng minh template là chưa đủ; 3 bước AI có thể gộp thành một lệnh.
- Tôi đã sửa: Thu hẹp Actor về sinh viên năm 3–4 hoặc mới ra trường ngành CNTT, có 1–2 dự án. Định nghĩa CV gốc là bản tổng hợp đầy đủ. Tách bottleneck thành diễn đạt lại và kiểm chứng kinh nghiệm. Thêm metric chất lượng dựa trên tỷ lệ bullet được giữ sau review. So sánh với JD thực tế để đo overlap từ khóa, đồng thời gộp 3 bước AI thành một bước single-shot.

### Self-check nộp phần 01
- [x] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge
