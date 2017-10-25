---
layout: post
title: "My Story about Lawnchair Launcher"
date: "2017-10-25 19:44"
category: open-source
image: 2017-10-25.jpg
---
You may have probably already heard about ["Lawnchair"](https://lawnchair.info) from several Android news sites or blog posts. It's an open-source launcher based on [Launcher3](https://android.googlesource.com/platform/packages/apps/Launcher3) which brings Google Now and dozens of settings to help personalize your home screen on every device. You also might have read about [Till Kottmann](https://deletescape.ch), the creator behind the launcher, but not about the rest of the team behind Lawnchair Launcher.

## Let the story begin...
The story started back in June 2017 when a friend hit me up with a link to a new launcher which he was saying:  
<blockquote>
  It is the perfect launcher! 1:1 Pixel Launcher, but with customization options <br />
  You have to try it, you will surely like it! :wink:
</blockquote>

And yes, indeed, I've begun to love it. For me the switch wasn't a huge deal tho, as I've already used the [Pixel Launcher](https://play.google.com/store/apps/details?id=com.google.android.apps.nexuslauncher) from Google before. But despite all of this, I started to love the launcher, especially for additional features like the support of icon packs or blur for example.

Then after using it for a while I noticed some issues and missing features (like the weather in the Google pill), so I've submitted them as a request to [Till Kottmann](https://deletescape.ch), the main developer of Lawnchair. He immediately replied to my request and promised me to add them as soon as possible. Two weeks later, he released [build v1.0.1063](https://github.com/Deletescape-Media/Lawnchair/releases/tag/1.0.1063) with a ton of new features, including the aforementioned Google pill weather widget.

## The moment of attention
It was in August 2017, when Till wanted to release Lawnchair to the Google Play Store, but realized that [someone have stolen his listing](https://t.me/lawnchairchannel/175) with the same package name. When he knew he would need help from Google, he contacted me immediately to explain the situation to me, as he knew that I could help him in getting contact to Google and solving the legal issue. I was abroad at this time for 2 weeks school of English, but it was not a problem for me to call people in different offices at Google around to world in order to solve his issue.

### So, did you have succeed? :thinking:
Sadly, after many calls, a friend explained to me that it's impossible to solve that over the phone or by e-mail and that the best chance would be to go to the Google office in Zurich, as Till is from Switzerland. But unfortunately Till has not yet found time to go to Zurich, so they had to find another solution...

## My part in the Lawnchair team
After my "success" in helping them with their legal issue, I started contributing to Lawnchair on GitHub by answering to open issues and completing the wiki with new FAQ entries, like giving answer to [why the weather widget is showing different information than Google Now](https://github.com/Deletescape-Media/Lawnchair/wiki/FAQ/474329417b04ddbcaa0e8d9496b3f2c742685d58). I also [added an issue template](https://github.com/Deletescape-Media/Lawnchair/commit/7df7bd15eafc86b57ac2f77e578bd52b55461383#diff-1a1c3dd142f76a5fad803a0c52839881) to help new people in submitting their bug reports to the Lawnchair team. With the time tho I was more interested in actual contributions to the code itself, so I started reviewing the code and to fix reported bugs.

This was the moment I started to became finally a part of the Lawnchair team. :heart:  
Here is a sample of the contributions I did in the meanwhile:

 - [Add support for animated clock icon on MIUI](https://github.com/Deletescape-Media/Lawnchair/pull/715)
 - [Add option in preferences to animate alternative clock apps](https://github.com/Deletescape-Media/Lawnchair/pull/756)
 - [Unicode insensitive comparison in All Apps search](https://github.com/Deletescape-Media/Lawnchair/pull/813)
 - [Remove whitespace from query when searching](https://github.com/Deletescape-Media/Lawnchair/pull/819)
 - [Fix derped regex](https://github.com/Deletescape-Media/Lawnchair/commit/580ffcbccd6056da9b9bf27f2a0235dd4713f116)

I would like to thank here [Rawi666](https://github.com/Rawi666) for his contributions and the help he offered, it was nice to talk with you!

## A new solution had to be found
It was still a hot topic since August 2017 and people kept spamming those requests on GitHub and Telegram along, so we had to overthink our current versioning system.

After a long discussion we came up with the idea to slowly move our deployment to the Google Play Store, while also changing the package name, so our old listing will be available again. No sooner said than done, I began to [massively change the necessary files](https://github.com/Deletescape-Media/Lawnchair/pull/835) and prepare my [private S3 storage for new uploads](https://storage.codebucket.de/) so we could release our first alpha version to the Play Store as soon as possible.

On October the 14th we were [happy to celebrate our first alpha version](https://twitter.com/lawnchairapp/status/919293171330310144) on the Google Play Store. We already hit 50.000 downloads with around 30.000 active users, and the trend is rising. :tada:

## So, what's next?
It doesn't feel like it's the end, but more like the beginning of a new chapter. We have still a lot of work to do before we release the final version. But since most of the team members are back in school or work, the final release will take some time. And as we promised, Lawnchair is and remains free of charge, no pro version or additional in-app purchase required! If you like our work, then consider buying the [donut donation](https://play.google.com/store/apps/details?id=ch.deletescape.donut) app, it helps us among other things with the maintenance costs for the hosting for example.

In the end, I would like to thank [Till Kottmann](https://deletescape.ch) and [Christopher Kardas](https://christopherkardas.me) for their support, you guys gave me actually motivation to do something. Also a big thanks goes to the rest of the team, you all are amazing! :hugs:
