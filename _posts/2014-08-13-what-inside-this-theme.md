---
layout: post
title: Tôi làm những gì với theme này?
tags:
- jekyll
- theme
- design
---

Tạm thời dựng một cái template thế này thôi đã. Có rất nhiều thứ có thể tuỳ biến nhưng chưa có thời gian nghịch. Bài viết ở đây chia làm 3 loại.

bài thông thường:
    
    ---
    layout: post
    title: post title 
    tags: post tags
    ---

hình ảnh:

    ---
    layout: post
    title: photo title
    kind: photo
    caption: photo caption putting here
    ---

photo slideshow: 

    ---
    layout: post
    title: slideshow title
    kind: slideshow
    slides:
    - url: path/to/image
    - url: path/to/image
    - url: path/to/image
    ---

###Kinh nghiệm
- github hỗ trợ hiển thị `.scss` file, không cần biên dịch trước.
- khai báo các file hình nền phần YAML đầu trang. Mỗi trang có thể có hình nền riêng. Nên dùng hình `.svg` cho nhẹ.
- dùng nhiều hình nền cũng được, miễn là nhẹ để người xem khỏi đợi lâu.

###Còn phải làm gì?
- hiển thị trên mobile. Làm responsive luôn là vấn đề rắc rối.
- video post? sound post? code highlight?
- gallery post (baguette box is good enough?)
- header and footer redesign
