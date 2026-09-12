# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Nguyễn Đình Phúc
- Mã học viên: 2A202602953
- Nhóm: Biệt đội ánh sáng
- Candidate problem nhóm chọn: Tự kê khai thuế 01/CNKD hằng quý

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động                  | Tôi đã làm gì? (việc cụ thể)                                                                                                                                                             | Kết quả / ảnh hưởng tới nhóm                                                                                             |
| -------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------ |
| Scan cá nhân               | Scan 10 problem từ thực tế làm Mobile dev (báo cáo TestFlight, crash app không log, spaced repetition).                                                                                  | Đóng góp 3 candidate (#4, #5, #6) vào kho chung 15 bài của nhóm.                                                         |
| Pitch Problem Card         | Pitch Problem #4 (Báo cáo tiến độ TestFlight cho sếp, lặp 1-2 lần/ngày, mất 15'/lần).                                                                                                    | Bài #4 được nhóm đánh giá cao, lọt top shortlist (34/35 điểm).                                                           |
| Challenge bài của bạn khác | Challenge bài thuế #10 của Long về rủi ro pháp lý cao, nguy cơ phạt nếu AI cộng sai và khó làm trong lab.                                                                                | Buộc nhóm phải hạ scope từ "AI nộp thuế tự động" xuống "Sandbox đối chiếu nháp + giải thích field".                      |
| Gom trùng / cluster        | Gom 15 bài thành 4 cụm theo luồng công việc; cùng nhóm chia việc theo thế mạnh.                                                                                                          | Gom gọn được 4 cụm rõ ràng, ai cũng có phần việc riêng và bắt tay vào làm ngay, không bị đùn đẩy.                        |
| Chọn candidate problem     | Thấy bài thuế #10 của Long thực tế và đáng làm hơn bài TestFlight của mình nên tôi đề xuất nhóm chọn bài #10, đồng thời góp ý cách thu hẹp phạm vi vào bản nháp để tránh rủi ro pháp lý. | Cả 5 người đồng thuận chấm bài #10 được 35/35 điểm và chốt làm bài này.                                                  |
| Validation / research      | Khảo sát nhanh (micro-poll) 8 bạn trong lớp có người thân làm hộ kinh doanh và rà soát các bài báo thực tế tại Bắc Ninh, DHTaxLaw.                                                       | Bổ sung số liệu thực tế vào bảng 4.1: 6/8 người thân phải kê 01/CNKD, 5/8 thấy điền chỉ tiêu khó nhất, 3/8 thuê đại lý.  |
| Workflow nhóm              | Tham gia phản biện luồng 7 bước hiện tại và 6 bước tương lai do Long vẽ; yêu cầu tách rõ bước Human Review.                                                                              | Workflow thể hiện rõ 5 thành phần: Rule, AI, Người, Boundary và Fallback khi AI sai.                                     |
| Problem Statement          | Làm writer cùng Đức: viết bản Problem Statement v0 và v1, điền cụ thể các mốc thời gian và chi phí.                                                                                      | Có bản Problem Statement đủ 6-7 mục với số đo cụ thể (giảm từ ~4 giờ xuống dưới 60 phút) và ghi rõ AI không được làm gì. |
| Rule / Workflow / Agent    | Viết bảng so sánh Rule / Workflow / Agent và trả lời 5 câu hỏi chốt; cùng nhóm chọn Workflow vì các bước kê khai đi theo đường thẳng và cần người chịu trách nhiệm số liệu.              | Nhóm thống nhất chọn Workflow thay vì làm Agent tự động, tránh được rủi ro pháp lý.                                      |
| Decision                   | Viết phần quyết định: chốt Go ở mức sandbox để thử nghiệm trong lab; lên kế hoạch thử trên 1 quý hóa đơn giả lập và ghi rõ khi nào dừng.                                                 | Nhóm có kế hoạch thử nghiệm cụ thể và điều kiện dừng rõ ràng (nếu AI sai >70% thì quay về dùng Excel).                   |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Dấu tay rõ nhất của tôi là liên kết các thành viên với nhau, sau đó giao việc để ai cũng có nhiệm vụ riêng biệt và có thể phát huy tốt vai trò base của mình
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase                   | Tôi dùng AI để làm gì?                                                         | AI hữu ích ở đâu?                                                          | AI sai / hời hợt ở đâu?                                                                                      | Tôi sửa gì bằng nhận định của mình?                                                                                                                       |
| ----------------------- | ------------------------------------------------------------------------------ | -------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Scan                    | Gợi ý thêm các góc nhìn phản biện theo 4 lăng kính từ bối cảnh dev công ty nhỏ | Gợi ý nhanh các pain point về việc giao việc miệng và chờ đợi TestFlight   | AI hay đưa ra các vấn đề chung chung như "họp hành nhiều", "viết tài liệu PRD" (vốn không có ở cty nhỏ)      | Lọc bỏ toàn bộ các pain sáo rỗng, chỉ giữ lại các vấn đề sát sườn kèm số đo thời gian thực tế hàng ngày (1-2 lần/ngày, 15 phút/lần).                      |
| Problem Card            | Tạo draft cấu trúc thẻ Problem Card và đặt câu hỏi tự vấn                      | Giúp khung sườn chuẩn hóa, không bị sót actor hay trigger                  | Đề xuất metric rất mơ hồ kiểu "tăng hiệu suất làm việc 50%", "cải thiện giao tiếp"                           | Tự viết lại metric định lượng bằng thời gian cụ thể (15 phút → 3 phút) và tỉ lệ sếp không cần hỏi lại.                                                    |
| Workflow                | Gợi ý các bước phân rã quy trình trước/sau                                     | Liệt kê được các bước thao tác cơ bản trên cổng điện tử                    | AI luôn đề xuất luồng "Agent tự động hóa 100% từ đọc hoá đơn đến nộp thuế", bỏ qua rủi ro pháp lý            | Tách luồng thành 6 bước rõ ràng, cài cắm Human Boundary bắt buộc ở bước review số liệu và bước tự bấm nộp trên eTax.                                      |
| Research                | Tìm kiếm các văn bản pháp luật và quy định liên quan đến hộ kinh doanh 2026    | Gợi ý được từ khóa Thông tư 18/2026/TT-BTC, Thông tư 50/2026, mẫu 01/CNKD  | AI tự bịa ra một số mốc thời hạn nộp thuế không có thực và trích dẫn số liệu thống kê không kiểm chứng được  | Tự tra cứu link bài viết chính thống (Bắc Ninh TV, BNEWS, Cổng DVC) và kiểm tra lại đúng văn bản pháp luật hiện hành.                                     |
| Problem Statement       | Rà soát câu chữ cho súc tích, chuyên nghiệp                                    | Gợi ý cách diễn đạt ngắn gọn các trường Actor và Bottleneck                | Viết câu chữ mang tính quảng cáo sản phẩm ("giải pháp toàn diện, đột phá"), lẫn lộn giữa Problem và Solution | Viết lại toàn bộ theo góc nhìn nỗi đau của chủ hộ kinh doanh, gọt giũa từng câu và đặt Success Metric có baseline và cách đo cụ thể.                      |
| Rule / Workflow / Agent | Thử thách phản biện: "Tại sao không dùng Rule đơn thuần hoặc Agent tự trị?"    | Đưa ra được các góc so sánh về chi phí phát triển và độ phức tạp tính toán | AI thiên vị Agent, cố vẽ ra viễn cảnh "Agent đa tác nhân tự đàm phán với cơ quan thuế" rất phi thực tế       | Khẳng định ma trận "Độ phức tạp cao × Độ mơ hồ thấp", bảo vệ lập luận Workflow là tối ưu nhất vì quy trình tuyến tính và cần người thật chịu trách nhiệm. |
| Decision                | Giả lập các câu hỏi chất vấn về rủi ro khi Go Production                       | Gợi ý các góc nhìn về vi phạm an toàn dữ liệu và sai sót số liệu kế toán   | AI đưa ra quyết định ba phải, không dám chốt Go hay No-Go cụ thể                                             | Tự ra quyết định "Go với scope nhỏ (Sandbox)", đặt ra ngưỡng dừng (rollback) rõ ràng: nếu sai >70% draft thì quay về dùng bảng Excel + checklist.         |

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
Từ Phase 3 đến Phase 6, tôi rút ra được khá nhiều, cả về cách nhìn nhận vấn đề lẫn cách phối hợp nhóm. Tôi là người đứng ra chia việc cho 5 đứa theo đúng thế mạnh. Lúc nghe 3 problem đầu của mọi người, tôi thấy bài thuế 01/CNKD của Long hay nhất, vì đây là vấn đề rất nhiều hộ kinh doanh đang gặp khi chuyển từ thuế khoán sang kê khai. Bài TestFlight của tôi an toàn hơn, nhưng tôi vẫn quyết định đề xuất cả nhóm dồn vào bài thuế, vì thấy nó khó hơn thật nhưng giá trị thực tế lớn hơn nhiều. Ban đầu tôi lo bài này rủi ro pháp lý cao, nhưng sau khi challenge Long thì nhóm thống nhất chỉ làm Sandbox đối chiếu nháp chứ không để AI nộp thay, nên tôi yên tâm nhận phần viết Problem Statement cùng Đức. Trong lúc làm workflow, AI từng xui nhóm làm Agent tự động 100% khâu nộp thuế, nhưng tôi gạt đi ngay vì nếu AI đọc sai hóa đơn thì hộ kinh doanh sẽ bị phạt. Ở bước viết Problem Statement, AI cũng viết rất sáo rỗng kiểu "giải pháp đột phá", buộc tôi phải tự tay sửa lại từng chỉ tiêu theo đúng nỗi đau thực tế. Khó khăn lớn nhất là số đo thời gian chưa thật chuẩn xác. Nếu được làm lại, tôi sẽ thúc nhóm đi phỏng vấn thực địa sớm hơn để có số liệu bấm giờ thật ngay từ đầu.
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
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI
