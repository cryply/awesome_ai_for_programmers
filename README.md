# Awesome AI for Programmers

A curated collection of the most useful AI resources for software development.

## Use Cases with LLMs

Practical applications of ChatGPT and other LLMs for developers:

1. **Code generation** — writing code from task descriptions, adding features to existing code (e.g., a function that sorts a list)
   - Refactoring (splitting a long method into shorter ones)
   - Optimization
2. **Test generation** — writing tests for code, generating UI tests
3. **Test naming** — naming tests according to best practices (see Prompts section)
4. **[TDD with AI](https://github.com/di-sukharev/AI-TDD)** — writing code from tests
5. **SQL queries** — writing and optimizing SQL queries
6. **ORM conversion** — converting SQL to Entity Framework and vice versa
7. **Code analysis** — finding style issues, async/multithreading bugs, inefficient queries
8. **Code explanation** — explaining algorithms and complex code
9. **Error debugging** — detailed error information and fixes
10. **Diagrams** — creating diagrams with [Mermaid](https://mermaid.js.org/), [quickchart.io](http://quickchart.io/), [Graphviz](https://graphviz.org/)
11. **Data generation** — generating test data arrays (e.g., medical terms)
12. **Documentation** — adding docs to methods, generating markdown from code
13. **Code conversion** — converting between programming languages
14. **Format conversion** — JSON to XML and vice versa
15. **Class generation** — generating classes from JSON
16. **Complexity analysis** — evaluating computational complexity
17. **Data escaping** — escaping JSON for string variables
18. **Interface implementation** — generating class implementations from interfaces

---

## Best Practices

- Use the strongest models: **[GPT-5.2](https://chat.openai.com/)**, **[Claude Opus 4.5](https://claude.ai/)**, **[Gemini 3 Pro](https://gemini.google.com/)** for best quality
- Provide examples (*few-shot prompting*)
- If the LLM is "lazy", use enhancer prompts or break down the task
- If you get compilation/runtime errors, paste them back and ask for fixes
- Explicitly indicate how you're delimiting code (e.g., "the code delimited by triple backticks")
- Google's [prompting cheat sheet](https://big-picture.com/media/the_prompt_engineering_cheat_sheet.pdf) is great for beginners ([explanation](https://medium.com/the-generator/the-perfect-prompt-prompt-engineering-cheat-sheet-d0b9c62a2bba))
- DeepLearning + OpenAI [prompt engineering course](https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/) for developers

---

## AI Services for Software Development

🌟 marks highly recommended services.

### Chat / LLMs

| Use Case | Recommended Tool |
|----------|------------------|
| Creative tasks | [GPT-5.2](https://chat.openai.com/) |
| Long docs + precision | [Claude Opus 4.5](https://claude.ai/) |
| Google multimodal | [Gemini 3 Pro](https://gemini.google.com/) |
| Live X data, unfiltered | [Grok 4](https://grok.x.ai/) |
| Open-source (free) | [DeepSeek V3.2](https://chat.deepseek.com/) |
| Chinese alternative | [Qwen 3](https://chat.qwenlm.ai/) |

**More Chatbots:**
- 🌟 [HuggingFace Chat](https://huggingface.co/chat/) — chat with best open models (Llama 3, Command R+)
- [Perplexity](https://www.perplexity.ai/) — chat focused on web search with citations
- [Groq](https://groq.com/) — ultra-fast inference
- [LMSys Chat](https://chat.lmsys.org/) — compare models side-by-side
- [MistralAI Chat](https://chat.mistral.ai/)
- [Cohere Coral](https://coral.cohere.com/) — Command R/R+ with RAG via Grounding
- [DuckDuckGo Chat](https://duckduckgo.com/?q=DuckDuckGo&ia=chat)

### Code Editors / IDE

| Use Case | Recommended Tool |
|----------|------------------|
| Terminal agent | [Claude Code](https://www.anthropic.com/claude-code) |
| Full project context | [Cursor](https://cursor.com/) |
| Cloud sandbox | [Codex](https://openai.com/index/openai-codex/) |
| Agentic IDE | [Google IDX](https://idx.dev/) |

**More IDEs:**
- [Aide](https://aide.dev/) — AI-powered IDE with code generation
- [Zed](https://zed.dev/) — lightweight, fast editor with built-in Copilot

**Autocomplete:**
- [GitHub Copilot](https://github.com/features/copilot) / [Copilot Chat](https://docs.github.com/en/copilot/github-copilot-chat) — most popular plugin for JetBrains/VS Code
- [llama-coder](https://github.com/ex3ndr/llama-coder) — open-source local Copilot for VS Code with Ollama
- [Continue](https://continue.dev/) — VS Code and JetBrains, supports Ollama and LM Studio
- [Cody](https://sourcegraph.com/cody) — VS Code autocomplete with [Ollama support](https://sourcegraph.com/blog/local-code-completion-with-ollama-and-cody)
- [supermaven](https://supermaven.com/) — ultra-fast autocomplete with 300k context window
- [Tabby](https://tabby.tabbyml.com/) — open-source autocomplete with local models

### Build / App Generators

| Use Case | Recommended Tool |
|----------|------------------|
| UI components | [v0](https://v0.dev/) |
| Full-stack apps | [Bolt.new](https://bolt.new/) |
| MVPs + backend | [Lovable](https://lovable.dev/) |
| Instant deploy | [Replit Agent](https://replit.com/) |

**More Generators:**
- 🌟 [aider](https://aider.chat) — AI pair programmer in terminal. High SWE-bench scores
- [Devin](https://cognition.ai/) — Cognition Labs' AI software engineer. Now used at Goldman Sachs, Santander
- [OpenHands](https://github.com/All-Hands-AI/OpenHands) — formerly OpenDevin, open-source alternative
- [SWE-agent](https://github.com/princeton-nlp/SWE-agent)
- [Plandex](https://github.com/plandex-ai/plandex) — terminal AI for large tasks

### Media Generation

| Use Case | Recommended Tool |
|----------|------------------|
| Artistic images | [Midjourney v7](https://www.midjourney.com/) |
| Open-source images | [Flux](https://blackforestlabs.ai/) |
| Cinematic video | [Sora 2](https://openai.com/sora/) |
| Google video | [Veo 3](https://deepmind.google/technologies/veo/) |
| Fast video | [Kling 2.6](https://klingai.com/) |
| Voice cloning | [ElevenLabs](https://elevenlabs.io/) |
| Music generation | [Suno v5](https://suno.com/) |

**More Media Tools:**
- [Runway Gen-4](https://runwayml.com/) — AI video with professional editing features
- [Pika](https://pika.art/) — AI video generation
- [Udio](https://www.udio.com/) — AI music generation
- [Riffusion](https://www.riffusion.com/) — AI music, unlimited free generations

### Research

| Use Case | Recommended Tool |
|----------|------------------|
| Web + citations | [Perplexity Pro](https://www.perplexity.ai/) |
| Your documents | [Claude Opus 4.5](https://claude.ai/) |
| Audio briefings | [NotebookLM](https://notebooklm.google.com/) |
| Deep research | [Gemini Deep Research](https://gemini.google.com/) |
| Live social trends | [Grok 4](https://grok.x.ai/) |

### Automation

| Use Case | Recommended Tool |
|----------|------------------|
| AI-native workflows | [n8n](https://n8n.io/) |
| Visual complex flows | [Make](https://make.com/) |

**Details:**
- 🌟 **[n8n](https://n8n.io/)** — open-source workflow automation. Self-hostable, 400+ integrations, native AI/LangChain support, AI agents. Best for developers
- **[Make](https://make.com/)** — formerly Integromat. Visual drag-and-drop, AI agents (April 2025), better for non-technical users

### Code Generation, Tests, Documentation & Code Review

| Tool | Features |
|------|----------|
| [JetBrains AI Assistant](https://www.jetbrains.com/ai/) | Code generation, test generation, commit summaries, code chat |
| [Open Interpreter](https://openinterpreter.com/) | Code Interpreter alternative with internet access, runs code locally |
| [Codium](https://www.codium.ai/) | Test generation, code review, improvements |
| [OpenCommit](https://github.com/di-sukharev/opencommit) | Generate commit messages from diffs |
| [Machinet](https://www.machinet.net/) | Context-aware code generation, unit tests, code search |

### Codebase Search

| Tool | Features |
|------|----------|
| 🌟 [greptile](https://app.greptile.com/) | Natural language code search (cloud) |
| [Sourcegraph](https://sourcegraph.com/code-search) | Natural language code search |
| [Phind for VS Code](https://marketplace.visualstudio.com/items?itemName=phind.phind) | VS Code extension with code search |

### Tools for Deploying AI Models

| Tool | Features |
|------|----------|
| 🌟 [LM Studio](https://lmstudio.ai/) | Deploy LLMs locally (HuggingFace gguf), chat UI, embeddings |
| 🌟 [Ollama](https://ollama.com/) | Deploy LLMs locally in a few clicks. Use with [Open WebUI](https://github.com/open-webui/open-webui) |
| [Llama file](https://github.com/Mozilla-Ocho/llamafile) | Deploy a model with API Gateway in one command |
| [LocalAI](https://github.com/mudler/LocalAI) | Run open-source models |
| [GPT4All](https://github.com/nomic-ai/gpt4all) | Local LLM deployment |

### Web & Desktop Clients for LLM Chat via API

| Tool | Platforms |
|------|-----------|
| 🌟 [Chatbox](https://chatboxai.app/) | Desktop, Android, iOS, Web for multiple LLMs (including Ollama) |
| [Open WebUI](https://github.com/open-webui/open-webui) | Web UI for various LLMs, manages Ollama models via UI |
| [NextChat](https://github.com/ChatGPTNextWeb/ChatGPT-Next-Web) | Popular web UI for multiple LLMs |
| 🌟 [Jan](https://jan.ai/) | Chat and backend with built-in models, integrates with OpenAI, Azure, OpenRouter |

### Specialized Tools

| Tool | Features |
|------|----------|
| 🌟 [Warp](https://www.warp.dev/) | AI-driven terminal |

### API & Proxies for AI Services

| Service | Description |
|---------|-------------|
| 🌟 [OpenRouter](https://openrouter.ai/) | Proxy to many models including GPT-4, Claude, open LLMs |
| [Mistral API](https://docs.mistral.ai/) | Mistral models API |
| [Groq API](https://console.groq.com/) | Ultra-fast inference API |
| [Claude API](https://www.anthropic.com/api) | Anthropic's Claude API |
| [Azure OpenAI](https://azure.microsoft.com/en-us/products/ai-services/openai-service) | Microsoft's OpenAI service |
| [Amazon Bedrock](https://aws.amazon.com/bedrock/) | AWS managed AI service |

### Cloud for LLM

| Service | Features |
|---------|----------|
| [together.ai](https://www.together.ai/) | Open-source models, custom deploys, fine-tuning |
| [Fireworks](https://fireworks.ai/) | Open-source models + FireFunction, custom deploys |
| [Amazon SageMaker](https://aws.amazon.com/sagemaker/) | Proprietary LLMs (Claude), embeddings (Cohere, Voyage) |
| [deepinfra](https://deepinfra.com/) | Affordable open LLMs, GPU rental |
| [Cloudflare Workers AI](https://developers.cloudflare.com/workers-ai/models/) | Small open models with playground and API |
| [Perplexity API](https://docs.perplexity.ai/) | Perplexity models + open models (Llama 3) |
| [Replicate](https://replicate.com/) | Open models via API, custom model deployment |

**GPU Rental:**

| Service | Link |
|---------|------|
| Lambda | [lambdalabs.com](https://lambdalabs.com/) |
| vast.ai | [cloud.vast.ai](https://cloud.vast.ai/) |
| nebius.ai | [nebius.ai](https://nebius.ai/) |
| RunPod | [runpod.io](https://www.runpod.io/) |

### Leaderboards & Model Lists

| Resource | Description |
|----------|-------------|
| [LMArena](https://lmarena.ai/) | Compare 2 random models with user voting |
| [Lmsys Arena](https://chat.lmsys.org/) | LLM leaderboard based on user ratings (Coding category available) |
| [LLM Explorer](https://llm.extractum.io/) | LLM catalog by size, VRAM requirements, coding scores |
| [BigCode Leaderboard](https://huggingface.co/spaces/bigcode/bigcode-models-leaderboard) | Coding models |
| [Open LLM Leaderboard](https://huggingface.co/spaces/HuggingFaceH4/open_llm_leaderboard) | Open LLMs |
| [MTEB Leaderboard](https://huggingface.co/spaces/mteb/leaderboard) | Embeddings models for RAG |

### AI Service Lists

| Resource | Description |
|----------|-------------|
| 🌟 [AIA Podcast Catalog](https://awclub.github.io) | AI services from [AIA Podcast](https://www.youtube.com/playlist?list=PLhf2AM9rZ9b8bFHSTh9jr2vlPd4Q0PJTZ) |
| [TopAI.tools](https://topai.tools/) | AI tools directory |
| [There's An AI for That](https://theresanaiforthat.com/ai/) | AI services with natural language search |

---

## Resources

### Courses

| Course | Provider |
|--------|----------|
| 🌟 [ChatGPT Prompt Engineering for Developers](https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/) | DeepLearning + OpenAI |
| [Prompting course with OpenAI](https://learnprompting.thinkific.com/courses/ChatGPT-for-Everyone) | Learn Prompting |
| [OpenAI Cookbook resources](https://cookbook.openai.com/articles/related_resources#video-courses) | OpenAI |

### Lectures

| Lecture | Speaker |
|---------|---------|
| [Intro to Large Language Models](https://www.youtube.com/watch?v=zjkBMFhNj_g) | Andrej Karpathy |
| [Let's build GPT Tokenizer](https://www.youtube.com/watch?v=zduSFxRajkE) | Andrej Karpathy |
| [Prompt Engineering Overview](https://youtu.be/dOxUroR57xs) | DAIR.AI |

### Articles

| Article | Source |
|---------|--------|
| [Prompt Engineering Guide](https://platform.openai.com/docs/guides/prompt-engineering) | OpenAI |
| [Best Practices](https://help.openai.com/en/articles/6654000-best-practices-for-prompt-engineering-with-openai-api) | OpenAI |
| [Prompting for Coding](https://www.promptingguide.ai/applications/coding) | Prompting Guide |
| [Prompt Engineering](https://docs.anthropic.com/claude/docs/prompt-engineering) | Anthropic |

### Communities

| Community | Link |
|-----------|------|
| 🌟 AIA Podcast | [YouTube](https://www.youtube.com/playlist?list=PLhf2AM9rZ9b8bFHSTh9jr2vlPd4Q0PJTZ) |

---

## Contribution

Improvements are warmly welcomed! Send PRs to expand the knowledge base.
