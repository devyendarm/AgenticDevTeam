# AgenticDevTeam

The AgenticDevTeam is a standalone, open-source boilerplate for orchestrating multi-agent AI pipelines. 

## Features
- **Model-Agnostic**: Effortlessly works across Claude, OpenAI, and Antigravity.
- **Dynamic Configuration**: Fully driven by `.ai/config.yaml` to adapt to any tech stack.
- **Pipeline Orchestration**: Define complex graphs and steps via `.ai/workflow.yaml`.
- **Pre-defined Roles**: Contains core personas (Product Manager, Analyst, Evaluator, Builder, Reviewer) configured via `.ai/roles/`.
- **Generic Tools**: Uses extensible CLI stubs for standard tasks like memory and RAG in `.ai/tools/`.

## Getting Started

1. Clone the repository.
2. Edit `.ai/config.yaml` to define your stack and models.
3. Update `.ai/workflow.yaml` to match your desired pipeline structure.
4. Execute the framework CLI to launch the pipeline!

## CI/CD Integration
Automatically trigger the framework in pull requests using the included GitHub Actions workflow (`.github/workflows/agentic-pr.yml`).
