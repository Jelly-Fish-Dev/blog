---
layout: post
title: Making a Blog or How I learned to stop worrying and love static site generators
author: Isaac Hawkins
categories: [web]
---


# So you want to build a Blog

Every Keyboard Warrior out there is trying to make their way in the world, make a splash and share their amazing code or opinions knows that the best way is to start a random blog and get it all on Hacker News before your insperation dies. Of course the real world is never that romatic but that doesn't mean you have to give up, at the very least you will at least be able to get your thoughts out there hopefully the mean comments that you'll get on reddit/hacker news won't hurt too much...


Yeah hopefully it won't be too bad!

# What tools should you use

The joy of wanting to start a blog is that there is no shortage is fully featured tools to both create, manage and deal with one. From Blogspot to Tumblr, Wordpress to Medium.com, there are plenty of great tools you can use to build your site...

But which one should you choose, which of the thousands of toolsets will work exactly how I want it to work. Some of the more technically minded may attempt to build their own blogging base, and quickly be shot down when they realise the level of work required to make it both stable, but also somewhat secure and actually properly work. 

For a while I was trapped in this hole, swearing myself that as a new freelance developer I was above these fancy toolsets... swearing that I could create, and even more arrogently manage a blogging engine for my own specific purposes. But for every stride I made in an eventual deployment, I felt a slip under my feet as something else went wrong, something that I needed to change and had to make right. The problem is because there are so many simmilar tools, you feel the need to make something... more.

# When you give in

Giving in from using the super specialised tool that you want to design is hard, its something however that you come to accept at all stages of being a developer, sure you can try and create a super speicalised system that handles your one purpose perfectlly, but theres often a node modual that will do what you want 4 times better, handle more use cases and not break if that mysterious dependancy you never use but for somereason the whole application breaks if you decide to get rid of it (I might be projecting a little...). 

A quote that stuck with me after a day of lots of hard work and very little progress being made on my blog application was something along the lines of: "A blog is just a webpage that hosts your posts, a text file on an ftp file could do the job if you have to". It was here where I realised my error, I realised that I didn't have to make some super fancy application just to host my blog, or even use a super fancy application. A blog *is* just a colleciton of posts, it doesn't need a particually fancy backend...

It just needs to serve my posts.

# Static Site Generators

Sometimes to build a house, you just need a hammer. And when you build a blog, you just need HTML. Now a Satic Site Generator is a bit more fancy than HTML, but it outputs static html pages, and gives you a degree of 2018 new programmer flavour that you can't get from the old ways. You want to be able to markdown what you intend on posting, then put it out there for everyone to make fun of on the internet. Theres no reason to over think the purpose of your blog, to add claps and comments and all manner of disgusting newr world features, its just a board to post yur thoughts,opinons and what you need to get out there.

Now as someone who works in web 3.0 fancy full stack applications that can get you the size of someones ring finger after putting it through a big data algorithm, that line of thinking is dangerous for my bottom line, but the reality is you just need a hammer.

The Hammer tht I chose was Jekyll, a well known static site generator that I could use to even host my blog just off Github pages, wihtout having to worrying about server hosting or downtime (like my main site seems to be doing if I don't tend to the docker deployment). Another upside to jekyll is it has lots of prebuilt themes so I don't have to venture into the tempremental territory of webpage styles.

By and Large, by using Jekyll to deploy my site, I was able to get it up and running in an afternnon, vs the hours of work I had put into a half complete execution of the same thing in Node. Sometimes developers feel the need to do it their own way due to some level of pride, but at the same time, it helps just to get the job done so you can move onto a more deserving, and rewarding project.