### Vai trò của Hub trong mạng:

1. **Kết nối các thiết bị**: Hub là thiết bị mạng đơn giản, được sử dụng để kết nối nhiều thiết bị với nhau trong một mạng cục bộ (LAN). Nó nhận tín hiệu từ một thiết bị và gửi tín hiệu đó tới tất cả các cổng khác, giúp các thiết bị trong mạng giao tiếp với nhau.
    
2. **Phát tán tín hiệu**: Hub hoạt động theo nguyên tắc phát tán (broadcast). Tất cả dữ liệu được gửi đến hub sẽ được truyền đến mọi thiết bị khác trong mạng, không quan tâm đến thiết bị đích là gì.
    
3. **Khuếch đại tín hiệu**: Một số hub (được gọi là "hub chủ động") có khả năng khuếch đại tín hiệu trước khi truyền đi, giúp tăng cường khoảng cách truyền dẫn trong mạng.
    

### Đặc điểm chính của Hub:

- **Hoạt động ở tầng 1 (tầng vật lý)** của mô hình OSI, tức là nó không có khả năng xử lý logic thông tin mạng hay địa chỉ MAC/IP của các thiết bị.
- **Truyền tín hiệu đến tất cả các thiết bị** kết nối với nó, bất kể thiết bị đó có phải là đích của tín hiệu hay không.
- **Không có tính năng chuyển mạch**: Khác với switch, hub không thể phân tích gói tin để biết thiết bị đích là gì, mà chỉ gửi tín hiệu đến tất cả các cổng.
- **Độ trễ tín hiệu** có thể xảy ra do phương pháp phát tán dữ liệu đến tất cả các cổng.

### Điểm yếu của Hub:

1. **Không hiệu quả**: Do hub gửi tất cả dữ liệu đến mọi cổng, điều này dẫn đến lãng phí băng thông mạng và làm giảm tốc độ truyền tải thông tin, đặc biệt khi có nhiều thiết bị kết nối cùng lúc.
    
2. **Xung đột dữ liệu (Collision)**: Khi nhiều thiết bị cùng gửi dữ liệu thông qua hub, các gói tin có thể va chạm (collision), dẫn đến mất dữ liệu và phải gửi lại, làm giảm hiệu suất của mạng.
    
3. **Không hỗ trợ VLAN**: Hub không có khả năng phân chia mạng thành các vùng mạng ảo (VLAN), điều này làm hạn chế tính linh hoạt trong việc quản lý mạng.
    
4. **Bảo mật kém**: Vì hub phát tán dữ liệu đến tất cả các thiết bị, điều này khiến thông tin dễ bị lộ ra đối với các thiết bị không phải đích, dẫn đến nguy cơ bị nghe lén (eavesdropping).
    

### Số lượng cổng của Hub (Hub ports):

- **Thường từ 4 đến 24 cổng**: Các hub thông thường có từ 4 đến 24 cổng, tùy thuộc vào mô hình và kích thước của hub.