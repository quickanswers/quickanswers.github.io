---
title: "JEE Advanced Maths Paper-2 | Question-1 | Detailed Solution"
date: 2022-12-11T00:04:05+05:30
draft: false
tags: ["Differentialequation", "Slope"]
categories: ["Maths", "JEE advanced", "Paper-2", "2022"]
cover: 
    image: img/post_8.png
    # alt: "Jee Advanced Maths Paper-1 | Question-1 | Detailed Solution"
    # caption: "Jee Advanced Maths Paper-1 | Question-1 | Detailed Solution"
---

The equation we are given can be written as: 

𝑥𝑑𝑦−(𝑦2−4𝑦)𝑑𝑥=0

This is a first-order linear differential equation and can be solved using the integrating factor method. The integrating factor is 𝑚=e^(∫𝑥𝑑𝑥)=e^(x^2/2).

We multiply both sides of the equation by the integrating factor to get:

e^(x^2/2)𝑥𝑑𝑦−e^(x^2/2)(𝑦2−4𝑦)𝑑𝑥=0

Now, we can integrate both sides of the equation to get:

∫e^(x^2/2)𝑥𝑑𝑦−∫e^(x^2/2)(𝑦2−4𝑦)𝑑𝑥=C

After integration, we get:

e^(x^2/2)*y - 1/2*e^(x^2/2)*(y^2 - 4y) = C

Now, we can use the initial condition y(1) = 2 to solve for the constant C. Substituting y = 2 and x = 1 in the above equation, we get:

e^(1/2)*2 - 1/2*e^(1/2)*(2^2 - 4*2) = C

Therefore, C = e^(1/2) - 1/2*e^(1/2)*4 = 1/2*e^(1/2).

Now, substituting C and x = √2 in the equation, we get:

e^(2/2)*y - 1/2*e^(2/2)*(y^2 - 4y) = 1/2*e^(1/2)

Rearranging the terms, we get:

e^(2/2)*y - 1/2*e^(2/2)*y^2 + 2*e^(2/2)*y = 1/2*e^(1/2)

Finally, we can solve for y:

e^(2/2)*y - 1/2*e^(2/2)*y^2 = 1/2*e^(1/2) - 2*e^(2/2)*y

y^2 - 4y + 2*e^(-2/2) = 0

Solving the above quadratic equation, we get:

y = 2 ± √(4 - 2*e^(-2/2)) 

y = 2 ± √(4 - 2*e^(-1)) 

y = 2 ± 2*e^(-1/2) 

Therefore, the value of 10y(√2) is:

10*(2 + 2*e^(-1/2)) = 10*(2 + 2*2^(-1/2)) = 10*(2 + √2) ≈ 20.83.