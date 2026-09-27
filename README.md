# Hi, I'm Henry 👋

**I lead products, design experiences and write code.** I'm Group Product Manager, Retention at Reuters, where I run a consumer product group across mobile, AI and partnerships. I also founded **Cleartext Labs**, where I build products that make complex information useful: from researching public records to predicting subway disruptions.

I like understanding the larger task someone is trying to complete. A search, a notification or a recommendation is one step towards it. My work is about helping people make progress.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-digitalhen-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/digitalhen)
[![Website](https://img.shields.io/badge/Portfolio-digitalhen.com-24292e?style=flat-square&logo=googlechrome&logoColor=white)](https://digitalhen.com)
[![Cleartext Labs](https://img.shields.io/badge/Lab-cleartextlabs.com-3b7a57?style=flat-square)](https://cleartextlabs.com)

### At Reuters

- **Consumer subscriptions and the app.** Led the Reuters News app rebuild and helped grow mobile and web subscriptions to **250K paying customers in two years**, reaching **$1M ARR in the first four weeks**. One-tap Apple ID sign-up and Apple Pay as the default increased iOS paywall conversion from **0.2% to 1.5%**.
- **Read Next.** Personally built the recommendation prototype using content embeddings and session behaviour, then worked with the team to ship it. It improved **recirculation 20%** and **subscription conversion 22% among single-article visitors**. The aim: help readers follow the question that brought them to an article.
- **Reasons to return.** Shipped smart recaps that increased returning-user session frequency **15%**, after testing and stopping AI article summaries when engagement stayed flat. Built a programme of **20+ A/B tests** with success and stopping criteria defined before launch.
- **AI with editorial judgement.** Led the design of **Cross Check**, combining multi-model validation, confidence scoring, source attribution and structured editorial review. Shipped AI-powered push notifications with a **10% click-through rate** and no editorial corrections after launch.
- **Distribution and partnerships.** Drove Apple News and Samsung News partnerships reaching **30M+ monthly active users**. Designed and shipped **Subscriptions on Rails**, extending paid access across third-party publishers, the Reuters ChatGPT app and MCP servers.
- **A team that can build.** Grew the product team from zero to **four PMs**, with coaching, ownership and room to develop. Designed and built an agentic workflow connecting user intelligence, **Figma, Claude Code, automated testing and deployment**, cutting average development cycles from **three months to under three weeks**. Onboarding scripts made it possible for non-technical colleagues to contribute; engineering adopted them as its default, and a designer took a new app feature through to production.

### Cleartext Labs

I build the complete experience: research, data pipelines, models, interface, deployment and getting it into people's hands. Some projects are commercial; others are free tools for people trying to understand the world or represent their interests.

| Project | What it does |
|---|---|
| **[Prospect](https://askprospect.com)** | Property intelligence built and commercialised with NYC brokers, connecting **1.24M residential units** and eight public-data feeds. A LightGBM model outperformed broker-defined listing signals **2.5x**. One query field routes names and addresses to direct database lookups and questions to AI analysis, avoiding unnecessary model calls. |
| **[subway.fyi](https://subway.fyi)** | Live NYC transit information and delay predictions, built on nine MTA feeds and roughly **1.8M rows a day**. Attracted **over one million visits in its first two weeks** and was presented to the MTA board. The prediction model achieved **1.76x baseline recall**, **38% fewer false alarms** and a median **43-minute warning** ahead of official alerts. |
| **[911records.org](https://911records.org)** | A free evidence explorer for **9/11 families, affected workers and lawyers**, making **24,436 documents and 172,000+ pages** searchable through maps, keyword and semantic search, and source-linked AI answers. Covered by **The City and 1010 WINS**, with comments from the Mayor's Office. |
| **[CEDAR](https://cedarcoparenting.com)** | Helps parents, including those representing themselves, organise communications, understand court-order provisions and prepare evidence. Connects communications to governing provisions, with structured reports and controlled access for parents, attorneys and mediators. |
| **[Blocklight](https://apps.cleartextlabs.com/blocklight/)** | An **MIT-licensed TypeScript library on MapLibre GL JS** for rendering building-level open data. Bring GeoJSON footprints and a JSON attribute table; it handles joins, aggregation, styling, viewport loading, 2D/3D switching and selection. Available on npm, with runnable examples and browser integration tests. |
| **[Userken.](https://userken.com/)** | A user-intelligence platform built from **more than 200,000 reviews across multiple types of apps**. Turns feedback into searchable research and virtual user panels for exploring reactions to features and communication, before testing with real customers. |
| **[Transcord](https://transcord.app)** | Call recording and transcription for journalists, with speaker separation, semantic search and access from Claude. Bootstrapped solo for six years. |

### How I build

**Design is part of the work.** I care about the path through a product, the language it uses and whether the next action makes sense. I work in Figma and code, and prototype to find out what should be built.

**AI does useful work; I own the decisions.** Beyond the Reuters workflow, I run a nightly agent for subway.fyi that retrains models, runs replay checks and promotes candidates only when they pass quality gates. It can leave the existing model in place and roll back when live false alarms rise.

**Evidence needs checking.** I rejected an overfit model for subway.fyi in favour of logistic regression, used time-based validation and published a scorecard that includes misses. At Prospect, an audit of **598 signals found 62% false positives**, prompting a redesign around deterministic rules first and model review for the remainder. For 9/11 records, original pages, source links and explicit evidence gaps help people inspect the answers.

### More open source

- [**911records**](https://github.com/digitalhen/911records) and [**911records-claude**](https://github.com/digitalhen/911records-claude): the records explorer and access from Claude.
- [**lume-story-discovery**](https://github.com/digitalhen/lume-story-discovery): a Firefox extension recommending what to read next using on-device embeddings, with no cloud and no tracking.
- [**gmail-mcp**](https://github.com/digitalhen/gmail-mcp): semantic email search from Claude.
- [**opnsense-mcp**](https://github.com/digitalhen/opnsense-mcp): firewall, VPN and DNS tools for Claude.
- **For fun:** [bike-bar](https://github.com/digitalhen/bike-bar), [orbital](https://github.com/digitalhen/orbital), [tab-tunnel](https://github.com/digitalhen/tab-tunnel) and [a Garmin watch face](https://github.com/digitalhen/burndown-garmin-watchface).

### Before Reuters

My route was **engineering → journalism → product**.

- **Lehman Brothers, Barclays Capital and Morgan Stanley:** a decade building real-time trading platforms, progressing from Associate to Vice President and building a ten-person technology team.
- **The Wall Street Journal:** Deputy Editor, WSJ Pro; launched **WSJ Pro Artificial Intelligence to 50K users on day one** and led the **Money and Investing visualisations team**, combining data, reporting and design.
- **Dow Jones:** Director, Strategic Initiatives; cut recurring cloud spend by **over $1M**, created a shared view of **250+ projects**, and expanded the internship programme from **35 to 125 students**, with training and mentorship across New York, Hong Kong and London.

BSc in Computer Science from **Exeter**; Master of Journalism from the **University of Hong Kong**, on a Google scholarship. Based in **New York City**.

### Tools and skills

**Product and design:** consumer apps · retention · subscriptions · research · experimentation · personalisation · information design · Figma · team development

**Engineering and data:** TypeScript/JavaScript · Python · SQL · Swift · React/Next.js · PostgreSQL/TimescaleDB · Snowflake · OpenSearch · MapLibre · ETL · APIs · OAuth · row-level security

**AI and delivery:** Claude Code · MCP · retrieval-augmented generation · embeddings · model routing · LightGBM · logistic regression · evaluation · automated testing · CI/CD · AWS · GCP · Docker

