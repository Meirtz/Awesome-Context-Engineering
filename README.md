# awesome-context-engineering

### Table of contents
- ✍️ [Write Context](#%EF%B8%8F-write-context)
- 🔎 [Select Context](#-select-context)
- ✂️ [Compress Context](#%EF%B8%8F-compress-context)
- 📦 [Isolate Context](#-isolate-context)

### What is Context Engineering?
[Tobias Lütke](https://x.com/tobi/status/1935533422589399127) (2025.06.19)
> I really like the term “**context engineering**” over prompt engineering.
> 
> It describes the core skill better: the art of providing all the context for the task to be plausibly solvable by the LLM.

[Andrej Karpathy](https://x.com/karpathy/status/1937902205765607626) (2025.06.26)
> +1 for "context engineering" over "prompt engineering".
> 
> ... **context engineering** is the delicate art and science of filling the context window with just the right information for the next step ...

![image](https://github.com/user-attachments/assets/e9550a21-26f2-47c2-9860-bf711b4826cf)
Image source: https://blog.langchain.com/context-engineering-for-agents/

## ✍️ Write Context
### Long-term memory
- [mem0](https://github.com/mem0ai/mem0) (`mem0ai`) ![](https://img.shields.io/github/stars/mem0ai/mem0.svg?style=social) Memory for AI Agents; Announcing OpenMemory MCP - local and secure memory management.
- [letta](https://github.com/letta-ai/letta) (`letta-ai`) ![](https://img.shields.io/github/stars/letta-ai/letta.svg?style=social) Letta (formerly MemGPT) is the stateful agents framework with memory, reasoning, and context management.
- [graphiti](https://github.com/getzep/graphiti) (`getzep`) ![](https://img.shields.io/github/stars/getzep/graphiti.svg?style=social) Build Real-Time Knowledge Graphs for AI Agents
- [cognee](https://github.com/topoteretes/cognee) (`topoteretes`) ![](https://img.shields.io/github/stars/topoteretes/cognee.svg?style=social) Memory for AI Agents in 5 lines of code
- [Memary](https://github.com/kingjulio8238/Memary) ![](https://img.shields.io/github/stars/kingjulio8238/Memary.svg?style=social) The Open Source Memory Layer For Autonomous Agents
- [memobase](https://github.com/memodb-io/memobase) (`memodb-io`) ![](https://img.shields.io/github/stars/memodb-io/memobase.svg?style=social) Profile-Based Long-Term Memory for AI Applications. Memobase handles user profiles, memory events, and evolving context
- [A-mem](https://github.com/agiresearch/A-mem) (`agiresearch`) ![](https://img.shields.io/github/stars/agiresearch/A-mem.svg?style=social) A-MEM: Agentic Memory for LLM Agents
- [MemoryOS](https://github.com/BAI-LAB/MemoryOS) (`BAI-LAB`) ![](https://img.shields.io/github/stars/BAI-LAB/MemoryOS.svg?style=social) A memory operation system for personalized AI
- [core](https://github.com/RedPlanetHQ/core) (`RedPlanetHQ`) ![](https://img.shields.io/github/stars/RedPlanetHQ/core.svg?style=social) Your personal plug and play memory layer for LLMs

## 🔎 Select Context

### MCP Servers
- [awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) ![](https://img.shields.io/github/stars/punkpeye/awesome-mcp-servers.svg?style=social) A collection of MCP servers.
- [mcp-servers](https://github.com/modelcontextprotocol/servers) (`modelcontextprotocol`) ![](https://img.shields.io/github/stars/modelcontextprotocol/servers.svg?style=social) Model Context Protocol Servers

### MCP Frameworks
- [mcp-python-sdk](https://github.com/modelcontextprotocol/python-sdk) (`modelcontextprotocol`) ![](https://img.shields.io/github/stars/modelcontextprotocol/python-sdk.svg?style=social) The official Python SDK for Model Context Protocol servers and clients
- [fastmcp](https://github.com/jlowin/fastmcp) (`CEO at PrefectHQ`) ![](https://img.shields.io/github/stars/jlowin/fastmcp.svg?style=social) The fast, Pythonic way to build MCP servers and clients
- [fastapi_mcp](https://github.com/tadata-org/fastapi_mcp) (`tadata-org`) ![](https://img.shields.io/github/stars/tadata-org/fastapi_mcp.svg?style=social) Expose your FastAPI endpoints as Model Context Protocol (MCP) tools, with Auth!
- [mcp-agent](https://github.com/lastmile-ai/mcp-agent) (`lastmile-ai`) ![](https://img.shields.io/github/stars/lastmile-ai/mcp-agent.svg?style=social) Build effective agents using Model Context Protocol and simple workflow patterns
- [mcp-use](https://github.com/mcp-use/mcp-use) (`mcp-use`) ![](https://img.shields.io/github/stars/mcp-use/mcp-use.svg?style=social) mcp-use is the easiest way to interact with mcp servers with custom agents
- [golf](https://github.com/golf-mcp/golf) (`golf-mcp`) ![](https://img.shields.io/github/stars/golf-mcp/golf.svg?style=social) Production-Ready MCP Server Framework • Build, deploy & scale secure AI agent infrastructure • Includes Auth, Observability, Debugger, Telemetry & Runtime • Run real-world MCPs powering AI Agents
- [enrichmcp](https://github.com/featureform/enrichmcp) (`featureform`) ![](https://img.shields.io/github/stars/featureform/enrichmcp.svg?style=social) EnrichMCP is a python framework for building data driven MCP servers

## ✂️ Compress Context
### Prompt compression
- [LLMLingua](https://github.com/microsoft/LLMLingua) (`microsoft`) ![](https://img.shields.io/github/stars/microsoft/LLMLingua.svg?style=social) To speed up LLMs' inference and enhance LLM's perceive of key information, compress the prompt and KV-Cache, which achieves up to 20x compression with minimal performance loss.
- [sammo](https://github.com/microsoft/sammo) (`microsoft`) ![](https://img.shields.io/github/stars/microsoft/sammo.svg?style=social) A library for prompt engineering and optimization (SAMMO = Structure-aware Multi-Objective Metaprompt Optimization)
- [Selective_Context](https://github.com/liyucheng09/Selective_Context) ![](https://img.shields.io/github/stars/liyucheng09/Selective_Context.svg?style=social) Compress your input to ChatGPT or other LLMs, to let them process 2x more content and save 40% memory and GPU time.
- [Toolkit-for-Prompt-Compression](https://github.com/3DAgentWorld/Toolkit-for-Prompt-Compression) (`3DAgentWorld`) ![](https://img.shields.io/github/stars/3DAgentWorld/Toolkit-for-Prompt-Compression.svg?style=social) Toolkit for Prompt Compression
- [500xCompressor](https://github.com/ZongqianLi/500xCompressor) ![](https://img.shields.io/github/stars/ZongqianLi/500xCompressor.svg?style=social) 500xCompressor: Generalized Prompt Compression for Large Language Models

### RAG compression
- [xRAG](https://github.com/Hannibal046/xRAG) ![](https://img.shields.io/github/stars/Hannibal046/xRAG.svg?style=social) xRAG: Extreme Context Compression for Retrieval-augmented Generation with One Token
- [recomp](https://github.com/carriex/recomp) ![](https://img.shields.io/github/stars/carriex/recomp.svg?style=social) RECOMP: Improving Retrieval-Augmented LMs with Compression and Selective Augmentation.
- [CompAct](https://github.com/dmis-lab/CompAct) (`dmis-lab`) ![](https://img.shields.io/github/stars/dmis-lab/CompAct.svg?style=social) CompAct: Compressing Retrieved Documents Actively for Question Answering
- [QGC](https://github.com/XMUDeepLIT/QGC) (`XMUDeepLIT`) ![](https://img.shields.io/github/stars/XMUDeepLIT/QGC.svg?style=social) Retaining Key Information under High Compression Rates: Query-Guided Compressor for LLMs


## 📦 Isolate Context
### Multi-Agent Frameworks
- [MetaGPT](https://github.com/FoundationAgents/MetaGPT) (`FoundationAgents`) ![](https://img.shields.io/github/stars/FoundationAgents/MetaGPT.svg?style=social) The Multi-Agent Framework: First AI Software Company, Towards Natural Language Programming
- [agno](https://github.com/agno-agi/agno) (`agno-agi`) ![](https://img.shields.io/github/stars/agno-agi/agno.svg?style=social) Full-stack framework for building Multi-Agent Systems with memory, knowledge and reasoning.
- [camel](https://github.com/camel-ai/camel) (`camel-ai`) ![](https://img.shields.io/github/stars/camel-ai/camel.svg?style=social) CAMEL: The first and the best multi-agent framework. Finding the Scaling Law of Agents.
- [agent-squad](https://github.com/awslabs/agent-squad) (`awslabs`) ![](https://img.shields.io/github/stars/awslabs/agent-squad.svg?style=social) Flexible and powerful framework for managing multiple AI agents and handling complex conversations
- [PraisonAI](https://github.com/MervinPraison/PraisonAI) (`MervinPraison`) ![](https://img.shields.io/github/stars/MervinPraison/PraisonAI.svg?style=social) PraisonAI is a production-ready Multi AI Agents framework, designed to create AI Agents to automate and solve problems ranging from simple tasks to complex challenges.
- [langroid](https://github.com/langroid/langroid) (`langroid`) ![](https://img.shields.io/github/stars/langroid/langroid.svg?style=social) Harness LLMs with Multi-Agent Programming
- [LazyLLM](https://github.com/LazyAGI/LazyLLM) (`LazyAGI`) ![](https://img.shields.io/github/stars/LazyAGI/LazyLLM.svg?style=social) Easiest and laziest way for building multi-agent LLMs applications.


- **[Context Kit](https://github.com/JDDavenport/context-kit)** — Open-source toolkit for Personal Context Artifacts: 4 Markdown templates (wiki, mental-models, voice, protocols) + 5 Claude Code skills. Gives AI agents persistent personal context without vendor lock-in. One-command install, model-agnostic.
