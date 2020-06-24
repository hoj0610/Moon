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
# 나의 반려동물을 소개해봅시다.
# Let me introduce my pet.

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

---

[BACK](https://hoj0610.github.io/posts/){: .btn}
