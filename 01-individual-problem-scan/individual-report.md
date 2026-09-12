# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Nguyễn Đình Phúc
- Mã học viên: 2A202602953
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...): Mobile developer
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):
  - nhận yêu cầu từ BA/BGĐ/Client
  - nghĩ design cho feature
  - code
  - test
  - fix bug
  - đẩy lên test flight đợi test
  - test hoàn thành đẩy lên store
  - báo cáo
  - Học tiếng Anh

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | Pain từ người khác | Nhận yêu cầu bằng nói miệng hoặc nhắn tin vội từ sếp/khách (hoàn toàn không có Jira hay tài liệu/spec), dev tự hiểu tự làm xong lại bị bảo "không đúng ý anh" | Mobile dev, Sếp, Client | 2–3 lần/tháng bị bắt đập đi sửa lại giao diện/flow sau khi đã code xong; mất thêm 1–2 ngày làm lại vì trao đổi miệng lúc nhớ lúc quên |
| 2 | Lặp lại | Quy trình xuất build và đẩy lên TestFlight thủ công hằng ngày (1–2 lần/ngày) mỗi khi xong tính năng hoặc fix bug, phải ngồi chờ Apple xử lý build | Mobile dev, Tester, Sếp | Ngày nào cũng build 1–2 lần, mất 15–20 phút/lần archive + upload + chờ Apple process; sếp và tester liên tục giục miệng: "Có bản mới trên TestFlight chưa em?" |
| 3 | AI có thể tốt hơn | Sếp chỉ gửi ảnh chụp app khác hoặc mô tả miệng rồi bảo "làm giống vậy đi", dev phải tự nghĩ toàn bộ bố cục UI, các state loading/lỗi | Mobile dev, End-user | Mất 1–2 tiếng mỗi tính năng để tự nháp layout và cân nhắc state; thỉnh thoảng demo xong sếp chê xấu hoặc bắt đổi vị trí các nút |
| 4 | Tốn thời gian | Sếp/Tester test trực tiếp thấy văng app là chụp màn hình hoặc quay video gửi thẳng qua chat bảo "bị lỗi này em ơi" mà không có log hay steps tái hiện | Mobile dev, Sếp, Tester | 3–4 lần/tuần nhận tin nhắn báo lỗi chỉ kèm 1 cái ảnh; dev phải chạy sang mượn máy sếp hoặc ngồi mò code 1–2 tiếng để đoán dòng gây crash |
| 5 | Tốn thời gian | Mất nhiều thời gian tự phân bổ, tính toán lịch ôn tập từ vựng tiếng Anh theo phương pháp lặp lại ngắt quãng (Spaced Repetition) | Bản thân (Mobile dev) | Mất 20–30 phút/ngày ngồi tính ngày ôn (1, 3, 7, 14, 30) trên sổ/Notion; công việc bận nên hay bị dồn ứ lịch 3–4 ngày/tuần dẫn đến nản và quên từ vựng |
| 6 | Tốn thời gian | Một mình tự lo từ A–Z khâu release lên App Store: tạo certificate, chụp ảnh đa kích thước màn hình, dịch mô tả, giải trình khi Apple từ chối | Mobile dev, Sếp | 1–2 lần release/tháng; mất 3–4 tiếng tự chụp màn hình và điền form checklist; nếu bị Apple reject guideline mất thêm 1–2 ngày tự mò cách sửa/kháng nghị |
| 7 | Lặp lại | Soạn tin nhắn báo cáo ngắn gửi trực tiếp cho sếp sau mỗi lần đẩy bản build mới lên TestFlight (tóm tắt vừa sửa bug gì, thêm tính năng gì, sếp cần test chỗ nào) | Mobile dev, Sếp | 1–2 lần/ngày sau mỗi đợt build, mất 10–15 phút lục lại commit để gõ tin nhắn báo cáo; sếp chỉ đọc lướt rồi vẫn quay sang hỏi: "Bản này đã sửa cái lỗi hôm qua anh nói chưa em?" |
| 8 | AI có thể tốt hơn | Đọc hiểu tài liệu kỹ thuật / SDK mới bằng tiếng Anh khi sếp yêu cầu tích hợp gấp tính năng mới (thanh toán, map, push noti) | Mobile dev, Sếp | 1–2 lần/tháng sếp giục làm gấp; mất 2–3 tiếng vừa đọc docs tiếng Anh vừa mò code mẫu để hiểu cơ chế và tích hợp vào app |
| 9 | Pain từ người khác | Thiếu thiết bị test đa dạng, dev chỉ test trên 1 máy rồi đẩy build, sếp/khách mở trên máy đời khác (màn hình nhỏ hoặc iOS cũ) bị vỡ giao diện | Mobile dev, Sếp, Client | 2–3 lần/tháng sếp cầm máy đời cũ test rồi bảo: "Sao trên máy anh chữ bị tràn/nút bị che mất em?", dev phải cuống cuồng sửa gấp trong ngày |
| 10 | AI có thể tốt hơn | Không có thời gian viết test bài bản, dev chỉ test vội luồng chính nên hay sót các trường hợp mạng yếu, mất mạng hoặc data rỗng | Mobile dev, Tester, Sếp | Cứ đẩy build TestFlight lên là 1–2 tiếng sau tester/sếp bấm vào lại thấy lỗi cơ bản (bấm nút liên tục bị gọi 2 lần, mất mạng đứng màn hình) |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**

