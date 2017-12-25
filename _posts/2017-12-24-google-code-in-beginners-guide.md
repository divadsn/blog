---
layout: post
title: "Google Code-in Beginners Guide"
date: "2017-12-24 03:50"
category: contest
image: 2017-12-24.jpg
---
This year I'm taking part in Google Code-in for the second and last time, as some of you might have already noticed that I will be 18 years old next year. But it doesn't keep me from sharing my experiences I gathered last year in this post, especially useful tips for newcomers who might want to join Google Code-in during this Christmas season. This guide is not only for Google Code-in beginners, but open-source in general.

Note: I won't go here in detail on how the contest works, for that I suggest [reading this page](https://developers.google.com/open-source/gci/how-it-works).

## 1. Registration
The entire contest is hosted by Google and takes place online from 28 November to 17 January. But before you register, you should get an overview of the [general contest rules](https://developers.google.com/open-source/gci/resources/contest-rules). Then you can proceed to the [sign up form](https://codein.withgoogle.com/student-signup/).

Keep in mind that the entire contest runs on [the dashboard](https://codein.withgoogle.com/dashboard/), especially your tasks and communication with your mentors, so creating a bookmark for faster access wouldn't be a bad idea. :wink:

### Fill out your parental consent online!
Last year I made a mistake by assuming that the online verification process will not work. That's why I decided to let my parents fill out the classic way, by printing out the parental consent and letting them to sign those papers in order to scan them back and send it onto the dashboard for verification.

And guess what? I had to redo everything as my parents have signed it wrongly, so in the end I just wasted 3 days on such a dumb thing, ugh. That's why I went with the online verification method this year and I was surprised how fast it went, my parental consent got accepted 2 hours after completing my first task, yay!

**Tl;dr: Online verification is much more faster and reliable than offline, you will thank me later.**

### Don't use fake identities
I know, some of you might be concerned about your privacy, and some of you might probably contribute anonymously under a pseudonym. But for Google Code-in it's important to use your real identity! Don't worry, you can at least decide how your name should show up in the public on the dashboard, so you can use your pseudonym. And if you don't want to receive anything from Google, then you can also use a spam account.

**Tl;dr: Use your real identity, will cause less problems for verification.**

### Find tasks to your wanted skills
I still remember looking for my first job today. In the beginning I was a bit shocked by the large number of available tasks, but then I realized that there are filter options. And then I chose a beginner's task for the beginning to familiarize myself with the organization I have "chosen". Because each organization uses different tools, such a beginner's task helped me to install and understand the use of these tools.

But then I wanted to do a normal task and started looking for tasks in my programming languages I already knew. The point behind it was that I can train my existing knowledge and learn new things. And that's how I do it this year again, sometimes I look for simple tasks and sometimes difficult ones that challenge me and force me to think more deeply about a solution. That's actually the more fun part of the contest in my opinion, you can't always expect a task being done as you thought it would be before picking it.

And yes, I do like challenging myself, just like last year. :muscle:

**Tl;dr: Search for tasks that suit your needs and knowledge and don't fear the unknown.**

## 2. Communication
### Different types of messaging methods
If you have decided not to stick to one organization then the chances that you will face this problem are very high. While you can expect most of organizations on Google Code-in to communicate via IRC, not everyone is using the same bug tracker. Some of them might use GitHub issues, some on the other side might use Phabricator. And some could even use JIRA as a bug tracking platform. Not to mention other alternatives like GitLab. :joy:

Jokes aside, you probably see what I'm trying to explain. The point is, you should _always_ check what the organization does use for communication and their guidelines on how to manage open issues. Most organizations put some notes in their task descriptions on the dashboard, so students know how to contribute.

When it comes to online chat, I think [the etiquette](https://en.wikipedia.org/wiki/Etiquette_in_technology) should be clear enough to everyone, right? :wink:

**Tl;dr: Always read the task description twice, you will see the requirements at the bottom of the description.**

### Cloud IRC vs. IRC bouncer and why it's good
You might also noticed in the meantime that all the messages which have been sent in that time are gone when closing the IRC client. And sadly, this is not a bug, it's actually how IRC works. But there are solutions on how to avoid that situation in the future: IRC bouncer ([ZNC](https://wiki.znc.in/ZNC)) or cloud IRC webclient (["The Lounge"](https://thelounge.github.io/))

#### Which is better for me?
It depends. Both options require you to have a Linux VPS in order to host it yourself. But you can also host it on a Raspberry Pi! ZNC should work on every Raspberry Pi beginning with the model B+, while "The Lounge" will only work with the Raspberry Pi 2 or higher since Node.js requires a lot of RAM.

Basically "The Lounge" is the easiest one to setup in my opinion, just download the deb package from [GitHub](https://github.com/thelounge/lounge/releases), install and launch it in the background, that's it. Now you only need to finish the installation by opening the address of your VPS in a browser of your choice and following the steps on the IRC network setup page.

But if you want to install ZNC then I recommend you [checking out their wiki](https://wiki.znc.in/ZNC), it has everything you will need to get ZNC installed on your server and configured to your own needs.

#### What are you using personally?
I am using both, "The Lounge" as my IRC client and ZNC as fallback if the client goes offline for whatever reason.

**Tl;dr: Install it if you have a Linux VPS or a Raspberry Pi (or other board), especially if you want to be 24/7.**

### Patience is very important
There is nothing more to say than a good old idiom:
<blockquote>
  Speech is silver, but silence is golden
</blockquote>

Keep in mind that your mentors are also humans who eventually leave their computers to sleep, work/school or study. Also they might be in different timezones and have different holidays than you.

**Tl;dr: Mentors have up to 36 hours time to review your submission, don't worry.**

### Try to ping only when it's really necessary
Generally it's not wrong to ask your mentor first when you are stuck with your task, but sometimes a quick search on Google could have helped you too. I rather keep pinging my mentors only in a situation when I don't understand the task description or when I am unsure about my current solution, so I can discuss with them.

**Tl;dr: Uncle Google is your best friend :wink:**

## 3. Contributions
### Issue trackers in common
When working with code you will mostly find your task details on a issue tracker like GitHub or Phabricator, but also tasks in outreach or quality assurance will be done on those as well. Usually you will find a link to their issue tracker in the task description and the sign up on those is also very easy, just make sure you use the same e-mail address as on Google Code-in during the registration, it will make things easier for your mentors.

Also you should claim your task on the issue tracker, so other contributors won't work on that unnecessarily. I already had a situation where a friend messaged me on IRC that he was already working on that issue, but he didn't know that because I haven't claimed the task. (Greetings to you, Albert221!)

**Tl;dr: Issue trackers are the main platform for communication with other contributors.**

### Setting up git properly
It's the most important tool when working with code, no matter which organization, it's used on every open-source project worldwide. Without git it would be nearly impossible to work simutanously on the same code without having to copy and paste everytime someone updated a file you have changed too.

It basically keeps a track of every change you have done, so it immediately knows which changes in files needs to be applied in order to have your local code updated with the remote repository and vice versa for other peoples changes. Also it allows maintainers to review your changes, so they can whether decide if your change will work with the other code or not and they can give you comments so you can improve your change in order to have the change accepted. And they can also easily revert your change when it was causing some trouble later.

That's why you should also setup your git properly, which means your commits will include the right author information. To do this, you need to execute the following 2-3 commands if you never done that:
```
git config --global user.name "<YOUR DISPLAYNAME>"
# Example: git config --global user.name "David Sn"

git config --global user.email "<YOUR E-MAIL ADDRESS>"
# Example: git config --global user.email "divad.nnamtdeis@gmail.com"
```

If you are required to provide your change on Gerrit:
```
git config --global gitreview.username "<YOUR GERRIT USERNAME>"
# Example: git config --global gitreview.username "Divadsn"
```

**Tl;dr: With great power comes great responsibility, that's why it's important to setup git properly.**

### Always look up commit message guidelines
The commit message plays an important role. They are the first thing other people will see of your commit. You should write your commit messages in English and in the imperative as simple as possible, as if you would instruct someone to your change.

The first line of the commit message is known as the subject, in which you describe your change in few words. Then you can describe your change in detail if it is necessary. Here is an example:
```
Fix tooltip accessibility for screen readers

By adding an additional aria-label attribute to the tooltip,
we can ensure that every tooltip will be accessible
for accessibility tools like screen readers.

Works with Echo extension, but I am not sure if there
are extensions who are using the original-title attribute.

Tested with ChromeVox on Chrome 62.0.3202.94.

Bug: T54711
Change-Id: I19500c4e8ccbdcb8288b9c2299a29b3f8a31639d
```

**Tl;dr: You commit messages should describe your changes easy and understandable for everyone, like Tl;dr.**

### Document every change for reviewers
Try to write comments to every new piece of code you have written, it will make it much more easier for your mentors to review your changes, which will also result in a faster review response time. Also it helps other contributors to understand your decisions on why you have done it in a particular way. You should also avoid commenting obvious things on the other side like why 2 plus 2 equals 4, but in situations where you have done something unusual, like casting an object to a string for example.

**Tl;dr: Commenting your code does help others in understanding your intentions.**

### Discuss every change and explain your idea
Do not hesitate to discuss with your mentors if you feel that the issue is somewhere else. Sometimes it can happen that your task has already been solved or needs to be solved in a different way. If you are sure, then explain your point of view on how the task should be solved and give an example on how to solve it in a different way so that the reported problem doesn't come up. And as always, keep calm and wait until your mentor has figured out.

**Tl;dr: Feel free to discuss your changes with others, maybe you can convince them. :wink:**

## 4. Final words
No matter how many tasks you have solved, the idea of Google Code-in is to introduce you to the amazing world of open-source and you should have fun doing your work for open-source. At the end you should be proud of yourself, that you have believed in yourself and learned so many new things. And I know that some of you are probably very keen on the grand prize, but I can only tell you one thing: **quality counts above all, not quantity.**

Even when you have not won a prize, you are still a winner and your prize is the knowledge you gained during the contest. And yes, I do look like someone who has already gained enough of knowledge, but I have also gained new knowledge last year and even this year, you can never learn enough.

I'm happy to see how new students are interested in open-source, since my classmates are completely uninterested in computer science, even though they are in a class with computer science. :unamused:

Merry Christmas and wish you best luck! :christmas_tree:

_This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/)._
