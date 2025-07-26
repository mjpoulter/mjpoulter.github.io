---
layout: post
title:  "Security(supply chain), Transparency and Trust"
date:   2025-07-26
categories: jekyll update
---
Lots going on again this week in the world of AI for software development. We had the qwen coder announcement along with their fork of the gemini cli to interact with their models <https://github.com/qwenlm/qwen-code>, and continued progress from anthropic with their introduction of sub-agents for Claude code <https://docs.anthropic.com/en/docs/claude-code/sub-agents>. Great progress continues. However on a more sobering note there was a reminder that basic security and supply chain security are still big issues that we need to guard again, and not forget about as we race forward to leverage all this new capabilities.

First we had the sharepoint zero day, whose impact will take a while to fully understand, but again just serves to remind us about the importance of basic security hygiene. <https://www.cisa.gov/news-events/alerts/2025/07/20/update-microsoft-releases-guidance-exploitation-sharepoint-vulnerabilities>.

As serious and impactful as that was the item that really caught my eye was the successful supply chain attack on the AWS Q developer VS code extension. <https://aws.amazon.com/security/security-bulletins/AWS-2025-015/> , which followed along behind recent issues with the open extension marketplace used by the vscode forks, eg cursor, windsurf etc.  <https://thehackernews.com/2025/06/critical-open-vsx-registry-flaw-exposes.html> . The reason the AWS issue seemed more serious to me was the way AWS handled the event, as well documented by Corey Quinn, they werent exactly transparent and of course that leads to a major loss of trust which is going to be hard for them to win back. <https://www.lastweekinaws.com/blog/amazon-q-now-with-helpful-ai-powered-self-destruct-capabilities/> Hopefully they learn the lesson and do better if there is a next time.


Of course we also had the recent story of the user who let an AI agent delete their production database, another reminder that we cant abandon basic controls in the name of experimentation. <https://gizmodo.com/replits-ai-agent-wipes-companys-codebase-during-vibecoding-session-2000633176>

We have had mcp server vulnerabilities as well, and mistakes there can also be catastrophic.

Anyway, all of which to say is that as we run fast, we need to sure not to break things, at least not things that matter! Its only really possible to go really fast if you have good brakes. And the bad guys are going to be actively trying to exploit our carelessness. How did the old "Hill Street Blues" saying go? "Let's be careful out there"..
{% include comments.html %}