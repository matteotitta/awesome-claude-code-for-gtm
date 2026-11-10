![awesome-claude-code-for-gtm cover](.github/cover.png)

# Awesome Claude Code for GTM [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Skills, agents, MCP servers, and workflows that put Claude Code to work on go-to-market problems.

Go-to-market work is mostly reading, writing, and moving structured data between systems, which is exactly what an agent harness is good at. This list collects the parts that already exist: skill libraries you can install, MCP servers that reach your CRM and enrichment stack, agent collections, and the research on whether any of it works.

Entries are alphabetical within each section. Star counts and dates were verified on 2026-11-08.

## Contents

- [How Claude Code Works for GTM](#how-claude-code-works-for-gtm)
- [Skill Libraries](#skill-libraries)
- [Marketing and GTM Skills](#marketing-and-gtm-skills)
- [Quickstarts](#quickstarts)
- [Agents and Subagents](#agents-and-subagents)
- [Plugins](#plugins)
- [MCP Servers for GTM](#mcp-servers-for-gtm)
- [GTM Tool Guides](#gtm-tool-guides)
- [Writing and Output Utilities](#writing-and-output-utilities)
- [Research](#research)
- [Courses and Communities](#courses-and-communities)

---

## How Claude Code Works for GTM

The mechanics of running GTM work inside an agent harness: what a skill is, how MCP connects an agent to your stack, and where the whole thing breaks down.

- [Agent Skills documentation](https://platform.claude.com/docs/en/agents-and-tools/agent-skills/overview) - Anthropic's reference for the skill format: the `SKILL.md` frontmatter contract, progressive disclosure of reference files, and how the model decides a skill is relevant. The frontmatter `description` field is the whole triggering mechanism, which is the single most common thing people get wrong.
- [AI-Powered GTM Workflows](https://www.genesysgrowth.com/blog/ai-powered-gtm-workflows-complete-guide) - Walks the full loop from research through positioning to shipped asset, treating the agent as an embedded operator rather than a copywriting box. Covers where the handoffs between research, strategy, and execution actually break, and why most GTM automation stalls at the point where a human has to re-explain context the agent already had.
- [AI Prompt Engineering for Marketers](https://www.genesysgrowth.com/blog/ai-prompt-engineering-for-marketers-complete-guide) - Prompt patterns aimed at marketing outputs specifically, where the failure mode is not a wrong answer but a plausible one in the wrong voice. Covers the difference between prompting for a draft and prompting for a decision.
- [Claude Code documentation](https://code.claude.com/docs/en/overview) - Official docs for the CLI: hooks, slash commands, subagents, settings, and MCP configuration. The hooks and settings pages matter most for GTM work, because that is where you enforce voice rules and spend gates that the model would otherwise talk itself out of.
- [Genesys Growth AI info](https://www.genesysgrowth.com/ai-info) - Structured summary of the practice, written to be machine-readable as much as human-readable.
- [How to build your AI GTM system](https://newsletter.genesysgrowth.com/p/how-to-build-your-ai-gtm-system) - Matteo Tittarelli and Kyle Poyar on the context layer most AI GTM stacks are missing. Lays out a four-tier system: a system of context (ICP, competitors, positioning, brand as a folder hierarchy), a system of skills that turn that context into research, strategy, and execution outputs, orchestration agents that fire skills on signals, and integrations that pull external data and push finished work to live destinations. The argument worth taking seriously is that compounding lives in the contextual spine and the folder structure, not in better prompts or more agents. Implementation runs on Claude Code, GitHub repos for team sharing, and MCP servers at both ends.
- [Model Context Protocol documentation](https://modelcontextprotocol.io/) - The open protocol that lets an agent call your CRM, enrichment provider, or analytics warehouse. Read the transports page before building anything; the difference between stdio and HTTP servers determines whether your GTM stack works in a cron job or only on your laptop.
- [The Genesys](https://newsletter.genesysgrowth.com/) - Matteo Tittarelli's newsletter on AI-native GTM practice: context systems, skills, and the tooling underneath them. Where the article above was published.
- [The GTM Engineer Pulse](https://gtmengineerschool.substack.com/) - Weekly newsletter from GTM Engineer School covering GTM engineering news and tooling.

## Skill Libraries

General-purpose skill collections. Most contain some GTM-adjacent material even when that is not their focus.

- [agentic-awesome-skills](https://github.com/sickn33/agentic-awesome-skills) - Installable library of 1,900+ agent skills spanning Claude Code, Cursor, Codex CLI, and Gemini. Breadth over depth, so treat it as a starting point to fork rather than a curated set. 43,394 stars, actively maintained.
- [alirezarezvani/claude-skills](https://github.com/alirezarezvani/claude-skills) - 345 skills bundled with 30+ agents and 70+ custom commands, packaged so the whole thing installs as a unit. Useful if you want a working configuration to strip down rather than a blank harness. 29,460 stars.
- [anthropics/skills](https://github.com/anthropics/skills) - Anthropic's own public skills repository and the reference implementation of the format. Read these first: `docx`, `pptx`, and `xlsx` show how a skill handles binary formats, and `skill-creator` is the canonical example of a skill that authors other skills. 188,943 stars.
- [borghei/Claude-Skills](https://github.com/borghei/Claude-Skills) - 343 skills and 76 expert agents organised by function, including marketing and PM tracks, alongside a Python stdlib of 835 tools. The `standards/` directory is the interesting part: it documents orchestration protocols rather than just shipping prompts. MIT with Commons Clause, so check the licence before commercial reuse. 1,068 stars.
- [google/skills](https://github.com/google/skills) - Google's own agent skills. The GTM-relevant part is the Google Ads API set, which walks through setting up and running the official Google Ads MCP server. 23,532 stars.
- [VoltAgent/awesome-agent-skills](https://github.com/VoltAgent/awesome-agent-skills) - 1,000+ skills gathered from official dev teams and the community, cross-compatible across harnesses. 36,966 stars.

## Marketing and GTM Skills

Skill libraries built specifically for marketing, sales, and revenue work.

- [aaron-marketing-skills](https://github.com/aaron-he-zhu/aaron-marketing-skills) - 120 marketing skills and 8 commands across seven disciplines including SEO/GEO and influencer work. 3,097 stars.
- [affiliate-skills](https://github.com/Affitor/affiliate-skills) - 50 skills for affiliate marketing: trend research, data-backed post generation, and creative production. Narrow but honest about its scope. 771 stars.
- [ai-business-skills](https://github.com/minhnv0807/ai-business-skills) - 63 bilingual marketing skills (Vietnamese and English), which is unusual in this space and useful if you run non-English GTM. 643 stars.
- [ai-marketing-claude](https://github.com/zubair-trabzada/ai-marketing-claude) - 15 marketing skills built around parallel subagents, including a website audit that fans out across pages concurrently. Worth reading for the fan-out pattern even if you do not use the skills. 2,872 stars.
- [aso-skills](https://github.com/appeeky/aso-skills) - App Store Optimization and app marketing skills, aimed at indie developers and app marketers. The only serious ASO-focused set here. 2,273 stars.
- [claude-blog](https://github.com/AgriciDaniel/claude-blog) - Blog skill suite with 30 sub-skills, 5 agents, and a gated delivery contract that dual-optimises for search and AI citation. The gate structure is the transferable idea. 2,672 stars.
- [claude-seo](https://github.com/AgriciDaniel/claude-seo) - Full SEO skill suite with subagents for technical, schema, GEO, local, and backlink audits. Same author as claude-blog, and the larger of the two. MIT. 27,322 stars.
- [coldoutboundskills](https://github.com/growthenginenowoslawski/coldoutboundskills) - Cold email and outbound skills: grade a campaign, build a list, check deliverability. MIT. 804 stars.
- [explorium-ai/gtm-skills](https://github.com/explorium-ai/gtm-skills) - GTM skills for Claude and Codex from Explorium, a B2B data vendor, so expect them to lean on its data. MIT. 355 stars.
- [founder-skills](https://github.com/firatcand/founder-skills) - Skills for founders building B2B SaaS, covering GTM alongside product, engineering, and design. Small and opinionated. 44 stars.
- [genesys-skills](https://github.com/matteotitta/genesys-skills) - Product marketing and GTM skills used in live consulting engagements: positioning, messaging, competitor research, ICP work, and content. Maintained by the author of this list and shared weekly through the Genesys newsletter. 48 stars.
- [goose-skills](https://github.com/gooseworks-ai/goose-skills) - Growth and GTM skills plus data APIs for running ads, social, and content from Claude Code, Codex, or Cursor. MIT. 1,296 stars.
- [gtm-engineer-skills](https://github.com/onvoyage-ai/gtm-engineer-skills) - Scores a website for answer-engine visibility across 16 foundational checks and 6 intelligence dimensions. One of the few skills here aimed at AEO measurement rather than content generation. 1,357 stars.
- [gtm-skills/gtm](https://github.com/gtm-skills/gtm) - GTM toolkit for agents covering research, intel, outreach, and CRM. Active again, last pushed October 2026. 189 stars.
- [makerskills](https://github.com/coreyhaines31/makerskills) - Skills for the solo operator's craft: decisions, research, second-brain, scenario modeling, and meta-skills for authoring further skills. MIT. 893 stars.
- [marketing-skills](https://github.com/kostja94/marketing-skills) - 160+ open-source skills across SEO, content, social, and influencer marketing. 1,088 stars.
- [marketingskills](https://github.com/coreyhaines31/marketingskills) - The most substantial marketing skill library here, covering CRO, copywriting, SEO, analytics, and growth engineering. MIT-licensed and actively maintained, which makes it the safest base to fork for client work. 59,108 stars.
- [NotFair](https://github.com/nowork-studio/notfair-plugin) - Open-source skills for SEO, GEO, Google Ads, and Meta Ads. The only set here that covers paid and organic in one place. 4,122 stars.
- [openclaudia-skills](https://github.com/OpenClaudia/openclaudia-skills) - Marketing skills spanning SEO, content, email, ads, analytics, and growth. Small enough to read end to end. Note the repo description and readme disagree on the skill count. 731 stars.
- [pm-skills](https://github.com/phuryn/pm-skills) - Product management skills marketplace with 100+ skills, commands, and plugins across discovery, strategy, execution, launch, and growth. The launch and growth tracks are the GTM-relevant ones. 27,759 stars.
- [rampstackco/claude-skills](https://github.com/rampstackco/claude-skills) - Stack-agnostic skills covering the full website lifecycle: brand, design, content, SEO, development, ops, and growth. 1,046 stars.
- [seo-skill-bench](https://github.com/aleclindz/seo-skill-bench) - Open benchmark that runs SEO skills headlessly against fixture sites and scores them. The only attempt here at measuring whether these skills actually work, which makes it more interesting than its star count suggests. 43 stars.
- [wholesaler-claude-skills](https://github.com/miron-tech/wholesaler-claude-skills) - Six skills for real estate wholesalers covering property recon, conversation coaching, and creative financing. Included as a worked example of vertical-specific GTM skills. 53 stars.

## Quickstarts

- [claude-code-tips](https://github.com/ykdojo/claude-code-tips) - 40+ tips from basics to advanced, including a custom status line setup. Not a scaffold, but the fastest way to stop making beginner mistakes. 10,321 stars.
- [repo-structure-agency](https://github.com/matteotitta/repo-structure-agency) - The same setup for agencies and consultants: one context folder per client, so Claude never mixes one client's positioning into another's work. Ships the 11 context skills and a filled-in example client. Maintained by the author of this list. 1 star.
- [repo-structure-in-house](https://github.com/matteotitta/repo-structure-in-house) - Free Claude Code workspace for one company's marketing: a `context/` folder every skill reads first, an `outputs/` folder per lane, five context skills and a worked example company. Aimed at marketers who have not run a CLI harness before. Formerly `claude-code-marketing-quickstart`. Maintained by the author of this list. 70 stars.

## Agents and Subagents

- [VoltAgent/awesome-claude-code-subagents](https://github.com/VoltAgent/awesome-claude-code-subagents) - 100+ specialised subagents across a wide range of use cases. The value for GTM work is the dispatch patterns rather than the agents themselves. 26,409 stars.
- [wshobson/agents](https://github.com/wshobson/agents) - Multi-harness agentic plugin marketplace spanning Claude Code, Codex CLI, Cursor, and Copilot. The largest agent collection here and the most cross-compatible. 42,295 stars.

## Plugins

- [Akii: SEO & AI Search Optimizer](https://github.com/akii-technologies-ltd/akii-seo-ai-search-optimizer) - A free MIT plugin for SEO teams using Claude Code. Audit sites, plan content, and build schema in the terminal. Estimate AI search visibility from public web signals or a connected Ahrefs Brand Radar account.
- [claude-hud](https://github.com/jarrodwatts/claude-hud) - Shows context usage, active tools, running agents, and todo state while Claude Code works. Context usage is the number that matters on long GTM research runs, and this is the cheapest way to see it. 29,134 stars.
- [claude-plugins-official](https://github.com/anthropics/claude-plugins-official) - Anthropic's managed directory of vetted Claude Code plugins. Start here before installing anything from a random marketplace. 46,386 stars.
- [clay-run/agent-plugins](https://github.com/clay-run/agent-plugins) - Clay's plugin for Claude Code, Codex, and Cursor: skills, MCP tools, and the `clay` CLI for search, enrichment, and table queries. The org's site is clay.com, though GitHub doesn't mark it verified. No licence declared. 145 stars.
- [codex-plugin-cc](https://github.com/openai/codex-plugin-cc) - OpenAI's plugin for calling Codex from inside Claude Code, for review or delegation. Notable mostly as evidence that the harnesses are converging. 34,970 stars.
- [compound-engineering-plugin](https://github.com/EveryInc/compound-engineering-plugin) - Every's plugin built around the idea that each shipped change should make the next one cheaper. The product-pulse and ship-learnings patterns port cleanly to GTM. 25,977 stars.
- [knowledge-work-plugins](https://github.com/anthropics/knowledge-work-plugins) - Anthropic's open plugins for Claude Cowork and Claude Code. The `marketing` plugin covers campaign plans, SEO audits, and email sequences; the `sales` plugin covers call prep, deal and pipeline review, and forecasting. Also carries partner plugins from Apollo and Common Room. Apache-2.0. 35,148 stars.

## MCP Servers for GTM

Servers that connect an agent to the GTM stack. This is a shortlist; [awesome-gtm-mcp-servers](https://github.com/matteotitta/awesome-gtm-mcp-servers) is the full catalogue with per-vendor coverage and the gaps stated explicitly.

Two things worth knowing before you wire anything up. **Most GTM vendors now run an official server**: Google Ads, Meta Ads, Semrush, Mixpanel, Clay, Hunter, Pipedrive, and Close all do, which this list said in July they didn't. Klaviyo has one too. **LinkedIn Ads** and **Search Console** are the two big surfaces still community-only, so vet those hardest before you hand one a budget. And **vendors are migrating to hosted servers**: Ahrefs, PostHog, and Hunter archived their local repos in favour of remote endpoints, Salesforce retired its local server, and HubSpot, Apollo, and Attio are hosted-first with no meaningful public repo. A repo-only view of this space is already wrong.

- [apify/apify-mcp-server](https://github.com/apify/apify-mcp-server) - Apify's official server, and the highest-starred MCP server in the GTM stack, exposing thousands of ready-made scrapers to an agent, covering social, search, maps, and e-commerce extraction. Supports OAuth so hosted clients can connect by URL alone. Formerly `actors-mcp-server`; publish this path. 15,218 stars.
- [exa-labs/exa-mcp-server](https://github.com/exa-labs/exa-mcp-server) - Exa's official server for neural web search and crawling. 5,216 stars.
- [firecrawl/firecrawl-mcp-server](https://github.com/firecrawl/firecrawl-mcp-server) - Firecrawl's official server for scraping, crawling, search, and structured extraction. Note the org rename: `mendableai/firecrawl-mcp-server` redirects here, and most lists still cite the stale path. 7,776 stars.
- [forcedotcom/mcp-hosted](https://github.com/forcedotcom/mcp-hosted) - Salesforce's official hosted MCP servers. The local `salesforcecli/mcp` server reached end of life on 2 November 2026 and is archived; Salesforce now ships its developer tooling as skills in [forcedotcom/sf-skills](https://github.com/forcedotcom/sf-skills). Apache-2.0. 136 stars.
- [googleads/google-ads-mcp](https://github.com/googleads/google-ads-mcp) - Google's official Google Ads server: reporting through GAQL, plus a few asset and label writes behind a confirm step. Google's docs still call it read-only, so check the repo for the current tools. Apache-2.0. 1,128 stars.
- [gtm-mcp](https://github.com/impecablemee/gtm-mcp) - Open-source B2B cold outreach pipeline rather than a vendor server. One `/launch` command finds companies through Apollo, classifies them, and drafts outreach. The most complete open GTM pipeline here, though small and last pushed April 2026. 70 stars.
- [HubSpot MCP Server](https://developers.hubspot.com/ai-tools/mcp) - HubSpot's official hosted server at `mcp.hubspot.com`, with read and write access to CRM objects and engagements. Hosted only. Ignore `HubSpot/mcp-server` on GitHub: it exists under the real org but is an empty placeholder.
- [mcp-gsc](https://github.com/AminForou/mcp-gsc) - The de-facto Search Console server, since Google publishes none. 2,142 stars.
- [modelcontextprotocol/registry](https://github.com/modelcontextprotocol/registry) - The official registry service, and where `modelcontextprotocol/servers` now sends you for third-party servers. 7,453 stars.
- [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers) - The canonical reference servers, maintained by the MCP steering group. Worth knowing it no longer carries a third-party integrations list. 91,859 stars.
- [twenty-crm-mcp-server](https://github.com/mhenry3164/twenty-crm-mcp-server) - MCP server for Twenty, the open-source CRM. The pairing matters: an open CRM plus an open server is the only fully inspectable CRM-agent stack here. 108 stars.

## GTM Tool Guides

Guides to the tools the servers above connect to, covering what each one is for and where it stops. These are the maintainer's own write-ups; see [contributing.md](contributing.md) for the disclosure.

- [Apollo](https://www.genesysgrowth.com/tools/apollo-io) - Contact database and sequencer. Note this is Apollo.io, not the Apollo GraphQL project, which publishes a similarly-named MCP server and is unrelated to GTM work.
- [Attio](https://www.genesysgrowth.com/tools/attio) - Modern CRM with a strong API, which makes it the easiest CRM to drive from an agent.
- [Clay](https://www.genesysgrowth.com/tools/clay) - Enrichment and waterfall orchestration across many providers.
- [Common Room](https://www.genesysgrowth.com/tools/common-room) - Signal capture across community, product usage, and job changes.
- [Gong](https://www.genesysgrowth.com/tools/gong) - Call recording and revenue intelligence; the source of the transcripts most win-loss work runs on.
- [HubSpot](https://www.genesysgrowth.com/tools/hubspot) - CRM and marketing automation.
- [lemlist](https://www.genesysgrowth.com/tools/lemlist) - Outbound sequencing across email and LinkedIn.

## Writing and Output Utilities

The parts that stop agent output from reading like agent output.

- [caveman](https://github.com/JuliusBrussee/caveman) - Cuts roughly 65% of tokens by stripping prose to essentials. A blunt instrument, but the token maths on long research runs is real. 118,202 stars.
- [humanizer](https://github.com/blader/humanizer) - Removes the tells of AI-generated writing. The most directly useful utility here for anyone publishing agent-drafted copy under their own name. 66,065 stars.

## Research

Evidence on whether any of this changes outcomes. Thin, and worth being honest about that.

- [GEO: Generative Engine Optimization](https://arxiv.org/abs/2311.09735) - Aggarwal et al. introduced systematic testing of generative-engine interventions and the benchmark most later work cites.
- [What Drives Citations in Production Large Language Models?](https://discoveredlabs.com/research/what-drives-ai-citations) - Discovered Labs' observational study of roughly 2 million citations across ChatGPT, Claude, Google AI, and Gemini, joined to 10,000 crawled pages. Finds prompt-content alignment to be the dominant page-level predictor (β = +0.37) and, more usefully, finds that the standard AEO checklist of FAQ blocks, structured data, and Core Web Vitals collapses toward zero once domain fixed effects are applied. Read the limitations section: it is observational, scoped to 19 B2B SaaS workspaces, and cannot establish causation.
- [Ranking Manipulation for Conversational Search Engines](https://arxiv.org/abs/2406.03589) - Kumar and Lakkaraju show that strategic lexical insertion measurably shifts LLM recommendation probability, which is the uncomfortable counterpart to any content-alignment finding.

## Courses and Communities

- [Clay University](https://university.clay.com/) - Free training on Clay specifically, and the best on-ramp to enrichment waterfalls.
- [GTM Engineer School](https://www.gtm-engineer-school.com/) - Cohort-based course teaching GTM operators to build AI-driven workflows, structured around a find-enrich-transform-export framework. Co-founded by the author of this list.
- [RevOps Co-op](https://www.revopscoop.com/) - Community for revenue operations practitioners, and the most active general RevOps forum.

## Related Lists

- [awesome-aeo-seo](https://github.com/discoveredlabs/awesome-aeo-seo) - Answer engine optimisation resources from the team behind the citation-drivers study above.
- [awesome-claude-code](https://github.com/hesreallyhim/awesome-claude-code) - The general Claude Code list, and the best starting point for anything not GTM-specific. 57,502 stars.
- [awesome-generative-engine-optimization](https://github.com/amplifying-ai/awesome-generative-engine-optimization) - The largest GEO list. Last pushed April 2026. 539 stars.
- [awesome-gtm-engineering](https://github.com/marketinguys/awesome-gtm-engineering) - GTM engineering tools and resources. One commit, unmaintained since June 2025, but still a useful snapshot of the tool landscape. 179 stars.
- [awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) - The comprehensive MCP server list. 97,450 stars.
