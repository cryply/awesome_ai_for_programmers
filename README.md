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
10. **Diagrams** — creating diagrams with Mermaid, [quickchart.io](http://quickchart.io/), Graphviz
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

- Use the strongest models: **GPT-5.2**, **Claude Opus 4.5**, **Gemini 3 Pro** for best quality
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
| Creative tasks | GPT-5.2 |
| Long docs + precision | Claude Opus 4.5 |
| Google multimodal | Gemini 3 Pro |
| Live X data, unfiltered | Grok 4 |
| Open-source (free) | DeepSeek V3.2 |
| Chinese alternative | Qwen 3 |

**Chatbots:**
- 🌟 **[ChatGPT](https://chat.openai.com/)** — chat, web search, image analysis, code execution, RAG. [Privacy settings](https://privacy.openai.com/policies?modal=take-control)
- 🌟 **[Claude](https://claude.ai/)** — chat, web search, image analysis, RAG. Huge context window for entire books. Claude Opus 4.5 is GPT-4 level or higher
- **[Gemini](https://gemini.google.com/)** — chat, web search, Google services integration
- 🌟 **[HuggingFace Chat](https://huggingface.co/chat/)** — chat with best open models (Llama 3, Command R+)
- **[Perplexity](https://www.perplexity.ai/)** — chat focused on web search with citations
- **[Groq](https://groq.com/)** — ultra-fast inference
- **[LMSys Chat](https://chat.lmsys.org/)** — compare models side-by-side
- **[MistralAI Chat](https://chat.mistral.ai/)**
- **[Cohere Coral](https://coral.cohere.com/)** — Command R/R+ with RAG via Grounding
- **[DuckDuckGo Chat](https://duckduckgo.com/?q=DuckDuckGo&ia=chat)**

### Code Editors / IDE

| Use Case | Recommended Tool |
|----------|------------------|
| Terminal agent | Claude Code |
| Full project context | Cursor |
| Cloud sandbox | Codex |
| Agentic IDE | Google Anti-Gravity |

**AI-driven IDEs:**
- 🌟 **[Cursor](https://cursor.sh/)** — VS Code fork with AI assistant, improved Copilot, context-aware chat. Supports custom OpenAI/Azure keys or local LLMs. New v2.2 with Debug Mode and Visual Editor
- **[Aide](https://aide.dev/)** — AI-powered IDE with code generation
- **[Zed](https://zed.dev/)** — lightweight, fast editor with built-in Copilot

**Autocomplete:**
- **[GitHub Copilot](https://github.com/features/copilot)** / **[Copilot Chat](https://docs.github.com/en/copilot/github-copilot-chat)** — most popular plugin for JetBrains/VS Code
- **[llama-coder](https://github.com/ex3ndr/llama-coder)** — open-source local Copilot for VS Code with Ollama
- **[Continue](https://continue.dev/)** — VS Code and JetBrains, supports Ollama and LM Studio
- **[Cody](https://sourcegraph.com/cody)** — VS Code autocomplete with [Ollama support](https://sourcegraph.com/blog/local-code-completion-with-ollama-and-cody)
- **[supermaven](https://supermaven.com/)** — ultra-fast autocomplete with 300k context window
- **[Tabby](https://tabby.tabbyml.com/)** — open-source autocomplete with local models

**Terminal Agents:**
- 🌟 **[Claude Code](https://www.anthropic.com/claude-code)** — Anthropic's agentic coding tool for terminal. Understands your codebase, executes routines, handles git workflows. Works in terminal, IDE extensions, or @claude on GitHub

### Build / App Generators

| Use Case | Recommended Tool |
|----------|------------------|
| UI components | v0 |
| Full-stack apps | Bolt.new |
| MVPs + backend | Lovable |
| Instant deploy | Replit Agent |

**Generators:**
- 🌟 **[v0](https://v0.dev/)** — Vercel's AI UI generator. Creates production-ready React components with Tailwind CSS
- 🌟 **[Bolt.new](https://bolt.new/)** — AI-first browser IDE for full-stack apps. Zero setup, instant prototyping
- 🌟 **[Lovable](https://lovable.dev/)** — formerly GPT Engineer. Full-stack from natural language, fastest MVPs ($20M ARR in 2 months)
- **[Replit Agent](https://replit.com/)** — build full apps from descriptions with instant deploy
- 🌟 **[aider](https://aider.chat)** — AI pair programmer in terminal. High SWE-bench scores
- **[Devin](https://cognition.ai/)** — Cognition Labs' AI software engineer. Now used at Goldman Sachs, Santander. 67% PR merge rate, 10x faster migrations
- **[OpenHands](https://github.com/All-Hands-AI/OpenHands)** — formerly OpenDevin, open-source alternative
- **[SWE-agent](https://github.com/princeton-nlp/SWE-agent)**
- **[Plandex](https://github.com/plandex-ai/plandex)** — terminal AI for large tasks

### Media Generation

| Use Case | Recommended Tool |
|----------|------------------|
| Artistic images | Midjourney v7 |
| Open-source images | Flux |
| Cinematic video | Sora 2 |
| Google video | Veo 3 |
| Fast video | Kling 2.6 |
| Voice cloning | ElevenLabs |
| Music generation | Suno v5 |

### Research

| Use Case | Recommended Tool |
|----------|------------------|
| Web + citations | Perplexity Pro |
| Your documents | Claude Opus 4.5 |
| Audio briefings | NotebookLM |
| Deep research | Gemini 3 Deep Research |
| Live social trends | Grok 4 |

### Automation

| Use Case | Recommended Tool |
|----------|------------------|
| AI-native workflows | n8n |
| Visual complex flows | Make |

**Platforms:**
- 🌟 **[n8n](https://n8n.io/)** — open-source workflow automation. Self-hostable, 400+ integrations, native AI/LangChain support, AI agents. Best for developers, per-execution pricing
- **[Make](https://make.com/)** — formerly Integromat. Visual drag-and-drop, AI agents (April 2025), better for non-technical users

### Code Generation, Tests, Documentation & Code Review

- **[JetBrains AI Assistant](https://www.jetbrains.com/help/idea/ai-assistant.html)** — code generation, test generation, commit summaries, code chat
- **[Open Interpreter](https://openinterpreter.com/)** — Code Interpreter alternative with internet access, runs code locally
- **[Codium](https://www.codium.ai/)** — test generation, code review, improvements
- **[OpenCommit](https://github.com/di-sukharev/opencommit)** — generate commit messages from diffs
- **[Machinet](https://www.machinet.net/)** — context-aware code generation, unit tests, code search

### Codebase Search

- 🌟 **[greptile](https://app.greptile.com/)** — natural language code search (cloud)
- **[Sourcegraph](https://sourcegraph.com/code-search)** — natural language code search
- **[Phind for VS Code](https://marketplace.visualstudio.com/items?itemName=phind.phind)** — VS Code extension with code search

### Tools for Deploying AI Models

- 🌟 **[LM Studio](https://lmstudio.ai/)** — deploy LLMs locally (from HuggingFace in gguf), includes chat UI and embeddings support
- 🌟 **[Ollama](https://ollama.com/)** — deploy LLMs locally in a few clicks. Use with [Open WebUI](https://github.com/open-webui/open-webui)
- **[Llama file](https://github.com/Mozilla-Ocho/llamafile)** — deploy a model with API Gateway in one command
- **[LocalAI](https://github.com/mudler/LocalAI)** — run open-source models
- **[GPT4All](https://github.com/nomic-ai/gpt4all)**

### Web & Desktop Clients for LLM Chat via API

- 🌟 **[Chatbox](https://chatboxai.app/)** — Desktop, Android, iOS, Web for multiple LLMs (including Ollama)
- **[Open WebUI](https://github.com/open-webui/open-webui)** — web UI for various LLMs, installs/removes Ollama models via UI
- **[NextChat](https://github.com/ChatGPTNextWeb/ChatGPT-Next-Web)** — popular web UI for multiple LLMs
- 🌟 **[Jan](https://jan.ai/)** — chat and backend with built-in models, integrates with OpenAI, Azure, OpenRouter

### Specialized Tools

- 🌟 **[Warp](https://www.warp.dev/)** — AI-driven terminal

### API & Proxies for AI Services

- 🌟 **[OpenRouter](https://openrouter.ai/)** — proxy to many models including GPT-4, Claude, open LLMs
- **Mistral API**
- **Groq API**
- **Claude API**
- **Azure OpenAI API**
- **Amazon Bedrock**

### Cloud for LLM

Cloud services for running and fine-tuning LLMs:

- **[together.ai](https://www.together.ai/)** — many open-source models, custom deploys, fine-tuning
- **[Fireworks](https://fireworks.ai/)** — open-source models + FireFunction, custom deploys
- **[Amazon SageMaker](https://aws.amazon.com/sagemaker/)** — proprietary LLMs (Claude), embeddings (Cohere, Voyage)
- **[deepinfra](https://deepinfra.com/)** — affordable open LLMs, GPU rental
- **[Cloudflare Workers AI](https://developers.cloudflare.com/workers-ai/models/)** — small open models with playground and API
- **[Perplexity API](https://docs.perplexity.ai/)** — Perplexity models + open models (Llama 3)
- **[Replicate](https://replicate.com/)** — open models via API, custom model deployment

**GPU Rental:**
- [Lambda](https://lambdalabs.com/)
- [vast.ai](https://cloud.vast.ai/)
- [nebius.ai](https://nebius.ai/)
- [RunPod](https://www.runpod.io/)

### Leaderboards & Model Lists

- **[LMArena](https://lmarena.ai/)** — compare 2 random models with user voting
- **[Lmsys Arena](https://chat.lmsys.org/)** — LLM leaderboard based on user ratings (Coding category available)
- **[LLM Explorer](https://llm.extractum.io/)** — LLM catalog by size (7B, 13B, 70B), VRAM requirements, coding scores
- **[BigCode Leaderboard](https://huggingface.co/spaces/bigcode/bigcode-models-leaderboard)** — coding models
- **[Open LLM Leaderboard](https://huggingface.co/spaces/HuggingFaceH4/open_llm_leaderboard)** — open LLMs
- **[MTEB Leaderboard](https://huggingface.co/spaces/mteb/leaderboard)** — embeddings models for RAG

### AI Service Lists

- 🌟 **[AIA Podcast Catalog](https://awclub.github.io)** — AI services from [AIA Podcast](https://www.youtube.com/playlist?list=PLhf2AM9rZ9b8bFHSTh9jr2vlPd4Q0PJTZ)
- **[TopAI.tools](https://topai.tools/)**
- **[There's An AI for That](https://theresanaiforthat.com/ai/)** — AI services with natural language search

---

## Resources

### Courses

- 🌟 **[ChatGPT Prompt Engineering for Developers](https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/)** — DeepLearning + OpenAI
- **[Prompting course with OpenAI](https://learnprompting.thinkific.com/courses/ChatGPT-for-Everyone)**
- [OpenAI Cookbook resources](https://cookbook.openai.com/articles/related_resources#video-courses)

### Lectures

- [Intro to Large Language Models](https://www.youtube.com/watch?v=zjkBMFhNj_g) — Andrej Karpathy
- [Let's build GPT Tokenizer](https://www.youtube.com/watch?v=zduSFxRajkE) — Andrej Karpathy
- [Prompt Engineering Overview](https://youtu.be/dOxUroR57xs) — DAIR.AI

### Articles

- [OpenAI Prompt Engineering Guide](https://platform.openai.com/docs/guides/prompt-engineering)
- [OpenAI Best Practices](https://help.openai.com/en/articles/6654000-best-practices-for-prompt-engineering-with-openai-api)
- [Prompting Guide for Coding](https://www.promptingguide.ai/applications/coding)
- [Anthropic Prompt Engineering](https://docs.anthropic.com/claude/docs/prompt-engineering)

### Communities

- 🌟 **[AIA Podcast YouTube](https://www.youtube.com/playlist?list=PLhf2AM9rZ9b8bFHSTh9jr2vlPd4Q0PJTZ)**

---

## Contribution

Improvements are warmly welcomed! Send PRs to expand the knowledge base.
