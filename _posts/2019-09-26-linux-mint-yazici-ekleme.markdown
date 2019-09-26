---
layout: post
title: "Linux Mint Yazıcı Ekleme"
date: 2019-09-26 12:00:00 +300
categories: jekyll update
---
Merhabalar,

bugün kendi sistemime kurduğum ve başka sistemlere muhtaç olmadan kullanabildiğim yazıcımın sisteme ekleme aşamasını anlatacağım.

Öncelikle terminalimizi açıp, cups paketini kurmamız gerekmektedir.

{% highlight ruby %}
-> sudo apt install cups
{% endhighlight %}

Kurulum aşaması bittikten sonra, localhost:631 adresine gidiyoruz.

Burada bizi kategoriler karşılamakta, 2.kategori(CUPS for Administrators) kısmında Adding Printers and Classes olan kısma gidelim.

Burada Printers->Add Printer dedikten sonra bize kullanıcı adı(sistemimizdeki) ve şifremizi sormakta, devam ettikten sonra yazıcımıza göre seçenekleri seçip ekliyoruz :)
