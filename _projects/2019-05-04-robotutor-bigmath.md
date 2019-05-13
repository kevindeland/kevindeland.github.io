---
layout: project
title: "RoboTutor: Base-Ten Blocks from Paper to Screen"
date: 2019-05-04 12:00:00 -0400
description: "Digitally implementing a research-backed way to teach base-ten."
categories: xprize education math research
permalink: /rt-baseten
thumb: rt-baseten_thumb.jpg
---

I grew up with base-ten block manipulatives. Some of my earliest math memories involve using these in Kindergarten.

![https://www.amazon.com/Teacher-Created-Resources-Foam-20617/dp/B007P23HJC]({{ site.baseurl }}/assets/base_ten_blocks.jpg)

<br>

When working on a problem like *building an app that can teach a child without a teacher*, as is the goal of the [Global Learning XPrize](https://www.xprize.org/prizes/global-learning), it will be necessary to get as many of the real world benefits of working with tangibles into the tablet. While it won't be quite the same, it's worth trying.

When designing EdTech for tablets, we can take advantage of what we already know about teaching kids using paper, and bring some of those lessons into the digital world. So how do we do this?

<br>
### Built on Evidence
[Fuson and Briars](https://www.jstor.org/stable/pdf/749373.pdf?casa_token=_H5NrKuSJiEAAAAA:BajqVgFES71JNfbP9JtOI6bXLLk5wL4qy3WBOGXK3t7dCDCodDCcuRshmxj2I-1xLM-7jIShQSxEWRhM4H2r7hLQg7WyidsBEVVqA6vjbNt1zMHBS2M) detail a way to use base-ten blocks to teach First- and Second-Grade Place-Value and Multi-digit Addition and Subtraction. I won't go into too many details of the study, but they tested over a hundred second-grade classrooms in the Pittsburgh Public School System. The students showed significant learning gains in Addition, Subtraction, and Place-Value tests.


![]({{ site.baseurl }}/assets/base_ten_fuson.png)

`The structure Fuson and Briars used.`

<br><br>
### Converting into Digital form
To convert this to a digital version for use in RoboTutor, we followed these very high-level steps:
1. Read to understand the step-by-step process used in Fuson and Briars.
2. Choose an example problem (e.g. 17 + 25) and work through each individual step, while drawing a wireframe (lo-fi prototype) of each step (see image below).
3. Decide how to represent the design (e.g. audio, movement, indicating).
4. Use Google Slides to make a medium-fidelity prototype. We used these as an artifact for discussion. We worked with [Emily Keebler](https://www.cmu.edu/pier/fellows-and-alumni/keebler.html), a PhD studying how kids learn math, to further refine the design. Emily helped us make design decisions like what the prompts should say and the order of the interactions.
5. Finally, the code was put into RoboTutor! Once it was finished, we continued user testing within house, and at our beta-testing site in [Bagamoyo](https://en.wikipedia.org/wiki/Bagamoyo).

<br><br>

![]({{ site.baseurl }}/assets/sub_400m399_2.jpg)

`A step-by-step wireframe of how a student would work through 400 minus 399.
Note how we have state changes in green and audio in pink.`

<br><br>

![]({{ site.baseurl }}/assets/bigmath_med_res_1.png)

`A medium-fidelity prototype. We used this to iterate on the step orderings, the wording of the prompts, the interactions, etc.`

<br><br>

![]({{ site.baseurl }}/assets/bigmath_trimmed.gif)

`The high-fi version, including animation, writing boxes, and RoboFinger to indicate what to do.`


<br><br>
### Future Improvements
There are many possible exercises that could be used to improve understanding:
- **Scaffolding and fading:** in this current iteration, students must work through an entire problem by themselves, with slight hints here and there. However, borrowing and carrying can be confusing. By *scaffolding* complex procedures, we perform certain steps in the procedure for the students and let them start small. Then we can slowly let the students perform more steps.
- **Fluency**: We already use Bubble Pop to build fluency for multiple domain areas. However, we do not have any fluency-building exercises that map multi-digit numbers to their base-ten representation (or vice-versa). That could be an easy next step to help students build fluency.
- **CTAT:** A longer-term goal of mine is to integrate [CTAT](http://ctat.pact.cs.cmu.edu/) on the backend of the tutor. I'd like to take the front-end interactions that are unique to RoboTutor, like character recognition, speech recognition, playing audio, and indicating with RoboFinger, and incorporate them into CTAT's behavior graphs.
