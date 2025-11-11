---
layout: post
title:  "World Models - for systems development"
date:   2025-11-10
categories: jekyll update
---

Good blog posting from Fei-Fei Li today on how she sees spatial intelligence as the necessary next step to start to move towards generalizable AI. Of course i have confirmation bias, because i think its become clear that without that type of approach we will not be able to get self-learning systems.

<https://drfeifei.substack.com/p/from-words-to-worlds-spatial-intelligence>

I also think that while software development, at least the coding part, is grounded in text and language, the overall systems architecture, design and operation of complex systems is much more than just the composition of all the words, as anyone who has been on a complex systems incident call with agree with. And so i think the goal of spatial intelligence applies to computational systems also. We wont get to AI that allows us to build, modify and operate complex critical systems semi-autonomously unless the models can appreciate the full logical and physical dynamics of all the components and their interactions, which in some sense is the computation equivalent of complex chemistry. The only world model i've seen explicitly focused on software development is from Meta, which used code from the python interpreter/compiler to generate execution traces and docker execution traces which were then used as part of the model training.
<https://ai.meta.com/research/publications/cwm-an-open-weights-llm-for-research-on-code-generation-with-world-models/>

You can see how you could extend this research to include more languages, execution traces, network traffic, app/transaction traffic etc etc, to start to build a more complete world model of how complex computational systems behave. Certainly seems like a promising direction to me, and aligned with Fei-Fei's thinking on spatial intelligence i think. Maybe there will be a generation of humanoid robot programmers in our future. Direct port access vs typing on a keyboard as with R2D2! Im guessing noone is actively pursuing this path at the moment. Too much economic incentive to continue iterating on the current approach with LLMs and agentic coding, moving to agentic SREs etc. But i think that will all hit a point of diminishing returns without really changing the way we build and operate systems. Maybe at that point the world model research will get more traction. No doubt we'll find out! Intersting space to follow for sure.

On a different note, the Majestic Labs folks coming out of stealth yesterday provided a little taste of what they are working on. Ive been predicting for a while that eventually the winning compute architecture will have a unified memory model. I recall multiprocessing before and after NUMA, and i know which one i preferred. 

<https://www.cnbc.com/2025/11/10/majestic-labs-meta-google-ai-funding.html?&qsearchterm=majestic>

This feels somewhat like that, but a little too sparse to be sure. Certainly interesting to follow as these folks have solid track records. More to come. But this is the compute equivalent of a world model. Unified memory and simplified compiler supported progragamning is the way you disintermediate CUDA, tho others are trying other approaches too. <https://siliconangle.com/2025/11/10/spectral-compute-raises-6m-fix-cuda-eliminate-nvidia-tax-ai-applications/> , buy that feels like a short term bandaid. Moving away from an explicit attached compute model with discrete memory and data movement to something more unified like a classic virtual memory NUMA multiprocessor is the longer term winning approach i think. We've been throught that journey before with minicomputers and mainframes with attached compute explicitly programmed and eventually they were superceded by simpler programming models. Now its true that the bleeding edge supercomputers are still explicitly parallel and programmed that way, but the programmers would undoubtedly prefer a simpler model.

ps. As a dyed in the wool supercomputer programmer with many lines of fortran behind me, i couldnt help but smile at this blog. <https://medium.com/@daxx5/fortran-outsmarted-our-billion-dollar-ai-chips-61f25b4a40fe> . Just reinforces my simpler is nearly always better point of view!