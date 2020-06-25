---
layout: post
title:  "랜덤 함수 복습"
date:   2020-06-23
excerpt: "random function"
tag:
- post
- programming
- python
comments: true
---
# <center>랜덤 함수</center>
# <center>random function review</center>

---
## python code

### 랜덤값 정의
{% highlight css %}
from random import *
{% endhighlight %}

### 0.0 ~ 1.0 미만의 임의의 값 생성
{% highlight css %}
print(random())
print(random())
print(random())
print(random())
print(random())
print(random())
{% endhighlight %}

### 0.0 ~ 10.0 미만의 임의의 값 생성
{% highlight css %}
print(random()*10)
print(random()*10)
print(random()*10)
print(random()*10)
print(random()*10)
print(random()*10)
print(random()*10)
{% endhighlight %}

### 1 ~ 10 이하의 임의의 값 생성
{% highlight css %}
print(int(random()*10)+1)
print(int(random()*10)+1)
print(int(random()*10)+1)
print(int(random()*10)+1)
print(int(random()*10)+1)
print(int(random()*10)+1)
print(int(random()*10)+1)
{% endhighlight %}

### 1 ~ 46 미만의 임의의 값 생성
{% highlight css %}
print(randrange(1, 46))
print(randrange(1, 46))
print(randrange(1, 46))
print(randrange(1, 46))
print(randrange(1, 46))
print(randrange(1, 46))
{% endhighlight %}

### 1 ~ 45 이하의 임의의 값 생성
{% highlight css %}
print(randint(1, 45))
print(randint(1, 45))
print(randint(1, 45))
print(randint(1, 45))
print(randint(1, 45))
print(randint(1, 45))
{% endhighlight %}

---

## result
{% highlight css %}
Python 3.8.3 (tags/v3.8.3:6f8c832, May 13 2020, 22:20:19) [MSC v.1925 32 bit (Intel)] on win32
Type "help", "copyright", "credits" or "license()" for more information.
>>> 
=================== RESTART: C:\Users\PC\Desktop\공부용\랜덤함수.py ===================
0.40672947459391173
0.034289954958000024
0.3877833217111154
0.7575104265679691
0.055630820607029396
0.20982870096836892
1.9564978407520606
0.9939222826397487
7.874053559302215
1.6928552249296125
0.2579489376603039
4.205195178928597
2.158375645087023
7
9
6
9
2
8
3
31
15
28
37
23
33
28
29
27
33
44
10
>>>
{% endhighlight %}

---

[BACK](https://hoj0610.github.io/posts/){: .btn}
