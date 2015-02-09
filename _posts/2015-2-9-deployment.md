---
layout: post
title: Deployment
---

I wanted to read up on the basics of how teams deploy products. While at GA, we were able to work on a group project using the Agile methodology and scrum tactics but because we worked so closely together, merging branches and getting our app to production was fairly easy. 

The following is a very basic primer on how larger teams **might** operate. Here are the basics for a good deployment workflow:

1. Developers work on bugs and features in separate branches. Really minor updates can be committed directly to the stable *development branch* (AKA as the *master branch* in git).

2. Once features are implemented, they are merged into the staging branch and deployed to the *Staging environment* for QA and testing.

3. After testing is complete, feature branches are merged into the development branch.

4. On the release date, the development branch is merged into production and then deployed to the *Production environment*.

Here is a diagram of the basic process:
![Deployment Diagram](http://blogs.msdn.com/blogfiles/pblog/WindowsLiveWriter/StudentprojectExpressSettinguptheenviron_1424A/sandboxes_3.gif)


