# HTML cơ bản

***

### 1.HTML là gì?
> **[HTML](https://topdev.vn/viec-lam-it/html-kt75)** là viết tắt của cụm từ **Hypertext Markup Language** (tạm dịch là Ngôn ngữ đánh dấu **[siêu văn bản](https://vi.wikipedia.org/wiki/Si%C3%AAu_v%C4%83n_b%E1%BA%A3n)**. **HTML** được sử dụng để tạo và cấu trúc các thành phần trong trang web hoặc ứng dụng, phân chia các đoạn văn, heading, titles, blockquotes… và **HTML** không phải là ngôn ngữ lập trình.
Cha đẻ của **HTML** là **Tim Berners-Lee**, cũng là người khai sinh ra World Wide Web và chủ tịch của **World Wide Web Consortium** (W3C – tổ chức thiết lập ra các chuẩn trên môi trường Internet). Các thiết lập và cấu trúc HTML được vận hành và phát triển bởi World Wide Web Consortium (W3C). Bạn có thể kiểm tra tình trạng mới nhất của ngôn ngữ này bất kỳ lúc nào trên trang **[W3C’s website](https://www.w3.org/)**.

### 2.HTML hoạt động như thế nào?
> Khi bạn gõ ra 1 tên miền, trình duyệt mà bạn đang sử dụng (chẳng hạn như Chrome) sẽ kết nối tới 1 máy chủ web, bằng cách dùng 1 địa chỉ IP, vốn được thấy bằng cách phân giải tên miền đó (DNS). Máy chủ web chính là 1 máy tính được kết nối tới internet và nhận các yêu cầu tới trang web từ trình duyệt của bạn. Máy chủ sau đó sẽ gửi trả thông tin về trình duyệt của bạn, là 1 tài liệu HTML, để hiển thị trang web!

> Một tập tin **HTML** sẽ bao gồm các phần tử **HTML** và được lưu lại dưới đuôi mở rộng là ***.html*** hoặc ***.htm.*** Khi một tập tin HTML được hình thành, việc xử lý nó sẽ do trình duyệt web đảm nhận. Trình duyệt sẽ đóng vai trò đọc hiểu nội dung HTML từ các thẻ bên trong và sẽ chuyển sang dạng văn bản đã được đánh dấu để đọc, nghe hoặc hiểu (do các bot máy tính hiểu).

> Bạn có thể xem chúng bằng cách sử dụng bất kỳ trình duyệt web nào (như Google Chrome, Safari, hay Mozilla Firefox). Trình duyệt đọc các files HTML này và xuất bản nội dung lên internet sao cho người đọc có thể xem được nó.

> Thông thường, trung bình một web chứa nhiều trang web HTML, ví dụ như: trang home, trang product, trang blog…

### 3.Cấu trúc của HTML
> Mỗi trang HTML chứa một bộ các **tag** (cũng được gọi là ***elements***). Mỗi thẻ sẽ có những tác dụng nhất định, giúp xây dựng nên một cấu trúc hoàn chỉnh cho Website. Bạn có thể xem như là việc xây dựng từng khối của một trang web. Nó tạo thành cấu trúc cây thư mục bao gồm section, paragraph, heading, và những khối nội dung khác.
> Hầu hết các HTML elements đều có tag mở và tag đóng với cấu trúc như `<tag></tag>`.
     #### *Các tag thông dụng của HTML*
HTML tags được sử dụng chủ yếu là 2 loại chính: **block-level tags** và **inline tags**.
  
 1. **Elements Block-level** : đây là loại tag cấp cao nhất, sẽ sử dụng toàn không gian trang web và luôn bắt đầu dòng mới của trang web. **3 block-level tags** mà tất cả các trang HTML đầu cần có đó là `<html></html>`, `<head></head>` và `<body></body>`.
 2. **Inline elements** chỉ chiếm phần nhỏ không gian web và không bắt đầu dòng mới của trang web. Chúng thường dùng để định dạng nội dung bên trong của **block level elements**.

 Để biết bố cục HTML của một trang web như thế nào, bạn có thể xem code ví dụ của một trang HTML được cấu trúc như thế nào:
 
     <!--<!DOCTYPE html>: khai báo kiểu dữ liệu hiển thị-->
      <!DOCTYPE html>
       <html>
      <!--<html> và </html>: cặp thẻ bắt buộc, element cấp cao nhất, có nhiệm vụ đóng gói tất cả nội dung của trang HTML.-->
      
      <!--<head> và </head>: khai báo các thông tin meta của trang web như: tiêu đề trang, charset
      <head>
        <!-- Phần đầu -->
        <!--charset="utf-8" dùng để gõ tiếng việt tránh bị lỗi hiển thị trên website-->
            <meta charset="utf-8">
        <!--Tiêu đề của trang-->
            <title>Thịnh cute</title>
    </head>
    <!-- Phần thân -->
    <!--comments ctrl + /-->
    
    <!--<body> và </body>: cặp thẻ dùng để đóng gói tất cả các nội dung sẽ hiển thị trên trang
    <body>
    
    <!--  1. h1 - h6 - heading - tiêu đề(Cỡ chữ sẽ giảm dần từ h1 -> h6)-->
            <h1>Thịnh có chút xíu</h1>
            <h2>Thịnh có chút xíu</h2>
            <h3>Thịnh có chút xíu</h3>
            <h4>Thịnh có chút xíu</h4>
            <h5>Thịnh có chút xíu</h5>
            <h6>Thịnh có chút xíu</h6>
               
    <!--2. p - paragragh - văn bản-->
            <p>Em iu anh Đăng nhất trên đời.</p>
            
    <!--3. img - ảnh-->
                <!--ảnh. alt là nếu ảnh lỗi sẽ hiện chữ-->
        <img src="https://o.vdoc.vn/data/image/2022/11/09/song-da.jpg" alt="ảnh sông">

    <!--4. a - anchor - neo liên kết(Hyperlinks)-->
        <a href="https://shopee.vn/product/579123024/20133428257">trang hoa</a>
       
 
    <!--5. ul, li - unordered list(danh sách sắp xếp tùy ý), list(thể hiện danh sách)-->
          <!--ul .list nhanh bằng cách thêm dấu sao li*(số list)-->
            <ul>
                <li>Quóc Thinh đz</a></li>
                
                <li>Quốc Thịnh dú to</li>
                <li>Quốc Thịnh 3s</li>
                <li>Clip nóng  QT</li>
            </ul>

    <!--6. table - bảng - gồm thead(phần đầu) - tbody(phần thân)-->
            <table>
                <thead>
                    <!--phần đầu-->
                       <th>stt</th>
                       <th>Tên</th>
                       <th>Địa chỉ</th>
               </thead>
                <tbody>
                    <!--dòng-->
                    <tr>
                        <td>1</td>
                        <td>Quốc THịnh</td>
                        <td>Trảng cò </td>
                    </tr>
                    
                </tbody>
            </table>

    <!--7. input - ô nhập-->
             <!--nhập chữ -->
                <input type="Text">
             <!-- dấu tích-->
                <input type="checkbox">
             <!--giống checkbox nhưng chỉ chọn đc 1 cái.name giống nhau chỉ chọn được 1 cái-->
                <input name="gender" type="radio">
                <input name="gender" type="radio">
                <input name="gender" type="radio">
           
    <!--8. button - nút bấm vào-->
                <button>đăng kí</button>
        </body>
    </html>
   
Nếu bạn muốn tìm hiểu thêm về tag **HTML**, hãy cân nhắc xem qua **[cheat sheet HTML](https://topdev.vn/blog/wp-content/uploads/2021/01/WSU-HTML-Cheat-Sheet.pdf)**
  
 ### 4.Ưu, nhược điểm của HTML
  
 > HTML là một ngôn ngữ đánh dấu siêu văn bản nên nó sẽ có vai trò xây dựng cấu trúc siêu văn bản trên một website, hoặc khai báo các tập tin kỹ thuật số (media) như hình ảnh, video, nhạc. Tuy nhiên, HTML có ưu và nhược điểm của riêng nó.
  
**Ưu điểm:**
* Được sử dụng rộng rãi, có rất nhiều nguồn tài nguyên hỗ trợ và cộng đồng sử dụng lớn.
* Học đơn giản và dễ hiểu.
* Mã nguồn mở và hoàn toàn miễn phí.
* Markup gọn gàng và đồng nhất.
* Tiêu chuẩn thế giới được vận hành bởi World Wide Web Consortium (W3C).
* Dễ dàng tích hợp với các ngôn ngữ backend như PHP, Python…
  
**Khuyết điểm:**

* Được dùng chủ yếu cho web tĩnh. Đối với các tính năng động như update hay realtime thời gian thực, bạn cần sử dụng JavaScript hoặc ngôn ngữ backend bên thứ 3 như PHP.
* Một số trình duyệt chậm hỗ trợ tính năng mới.
  
### 5.HTML đóng vai trò gì trong webside
  
Với những ưu và khuyết điểm trên, điều đó không có nghĩa là chỉ sử dụng HTML để tạo ra một website mà HTML chỉ đóng một vai trò hình thành trên website. Một website chuẩn sẽ được hình thành bởi:
  
* **HTML** – Xây dựng cấu trúc và định dạng các siêu văn bản.
* **CSS** – Định dạng các siêu văn bản dạng thô tạo ra từ HTML thành một bố cục website, có màu sắc, ảnh nền,….
* **Javascript** – Tạo ra các sự kiện tương tác với hành động của người dùng (ví dụ như là chat, update nội dung, hiệu ứng slide).
* **PHP** – Ngôn ngữ lập trình để xử lý và trao đổi dữ liệu giữa máy chủ đến trình duyệt.
* **MySQL** – Hệ quản trị cơ sở dữ liệu truy vấn có cấu trúc.
  
 > Nếu website là một cơ thể hoàn chỉnh thì HTML chính là bộ xương của cơ thể đó. Dù website thuộc thể loại nào, giao tiếp với ngôn ngữ lập trình nào để xử lý dữ liệu thì vẫn phải cần HTML để hiển thị nội dung ra cho người dùng xem.
### 6.HTML, CSS và Javascript bổ trợ cho nhau như thế nào?
  
  Tuy HTML được đánh giá là khung sườn cho website nhưng nó vẫn chưa đủ khả năng xây dựng một trang web chuyên nghiệp. Do đó, các lập trình viên thường chỉ sử dụng HTML để thêm các element dạng văn bản và xây dựng giao diện cấu trúc cho phần nội dung trên trang.

Với khả năng tương thích cao, HTML khi kết hợp cùng **[CSS](https://topdev.vn/blog/css-la-gi/)** và Javascript sẽ có thể giúp tăng trải nghiệm cho người dùng và thiết lập được các chức năng cao cấp khác. Cụ thể:
  
  * CSS đóng vai trò chính trong việc thiết kế, xây dựng background, màu sắc và các hiệu ứng cho trang
  * Javascript có nhiệm vụ giúp tạo ra các chức năng động như: thư viện hình ảnh, slider, pop-up…
  
  ***Website có hai loại chính:***
>  **Website tĩnh (static web)** – Là một website không giao tiếp với máy chủ web để gửi nhận dữ liệu mà chỉ có các dữ liệu được khai báo sẵn bằng HTML và trình duyệt đọc.
  
> **Website động (dynamic web)** – Là một website sẽ giao tiếp với một máy chủ để gửi nhận dữ liệu, các dữ liệu đó sẽ gửi ra ngoài cho người dùng bằng văn bản HTML và trình duyệt sẽ hiển thị nó. Để một website có thể giao tiếp với máy chủ web thì sẽ dùng một số ngôn ngữ lập trình dạng server-side như PHP, ASP.NET, Ruby,..để thực hiện. Ví dụ như một website làm bằng WordPress là website động.
  
 ### 7.Các phần mềm để lập trình HTML
  Để lập trình web hiệu quả và tiết kiệm thời gian, công sức, bạn có thể sử dụng các phần mềm lập trình HTML miễn phí và hiệu quả dưới đây:

* [Sublime Text](https://topdev.vn/blog/theme-sublime-text/)
* [Visual Studio Code](https://topdev.vn/blog/vs-code-theme/) (VS Code)
* [Atom](https://topdev.vn/blog/text-editors-atom-va-sublime/)
  
### 9.Tài nguyên tham khảo HTML
  HTML là thành phần cực kỳ quan trọng của một website. Các thiết lập và cấu trúc HTML được vận hành và phát triển bởi World Wide Web Consortium (W3C). Bạn có thể kiểm tra tình trạng mới nhất của HTML bất kỳ lúc nào trên trang [W3C’s website.](https://www.w3.org/)

***by Tensoract***
  
  
