# Awesome AI Agents [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of AI agent frameworks, platforms, tools, and resources. AI agents are systems that use large language models to reason, plan, and take autonomous actions to accomplish goals.

Whether you're building agents, deploying them in production, or researching the space, this list has you covered.

**Last updated:** April 2026 · **Entries:** 180+ · [Submit a tool](CONTRIBUTING.md)

<details>
<summary><strong>What makes a good AI agent?</strong></summary>
<br>

An AI agent goes beyond chat — it can:
- **Reason** about multi-step problems
- **Plan** a sequence of actions
- **Use tools** (APIs, browsers, code execution)
- **Remember** context across sessions
- **Act autonomously** without step-by-step instructions

</details>

---

## Contents

- [Agent Frameworks](#agent-frameworks)
- [Agent Platforms & Marketplaces](#agent-platforms--marketplaces)
- [Coding Agents & AI IDEs](#coding-agents--ai-ides)
- [Research Agents](#research-agents)
- [Automation & Browser Agents](#automation--browser-agents)
- [Multi-Agent Systems](#multi-agent-systems)
- [Voice & Phone Agents](#voice--phone-agents)
- [Sales & Outreach Agents](#sales--outreach-agents)
- [Customer Support Agents](#customer-support-agents)
- [Data & Analytics Agents](#data--analytics-agents)
- [Design & Creative Agents](#design--creative-agents)
- [Video & Content Agents](#video--content-agents)
- [Finance & Trading Agents](#finance--trading-agents)
- [Agent Memory](#agent-memory)
- [Agent Security](#agent-security)
- [Agent Monitoring & Observability](#agent-monitoring--observability)
- [Agent Infrastructure & Deployment](#agent-infrastructure--deployment)
- [Hardware & Local Inference](#hardware--local-inference)
- [MCP Servers & Tool Integrations](#mcp-servers--tool-integrations)
- [Learning Resources](#learning-resources)
- [Contributing](#contributing)

---

## Agent Frameworks

*Libraries and SDKs for building AI agents from scratch.*

| Project | Description | Stars |
|---------|-------------|-------|
| [LangChain](https://github.com/langchain-ai/langchain) | Framework for developing applications powered by language models, with extensive tool and memory support | ![GitHub Repo stars](https://img.shields.io/github/stars/langchain-ai/langchain) |
| [LangGraph](https://github.com/langchain-ai/langgraph) | Library for building stateful, multi-step agent workflows as graphs, from the LangChain team | ![GitHub Repo stars](https://img.shields.io/github/stars/langchain-ai/langgraph) |
| [CrewAI](https://github.com/crewAIInc/crewAI) | Framework for orchestrating role-playing autonomous AI agents that collaborate to solve tasks | ![GitHub Repo stars](https://img.shields.io/github/stars/crewAIInc/crewAI) |
| [AutoGen](https://github.com/microsoft/autogen) | Microsoft's framework for building multi-agent conversational systems with customizable agents | ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/autogen) |
| [Semantic Kernel](https://github.com/microsoft/semantic-kernel) | Microsoft SDK for integrating LLMs into apps with planning, memory, and plugin support | ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/semantic-kernel) |
| [Anthropic Agent SDK](https://docs.anthropic.com/en/docs/agents) | Official SDK for building agents with Claude. Tool use, computer use, and managed agent workflows | — |
| [Google ADK](https://github.com/google/adk-python) | Google's Agent Development Kit for building agents with Gemini, including tool use and orchestration | ![GitHub Repo stars](https://img.shields.io/github/stars/google/adk-python) |
| [Haystack](https://github.com/deepset-ai/haystack) | End-to-end NLP framework with agent capabilities, RAG pipelines, and tool use | ![GitHub Repo stars](https://img.shields.io/github/stars/deepset-ai/haystack) |
| [Pydantic AI](https://github.com/pydantic/pydantic-ai) | Agent framework from the Pydantic team, focused on type-safe agent development with structured outputs | ![GitHub Repo stars](https://img.shields.io/github/stars/pydantic/pydantic-ai) |
| [Smolagents](https://github.com/huggingface/smolagents) | Hugging Face's lightweight library for building agents that write and execute Python code | ![GitHub Repo stars](https://img.shields.io/github/stars/huggingface/smolagents) |
| [Atomic Agents](https://github.com/BrainBlend-AI/atomic-agents) | Modular framework for building AI agents and pipelines with a focus on composability | ![GitHub Repo stars](https://img.shields.io/github/stars/BrainBlend-AI/atomic-agents) |
| [OpenClaw](https://github.com/openclaw/openclaw) | Open source personal AI that runs on your hardware, connects to messaging apps, and executes tasks 24/7 | ![GitHub Repo stars](https://img.shields.io/github/stars/openclaw/openclaw) |
| [OpenCode](https://github.com/sst/opencode) | Open source AI coding agent that supports 300+ models including local ones | ![GitHub Repo stars](https://img.shields.io/github/stars/sst/opencode) |
| [Phidata](https://github.com/phidatahq/phidata) | Toolkit for building AI assistants with memory, knowledge, and tools. Clean Python API | ![GitHub Repo stars](https://img.shields.io/github/stars/phidatahq/phidata) |
| [ControlFlow](https://github.com/PrefectHQ/ControlFlow) | Python framework for building agentic AI workflows by Prefect. Structured tasks with dependencies | ![GitHub Repo stars](https://img.shields.io/github/stars/PrefectHQ/ControlFlow) |
| [Instructor](https://github.com/jxnl/instructor) | Structured outputs from LLMs. Not an agent framework per se, but essential for building reliable agent tool calls | ![GitHub Repo stars](https://img.shields.io/github/stars/jxnl/instructor) |

## Agent Platforms & Marketplaces

*No-code/low-code platforms and marketplaces for deploying and sharing agents and agent skills.*

- [Dify](https://github.com/langgenius/dify) — Open-source platform for building LLM-powered apps with visual agent workflow orchestration. ![GitHub Repo stars](https://img.shields.io/github/stars/langgenius/dify)
- [Flowise](https://github.com/FlowiseAI/Flowise) — Drag-and-drop UI for building customized LLM agent flows using LangChain. ![GitHub Repo stars](https://img.shields.io/github/stars/FlowiseAI/Flowise)
- [Botpress](https://github.com/botpress/botpress) — Open-source platform for building and deploying AI-powered chatbots and agents. ![GitHub Repo stars](https://img.shields.io/github/stars/botpress/botpress)
- [Superagent](https://github.com/superagent-ai/superagent) — Platform for deploying production-ready AI agents with built-in memory, tools, and APIs.
- [AgentGPT](https://github.com/reworkd/AgentGPT) — Browser-based platform that lets you assemble, configure, and deploy autonomous AI agents. ![GitHub Repo stars](https://img.shields.io/github/stars/reworkd/AgentGPT)
- [skills.sh](https://skills.sh/) — Official leaderboard and directory for 90,000+ agent skill packages. Tracks real install counts across 19 AI agents.
- [Anthropic Official Skills](https://github.com/anthropics/skills) — Anthropic's official SKILL.md templates for Claude Code. Document creation, frontend design, development workflows.
- [Everything Claude Code](https://github.com/affaan-m/everything-claude-code) — 30 agents, 136 skills, 60 commands. The most comprehensive Claude Code resource. ![GitHub Repo stars](https://img.shields.io/github/stars/affaan-m/everything-claude-code)
- [OpenRouter](https://openrouter.ai/) — Unified API for 200+ LLMs. Route agent requests to the best model for each task.
- [Wordware](https://www.wordware.ai/) — IDE for building AI agents with a natural language programming model. Deploy as APIs.

## Coding Agents & AI IDEs

*AI agents that write, debug, review, and refactor code — plus AI-native development environments.*

### CLI & Terminal Agents
- [Claude Code](https://claude.ai/download) — Anthropic's CLI coding agent. Terminal-native, 200K context, MCP integrations, multi-file editing. $20/month with Claude Pro. [Full review](https://virtualuncle.com/claude-pro-review-2026/)
- [OpenAI Codex](https://openai.com/codex) — OpenAI's cloud-based coding agent. Runs tasks asynchronously in sandboxed environments. Available with ChatGPT Pro.
- [Aider](https://github.com/Aider-AI/aider) — AI pair programming in your terminal. Works with any LLM to edit code in your local git repo. ![GitHub Repo stars](https://img.shields.io/github/stars/Aider-AI/aider)
- [Goose](https://github.com/block/goose) — Open source coding agent by Block (Jack Dorsey). Rust-based, works with any LLM. ![GitHub Repo stars](https://img.shields.io/github/stars/block/goose)
- [Mentat](https://github.com/AbanteAI/mentat) — AI coding assistant that works directly with your codebase from the command line.
- [OpenCode](https://github.com/sst/opencode) — Open source terminal coding agent supporting 300+ models. ![GitHub Repo stars](https://img.shields.io/github/stars/sst/opencode)
- [OmX (Oh My codeX)](https://github.com/nicekid1/omx) — Adds hooks, agent teams, and HUDs to OpenAI Codex. ![GitHub Repo stars](https://img.shields.io/github/stars/nicekid1/omx)
- [toprank](https://github.com/nowork-studio/toprank) — Open-source Claude Code plugin with 9 SEO and Google Ads skills for traffic audits, schema markup, bid updates, and CMS publishing.

### AI IDEs & Editors
- [Cursor](https://cursor.com/) — AI-first code editor built on VS Code. Tab completion, inline chat, multi-file agents. The most popular AI IDE.
- [Windsurf](https://codeium.com/windsurf) — AI IDE by Codeium. Cascade agent for multi-file edits, deep codebase understanding.
- [Bolt.new](https://bolt.new/) — Full-stack app builder in the browser. Prompts to production in minutes. By StackBlitz.
- [Lovable](https://lovable.dev/) — AI full-stack engineer. Describe an app, get production code with Supabase backend.
- [Replit Agent](https://replit.com/) — Cloud IDE with agent that builds full apps from natural language prompts.
- [Continue](https://github.com/continuedev/continue) — Open-source AI code assistant for VS Code and JetBrains. Agent mode for autonomous coding. ![GitHub Repo stars](https://img.shields.io/github/stars/continuedev/continue)
- [Void](https://voideditor.com/) — Open-source Cursor alternative. AI code editor that runs locally.

### Software Engineering Agents
- [SWE-agent](https://github.com/princeton-nlp/SWE-agent) — Princeton agent that turns LLMs into software engineers capable of fixing real GitHub issues. ![GitHub Repo stars](https://img.shields.io/github/stars/princeton-nlp/SWE-agent)
- [Devin](https://devin.ai/) — Cognition Labs' autonomous software engineer. Handles full development tasks end-to-end.
- [GPT Engineer](https://github.com/gpt-engineer-org/gpt-engineer) — Agent that generates entire codebases from a single prompt. ![GitHub Repo stars](https://img.shields.io/github/stars/gpt-engineer-org/gpt-engineer)
- [Devika](https://github.com/stitionai/devika) — Agentic AI software engineer that understands high-level instructions and breaks them into steps.
- [Amazon Q Developer](https://aws.amazon.com/q/developer/) — AWS's AI coding assistant. Agents for code transformation, test generation, and security scanning.
- [OpenHands](https://github.com/All-Hands-AI/OpenHands) — Open-source platform for software development agents. Formerly OpenDevin. ![GitHub Repo stars](https://img.shields.io/github/stars/All-Hands-AI/OpenHands)

## Research Agents

*Agents designed for information gathering, analysis, and research tasks.*

- [GPT Researcher](https://github.com/assafelovic/gpt-researcher) — Autonomous agent that conducts comprehensive online research on any topic, producing detailed reports. ![GitHub Repo stars](https://img.shields.io/github/stars/assafelovic/gpt-researcher)
- [Hermes Agent](https://github.com/NousResearch/hermes-agent) — Self-improving AI agent by Nous Research with persistent memory, autonomous skill creation, and a learning loop. [In-depth guide](https://virtualuncle.com/hermes-agent-complete-guide-2026/) ![GitHub Repo stars](https://img.shields.io/github/stars/NousResearch/hermes-agent)
- [STORM](https://github.com/stanford-oval/storm) — Stanford research agent that generates Wikipedia-like articles by researching and synthesizing information from the web.
- [Feynman](https://github.com/getcompanion-ai/feynman) — Open source research agent with 4 specialized subagents: Researcher, Reviewer, Writer, Verifier.
- [DeepTutor](https://github.com/deeptutor-ai/deeptutor) — Agent-native personalized learning assistant that adapts to your knowledge level. ![GitHub Repo stars](https://img.shields.io/github/stars/deeptutor-ai/deeptutor)
- [Tavily](https://github.com/tavily-ai/tavily-python) — Search API and research tools optimized for AI agents and RAG applications.
- [Perplexity](https://perplexity.ai/) — AI-powered search engine with agent-like research capabilities. Cites sources.
- [Elicit](https://elicit.com/) — AI research assistant for academic papers. Finds, summarizes, and extracts data from studies.

## Automation & Browser Agents

*Agents that automate workflows, browser tasks, and business processes.*

- [n8n](https://github.com/n8n-io/n8n) — Fair-code workflow automation platform with 400+ integrations and native AI agent nodes. ![GitHub Repo stars](https://img.shields.io/github/stars/n8n-io/n8n)
- [Activepieces](https://github.com/activepieces/activepieces) — Open-source no-code business automation platform, alternative to Zapier. ![GitHub Repo stars](https://img.shields.io/github/stars/activepieces/activepieces)
- [Skyvern](https://github.com/Skyvern-AI/skyvern) — AI agent that automates browser-based workflows using computer vision and LLMs. ![GitHub Repo stars](https://img.shields.io/github/stars/Skyvern-AI/skyvern)
- [Browser Use](https://github.com/browser-use/browser-use) — Library that enables AI agents to control web browsers for task automation. ![GitHub Repo stars](https://img.shields.io/github/stars/browser-use/browser-use)
- [LaVague](https://github.com/lavague-ai/LaVague) — Framework for building AI web agents that interact with websites through natural language. ![GitHub Repo stars](https://img.shields.io/github/stars/lavague-ai/LaVague)
- [Playwright](https://github.com/microsoft/playwright) — Not AI-native, but the most popular browser automation framework. Many AI agents use it under the hood. ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/playwright)
- [Claude Cowork](https://claude.ai/product/claude-cowork) — Anthropic's agentic system for knowledge work. Computer use, Dispatch, 38+ connectors.
- [Agent Reach](https://github.com/Panniantong/Agent-Reach) — Give your AI agent eyes to see the internet. Read and search Twitter, Reddit, YouTube, GitHub — zero API fees. ![GitHub Repo stars](https://img.shields.io/github/stars/Panniantong/Agent-Reach)
- [Multion](https://multion.ai/) — AI agent API for web browsing. Handles complex multi-step web tasks autonomously.
- [Zapier AI](https://zapier.com/ai) — Zapier's AI automation layer. Natural language to workflow automation across 6,000+ apps.

## Multi-Agent Systems

*Frameworks and projects where multiple agents collaborate, debate, or compete.*

- [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) — One of the first autonomous AI agent projects, capable of self-prompting to achieve complex goals. ![GitHub Repo stars](https://img.shields.io/github/stars/Significant-Gravitas/AutoGPT)
- [MetaGPT](https://github.com/geekan/MetaGPT) — Multi-agent framework that assigns different roles (PM, architect, engineer) to form a collaborative software company. ![GitHub Repo stars](https://img.shields.io/github/stars/geekan/MetaGPT)
- [BabyAGI](https://github.com/yoheinakajima/babyagi) — Minimal framework demonstrating AI-powered task management with autonomous task creation.
- [ChatDev](https://github.com/OpenBMB/ChatDev) — Virtual software company where agents fill roles like CEO, CTO, programmer, and tester. ![GitHub Repo stars](https://img.shields.io/github/stars/OpenBMB/ChatDev)
- [CAMEL](https://github.com/camel-ai/camel) — Communicative Agents for "Mind" Exploration of Large Language Model Society. ![GitHub Repo stars](https://img.shields.io/github/stars/camel-ai/camel)
- [GPTeam](https://github.com/101dotxyz/GPTeam) — Multi-agent simulation where AI agents collaborate, form memories, and interact in a shared world.
- [Swarm](https://github.com/openai/swarm) — OpenAI's experimental framework for lightweight multi-agent orchestration and handoffs.
- [Magentic-One](https://github.com/microsoft/autogen/tree/main/python/packages/magentic-one) — Microsoft's multi-agent system with a lead Orchestrator agent coordinating specialist agents.

## Voice & Phone Agents

*AI agents that handle voice conversations, phone calls, and audio interactions.*

- [Vapi](https://vapi.ai/) — Platform for building voice AI agents. Handle phone calls, schedule appointments, qualify leads.
- [Bland AI](https://www.bland.ai/) — AI phone agent that makes and receives calls at scale. Enterprise voice automation.
- [Retell AI](https://www.retell.ai/) — Build conversational voice AI agents. Low-latency, interruptible, multi-lingual.
- [ElevenLabs Agents](https://elevenlabs.io/conversational-ai) — Conversational AI with the most realistic voice synthesis. Build voice agents with custom voices.
- [PlayHT](https://play.ht/) — AI voice platform with agent capabilities. Voice cloning and real-time generation.
- [Vocode](https://github.com/vocodedev/vocode-python) — Open-source library for building voice AI agents. Works with any LLM and speech provider. ![GitHub Repo stars](https://img.shields.io/github/stars/vocodedev/vocode-python)
- [LiveKit Agents](https://github.com/livekit/agents) — Framework for building real-time, multimodal AI agents. WebRTC-based. ![GitHub Repo stars](https://img.shields.io/github/stars/livekit/agents)

## Sales & Outreach Agents

*AI agents for lead generation, email outreach, CRM automation, and sales workflows.*

- [Clay](https://clay.com/) — AI-powered data enrichment and outreach platform. Waterfall enrichment across 100+ data providers.
- [Instantly](https://instantly.ai/) — AI email outreach at scale. Automated sequences, warm-up, lead management.
- [Apollo](https://apollo.io/) — Sales intelligence platform with AI-powered prospecting and outreach agents.
- [Artisan](https://www.artisan.co/) — AI sales agent (Ava) that automates outbound — finds leads, writes emails, books meetings.
- [11x](https://11x.ai/) — AI SDR agents. Alice (outbound) and Jordan (phone) handle the full sales pipeline.
- [SalesGPT](https://github.com/filip-michalsky/SalesGPT) — Open-source AI sales agent powered by LangChain. Context-aware, multi-stage sales conversations. ![GitHub Repo stars](https://img.shields.io/github/stars/filip-michalsky/SalesGPT)

## Customer Support Agents

*AI agents for customer service, helpdesk, and support automation.*

- [Intercom Fin](https://www.intercom.com/fin) — AI agent that resolves 50%+ of support tickets instantly. Trained on your help center.
- [Zendesk AI](https://www.zendesk.com/ai/) — AI agents built into Zendesk. Auto-resolve tickets, suggest responses, route conversations.
- [Sierra](https://sierra.ai/) — Conversational AI for customer experience. Enterprise-grade, brand-safe autonomous agents.
- [Ada](https://www.ada.cx/) — AI-first customer service platform. Automated resolution across channels.
- [Tidio](https://www.tidio.com/) — AI chatbot + live chat platform for e-commerce. Lyro AI agent handles common questions.
- [Chatwoot](https://github.com/chatwoot/chatwoot) — Open-source customer engagement platform with AI agent integrations. ![GitHub Repo stars](https://img.shields.io/github/stars/chatwoot/chatwoot)

## Data & Analytics Agents

*AI agents that analyze data, generate insights, build dashboards, and run queries.*

- [Julius AI](https://julius.ai/) — AI data analyst. Upload data, ask questions in natural language, get charts and insights.
- [Rows AI](https://rows.com/) — Spreadsheet with built-in AI analyst. Summarize, categorize, and extract from data.
- [PandasAI](https://github.com/sinaptik-ai/pandas-ai) — Python library that adds AI capabilities to Pandas. Chat with your dataframes. ![GitHub Repo stars](https://img.shields.io/github/stars/sinaptik-ai/pandas-ai)
- [Hex](https://hex.tech/) — Data workspace with AI agent for SQL, Python, and visualization. Magic AI writes queries from questions.
- [Open Interpreter](https://github.com/OpenInterpreter/open-interpreter) — Run code locally via natural language. Like ChatGPT Code Interpreter but on your machine. ![GitHub Repo stars](https://img.shields.io/github/stars/OpenInterpreter/open-interpreter)
- [MindsDB](https://github.com/mindsdb/mindsdb) — AI tables in databases. Query ML models like regular SQL tables. ![GitHub Repo stars](https://img.shields.io/github/stars/mindsdb/mindsdb)

## Design & Creative Agents

*AI agents for UI/UX design, image generation, and creative workflows.*

- [Galileo AI](https://www.usegalileo.ai/) — AI UI design agent. Generate high-fidelity designs from text descriptions.
- [Uizard](https://uizard.io/) — AI-powered design tool. Turn screenshots, sketches, or text into editable designs.
- [Figma AI](https://www.figma.com/ai/) — AI features built into Figma. Generate designs, rename layers, summarize files.
- [v0](https://v0.dev/) — Vercel's AI UI generator. Describe a component, get production React/Tailwind code.
- [Midjourney](https://midjourney.com/) — Leading AI image generation. Not an agent per se, but increasingly used in agentic design workflows.
- [ComfyUI](https://github.com/comfyanonymous/ComfyUI) — Node-based Stable Diffusion UI. Powerful for building automated image generation pipelines. ![GitHub Repo stars](https://img.shields.io/github/stars/comfyanonymous/ComfyUI)

## Video & Content Agents

*AI agents for video creation, editing, and content generation.*

- [HeyGen](https://heygen.com/) — AI video generation platform. Create talking avatar videos from text. Enterprise video agents.
- [Synthesia](https://www.synthesia.io/) — AI video platform with 230+ digital avatars. Text-to-video at scale.
- [Runway](https://runwayml.com/) — AI creative tools for video generation, editing, and visual effects.
- [Descript](https://descript.com/) — AI-powered video and podcast editing. Edit video by editing text transcripts.
- [Opus Clip](https://opus.pro/) — AI agent that finds and clips the best moments from long videos for social media.
- [Jasper](https://jasper.ai/) — AI content platform for marketing teams. Brand-voice trained content generation.
- [Copy.ai](https://copy.ai/) — AI content agent for go-to-market teams. Workflows for sales, marketing, and ops.

## Finance & Trading Agents

*AI agents for financial analysis, trading, prediction markets, and fintech.*

- [Polymarket Agents](https://github.com/Polymarket/agents) — Official framework for AI agents on Polymarket prediction markets. LLM-driven trading. ![GitHub Repo stars](https://img.shields.io/github/stars/Polymarket/agents)
- [FinGPT](https://github.com/AI4Finance-Foundation/FinGPT) — Open-source financial LLMs. Sentiment analysis, forecasting, robo-advising. ![GitHub Repo stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinGPT)
- [FinRL](https://github.com/AI4Finance-Foundation/FinRL) — Deep reinforcement learning framework for quantitative finance. ![GitHub Repo stars](https://img.shields.io/github/stars/AI4Finance-Foundation/FinRL)
- [OpenBB](https://github.com/OpenBB-finance/OpenBB) — Open-source investment research platform. Terminal, SDK, and AI copilot. ![GitHub Repo stars](https://img.shields.io/github/stars/OpenBB-finance/OpenBB)
- [Composer](https://www.composer.trade/) — AI-powered trading platform. Build, backtest, and execute strategies with natural language.
- [Numerai](https://numer.ai/) — AI hedge fund where data scientists build models that trade real markets. Crowd-sourced alpha.

## Agent Memory

*Systems for giving agents persistent memory across sessions.*

- [BrainCTL](https://github.com/brainctl/brainctl) — Single SQLite file memory system with FTS5 search, knowledge graph, and write gate for redundancy rejection.
- [ChromaDB](https://github.com/chroma-core/chroma) — AI-native open-source embedding database. The most popular vector store for agent RAG. ![GitHub Repo stars](https://img.shields.io/github/stars/chroma-core/chroma)
- [Letta](https://github.com/letta-ai/letta) — Framework for creating LLM agents with long-term memory and self-editing capabilities. ![GitHub Repo stars](https://img.shields.io/github/stars/letta-ai/letta)
- [Mem0](https://github.com/mem0ai/mem0) — Memory layer for AI agents. Persistent, contextual memory that improves over time. ![GitHub Repo stars](https://img.shields.io/github/stars/mem0ai/mem0)
- [Motorhead](https://github.com/getmetal/motorhead) — Memory and context management server for LLMs. Redis-backed, handles long conversations.
- [Tree Ring Memory](https://github.com/TerminallyLazy/Tree-Ring-Memory) — Local-first memory lifecycle for AI agents with Rust CLI, SQLite/FTS recall, audit, consolidation, and forgetting. ![GitHub Repo stars](https://img.shields.io/github/stars/TerminallyLazy/Tree-Ring-Memory)
- [Zep](https://github.com/getzep/zep) — Long-term memory for AI assistants with facts extraction, entity graphs, and temporal awareness. ![GitHub Repo stars](https://img.shields.io/github/stars/getzep/zep)

## Agent Security

*Tools and resources for securing AI agents, preventing prompt injection, and safe deployment.*

- [Rebuff](https://github.com/protectai/rebuff) — Self-hardening prompt injection detector that learns from attacks to improve over time.
- [LLM Guard](https://github.com/protectai/llm-guard) — Comprehensive toolkit for securing LLM interactions with input/output scanners. ![GitHub Repo stars](https://img.shields.io/github/stars/protectai/llm-guard)
- [Garak](https://github.com/NVIDIA/garak) — NVIDIA's LLM vulnerability scanner. Probes for hallucination, data leakage, prompt injection.
- [NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails) — NVIDIA toolkit for adding programmable safety rails to LLM-powered applications. ![GitHub Repo stars](https://img.shields.io/github/stars/NVIDIA/NeMo-Guardrails)
- [Invariant Guardrails](https://github.com/invariantlabs-ai/invariant) — Runtime security for AI agents. Monitors tool calls and blocks unsafe actions in real-time.
- [Lakera Guard](https://www.lakera.ai/) — Real-time prompt injection and data leakage protection. API-based.
- [Snyk ToxicSkills Research](https://snyk.io/blog/toxicskills-malicious-ai-agent-skills-clawhub/) — First comprehensive audit of agent skills. Found 13.4% critical security issues. [Full analysis](https://virtualuncle.com/agent-skills-marketplace-skills-sh-2026/)

## Agent Monitoring & Observability

*Tools for tracing, debugging, and monitoring agent behavior in production.*

- [LangSmith](https://github.com/langchain-ai/langsmith-sdk) — Platform for debugging, testing, evaluating, and monitoring LLM applications and agents.
- [Langfuse](https://github.com/langfuse/langfuse) — Open-source LLM engineering platform with tracing, evaluations, and metrics. ![GitHub Repo stars](https://img.shields.io/github/stars/langfuse/langfuse)
- [Phoenix](https://github.com/Arize-AI/phoenix) — Open-source observability for LLM applications with tracing and evaluation. ![GitHub Repo stars](https://img.shields.io/github/stars/Arize-AI/phoenix)
- [OpenLLMetry](https://github.com/traceloop/openllmetry) — Open-source observability for LLMs built on OpenTelemetry. Vendor-neutral tracing.
- [AgentOps](https://github.com/AgentOps-AI/agentops) — Toolkit for agent monitoring, testing, and replay with session-level observability.
- [Helicone](https://github.com/Helicone/helicone) — Open-source LLM observability. Request logging, caching, rate limiting, analytics. ![GitHub Repo stars](https://img.shields.io/github/stars/Helicone/helicone)
- [Braintrust](https://www.braintrust.dev/) — Evaluation and observability platform for AI products. Logging, scoring, experiments.
- [Weights & Biases Weave](https://wandb.ai/site/weave/) — LLM application tracing and evaluation by W&B.

## Agent Infrastructure & Deployment

*Platforms and tools for deploying, scaling, and managing AI agents in production.*

- [Modal](https://modal.com/) — Serverless compute for AI. Run agent workloads, fine-tuning, and batch jobs without managing infrastructure.
- [Replicate](https://replicate.com/) — Run AI models in the cloud via API. Easy deployment for agent backends.
- [Together AI](https://together.ai/) — Fast inference platform for open-source LLMs. Serverless, dedicated, and fine-tuning.
- [Fly.io](https://fly.io/) — Deploy apps globally. Popular for hosting agent backends and MCP servers.
- [Railway](https://railway.app/) — Instant deployment for full-stack apps. One-click deploys for agent backends.
- [E2B](https://github.com/e2b-dev/E2B) — Cloud sandboxes for AI agents. Secure code execution environments. ![GitHub Repo stars](https://img.shields.io/github/stars/e2b-dev/E2B)
- [Dagster](https://github.com/dagster-io/dagster) — Orchestration platform for data and AI pipelines. Schedule and monitor agent workflows. ![GitHub Repo stars](https://img.shields.io/github/stars/dagster-io/dagster)

## Hardware & Local Inference

*Infrastructure, edge computing, and hardware for running AI agents locally.*

- [Ollama](https://github.com/ollama/ollama) — Run large language models locally with a simple API. The most popular local LLM runtime. ![GitHub Repo stars](https://img.shields.io/github/stars/ollama/ollama)
- [llama.cpp](https://github.com/ggerganov/llama.cpp) — Efficient C/C++ inference of LLMs on commodity hardware. ![GitHub Repo stars](https://img.shields.io/github/stars/ggerganov/llama.cpp)
- [vLLM](https://github.com/vllm-project/vllm) — High-throughput LLM serving engine with PagedAttention. Production-grade. ![GitHub Repo stars](https://img.shields.io/github/stars/vllm-project/vllm)
- [LocalAI](https://github.com/mudler/LocalAI) — Drop-in OpenAI-compatible API for running LLMs locally. ![GitHub Repo stars](https://img.shields.io/github/stars/mudler/LocalAI)
- [TensorRT-LLM](https://github.com/NVIDIA/TensorRT-LLM) — NVIDIA library for optimizing LLM inference on GPUs.
- [LM Studio](https://lmstudio.ai/) — Desktop app for running local LLMs. GUI for downloading, configuring, and chatting with models.
- [Jan](https://github.com/janhq/jan) — Open-source ChatGPT alternative that runs 100% offline. Desktop app for local AI. ![GitHub Repo stars](https://img.shields.io/github/stars/janhq/jan)
- [GPT4All](https://github.com/nomic-ai/gpt4all) — Run LLMs locally on any hardware. Desktop app + Python bindings. ![GitHub Repo stars](https://img.shields.io/github/stars/nomic-ai/gpt4all)

## MCP Servers & Tool Integrations

*Model Context Protocol servers and tool integrations that give agents access to external services.*

> [MCP](https://modelcontextprotocol.io/) is an open standard for connecting AI agents to data sources and tools.

- [MCP Servers (Official)](https://github.com/modelcontextprotocol/servers) — Official repository of MCP servers. Filesystem, GitHub, Slack, databases, and more. ![GitHub Repo stars](https://img.shields.io/github/stars/modelcontextprotocol/servers)
- [Awesome MCP Servers](https://github.com/punkpeye/awesome-mcp-servers) — Community curated list of MCP servers and resources. ![GitHub Repo stars](https://img.shields.io/github/stars/punkpeye/awesome-mcp-servers)
- [Composio](https://github.com/ComposioHQ/composio) — Integration platform for AI agents. 250+ pre-built tool integrations. ![GitHub Repo stars](https://img.shields.io/github/stars/ComposioHQ/composio)
- [Toolhouse](https://toolhouse.ai/) — Universal tool server for AI agents. Connect any agent to any API.

## Learning Resources

*Tutorials, courses, papers, and guides for understanding and building AI agents.*

### Guides & Blogs
- [Building Effective Agents](https://www.anthropic.com/research/building-effective-agents) — Anthropic's guide to practical patterns for building reliable AI agents.
- [LLM Powered Autonomous Agents](https://lilianweng.github.io/posts/2023-06-23-agent/) — Lilian Weng's (OpenAI) comprehensive blog on LLM-based agent architecture.
- [Andrew Ng's AI Agentic Design Patterns](https://www.deeplearning.ai/the-batch/how-agents-can-improve-llm-performance/) — Core agentic design patterns: reflection, tool use, planning, and multi-agent collaboration.
- [AutoGPT Blog](https://news.agpt.co/) — Developments in autonomous AI agents and the AutoGPT ecosystem.

### Papers
- [The Rise and Potential of Large Language Model Based Agents](https://arxiv.org/abs/2309.07864) — Survey paper covering the full landscape of LLM-based agents.
- [A Survey on Large Language Model based Autonomous Agents](https://arxiv.org/abs/2308.11432) — Comprehensive survey on LLM agent architectures and applications.
- [ReAct: Synergizing Reasoning and Acting in Language Models](https://arxiv.org/abs/2210.03629) — The foundational paper on reasoning + acting agent pattern.

### More Lists
- [Awesome LLM-Powered Agent](https://github.com/hyp1231/awesome-llm-powered-agent) — Curated list focused on the academic research side of LLM agents.
- [Agent Protocol](https://github.com/AI-Engineer-Foundation/agent-protocol) — Unified API specification for communicating with AI agents.

---

## Contributing

Contributions are welcome! Please read the [contributing guidelines](CONTRIBUTING.md) before submitting a pull request.

**To add a tool:** Open a PR with the tool name, link, and a one-line description. Include the GitHub stars badge if applicable.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work. See [LICENSE](LICENSE) for details.
