---
title: "Hello world"
date: "2020-07-05T03:32:08.730Z"
template: "post"
draft: false
slug: "hello-world"
category: "daily log"
tags: 
  - "confetti"
  - "daily"
description: "the one in which Angela sets up a project blog using Gatsby, Lumen, Netlify, and a finnicky post generator package"
---

Hello world! 

### Done today:  
- decided on a project name 
- created Pagotometer logo (more on this later)
- set up blog (we're officially Jamstack-ing now wooo)
- fell a little bit in love with Gatsby

### A proud moment: 
I'm using the Lumen boilerplate which has a specific template for blog posts; oddly enough the package doesn't include a generator for each post. I added the [Gatsby Lumen Post Generator](https://github.com/reed-jones/gatsby-lumen-post-generator) which was a good starting point for generating posts, but since it's 2 years old it needed some dusting off and reformatting to catch it up with the latest versions of Lumen. This involved diving into the code for the package and some sleuthing to see where the mismatches between the post generator and the Lumen boilerplate were. It felt good to recognize JS code and use the familiarity to orient myself towards file reading and writing, two tasks I've not tried in JS yet.

### A squashed bug: 
For a while I kept getting this weird error message whenever I ran `yarn lumen-post` to generate a new post: 

`env: node\r: No such file or directory`

I learned that ['\r' indicated a weird carriage return symbol](https://github.com/docsifyjs/docsify-cli/issues/78) that appears in some text files. Fixed by installing dos2unix and running it on LumenNewPost.js to convert it to unix. 

### Interesting discovery: 

Someone made an [Emoji Compass](https://apps.apple.com/us/app/the-emoji-compass/id1440200804) loosely based off Philip Glass' His Dark Materials trilogy, the same source inspiration for my Pagotometer! Really happy to have found it because it demonstrates how a compass UI could look/feel like as an app. [Source code for it](https://github.com/BadIdeaFactory/corporate/issues/45) is available too. I love the internet.



