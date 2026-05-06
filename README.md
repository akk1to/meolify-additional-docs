<img width="3506" height="960" alt="backdrop" src="https://github.com/user-attachments/assets/dece0859-b8d0-4315-a181-88732b4dd997" />

## Kế hoạch xây dựng Model trí tuệ nhân tạo

**1. Chuẩn bị (7/5/2026 - 20/5/2026):**
> - Chính thức chốt đầu tư hạ tầng từ hội đồng đầu tư.
> - Xây dựng phòng đặt máy chủ theo kế hoạch đề ra, đồng thời build máy chủ vật lý phục vụ việc huấn luyện.
> - Nhận máy, cài đặt máy theo kế hoạch đề ra.
> - Trong lúc đó, sẽ sử dụng nền tảng [Google Colab](https://colab.research.google.com/) để train, sử dụng tầm 100 đơn vị điện toán trong lúc chờ hoàn thiện phòng máy chủ.

**2. Huấn luyện trí tuệ nhân tạo (20/5/2026 - 28/7/2026)**
> - Trải qua quá trình huấn luyện trí tuệ nhân tạo liên tục, đạt ít nhất 200H Fine-tune để đảm bảo sản phẩm demo ổn định.
> - Liên tục ghi chép thông số, chi tiết quá trình huấn luyện để xây dựng đề tài khoa học cho dự án.
> - Tích hợp nhiều tính năng, nền tảng để hoàn thiện Model trí tuệ nhân tạo.

**3. Ra mắt sản phẩm trí tuệ nhân tạo + kêu gọi đầu tư vào dự án (8/2026)**
> - Ra mắt demo trí tuệ nhân tạo, đề án về trí tuệ nhân tạo, ra mắt nội dung sản phẩm trên Github.
> - Thu hút sự chú ý về dự án và mong muốn đầu tư xây dựng dự án hoặc sử dụng dự án từ các cá nhân và tổ chức nước ngoài trên các nền tảng như ProductHunt, Kickstarter,...
> - Sử dụng thử nghiệm trí tuệ nhân tạo kết hợp cùng nền tảng Meowlify cho các đối tác, kêu gọi ủng hộ xây dựng dự án.

## Chi tiết kế hoạch phát triển dự án

**1. Xây dựng sản phẩm**
> - Tiến hành xây dựng nền tảng dự án Meowlify và trí tuệ nhân tạo NekoAI như kế hoạch đã đề ra.
> - Xây dựng hoàn thiện Frontend, Backend, hệ thống tự động hóa, etc.
> - Tiến hành huấn luyện trí tuệ nhân tạo theo các kế hoạch đã đề ra.
> - Liên tục thử nghiệm, chỉnh sửa và rút ra kết luận để cải thiện sản phẩm trong quá trình xây dựng dự án.
> - Liên tục thu thập dữ liệu trong quá trình xây dựng dự án để làm cơ sở cho đề tài khoa học sau này.

**2. Thử nghiệm sản phẩm**
> - Tiến hành thử nghiệm mẫu sản phẩm hoàn thiện tối thiểu, thu thập dữ liệu để nghiệm thu và rút ra thay đổi để cải thiện sản phẩm.
> - Tiến hành thử nghiệm trí tuệ nhân tạo, thử cho huấn luyện thông qua việc học hỏi tự động có chọn lọc.
> - Tiến hành xây dựng đề tài cơ sở cho các nền tảng kết hợp hệ sinh thái trí tuệ nhân tạo NekoAI.
> - Xây dựng cơ sở đề tài khoa học của hệ sinh thái NekoAI và các nền tảng liên quan.

**3. Ra mắt thử nghiệm, kêu gọi đầu tư vào dự án**
> - Tiến hành ra mắt sản phẩm thử nghiệm, cho sử dụng thử nghiệm trên các đối tác chiến lược và đối tác thử nghiệm sớm.
> - Giới thiệu cho các nền tảng lớn thử sử dụng sản phẩm, cũng như tuyển Tester thử nghiệm nền tảng.
> - Liên tục thu thập dữ liệu hệ thống, để tinh chỉnh cải thiện sản phẩm và làm cơ sở cho đề tài khoa học của nền tảng.
> - Kêu gọi đầu tư xây dựng dự án thông qua các nền tảng như ProductHunt, Kickstarter, etc.
> - Xây dựng một cộng đồng người dùng sản phẩm và người quan tâm sản phẩm.
> - Xây dựng hoàn thiện cơ sở đề tài khoa học cho dự án.

**4. Hoàn thiện & ra mắt sản phẩm**
> - Hoàn thiện sản phẩm & phân phối bản quyền sản phẩm cho các đối tác chiến lược và người dùng.
> - Đăng ký bản quyền của sản phẩm và phân phối dưới nhà phân phối MerryHome.
> - Sử dụng đề tài khoa học đã xây dựng để tham gia các cuộc thi KHKT, YTST, etc. để tạo cơ sở khoa học cho đề án, cũng như nhận thành tích cho dự án.
> - Liên tục xây dựng các nền tảng liên kết với sản phẩm để trở thành một hệ sinh thái hoàn thiện.

## Các nền tảng dự kiến xây dựng liên quan tới hệ sinh thái NekoTech

(work in progress)

## Bản thiết kế kĩ thuật xây dựng phòng máy chủ

**1. Tổng quan kỹ thuật**

| Hạng mục          | Thông số kĩ thuật                                                           |
|-------------------|-----------------------------------------------------------------------------|
| Quy mô diện tích  | ~22.5m² (dài 7.9m x rộng 2.85m x cao 2.0m)                                  |
| Công suất tải     | Khởi điểm 1000W, dự phòng mở rộng lên 3000W (tương đương 3 Server Node)     |
| Mục tiêu âm học   | Triệt tiêu 95% tiếng ồn từ quạt máy chủ giữa phòng Server và phòng kĩ thuật |
| Ngân sách dự tính | 30 - 35tr đồng (chưa tính IPS & thiết bị IT)                                |
| Tiến độ xây dựng  | Hoàn thiện đúng tiến độ trước ngày 20/5/2026                                |

**2. Phân bổ không gian chức năng**

Phân bổ các phân khu trong phòng máy chủ như sau:
- Phân khu **Server Zone** (bên trái):
> - Kích thước 3.0m x 2.85m, nằm sát hướng kéo cáp quang & CB tổng.
> - Đảm bảo khoảng lùi mặt trước > 1m để thao tác tháo lắp linh kiện Rack, đảm bảo hành lang khí nóng mặt sau 0.8m.
> - Bắt buộc giới hạn sử dụng tủ Rack 27U/32U do trần lọt lòng còn 2.0m.
- Phân khu **NOC - Network Operation Center** (bên phải):
> - Kích thước 3.9m x 2.85, với mục đích theo dõi giám sát hệ thống và quản trị hạ tầng.
- Phân khu giao thông:
> - Cửa ra vào rộng 1m nằm chính giữa (từ m 3.45 -> 4.45), làm vùng đệm giữa 2 khu.

**3. Giải pháp kết cấu vỏ bọc**

3.1. Xử lý trần và chống dột mái
> - **Ngoại vi:** Dán bọc toàn bộ đầu vít khe giáp lai mái tôn bằng băng keo màng nhôm chống dột chịu nhiệt.
> - **Nội vi:** Lắp đặt hệ trần thả bằng tấm Panel EPS 50mm cách mái tôn khoảng 5cm.

3.2. Gia cố rào ban công & vách bao che
> - Hàn bổ sung 1-2 thanh xà gồ thép hộp mỏng mạ kẽm ở cao độ 1.5m liên kết với 6 trụ chính để gia cố chống rung gió chấn cho nửa trên.
> - Ốp tấm Panel EPS 50mm ở **mặt trong rào sắt**. Sử dụng U nhôm định hình bắt vít xuống mặt sàn ban công.
> - Bơm đầy keo bọt nở (PU Foam) và dán Silicon Apollo A500 tại khe tiếp giáp chân vách mặt ngoài để chặn nước mưa tạt thấm chân tường.

3.3. Hệ vách cách âm:
> - Thi công hệ vác tiêu âm 3 lớp:
> + 1. **Lớp khóa chấn:** Phủ kín tường bằng màng cao su non 10mm - 15mm.
> + 2. **Lớp tiêu âm:** Dựng khung xương nhôm/thép, nhét kín các tấm sợi khoáng Rockwool (Tỉ trọng 60kg/m³ hoặc 80kg/m³). Tuyệt đối không dùng EPS ở vị trí này.
> + 3. **Lớp hoàn thiện:** Ốp 1-2 lớp tấm thạch cao hoặc Cemboard, trét mí và viền keo chống lọt âm.

**4. Xử lý giao điểm cửa đi & cửa sổ**

4.1. Hệ thống cửa sổ:
> Trám kín hoàn toàn 2 ô cửa sổ lùa hiện hữu bằng cách nhồi sợi khoáng vào lọt lòng khung, sau đó bắn tấm thạch cao bít vĩnh viễn và đi keo Silicon. Không dùng vật liệu truyền nhiệt. Nếu có nhu cầu quan sát, chỉ được phép sử dụng Kính hộp hút chân không.

4.2. Cửa đi chính:
> - **Cơ cấu:** Cửa mở quay với hướng mở lật ra ngoài phân khu NOC (tránh va đập tủ Rack).
> - **Vật liệu:** Cửa thép vân gỗ lõi tổ ong chống cháy hoặc Nhôm kính hệ.
> - **Phụ kiện bắt buộc:** Khóa gạt đa điểm ép ron cao su và Thanh chặn đáy tự động cơ học thả xuống khi đóng cửa.

**5. Hệ thống điện & làm mát**

5.1. Hệ thống làm mát
> - **Thiết bị:** Điều hòa 1.5HP Inverter phủ mạ chống ăn mòn (TitanGold/Gold Fin).
> - **Vị trí lắp đặt:** Đặt trong Server Zone, treo cách trần tối thiểu 15-20cm để lấy gió hồi. Mặt thổi gió hướng xuống phía trước mặt tủ Rack.
> - **Khử ẩm:** Bổ sung máy hút ẩm dân dụng chạy tự động khi độ ẩm > 60%.

5.2. Chống tĩnh điện và chịu lực
> - Phủ toàn bộ mặt sàn bằng Sàn nhựa giả gỗ hèm khóa hoặc dán keo để triệt tiêu bụi xốp.
> - Tại khu vực đặt tủ Rack có trang bị UPS EBM mở rộng (trọng tải đạt 150kg - 200kg), lót tấm thép gân (5mm) dưới chân tủ để phân tán lực nén đều trên mặt sàn ban công.
> - Trang bị thảm cao su chống tĩnh điện (ESD Mat) có dây kẹp tiếp địa tại khu vực thao tác kỹ thuật phần cứng.
