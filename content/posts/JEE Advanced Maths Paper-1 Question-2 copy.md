---
title: "JEE Advanced Maths Paper-1 | Question-2 | Detailed Solution"
date: 2022-12-08T00:04:05+05:30
draft: false
tags: ["Complexnumbers", "Equations", "Algebra", "Imaginarynumbers", "Roots"]
categories: ["Maths", "JEE advanced", "Paper-1", "2022"]
cover: 
    image: img/post_2.png
    # alt: 
---
In this problem, we are given the equation z^-1 - z^3 = i(z^-1 + z^3) and asked to find the number of distinct roots of this equation in the set of complex numbers.

To solve this equation, we can start by multiplying both sides by z:

z*(z^-1 - z^2) = i(z*(z^-1 + z^2)).

This simplifies to:

z^-1 - z^3 = i(z^-1 + z^3).

We can then multiply both sides by z^3:

z^2 - z^6 = i(z^2 + z^6).

This simplifies to:

z^6 + z^2 - iz^6 - iz^2 = 0.

Combining the terms on the left-hand side, we get:

(1-i)z^6 + (1-i)z^2 = 0.

We can then factor this equation as:

(z^2 + 1)(z^4 - iz^2 + 1) = 0.

This equation has two distinct roots: z^2 = -1 and z^4 - iz^2 + 1 = 0.

The roots of the equation z^2 = -1 are z = sqrt(-1) and z = -sqrt(-1). These are the same as the roots of the equation z^2 + 1 = 0, so we only count them once.

The roots of the equation z^4 - iz^2 + 1 = 0 can be found using the quadratic formula. The roots are:

z = sqrt(i +/- sqrt(3))/sqrt(2).

These roots are distinct, since they have different values.

Therefore, the total number of distinct roots of the equation z^-1 - z^3 = i(z^-1 + z^3) is 2 + 2 = 4.

So the answer is 4.