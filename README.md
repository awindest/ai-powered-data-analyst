### AI Powered Data Analyst

Build an AI Data Analyst with LM Studio, Qwen, Prefect and `pydantic-ai` to analyze datasets, detect anomalies and generate insights.

We will show how to build this workflow using Prefect and `pydantic.ai`. The integration demonstrates automatic retries for LLM calls, full observability of the decisions made by the agent and durable execution semantics that makes the workflow idempotent and rerunnable.

## Setup Flow

# Install LM Studio

Download from [https://lmstudio.ai](https://lmstudio.ai) and install

# Install uv

Instructions are [here](https://docs.astral.sh/uv/getting-started/installation/).

I used `brew install uv`.

# Install LLM

# Install Dependencies

`uv add pydantic-ai[prefect] pandas`

