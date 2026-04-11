# Awesome AI Agents [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of AI agent frameworks, platforms, tools, and resources. AI agents are systems that use large language models to reason, plan, and take autonomous actions to accomplish goals.

Whether you're building agents, deploying them in production, or researching the space, this list has you covered.

## Contents

- [Agent Frameworks](#agent-frameworks)
- [Agent Platforms & Marketplaces](#agent-platforms--marketplaces)
- [Research Agents](#research-agents)
- [Automation Agents](#automation-agents)
- [Coding Agents](#coding-agents)
- [Multi-Agent Systems](#multi-agent-systems)
- [Agent Memory](#agent-memory)
- [Agent Security](#agent-security)
- [Agent Monitoring & Observability](#agent-monitoring--observability)
- [Hardware for Agents](#hardware-for-agents)
- [Learning Resources](#learning-resources)
- [Contributing](#contributing)

---

## Agent Frameworks

*Libraries and frameworks for building AI agents from scratch.*

- [LangChain](https://github.com/langchain-ai/langchain) — Framework for developing applications powered by language models, with extensive tool and memory support. ![GitHub Repo stars](https://img.shields.io/github/stars/langchain-ai/langchain)
- [LangGraph](https://github.com/langchain-ai/langgraph) — Library for building stateful, multi-step agent workflows as graphs, from the LangChain team. ![GitHub Repo stars](https://img.shields.io/github/stars/langchain-ai/langgraph)
- [CrewAI](https://github.com/crewAIInc/crewAI) — Framework for orchestrating role-playing autonomous AI agents that collaborate to solve tasks. ![GitHub Repo stars](https://img.shields.io/github/stars/crewAIInc/crewAI)
- [AutoGen](https://github.com/microsoft/autogen) — Microsoft's framework for building multi-agent conversational systems with customizable agents. ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/autogen)
- [Semantic Kernel](https://github.com/microsoft/semantic-kernel) — Microsoft SDK for integrating LLMs into apps with planning, memory, and plugin support. ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/semantic-kernel)
- [Haystack](https://github.com/deepset-ai/haystack) — End-to-end NLP framework with agent capabilities, retrieval-augmented generation pipelines, and tool use. ![GitHub Repo stars](https://img.shields.io/github/stars/deepset-ai/haystack)
- [Pydantic AI](https://github.com/pydantic/pydantic-ai) — Agent framework from the Pydantic team, focused on type-safe agent development with structured outputs.
- [Smolagents](https://github.com/huggingface/smolagents) — Hugging Face's lightweight library for building agents that write and execute Python code to solve tasks.
- [Atomic Agents](https://github.com/BrainBlend-AI/atomic-agents) — Modular framework for building AI agents and pipelines with a focus on composability and atomicity.
- [OpenClaw](https://github.com/openclaw/openclaw) — The most popular AI agent project in history (350k+ stars). Open source personal AI that runs on your hardware, connects to messaging apps, and executes tasks autonomously 24/7. ![GitHub Repo stars](https://img.shields.io/github/stars/openclaw/openclaw)
- [OpenCode](https://github.com/sst/opencode) — Open source AI coding agent that supports 300+ models including local ones. TypeScript alternative to Claude Code. ![GitHub Repo stars](https://img.shields.io/github/stars/sst/opencode)

## Agent Platforms & Marketplaces

*No-code/low-code platforms and marketplaces for deploying and sharing agents and agent skills.*

- [Dify](https://github.com/langgenius/dify) — Open-source platform for building LLM-powered apps with visual agent workflow orchestration. ![GitHub Repo stars](https://img.shields.io/github/stars/langgenius/dify)
- [Flowise](https://github.com/FlowiseAI/Flowise) — Drag-and-drop UI for building customized LLM agent flows using LangChain. ![GitHub Repo stars](https://img.shields.io/github/stars/FlowiseAI/Flowise)
- [Botpress](https://github.com/botpress/botpress) — Open-source platform for building and deploying AI-powered chatbots and agents. ![GitHub Repo stars](https://img.shields.io/github/stars/botpress/botpress)
- [Superagent](https://github.com/superagent-ai/superagent) — Platform for deploying production-ready AI agents with built-in memory, tools, and APIs.
- [AgentGPT](https://github.com/reworkd/AgentGPT) — Browser-based platform that lets you assemble, configure, and deploy autonomous AI agents. ![GitHub Repo stars](https://img.shields.io/github/stars/reworkd/AgentGPT)
- [skills.sh](https://skills.sh/) — Official leaderboard and directory for 90,000+ agent skill packages. Tracks real install counts across 19 AI agents.
- [Anthropic Official Skills](https://github.com/anthropics/skills) — Anthropic's official SKILL.md templates for Claude Code. Document creation, frontend design, development workflows.
- [Everything Claude Code](https://github.com/affaan-m/everything-claude-code) — 130k+ stars. 30 agents, 136 skills, 60 commands. The most comprehensive Claude Code resource. ![GitHub Repo stars](https://img.shields.io/github/stars/affaan-m/everything-claude-code)

## Research Agents

*Agents designed for information gathering, analysis, and research tasks.*

- [GPT Researcher](https://github.com/assafelovic/gpt-researcher) — Autonomous agent that conducts comprehensive online research on any topic, producing detailed reports. ![GitHub Repo stars](https://img.shields.io/github/stars/assafelovic/gpt-researcher)
- [Hermes Agent](https://github.com/NousResearch/hermes-agent) — Self-improving AI agent by Nous Research with persistent memory, autonomous skill creation, and a learning loop that gets smarter over time. 24k+ stars. [In-depth guide](https://virtualuncle.com/hermes-agent-complete-guide-2026/) ![GitHub Repo stars](https://img.shields.io/github/stars/NousResearch/hermes-agent)
- [Feynman](https://github.com/getcompanion-ai/feynman) — Open source research agent with 4 specialized subagents: Researcher, Reviewer, Writer, Verifier. Searches papers, peer reviews findings, and verifies every citation.
- [DeepTutor](https://github.com/deeptutor-ai/deeptutor) — Agent-native personalized learning assistant that adapts to your knowledge level. ![GitHub Repo stars](https://img.shields.io/github/stars/deeptutor-ai/deeptutor)
- [STORM](https://github.com/stanford-oval/storm) — Stanford research agent that generates Wikipedia-like articles by researching and synthesizing information from the web.
- [Tavily](https://github.com/tavily-ai/tavily-python) — Search API and research tools optimized for AI agents and RAG applications.

## Automation Agents

*Agents that automate workflows, browser tasks, and business processes.*

- [n8n](https://github.com/n8n-io/n8n) — Fair-code workflow automation platform with 400+ integrations and native LangChain nodes for AI agent workflows. ![GitHub Repo stars](https://img.shields.io/github/stars/n8n-io/n8n)
- [Activepieces](https://github.com/activepieces/activepieces) — Open-source no-code business automation platform, alternative to Zapier. ![GitHub Repo stars](https://img.shields.io/github/stars/activepieces/activepieces)
- [Skyvern](https://github.com/Skyvern-AI/skyvern) — AI agent that automates browser-based workflows using computer vision and LLMs. ![GitHub Repo stars](https://img.shields.io/github/stars/Skyvern-AI/skyvern)
- [Browser Use](https://github.com/browser-use/browser-use) — Library that enables AI agents to control web browsers for task automation. ![GitHub Repo stars](https://img.shields.io/github/stars/browser-use/browser-use)
- [LaVague](https://github.com/lavague-ai/LaVague) — Framework for building AI web agents that interact with websites through natural language. ![GitHub Repo stars](https://img.shields.io/github/stars/lavague-ai/LaVague)
- [Claude Cowork](https://claude.ai/product/claude-cowork) — Anthropic's agentic system for knowledge work. Computer use, Dispatch (phone-to-desktop tasks), 38+ connectors. Included with Claude Pro.
- [Agent Reach](https://github.com/Panniantong/Agent-Reach) — Give your AI agent eyes to see the internet. Read and search Twitter, Reddit, YouTube, GitHub — one CLI, zero API fees. ![GitHub Repo stars](https://img.shields.io/github/stars/Panniantong/Agent-Reach)

## Coding Agents

*AI agents that write, debug, review, and refactor code.*

- [Claude Code](https://claude.ai/download) — Anthropic's CLI coding agent. Terminal-native, 200K context, MCP integrations, multi-file editing. $20/month with Claude Pro. [Full review](https://virtualuncle.com/claude-pro-review-2026/)
- [OpenAI Codex](https://openai.com/codex) — OpenAI's cloud-based coding agent. Runs tasks asynchronously in sandboxed environments. Available with ChatGPT Pro ($100/month).
- [Aider](https://github.com/Aider-AI/aider) — AI pair programming in your terminal, works with any LLM to edit code in your local git repo. ![GitHub Repo stars](https://img.shields.io/github/stars/Aider-AI/aider)
- [SWE-agent](https://github.com/princeton-nlp/SWE-agent) — Princeton agent that turns LLMs into software engineering agents capable of fixing real GitHub issues. ![GitHub Repo stars](https://img.shields.io/github/stars/princeton-nlp/SWE-agent)
- [GPT Engineer](https://github.com/gpt-engineer-org/gpt-engineer) — Agent that generates an entire codebase from a single prompt, with iterative refinement. ![GitHub Repo stars](https://img.shields.io/github/stars/gpt-engineer-org/gpt-engineer)
- [Goose](https://github.com/block/goose) — Open source coding agent by Block (Jack Dorsey). Rust-based, works with any LLM, full agent loop. ![GitHub Repo stars](https://img.shields.io/github/stars/block/goose)
- [Mentat](https://github.com/AbanteAI/mentat) — AI coding assistant that works directly with your codebase from the command line.
- [Devika](https://github.com/stitionai/devika) — Agentic AI software engineer that understands high-level instructions and breaks them into coding steps.
- [Continue](https://github.com/continuedev/continue) — Open-source AI code assistant IDE extension with agent capabilities for VS Code and JetBrains. ![GitHub Repo stars](https://img.shields.io/github/stars/continuedev/continue)
- [OmX (Oh My codeX)](https://github.com/nicekid1/omx) — Adds hooks, agent teams, and HUDs to OpenAI Codex. 20K+ stars. ![GitHub Repo stars](https://img.shields.io/github/stars/nicekid1/omx)

## Multi-Agent Systems

*Frameworks and projects where multiple agents collaborate, debate, or compete.*

- [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) — One of the first autonomous AI agent projects, capable of self-prompting to achieve complex goals. ![GitHub Repo stars](https://img.shields.io/github/stars/Significant-Gravitas/AutoGPT)
- [MetaGPT](https://github.com/geekan/MetaGPT) — Multi-agent framework that assigns different roles (PM, architect, engineer) to GPTs to form a collaborative software company. ![GitHub Repo stars](https://img.shields.io/github/stars/geekan/MetaGPT)
- [BabyAGI](https://github.com/yoheinakajima/babyagi) — Minimal framework demonstrating AI-powered task management with autonomous task creation and prioritization.
- [ChatDev](https://github.com/OpenBMB/ChatDev) — Virtual software company where agents fill roles like CEO, CTO, programmer, and tester to build software collaboratively. ![GitHub Repo stars](https://img.shields.io/github/stars/OpenBMB/ChatDev)
- [CAMEL](https://github.com/camel-ai/camel) — Communicative Agents for "Mind" Exploration of Large Language Model Society; role-playing agent framework. ![GitHub Repo stars](https://img.shields.io/github/stars/camel-ai/camel)
- [GPTeam](https://github.com/101dotxyz/GPTeam) — Multi-agent simulation where AI agents collaborate, form memories, and interact in a shared world.
- [Swarm](https://github.com/openai/swarm) — OpenAI's experimental framework for lightweight multi-agent orchestration and handoffs.

## Agent Memory

*Systems for giving agents persistent memory across sessions.*

- [Mem0](https://github.com/mem0ai/mem0) — Memory layer for AI agents. Persistent, contextual memory that improves over time. ![GitHub Repo stars](https://img.shields.io/github/stars/mem0ai/mem0)
- [Letta](https://github.com/letta-ai/letta) — Framework for creating LLM agents with long-term memory and self-editing capabilities. ![GitHub Repo stars](https://img.shields.io/github/stars/letta-ai/letta)
- [Zep](https://github.com/getzep/zep) — Long-term memory for AI assistants with facts extraction, entity graphs, and temporal awareness. ![GitHub Repo stars](https://img.shields.io/github/stars/getzep/zep)
- [BrainCTL](https://github.com/brainctl/brainctl) — Single SQLite file memory system with FTS5 search, knowledge graph, and write gate for redundancy rejection.

## Agent Security

*Tools and resources for securing AI agents, preventing prompt injection, and safe deployment.*

- [Rebuff](https://github.com/protectai/rebuff) — Self-hardening prompt injection detector that learns from attacks to improve over time.
- [LLM Guard](https://github.com/protectai/llm-guard) — Comprehensive toolkit for securing LLM interactions with input/output scanners for toxicity, PII, and prompt injection. ![GitHub Repo stars](https://img.shields.io/github/stars/protectai/llm-guard)
- [Garak](https://github.com/NVIDIA/garak) — NVIDIA's LLM vulnerability scanner that probes for hallucination, data leakage, prompt injection, and more.
- [NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails) — NVIDIA toolkit for adding programmable safety rails to LLM-powered applications. ![GitHub Repo stars](https://img.shields.io/github/stars/NVIDIA/NeMo-Guardrails)
- [Invariant Guardrails](https://github.com/invariantlabs-ai/invariant) — Runtime security for AI agents. Monitors tool calls and blocks unsafe actions in real-time.
- [Snyk ToxicSkills Research](https://snyk.io/blog/toxicskills-malicious-ai-agent-skills-clawhub/) — First comprehensive audit of agent skills. Found 13.4% critical security issues across 3,984 skills. [Full security analysis](https://virtualuncle.com/agent-skills-marketplace-skills-sh-2026/)

## Agent Monitoring & Observability

*Tools for tracing, debugging, and monitoring agent behavior in production.*

- [LangSmith](https://github.com/langchain-ai/langsmith-sdk) — Platform for debugging, testing, evaluating, and monitoring LLM applications and agents.
- [Langfuse](https://github.com/langfuse/langfuse) — Open-source LLM engineering platform with tracing, evaluations, prompt management, and metrics. ![GitHub Repo stars](https://img.shields.io/github/stars/langfuse/langfuse)
- [Phoenix](https://github.com/Arize-AI/phoenix) — Open-source observability for LLM applications with tracing, evaluation, and dataset management. ![GitHub Repo stars](https://img.shields.io/github/stars/Arize-AI/phoenix)
- [OpenLLMetry](https://github.com/traceloop/openllmetry) — Open-source observability for LLMs built on OpenTelemetry, providing vendor-neutral tracing.
- [AgentOps](https://github.com/AgentOps-AI/agentops) — Toolkit for agent monitoring, testing, and replay with session-level observability.
- [Helicone](https://github.com/Helicone/helicone) — Open-source LLM observability platform with request logging, caching, rate limiting, and analytics.

## Hardware for Agents

*Infrastructure, edge computing, and hardware projects designed for running AI agents.*

- [Ollama](https://github.com/ollama/ollama) — Run large language models locally with a simple API, enabling offline and edge agent deployments. ![GitHub Repo stars](https://img.shields.io/github/stars/ollama/ollama)
- [llama.cpp](https://github.com/ggerganov/llama.cpp) — Efficient C/C++ inference of LLMs on commodity hardware, powering local agent runtimes. ![GitHub Repo stars](https://img.shields.io/github/stars/ggerganov/llama.cpp)
- [vLLM](https://github.com/vllm-project/vllm) — High-throughput LLM serving engine with PagedAttention, designed for production agent workloads. ![GitHub Repo stars](https://img.shields.io/github/stars/vllm-project/vllm)
- [LocalAI](https://github.com/mudler/LocalAI) — Drop-in OpenAI-compatible API for running LLMs locally on consumer-grade hardware. ![GitHub Repo stars](https://img.shields.io/github/stars/mudler/LocalAI)
- [TensorRT-LLM](https://github.com/NVIDIA/TensorRT-LLM) — NVIDIA library for optimizing LLM inference on GPUs with quantization and kernel fusion.

## Learning Resources

*Tutorials, courses, papers, and guides for understanding and building AI agents.*

- [LLM Powered Autonomous Agents](https://lilianweng.github.io/posts/2023-06-23-agent/) — Lilian Weng's (OpenAI) comprehensive blog post on the architecture of LLM-based agents.
- [The Rise and Potential of Large Language Model Based Agents](https://arxiv.org/abs/2309.07864) — Survey paper covering the full landscape of LLM-based agents.
- [Building Effective Agents](https://www.anthropic.com/research/building-effective-agents) — Anthropic's guide to practical patterns for building reliable AI agents.
- [Andrew Ng's AI Agentic Design Patterns](https://www.deeplearning.ai/the-batch/how-agents-can-improve-llm-performance/) — Overview of core agentic design patterns: reflection, tool use, planning, and multi-agent collaboration.
- [AutoGPT Blog](https://news.agpt.co/) — Blog covering developments in autonomous AI agents and the AutoGPT ecosystem.
- [Awesome LLM-Powered Agent](https://github.com/hyp1231/awesome-llm-powered-agent) — Another curated list focused on the academic research side of LLM agents.
- [Agent Protocol](https://github.com/AI-Engineer-Foundation/agent-protocol) — Unified API specification for communicating with AI agents, enabling interoperability.

---

## Contributing

Contributions are welcome! Please read the [contributing guidelines](CONTRIBUTING.md) before submitting a pull request.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work. See [LICENSE](LICENSE) for details.
