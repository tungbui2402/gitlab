# gitlab
## Khái niệm
GitLab là một trang web dựa trên DevOps mã nguồn mở và là một phần mềm có chức năng và nhiệm vụ quản lý phiên bản mã nguồn, cung cấp một trình quản lý Git-repository. Trình quản lý này có các tiện ích như wiki, theo dõi sự cố và tích hợp liên tục. Bên cạnh đó là khả năng triển khai các tính năng pipeline và sử dụng license mã nguồn mở được phát triển bởi GitLab Inc. Khi sử dụng GitLab các cá nhân hay tổ chức có thể lưu trữ và quản lý kho code dễ dàng, an toàn và truy cập nhanh chóng thông qua Internet. Với GitLab, nó cung cấp dung lượng lưu trữ miễn phí cho người dùng, ngoài ra còn có thể nâng cấp dung lượng (mất phí) khi muốn sử dụng nhiều dung lượng hơn.
## Lịch sử phát triển
- Khởi đầu (2011-2012): GitLab được sáng lập bởi Dmitriy Zaporozhets và Valery Sizov vào năm 2011 tại Ukraine. Phiên bản đầu tiên của GitLab (GitLab 1.0) được phát hành vào tháng 2 năm 2012 với các tính năng cơ bản của một hệ thống quản lý mã nguồn.
- Sự phát triển ban đầu (2012-2014): GitLab nhanh chóng phát triển và thu hút sự quan tâm của cộng đồng phát triển phần mềm mã nguồn mở. Các phiên bản mới liên tục được phát hành với nhiều cải tiến và tính năng mạnh mẽ hơn.
- Hình thành công ty GitLab (2014): Trong năm 2014, GitLab được chuyển từ một dự án mã nguồn mở cá nhân thành một công ty. GitLab B.V. được thành lập và trở thành tập trung chính cho phát triển và hỗ trợ của GitLab.
- Hệ thống GitLab.com (2014): GitLab đã mở cửa hàng trực tuyến GitLab.com, nơi người dùng có thể đăng ký và sử dụng dịch vụ GitLab trên đám mây.
- Khiến cho GitLab trở thành một giải pháp toàn diện (2015-2018): GitLab đã tập trung vào việc tạo ra một nền tảng quản lý mã nguồn và dự án phát triển toàn diện, bao gồm tích hợp liên tục (CI) và phát hành liên tục (CD), quản lý dự án, quản lý vấn đề, và nhiều tính năng khác.
- Kênh cấp dữ liệu, Docker, Kubernetes và DevOps (2017-2019): GitLab tích hợp các công nghệ và khái niệm DevOps, cung cấp một giải pháp hoàn chỉnh để phát triển và triển khai phần mềm. Họ mở rộng tích hợp với Docker và Kubernetes, giúp người dùng triển khai ứng dụng dễ dàng và hiệu quả.
- Cú hích đầu tư và mua lại (2019-2021): GitLab đã nhận được đầu tư đáng kể và tham gia vào các cuộc mua lại chiến lược để mở rộng khả năng và phạm vi của họ.
- Công ty trở thành công ty công cộng (2021): GitLab công bố kế hoạch IPO và trở thành một công ty công cộng, niêm yết trên Sàn giao dịch chứng khoán Nasdaq vào ngày 14 tháng 10 năm 2021 dưới biểu tượng "GTLB".

## Đặc điểm của gitlab
Quản lý Mã nguồn (Source Code Management - SCM):

- Hỗ trợ Git: GitLab sử dụng hệ thống quản lý mã nguồn phổ biến Git cho việc theo dõi và quản lý mã nguồn.
- Tính năng nhánh và hợp nhất: GitLab hỗ trợ quản lý nhánh (branch) và quá trình hợp nhất (merge) để quản lý mã nguồn một cách hiệu quả.

Quản lý Dự án:

- Trang tổng quan dự án: Cung cấp một trang tổng quan về dự án với thông tin về nhóm, lịch sử thay đổi, vấn đề, và CI/CD.
- Tính năng vấn đề (Issue Tracking): Cho phép theo dõi, báo cáo và quản lý vấn đề, công việc, và tính năng trong dự án.

Tích hợp Liên tục và Phát hành Liên tục (CI/CD):

- CI/CD tích hợp sẵn: GitLab cung cấp các tính năng tích hợp liên tục và phát hành liên tục để tự động hóa quy trình phát triển và triển khai.
- Runners: GitLab hỗ trợ GitLab Runners, một phần của hệ thống CI/CD, để thực hiện các công việc phức tạp như kiểm thử và triển khai.

Quản lý Repository và Wiki:

- Quản lý mã nguồn: GitLab cung cấp các công cụ để quản lý repository, xem lịch sử thay đổi, so sánh các phiên bản, và nhiều tính năng khác.
- Wiki tích hợp: Cho phép tạo và quản lý tài liệu dự án trực tiếp trong GitLab.

Tích hợp với Công cụ Phát triển Phần mềm:

- Hỗ trợ tích hợp với nhiều công cụ phát triển khác nhau như Jira, Jenkins, Docker, Kubernetes, và nhiều công cụ khác.
- API mạnh mẽ: GitLab cung cấp API cho phép tích hợp với các dịch vụ và công cụ khác.

Quản lý Quyền lợi và Bảo mật:

- Quản lý quyền: GitLab cung cấp hệ thống quản lý quyền lợi mạnh mẽ để kiểm soát quyền truy cập vào dự án và các tính năng.
- Bảo mật cao: Hỗ trợ nhiều tính năng bảo mật như xác thực hai yếu tố (2FA), quét mã nguồn, và quản lý chính sách bảo mật.

