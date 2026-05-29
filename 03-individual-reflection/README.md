# 03 - Individual Reflection

## Case nhóm: Tư vấn và phản hồi inbox đa kênh cho shop online nhỏ

Bài nhóm chọn vấn đề: một shop online nhỏ bán hàng trên nhiều kênh như Facebook, Zalo, TikTok Shop và Shopee phải xử lý nhiều tin nhắn khách hàng mỗi ngày. Tin nhắn liên quan đến giá sản phẩm, tình trạng hàng, size, phí vận chuyển, thời gian giao hàng, trạng thái đơn và yêu cầu đổi trả. Vì thông tin nằm rải rác ở nhiều nền tảng, chủ shop hoặc nhân viên CSKH dễ bỏ sót khách, phản hồi chậm hoặc trả lời sai thông tin.

---

# 1. Đóng góp của Chung trong nhóm

| Hoạt động               | Chung đã làm gì?                                                                                                                                                 | Kết quả                                                                                           |
| ----------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------- |
| Scan cá nhân            | Đưa ra case shop online nhận tin nhắn khách hàng từ nhiều kênh như Facebook, Zalo, TikTok Shop và Shopee                                                         | Nhóm có một candidate rõ về inbox đa kênh, có actor, workflow và pain cụ thể                      |
| Top 3 Problem Cards     | Chọn 3 vấn đề chính: tin nhắn khách hàng nhiều kênh, câu hỏi lặp lại, đổi trả/khiếu nại khó theo dõi                                                             | Nhóm có thêm input để so sánh với các bài cá nhân khác                                            |
| Pitch                   | Pitch problem "tin nhắn khách hàng nhiều kênh" với bottleneck là đọc, phân loại tin và tìm thông tin trước khi trả lời                                           | Bài của Chung được đưa vào cluster "Inbox / CSKH đa kênh"                                         |
| Challenge               | Đặt câu hỏi liệu shop nhỏ có thật sự cần AI không hay chỉ cần inbox chung, template và auto-reply                                                                | Nhóm không nhảy thẳng sang Agent, mà phân biệt rõ Rule, Workflow và Agent                         |
| Workflow                | Góp phần xây current workflow và future workflow: kiểm tra nhiều kênh -> phân loại intent -> tra thông tin -> trả lời, sau đó chuyển thành workflow có AI hỗ trợ | Nhóm có workflow trước/sau rõ hơn, nhìn được bottleneck và human boundary                         |
| Metric                  | Đề xuất các metric như tổng thời gian xử lý inbox, thời gian phản hồi FAQ, số tin bị bỏ sót, số câu trả lời sai/cần sửa                                          | Problem Statement có metric đo được, không chỉ nói "nhanh hơn" hoặc "tốt hơn"                     |
| Boundary                | Góp ý AI không được tự gửi tin, không tự chốt đơn, không tự hoàn tiền, không tự hứa đổi trả                                                                      | Nhóm kiểm soát rủi ro tốt hơn, tránh biến bài thành Agent quá rộng                                |
| Rule / Workflow / Agent | Lập luận chọn Workflow vì AI chỉ nên phân loại intent và gợi ý câu trả lời, còn người thật review trước khi gửi                                                  | Nhóm thống nhất chọn Workflow thay vì Agent                                                       |
| Decision                | Đồng ý với quyết định "Go for offline prototype / Not Yet for live deployment"                                                                                   | Quyết định cuối hợp lý hơn vì có thể thử trong lab nhưng chưa triển khai live khi thiếu data thật |
| Sửa bài nhóm            | Góp ý sửa baseline, thêm cách đo metric, thêm bảng 9 candidates và làm rõ scope pilot                                                                            | Bản group statement chặt hơn và bám rubric chấm điểm hơn                                          |

---

# 2. Bảng dùng AI trong quá trình làm bài

