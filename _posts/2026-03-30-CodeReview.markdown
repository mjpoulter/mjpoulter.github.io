---
layout: post
title:  "Code Review in the age of Agentic code generation"
date:   2026-03-30
categories: jekyll update
---

I see a bunch of folks saying they no longer engage in code reviews, but i think that misses a whole bunch of context around why we do code reviews i the first place. Its usually not to critique the implementation perse, although we do some of that in teaching moments. But it is to create a shared understanding of the code base and its compliance with the teams architecture and design principles and coding taste an esthetics. IMO you want your coding agents to comply with that need in the same way as you would a human developer. In that context its interesting to see a couple of things that came up in the last few days. First Qodo got a bunch of funding to help them build AI supported code review. And OpenAI announced a plugin for Claude Code (acknowledging them as market leader it seems) to allow Codex to be used for code review. I think we are still figuring all this out, but i am glad to see that there is still an effort to get the benefits of code review in the new world of AI enabled software engineering. If we dont ensure code quality and overall code health in our code base, im pretty sure it will decay over time. And i dont agree with the thesis that looking at AI created code is like looking at the output of a compiler. Its very different. One is predictable and repeatable, the other isnt.

All evolving for sure. But if we allow our code bases to decay, we will regret it over time. And while the new tools can help with refactoring, if the humans lose the sense of the overall structure of the code base, its really hard to refactor effectively. I may just be an old guy hanging on to old processes, but i feel strongly that you need to have an understanding of the code base if you are going to maintain it and enhance it over time and not hit a wall at some point. We'll see.

{% include comments.html %}
