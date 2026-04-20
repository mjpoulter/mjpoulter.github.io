---
layout: post
title:  "All about the chips (again)"
date:   2026-04-20
categories: jekyll update
---
So while there has been lots of agonizing about the availablity of land, power, electricians and plumbers (everything is watercooled again) it seems we are back to focusing on chips. After all its the characteristic of the current approach to compute that is driving the power and cooling demands. Nvidia continues to push that their approach is the one true way as it is generalized accelerated compute and that they have the influence on the supply chain to ensure supply, but there are cracks beginning to appear in that facade, including their introduction of the Groq based LPU's.

In the news we have Elon's Terafab initiative to introduce capacity outside of the current players, or more to the point, outside TSMC. And Intel has signed up for that gig. Not sure if Elon has figured out how to get more out of ASML or how to produce alternatives, but that seems to still be the key bottleneck in chip supply, and so limits our ability to produce more wafers of completed chips, regardless of design.

The other thread is custom designs from the hyperscalers to reduce the dependence on Nvidia and to produce more effecient designs for inference. Google is making a big move in that direction, as it seems are Meta (as Hok Tan resigns from the board so as to reduce the need to disclose their spend with Broadcom). AWS of course have their initiatives as do Microsoft. Google seems inclined to work beyond Broadcom, with tie ups with Mediatek and Marvell alongside their existing Broadcom TPU relationship.

i personally believe that the way forward is to reimagine the compute architecture to make it more efficient as that is going to be key to making the adoption of GenAI more widespread. I also dont buy the Nvidia position that their approach is general. GPU's arent exactly general purpose. They work well for training, but even there, it might be that there are more efficient approaches, not withstanding the fact that GPUs were the initial enabler of the progress with model training. The Groq push is an implicit admission no matter how its spun. The danger is that Nvidia lock up the supply chain and make it hard for others to compete. Which of course they can afford to do as a defacto monopoly. Here's hoping innovation and not just heft, wins the day, and TSMC show some love to other players. But there's a reason Elon is doing Terafab. He believes that power will be solved, even if its by putting datacenters in space, but that you cant solve for chip supply unless we dramatically increase the production capacity or find ways to reduce the need.

Nvidia + TSMC + ASML is currently a monopoly supply chain.

{% include comments.html %}
