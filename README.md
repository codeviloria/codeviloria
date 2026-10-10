# Hi there, I'm Gino Viloria 👋

<div align="center">

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=2E97F7&center=true&vCenter=true&width=600&lines=Senior+RAN+Engineer+%E2%86%92+AI+Engineer;15%2B+Years+in+2G-5G+Radio+Networks;AI+Agents+for+Network+Operations;LangChain+%C2%B7+LangSmith+%C2%B7+Ollama;Local+RAG+%C2%B7+MCP+Servers+(FastMCP);Python+Automation+for+RAN)](https://git.io/typing-svg)

</div>

## 🚀 About Me

```python
class GinoViloria:
    def __init__(self):
        self.name = "Gino Viloria"
        self.role = "Senior RAN Engineer | AI Agents for Network Operations"
        self.location = "Barranquilla, Colombia 🇨🇴"
        self.education = {
            "undergrad": "Telecommunications Engineering",
            "postgrad": "AI & Machine Learning - UT Austin 🤘"
        }

    def get_expertise(self):
        return {
            "telecom": ["2G-5G Networks", "5G NSA/SA", "vRAN/Open RAN", "RF Planning & Optimization"],
            "software": ["Python", "SQL", "Bash", "FastAPI", "C# (Unity)"],
            "ai": ["LangChain", "LangSmith", "Ollama (local LLMs)", "RAG + embeddings", "MCP (FastMCP)", "scikit-learn"],
            "infra": ["Docker", "Linux", "GitHub Actions", "Terraform + AWS (personal project)"],
            "data": ["pandas", "PostgreSQL (JSONB, pgvector)", "Grafana", "Power BI"]
        }

    def what_makes_me_unique(self):
        return """
        🎯 Unique Combination:
        - 15+ years of hands-on RAN experience across Latin America and Japan
        - Python/SQL automation and AI agents built on that domain knowledge
        - I build tools that solve real operational problems
          because I've lived those problems in the field

        👨‍👧 Passion for Teaching:
        - Built a Family Tech Lab with VM infrastructure
        - Teaching cybersecurity & networking to my daughter
        - She won 1st place in a science fair with a CV project we built together!
        """

    def current_focus(self):
        return [
            "🤖 Building AI agents for RAN troubleshooting (5G NSA / EN-DC)",
            "📚 LangChain Academy → LangChain Certified Agent Engineer (LCAE)",
            "🧠 Learning LangGraph, agent memory, middleware and the A2A protocol",
            "🔧 Learning to fine-tune open-weight models (LoRA / QLoRA)",
            "🧪 Evaluating agents with LangSmith datasets and graders",
            "🎮 Creating games in Unity with my daughter",
            "🔐 Hack The Box machines + web security path, TryHackMe"
        ]

    def hobbies(self):
        return ["🏄 Surfing", "🛹 Skateboarding", "🏃 Running", "👨‍👧 Family Tech Time"]

# Initialize
me = GinoViloria()
print(me.what_makes_me_unique())
```

---

## 🎯 The Unique Value Proposition

<table>
<tr>
<td width="50%">

### 🏗️ Telecom RAN Expert
- **15+ years** optimizing 2G–5G networks in 8 countries
- RF team that launched **Rakuten Mobile** (Japan), the first fully virtualized Open RAN commercial network
- Multi-vendor: **Huawei**, **Nokia**, **Ericsson**, **Altiostar**, **Airspan**
- KPI root-cause analysis, L3/E2E signaling, parameter audits

</td>
<td width="50%">

### 🤖 Automation & AI Builder
- **Python/SQL automation:** site configuration from ~2 h to ~20 min per site
- **Golden Parameter Audit:** ~30K Huawei cells, ~800K findings (PostgreSQL + Grafana)
- **AI agents on local models**, traced and debugged in LangSmith
- **Local RAG and MCP servers** (FastMCP) on a CPU home lab
- Post-grad in **AI/ML from UT Austin**

</td>
</tr>
</table>

**Result:** I speak both languages, RAN operations and modern software, and build tools that close the gap between them.

---

## 👨‍👧 Family Tech Lab 🔐

A **home cybersecurity lab** where my daughter and I learn together:

<div align="center">

| 🖥️ Lab Setup | 🎯 Activities | 🏆 Achievements |
|:---:|:---:|:---:|
| **5+ Virtual Machines** | Hack The Box challenges | Science Fair 1st Place |
| Kali Linux + VulnHub | TryHackMe rooms | Computer Vision Project |
| Network segmentation | pwn.college exercises | Unity Game Development |
| Firewall configs | CTF competitions | |

</div>

**Why this matters professionally:**
- ✅ **Teaching complex concepts** in simple terms (critical for cross-functional teams)
- ✅ **Mentoring & coaching** with proven results
- ✅ **Breaking down problems** into learnable chunks
- ✅ **Documentation & knowledge sharing** mindset

---

## 🔥 Featured Projects

### 🤖 AI Agents for Telecom

#### 📡 [5G NSA Troubleshooting Agent](https://github.com/codeviloria/5g-nsa-agent)
Tool-calling agent that diagnoses 5G NSA (EN-DC) problems: SMTC vs SSB timing, B1 threshold, NR PCI mod-3/mod-30 and per-SSB-beam quality.
- **How:** runs 100 % locally on Ollama (Qwen3 8B on CPU); built twice, as a plain Python loop and with LangChain `create_agent`; traced in LangSmith
- **Result:** four trace-driven iterations took it from stopping at the first finding to **every root cause found, with no unsupported actions, in both test scenarios**
- **Tech:** Python, LangChain, LangSmith, Ollama, uv, GitHub Actions · fictional network data

#### ✍️ [Signal to Agents](https://signal-to-agents.pages.dev) · [repo](https://github.com/codeviloria/signal-to-agents)
My lab notebook on AI agents for telecom, in English and Spanish.
- **Tech:** Astro, Cloudflare Pages

#### 🖥️ Home AI Lab *(personal)*
Three CPU-only servers for local AI experiments.
- Local LLMs and **embedding models** with Ollama
- **RAG proofs of concept** over local knowledge bases
- **MCP servers built with FastMCP and deployed**
- WireGuard mesh across five machines running parallel AI coding agents

---

### 🔧 Network Automation *(work projects, code not public)*

#### 🔎 Golden Parameter Audit Framework
Python ingestion of Huawei MAE configuration exports (~30K LTE cells + 5G NR) into PostgreSQL 16 (JSONB), rule-based validation (~800K findings). Reporting evolved from Grafana / Power BI to a Next.js web front end, with Gradio for quick POCs.

#### ⚙️ Site Configuration Automation
Python + Jinja2 templates that generate 4G/5G site parameter scripts from planning data: **~2 h → ~20 min per site**, no manual typing errors.

#### 📍 RAN Field-Validation Tools *(personal)*
Python tools and a Telegram bot that, for a coordinate or cell, pull alarms, KPIs and configuration from Huawei OSS and cross-check crowdsourced coverage: one message instead of four tools. **Next:** expose them as tools for an agent.

### ☁️ LeadTide *(personal, in development, not deployed)*
Serverless CRM designed with Terraform for AWS: Lambdas behind API Gateway (JWT), RDS PostgreSQL + pgvector, SQS workers with DLQ, CI/CD with GitHub Actions + OIDC.

---

### 🎮 Game Development & Teaching

#### 🕹️ Unity Platformer MVP *(with my daughter)*
2D platformer built as a father-daughter mentoring project.
- **Learning journey:** game physics, C# programming, Unity engine
- **Tech:** Unity, C#

#### 🎯 Computer Vision Science Fair Project *(2023)*
🏆 **1st Place Winner**: real-time object detection system.
- **Tech:** Python, OpenCV, YOLO

#### 🤖 Wally, Electronics Development *(2023)*
Technical mentorship on an electronics/embedded project: architecture guidance and hardware-software integration.

---

## 🛠️ Tech Stack & Tools

<div align="center">

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)

