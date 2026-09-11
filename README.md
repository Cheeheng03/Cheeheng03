# Tang Chee Heng

Technical Co-Founder · AI Systems & Automation Engineer · DeFi Protocol Engineer

I build production AI systems, workflow automations, and operational software for real businesses. I am a technical co-founder at [Zedech Solutions](https://www.zedech.com/), where I lead engineering across AI agents, internal platforms, data pipelines, and customer-facing products. I am also a co-founder and protocol engineer at Polystream.

My work ranges from WhatsApp agents and retrieval-augmented assistants to offline-first field applications, multi-tenant operations platforms, and security-audited smart-contract infrastructure. I enjoy turning ambiguous, manual workflows into reliable systems that teams can use every day.

[Zedech](https://www.zedech.com/) • [LinkedIn](https://www.linkedin.com/in/chee-heng-tang-51b080312/) • [Email](mailto:cheehengtang@gmail.com)

---

## What I am building

### AI systems and workflow automation

| Product / capability | What it does | Stack / methods |
| --- | --- | --- |
| **[Zedech Solutions](https://www.zedech.com/)** | I lead engineering for AI assistants, autonomous workflows, dashboards, data pipelines, and internal operations systems—from discovery and architecture through deployment and support. | AI agents · RAG · workflow automation · TypeScript · Python · PostgreSQL · Docker |
| **LeadPilot** | Turns business data into scored prospects and managed outreach campaigns. It combines rule-based and LLM scoring with WhatsApp Business outreach and a full campaign inbox. | Next.js · TypeScript · Prisma/PostgreSQL · Python · Celery · Redis · Playwright · Docker |
| **Company intranet and operations tools** | Configurable internal platforms for HR workflows, employee resources, forms, document generation, permissions, reporting, and company-wide information management. Designed to be adapted across organizations rather than rebuilt from scratch. | Next.js · TypeScript · Prisma/PostgreSQL · Better Auth · Tailwind CSS · shadcn/ui · Docker · Neon · Vercel |

### Digital marketing intelligence

I use AI as a research and decision-support layer for digital marketing—not simply as a generic copy generator.

| Stage | What I do | Output |
| --- | --- | --- |
| **Market research** | Study the client's market, customer segments, buying motivations, pain points, and the language customers already use. | Audience themes · pain points · buying triggers · positioning angles |
| **Competitor analysis** | Analyze well-performing and sustained Meta ads from the client's market and competitors, including their offers, landing pages, creative formats, hooks, and calls to action. | Competitor map · messaging gaps · recurring winning patterns |
| **Performance-pattern analysis** | Compare well-performing examples to identify the structures behind them—opening hooks, problem framing, proof, offer design, creative style, and CTA patterns. | Evidence-backed creative directions and campaign hypotheses |
| **Copy generation** | Generate ad-copy variants from the market analysis and proven examples while preserving the client's brand voice and offer. | Hooks · primary text · headlines · CTAs · creative briefs · test variants |
| **Iteration** | Turn campaign results into structured feedback for the next research and copy cycle. | New test ideas · refined messaging · reusable campaign knowledge |

### Web systems

Through **[Zedech Studio](https://studio.zedech.com/)**, I build conversion-focused websites, landing pages, SEO foundations, content workflows, analytics, and self-service admin systems. These projects connect the public marketing layer to the operations behind it, including lead capture, CRM routing, WhatsApp enquiries, content management, and reporting.

---

## Selected production systems

Some client implementations are private, so the systems are described without identifying the organizations.

| System | What it delivers | Stack |
| --- | --- | --- |
| **AI-enabled automotive operations platform** | A multi-tenant system for customers, vehicles, appointments, workshop jobs, staff assignments, checklists, status updates, and reporting. Its WhatsApp layer manages enquiries, booking flows, media, delivery states, multilingual onboarding, urgent-case triage, and human escalation. It also connects to existing accounting data and provides controlled tools for AI agents. | Bun · TypeScript · Next.js · Hono · Prisma/PostgreSQL · Redis/BullMQ · Docker · object storage · PostgreSQL RLS |
| **WhatsApp guest concierge** | A round-the-clock conversational assistant for short-term-rental operations. It answers property-specific questions, assists with check-in and common issues, retains conversation context, and escalates exceptional cases to a human instead of inventing an answer. | WhatsApp integration · RAG · structured knowledge base · conversation memory · human escalation |
| **Offline-first field inspection and compliance platform** | A tablet-first technician app for configurable checklists, equipment records, photographs, remarks, customer signatures, and reliable offline work. Its admin system handles scheduling, templates, approvals, users, audit history, imports, and locked, versioned PDF reports. | Expo/React Native · Next.js · Hono · Prisma/PostgreSQL · Better Auth · WatermelonDB · Cloudflare R2 · Gotenberg |
| **Self-service business website and CMS** | A conversion-focused public website and constrained page builder. Non-technical staff can manage services, products, portfolios, certificates, media, custom fields, spreadsheet imports, and WhatsApp enquiry flows without depending on a developer. | Next.js · TypeScript · Hono · Prisma/PostgreSQL · Cloudflare R2 · Better Auth · Puck · Tailwind CSS · Vercel |
| **Multi-tenant HR and company intranet** | A reusable operations portal for employee resources, HR workflows, configurable forms, document generation, announcements, calendars, permissions, and reporting, with organization-level isolation and customization. | Next.js · TypeScript · Prisma/PostgreSQL · Better Auth · Tailwind CSS · shadcn/ui · Docker · Neon · Vercel |
| **E-commerce storefront and operations console** | A responsive storefront with an independent admin experience for products, inventory, orders, content, and daily store operations—allowing the operating team to run the system without ongoing developer intervention. | TypeScript · Next.js · React · Tailwind CSS · PostgreSQL · admin and content workflows |

Across these systems, I work beyond the interface: requirements discovery, architecture, data modeling, AI-agent boundaries, authentication and permissions, background jobs, testing, CI/CD, deployment, observability, and production support.

---

## Selected research and open-source work

- **Decentralized credit scoring** — Analyzed 2,000+ on-chain wallets and trained CatBoost, Gradient Boosting, and Random Forest models for wallet-risk assessment, reaching an R² of up to 0.985. Connected the scoring pipeline to smart contracts through Chainlink nodes and external adapters.
- **[DeESG](https://github.com/Cheeheng03/DeESG)** — A decentralized ESG scoring platform combining IoT environmental data, AI clustering, Chainlink oracles and automation, token incentives, and privacy-preserving governance.
- **[AI Guardian](https://github.com/Cheeheng03/AIGuardian)** — A deepfake and image-authenticity system combining AI inference with on-chain image verification, ICP canisters, and World ID.
- **[Clawmono](https://github.com/PragmaMoney/clawmono-monorepo)** — Payment infrastructure for AI agents using on-chain identities, constrained smart wallets, spending policies, and an x402-compatible payment proxy.

---

## Stack

- **AI and automation:** Python, FastAPI, Celery, RAG, FAISS, local Whisper, LangChain, Hugging Face, OpenAI-compatible APIs, OpenRouter, n8n, Apify
- **Product engineering:** TypeScript, Bun, Node.js, Next.js, React, React Native, Expo, Hono, Tailwind CSS, shadcn/ui
- **Data and infrastructure:** PostgreSQL, Prisma, Neon, Redis, BullMQ, SQLite, Docker, Cloudflare R2, Vercel, GitHub Actions
- **Blockchain and DeFi:** Solidity, Foundry, Hardhat, Ethers.js, Wagmi, Chainlink, Pyth, RedStone, account abstraction, smart accounts
- **Protocol research:** DeFiLlama, Dune Analytics, DeBank, Etherscan, Tenderly, The Graph

---

## Recognition

- **Winner**, Chainlink “Connect the World” at ETHGlobal Bangkok — DeESG
- **5th place**, Innovation on Scroll at ETHGlobal Bangkok — DeESG
- **Winner**, Best Community Application on Scroll at ETH KL — AI Guardian
- **Winner**, ICP–Ethereum Chain Fusion Challenge at ETH KL — AI Guardian

---

## DeFi and on-chain infrastructure

### Polystream

I co-founded Polystream and led core protocol engineering for a multi-chain yield platform designed to make DeFi strategies accessible through a simpler web and mobile experience.

| Area | My contribution |
| --- | --- |
| **Protocol architecture** | Designed and built the core Solidity contracts around an ERC-4626 vault architecture supporting multiple assets across three blockchain networks. |
| **Yield-strategy research** | Researched lending markets, liquidity pools, yield tokenization, leveraged looping, cross-chain liquidity, and stablecoin strategies. I reviewed protocol architecture, smart contracts, capital flows, yield sustainability, integration risks, and security assumptions before implementation. |
| **Strategy integrations** | Integrated 35+ DeFi protocols and strategies—including Pendle, Aave, Curve, Balancer, and Morpho—into a common vault system. Built allocation mechanisms that distribute capital across strategies targeting approximately 8–12% APY. |
| **Security controls** | Implemented curator-controlled execution with whitelisted strategies and guarded external-contract interactions to reduce the protocol's attack surface and protect user capital. |
| **Testing and verification** | Built the Foundry testing infrastructure covering unit, integration, invariant, and fuzz tests for vault accounting, deposits and withdrawals, strategy adapters, allocation behavior, and edge cases. |
| **Security audit** | Led the technical audit process with Cantina: explained the architecture to auditors, reproduced and evaluated findings, implemented remediations, and verified the resulting changes. |
| **Backend and monitoring** | Built event listeners, oracle integrations, vault trackers, monitoring services, and supporting processes for near-real-time visibility into vault state and strategy activity. |
| **Product delivery** | Contributed across the complete product surface, including the web dApp, React Native mobile application, curator dashboard, wallet and account-abstraction flows, and operational tooling for managing vault strategies. |

Polystream began at the Scroll Open Hackathon, where it received second place and a $15K prize. The team was subsequently selected for Scroll Campus and later secured $95K in Scroll Foundation investment and grants.
