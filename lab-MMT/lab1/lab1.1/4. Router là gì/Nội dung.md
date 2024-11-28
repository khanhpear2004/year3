### Vai trò của Router trong mạng:

1. **Định tuyến dữ liệu giữa các mạng**: Router là thiết bị mạng quan trọng có nhiệm vụ kết nối và định tuyến lưu lượng dữ liệu giữa các mạng khác nhau, ví dụ từ mạng nội bộ (LAN) ra mạng diện rộng (WAN) hoặc Internet. Nó đảm bảo rằng dữ liệu được gửi đến đúng mạng đích thông qua các giao thức định tuyến.
    
2. **Phân đoạn các mạng con (Subnetting)**: Router có thể phân đoạn các mạng lớn thành các mạng con nhỏ hơn (subnet), giúp tối ưu hóa lưu lượng mạng và cải thiện bảo mật.
    
3. **Dịch địa chỉ IP (NAT)**: Router hỗ trợ Network Address Translation (NAT), cho phép nhiều thiết bị trong mạng nội bộ sử dụng chung một địa chỉ IP công cộng khi truy cập Internet, giúp tiết kiệm tài nguyên địa chỉ IP.
    
4. **Chức năng bảo mật**: Một số router cung cấp các tính năng bảo mật như tường lửa (firewall), giúp bảo vệ mạng nội bộ khỏi các cuộc tấn công từ bên ngoài.
    
5. **Kết nối giữa các công nghệ mạng khác nhau**: Router có thể kết nối giữa các loại mạng khác nhau như Ethernet, mạng không dây (Wi-Fi), hoặc các mạng dựa trên sợi quang.
    

---

### Đặc điểm chính của Router:

- **Hoạt động ở tầng 3 (tầng mạng) của mô hình OSI**: Router xử lý địa chỉ IP và sử dụng các giao thức định tuyến để tìm đường đi tối ưu cho gói tin đến đích.
    
- **Sử dụng bảng định tuyến**: Router duy trì bảng định tuyến chứa thông tin về các mạng đích và đường đi tốt nhất để chuyển tiếp dữ liệu. Bảng này được cập nhật liên tục thông qua các giao thức định tuyến như OSPF, BGP, hoặc RIP.
    
- **Chuyển tiếp gói tin thông qua IP**: Router phân tích gói tin dựa trên địa chỉ IP đích và quyết định chuyển tiếp chúng đến mạng đích tương ứng.
    
- **Hỗ trợ NAT và PAT**: Router có khả năng dịch địa chỉ mạng (NAT) và dịch cổng địa chỉ mạng (PAT) để quản lý lưu lượng ra vào mạng nội bộ và cung cấp các kết nối Internet an toàn.
    
- **Định tuyến động và tĩnh**: Router có thể sử dụng cả phương thức định tuyến động (thông qua giao thức định tuyến) và định tuyến tĩnh (cấu hình thủ công).
    

---

### Sự khác biệt giữa Router và Switch:

| **Tiêu chí**                   | **Router**                                                 | **Switch**                                                           |
| ------------------------------ | ---------------------------------------------------------- | -------------------------------------------------------------------- |
| **Tầng hoạt động**             | Tầng 3 (Tầng mạng)                                         | Tầng 2 (Tầng liên kết dữ liệu)                                       |
| **Chức năng chính**            | Định tuyến gói tin giữa các mạng khác nhau                 | Kết nối và chuyển tiếp gói tin giữa các thiết bị trong cùng mạng LAN |
| **Địa chỉ sử dụng**            | Sử dụng địa chỉ IP để định tuyến gói tin                   | Sử dụng địa chỉ MAC để chuyển gói tin                                |
| **Bảng định tuyến / bảng MAC** | Sử dụng bảng định tuyến IP                                 | Sử dụng bảng CAM chứa địa chỉ MAC                                    |
| **Kết nối mạng nội bộ**        | Kết nối các mạng khác nhau (LAN đến WAN, LAN đến Internet) | Kết nối các thiết bị trong cùng một mạng nội bộ (LAN)                |
| **Chức năng bảo mật**          | Có thể tích hợp tường lửa và các tính năng bảo mật         | Ít tính năng bảo mật hơn, chủ yếu dựa vào khả năng chuyển mạch       |
| **Phạm vi hoạt động**          | Hoạt động giữa các mạng lớn (mạng LAN, WAN)                | Hoạt động chủ yếu trong mạng LAN                                     |

---

### Cổng của Router (Router Ports):

1. **Cổng WAN (Wide Area Network)**: Đây là cổng được sử dụng để kết nối router với mạng diện rộng (thường là kết nối Internet). Cổng WAN nhận và gửi dữ liệu từ mạng nội bộ (LAN) ra ngoài, thường được gắn với địa chỉ IP công cộng.
    
2. **Cổng LAN (Local Area Network)**: Các cổng này kết nối router với các thiết bị hoặc switch trong mạng nội bộ. Cổng LAN thường sử dụng địa chỉ IP riêng (private IP) và tạo mạng nội bộ cho các thiết bị trong gia đình hoặc công ty.
    
3. **Cổng Ethernet**: Router thường có nhiều cổng Ethernet để kết nối với các thiết bị có dây, chẳng hạn như máy tính, switch, hoặc các thiết bị mạng khác.
    
4. **Cổng quang (Fiber)**: Một số router cao cấp có cổng quang để kết nối trực tiếp với các dịch vụ Internet tốc độ cao sử dụng cáp quang (Fiber-optic).
    
5. **Cổng Console**: Router thường có một cổng console dùng để quản lý và cấu hình thiết bị qua giao diện dòng lệnh, thường được sử dụng bởi các kỹ sư mạng hoặc quản trị viên hệ thống.
    

---

### Kết luận:

Router đóng vai trò quan trọng trong việc định tuyến dữ liệu giữa các mạng khác nhau, giúp kết nối mạng nội bộ với mạng bên ngoài như Internet, đồng thời cung cấp các tính năng bảo mật và quản lý mạng.