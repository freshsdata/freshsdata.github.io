# Fresh's Data

## Tác giả
Name: Hoàng Minh Tươi
E-mail: hmtuoi.sdh19@hcmut.edu.vn

## Mục đích
Dự án Fresh's Data được thành lập với 2 mục đích:
1.  Hệ thống lại một cách kinh nghiệm hóa những kiến thức và kinh nghiệm đạt được trong quá trình nghiêm cứu và làm việc.
2. Chia sẽ đến các bạn có cùng sở thích để thảo luận và cũng cố thêm sự hiểu biết về các vấn đề liên quan.

## Clone project
git clone git@github.com:freshsdata/freshsdata.github.io.git freshsdata

## Đóng góp cho project
Với vai trò là tác giả, tôi chân thành cảm ơn và chào mừng sự đóng góp từ mọi người để giúp dự án thành công hơn. Bạn có thể đóng góp cho project thông qua các cách:
1. Để lại những chia sẻ của mình ở phần comment cuối mỗi bài.
2. Trực tiếp tham gia xây dựng nội dung cho dự án. Với cách đóng góp này, bạn có thể liên lạc với tôi thông qua e-mail(hmtuoi.sdh19@hcmut.edu.vn).

## Branch trong project
### master
Trên master branch, nội dung blog đã được generate từ *.ipynb files trên devel branch sang *.html files. Đây chính là nội dung hiển thị của blog đến người đọc.
### devel
devel branch được sử dụng trong quá trình xây dựng nội dung cho blog. Bài viết sẽ được viết dưới định dạng file *.ipynb sử dụng editor [Jupyter Notebook](https://jupyter.org/).

## .gitignore
Hiện tại file .gitignore đã được setup để ignore đi một số file phát sinh không cần thiết thêm vào lịch sử trong quá trình xây dựng nội dung cho blog. Trong quá trình xây dựng nội dung có thể tự do chỉnh sửa trên máy local nhưng cần xem xét trước khi publish các thay đổi, tránh trường hợp dư thừa và làm phức tạp file config ban đầu.

## Virtual environment
Trong quá trình xây dựng nội dung cho blog, virtual environment được sử dụng làm môi trường làm việc độc lập cho project. Trong môi trường làm việc này cần setup một số module cần thiết được liệt kê trong file requirements.txt.
* Chú ý: Môi trường sử dụng trong hướng dẫn là Windows 10.
### Yêu cầu trước khi tạo virtual environment
1. [Python version 3.7.4](https://www.python.org/downloads/) hoặc cao hơn.
2. [Pip package](https://pypi.org/project/pip/).
3. [virtualenv package](https://pypi.org/project/virtualenv/). Sử dụng command "pip install virtualenv" để cài đặc virtualenv.
### Tạo và activate virtual environment
Thực hiện commands sau để tạo và activate virtual environment với tên venv.
> virtualenv venv
> .\venv\Scripts\activate
## Install requirement packages
Danh sách các package cần thiết trong quá trình xây dựng nội dung cho blog được liệt kê trong file requirements.txt.
Thực hiện command bên dưới để cài đặt những package cần thiết trong venv.
> pip install -r requirements.txt
## Install submodules
Submodule là các external project cần thiết cho việc xây dựng nội dung blog. Để cài đặt các submodule ta thực hiện các command sau:
> git submodule init
> git submodule update


