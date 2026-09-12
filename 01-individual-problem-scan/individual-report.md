# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Đoàn Anh Quân
- Mã học viên: 2A20260803
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...): 
Sinh viên năm 4 của 1 trường đại học cũng như đang thực tập tại 1 doanh nghiệp nhỏ.
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):
+ Lập kế hoạch và sắp xếp trong tuần tuần
+ Kiểm tra thông báo, email
+ Chuẩn bị báo cáo, tóm tắt nội dung
+ Tìm kiếm tài liệu, chuẩn bị, ôn tập
---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | Lặp lại | Kiểm tra mail hằng ngày để cập nhật thay đổi về môn học, lịch học và thông báo ở trường | User | Mất khoảng 30 phút/ngày |
| 2 | Lặp lại | Lập thời gian biểu và đặt nhắc nhở thủ công cho lịch trình, lớp học và lịch họp nhóm mỗi tuần | User | 1 tiếng/tuần |
| 3 | Tốn thời gian | Đọc hiểu và tóm tắt nội dung môn học, tài liệu dài hoặc văn bản phức tạp. | User | 45 phút/bản |
| 4 | Tốn thời gian | Tìm kiếm và tổng hợp tài liệu tham khảo từ nhiều nguồn (slide, sách, paper) cho đồ án | User | 1-3 tiếng/đồ án |
| 5 | AI có thể tốt hơn | Đọc hiểu tài liệu chuyên ngành tiếng Anh (paper, tài liệu kỹ thuật) | User | Tốn khoảng 1 tiếng/tài liệu |
| 6 | AI có thể tốt hơn | Tự rà soát code hoặc báo cáo trước khi nộp nhưng bỏ sót lỗi chính tả, thiếu chú thích hoặc logic | User | Hay bị mentor trả lại để sửa, mất khoảng 30 phút review |
| 7 | Pain từ người khác | Tổng hợp và hợp nhất các file bài tập nhóm rời rạc (Word, ảnh chụp, Zalo) thành bản hoàn chỉnh. | User + nhóm học | 1-2 giờ /lần |
| 8 | Pain từ người khác | Tổng hợp các task giao rải rác từ mentor/PM qua nhiều kênh (Slack, email, họp) thành to-do list | User | Dễ sót việc mỗi tuần, mất 30 phút tổng hợp |
| 9 | Tốn thời gian | Làm slide thuyết trình nhóm: gom nội dung, căn chỉnh layout, đồng bộ font chữ và màu sắc. | User + nhóm học | 2-3 giờ/lần |
| 10 | Lặp lại | Tóm tắt bài giảng sau mỗi buổi học theo một cấu trúc cố định (ý chính, từ khóa, câu hỏi ôn tập) | User | ~20 phút/buổi |
| 11 | AI có thể tốt hơn | Tìm kiếm đề ôn tập, hướng dẫn giải, chấm điểm và sửa lỗi khi tự học | User | Tốn 30 phút tìm nguồn và phải tự kiểm tra
| 12 | AI có thể tốt hơn | Tự học tiếng anh bằng AI về các kỹ năng nói - đọc - viết | User | Chi phí di chuyển và khóa học cao


> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi: 
- Ý dùng được:
- Ý bỏ vì không phải pain thật:

**Self-check Phase 1:**
- [X] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [X] Dùng ít nhất 3/4 lăng kính
- [X] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Tổng hợp Task phân tán từ Mentor/PM | Pain thật và tần suất cao. Có workflow rõ ràng. AI fit tốt | Khả năng tự động hóa đồng bộ dữ liệu xuyên suốt các nền tảng |
| 2 | Tự động hóa giải bài tập và chấm sửa lỗi | Pain thật về thời gian. Metric tốt. Impact rộng và nhiều | Tính chuẩn xác trong cơ chế phản hồi lỗi |
| 3 | Học tiếng Anh bằng AI | Nhiều người đau và market lớn. Workflow cá nhân tốt. Impact rộng | Độ tự nhiên và chuẩn xác của AI trong đánh giá kỹ năng nói

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — Tổng hợp task từ nhiều nguồn

**Problem 1 câu:**  
Junior/Intern gặp khó khăn trong việc tổng hợp và theo dõi các nhiệm vụ giao rải rác từ quản lý qua nhiều kênh tiếp khác nhau (Discord, Mail, Slack, Zalo,...) dẫn đến tốn thời gian rà soát và dễ bỏ sót việc.

**Actor:**
Junior/Intern tự túc (chủ động giải quyết vấn đề cá nhân vì không thể ép cấp trên chuẩn hóa kênh giao tiếp).

**Thời điểm / bối cảnh:**  
Cuối ngày làm việc hoặc đầu tuần khi cần lên kế hoạch tổng quan cá nhân.  

**Current workflow:**

