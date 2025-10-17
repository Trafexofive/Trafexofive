```
 ██████╗  █████╗ ██████╗  ███████╗██████╗ ███████╗███████╗██████╗ 
██╔════╝ ██╔══██╗██╔══██╗██╔════╝██╔══██╗██╔════╝██╔════╝██╔══██╗
██║  ███╗██║  ██║██║  ██║███████╗██████╔╝█████╗  █████╗  ██║  ██║
██║   ██║██║  ██║██║  ██║╚════██║██╔═══╝ ██╔══╝  ██╔══╝  ██║  ██║
╚██████╔╝╚█████╔╝██████╔╝███████║██║     ███████╗███████╗██████╔╝
 ╚═════╝  ╚════╝ ╚═════╝ ╚══════╝╚═╝     ╚══════╝╚══════╝╚═════╝ 
```

# 👋 Aka L'bro

**Production systems from scratch. Self-hosted on my own bare metal.**

I build low-level, self-hosted infrastructure (mostly coded from scratch) that actually works—mail servers, CI/CD pipelines, specialized stacks, bespoke experimental protocols, LLM integration and agentic architectures. Everything runs on iron I control. No cloud providers. No vendor lock-in. Just FOSS, features, optimization, and competence.

**Vim Motions. Arch Linux. C/C++/Python/Bash. Language agnostic. FOSS maximalist.**

---

## 🔧 What I Ship

I don't build MVPs or demos. I build **production-grade systems** because that's the only way to learn what actually matters. Everything I ship is:

- **Battle-tested** - Running real workloads for me and the crew
- **Self-hosted** - Complete data sovereignty, zero external dependencies where possible
- **Built from scratch** - Understanding every layer of the stack
- **Optimized** - Performance and efficiency aren't optional

### Technical Focus

**Low-level systems programming** • Direct hardware interaction, performance tuning/benchmarking, performant C++ microservices  
**Self-hosted infrastructure** • Mail, Git, media, self-hosted FOSS services and webUIs, CI/CD, databases, monitoring—all on my iron  
**Automation pipelines** • Zero-touch deployments—just clone and `make up`  
**Wheel reinvention** • Sometimes the existing wheel sucks and you need a better one. But in 99% of cases, it's not. Yet the best way to learn is to build it yourself.

---

## 🛠️ Stack

**Languages:** My heart belongs to C • C++ • Python • Lua • Bash • But whatever solves the problem best  
**Environment:** Arch Linux • Bare metal servers • Self-hosted everything • Docker • Systemd • Nix (occasionally) • Nvim  
**Philosophy:** Minimize dependencies, maximize control, ship production-ready or don't ship (even though the code might be sh*t)

### Self-Hosted Infrastructure

Currently running:
- **Email infrastructure** - Full mail server stack with spam filtering, encryption
- **Bespoke Git server** - Self-hosted repos, no GitHub dependency for critical code
- **CI/CD** - Automated build, test, deploy pipelines
- **Proxy server stack** - NPM (nginx Proxy Manager), ddclient (REST dynamic DNS client), AdGuard Home (network-wide ad blocking), and Glance (neat configurable dashboard using YAML manifests)
- **Databases** - PostgreSQL, Redis, SQLite, Neo4j depending on use case
- **Web services** - Custom HTTP servers, reverse proxies, all the usual suspects
- **DeepSearch stack** - Self-hosted DeepSearch microservice stack for agentic deep search with LLM vector storage and retrieval, multiple browser engines, caching
- **Media && Music stack** - [Your media services here]
- **Automation and AI** - n8n instance with Postgres and Redis integrated with OpenWebUI. Crawlers, scrapers, data pipelines, you name it.

Wish I could run more services but iron is finite.

All managed as code. All version controlled. All understood at the system level.

---

## 🎯 Current Work

### Active Projects

[ I'll fill this empty for now ]

### Research Interests

- Systems architecture and emergent complexity
- AI agent orchestration, autonomy and their emerging architectures
- LLM safety and alignment
- A bit of general purpose security as of late (mainly in code and hardware infras), as well as OSINT
- Trading, quantitative analysis and algorithmic strategies (mostly experimental and hobbyist for now)
- Of course, no quant or data science work is complete without mastering a bunch of Python libraries like pandas, numpy, matplotlib, seaborn, scikit-learn, tensorflow, keras, pytorch etc. Obviously not an easy feat. For that reason I'm starting to use a self-hosted instance of Marimo (for py notebooks, I highly suggest you check it out) for fast Python prototyping
- Performance optimization at scale (system design, network stacks, storage systems, optimization techniques and paradigms)

---

## 🏗️ Build Philosophy

```
1. Understand the problem from first principles
2. Build for production, not for demo day
3. Self-host on infrastructure you control
4. Optimize ruthlessly, measure everything
5. Iterate based on real-world usage
6. Share what works with the crew
```

**Core Principles:**
- Dependencies are technical debt
- Complexity is only justified when it enables emergent capabilities
- If you don't understand it, you don't control it
- Production is the only environment that matters
- Manual processes are inefficiencies waiting to be automated

---

## 🎮 Mental Model

Even though I replaced gaming with code, my engineering approach is still fundamentally shaped by these experiences:

**Factorio** → Systems thinking at scale  
- Every component is part of a larger pipeline
- Bottlenecks compound exponentially—find them early
- Automation isn't optional, it's the entire point
- Throughput optimization is a never-ending game
- The factory must grow (but efficiently)

**Minecraft Expert Tech Modpacks** → Embracing necessary complexity  
- No shortcuts—complexity gates progression for a reason
- Multi-stage processing pipelines teach you about dependencies
- Sometimes you need 7 intermediate steps to get the output you want
- Understanding the tech tree is understanding the system
- Deep integration between systems creates emergent gameplay

**Dead Cells** → Iteration and adaptation (when I still had time)  
- Fast iteration cycles reveal what actually works
- Learn from failures, don't repeat them
- Muscle memory comes from repetition, not theory
- Optimize the critical path, improvise the rest

**Half-Life & Arcade Shooters** → Tight systems design  
- Every element serves a purpose
- Resource management under pressure
- Quick decisions with incomplete information
- Systems should feel responsive, not sluggish

*I treat infrastructure like a factory floor: optimize throughput, eliminate bottlenecks, automate the boring parts, measure everything, and iterate until bulletproof. Every service is a machine in a larger assembly line. Every failure is a signal. Every optimization unlocks the next stage of scale.*

---

## 💡 Why I Build

**Recreational engineer. Indie hacker. Complexity enjoyer.**

I build tools that solve problems I actually have—not problems VCs think I should care about. Everything here is built for:

- **Personal infrastructure** - Tools I need daily
- **The crew** - Solutions that help my friends and collaborators  
- **Learning** - Building from scratch teaches what copying or "vibing" never will
- **Ownership** - My code, my data, my servers, my rules

I value:
- **Data sovereignty** over convenience
- **Understanding** over abstraction
- **Control** over managed services
- **Production quality** over shipping fast (sometimes XD, fine line there)

---

## 🤝 Collaboration

Open to working with:
- Fellow wheel reinventors who aren't afraid of complexity
- Self-hosters who value data sovereignty
- Low-level enthusiasts who care about performance
- FOSS advocates building open systems
- Anyone shipping real solutions for real problems

If you're building something that requires systems thinking, optimization, and production-ready code—let's talk.

---

## 📫 Get in Touch

Building on my own infrastructure (always) • Sharing what works (sometimes)

**"Dependencies are suggestions. Complexity enables emergence. Production is the only environment that matters."**

---

<sub>The Great Work Continues ...</sub>
