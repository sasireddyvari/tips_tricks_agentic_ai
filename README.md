# Tips and Tricks for Agentic AI

A notebook-first repository of practical patterns for building agentic AI systems with Python, LangChain, LangGraph, LangSmith, tools, retrieval, and evaluation.

## What this repo focuses on

- General agentic AI patterns across domains
- Python-first implementation notes
- LangChain tool usage and structured outputs
- LangGraph workflow design
- LangSmith tracing, datasets, and evals
- Retrieval, routing, and guardrails
- Prompt and chain design tips
- Evaluation and debugging habits
- Modern tricks like streaming, human review, and fallback paths

## Included notebooks

- `notebooks/00_overview.ipynb`
- `notebooks/01_langchain_tools.ipynb`
- `notebooks/02_rag_and_retrieval.ipynb`
- `notebooks/03_agentic_workflows.ipynb`
- `notebooks/04_evals_and_guardrails.ipynb`
- `notebooks/05_langsmith_langgraph_modern_stack.ipynb`

## How to use

Open the notebooks in Jupyter or VS Code and run them top to bottom.

The examples are written to be:

- easy to adapt
- safe for offline study
- useful for production-minded demos
- reusable across many business domains

## Important note

The notebooks intentionally show where you can swap in stronger local or hosted models later.
For example, the code comments highlight how a larger model, GPU serving, or vLLM endpoint would fit into the flow.

## Good places to extend

- Add real LangSmith trace screenshots once you connect a project
- Add a notebook for prompt evaluation experiments
- Add a notebook for tool-calling and retry policies
- Add an end-to-end mini app that uses the notebook patterns
