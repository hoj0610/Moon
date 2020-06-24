---
layout: post
title:  "나의 반려동물은 아이일까 어른일까?"
date:   2020-06-23
excerpt: "Is my pet a child or an adult?"
tag:
- sample
- post
- video
comments: true
---
# <center>나의 반려동물을 소개해봅시다.</center>
# <center>Let me introduce my pet.</center>

---
## python code

{% highlight css %}
animal = input("동물 종이 무엇인가요? : ")
name = input(animal+" 이름은 무엇인가요? : ")
age = int(input("나이를 어떻게 되나요? : "))
is_abult = age >= 3

print("우리집 "+animal+"의 이름은 "+name+"예요")
print(name+"는 "+str(age)+"살입니다.")
print(name+"는 어른일까요? " + str(is_abult))
{% endhighlight %}

## result
{% highlight css %}
Python 3.8.3 (tags/v3.8.3:6f8c832, May 13 2020, 22:20:19) [MSC v.1925 32 bit (Intel)] on win32
Type "help", "copyright", "credits" or "license()" for more information.
>>> 
==================== RESTART: C:\Users\PC\Desktop\공부용\동물.py ====================
동물 종이 무엇인가요? : 고양이
고양이 이름은 무엇인가요? : 디디
나이를 어떻게 되나요? : 4
우리집 고양이의 이름은 디디예요
디디는 4살입니다.
디디는 어른일까요? True
>>> 
{% endhighlight %}

---

[BACK](https://hoj0610.github.io/posts/){: .btn}