| Phase                   | Tôi dùng AI để làm gì?                                                                                              | AI hữu ích ở đâu?                                                                                    | AI sai/hời hợt ở đâu?                                                                                | Tôi sửa gì bằng nhận định của mình?                                                                   |
| ----------------------- | ------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- |
| Scan cá nhân            | Nhờ AI gợi ý thêm các vấn đề quanh shop online, CSKH, tin nhắn đa kênh, FAQ và đổi trả                              | AI giúp mở rộng từ một bối cảnh ban đầu thành nhiều problem candidates có actor và pain khác nhau    | AI có xu hướng đề xuất "xây chatbot" quá sớm, trong khi bài yêu cầu problem first                    | Tôi giữ lại các problem có workflow thật, bỏ các ý quá solution-first                                 |
| Problem Card            | Nhờ AI chuẩn hóa Problem Card: actor, workflow, bottleneck, impact, metric, non-AI alternative, AI hypothesis       | AI giúp biến mô tả đời thường thành cấu trúc bài nộp rõ ràng                                         | Một số metric ban đầu còn ước lượng, chưa có cách đo cụ thể                                          | Tôi ghi rõ baseline là giả định cần validate và thêm cách đo cho từng metric                          |
| Workflow                | Nhờ AI chuyển mô tả thành workflow current state và future state                                                    | AI giúp tách các bước trong quy trình và chỉ ra AI nằm ở đâu                                         | AI đôi lúc gộp nhiều bước lại, ví dụ vừa gửi phản hồi vừa chuyển đơn sang đóng gói làm scope bị rộng | Tôi tách rõ workflow chính là phản hồi inbox, còn chuyển đơn chỉ là nhánh phụ nếu khách chốt          |
| Mermaid diagram         | Nhờ AI viết Mermaid để GitHub render workflow                                                                       | Nhanh hơn khi tạo sơ đồ before/after trong README                                                    | Mermaid ban đầu hơi dài và có vài node chưa rõ human boundary                                        | Tôi sửa lại nhãn để thấy bottleneck, AI step và human review rõ hơn                                   |
| Group convergence       | Nhờ AI tổng hợp 3 bài cá nhân thành bảng cluster và shortlist                                                       | AI giúp gom các candidate trùng pattern như inbox đa kênh, FAQ, gom đơn, khiếu nại, review xấu       | AI ban đầu ghi "khoảng 9-12 candidates" dù nhóm có 3 người, mỗi người top 3 nên phải là 9            | Tôi sửa thành đúng "3 người x 3 problems = 9 candidates" và thêm bảng 9 candidates ban đầu            |
| Research                | Nhờ AI gợi ý các tool/pattern như Meta Business Suite Inbox, Zalo OA, Shopee Auto-Reply, TikTok Shop Chat Assistant | AI giúp thấy thị trường đã có pattern: inbox chung, auto-reply, gợi ý câu trả lời, người thật review | Một số tool có thể cần quyền API hoặc chưa phù hợp pilot 4 tiếng                                     | Tôi không claim build full integration, chỉ dùng research để rút ra pattern và chọn offline prototype |
| Problem Statement       | Nhờ AI phản biện Problem Statement v0 và đề xuất v1                                                                 | AI giúp chỉ ra phần thiếu như metric, boundary, AI intervention point, risk và người thật kiểm tra   | AI đôi lúc viết quá rộng, bao gồm cả chốt đơn, đổi trả, hoàn tiền                                    | Tôi thu hẹp scope: AI chỉ phân loại intent và gợi ý bản nháp trả lời, không tự xử lý case nhạy cảm    |
| Rule / Workflow / Agent | Nhờ AI so sánh No AI, Rule, Workflow, Agent                                                                         | AI giúp lập luận vì sao Rule chưa đủ và Agent quá rủi ro                                             | AI có xu hướng làm solution lớn hơn cần thiết                                                        | Tôi chốt Workflow và thêm bảng AI được phép làm gì theo từng intent                                   |
| Final decision          | Nhờ AI kiểm tra decision theo rubric                                                                                | AI giúp phát hiện "Go" quá mạnh khi data vẫn Not Yet                                                 | Nếu để "Go" chung chung thì dễ bị hiểu là triển khai live ngay                                       | Tôi sửa thành "Go for offline prototype / Not Yet for live deployment"                                |

---

# 3. Bài học cá nhân

Qua bài Day 02, tôi học được rằng một problem tốt không phải là problem nghe có vẻ "AI" nhất, mà là problem có actor rõ, workflow rõ, bottleneck rõ và metric đo được. Ban đầu, tôi nghĩ bài toán shop online đơn giản là "làm chatbot trả lời khách". Nhưng khi vẽ workflow, tôi nhận ra vấn đề thật không nằm ở chatbot, mà nằm ở việc shop phải xử lý tin nhắn từ nhiều kênh, tự đọc từng tin, tự phân loại ý định, tự tra thông tin rồi mới trả lời.

Tôi cũng học được rằng không nên chọn Agent ngay từ đầu. Với case này, Agent nghe có vẻ mạnh, nhưng rủi ro cao vì AI có thể tự trả lời sai giá, sai size, sai tồn kho, tự hứa đổi trả hoặc xử lý nhầm khiếu nại. Workflow hợp lý hơn vì AI chỉ hỗ trợ một số bước cụ thể như phân loại intent và gợi ý câu trả lời, còn người thật vẫn review trước khi gửi.

