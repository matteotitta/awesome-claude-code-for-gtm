# GTM tools that work with Claude Code

The directory behind [Awesome Claude Code for GTM](../readme.md): every tool on the GTM Developer Tools map, plus the other GTM apps that ship an MCP server or a CLI, so Claude Code can drive them directly.

Built from [Adam's GTM Report](https://posts.adamgtm.com/) by Adam Schoenfeld, using his [GTM Developer Tools map](https://adamgtm.com/gtm-dev) and [GTM Index](https://adamgtm.com/index). The descriptions are ours. For his agent-readiness and share-of-voice scores, see the map itself.

`MCP` means the vendor ships an MCP server. `CLI` means it ships a command-line tool. Tools with neither are reachable by API. Entries are alphabetical within each section. Every link was checked on 2026-11-11; some vendor sites block automated checks, and a sample of those was opened by hand.

## Contents

**The GTM Developer Tools map**

- [Data and signals](#data-and-signals) (57)
- [Web search and scraping](#web-search-and-scraping) (38)
- [Browsers and computer use](#browsers-and-computer-use) (20)
- [Communication](#communication) (36)
- [Agents and agent builders](#agents-and-agent-builders) (54)
- [Workflows and orchestration](#workflows-and-orchestration) (16)
- [Context and memory](#context-and-memory) (34)
- [Connectors and MCP](#connectors-and-mcp) (9)
- [Run and deploy](#run-and-deploy) (32)
- [GTM platforms going headless](#gtm-platforms-going-headless) (120)

**More GTM tools with an MCP server or CLI**

- [CRM](#crm) (7)
- [Prospecting and outbound](#prospecting-and-outbound) (22)
- [Sales and conversation intelligence](#sales-and-conversation-intelligence) (41)
- [Customer success and support](#customer-success-and-support) (8)
- [Marketing execution](#marketing-execution) (34)
- [Advertising](#advertising) (25)
- [AEO and AI search visibility](#aeo-and-ai-search-visibility) (14)
- [Website and inbound](#website-and-inbound) (20)
- [Creative and content](#creative-and-content) (17)
- [Data and intelligence](#data-and-intelligence) (30)
- [GTM infrastructure](#gtm-infrastructure) (14)
- [Other GTM tools](#other-gtm-tools) (8)

---

## Data and signals

Company, people, intent, and event data an agent can pull into a list or a CRM record.

- [Adapt](https://www.adapt.io) - Lookup service with about 61 million business contacts for building sales and marketing lists.
- [AI Ark](https://ai-ark.com) - Finds lookalike companies and people across a B2B database using meaning-based search, aimed at GTM engineers. `MCP` ([MCP docs](https://docs.ai-ark.com/mcp))
- [Anymailfinder](https://anymailfinder.com) - Email finder for outbound teams that only hands back addresses it has checked. Acquired.
- [Apollo.io](https://www.apollo.io) - Contact database plus outreach tool whose assistant actually carries out prospecting steps for sales teams. `MCP` `CLI` ([MCP docs](https://docs.apollo.io/docs/apollo-mcp))
- [AroundDeal](https://arounddeal.com) - Prospect data on people and companies, strongest in Asia-Pacific, for teams prospecting in the region.
- [Autobound](https://autobound.ai) - Writes tailored outreach drafts for reps using signals pulled from the tools they already use. `MCP` ([MCP docs](https://www.autobound.ai/integrations/mcp))
- [BetterContact](https://bettercontact.rocks) - Tries several data vendors in a row and cross-checks results to find emails and mobiles.
- [BlitzAPI](https://blitz-api.ai) - Fetches people and company info from LinkedIn through one endpoint for prospecting tools. `MCP` ([MCP docs](https://docs.blitz-api.ai/guide/integrations/MCP))
- [Bombora](https://bombora.com) - Intent data from a shared publisher network showing which companies are researching a topic right now.
- [Bouncer](https://usebouncer.com) - Checks whether email addresses are real before a cold campaign goes out.
- [BuiltWith](https://builtwith.com) - Reveals the software behind any website, so sellers can target companies running a particular tool. `MCP` `CLI` ([MCP docs](https://builtwith.com/mcp))
- [Captain Data](https://captaindata.com) - GTM engineers pull data from LinkedIn and other sites straight into their sales tools. `MCP` ([MCP docs](https://www.captaindata.com/mcp))
- [Clay](https://clay.com) - Build lead lists in a grid where each column fetches vendor data or runs AI research. `MCP` `CLI` ([MCP docs](https://www.clay.com/mcp))
- [Common Room](https://commonroom.io) - Reads Discord, GitHub and social chatter for buying signals and picks accounts. Now part of Zoom. `MCP` `CLI` ([MCP docs](https://www.commonroom.io/docs/using-common-room/mcp-server/))
- [Coresignal](https://coresignal.com) - Fresh records on firms, workers, and job ads, searchable in plain English for enrichment and research. `MCP` ([MCP docs](https://docs.coresignal.com/mcp/coresignal-mcp))
- [Crustdata](https://crustdata.com) - Fresh data on people and companies that agents and GTM engineers can pull into workflows. `MCP` ([MCP docs](https://mcp.crustdata.com))
- [CUFinder](https://cufinder.io) - Fills in missing company and people data on lead lists for sales teams. `MCP` ([MCP docs](https://apidoc.cufinder.io/mcp/introduction))
- [Datagma](https://datagma.com) - Contact enrichment source with deep European coverage that GTM engineers add to their lookup waterfalls.
- [Deepline](https://deepline.com) - GTM engineers plug data vendors into coding agents and keep each workflow as plain TypeScript. `MCP` `CLI` ([MCP docs](https://deepline.com/docs/mcp/setup))
- [Dropcontact](https://dropcontact.com) - Finds and fills in emails on the fly without keeping a stored database, staying GDPR-safe. `MCP`
- [Enrich](https://www.enrich.so) - Reverse email lookups, verified contact details, and company facts that sales and GTM engineers can query. `MCP` ([MCP docs](https://www.enrich.so/mcp))
- [Enrow](https://enrow.io) - Email finder tuned to return addresses that actually land in inboxes, not just more matches. `MCP` `CLI`
- [Explorium](https://explorium.ai) - Business data from 50+ providers in one feed, built for GTM engineers wiring up agents. `MCP` ([MCP docs](https://www.explorium.ai/mcp/))
- [Findymail](https://findymail.com) - Email finder and checker that still works when a domain is catch-all, so lists bounce less.
- [FullContact](https://fullcontact.com) - Identity matching that ties a person's various emails, phones, and devices into one customer record. Acquired. `MCP` ([MCP docs](https://www.fullcontact.com/mcp/))
- [FullEnrich](https://fullenrich.com) - Checks 20+ data vendors in turn to find working emails and mobile numbers for outbound teams. `MCP` `CLI` ([MCP docs](https://fullenrich.com/mcp))
- [G2](https://www.g2.com) - Software review site whose buyer browsing data is sold to vendors as intent signals. `MCP`
- [GetProspect](https://getprospect.com) - Email finder for SDRs with a simple CRM to keep the prospects it uncovers.
- [GTM.AI](https://gtm.ai/) - ZoomInfo's connection that lets AI agents look up its company and contact data live. `MCP` `CLI` ([MCP docs](https://gtm.ai/docs/mcp))
- [Harmonic](https://harmonic.ai) - Startup database for investors, with an agent that maps markets using funding and hiring signals.
- [HG Insights](https://hginsights.com) - Account data on what technology big companies use, spend on, and research. `MCP`
- [Icypeas](https://icypeas.com) - Finds and checks work email addresses, often used as one step in an enrichment chain. `MCP` ([MCP docs](https://www.icypeas.com/integrations/mcp))
- [Kickbox](https://kickbox.com) - Confirms an email address is real and can receive mail before you hit send. Acquired.
- [LeadMagic](https://leadmagic.io) - Pulls checked emails and mobiles for GTM teams, billing only for results that work. `MCP` `CLI` ([MCP docs](https://leadmagic.io/solutions/mcp))
- [Limadata](https://limadata.com/) - Developer data service covering people, companies and buying signals, with alerts on job moves and funding. `MCP` ([MCP docs](https://limadata.com/mcp))
- [MillionVerifier](https://millionverifier.com) - Low-cost tool that checks big email lists for bad addresses before cold sending.
- [MoltSets](https://moltsets.com) - Contact data source for agents that looks up people and finds and checks emails and phones. `MCP` `CLI` ([MCP docs](https://developer.moltsets.com/integrations/moltsets-mcp))
- [NeverBounce](https://neverbounce.com) - Checks email addresses one by one or in bulk so fewer messages bounce. Acquired.
- [Nymeria](https://nymeria.io) - Recruiters and sellers look up a LinkedIn profile and get checked personal emails and phone numbers.
- [Ocean.io](https://ocean.io) - Studies your won deals to find similar companies, ranks them and researches each one. `MCP` ([MCP docs](https://app.ocean.io/docs/getting-started/mcp))
- [People Data Labs](https://peopledatalabs.com) - Huge database of people and company profiles for developers building enrichment features. `MCP` ([MCP docs](https://peopledatalabs.com/docs/mcp))
- [PredictLeads](https://predictleads.com) - Tracks company job openings, tech stack shifts and new funding as signals for enrichment workflows. `MCP` ([MCP docs](https://docs.predictleads.com/mcp))
- [Prospeo](https://prospeo.io) - Recruiters and sellers use it to pull checked emails and mobiles from LinkedIn pages. `MCP`
- [RevenueBase](https://revenuebase.ai) - Database of companies and the people who work there, used to build outbound prospect lists.
- [RocketReach](https://rocketreach.co) - Give it a name and employer and it returns that person's work email or phone. `MCP` ([MCP docs](https://docs.rocketreach.co/reference/mcp))
- [Scalelist](https://scalelist.com) - Chrome add-on that pulls Sales Navigator lists out with checked emails and direct dials for SDRs. `MCP`
- [Scrapin](https://scrapin.io) - Real-time LinkedIn people and company lookups that developers plug into their own products.
- [Scrubby](https://scrubby.io) - Tells you whether catch-all and other risky addresses will bounce before outbound emails go out.
- [Store Leads](https://storeleads.app) - Database of online stores showing which platforms and apps each one uses, for ecommerce sellers. `MCP`
- [The Swarm](https://theswarm.com) - Maps who your team knows to find warm introductions into target accounts. `MCP` ([MCP docs](https://www.theswarm.com/integrations/mcp))
- [TheirStack](https://theirstack.com) - Reads company job ads to reveal what software they use and what roles they hire. `MCP` ([MCP docs](https://theirstack.com/en/docs/mcp))
- [Twain](https://www.twain.ai) - Digs into each account in real time, then writes sourced one-to-one emails your sequencer sends. `MCP` ([MCP docs](https://intercom.help/usetwain/en/articles/14816810-what-is-mcp-and-how-does-it-work-with-twain))
- [Unipile](https://unipile.com) - Single connection that outreach tools use to reach LinkedIn, email, and chat apps. `MCP`
- [Verifalia](https://verifalia.com) - Live email checking that catches typos, throwaway domains, and likely bounces before you hit send.
- [Wappalyzer](https://www.wappalyzer.com) - Looks up which website builder, analytics, and shop software any company's site runs. `MCP` ([MCP docs](https://www.wappalyzer.com/docs/integrations/mcp/))
- [ZeroBounce](https://zerobounce.net) - Checks email lists for bad or risky addresses so your sends keep a good reputation. `MCP`
- [ZoomInfo](https://zoominfo.com) - B2B database of checked contacts, company records and buying intent for sales and RevOps teams. `MCP` `CLI` ([MCP docs](https://gtm.ai/docs/mcp))

## Web search and scraping

Search and extraction for the open web: the research layer under most GTM agents.

- [Apify](https://apify.com) - Store of ready-made scrapers and crawlers you can run in the cloud to pull web data. `MCP` `CLI` ([MCP docs](https://docs.apify.com/integrations/mcp))
- [Brave Search API](https://brave.com) - Web search results from Brave's own index of billions of pages, not resold from Google. `MCP`
- [Bright Data](https://brightdata.com) - Rotating home-IP proxies, scrapers, and ready-made datasets that help agents get past bot blocks. `MCP` `CLI`
- [Browse AI](browse.ai) - Point-and-click web scraper that turns pages into data feeds and adjusts when layouts change.
- [Context.dev](https://www.context.dev/) - Web data service for agents that searches sites, extracts fields, and deals with proxies and rendering. `MCP` `CLI` ([MCP docs](https://docs.context.dev/install-mcp))
- [Crawlbase](https://crawlbase.com) - Scraping and crawling service with built-in proxies so developers' requests don't get blocked. `MCP` ([MCP docs](https://crawlbase.com/mcp))
- [DataForSEO](https://dataforseo.com) - Search ranking and keyword data you pay for per request, used to build SEO tools. `MCP`
- [Decodo](https://decodo.com) - Residential, mobile, and datacenter proxies, along with scraping tools that get past CAPTCHAs, for data teams. `MCP` `CLI` ([MCP docs](https://help.decodo.com/docs/mcp))
- [Diffbot](https://diffbot.com) - Reads web pages and organizes what it finds into a huge searchable knowledge graph. `MCP`
- [Exa.ai](https://exa.ai) - Web search made for AI agents and language models, returning results machines can read easily. `MCP` ([MCP docs](https://exa.ai/mcp))
- [Firecrawl](https://firecrawl.dev) - Developers fetch any web page as tidy markdown ready for AI agents, proxies included. `MCP` `CLI`
- [Hexomatic](https://hexomatic.com) - No-code web scraping and task automation for teams with no engineers on hand.
- [Import.io](https://import.io) - Turns websites into clean datasets for large companies' research and data teams. Acquired.
- [Jina](https://jina.ai) - Turns any web page into markdown and pulls fresh search results for language models. Acquired. `MCP` `CLI` ([MCP docs](https://mcp.jina.ai))
- [Linkup](https://linkup.so) - Web search service that answers from vetted sources with citations, for grounding AI agents. `MCP` `CLI` ([MCP docs](https://docs.linkup.so/pages/integrations/mcp/mcp))
- [NetNut](https://netnut.io) - Residential IPs for developers who scrape at scale, so requests look like ordinary home users. Acquired.
- [Nimble](https://nimbleway.com) - Turns pages from any site into clean structured data that analysts and developers can request. `MCP` `CLI` ([MCP docs](https://www.nimbleway.com/mcp))
- [Octoparse](https://octoparse.com) - No-code scraper where you click on parts of a page to pull out the data. `MCP` `CLI` ([MCP docs](https://www.octoparse.com/mcp))
- [Olostep](https://olostep.com) - Crawls websites and hands back clean data ready to feed into language models. `MCP` `CLI`
- [Oxylabs](https://oxylabs.io) - Proxy network and scraping tools for collecting public web data at large scale. `MCP` `CLI`
- [Parallel](https://parallel.ai) - Gives AI agents a research layer for searching the web and pulling structured, model-ready data. `MCP` `CLI`
- [Perplexity Sonar API](https://docs.perplexity.ai) - Perplexity's live web search for developers, returning answers with source links instead of stale model memory. `MCP` ([MCP docs](https://docs.perplexity.ai/mcp))
- [Scrape.do](https://scrape.do) - Developers scrape past anti-bot walls and pay only for requests that succeed.
- [ScrapeGraphAI](https://scrapegraphai.com) - Ask for page data in plain English and get clean, structured fields back for your pipeline. `CLI`
- [ScrapeOps](https://scrapeops.io) - One endpoint in front of 20+ proxy providers, with tools to schedule, parse, and watch scrapers. `MCP` ([MCP docs](https://scrapeops.io/docs/mcp/overview/))
- [ScraperAPI](https://scraperapi.com) - Developers send a URL and get the page back, with proxies and script loading handled. `MCP` `CLI`
- [Scrapfly](https://scrapfly.io) - Scraping service with a cloud browser and anti-bot handling that agents and developers can call directly. `MCP` `CLI` ([MCP docs](https://scrapfly.io/docs/mcp/getting-started))
- [ScrapingBee](https://scrapingbee.com) - Scraping service that handles the proxy and headless browser work and returns plain HTML. Acquired. `MCP` `CLI` ([MCP docs](https://mcp.scrapingbee.com))
- [Scrapingdog](https://scrapingdog.com) - Low-cost scraping service that handles proxy rotation and page rendering so developers don't get blocked.
- [SearchApi](https://www.searchapi.io) - Developers pull live search results from Google, YouTube, Maps, and more as clean structured data. `MCP` ([MCP docs](https://www.searchapi.io/integrations/mcp))
- [SerpApi](https://serpapi.com) - Returns results from 100+ search engines, Google included, as tidy JSON for developers. `MCP` `CLI` ([MCP docs](https://serpapi.com/integrations/mcp))
- [Serper](https://serper.dev) - Google search results returned fast to developers, paid per use with no contract.
- [Spider](https://spider.cloud) - Fast crawler that turns web pages into tidy markdown ready for LLM apps. `MCP` ([MCP docs](https://spider.cloud/docs/integrations/mcp/))
- [Tavily](https://www.tavily.com/) - Web search for agents that returns results with sources ready to cite. Now part of Nebius. `MCP` `CLI` ([MCP docs](https://docs.tavily.com/documentation/mcp))
- [The Hog](https://thehog.ai) - One feed for agent builders that searches, enriches, and watches web data on people and companies. `MCP` ([MCP docs](https://docs.thehog.ai/mcp))
- [You.com](https://you.com) - Real-time web search and deep research endpoints that AI apps call for fresh answers. `MCP`
- [ZenRows](https://zenrows.com) - Scraping service that slips past anti-bot defenses, loads dynamic pages, and hands back clean data. `MCP` ([MCP docs](https://docs.zenrows.com/integrations/mcp/anthropic-claude-api))
- [Zyte](https://zyte.com) - Scraping service that takes care of IP rotation and page rendering, then returns tidy structured data.

## Browsers and computer use

Headless and hosted browsers for the jobs no API covers.

- [Anchor Browser](https://anchorbrowser.io) - Cloud browsers for agents that get through logins and two-factor checks on their own. `MCP` ([MCP docs](https://docs.anchorbrowser.io/advanced/mcp))
- [Anthropic Computer Use](https://claude.com) - Claude feature that operates a real screen, clicking and typing to finish tasks for developers' agents. `MCP` ([MCP docs](https://docs.anthropic.com/mcp))
- [Axiom AI](https://axiom.ai) - No-code browser bots that handle repetitive web chores like form filling and data copying. `MCP` ([MCP docs](https://axiom.ai/docs/developer-hub/mcp/))
- [Bardeen](https://bardeen.ai) - Pulls lead lists off websites, has AI check fit, and adds verified contact details.
- [Browser Use](https://browser-use.com) - Open-source code that gives agents a real browser to click, type, and read pages. `CLI`
- [Browserbase](https://browserbase.com) - Cloud browsers that AI agents can drive to click through websites, at large scale. `MCP` `CLI` ([MCP docs](https://browserbase.com/mcp))
- [Browserless](https://browserless.io) - Hosted headless browsers for scrapers and automations that need to avoid getting blocked. `MCP` ([MCP docs](https://docs.browserless.io/mcp/browser-agent))
- [Deck](https://www.deck.co) - Agents sign in to apps on a user's behalf and pull back clean data. `MCP`
- [Hyperbrowser](https://hyperbrowser.ai) - Cloud browsers that agents can launch on demand to visit and use websites. `MCP` `CLI`
- [Kernel](https://kernel.sh) - Hosted browsers using stealth settings so AI agents visit websites without tripping bot checks. `MCP` `CLI` ([MCP docs](https://kernel.sh/docs/reference/cli/mcp))
- [Kondo](https://trykondo.com) - Desktop app holding your LinkedIn and WhatsApp DMs, which AI agents can sort and answer. `MCP` ([MCP docs](https://trykondo.com/mcp))
- [Lightpanda](https://lightpanda.io) - Lightweight headless browser that AI agents use to open pages and pull content. `MCP` `CLI`
- [Magical](https://getmagical.com) - Agents that handle billing and patient intake for healthcare offices, having left text expansion behind. `MCP`
- [Notte](https://notte.cc) - Runs web browsers for AI agents and takes care of logins, proxies, and logging. `MCP` `CLI`
- [OpenAI Operator](https://openai.com) - OpenAI's early web-browsing agent, which filled forms and navigated sites, now absorbed into ChatGPT Agent. `CLI`
- [Scrapybara](https://scrapybara.com) - Cloud desktops that computer-use agents can see, click, and type in like a person would. `MCP`
- [Simular](https://simular.ai) - Agent that drives desktop software and web browsers the way a person does, without custom integrations. `CLI`
- [Skyvern](https://skyvern.com) - Self-hostable browser automation that uses vision and language models to finish tasks on any site. `MCP` `CLI`
- [Steel](https://steel.dev) - Open-source browser infrastructure, hosted or self-run, so agents can browse, click, and pull data from sites. `MCP`
- [UiPath](https://uipath.com) - Business automation suite that coordinates software robots and AI agents for large companies. `MCP`

## Communication

Email, voice, SMS, and transcription infrastructure an agent can send and listen through.

- [AssemblyAI](https://assemblyai.com) - Turns audio into text and adds summaries and other analysis for apps built on calls. `MCP` ([MCP docs](https://www.assemblyai.com/topic/mcp))
- [Bandwidth](https://bandwidth.com) - Phone-carrier-level calling, texting, and emergency 911 services that developers build into their software. `MCP` ([MCP docs](https://bandwidth.com/mcp))
- [Bird Email](https://bird.com) - Texting, email, and WhatsApp messaging at scale through one connection, formerly called MessageBird. `MCP` ([MCP docs](https://bird.com/docs/ai/mcp-server))
- [Bland](https://bland.ai) - Cheap AI phone agents that place and answer calls in bulk for sales and support teams.
- [Cartesia](https://cartesia.ai) - Very fast voice models for speech and transcription, plus tools to build voice agents. `MCP` `CLI` ([MCP docs](https://docs.cartesia.ai/tools/ai/mcp))
- [Courier](https://www.courier.com) - Developers route app alerts to email, text, push, chat, or in-app inboxes from one service. `MCP` `CLI` ([MCP docs](https://www.courier.com/docs/tools/mcp))
- [Deepgram](https://deepgram.com) - Speech recognition and voice generation services developers use to build voice products. `MCP` `CLI` ([MCP docs](https://docs.deepgram.com/mcp))
- [ElevenLabs](https://elevenlabs.io) - Turns text into lifelike speech, clones voices and runs voice bots for support and product teams. `MCP` `CLI`
- [Infobip](https://infobip.com) - Global messaging service for texting, WhatsApp, and phone calls that CX and dev teams wire up. `MCP` ([MCP docs](https://mcp.infobip.com))
- [Infraforge](https://infraforge.ai) - Private IPs, mailboxes, and domains set up so outbound teams' cold email avoids spam. `MCP` `CLI`
- [LiteMail](https://litemail.ai/) - Cold emailers buy pre-warmed Google and Microsoft inboxes here, with domain records set up automatically.
- [Loops](https://loops.so) - Email tool for software companies that sends both newsletters and product-triggered messages from one place. `MCP` `CLI`
- [Maildoso](https://maildoso.ai) - Inboxes and domains set up for cold email so outbound messages land in the inbox.
- [MailerSend](https://www.mailersend.com) - Developers use it to send transactional app emails, with a template editor, from MailerLite's makers.
- [Mailforge](https://mailforge.ai) - Buys extra domains and mailboxes in bulk so cold email never touches your main domain. `MCP` `CLI`
- [Mailgun](https://www.mailgun.com) - Email-sending service developers use for receipts and alerts, with tools to stay out of spam. Acquired. `MCP` ([MCP docs](https://www.mailgun.com/integrations/mcp-server/))
- [Mailjet](https://www.mailjet.com) - Email delivery service developers use to send marketing and transactional messages in volume. Acquired. `MCP` ([MCP docs](https://documentation.mailjet.com/hc/en-us/articles/42810091203867-Installing-the-Mailjet-MCP-Server))
- [MailReef](https://mailreef.com) - Sending infrastructure for cold email that developers build outbound products on.
- [Netcore Email API](https://netcorecloud.com) - Developer email-sending service from Netcore, built on Pepipost tech and focused on fast, reliable delivery. `MCP` ([MCP docs](https://netcorecloud.com/mcp))
- [Nylas](https://nylas.com) - Developers connect once to sync email, calendars, and contacts across many inbox providers. `CLI`
- [Plivo](https://plivo.com) - Programmable texting and calling for developers, plus a no-code builder for AI voice agents. `MCP`
- [Postmark](https://postmarkapp.com) - Delivers transactional emails from its own servers and IPs so important notices hit the inbox. Acquired. `MCP`
- [Recall.ai](recall.ai) - Developers drop a bot into video meetings and get back the recording and transcript.
- [Resend](https://resend.com) - Developers send transactional and marketing email through one service, building templates in React. `MCP` `CLI` ([MCP docs](https://resend.com/changelog/mcp))
- [Retell AI](https://www.retellai.com) - Build voice agents that answer incoming calls and dial outbound ones, aimed at contact center developers. `MCP` ([MCP docs](https://docs.retellai.com/build/single-multi-prompt/mcp))
- [Sendbird](https://sendbird.com) - Adds in-app messaging, voice calls, and video calls to phone and browser apps for developers.
- [Sinch](https://sinch.com) - Sends texts, calls, email, and login codes through one set of connections for big apps. `MCP` `CLI`
- [Slack](https://slack.com) - Team chat app where coworkers and AI agents now share channels and get work done. Acquired. `MCP` ([MCP docs](https://docs.slack.dev/ai/slack-mcp-server/))
- [SparkPost](https://www.sparkpost.com) - Enterprise email delivery for developers, with inbox placement tools and send analytics. Acquired.
- [Synthflow](https://synthflow.ai) - Build phone-answering voice agents visually, no code needed, for support and operations teams. `MCP`
- [Telnyx](https://telnyx.com) - Owns its own phone network and pairs voice, texting, GPUs, and edge servers for live agents. `MCP` `CLI`
- [Twilio](https://twilio.com) - Developer building blocks for sending texts, placing calls and confirming phone numbers within your product. `MCP` `CLI` ([MCP docs](https://www.twilio.com/docs/ai/mcp))
- [Twilio SendGrid](https://twilio.com) - Twilio's email sending service, letting developers push app email at volume and marketers run campaigns. `MCP` `CLI` ([MCP docs](https://www.twilio.com/docs/ai/mcp))
- [Vapi](https://vapi.ai) - Voice agent toolkit that wires speech, language models, and voices into fast phone calls. `MCP` `CLI` ([MCP docs](https://docs.vapi.ai/tools/mcp))
- [Vonage](https://vonage.com) - Voice, text, and video calling building blocks that developers add to their own apps. Acquired. `MCP` `CLI`
- [Zapmail](https://zapmail.ai) - Sets up large batches of Google and Outlook mailboxes for cold email teams.

## Agents and agent builders

Coding agents, chat agents, and the frameworks for building your own.

- [Aider](https://aider.chat) - Terminal pair programmer that edits code in your git project using whichever model you pick. `CLI`
- [Amazon Bedrock AgentCore](https://aws.amazon.com/bedrock/agentcore/) - Amazon's service for running agents in production, with secure tool access and tracing. `MCP` `CLI` ([MCP docs](https://docs.aws.amazon.com/bedrock-agentcore/latest/devguide/mcp-getting-started.html))
- [Amp](https://ampcode.com) - Coding agent you run locally or across many cloud machines at once to build software. `MCP` `CLI` ([MCP docs](https://ampcode.com/mcp))
- [Augment Code](https://augmentcode.com) - Coordinates AI agents for engineering work from planning to incident response, with people approving key steps. `MCP` `CLI` ([MCP docs](https://www.augmentcode.com/mcp))
- [Base44](https://base44.com) - Builds a usable web app from a plain-language description, no coding needed. Acquired. `MCP` `CLI`
- [Bolt.new](https://bolt.new) - Browser-based builder that turns plain prompts into working full-stack web apps with no local setup.
- [Breeze](https://www.hubspot.com/products/artificial-intelligence/breeze-ai-agents) - AI agents inside HubSpot that marketing, sales, and support teams can use or build without code. `MCP` ([MCP docs](https://developers.hubspot.com/ai-tools/mcp))
- [Claude Code](https://claude.com/product/claude-code) - Anthropic's terminal coding assistant that reads your repo, edits files and runs tasks for builders. `MCP` `CLI` ([MCP docs](https://code.claude.com/docs/en/mcp))
- [Cline](https://cline.bot) - Coding agent that runs inside VS Code, reading and changing files across your project. `MCP` `CLI` ([MCP docs](https://docs.cline.bot/mcp/mcp-overview))
- [Codex](https://openai.com) - OpenAI's coding assistant that finishes tasks in a walled-off sandbox and hands back pull requests. `MCP` `CLI`
- [Continue](https://continue.dev) - Customizable open-source code helper that plugs into VS Code or JetBrains editors. Acquired. `CLI`
- [CrewAI](https://crewai.com) - Framework for setting up groups of AI agents who split up and finish tasks together. `MCP` `CLI`
- [Cursor](https://cursor.com) - VS Code-based editor where AI agents write and fix your code. Now part of SpaceX. `MCP` `CLI` ([MCP docs](https://cursor.com/docs/cli/mcp))
- [Databricks Agent Bricks](https://www.databricks.com/product/artificial-intelligence/agent-bricks) - Enterprise teams build agents over their Databricks data and tune quality with generated test cases. `MCP` ([MCP docs](https://docs.databricks.com/aws/en/generative-ai/mcp/))
- [Devin](https://devin.ai) - AI software engineer that works from tickets, changes the code and opens pull requests for review. `MCP` `CLI` ([MCP docs](https://docs.devin.ai/work-with-devin/devin-mcp))
- [Dify](https://dify.ai) - Open-source canvas for making AI apps and agent workflows by dragging blocks together. `MCP` `CLI` ([MCP docs](https://docs.dify.ai/en/use-dify/publish/publish-mcp))
- [Dust](https://dust.tt) - Build no-code AI agents wired to the documents and tools your company already uses. `MCP` `CLI` ([MCP docs](https://docs.dust.tt/docs/user-documentation/agents/integrations/dust-mcp-server))
- [Empler AI](https://empler.ai) - No-code setup for teams of AI agents that handle marketing content and creative work.
- [Factory AI](https://factory.ai) - Engineering teams hand tasks to its Droids, coding agents that write, test, and ship software. `MCP` `CLI` ([MCP docs](https://docs.factory.ai/cli/configuration/mcp))
- [Flowise](https://flowiseai.com) - Open-source drag-and-drop tool for linking language models, tools, and agents into apps. Acquired.
- [Gemini CLI](https://google.com) - Terminal-based coding agent from Google, open source, that writes and runs code with Gemini. `CLI`
- [Genspark](https://genspark.ai) - AI workspace where one request becomes research, calls, slides, code, or simple apps. `CLI`
- [GitHub Copilot](https://github.com) - GitHub's coding assistant that suggests code, checks pull requests and works on issues you assign it. `MCP` `CLI` ([MCP docs](https://github.com/mcp))
- [Google Antigravity](https://antigravity.google) - Google's coding workspace where agents plan and test software using the editor, browser, and command line. `CLI`
- [Grok Bot](https://x.ai/bot) - xAI bots with their own cloud computer that sign into apps and do recurring chores. `CLI`
- [Hermes Agent](https://hermes-agent.nousresearch.com) - Self-hosted agent that builds new skills from past jobs and chats on Telegram or Slack. `MCP` `CLI` ([MCP docs](https://hermes-agent.nousresearch.com/docs/user-guide/features/mcp))
- [Hightouch](https://hightouch.com) - Copies warehouse data into every business tool, plus AI that writes campaign content for marketers. `MCP` `CLI`
- [Kiro](https://kiro.dev) - Amazon's coding editor where an agent builds working code from written specs and plans. `MCP` `CLI` ([MCP docs](https://kiro.dev/docs/mcp/))
- [LangChain](https://langchain.com) - Developer toolkit and hosted runtime for multi-step AI agents that remember state between steps. `MCP` `CLI` ([MCP docs](https://docs.langchain.com/langsmith/agent-server-api/mcp/mcp-get))
- [LangGraph](https://www.langchain.com/langgraph) - LangChain framework for building agents that remember state and run long multi-step jobs. `MCP` `CLI` ([MCP docs](https://docs.langchain.com/langsmith/agent-server-api/mcp/mcp-get))
- [Lindy](https://lindy.ai) - No-code AI assistants that plug into your apps and handle repeat multi-step work.
- [Lovable](https://lovable.dev) - Non-coders describe an app in plain words and get a working web or phone app. `MCP` ([MCP docs](https://docs.lovable.dev/integrations/lovable-mcp-server))
- [Manus](https://manus.im) - General agent that researches online, writes code, and hands back finished work from a task.
- [Microsoft Copilot Studio](https://www.microsoft.com/en-us/microsoft-365-copilot/microsoft-copilot-studio) - Microsoft's low-code agent builder that taps over 1,400 data connectors and publishes into Teams and SharePoint. `MCP` `CLI` ([MCP docs](https://learn.microsoft.com/en-us/microsoft-copilot-studio/mcp-add-existing-server-to-agent))
- [MindStudio](https://mindstudio.ai) - Drag-and-drop agent maker that lets ops and GTM teams chain models and apps without writing code. `MCP` `CLI` ([MCP docs](https://mindstudio.ai/mcp))
- [OpenAI AgentKit](https://platform.openai.com/agent-builder) - OpenAI's toolkit for designing agents visually or in code, then deploying them with connectors. `MCP` `CLI` ([MCP docs](https://platform.openai.com/docs/guides/tools-connectors-mcp))
- [OpenClaw](https://openclaw.ai) - Run your own AI assistant on any model and message it through WhatsApp, Telegram or Slack. `MCP` `CLI` ([MCP docs](https://docs.openclaw.ai/cli/mcp))
- [OpenCode](https://opencode.ai) - Coding agent under the MIT license that runs on 75+ model providers, local models too. `MCP` `CLI` ([MCP docs](https://opencode.ai/docs/mcp-servers))
- [Relevance AI](https://relevanceai.com) - Build AI agents for prospecting and account research without writing code, aimed at ops teams. `MCP`
- [Replit](https://replit.com) - Turn a prompt into a live app, with direct hooks into Microsoft Fabric and Databricks data. `MCP`
- [Retool](https://retool.com) - Drag-and-drop builder for internal apps that connect to your databases, outside services, and language models. `MCP`
- [Salesforce Agentforce](https://www.salesforce.com/agentforce/) - Salesforce's own AI agents that handle selling, support, and marketing tasks inside your CRM. `MCP` `CLI` ([MCP docs](https://www.salesforce.com/agentforce/mcp-support/))
- [Sintra](https://sintra.ai) - A dozen helpers, each with a job like social, sales, email, or support, for solo founders.
- [Snowflake Cortex AI](https://www.snowflake.com/en/product/features/cortex/) - Snowflake add-on for calling language models and building data agents with plain SQL. `MCP`
- [Sourcegraph](https://sourcegraph.com) - Code search across all your repos that also gives AI coding agents enough context to work. `MCP` `CLI` ([MCP docs](https://sourcegraph.com/mcp))
- [Stack AI](https://stack-ai.com) - No-code builder for AI agents with governance controls, aimed at banks and healthcare. Acquired. `MCP`
- [Swan AI](https://getswan.com) - Turns written playbooks into agents that spot site visitors and reach out on LinkedIn and email. `MCP`
- [Tabnine](https://tabnine.com) - Code suggestions that security-minded enterprises can run self-hosted or offline. Now part of Tricentis. `CLI`
- [v0](https://v0.app) - Vercel's tool that writes React interfaces and whole apps from a text description. `MCP` `CLI`
- [Vellum](https://vellum.ai) - Personal AI assistant that remembers context across chats, after moving away from LLM developer tooling. `CLI`
- [Vertex AI Agent Builder](https://cloud.google.com/products/agent-builder) - Google Cloud's kit for building and running teams of AI agents with open-source ADK. `MCP` `CLI`
- [Warp](https://warp.dev) - Hands tickets to AI coders and grades the code they produce so teams can adjust setups. `MCP` `CLI`
- [Windsurf](https://codeium.com) - Coding editor for running and reviewing several AI coding agents at once. Acquired. `MCP` `CLI` ([MCP docs](https://codeium.com/mcp))
- [Zed](https://zed.dev) - Quick code editor with an AI agent built in for writing and moving through code. `CLI`

## Workflows and orchestration

Tools that chain steps, schedule runs, and move data between systems.

- [Cargo](https://getcargo.ai) - Revenue workflows written as TypeScript code with version history, for GTM engineers who prefer code. `MCP` `CLI` ([MCP docs](https://docs.getcargo.ai/api-reference/ai--mcp/get-mcp-server))
- [Gumloop](https://gumloop.com) - No-code builder where staff create AI agents and IT keeps a lid on access and cost. `MCP` `CLI` ([MCP docs](https://www.gumloop.com/mcp))
- [Latenode](https://latenode.com) - Drag-and-drop automation builder where you can add JavaScript code, browser steps, and AI agents. `MCP` ([MCP docs](https://latenode.com/products/mcp))
- [Lleverage](https://lleverage.ai) - Agents built without code that handle order entry and invoice matching for manufacturers and distributors. `MCP` ([MCP docs](https://mcp.lleverage.ai))
- [Make](https://www.make.com) - Visual drag-and-drop builder for app automations with branching paths, for ops teams who skip code. `MCP` `CLI` ([MCP docs](https://developers.make.com/mcp-server))
- [n8n](https://n8n.io) - Open-source automation builder you can host yourself, mixing code steps and AI agents in one flow. `MCP` `CLI` ([MCP docs](https://docs.n8n.io/advanced-ai/mcp/accessing-n8n-mcp-server/))
- [OXYGEN](https://oxygen-agent.com) - Command-line agent for GTM engineers to run outbound across 25+ tools from Claude Code. `MCP` `CLI` ([MCP docs](https://oxygen-agent.com/docs/surfaces/mcp))
- [Pancake](https://getpancake.ai/) - Outbound agent that turns one prompt into ongoing lead searches and email follow-ups. `MCP`
- [Pipedream](https://pipedream.com) - Plugs agents into other apps and takes care of logins and expiring access tokens. Acquired. `MCP` `CLI` ([MCP docs](https://pipedream.com/docs/connect/mcp))
- [Power Automate](https://powerautomate.microsoft.com) - Microsoft tool for automating work across apps without much code, where Copilot builds flows from prompts. `MCP` `CLI`
- [Relay.app](https://relay.app) - Workflow builder that mixed AI steps with human sign-off points; the company closed in fall 2026. `MCP`
- [TexAu](https://texau.com) - Spreadsheet-style workspace where GTM operators enrich, verify, and score leads, then push them to the CRM. `MCP` ([MCP docs](https://www.texau.com/mcp))
- [Tray.ai](tray.ai) - Enterprise integration tool that links business apps and lets IT build guarded agents with Merlin. `MCP`
- [Windmill](https://windmill.dev) - Open-source engine you host yourself to turn scripts into automations, apps, and agent tools. `MCP` `CLI`
- [Workato](https://workato.com) - Enterprise automation tool for building flows that connect and run work across business apps. `MCP` `CLI` ([MCP docs](https://workato.com/mcp))
- [Zapier](https://zapier.com) - No-code connector that links thousands of apps with if-this-then-that automations, now usable by AI tools. `MCP`

## Context and memory

Where an agent keeps what it knows: GTM context layers, memory stores, and the warehouse.

- [BigQuery](https://cloud.google.com) - Google Cloud warehouse that data teams query with SQL over huge amounts of data, no servers. `MCP` `CLI`
- [Census](https://getcensus.com) - Syncs data from your warehouse into the sales and marketing apps your teams use. Acquired. `MCP` ([MCP docs](https://docs.getcensus.com/mcp))
- [Chroma](https://trychroma.com) - Embedding store developers add to AI apps so answers use their data. Now part of Replit. `MCP` `CLI` ([MCP docs](https://docs.trychroma.com/cloud/package-search/mcp))
- [Clearskies](https://www.clearskies.cc) - Joins CRM, call, email, and Slack data into one map so revenue agents have context. `MCP` ([MCP docs](https://mcp.clearskies.cc))
- [ClickHouse](https://clickhouse.com) - Open-source column-based database that answers analytics questions on huge datasets in real time. `MCP` `CLI`
- [Cognee](https://cognee.ai) - Memory for AI agents that turns your data into a graph they can reason over. `MCP` `CLI`
- [ColdIQ](https://coldiq.com) - Single data source for agent builders that picks the best of 40+ enrichment vendors per request. `MCP` ([MCP docs](https://coldiq.com/mcp/windsor-mcp))
- [Databricks](https://databricks.com) - Data lakehouse where teams run pipelines, reporting, and machine learning, with agents on top. `MCP` `CLI` ([MCP docs](https://docs.databricks.com/aws/en/generative-ai/mcp/))
- [Fivetran](https://fivetran.com) - Ready-made connectors that copy data from hundreds of apps into your warehouse. `MCP`
- [Fluint](https://www.fluint.io) - Context layer that hands AI sales agents deal data and links their actions to won revenue. `MCP`
- [LanceDB](https://lancedb.com) - Open-source embedded store that keeps embeddings next to your data for vector and keyword search. `MCP`
- [Letta](https://letta.com) - Runtime for long-lived AI agents whose memory updates itself as they learn, aimed at developers. `CLI`
- [Mem0](https://mem0.ai) - Memory add-on for AI agents so they recall past chats instead of starting from scratch. `MCP` `CLI`
- [Milvus](https://milvus.io) - Open-source database for AI embeddings, built to search very large collections quickly. `MCP`
- [MongoDB](https://mongodb.com) - Document database whose cloud version adds vector search so AI agents can store and find data. `MCP` `CLI` ([MCP docs](https://www.mongodb.com/products/tools/mcp-server))
- [MotherDuck](https://motherduck.com) - DuckDB in the cloud, a lightweight warehouse for small and medium analytics workloads. `MCP` `CLI` ([MCP docs](https://motherduck.com/docs/sql-reference/mcp/))
- [Nekt](https://www.nekt.com) - Gathers 200+ data sources into permissioned tables that AI agents can query, for RevOps teams. `MCP` ([MCP docs](https://docs.nekt.com/mcp))
- [Neo4j](https://neo4j.com) - Graph database that maps how things relate, used for agent memory and knowledge graphs. `MCP` `CLI` ([MCP docs](https://neo4j.com/docs/mcp))
- [Neo4j Agent Memory](https://neo4j.com/labs/agent-memory/) - Stores an agent's chats, people, and reasoning in a single graph so it remembers over time. `MCP` `CLI` ([MCP docs](https://neo4j.com/labs/agent-memory/reference/mcp-tools/))
- [Octave](https://www.octavehq.com) - Keeps products, personas and segments in one model so agents and reps share the same context. `MCP` ([MCP docs](https://docs.octavehq.com/mcp/overview))
- [Pinecone](https://pinecone.io) - Vector database that stores embeddings for fast meaning-based search inside AI apps. `MCP` `CLI`
- [Qdrant](https://qdrant.tech) - Open-source Rust database that stores AI embeddings and finds similar items fast, for app builders. `MCP`
- [Redis](https://redis.io) - Fast in-memory database that also handles vector search for AI apps and caching. `MCP`
- [Redis Agent Memory](https://redis.io/agent-memory/) - Hosted memory from Redis that pulls key facts from agent chats and recalls them by meaning. `MCP`
- [RudderStack](https://rudderstack.com) - Collects product and website events and lands them in your own data warehouse. `MCP` `CLI`
- [Snowflake](https://www.snowflake.com) - Cloud data warehouse where big companies store, analyze, and govern data and AI agents. `MCP` ([MCP docs](https://docs.snowflake.com/en/user-guide/snowflake-cortex/cortex-agents-mcp))
- [Supermemory](https://supermemory.ai) - Memory layer that lets agents save what they learn and recall it in later chats. `MCP` ([MCP docs](https://supermemory.ai/mcp/))
- [Turbopuffer](https://turbopuffer.com) - Low-cost vector database on cloud object storage for search and memory in AI apps.
- [Twilio Segment](https://segment.com) - Gathers customer events from every touchpoint into live profiles and forwards them to hundreds of tools. `MCP` `CLI` ([MCP docs](https://www.twilio.com/docs/ai/mcp))
- [Vasco](https://vasco.app) - Links sales, billing, call, and usage records so agents get revenue numbers right instead of guessing. `MCP`
- [Vectara](vectara.com) - Gives enterprise agents cited answers from company files, respecting who is allowed to see what. `MCP` ([MCP docs](https://github.com/vectara/vectara-mcp))
- [Weaviate](https://weaviate.io) - Open-source store for embeddings that blends keyword and meaning search for agent memory. `MCP`
- [Zep](https://getzep.com) - Gives agents lasting memory of users and past chats using a knowledge graph that tracks time. `MCP` ([MCP docs](https://docs.getzep.com/mcp))
- [Zilliz](https://zilliz.com) - Hosted version of the open-source Milvus vector database, for AI engineers storing and searching embeddings. `MCP` `CLI`

## Connectors and MCP

Gateways that hand an agent many integrations behind one connection.

- [ACI.dev](https://aci.dev) - Open-source layer that connects AI agents to 600+ apps with login and permissions handled. `MCP`
- [Arcade.dev](https://arcade.dev) - Hosts agent tools that sign each user in with their own account, not shared keys. `MCP` `CLI`
- [Composio](https://composio.dev) - Ready-made app connections and login handling so developers' agents can act in hundreds of tools. `MCP` `CLI` ([MCP docs](https://mcp.composio.dev))
- [Glama](https://glama.ai) - Catalog of hosted tool servers that developers browse, run, and hook up to their agents. `MCP` ([MCP docs](https://glama.ai/mcp/methodology))
- [Gradient Works](https://www.gradient.works) - Assigns accounts to reps dynamically using AI scores, replacing fixed territories for RevOps. `MCP` ([MCP docs](https://docs.gradient.works/kb/mcp/overview))
- [Klavis](https://klavis.ai) - Strata points AI agents to the right tool when they have too many to choose. `MCP` ([MCP docs](https://www.klavis.ai/docs/concepts/mcp))
- [mcp.so](https://mcp.so) - Community-run listing of connector servers, clients, and agent skills for developers wiring AI to tools. `MCP` `CLI` ([MCP docs](https://mcp.so/server/mcp/waystation-ai))
- [Smithery](https://smithery.ai) - Directory and hosting for agent tool servers that developers can find, deploy, and plug in. `MCP` `CLI`
- [Toolhouse](https://toolhouse.ai) - Email a plain-English request and an AI worker handles jobs such as researching leads or follow-ups. `MCP` `CLI`

## Run and deploy

Hosting, sandboxes, databases, and model APIs to run agents on.

- [AWS](https://aws.amazon.com) - Amazon’s cloud for servers, storage, and databases, plus Bedrock to run AI agents. `MCP` `CLI`
- [Baseten](https://baseten.co) - Hosts and scales custom AI models on GPUs so engineering teams don't manage servers themselves. `MCP` `CLI` ([MCP docs](https://docs.baseten.co/mcp))
- [Beam](https://beam.cloud) - Serverless GPU sandboxes you start on demand to run AI jobs, all open source. `MCP` `CLI`
- [Blaxel](https://blaxel.ai) - Warm sandboxes so production agents start right away instead of booting cold. Now part of Baseten. `MCP` `CLI`
- [Cloudflare Workers](https://cloudflare.com) - Runs your code on Cloudflare's worldwide servers, with storage and browser tools for building agents. `MCP` `CLI`
- [Convex](https://convex.dev) - TypeScript backend database that pushes each data update to all connected apps in real time. `MCP` `CLI` ([MCP docs](https://mcp.convex.dev))
- [Daytona](https://daytona.io) - Spins up isolated coding sandboxes in under a tenth of a second for AI agents. `MCP` `CLI` ([MCP docs](https://www.daytona.io/docs/en/mcp/))
- [DBOS](https://dbos.dev) - Keeps backend workflows running through crashes and restarts by saving progress in Postgres. `MCP` `CLI` ([MCP docs](https://docs.dbos.dev/integrations/mcp))
- [E2B](https://e2b.dev) - Gives AI agents isolated mini virtual machines to execute code, use a browser, and edit files. `MCP` `CLI`
- [Fly.io](https://fly.io) - Gives every agent its own Linux machine that pauses when idle and keeps its files. `MCP` `CLI` ([MCP docs](https://fly.io/docs/mcp/))
- [Groq](https://groq.com) - Fast AI model hosting on custom chips for apps where response speed matters. `MCP` ([MCP docs](https://docs.groq.com/mcp))
- [Hatchet](https://hatchet.run) - Engineering teams use it to queue, schedule, and coordinate long tasks and agent runs. `CLI`
- [Inngest](https://inngest.com) - Runs background jobs as steps that retry on failure, with no queue servers to manage. `MCP` `CLI`
- [Lambda](https://lambdalabs.com) - Rent cloud GPUs on demand to train and run AI models without long contracts.
- [Modal](https://modal.com) - Python developers run code in the cloud on GPUs that start and stop as needed.
- [Neon](https://neon.com) - Postgres database that runs without servers and copies itself instantly for testing. Acquired. `MCP` `CLI`
- [Netlify](https://netlify.com) - Hosts websites straight from Git and gives each pull request its own preview link. `MCP` `CLI`
- [Northflank](https://northflank.com) - Platform engineers ship apps, databases, and AI services onto their own cloud or a hosted one. `MCP` `CLI` ([MCP docs](https://northflank.com/docs/v1/application/ai-agents/mcp-server))
- [OpenRouter](https://openrouter.ai) - Single endpoint for hundreds of AI models, with automatic fallback between providers. Now part of Stripe. `MCP`
- [Railway](https://railway.com) - Push a GitHub repo and get a running service, databases and scaling included. `MCP` `CLI`
- [Render](https://render.com) - Cloud hosting for web apps, background jobs, and scheduled tasks with no server upkeep. `MCP` `CLI`
- [Replicate](https://replicate.com) - Run thousands of hosted AI models, open or custom, and pay by the second. Acquired. `MCP` ([MCP docs](https://mcp.replicate.com))
- [Restate](https://restate.dev) - Keeps long-running workflows and agents on track through crashes by saving state and retrying steps. `CLI`
- [Runloop](https://runloop.ai) - Coding agents get on-demand sandboxes to execute and check their code away from production. `MCP` `CLI`
- [RunPod](https://runpod.io) - Rents GPUs on demand so engineers can run AI models without looking after servers. `MCP` `CLI`
- [Supabase](https://supabase.com) - Open-source backend that gives app builders a Postgres database plus login, file storage and vector search. `MCP` `CLI` ([MCP docs](https://supabase.com/mcp))
- [Temporal Technologies](https://temporal.io) - Developers write long-running processes as normal code, and it handles crashes, retries, and saved state. `MCP` `CLI`
- [Together AI](https://together.ai) - GPU cloud serving hundreds of open AI models, from the team behind FlashAttention. `MCP` `CLI`
- [Trigger.dev](https://trigger.dev) - Runs background jobs and long AI workflows from your code, picking up again after failures. `MCP` `CLI` ([MCP docs](https://trigger.dev/docs/ai-chat/mcp))
- [Turso](https://turso.tech) - Separate SQLite database for every user or agent, kept near them. Now part of Supabase. `MCP` `CLI` ([MCP docs](https://docs.turso.tech/agentfs/guides/mcp))
- [Upstash QStash](https://upstash.com) - Serverless message queue that runs scheduled jobs and retries web requests when your functions fail. `MCP`
- [Vercel](https://vercel.com) - Frontend web hosting that now also offers the gateway, sandboxes and workflow tools agents need. `MCP` `CLI` ([MCP docs](https://vercel.com/docs/mcp))

## GTM platforms going headless

The CRMs, sequencers, and marketing suites you already pay for, now reachable by API, MCP, or CLI.

- [6sense](https://6sense.com) - Ranks accounts by how close they are to buying, with an AI analyst helping each rep. `MCP` ([MCP docs](https://support.6sense.com/docs/6sense-model-context-protocol-mcp-1))
- [ActiveCampaign](https://activecampaign.com) - Small-business CRM and email automation tool, now with dozens of AI helpers for campaigns. `MCP` ([MCP docs](https://help.activecampaign.com/hc/en-us/articles/22566179229596-Get-started-with-the-ActiveCampaign-MCP-Server))
- [Adobe](https://adobe.com) - Maker of Creative Cloud design tools and an agent-based suite for running marketing. `MCP` `CLI`
- [Adobe Marketo Engage](https://developers.marketo.com) - Long-running enterprise marketing automation tool from Adobe, now with built-in agents for building campaigns. `MCP` `CLI` ([MCP docs](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/mcp-server))
- [Affinity.co](https://affinity.co) - CRM for venture and private equity firms that maps the team's network and tracks deals. `MCP` ([MCP docs](https://developer.affinity.co/pages/mcp/authentication))
- [Ahrefs](https://ahrefs.com) - SEO toolkit with its own crawler for keywords and backlinks, now also tracking AI chatbot mentions. `MCP` ([MCP docs](https://docs.ahrefs.com/mcp/docs/introduction))
- [Aimfox](https://aimfox.com) - Automatic LinkedIn invites and follow-up notes that keep new prospects flowing into your pipeline. `MCP` ([MCP docs](https://mcp.aimfox.com))
- [Airtable](https://airtable.com) - Spreadsheet-style app builder where AI agents work through your records. Now part of Bending Spoons. `MCP` ([MCP docs](https://support.airtable.com/docs/using-the-airtable-mcp-server))
- [Albacross](https://albacross.com) - Shows which companies visit your website and how ready they are to buy.
- [Amplemarket](https://amplemarket.com) - Finds leads, adds their contact details, and sends outbound sequences timed to buying signals. `MCP`
- [Amplitude](https://amplitude.com) - Shows how people use your product and, lately, where AI agent sessions go wrong. `MCP` `CLI` ([MCP docs](https://amplitude.com/mcp))
- [AthenaHQ](https://athenahq.ai) - Shows how often AI assistants like Gemini and ChatGPT cite your brand, and what to fix. `MCP`
- [Avoma](https://www.avoma.com) - Records sales calls, then scores deal health and coaches reps from what was said. `MCP` ([MCP docs](https://help.avoma.com/avoma-mcp-server-user-guide))
- [Backstory](https://backstory.ai) - Puts rep activity in the CRM without typing, then predicts pipeline and points to key deals. `MCP` ([MCP docs](https://people.ai/platform/mcp))
- [Botify](https://www.botify.com) - Enterprise SEO tool built on crawl and server log data, now measuring AI search presence. `MCP`
- [Braze](https://braze.com) - Consumer brands reach users by email, in-app screens and phone notifications, with AI agents assembling campaigns. `MCP` ([MCP docs](https://www.braze.com/docs/user_guide/brazeai/mcp_server))
- [Breakcold](https://breakcold.com) - CRM for social sellers that shows what prospects post on LinkedIn next to your deals. `MCP` ([MCP docs](https://www.breakcold.com/mcp))
- [BrightEdge](https://www.brightedge.com) - Enterprise SEO suite that tracks search rankings and how often AI assistants mention your brand. `MCP`
- [Cabal](https://getcabal.com) - Founders use their backers' and advisors' contacts to get warm intros to buyers and hires. `MCP`
- [Cal.com](https://cal.com) - Open-source booking tool that AI agents can use to schedule and manage meetings. `MCP` `CLI`
- [Calendly](https://calendly.com) - Booking links so prospects grab an open slot themselves instead of trading emails about times. `MCP` ([MCP docs](https://developer.calendly.com/docs/mcp/calendly-mcp-server))
- [Chili Piper](https://chilipiper.com) - Inbound lead router that pairs each form fill with a rep and schedules the call instantly. `MCP` ([MCP docs](https://help.chilipiper.com/hc/en-us/articles/50430350863635-How-do-I-connect-Chili-Piper-via-MCP))
- [Clari](https://clari.com) - Revenue forecasting for sales leaders, built on CRM and call data, that warns about slipping deals. `MCP`
- [Clodura](https://clodura.ai) - Sales tool that finds and checks prospect contacts, then runs email sequences and calls.
- [Close](https://www.close.com) - Sales CRM for small teams with phone calls, email, and texting built right in. `MCP` ([MCP docs](https://developer.close.com/mcp))
- [Cognism](https://cognism.com) - Contact data for prospecting in Europe, with mobile numbers checked by phone and GDPR in mind. `MCP` ([MCP docs](https://docs.cognism.com/docs/mcp-server))
- [Conductor](https://conductor.com) - Enterprise SEO suite that now tracks and improves how brands show up in AI answers. `MCP` ([MCP docs](https://www.conductor.com/platform/features/mcp-server/))
- [Connect the Dots](https://ctd.ai) - Puts your team's shared network into a search showing who can introduce whom. `MCP` ([MCP docs](https://ctd.ai/integrations-mcp))
- [ContactOut](https://contactout.com) - Recruiters and reps use it to get a LinkedIn member's private email and mobile number. `MCP`
- [Copper](https://copper.com) - CRM built into Gmail and Google Calendar for service businesses that sell on relationships.
- [Crossbeam](https://crossbeam.com) - Shows which accounts you and your partners have in common, safely, without sharing full lists. `MCP` ([MCP docs](https://help.crossbeam.com/en/articles/12601327-crossbeam-mcp-server-limited-availability))
- [Crunchbase](https://crunchbase.com) - Database of startup funding rounds, company facts and investor moves, used for research and prospecting. `MCP` ([MCP docs](https://data.crunchbase.com/docs/mcp-overview))
- [Customer.io](https://customer.io) - Sends messages across channels based on what each user does, and an AI agent drafts campaigns. `MCP` `CLI` ([MCP docs](https://docs.customer.io/ai/mcp-server/))
- [Demandbase](https://demandbase.com) - ABM software that flags companies showing buying interest, then points ads and rep outreach their way. `MCP` ([MCP docs](https://developer.demandbase.com/docs/mcp))
- [Docusign](https://www.docusign.com) - Collects e-signatures on contracts and tracks agreements through renewal, used by sales ops and legal teams. `MCP`
- [Dux-Soup](https://dux-soup.com) - Browser add-on that visits, connects with, and messages LinkedIn prospects on autopilot for reps.
- [Evaboot](https://evaboot.com) - Pulls your Sales Navigator lead lists out of LinkedIn and adds verified emails. `MCP`
- [Factors.ai](https://factors.ai) - Spots accounts ready to buy, names the visitors, credits touchpoints, and kicks off ABM campaigns. `MCP` ([MCP docs](https://www.factors.ai/scout/mcp))
- [FinalScout](https://finalscout.com) - Reps and recruiters paste a LinkedIn profile and get a work email, found with ChatGPT.
- [Firmable](https://www.firmable.com) - Company and people data for prospecting in Australia and NZ, aimed at local sellers. `MCP` ([MCP docs](https://docs.firmable.com/mcp/overview))
- [Folderly](https://folderly.com) - Finds out why cold emails land in spam and fixes the setup behind it.
- [Folk](https://folk.app) - CRM for agencies and small sales teams, with AI that looks up contacts and writes follow-ups. `MCP` ([MCP docs](https://developer.folk.app/mcp/overview))
- [Frontspin](https://frontspin.com) - Power dialer that works through call lists and logs every rep conversation. Now part of TitanX.
- [Gong](https://gong.io) - Captures every sales conversation, warns about shaky deals and writes follow-ups and pipeline updates for reps. `MCP`
- [Goodie AI](https://higoodie.com) - Ecommerce brands see and raise their visibility in shopping assistants like Rufus and ChatGPT Shopping. `MCP`
- [Hex](https://hex.tech) - Notebooks for data teams, with an agent that pulls answers from the warehouse using trusted metrics. `MCP` `CLI` ([MCP docs](https://learn.hex.tech/docs/api-integrations/mcp-server))
- [HeyReach](https://heyreach.io) - Runs LinkedIn outreach from many sender accounts at once, with all replies landing in one inbox. `MCP` `CLI` ([MCP docs](https://www.heyreach.io/mcp))
- [HubSpot](https://www.hubspot.com) - Mid-market CRM bundling marketing, sales and service tools, often picked as the lighter Salesforce alternative. `MCP` `CLI` ([MCP docs](https://developers.hubspot.com/mcp))
- [Hunter.io](https://hunter.io) - Email finder that looks up work addresses by company website and checks each one. `MCP`
- [Instantly](https://instantly.ai) - Cold email tool that spreads sends across many inboxes and comes with its own lead database. `MCP` `CLI` ([MCP docs](https://developer.instantly.ai/mcp/introduction))
- [Intricately](https://intricately.com) - Reveals the cloud services and software a company uses so sellers can target buyers. Acquired.
- [Intuit Mailchimp](https://mailchimp.com) - Small businesses send newsletters and automated email campaigns from it. Acquired.
- [Iterable](https://iterable.com) - Cross-channel marketing tool with Nova agents that check campaigns, test ideas, and tailor each message. `MCP` ([MCP docs](https://support.iterable.com/hc/en-us/articles/42936800222612-Overview-of-Iterable-s-MCP-Server))
- [June](https://june.so) - Product analytics for B2B SaaS that tracked usage by account. Acquired.
- [Klaviyo](https://klaviyo.com) - Email and SMS marketing for online shops, where AI agents can draft full campaigns. `MCP` `CLI`
- [Koncert](https://koncert.com) - Dialer that rings several prospects at once and puts reps through only when someone answers.
- [La Growth Machine](https://lagrowthmachine.com) - Runs outreach on LinkedIn and email together and fills gaps in contact data from several providers.
- [Lead411](https://lead411.com) - Outbound reps get checked emails, phone numbers, and a heads-up when key accounts hire new leaders. `MCP`
- [Leadfeeder](https://leadfeeder.com) - Reveals which companies visit your site, rates their interest, and sends good fits to your CRM. `MCP`
- [LeadIQ](https://leadiq.com) - Grabs verified contact details while reps browse LinkedIn and drops them in the CRM or sequencer. `MCP`
- [LeanData](https://leandata.com) - RevOps teams draw routing rules visually to assign accounts, leads and meetings to whoever owns them. `MCP`
- [Lemlist](https://www.lemlist.com) - Outbound sequences over email and LinkedIn with inbox warmup and a lead database built in. `MCP` ([MCP docs](https://developer.lemlist.com/mcp/lemlist-agent))
- [LinkedIn Sales Navigator](https://linkedin.com) - LinkedIn's paid search tool for finding and messaging prospects with advanced filters.
- [Lusha](https://lusha.com) - Affordable company and contact lookup with emails, phone numbers, and buying signals for small sales teams. `MCP`
- [Mailivery](https://mailivery.io) - Warms up new or cold inboxes by swapping AI-written emails with other accounts to protect deliverability.
- [Mailreach](https://mailreach.co) - Builds sender reputation for new inboxes and checks whether cold emails land in spam. `MCP` ([MCP docs](https://docs.mailreach.co/mcp))
- [Mailshake](https://mailshake.com) - SDRs set up cold email drips once, and it handles every follow-up step on its own.
- [Manyreach](https://manyreach.com) - Bulk cold email sender that lets sellers run large outbound campaigns to win new customers.
- [Mattermark](https://mattermark.com) - Database of companies, investors, funding rounds, and growth signals for deal and sales researchers. Acquired.
- [Metronome](https://metronome.com) - Tracks product usage and turns it into invoices for companies with usage pricing. Acquired.
- [Mixmax](https://www.mixmax.com) - Adds sequences, meeting booking, and email tracking right inside Gmail for sales reps. `MCP` ([MCP docs](https://www.mixmax.com/mcp-server-guide))
- [Mixpanel](https://mixpanel.com) - Tracks what users click and do in your product to measure feature adoption. `MCP` ([MCP docs](https://mixpanel.com/docs/mcp))
- [Notion](https://notion.so) - Workspace for notes, wikis, and team databases, now with AI agents that do tasks. `MCP` `CLI`
- [Oppwiser](https://oppwiser.com) - Finds companies that look like your best customers so sales and marketing can grow pipeline.
- [Orb](https://withorb.com) - Bills customers by counting usage events like requests and compute time. Now part of Adyen.
- [Otter.ai](https://otter.ai) - Writes live transcripts and notes for meetings or recordings you upload, for busy teams. `MCP` ([MCP docs](https://otter.ai/mcp))
- [OtterlyAI](https://otterly.ai) - Self-serve tracker that shows where your brand gets cited in ChatGPT, Gemini, and Perplexity answers. `MCP`
- [Outplay](https://outplayhq.com) - Sales reps line up emails, phone calls, and social touches in a single outbound cadence. Acquired.
- [Outreach](https://outreach.ai/) - Runs sales cadences across channels for reps, and is moving to AI agents for deals. `MCP` ([MCP docs](https://support.outreach.io/support/solutions/articles/159000425158-outreach-mcp-server))
- [Paddle](https://www.paddle.com) - Acts as the legal seller for software companies, handling global billing, sales tax, and payments. `MCP` ([MCP docs](https://developer.paddle.com/concepts/mcp))
- [PandaDoc](https://pandadoc.com) - Legal and sales teams draft proposals from saved templates and get contracts signed online. `MCP` ([MCP docs](https://developers.pandadoc.com/docs/how-to-use-the-pandadoc-mcp-server))
- [Peec AI](https://peec.ai) - Shows marketers how often their brand comes up when Gemini, ChatGPT, or Perplexity answer questions. `MCP` ([MCP docs](https://peec.ai/mcp))
- [PhantomBuster](https://phantombuster.com) - Runs bots in the cloud to collect LinkedIn and social data and engage prospects automatically.
- [Pipedrive](https://www.pipedrive.com) - Simple CRM for small sales teams that tracks deals on a visual stage board. Acquired. `MCP` ([MCP docs](https://www.pipedrive.com/en/features/mcp-server))
- [Pocus](https://pocus.com) - Tells sales which self-serve accounts are worth a call, using product and billing data. Acquired.
- [PostHog](https://posthog.com) - Product analytics, session replays, feature flags, and experiments in one open-source tool agents can query. `MCP` `CLI` ([MCP docs](https://posthog.com/mcp))
- [Primer](https://www.sayprimer.com) - Demand-gen teams target ads using CRM and website data, then check real impact against holdout groups. `CLI`
- [Pylon](https://www.usepylon.com) - B2B customer support tool that gathers chats from Slack, email, and Teams into one list. `MCP` ([MCP docs](https://docs.usepylon.com/pylon-docs/integrations/pylon-mcp))
- [QuickMail](https://quickmail.com) - Runs cold email campaigns for outbound sellers and agencies and keeps an eye on inbox placement.
- [RB2B](https://rb2b.com) - Names the actual people visiting your website, not only their companies, for US traffic. `MCP` ([MCP docs](https://docs.rb2b.com/mcp))
- [Reply.io](https://reply.io) - Outbound sales software where an AI rep runs email, call, and social sequences. `MCP` `CLI` ([MCP docs](https://reply.io/mcp/))
- [RevenueHero](https://revenuehero.io) - Matches each inbound demo request with the correct rep and books a call on the spot. `MCP` ([MCP docs](https://mcp.revenuehero.io))
- [Salesforce](https://www.salesforce.com) - Big-company CRM holding customer records for sales, support and marketing teams, now adding Agentforce agents. `MCP` `CLI`
- [Saleshandy](https://saleshandy.com) - Runs cold email follow-ups at volume and flags spam risk ahead of each send. `MCP` `CLI` ([MCP docs](https://www.saleshandy.com/mcp))
- [SalesIntel](https://salesintel.io) - People-checked B2B contacts plus Bombora buying-intent data to help reps pick who to call.
- [Salesloft](https://salesloft.com) - Sales engagement software that runs outbound sequences and coaches reps live during calls. `MCP` ([MCP docs](https://mcp.salesloft.com))
- [Scrunch AI](https://scrunch.com) - Tracks brand mentions in chatbots and slims sites down for AI crawlers. Now part of Sitecore. `MCP` ([MCP docs](https://developers.scrunch.com/mcp/overview))
- [Seamless.ai](https://seamless.ai) - Contact database that checks the live web to find and confirm prospects' email and phone details. `MCP` ([MCP docs](https://docs.seamless.ai/mcp/access-control))
- [Seismic](https://seismic.com) - Home for sales decks and rep training that large sales teams search and tailor. `MCP`
- [Semrush](https://semrush.com) - SEO and content suite with keyword, backlink and rival data, now measuring AI search visibility. Acquired. `MCP` ([MCP docs](https://semrush.com/mcp))
- [Sendoso](https://sendoso.com) - Sends physical gifts and mailers to prospects when a sales or marketing step fires. `MCP` ([MCP docs](https://www.sendoso.com/platform/features/mcp))
- [Siteimprove](https://www.siteimprove.com) - Checks large websites for SEO and accessibility problems and tracks mentions in AI answers. Acquired. `MCP` ([MCP docs](https://help.siteimprove.com/support/solutions/articles/80001221061-how-to-connect-to-and-use-the-siteimprove-mcp-server))
- [Smartlead](https://www.smartlead.ai) - Agencies and outbound teams send cold email through unlimited mailboxes with automatic warmup. `MCP` `CLI`
- [Snitcher](https://snitcher.com) - Reveals which companies visit your website so sales can follow up with named accounts.
- [Stripe](https://stripe.com) - Payments service developers use to take money online, now usable by AI agents too. `MCP` `CLI` ([MCP docs](https://docs.stripe.com/mcp))
- [Surfe](https://surfe.com) - Checks several data sources for prospect emails and phones, then saves them to your CRM. `MCP` ([MCP docs](https://surfe.com/integrations/mcp))
- [Tally](https://tally.so) - Free online form maker for collecting signups, survey answers, and feedback from customers. `MCP` ([MCP docs](https://tally.so/help/mcp))
- [TrustRadius](https://trustradius.com) - Software review site that passes vendors leads based on what buyers read and compare. Acquired.
- [Typeform](https://typeform.com) - Survey and form maker that asks people one question per screen, like a chat.
- [UpLead](https://uplead.com) - Contact and company database for building prospect lists, backed by a data accuracy guarantee.
- [UserGems](https://usergems.com) - Finds individual buyers who are in market and has its Gem-E agent launch outbound to them. `MCP` ([MCP docs](https://help.usergems.com/article/usergems-mcp-getting-started))
- [Vector](https://vector.co) - Learns who a website visitor is by name, then shows ads to that specific person. `MCP`
- [Warmforge](https://warmforge.ai) - Keeps cold email mailboxes healthy with automatic warmup and alerts when deliverability starts slipping. `MCP` `CLI`
- [Webflow](https://webflow.com) - Design and launch real websites visually, so marketing teams skip waiting on engineers. `MCP` `CLI` ([MCP docs](https://developers.webflow.com/mcp/reference/overview))
- [Wiza](https://wiza.co) - Pulls verified emails and phone numbers from LinkedIn profiles and searches for sales and recruiting. `MCP`
- [Woodpecker](https://woodpecker.co) - Cold email tool that sends step-by-step follow-ups automatically so SDRs get more replies. `MCP` `CLI` ([MCP docs](https://developers.woodpecker.co/docs/mcp/))
- [Yext](https://yext.com) - Keeps brand listings synced across search and AI answers, with Scout showing how AI describes you. `MCP`
- [Zeliq](https://zeliq.com) - Fills in emails and numbers from several providers, then reaches prospects by email, LinkedIn, and phone.
- [Zendesk](https://zendesk.com) - Support ticket desk for chat, phone and email, with AI agents handling simple tickets. Acquired. `MCP` ([MCP docs](https://mcp.zendesk.com))
- [ZoomInfo Chorus AI](https://chorus.ai) - Call recorder from ZoomInfo that spots shaky deals and coaching moments for sales managers. `CLI`

---

The tools below sit outside the developer-tools map but ship an MCP server or a CLI, which is what makes them usable from Claude Code.

## CRM

- [Attio](https://attio.com) - Startup CRM you shape like a database, which AI agents can search and act on. `MCP` ([MCP docs](https://docs.attio.com/mcp/overview))
- [Clarify](https://clarify.ai) - Self-updating CRM that logs your emails, calls, and meetings without manual entry. `MCP` ([MCP docs](https://clarify.ai/integrations/mcp))
- [Day.ai](https://day.ai) - CRM that remembers every call, email, and Slack thread and has assistants update records. `MCP`
- [Lightfield](https://lightfield.app) - AI CRM that writes its own records using your calls and inbox, then prospects and coaches. `MCP` `CLI` ([MCP docs](https://docs.lightfield.app/getting-started/mcp-quickstart/))
- [Monaco](https://monaco.com) - Startup sales system that keeps the CRM and outbound prospecting together, run by agents. `MCP`
- [Reevo](https://reevo.ai) - CRM with prospecting, dialing, sequences, and forecasting in one place, meant to replace several sales tools. `MCP` ([MCP docs](https://help.reevo.ai/AI-and-productivity/Reevo-MCP))
- [Zero](https://zero.inc) - CRM for AI startups where agents read call notes, update deals, and watch accounts. `MCP` ([MCP docs](https://docs.zero.inc/developers/mcp))

## Prospecting and outbound

- [Alta](https://www.altahq.com/) - Named AI agents that research prospects, run outreach, qualify inbound leads, and book meetings. `MCP` ([MCP docs](https://support.altahq.com/en/articles/15517839-connecting-alta-mcp-to-claude))
- [Atonom](https://atonom.ai/) - AI staff handling phone, email, and chat for lead qualifying, booking, support, and hiring screens. `CLI`
- [Coldreach](https://coldreach.ai) - Watches accounts for intent and fires off personalized outbound at volume when it shows up. `MCP` ([MCP docs](https://developer.coldreach.ai/mcp))
- [Enginy.ai](https://enginy.ai) - AI agents that find leads, fill in contact data, and send outbound, formerly called Genesy. `MCP` ([MCP docs](https://docs.enginy.ai/essentials/mcp))
- [Gojiberry AI](https://gojiberry.ai) - Spots warm leads from LinkedIn activity and buying signals, then runs the outreach for you. `MCP` ([MCP docs](https://help.gojiberry.ai/en/articles/14540015-using-the-gojiberry-mcp-server))
- [Harmony.ai](https://harmony.ai/) - Voice agents that take sales calls, qualify leads, book meetings, and hand hot prospects to reps. `MCP` ([MCP docs](https://docs.harmony.ai/mcp/overview/))
- [Humanlinker](https://humanlinker.com) - Reads each prospect's personality cues and suggests how reps should word their outreach. `MCP`
- [Jazon](https://lyzr.ai) - Lyzr's sales agents research accounts, run outreach, and keep CRM deals current. `CLI`
- [Landbase](https://landbase.com) - Describe your ideal buyer in plain words and agents build lists and run outbound. `MCP` `CLI` ([MCP docs](https://docs.landbase.com/mcp))
- [Leadgenerator.io](https://www.leadgenerator.io/) - Agents pick prospects, write and send cold emails from warmed inboxes, and book calls for sellers. `MCP` ([MCP docs](https://www.leadgenerator.io/mcp))
- [Lensmor](https://www.lensmor.com/) - Event prospecting tool that lists who exhibits or attends a trade show, with decision-maker contacts. `MCP` ([MCP docs](https://api.lensmor.com/mcp/overview))
- [MarketBetter AI](https://marketbetter.ai/) - Names anonymous site visitors, ranks their buying intent, then drafts emails and call notes for reps. `MCP` ([MCP docs](https://marketbetter.ai/mcp))
- [Nooks](https://nooks.ai) - SDR dialer that rings several prospects at once, with AI for account research and coaching. `MCP`
- [Obert](https://obert.io/) - Ranks leads by ICP fit, then handles email, LinkedIn, and call outreach for lean founding teams. `MCP` ([MCP docs](https://docs.obert.io/docs/mcp))
- [OpenFunnel](https://openfunnel.dev) - Agents tuned to your product and ICP watch your market for live buying signals. `MCP` ([MCP docs](https://docs.openfunnel.dev/mcp))
- [Persana AI](https://persana.ai) - Lead enrichment plus AI-driven sales agents drawing on many data sources, since shut down. Acquired. `MCP` ([MCP docs](https://persana.ai/persana-mcp))
- [Salesforge.ai](https://salesforge.ai) - Outbound AI rep called Agent Frank, backed by the company's own cold email sending setup. `MCP` `CLI` ([MCP docs](https://help.salesforge.ai/en/articles/10333582-salesforge-mcp-server-with-claude-for-cold-email-and-linkedin-outreach))
- [Signado](https://signado.io/) - Agencies spot leads in LinkedIn comments, score their fit, and keep the thread as an opener. `MCP` ([MCP docs](https://signado.io/mcp))
- [Skyp](https://skyp.ai) - Writes every outbound email and LinkedIn note fresh and runs the domains and warmup behind sending. `MCP` ([MCP docs](https://skyp.ai/mcp))
- [Sprouts Data Intelligence](https://sprouts.ai) - Finds accounts that match your ICP, adds intent data, then runs outbound for ABM teams. `MCP`
- [TalkToHumans](https://www.talktohumans.app/) - Runs LinkedIn outreach from your browser and stops follow-ups as soon as someone replies. `MCP` ([MCP docs](https://www.talktohumans.app/docs/developers/mcp))
- [Unify](https://www.unifygtm.com) - Reps chat with it to find prospects, fill in their details and write outreach sequences. `MCP` ([MCP docs](https://docs.unifygtm.com/developers/mcp/getting-started#claude-desktop-%2F-claude-ai))

## Sales and conversation intelligence

- [Accord](inaccord.com) - Shared deal rooms that turn sales methods like MEDDPICC into playbooks reps must follow. `MCP` ([MCP docs](https://inaccord.com/blog-posts/introducing-the-accord-mcp-server))
- [Actively AI](https://actively.ai) - Assigns one AI agent to each target account to research and work it like a rep. `MCP`
- [Attention](https://attention.com) - Call recorder for sales teams that grades each call and handles CRM updates and follow-up emails. `MCP` ([MCP docs](https://docs.attention.com/mcp/authentication))
- [Circleback](https://circleback.ai) - Meeting notetaker that writes up summaries and action items and updates your CRM afterward. `MCP`
- [Consensus](https://goconsensus.com) - Self-serve product demos that adapt to each buyer, so they can explore before meeting sales. `MCP`
- [Crayon](https://www.crayon.co) - Watches competitor pricing and messaging changes and sends battlecards straight to your reps. Acquired. `MCP` ([MCP docs](https://www.crayon.co/blog/crayon-launches-first-competitive-intelligence-mcp-server))
- [DevRev](https://devrev.ai) - Puts customer support, CRM, and product engineering work in one shared system for software companies. `MCP` `CLI` ([MCP docs](https://developer.devrev.ai/airsync/mcp))
- [Dialfyne](https://dialfyne.com/) - Power dialing, email, and AI practice calls for SDR teams, paid by the minute. `MCP` ([MCP docs](https://dialfyne.com/mcp))
- [Dock](https://www.dock.us/) - Shared deal rooms plus a sales content library that can power buyer-facing AI agents. `MCP` ([MCP docs](https://help.dock.us/en/collections/19692365-dock-s-mcp))
- [Endgame](https://endgame.io) - Builds a searchable map of calls, deals, and emails so reps and agents prep for meetings. `MCP` ([MCP docs](https://docs.endgame.io/features/mcp-server))
- [Fathom](https://fathom.ai) - Bot-free call recorder that sends summaries into your CRM and chat assistants. Now part of Superhuman. `MCP`
- [Fireflies](https://fireflies.ai) - Call notetaker that records and writes up Google Meet, Zoom and Teams calls, all searchable later. `MCP` ([MCP docs](https://docs.fireflies.ai/getting-started/mcp-configuration))
- [Forgeby](https://forgeby.com/) - Give it a sales goal and it researches accounts, writes emails, and handles follow-ups. `MCP` ([MCP docs](https://forgeby.com/mcp.html))
- [Grain](https://grain.com) - Captures sales call recordings and transcripts, then flags deal signals worth a coaching chat. `MCP`
- [Granola](https://granola.ai) - Meeting notepad that expands your quick jottings into complete write-ups, for people stacked with calls. `MCP` ([MCP docs](https://docs.granola.ai/help-center/sharing/integrations/mcp))
- [Guru](https://www.getguru.com) - Company knowledge base that keeps facts checked and gives sourced answers to staff and AI tools. `MCP`
- [HighLevel](https://www.gohighlevel.com) - CRM and marketing toolkit agencies rebrand as their own and sell to small-business clients. `MCP`
- [Highspot](https://highspot.com) - Gives reps the right decks, coaching, and next steps for each live deal. Acquired. `MCP` ([MCP docs](https://highspot.com/product/mcp-server/))
- [Introhive](https://introhive.com) - Digs up who knows whom inside CRM records for business development teams at services firms. `MCP` ([MCP docs](https://www.introhive.com/introhive-mcp/))
- [Introw](https://www.introw.io) - Channel teams manage partners, deal registration, and content from Slack and the CRM, no portal. `MCP` ([MCP docs](https://www.introw.io/integrations/mcp))
- [Klue](https://klue.com) - Collects competitor news from many sources and your reps, then packages it as sales battlecards. `MCP` ([MCP docs](https://github.com/kluein/klue-mcp-public))
- [Microsoft Dynamics 365 Sales](dynamics.microsoft.com) - Microsoft's enterprise CRM, where built-in agents qualify leads and warn sales leaders about risky deals. `MCP` ([MCP docs](https://dynamics.microsoft.com/mcp))
- [Minoa](https://www.minoa.io) - Drafts ROI cases from CRM and call data, then checks the promised value after purchase. `MCP` ([MCP docs](https://www.minoa.io/mcp))
- [Mutiny](https://mutinyhq.com) - Sellers ask it from Claude or ChatGPT for branded deal rooms, decks and prospect pages. `MCP`
- [Navattic](navattic.com) - Makes clickable product tours with no code that reps can send to buyers. `MCP` ([MCP docs](https://docs.navattic.com/mcp))
- [Nex.ai](https://nex.ai) - Watches sellers work in HubSpot, Gong, and Slack, then sets up agents to copy those routines. `MCP` `CLI` ([MCP docs](https://nex.ai/blog/nex-mcp-server))
- [PartnerStack](https://partnerstack.com) - Finds, signs up, and pays affiliates and resellers for B2B software companies. `MCP` ([MCP docs](https://partnerstack.com/mcp))
- [Peppr](https://www.usepeppr.ai/) - Listens on live calls, showing reps answers and playbook nudges the moment a buyer asks something. `MCP` ([MCP docs](https://docs.usepeppr.ai/mcp))
- [Reprise](reprise.com) - Copies your product's front end into realistic demo setups that sales engineers tailor for each buyer. `MCP` ([MCP docs](https://www.reprise.com/platform/mcp))
- [Salesfinity](https://salesfinity.ai) - Dialer that calls many prospects at once, coaches reps live, and logs calls in the CRM. `MCP` ([MCP docs](https://docs.salesfinity.ai/mcp/overview))
- [Showpad](https://showpad.com) - Stores sales decks and training, then shows which buyers open and engage with them. Acquired. `MCP` `CLI` ([MCP docs](https://developer.showpad.com/docs/integrations/platform-independent/mcp))
- [SiftHub](https://sifthub.io) - Drafts RFP and security questionnaire answers from your knowledge base, then prompts reps during live calls. `MCP` ([MCP docs](https://www.sifthub.io/mcp))
- [SoundGTM](https://soundgtm.com) - Founders track partner-sourced deals, work out commissions, and line up Stripe payouts in one place. `MCP`
- [Spekit](spekit.com) - Pops up coaching and sales content in Slack and Salesforce while reps work their deals. `MCP` ([MCP docs](https://www.spekit.com/platform/mcp))
- [Spotlight.ai](https://www.spotlight.ai/) - Reads call recordings and email threads, then fills in MEDDPICC and warns about shaky deals. `MCP` ([MCP docs](https://www.spotlight.ai/knowledge-graph-mcp))
- [Streak](https://www.streak.com) - Small teams run deals, mail merges, and open tracking from a CRM built into Gmail. `MCP` ([MCP docs](https://streak.com/integrations/mcp))
- [Supademo](https://supademo.com) - Records product screens into click-through demos that AI can narrate and tailor for each prospect. `MCP` ([MCP docs](https://supademo.com/mcp))
- [Sybill AI](https://www.sybill.ai) - Reads buyer words and body cues on calls, then drafts recaps and fills in the CRM. `MCP`
- [tl;dv](https://tldv.io) - Free meeting recorder with no bot that sends AI call summaries into your CRM. `MCP`
- [valueIQ](https://valueiq.ai) - Drafts business cases for live deals and compares rival pricing, for teams without value engineers. `MCP` ([MCP docs](https://valueiq.ai/mcp))
- [Walnut](walnut.io) - Captures a click-through of your product and turns it into a tailored demo for sales teams. `MCP`

## Customer success and support

- [Agency](https://agency.inc) - AI coworker that handles daily customer success tasks so each CSM can cover more accounts. `MCP`
- [Fin (Intercom)](https://intercom.com) - Helpdesk whose Fin agent answers customers on chat, email and phone. Now part of Salesforce. `MCP` ([MCP docs](https://developers.intercom.com/docs/guides/mcp))
- [Gainsight](https://gainsight.com) - Customer success software that rates account health and kicks off renewal plays. Acquired. `MCP` ([MCP docs](https://support.gainsight.com/gainsight_nxt/AI_Assistants/MCP_Integration/Admin_Guide/Set_Up_Gainsight_CS_MCP_Server_Integration))
- [Lorikeet](https://lorikeetcx.ai) - AI support agent for fintech, health, and insurance firms that settles tricky cases on any channel. `MCP`
- [Oliv AI](https://oliv.ai) - Dozens of named sales agents that log meetings, keep the CRM current, and coach reps. `MCP`
- [Planhat](planhat.com) - Customer success hub that pulls usage, support, and contract data together and runs agents on it. `MCP` ([MCP docs](https://docs.planhat.com/mcp))
- [QuadSci](https://quadsci.ai) - Forecasts which SaaS customers will churn or grow, months in advance, using product and call data. `MCP`
- [Vitally](vitally.io) - Gives CS leaders playbooks, shared plans, and health scores built from product and CRM data. `MCP` ([MCP docs](https://docs.vitally.io/en/articles/15862100-vitally-mcp-server))

## Marketing execution

- [Amperity](https://amperity.com) - Matches records about the same shopper across sources into one profile for big consumer brands. `MCP`
- [Bloomreach](https://bloomreach.com) - Online store marketing that decides what each shopper sees next across email, site, and ads. `MCP` ([MCP docs](https://documentation.bloomreach.com/loomi-connect/docs/get-started-with-mcp))
- [BlueConic](https://www.blueconic.com) - B2C marketers get live customer profiles and AI agents that run campaigns inside set limits. `MCP` ([MCP docs](https://support.blueconic.com/en/articles/415706-blueconic-model-context-protocol-mcp))
- [Brand24](https://brand24.com) - Social listening for agencies and brand marketers, catching mentions and sentiment across web and social. `MCP` ([MCP docs](https://help.brand24.com/en/articles/13011375-brand24-mcp))
- [Brevo](https://brevo.com) - Email and SMS marketing for small businesses that also includes a contact manager and chat. `MCP` ([MCP docs](https://developers.brevo.com/docs/mcp-protocol))
- [Brew](https://brew.new/) - Founders get on-brand emails drafted from prompts, with style picked up from their own site. `MCP` `CLI` ([MCP docs](https://docs.brew.new/api-reference/mcp/overview))
- [Buffer](buffer.com) - Plans and publishes posts on over ten social networks from a shared calendar for solo creators. `MCP` ([MCP docs](https://developers.buffer.com/guides/integrations/mcp.html))
- [Cordial](https://cordial.com/) - Lifecycle messaging tool with its own customer database that picks who gets what, where, and when. `MCP` `CLI` ([MCP docs](https://developers.cordial.com/mcp/))
- [Elastic Email](https://elasticemail.com) - Email sender covering both app-triggered messages and bulk marketing campaigns, for coders and marketers. `MCP` ([MCP docs](https://elasticemail.com/mcp))
- [Enrich Labs](https://www.enrichlabs.ai) - An AI marketer named Helena reads your ad and analytics accounts, then plans and runs campaigns. `MCP`
- [Events.com](https://events.com) - Event software covering ticket sales, sponsor deals, and door check-in for conference organizers. `MCP` ([MCP docs](https://mcp.events.com))
- [Everflow](https://www.everflow.io) - Partner marketing tool that measures affiliate and influencer results and pays partners automatically. `MCP` ([MCP docs](https://developers.everflow.io/ai-automation/mcp/examples))
- [FirstPromoter](https://firstpromoter.com) - Tracks recurring affiliate commissions for SaaS companies by plugging into Stripe, Paddle, or Chargebee. `MCP` ([MCP docs](https://docs.firstpromoter.com/mcp/overview))
- [Folloze](https://www.folloze.com) - ABM teams give it a brief and get landing pages, emails, and ads tailored per account. `MCP` ([MCP docs](https://engage.folloze.com/follozemcp))
- [Gradial](https://gradial.com) - Marketing ops agents that clear page edit, asset, and QA requests for enterprise teams. `MCP` ([MCP docs](https://docs.gradial.com/docs/integrations-administration-and-setup/integrations/custom-mcp))
- [Hootsuite](https://hootsuite.com) - Plan, publish, and measure social media posts across many networks from a single dashboard. `MCP` ([MCP docs](https://www.hootsuite.com/integrations/mcp))
- [iCustomer](https://www.icustomer.ai/) - Agents rank buyers from your warehouse data and tell campaign tools who to target and when. `MCP`
- [Inflection.io](https://inflection.io) - Marketing automation for B2B teams built on product usage data, pitched as a Marketo swap. `MCP` ([MCP docs](https://docs.inflection.io/agents/inflection-mcp))
- [Insider](useinsider.com) - Customer data hub where AI agents choose and send messages over email, SMS, WhatsApp, and push. `MCP` ([MCP docs](https://useinsider.com/mcp))
- [Jasper AI](https://jasper.ai) - Shows where AI answer engines cite your brand, then drafts and posts content to improve it. `MCP`
- [Kindling](https://www.kindlinghq.com) - Turns your B2B customers into paid creators and manages their rates and payouts. `MCP` ([MCP docs](https://www.kindlinghq.com/docs/mcp/))
- [MailerLite](https://www.mailerlite.com) - Simple newsletter and email campaign tool for small businesses and solo creators. Acquired. `MCP`
- [Meltwater](https://meltwater.com) - Watches news and social media worldwide so PR teams see what's said about them. Acquired. `MCP` ([MCP docs](https://developer.meltwater.com/guides/meltwater-mcp/overview/))
- [MoEngage](https://moengage.com) - Consumer marketing tool whose agents write campaigns, run tests, and personalize push, SMS, and email. `MCP` ([MCP docs](https://moengage.com/docs/mcp))
- [OneSignal](onesignal.com) - Growth teams message app users by push, text, email, or in-app, with AI drafting and testing. `MCP` ([MCP docs](https://documentation.onesignal.com/docs/en/model-context-protocol))
- [Optimove](https://optimove.com) - Plans retention and lifecycle messages across channels using what you know about each customer. `MCP` ([MCP docs](https://developer.optimove.com/docs/optimove-mcp-connector))
- [Ortto](ortto.com) - Marketing automation, customer data, and analytics together, so small teams build email and SMS journeys. `MCP` ([MCP docs](https://ortto.com/learn/ortto-mcp-connect-ai-to-your-customer-data-for-smarter-insights/))
- [Postscript](https://postscript.io) - Text message marketing for Shopify stores sending SMS and MMS campaigns to shoppers. `MCP` ([MCP docs](https://docs.postscript.io/mcp))
- [Rokt mParticle](https://mparticle.com) - Customer data hub that merges your own data and has AI suggest audiences to launch. Acquired. `MCP` `CLI` ([MCP docs](https://docs.mparticle.com/mcp))
- [Sequel](https://sequel.io) - Hosts webinars under your company's web address, with AI that recycles talks into clips and posts. `MCP` ([MCP docs](https://sequel.io/platform/mcp-server))
- [Spectacle](https://www.spectaclehq.com) - B2B marketers track visits on their own domain and send won-deal revenue to their ad platforms. `MCP`
- [Tealium](https://tealium.com) - Collects customer data from sites, apps, and offline sources and sends it to marketing tools live. `MCP` ([MCP docs](https://docs.tealium.com/server-side/context-api/managed-mcp-server/))
- [Writer](https://writer.com) - Enterprise writing assistant running on Writer's Palmyra models that keeps company content on brand. `MCP`
- [Zeotap](https://zeotap.com) - Links anonymous customers across devices and adds outside data so large consumer brands target better. `MCP` ([MCP docs](https://docs.zeotap.com/mcp))

## Advertising

- [AdRoll](adroll.com) - Retargets past site visitors with display, social, and streaming TV ads from one bidding system. `MCP` ([MCP docs](https://help.adroll.com/hc/en-us/articles/44128588376077-AdRoll-MCP-Server-Beta))
- [Adverity](https://adverity.com) - Gathers ad spend and campaign data from many sources and tidies it up for reporting. `MCP` ([MCP docs](https://docs.adverity.com/guides/mcp/mcp-setup.html))
- [AppsFlyer](https://appsflyer.com) - Tells mobile marketers which ads bring in app downloads and sends users to the correct screen. `MCP` ([MCP docs](https://www.appsflyer.com/products/agentic-ai/mcp/))
- [Fibbler](fibbler.co) - Connects Google and LinkedIn ad activity to pipeline, then nudges reps when accounts get hot. `MCP` ([MCP docs](https://www.fibbler.co/docs/mcp/getting-started))
- [Funnel](https://funnel.io) - Gathers ad and campaign numbers from all your channels, cleans them, and feeds your dashboards. `MCP` ([MCP docs](https://funnel.io/funnel-mcp))
- [Higgsfield](https://higgsfield.ai) - Ad and social teams generate lots of video and image creative from prompts. `MCP` `CLI` ([MCP docs](https://higgsfield.ai/mcp))
- [HockeyStack](https://hockeystack.com) - Revenue analytics with agents that copy how your best deals were won and work enterprise deals. `MCP` ([MCP docs](https://docs.hockeystack.com/marketing-intelligence/mcp))
- [Impact.com](impact.com) - Runs affiliate and creator partnerships, tying their traffic to real sales and paying them out. `MCP` ([MCP docs](https://integrations.impact.com/ai-solutions/mcp-quick-start))
- [Influ2](https://www.influ2.com) - Shows ads to named people at target accounts and reports who actually saw them. `MCP` ([MCP docs](https://www.influ2.com/playbooks/influ2-mcp-promptbook))
- [Lifesight](https://lifesight.io/) - Measures which marketing spend works through mix models and lift tests, then lets agents shift budgets. `MCP` ([MCP docs](https://lifesight.io/mcp/))
- [Madhive](https://madhive.com) - Plans, buys, and measures streaming TV ads for local broadcasters and political campaigns in one place. `MCP`
- [Metadata](metadata.io) - Creates and runs B2B ad campaigns on many channels while marketers keep control of spend. `MCP`
- [Moloco](https://moloco.com) - Machine learning ad buying for apps and connected TV, plus tools for retailer ad networks. `MCP` ([MCP docs](https://developer.moloco.cloud/docs/mcp-getting-started))
- [Omneky](omneky.com) - Paid social marketers feed in one brief and get videos, ad images, and creator-style clips back. `MCP` ([MCP docs](https://www.omneky.com/mcp))
- [Permutive](https://permutive.com) - Publisher audience tool that targets and measures ads without third-party cookies. `MCP` ([MCP docs](https://docs.permutive.com/api/mcp/get_cohort_detail))
- [Propensity](https://www.propensity.com) - Names the people visiting your site, fills in their details, and targets them with ads. `MCP`
- [Recast](https://getrecast.com) - Marketing mix models updated every week, showing which channels really bring in revenue. `MCP`
- [Ryze AI](https://www.get-ryze.ai) - Performance marketers hand ad tuning, SEO checks, and landing page builds to autonomous AI agents. `MCP`
- [Supermetrics](https://supermetrics.com) - Copies campaign numbers from every ad account into spreadsheets or BI tools for marketing reports. `MCP` ([MCP docs](https://mcp.supermetrics.com))
- [Synter](https://synterai.com/) - Hooks AI agents up to your ad accounts to run campaigns within set budgets and approvals. `MCP` `CLI` ([MCP docs](https://docs.synterai.com/mcp/configuration))
- [Tofu](https://tofuads.com/) - Writes tailored ads, emails, and web pages for each account in a B2B campaign. `MCP` ([MCP docs](https://ads.tofuhq.com/mcp/setup))
- [Universal Ads](https://www.universalads.com/) - Comcast's self-serve streaming TV ads for small brands, with no spend floor or contract lock-in. `MCP` ([MCP docs](https://www.universalads.com/mcp))
- [Upside](https://upside.tech) - Joins scattered CRM, inbox, and call records into one account map that agents can query. `MCP` ([MCP docs](https://docs.upside.tech/docs/upside-mcp))
- [Vibe.co](https://vibe.co) - Self-serve TV streaming ads for small businesses, with AI-made video and targeting. Now part of Walmart. `MCP` ([MCP docs](https://vibe.co/integrations/mcp))
- [Windsor.ai](https://windsor.ai) - Analysts move campaign data from ad tools into warehouses, dashboards, or chat assistants without code. Acquired. `MCP`

## AEO and AI search visibility

- [AirOps](https://airops.com) - Content teams audit their AI answer presence, then generate and ship pages to raise it. `MCP`
- [Amplitude AI Visibility](https://amplitude.com/ai-visibility) - Measures how ChatGPT and Google's AI answers talk about your brand and links it to revenue. `MCP` `CLI` ([MCP docs](https://amplitude.com/mcp))
- [Blastra](https://blastra.io) - Completes your profiles on 28 review sites like G2 so AI assistants recommend you. `MCP` ([MCP docs](https://blastra.io/docs/mcp-connector))
- [DemandSphere](https://www.demandsphere.com/) - Follows search positions, AI Overview spots, and citations of your brand across many markets and engines. `MCP` ([MCP docs](https://www.demandsphere.com/research/demandsphere-radar/mcp/))
- [GrowthX](https://growthx.ai) - Content teams use its AI agents to write and publish pages that AI answers cite. `MCP` ([MCP docs](https://growthx.ai/docs/product/admin/mcp-server))
- [Lightsage](https://lightsage.com) - Shows devtool marketers whether coding assistants suggest their product and how their docs compare to rivals. `MCP` ([MCP docs](https://lightsage.com/leaderboard/claudecode/mcp))
- [Limy AI](https://limy.ai) - Shows brands how they come up in ChatGPT-style answers and how to improve it. `MCP` ([MCP docs](https://docs.getlimy.ai/mcp/limy-mcp-server))
- [Local Falcon](https://www.localfalcon.com) - Tracks local map rankings store by store and now checks brand visibility in ChatGPT and Gemini. `MCP` ([MCP docs](https://www.localfalcon.com/features/mcp))
- [Profound](https://tryprofound.com) - Shows brands where they turn up in Gemini, ChatGPT and Perplexity answers, with agents drafting fixes. `MCP` ([MCP docs](https://tryprofound.com/docs/mcp))
- [Prominara](https://prominara.com) - Spots where AI answer engines skip your brand, drafts fixes, and checks if citations improve. `MCP`
- [Ranked AI](https://www.ranked.ai) - White-label tracker for brand rankings in AI chat answers that agencies resell to their clients. `MCP` ([MCP docs](https://www.ranked.ai/developers/mcp/overview))
- [Searchable](searchable.com) - Shows marketers how often AI assistants like ChatGPT and Perplexity mention their brand. `MCP` ([MCP docs](https://docs.searchable.com/integrations/mcp))
- [seoClarity](seoclarity.net) - SEO toolkit for big teams that also watches and repairs how you appear in AI answers. `MCP` ([MCP docs](https://www.seoclarity.net/ai-seo/mcp-server))
- [Writesonic](writesonic.com) - Shows how often AI chatbots cite your brand, then sends agents to fill content gaps. `MCP` ([MCP docs](https://writesonic.com/mcp))

## Website and inbound

- [Acquia](https://acquia.com) - Hosts and manages big company websites built on Drupal, with marketing tools on top. Acquired. `MCP` ([MCP docs](https://docs.acquia.com/source-cms/source-cms-mcp-server))
- [Chameleon](chameleon.io) - Product tours and checklists inside your app, with AI that spots friction and retires stale guides. `MCP`
- [Default](https://www.default.com) - Sends each inbound lead to the right rep after checking fit, plus an agent named Dot. `MCP` ([MCP docs](https://docs.os.default.com/mcp-server))
- [Docket](https://docket.io) - Website agent that talks with visitors over voice or text, qualifies them and books meetings. `MCP` ([MCP docs](https://help.docket.io/en/articles/8225942528-connect-docket-demand-mcp))
- [Flint](https://www.flint.com) - Creates a landing page for each ad campaign and applies Google Ads edits after your approval. `MCP`
- [Framer](https://framer.com) - Website builder where marketers design, edit, and publish live sites with an AI helper. `MCP`
- [Instapage](instapage.com) - Landing page builder for ad campaigns, with heatmaps and A/B tests to lift conversions. `MCP` ([MCP docs](https://instapage.com/mcp))
- [Kameleoon](https://www.kameleoon.com) - A/B testing tool where you describe an experiment in words and an agent builds it. `MCP` ([MCP docs](https://docs.kameleoon.com/de/mcp/claude-connector))
- [Landingi](https://landingi.com) - Agency-friendly page builder that drafts landing pages with AI, split tests them, and mass-produces variants. `MCP` ([MCP docs](https://mcp.landingi.com/docs))
- [Leadpages](leadpages.com) - Landing page maker for small businesses that keeps A/B testing and sends visitors to the winner. `MCP` ([MCP docs](https://leadpages.com/developers/mcp))
- [Optimizely](https://www.optimizely.com) - Enterprise A/B testing and content management, with AI agents that help test and personalize web pages. `MCP`
- [Ploy](https://ploy.ai) - Growth teams hand site building, visitor spotting and ad campaigns to a crew of AI agents. `CLI`
- [Sitecore](https://sitecore.com) - Content system for big global brands that runs websites, commerce, and personalization together. Acquired. `MCP` ([MCP docs](https://doc.sitecore.com/sai/users/sitecoreai/sitecore-marketer-mcp-server/sitecore-marketer-mcp-server.html))
- [Syft Data](https://syftdata.com) - Reveals who visits your site or engages on LinkedIn, rates their fit, and kicks off outreach. `MCP`
- [Uniform](https://www.uniform.dev) - Visual workspace on a headless stack so marketers change pages without filing developer tickets. `MCP` `CLI` ([MCP docs](https://www.uniform.dev/integrations/mcp))
- [Userpilot](https://userpilot.com) - In-app guides, surveys, and usage analytics, plus an agent that builds onboarding flows for you. `MCP` ([MCP docs](https://docs.userpilot.com/ai/userpilot-mcp-server))
- [VWO](https://vwo.com) - Runs A/B tests and records how visitors behave, with AI that suggests and drafts test versions. `MCP` ([MCP docs](https://developers.wingify.com/v2/docs/fme-mcp-server))
- [Warmly](https://warmly.ai) - Unmasks site visitors for AI agents to phone, email or chat. Now part of HubSpot. `MCP`
- [Webless](https://webless.ai) - Swaps site search for an AI answer box, showing marketers what visitors ask and what's missing. `MCP` ([MCP docs](https://docs.webless.ai/mcp))
- [Zoovu](https://zoovu.com) - Quiz-style product finders that guide online shoppers toward a good match in sprawling catalogs. `MCP` ([MCP docs](https://docs.zoovu.com/tags/mcp))

## Creative and content

- [Air](https://air.inc) - Shared visual library where creative teams store, review, and approve brand assets. `MCP` ([MCP docs](https://help.air.inc/en/articles/15015243-setting-up-air-s-mcp-server-for-claude-desktop))
- [Artlist](https://artlist.io) - Royalty-free music, sound effects, and stock video, plus an AI studio for making video scenes. `MCP` ([MCP docs](https://help.artlist.io/hc/en-us/articles/38948588333469-Artlist-MCP-Connect-Claude-ChatGPT-and-VS-Code-to-Artlist))
- [Beautiful.ai](https://beautiful.ai) - Builds slide decks from a short description, with layouts that adjust themselves while you edit. `MCP` ([MCP docs](https://support.beautiful.ai/hc/en-us/articles/44246954338829-Beautiful-ai-MCP-Quick-Setup-FAQ))
- [beehiiv](https://www.beehiiv.com) - Newsletter tool for publishers that handles sending, websites, audience growth, ad income and paid tiers. `MCP` ([MCP docs](https://www.beehiiv.com/mcp))
- [Canva](https://canva.com) - Simple design editor where non-designers make graphics, slide decks and videos by dragging pieces around. `MCP` ([MCP docs](https://www.canva.dev/docs/apps/dev-mcp-server/))
- [Descript](https://descript.com) - Video and podcast editor where you cut footage by deleting words in the transcript. `MCP` ([MCP docs](https://help.descript.com/developers/mcp/overview))
- [Favikon](https://www.favikon.com) - Rates millions of creators for real engagement and fake followers before brands partner with them. `MCP` ([MCP docs](https://app.favikon.com/mcp/))
- [Gamma](https://gamma.app) - Turns a prompt into on-brand slides, docs and web pages you then edit by chatting. `MCP` ([MCP docs](https://developers.gamma.app/mcp/gamma-mcp-server))
- [HeyGen](https://heygen.com) - Makes presenter videos from a script, with voice cloning and lip-matched translation for marketing teams. `MCP` `CLI` ([MCP docs](https://heygen.com/mcp))
- [OpusClip](https://opus.pro) - Finds the best moments in long videos and cuts them into shorts for social channels. `MCP` ([MCP docs](https://www.opus.pro/mcp))
- [Pika Labs](https://pika.art) - Ad teams mix several AI models to make video and images, reusing the same characters throughout. `MCP` ([MCP docs](https://pika.art/mcp))
- [Riverside](riverside.fm) - Remote podcast studio that records each guest in high quality and cuts clips with AI. `MCP` ([MCP docs](https://riverside.fm/mcp))
- [Runway](https://runwayml.com) - Video generation and editing for creative teams, mixing its own models with rivals like Kling. `MCP` ([MCP docs](https://mcp.runwayml.com))
- [Syllaby](https://syllaby.io/) - Creators type an idea and get a script, an avatar video with voiceover, and scheduled posts. `MCP` ([MCP docs](https://syllaby.io/mcp/))
- [Templafy](https://templafy.com) - Large companies use it to keep Word and PowerPoint documents on brand with shared templates. `MCP` ([MCP docs](https://www.templafy.com/home/platform/mcp/))
- [Typeface](https://typeface.ai) - Creates marketing copy and images that follow a large company's brand style and assets. `MCP` ([MCP docs](https://www.typeface.ai/mcp))
- [Upfluence](https://www.upfluence.com) - Searches millions of creators, runs influencer campaigns, pays creators, and tracks the sales they drive. `MCP` ([MCP docs](https://www.upfluence.com/platform/upfluence-mcp))

## Data and intelligence

- [Alysio](https://alysio.ai) - Reps ask questions and trigger automations across GTM tools here instead of opening the CRM. `MCP` ([MCP docs](https://alysio.ai/mcps))
- [Bloomberry](https://bloomberry.com) - Alerts sales teams when companies start or stop paying for specific B2B software products. `MCP`
- [BuyerCaddy](https://buyercaddy.com/) - Shows which of 171,000+ software products companies run, plus wasted spend and purchase signals. `MCP` ([MCP docs](https://buyercaddy.com/mcp))
- [CaliberMind](https://calibermind.com) - Warehouse of GTM tool data used to score accounts and credit touches. Now part of Integrate. `MCP` ([MCP docs](https://docs.calibermind.com/agent-cal/calibermind-mcp-server/))
- [CompanyEnrich](https://companyenrich.com) - Company lookups, people search, and lookalike discovery that agents can call directly. `MCP` ([MCP docs](https://docs.companyenrich.com/docs/mcp-server))
- [Data Legion](https://www.datalegion.ai) - People and company data sold per call, payable by agents with stablecoins. `MCP` `CLI` ([MCP docs](https://www.datalegion.ai/docs/integrations/mcp-server))
- [Databox](https://databox.com) - Marketers pull KPIs from over 130 apps into live dashboards, then quiz an AI analyst. `MCP` ([MCP docs](https://developers.databox.com/docs/mcp/overview))
- [Dreamdata](https://dreamdata.io) - Maps each B2B buyer's journey across channels and links every touch to revenue. `MCP` ([MCP docs](https://developer.dreamdata.io/mcp/mcp-server/))
- [Dun & Bradstreet](dnb.com) - Business credit and company records tied to its DUNS ID, for sales and risk teams. Acquired. `MCP` ([MCP docs](https://www.dnb.com/en-us/solutions/artificial-intelligence/connectors/dnb-mcp.html))
- [Floqer](https://floqer.com) - Fills CRM gaps from many data sources and starts routing or outreach when accounts change. `MCP` ([MCP docs](https://floqer.com/docs/mcp/getting-started))
- [Freckle.io](https://www.freckle.io) - Terminal tool for GTM engineers that runs enrichment workflows across 40+ data vendors with coding agents. `CLI`
- [Improvado](https://improvado.io) - Merges data from over a thousand marketing sources so analysts and AI agents can ask questions. `MCP` ([MCP docs](https://improvado.io/docs-section-topic/improvado-mcp-text))
- [Keyplay](https://keyplay.io) - Scores how well accounts fit your ICP and helps pick which to target. Acquired. `MCP` ([MCP docs](https://docs.keyplay.io/en/articles/13643214-keyplay-mcp))
- [Kooperativa.io](https://kooperativa.io/) - Person and company records for RevOps, with alerts when someone switches jobs or headcount moves. `MCP` ([MCP docs](https://docs.kooperativa.io/mcp))
- [Leadspace](leadspace.com) - Scores how well each account matches your ICP, then syncs those scores to Salesforce or Marketo. `MCP` ([MCP docs](https://www.leadspace.com/solutions/leadspace-mcp))
- [pipe0](https://www.pipe0.com/) - Runs contact and company lookups through dozens of data sources in order, for GTM builders. `MCP` ([MCP docs](https://pipe0.com/docs/sdks/mcp))
- [Reo.Dev](https://www.reo.dev/) - Spots developers at target accounts from GitHub, npm, and Docker activity, for sellers of technical products. `MCP` `CLI` ([MCP docs](https://mcp.reo.dev))
- [RevSure AI](https://www.revsure.ai) - Joins call, CRM, and marketing data so AI agents can spot deals at risk. `MCP` ([MCP docs](https://documents.revsure.ai/docs/revsure-mcp-server-1))
- [Rings AI](https://www.rings.ai) - Venture capital, banking, and buyout teams use it to find warm intros through colleagues' contacts. `MCP` ([MCP docs](https://docs.rings.ai/guides/mcp))
- [SegmentStream](https://segmentstream.com) - Works out which ads drive sales through attribution and lift tests, then shifts budget between platforms. `MCP` `CLI` ([MCP docs](https://docs.segmentstream.com/mcp/overview))
- [Sillage](https://www.getsillage.com/) - Feeds GTM agents signals like job changes, new hires, and competitor engagement on accounts. `MCP` ([MCP docs](https://www.getsillage.com/docs/mcp))
- [Similarweb](https://www.similarweb.com) - Estimates website and app traffic so marketers can size up competitors and spot market shifts. `MCP`
- [SixtyFour](https://www.sixtyfour.ai) - Investigation agents that follow a person or company through records and online sources, for risk teams. `MCP`
- [SparkToro](https://sparktoro.com) - Audience research tool that reveals the podcasts, websites, and social profiles your buyers pay attention to. `MCP` ([MCP docs](https://sparktoro.com/mcp))
- [Sumble](https://sumble.com) - Reads job postings to tell sellers which companies run which software. `MCP` ([MCP docs](https://sumble.com/integrations/mcp))
- [The Org](https://theorg.com) - Public org charts showing who runs each team, useful for recruiters and sellers before reaching out. `MCP` ([MCP docs](https://developers.theorg.com/mcp))
- [Trigify](https://trigify.io) - Watches CRM changes and LinkedIn activity, then alerts SDRs when an account looks ready to buy. `MCP` `CLI`
- [TwitterAPI.io](https://twitterapi.io/) - Pulls profiles, posts, and follower lists from X, feeding social monitoring apps and GTM agents. `MCP` ([MCP docs](https://twitterapi.io/twitter-mcp-server))
- [WhiteWhale](https://getwhitewhale.com) - Watches accounts for the signals you choose and posts cited alerts to Slack or your CRM. `MCP` ([MCP docs](https://www.getwhitewhale.com/integrations/mcp))
- [Wynter](https://wynter.com) - Tests your messaging and landing pages with real B2B buyers and scores how clear it is. `MCP` ([MCP docs](https://wynter.com/docs/mcp))

## GTM infrastructure

- [Frontrunner](https://usefr.com) - Agent workspace where sales teams define buying signals, then run research, routing, and CRM cleanup. `MCP` ([MCP docs](https://dev.usefr.com/docs/mcp))
- [GrowthBook](https://www.growthbook.io) - Open-source A/B tests and feature toggles that calculate results from your own warehouse. `MCP` `CLI`
- [GrowthLoop](https://www.growthloop.com) - Customer data tool on top of your warehouse where AI agents build audiences and launch campaigns. `MCP` ([MCP docs](https://docs.growthloop.com/mcp))
- [looot](https://looot.ai/) - One key gives agent builders access to many data providers, switching sources when a lookup misses. `MCP` `CLI` ([MCP docs](https://docs.looot.ai/get-started/quickstart-mcp))
- [Orbitype](https://www.orbitype.com) - Cloud workspace where agents and fixed automations handle prospecting, enrichment, and outreach for RevOps teams. `MCP`
- [Polytomic](https://www.polytomic.com) - Two-way data syncing that links a warehouse to tools such as Salesforce or HubSpot for RevOps. `MCP` ([MCP docs](https://docs.polytomic.com/mcp))
- [Poolside AI](https://poolside.ai) - Open-weight coding models in large cloud and small on-device sizes for teams building coding agents. `MCP` `CLI`
- [Redpoint Global](https://www.redpointglobal.com) - Enterprise customer data tool that links profiles right in Snowflake without copying your data elsewhere. `MCP`
- [Riisp](https://www.riisp.com) - Spots drift in HubSpot pipelines, lead routing, and attribution, then fixes problems once RevOps signs off. `MCP`
- [Scalebrowser](https://scalebrowser.net/) - Gives each browser agent a separate, lasting profile so sessions and device fingerprints survive between runs. `MCP` `CLI` ([MCP docs](https://scalebrowser.net/docs/agents/mcp-server))
- [Sweep.io](https://www.sweep.io) - Maps, documents, and automates the setup behind a Salesforce org so admins can change it safely. `MCP` ([MCP docs](https://www.sweep.io/sweep-model-context-protocol))
- [Vibe Prospecting](https://www.vibeprospecting.ai) - Type a plain request in Claude and get back a list of matching B2B leads. `MCP` ([MCP docs](https://www.explorium.ai/mcp/))
- [Viktor](https://viktor.com) - Slack and Teams coworker that hooks into thousands of business tools and finishes tasks for founders. `MCP` `CLI` ([MCP docs](https://viktor.com/docs/mcp-server))
- [Vinkius](https://vinkius.com/) - Shared connection layer that links agents to apps and databases, handling logins, permissions, and action logs. `MCP` `CLI` ([MCP docs](https://vinkius.com/learn/en/mcp-fusion))

## Other GTM tools

- [Anthropic](https://anthropic.com) - AI lab that makes Claude for chat, coding through Claude Code, and building apps. `MCP` ([MCP docs](https://docs.anthropic.com/mcp))
- [Claude Cowork](https://claude.com) - Anthropic's all-round AI agent that helps with everyday knowledge work, not just sales tasks. `MCP` ([MCP docs](https://docs.anthropic.com/mcp))
- [Fullstory](https://fullstory.com) - Records every click on a website so teams and agents can replay sessions and spot friction. `MCP` ([MCP docs](https://developer.fullstory.com/mcp/introduction/))
- [Glean](https://glean.com) - Searches across a company's work apps and answers questions while respecting who can see what. `MCP` ([MCP docs](https://docs.glean.com/administration/platform/mcp/about))
- [Mistral AI](https://mistral.ai) - European AI lab releasing open-weight models plus tools for building enterprise agents. `MCP` ([MCP docs](https://docs.mistral.ai/resources/mcp))
- [OpenAI](https://openai.com) - Maker of GPT models and ChatGPT, plus ready-made agents for support and security work. `CLI`
- [xAI](https://x.ai) - Company behind the Grok models that also rents out its GPU computing power. `CLI`
- [Zoom](https://www.zoom.com) - Video calls, phone, and chat for whole companies, with an assistant that summarizes meetings. `MCP` ([MCP docs](https://docs.zoom.com/mcp))
