# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Đinh Văn Bình
- Mã học viên: 2A202602830
- Nhóm: Nhóm Hí ộ (Nguyễn Thành Vinh, Trần Hữu Đức, Đinh Văn Bình, Doãn Hữu Nguyên, Tô Huy Thông)
- Candidate problem nhóm chọn: Lọc slide hoặc PDF dài để tạo bản đồ nội dung ưu tiên theo learning objectives.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Tự scan 7 problems từ đời sống sinh viên (xe bus, điểm danh, workshop, CSVC, việc làm cựu SV, họp nhóm, lọc slide bài giảng) với đầy đủ metric và bằng chứng số liệu. | Đóng góp 3 candidate đa dạng vào kho ý tưởng chung của nhóm; có 1 candidate về lọc slide bài giảng được nhóm đưa vào làm bằng chứng cho cluster A. |
| Pitch Problem Card | Pitch Problem Card #1 (Tra cứu quyền lợi & quy chế CSVC trường) trong 2 phút: phân tích rõ workflow 5 bước, bottleneck ở khâu tra cứu PDF dài, metric giảm từ 20' xuống <1'. | Giúp nhóm thảo luận sâu về tính khả thi của bài toán RAG trên tài liệu nội bộ và các rào cản truy cập dữ liệu chính thống của trường. |
| Challenge bài của bạn khác | Challenge bài "Theo dõi hạn VPS/domain" của Vinh và "Gom task/deadline" của Thông: chỉ ra Rule/Cronjob hoặc Google Calendar đã giải quyết được 80%, chưa cần dùng đến AI. | Giúp nhóm loại bỏ sớm các bài toán quá nghiêng về Rule/Process fix đơn thuần để tập trung vào bài toán thực sự cần hiểu ngữ cảnh. |
| Gom trùng / cluster | Cùng nhóm phân loại 15 candidates thành 4 cụm (A: Học & tra cứu tài liệu, B: Báo cáo & tiến độ, C: Task & lịch, D: Hạ tầng kỹ thuật). | Nhận diện cụm A là cụm có pain point chung mạnh nhất khi có tới 4/5 thành viên cùng gặp vấn đề tìm và lọc tài liệu học tập. |
| Chọn candidate problem | Tham gia chấm điểm ma trận 8 tiêu chí và cùng nhóm đồng thuận chọn bài toán "Lọc slide/PDF theo mục tiêu học" (đạt điểm cao nhất: 34/40). | Giúp nhóm chốt được đề tài vừa sức pilot trong thời gian lab (1 slide deck, 1 learning objective), không bị trượt sang hệ thống quá lớn. |
| Validation / research | Cung cấp baseline cá nhân: mất 45–60 phút/môn để đọc lọc slide 60–80 trang; đồng thời chỉ ra rủi ro không nên dùng claim "70% sinh viên không đọc" khi chưa có khảo sát thực tế. | Nhóm đưa số liệu baseline 45–60 phút của tôi vào bảng Quick Validation (Mục 4.1) và giữ định hướng kiểm chứng thận trọng. |
| Workflow nhóm | Đóng góp bước "Human boundary" và cơ chế trích dẫn nguồn (số trang, đề mục) trong quy trình Future State; đề xuất Fallback khi AI không trích được trang gốc. | Workflow nhóm có ranh giới kiểm soát rủi ro rõ ràng, không để AI tóm tắt tùy tiện mà bắt buộc sinh viên phải đối chiếu trang slide gốc. |
| Problem Statement | Phản biện bản v0 (quá chung chung về "tổng hợp kiến thức") để nhóm thu hẹp thành bản v1 tập trung vào "bản đồ nội dung ưu tiên theo learning objective". | Problem Statement v1 chặt chẽ, có boundary rõ (AI chỉ lọc trang liên quan, không tóm tắt thay việc học của sinh viên). |
| Rule / Workflow / Agent | Phân tích vì sao bài này chỉ nên dừng ở mức `Workflow` (RAG trích xuất theo mục tiêu) chứ không nên nhảy lên `Agent` hay chỉ dùng `Rule` từ khóa. | Nhóm thống nhất 100% chọn phương án Workflow, tránh bẫy ham làm Agent phức tạp không kiểm soát được độ chính xác. |
| Decision | Thống nhất với nhóm ra quyết định "Pilot có điều kiện" (Go có điều kiện) trước khi quyết định mở rộng. | Nhóm có kế hoạch pilot thực tế trong lab với 1 slide deck thật và 5 sinh viên thử nghiệm trước khi xây dựng sản phẩm lớn. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Tôi là người kiên trì bảo vệ yêu cầu bắt buộc AI phải trích dẫn đúng số trang và đề mục gốc vào bước Human Boundary trong workflow, ngăn chặn rủi ro sinh viên tin tưởng mù quáng vào bản tóm tắt bịa đặt (hallucination); đồng thời đóng góp số liệu baseline thực tế mất 45–60 phút khi đọc lọc slide 60–80 trang được ghi nhận trong bảng validation của nhóm.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Mở rộng góc nhìn và phản biện 5 vấn đề ban đầu của bản thân. | Gợi ý cách quy đổi từ "than phiền chính sách" sang "điểm nghẽn quy trình" và bổ sung các lăng kính còn thiếu. | Gợi ý một số problem chung chung không có trải nghiệm thật (như quản lý chi tiêu sinh viên). | Bỏ các gợi ý sáo rỗng, giữ lại các vấn đề bản thân thực sự trải qua (xe bus, điểm danh QR, CSVC, lọc slide bài giảng). |
| Problem Card | Đóng vai Skeptical Product Manager để "bắt bẻ" Problem Card #1 trước khi mang đi pitch. | Chỉ ra điểm yếu chí mạng: quy định văn bản mâu thuẫn với thực tế bảo vệ thực thi, và rủi ro phạm vi actor quá rộng. | Đòi hỏi phải có survey diện rộng ngay lập tức (không khả thi trong thời gian làm lab). | Tự thu hẹp actor thành sinh viên hệ đào tạo thực chiến và bổ sung fallback hiển thị hotline quản lý CSVC. |
| Workflow | Viết script render sơ đồ workflow trực quan và tính toán thời gian Before/After. | Giúp cấu trúc hóa 2 luồng rõ ràng, trực quan hóa vị trí bottleneck và human boundary. | AI có xu hướng tự động hóa 100% các bước, bỏ qua khâu kiểm tra thủ tục của con người. | Tôi tự đặt lại bước Human Boundary bắt buộc người dùng đối chiếu trích dẫn gốc trước khi đến phòng ban. |
| Research | Tra cứu các giải pháp lọc tài liệu và pattern công nghệ RAG/Semantic Search hiện có. | Tổng hợp nhanh các công cụ như NotebookLM, ChatPDF và cơ chế chunking tài liệu dài. | Không đánh giá được hạn chế khi slide có nhiều sơ đồ, hình ảnh đồ họa phức tạp. | Cùng nhóm xác định phạm vi pilot chỉ áp dụng với slide có cấu trúc chữ rõ ràng và mục tiêu học tập cụ thể. |
| Problem Statement | Không dùng | Tự nhóm thảo luận vì ngôn từ Problem Statement cần sự đồng thuận và hiểu sâu sắc từ chính các thành viên. | N/A | Tự nhóm viết và tinh chỉnh từ v0 sang v1 để tránh phụ thuộc vào văn phong máy móc của AI. |
| Rule / Workflow / Agent | Phân tích sự khác biệt và ranh giới giữa Rule, Workflow và Agent cho bài toán lọc slide. | Làm rõ cơ chế kỹ thuật: Rule (regex/keyword) vs Workflow (RAG theo learning objective) vs Agent (tự lên lộ trình học). | Thường xúi giục chọn Agent vì nghe "thông minh và tiềm năng hơn" mà lờ đi chi phí và rủi ro sai lệch. | Kiên quyết giữ quan điểm chọn Workflow, giữ người học làm trung tâm kiểm duyệt thông tin. |
| Decision | Không dùng | Quyết định Go / Not Yet / No-Go phải dựa trên năng lực và cam kết thật của 5 thành viên trong nhóm. | N/A | Nhóm tự thống nhất điều kiện pilot trên 1 slide môn học thực tế thay vì để AI quyết định thay. |

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
Khi lắng nghe top 3 problems của các thành viên trong nhóm, tôi nhận ra một điều thú vị là dù xuất phát điểm khác nhau, có tới 4/5 người cùng có chung một nỗi đau lớn về việc bị quá tải khi đọc và lọc tài liệu học tập. Ban đầu, nhóm tôi cũng có lúc bị cuốn vào tâm lý solution-first, một vài bạn muốn xây dựng hẳn một "AI Tutor Agent" có thể tự động học và giải thích mọi thứ cho thật ngầu. Tuy nhiên, sau khi phân tích kỹ quy trình và đối chiếu với bài học "Problem first, not AI first", tôi và các bạn đã kéo nhau lại để nhận diện rõ điểm nghẽn thực sự chỉ nằm ở khâu đọc lướt để xác định phần nội dung trọng tâm. Đóng góp rõ nét nhất của tôi vào bản nộp nhóm là việc kiên trì bảo vệ bước Human Boundary và yêu cầu AI bắt buộc phải trích dẫn đúng số trang slide gốc, tránh để sinh viên ỷ lại vào bản tóm tắt mà bỏ qua việc đọc hiểu bản chất. Điều khó nhất với chúng tôi khi viết Problem Statement v1 không phải là đặt ra con số metric thời gian, mà là xác định ranh giới (boundary): AI chỉ đóng vai trò vẽ bản đồ ưu tiên nội dung, tuyệt đối không được làm thay việc tư duy và học tập của người học. Nếu được làm lại từ đầu, tôi sẽ challenge nhóm mạnh mẽ hơn ngay từ khâu validation ngoài thực tế, chủ động phỏng vấn thêm 2–3 sinh viên khóa khác để bộ số liệu baseline không chỉ dừng lại ở ước tính cá nhân của các thành viên trong nhóm.
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

