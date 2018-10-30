---
layout: post
title:  "การสร้าง blog ด้วย Jekyll อย่างเร็วๆ ใน 5 ขั้นตอน!"
date:   2018-10-30 15:19:27 +0700
categories: jekyll update
---

1.เปิดโปรแกรม Terminal

2.ใช้คำสั่ง 
{% highlight ruby %}
gem install bundler jekyll
# เพื่อติดตั้งโปรแกรม Jekyll
{% endhighlight %}

3.ใช้คำสั่ง 
{% highlight ruby %}
jekyll new my-blog         
# สร้าง blog ใหม่ในโฟลเดอร์ `my-blog`
{% endhighlight %}

4.ใช้คำสั่ง 
{% highlight ruby %}
cd my-blog                 
# เพื่อเข้าไปในโฟลเดอร์ `my-blog`
{% endhighlight %}

5.ใช้คำสั่ง 
{% highlight ruby %}
bundle exec jekyll serve
# => ถึงจุดนี้สามารถเปิด browser เพื่อดู blog ที่พึ่งสร้างใหม่ได้ที่ http://localhost:4000
{% endhighlight %}






