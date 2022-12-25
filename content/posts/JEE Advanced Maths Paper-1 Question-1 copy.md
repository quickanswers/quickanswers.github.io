---
title: "JEE Advanced Maths Paper-1 | Question-1 | Detailed Solution"
date: 2022-12-08T00:04:05+05:30
draft: false
tags: ["Statistics", "Probability"]
categories: ["Maths", "JEE advanced", "Paper-1", "2022"]
cover: 
    image: img/post_1.png
    # alt: "Jee Advanced Maths Paper-1 | Question-1 | Detailed Solution"
    # caption: "Jee Advanced Maths Paper-1 | Question-1 | Detailed Solution"
---
<!-- ![Test Image](/img) -->

In this problem, we are given data about the symptoms of 900 persons in a study about a pandemic. Our goal is to find the probability that a randomly chosen person has at most one symptom.

To solve this problem, we can use the principle of inclusion-exclusion. This principle states that if we have a group of people with multiple characteristics, we can find the number of people with a certain combination of characteristics by adding the number of people with each characteristic separately, then subtracting the number of people with any pair of characteristics, then adding back the number of people with any triple of characteristics, and so on.

In this case, we want to find the number of people with at most one symptom. To do this, we can use the following steps:

Add the number of people with each symptom separately: 190 + 220 + 220 = 630
Subtract the number of people with any pair of symptoms: 330 - 30 = 300
Add back the number of people with all three symptoms: 30
Divide the final result by the total number of people to find the probability: (630 - 300 + 30)/900 = 360/900 = 2/5
Therefore, the probability that a person chosen randomly from these 900 persons has at most one symptom is 2/5.