```text
1. Mở lần lượt toàn bộ các kênh
2. Tìm kiếm tin nhắn cũ về giao công việc
3. Tổng hợp bằng tay các công việc vào sổ tay các nhân
4. Sắp xếp thứ tự ưu tiên các công việc
5. Xác thực lại với mentor đối với các task chưa rõ
```

**Bottleneck:**  
Thiếu nguồn dữ liệu tập trung và thông tin bị nhiễu loạn, đặc biệt là các yêu cầu giao việc bằng miệng không thể tự động hóa bằng phần mềm đơn thuần.
Điểm nghẽn nằm ở sự phân mảnh của dữ liệu (fragmented channels) và chi phí chuyển đổi ngữ cảnh (context switching) liên tục giữa các ứng dụng chỉ để gom task.

**Impact:**  
Mất 20 - 30 phút mỗi ngày dò tìm thông tin; rủi ro sót việc cao dẫn đến trễ deadline và giảm độ tín nhiệm với mentor.

**Success metric:**
Thời gian tổng hợp to-do list giảm dưới 10 phút; không cần mentor nhắc lại công việc; tỷ lệ task bị bỏ sót giảm xuống còn 0%.

**Non-AI alternative:**  
Yêu cầu khi giao việc phải được tag hoặc thread hóa vào 1 kênh chung cố định, nói miệng thì note lại. Hoặc mỗi khi thấy tin nhắn giao việc ở bất kỳ kênh nào thì phải lập tức copy sang một file chung duy nhất ngay tại thời điểm đó.

**AI hypothesis:**  
AI tự động quét và trích xuất thực thể (task, deadline) từ các kênh giao tiếp để đồng bộ vào một bảng to-do list thống nhất.

**Quick gut:**
[ ] No AI / process fix
[ ] Rule
[X] Workflow
[ ] Agent
[ ] Chưa biết

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — 30 phút

