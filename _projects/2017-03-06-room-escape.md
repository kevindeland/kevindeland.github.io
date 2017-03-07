---
layout: project
title: "Educational Room Escape"
date: 2017-1-20 19:17:00 -0400
description: "A room escape with educational content"
categories: education fun
---

If you've ever done a room escape before, you have been exposed to puzzles, pattern matching, cooperation, etc etc. I went to an SXSWedu event hosted by (Business Innovation Factory)[http://www.businessinnovationfactory.com/] (which is a super cool group of people... they recently worked *with* high school students to help design their own high school). First  we did a room escape (or puzzle room) in Austin called (The Escape Game)[http://theescapegameaustin.com/]. Our group did the hardest room (Prison Break) and got out with 15 minutes left to go! We then debriefed and talked about the educational aspects of our experiment. 
- content: what is the educational content you had to draw from to solve the room? Most rooms rely on knowledge that has a very common public denominator, like puzzles, chess pieces, playing cards, letters, colors, tic tac toe boards, mazes, etc.
- teamwork: communicating and collaboring with teammates. Sharing information, etc.
- metacognitve: knowing when to ask for help, when you're stuck on something, etc.

We then worked in groups to do some prototyping. My classmate and I really wanted to integrate educational content into the room escape, we brainstormed all sorts of crazy ideas, including:
- Punnett Squares
- Chemical Reactions
- Line Graphs
- Pendulums, Springs, and Pulleys

Here are some of the things I built: 

### Algebra and the Formula of a A Line

This puzzle tests the solver's knowledge of line equations. They must examine a cartesian plot of lines, and plug into equations numbers which are then used to open a lock. 

Here's the cartesian plot I made. Each sticky note represents 1x1 unit. The lines are made with pipe colors (red, green, blue, yellow).
![]({{ site.baseurl }}/assets/sxsw/room/graph2.jpg)

These are the clues the users had at their disposal. The color is a bit off here, but one formula is green, the other is blue. The green formula corresponds with the green line, and the blue corresponds with the blue (the red and yellow lines were red herrings!).
![]({{ site.baseurl }}/assets/sxsw/room/clues2.jpg)
![]({{ site.baseurl }}/assets/sxsw/room/formulas.png)


To unlock this lock, they had to determine the slopes and y-intercepts of the lines, which then corresponded to the numbers on this lock. Opening the lock leads them to the next clue!
![]({{ site.baseurl }}/assets/sxsw/room/lock1.jpg)

Here are some educators working to solve it! 
![]({{ site.baseurl }}/assets/sxsw/room/graph_solving2.jpg)

#### Struggles and Misconceptions
There were a few places where users struggled:
- Not everyone made the immediate connection that the formula and the line matched via color. Some users tried to solve the lock using the red line instead of the blue. That is, my red herring was effective! 
- Once the users got the 4 numbers, it was difficult for them to put the numbers in the correct order on the lock. I thought there would be only two possible orders they would consider, based on the way the clues were given (blue then green, or green then blue), but one group seemed to try every possible combination.
- Understanding how the numbers fit into each equation. That is, understanding the denominator, or understanding how a negative number would work on the lock.


### DNA Prototype
Here's a prototype I made after the line graph. This one involves matching sequences of DNA. Theoretically, each 3-phosphate sequence (enough to make one protein! or... whatever that term is... I forget), would be associated with a letter. The users would have to sort through the 3-phosphate sequences in a big pile and match them to the loose DNA strand. Then the ordering of the letters would unlock a letter-combination lock.
![]({{ site.baseurl }}/assets/sxsw/room/dna3.jpg)

The DNA strand is made of pipe cleaners. 
![]({{ site.baseurl }}/assets/sxsw/room/dna2.jpg)

Here's what a solved sequence might look like (not shown: the lock-opening step).
![]({{ site.baseurl }}/assets/sxsw/room/dna1.jpg)


### Next Steps
Overall, I think that Escape Rooms can be a fun way to incorporate lessons about communication and collaboration. However, I am skeptical about the educational value of inserting these more advanced lessons into escape rooms. I think they have their place, but I am not sure if it would be a valuable classroom activity if the teacher were looking to use it as a vessel to teach content. However, I think there is definitely a place for these, which I cannot fully and properly articulate at the moment because I just got extremely hungry and want to eat some of the amazing tacos that Austin has to offer. But I would like to mimic the behavior of an Escape Room within a Cognitve Tutor, because I think immediate and directed feedback can be extremely beneficial to help puzzle-solvers through tasks that are longer, more complex, and more arduous... so that they know whether or not they are going down the right path.