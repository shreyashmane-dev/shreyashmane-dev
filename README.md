
<!-- ============================================================ -->
<!--   SHREYASH MANE — GitHub Profile README                      -->
<!-- ============================================================ -->

<div align="center">

<img width="100%" alt="Shreyash Mane — Software Developer and CSE Student" src="https://capsule-render.vercel.app/api?type=venom&height=280&color=0:FF0080,50:7928CA,100:0f0c29&text=SHREYASH%20MANE&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=AI%20Systems%20%7C%20Full-Stack%20Development%20%7C%20CSE%20Student&descAlignY=58&descSize=17" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=2800&pause=800&color=FF0080&center=true&vCenter=true&width=850&lines=%3E+building+systems%2C+not+just+interfaces...;%3E+exploring+AI+and+machine+learning...;%3E+engineering+search+and+local+AI+tools...;%3E+turning+ideas+into+working+software...;%3E+status%3A+always+building" alt="Building systems, exploring AI, engineering software" />

<br />

<img src="https://komarev.com/ghpvc/?username=shreyashmane-dev&style=for-the-badge&color=FF0080&label=PROFILE+VIEWS" alt="GitHub profile views" />
<img src="https://img.shields.io/github/followers/shreyashmane-dev?label=FOLLOWERS&style=for-the-badge&color=7928CA&logo=github" alt="GitHub followers" />
<img src="https://img.shields.io/badge/OPEN_TO-COLLABORATION-00C853?style=for-the-badge&logo=statuspage&logoColor=white" alt="Open to collaboration" />

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.gif" width="100%" alt="Decorative rainbow divider" />

## About Me

```js
const shreyash = {
  role: "Computer Science & Engineering Student",
  focus: [
    "AI Systems & Machine Learning",
    "Full-Stack Engineering",
    "Developer Tools & Automation",
    "Search and Data Infrastructure"
  ],
  technologies: [
    "Python", "TypeScript", "React", "Node.js",
    "FastAPI", "PyTorch", "PostgreSQL", "Firebase"
  ],
  philosophy: "Understand the system. Build it. Test it. Improve it.",
  currentGoal: "Build useful software with strong engineering foundations",
  funFact: "Debugging is better with music on 🎧"
};

console.log(shreyash.currentGoal);
```

I'm a Computer Science and Engineering student interested in building software that goes beyond basic interfaces. I work across AI experimentation, full-stack applications, developer tooling, search infrastructure, and local-first software.

I learn by building: designing the architecture, implementing the core systems, testing edge cases, and documenting what actually works. I value practical engineering, honest evaluation, and projects that solve real problems.

## Engineering Interests

- **AI & Machine Learning:** Transformer models, model evaluation, explainability, local inference, and AI-assisted workflows.
- **Backend & Infrastructure:** APIs, data pipelines, indexing, persistence, authentication, and service architecture.
- **Full-Stack Development:** TypeScript, React, application architecture, responsive interfaces, and cross-platform products.
- **Developer Productivity:** Windows utilities, automation, command-line tools, and software quality workflows.

---

## Featured Engineering Projects

These projects are selected for their technical scope, engineering depth, and the systems they demonstrate. Experimental work is identified as experimental rather than presented as a finished production product.

<details open>
<summary><b>🔎 OM Search — Independent Web Search Engine</b></summary>

An independent web search engine project built around its own crawling, ingestion, indexing, and retrieval pipeline. The system includes a persistent URL frontier, asynchronous crawler, robots.txt policy handling, network-safety checks against SSRF, HTML content extraction, content deduplication, BM25 retrieval, and a multi-feature ranking pipeline with link-authority signals.

**Engineering focus**
- Web crawling, URL normalization, and persistent crawl-state management.
- Robots.txt compliance, per-host politeness, redirect checks, and network safety.
- Document extraction, fingerprinting, and incremental indexing.
- OpenSearch BM25 retrieval, query processing, ranking features, and PageRank-oriented authority signals.
- Information retrieval evaluation using metrics such as MRR, MAP, and NDCG.

**Technologies:** `Python` `FastAPI` `OpenSearch` `PostgreSQL` `SQLite` `React` `TypeScript` `Docker`

