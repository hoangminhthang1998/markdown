# Hướng dẫn cài đặt Ubuntu trên máy tính ảo VMware chuẩn nhất
Mục Lục Nội Dung

[I. Cần chuẩn bị những gì ?](https://blogchiasekienthuc.com/thu-thuat-hay/cai-dat-ubuntu-tren-may-tinh-ao-vmware.html#i-can-chuan-bi-nhung-gi)

[II. Cài đặt phần mềm VMware Pro](https://blogchiasekienthuc.com/thu-thuat-hay/cai-dat-ubuntu-tren-may-tinh-ao-vmware.html#ii-cai-dat-phan-mem-vmware-pro)

[III. Cài đặt Linux lên trên máy ảo VMware](https://blogchiasekienthuc.com/thu-thuat-hay/cai-dat-ubuntu-tren-may-tinh-ao-vmware.html#iii-cai-dat-linux-len-tren-may-ao-vmware)

Nếu như bạn là một sinh viên đam mê công nghệ hoặc bạn là một sinh viên đang theo học ngành công nghệ thông tin thì việc biết cách cài đặt và sử dụng hệ điều hành Ubuntu trên [máy tính ảo](https://blogchiasekienthuc.com/thu-thuat-may-tinh/tao-may-tinh-ao-bang-vmware-workstation.html) (cụ thể VMware) là vô cùng quan trọng. Đặc biệt đối với các bạn học chuyên ngành IT thì môn học hệ điều hành là một môn bắt buộc và không thể thiếu được.
Chính vì vậy mà hôm nay, mình sẽ hướng dẫn cho các bạn cách để **cài đặt hệ điều hành Ubuntu trên máy tính ảo VMware** một cách đơn giản và hiệu quả nhất.
Mục đích của bài viết này là giới thiệu cách thức cài đặt hệ điều hành Ubuntu lên máy ảo VMWare Pro. Sau khi cài đặt xong thì bạn có thể tự khám phá về cách sử dụng, cũng như cách hoạt động của hệ điều hành này và lập trình sử dụng Shell cho các bài thực hành môn Hệ điều hành.
### I. Cần chuẩn bị những gì ?
Những thứ cần chuẩn bị trước khi thực hiện các bước trong bài thực hành này bao gồm:

Phần mềm VMWare Workstation ( trong bài hướng dẫn này mình dùng phiên bản VMWare Pro 14 ). Nói chung là phiên bản nào cũng OK cả thôi 😀 [Link tải](https://my.vmware.com/web/vmware/details?downloadGroup=WKST-1412-WIN&productId=686&rPId=23138)

File cài đặt Ubuntu (file ISO): [Link tải](https://www.ubuntu.com/download/desktop)
### II. Cài đặt phần mềm VMware Pro
Quá trình cài đặt rất dễ, bạn tham khảo các bước cài đặt sau đây.

**+ Bước 1** : Nhấp đúp chuột vào file cài đặt VMware hoặc nhấn chuột phải vào file cài và chọn `Run as administrator để` chạy với quyền Admin => và chọn `Next`.


![cai-ubuntu-tren-may-ao-vmware (18)](https://blogchiasekienthuc.com/wp-content/uploads/2018/07/cai-ubuntu-tren-may-ao-vmware-18.png)


**+ Bước 2**: Đánh dấu tích vào ô `Accept` => nhấn `Next` để đồng ý với điều khoản sử dụng phần mềm.


![cai-ubuntu-tren-may-ao-vmware (1)](https://blogchiasekienthuc.com/wp-content/uploads/2018/07/cai-ubuntu-tren-may-ao-vmware-1.png)

Tiếp tục nhấn `Next..`


![cai-ubuntu-tren-may-ao-vmware (2)](https://blogchiasekienthuc.com/wp-content/uploads/2018/07/cai-ubuntu-tren-may-ao-vmware-2.png)

Nhấn `Next` tiếp tục… 😛


![cai-ubuntu-tren-may-ao-vmware (3)](https://blogchiasekienthuc.com/wp-content/uploads/2018/07/cai-ubuntu-tren-may-ao-vmware-3.png)

Nhấn `Next` phát nữa….


![cai-ubuntu-tren-may-ao-vmware (4)](https://blogchiasekienthuc.com/wp-content/uploads/2018/07/cai-ubuntu-tren-may-ao-vmware-4.png)

**+ Bước 3** : Sau đó bạn nhấn chọn `Install` để cài đặt.


![cai-ubuntu-tren-may-ao-vmware (5)](https://blogchiasekienthuc.com/wp-content/uploads/2018/07/cai-ubuntu-tren-may-ao-vmware-5.png)

Quá trình cài đặt sẽ bắt đầu diễn ra, bạn vui lòng đợi cho quá trình này kết thúc.


![cai-ubuntu-tren-may-ao-vmware (6)](https://blogchiasekienthuc.com/wp-content/uploads/2018/07/cai-ubuntu-tren-may-ao-vmware-6.png)


**+ Bước 4** : Cuối cùng, bạn nhấn `Finish` để kết thúc. Bây giờ chúng ta có thể sử dụng phần mềm VMware với đầy đủ các tính năng cho phần thực hành.


![cai-ubuntu-tren-may-ao-vmware (7)](https://blogchiasekienthuc.com/wp-content/uploads/2018/07/cai-ubuntu-tren-may-ao-vmware-7.png)


### III. Cài đặt Linux lên trên máy ảo VMware

**+ Bước 1**: Bạn nhấn vào nút `Create a New Virtual Machine`.

![cai-ubuntu-tren-may-ao-vmware (8)](https://blogchiasekienthuc.com/wp-content/uploads/2018/07/cai-ubuntu-tren-may-ao-vmware-8.png)

**+ Bước 2** : Chọn dạng cài đặt là `Typical` => sau đó nhấn chọn `Next` để tiếp tục.

![cai-ubuntu-tren-may-ao-vmware (9)](https://blogchiasekienthuc.com/wp-content/uploads/2018/07/cai-ubuntu-tren-may-ao-vmware-9.png)

**+ Bước 3** : Tích chọn `Installer disc image file (iso)` => nhấn vào `Browse.....` để chọn đường dẫn trỏ tới file ISO của bộ cài Ubuntu => và `Next`.

![cai-ubuntu-tren-may-ao-vmware (10)](https://blogchiasekienthuc.com/wp-content/uploads/2018/07/cai-ubuntu-tren-may-ao-vmware-10.png)

**+ Bước 4** : Đặt `Tên` và `Password` (lưu ý không viết hoa chữ cái đầu tiên cho `user name` nhé). Sau đó nhấn `Next`.

![cai-ubuntu-tren-may-ao-vmware (11)](https://blogchiasekienthuc.com/wp-content/uploads/2018/07/cai-ubuntu-tren-may-ao-vmware-11.png)

Bạn có thể đặt lại tên trong mục `Virtual machine name`, hoặc có thể giữ nguyên theo mặc định => chọn `Next`.

![cai-ubuntu-tren-may-ao-vmware (12)](https://blogchiasekienthuc.com/wp-content/uploads/2018/07/cai-ubuntu-tren-may-ao-vmware-12.png)

**+ Bước 5** : Chọn dung lượng ổ cứng cho máy ảo như hình, theo mình bạn nên để trong khoản 20 – 50 GB tùy vào dung lượng ổ cứng và nhu cầu sử dụng của bạn.

![cai-ubuntu-tren-may-ao-vmware (13)](https://blogchiasekienthuc.com/wp-content/uploads/2018/07/cai-ubuntu-tren-may-ao-vmware-13.png)

**+ Bước 6** : Bạn có thể chọn `Customize Hardware` để thay đổi tùy chọn và có nhiều tùy chọn hơn.

![cai-ubuntu-tren-may-ao-vmware (14)](https://blogchiasekienthuc.com/wp-content/uploads/2018/07/cai-ubuntu-tren-may-ao-vmware-14.png)

**+ Bước 7** : Các tùy chọn có thể thay đổi như hình dưới. Nếu như máy tính của bạn có dung lượng RAM lớn, thì nên để RAM nhiều nhiều một chút để máy tính ảo chạy mượt hơn.

Sau đó nhấn `Close` và `Finish`

![cai-ubuntu-tren-may-ao-vmware (15)](https://blogchiasekienthuc.com/wp-content/uploads/2018/07/cai-ubuntu-tren-may-ao-vmware-15.png)
**+ Bước 8**: Giao diện cài xong như hình bên dưới => chọn `Power on the virtual machine` để khởi động và boot vào bộ cài Ubuntu.

![cai-ubuntu-tren-may-ao-vmware (16)](https://blogchiasekienthuc.com/wp-content/uploads/2018/07/cai-ubuntu-tren-may-ao-vmware-16.png)

Quá trình boot và bung file Ubuntu ra máy ảo đang diễn ra. Bạn đợi cho quá trình này kết thúc thôi 😀

![cai-ubuntu-tren-may-ao-vmware (17)](https://blogchiasekienthuc.com/wp-content/uploads/2018/07/cai-ubuntu-tren-may-ao-vmware-19.png)

Vậy là thành công rồi !

![cai-ubuntu-tren-may-ao-vmware (18)](https://blogchiasekienthuc.com/wp-content/uploads/2018/07/cai-ubuntu-tren-may-ao-vmware-20.png)

Giao diện như hình bên dưới.

![cai-ubuntu-tren-may-ao-vmware (19)](https://blogchiasekienthuc.com/wp-content/uploads/2018/07/cai-ubuntu-tren-may-ao-vmware-21.png)

Vậy là chúng ta đã cài đặt thành công, bây giờ thì bạn đã có thể sử dụng hệ điều hành Ubuntu này để lập trình cho môn học Hệ điều hành.

	```sh
	**Lưu ý**: Để kích hoạt bản quyền cho phần mềm VMware Pro thì bạn có thể nhấn vào nút Enter a license key => và nhập Key vào. Key ở đâu thì bạn có thể tìm kiếm trên mạng có rất là nhiều luôn 😀
	```
	
![cai-ubuntu-tren-may-ao-vmware (20)](https://blogchiasekienthuc.com/wp-content/uploads/2018/07/cai-ubuntu-tren-may-ao-vmware-17.png)

- Đọc thêm:
  - [Phần mềm tạo máy tính ảo VMware Workstation 12 Pro](https://blogchiasekienthuc.com/phan-mem-mien-phi/phan-mem-tao-may-tinh-ao.html)
  - [Kinh nghiệm, thủ thuật sử dụng phần mềm tạo máy ảo VMware](https://blogchiasekienthuc.com/thu-thuat-hay/thu-thuat-su-dung-vmware-phan-mem-tao-may-ao.html)
  - [Thiết lập chế độ Boot ưu tiên mặc định trên máy tính ảo VMware](https://blogchiasekienthuc.com/thu-thuat-hay/thiet-lap-che-do-boot-uu-tien-mac-dinh-tren-may-tinh-ao-vmware.html)
  
**Lời kết**

Vâng ! Đến đây mình vừa hướng dẫn xong cho các bạn **cách cài đặt hệ điều hành Ubuntu trên máy ảo VMware Pro** rồi nhé. Phải công nhận là rất đơn giản đúng không nào 😀
Hi vọng bài chia sẻ của mình trong ngày hôm nay sẽ giúp ích cho bạn và mang lại thêm cho bạn những kiến thức thú vị và bổ ích. Chúc các bạn học tập tốt ! Good Luck.