- Prompt đã hỏi: Tôi là Mobile Developer trong công ty product nhỏ, không dùng Jira hay quy trình bài bản nào; việc giao việc hoàn toàn qua nói miệng/chat riêng. Báo cáo chỉ là tin nhắn tóm tắt ngắn gửi trực tiếp cho sếp sau khi đẩy bản build mới lên TestFlight hằng ngày (1-2 lần/ngày). Hãy gợi ý các problem thật theo 4 lăng kính với số liệu định lượng thực tế.
- Ý dùng được: Vấn đề giao việc miệng gây hiểu sai ý, khâu chờ TestFlight bị hối thúc, việc phải tự lục commit để gõ tin nhắn báo cáo sếp sau mỗi build nhưng sếp đọc lướt vẫn hỏi lại, nhận ảnh crash không có log, và tốn thời gian tính lịch học tiếng Anh Spaced Repetition.
- Ý bỏ vì không phải pain thật: Các quy trình Jira/PRD/standup formal vì không tồn tại trong bối cảnh công ty nhỏ.

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
| 1 | Soạn tin nhắn báo cáo ngắn gửi trực tiếp cho sếp sau mỗi lần đẩy bản build mới lên TestFlight (Problem #7) | Workflow lặp lại hằng ngày (1–2 lần/ngày); bottleneck rõ ràng ở bước lọc commit & viết tóm tắt; impact đo được bằng phút (15' → 3'); rất sát thực tế công ty nhỏ và khả thi trong lab | Sếp có chấp nhận văn phong tin nhắn do AI sinh ra không; nếu commit viết sơ sài thì AI lấy context từ đâu |
| 2 | Mất nhiều thời gian tự phân bổ, tính toán lịch ôn tập từ vựng tiếng Anh theo phương pháp lặp lại ngắt quãng (Spaced Repetition) (Problem #5) | Trải nghiệm thật của bản thân; tốn 20–30 phút/ngày; thuật toán ngắt quãng (1, 3, 7, 14, 30 ngày) rất rõ để so sánh Rule vs Workflow | Liệu các app có sẵn như Anki đã giải quyết đủ tốt chưa; AI đem lại giá trị gia tăng gì vượt trội |
| 3 | Sếp/Tester test trực tiếp thấy văng app là chụp màn hình hoặc quay video gửi thẳng qua chat báo "bị lỗi này em ơi" mà không có log hay steps tái hiện (Problem #4) | Pain point kỹ thuật nặng nề nhất; tốn 1–2 tiếng mỗi lần mò mẫm code; AI multimodal có tiềm năng đọc ảnh map vào code | AI có đủ context toàn bộ repo code để phỏng đoán chính xác nguyên nhân crash mà không cần log chi tiết không |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — Soạn tin nhắn báo cáo tiến độ trực tiếp cho sếp sau mỗi bản build TestFlight

```text
Problem 1 câu:
Mỗi khi đẩy bản build mới lên TestFlight (1–2 lần/ngày), Mobile dev mất 15 phút lục lại commit và ghi chú để gõ tin nhắn báo cáo gửi sếp, nhưng sếp đọc lướt rồi vẫn hỏi lại vì tin nhắn thiếu cấu trúc rõ ràng.

Actor:
Mobile developer (người soạn báo cáo) và Sếp / Product Owner (người nhận báo cáo qua chat).

Thời điểm / bối cảnh:
Ngay sau khi hoàn tất xuất build và upload lên TestFlight trong ngày làm việc (1–2 lần/ngày).

Current workflow 3-7 bước:
1. Xcode xuất build và upload lên TestFlight, ngồi chờ Apple process xong (15')
2. Mở terminal gõ git log để rà soát lại các commit đã làm trong ngày (5')
3. Lọc thủ công các commit quan trọng (tính năng mới vs bug fix) và nhớ lại các thay đổi (5')
4. Soạn tin nhắn văn bản tóm tắt: build number, các điểm mới, màn hình sếp cần test (5')
5. Gửi tin nhắn qua app chat (Zalo/Skype/Slack) cho sếp và tester (1')

Bottleneck:
Bước 3 + 4: Lục lại commit và tự viết narrative tóm tắt ngắn gọn, dễ hiểu cho sếp mà không bị sót việc (mất 10 phút).

Impact:
1–2 lần/ngày × 10–15 phút = 15–30 phút/ngày (1.5–2.5 tiếng/tuần). Báo cáo sơ sài làm sếp test nhầm chỗ hoặc hỏi lại nhiều lần gây đứt mạch code.

Success metric:
Giảm thời gian soạn tin nhắn từ 15 phút xuống dưới 3 phút/lần; giảm số câu sếp hỏi lại về nội dung build từ 3–4 lần/tuần xuống 0–1 lần/tuần.

Non-AI alternative:
Tạo template tin nhắn mẫu trong Apple Notes/Notion để copy-paste điền tay. (Hạn chế: vẫn phải tự đọc commit và tự gõ mô tả, dễ lười cập nhật).

AI hypothesis:
AI nhận input là danh sách commit log thô (git log) trong ngày → tự phân loại (Mới / Sửa lỗi / Chú ý khi test) → sinh sẵn tin nhắn tóm tắt ngắn gọn dưới 100 từ → Dev chỉ cần review 30s rồi bấm gửi.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — 31 phút

[1 Check TestFlight: 5'] → [2 Lục Git log: 5'] → [3 Lọc commit: 5'] → [4 Soạn tin nhắn báo sếp: 10']  <-- bottleneck → [5 Gửi & trả lời câu hỏi: 6']

FUTURE STATE — 8 phút

[1 Auto-pull git log: 1'] → [2 AI phân loại & draft tin nhắn: 1'] → [3 Dev review + edit: 3']  <-- human boundary → [4 Gửi tin nhắn qua chat: 1'] → [5 Sếp đọc tin nhắn chuẩn, test ngay: 2']

Fallback: nếu AI tóm tắt sai hoặc ảo giác commit, dev copy template thủ công gõ lại trong 5 phút.
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — Phân bổ & nhắc lịch ôn tập từ vựng tiếng Anh theo phương pháp lặp lại ngắt quãng (Spaced Repetition)

```text
Problem 1 câu:
Mobile dev mất 20–30 phút mỗi ngày tính toán lịch và tự tạo câu ví dụ để ôn từ vựng kỹ thuật theo phương pháp Spaced Repetition, dẫn đến dồn ứ và nản lòng bỏ dở lộ trình.

Actor:
Bản thân (Mobile Developer đang tự học tiếng Anh chuyên ngành).

Thời điểm / bối cảnh:
Đầu giờ sáng hoặc cuối ngày khi dành thời gian học và ôn tập từ vựng tiếng Anh kỹ thuật.

Current workflow 3-7 bước:
1. Gặp từ mới khi đọc tài liệu kỹ thuật / SDK / code review (2')
2. Ghi chép từ mới và nghĩa vào sổ tay hoặc Notion (3')
3. Tính toán các mốc ngày cần ôn (ngày 1, 3, 7, 14, 30) và add vào lịch nhắc nhở (10')
4. Tìm kiếm ngữ cảnh hoặc tự nghĩ câu ví dụ liên quan đến Mobile dev để dễ nhớ (10')
5. Tự kiểm tra và đánh giá mức độ nhớ các từ đến hạn ôn trong ngày (10')

Bottleneck:
Bước 3 + 4: Mất công tự tính chu kỳ ngắt quãng và tự nghĩ câu ví dụ thực tế sát với bối cảnh lập trình mobile (mất 20 phút).

Impact:
20–30 phút/ngày; 3–4 ngày/tuần bị quá tải do lịch ôn dồn cục, dẫn đến tỷ lệ bỏ cuộc sau 2–3 tuần lên tới 70%.

Success metric:
Giảm thời gian lên lịch và tạo ví dụ từ 20 phút xuống dưới 3 phút/ngày; duy trì chuỗi học liên tục ít nhất 21 ngày.

Non-AI alternative:
Dùng ứng dụng Anki hoặc Quizlet có sẵn thuật toán SM-2. (Hạn chế: giao diện Anki phức tạp, mất công nhập thủ công từng thẻ và không tự sinh ví dụ ngữ cảnh dev).

AI hypothesis:
Dev chỉ cần nhập từ vựng + ngữ cảnh gặp phải → AI tự sinh câu ví dụ ngữ cảnh Mobile dev và tự động tính mốc ngày ôn ngắt quãng → gửi thông báo nhắc ôn tập đúng lịch.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — 35 phút

[1 Note từ mới: 3'] → [2 Tính ngày ngắt quãng: 10']  <-- bottleneck → [3 Tự nghĩ ví dụ IT: 10'] → [4 Ôn tập thủ công: 12']

FUTURE STATE — 10 phút

[1 Nhập từ mới: 1'] → [2 AI sinh ví dụ dev + xếp lịch ngắt quãng: 1'] → [3 Dev duyệt qua nghĩa & ví dụ: 2']  <-- human boundary → [4 Nhận nhắc nhở & ôn tập 5 phút: 6']

Fallback: nếu AI sinh ví dụ không chuẩn ngữ cảnh, dev tự sửa lại ví dụ hoặc tra cứu từ điển kỹ thuật có sẵn.
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — Phân tích nguyên nhân lỗi crash từ ảnh chụp màn hình do sếp/tester gửi qua chat

```text
Problem 1 câu:
Khi sếp hoặc tester báo lỗi bằng ảnh chụp màn hình/video qua chat mà không có log, Mobile dev mất 1–2 tiếng mò mẫm phỏng đoán dòng code crash và không tái hiện được lỗi.

Actor:
Mobile developer (người sửa lỗi), Sếp và Tester (người báo lỗi qua chat).

Thời điểm / bối cảnh:
Sau khi đẩy build TestFlight, sếp/tester mở app test và gặp crash bất ngờ.

Current workflow 3-7 bước:
1. Nhận ảnh chụp màn hình hoặc video báo lỗi qua chat (1')
2. Nhắn tin hỏi dồn sếp/tester: bấm nút nào trước đó, dùng máy gì, iOS mấy (10')
3. Mở code dự án, tìm màn hình liên quan và rà soát các hàm có khả năng crash (20')
4. Mở Crashlytics / Sentry tìm xem có session crash nào tương ứng thời gian đó không (20')
5. Tự tái hiện lỗi trên máy dev hoặc mượn máy sếp để debug (30')
6. Sửa code và test lại (15')

Bottleneck:
Bước 3 + 4: Phỏng đoán vị trí code bị lỗi từ giao diện ảnh chụp và đối chiếu với log crash phân tán không rõ ràng (mất 40 phút).

Impact:
2–3 lần/tuần, mỗi lần mất 60–90 phút; làm gián đoạn việc code tính năng mới, gây ức chế khi sếp giục sửa ngay.

Success metric:
Giảm thời gian định vị vùng code nghi vấn từ 40 phút xuống dưới 10 phút; tăng tỷ lệ tái hiện được lỗi ngay trong lần thử đầu tiên lên 80%.

Non-AI alternative:
Bắt buộc sếp/tester cài đặt tool Shake-to-report (như Instabug) để tự động gửi log thiết bị. (Hạn chế: tốn chi phí bản quyền, sếp ngại thao tác, tốn công tích hợp SDK).

AI hypothesis:
Dev đưa ảnh màn hình lỗi vào AI + mô tả ngắn → AI nhận diện UI component, phỏng đoán state/API call tương ứng và chỉ ra top 3 đoạn code trong repo có rủi ro cao nhất kèm câu hỏi cần hỏi sếp để tái hiện lỗi.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — 96 phút

[1 Nhận ảnh qua chat: 1'] → [2 Chat hỏi thêm context: 10'] → [3 Mò code đoán vị trí: 20'] → [4 Tìm Crashlytics: 20']  <-- bottleneck → [5 Tự repro lỗi: 30'] → [6 Sửa code: 15']

FUTURE STATE — 35 phút

[1 Nhận ảnh qua chat: 1'] → [2 AI soi ảnh + gợi ý flow & vị trí code nghi vấn: 3'] → [3 Dev kiểm tra đúng file code: 5']  <-- human boundary → [4 Tái hiện lỗi theo gợi ý: 15'] → [5 Sửa code: 11']

Fallback: nếu AI suy luận sai màn hình, dev quay lại mượn trực tiếp máy của sếp để cắm dây debug vào Xcode.
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Problem Card #1 — Soạn tin nhắn báo cáo tiến độ trực tiếp cho sếp sau mỗi bản build TestFlight.
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
1. Workflow lặp lại hàng ngày (1–2 lần/ngày) rất cụ thể từ git commit đến tin nhắn báo cáo, không phụ thuộc vào công cụ cồng kềnh.
2. Số đo thời gian cực kỳ rõ ràng: giảm từ 15 phút xuống dưới 3 phút/lần, tiết kiệm 1.5–2.5 tiếng/tuần và xóa bỏ tình trạng sếp hỏi lại do tin nhắn thiếu cấu trúc.
3. Rất sát thực tế công ty product nhỏ, nhóm dễ đồng cảm và hoàn toàn khả thi để giải quyết trọn vẹn trong buổi lab 4 tiếng mà không bị trượt sang hệ thống AI quá rộng.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
1. "Nếu dev chỉ commit sơ sài kiểu 'fix bug', 'update UI' thì AI lấy đâu ra ngữ cảnh để viết báo cáo có nghĩa cho sếp, hay lúc đó lại bịa đặt (ảo giác)?"
2. "Liệu bài toán này có thật sự cần đến AI không, hay chỉ cần một Bash script đọc git log điền vào template có sẵn là đã giải quyết được 80% vấn đề?"
```

**AI phản biện Card (nếu có):**

- Điểm yếu AI chỉ ra: AI phản biện rằng bài toán này rất dễ bị giải quyết bằng Rule/Script thông thường nếu commit message đã rõ, và AI có nguy cơ sinh ra tin nhắn quá dài dòng/trang trọng không phù hợp với văn hóa chat nhanh của sếp.
- Tôi sửa gì: Tôi đã siết chặt boundary: AI chỉ đóng vai trò phân loại ngắn gọn (3-4 gạch đầu dòng), giới hạn tin nhắn dưới 100 từ với ngôn từ trực diện, và dev bắt buộc là người duyệt cuối (human boundary) trong 30 giây trước khi bấm gửi.

### Self-check nộp phần 01

- [x] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge

