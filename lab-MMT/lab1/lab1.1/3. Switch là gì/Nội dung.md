### Vai trò của Switch trong mạng:

1. **Kết nối các thiết bị**: Switch, giống như hub, được sử dụng để kết nối nhiều thiết bị (máy tính, máy in, máy chủ) trong một mạng cục bộ (LAN). Tuy nhiên, khác với hub, switch phân tích dữ liệu và chỉ gửi đến thiết bị đích cụ thể, giúp tối ưu hóa hiệu suất mạng.
    
2. **Chuyển mạch thông minh**: Switch hoạt động ở tầng 2 (tầng liên kết dữ liệu) của mô hình OSI và có khả năng sử dụng địa chỉ MAC để xác định thiết bị đích. Khi nhận dữ liệu, switch lưu lại địa chỉ MAC của các thiết bị kết nối và chuyển tiếp dữ liệu một cách hiệu quả chỉ đến thiết bị nhận.
    
3. **Giảm xung đột dữ liệu**: Switch giúp giảm thiểu hiện tượng va chạm (collision) dữ liệu vì nó tạo ra các mạch ảo riêng biệt giữa thiết bị gửi và thiết bị nhận, giúp tăng tốc độ và hiệu suất của mạng.
    
4. **Hỗ trợ VLAN**: Switch có khả năng phân chia các thiết bị thành các mạng VLAN (Virtual Local Area Network), giúp tối ưu quản lý và bảo mật mạng.
    

---

### Đặc điểm chính của Switch:

- **Hoạt động ở tầng 2 và 3 của mô hình OSI**: Switch thường hoạt động ở tầng liên kết dữ liệu (Layer 2), nhưng một số switch cũng hỗ trợ chức năng của router (Layer 3) để định tuyến dữ liệu giữa các mạng.
    
- **Học địa chỉ MAC**: Switch học địa chỉ MAC của tất cả các thiết bị kết nối vào nó và sử dụng bảng CAM (Content Addressable Memory) để lưu trữ thông tin về địa chỉ MAC, từ đó quyết định nơi cần gửi gói tin.
    
- **Gửi dữ liệu có chọn lọc**: Switch không phát tán gói dữ liệu đến mọi thiết bị như hub. Thay vào đó, nó chỉ gửi gói tin đến thiết bị có địa chỉ MAC phù hợp với gói tin nhận được.
    
- **Giảm thiểu va chạm dữ liệu**: Bằng cách chỉ truyền dữ liệu đến thiết bị đích, switch tạo ra các đoạn mạng riêng biệt cho mỗi cặp thiết bị, từ đó giảm thiểu hiện tượng xung đột và cải thiện hiệu suất mạng.
    
- **Full-duplex communication**: Switch cho phép các thiết bị giao tiếp ở chế độ full-duplex, nghĩa là các thiết bị có thể gửi và nhận dữ liệu cùng một lúc, giúp tối ưu băng thông.
    

---

### Sự khác biệt giữa Hub và Switch:

| **Tiêu chí**         | **Hub**                                       | **Switch**                                 |
| -------------------- | --------------------------------------------- | ------------------------------------------ |
| **Tầng hoạt động**   | Tầng 1 (Tầng vật lý)                          | Tầng 2 (Tầng liên kết dữ liệu)             |
| **Cách gửi dữ liệu** | Phát tán (Broadcast) đến tất cả các thiết bị  | Chỉ gửi đến thiết bị đích (Unicast)        |
| **Xung đột dữ liệu** | Dễ xảy ra do truyền đến tất cả các cổng       | Giảm thiểu xung đột nhờ gửi có chọn lọc    |
| **Bảng địa chỉ MAC** | Không sử dụng bảng MAC                        | Sử dụng bảng CAM để lưu địa chỉ MAC        |
| **Hiệu suất mạng**   | Kém hiệu quả hơn, băng thông bị lãng phí      | Tối ưu hiệu suất mạng, giảm tải băng thông |
| **Chế độ truyền**    | Chỉ hỗ trợ half-duplex (gửi và nhận lần lượt) | Hỗ trợ full-duplex (gửi và nhận cùng lúc)  |

---

### Điểm yếu của Switch:

1. **Chi phí cao hơn**: Switch có giá thành cao hơn nhiều so với hub vì tính năng thông minh và hiệu suất tốt hơn. Điều này có thể là một yếu tố hạn chế đối với các mạng nhỏ có ngân sách hạn hẹp.
    
2. **Đòi hỏi cấu hình phức tạp hơn**: Đặc biệt đối với các switch quản lý (managed switch), việc cấu hình VLAN, bảo mật, và quản lý mạng có thể phức tạp, đòi hỏi kiến thức chuyên môn về mạng.
    
3. **Không xử lý được các lỗi phần mềm cao cấp**: Mặc dù switch rất mạnh trong việc chuyển tiếp dữ liệu, nó không thể xử lý các nhiệm vụ cao cấp hơn, chẳng hạn như định tuyến giữa các mạng, mà thường yêu cầu thêm một router.
    
4. **Bảng CAM giới hạn**: Switch có thể gặp vấn đề khi quá nhiều thiết bị kết nối và bảng CAM bị đầy, làm giảm hiệu quả của quá trình chuyển tiếp dữ liệu.
    

---

### Số lượng cổng của Switch (Switch ports):

- **Thường từ 8 đến 48 cổng**: Các switch tiêu chuẩn dành cho doanh nghiệp hoặc mạng gia đình thường có từ 8 đến 48 cổng Ethernet. Tuy nhiên, switch cấp doanh nghiệp có thể có nhiều cổng hơn (lên đến 96 cổng) hoặc hỗ trợ các module cổng mở rộng.
    
- **Cổng quang (SFP/SFP+)**: Ngoài cổng Ethernet thông thường, nhiều switch còn có cổng SFP hoặc SFP+ để kết nối với các sợi quang, cho phép mở rộng khoảng cách truyền tải và kết nối với các switch hoặc thiết bị mạng khác ở xa.
    

Switch là thiết bị mạng quan trọng, giúp cải thiện hiệu suất và tính linh hoạt của mạng, phù hợp với cả mạng gia đình lẫn mạng doanh nghiệp lớn.

4o