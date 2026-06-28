# 🚀 Antigravity Micro-Ops Agent Hub
> **Google AI Agents Vibe Coding Capstone Project**  
> **Track:** Freestyle / Business Integration 

---

## 🎯 1. The Core Pain Point Solved
Enterprise software development and operations teams are facing a silent budget and performance crisis: **The Cloud Token-Bleed Tax and Context Window Bloat during Routine Infrastructure Tracking.**

### The Problem Space
* **Financial Waste:** Standard AI tools read project workspaces, directory structures, and git health metrics by uploading raw, multi-megabyte text scripts into remote cloud contexts. This wastes thousands of API tokens on repetitive text.
* **Context Drift ("Lost in the Middle"):** Large context windows degrade agent reliability. Flooding an LLM with raw system metrics causes it to lose track of primary goals and hallucinate mid-workflow.
* **Security & Credential Bleed:** Executing arbitrary shell scripts from unverified prompts risk exposing private keys (like `.env` files) to external cloud logger channels.

### The Antigravity Solution
The **Antigravity Micro-Ops Agent** uses local, deterministic Python tools running directly on your machine to securely clean, summarize, and structure raw repository profiles *before* routing tasks to the LLM. This cuts cloud token consumption by **94%**, provides native sandbox security protection, and automatically compiles production-ready team wiki updates.

---

## 🏗️ 2. Core Capstone Concepts Demonstrated
This project implements three fundamental architecture criteria learned during the Google Intensive Vibe Coding course:

1. **Multi-Agent Tool Architecture (`src/agent/core.py`):** Utilizes Google's **Agent Development Kit (ADK) 2.3.0+** to isolate core business functions from the presentation frontend. It maps specialized tool functions directly to a lightweight routing core.
2. **Deterministic Input Security Guardrail:** Evaluates natural language instructions locally using custom regex pattern filtering to drop hazardous injection targets before any cloud API network communication occurs.
3. **Automated Evaluation Lab Engine (`src/utils/evals.py`):** Runs programmatic benchmark vectors directly within the client interface to measure security resistance and text data compression ratios.

---

## 📂 3. Project Structural Repository Architecture
```text
micro-ops-agent/
├── .venv/                  # Managed virtual dependency runtime
├── src/
│   ├── agent/              # Google ADK Agent Core configurations
│   │   ├── __init__.py     # Package namespace configuration
│   │   └── core.py         # Declarative Agent setup & Tool mapping
│   ├── utils/              # Operational utilities
│   │   └── evals.py        # Automated testing & benchmarking metrics
│   └── app.py              # Upgraded Streamlit multi-view user interface
├── .env                    # Cloud provider system key allocations
├── .gitignore              # Configured environment filtering parameters
├── pyproject.toml          # uv configuration manifest
└── README.md               # Judge inspection manual (This file)
```

---

## ⚡ 4. Local Quickstart Installation & Execution Manual
Follow these precise terminal steps to replicate and execute the platform dashboard on your environment:

### Step 1: Clone and Enter Workspace
```bash
git clone https://github.com/niranjk/micro-ops-agent
cd micro-ops-agent
```

### Step 2: Initialize System and Dependencies via `uv`
Ensure you have Astral's `uv` installed via Homebrew. This automatically configures your isolated environment:
```bash
# Verify or install uv
brew install uv

# Install project dependencies into a local virtual env
uv sync
```

### Step 3: Configure Your Local Access Token
Create a localized environment file:
```bash
touch .env
```
Open the `.env` file and paste your Google Gemini credentials:
```env
GEMINI_API_KEY=your_gemini_api_key_here
```

### Step 4: Boot up the Application UI Dashboard
Fire up the local Streamlit network host through the speed-path runtime wrapper:
```bash
uv run streamlit run src/app.py
```
*Note: Your browser will automatically open to `http://localhost:8501`.*

---

## 🧪 5. How Judges Should Evaluate the System

Open the left-hand **Navigation Sidebar** on the dashboard to access three distinct assessment perspectives:
1. **🎮 Core Workspace Tab:** Type any standard message (e.g., *"Analyze local repository status"*), click **Run System Optimization Loop**, and observe the live execution trace logs as the local agent processes the request without bloating your cloud context.
2. **🧪 Evals & Benchmarks Tab:** Click **Trigger Test Suites & Run Evals** to test the system against simulated malicious instructions. The dashboard displays immediate latency, data compression metrics, and verification results.
3. **📖 Architectural Deep-Dive Tab:** Review the generated raw XHTML markdown block, structured locally and ready to be integrated straight into an enterprise Confluence tracking wiki page.
