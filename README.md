# Adesh Gairola

[adeshgairola.com](https://adeshgairola.com) · [raxitlabs.com](https://raxitlabs.com) · [LinkedIn](https://www.linkedin.com/in/adeshgairola/) · [@adeshgairola](https://x.com/adeshgairola) · hi@adeshgairola.com

**Security is a habit, not a project.**

I do security. Network first at Cisco, then cloud for eight years at AWS and now AI, though the thing that keeps pulling me back is the same one every time.. somebody hands a system more power than anyone has thought carefully about, and then we all find out what happens. Agents are just the current version of that. They act on their own, they call tools, they spawn other agents, and the identity and authorisation models we built for humans and service accounts do not really have an answer for it yet. I think that gap is the interesting problem of the next few years and I could be wrong about the shape of it, so I build things and write them up in public while I am still working it out.

## What I am building

[raxIT Labs](https://raxitlabs.com). An AI governance and security platform where every agent tool call has to clear a policy decision before it runs. Cedar underneath, a sidecar doing the enforcement so customer data never leaves the customer's environment and [Python and TypeScript clients](https://pypi.org/project/raxit/) that instrument 17 agent frameworks. Multi-tenant across AWS and GCP, four regions, data residency per tenant. Docs at [docs.raxit.ai](https://docs.raxit.ai).

The part I like most is the free bit. The [Knowledge Base](https://raxitlabs.com/kb) is 4,300+ AI incidents, threats, controls and regulatory clauses, kept current, no signup. It grounds the platform's policy library and it is genuinely useful on its own.

## Open source

**[agent-security-review](https://github.com/raxITlabs/agent-security-review)** ast-grep rule pack for scanning AI agent code, organised around Scope, Sign and Stop. Grounded in Meta's Rule of Two, CaMeL, MAESTRO and the lethal trifecta. Rules pull live so the checks stay current.

**[dogwood](https://github.com/raxITlabs/dogwood)** A governance language for agents and their tools. Cedar policies plus temporal conditions (`since`, `formerly`, `once`) so a policy can look back over what the agent actually did in the last hour, not just what it is asking for now. Rust.

**[mcp-oauth-sample](https://github.com/raxITlabs/mcp-oauth-sample)** OAuth 2.1 authorisation server and MCP server running serverless on Vercel, with real-time analytics and threat detection. A reference for wiring auth into MCP properly.

**[gpt-oss-safeguard-testing](https://github.com/raxITlabs/gpt-oss-safeguard-testing)** Testing framework for the GPT-OSS-Safeguard model. 1,800+ test cases across 15 policy categories, including data exfiltration, unauthorised actions and risk tiering, scored on attack success rate, precision and recall.

**[GrayZoneBench](https://github.com/raxITlabs/GrayZoneBench)** Benchmark for how models handle gray-zone requests, the ones that are neither clearly fine nor clearly refusable. CLI for running it, dashboard for reading the results.

**[nla-audit](https://github.com/raxITlabs/nla-audit)** An experiment in monitoring what an LLM is thinking, reading activation-level thoughts through Anthropic's Natural Language Autoencoder.

**[DirePhish](https://github.com/raxITlabs/DirePhish)** Incident response tabletop simulation with a multi-agent swarm running the exercise.

**[securing-ralph-loop](https://github.com/agairola/securing-ralph-loop)** Security checks in the path of an autonomous agent loop. Scan before commit, fix iteratively, escalate when the agent gets stuck. Not bulletproof, and it was never meant to be. It is a thought exercise in whether traditional DevSecOps practices can be handed to an agent and still leave it functional.

**[skills](https://github.com/raxITlabs/skills)** Open agent skills for AI security. First one is model-scanner, which scans model files for malicious pickles and maps what it finds to the ISM, the EU AI Act, OWASP LLM Top 10, MITRE ATLAS and NIST AI RMF.

## Writing and talks

- [Kill the God Agent](https://raxitlabs.com/blogs/kill-the-god-agent), from AI Engineer Melbourne 2026. Breaking one monolithic agent into purpose-built ones, with capability scoping, real identity and a deterministic policy gate on every action.
- [Agent identity in four layers](https://raxitlabs.com/blogs/agent-identity-four-layers).
- [Australia's new AI framework](https://raxitlabs.com/blogs/npc-nation-australia-ai-framework), a working read of what it actually asks for.
- More at [raxitlabs.com/blogs](https://raxitlabs.com/blogs).

## Before this

**raxIT Labs**, founder and chief technology officer. Sydney, 2025 to now.

**AWS Professional Services**, senior security consultant and AI security practice manager for Australia and New Zealand, 2023 to 2025. Built the region's AI security practice from nothing: the review methodology, the delivery playbook, the commercial packaging. Shipped the guardrail layer behind the first internal generative AI deployments at two of Australia's major banks. Co-authored the reference threat model for AI and agentic applications, STRIDE and MAESTRO, released publicly in AWS Threat Composer.

**AWS**, security consultant and cloud security architect, 2017 to 2023. PCI DSS, SOC 2 and APRA-regulated workload migrations for Australian and New Zealand financial services. Posture management at platform scale, AWS Config platform rules, Security Hub and OCSF.

**Cisco**, team lead for TAC VPN and network security across Asia Pacific, 2012 to 2017. Thirty engineers, the full VPN portfolio, carrier severity-one escalations.

Contributing member of the OWASP LLM Top 10 since v0.5 and the agentic AI security guidelines. I run AI Security Circle Sydney, a homegrown vendor-neutral practitioner community. CCIE Security, B.Tech computer science.

## Say hi

Happy to talk about agent security, policy enforcement, or whatever cloud security thing is currently bugging you. [hi@adeshgairola.com](mailto:hi@adeshgairola.com) or [LinkedIn](https://www.linkedin.com/in/adeshgairola/).

- A
