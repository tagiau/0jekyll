---
layout: post
title: Hướng dẫn sơ
author: admin
tags: [ghim]
---
Đây là bài gửi được viết từ github new file. 
Nội dung tóm lược xem trước ở đây. Tốt nhất là hơn 22 từ trước khi thêm các thẻ html hoặc kiểu markdown

### Phần gửi bài
- Muốn tạo bài thì bạn tạo 2016-10-10-filename.md vào thư mục _posts ở ngoài hoặc trong subcat
- Bạn hãy tham khảo nội dung 1 bài mẩu nào đó (---...---)
- Lưu ý là thumb nếu là link có http thì tự code sẽ hiển thị hình luôn còn ko là dạng thumbname.jpg, bạn hãy tải
lên thư mục assets/pthumb/thumbname.jpg

### Phần skin
- Là dùng để đổi skin theo mùa, dự tính làm sẵn 8 skin.
- Skin là thư mục nằm trong _include/{skin-name}.
- Làm skin để dùng chung data _posts
- Bạn muốn thay đổi skin thì vào _config.yml > skin , đổi giống tên thư mục trong _include
- Bạn hãy tạo dùm vài skin và gửi mình nhé. Bằng cách nhân bản 1 skin nào đó và tùy chỉnh.

### Phần chuyên mục (cat)
- Bộ code này hổ trợ cat bằng thư mục ngang _config.yml. Bên trong gồm 1 file index.html và thư mục _posts
- Để tạo 1 cat bạn hãy nhân bản thư mục subcat, và có thể tạo bài trong _posts

### Phần nhãn (tag)
- Trong jekyll tag khác cat và đôi lúc chúng cũng giống nhau, nên phần tag mình chỉ dùng làm nhãn cho bài và ko có phân url

### Phần comment
- Trong bộ cod này có sẵn phần comment bằng firebase nhưng bạn sẽ ko sài được vì crossdomain
- Bạn hãy vào _include/comment đọc và thay đổi cái url firebase.
- Nếu thích thì mình làm thêm phần comment bằng facebook.

Tạm thời nhiu đó. rất mong được chia sẽ với các bạn. hãy fork project này và chúng ta cùng đóng góp nhé.
