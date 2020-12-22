---
layout: post
title:      "Setup Issues - and How to Move Past Them"
date:       2020-12-22 00:25:13 -0500
permalink:  setup_issues_-_and_how_to_move_past_them
---

## The (common) Bane of All Developers
 
Trhoughout my planning and development phase of mapping out my Rails App to the time I started implementing and then towards the end of finalizing my Project to share with the Flatiron Community, I like many other developers ran into several "setup issues" along the way.

Now I can say how amazing it is to have the motivation and the vigor to start coding, tinkering, revising, and implementing your code base closer and closer to what you envisioned it being, but there's that inevitable moment during any new piece of work where you hit ... a snag. A bump. An obstacle. Sometimes that barrier is a matter of moments, a small typo, a silly error, something you didn't recognize as you were implementing a new function. Than, you start to come across the not so easily traceable errors or the missing files which prevent your program from initializing the program

Here are 4 ways to troubleshoot and hopefully figure out a way around your obstacle!

**# 1 **- binding.pry is your best friend

Some coding languages (specifically but not limited to Ruby) are extremely user friendly when it comes to identifying the root cause of why something didn't work as intended! My first tool in the coding toolkit that has helped me through thick and thin is to rely on the Ruby Gem pry.


![binding.pry](https://i.imgur.com/lKkI6t1.png)


The concept is that you can 'pry' open a point in your code flow and stop time... I mean, verify that your variables and methods are accesible and reading as expected for your code to work.

To do so, navigate to your Gemfile file in your folder tree, add `gem pry` and then in your terminal, run `bundle install` to make sure the gem has properly been installed. Then drop a `binding.pry` wherever in your codebase you suspect your program faces an error and you need to do some troubleshooting to make sure all of your expected methods and variables are generating correctly. Then methodically follow your code flow and move the `binding.pry` as you go!

**# 2** - Stack Trace? Syntax Errors? Great!

Often, the program will throw an error indicating where the code came to a stop, which controller or method it can be found in, and even the line of code you should be looking into. While it might not explicitly inform you what to do the fix it, those errors can be copy/pasted, looked up and searched for to see if other Programmer (such as yourself!) have encountered and how to approach the problem. Using this in conjunction the previous suggestion, will help clarify what might be your current error

![Stack Trace](https://i.imgur.com/vUSzZxy.png)

**# 3** - Documentation and Guides

The internet is an endless mountain of information. But knowing how to search for what your looking for can be a bit tricky sometimes. Some hints, use general terms like "ruby guide omniauth" or "rails generate model" to focus your search, then tweak based on the search results if those answers are helpful to you. Even if you think you've searched to no avail, changing some of the search parameters can yield a new batch of helpful [StackOverflow.com](http://) and [Ruby API doc](https://api.rubyonrails.org/) to help you understand how a new method is supposed to be implemented.

![Ruby and Ruby](https://i.imgur.com/PdSGYvy.png)

**# 4** - Phone a Friend

But really though, getting a second pair of eyes or reaching out to someone in the Slack Community can be vital to coming up with a solution or attempting a new approach. The entire community of developers are all continuously learning and building up their knowledge not only by their own research, but also coordinating and helping others as they have been helped before them. Problem with trying to figure out OmniAuth and implement a login strategy? So have tons of others! In fact, there's several several Blog posts and how-to's to help guide new programmers to navigate their tricky setup. Once you've gotten the hang of a skill and know the pitfalls because you asked for insight or advice, the easier it is the next time you come across it. Maybe even help the next person who comes along and struggles with the same issue!


Hopefully, these are tips/strategies that you already know are effective and very useful tools to keep in your toolkit.

From small to large, errors and the problems which cause them are what allow us to become better developers. By constantly expanding our knowledge of how code should work and finding how out to effectively recognize and correct problems as they arise, you'll be quickly on your way to the next coding endeavor! 


