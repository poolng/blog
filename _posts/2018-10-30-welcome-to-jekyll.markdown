---
layout: post
title:  "สร้าง blog ด้วย Jekyll ใน 5 ขั้นตอน!"
date:   2018-10-30 15:19:27 +0700
categories: jekyll update
---

1.เปิดโปรแกรม Terminal

2.ติดตั้งโปรแกรม Jekyll 

ใช้คำสั่ง 
{% highlight ruby %}
gem install bundler jekyll
{% endhighlight %}

3.สร้างโฟลเดอร์ `my-blog` และแบบร่าง blog 

ใช้คำสั่ง 
{% highlight ruby %}
jekyll new my-blog         
{% endhighlight %}

4.เจาะเข้าไปในโฟลเดอร์ `my-blog` 

ใช้คำสั่ง 
{% highlight ruby %}
cd my-blog                 
{% endhighlight %}

5.สุดท้าย 

ใช้คำสั่ง 
{% highlight ruby %}
bundle exec jekyll serve
{% endhighlight %}
เปิด blog ให้ใช้งานได้

ถึงจุดนี้สามารถเปิด web browser (Chrome, FireFox, IE, Safari) 
เพื่อดู blog ที่พึ่งสร้างใหม่ได้ที่ http://localhost:4000






