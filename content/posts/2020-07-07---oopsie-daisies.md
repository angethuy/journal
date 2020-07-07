---
title: "oopsie daisies"
date: "2020-07-07T02:41:41.831Z"
template: post
draft: false
slug: "oopsie-daisies"
category: "daily log"
tags: 
  - "ahhhhhhhhhh"
  - "daily"
description: "the one in which Angela realizes she regrettably deleted all the dependencies and even more regrettably chooses to manually redownload all of them"
---

IT WAS THE BEST OF TIMES, IT WAS THE WORST OF TIMES

### Done today: 
- official capstone kick off 
- explored the Yelp Fusion API and successfully retrieved a really detailed list of ice cream shops in Seattle! 
- ported that JSON data into an Airtable 
- fixed broken blog dependencies AHHHHHHH 

### Lesson learned: 

At some point during my last work day I deleted my package.json file and node_modules in my journal repo because I thought doing so would fix the fact that I accidentally installed some packages using npm and some as yarn (why are there even two major package managers grrgrrr). 

Turns out all it did was delete all the things. So when I started up my dev server for this blog I was met with many! angry! terminal! messages! saying that different dependencies and packages could not be found. `yarn install` couldn't help me. Cue an hour of manually figuring out which dependencies were still missing and running `yarn add` on about 2 dozen packages. 

The good news is I will likely never, ever mix up my package managers ever again. The bad news is I checked github after all of this and saw that *I had checked in the correct version of the package.json file and had I remembered that, I wouldn't have had to manually install anything*. Good news is I will likely never, ever question the value of good Git hygiene ever again. Bad news is I'm still screaming on the inside and will probably continue screaming for the rest of today. 

Another cool thing was how quickly I was able to modify the post generation script using what I had learned last time. It also helped a lot that I had written my work notes down from the previous work session. 

All progress counts.

### Brainfood 

I had a nice chat with my industry mentor today and we spoke about estimating work time. I told her that I imagine Real Functional Adults to be able to more accurately estimate how long a task will take. She laughed at that and said in reality, no one knows. So we agreed that my goal should not be "estimate time more accurately" but rather, "recognize when I need to adjust my goals to account for unforeseeable snags in the plans". It's a lot less weight to think "I will get as far as I can on 6 solid hours to work today" vs "I will get x and y and z done today".
