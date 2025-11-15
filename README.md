# notebooks-ai

This repository will be mostly a personal collection of notes and experiments with AI, large language models, and related technologies.

I like to learn by taking notes and actually running the code, seeing examples and have the option to change the code. Each notebook usually contains:

- Explanations and context in Markdown
- Working code examples that you can run yourself
- Visualizations and print outputs to illustrate results

This makes it easier for me to study concepts and patterns, and hopefully it can be useful for others who want concrete, runnable examples alongside the theory.

## Notebooks
| Notebook | Description |
|---------|-------------|
| [short_term_memory.ipynb](notebooks/short_term_memory.ipynb) | InMemorySaver, checkpoints, thread_id with LangGraph |
| [tools.ipynb](notebooks/tools.ipynb) | Introduction to tools with LangChain. 

### How to use
1. Clone the repository
2. Install dependencies with `uv sync` (or `poetry install` if using poetry)
3. Create a `.env` file in the project root and add any necessary environment variables. Each notebook will mention which variables are needed to run the code.
