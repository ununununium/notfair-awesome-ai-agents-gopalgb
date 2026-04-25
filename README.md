# Awesome AI Agents [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of AI agent frameworks, tools, platforms, and resources for building autonomous AI systems.

AI agents are systems that use LLMs to reason, plan, and take actions autonomously. This list covers the full ecosystem -- from frameworks for building agents to tools for monitoring, orchestrating, and deploying them in production.

**Star this repo** to keep up with the rapidly evolving AI agent landscape.

---

## Contents

- [Agent Frameworks](#agent-frameworks)
- [Multi-Agent Systems](#multi-agent-systems)
- [Memory & State](#memory--state)
- [Orchestration & Workflow](#orchestration--workflow)
- [Monitoring & Observability](#monitoring--observability)
- [Platforms & APIs](#platforms--apis)
- [Developer Tools](#developer-tools)
- [Code Agents](#code-agents)
- [Open Source Agents](#open-source-agents)
- [RAG & Knowledge](#rag--knowledge)
- [Agent Infrastructure](#agent-infrastructure)
- [Evaluation & Testing](#evaluation--testing)
- [Voice & Multimodal Agents](#voice--multimodal-agents)
- [Papers & Research](#papers--research)
- [Tutorials & Courses](#tutorials--courses)
- [Community](#community)
- [Contributing](#contributing)

---

## Agent Frameworks

Frameworks for building, composing, and deploying AI agents.

| Name | Stars | Description |
|------|-------|-------------|
| [LangChain](https://github.com/langchain-ai/langchain) | ![Stars](https://img.shields.io/github/stars/langchain-ai/langchain?style=flat-square&label=) | Framework for developing applications powered by LLMs with chains, agents, and retrieval |
| [LangGraph](https://github.com/langchain-ai/langgraph) | ![Stars](https://img.shields.io/github/stars/langchain-ai/langgraph?style=flat-square&label=) | Library for building stateful, multi-step agent workflows as graphs |
| [CrewAI](https://github.com/crewAIInc/crewAI) | ![Stars](https://img.shields.io/github/stars/crewAIInc/crewAI?style=flat-square&label=) | Framework for orchestrating role-playing autonomous AI agents in collaborative crews |
| [DSPy](https://github.com/stanfordnlp/dspy) | ![Stars](https://img.shields.io/github/stars/stanfordnlp/dspy?style=flat-square&label=) | Framework for programming (not prompting) LMs with composable and optimizable modules |
| [AutoGen](https://github.com/microsoft/autogen) | ![Stars](https://img.shields.io/github/stars/microsoft/autogen?style=flat-square&label=) | Microsoft's framework for building multi-agent conversational AI systems |
| [Agno](https://github.com/agno-agi/agno) | ![Stars](https://img.shields.io/github/stars/agno-agi/agno?style=flat-square&label=) | Lightweight framework for building multimodal AI agents with memory and tools |
| [Smolagents](https://github.com/huggingface/smolagents) | ![Stars](https://img.shields.io/github/stars/huggingface/smolagents?style=flat-square&label=) | Hugging Face's minimalist library for building powerful agents in few lines of code |
| [PydanticAI](https://github.com/pydantic/pydantic-ai) | ![Stars](https://img.shields.io/github/stars/pydantic/pydantic-ai?style=flat-square&label=) | Agent framework from the Pydantic team with type-safe, model-agnostic design |
| [Swarm](https://github.com/openai/swarm) | ![Stars](https://img.shields.io/github/stars/openai/swarm?style=flat-square&label=) | OpenAI's lightweight multi-agent orchestration framework (educational) |
| [Atomic Agents](https://github.com/BrainBlend-AI/atomic-agents) | ![Stars](https://img.shields.io/github/stars/BrainBlend-AI/atomic-agents?style=flat-square&label=) | Modular, composable framework for building AI agents with atomic components |
| [Llama Agents](https://github.com/run-llama/llama-agents) | ![Stars](https://img.shields.io/github/stars/run-llama/llama-agents?style=flat-square&label=) | Async framework for building multi-agent systems from LlamaIndex |
| [ControlFlow](https://github.com/PrefectHQ/ControlFlow) | ![Stars](https://img.shields.io/github/stars/PrefectHQ/ControlFlow?style=flat-square&label=) | Agentic AI framework by Prefect for building structured, observable workflows |

## Multi-Agent Systems

Frameworks and platforms focused on multi-agent coordination and collaboration.

| Name | Stars | Description |
|------|-------|-------------|
| [MetaGPT](https://github.com/geekan/MetaGPT) | ![Stars](https://img.shields.io/github/stars/geekan/MetaGPT?style=flat-square&label=) | Multi-agent framework that assigns different roles (PM, Engineer, QA) to GPTs for complex tasks |
| [ChatDev](https://github.com/OpenBMB/ChatDev) | ![Stars](https://img.shields.io/github/stars/OpenBMB/ChatDev?style=flat-square&label=) | Virtual software company with agents acting as CEO, CTO, programmer, and tester |
| [Swarms](https://github.com/kyegomez/swarms) | ![Stars](https://img.shields.io/github/stars/kyegomez/swarms?style=flat-square&label=) | Enterprise-grade multi-agent orchestration framework with swarm intelligence |
| [CAMEL](https://github.com/camel-ai/camel) | ![Stars](https://img.shields.io/github/stars/camel-ai/camel?style=flat-square&label=) | Communicative agents for "mind" exploration of large-scale language model society |
| [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) | ![Stars](https://img.shields.io/github/stars/Significant-Gravitas/AutoGPT?style=flat-square&label=) | Autonomous GPT-4 agent that chains thoughts to achieve goals independently |
| [BabyAGI](https://github.com/yoheinakajima/babyagi) | ![Stars](https://img.shields.io/github/stars/yoheinakajima/babyagi?style=flat-square&label=) | AI-powered task management system that creates, prioritizes, and executes tasks |
| [SuperAGI](https://github.com/TransformerOptimus/SuperAGI) | ![Stars](https://img.shields.io/github/stars/TransformerOptimus/SuperAGI?style=flat-square&label=) | Open-source autonomous AI agent framework with tools, memory, and concurrent agents |

## Memory & State

Systems for giving agents persistent memory and managing conversational state.

| Name | Stars | Description |
|------|-------|-------------|
| [Mem0](https://github.com/mem0ai/mem0) | ![Stars](https://img.shields.io/github/stars/mem0ai/mem0?style=flat-square&label=) | Self-improving memory layer for LLM applications with personalization |
| [Zep](https://github.com/getzep/zep) | ![Stars](https://img.shields.io/github/stars/getzep/zep?style=flat-square&label=) | Long-term memory for AI assistants with facts, summaries, and knowledge graphs |
| [Letta (MemGPT)](https://github.com/letta-ai/letta) | ![Stars](https://img.shields.io/github/stars/letta-ai/letta?style=flat-square&label=) | Framework for creating LLM agents with long-term memory and self-editing capabilities |
| [Chromadb](https://github.com/chroma-core/chroma) | ![Stars](https://img.shields.io/github/stars/chroma-core/chroma?style=flat-square&label=) | AI-native open-source embedding database for agent memory and retrieval |
| [Milvus](https://github.com/milvus-io/milvus) | ![Stars](https://img.shields.io/github/stars/milvus-io/milvus?style=flat-square&label=) | Cloud-native vector database for scalable similarity search and AI applications |

## Orchestration & Workflow

Tools for orchestrating agent workflows, scheduling, and process automation.

| Name | Stars | Description |
|------|-------|-------------|
| [n8n](https://github.com/n8n-io/n8n) | ![Stars](https://img.shields.io/github/stars/n8n-io/n8n?style=flat-square&label=) | Fair-code workflow automation with AI agent capabilities and 400+ integrations |
| [Temporal](https://github.com/temporalio/temporal) | ![Stars](https://img.shields.io/github/stars/temporalio/temporal?style=flat-square&label=) | Durable execution platform for reliable agent workflows and orchestration |
| [Prefect](https://github.com/PrefectHQ/prefect) | ![Stars](https://img.shields.io/github/stars/PrefectHQ/prefect?style=flat-square&label=) | Workflow orchestration framework for building data pipelines and AI workflows |
| [Inngest](https://github.com/inngest/inngest) | ![Stars](https://img.shields.io/github/stars/inngest/inngest?style=flat-square&label=) | Durable workflow engine for AI-powered applications with step functions and retries |
| [Windmill](https://github.com/windmill-labs/windmill) | ![Stars](https://img.shields.io/github/stars/windmill-labs/windmill?style=flat-square&label=) | Open-source developer platform for scripts, workflows, and UIs as code |

## Monitoring & Observability

Tools for tracing, debugging, and monitoring AI agent systems in production.

| Name | Stars | Description |
|------|-------|-------------|
| [Logfire](https://github.com/pydantic/logfire) | ![Stars](https://img.shields.io/github/stars/pydantic/logfire?style=flat-square&label=) | Observability platform from Pydantic for monitoring Python apps and AI agents |
| [LangSmith](https://smith.langchain.com/) | -- | LangChain's platform for debugging, testing, evaluating, and monitoring LLM applications |
| [Langfuse](https://github.com/langfuse/langfuse) | ![Stars](https://img.shields.io/github/stars/langfuse/langfuse?style=flat-square&label=) | Open-source LLM engineering platform with tracing, evals, and prompt management |
| [Arize Phoenix](https://github.com/Arize-ai/phoenix) | ![Stars](https://img.shields.io/github/stars/Arize-ai/phoenix?style=flat-square&label=) | Open-source AI observability with traces, evaluations, and dataset management |
| [OpenLLMetry](https://github.com/traceloop/openllmetry) | ![Stars](https://img.shields.io/github/stars/traceloop/openllmetry?style=flat-square&label=) | Open-source observability for LLM applications using OpenTelemetry |
| [Helicone](https://github.com/Helicone/helicone) | ![Stars](https://img.shields.io/github/stars/Helicone/helicone?style=flat-square&label=) | Open-source LLM observability platform with logging, caching, and rate limiting |

## Platforms & APIs

Commercial platforms and APIs for building and deploying AI agents.

| Name | Description |
|------|-------------|
| [OpenAI Assistants API](https://platform.openai.com/docs/assistants) | Build AI assistants with tools, files, and persistent threads |
| [Anthropic Claude Tool Use](https://docs.anthropic.com/en/docs/tool-use) | Claude's function calling and tool use for building agentic systems |
| [Google Gemini](https://ai.google.dev/) | Google's multimodal AI with function calling and grounding capabilities |
| [AWS Bedrock Agents](https://aws.amazon.com/bedrock/agents/) | Fully managed service for building AI agents on AWS infrastructure |
| [Azure AI Agent Service](https://azure.microsoft.com/en-us/products/ai-services/) | Microsoft's enterprise platform for deploying AI agents at scale |
| [Vertex AI Agent Builder](https://cloud.google.com/products/agent-builder) | Google Cloud's platform for building conversational AI agents |
| [Relevance AI](https://relevanceai.com/) | No-code platform for building and deploying AI agents and workflows |

## Developer Tools

IDEs, coding assistants, and development tools for building with AI agents.

| Name | Stars | Description |
|------|-------|-------------|
| [Claude Code](https://docs.anthropic.com/en/docs/claude-code) | -- | Anthropic's agentic coding tool that operates directly in your terminal |
| [Cursor](https://cursor.com/) | -- | AI-first code editor with multi-file editing, codebase understanding, and agent mode |
| [aider](https://github.com/Aider-AI/aider) | ![Stars](https://img.shields.io/github/stars/Aider-AI/aider?style=flat-square&label=) | AI pair programming in your terminal that edits code in your local git repo |
| [Continue](https://github.com/continuedev/continue) | ![Stars](https://img.shields.io/github/stars/continuedev/continue?style=flat-square&label=) | Open-source AI code assistant for VS Code and JetBrains |
| [OpenHands](https://github.com/All-Hands-AI/OpenHands) | ![Stars](https://img.shields.io/github/stars/All-Hands-AI/OpenHands?style=flat-square&label=) | Platform for AI-powered software development agents (formerly OpenDevin) |
| [SWE-agent](https://github.com/princeton-nlp/SWE-agent) | ![Stars](https://img.shields.io/github/stars/princeton-nlp/SWE-agent?style=flat-square&label=) | Agent that autonomously fixes GitHub issues using LLMs |
| [v0](https://v0.dev/) | -- | Vercel's generative UI tool that creates React components from prompts |
| [bolt.new](https://bolt.new/) | -- | StackBlitz's AI-powered full-stack web development agent in the browser |
| [Devika](https://github.com/stitionai/devika) | ![Stars](https://img.shields.io/github/stars/stitionai/devika?style=flat-square&label=) | Agentic AI software engineer that understands instructions and writes code |

## Code Agents

Specialized agents focused on software engineering tasks.

| Name | Stars | Description |
|------|-------|-------------|
| [Devin](https://devin.ai/) | -- | Cognition's autonomous AI software engineer |
| [Codex](https://github.com/openai/codex) | ![Stars](https://img.shields.io/github/stars/openai/codex?style=flat-square&label=) | OpenAI's lightweight coding agent that runs in your terminal |
| [Copilot Workspace](https://githubnext.com/projects/copilot-workspace) | -- | GitHub's agent-powered development environment for planning and implementing changes |
| [Cline](https://github.com/cline/cline) | ![Stars](https://img.shields.io/github/stars/cline/cline?style=flat-square&label=) | Autonomous coding agent for VS Code that uses CLI and browser |
| [Mentat](https://github.com/AbanteAI/mentat) | ![Stars](https://img.shields.io/github/stars/AbanteAI/mentat?style=flat-square&label=) | AI coding assistant that works with your codebase from the command line |
| [GPT Engineer](https://github.com/gpt-engineer-org/gpt-engineer) | ![Stars](https://img.shields.io/github/stars/gpt-engineer-org/gpt-engineer?style=flat-square&label=) | Specify what you want it to build, the AI asks for clarification, and then builds it |
| [Plandex](https://github.com/plandex-ai/plandex) | ![Stars](https://img.shields.io/github/stars/plandex-ai/plandex?style=flat-square&label=) | AI coding engine for complex tasks spanning many files and steps |

## Open Source Agents

Standalone open-source agent projects for various use cases.

| Name | Stars | Description |
|------|-------|-------------|
| [Open Interpreter](https://github.com/OpenInterpreter/open-interpreter) | ![Stars](https://img.shields.io/github/stars/OpenInterpreter/open-interpreter?style=flat-square&label=) | Natural language interface for your computer that runs code locally |
| [GPT Researcher](https://github.com/assafelovic/gpt-researcher) | ![Stars](https://img.shields.io/github/stars/assafelovic/gpt-researcher?style=flat-square&label=) | Autonomous agent for comprehensive online research on any topic |
| [AgentGPT](https://github.com/reworkd/AgentGPT) | ![Stars](https://img.shields.io/github/stars/reworkd/AgentGPT?style=flat-square&label=) | Assemble, configure, and deploy autonomous AI agents in your browser |
| [Phidata](https://github.com/phidatahq/phidata) | ![Stars](https://img.shields.io/github/stars/phidatahq/phidata?style=flat-square&label=) | Build multi-modal agents with memory, knowledge, tools, and reasoning |
| [AgentScope](https://github.com/modelscope/agentscope) | ![Stars](https://img.shields.io/github/stars/modelscope/agentscope?style=flat-square&label=) | Multi-agent platform with distributed support from Alibaba |
| [Composio](https://github.com/ComposioHQ/composio) | ![Stars](https://img.shields.io/github/stars/ComposioHQ/composio?style=flat-square&label=) | Integration platform for AI agents with 250+ tools (GitHub, Slack, Jira, etc.) |
| [Browser Use](https://github.com/browser-use/browser-use) | ![Stars](https://img.shields.io/github/stars/browser-use/browser-use?style=flat-square&label=) | Make AI agents interact with websites through natural browser automation |
| [OASIS](https://github.com/camel-ai/oasis) | ![Stars](https://img.shields.io/github/stars/camel-ai/oasis?style=flat-square&label=) | Open agent social interaction simulator — model up to 1M agents with sentiment evolution and counter-narrative dynamics |
| [agent-outbound](https://github.com/sodiray/agent-outbound) | ![Stars](https://img.shields.io/github/stars/sodiray/agent-outbound?style=flat-square&label=) | LLM-powered cold email outreach agent with deliverability monitoring and reply classification |
| [Postiz](https://github.com/gitroomhq/postiz-app) | ![Stars](https://img.shields.io/github/stars/gitroomhq/postiz-app?style=flat-square&label=) | Open-source social media scheduling agent with AI content generation for LinkedIn, X, and other platforms |

## RAG & Knowledge

Tools for retrieval-augmented generation and knowledge management for agents.

| Name | Stars | Description |
|------|-------|-------------|
| [LlamaIndex](https://github.com/run-llama/llama_index) | ![Stars](https://img.shields.io/github/stars/run-llama/llama_index?style=flat-square&label=) | Data framework for connecting LLMs with external data sources |
| [Haystack](https://github.com/deepset-ai/haystack) | ![Stars](https://img.shields.io/github/stars/deepset-ai/haystack?style=flat-square&label=) | End-to-end NLP framework for building RAG pipelines and search systems |
| [Unstructured](https://github.com/Unstructured-IO/unstructured) | ![Stars](https://img.shields.io/github/stars/Unstructured-IO/unstructured?style=flat-square&label=) | Open-source toolkit for ingesting and preprocessing documents for RAG |
| [Embedchain](https://github.com/embedchain/embedchain) | ![Stars](https://img.shields.io/github/stars/embedchain/embedchain?style=flat-square&label=) | Framework for creating RAG-powered bots over any dataset |
| [RAGFlow](https://github.com/infiniflow/ragflow) | ![Stars](https://img.shields.io/github/stars/infiniflow/ragflow?style=flat-square&label=) | Open-source RAG engine with deep document understanding |

## Agent Infrastructure

Tools and protocols for agent communication, tool use, and deployment.

| Name | Stars | Description |
|------|-------|-------------|
| [MCP (Model Context Protocol)](https://github.com/modelcontextprotocol) | -- | Anthropic's open protocol for connecting AI models with data sources and tools |
| [Ollama](https://github.com/ollama/ollama) | ![Stars](https://img.shields.io/github/stars/ollama/ollama?style=flat-square&label=) | Run large language models locally for private agent deployments |
| [vLLM](https://github.com/vllm-project/vllm) | ![Stars](https://img.shields.io/github/stars/vllm-project/vllm?style=flat-square&label=) | High-throughput LLM serving engine for production agent deployments |
| [LiteLLM](https://github.com/BerriAI/litellm) | ![Stars](https://img.shields.io/github/stars/BerriAI/litellm?style=flat-square&label=) | Unified API to call 100+ LLM providers with load balancing and spend tracking |
| [Instructor](https://github.com/jxnl/instructor) | ![Stars](https://img.shields.io/github/stars/jxnl/instructor?style=flat-square&label=) | Structured output from LLMs with validation -- essential for reliable agent tool use |

## Evaluation & Testing

Frameworks for evaluating and testing AI agent performance.

| Name | Stars | Description |
|------|-------|-------------|
| [GAIA Benchmark](https://github.com/ChuanMQuan/gaia-benchmark) | -- | Benchmark for general AI assistants testing real-world multi-step reasoning |
| [AgentBench](https://github.com/THUDM/AgentBench) | ![Stars](https://img.shields.io/github/stars/THUDM/AgentBench?style=flat-square&label=) | Benchmark for evaluating LLMs as agents across diverse environments |
| [SWE-bench](https://github.com/princeton-nlp/SWE-bench) | ![Stars](https://img.shields.io/github/stars/princeton-nlp/SWE-bench?style=flat-square&label=) | Benchmark for evaluating LLMs on real-world software engineering problems |
| [DeepEval](https://github.com/confident-ai/deepeval) | ![Stars](https://img.shields.io/github/stars/confident-ai/deepeval?style=flat-square&label=) | Open-source evaluation framework for LLMs and AI agents |
| [Ragas](https://github.com/explodinggradients/ragas) | ![Stars](https://img.shields.io/github/stars/explodinggradients/ragas?style=flat-square&label=) | Evaluation framework for RAG pipelines with metrics for faithfulness and relevancy |

## Voice & Multimodal Agents

Agents that work with voice, vision, and multiple modalities.

| Name | Stars | Description |
|------|-------|-------------|
| [LiveKit Agents](https://github.com/livekit/agents) | ![Stars](https://img.shields.io/github/stars/livekit/agents?style=flat-square&label=) | Build real-time multimodal AI agents with voice, video, and data channels |
| [Pipecat](https://github.com/pipecat-ai/pipecat) | ![Stars](https://img.shields.io/github/stars/pipecat-ai/pipecat?style=flat-square&label=) | Open-source framework for voice and multimodal conversational AI |
| [Vocode](https://github.com/vocodedev/vocode-python) | ![Stars](https://img.shields.io/github/stars/vocodedev/vocode-python?style=flat-square&label=) | Build voice-based LLM agents with streaming speech-to-speech pipelines |
| [OpenAI Realtime API](https://platform.openai.com/docs/guides/realtime) | -- | Native speech-to-speech API for building real-time voice agents |

## Papers & Research

Key academic papers on AI agents and autonomous systems.

| Paper | Year | Description |
|-------|------|-------------|
| [ReAct: Synergizing Reasoning and Acting](https://arxiv.org/abs/2210.03629) | 2022 | Foundational paper on combining reasoning traces with actions in LLMs |
| [Toolformer](https://arxiv.org/abs/2302.04761) | 2023 | Teaching language models to use tools autonomously |
| [Generative Agents](https://arxiv.org/abs/2304.03442) | 2023 | Interactive simulacra of human behavior using LLM-powered agents |
| [Voyager](https://arxiv.org/abs/2305.16291) | 2023 | LLM-powered embodied agent for lifelong learning in Minecraft |
| [Chain-of-Thought Prompting](https://arxiv.org/abs/2201.11903) | 2022 | Eliciting reasoning in LLMs through chain-of-thought demonstrations |
| [Tree of Thoughts](https://arxiv.org/abs/2305.10601) | 2023 | Deliberate problem solving with LLMs through exploration of reasoning paths |
| [Reflexion](https://arxiv.org/abs/2303.11366) | 2023 | Language agents with verbal reinforcement learning |
| [LATS](https://arxiv.org/abs/2310.04406) | 2023 | Language Agent Tree Search -- unifying reasoning, acting, and planning |
| [The Landscape of Emerging AI Agent Architectures](https://arxiv.org/abs/2404.11584) | 2024 | Survey of multi-agent system architectures and design patterns |
| [A Survey on Large Language Model based Autonomous Agents](https://arxiv.org/abs/2308.11432) | 2023 | Comprehensive survey covering agent construction, applications, and evaluation |

## Tutorials & Courses

Learning resources for building AI agents.

| Resource | Description |
|----------|-------------|
| [DeepLearning.AI - AI Agents in LangGraph](https://www.deeplearning.ai/short-courses/ai-agents-in-langgraph/) | Short course on building agentic workflows with LangGraph |
| [DeepLearning.AI - Multi AI Agent Systems with CrewAI](https://www.deeplearning.ai/short-courses/multi-ai-agent-systems-with-crewai/) | Short course on multi-agent orchestration with CrewAI |
| [LangChain Academy](https://academy.langchain.com/) | Official courses on building with LangChain and LangGraph |
| [Hugging Face Agents Course](https://huggingface.co/learn/agents-course) | Free course on building AI agents with open-source tools |
| [AI Agent Infrastructure (Newsletter)](https://www.aiagentinfra.com/) | Weekly newsletter covering AI agent tools and infrastructure |
| [Awesome LLM-Powered Agent](https://github.com/hyp1231/awesome-llm-powered-agent) | Another curated list focused on LLM-powered autonomous agents |

## Community

Places to discuss AI agents and connect with builders.

| Community | Description |
|-----------|-------------|
| [r/AI_Agents](https://www.reddit.com/r/AI_Agents/) | Reddit community for AI agent discussions |
| [LangChain Discord](https://discord.gg/langchain) | Official LangChain community |
| [CrewAI Discord](https://discord.gg/crewai) | Official CrewAI community |
| [AI Agent Twitter/X List](https://x.com/i/lists/ai-agents) | Curated list of AI agent builders and researchers |

---

## Contributing

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

### How to Contribute

1. Fork this repository
2. Add your resource in the appropriate category
3. Use the format: `| [Name](link) | ![Stars](badge) | One-line description |`
4. Submit a pull request

### Criteria for Inclusion

- Must be actively maintained (commit within last 6 months)
- Must be relevant to AI agents (not general ML/AI tools)
- Must have a clear README or documentation
- Open-source projects preferred, but notable commercial tools accepted
- No duplicate entries

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Gopal Bagaswar](https://github.com/GopalGB) has waived all copyright and related or neighboring rights to this work.


| [AgentScope](https://github.com/agentscope-ai/agentscope) | ![Stars](https://img.shields.io/github/stars/agentscope-ai/agentscope?style=flat-square&label=) | Production-ready agent framework with ReAct agents, MCP support, voice agents, and multi-model routing. Supports Anthropic, OpenAI, DashScope, Gemini, Ollama |
