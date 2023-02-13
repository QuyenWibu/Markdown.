# Github  :smile:

***

### Một số khái niệm cơ bản:blush:

* **VCS (Version Control System)**: Hệ thống kiểm soát phiên bản trong
phát triển phần mềm giúp:

> Theo dõi mọi thay đổi của mã nguồn ở mọi thời điểm, lưu trữ các
phiên bản khác nhau của mã nguồn và giúp trở lại phiên bản mã
nguồn cũ nếu có cần thiết.

> Đồng thời cho phép hợp nhất các phiên bản khác nhau của mã
nguồn nhằm đảm bảo tính toàn vẹn và dễ dàng hơn trong việc
code cùng nhau trong các dự án phần mềm lớn.

* **DVCS (Distributed Version Control System)**: Hệ thống quản lý phiên
bản “phân tán” là một dạng của hệ thống quản lý phiên bản:

> Khác với VCS thì DVCS lưu trữ mã nguồn ở cả server tập trung
đồng thời cũng tạo các bản copy mã nguồn trên máy tính của các
dev tham gia vào việc phát triển mã nguồn.

> Cho phép thực hiện thay đổi code và hợp nhất code mà không
gây ra xung đột cho mã nguồn chính.

## :one:.Tìm hiểu về Github:question:

### Lịch sử của Git:scroll:

* Git (/ɡɪt/, đọc là "Ghít") là phần mềm
quản lý mã nguồn phân tán được phát
triển bởi Linus Torvalds vào năm 2005,
ban đầu dành cho việc phát triển nhân
Linux. 

* Hiện nay, Git trở thành một trong các
phần mềm quản lý mã nguồn phổ
biến nhất. Git là phần mềm mã nguồn
mở được phân phối theo giấy phép
công cộng GPL2

### Các thành phần của Git :octocat:

:point_right: Cơ chế lưu trữ **(snapshot)**: Cơ chế lưu trữ phiên
bản của Git là sau mỗi lần bạn thực hiện lưu
trạng thái (commit) sẽ tạo ra một “ảnh chụp”
(snapshot) lưu lại nội dung tất cả các tập tin, thư
mục tại thời điểm đó rồi tạo tham chiếu tới
snapshot đó. 

:point_right: Để hiệu quả hơn, nếu như tập tin không có thay
đổi, Git không lưu trữ tập tin đó lại mà chỉ tạo
liên kết tới tập tin gốc đã tồn tại trước đó. Sau đó
khi cần bạn hoàn toàn có thể khôi phục và sử
dụng lại một snapshot.

:point_right: **Commit**: Là là thao tác báo cho hệ thống biết
bạn muốn lưu lại trạng thái hiện hành, ghi nhận
lại lịch sử các xử lý như đã thêm, xóa, cập nhật
các file hay thư mục nào đó trên repository.

:point_right: Khi thực hiện **commit**, trong repository sẽ ghi lại
sự khác biệt từ lần **commit** trước với trạng thái
hiện tại.

:point_right: Các **commit** ghi nối tiếp với nhau theo thứ tự
thời gian do đó chỉ cần theo vết các commit thì
có thể biết được lịch sử thay đổi trong quá khứ.

:point_right: **Branch (Nhánh)**: Trong git, nhánh là một phiên
bản mã nguồn tách riêng từ nhánh
chính(thường gọi là master) nhằm mục đích
them các tính năng đang phát triển, fix bug mà
không làm ảnh hưởng đến nhánh chính

:point_right: Một repo có thể có nhiều nhánh và các nhánh
có thể hợp nhất code lại với nhau. 

### Ưu điểm của Git :thumbsup:

* Cho phép làm việc với kho lưu trữ mã nguồn
offline.Git:heavy_check_mark:

* Dễ dàng thực hiện việc tích hợp thêm các chức
năng vào mã nguồn đang phát triển.Git:heavy_check_mark:

* Lưu trữ mã nguồn hiệu quả và tiết kiệm dung
lượng.Git:heavy_check_mark:

