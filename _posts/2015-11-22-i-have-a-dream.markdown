---
layout: post
title:  "I have a dream"
date:   2015-11-22 19:36:00
categories: blog
author: mick
---
Welcome to the first blog post of the Zeal SNES SDK. This blog will document my journey about learning about the SNES internals, the developments of tools and librairies and analysis of existing games for studying how they did certain graphics effects.

But first, let's explain why I decided to create my own SDK with its own high-level assembler and this blog.

### The seed of the idea
I'm a person with a lots of idea for projects. On the verge on turning on my third decade, I started thinking about what I really want to do with my life, before I get more responsibilities (if that ever happen). One of these idea projects was to create a cyberpunk/hacking short film with special effects, I'm not a filmmaker by any means but that's something I wanted to try. But someday that idea switched completely and the idea became to make a JRPG game with that similar theme. Often, the JRPG genre is based around sword and sorcery themes and rarely they explore other universes of fiction. I also always wanted to write a game for a old-school console like the NES or SNES. So the idea combined to create a short (2-3 hours) JRPG for the Super Nintendo, one of my favorites game console of all time. Why short ? Because I want to complete the project and having a smaller scope would help achieve that goal.

### Why create your own tools ?
I could try to use existing tools but I found the pipeline to be lacking. For instance, the tool to convert graphics to be suitable for the SNES graphics processor is using PCX as an image format. PCX is dated format that is hardly used nowadays, the artists that I know uses GIF or PNG as a image format for pixel art. GIF was hindered with patents for a long time but the patents expired in 2004 so we can use the format without issue in a open-source project.

For the assembler, I could have used [WLA-DX](http://www.villehelin.com/wla.html), [ca65](http://cc65.github.io/cc65/) or byuu's [bass](http://byuu.org/tool/bass/) but I want to try to write my own assembler with high-level features like scoping, module, if statement, math expression and other features that will come by when I'll write and use the assembler. I would also love to integrate it with Visual Studio with source-level debugging support, we'll see if I ever do that.

If you know a bit about the SNES architecture, you know that sound is a complex matter. I intend to reuse exiting code and tools, and only modify existing tools if I have to. 

### How much do you know about the SNES ?
Well to be honest I don't known that much about the SNES internals, the graphics processor (or PPU) for instance is a complete mystery for me. That's one reason why I created this blog, to share with you my discovery of that complex beast. But I know enough to be able to do some assembly ROM hacking, so far I added [MSU-1](http://helmet.kafuka.org/msu1.htm) support to many classic games, see my [romhacking.net](http://www.romhacking.net/community/3447/) profile for more info.

### The name
I always named my personal game engines with name coming from my favorite game of all time, Chrono Trigger. My modern 2D game engine experiment was called **Black Omen**. For the retro gaming engine, I find **Zeal** to be a fitting name because Zeal is the kingdom of dreams and I always dreamed to write my own homebrew and programming language.

### State of the project
So far, there is no code written yet, I wanted to setup this blog first. I intend to stream some of the development of the SDK so follow the project on social media to known when I'll start doing that.