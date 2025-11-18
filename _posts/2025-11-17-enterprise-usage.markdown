---
layout: post
title:  "The challenge of LLM usage in the enterprise"
date:   2025-11-17
categories: jekyll update
---

Really interesting reset for microsoft being revealed over the last week. Great podcast interview with Satya that is definitely worth a watch/listen. He has clearly moved from the first phase of the LLM cycle and moving to positioning AI as a long term enterprise portfolio play with a big emphasis on COGS in order to be make the offerings affordable.

<https://www.dwarkesh.com/p/satya-nadella-2>

and then the announcement of the tie up between Microsoft and Nvidia with Anthropic. Jensen mentions the enterprise sales cycle.

<https://blogs.microsoft.com/blog/2025/11/18/microsoft-nvidia-and-anthropic-announce-strategic-partnerships/>

All of this talks to the challenge of adoption in the enterprise. While the leading use case of GenAI for software engineering is making progress in enterprise adoption, there are still significant challenges on getting things in place in a secure, compliant and cost effective manner. 

Matt Assay had an infoworld article that sums up the need. Boring adherence to compliance and governance is what is needed. Not lots of hype.
<https://www.infoworld.com/article/4082782/boring-governance-is-the-path-to-real-ai-adoption.html>

Its still very hard to get the companies with AI offerings to focus on the adoption needs of the enterprises. As companies build in new AI capabilities they hook in the LLMs in ways that often make it hard for an enterprise to get comfortable with the implementation, with it being difficult to assure that their information is being appropriately protected, and it gets worse with mcp and agents. Ideally there would be a standardized way to implement those sorts of features such that the enterprise security / information boundary is easy to understand and the existing boundaries are respected. Without that the sprawl of different implementations make the AI addons very difficult to adopt. That then reinforces the narrative that AI is still not enhancing enterprise efficiency, and implies that the revenue potential, remains just that, potential, not actual. Which makes it hard to see how the big scaleout data center build out gets funded, which is clearly why micosoft took a pause and reevaluated their approach.

One approach that companies are pursuing, is to emulate the palantir model of forward deployed engineers. Poolside just did an acquisition in support of that thesis. 
<https://poolside.ai/blog/fern-labs-acquisition>

That helps with providing the skills needed to work through the complexity of standing up all the various pieces, but doesnt solve the basic problem of the implementation approaches sprawl and the lack of understanding of all the governance needs. It will be interesting to see how long it takes before companies figure that out. Its clearly becoming clearer to Nvidia and Microsoft. Hopefully others that provide capabilties to enterprises will also get the message and Satya's "its not a zero sum game" perspective and work together to solve for common adoptions patterns.

Without the enterprise adoption revenue we could be watching an awful lot of ads to pay for all the inference costs. Which is the approach that sourcegraph have taken with the free tier of the amp genai coding tool and it seems to be working for them. Hopefully thats only for personal free tiers so folks like me can experiment, and the tools show enough value to warrant the costs of running them for mainstream production usage. Too many adds might make me pay for a subscription! Still I digress. Lets get to boring quickly! I'd love to be able to just plug in a tool or service with AI assists in a standard cookie cutter way, with a standard set of security/governance reviews and not have each case be completely unique.

Boring is good!
{% include comments.html %}
