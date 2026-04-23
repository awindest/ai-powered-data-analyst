# AI Powered Data Analyst

Build an AI Data Analyst with LM Studio, Qwen, Prefect and `pydantic-ai` to analyze datasets, detect anomalies and generate insights.

We will show how to build this workflow using Prefect and `pydantic.ai`. The integration demonstrates automatic retries for LLM calls, full observability of the decisions made by the agent and durable execution semantics that makes the workflow idempotent and rerunnable.

## Setup Flow

### Install LM Studio

Download from [https://lmstudio.ai](https://lmstudio.ai) and install.

### Install LLM

Open LM Studio and click the search for model button and select an appropriate model. I used Qwen3.5 9B for my machine. Pick a model based on your VRAM (e.g., Qwen3.5 9B is a solid choice). Make sure the format is `GGUF`. Download the model. Depending on your network speed this may take a while.


### Start the Local Server

Go to the Developer panel, load your model and turn on your server. I had to flick the status switch from `Stopped` to `Running`; this may change in the future.
Your local server runs on http://localhost:1234 by default.

### Install uv

Instructions are [here](https://docs.astral.sh/uv/getting-started/installation/).

I used `brew install uv`.

### Install Pythonic Dependencies

`uv add pydantic-ai[prefect] pandas`