* Miễn phí, mã nguồn mở Git:heavy_check_mark:

## :two:.Tìm hiểu về Github

### Lịch sử của Github:scroll:

* GitHub là một dịch vụ cung cấp kho lưu trữ mã
nguồn Git dựa trên nền web cho các dự án phát
triển phần mềm.
* Sự phát triển của nền tảng GitHub bắt đầu vào
ngày 19 tháng 10 năm 2007. Trang web được đưa
ra vào tháng 4 năm 2008 do Tom PrestonWerner, Chris Wanstrath, và PJ Hyett.
* Vào ngày 4 tháng 6 năm 2018, Microsoft đã
thông báo việc đạt được thỏa thuận mua lại
GitHub với giá 7,5 tỷ Đô la Mỹ.

### Các thành phần của Github :octocat:

:point_right: Giao diện web trực quan: Dự án trên Github có
thể được truy cập và thao tác sử dụng một giao
diện dạng web và làm việc với tất cả các lệnh Git
tiêu chuẩn. 

:point_right: Dễ dàng tìm kiếm các repo công cộng: Github
cũng cho phép người dùng đăng ký và không
đăng ký tài khoản để duyệt repository công
cộng trên trang web. 

:point_right: Đầy đủ chức năng của một mạng xã hội:
Trang web cung cấp các chức năng mạng xã hội
như feed, theo dõi, wiki và đồ thị mạng xã hội
để hiển thị cách các dev làm việc trên repository
dự án.

:point_right: Mỗi người sử dụng phải tạo ra một tài khoản cá
nhân để đóng góp nội dung lên Github, nhưng
các repo công cộng có thể được duyệt và tải về
với bất cứ ai. 

:point_right: Với một người dùng đã đăng ký tài khoản, họ có
thể thảo luận, quản lý, tạo ra các repo, đóng góp
cho repo dự án của người dùng khác, và xem
xét thay đổi mã.

:point_right: Lưu trữ các đoạn code nhỏ: GitHub cũng có
một dịch vụ khác: một trang web kiểu pastebin
gọi là Gist, dùng để lưu trữ các đoạn mã; trong
khi Github sẽ được cho lưu trữ các dự án lớn
hơn.

### Ưu điểm của Github :thumbsup:

* Quản lý và tổ chức code hiệu quả.Git:heavy_check_mark:

* Dễ dàng hơn cho dev trong việc code cùng
nhau, đánh giá code và hợp nhất code.Git:heavy_check_mark:

* Có cộng đồng mã nguồn mỡ và lớn sử dụng
github rộng rãi.Git:heavy_check_mark:

* Dễ viết tài liệu và tìm bug, fix bug.Git:heavy_check_mark:
 
* Có hỗ trợ các tool CI/CD, quản lý project và hơn
thế nữa.Git:heavy_check_mark:

## :three:.Demo

### Các lệnh Git thường dùng

* Tạo một repo cục bộ từ folder:
    * cd “tên folder”
    * git init

* Thêm file chuẩn bị commit:
    * Add từng file: git add “file1” “file2” …
    * Add nhiều file: git add .

* Commit:
    * git commit –m “Commit message”
    
* Xem trạng thái commit:
    * git status

* Xem lịch sử commit:
    * git log

* Tạo nhánh mới
    * git branch “Tên nhánh”

* Chuyển từ nhánh chính sang nhánh khác:
    * git checkout “Tên nhánh”

* Liệt kê tất cả các nhánh
    * git branch

* Hợp nhất code với nhánh chính
    * git checkout “Tên nhánh chính”
    * git merge “Nhánh cần hợp nhất”

* Thêm remote repo vào local repo
    * git remote add origin “repository url”

* Đẩy code từ local repo lên remote repo
    * git push -u origin “tên nhánh chính”

* Cập nhật thay đổi ở remote repo:
    * git pull origin “tên nhánh”

* Tạo một bản copy remote repo ở trên máy:
    * git clone “remote url”
    
***by Tensoract***
