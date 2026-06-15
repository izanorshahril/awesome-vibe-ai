# Awesome Vibe AI

> A curated map of AI tools, agents, models, apps, and learning resources for builders who want to explore, prototype, automate, and ship with modern AI.

This README combines the patterns from broad AI directories, LLM app cookbooks, generative AI lists, agent directories, and practical tool indexes. It favors useful categories, recognizable tools, and quick orientation over exhaustive duplication.

## How to Choose

| If you want to... | Start here |
| --- | --- |
| Call frontier models from an app | [LLM APIs and Model Providers](#llm-apis-and-model-providers) |
| Run models locally | [Local and Self-Hosted AI](#local-and-self-hosted-ai) |
| Build agents with tools and memory | [Agent Frameworks and Orchestration](#agent-frameworks-and-orchestration) |
| Create agent-powered apps | [LLM Apps, RAG, and Templates](#llm-apps-rag-and-templates) |
| Use AI inside an IDE or terminal | [AI Coding and Developer Tools](#ai-coding-and-developer-tools) |
| Build browser, desktop, or workflow agents | [Browser, Desktop, and Workflow Agents](#browser-desktop-and-workflow-agents) |
| Generate image, video, audio, or 3D assets | [Creative AI](#creative-ai) |
| Add search, documents, or knowledge retrieval | [Search, RAG, Memory, and Data](#search-rag-memory-and-data) |
| Evaluate, monitor, and govern AI systems | [Evaluation, Safety, and Governance](#evaluation-safety-and-governance) |
| Learn the foundations | [Learning Resources](#learning-resources) |

## Contents

- [LLM APIs and Model Providers](#llm-apis-and-model-providers)
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
- [Learning Resources](#learning-resources)
- [Source Inspiration](#source-inspiration)

## LLM APIs and Model Providers

| Resource | Notes |
| --- | --- |
| [OpenAI API](https://platform.openai.com/) | Frontier text, reasoning, multimodal, audio, image, and agent APIs. |
| [Anthropic Claude API](https://www.anthropic.com/api) | Claude models with long context, tool use, computer use, and strong writing/coding workflows. |
| [Google Gemini API](https://ai.google.dev/) | Gemini models, AI Studio, multimodal inputs, long context, and Google ecosystem integration. |
| [Mistral AI](https://mistral.ai/) | European model provider with open-weight and commercial models. |
| [DeepSeek](https://www.deepseek.com/) | Efficient reasoning and coding models with open model releases. |
| [Cohere](https://cohere.com/) | Enterprise-focused Command and Embed models, especially strong for RAG. |
| [xAI Grok](https://x.ai/) | Grok models with real-time product integrations and multimodal capabilities. |
| [OpenRouter](https://openrouter.ai/) | Unified access to many models with model routing and pricing comparison. |
| [Together AI](https://www.together.ai/) | Hosted inference and fine-tuning for open models. |
| [Groq](https://groq.com/) | Ultra-fast inference for supported open models. |

## Open Models and Reasoning Models

| Resource | Notes |
| --- | --- |
| [Llama](https://www.llama.com/) | Meta open-weight model family for local, cloud, and enterprise use. |
| [Qwen](https://github.com/QwenLM) | Alibaba model family with multilingual, coding, and agentic strengths. |
| [DeepSeek V3 / R1](https://github.com/deepseek-ai) | Open models for reasoning, coding, and cost-efficient inference. |
| [Mistral / Mixtral](https://mistral.ai/models/) | Efficient open-weight and commercial models with strong function calling. |
| [Gemma](https://github.com/google-deepmind/gemma) | Google's efficient open model family for local and edge use. |
| [Phi](https://huggingface.co/microsoft) | Compact Microsoft models for local, edge, and focused tasks. |
| [Command R+](https://cohere.com/command) | RAG-optimized model family from Cohere. |
| [StarCoder2](https://github.com/bigcode-project/starcoder2) | Open code-focused LLM family. |
| [OLMo](https://allenai.org/olmo) | Open model family with open training artifacts for research. |
| [GLM](https://github.com/zai-org/GLM-4) | Open model family from Z.ai/Zhipu for reasoning and agentic tasks. |

## Local and Self-Hosted AI

| Resource | Notes |
| --- | --- |
| [Ollama](https://ollama.com/) | Simple local model runner with a friendly CLI and model library. |
| [llama.cpp](https://github.com/ggml-org/llama.cpp) | Core C/C++ inference engine for CPU, GPU, and Apple Silicon. |
| [LM Studio](https://lmstudio.ai/) | Desktop app for discovering and running local LLMs. |
| [Jan](https://jan.ai/) | Offline-first desktop AI assistant and local model manager. |
| [Open WebUI](https://github.com/open-webui/open-webui) | Self-hosted AI interface for local and remote models. |
| [LocalAI](https://github.com/mudler/LocalAI) | OpenAI-compatible local inference server. |
| [GPT4All](https://github.com/nomic-ai/gpt4all) | Local chat app and model ecosystem for consumer hardware. |
| [vLLM](https://github.com/vllm-project/vllm) | High-throughput LLM serving for production inference. |
| [Llamafile](https://github.com/Mozilla-Ocho/llamafile) | Package models as single runnable files. |
| [AnythingLLM](https://github.com/Mintplex-Labs/anything-llm) | All-in-one private AI app with RAG, agents, and multi-model support. |

## AI Chatbots and Multi-Model Interfaces

| Resource | Notes |
| --- | --- |
| [ChatGPT](https://chatgpt.com/) | General AI assistant with GPTs, tools, files, browsing, image generation, and research features. |
| [Claude](https://claude.ai/) | Long-context assistant for writing, coding, document analysis, and tool workflows. |
| [Gemini](https://gemini.google.com/) | Google assistant with multimodal input, workspace integration, and deep research features. |
| [Microsoft Copilot](https://copilot.microsoft.com/) | Everyday and enterprise assistant integrated with Microsoft products. |
| [Perplexity](https://www.perplexity.ai/) | AI search and research assistant with cited answers. |
| [Poe](https://poe.com/) | Multi-bot interface for accessing many models and custom assistants. |
| [LibreChat](https://github.com/danny-avila/LibreChat) | Self-hosted multi-model chat interface. |
| [LobeChat](https://github.com/lobehub/lobe-chat) | Open-source chat UI with plugin and multimodal support. |
| [SillyTavern](https://github.com/SillyTavern/SillyTavern) | Local-first advanced chat frontend, often used for roleplay and custom characters. |
| [TypingMind](https://www.typingmind.com/) | BYOK chat interface with prompt libraries, plugins, and multi-model support. |

## AI Coding and Developer Tools

### IDE and Editor Assistants

| Resource | Notes |
| --- | --- |
| [GitHub Copilot](https://github.com/features/copilot) | IDE-native code completion, chat, agent mode, reviews, and issue-to-PR workflows. |
| [Cursor](https://cursor.com/) | AI-native IDE built around codebase-aware chat and multi-file edits. |
| [Windsurf](https://windsurf.com/) | Agentic IDE with Cascade-style project workflows. |
| [JetBrains AI](https://www.jetbrains.com/ai/) | Deep AI integration across JetBrains IDEs. |
| [Amazon Q Developer](https://aws.amazon.com/q/developer/) | AWS-aware coding assistant, cloud helper, and security companion. |
| [Sourcegraph Cody](https://sourcegraph.com/cody) | AI assistant for large codebases and enterprise source graphs. |
| [Continue](https://www.continue.dev/) | Open-source customizable AI assistant for IDEs. |
| [Tabnine](https://www.tabnine.com/) | Privacy-focused code completion with enterprise deployment options. |

### Terminal and Autonomous Coding Agents

| Resource | Notes |
| --- | --- |
| [Aider](https://aider.chat/) | Git-aware terminal pair programmer for multi-file changes. |
| [Claude Code](https://www.anthropic.com/claude-code) | Terminal-first agentic coding assistant from Anthropic. |
| [OpenAI Codex CLI](https://github.com/openai/codex) | Command-line coding agent for codebase tasks. |
| [Gemini CLI](https://github.com/google-gemini/gemini-cli) | Open-source Gemini-powered terminal agent. |
| [Cline](https://github.com/cline/cline) | VS Code agent that can edit files, run commands, and use tools. |
| [Roo Code](https://github.com/RooCodeInc/Roo-Code) | Cline-family autonomous coding extension with structured modes. |
| [OpenHands](https://github.com/OpenHands/OpenHands) | Open-source autonomous software engineering platform. |
| [SWE-agent](https://github.com/SWE-agent/SWE-agent) | Agent for resolving software engineering issues. |
| [PR-Agent](https://github.com/qodo-ai/pr-agent) | Open-source AI pull request reviewer and improver. |
| [Qodo](https://www.qodo.ai/) | Code review, testing, and quality platform for AI-assisted development. |

### App and UI Builders

| Resource | Notes |
| --- | --- |
| [Bolt.new](https://bolt.new/) | Prompt-to-full-stack web app builder in the browser. |
| [Lovable](https://lovable.dev/) | Conversational app builder with preview and deploy workflow. |
| [v0](https://v0.app/) | Prompt-to-React/Tailwind UI generation from Vercel. |
| [Replit Agent](https://replit.com/agent) | Full-stack app generation and deployment inside Replit. |
| [Dyad](https://github.com/dyad-sh/dyad) | Local-first open-source app builder. |
| [Create.xyz](https://www.create.xyz/) | Prompt-based web app and component generation. |

## Agent Frameworks and Orchestration

| Resource | Notes |
| --- | --- |
| [LangChain](https://www.langchain.com/) | Broad LLM application framework with tools, retrievers, and integrations. |
| [LangGraph](https://github.com/langchain-ai/langgraph) | Graph-based framework for durable, stateful, human-in-the-loop agents. |
| [LlamaIndex](https://www.llamaindex.ai/) | Data-centric framework for RAG, retrieval, agents, and knowledge workflows. |
| [CrewAI](https://github.com/crewAIInc/crewAI) | Role-based multi-agent orchestration. |
| [Microsoft AutoGen](https://github.com/microsoft/autogen) | Multi-agent conversation and orchestration framework. |
| [Semantic Kernel](https://github.com/microsoft/semantic-kernel) | Microsoft agent SDK for C#, Python, and Java. |
| [OpenAI Agents SDK](https://github.com/openai/openai-agents-python) | Agent framework with tool use, handoffs, tracing, and guardrails. |
| [Google ADK](https://github.com/google/adk-python) | Google's agent development kit for Gemini and Vertex AI workflows. |
| [Pydantic AI](https://github.com/pydantic/pydantic-ai) | Type-safe Python agent framework from the Pydantic team. |
| [DSPy](https://github.com/stanfordnlp/dspy) | Programmatic optimization of prompts, chains, and language-model pipelines. |
| [Haystack](https://haystack.deepset.ai/) | Pipeline-oriented framework for search, RAG, and production LLM apps. |
| [Smolagents](https://github.com/huggingface/smolagents) | Lightweight code-first agent framework from Hugging Face. |
| [Mastra](https://github.com/mastra-ai/mastra) | TypeScript agent framework with workflows, memory, and integrations. |
| [Letta](https://github.com/letta-ai/letta) | Stateful agents with memory, tools, and REST API support. |
| [MetaGPT](https://github.com/FoundationAgents/MetaGPT) | Multi-agent software-company simulation and product workflow. |

## LLM Apps, RAG, and Templates

| Resource | Notes |
| --- | --- |
| [awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps) | Runnable AI agent, RAG, voice, MCP, and fine-tuning templates. |
| [Dify](https://github.com/langgenius/dify) | Open-source LLM app platform with workflows, agents, RAG, and model management. |
| [Flowise](https://github.com/FlowiseAI/Flowise) | Drag-and-drop LLM flow, agent, and RAG builder. |
| [Langflow](https://github.com/langflow-ai/langflow) | Visual builder for LangChain/LangGraph-style AI workflows. |
| [RAGFlow](https://github.com/infiniflow/ragflow) | Open-source RAG engine with document understanding and agent capabilities. |
| [PrivateGPT](https://github.com/zylon-ai/private-gpt) | Ask questions over local documents with privacy in mind. |
| [Quivr](https://github.com/QuivrHQ/quivr) | Personal knowledge base and second-brain RAG app. |
| [STORM](https://github.com/stanford-oval/storm) | Research and report generation system from Stanford. |
| [GPT Researcher](https://github.com/assafelovic/gpt-researcher) | Autonomous research assistant that produces cited reports. |
| [NotebookLM](https://notebooklm.google/) | Document-based research and note-taking assistant from Google. |

## MCP, Tool Use, and Protocols

| Resource | Notes |
| --- | --- |
| [Model Context Protocol](https://modelcontextprotocol.io/) | Open standard for connecting AI models to tools and data sources. |
| [MCP Servers](https://github.com/modelcontextprotocol/servers) | Reference MCP server implementations. |
| [MCP Registry](https://registry.modelcontextprotocol.io/) | Registry for discovering MCP servers and integrations. |
| [Awesome MCP Servers](https://github.com/punkpeye/awesome-mcp-servers) | Community index of MCP servers. |
| [Playwright MCP](https://github.com/microsoft/playwright-mcp) | Browser automation MCP server built on Playwright. |
| [Composio](https://github.com/ComposioHQ/composio) | Tool integration platform for agents and LLM apps. |
| [Arcade AI](https://github.com/ArcadeAI/arcade-ai) | Authenticated tool access for AI agents. |
| [Toolhouse](https://toolhouse.ai/) | Cloud-hosted tool infrastructure for agents. |
| [OpenAPI](https://www.openapis.org/) | Standard API specification frequently used as a bridge into agent tools. |
| [A2A Protocol](https://github.com/a2aproject/A2A) | Agent-to-agent communication protocol. |

## Browser, Desktop, and Workflow Agents

### Browser and Computer Use

| Resource | Notes |
| --- | --- |
| [Browser Use](https://github.com/browser-use/browser-use) | Open-source framework for LLM-controlled browser automation. |
| [Stagehand](https://github.com/browserbase/stagehand) | Browser automation framework with natural-language actions. |
| [Skyvern](https://github.com/Skyvern-AI/skyvern) | Vision-first browser automation for complex web workflows. |
| [Agent S](https://github.com/simular-ai/Agent-S) | GUI automation framework for desktop and browser agents. |
| [Browserbase](https://www.browserbase.com/) | Cloud browser infrastructure for AI agents. |
| [Firecrawl](https://github.com/firecrawl/firecrawl) | Converts websites into LLM-ready markdown and structured data. |
| [Crawl4AI](https://github.com/unclecode/crawl4ai) | AI-ready web crawler and scraper. |
| [Jina Reader](https://github.com/jina-ai/reader) | URL-to-clean-text reader API for LLM ingestion. |

### Workflow Automation

| Resource | Notes |
| --- | --- |
| [n8n](https://github.com/n8n-io/n8n) | Open-source workflow automation with AI nodes. |
| [Zapier AI](https://zapier.com/ai) | Natural-language automation across thousands of apps. |
| [Make](https://www.make.com/) | Visual automation platform with AI workflow capabilities. |
| [Activepieces](https://github.com/activepieces/activepieces) | Open-source Zapier-style automation platform. |
| [Temporal](https://temporal.io/) | Durable execution platform for long-running agent workflows. |
| [Trigger.dev](https://github.com/triggerdotdev/trigger.dev) | Background jobs and scheduled tasks for AI apps. |
| [Pipedream](https://pipedream.com/) | Developer-friendly workflow automation for APIs and events. |

## Voice and Realtime AI

| Resource | Notes |
| --- | --- |
| [OpenAI Realtime API](https://platform.openai.com/docs/guides/realtime) | Realtime speech-to-speech and multimodal interactions. |
| [Gemini Live API](https://ai.google.dev/gemini-api/docs/live) | Realtime voice and video interaction with Gemini. |
| [LiveKit Agents](https://github.com/livekit/agents) | Framework for realtime voice, video, and multimodal agents. |
| [ElevenLabs](https://elevenlabs.io/) | Voice generation, voice agents, dubbing, and speech tools. |
| [Vapi](https://vapi.ai/) | Developer platform for low-latency voice agents. |
| [Deepgram](https://deepgram.com/) | Speech-to-text and text-to-speech APIs for voice applications. |
| [AssemblyAI](https://www.assemblyai.com/) | Speech recognition with diarization, summaries, and audio intelligence. |
| [Pipecat](https://github.com/pipecat-ai/pipecat) | Open-source framework for voice and multimodal conversational agents. |
| [Rasa](https://github.com/RasaHQ/rasa) | Open-source conversational AI framework. |
| [Vocode](https://github.com/vocodedev/vocode-core) | Open-source voice-based LLM application framework. |

## Creative AI

### Image Generation and Design

| Resource | Notes |
| --- | --- |
| [Midjourney](https://www.midjourney.com/) | High-quality artistic image generation. |
| [DALL-E](https://openai.com/dall-e-3) | Image generation with strong prompt comprehension and ChatGPT integration. |
| [Stable Diffusion](https://stability.ai/) | Open image generation ecosystem with local workflows and model customization. |
| [FLUX](https://bfl.ai/) | Open-weight and API image models from Black Forest Labs. |
| [Ideogram](https://ideogram.ai/) | Image generation with strong text rendering. |
| [Recraft](https://www.recraft.ai/) | Design-focused image, vector, and brand asset generation. |
| [Leonardo AI](https://leonardo.ai/) | Multi-model image platform for game, product, and creative assets. |
| [ComfyUI](https://github.com/comfyanonymous/ComfyUI) | Node-based Stable Diffusion workflow interface. |
| [Civitai](https://civitai.com/) | Community model, LoRA, and workflow hub for image generation. |
| [PhotoRoom](https://www.photoroom.com/) | AI product photo editing, background removal, and commerce visuals. |

### Video, Audio, Music, and 3D

| Resource | Notes |
| --- | --- |
| [Runway](https://runwayml.com/) | AI video generation and editing suite. |
| [Sora](https://openai.com/sora) | OpenAI video generation model and product. |
| [Google Veo](https://deepmind.google/models/veo/) | Google video generation model family. |
| [Kling AI](https://kling.ai/) | Text-to-video and image-to-video generation. |
| [Pika](https://pika.art/) | Beginner-friendly AI video generation and editing. |
| [Luma Dream Machine](https://lumalabs.ai/dream-machine) | High-quality text/image-to-video and 3D-adjacent creative tools. |
| [HunyuanVideo](https://github.com/Tencent-Hunyuan/HunyuanVideo) | Open-source video generation model from Tencent. |
| [Suno](https://suno.com/) | Text-to-song generation with vocals and instruments. |
| [Udio](https://www.udio.com/) | Music generation with detailed control. |
| [Meta AudioCraft](https://github.com/facebookresearch/audiocraft) | Open-source audio and music generation toolkit. |
| [Stable Audio](https://www.stableaudio.com/) | AI music and audio generation. |
| [Meshy](https://www.meshy.ai/) | Text/image-to-3D asset generation. |
| [Tripo AI](https://www.tripo3d.ai/) | Fast 3D model generation from text or images. |

## Search, RAG, Memory, and Data

### Search and Retrieval

| Resource | Notes |
| --- | --- |
| [Perplexity Sonar](https://docs.perplexity.ai/) | Search API for cited AI answers. |
| [Tavily](https://www.tavily.com/) | Search API built for agents and RAG. |
| [Exa](https://exa.ai/) | Neural search API for meaning-based web retrieval. |
| [Brave Search API](https://brave.com/search/api/) | Independent web search API with privacy focus. |
| [SerpAPI](https://serpapi.com/) | Search engine results API for AI and automation workflows. |

### Vector Databases, Memory, and RAG Infrastructure

| Resource | Notes |
| --- | --- |
| [Pinecone](https://www.pinecone.io/) | Managed vector database for production RAG. |
| [Weaviate](https://weaviate.io/) | Open-source vector database with hybrid search. |
| [Qdrant](https://qdrant.tech/) | High-performance vector database written in Rust. |
| [Chroma](https://www.trychroma.com/) | Developer-friendly vector database for prototyping and apps. |
| [Milvus](https://milvus.io/) | Cloud-native vector database for large-scale retrieval. |
| [pgvector](https://github.com/pgvector/pgvector) | Vector search extension for PostgreSQL. |
| [Mem0](https://github.com/mem0ai/mem0) | Memory layer for AI agents and applications. |
| [Zep](https://github.com/getzep/zep) | Long-term memory and temporal knowledge graph for agents. |
| [Cognee](https://github.com/topoteretes/cognee) | Memory and knowledge graph engine for agents. |
| [Unstructured](https://github.com/Unstructured-IO/unstructured) | Document ingestion and preprocessing for RAG. |
| [LlamaParse](https://www.llamaindex.ai/llamaparse) | Document parsing for complex PDFs and structured extraction. |
| [Docling](https://github.com/docling-project/docling) | Document conversion toolkit for PDFs, office docs, and images. |

### Data and Analysis Agents

| Resource | Notes |
| --- | --- |
| [Julius AI](https://julius.ai/) | Natural-language analysis for spreadsheets and data files. |
| [PandasAI](https://github.com/sinaptik-ai/pandas-ai) | Chat with data using Pandas and SQL-style operations. |
| [Hex](https://hex.tech/) | Collaborative data notebooks and AI-assisted analytics. |
| [TaskWeaver](https://github.com/microsoft/TaskWeaver) | Microsoft code-first agent framework for data analytics tasks. |
| [Vanna](https://github.com/vanna-ai/vanna) | Text-to-SQL and database assistant framework. |
| [Wren AI](https://github.com/Canner/WrenAI) | Open-source text-to-SQL and generative BI agent. |

## Business and Productivity AI

| Resource | Notes |
| --- | --- |
| [Notion AI](https://www.notion.so/product/ai) | AI writing, search, and knowledge management inside Notion. |
| [Taskade](https://www.taskade.com/) | AI workspace for tasks, notes, mind maps, and agents. |
| [Mem](https://mem.ai/) | AI-powered notes and personal knowledge management. |
| [Otter.ai](https://otter.ai/) | Meeting transcription and summaries. |
| [Fireflies.ai](https://fireflies.ai/) | Meeting transcription, search, and conversation intelligence. |
| [Jasper](https://www.jasper.ai/) | Marketing content platform with brand voice workflows. |
| [Writer](https://writer.com/) | Enterprise writing and content generation platform. |
| [Grammarly](https://www.grammarly.com/) | Writing, grammar, tone, and style assistant. |
| [Intercom Fin](https://www.intercom.com/fin) | AI customer support agent for help center-driven answers. |
| [Zendesk AI](https://www.zendesk.com/service/ai/) | Support automation, routing, summarization, and agent assist. |
| [Salesforce Einstein](https://www.salesforce.com/artificial-intelligence/) | CRM AI and autonomous agent features across Salesforce. |
| [HubSpot Breeze](https://www.hubspot.com/artificial-intelligence) | AI assistants and agents for CRM, marketing, and sales. |

## Evaluation, Safety, and Governance

### Evaluation and Observability

| Resource | Notes |
| --- | --- |
| [LangSmith](https://www.langchain.com/langsmith) | Tracing, testing, and evaluation for LangChain and agent apps. |
| [Langfuse](https://langfuse.com/) | Open-source LLM observability, prompt management, and evaluations. |
| [Arize Phoenix](https://github.com/Arize-ai/phoenix) | Open-source AI observability and tracing. |
| [Braintrust](https://www.braintrust.dev/) | Eval-driven development for LLM applications. |
| [Promptfoo](https://www.promptfoo.dev/) | Prompt testing, evals, red-teaming, and CI workflows. |
| [Ragas](https://github.com/explodinggradients/ragas) | Evaluation framework for RAG pipelines. |
| [Helicone](https://www.helicone.ai/) | Gateway and observability for LLM usage, cost, and latency. |

### Safety and Governance

| Resource | Notes |
| --- | --- |
| [Guardrails AI](https://github.com/guardrails-ai/guardrails) | Validation and structural guarantees for LLM outputs. |
| [NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails) | Programmable conversational guardrails from NVIDIA. |
| [LLM Guard](https://github.com/protectai/llm-guard) | Input/output scanners for prompt injection, PII, and toxicity. |
| [Lakera Guard](https://www.lakera.ai/) | Prompt injection and data leakage protection. |
| [Rebuff](https://github.com/protectai/rebuff) | Prompt injection detection and self-hardening. |
| [OWASP Top 10 for LLM Applications](https://owasp.org/www-project-top-10-for-large-language-model-applications/) | Security risks and guidance for LLM and agentic apps. |
| [Credo AI](https://www.credo.ai/) | AI governance and compliance platform. |
| [IBM watsonx.governance](https://www.ibm.com/products/watsonx-governance) | Enterprise AI risk and governance tooling. |
| [NIST AI Risk Management Framework](https://airc.nist.gov/AI_RMF_Knowledge_Base) | US AI risk management framework. |
| [EU AI Act](https://artificialintelligenceact.eu/) | EU regulatory framework for AI systems. |

## Infrastructure, Deployment, and MLOps

| Resource | Notes |
| --- | --- |
| [AWS Bedrock](https://aws.amazon.com/bedrock/) | Managed foundation models, agents, knowledge bases, and enterprise deployment. |
| [Azure AI Foundry](https://azure.microsoft.com/en-us/products/ai-foundry) | Azure platform for building, evaluating, and deploying AI apps. |
| [Google Vertex AI](https://cloud.google.com/vertex-ai) | Google Cloud AI platform with Gemini, Model Garden, tuning, and MLOps. |
| [Databricks Mosaic AI](https://www.databricks.com/product/machine-learning) | Data and AI platform with model serving, MLflow, and governance. |
| [MLflow](https://mlflow.org/) | Experiment tracking, model registry, evaluation, and GenAI operations. |
| [Weights & Biases](https://wandb.ai/) | Experiment tracking, model monitoring, and AI app evaluation. |
| [Modal](https://modal.com/) | Serverless compute for AI workloads. |
| [RunPod](https://www.runpod.io/) | Cloud GPU and serverless GPU platform. |
| [Replicate](https://replicate.com/) | Run and deploy open models through APIs. |
| [BentoML](https://www.bentoml.com/) | Model serving and deployment framework. |
| [KServe](https://kserve.github.io/website/) | Kubernetes-native model serving. |
| [LiteLLM](https://github.com/BerriAI/litellm) | LLM gateway for routing, fallbacks, spend tracking, and provider abstraction. |
| [Portkey](https://portkey.ai/) | AI gateway, observability, caching, and governance layer. |

## Benchmarks and Leaderboards

| Resource | Notes |
| --- | --- |
| [LMArena](https://lmarena.ai/) | Crowdsourced chatbot arena and model leaderboard. |
| [Artificial Analysis](https://artificialanalysis.ai/) | Independent model quality, speed, price, and latency comparisons. |
| [Open LLM Leaderboard](https://huggingface.co/spaces/open-llm-leaderboard/open_llm_leaderboard) | Open model benchmark tracking. |
| [LLM Stats](https://llm-stats.com/) | Model stats, pricing, context windows, and leaderboard aggregation. |
| [OpenRouter Rankings](https://openrouter.ai/rankings) | Model usage and popularity rankings across OpenRouter. |
| [SWE-bench](https://www.swebench.com/) | Software engineering benchmark from real GitHub issues. |
| [LiveBench](https://livebench.ai/) | Continuously updated benchmark designed to reduce contamination. |
| [AgentBench](https://github.com/THUDM/AgentBench) | Benchmark for evaluating LLMs as agents. |
| [GAIA](https://huggingface.co/papers/2311.12983) | Benchmark for real-world assistant tasks requiring reasoning and tools. |
| [WebArena](https://github.com/web-arena-x/webarena) | Web agent benchmark on realistic websites. |

## Learning Resources

### Guides and Cookbooks

| Resource | Notes |
| --- | --- |
| [OpenAI Cookbook](https://github.com/openai/openai-cookbook) | Practical examples for OpenAI APIs and app patterns. |
| [Anthropic Cookbook](https://github.com/anthropics/anthropic-cookbook) | Claude examples, tools, and agent recipes. |
| [Google Gemini Cookbook](https://github.com/google-gemini/cookbook) | Gemini API examples and implementation patterns. |
| [Prompt Engineering Guide](https://www.promptingguide.ai/) | Community guide to prompting techniques and patterns. |
| [Learn Prompting](https://learnprompting.org/) | Beginner-to-advanced prompting course. |
| [Microsoft Generative AI for Beginners](https://github.com/microsoft/generative-ai-for-beginners) | Free course for generative AI fundamentals. |
| [Microsoft AI Agents for Beginners](https://github.com/microsoft/ai-agents-for-beginners) | Introductory course for building AI agents. |
| [Hugging Face Agents Course](https://huggingface.co/learn/agents-course) | Open course for building agents with Hugging Face tools. |

### Papers, Books, and Courses

| Resource | Notes |
| --- | --- |
| [LLM Powered Autonomous Agents](https://lilianweng.github.io/posts/2023-06-23-agent/) | Foundational overview of planning, memory, and tool use. |
| [ReAct](https://arxiv.org/abs/2210.03629) | Reasoning and acting pattern behind many agent workflows. |
| [Toolformer](https://arxiv.org/abs/2302.04761) | Training language models to use tools. |
| [Tree of Thoughts](https://arxiv.org/abs/2305.10601) | Deliberate search over reasoning paths. |
| [AI Engineering](https://www.oreilly.com/library/view/ai-engineering/9781098166298/) | Chip Huyen's guide to building production AI systems. |
| [Build a Large Language Model From Scratch](https://www.manning.com/books/build-a-large-language-model-from-scratch) | Sebastian Raschka's implementation-focused LLM book. |
| [DeepLearning.AI Short Courses](https://www.deeplearning.ai/short-courses/) | Short practical courses on LLMs, agents, RAG, and prompting. |
| [fast.ai Practical Deep Learning](https://course.fast.ai/) | Practical deep learning course. |
| [Stanford CS224N](https://web.stanford.edu/class/cs224n/) | Stanford NLP course. |

### Communities and News

| Resource | Notes |
| --- | --- |
| [Latent Space](https://www.latent.space/) | AI engineering newsletter and podcast. |
| [The Rundown AI](https://www.therundown.ai/) | Daily AI news digest. |
| [Ben's Bites](https://www.bensbites.co/) | Daily AI product and builder newsletter. |
| [Simon Willison's Weblog](https://simonwillison.net/) | Practical writing on LLMs, tools, and open source AI. |
| [r/LocalLLaMA](https://www.reddit.com/r/LocalLLaMA/) | Community for local and open-source LLMs. |
| [r/LangChain](https://www.reddit.com/r/LangChain/) | Community for LangChain, LangGraph, and agent builders. |
| [Hugging Face](https://huggingface.co/) | Models, datasets, Spaces, papers, and community resources. |
| [Papers With Code](https://paperswithcode.com/) | Research papers connected to code and benchmarks. |

## Source Inspiration

This README was reworked from the sources listed in [list.txt](list.txt):

- [awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps) for runnable app/template organization.
- [awesome-ai-agents-2026](https://github.com/ARUNAGIRINATHAN-K/awesome-ai-agents-2026) and [awesome-ai-agents-2026](https://github.com/caramaschiHG/awesome-ai-agents-2026) for agent categories, orchestration, protocols, observability, and vertical agents.
- [FMHY Artificial Intelligence](https://fmhy.net/ai) for practical AI site/tool indexing and local/self-hosted distinctions.
- [awesome-generative-ai](https://github.com/steven2358/awesome-generative-ai) for generative media, writing, search, and learning resources.
- [awesome-ai](https://github.com/edwardtay/awesome-ai) for the decision guide, platform/API taxonomy, governance, infrastructure, and benchmarks.

## Contributing

Contributions are welcome. Good additions should be useful, actively maintained, and placed in the most specific category possible.

Suggested entry style:

```markdown
| [Tool Name](https://example.com/) | Short, practical description of what it helps people do. |
```

Prefer tools, models, papers, templates, and learning resources that someone can evaluate or use directly. Mark archived, deprecated, or inactive projects when known.