Cộng đồng và Hỗ trợ Thương mại:

- Cộng đồng mở: GitLab có một cộng đồng mạnh mẽ và tích cực, với nhiều đóng góp từ cộng đồng mã nguồn mở.
- GitLab Enterprise: Cung cấp phiên bản hỗ trợ thương mại với các tính năng và dịch vụ mở rộng.

## Lý do nên sử dụng gitlab
Có nhiều lý do mà các tổ chức và nhà phát triển chọn sử dụng GitLab cho quản lý mã nguồn và phát triển phần mềm.

Quản lý Mã nguồn hiệu quả:
   - GitLab sử dụng Git, hệ thống quản lý mã nguồn phổ biến và mạnh mẽ, giúp quản lý mã nguồn một cách hiệu quả.

Tích hợp Liên tục và Phát hành Liên tục (CI/CD):
   - Cung cấp tích hợp liên tục và phát hành liên tục tích hợp sẵn, giúp tự động hóa quy trình phát triển và triển khai.

Quản lý Dự án toàn diện:
   - Cung cấp một nền tảng toàn diện cho quản lý dự án, bao gồm quản lý nhánh, vấn đề, wiki, và tính năng tích hợp với nhiều công cụ phát triển khác.

Wiki tích hợp và Tài liệu Dự án:
   - Có hỗ trợ tích hợp Wiki để tạo và quản lý tài liệu dự án, giúp đội ngũ phát triển dễ dàng chia sẻ thông tin và kiến thức.

Tích hợp với Công cụ Phát triển Phần mềm:
   - Hỗ trợ tích hợp với nhiều công cụ và dịch vụ khác nhau như Docker, Kubernetes, Jira, Jenkins, và nhiều công cụ khác.

Bảo mật và Quản lý Quyền:
   - Cung cấp cơ sở hạ tầng bảo mật mạnh mẽ và có khả năng quản lý quyền lợi chi tiết, giúp bảo vệ mã nguồn và dữ liệu của dự án.

Cộng đồng và Hỗ trợ:
   - GitLab có một cộng đồng mở rộng và tích cực, với hỗ trợ đầy đủ từ cộng đồng và cả từ GitLab Enterprise với dịch vụ hỗ trợ thương mại.

GitLab CI/CD Runners:
   - GitLab CI/CD Runners cho phép thực hiện các công việc phức tạp như kiểm thử và triển khai, mở rộng khả năng của hệ thống CI/CD.

Tính Linh hoạt và Mở rộng:
   - GitLab được thiết kế để linh hoạt và mở rộng, phù hợp với các dự án phát triển phần mềm của mọi kích thước.

Giá Trị Chi phí và Tổng chi phí sở hữu (TCO):
    - GitLab cung cấp phiên bản mã nguồn mở và phiên bản trả phí, cho phép các tổ chức lựa chọn dựa trên nhu cầu của họ và giảm chi phí so với một số giải pháp khác.

Những lý do trên làm cho GitLab trở thành một lựa chọn phổ biến cho quản lý dự án và phát triển phần mềm, đặc biệt là trong môi trường DevOps và các dự án có quy mô lớn.

## Cài đặt
B1: Kiểm tra cập nhật trên máy:
```
sudo apt update
sudo apt upgrade
```
B2: Cài đặt các dependency bằng lệnh:
```
sudo apt install ca-certificates curl openssh-server postfix tzdata perl
```
B3: Cài đặt gitlab:
- Vào thư mục tmp:
```
cd /tmp
```
- Tải script cài đặt:
```
curl -LO https://packages.gitlab.com/install/repositories/gitlab/gitlab-ce/script.deb.sh
```
- Kiểm tra script bằng lệnh less:
```
less /tmp/script.deb.sh
```
- Sau khi kiểm tra xong thì chạy bash:
```
sudo bash /tmp/script.deb.sh
```
- Sau khi chạy bash xong thì chạy lệnh apt để cài gitlab:
```
sudo apt install gitlab-ce
```
B4: Thiết lập các rule của firewall:
```
sudo ufw allow http
sudo ufw allow https
sudo ufw allow OpenSSH
```
- Kiểm tra: `sudo ufw status`

## Chỉnh sửa cấu hình gitlab
B1: Mở file cấu hình gitlab:
```
sudo nano /etc/gitlab/gitlab.rb
```
B2: Tìm dòng `external_url` và đổi 'http://your_domain' về địa chỉ ip của máy. Ví dụ như `https://10.0.5.104`
B3: Lưu file và chạy lệnh sau để chạy lại cấu hình gitlab:
```
sudo gitlab-ctl reconfigure
```

B4: Đăng nhập:
- Truy cập vào file sau để lấy mật khẩu tài khoản root(administrator):
```
sudo nano /etc/gitlab/initial_root_password
```
- Sau đó truy cập vào tên miền và thêm `/users/sign_in`, ví dụ như `https://10.0.5.104/users/sign_in`
- Đăng nhập với tài khoản root và mật khẩu ở file trên
- Sau khi đăng nhập thành công thì ấn vào avatar của tài khoản, chọn `edit profile`
- Ở màn hình `edit profile` chọn `password`, sau đó nhập mật khẩu và xác nhận đổi. Sau khi đổi thì gitlab sẽ quay lại màn hình đăng nhập.
- Đăng nhập tài khoản root với mật khẩu mới để vào gitlab


Nguồn tham khảo: `https://www.youtube.com/watch?v=oqdjLV8q1QM&ab_channel=MivoCloud`
