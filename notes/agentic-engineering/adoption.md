---
title: Adopting coding agents
description: "Rolling out coding agents in an engineering team, and checking whether they make the team faster and its software better."
why: "Spending on agents, hiring plans and team design all rest on how much agents speed up the work, and developers' own estimates of that are unreliable. Controlled studies and repository data give a company a sounder basis for these decisions."
reviewed: 2026-11-21
sidebar:
  order: 1
tags: [adoption, productivity, rct, coding-agents]
related: [agentic-engineering/tools, delivery/delivery-metrics, agentic-engineering/delivery, agentic-engineering/supervising-agents, team/engineering-strategy]
sources:
  - title: We are Changing our Developer Productivity Experiment Design
    author: "Joel Becker, Nate Rush, Tom Cunningham, David Rein, Khalid Mahamud (METR)"
    url: "https://metr.org/blog/2026-02-24-uplift-update/"
    type: article
    year: 2026
    note: "METR's early-2025 randomised trial found that experienced open-source developers took 19% longer with AI tools. This update reports a second study whose data METR judges unreliable, because more developers now decline to work without AI. METR expects the speed-up is now larger but cannot measure it with this design."
  - title: "Speed at the Cost of Quality: How Cursor AI Increases Short-Term Velocity and Long-Term Complexity in Open-Source Projects"
    author: "Hao He, Courtney Miller, Shyam Agarwal, Christian Kästner, Bogdan Vasilescu (Carnegie Mellon University)"
    url: "https://arxiv.org/abs/2511.04427"
    type: paper
    year: 2025
    note: "A difference-in-differences study of 806 open-source GitHub projects that adopted Cursor between January 2024 and March 2025, compared with a matched control group. Lines added rose three to five times in the first month, but the gain faded after two months. Static analysis warnings rose about 30% and code complexity about 41%, and the authors link these rises to the later slowdown. Results hold for projects that adopted after Cursor's agent mode shipped."
  - title: "Artificial Intelligence in the Firm: Bottlenecks in Software Production"
    author: "Fiona Chen, James Stratton (Harvard University)"
    url: "https://fion.ac/jellyfish.pdf"
    type: paper
    year: 2026
    note: "A working paper that compares firms by when they adopted AI coding tools, using data on 720,542 workers at 655 firms from Jellyfish, which sells engineering analytics. A year after adopting coding agents, firms opened 35.7% more pull requests, but resolved issues rose only 13.7%, a borderline result, and no effect on employment was detected. Code review became the bottleneck: time from review submission to merge rose 56.1%. It is not peer reviewed, and Jellyfish checked it only for proprietary data."
  - title: "Adoption and Impact of Command-Line AI Coding Agents: A Study of Microsoft's Early 2026 Rollout of Claude Code and GitHub Copilot CLI"
    author: "Emerson Murphy-Hill, Jenna Butler, Alexandra Savelieva (Microsoft)"
    url: "https://arxiv.org/abs/2607.01418"
    type: paper
    year: 2026
    note: "A study of tens of thousands of Microsoft engineers during the company's rollout of two command-line coding agents. First use spread mainly through colleagues, and adopters merged about 24% more pull requests than estimated without the tools, over four months. Merged pull requests stand in for output, which the authors note is not delivered value. Microsoft owns GitHub, which sells Copilot CLI."
  - title: "Introducing the DORA AI Capabilities Model: 7 keys to succeeding in AI-assisted software development"
    author: "Kevin M. Storer, Derek DeBellis (Google Cloud DORA)"
    url: "https://cloud.google.com/blog/products/ai-machine-learning/introducing-doras-inaugural-ai-capabilities-model"
    type: article
    year: 2025
    note: "DORA's model of seven team and organisation capabilities that decide whether AI tools pay off, built from 78 interviews and a survey of almost 5,000 people. They include a clear AI policy, AI access to internal data, small batches, version control with rollback, a focus on users and a good internal platform. Without a focus on users, AI adoption was linked to worse team performance. Google sells AI coding tools."
  - title: How AI is transforming work at Anthropic
    author: "Anthropic (Saffron Huang, Bryan Seethor, Esin Durmus, Kunal Handa, Miles McCain, Michael Stern, Deep Ganguli)"
    url: "https://www.anthropic.com/research/how-ai-is-transforming-work-at-anthropic"
    type: article
    year: 2025
    note: "A survey of 132 Anthropic engineers and researchers, with 53 interviews and Claude Code usage data. Staff report using Claude in 60% of their work and a 50% productivity gain, and delegate mostly tasks that are easy to check or low stakes. The figures are self-reported, at a company that sells the tool."
  - title: My AI Adoption Journey
    author: Mitchell Hashimoto
    url: "https://mitchellh.com/writing/my-ai-adoption-journey"
    type: article
    year: 2026
    note: "An experienced engineer's path from sceptic to daily use of coding agents, in six steps. They include redoing his own commits with an agent to learn its limits, handing it end-of-day and easy tasks, and building tools that let it check its own work."
---
