---
layout: post
title:      "My First CLI: Becoming a more effective 'Learn'er!"
date:       2019-03-17 23:57:54 -0400
permalink:  my_first_cli_becoming_a_more_effective_learner
---


I'm thankful for what an amazing learning experience this first project assessment turned out to be.

For both its ups and downs, its been great to finally be able to combine my accumulated knowledge between GitHub commits, refactoring effective code, and leaning on our coding resources.

I've learned some great things to do and not to do that I would like to share briefly so others can benefit from my experiences:

Do's:
1. Plan ahead.
2. Enjoy tinkering!
3. Push your boundaries.

Don'ts:
1. Don't be afraid to seek out answers
2. Believe there's only way to accomplish your goal
3. Let yourself get discouraged

In programming, much like any other activty in life, we allow ourselves to use our time to see if it's worth doing. Is it worth taking the extra time out of our lives to start a programming course? Is it worth taking the extra few minutes to see what happens if I remove a code dependency or sift through Nokogiri for that specific attribute? Is it worth programming and reprogramming a method call so it's easier for someone completely new to jump in and start manipulating it?

**The answer hands down: Yes!
**

![](https://i.imgur.com/pzNYJds.png)

*Just as the bunny has realized, time isn't always on our side.*

Time is precious you might say?** Yes - Yes it is.**

So why bother with all of this extra effort, you might think to yourself?

Well, the extra time and effort you spend today can pay dividends and exponential returns and benefits down the line. All of that extra coding to tinker with cleaning up your code and figuring out how an issue kept cropping up and how to prevent it from reoccuring? That is valuable time spent guarding your future!~

While coding my first CLI (Command Line Interface) program for this Learn.co project assessment, I ran into a very painful learning experiences I'm glad to have to run into, but never wavered against.

## "Code Dependencies & Version Control" 
After making strides with getting the program working with hard-coded data and getting ready to begin using live data from Teeturtle's website, I ran into a roadblock. For some reason, I could no longer run my program as this "Compatible version" error could not be resolved by Bundler.

![](https://i.imgur.com/PbjUtkA.png)

*What is going on here?*

It took me a full hour or so of reviewing my code, looking through my object classes and previous Github commit messages for any clue as to what I may have changed that caused my code to come to a halt. I knew based on reviewing the error message that it had to do with code dependencies and the version (Ruby's very friendly with that, it tells you exactly what you're looking for.) I tried searching online through Google, reddit posts, ruby-docs with queries I thought would help. Things like "gem install" or "./bin/setup help." After little progress, I reached out to my Technical Coach for assistance.

After reviewing my code, she recommended and verified that the issue was 
> `spec.add_development_dependency "bundler", "~> 1.17"` 

to   
> `spec.add_development_dependency "bundler"`

and rerunning 'bundle install'. In no time at all, I was able to clear past the obstacle and continue pushing on with my programming! A sigh of relief and satisfaction on two counts:

1. I had known what the issue was
2. I had reached out for assistance when it was needed

Knowing **when to look for answers on your own** and **when to call in backup** is crucial for any learning experience. I made sure that before seeking out help from experienced veterans such as my Technical Coach or my programming cohort, I took a look for what might be the cause of the issue myself first. By doing so, I ensured that I knew the probable cause of the issue, what possible options I could use to resolve the issue, and what questions I should be asking if I needed to revisit the issue.

I knew that based on the error that it in fact was something to do with the "version", something outside of my own programming and concentrated with the code environment and requirements I was requesting Ruby to have, as well as something relatively simple I could adjust once I found it.

By breaking down the issue before I reached out for help, I was better prepared to request and receive assistance once I had another pair of eyes look into the issue. Reinforcing the learning process by recognizing issues, coming up with possible solutions, and creating effective requests for help has made me a better learner and a stronger programmer.

Once I was able to push forward with coding, I was extremely pleased to be able to complete the assessment and bring live WEB data to my simple yet effective CLI program. I hope that this helps others learn to embrace the obstacles we come across and be effective learners in the programs to come.

![](https://i.imgur.com/P3vzy2z.png)


