# 🤖 Agentic AI Research Pipeline

**Tool Use · Self-Reflection · HTML Report Generation**

---

## What This Project Does

This notebook builds a **3-stage agentic AI pipeline** that can autonomously research any topic and publish a polished HTML report:

```
📥 Topic Input
     ↓
🔎 Stage 1: Tool Use       — Agent calls arXiv + web search APIs to gather real data
     ↓
🪞 Stage 2: Reflection     — Agent critiques its own draft and rewrites for quality
     ↓
📄 Stage 3: HTML Output    — Final report converted to styled, shareable HTML
```

---

## Why I Built This

I'm a **Senior Technical Product Manager** with 14+ years in AI-powered platforms, actively building hands-on AI skills to complement my product expertise.

Understanding how agentic pipelines work under the hood helps me:
- Write sharper requirements for AI features
- Have credible technical conversations with engineering teams
- Spot failure modes in multi-step AI workflows
- Design better evaluation frameworks for AI product quality

---

## Key Concepts Demonstrated

| Concept | Description |
|---------|-------------|
| **Tool Calling** | LLM invokes external APIs (arXiv, Tavily) mid-conversation |
| **Agentic Loop** | Model runs multiple turns autonomously until the task is complete |
| **Self-Reflection** | Model critiques its own output and rewrites — improving quality |
| **Structured Outputs** | JSON response format for reliable, parseable outputs |
| **Secure API Keys** | Environment variables via `.env` — never hardcoded |

---

## Tech Stack

- **Python 3.11**
- **OpenAI API** (GPT-4o-mini, tool/function calling)
- **arXiv Python API** — academic paper search
- **Tavily API** — real-time web search
- **python-dotenv** — secure API key management
- **Jupyter Notebook**

---

## Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/YOUR_USERNAME/agentic-research-pipeline.git
cd agentic-research-pipeline
```

### 2. Install dependencies
```bash
pip install openai tavily-python arxiv python-dotenv
```

### 3. Set up API keys
Create a `.env` file in the project root:
```
OPENAI_API_KEY=your_openai_key_here
TAVILY_API_KEY=your_tavily_key_here
```
> ⚠️ Never commit your `.env` file. It's already in `.gitignore`.

### 4. Run the notebook
Open `agentic_research_pipeline.ipynb` in Jupyter and run cells top to bottom.
Change `RESEARCH_TOPIC` to any topic you want to research!

---

## Sample Output

The pipeline generates a structured research report with:
- Introduction and background
- Key findings synthesized from multiple sources
- Notable studies and citations
- Implications and future directions
- Clean HTML formatting for sharing

---

## What I'd Explore Next

- Add **persistent memory** for multi-session research continuity
- Implement **parallel tool calls** for faster data gathering
- Add a **confidence scoring** layer — agent flags uncertain claims
- Integrate a **vector database** for RAG (Retrieval-Augmented Generation)
- Build a **multi-agent version** with separate researcher + fact-checker agents

---

## About Me

Senior Technical Product Manager with expertise in AI platforms, digital commerce, and enterprise SaaS. Currently deepening hands-on AI/ML skills to build more technically credible AI products.

📎 [LinkedIn](https://linkedin.com/in/YOUR_PROFILE) | 🌐 [Portfolio](YOUR_PORTFOLIO_URL)

---

*Part of my ongoing AI learning journey.*
