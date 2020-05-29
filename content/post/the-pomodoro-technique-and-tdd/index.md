---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "The Pomodoro Technique and TDD"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2015-12-06T22:21:10-04:00
lastmod: 2015-12-06T22:21:10-04:00
featured: false
draft: false
featured: true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: true

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
![Tomato Timer](tomato-timer-small.jpg)
If you are a programmer you know time management issues are an inherent part of the job. Programming requires creativity. However, to tap into this creativity most programmers strive for a state of flow to help them get 'in the zone'. This feels like the most productive time. Inconveniently, a good programmer is often involved in many other tasks: <span style="font-size: 12pt;">
</span>
<ul>
 	<li>Meetings</li>
 	<li>Support Issues</li>
 	<li>Pre-sales</li>
 	<li>Interviews</li>
 	<li>Timekeeping</li>
 	<li>More Meetings</li>
</ul>
These tasks are as important as the actual programming, but often seem to get in the way of what programmers love to do – write code. It's a problem I've struggled with over the years. There are two techniques that can help when done in tandem, <a href="http://pomodorotechnique.com/">The Pomodoro Technique</a>, and <a href="http://en.wikipedia.org/wiki/Test-driven_development">Test Driven Development (TDD)</a> using Baby Steps. Together, these techniques give you the ability to get real coding done, even with frequent interruptions throughout your day.
<h2>The Pomodoro Technique.</h2>
The Pomodoro Technique is a time management technique that is especially useful for busy people. Here is a breakdown:
<ul>
 	<li>Do 25 minutes of focused work. This time period is called a 'Pomodoro', named after the kitchen timer shaped like a tomato.</li>
 	<li>Take a 5 minute break.</li>
 	<li>Repeat</li>
 	<li>After every 4 Pomodoros – take a longer break.</li>
</ul>
Each Pomodoro is intended to be performed without interruption. If anyone were to interrupt you during this time, you would simply ask if you could get back to them in a few minutes, at the end of the Pomodoro period. If it were someone from your team causing the interruption, you could simply say you're in a Pomodoro and they would know that you'll get back to them upon completion. This requires some education across your team. To be successful with the Pomodoro technique you need to be able to select a task to be done, and feel like you can reach a logical breaking point at the end of 25 minutes.
<h2>TDD and Baby Steps</h2>
Time-boxing a coding session into 25 minutes can be difficult. This is where using Test Driven Development can help you get real code written in a short length of time. In short, TDD follows a very simple cycle known as the 'Red-Green-Refactor' cycle. After deciding on what test you would like to write do the following:
<ul>
 	<li>Write a failing test (Red)</li>
 	<li>Write the implementation to make that test pass (Green)</li>
 	<li>Refactor the code, for simplicity (Refactor)</li>
 	<li>Repeat</li>
</ul>
I first experienced the practice of doing TDD in Baby Steps when I was at a <a href="http://coderetreat.org/">Code Retreat</a> in Floyd, Virginia in 2012. It was facilitated by <a href="http://articles.coreyhaines.com/">Corey Haines</a> and I was doing a pairing session with <a href="https://twitter.com/jthurne">Jim Hurne</a>. The challenge was to write a test and its implementation within two minutes. If you didn't complete the test and its implementation you had to delete your code and try again. I was amazed at how difficult it was to get this done. I was also amazed to see how fast Jim was on the keyboard, knowing all the important keyboard shortcuts that allowed him to code efficiently. I realized I had some practice to do. I also realized the value of doing a complete piece of code in a very small amount of time. Soon, I found that by following TDD principles, and writing <a href="http://www.cleancoders.com">Clean Code</a> with small functions, I was able to write good, production worthy, tested code in minutes. More than that, I felt comfortable checking in my code very frequently, within minutes instead of hours or days.
<h2>Pomodoros and TDD Together</h2>
The Pomodoro Technique and Test Driven Development pair together well for programming efficiency. Test Driven Development using Baby Steps allows a programmer to code small chunks of releasable code within a short time period. The Pomodoro Technique allows for frequent, but structured, interruptions throughout your day. When you learn to plan your coding effort in terms of Pomodoros, you can maintain your focus during each Pomodoro. You create the illusion of successful multi-tasking, when in reality you are focusing on only one task at a time.
<h2>For More Information</h2>
<ul>
 	<li>Pomodoro Technique: <a href="http://pomodorotechnique.com/">http://pomodorotechnique.com/</a></li>
 	<li>Test Driven Development: <a href="http://en.wikipedia.org/wiki/Test-driven_development\">http://en.wikipedia.org/wiki/Test-driven_development\</a></li>
 	<li>Code Retreat: <a href="http://coderetreat.org/">http://coderetreat.org/</a></li>
 	<li>
<div>Clean Code: <a href="http://www.cleancoders.com">http://www.cleancoders.com</a></div>
&nbsp;</li>
</ul>
&nbsp;
