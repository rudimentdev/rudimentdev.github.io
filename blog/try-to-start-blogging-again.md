---
title: Try to start blogging again
date: 2022-05-26 15:16:09 +7
tags:
    - writing
    - static website generator
---

In 2007 I start my first blog on Blogger, which I write in Bahasa Indonesia since my written English is far from good enough for conveying things I want to write about at the time. My reason for starting my own blog is just following blindly what most of the people on the internet doing at that time since it's the time I start my foray into the interesting and exciting world of the Internet.

The interest is short-lived, it's gone as quickly as it came, and the blog only amounted to measly 5 published posts. I got busy juggling between college and my other interests of messing around with Linux and learning computer programming. I love going online, foraging all kinds of articles and web pages relating to Linux and computer programming. Even at the campus, I spent most of my recess time at the campus cheap Internet cafe, surfing the Internet via the sluggish dial-up connection, hoarding downloaded web pages on dozen of 3,5-inch floppy disks, which I copy over later on to my measly 40 GB harddrive.

Recently at my day job I need to write documentation for our service API which needs to have a white-label feature, where we have a separate unit of businesses that use the same service API but with different branding. We already have OpenAPI documentation for the service API, but we have difficulties making it white-labelable, for lack of a better word. Because of that I decided to use [Docusaurus](https://docusaurus.io/), a static website generator focused on building a documentation website. With the React components feature, I'm able to make the documentation website white-labelable.

After experiencing the simply wondrous taste of a static website generator, I'm hooked on the idea of creating a website that is geared toward writing content with simple tools. I also realized how important the skill of writing good documentation for my daily job as a software engineer and how lack I'm of it is. Therefore I decided to pick up the blog writing activity once more, to try to force myself to improve my writing skill.

After assessing multiple static website generators, I choose to use [Eleventy](https://www.11ty.dev/) considering how easy it is to learn and use compared to other choices regarding my lack of experience with static website generators. It satisfies my needs, which I decided to be as simple as a blog could be, which is just a list of posts, a post with title and date, and tags reference. I want to focus more on writing content instead of bike-shedding on the blog bells and whistles.

I choose the simple and free Github Pages for public repo with a custom domain name to host the website. I use Github Actions to build and deploy the website. The source code repository is at [https://github.com/rudimentdev/rudiment.dev](https://github.com/rudimentdev/rudiment.dev) if anyone would like to have a look.

Now after doing all of that effort, making my mind to improve my writing skill, what's left to be doing is that I need to keep on writing and stick to it, let's hope it will be better this time :).
