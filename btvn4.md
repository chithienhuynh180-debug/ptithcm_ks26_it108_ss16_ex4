**Bài 4 : Tối ưu hóa Lưu trữ Dữ liệu Doanh nghiệp** 

**3\.**

- **Xử lý mạng và gập máy:**  
+ Giới hạn tốc độ tải: Vào cài đặt OneDrive \-\> Sync and backup \-\> Advanced settings \-\> Network \-\> Chọn upload thì đặt tốc độ tải file nhỏ một chút để tránh sập mạng .  
+ Gập máy để không tắt wifi: chỉnh Windows về chế độ gập màn hình thì máy vẫn chạy, cắm sạc để qua đêm  là sẽ tải đc về sau 1 đêm. 

###      

###           **4\.** 

###          **Giải pháp kỹ thuật**

- Bật Files On-Demand:  
+ OneDrive: Vào Settings \-\> Sync and backup \-\> Advanced settings \-\> Bật Files On-Demand. Sau đó ra thư mục video, chuột phải chọn Free up space.  
+ Google Drive: Vào Settings \> Preferences \> Chọn chế độ Stream files   
+ Hiệu quả: File video hiển thị biểu tượng đám mây, kích thước thật là 0 bytes trên ổ cứng. Chỉ khi nào click chuột để xem thì máy mới tải tạm về. Xem xong thì chuột phải chọn lại Free up space để giải phóng ngay.

###  **Báo cáo dung lượng**

| Tiêu chí | Tải hết về | Dùng Files On-Demand |
| :---- | :---- | :---- |
| **Dữ lượng trên Cloud** | 500 GB | 500 GB |
| **Dung lượng ổ cứng của máy còn trống** | \~200 GB | \~200 GB |
| **Dung lượng ổ cứng thực tế tốn**  | 500 GB | khoảng một chút MB (chỉ lưu tên file, thông tin cơ bản,dung lượng,..) |
| **Kết quả** | Tràn ổ cứng, máy treo lập tức | Chạy mượt, ổ cứng vẫn trống \~200 GB |

**Chứng minh** : Files On-Demand chỉ tạo các file hiển thị tên file  trên máy. còn file 500GB dữ liệu video giám sát campus nằm hoàn toàn trên Cloud, chỉ khi nào click  chuột mở file này thì mới tốn dung lượng, nên 256GB hoàn toàn không bị tràn.

