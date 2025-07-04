---
layout: ../../layouts/MDPostLayout.astro
title: 'Using Neovim'
pubDate: 2025-07-03
description: 'My experience using Neovim (So far).'
author: 'Sophi Dickens'
image:
  url: 'https://cdn.thenewstack.io/media/2025/03/53f8c39d-novim-1024x768.jpg'
  alt: 'The Neovim N logo with Neovim after it.'
tags: ['development', 'neovim', 'code-editor']
---
I'm using this project as my introduction to Neovim.<br>
# **Neovim**<br>
Neovim is a code editing software that runs in a terminal window. I'm using the Warp terminal that Neovim is sponsored by, which I had already started using prior to attempting to use Neovim.<br>
## **The IDE vs Neovim**<br>
My IDE of choice before using Neovim was Visual Studio Code. I had been using the native autocompletion and the GitHub Copilot support to make my life easier. Problem was, I couldn't shake the feeling that the number of extensions and AI features were turning me into another Gen-Z brainrot vibecoder. So I decided to switch to something more hands-on.<br>
Making the switch to Neovim was simple. I already had Warp, and all I really needed to do was install it. So I did, I ran brew install neovim, routed to the root folder of the project I was working on, ran nvim and BAM! I saw a largely blank screen and had absolutely no idea what to make of it.<br>
## **Starting to Use Neovim**<br>
The starting screen with no plugins is incredibly barebones. That makes perfect sense for a text editor within a terminal window. There are 4 options when you open Neovim without specifying a directory:<br>
*:help nvim*<br>
*:checkhealth*<br>
*:q*<br>
*:help*<br>
I have used all of these to various degrees since starting to use Neovim. Mostly *:q*. So if someone asks me to quit any vim fork, I can flex my knowledge and delete all their work in the process *:q!*.<br>
I've used *:checkhealth* twice. Both times were to try to figure out what plugin set I had installed for Neovim. Neither time actually answered my question.<br>
*:help* comes in handy occasionally but I don't use it as much as I should. Usually I have specific questions that I need to answer using the internet. It has helped occasionally, but I've used the internet to learn more, *:Ntree* and *:b* were big ones I learned using the internet and I use those more than *:help*.<br>
## **The Neovim Tutor**<br>
Then I hit *:help nvim*. The specific Neovim help page was the key I needed to unlock Neovim and use it efficiently. The first thing *:help nvim* tells you to do if you are new to vim is run *:tutor*. The Neovim Tutor walks you through the main commands for using Neovim efficiently. It shows you the movement controls, different functions for search, replace, the primary macros for switching modes, selecting areas, deleting areas, yanking and putting, and many other macros that are meant to speed up your life when using a non-IDE text editor.<br>
Learning using the Neovim tutor was beyond useful. By the end of the first day of playing around in the tutorial I was replacing characters, deleting to the end of lines, searching documents and substituting text, moving around the document with ease. Has it increased my productivity? Not yet. I am still fairly beginner level with using Neovim compared to where I was with VSCode, but am I better than I thought I would be this quickly? Absolutely.<br>
## **Switching to Neovim**<br>
It was a lot easier to switch to Neovim that I thought it would be. But I can't say that it doesn't have it's drawbacks out of the gate.<br>
There are some key differences between the IDE and Neovim that are immediately noticeable.<br>
### **Different Types of Control**<br>
The "reason" I switched to Neovim was because I had worn out my right arrow key from how hard I press it. And by worn out, I mean that the key is missing. I use a macbook and I am missing the right arrow key. It got really annoying having to push the tiny switch to press the right arrow. Vim's method of using the H J K and L keys for movement is generally the same as using the arrow keys. They accomplish the same thing of taking you from wherever you are, to wherever you want to go. The difference comes when you hit other keys before these movement keys. Vim starts to show it's macro oriented approach when you combine the number and movement keys.<br>
*4h*. Move 4 to the left. *6l*. Move 6 to the right. *14j*. Move down 14 rows. Getting the feeling of this new control scheme is the first hurdle in using any vim fork. Then you add the action macros. *d4k*. Delete everything between my cursor and exactly 4 lines above it.<br>
### **Neovim Does Not Want to Do It For You**<br>
When you use an IDE, with all of its autocompletion, AI tools, extensions, key-binds, and extra tabs with Git integration, you can rely very heavily on all of these tools to make your workflow quicker and aid you in long and repetitive programming tasks. **Neovim will not do that for you**. Neovim does not natively have autocomplete. Neovim does not natively have AI tools. Neovim does not have a built in extensions page. Neovim wants you to RTFM, **Read The F\*\*\*ing Manual**.<br>
I had previously thought of myself as someone who enjoyed reading the manual. I have been against using AI to generate entire codebases. I had it on my resume, "A software developer who enjoys parsing the documentation". Yes that is a boring tagline, I know. It definitely turned heads (it didn't). I have read more documentation in the past month working on this project than I had in the years of software development I had done using VSCode.<br>
### **VSCode**<br>
I had been using VSCode to develop for years, and it had been alright. But the pushing of AI tools was beginning to get on my nerves. Learning with AI is not learning, it became reliance. If I used AI to write one piece of my code, I could not stop using it. I could not understand my code when AI had touched it. When I asked AI to fix a bug in my code, it took away my questions without answering any of them. And as soon as I had to come back to that code to fix another bug that another one of my changes caused, I would end up having to use AI again. My Build It Bootstrap Project ended up getting scrapped because of this fundemental lack of understanding of my code. You can still find it on my GitHub Profile which is linked in the social section at the bottom of this page.<br>
AI kept me from learning, and VSCode adding GitHub Copilot support was a further detriment to my pursuit of knowledge. I found that VSCode trying to hold my hand and push me to use GitHub Copilot and ChatGPT more and more. I got fed up with it. I switched from VSCode to Neovim, leaving behind the fancy IDE feeling. I much would rather learn the hard way than fail from trying the easy way.<br>
## **Opinion**<br>
I enjoy Neovim. I have had a lot more fun writing things in Neovim than I did in VSCode. Bouncing around my text editor is infinitely more satisfying. If you are looking for your text editor to want to help you, vanilla Neovim is not for you. I would love to add some plugins to my Neovim to color things and liven it up a little bit. I would love to find plugins that helped me navigate my project folder and side-by-side tabs more easily. But I would much rather have to find a few extra plugins than have my IDE feed me AI slop and stunt my brain.
