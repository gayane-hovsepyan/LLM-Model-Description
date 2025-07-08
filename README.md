# README

## Internship Task: Chatbot Log Analysis & Optimization Proposal

### Overview
This task involves analyzing `logs.json` to identify key problems affecting chatbot performance and proposing an improvement strategy. The deliverable includes root cause analysis, quantitative trade-off analysis, and a recommendation to the product manager.

### Files
- `analyze_json.ipynb`: Jupyter notebook containing detailed analysis of logs, evidence extraction, and cost calculations.
- `Untitled document.pdf`: Written report summarizing findings, hypotheses, and final recommendation.

### Key Findings
1. **Root Cause Analysis**
   - **Problem 1**: High response latency due to large context processing in generation (especially from PDFs).
   - **Problem 2**: Outdated and inaccurate information caused by retrieval from stale PDFs and Confluence data.

2. **Trade-off Analysis**
   - Compared adding a Cohere Re-ranker (Option A) vs increasing retrieval context size (Option B).
   - Estimated costs and latency impacts for each option.

### Recommendation
- **Option A (Re-ranker)** is recommended, due to:
  - Lower additional cost ($100/month vs $720/month).
  - Higher precision and better relevance.
  - More predictable latency impact.

### How to Run
- Open `analyze_json.ipynb` in Jupyter or VSCode.
- Execute cells step-by-step to view log analysis, calculations, and supporting charts.

### Author
[Your Name]
