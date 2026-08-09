Hi, I'm Mario

I automate the operational work behind streaming pipelines.

At Warner Bros. Discovery I run encoding and OTT delivery operations for Max and Discovery+, across a catalog of more than 100,000 titles. The part I care about is taking the manual work out of it. Two recent examples: Python monitoring that polls our pipeline and orchestration systems and posts structured failure alerts to Slack, and an automation that writes status notes into our asset management system through its API, with resume logging and retry so an interrupted run never double-posts. That one replaced manual entry of a thousand-plus comments and gave four hours a day back to the operations team.

Before that, six years in master control at Cox Media Group, where live television taught me that systems fail and what matters is how fast you see it.

Right now I'm working through a 28-week push into AI workflow automation. n8n Academy N8N101 and N8N102 done, N8N103 next, plus agent patterns, RAG, and the Model Context Protocol. AWS AI Practitioner exam in December.

What I'm building

n8n-automations — weekly automation builds, one folder per week. Each ships with the workflow, the reasoning behind the node choices, and an honest account of what broke.

Four questions I ask of anything I build, because they decide whether it survives contact with production:

Idempotency — what happens if this runs twice?
Error handling — retries, backoff, and where failures land when nobody is watching
Cost — which steps genuinely need an LLM, and which are just plumbing
Verification — how do I know it worked, rather than assuming it did

Atlanta, GA · LinkedIn
