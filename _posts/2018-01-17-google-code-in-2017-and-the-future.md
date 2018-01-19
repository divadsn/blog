---
layout: post
title: "Google Code-in 2017 and the Future"
date: "2018-01-17 17:37"
category: contest
image: 2018-01-17.jpg
---
Today I am writing my final task for Google Code-in 2017, which is the blog post you are currently going to read on. Some of you may also know that last year I also participated in Google Code-in 2016 (which you can [read about here](https://www.codebucket.de/blog/contest/2017/01/05/google-code-in-2016.html)) and that this time it was my very last participation. Now after I've finished writing this blog post, my mentors will review it and then they will pick the finalists and Grand Prize Winners in the next days.

But does it mean that I will stop contributing to Wikimedia? **Or to open-source?**

## Let's start off from the beginning
In the last year's post I said that I will definitely participate in the next Google Code-in. Unfortunately, the situation at my school got out of my control and things went badly. This also meant that my parents weren't so happy about the whole situation which was caused by my participation. I still can remember them telling me that they won't sign any parental consent if I don't get the situation at school until then on control.

But I didn't gave up, because after all everything is possible, no matter how challenging it is. So I went away from any kind of open-source contributions in March and started to make up all the bad grades to get the situation under control until the end of the school year. And guess what? I did it, because I not only wanted to take part again in open-source contributions and Google Code-in 2017, but I also wanted to show everyone that I will make it to the next class, regardless of what I am doing beside the school life. It also teached me a lot when it comes to organizing your life, which may be also useful a lot when programming on a large project!

![My activity on GitHub over the past year](https://i.imgur.com/H6ZlXzC.png){: class="image fit" }  
_As you can see, my GitHub activity was close to none between March and July_

Then on 20th October someone at school asked me if I gonna be participating in Google Code-in again and that was the moment I woke up, as I was then trying to keep my grades good enough at school so my parents would let me participate in the contest. So I started to look up on which organizations are taking part in Google Code-in 2017 and after some time I made the final decision: **[Wikimedia](https://www.wikimedia.org/)**

### But why Wikimedia again and not another organization? :thinking:
This has many reasons, one of which is the community I liked from last year. It's very lovely over there, there are plenty volunteers who were working daily on various Wikimedia projects, like MediaWiki or the Wikipedia app for example. They put every free time and effort into endless CRs to improve services everyone of us uses regularly on the Internet and they do it all for free. Without volunteers like them we couldn't have the platform we access the knowledge to our research purposes and share it with others. For me working with them on tasks they've mentored makes it all kinda special, as I am using Wikipedia myself regularly and it always served me well.

In the end it is this special atmosphere that you could feel on the **#wikimedia-dev** IRC channel, where people have always been helpful and helped you on every question or problem you were stuck on.

## So how was the contest?
To be honest, beyond all the good atmosphere and lovely community on IRC, the last 50 days have been very exhausting for me. The biggest problem for me was mostly the time difference between mine and the mentor's timezone, which resulted in sleepless nights and a broken sleep pattern. On some days I couldn't even talk normally because I was overtired. It also had an effect on the performance and quality of my patches, so I had repeatedly overlooked something while sending a task or misunderstood it completely. But fortunately my mentors had an understanding for this and I quickly made follow-up patches to add missing things.

This time I wanted to focus more on keeping up with the community by talking with others on IRC and helping them on Phabricator. I quickly noticed that there is no dedicated channel for smalltalks, which also [got attention by **Albert221** and **andre__**](https://phabricator.wikimedia.org/T181738#3800489). So I created a group on Telegram ([@wikimediagci](https://t.me/wikimediagci)) where we could spam and talk about anything we want without any public logging. You can still join us if you want, we're still active there and you can ask us anything about Wikimedia or Google Code-in.

<blockquote>
  "Open-source never sleeps" ~ Albert221, on #wikimedia-dev, 2k17
</blockquote>

Having that quote in mind I completed **32 tasks (including this one)** and the majority of them were from Code and Research/Documentation category. Here's a summary of some of the bigger tasks I've done:

 - Kiwix mobile app on Android: Implement a SwipeRefershLayout to improve our UI<br />
   <https://github.com/kiwix/kiwix-android/pull/297>
 - Create a Phabricator backend for python-social-auth<br />
   <https://github.com/python-social-auth/social-core/pull/169>
 - Fix Mobile infobox styles to work well with multiple column infobox rows<br />
   <https://phabricator.wikimedia.org/T168716>
 - MediaWiki "Echo" extension: Help tooltip in preferences should be accessible<br />
   <https://phabricator.wikimedia.org/T54711>
 - Support Wordmark in Internet Explorer 8 in MediaWiki's MinervaNeue skin (advanced task)<br />
   <https://phabricator.wikimedia.org/T166684>
 - Screenshot Commons Android app in Polish pl-PL/German de-DE<br />
   <https://github.com/commons-app/apps-android-commons/issues/960>
 - MediaWiki's Timeline extension error messages should not use the deprecated HTML tag &lt;tt&gt;<br />
   <https://phabricator.wikimedia.org/T182968>
 - Add tabindex to MediaWiki's Special:Upload page<br />
   <https://phabricator.wikimedia.org/T25238>
 - Score extension: Generalize wording of audio formats in the code<br />
   <https://phabricator.wikimedia.org/T183753>
 - Find alternatives to TiMidity++ and compare performance<br />
   <https://phabricator.wikimedia.org/T181897>
 - Make scores output MP3 files<br />
   <https://phabricator.wikimedia.org/T181875>
 - Replace assertRaises with assertRaisesRegex in Pywikibot<br />
   <https://phabricator.wikimedia.org/T154281>

I also tried not to select repetitive tasks like last year because they were not requiring much interaction with the mentors, which was not my intention as I wanted to **learn new things** by talking with different mentors.

## Final words
I would like to thank everyone from Wikimedia who was involved in Google Code-in, to AKlapper ([Andre Klapper](https://www.mediawiki.org/wiki/User:AKlapper_(WMF))), FlorianSW ([Florian Schmidt](https://www.mediawiki.org/wiki/User:Florianschmidtwelzow)), Jayvdb ([John Vandenberg](https://www.mediawiki.org/wiki/User:John_Vandenberg)), Reedy ([Sam Reed](https://www.mediawiki.org/wiki/User:Reedy)) and SSethi ([Srishti Sethi](https://www.mediawiki.org/wiki/User:SSethi_(WMF))) for organizing all tasks and the participation in GCI, it was a good time with you all again!

Also I want to thank **andre__, Ebe123, bawolff, d3r1ck, FlorianSW, framawiki, jayvdb, jdlrobson, Legoktm, Kelson, mhutti1, MtDu, Niharika, Nikerabbit, tonythomas, Xqt, Zppix** in alphabetical order for their effort in mentoring me, answering my questions and solving my problems I had struggled when writing code through all those different tasks. I learned so many new things from everyone of you, you are the real heroes of Wikimedia and you do what you are pasionate about, which is contributing to open-source. I will really miss the times with you on IRC at **#wikimedia-dev**!

And thanks to some fellow students, to **Albert221** (from Poland), **Phantom42** (from Ukraine) and **refeed** (from Indonesia), it was a fun time joking around with you or helping each other on IRC, I hope to see you again soon! :hugs:

Lastly I also want to thank a lot my IT teacher, **Andrzej Dyrek**, for bringing Google Code-in to my attention and convincing my parents to let me take part last year. Also for telling my teachers that they shouldn't expect me being prepared for classes. I'm very grateful for what he did for me during the contest.

And of course a big thanks to my parents (and my dog) for supporting me everytime, motivating me in bad days and allowing me to take part in Google Code-in 2016 and 2017! :heart:

### And what about the future?
Now you may say that I will stop contributing to Wikimedia and you might be true. In fact I still have some tasks on my todo list which I want to complete in all peace. I will also be around on IRC and Gerrit when someone needs help understanding a change I did or when some change is related to mine in a CR. But aside of Wikimedia, I have also other open-source projects to work on.

![What's up with the Lawnchair development?](https://i.imgur.com/CcTUQ27.png){: class="image fit" }  
_Everyone from the Lawnchair team is busy with other stuff, including me._

Many projects like [Lawnchair Launcher](https://lawnchair.info) have been paused during Google Code-in and people are already asking when a next update will be released, so I want to get those projects back alive. Apart from that, I will continue contributing to MediaWiki and Kiwix whenever I find time and bugs to fix!

That's all for now, Google Code-in 2017 is now over and I hope some of my readers will take part next time!

You can read my previous blog posts about Google Code-in:
 - [Google Code-in Beginners Guide](https://www.codebucket.de/blog/contest/2017/12/24/google-code-in-beginners-guide.html)
 - [Google Code-in 2016](https://www.codebucket.de/blog/contest/2017/01/05/google-code-in-2016.html)

*This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).*