### AI & Data Science
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

### Infra & DevOps
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare_Pages-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)

### Data & Visualization
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![PowerBI](https://img.shields.io/badge/PowerBI-F2C811?style=for-the-badge&logo=power-bi&logoColor=black)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)

### Tools
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-000000?style=for-the-badge&logo=unity&logoColor=white)
![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kali-linux&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)

### 📚 Learning now
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![LoRA/QLoRA](https://img.shields.io/badge/Fine--tuning-LoRA_%7C_QLoRA-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

</div>

---

## 📊 GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=codeviloria&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=codeviloria&layout=compact&langs_count=8&theme=tokyonight"/>

</div>

---

## 🎓 Certifications & Continuous Learning

<details>
<summary><b>🏆 Certifications (click to expand)</b></summary>

### AI & Machine Learning
- 🎓 **Post-Graduate Program in AI & ML** - University of Texas at Austin (2024)
- 📜 **Introduction to LangChain (Python)** - LangChain Academy (2026)
- 📜 **AI Agents** - Kaggle
- 📜 **Machine Learning Specialization** - IBM Cognitive Class
- 📜 **Neural Networks with TensorFlow** - Platzi
- 📜 **LangChain & Vector Databases for NLP** - Platzi
- ⏳ **LangChain Certified Agent Engineer (LCAE)** - in preparation

### Data Science & Engineering
- 📜 **Data Visualization with Python** - IBM Cognitive Class
- 📜 **ETL Process Development** - UBITS
- 📜 **Data Storytelling** - Seaborn, Geopandas, Plotly
- 📜 **Business Data Analytics Program** - UBITS

### Cloud & DevOps
- 📜 **Docker Fundamentals** - Platzi
- 📜 **PostgreSQL Database Administration** - Platzi

### Telecom Expertise
- 📜 **5G RF Planning and Design** - Award Solutions Inc (USA)
- 📜 **LTE RF Optimization** - Award Solutions Inc (USA)
- 📜 **Open RAN & vRAN Architecture** - Rakuten Mobile Training

### Other
- 📜 **Git & GitHub Collaborative Work** - UBITS & Platzi
- 📜 **Google Workspace Administration** - 2024
- 🏆 **CTF Competition Winner** - Barranquilla Cybersecurity Challenge (2024)
- 🏆 **Hackathon Participant** - Google Developer Group Barranquilla (2024)
- 🏆 **Hackathon Participant** - Kaggle (Gemma)

</details>

---

## 📝 Latest Blog Posts

<!-- BLOG-POST-LIST:START -->
- 📡 [Teaching a Local LLM to Troubleshoot 5G NSA: What the Traces Taught Me](https://signal-to-agents.pages.dev/blog/5g-nsa-agent-tool-calling-gemma4/) · [en español](https://signal-to-agents.pages.dev/blog/es/5g-nsa-agent-tool-calling-gemma4/)
<!-- BLOG-POST-LIST:END -->

---

## 🤝 Let's Connect!

I'm always interested in connecting with people working on:
- 🤖 **AI agents** for network operations
- 🌐 **Network automation** and intelligent infrastructure
- 🧠 **Local LLMs**, RAG and agent evaluation
- 👨‍🏫 **Technical education** and mentoring
- 🔐 **Cybersecurity** and ethical hacking

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gino-viloria-4690753a/)
[![Blog](https://img.shields.io/badge/Blog-Signal_to_Agents-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)](https://signal-to-agents.pages.dev)

</div>

---

## 💡 Quote I Live By

<div align="center">

> *"The best way to learn is to teach. The best way to master something is to explain it to others."*
>
> This philosophy drives everything I do, from the Family Tech Lab to writing about every agent I build.

</div>

---

## 🎯 Q4 2026 Focus

- [x] 🚀 Publish my first open-source AI agent ([5g-nsa-agent](https://github.com/codeviloria/5g-nsa-agent))
- [x] 📝 Launch my technical blog ([Signal to Agents](https://signal-to-agents.pages.dev))
- [x] 🎓 Complete *Introduction to LangChain* (LangChain Academy)
- [ ] 🎓 LangChain Certified Agent Engineer (LCAE)
- [ ] 🧪 Add LangSmith evaluation (dataset + graders) to the 5G agent
- [ ] 🧠 Add LangGraph and agent memory to the 5G agent
- [ ] 🔧 Fine-tune a small open-weight model with QLoRA (Kaggle GPU) and compare it against the base model
- [ ] 📝 Second blog post

---

## 🌟 Fun Facts

- 🏄 I combine surfing sessions with debugging sessions: both require patience and reading the waves/logs
- 🛹 Been skateboarding since before I knew what an IP address was
- 👨‍👧 My daughter can now explain buffer overflows better than some senior engineers
- 🎮 Learning game development is teaching me more about clean code than most books
- 🌊 Based in Barranquilla, Colombia, where the Caribbean meets cutting-edge tech

---

<div align="center">

### 📈 Profile Views

![](https://komarev.com/ghpvc/?username=codeviloria&color=blueviolet&style=flat-square&label=Profile+Views)

---

### ⭐ If you find my work interesting, feel free to star some repos!

**Let's build something amazing together** 🚀

</div>

---

<div align="center">
<sub>Last updated: October 2026 | Made with ❤️ and lots of ☕</sub>
</div>
