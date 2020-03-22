---
layout: post
title: Few more thoughts from The Pragmatic Programmer
---

Continuing on my previous post, I'm going to try to explore more of my thoughts from reading <a href="https://www.amazon.in/Pragmatic-Programmer-journey-mastery-Anniversary-ebook/dp/B07VRS84D1/ref=asc_df_B07VRS84D1/">The Pragmatic Programmer</a> by David Thomas and Andrew Hunt.<br>

The next few chapters go through various aspects of a software engineer's job and some interesting suggestions that help improve the quality of our work. I've elaborated on a few here:

<h3>ETC or Easier To Change</h3>
Almost all of us have heard about the most important principle of software design, DRY or Don't Repeat Yourself. There's another similar principle that all software engineers need to know and that's ETC. Most of us already know this, but, we just don't seem to use it all that much.<br>
All software has to be easy to change. This intrinsically has a few other principles incorporated into it like:
1. <b>Don't Repeat Yourself</b> - If you have similar/same code in many places, you're probably going to find it harder to change every place the code is being used.
2. <b>Decoupling</b> - Keeping your code decoupled. This takes you a long way. Any change to any part of the system doesn't affect the rest of the system. That means easier to change.

> Good design is easier to change than bad design.

<h3>Tracer bullets</h3>
Imagine being a gunman firing at a target in the dark. You're not sure if you're hitting the target or missing them. The solution? Tracer bullets! Tracer bullets are bullets used with actual ammunition. They leave a pyrotechnic trail when they are fired. This way, the gunman knows where he is firing.<br>
It's a similar situation with the software we build. When you're not sure what the result is supposed to be, build a prototype. Something that touches all modules of the final system. This will help us get feedback from the stakeholders interactively and improve on the system step by step.

<h3>Take time setting up your workspace</h3>
This is something that hit me where it means a lot. I had been doing a lot of things in my day-to-day life wrong. Set up your workspace in such a way that it keeps you productive. Automate everything you do daily. The 15-20 minutes that you spend doing this will save you hours in the following months.<br>
I never took the time to set up my command prompt. Everytime, I wanted to check which branch I was working on, I typed `git branch`. I took minutes to get my project to compile and run. One day, a senior colleague of mine was sharing his screen with me and damn! His terminal always displayed the branch he was on and he had written a script to compile and run the project.<br>
Many such things will improve your productivity. Find them and use them!

<h3>Rubber duckling</h3>
Rubber duckling is a debugging strategy. Before I go into this, I want to mention here that there are many more strategies in the book. This is one that seemed the most accurate to me.<br>
The best way to debug is to explain your program to someone. Talk about what the program is supposed to do and how it's failing. It doesn't matter even if the other person isn't a programmer. While you go about explaining your issue to someone, the "a ah!" moment comes.<br>
Now, I'm not just saying this because it's in the book. This is something that has happened to me at work. While I was in the middle of asking my elaborate problem, the solution hit me. It has happened multiple times over the last few months.<br>
Given that many of us are working from home, you may have experienced it too. While you're typing your problem on slack in hopes of getting a solution from your co-worker, your brain just hits you! Yep, that's what is the rubber duckling.<br><br>

Why the name? The authors ran into someone who was achieving this with a rubber duckling. He carried around a rubber duckling he kept on his monitor while he coded. Hence, the name.

> Explain your bug to someone and fix it yourself

That's it for this post. Few more to come.
