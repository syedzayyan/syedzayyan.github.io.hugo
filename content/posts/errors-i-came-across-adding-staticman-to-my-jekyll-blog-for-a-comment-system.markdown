---
title:  "Errors I came across adding Staticman to my ❌Jekyll❌ Hugo Blog for a Comment System"
date: 2022-02-23 11:22:01 +0000
tags: ["tutorial"]
---

[There are way better](https://github.com/travisdowns/travisdowns.github.io) resources that teach you how to add staticman to your blog. You are better off with those ones. Now with the disclaimer out of the way, we can move on with how to deal with errors. 

## [GITHUB_READING_FILE]

What this basically means, is that staticman cannot find your staticman.yml file in your repository. Now if you are like me, an idiot, you would be thinking that this is in my local repository how do I even.... Staticman looks at your github repo if you have followed the above tutorial, and read it properly. I obviously did not. 

To fix the issue all you need to do is commit your changes to the repo to your preffered branch. With this we move onto the second error.

## [BRANCH MISMATCH]

In your staticman.yml file there will be a "branch" configuration. If you want to test out locally and you are committing to a test branch like me, you'd need to change this config to your preferred branch and the "staticman_url" in the _config.yml file.

Bottom line is read your tutorials properly and don't be like me and waste 2 days worth of your time. Well if you have found this article you are already like me I suppose. 

:) xx

## Update: **14th March 2022**

I have since switched to a Hugo blog. I couldn't get the strikthrough syntax to work, you can tell by the ugly title. If you have any ideas make a pull request, email me or  I don't know really. For setting up staticman with Hugo I followed ze [tutorial](https://dancwilliams.com/hugo-staticman-nested-replies-and-email-notifications/). This blog's code is open source anyways, urmmm you could if you like change the css :). I basically copied the commenting CSS from Dan's older blog, just changed the CSS variables to suit this blog.

There are some more errors I made along the way, like trying to code my own form. Which was a big mistake. I'd say, start with a simple enough form like the one I cited and then maybe change the code from there. I started with my Jekyll form, which was not the best of ideas. Start simple is another advice I could give.

:) xxx