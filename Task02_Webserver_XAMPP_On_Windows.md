
## Tìm hiểu XAMPP

> Tài liệu: 
>
> Người thực hiện: **Phạm Thị Thanh Bình**
>
> Cập nhật lần cưối: **16/02/2017**

### Mục lục
[1. Tìm hiểu localhost](#timhieulocalhost)
	[1.1 Khái niệm localhost](#khainiemlocalhost)
	[1.2 Mục đích sử dụng localhost](#mucdichsudunglocalhost)
	[1.3 localhost vận hành như thế nào](#localhostvanhanhnhuthenao)
[2. Tìm hiểu XAMPP](#timhieuxampp)

[3. Cách cài đặt xampp](#cachcaidatxampp)


---

<a name="timhieulocalhost"></a>
### 1.Tìm hiểu localhost

	<a name="khainiemlocalhost"></a>
	#### 1.1 Khái niệm localhost
	Localhostlà địa chỉ của 1 máy chủ(server) cho phép các máy trong mạng  LAN có thể truy xuất thông tin theo một phương thức nào đó, dĩ nhiên trong đó có máy của mình rồi.
	Thông thường localhost hiểu là một Server trên máy của mình dùng vào một số mục đích nhất định nào đó.

	<a name="mucdichsudunglocalhost"></a>
	#### 1.2 Mục đích sử dụng localhost
	Như chúng ta biết một số ngôn ngữ lập trình như PHP, ASP ... là những ngôn ngữ dành cho Server tức là những ngôn ngữ chỉ thực thi trên Server (hay còn gọi là host)
	Nhưng không phải ai cũng có điều kiện và tiền bạc để thuê host của các nhà cung cấp, hoặc đơn giản là dùng host free, lý do là vì ... máy không nối mạng.
	Vậy thì muốn chạy được PHP hoặc ASP thì phải làm sao khi không có mạng ... giải pháp đưa ra đó là cài đặt localhost.
	Localhost là giải pháp đưa ra để có thể chạy PHP, ASP ngay trên máy tính của mình, và các máy tính khác trong mạng LAN có thể truy cập vào máy mình theo giao thức HTTP
	Biến máy tính của mình thành một Server và như vậy bạn có thể tha hồ học lập trình PHP, ASP... và cao hơn bạn có thể cài đặt các Website thử nghiệm trên máy mình như là : Nukeviet, Joomla, BoBlog ....
	Một Server (host) hoàn chỉnh để chạy được PHP bao gồm các thành phần.
		+ Web server : hỗ trợ giao thức HTTP, dùng để truy cập dữ liệu như bạn truy cập vào website
			Có thể dùng : Server Apache, IIS ...
		+ Database server : là server quản lý quy xuất cơ sở dữ liệu
		+ PHP : hỗ trợ ngôn ngữ PHP 
		+ ASP : hỗ trợ ngôn ngữ PHP (nếu có thì càng tốt, nếu học PHP thì ko cần cái này )
		+ Perl : hỗ trợ ngôn ngữ Perl
		+ ...
	Hiện nay có những gói cài đặt, được tích hợp tất cả những thứ cần thiết để cài đặt một localhost như : Apache server, MYSQL, PHP, Perl ...
	Các gói cài đặt dạng này có thể kết đến như : XAMPP, LAMPP, Appserv ...
	Nổi trội trong số đó là XAMPP với những ưu điểm vượt trội : Nhỏ gọn, tiện lợi, dễ cài đặt và sử dụng, ít lỗi
