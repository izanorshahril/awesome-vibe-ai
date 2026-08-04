# Awesome Vibe AI

> A curated map of AI tools, agents, models, apps, and platforms for builders who want to explore, prototype, automate, and ship with modern AI.

This README combines patterns from broad AI directories, LLM app cookbooks, generative AI lists, agent directories, and practical tool indexes. It favors open source, developer accessibility, and useful tool categories over enterprise procurement lists.

## Contents

- [Major AI Ecosystems and Multi-Product Providers](#major-ai-ecosystems-and-multi-product-providers)
  - [Western AI Ecosystems](#western-ai-ecosystems)
  - [Eastern / Asian AI Ecosystems](#eastern--asian-ai-ecosystems)
- [LLM APIs and Model Gateways](#llm-apis-and-model-gateways)
- [Open Models and Reasoning Models](#open-models-and-reasoning-models)
- [Local and Self-Hosted AI](#local-and-self-hosted-ai)
- [AI Chatbots and Multi-Model Interfaces](#ai-chatbots-and-multi-model-interfaces)
- [AI Coding and Developer Tools](#ai-coding-and-developer-tools)
- [Agent Frameworks and Orchestration](#agent-frameworks-and-orchestration)
- [LLM Apps, RAG, and Templates](#llm-apps-rag-and-templates)
- [MCP, Tool Use, and Protocols](#mcp-tool-use-and-protocols)
- [Browser, Desktop, and Workflow Agents](#browser-desktop-and-workflow-agents)
- [Voice and Realtime AI](#voice-and-realtime-ai)
- [Creative AI](#creative-ai)
- [Search, RAG, Memory, and Data](#search-rag-memory-and-data)
- [Business and Productivity AI](#business-and-productivity-ai)
- [Evaluation, Safety, and Governance](#evaluation-safety-and-governance)
- [Infrastructure, Deployment, and MLOps](#infrastructure-deployment-and-mlops)
- [Benchmarks and Leaderboards](#benchmarks-and-leaderboards)
- [Outdated and Solo Projects (Pending Removal)](#outdated-and-solo-projects-pending-removal)

## Major AI Ecosystems and Multi-Product Providers

### Western AI Ecosystems

| Provider | Product | Description |
| --- | --- | --- |
| **Anthropic** | [Claude](https://claude.ai/) | Flagship long-context web assistant for writing, coding, document analysis, and artifacts. |
| | [Claude API](https://www.anthropic.com/api) | Developer API for Claude models supporting vision, tool use, and computer use. |
| | [Claude Code](https://www.anthropic.com/claude-code) | Terminal-first autonomous coding agent for direct project edits. |
| **Google** | [Gemini](https://gemini.google.com/) | Flagship Google AI platform, assistant, Workspace integration, and multimodal ecosystem (includes Veo and NotebookLM integrations). |
| | [Antigravity](https://antigravity.google/) | Agentic AI coding platform and ecosystem available across CLI, Desktop, IDE extension, and SDK. |
| | [Gemini CLI](https://github.com/google-gemini/gemini-cli) | Open-source terminal agent powered by Gemini for local developer workflows. |
| | [Gemma Models](https://github.com/google-deepmind/gemma) | Lightweight open-weight model family designed for local device execution. |
| | [Google AI Studio](https://aistudio.google.com/) | Web prototyping environment for prompt engineering, Gemini API key management, developer API access, and Veo video generation. |
| | [Google Flow](https://flow.google/) | Google's generative creative and media platform incorporating Veo video generation models. |
| | [NotebookLM](https://notebooklm.google/) | Research assistant transforming uploaded documents into grounded notes and Audio Overviews (also accessible directly through Gemini). |
| | [Vertex AI](https://cloud.google.com/vertex-ai) | Google Cloud enterprise platform for Gemini model tuning, serving, and MLOps. |
| **Meta** | [AudioCraft](https://github.com/facebookresearch/audiocraft) | Open-source deep learning framework for audio and music generation. |
| | [Llama Open Models](https://github.com/meta-llama/llama) | Premier open-weight model family for local runtime, fine-tuning, and cloud deployment. |
| **Microsoft** | [AutoGen](https://github.com/microsoft/autogen) | Open-source multi-agent conversation framework. |
| | [Azure AI Foundry](https://azure.microsoft.com/en-us/products/ai-foundry) | Unified cloud platform for building, evaluating, and deploying AI models. |
| | [Phi Models](https://github.com/microsoft/Phi-3Cookbook) | Compact open model family optimized for local and edge execution. |
| | [Playwright MCP](https://github.com/microsoft/playwright-mcp) | Open-source Model Context Protocol server for Playwright browser automation. |
| | [Semantic Kernel](https://github.com/microsoft/semantic-kernel) | Enterprise agent SDK for C#, Python, and Java. |
| **Mistral AI** | [Mistral GitHub](https://github.com/mistralai) | Open-weight model repositories for dense and sparse mixture-of-experts models. |
| | [Mistral Platform](https://mistral.ai/) | Hosted API endpoints, Le Chat assistant, and commercial model platform. |
| **OpenAI** | [ChatGPT](https://chatgpt.com/) | Flagship AI assistant with web browsing, files, voice, image generation, and deep research. |
| | [Codex CLI](https://github.com/openai/codex) | Command-line developer agent for automated code generation and codebase editing. |
| | [OpenAI Agents SDK](https://github.com/openai/openai-agents-python) | Python agent framework with handoffs, guardrails, and tracing. |
| | [OpenAI Platform / API](https://platform.openai.com/) | Developer API access for text, reasoning (o1/o3), vision, realtime audio, and embeddings. |
| **xAI** | [Grok](https://x.ai/) | Realtime web-connected conversational model with vision and product features. |
| | [Grok Build](https://github.com/xai-org/grok-build) | Open-source CLI build and coding agent powered by Grok. |

### Eastern / Asian AI Ecosystems

| Provider | Product | Description |
| --- | --- | --- |
| **Alibaba / Qwen** | [Qwen Chat](https://chat.qwen.ai/) | Flagship web chat platform, multimodal assistant, and agent ecosystem. |
| | [Qwen Code](https://github.com/QwenLM/qwen-code) | Open-source Qwen-powered terminal coding assistant. |
| | [Qwen Open Weights](https://huggingface.co/Qwen) | Official open-weight releases (Qwen 2.5, Qwen-Coder, QWR) on Hugging Face and GitHub. |
| **DeepSeek** | [DeepSeek GitHub](https://github.com/deepseek-ai) | Open-weight repositories for reasoning (R1) and coding (V3) models. |
| | [DeepSeek Platform](https://www.deepseek.com/) | Hosted web assistant and commercial API endpoint for cost-effective inference. |
| **Moonshot AI / Kimi** | [Kimi Chat](https://kimi.moonshot.cn/) | Flagship web and mobile conversational assistant platform. |
| | [Kimi Code CLI](https://github.com/MoonshotAI/kimi-cli) | Open-source terminal agent for coding tasks. |
| | [Moonshot Platform](https://platform.moonshot.cn/) | Developer API endpoint platform. |
| **Xiaomi / MiMo** | [MiMo Platform](https://mimo.xiaomi.com/) | Xiaomi AI platform and model ecosystem. |
| | [MiMo-Code](https://github.com/XiaomiMiMo/MiMo-Code) | Open-source developer CLI agent by Xiaomi. |
| **Zhipu AI / GLM** | [GLM GitHub](https://github.com/zai-org/GLM-4) | Open-weight model releases for reasoning and agentic tasks. |
| | [Zhipu Platform](https://open.bigmodel.cn/) | Flagship model platform and Zhipu Qingyan assistant. |

## LLM APIs and Model Gateways

| Resource | Notes |
| --- | --- |
| [Groq](https://groq.com/) | Ultra-fast inference engine for open-weight models. |
| [OpenRouter](https://openrouter.ai/) | Unified API gateway accessing many models with routing, fallbacks, and price comparisons. |
| [Poolside](https://github.com/poolsideai) | Open model platform and developer ecosystem for Laguna coding models. |
| [Together AI](https://www.together.ai/) | Cloud platform for open model inference, fine-tuning, and serverless hosting. |

## Open Models and Reasoning Models

| Resource | Notes |
| --- | --- |
| [OLMo](https://github.com/allenai/OLMo) | Open model family with fully open training artifacts and code. |
| [StarCoder2](https://github.com/bigcode-project/starcoder2) | Open code-focused LLM family. |

## Local and Self-Hosted AI

| Resource | Notes |
| --- | --- |
| [AnythingLLM](https://github.com/Mintplex-Labs/anything-llm) | Open-source desktop/server private AI app with RAG, agents, and multi-model support. |
| [GPT4All](https://github.com/nomic-ai/gpt4all) | Open-source local chat app and model ecosystem for desktop users. |
| [Jan](https://github.com/janhq/jan) | Offline-first desktop AI assistant and local model manager. |
| [llama.cpp](https://github.com/ggml-org/llama.cpp) | Core C/C++ inference engine for CPU, GPU, and Apple Silicon. |
| [Llamafile](https://github.com/Mozilla-Ocho/llamafile) | Executable single-file LLM distribution format by Mozilla. |
| [LocalAI](https://github.com/mudler/LocalAI) | OpenAI-compatible local inference server for CPU/GPU hardware. |
| [Ollama](https://github.com/ollama/ollama) | Local model runner with a simple CLI, REST API, and model library. |
| [Open WebUI](https://github.com/open-webui/open-webui) | Feature-rich self-hosted AI Web UI supporting local and remote models. |
| [vLLM](https://github.com/vllm-project/vllm) | High-throughput LLM serving engine for production local/cloud inference. |
| [LM Studio](https://lmstudio.ai/) | Free desktop app for discovering, downloading, and running local LLMs. |

## AI Chatbots and Multi-Model Interfaces

| Resource | Notes |
| --- | --- |
| [LibreChat](https://github.com/danny-avila/LibreChat) | Open-source self-hosted multi-model chat interface with plugin support. |
| [LobeChat](https://github.com/lobehub/lobe-chat) | Open-source modern chat frontend with agent, plugin, and multimodal support. |
| [SillyTavern](https://github.com/SillyTavern/SillyTavern) | Local-first open-source chat frontend for custom prompts, agents, and personas. |
| [Perplexity](https://www.perplexity.ai/) | AI search engine and research assistant with cited web sources. |
| [Poe](https://poe.com/) | Multi-bot interface for testing and interacting with diverse AI models. |
| [TypingMind](https://www.typingmind.com/) | BYOK web interface with prompt libraries, plugins, and custom model endpoints. |

## AI Coding and Developer Tools

### IDE and Editor Assistants

| Resource | Notes |
| --- | --- |
| [Continue](https://github.com/continuedev/continue) | Open-source customizable AI coding assistant for VS Code and JetBrains. |
| [Zed](https://github.com/zed-industries/zed) | Open-source high-performance code editor with native AI assistant and agent mode. |
| [Amazon Q Developer](https://aws.amazon.com/q/developer/) | IDE assistant for coding, cloud, and security workflows. |
| [Cursor](https://cursor.com/) | AI-native IDE built around codebase-aware chat and multi-file edits. |
| [GitHub Copilot](https://github.com/features/copilot) | IDE code completion, chat, agent mode, and pull request assistance. |
| [JetBrains AI](https://www.jetbrains.com/ai/) | Deep AI completion and chat integrated across JetBrains IDEs. |
| [Windsurf](https://windsurf.com/) | Agentic IDE with Cascade-style codebase interaction. |

### Terminal and Autonomous Coding Agents

| Resource | Notes |
| --- | --- |
| [Aider](https://github.com/Aider-AI/aider) | Open-source Git-aware terminal pair programmer for multi-file code editing. |
| [Cline](https://github.com/cline/cline) | Open-source VS Code extension for file editing, terminal execution, and tool use. |
| [CodeBuff](https://github.com/CodebuffAI/codebuff) | Fast open-source agent for automated codebase editing. |
| [CommandCode](https://github.com/CommandCodeAI/command-code) | Open-source agent CLI for command execution and refactoring. |
| [Crush](https://github.com/charmbracelet/crush) | Terminal-native interactive AI coding agent built with Charm CLI tools. |
| [GitHub Copilot CLI](https://github.com/cli/cli) | Official GitHub command-line assistant for Copilot workflows. |
| [Goose](https://github.com/aaif-goose/goose) | Open-source AI Alliance developer agent for codebase automation. |
| [KiloCode](https://github.com/Kilo-Org/kilocode) | Open-source CLI agent for code execution and task automation. |
| [Kiro](https://github.com/kirodotdev/Kiro) | Open-source terminal developer assistant by Amazon. |
| [Kon](https://github.com/0xku/kon) | Open-source Python CLI coding agent for terminal pair programming. |
| [Mini-SWE](https://github.com/SWE-agent/mini-swe-agent) | Minimalist open-source software engineering agent for issue resolution. |
| [Nanobot](https://github.com/HKUDS/nanobot) | Open-source ultra-lightweight codebase agent. |
| [Oh My Pi (Omp)](https://github.com/can1357/oh-my-pi) | Open-source feature-expanded terminal coding agent frontend. |
| [OpenCode](https://github.com/anomalyco/opencode) | Open-source CLI coding agent for codebase navigation and edits. |
| [OpenHands](https://github.com/All-Hands-AI/OpenHands) | Open-source autonomous software engineering platform and agent. |
| [OpenInterpreter](https://github.com/openinterpreter/openinterpreter) | Open-source code interpreter running code locally in terminal. |
| [OpenSquilla](https://github.com/opensquilla/opensquilla) | Open-source coding agent featuring multi-provider smart cost routing. |
| [Pi](https://github.com/earendil-works/pi) | Open-source lightweight terminal coding agent architecture. |
| [PR-Agent](https://github.com/qodo-ai/pr-agent) | Open-source AI pull request reviewer, doc generator, and code improver. |
| [Reasonix](https://github.com/esengine/DeepSeek-Reasonix) | DeepSeek-native agent tailored for reasoning and coding. |
| [Roo Code](https://github.com/RooCodeInc/Roo-Code) | Open-source autonomous coding agent with specialized mode personas. |
| [SWE-agent](https://github.com/SWE-agent/SWE-agent) | Open-source agent system for resolving real GitHub software engineering issues. |
| [T3 Code](https://github.com/pingdotgg/t3code) | Open-source multi-platform coding agent harness. |
| [Tau](https://github.com/huggingface/tau) | Open-source Python-based coding agent reference implementation. |
| [TmuxAI](https://github.com/alvinunreal/tmuxai) | Open-source Tmux-integrated terminal AI pair assistant. |
| [Warp](https://github.com/warpdotdev/warp) | AI-integrated terminal built for developer productivity. |
| [Qodo](https://www.qodo.ai/) | Code quality, test generation, and review platform for AI workflows. |

### App and UI Builders

| Resource | Notes |
| --- | --- |
| [Dyad](https://github.com/dyad-sh/dyad) | Open-source local-first full-stack app generator. |
| [Bolt.new](https://bolt.new/) | Browser-based full-stack prompt-to-app builder and runtime environment. |
| [Create.xyz](https://www.create.xyz/) | Web app and visual component builder powered by AI prompts. |
| [Lovable](https://lovable.dev/) | Prompt-to-web-app platform with visual staging and deployment. |
| [Replit Agent](https://replit.com/agent) | Autonomous full-stack application creator integrated into Replit. |
| [v0](https://v0.app/) | Generative UI tool for React, Tailwind, and Web component design. |

## Agent Frameworks and Orchestration

| Resource | Notes |
| --- | --- |
| [AgentsMesh](https://github.com/AgentsMesh/AgentsMesh) | Open-source multi-platform agent coordination mesh network. |
| [CrewAI](https://github.com/crewaiinc/crewai) | Multi-agent role-playing orchestration framework. |
| [DSPy](https://github.com/stanfordnlp/dspy) | Open-source framework for optimizing LM prompts and pipeline weights. |
| [Factory](https://github.com/Factory-AI) | Open-source self-improving SDLC agent framework. |
| [Google ADK](https://github.com/google/adk-python) | Open-source agent development kit for Gemini workflows. |
| [Haystack](https://github.com/deepset-ai/haystack) | Production open-source pipeline framework for RAG and agent search. |
| [Hermes-Agent](https://github.com/NousResearch/hermes-agent) | All-round open-source agent framework by Nous Research. |
| [LangChain](https://github.com/langchain-ai/langchain) | Open-source framework for building LLM applications, tools, and retrievers. |
| [LangGraph](https://github.com/langchain-ai/langgraph) | Graph-based open-source framework for stateful, multi-agent workflows. |
| [Letta](https://github.com/letta-ai/letta) | Stateful agent framework with long-term memory management. |
| [LlamaIndex](https://github.com/run-llama/llama_index) | Data-centric open-source framework for RAG, memory, and indexing. |
| [Mastra](https://github.com/mastra-ai/mastra) | TypeScript agent framework for workflows, memory, and integrations. |
| [MetaGPT](https://github.com/FoundationAgents/MetaGPT) | Multi-agent framework modeling software role workflows. |
| [OpenClaw](https://github.com/openclaw/openclaw) | Open-source self-improving agent framework. |
| [PraisonAI](https://github.com/MervinPraison/PraisonAI) | Open-source multi-agent framework for automated task orchestration. |
| [Pydantic AI](https://github.com/pydantic/pydantic-ai) | Type-safe Python agent framework built on Pydantic. |
| [Smolagents](https://github.com/huggingface/smolagents) | Lightweight code-first Python agent library from Hugging Face. |
| [Traycer](https://github.com/traycerai/traycer) | Open-source agent orchestration and workflow engine. |

## LLM Apps, RAG, and Templates

| Resource | Notes |
| --- | --- |
| [awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps) | Curated collection of open-source agent, RAG, and voice application templates. |
| [Buzz](https://github.com/block/buzz) | Open-source conversational agent platform workspace by Block. |
| [Dify](https://github.com/langgenius/dify) | Open-source application platform for orchestrating LLMs, agents, and RAG. |
| [Flowise](https://github.com/FlowiseAI/Flowise) | Open-source visual UI node builder for AI agents and RAG flows. |
| [GPT Researcher](https://github.com/assafelovic/gpt-researcher) | Autonomous open-source agent for web research and synthesis. |
| [Langflow](https://github.com/langflow-ai/langflow) | Visual canvas framework for constructing LangChain/LangGraph flows. |
| [PrivateGPT](https://github.com/zylon-ai/private-gpt) | Local, privacy-first open-source document Q&A application. |
| [Quivr](https://github.com/QuivrHQ/quivr) | Open-source second-brain and knowledge base app powered by RAG. |
| [RAGFlow](https://github.com/infiniflow/ragflow) | Deep document understanding RAG engine with workflow capabilities. |
| [STORM](https://github.com/stanford-oval/storm) | Stanford research project for automated deep-dive report generation. |

## MCP, Tool Use, and Protocols

| Resource | Notes |
| --- | --- |
| [A2A Protocol](https://github.com/a2aproject/A2A) | Open protocol standard for agent-to-agent communication. |
| [Arcade AI](https://github.com/ArcadeAI/arcade-ai) | Open-source infrastructure for authorization and tool invocation in agents. |
| [Awesome MCP Servers](https://github.com/punkpeye/awesome-mcp-servers) | Community catalog of MCP servers and plugins. |
| [Composio](https://github.com/ComposioHQ/composio) | Tooling integration ecosystem for AI agents. |
| [MCP Registry](https://registry.modelcontextprotocol.io/) | Registry for discovering MCP plugins and integrations. |
| [MCP Servers](https://github.com/modelcontextprotocol/servers) | Reference open-source server implementations for Model Context Protocol. |
| [Model Context Protocol](https://github.com/modelcontextprotocol) | Open specification connecting AI models to external tools and data context. |
| [OpenAPI](https://www.openapis.org/) | Standard REST specification commonly bridge-translated to LLM tools. |
| [Toolhouse](https://toolhouse.ai/) | Managed serverless execution environment for agent tools. |

## Browser, Desktop, and Workflow Agents

### Browser and Computer Use

| Resource | Notes |
| --- | --- |
| [Agent S](https://github.com/simular-ai/Agent-S) | Open-source desktop computer GUI interaction framework. |
| [Browser Use](https://github.com/browser-use/browser-use) | Open-source Web automation framework driven by LLMs. |
| [Crawl4AI](https://github.com/unclecode/crawl4ai) | Open-source web crawler designed for LLM extraction pipelines. |
| [Firecrawl](https://github.com/firecrawl/firecrawl) | Open-source API turning web pages into clean LLM Markdown. |
| [Jina Reader](https://github.com/jina-ai/reader) | Open-source URL reader converting HTML to structured LLM context. |
| [Skyvern](https://github.com/Skyvern-AI/skyvern) | Open-source vision-driven browser automation agent. |
| [Stagehand](https://github.com/browserbase/stagehand) | Open-source Playwright-based browser agent framework. |
| [Browserbase](https://www.browserbase.com/) | Cloud browser environment for executing web agent operations. |

### Workflow Automation

| Resource | Notes |
| --- | --- |
| [Activepieces](https://github.com/activepieces/activepieces) | Open-source workflow automation platform with AI app integrations. |
| [n8n](https://github.com/n8n-io/n8n) | Fair-code/open-source node workflow platform with native AI nodes. |
| [Temporal](https://github.com/temporalio/temporal) | Open-source durable execution engine for long-running workflows and agents. |
| [Trigger.dev](https://github.com/triggerdotdev/trigger.dev) | Open-source background job system for serverless AI apps. |
| [Make](https://www.make.com/) | Visual automation builder supporting AI integrations. |
| [Pipedream](https://pipedream.com/) | Developer event-driven workflow automation platform. |
| [Zapier AI](https://zapier.com/ai) | Natural language workflow builder and multi-app automation platform. |

## Voice and Realtime AI

| Resource | Notes |
| --- | --- |
| [LiveKit Agents](https://github.com/livekit/agents) | Open-source framework for building realtime voice and video AI agents. |
| [Pipecat](https://github.com/pipecat-ai/pipecat) | Open-source framework for real-time multimodal and voice agents. |
| [Rasa](https://github.com/RasaHQ/rasa) | Open-source conversational assistant framework. |
| [Vocode](https://github.com/vocodedev/vocode-core) | Open-source Python library for building voice LLM apps. |
| [AssemblyAI](https://www.assemblyai.com/) | Speech recognition API with transcript analysis and intelligence. |
| [Deepgram](https://deepgram.com/) | Realtime speech-to-text and text-to-speech API. |
| [ElevenLabs](https://elevenlabs.io/) | Synthetic voice generation, voice clone, and conversational agent API. |
| [Vapi](https://vapi.ai/) | Low-latency orchestration API for voice assistants. |

## Creative AI

### Image Generation and Design

| Resource | Notes |
| --- | --- |
| [Civitai](https://civitai.com/) | Model share community for open-weight LoRAs and checkpoints. |
| [ComfyUI](https://github.com/comfyanonymous/ComfyUI) | Open-source node-based pipeline interface for diffusion models. |
| [FLUX](https://github.com/black-forest-labs/flux) | Open-weight and API image generation models by Black Forest Labs. |
| [Stable Diffusion](https://github.com/Stability-AI/stablediffusion) | Open-weight image generation model ecosystem and architecture. |
| [Ideogram](https://ideogram.ai/) | Image generation tool specialized in typography and graphic text. |
| [Leonardo AI](https://leonardo.ai/) | Generative image suite for game design and visual art. |
| [Midjourney](https://www.midjourney.com/) | Commercial image generation model known for high aesthetic quality. |
| [PhotoRoom](https://www.photoroom.com/) | E-commerce photo background generation and editing. |
| [Recraft](https://www.recraft.ai/) | Design-focused vector, icon, and brand asset generation platform. |

### Video, Audio, Music, and 3D

| Resource | Notes |
| --- | --- |
| [HunyuanVideo](https://github.com/Tencent-Hunyuan/HunyuanVideo) | Open-source high-resolution video generation model. |
| [Kling AI](https://kling.ai/) | Text and image-to-video generation tool. |
| [Luma Dream Machine](https://lumalabs.ai/dream-machine) | Generative video and 3D-adjacent visual generation engine. |
| [Meshy](https://www.meshy.ai/) | Text/image to textured 3D asset generation tool. |
| [Pika](https://pika.art/) | Video creation and prompt animation platform. |
| [Runway](https://runwayml.com/) | Creative video synthesis and generative camera control platform. |
| [Stable Audio](https://www.stableaudio.com/) | Music and sound effect generator by Stability AI. |
| [Suno](https://suno.com/) | AI music generator creating full songs with lyrics and vocals. |
| [Tripo AI](https://www.tripo3d.ai/) | Fast 3D model draft generator from prompts or images. |
| [Udio](https://www.udio.com/) | High-fidelity generative music studio. |

## Search, RAG, Memory, and Data

### Search and Retrieval

| Resource | Notes |
| --- | --- |
| [Brave Search API](https://brave.com/search/api/) | Privacy-focused web index search API for agents and RAG. |
| [Exa](https://exa.ai/) | Neural embeddings-based search engine for semantic retrieval. |
| [SerpAPI](https://serpapi.com/) | Search engine result parser API for Google, Bing, and web engines. |
| [Tavily](https://www.tavily.com/) | Search API tailored for agentic workflows and automated retrieval. |

### Vector Databases, Memory, and RAG Infrastructure

| Resource | Notes |
| --- | --- |
| [ActiveGraph](https://github.com/yoheinakajima/activegraph) | Open-source dynamic graph runtime for agent knowledge stores. |
| [Chroma](https://github.com/chroma-core/chroma) | Developer-friendly open-source vector database for Python and JS. |
| [CodeGraph](https://github.com/colbymchenry/codegraph) | Open-source GraphRAG engine specialized for codebase structural context. |
| [Cognee](https://github.com/topoteretes/cognee) | Open-source memory and graph pipeline for AI app context. |
| [Docling](https://github.com/docling-project/docling) | Open-source document processing tool for PDF, DOCX, and images. |
| [Graphify](https://github.com/Graphify-Labs/graphify) | Open-source GraphRAG knowledge graph construction framework. |
| [GraphRAG](https://github.com/microsoft/graphrag) | Open-source Graph-based RAG extraction and reasoning engine. |
| [LightRAG](https://github.com/HKUDS/LightRAG) | Open-source lightweight graph retrieval engine for low-cost GraphRAG. |
| [Mem0](https://github.com/mem0ai/mem0) | Open-source personalized memory layer for AI agents. |
| [Milvus](https://github.com/milvus-io/milvus) | Open-source cloud-native vector database for massive scale. |
| [pgvector](https://github.com/pgvector/pgvector) | Open-source vector similarity search extension for PostgreSQL. |
| [Potpie](https://github.com/potpie-ai/potpie) | Open-source codebase context and ontology framework for SDLC agents. |
| [Qdrant](https://github.com/qdrant/qdrant) | High-performance open-source vector search engine built in Rust. |
| [Unstructured](https://github.com/Unstructured-IO/unstructured) | Open-source document parsing library for RAG data preparation. |
| [Weaviate](https://github.com/weaviate/weaviate) | Open-source vector database with hybrid keyword and vector search. |
| [Zep](https://github.com/getzep/zep) | Open-source long-term memory engine and graph store for agents. |
| [Pinecone](https://www.pinecone.io/) | Managed cloud vector database for production RAG systems. |

### Data and Analysis Agents

| Resource | Notes |
| --- | --- |
| [PandasAI](https://github.com/sinaptik-ai/pandas-ai) | Open-source conversational data analysis library for Pandas dataframes. |
| [Vanna](https://github.com/vanna-ai/vanna) | Open-source RAG-based Text-to-SQL framework. |
| [Wren AI](https://github.com/Canner/WrenAI) | Open-source Text-to-SQL AI agent for business intelligence. |
| [Hex](https://hex.tech/) | Data workspace platform with integrated AI notebook assistance. |
| [Julius AI](https://julius.ai/) | Interactive data science assistant for files and spreadsheets. |

## Business and Productivity AI

| Resource | Notes |
| --- | --- |
| [Fireflies.ai](https://fireflies.ai/) | Conversation intelligence and meeting assistant. |
| [Grammarly](https://www.grammarly.com/) | Realtime writing, tone, and grammar editing platform. |
| [Intercom Fin](https://www.intercom.com/fin) | AI customer support bot resolving customer support queries. |
| [Mem](https://mem.ai/) | AI-powered personal knowledge base and workspace assistant. |
| [Notion AI](https://www.notion.so/product/ai) | Writing assistant, Q&A, and knowledge search integrated into Notion. |
| [Otter.ai](https://otter.ai/) | Automated meeting transcription and summary recorder. |
| [Taskade](https://www.taskade.com/) | Task management and mind mapping platform with AI agent features. |

## Evaluation, Safety, and Governance

### Evaluation and Observability

| Resource | Notes |
| --- | --- |
| [Arize Phoenix](https://github.com/Arize-ai/phoenix) | Open-source AI tracing and evaluation platform. |
| [Langfuse](https://github.com/langfuse/langfuse) | Open-source LLM observability, prompt management, and evals. |
| [Promptfoo](https://github.com/promptfoo/promptfoo) | Open-source CLI for testing prompts, security evals, and red-teaming. |
| [Ragas](https://github.com/explodinggradients/ragas) | Open-source evaluation framework for RAG architecture pipelines. |
| [Braintrust](https://www.braintrust.dev/) | Enterprise-ready evaluation platform for prompt and app testing. |
| [Helicone](https://www.helicone.ai/) | LLM gateway for logging, caching, and cost monitoring. |
| [LangSmith](https://www.langchain.com/langsmith) | Managed platform for tracing, testing, and monitoring LLM apps. |

### Safety and Governance

| Resource | Notes |
| --- | --- |
| [Guardrails AI](https://github.com/guardrails-ai/guardrails) | Open-source output validation and structure enforcement library. |
| [LLM Guard](https://github.com/protectai/llm-guard) | Open-source security toolkit for evaluating LLM inputs and outputs. |
| [NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails) | Open-source toolkit for controlling LLM conversational boundaries. |
| [EU AI Act](https://artificialintelligenceact.eu/) | Regulatory framework compliance guide for AI models in Europe. |
| [Lakera Guard](https://www.lakera.ai/) | Security guard API for prompt injection and data leakage protection. |
| [NIST AI Risk Management Framework](https://airc.nist.gov/AI_RMF_Knowledge_Base) | Standards framework for managing AI safety and operational risk. |
| [OWASP Top 10 for LLM Applications](https://owasp.org/www-project-top-10-for-large-language-model-applications/) | Security risk framework for LLM and agent applications. |

## Infrastructure, Deployment, and MLOps

| Resource | Notes |
| --- | --- |
| [BentoML](https://github.com/bentoml/BentoML) | Open-source framework for building and serving AI applications. |
| [KServe](https://github.com/kserve/kserve) | Open-source Kubernetes-native model serving platform. |
| [LiteLLM](https://github.com/BerriAI/litellm) | Open-source API proxy for routing 100+ LLMs with unified input/output schemas. |
| [MLflow](https://github.com/mlflow/mlflow) | Open-source platform for ML experiment tracking and model registry. |
| [AWS Bedrock](https://aws.amazon.com/bedrock/) | Cloud foundation model hosting, agent, and RAG service. |
| [Databricks Mosaic AI](https://www.databricks.com/product/machine-learning) | Enterprise data platform for model training, serving, and governance. |
| [Modal](https://modal.com/) | Serverless Python infrastructure for running GPU/CPU jobs. |
| [Portkey](https://portkey.ai/) | AI gateway for routing, fallback strategy, and latency control. |
| [Replicate](https://replicate.com/) | Cloud API platform for running open-source models on demand. |
| [RunPod](https://www.runpod.io/) | On-demand cloud GPU instances and serverless inference. |
| [Weights & Biases](https://wandb.ai/) | Platform for tracking experiments, dataset versioning, and evaluation. |

## Benchmarks and Leaderboards

| Resource | Notes |
| --- | --- |
| [AgentBench](https://github.com/THUDM/AgentBench) | Open benchmark for evaluating LLMs as multi-environment agents. |
| [Artificial Analysis](https://artificialanalysis.ai/) | Independent benchmark comparing model speed, latency, quality, and cost. |
| [LiveBench](https://livebench.ai/) | Uncontaminated continuously-updated benchmark suite for LLMs. |
| [LMArena](https://lmarena.ai/) | Crowdsourced blind Elo ranking arena for LLMs. |
| [LLM Stats](https://llm-stats.com/) | Aggregated stats for context length, pricing, and benchmark scores. |
| [Open LLM Leaderboard](https://huggingface.co/spaces/open-llm-leaderboard/open_llm_leaderboard) | Open-source model tracking and evaluation benchmark by Hugging Face. |
| [OpenRouter Rankings](https://openrouter.ai/rankings) | Real-world usage and token volume rankings across model providers. |
| [SWE-bench](https://github.com/swe-bench/SWE-bench) | Benchmark dataset evaluating agents on real GitHub issues. |
| [WebArena](https://github.com/web-arena-x/webarena) | End-to-end web environment benchmark for web-based agents. |

## Outdated and Solo Projects (Pending Removal)

> [!NOTE]
> This category tracks projects flagged for potential future removal based on low activity (> 1 month without updates), explicit discontinuation, or single-maintainer status (solo developer with only automated bot/AI contributors).

| Resource | Notes | Status / Reason |
| --- | --- | --- |
| [Rebuff](https://github.com/protectai/rebuff) | Prompt injection detection and defense framework. | **Archived**: Repository archived on GitHub in May 2025. |
| [Sora](https://openai.com/sora) | Generative text-to-video creation tool and model. | **Discontinued**: Web experience and API shut down by OpenAI in early 2026. |
| [TaskWeaver](https://github.com/microsoft/TaskWeaver) | Microsoft code-first agent framework for data analytics. | **Archived**: Repository archived on GitHub by maintainers in March 2026. |