[1 Quét tin nhắn cũ: 15'] <-- bottleneck
→ [2 Kiểm tra chưa đọc: 5']
→ [3 Xem ghi chú họp, task giao miệng: 5']
→ [4 Chép vào to-do list: 10']  
→ [5 Sắp xếp ưu tiên: 5']
→ [6 Xác thực các task: không cố định']
```

```text
FUTURE STATE — 10 phút

[1 Tự động thu thập dữ liệu đa kênh + ghi âm nhanh yêu cầu miệng: 3'] 
→ [2 AI phân tích & trích xuất task, deadline: 2']
→ [3 AI gom nhóm và đề xuất to-do list: 1']
→ [4 User Review & Chỉnh sửa: 5'] <-- human-in-the-loop
```
Fallback: AI bỏ sót task → Người dùng tự bổ sung thủ công.


File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — Tìm kiếm đề và hỗ trợ ôn tập, chấm sửa lỗi

**Problem 1 câu:**  
Người học mất nhiều thời gian tìm kiếm nguồn đề ôn tập bên ngoài và thiếu công cụ chấm điểm, hướng dẫn giải chi tiết khi tự học các chủ đề chuyên môn.

**Actor:**  
Học sinh, sinh viên, người tự học các môn tự nhiên, kỹ thuật và thuật toán.

**Thời điểm / bối cảnh:**  
Giai đoạn ôn thi hoặc khi muốn kiểm tra năng lực bản thân sau khi học xong một chương lý thuyết.

**Current workflow:**

```text
1. Xác định nội dung/chủ đề cần ôn tập
2. Tìm kiếm đề thi, bài tập mẫu trên internet hoặc diễn đàn
3. Tự giải quyết bài toán ra giấy hoặc code
4. Tự kiểm tra kết quả bằng code chạy thử hoặc tìm đáp án mẫu
5. Mò mẫm tìm nguyên nhân khi gặp lỗi sai không rõ lý do
```

**Bottleneck:**  
Bước 2 & 5 — tốn nhiều thời gian tìm kiếm nguồn tài liệu phù hợp và thiếu phản hồi chi tiết về bản chất lỗi sai.

**Impact:**  
Mất 40 phút tìm đề. Hiệu suất tự học thấp, dễ nản khi gặp bài toán khó không có lời giải thích mạch lạc. Mất nhiều thời gian để tự giải hoặc không tìm ra được đáp án đúng.

**Success metric:**
Giảm 70% thời gian tìm kiếm tài liệu; thời gian nhận giải thích lỗi sai dưới 1 phút; biết được cách làm đúng.

**Non-AI alternative:**  
Tham gia các nhóm hỏi đáp học thuật, mua sách bài tập có kèm đáp án chi tiết phía sau, học nhóm, học thêm, hỏi bài người khác.

**AI hypothesis:**  
AI tự động sinh đề theo đúng cấp độ, chấm bài làm của người học và đóng vai trò gia sư giải thích tường tận từng bước sai.

**Quick gut:**
[ ] No AI / process fix
[ ] Rule
[ ] Workflow
[X] Agent
[ ] Chưa biết
**Draft workflow Card #2:**

```text
CURRENT STATE — 110 phút

[1 Xác định chủ đề: 5']
→ [2 Tìm kiếm đề/tài liệu ngoài: 30]  <-- bottleneck
→ [3 Tự giải bài tập: 15']
→ [4 Dò đáp án / chạy thử: 5']
→ [5 Mò mẫm sửa lỗi: 15'] <-- bottleneck
```
```text
FUTURE STATE — 25 phút

[1 AI tạo đề ôn tập tùy chỉnh: 2']
→ [2 Người học làm bài: 15']
→ [3 AI chấm điểm và chỉ ra lỗi sai: 3']
→ [4 Người học đọc giải thích chi tiết: 5']  <-- human boundary
```
Fallback: AI sinh đề quá dễ hoặc quá khó → Người dùng yêu cầu điều chỉnh mức độ (Prompt tuning).

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — Tự học các kỹ năng tiếng Anh bằng AI

**Problem 1 câu:**  
Người học mất nhiều thời gian tìm kiếm nguồn đề ôn tập bên ngoài và thiếu công cụ chấm điểm, hướng dẫn giải chi tiết khi tự học các chủ đề chuyên môn.Người học mất nhiều thời gian tìm kiếm nguồn đề ôn tập bên ngoài và thiếu công cụ chấm điểm, hướng dẫn giải chi tiết khi tự học các chủ đề chuyên môn.

**Actor:**  
Sinh viên / Người đi làm có nhu cầu học tiếng Anh, lấy chứng chỉ.

**Thời điểm / bối cảnh:** 
Thời gian rảnh cá nhân phân bổ không cố định trong ngày.

**Current workflow:**

```text
1. Đăng ký lịch học tại trung tâm hoặc khóa online cố định
2. Di chuyển đến lớp hoặc đăng nhập đúng giờ
3. Nghe giảng và làm bài tập theo giáo trình chung
4. Nộp bài viết và chờ giảng viên chấm sửa
5. Luyện nói hạn chế theo thời lượng của lớp học
```

**Bottleneck:**  
Bước 4 & 5 — độ trễ phản hồi bài viết lâu và thiếu không gian 1-on-1 để luyện nói phản xạ.

**Impact:**  
Chi phí cao, dễ bỏ học giữa chừng vì lệch lịch trình, tiến độ cải thiện chậm ở kỹ năng chủ động.

**Success metric:**
Duy trì tần suất luyện tập hằng ngày; giảm 100% độ trễ nhận phản hồi chấm sửa lỗi.

**Non-AI alternative:**  
Thuê gia sư trực tuyến 1-on-1 hoặc tham gia câu lạc bộ tiếng Anh ngoại khóa.

**AI hypothesis:**  
AI cung cấp môi trường hội thoại đa phương thức (giọng nói/văn bản) tương tác tức thì và chấm sửa lỗi viết tự động.

**Quick gut:**  
[ ] No AI / process fix
[ ] Rule
[ ] Workflow
[X] Agent
[ ] Chưa biết

**Draft workflow Card #3:**

```text
CURRENT STATE — 120 phút/buổi

[1 Di chuyển / Đăng nhập lớp: 30']
→ [2 Học lý thuyết chung: 40']
→ [3 Luyện nói hạn chế: 20']
→ [4 Nộp bài viết chờ chấm: 20']
→ [5 Đóng gói / kết thúc: 10']  <-- bottleneck (độ trễ phản hồi)
```
```text
FUTURE STATE — 30 phút/buổi

[1 Mở ứng dụng AI bất kỳ lúc nào: 2']
→ [2 AI tương tác luyện nói phản xạ: 15']
→ [3 AI chấm sửa bài viết tức thì: 10']
→ [4 Người dùng tiếp thu feedback: 3']  <-- human boundary
```

Fallback: AI phát âm chưa tự nhiên ở một số sắc thái → Người dùng chuyển sang chế độ text.


File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Tôi muốn pitch nhất là card 1
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Workflow: Gom tin nhắn đa kênh (Discord, Zalo, Mail) -> AI trích xuất task/deadline -> Đổ thẳng vào to-do list cá nhân.

Số đo: Thời gian tổng hợp giảm từ 30 phút xuống dưới 10 phút mỗi ngày; tỷ lệ bỏ sót công việc giảm về 0%.

Impact: Giúp Junior/Intern tiết kiệm thời gian rà soát, không bị trễ deadline và giữ vững độ tín nhiệm với quản lý trong môi trường giao việc phân mảnh.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
Thách thức về công nghệ. 1 thứ gì đó có thể truy cập nhiều nền tảng khác nhau. Ngoài ra còn thách thức về bảo mật thông tin.
```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra:
- Tôi sửa gì:

### Self-check nộp phần 01
- [X] Có 5+ problems + top 3 Cards đủ field
- [X] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [X] Đã chọn 1 card pitch + câu hỏi challenge
