---
layout: project
title: "Binary Card Tutor"
date: 2015-12-10 12:00:00 -0400
description: "An interactive program built with CTAT."
categories: binary boolean ITS
thumb: binary_cards.png
permalink: /binary
---

This was my first ever full CTAT<sup>[1]</sup> tutor. I built it during CMU's LearnLab summer school.
I wanted to make an ITS (Intelligent Tutoring System) that was more than just text boxes for students to type in. So I decided to work with binary number conversion. Instead of just converting a decimal to a binary number, the student can visualize what the binary number looks like.


![]({{ site.baseurl }}/assets/binary_demo.gif)

<br><br>

<h3>Some cool elements</h3>
It won't let you enter the binary number values until you flip the cards over to display the correct number of dots.


Each CTAT tutor has a skill bar that can be used to track a student's skill improvement over time.


<br><br>

<h3>Improvements I would make</h3>
- Bug: it still says "until only 2 dots are visible". It should change with the problem and say "6".
- It should explicitly teach that a "1" means the card is face up and a "0" means the card is face down.




<br><br>

[1] [CTAT](http://ctat.pact.cs.cmu.edu/) stands for "Cognitive Tutor Authoring Tools". It's a CMU-built system for building "Intelligent Tutoring Systems".
