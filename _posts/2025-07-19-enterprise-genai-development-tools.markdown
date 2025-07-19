---
layout: post
title:  "GenAI Dev tools - in the enterprise"
date:   2025-07-19
categories: jekyll update
---

Generative AI for software development seems to have become the first place where folks believe there is going to be revenue generating traction. Lots of swirl this week around windsurf as previously noted, but also Anysphere (cursor) who acqui-hired talent from Resourcely and Koala this week, but also seem to have lost the two folks they had lured from Anthropic/Claude Code, back to Anthropic, and we wont mention the crazy money Meta is putting to play in acquiring talent. If you read through what happened at Windsurf you realize that the second tier folks have a different set of concerns than the leading talent. And i have to think that all this is going to change the way folks joining in the later waves of hiring at these sorts of startup think about their contracts, vesting schedules and just general trust in the mission? Even Daniel Gross leaving as CEO Safe SuperIntelligence so soon is bizarre, but shows the level of $$s being moved around. It doesnt feel healthy and makes you wonder if there is any appettite for a new round of startups as the big guys double down on competing. After all it was Microsoft, OpenAI, Google and Anthropic driving the Windsurf, Anysphere swirl. I have a hard time seeing how the smaller guys continue to compete.. but we'll see i guess, perhaps the big guys wont really understand the sustaining marketplace, which for software development is the enterprise, not retail.

On that note, most of the early push as been around creation and modification of code, with a secondary focus on pipelines etc. And while there is clearly value there, its not really hitting the enterprise problem space head on. In an enterprise you are dealing with lots (and lots) of preexisting code/systems/processes with preexisting context and policy, standards, guidelines, frameworks, libraries, documentation of lots of different vintages. So very little greenfield, lots of brownfield, and some toxic waste dumps. Understanding is incomplete with much code written by folks no longer with the firms (like me!).

 The current sets of tools dont really address the space very well, or they take a lot of adapting, which means that more effort has to be put into implementing them to reap the benefit. And in my experience, understanding in context is a real value add, and unlike generation, has few downsides. ie if the output isnt 100% accurate it doesnt matter, because human recollection isnt 100% accurate in that context either. And of course understanding in context. is key to updates, modifications, transformations, reengineering etc. and not to mention creation of the full range of tests (ie not just unit tests)

To that end, the announcement that caught my eye this week was from reflection.ai https://reflection.ai/ with their initial intro of asimov https://reflection.ai/blog/introducing-asimov .. and a good rendition of their perspective on the latest no priors podcast https://www.youtube.com/watch?v=xqyy_Zs8Fgw . Definitely felt like they understand the problem space well and have an approach to solving for it.. Early days, but i like their approach.. as always.. time will tell..

Ive also been trying out the cli tools this week.. most recently the google gemini code assist cli (which they've opensourced). I like it in certain situations, much like claude code.. and much like any console interaction, but i still move back to the IDE for most clean sheet creation.

In other news, AWS continuing to play catchup with their Bedrock Agentcore and related annoucements, they seem to be having a hard time getting mindshare around AI in general, and so moving back to an infra approach probably makes sense for them https://www.aboutamazon.com/news/aws/aws-summit-agentic-ai-innovations-2025

On a related AWS note i discovered that they opensourced their postgres replication a few weeks ago https://aws.amazon.com/about-aws/whats-new/2025/06/open-sourcing-pgactive-active-active-replication-extension-postgresql/. Good to see them giving back. 

Still thinking about the right cadence for these sort of postings going forward. Inside a firm its easy to just post quick snippets as they come to mind, or to give in the moment opinion on news. For some reason this feels a little more formal with a need to carve out some time to do it. Hence the Saturday morning(West Coast) post this week. No doubt i'll figure out a rythmn after a few weeks.

{% include comments.html %}