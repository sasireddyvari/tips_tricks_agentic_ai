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
- Full-stack AI capability patterns across text, tools, memory, multimodal, and orchestration
- Safety testing, structured outputs, and model selection patterns
- Observability and adaptation patterns with Grafana and PEFT
- MLOps patterns with MLflow and Airflow

## Included notebooks

- `notebooks/00_overview.ipynb`
- `notebooks/01_langchain_tools.ipynb`
- `notebooks/02_rag_and_retrieval.ipynb`
- `notebooks/03_agentic_workflows.ipynb`
- `notebooks/04_evals_and_guardrails.ipynb`
- `notebooks/05_langsmith_langgraph_modern_stack.ipynb`
- `notebooks/06_ai_capabilities_playbook.ipynb`
- `notebooks/07_prompt_injection_and_safety.ipynb`
- `notebooks/08_structured_outputs_and_tools.ipynb`
- `notebooks/09_model_selection_and_comparison.ipynb`
- `notebooks/10_grafana_and_peft_playbook.ipynb`
- `notebooks/11_mlops_mlflow_airflow_playbook.ipynb`

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
- Add a multimodal notebook for PDF, image, or audio workflows
- Add a notebook for agent memory and state management
- Add a notebook for prompt injection red-team tests
- Add a notebook for comparing local, hosted, and GPU-backed models
- Add a notebook for Grafana observability and PEFT fine-tuning workflows
- Add a notebook for MLOps experiment tracking and orchestration
