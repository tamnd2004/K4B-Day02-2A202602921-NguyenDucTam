# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Nguyễn Đức Tâm
- Mã học viên: 2A202602921
- Nhóm: A1-Gold
- Candidate problem nhóm chọn: Những người làm việc/học tập theo dự án thường xuyên bị lỡ các công việc hoặc thông tin quan trọng do bị trôi tin nhắn trong các nhóm chat có quá nhiều "tiếng ồn" (tin nhắn rác, thảo luận không liên quan).

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động                  | Tôi đã làm gì? (việc cụ thể)                                                                                                                                         | Kết quả / ảnh hưởng tới nhóm                                                                                                                          |
| -------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| Scan cá nhân               | Tôi scan 6 problems từ sinh hoạt hằng ngày, sau đó chọn top 3 gồm lên kế hoạch bữa ăn, quản lý task/lịch cá nhân và theo dõi chi tiêu.                               | Nhóm có thêm 3 candidate thuộc nhóm problem cá nhân, trong đó các problem đều có actor, workflow và số đo cụ thể để so sánh.                          |
| Pitch Problem Card         | Tôi pitch Problem Card về việc sinh viên/người trẻ sống tự lập mất nhiều thời gian quyết định ăn gì và đối chiếu nguyên liệu đang có.                                | Giúp nhóm có thêm một candidate có workflow rõ và impact đo được bằng thời gian, số lần mua thiếu và thực phẩm lãng phí.                              |
| Challenge bài của bạn khác | Tôi challenge candidate về tin nhắn nhóm bị trôi ở điểm “tiếng ồn” còn khá cảm tính, đồng thời hỏi cần giới hạn AI được đọc dữ liệu đến đâu để tránh vấn đề privacy. | Nhóm làm rõ rằng pain mạnh nhất ở nhóm chat đông người/thiếu quy ước và bổ sung boundary chỉ xử lý dữ liệu trong phạm vi được cấp quyền.              |
| Gom trùng / cluster        | Với vai trò Facilitator, tôi hỗ trợ nhóm gom các candidate theo pattern chung thay vì tranh luận từng ý riêng lẻ.                                                    | Nhóm hội tụ các ý thành 4 cluster và nhìn rõ cụm quản lý thông tin thời gian thực là cụm phù hợp nhất để shortlist.                                   |
| Chọn candidate problem     | Tôi điều phối phần so sánh shortlist theo actor, workflow, evidence, impact, khả năng làm trong lab và mức độ nhóm hiểu domain.                                      | Nhóm chọn candidate #4 về tin nhắn nhóm bị trôi với tổng điểm cao nhất 33 điểm.                                                                       |
| Validation / research      | Tôi hỗ trợ tổng hợp kết quả interview/poll và đối chiếu các giải pháp đã có như Slack AI, Teams Copilot và Discord.                                                  | Nhóm xác nhận 5/6 người từng bỏ lỡ thông tin/task vì tin nhắn bị trôi và nhận ra khoảng trống nằm ở ưu tiên/gợi ý người cần xử lý, không chỉ tóm tắt. |
| Workflow nhóm              | Tôi hỗ trợ rà lại current/future workflow để phân biệt bước nào là máy/Rule, bước nào AI và bước nào bắt buộc Human Review.                                          | Workflow cuối có boundary rõ: AI xử lý và gợi ý, nhưng người dùng vẫn review trước khi tag, gửi tin hoặc tạo task.                                    |
| Problem Statement          | Tôi góp ý thu hẹp PS từ bài toán “lọc và tóm tắt mọi tin nhắn” sang bài toán cụ thể hơn là fetch context và gợi ý đúng người cần tag.                                | PS v1 có actor, 4 bước workflow, success metric tag đúng ≥85%, thời gian xử lý 3 phút/tin và boundary rõ hơn.                                         |
| Rule / Workflow / Agent    | Tôi cùng nhóm so sánh Rule, Workflow và Agent dựa trên độ mơ hồ, độ phức tạp và nhu cầu fetch context động.                                                          | Nhóm chọn Agent cho bước phân tích context/gợi ý tag, nhưng vẫn dùng Workflow làm khung tổng thể và giữ Human Review để kiểm soát rủi ro.             |
| Decision                   | Tôi tham gia chốt tiêu chí Go/Not Yet/No-Go và điều kiện rollback trước khi nhóm quyết định.                                                                         | Nhóm quyết định Go với pilot nhỏ trên 1 nhóm dự án 5–10 người, 50 tin nhắn; rollback nếu độ chính xác tag dưới 60% hoặc review chậm hơn baseline.     |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Dấu tay rõ nhất của tôi là vai trò Facilitator trong quá trình hội tụ từ nhiều candidate về một bài toán chung, đặc biệt ở việc yêu cầu nhóm làm rõ actor, metric, boundary và lý do chọn Agent thay vì chọn vì “ngầu”. Tôi cũng góp phần giữ Human Review là điểm kiểm soát bắt buộc trước khi Agent thực hiện hành động thật.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase                   | Tôi dùng AI để làm gì?                                                                  | AI hữu ích ở đâu?                                                                                | AI sai / hời hợt ở đâu?                                                                           | Tôi sửa gì bằng nhận định của mình?                                                                                            |
| ----------------------- | --------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------ |
| Scan                    | Nhờ AI gợi ý thêm các problem đời sống có thể đo bằng thời gian, tần suất hoặc chi phí. | Giúp mở rộng góc nhìn và gợi ý các problem như meal planning, task management, expense tracking. | Một số ý quá rộng như thiếu động lực, ngủ không đủ hoặc “sống healthy hơn”, không có workflow rõ. | Tôi bỏ các ý không có actor/bottleneck cụ thể và chỉ giữ problem có thể đo được bằng số.                                       |
| Problem Card            | Nhờ AI phản biện top 3 và gợi ý cách viết bottleneck, impact, success metric.           | Giúp cấu trúc Card rõ hơn và tách được current workflow với future workflow.                     | AI có xu hướng đề xuất automation quá sớm khi chưa chứng minh pain đủ rõ.                         | Tôi giữ non-AI alternative và human boundary để không mặc định problem nào cũng cần AI.                                        |
| Workflow                | Dùng AI để kiểm tra xem flow đã phân biệt Rule, AI, Human và fallback rõ chưa.          | Giúp phát hiện các bước có thể gom/tự động hóa và vị trí cần Human Review.                       | AI dễ làm future workflow quá “đẹp”, bỏ qua khả năng gắn nhãn sai hoặc hiểu sai context.          | Tôi giữ bước mở lại tin nhắn gốc, Human Review và fallback về cách xử lý thủ công.                                             |
| Research                | Dùng AI để gợi ý các tool/pattern tương tự cần tìm hiểu.                                | Giúp định hướng nhanh đến Slack AI, Teams Copilot và các pattern tóm tắt/digest.                 | AI có thể đưa claim về tính năng hoặc hiệu quả mà chưa có nguồn kiểm chứng.                       | Tôi chỉ giữ các ý có thể đối chiếu với nguồn chính thức và không dùng số liệu chưa verify.                                     |
| Problem Statement       | Nhờ AI challenge các field còn mơ hồ trong PS v0.                                       | AI chỉ ra Impact còn chung chung và Boundary chưa rõ phạm vi dữ liệu được đọc.                   | AI ban đầu mở scope quá rộng sang lọc, tóm tắt, tạo task và gửi phản hồi cùng lúc.                | Tôi cùng nhóm thu hẹp PS v1 vào fetch context + gợi ý tag, có metric và boundary cụ thể.                                       |
| Rule / Workflow / Agent | Dùng AI để so sánh khi nào Rule, Workflow hoặc Agent phù hợp với cùng một problem.      | Giúp nhóm nhìn rõ Agent chỉ hợp lý khi phải fetch context động và suy luận ngữ cảnh.             | AI dễ mặc định Agent là phương án mạnh nhất nếu chỉ nhìn vào độ phức tạp.                         | Tôi đối chiếu lại với 5 câu hỏi chốt và giữ Workflow làm khung, Agent chỉ dùng ở bước thật sự cần.                             |
| Decision                | Dùng AI để phản biện tiêu chí Go và gợi ý điều kiện rollback/pilot nhỏ.                 | Giúp biến quyết định thành các tiêu chí đo được thay vì chỉ nói “ý tưởng hay”.                   | AI có thể đặt threshold tùy ý nếu không gắn với baseline.                                         | Tôi giữ các chỉ số nhóm đã chốt: tag đúng ≥85%, 3 phút/tin và rollback nếu độ chính xác dưới 60% hoặc review chậm hơn cách cũ. |