Việc so sánh No AI / Rule / Workflow / Agent giúp nhóm nhìn rõ hơn phần nào không cần AI. Ví dụ, quick reply, template hoặc auto-reply theo keyword có thể xử lý một phần FAQ đơn giản. Tuy nhiên, khi khách hỏi bằng nhiều kiểu khác nhau, viết tắt, sai chính tả hoặc hỏi nhiều ý trong một tin nhắn, AI mới có giá trị hơn Rule.

Tôi cũng thấy metric rất quan trọng. Nếu chỉ viết "trả lời nhanh hơn" thì không đủ. Nhóm cần có baseline, target và cách đo rõ ràng, ví dụ: tổng thời gian xử lý inbox/ngày, thời gian phản hồi FAQ, thời gian xử lý một tin lặp, tỷ lệ AI phân loại intent đúng, tỷ lệ câu trả lời dùng được sau chỉnh nhẹ và số lỗi nghiêm trọng do AI.

---

# 4. Điều tôi làm tốt

* Không bắt đầu bằng "xây chatbot", mà bắt đầu từ bối cảnh và workflow của shop online.
* Đưa ra problem có actor rõ: chủ shop hoặc nhân viên CSKH.
* Đưa ra workflow có bottleneck cụ thể: phân loại tin, tra thông tin và gõ câu trả lời.
* Biết challenge nhóm về việc có cần AI không hay chỉ cần Rule/template.
* Góp phần giữ scope nhỏ: offline prototype trước, chưa triển khai live.
* Góp ý boundary để AI không tự gửi tin, không tự chốt đơn, không tự xử lý đổi trả.

---

# 5. Điều tôi chưa làm tốt

* Baseline ban đầu còn ước lượng nhiều, chưa có log tin nhắn thật từ một shop cụ thể.
* Một số metric ban đầu chỉ đo theo ngày, chưa đủ để chứng minh tác dụng thật của AI.
* Phần future workflow ban đầu còn trộn giữa pilot Google Sheet và future inbox thật.
* Một số bước như "chuyển đơn sang file đóng gói" có thể làm scope bị rộng nếu không ghi là nhánh phụ.
* Research chủ yếu dùng để hiểu pattern, chưa kiểm chứng sâu từng API hoặc chi phí triển khai thật.

---

# 6. Nếu làm lại, tôi sẽ đổi gì?

Nếu làm lại, tôi sẽ validate sớm hơn bằng cách lấy một bộ 50-100 tin nhắn thật hoặc tin mô phỏng sát thực tế. Tôi sẽ đo thủ công trước trên cùng bộ tin nhắn, sau đó đo lại khi dùng workflow AI hỗ trợ. Như vậy nhóm có thể chứng minh AI thật sự giúp giảm thời gian xử lý từng tin, chứ không chỉ giảm tổng thời gian theo ngày.

Tôi cũng sẽ tách rõ hơn giữa pilot và sản phẩm thật. Trong pilot, Google Sheet là đủ để test phân loại intent và gợi ý câu trả lời. Nhưng với shop thật, Google Sheet không phải inbox tốt vì không realtime và dễ quên copy dữ liệu. Vì vậy, future state thật nên là inbox/tool gom tin, còn Google Sheet chỉ là cách mô phỏng trong lab.

Tôi sẽ làm rõ metric theo 2 tầng:

1. Metric vận hành theo ngày: tổng thời gian xử lý inbox, tin chưa xử lý cuối ngày, số đơn mất do phản hồi chậm.
2. Metric chứng minh AI theo từng tin nhắn: thời gian xử lý một tin lặp, intent accuracy, tỷ lệ câu trả lời dùng được, số lỗi nghiêm trọng.

Cuối cùng, tôi sẽ giữ decision thận trọng hơn: Go cho offline prototype, nhưng Not Yet cho live deployment. Điều này hợp lý hơn vì nhóm chưa có data live, chưa có API đầy đủ và chưa kiểm chứng độ chính xác trên dữ liệu thật.

---

# 7. Reflection ngắn

Bài lab này giúp tôi hiểu rằng AI Product không phải là chọn một mô hình AI rồi gắn vào problem. Cách làm đúng là đi từ workflow hiện tại, tìm bottleneck, xác định metric, đặt boundary, sau đó mới quyết định AI có phù hợp không. Với case shop online, AI có ích nhưng chỉ nên là một phần trong workflow. Người thật vẫn phải kiểm tra ở các bước có rủi ro như giá, size, tồn kho, trạng thái đơn hàng, đổi trả và khiếu nại.

Điều quan trọng nhất tôi học được là: Workflow tốt thường thực tế hơn Agent. Agent chỉ nên được cân nhắc khi dữ liệu sạch, API ổn định, quyền hạn rõ và rủi ro đã được kiểm soát. Trong bài này, Workflow là lựa chọn hợp lý vì nó giảm tải cho chủ shop/CSKH nhưng vẫn giữ người thật ở điểm quyết định cuối.
