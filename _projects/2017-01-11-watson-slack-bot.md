---
layout: project
title: "Watson-Powered Slackbot"
date: 2016-03-14 12:00:00 -0400
description: "A forum patrolling slackbot enhanced by IBM Watson Tone Analyzer API."
categories: Watson slack
thumb: watson_bot_thumb.png
---

1. Periodically scrapes messages from IBM Connections Forum.
2. Uses redis caching to determine if message has already been seen.
3. Runs messages through [IBM Watson Tone Analyzer](https://www.ibm.com/watson/developercloud/tone-analyzer.html) to determine tone of message.
4. Posts to slack with corresponding emoji

This was a fun little side project I developed for the CIO Cloud team at IBM. I loved experimenting with the Watson services to see what they could do with text. The Tone Analyzer API looks for key words to determine the tone of the message. As you may see below, sometimes it was not entirely clear why API determined a message to have a partciular tone.  

![]({{ site.baseurl }}/assets/bluemix_emoji_1.png)
