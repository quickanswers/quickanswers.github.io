---
title: "JEE Advanced Maths Paper-1 | Question-3 | Detailed Solution"
date: 2022-12-10T00:04:05+05:30
draft: false
tags: ["ArithmeticProgression", "CommonDifference", "Algebra", "Geometry"]
categories: ["Maths", "JEE advanced", "Paper-1", "2022"]
cover: 
    image: img/post_3.png
    # alt: 
---
In this problem, we are given two arithmetic progressions with common differences d1 and d2, respectively. The nth term of the first arithmetic progression is ln = l1 + (n-1)d1, and the nth term of the second arithmetic progression is wn = w1 + (n-1)d2. We are also told that the area of the rectangle with length ln and width wn is An = ln * wn.

Our goal is to find the value of A100 - A90, given that A51 - A50 = 1000 and d1d2 = 10.

First, we can use the given information to find the value of d1d2. We are told that A51 - A50 = 1000, which we can express in terms of d1, d2, and the first terms of the two arithmetic progressions:

A51 - A50 = l51 * w51 - l50 * w50 = (l1 + 50d1) * (w1 + 50d2) - (l1 + 49d1) * (w1 + 49d2) = 1000

We can expand this equation to get:

50d1w1 + 2500d1d2 - 49d1w1 - 2401d1d2 = 1000

This simplifies to:

99d1d2 = 601

Since d1d2 = 10, we can divide both sides of this equation by 10 to get:

d1d2 = 601/99

Now that we have found the value of d1d2, we can use it to find the value of A100 - A90.

We are told that A100 - A90 = l100 * w100 - l90 * w90 = (l1 + 99d1) * (w1 + 99d2) - (l1 + 89d1) * (w1 + 89d2).

We can expand this equation to get:

90d1w1 + 8100d1d2 - 89d1w1 - 8009d1d2 = A100 - A90

This further simplifies to:

91d1d2 = 91

Substituting our value for d1d2, we get:

91 * 601/99 = 91

Therefore, the value of A100 - A90 is 91.