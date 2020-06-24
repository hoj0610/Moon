---
layout: post
title: "숫자맞히기 게임"
date: 2020-06-22
excerpt: "UP-DOWN GAME"
tags: [sample post, readability, test, image, feature]
feature: './images-git/하늘.jpg
comments: true
---
# 숫자맞히기 게임을 시작해봅시다!

# Let's paly the up&down game!

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

[BACK](https://hoj0610.github.io/posts/){: .btn}
