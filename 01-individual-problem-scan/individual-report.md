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

#### Problem Card #1 — [Tên problem]

```text
Problem 1 câu:

Actor:

Thời điểm / bối cảnh:

Current workflow 3-7 bước:
1.
2.
3.
4.
5.

Bottleneck:

Impact:

Success metric:

Non-AI alternative:

AI hypothesis:

Quick gut:
[ ] No AI / process fix
[ ] Rule
[ ] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — ___ phút

[1 ...: __'] → [2 ...: __'] → [3 ...: __'] → [4 ...: __']  <-- bottleneck

FUTURE STATE — ___ phút

[1 ...: __'] → [2 ...: __'] → [3 ... review: __']  <-- human boundary

Fallback: nếu AI sai thì ...
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — [Tên problem]

```text
Problem 1 câu:

Actor:

Thời điểm / bối cảnh:

Current workflow 3-7 bước:
1.
2.
3.
4.
5.

Bottleneck:

Impact:

Success metric:

Non-AI alternative:

AI hypothesis:

Quick gut:
[ ] No AI / process fix
[ ] Rule
[ ] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — ___ phút

[1 ...] → [2 ...] → [3 ...]  <-- bottleneck

FUTURE STATE — ___ phút

[1 ...] → [2 ...] → [3 ... review]  <-- human boundary

Fallback: ...
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — [Tên problem]

```text
Problem 1 câu:

Actor:

Thời điểm / bối cảnh:

Current workflow 3-7 bước:
1.
2.
3.
4.
5.

Bottleneck:

Impact:

Success metric:

Non-AI alternative:

AI hypothesis:

Quick gut:
[ ] No AI / process fix
[ ] Rule
[ ] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — ___ phút

[1 ...] → [2 ...] → [3 ...]  <-- bottleneck

FUTURE STATE — ___ phút

[1 ...] → [2 ...] → [3 ... review]  <-- human boundary

Fallback: ...
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text

```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text

```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text

```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra:
- Tôi sửa gì:

### Self-check nộp phần 01
- [ ] Có 5+ problems + top 3 Cards đủ field
- [ ] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [ ] Đã chọn 1 card pitch + câu hỏi challenge