> Nếu phase nào không dùng AI, ghi `Không dùng` và vì sao tự làm.

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
Khi nghe top 3 problems của các bạn khác, tôi nhận ra một problem tốt không nhất thiết phải là ý tưởng phức tạp nhất mà phải có actor, workflow và pain đủ rõ để kiểm chứng. Ban đầu tôi thiên về các problem gần với đời sống cá nhân như lên kế hoạch bữa ăn vì dễ hình dung và có số liệu cụ thể. Tuy nhiên, sau khi nhóm cluster và chấm điểm, tôi đồng ý chuyển sang bài toán tin nhắn nhóm bị trôi vì vấn đề này có tính đại diện cho cả nhóm và có thể validate nhanh hơn. Trong quá trình thảo luận, tôi thấy nhóm có lúc khá dễ bị solution-first khi nói đến Agent trước khi boundary và metric được làm rõ. Vì vậy, với vai trò Facilitator, tôi tập trung kéo cuộc thảo luận về các câu hỏi: AI cần can thiệp đúng bước nào, sai thì ai kiểm tra, và Rule hoặc Workflow có đủ không. Điều khó nhất với tôi khi viết Problem Statement là boundary, vì nếu cho AI quá nhiều quyền thì solution có vẻ mạnh nhưng rủi ro privacy và gợi ý sai người cũng tăng theo. Sau validation, tôi thấy việc 5/6 người từng bỏ lỡ thông tin vì tin nhắn bị trôi là bằng chứng đủ mạnh để giữ problem, nhưng chưa đủ để cho AI tự hành động. Tôi đồng ý với thiết kế Human Review trước khi tag hoặc tạo task vì đây là điểm cân bằng giữa tự động hóa và kiểm soát. Dấu tay rõ nhất của tôi trong artifact cuối là quá trình giúp nhóm hội tụ, làm rõ metric/boundary và không chọn Agent chỉ vì nó nghe mạnh hơn. Nếu làm lại, tôi sẽ challenge mạnh hơn ở baseline thời gian và độ chính xác, vì một số metric hiện tại vẫn là mục tiêu kỳ vọng và cần pilot thực tế để xác nhận.
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
