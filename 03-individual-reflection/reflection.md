# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Trần Tuấn Hoàng
- Mã học viên: 2A202602832
- Nhóm: BotVN
- Candidate problem nhóm chọn: Bot tự động gom và tra cứu quyết định chốt đồ án trong nhóm chat

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Tìm các vấn đề thực tế xung quanh. | Có list vấn đề thô. |
| Pitch Problem Card | Trình bày nhanh vụ lọc CV, đưa 1 số liệu chứng minh. | Nhóm thấy rõ độ nghiêm trọng. |
| Challenge bài của bạn khác | Đặt 2 câu hỏi phản biện tính khả thi. | Loại được 1 idea khó làm. |
| Gom trùng / cluster | Gộp 3 ý tưởng na ná nhau vào mảng giáo dục. | Bảng gọn, vote nhanh hơn. |
| Chọn candidate problem | Vote chọn chủ đề lọc tin nhắn chat (quan trọng/rác). | Chốt được đề tài chính. |
| Validation / research | Lấy tin nhắn từ group chat thật ra đối chiếu. | Xác nhận vấn đề là có thật, không tự biên. |
| Workflow nhóm | Đề xuất chia việc 3 bước: gom data, dựng luồng LLM, test. | Thống nhất được task và người làm. |
| Problem Statement | Nháp 2 câu chốt lại core problem. | Chốt được Problem Statement. |
| Rule / Workflow / Agent | Lên luồng xử lý cho LLM. Viết 2 rule bắt lỗi. | Agent chạy ổn, ra đúng form. |
| Decision | Chốt chạy mô hình SLM lượng hóa local thay vì gọi API ngoài. | Chốt lẹ phương án, đỡ cãi nhau dài. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**
```text
Tôi góp ý phản biện và chốt đề tài.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Brainstorm các vấn đề hay gặp trong công việc và học tập. | Đưa ra nhiều ý tưởng nhanh trong thời gian ngắn. | Ý tưởng quá chung chung, mang tính sách vở (như quản lý thời gian, stress). | Tự lọc lấy các vấn đề thực tế mình hay bức xúc (như trôi tin nhắn nhóm, lọc CV). |
| Problem Card | Lên khung thẻ vấn đề và tóm tắt nội dung. | Format thẻ gọn gàng, rõ các mục. | Tự bịa số liệu dẫn chứng không có nguồn kiểm chứng. | Tự tìm số liệu thực tế về tỷ lệ trôi tin và thời gian lọc thủ công để điền vào. |
| Workflow | **Không dùng** | — | — | Nhóm tự bàn vì phải dựa trên thời gian rảnh và thế mạnh từng người, AI không biết ai làm tốt mảng nào để chia việc. |
| Research | Gợi ý các tiêu chí phân loại tin nhắn (quan trọng vs không quan trọng). | Cho một khung tiêu chí khá logic và bài bản. | Không hiểu tiếng lóng, viết tắt, teencode và văn hóa tag nhóm ở Việt Nam. | Lấy tin nhắn thực tế từ các nhóm chat của mình ra để đối chiếu và sửa lại bộ tiêu chí cho sát. |
| Problem Statement | Viết lại câu mô tả vấn đề cho mượt. | Giúp câu văn đúng cấu trúc chuẩn của một Problem Statement. | Văn phong sáo rỗng, đao to búa lớn và dài dòng. | Cắt hết từ thừa, viết lại 1 câu ngắn gọn đúng thẳng vào nỗi đau bị sót việc do trôi tin. |
| Rule / Workflow / Agent | Viết nháp system prompt và các rule phân loại tin nhắn. | Sinh khung prompt nhanh, liệt kê được các case cơ bản. | Rule rất máy móc, chỉ cần dính từ khóa là bắt nhầm tin đùa cợt thành tin khẩn cấp. | Tự viết thêm rule xét theo ngữ cảnh câu trước đó và rule bỏ qua tin chỉ chứa icon, sticker. |
| Decision | **Không dùng** | — | — | Nhóm tự quyết định vì liên quan đến cấu hình máy có sẵn và chi phí chạy mô hình, AI không thể quyết thay được. |

---

## 3. Reflection câu hỏi mở

Chọn 3-4 câu trong 6 câu dưới để viết thành đoạn 8-12 câu (không trả lời bullet 1 dòng):
- Tôi học được gì khi nghe top 3 problems của các bạn khác?
- Nhóm có lúc nào bị solution-first, đòi làm Agent cho ngầu không?
- Tôi có thay đổi ý kiến sau khi bị challenge không, vì sao đổi?
- Tôi đóng góp gì thật sự vào artifact cuối, phần nào có dấu tay của tôi?
- Điều khó nhất khi viết Problem Statement là gì, metric hay boundary?
- Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?

**Reflection:**

```text
Ban đầu, cả nhóm khá solution-first, ai cũng hào hứng với ý tưởng xây một Agent đa năng nên chưa xác định rõ vấn đề cốt lõi. Vì vậy, khi viết Problem Statement, chúng tôi mất khá nhiều thời gian để thống nhất xem bài toán thực sự bắt đầu và kết thúc ở đâu. Tôi nhận ra vấn đề lớn nhất lúc đó là phạm vi cứ bị mở rộng bởi quá nhiều use-case. Tôi đã lên tiếng phản biện và thuyết phục cả nhóm thu hẹp lại, tập trung đúng vào bài toán lọc tin nhắn quan trọng. Đây cũng là đóng góp rõ nhất của tôi trong sản phẩm cuối. Tuy nhiên, nếu làm lại, tôi sẽ muốn nhóm kiểm tra dữ liệu thực tế ngay từ đầu thay vì tranh luận quá nhiều dựa trên giả định. Việc nhìn vào các group chat thật có thể giúp chúng tôi sớm xác định vấn đề và loại bỏ những ý tưởng chưa thực sự cần thiết.
```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [x] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [x] [15đ] Nhóm có workflow trước/sau
- [x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [x] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [ ] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI

