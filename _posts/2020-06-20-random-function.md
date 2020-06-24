---
layout: post
title:  "랜덤 함수 복습"
date:   2020-06-23
excerpt: "random function"
tag:
- sample
- post
- video
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

[BACK](https://hoj0610.github.io/posts/){: .btn}
