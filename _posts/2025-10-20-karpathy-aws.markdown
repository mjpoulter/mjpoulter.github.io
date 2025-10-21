---
layout: post
title:  "Resilience and AI realism"
date:   2025-10-20
categories: jekyll update
---
I had a post already to go, and then we had the AWS US-East-1 outage which had me reflecting on what we should be expecting from our systems these days, and particularly the implications for integrating AI solutions into our lives if folks continue to engage in magical thinking when it comes to resiliency tradeoffs. Do we really want our self-driving cars looking for a route update and having a problem because us-east-1 is down? (which further goes to my point about wanting critical inference to be local/at the edge). Seems far fetched but there were lots of systems yesterday that i was surprised to see taking an outage. You'd think by now most companies would have their systems at least multi-region resilient. I know multi-cloud is much harder and in many cases probably is hard to justify for many, but i think i'd want multi-everything for safety critical systems, and AI may well quickly end up there. These sorts of designs are hard, take care and detailed design to address all the failure mode edge case, but i think that should be table stakes for most mission critical systems these days. Maybe regulators need to insist and companies procuring products to be more careful about understanding their suppliers resiliency and backup plans. After all "things fail all the time". <https://cacm.acm.org/opinion/everything-fails-all-the-time/>

And so onto the post i had planned. I wanted to highlight recent work, blog and podcast material from Andrej Karpathy. It was interesting to hear from the person who coined "Vibe Coding" putting it in its appropriate context and making the point that serious software engineering can't/shouldnt be done that way. Also great release of NanoChat. The blog and podcast are both worth a look/listen, and the Nanochat repo is defintely worth checking out. I think the material speaks for itself. Of course confirmation bias has it resonating with me !!
<https://github.com/karpathy/nanochat> ,
<https://karpathy.bearblog.dev/animals-vs-ghosts/> ,
<https://www.dwarkesh.com/p/andrej-karpathy>
 
 Its noticeable that on the back of the podcast, because of Andrej's reputation and visibility, and the fact that he's not a typical AI skeptic, that more people have been paying attention to his more cautious view on the work still needed to get to AGI or superintelligence. I also think his perspective that adoption will be gradual and not a point in time event correlates with my own thinking and those of others who refer to the classic enterprise adoption cycle for new technologies (this is just another technology adoption cycle) along with the AI industry's search for stable, sticky revenue and margins that will pay for the investments and not turn away adopters. Andrej thinks is a decade away and i tend to agree, and thats not even considering that maybe we wont get their with transformer based LLMs and need new approaches (he was very scathing of reinforcement learning).

 So more work to do. Lets make sure that as we innovate we take into account resiliency!

{% include comments.html %}