[**View Repository →**](https://github.com/shreyashmane-dev/OmSearch)

</details>

<details open>
<summary><b>🧩 Nexyris Local — Portable Local AI Studio</b></summary>

A portable desktop AI environment designed to keep local models, conversations, projects, and application data together on removable storage. Nexyris integrates a local inference runtime, model discovery and management, hardware detection, a terminal workspace, persistent SQLite storage, and a Model Context Protocol (MCP) server.

**Engineering focus**
- Local GGUF model discovery and runtime management through llama.cpp and compatible engines.
- Portable application paths and removable-drive-aware storage layout.
- Model catalog, resumable downloads, hardware inspection, and runtime lifecycle handling.
- Local conversation and project persistence using SQLite.
- MCP tools, resources, and prompts for integration with compatible AI clients.
- Automated tests covering portability, storage, model parsing, downloads, runtime lifecycle, and MCP behavior.

**Technologies:** `TypeScript` `React` `Node.js` `llama.cpp` `GGUF` `SQLite` `MCP`

[**View Repository →**](https://github.com/shreyashmane-dev/Nexyris)

</details>

<details open>
<summary><b>🧠 VEYRA — Experimental Language Model & Personal AI</b></summary>

An experimental personal AI and language-model research project. VEYRA includes a from-scratch decoder-only Transformer implementation, a custom tokenization pipeline, training utilities, inference and generation code, checkpoint management, and a terminal-based assistant with persistent memory.

**Engineering focus**
- Decoder-only Transformer architecture implemented in PyTorch.
- Rotary positional embeddings (RoPE), RMSNorm, causal attention, optional grouped-query attention, and SwiGLU feed-forward layers.
- Tokenizer, dataset preparation, training configuration, checkpointing, and inference pipeline.
- Training and evaluation workflows designed for constrained hardware.
- SQLite-backed assistant memory and a modular language-engine interface.

**Technologies:** `Python` `PyTorch` `Transformer` `RoPE` `RMSNorm` `GQA` `SQLite`

**Project status:** Research prototype. The model architecture and training infrastructure are implemented, but the current tiny checkpoint is not evidence of a generally capable language model. Training quality and evaluation remain active work.

[**View Repository →**](https://github.com/shreyashmane-dev/Veyra)

</details>

<details>
<summary><b>⚖️ XAI Governance — Model Trust & Explainability Platform</b></summary>

A platform for inspecting machine-learning models and datasets, evaluating predictive performance, generating explainability outputs, monitoring model drift, and organizing governance and audit reports.

**Engineering focus**
- Model and dataset ingestion with compatibility checks.
- Classification and regression evaluation metrics.
- SHAP-based explainability and feature analysis.
- Model drift monitoring, governance scoring, and reporting workflows.
- Authentication, tenant-aware records, and audit events.

**Technologies:** `Python` `FastAPI` `React` `MongoDB` `Scikit-learn` `SHAP` `Firebase`

**Project status:** Prototype. Model-file handling and security hardening are ongoing; uploaded model artifacts must be treated as untrusted input.

[**View Repository →**](https://github.com/shreyashmane-dev/Xai-governance-platform_M)

</details>

<details>
<summary><b>🛠️ AnoS — Windows Developer Tools Suite</b></summary>

A collection of standalone Windows developer utilities under the AnoS identity. The suite focuses on reducing repetitive development setup and maintenance work through command-line tools, launchers, a searchable web catalog, and validation scripts.

**Included utility areas**
- Development environment setup and system diagnostics.
- Project scaffolding and GitHub workflow helpers.
- Package management and workspace organization.
- Build-artifact cleanup and local HTTP serving.
- Key generation and system/network utilities.

The repository includes standalone Batch tools, PowerShell launchers, a browser-based catalog, tool metadata, hash-generation scripts, and validation workflows.

**Technologies:** `Windows Batch` `PowerShell` `JavaScript` `HTML` `CSS` `Automation`

[**View Repository →**](https://github.com/shreyashmane-dev/dev-tools-suite)

</details>

<details>
<summary><b>🧾 OpenPOS — Cross-Platform Point of Sale</b></summary>

A point-of-sale project aimed at bringing retail operations into a unified Windows and Android workflow. The product direction covers everyday sales operations, order handling, and inventory-oriented business workflows.

**Technologies:** `Windows` `Android` `Application Development`

**Repository:** The public repository link is not included yet.

</details>

<div align="center">

<a href="https://github.com/shreyashmane-dev?tab=repositories">
  <img src="https://img.shields.io/badge/EXPLORE_ALL_REPOSITORIES-181717?style=for-the-badge&logo=github&logoColor=white" alt="Explore all GitHub repositories" />
</a>

</div>

---

## More Projects

A selection of other projects exploring applied AI, security, productivity, and real-world application development.

| Project | Focus | Repository |
|---|---|---|
| **Drishti AI** | Retinal image analysis, model training, and visual explainability research | [GitHub](https://github.com/shreyashmane-dev/Drishti-AI) |
| **KisanDirect** | Farmer-to-buyer agricultural marketplace prototype with AI-assisted workflows | [GitHub](https://github.com/shreyashmane-dev/krushi-direct) |
| **SecureCode AI** | Static code analysis, security findings, and code-quality reporting | [GitHub](https://github.com/shreyashmane-dev/Secure-codeb-AI) |
| **First Aid Hospital** | Emergency assistance platform with triage workflows and hospital discovery | [GitHub](https://github.com/shreyashmane-dev/First-Aid) |
| **WindCast AI** | Machine-learning experiments for short-term wind-power forecasting | [GitHub](https://github.com/shreyashmane-dev/WindCast-AI) |
| **Aivora** | Personal expense tracking and finance management application | [Web](https://github.com/shreyashmane-dev/aivora-web) · [Android](https://github.com/shreyashmane-dev/aivora-capacitor-app) |

---

## Tech Stack

<div align="center">

**Languages**

<img src="https://skillicons.dev/icons?i=python,ts,js,java,c,cpp,bash" alt="Python, TypeScript, JavaScript, Java, C, C++ and Bash" />

**Frontend & Application Development**

<img src="https://skillicons.dev/icons?i=html,css,react,vite,nextjs,tailwind" alt="HTML, CSS, React, Vite, Next.js and Tailwind CSS" />

**Backend, Data & AI**

<img src="https://skillicons.dev/icons?i=nodejs,fastapi,postgres,mongodb,firebase,sqlite,pytorch" alt="Node.js, FastAPI, PostgreSQL, MongoDB, Firebase, SQLite and PyTorch" />

**Tools & Platforms**

<img src="https://skillicons.dev/icons?i=git,github,vscode,figma,docker,linux,vercel,postman" alt="Git, GitHub, VS Code, Figma, Docker, Linux, Vercel and Postman" />

</div>

---

## GitHub Statistics

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=shreyashmane-dev&show_icons=true&theme=radical&hide_border=true&bg_color=0D1117&title_color=FF0080&icon_color=7928CA&text_color=c9d1d9&rank_icon=github" alt="Shreyash's GitHub statistics" />
<img height="165" src="https://github-readme-streak-stats.herokuapp.com/?user=shreyashmane-dev&theme=radical&hide_border=true&background=0D1117&ring=FF0080&fire=7928CA&currStreakLabel=FF0080" alt="GitHub contribution streak" />

<img width="60%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=shreyashmane-dev&layout=compact&theme=radical&hide_border=true&bg_color=0D1117&title_color=FF0080&text_color=c9d1d9" alt="Most used programming languages on GitHub" />

</div>

<details>
<summary><b>Stats card troubleshooting</b></summary>

GitHub statistics cards are images served by external services. They can occasionally be unavailable or rate-limited.

1. Refresh the profile page after some time.
2. Confirm the username in each image URL is `shreyashmane-dev`.
3. For greater reliability, deploy your own instance of [GitHub Readme Stats](https://github.com/anuraghazra/github-readme-stats) and update the image URLs to use that instance.

</details>

---

## Contribution Activity

<div align="center">

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=shreyashmane-dev&theme=react-dark&hide_border=true&bg_color=0d1117&color=FF0080&line=7928CA&point=ffffff" alt="GitHub contribution activity graph" />

### 🏆 GitHub Trophies

<img src="https://github-profile-trophy.vercel.app/?username=shreyashmane-dev&theme=radical&no-frame=true&row=1&column=7" alt="GitHub profile trophies" />

### 🐍 Contribution Snake

<img src="https://raw.githubusercontent.com/shreyashmane-dev/shreyashmane-dev/output/github-contribution-grid-snake-dark.svg" alt="GitHub contribution snake animation" />

</div>

---

## Currently Learning & Improving

- Designing and evaluating machine-learning systems rather than relying only on model APIs.
- Building reliable backend services, data pipelines, and search infrastructure.
- Improving software testing, security, observability, and deployment practices.
- Exploring local AI inference, model tooling, and agent interoperability.

---

## Let's Connect

<div align="center">

<a href="https://www.linkedin.com/in/shreyash-mane-7675a4385">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
<a href="mailto:shreyashmane649@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
</a>
<a href="https://github.com/shreyashmane-dev">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
</a>

</div>

---

## A Note on Building

```text
Learn the fundamentals.
Build the system.
Test the assumptions.
Measure what matters.
Fix what breaks.
Repeat.
```

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.gif" width="100%" alt="Decorative rainbow divider" />

<div align="center">

<img width="100%" alt="Shreyash Mane — Keep building" src="https://capsule-render.vercel.app/api?type=venom&color=0:0f0c29,50:7928CA,100:FF0080&height=140&section=footer" />

</div>
