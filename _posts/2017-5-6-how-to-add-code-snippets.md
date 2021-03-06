---
layout: post
title: How to add Code Snippets
date: 2017-5-7 10:44
---
![codesnippet](http://i.imgur.com/4w1OEUa.png)
---
Ever wanted to add a pretty block of beautiful code?

In this tutorial, I will be teaching you how to add great looking code snippets to your website! We will be using a Javascript API called [SyntaxHighlighter](http://alexgorbatchev.com/SyntaxHighlighter) to help us with this task. Sure, we could code our own syntax highlighter, but a popular saying in the programming world is ***"don't reinvent the wheel"*** -- Which basically means, if someone else has already written a great piece of code for your intended purpose, unless you can somehow improve upon it, just use it.

**<u>Alright, lets get started.</u>**

First, find your index.html, and inside the `<head>` tag, paste the following:

<pre class="brush:html">
<code>
<link href='http://alexgorbatchev.com/pub/sh/current/styles/shCore.css' rel='stylesheet' type='text/css'/> 
<link href='http://alexgorbatchev.com/pub/sh/current/styles/shCoreDefault.css' rel='stylesheet' type='text/css'/> 
<link href='http://alexgorbatchev.com/pub/sh/current/styles/shThemeDefault.css' rel='stylesheet' type='text/css'/> 
<script src='http://alexgorbatchev.com/pub/sh/current/scripts/shCore.js' type='text/javascript'> </script>
</code>
</pre>
