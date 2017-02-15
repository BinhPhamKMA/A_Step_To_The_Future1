
## Tìm hiểu markdown.

> Tài liệu: Markdown là gì
>
> Thực hiện:**Phạm Thị Thanh Bình**
>
> Cập nhật lần cuối: **15/02/2017**

### Mục lục 
[1. Tìm hiểu GitHub](#timhieugithub)

[2. Markdown là gì?](#markdownlagi)

[3. Lịch sử hình thành markdown](#lichsumarkdown)

[4. Cú pháp sử dụng markdown](#cuphapsudung)

- [4.1. Tạo tiêu đề](#taotieude)

- [4.2. Định dạng chữ ](#dinhdangchu)

- [4.3. Tạo danh sách](#taodanhsach)

- [4.4. Tạo liên kết](#taolienket)

- [4.5. Tạo liên kết tự động](#lienkettudong)

- [4.6. Tạo hình ảnh](#taohinhanh)

- [4.7. Tạo trích dẫn](#taotrichdan)

- [4.8.Tạo kẻ ngang](#taokengang)

- [4.9. Tạo điểm nhấn ](#taodiemnhan)

- [4.10. Tạo chú thích cuối trang](#taochuthich)

- [4.11. Tạo bảng  ](#taobang)

	
---

<a name="timhieugithub"></a>
### 1.Tìm hiểu GitHub
GitHub là một dịch vụ lưu trữ trên web dành cho các dự án có sử dụng hệ thốngmkiểm soát Git revision.
GitHub cung cấp chức năng social networking như là feeds,followers và network grap để các developer học
hỏi kinh nghiệm làm việc thông qua lịch sử commit.Nếu comment dùng để mô tảchức năng đoạn code,thì commit message
trên git dùng để mô tả hành động dev vừa thực hiện trên code.

**Cần làm gì để có thể sử dụng GitHub?**
- B1: Đăng ký một tài khoản tại github và đăng nhập
- B2: Học cách sử dụng ngôn ngữ Markdown
( vì nếu viết bài bằng markdown sẽ mang lại sự tường  mình cho bài viết của bạn)
- B3: Tạo một repo đầu tiên và gõ Hello world bằng Markdown
Sau đó tạo các repo tùy mục đích, clone nó về client và code.

---


<a name="markdownlagi"></a>
### 2.Markdown là gì?

Markdown là một ngôn ngữ đánh dấu với cú pháp văn bản thô, được thiết kế để có thể dễ dàng chuyển thành HTML và nhiều định 
dạng khác sử dụng một công cụ cùng tên. Nó thường được dùng để tạo các tập tin readme, viết tin nhắn trên các diễn đàn, và 
tạo văn bản có định dạng bằng một trình biên tập văn bản thô.


---


<a name="lichsumarkdown"></a>
### 3.Lịch sử hình thành Markdown 
Năm 2004, John_Gruber - một designer, blogger chuyên về các sản phẩm của Apple phát điên sau khi phải viết một tài liệu HTML dài dằng dặc. Anh nảy ra ý tưởng tạo ra một ngôn ngữ cho các tài liệu trên web mà phải dễ viết, dễ đọc ở định dạng tự nhiên và có thể chuyển thành HTML. Với sự giúp đỡ của Aaron Swartz. John_Gruber thực sự đã phát minh ra Markdown mà chúng ta biết ngày nay.


---


<a name="cuphapsudung"></a>
### 4.Cú pháp sử dụng Markdown

<a name="taotieude"></a>
**Tạo tiêu đề:**

	 #1.Tiêu đề 1
	 ##2.Tiêu đề 2
	
Để tạo tiêu đề trong markdown chúng ta chỉ cần chèn ký tự #ngay phía trước.Số lượng ký tự # sẽ xác định độ sâu của tiêu đề(h1-h6 trong HTML)

<a name="dinhdangchu"></a>
**Định dạng chữ**

	**In đậm** hoặc __In đậm__(<b>-HTMl)
	*In nghiêng* hoặc _In nghiêng_
	~~Chữ gạch ngang~~
	
<a name="taodanhsach"></a>
**Tạo danh sách**

	Tạo danh sách dạng số :
		1.Danh sách 1 
		2.Danh sách 2
	
	Tạo dạnh sách bullet :
		- Danh sách 1 
		- Danh sách 2
<a name="taolienket"></a>		
**Tạo liên kết**

	![Tên Link](Đường dẫn) (<a>)
	![Tên Link với chú thích](đường dẫn"chú thích") (<a name="chú thích">)

<a name="lienkettudong"></a>
**Tạo liên kết tự động** 

	 chỉ cần gõ đường link tuyệt đối(có HTTP hoặc HTTPs markdown sẽ tự liên kết tự động)
	 https://gitter.im/bi-to
	 
<a name="taohinhanh"></a> 
**Tạo hình ảnh**

	 ![](đường dẫn)(<img/>)
	 ![](đường dẫn"title")(<img alt="">)
	 
<a name="taotrichdan"></a>
**Tạo trích dẫn**

 	Để tạo trích dẫn bạn chèn > ngay phía trước
	
<a name="taokengang"></a>
**Tạo đường kẻ gạch ngang**

	Bạn gõ --- hoặc *** hoặc ___

<a name="taodiemnhan"></a>
** Tạo điểm nhấn ** 

	==Text==
	
<a name="taochuthich"></a>
**Tạo chú thích cuối trang**

	-[^1]:chú thích 1

<a name="taobang"></a>
**Tạo bảng**

	|Cột 1 hàng 1 |Cột 2|Cột 3|Cột 4|
	|-------------|-----|-----|-----|
	|Hàng 2       | 2*1 |2*2  | 2*3 |
	|Hàng 3       | 3*1 | 3*2 | 3*3 |
	

