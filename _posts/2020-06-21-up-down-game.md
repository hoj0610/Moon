---
layout: post
title: "숫자맞히기 게임"
date: 2013-05-22
excerpt: "up-down game"
tags: 
- post
- programming
- python
comments: true
---
# <center>숫자맞히기 게임을 시작해봅시다!</center>
# <center>Let's play the up&down game!</center>

---
## python code

{% highlight css %}
import random
count=0
guess=0
number=random.randint(1,100)
print("< UP&DOWN GAME >")

while guess != number:
    count=count+1
    guess=int(input("Please enter a number : "))
    if guess>number:
        print("DOWN")
    elif guess<number:
        print("UP")
    else :
        print("CONGRATULATIONS! COUNT = ",count)
        break
{% endhighlight %}

---

## result
{% highlight css %}
Python 3.8.3 (tags/v3.8.3:6f8c832, May 13 2020, 22:20:19) [MSC v.1925 32 bit (Intel)] on win32
Type "help", "copyright", "credits" or "license()" for more information.
>>> 
============ RESTART: C:\Users\PC\Desktop\유쾌한 코딩 (lms)\파이썬 테스트\ff.py ===========
< UP&DOWN GAME >
Please enter a number : 80
DOWN
Please enter a number : 40
DOWN
Please enter a number : 20
DOWN
Please enter a number : 10
UP
Please enter a number : 15
UP
Please enter a number : 17
DOWN
Please enter a number : 16
CONGRATULATIONS! COUNT =  7
>>> 
{% endhighlight %}

---

[BACK](https://hoj0610.github.io/posts/){: .btn}
