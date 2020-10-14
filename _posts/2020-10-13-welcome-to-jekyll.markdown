---
layout: post
title:  "Welcome to Jekyll!"
date:   2020-10-13 22:04:41 -0400
categories: jekyll update
---
You’ll find this blog is build on top of [Jekyll](https://jekyllrb.com/).

If you are looking for build a *static* presentation websites, like personal blog and professional portfolio, meanwhile you are intended to focus on the contents rather than building everything from scratch, then Jekyll and Github Pages could be the things you want to take a look at first. This combination of tech stack is reliable, easy to use, and maintain.

One of the most important advantages of using Jekyll and Github Pages is the abundant resources you can find online. Not only the step by step [instructions](https://programminghistorian.org/en/lessons/building-static-sites-with-jekyll-github-pages), but the tons of successful and beautiful [examples](https://jekyllrb.com/showcase/) make it is easy to start with. 

There is no need to reinvent the wheels. The above instructions are very informactive. I installed my ruby2.6.0 and gem via brew on MacOS 10.14. Just one thing happened to me while I was installed the Jekyll.  After the installation of Jekyll has done, I typed `jekyll` in my terminal. However,
~~~bash
$ jekyll
~~~

Gives an error:
~~~bash
-bash: jekyll: command not found
~~~

I had few experience with ruby and I searched online for solutions. Unfortunately nothing worked and I almost gave up. Until I tried the following 

~~~bash
rbenv rehash
~~~
 
The problem sloved! If you are using  RBENV instead of RVM you simply need to run rehash in the command line after installing jekyll.

This is the easiest and the right one I needed. If you are in a similiar setting, try it before anything else.

