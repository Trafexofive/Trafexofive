# GODSPEED

![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-%2300599C.svg?style=flat&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Arch Linux](https://img.shields.io/badge/Arch_Linux-1793D1?style=flat&logo=arch-linux&logoColor=white)
![Self Hosted](https://img.shields.io/badge/Self_Hosted-100%25-green)
![Bare Metal](https://img.shields.io/badge/Bare_Metal-No_Cloud-orange)

I build production infrastructure from scratch and run it on my own hardware. No cloud providers. No vendor lock-in. Everything self-hosted, battle-tested, and optimized for real workloads.

**Systems programmer. Infrastructure engineer. FOSS maximalist.**

---

## Current Projects

### [second-brain-stack](https://github.com/Trafexofive/second-brain-stack)
**Self-hosted knowledge management with AI-powered search and knowledge graphs.**

Production semantic search over personal knowledge bases. FastAPI backend with SQLite storage, vector embeddings for similarity search, RAG for conversational queries, and Neo4j for relationship mapping. Handles thousands of documents with sub-second retrieval. Built to replace Notion/Obsidian with full data sovereignty.

**Stack:** Python • FastAPI • SQLite • ChromaDB • LangChain • Neo4j  
**Features:** Vector search • RAG pipelines • Knowledge graphs • RESTful API

### [SimpleCrawler-MK4](https://github.com/Trafexofive/SimpleCrawler-MK4)
**Distributed web crawler that transforms documentation into LLM-ready structured data.**

Microservices architecture for concurrent crawling at scale. Intelligent parsing with content normalization, deduplication, and metadata extraction. Redis-backed task queue handles thousands of concurrent crawls. PostgreSQL stores structured output optimized for embedding generation.

**Stack:** Python • FastAPI • PostgreSQL • Redis • Docker • BeautifulSoup  
**Features:** Concurrent crawling • Smart parsing • Content normalization • Microservices architecture

### [DeepSearchStack](https://github.com/Trafexofive/DeepSearchStack)
**Self-hosted deep search engine with LLM enrichment and multi-source aggregation.**

Aggregates results from multiple search engines, enriches with LLM analysis, caches intelligently, and serves through a unified API. Vector storage for semantic search. Built to replace Google with complete privacy and customizable ranking algorithms.

**Stack:** Python • FastAPI • Redis • Vector DB • LLM integration  
**Features:** Multi-engine aggregation • LLM enrichment • Intelligent caching • Semantic search

---

## Technical Stack

**Languages:** C • C++ • Python • Bash • Lua • Go • TypeScript when necessary  
**Infrastructure:** Arch Linux • Bare metal servers • Docker • Systemd • Nginx • WireGuard  
**Databases:** PostgreSQL • SQLite • Redis • Neo4j  
**Tools:** Neovim • Git • Make • GCC/Clang  
**Philosophy:** Minimal dependencies, maximum control, production-grade or don't ship

### Self-Hosted Infrastructure

Currently running on hardware I own:

**Core Services:** Full email stack (Postfix, Dovecot, rspamd) • Git server (Gitea) • Proxy management (nginx) • DNS/Ad-blocking (AdGuard) • VPN (WireGuard) • Dashboard (Glance)

**Media & Content:** Navidrome (music streaming) • Audiobookshelf (audiobooks/podcasts) • YouTube archiving (yt-dlp stack)

**Development:** Build servers • Container registry • Private package mirrors • Testing environments • Experimental labs

All managed as code. All version controlled. All understood at the system level.

---

## Selected Work

### Production Infrastructure

**[second-brain-stack](https://github.com/Trafexofive/second-brain-stack)** - AI-powered knowledge management with semantic search, RAG, and knowledge graphs. Replaces Notion/Obsidian with full data sovereignty.

**[SimpleCrawler-MK4](https://github.com/Trafexofive/SimpleCrawler-MK4)** - Distributed web crawler with microservices architecture. Transforms documentation into LLM-ready structured data at scale.

**[DeepSearchStack](https://github.com/Trafexofive/DeepSearchStack)** - Self-hosted search engine with multi-source aggregation and LLM enrichment. Complete privacy with customizable ranking.

**[DB-Forge-MK1](https://github.com/Trafexofive/DB-Forge-MK1)** - Database-as-a-Service platform with TypeScript backend and multi-language clients.

**[iq-option-bot-api](https://github.com/Trafexofive/iq-option-bot-api)** - AI-powered trading bot with LLM integration and microservices architecture.

### AI & Automation

**[Cortex-MK1](https://github.com/Trafexofive/Cortex-MK1)** - Experimental AI orchestration and agent coordination system.

**[automation-stack-MK1](https://github.com/Trafexofive/automation-stack-MK1)** - Self-hosted automation infrastructure with Docker orchestration.

**[LSP-Context](https://github.com/Trafexofive/LSP-Context)** - Language Server Protocol context extraction for enhanced code analysis.

### Systems Programming

**[satori](https://github.com/Trafexofive/satori)** - Custom programming language implementation from scratch in C.

**[agent-lib](https://github.com/Trafexofive/agent-lib)** - C++ library for building autonomous agents.

**[excel-tui](https://github.com/Trafexofive/excel-tui)** - Terminal spreadsheet with Excel-like functionality in C++.

**[cub3d](https://github.com/Trafexofive/cub3d)** - Raycasting game engine inspired by Wolfenstein 3D.

**[minishell](https://github.com/Trafexofive/minishell)** - Bash-like shell implementation from scratch.

**[IRC-cpp](https://github.com/Trafexofive/IRC-cpp)** - Full IRC server implementation in C++.

### Developer Tools

**[BoilerFab](https://github.com/Trafexofive/BoilerFab)** - Project scaffolding platform for rapid development setup.

**[RTFM](https://github.com/Trafexofive/RTFM)** - Documentation and reference tool with personality.

**[noter](https://github.com/Trafexofive/noter)** - Efficient note-taking CLI tool in Go.

**[blogen](https://github.com/Trafexofive/blogen)** - Static blog generator with minimal dependencies.

### Self-Hosted Services

**[inception-42](https://github.com/Trafexofive/inception-42)** - Complete Docker infrastructure with multiple services.

**[ollama-api-server-docker](https://github.com/Trafexofive/ollama-api-server-docker)** - Local LLM API server.

**[whisper-docker](https://github.com/Trafexofive/whisper-docker)** - Self-hosted speech-to-text service.

**[yt-dlp-stack](https://github.com/Trafexofive/yt-dlp-stack)** - YouTube download and archiving automation.


---

## Research Interests

Systems architecture and emergent complexity • AI agent orchestration and autonomy • LLM safety and alignment • Quantitative trading and algorithmic strategies • Performance optimization at scale • Low-level programming (assembly, embedded systems, FPGAs) • Security and OSINT • Entropy in systems design

---

## Philosophy

Dependencies are technical debt. Complexity is justified only when it enables emergent capabilities. If you don't understand it at the system level, you don't control it. Production is the only environment that teaches truth. Manual processes are bugs waiting to be automated.

Infrastructure is a factory floor: optimize throughput, eliminate bottlenecks, automate relentlessly, measure everything, iterate until bulletproof. Every service is a machine in a larger assembly line. Every failure is a signal. Every optimization unlocks the next stage of scale.

---

## Contact

**Email:** lamkadmi.business@gmail.com

Open to collaboration on systems-level projects, self-hosted infrastructure, performance optimization, and production-grade tooling. If you're building something that requires deep technical work and you ship real solutions—let's talk.

---

*Building on my own infrastructure. Sharing what works.*

