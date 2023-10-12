# 1. Hệ điều hành Linux là gì?
Linux là một hệ điều hành máy tính mã nguồn mở được phát triển từ năm 1991 dựa trên hệ điều hành Unix và bằng viết bằng ngôn ngữ C.

Do Linux được phát hành miễn phí và có nhiều ưu điểm vượt trội nên Linux vẫn giữ được một chỗ đứng vững chắc trong lòng người dùng trước các ông lớn như Windows hay macOS.
# 2. Các distro (bản phân phối) phổ biến của Linux
## 2.1 Ubuntu
Hệ điều hành Ubuntu là một trong những bản phân phối (distro) Linux phổ biến nhất hiện nay do Mark Shuttleworth sáng lập và công ty Canonical của ông tài trợ. Hệ điều hành này được sử dụng phổ biến và ưa chuộng vì có giao diện đẹp, thân thiện, dễ sử dụng, kho phần mềm ứng dụng rất phong phú đáp ứng được hầu hết yêu cầu của người dùng, các version được cập nhật liên tục.  

Ubuntu được chia làm 2 loại:  
+ Ubuntu Desktop: Sử dụng cho người dùng cuối (end user). 
+ Ubuntu Server: Sử dụng để cài các dịch vụ phục vụ cho người dùng cuối.  
## 2.2 Debian
Debian là một distro chứa số lượng các phần mềm rất lớn, Debian được xây dựng bởi một tổ chức nguyên tình nguyện cống hiến đểphát triển phần mềm tự do và đẩy mạnh những lý tưởng của công 
động phần mềm tự do. Dự án Debian xây dựng vào năm 1993. Debian có tiếng về mối liên kết chặt chẽ với triết lí Unix và phần mềm tự do. Nó cũng 
có tiếng về sự phong phú cho các chọn lựa: phiên bản phát hành hiện tại có hơn 29000 gói phần mềm cho 11 kiến trúc máy tính, từ kiến trúc ARM thường gặp ở các hệ thống nhúng và kiến trúc máy tính lớn s390 của IBM cho đến các kiến trúc thường gặp trên máy tính cá nhân hiện đại như x86 và PowerPC. Debian được hỗ trợ nhờ các khoản quyên góp thông qua tổ chức Software in the Public Interest, một tổ chức bảo trợ phi lợi nhuận cho các dự án phần mềm tự do.  
## 2.3 RedHat Enterprise Linux
Red Hat Enterprise Linux (RHEL) là một bản phân phối Linux được phát triển bởi Red Hat và mục tiêu hướng tới thị trường thương mại. Red Hat Enterprise Linux là một trong những hệ điều hành an toàn nhất hiện có, sẵn sàng đáp ứng khối lượng tính toán cường độ cao out-of-the-box. Ngoài ra còn cung cấp bộ các tùy chỉnh tối ưu hiệu suất giúp bạn điều chỉnh và sắp xếp hành vi hệ thống tùy theo khối lượng công việc cụ thể. Được triển 
khai trong các cơ quan chính phủ, tài chính - ngân hàng, nơi mà bảo vệ dữ liệu là việc 
quan trọng nhất.
## 2.4 Centos
CentOS là viết tắt của Community Enterprise Operating System. Centos là một bản phân phối hệ điều hành tự do dựa trên Linux kernel. Nó có nguồn gốc hoàn toàn từ bản phân phối Red Hat Enterprise Linux (RHEL). Những người phát triển CentOS đã tận dụng mã nguồn của Red Hat để tạo ra một sản phẩm hoàn toàn tương tự tuy nhiên cái 
giá của nó là miễn phí. Ngày nay, CentOS thường được sử dụng trong các doanh nghiệp bởi tính ổn định vòng đời End-of-Life dài.
## 2.5 Kali Linux
Kali Linux là một distro của Linux, được sử dụng để kiểm tra, tấn công thử nghiệm vào các lỗ hỏng của hệ thống công nghệ thông tin. Kali linux được viết dựa trên nền tảng của Debian được đồng bộ hóa với các Repository của Debian nên có thể dễ dàng có được các bản cập nhật vá lỗi bảo mật mới nhất và các cập nhật Repository. Đay là một phiên bản tiến hóa của Backtrack và distro này rất hữu ích đối với những chuyên gia đánh giá bảo mật.
# 3. Cấu trúc hệ điều hành Linux
Kiến trúc của HĐH Linux chia làm 3 thành phần: Kernel, Shell, Applications  
**Kernel (nhân):** Đây là phần quan trọng và được ví như trái tim của HĐH, Phần kernel chứa các module, thư viện để quản lý và giao tiếp với phần cứng và các ứng dụng  
**Shell:** Shell là một chương trình. Có chức năng thực thi các lệnh (command) từ người dùng hoặc từ các ứng dụng – tiện ích yêu cầu chuyển đến cho Kernel xử lý. Bên cạnh đó, shell còn có khả năng bảo vệ kernel từ các yêu cầu không hợp lệ.  
Các loại shell:  
+ Sh (the Bourne Shell): đây là shell nguyên thủy của UNIX được viết bởi 
Stephen Bourne vào năm 1974. Đến nay shell sh vẫn sử dụng rộng rãi.
+ Bash(Bourne-again shell): đây là shell mặc định trên linux.
+ csh (the C shell): shell được viết bằng ngôn ngữ lập trình C, được viết bởi Bill Joy vào năm 1978.
+ Ngoài ra còn có các loại shell khác như: ash (the Almquist shell), tsh (the TENEX C shell), zsh (the Z shell).  

Dấu nhắc Shell thay đổi tùy thuộc vào tài khoản user đang làm việc. Khi làm việc với tài khoản user root, dấu nhắc shell có dạng:   
>[root@localhost root]#   

Khi làm việc với tài khoản user thường, dấu nhắc shell có dạng:  
>[linux@localhost linux]$

**Applications:** Là các ứng dụng và tiện ích mà người dùng cài đặt trên Server. Ví dụ: ftp, samba, Proxy, …



