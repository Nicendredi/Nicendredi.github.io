---
layout: post
title: The strugle of creating my own blog
categories: webdev
author_staff_member: nendredi
show_comments: true
---
This website is not my first attempt at bloging (it was for publishing French novels in a serial fashion). But, no matter how much time I spent building or configuring my blog, it was never good enough : CMSs always lacked some functionality or personalization, building it from scratch was a pain and other solutions demanded way too much work or knowledge.

## The tool to rule them all

However if you are reading theses lines, it means I finally found a solution ! Well the truth is that I stumbled on the perfect tool about 2 years ago : [Jekyll]. A simple, blog-aware, static site generator that generates the blog posts from [Markdown] files ? Sign me in ! There was just a tiny mini problem : I suck at web designing... So after a few ugly projects I put that project aside on that pile. You know which one : the pile of projects you keep telling yourself you will get back on someday. I am proud to say I made at least one project of this pile a reality.

Yet it was not as straight forward as you might think. A few months back I tried to build a blog almost from scratch using only Jekyll and what I knew in web development. And, *[of course]*, I failed, because I could not find a way to make the website as pretty as I imagined. Nonetheless I did not gave up quite yet. I started searching for an easy solution to use Bootstrap with Jekyll.

Hence [Jekyll Bootstrap], a Jekyll theme and plugins mash up. Excited at first, I grew tired of the Bootstrap white design pretty quick, so I tried to modify the source code. And that is pretty much when I gave up on Jekyll Bootstrap... I know people who are used to Bootstrap or who like Jekyll Bootstrap are going to say things like "you should have tried this way", "why didn't you tried this?", and so on.

The thing is that I am not comfortable with Bootstrap : every time I try to make something that I know how to do from scratch, I end up reading more documentation than for doing it from scratch and the results are not what I wanted. I am pretty sure it is all my fault, but I have no idea how to fix this.

Moreover I started thinking on how to make the blog multilingual and hit a wall : there are way too many files to seek through ! If I wanted to translate every word on the blog (not the code of course), I had to check more than 30 files just in the `\_includes` files.

## The Jekyll Bootstrap aftermath

So there I am, with a Jekyll Bootstrap project that I do not like, but still that urge to make a blog. Being the type of person who browse aimlessly until it finds something worth it, I dug up a great use of Jekyll, GitHub and cloud sharing : [CloudCannon]. First thing first, ~~I'm the realest~~ this is not an ad for that company, I am just fan of the idea behind it and a bit jealous I did not build it first. I will not list every functionality, but the most important is that, by versioning a Jekyll project on GitHub and developing a web interface to edit the content of the website, they have created an ultra light-weight CMS easy to use and improve. If you want a fascinating example just read the [Netflix's Case Study].

Anyhow after reading a few pages and consulting their well made [tutorial database][CloudCannon Academy], I was sold, but being the penniless developer that I am, I cringed when I read the word *Pricing*. At the exact moment I was going to close that tab, I spied with little eye, something starting with *F*... [Freebies] !
And not any freebies, but Jekyll Templates so well done they should come with every install of Jekyll so people knew straight from the beginning how eye-pleasing and efficient can a good Jekyll website be.

So I started tinkering with the theme to make it mine and configure it. It was so intuitive that in a few hours all was set and clean. I'm writing this post on the next day and I fell like nothing can stop me. This website is empowered by Jekyll and CloudCannon but the real thing they empowered is me.

[Jekyll]: https://jekyllrb.co
[Markdown]: https://daringfireball.net/projects/markdown/
[of course]: https://youtu.be/X8u7px_GzWQ
[Jekyll Bootstrap]: https://github.com/plusjade/jekyll-bootstrap
[CloudCannon]: https://cloudcannon.com
[Netflix's Case Study]: https://cloudcannon.com/case-studies/netflix/
[CloudCannon Academy]: https://learn.cloudcannon.com/
[Freebies]: https://cloudcannon.com/freebies/

**TLDR;** Building a blog is hard, but it's easier with [CloudCannon]'s [Freebies]
