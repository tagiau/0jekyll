---
layout: post
title: Jekyll on android
author: admin
tags: [jekyll,android,termux]
---
{% include video_yt id='Y7Ihxz14Y78' %}
Hướng dẫn cài đặt jekyll trên android không cần root thiết bị.

Đầu tiên bạn phải cài ứng dụng termux, vào play store mà cài dễ thôi mà. Ôtê coi như đã có termux rồi dzô.

- Cấp quyền w/r sdcard cho termux
```
termux-setup-storage
```
- Di chuyển đến thư mục có quyền
```
cd /sdcard/Android/data/com.termux/files
```
- Nâng cấp cái gói termux
```
pkg update
```
- Cài cái gói cho jekyll
```
pkg install ruby-dev libxml2-dev libxslt-dev libffi-dev pkg-config make clang
```
- Cài gói nokogiri, cấu hình đường đẫn
```
gem install nokogiri -- --use-system-libraries --with-xml2-config=/data/data/com.termux/files/usr/bin/xml2-config --with-xml2-include=/data/data/com.termux/files/usr/include/libxml2
```
- Cài jekyll kiểu đầy đủ như github pages
```
gem install github-pages
```
- Cài cái cuối cùng. xong 
```
gem install listen bundler
```

Tao thử site mẫu
```
jekyll new demosite
```
Chạy server jekyll
```
cd demosite
jekyll server
```
(Lần sau có chạy server lại thì di chuyển vào thư mục có project)
```
cd /sdcard/Android/data/com.termux/files/(projectname)
```

Weldone.
