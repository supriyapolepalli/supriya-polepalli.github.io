# Supriya Polepalli | Portfolio

Personal portfolio of Supriya Polepalli, a full stack engineer who builds web applications, search systems, streaming data pipelines and LLM agents.

**Live site:** https://supriya-polepalli.github.io

## About this site

A fast, single page portfolio written in plain HTML, CSS and a small amount of JavaScript. There is no framework, no build step and no external dependencies, so it loads instantly and is easy to maintain.

## Highlights

* **Work history** across Glix, SAP and Tata Consultancy Services, with measurable results for each role
* **Four AI projects**
  * Enterprise Agentic Search Copilot: hybrid search, reranking and LLM judge evaluation
  * Distributed AI Analytics and Text to SQL Agents: schema grounding and self correcting retries
  * MCP Multi Agent Workflow and Tool Orchestrator: LangGraph, FastAPI, approval gates and token budgets
  * Autonomous Web Extraction and Semantic Discovery Engine: Next.js, Elasticsearch and LLM extraction
* **Interactive replay** of a guarded multi agent run, showing planning, tool calls, budget checks and human approval
* **Responsive layout** with a sticky sidebar on desktop and a stacked layout on phones
* **Automatic light and dark mode** that follows the visitor's device settings

## Tech

* HTML5 and CSS3 (grid, custom properties, media queries)
* Vanilla JavaScript for the section highlighting and the agent replay
* Hosted on GitHub Pages

## Project structure

```
supriya-polepalli.github.io/
  index.html     the entire site
  README.md      this file
```

## Run locally

```
git clone https://github.com/supriya-polepalli/supriya-polepalli.github.io.git
cd supriya-polepalli.github.io
python3 -m http.server 8000
```

Then open http://localhost:8000 in your browser. You can also open `index.html` directly.

## Deploy

The site is served by GitHub Pages from the `main` branch.

1. Open the repository Settings, then Pages.
2. Under Build and deployment, choose Deploy from a branch.
3. Select `main` and `/ (root)`, then Save.
4. Every commit to `main` updates the live site within a minute or two.

## Customize

* Colors are set once at the top of `index.html` in the `:root` block (`--blue`, `--hi`, `--bg`, `--ink`)
* Work history lives in the `#work` section
* Projects live in the `#project` section
* Skills live in the `#stack` section

## Contact

* Email: priyapolepalli30@gmail.com
* LinkedIn: https://linkedin.com/in/supriyapolepalli
* GitHub: https://github.com/supriya-polepalli

## License

The code of this site is free to learn from. The text, résumé content and personal details belong to Supriya Polepalli and may not be reused.
