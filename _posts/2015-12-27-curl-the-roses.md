---
layout: post
title: CURL: A Reminder to Look Stuff Up
---

Summary: Stop and smell the coding roses.

The full post title should really read: **CURL: A Reminder to Look Stuff Up (Even if It's Not Directly Pertinent to Your Immediate Objective).

I recently started a new job and was setting up my development environment on my new computer. I found myself using the **curl** command often to install various programs.

Side note: this post could also be titled ***The Benefits of a Calm and Organized Work Environment***.

I took a moment to stop and read a little about exactly what the **curl** command did to refresh my memory (having briefly visited the topic when examining APIs in an earlier post).

Long story short, the **curl** command acts as a client sending an HTTP request that contains a ***method*** (like GET, POST, HEAD, etc.) to a server to retrieve info.

So, for example, when you type ```curl http://curl.haxx.se``` into your command line, you will get all of the HTML for that particular page show up in your terminal.


Equally important, in my searches I came across a really great page providing for not only background info on **curl** but on HTTP scripting as well. A ton of great reading can be found on the [curl.haxx.se](http://curl.haxx.se/docs/httpscripting.html#Background) site including:

- HTTP Authentication
- HTML Forms and Methods (GET, POST, etc. requests); and
- Cookies