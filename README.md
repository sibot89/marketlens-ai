# MarketLens AI

An AI-powered market intelligence platform built with a hierarchical multi-agent architecture.

MarketLens uses autonomous AI agents to analyze markets, identify competitors, evaluate risks, and generate structured research reports.

---

## Overview

Market research often requires significant time and effort to collect information, analyze competitors, identify risks, and summarize findings.

MarketLens automates this process by combining:

* Large Language Models (LLMs)
* Hierarchical multi-agent orchestration
* Web-based research
* Structured data validation
* Automated report generation

The result is a market intelligence workflow that transforms a simple market topic into an evidence-based analysis report.

---

## Architecture

MarketLens uses a **hierarchical multi-agent workflow** in which the Planner Agent defines the research strategy, specialized research agents execute the analysis, and the Writer Agent synthesizes the findings into a structured report.

![MarketLens Architecture](assets/architecture.png)

### Workflow

**1. Planner Agent**

Defines the research strategy and guides the downstream research agents.

**2. Research Agents**

Two specialized agents independently investigate different aspects of the market:

* **Market Research Agent** — market size, growth trends, CAGR, competitors, and opportunities
* **Risk Research Agent** — market risks, business constraints, technology limitations, and regulatory considerations

**3. Writer Agent**

Synthesizes the research findings and produces a validated structured report.

**4. Structured Output**

The final analysis is validated using Pydantic's `MarketEvidence` schema and can be exported as a PDF report.

---

## Key Features

* ✅ Hierarchical multi-agent architecture
* ✅ Autonomous market research workflow
* ✅ Web-based information gathering
* ✅ Competitor analysis
* ✅ Risk assessment
* ✅ Structured output validation with Pydantic
* ✅ Automated PDF report generation
* ✅ Streamlit-based user interface

---

## Technology Stack

* Python
* CrewAI
* Gemini LLM
* Serper Search API
* Pydantic
* Streamlit

---

## Example Analysis

### Input

```text
AI Coding Assistants Market
```

### Generated Report

The analysis includes:

* Market overview
* Market growth and CAGR
* Competitor landscape
* Key risks
* Strategic insights

---

## Project Structure

This repository contains the public-facing portfolio materials for MarketLens.

```text
marketlens-ai/
│
├── README.md
├── LICENSE
│
├── assets/
│   └── architecture.png
│
├── screenshots/
│   └── ...
│
└── demo/
    └── ...
```

The full application source code is maintained separately.

---

## Installation

The public repository currently focuses on the project's architecture, documentation, and demonstration materials.

The full application can be run from the private development repository.

---

## Future Improvements

Potential future enhancements include:

* Retrieval-Augmented Generation (RAG) for historical reports
* Persistent analysis memory
* Additional specialized research agents
* Additional market data sources
* Advanced market forecasting

---

## Author

Built as a practical AI engineering portfolio project demonstrating:

* Multi-agent systems
* LLM application development
* AI-assisted research workflows
* Structured data validation
* Automated report generation
