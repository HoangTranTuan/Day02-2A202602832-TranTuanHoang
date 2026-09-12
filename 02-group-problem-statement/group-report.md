# 02 — Group Problem Statement (Bản nộp nhóm)

> Làm chung 1 bản, mỗi thành viên copy vào repo cá nhân. Đi theo Phase 3 → 6 trong `01-worksheet.md`. Nhóm chỉ chọn **candidate problem** ở Phase 3, viết Problem Statement sau khi validate + vẽ workflow.

## Thành viên nhóm

| STT | Họ và tên         | Mã học viên | Vai trò trong nhóm (VD: facilitator, workflow, research, writer) |
| --- | ----------------- | ----------- | ---------------------------------------------------------------- |
| 1   | Trần Tuấn Hoàng   |             | facilitator                                                      |
| 2   | Nguyễn Minh Ngọc  | 2A202602530 | workflow                                                         |
| 3   | Nguyễn Tiến Lượng | 2A202602378 | research                                                         |
| 4   | Lục Tiến Đạt      | 2A202602969 | writer                                                           |

**Candidate problem nhóm chọn (1 câu):**

---

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh của nhóm |
|---|---|---|---|---|---|
| 1 | Lục Tiến Đạt | Tự động hóa tóm tắt họp nhóm online và trích xuất Action Items | Thành viên nhóm đồ án môn học (3-5 sinh viên CS) | Họp xong không ghi chép; mất 20 phút nhắn hỏi lại "ai làm gì", bỏ sót 30% công việc. | Rất phổ biến trong làm việc nhóm, dễ triển khai AI để tự động hóa trích xuất task. |
| 2 | Lục Tiến Đạt | Tra cứu quyết định chốt deadline, format bài, quy chuẩn code trong nhóm chat | Thành viên nhóm đồ án môn học (3-5 sinh viên CS) | Mất 15-20 phút scroll lội 100+ tin nhắn rác/ngày để tìm lại thông tin đã chốt. | Nỗi đau có thật nhưng giải pháp có thể bị trùng lặp với tính năng search của các chat app, có thể làm thành dạng bot nội bộ. |
| 3 | Lục Tiến Đạt | Gom file, chuẩn hóa văn phong và định dạng Báo cáo đồ án nhóm | Người chịu trách nhiệm gom & nộp báo cáo | Tốn 3-4 tiếng cận deadline ghép 4-5 file lẻ, sửa lệch font/văn phong và đánh lại số hình ảnh. | Đánh trúng tâm lý "cực hình" của trưởng nhóm lúc sát giờ nộp, impact tiết kiệm thời gian rất rõ rệt. |
| 4 | Nguyễn Tiến Lượng | Thông tin báo lỗi từ team monitor gửi developer chưa đầy đủ | Dev, software, hardware, member đội monitor | Thiếu log/thiết bị/điều kiện gây lỗi khiến dev phải hỏi lại 2-3 lần, tốn thêm 10-20 phút/lỗi. | Vấn đề cực kỳ thực tế trong quy trình dev, workflow rõ ràng và tính khả thi để áp dụng AI điền form rất cao. |
| 5 | Nguyễn Tiến Lượng | Kiểm tra trạng thái hệ thống và log thủ công để phát hiện bất thường | Member trong đội monitor, software, hardware | Đọc và đối chiếu thủ công lặp lại 3-5 lần/ngày, mất tổng 30-60 phút/ngày. | Bottleneck rõ ràng nhưng có vẻ thiên về việc viết automation script (Rule-based) quét log định kỳ hơn là cần AI phân tích sâu. |
| 6 | Nguyễn Tiến Lượng | Tổng hợp daily note về tiến độ, vấn đề phát sinh và action item | PM, member đội software/hardware, monitor | Tốn 15-20 phút/lần thu thập và ghi chép thông tin thủ công (5 lần/tuần). | Tính lặp lại hàng ngày cao, dùng LLM tóm tắt trực tiếp sẽ tiết kiệm đáng kể effort quản lý. |
| 7 | Nguyễn Minh Ngọc | Chỉnh sửa CV và khớp key skill thủ công cho từng tin tuyển dụng | Fresher/Junior Dev mới tốt nghiệp | Tốn 45 phút/lần (làm 10-12 lần/tuần, ~8 tiếng/tuần) chủ yếu để đọc JD và chỉnh skill. | Nhu cầu thực tế rất lớn với người mới ra trường (trùng ý tưởng với Tuấn Hoàng bên dưới). Tuy nhiên cần giới hạn để CV giữ được tính trung thực. |
| 8 | Nguyễn Minh Ngọc | Debug lỗi phát sinh (NullPointer/Config) khi làm dự án cá nhân | Dev tự học / Sinh viên CNTT | Đọc log và tìm nguyên nhân thủ công mất 1.5-2 tiếng/lỗi (tần suất ~4 lần/tuần). | Nỗi đau chuẩn, nhưng hiện tại các tool như Copilot hay ChatGPT đã làm quá tốt việc này, khó tạo tính đột phá. |
| 9 | Nguyễn Minh Ngọc | Tra cứu và viết truy vấn SQL phức tạp (JOIN, Aggregation) | Sinh viên CNTT / Fresher Dev | Mất 20-30 phút cho 1 câu bài tập khó, phải tra Google/StackOverflow ~5 lần/ngày. | Vấn đề phổ biến ở sinh viên, nhưng dễ bị thay thế hoàn toàn bởi các công cụ GenAI lập trình hiện có. |
| 10 | Trần Tuấn Hoàng | Gửi CV cho nhiều nơi tốn quá nhiều thời gian vì phải tinh chỉnh thủ công từng từ khóa, kỹ năng để khớp với mô tả công việc (JD) của từng vị trí. | Sinh viên năm 3-4 / mới tốt nghiệp ngành CNTT (Data/AI/Backend), đã có ít nhất 1-2 dự án. | Mất 45-60 phút chỉ để tinh chỉnh từ khóa và diễn đạt lại ý cho khớp JD của 1 CV. | Ý tưởng cực tốt và sắc bén, rất thiết thực khi phải customize CV liên tục để apply vào các lab nghiên cứu chuyên sâu hay vị trí AI. Cần chú ý ranh giới để AI không tự "bịa" kỹ năng. |
| 11 | Trần Tuấn Hoàng | Lừa đảo tài chính qua điện thoại sử dụng kịch bản mạo danh thay đổi liên tục, ép chuyển tiền hoặc cung cấp OTP, vượt qua bộ lọc truyền thống. | Người dùng điện thoại (đặc biệt là người lớn tuổi, ít am hiểu công nghệ). | Tự đánh giá phụ thuộc tâm lý (5-10' bị thao túng); blacklist không chặn được số mới/VoIP. | Impact xã hội cực lớn. Hướng tiếp cận tối ưu mô hình nhận diện chạy trực tiếp cục bộ (Edge AI) để phân tích ngữ cảnh, giảm độ trễ là rất triển vọng nhưng rào cản kỹ thuật khá cao. |
| 12 | Trần Tuấn Hoàng | Đọc và tổng hợp tài liệu, bài báo nghiên cứu chuyên sâu mất quá nhiều thời gian chỉ để nắm bắt kiến trúc mô hình và các điểm hạn chế (limitation). | Sinh viên, người làm nghiên cứu. | Mất nhiều thời gian đọc kỹ (90' cho Methodology) vì phần phương pháp và limitation thường viết rải rác, ẩn ý. | Nỗi đau cực kỳ chân thực khi phải cày số lượng lớn paper phức tạp về mô hình học sâu hoặc kiến trúc mạng. Dễ dàng chứng minh tính hiệu quả bằng số giờ đọc được cắt giảm. |

### 3.2. Gom trùng / cluster (gom 9-12 ý thành 3-4 cụm)

| Cluster | Candidates included | Pattern chung | Ghi chú |
| --- | --- | --- | --- |
| **A (Quản lý giao tiếp & Tiến độ)** | 1, 2, 6 | Rút trích, tra cứu thông tin (action items, deadline, daily note) từ các luồng giao tiếp lộn xộn (tin nhắn, meeting) để quản lý tiến độ công việc. | Khả thi cao khi áp dụng LLM để tóm tắt văn bản không cấu trúc; giải quyết tốt sự lặp lại hàng ngày/tuần. |
| **B (Xử lý & Tùy biến tài liệu chuyên sâu)** | 3, 7, 10, 12 | Phải đọc hiểu lượng lớn văn bản (file đồ án, JD, paper), sau đó trích xuất thông tin, đối chiếu hoặc viết lại theo chuẩn mục tiêu. | Candidate 7 và 10 trùng lặp trực tiếp (CV). Nhóm này rất tiềm năng nếu kết hợp RAG để đối chiếu chính xác, tránh hallucination. |
| **C (Hỗ trợ Dev, Monitor & Anomaly Detection)** | 4, 5, 8, 9 | Đối chiếu log, thông báo lỗi, trạng thái hệ thống để phát hiện bất thường (anomaly) hoặc tìm hướng xử lý vấn đề kỹ thuật, code. | Workflow rõ ràng nhưng mảng debug/code dễ bị cạnh tranh bởi Copilot. Việc phân tích log hệ thống đặc thù sẽ ít bị đụng hàng hơn. |
| **D (Cảnh báo rủi ro thời gian thực)** | 11 | Phân tích luồng dữ liệu (âm thanh/văn bản) liên tục để nhận diện ngữ cảnh bất thường và phát cảnh báo tức thì. | Impact xã hội cao nhưng đòi hỏi kiến trúc tối ưu (ví dụ: mô hình ngôn ngữ nhỏ chạy cục bộ bằng Edge AI) để đảm bảo độ trễ cực thấp. |

### 3.3. Shortlist (giữ 2-3 bài trả lời được 7 câu hỏi worksheet)

| Candidate | Vì sao vào shortlist (2-3 ý) | Rủi ro / điều chưa rõ |
| --- | --- | --- |
| **Candidate 10 (Tinh chỉnh CV thủ công theo JD)** | - Workflow cực kỳ rõ ràng (Đọc JD -> Lọc kỹ năng -> Viết lại diễn đạt).<br>- Điểm nghẽn dễ định lượng (giảm từ 45-60 phút xuống dưới 15 phút).<br>- Impact thực tiễn cao, phục vụ tệp người dùng lớn (sinh viên mới ra trường/dev trẻ). | - Ranh giới kiểm soát để AI không "bịa" (hallucinate) kỹ năng ứng viên không có.<br>- Chưa rõ việc rút ngắn thời gian có thực sự tăng tỷ lệ pass hồ sơ hay chỉ dẫn đến việc spam CV. |
| **Candidate 12 (Trích xuất Limitation từ bài báo nghiên cứu)** | - Nỗi đau lặp lại liên tục với tần suất cao trong giới học thuật và nghiên cứu.<br>- Luồng trích xuất thông tin rất cụ thể (Abstract -> Methodology -> Limitation).<br>- Dễ dàng chứng minh tính hiệu quả bằng số giờ đọc được cắt giảm. | - Các bài báo chuyên sâu chứa nhiều công thức toán học/kiến trúc phức tạp có thể khiến công cụ đọc PDF phân tích sai ngữ cảnh.<br>- Rủi ro AI trích xuất sai bản chất hạn chế của mô hình. |
| **Candidate 4 (Thông tin báo lỗi từ team monitor thiếu chi tiết)** | - Vấn đề B2B rất thực tế trong quy trình phát triển phần mềm hàng ngày.<br>- Đầu vào (tin nhắn/log lộn xộn) và đầu ra (form báo lỗi chuẩn hóa) được định nghĩa rất chặt chẽ, cực kỳ phù hợp để LLM xử lý.<br>- Tiết kiệm 10-20 phút giao tiếp dư thừa cho mỗi lỗi phát sinh. | - Để có giá trị thực tiễn, giải pháp bắt buộc phải tích hợp thẳng vào nền tảng nội bộ (Slack/Teams/Jira). Nếu làm web app rời, developer/monitor sẽ lười sử dụng. |

### 3.4. Score để đồng thuận (chấm 1-5, ép nói rõ vì sao cho 5 / cho 3)

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
| --------- | -------: | ----------: | ---------------: | -------------: | ------------: | -----------------: | ---------------: | ---: |
| **Candidate 10** (Tinh chỉnh CV) | 5 | 5 | 4 | 5 | 5 | 4 | 5 | 33 |
| **Candidate 12** (Trích xuất từ paper) | 4 | 4 | 4 | 5 | 4 | 4 | 5 | 30 |
| **Candidate 4** (Báo lỗi thiếu chi tiết)| 5 | 5 | 5 | 4 | 3 | 5 | 4 | 31 |

#### Giải thích chi tiết các điểm 5 và 3:

**1. Candidate 10 (Tinh chỉnh CV thủ công theo JD):**
- **Cho 5 (Actor, Workflow, Impact, Domain):** Vấn đề cực kỳ gần gũi với toàn bộ thành viên nhóm. Luồng công việc trực quan (đọc JD -> tìm kỹ năng -> viết lại diễn đạt). Impact đo lường được ngay bằng phút (giảm từ 60' xuống 15'). 
- **Cho 5 (Làm trong lab):** Bài toán text-to-text thuần túy, cực kỳ khả thi để làm bản MVP nhanh bằng các kỹ thuật Prompt Chain cơ bản mà không cần setup môi trường phức tạp.

**2. Candidate 12 (Trích xuất Limitation từ bài báo nghiên cứu):**
- **Cho 5 (Impact):** Rút ngắn được hàng giờ đồng hồ "cày" các bài báo khoa học phức tạp, giá trị tiết kiệm thời gian là rất lớn.
- **Cho 5 (Nhóm hiểu domain):** Nhóm có thành viên xuất thân từ khoa Toán Tin, trực tiếp nghiên cứu sâu về các kiến trúc học máy phức tạp, mô hình dự báo chuỗi thời gian nên việc phải đọc hiểu và bóc tách cấu trúc paper diễn ra liên tục, đảm bảo độ thấu hiểu bài toán sâu sắc để làm mượt luồng UX.

**3. Candidate 4 (Thông tin báo lỗi từ team monitor thiếu chi tiết):**
- **Cho 5 (Actor, Workflow, Evidence, So sánh R/W/A):** Vấn đề quy trình cực chuẩn xác, evidence rõ ràng từ lịch sử chat. Trục so sánh rất tuyệt vời (Rule: Bắt điền form cứng -> Workflow: AI tự đọc log trích xuất form -> Agent: AI tự động ping hỏi lại dev đúng những trường thông tin còn thiếu).
- **Cho 3 (Làm trong lab):** Để demo có tính thuyết phục, bài này đòi hỏi phải giả lập môi trường giao tiếp thực tế (mockup webhook của Slack/Teams) và setup các cục log hệ thống mẫu. Rủi ro tốn thời gian cấu hình và có thể không kịp hoàn thiện trong thời lượng của buổi lab.

**Candidate nhóm chọn (1 bài duy nhất):**

```text
Bot tự động gom và tra cứu quyết định chốt đồ án trong nhóm chat
```

**Vì sao chọn (4-5 câu):**

```text

```

**Vì sao KHÔNG chọn các candidate còn lại (mỗi bài 2-3 câu):**

```text

```

**Disagreement (nếu có — ai lo gì, chốt ra sao):**

```text

```

---

## Phase 4 — Quick Validation + Research

### 4.1. Quick validation (ít nhất 1 cách: interview 2-3 người hoặc survey 5-10 người)

| Nguồn                          | Số người / mẫu | Tín hiệu xác nhận (kèm quote nguyên văn) | Tín hiệu phản bác | Nhóm sửa problem thế nào |
| ------------------------------ | -------------: | ---------------------------------------- | ----------------- | ------------------------ |
| Interview                      |                |                                          |                   |                          |
| Survey / poll                  |                |                                          |                   |                          |
| Log / ticket / review (nếu có) |                |                                          |                   |                          |

**Insight sau validation (1-2 câu — pain thật nằm ở đâu):**

```text

```

Bằng chứng đính kèm (nếu có): `02-group-problem-statement-survey.png`, `...-interview-notes.md`

### 4.2. Research giải pháp đã có (ít nhất 2-3 tools/patterns + 1-2 link kiểm được)

| Nguồn / tool / case | Link | Họ giải quyết bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
| ------------------- | ---- | ----------------------- | --------- | --------------------- | ---------------- |
|                     |      |                         |           |                       |                  |
|                     |      |                         |           |                       |                  |
|                     |      |                         |           |                       |                  |

**Research takeaway (2-3 câu — nên build gì / không build gì):**

```text

```

> Lưu ý: không dùng số liệu AI đưa nếu không verify được link chính thức. Ghi rõ giả định chưa chắc.

---

## Phase 5 — Workflow + Problem Statement

### 5.1. Current workflow bản nhóm

Dán workflow hoặc link file: `02-group-problem-statement-workflow.png/pdf/md`

```text
[1 ...: __' - ai làm] → [2 ...: __'] → [3 ...: __'] → [4 ... bottleneck: __'] → ...
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú (handoff? bottleneck?) |
| ---- | ----- | ----- | ------ | -------------------- | ------------------------------ |
| 1    |       |       |        |                      |                                |
| 2    |       |       |        |                      |                                |
| 3    |       |       |        |                      |                                |
| 4    |       |       |        |                      |                                |
| 5    |       |       |        |                      |                                |
| 6    |       |       |        |                      |                                |
| 7    |       |       |        |                      |                                |

**Bottleneck chính (2-3 câu):**

```text

```

### 5.2. Future workflow bản nhóm

Phải nhìn ra 5 thứ: bước nào máy (Rule), bước nào AI, bước nào người, boundary ở đâu, fallback khi AI sai.

```text
[1 ...: __' - máy] → [2 AI ...: __'] → [3 ... review: __' - boundary] → [4 ... gửi]

Fallback: ...
```

**Before/after impact:**

| Metric           | Trước | Sau kỳ vọng | Cách đo |
| ---------------- | ----: | ----------: | ------- |
| Tổng thời gian   |       |             |         |
| Số bước          |       |             |         |
| Số bước thủ công |       |             |         |
| Bottleneck chính |       |             |         |
| Risk mới         |       |             |         |

### 5.3. Problem Statement v0 (mỗi field 2-3 câu)

| Field              | Nội dung |
| ------------------ | -------- |
| **Actor**          |          |
| **Workflow**       |          |
| **Bottleneck**     |          |
| **Impact**         |          |
| **Success Metric** |          |
| **Boundary**       |          |

**Câu hỏi AI phản biện v0 (nếu có):**

- Field nào mơ hồ:
- Tôi sửa gì:

---

## Phase 6 — Rule / Workflow / Agent + Decision

### 6.0. Ma trận độ phù hợp (suy nghĩ nhanh, không thay quyết định cuối)

- Độ mơ hồ: [ ] Thấp (có đúng/sai rõ) / [ ] Cao (nhiều cách trả lời vẫn OK) — Vì sao:
- Độ phức tạp: [ ] Thấp (1-2 bước) / [ ] Cao (3+ bước/nguồn, phụ thuộc nhau) — Vì sao:

**Bài toán nhóm nằm ở ô nào:**

```text

```

**Vì sao (2-3 câu):**

```text

```

### 6.1. So sánh Rule / Workflow / Agent (so trên cùng 1 bài)

| Mức          | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? (Dùng cho bước nào?) |
| ------------ | --------------------------- | ---------- | ------ | -------------------------- |
| **Rule**     |                             |            |        |                            |
| **Workflow** |                             |            |        |                            |
| **Agent**    |                             |            |        |                            |

**5 câu hỏi chốt (trả lời câu đầy đủ):**

1. Rule có giải được 70-80% case không?
2. Các bước có đi thẳng một đường không hay phải rẽ nhánh?
3. Có thật sự cần Agent tự lập kế hoạch + gọi tool không?
4. Nếu AI sai, ai phát hiện đầu tiên và sửa trong bao lâu?
5. Có hạ được từ Agent → Workflow → Rule không?

**Mức chọn:**

```text
[Rule / Workflow / Agent]
```

**Vì sao chọn (3-4 câu):**

```text

```

**Vì sao không chọn mức đơn giản hơn (2-3 câu):**

```text

```

### 6.2. Problem Statement v1 (v0 sửa chặt hơn + 3 field cuối)

| Field                                                                          | Nội dung |
| ------------------------------------------------------------------------------ | -------- |
| **Actor**                                                                      |          |
| **Workflow**                                                                   |          |
| **Bottleneck**                                                                 |          |
| **Impact**                                                                     |          |
| **Success Metric**                                                             |          |
| **Boundary** (làm / không làm)                                                 |          |
| **AI intervention point** (can thiệp sau bước nào, trước bước nào)             |          |
| **Mức chọn** (Rule / Workflow / Agent + 1 câu vì sao)                          |          |
| **Rủi ro & người thật kiểm tra** (rủi ro lớn nhất + ai kiểm tra bằng cách nào) |          |

### 6.3. Final decision

| Câu hỏi                               | Yes / Not Yet / No | Ghi chú (câu đầy đủ) |
| ------------------------------------- | ------------------ | -------------------- |
| Actor + workflow rõ chưa?             |                    |                      |
| Baseline + metric đo được chưa?       |                    |                      |
| Data/input đủ dùng chưa?              |                    |                      |
| AI sai, hậu quả chấp nhận được không? |                    |                      |
| Có người review/owner không?          |                    |                      |
| Có cách non-AI đơn giản hơn không?    |                    |                      |

**Decision:**

```text
[Go / Not Yet / No-Go]
```

**Lý do (3-4 câu dựa trên bằng chứng):**

```text

```

**Nếu Go — pilot nhỏ nhất (data nào, chạy tay ra sao, đo 3 số nào):**

```text

```

**Nếu Not Yet — cần validate gì trước:**

```text

```

**Nếu No-Go — làm gì thay AI:**

```text

```

**Exit / rollback (khi nào dừng AI, quay về cách cũ):**

```text

```

---

### Self-check nộp phần 02 (nhóm)

- [ ] Có nhật ký hội tụ 9-12 → 1 (cluster + shortlist + score)
- [ ] Có validation (quote thật) + research (link kiểm được)
- [ ] Có workflow trước/sau đủ thời gian, handoff, bottleneck, boundary, fallback
- [ ] Có PS v0 → v1, metric có trước/sau + cách đo, boundary có làm/không làm
- [ ] Có so sánh Rule/Workflow/Agent + Decision Go/Not Yet/No-Go có lý do
