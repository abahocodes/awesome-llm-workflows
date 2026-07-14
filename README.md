# Awesome LLM Workflows [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

> Tools, frameworks, and resources for building, orchestrating, and shipping LLM workflows: RAG pipelines, AI agents, chatbots, and multi-step AI automation.

Maintained by the team behind [LLMGraph](https://llmgraph.ai/?utm_source=github&utm_medium=awesome-llm-workflows&utm_content=header), a no-code visual builder for LLM workflows.

**Add your tool in under two minutes:** [edit the README in your browser](https://github.com/abahocodes/awesome-llm-workflows/edit/main/README.md) (GitHub opens the PR for you) or [fill in the suggestion form](https://github.com/abahocodes/awesome-llm-workflows/issues/new?template=suggest-a-tool.yml) and we will add it for you. PRs reviewed within 48 hours. See [CONTRIBUTING.md](CONTRIBUTING.md).

## Contents

- [Visual Workflow Builders](#visual-workflow-builders)
- [Code-First Frameworks](#code-first-frameworks)
- [Agent Frameworks](#agent-frameworks)
- [RAG & Retrieval](#rag--retrieval)
- [Observability & Evaluation](#observability--evaluation)
- [Serving & Inference](#serving--inference)
- [Learning Resources](#learning-resources)

## Visual Workflow Builders

*Design LLM pipelines on a canvas instead of in code.*

- [LLMGraph](https://llmgraph.ai/?utm_source=github&utm_medium=awesome-llm-workflows&utm_content=entry) - No-code visual builder for LLM workflows; build on a canvas or by chat, deploy to a REST API + embeddable chat widget in one click. *(Maintained by us.)*
- [Langflow](https://github.com/langflow-ai/langflow) - Visual IDE for LangChain-style flows with drag-and-drop components.
- [Flowise](https://github.com/FlowiseAI/Flowise) - Open-source drag-and-drop UI for building LLM chains and agents.
- [Dify](https://github.com/langgenius/dify) - LLM app development platform with visual orchestration, RAG, and agent capabilities.
- [n8n](https://github.com/n8n-io/n8n) - General workflow automation with strong AI/LLM nodes; self-hostable.
- [Rivet](https://github.com/Ironclad/rivet) - Visual programming environment for LLM agents from Ironclad, runs as a desktop app.
- [PySpur](https://github.com/PySpur-Dev/pyspur) - Python-based visual builder for AI agent workflows.
- [ComfyUI](https://github.com/comfyanonymous/ComfyUI) - Node-graph interface, originally for diffusion models, increasingly used for multi-model pipelines.

## Code-First Frameworks

*Build workflows in code with batteries included.*

- [LangChain](https://github.com/langchain-ai/langchain) - The most widely used framework for composing LLM calls, tools, and memory.
- [LangGraph](https://github.com/langchain-ai/langgraph) - Graph-structured, stateful orchestration for agents from the LangChain team.
- [LlamaIndex](https://github.com/run-llama/llama_index) - Data framework focused on connecting LLMs to your data (RAG).
- [Haystack](https://github.com/deepset-ai/haystack) - Production-oriented pipelines for RAG, search, and agents from deepset.
- [DSPy](https://github.com/stanfordnlp/dspy) - Programming model that optimizes prompts/weights instead of hand-tuning them.
- [Semantic Kernel](https://github.com/microsoft/semantic-kernel) - Microsoft's SDK for integrating LLMs into apps with plugins and planners.
- [Mastra](https://github.com/mastra-ai/mastra) - TypeScript agent/workflow framework with durable execution.

## Agent Frameworks

*Multi-step, tool-using, autonomous or semi-autonomous systems.*

- [CrewAI](https://github.com/crewAIInc/crewAI) - Role-based multi-agent orchestration.
- [AutoGen](https://github.com/microsoft/autogen) - Microsoft's framework for multi-agent conversation and collaboration.
- [OpenAI Agents SDK](https://github.com/openai/openai-agents-python) - OpenAI's first-party agent orchestration SDK.
- [smolagents](https://github.com/huggingface/smolagents) - Hugging Face's minimal agent library with code-execution agents.
- [Agno](https://github.com/agno-agi/agno) - Lightweight framework for building agents with memory, knowledge, and tools.

## RAG & Retrieval

- [Chroma](https://github.com/chroma-core/chroma) - Open-source embedding database, easy local start.
- [Qdrant](https://github.com/qdrant/qdrant) - Vector search engine in Rust with strong filtering.
- [Weaviate](https://github.com/weaviate/weaviate) - Vector database with hybrid search and modules.
- [pgvector](https://github.com/pgvector/pgvector) - Vector similarity inside Postgres; the boring, excellent choice.
- [Milvus](https://github.com/milvus-io/milvus) - Scalable vector database for large deployments.
- [Crawl4AI](https://github.com/unclecode/crawl4ai) - Web crawling built for feeding content to LLMs.
- [Unstructured](https://github.com/Unstructured-IO/unstructured) - Document parsing/ETL for RAG ingestion.

## Observability & Evaluation

- [Langfuse](https://github.com/langfuse/langfuse) - Open-source LLM tracing, metrics, and prompt management.
- [Phoenix](https://github.com/Arize-ai/phoenix) - Open-source LLM observability and evals from Arize.
- [promptfoo](https://github.com/promptfoo/promptfoo) - Test and red-team prompts/workflows like unit tests.
- [Ragas](https://github.com/explodinggradients/ragas) - Evaluation metrics purpose-built for RAG pipelines.
- [DeepEval](https://github.com/confident-ai/deepeval) - Unit-testing framework for LLM outputs.
- [Helicone](https://github.com/Helicone/helicone) - Proxy-based LLM observability and cost tracking.

## Serving & Inference

- [vLLM](https://github.com/vllm-project/vllm) - High-throughput LLM serving with PagedAttention.
- [Ollama](https://github.com/ollama/ollama) - Run open models locally with one command.
- [llama.cpp](https://github.com/ggml-org/llama.cpp) - CPU/GPU inference for GGUF models everywhere.
- [LiteLLM](https://github.com/BerriAI/litellm) - One API for 100+ LLM providers, with proxy/gateway mode.
- [OpenRouter](https://openrouter.ai) - Hosted multi-provider LLM gateway.

## Learning Resources

- [Prompt Engineering Guide](https://github.com/dair-ai/Prompt-Engineering-Guide) - The standard reference for prompting techniques.
- [What Are Embeddings](https://vickiboykis.com/what_are_embeddings/) - Free book by Vicki Boykis; the best intro to embeddings.
- [LLM Course](https://github.com/mlabonne/llm-course) - Roadmaps + notebooks covering the full LLM stack.
- [Building LLM Applications for Production](https://huyenchip.com/2023/04/11/llm-engineering.html) - Chip Huyen's foundational essay on LLM engineering.
- [How to Add an AI Customer Support Assistant Without Code](https://llmgraph.ai/blog/no-code-customer-support-assistant?utm_source=github&utm_medium=awesome-llm-workflows&utm_content=learning) - Practical walkthrough of a no-code RAG support bot.

## Contributing

Contributions welcome, and easy: [edit the README in your browser](https://github.com/abahocodes/awesome-llm-workflows/edit/main/README.md) or [suggest a tool via the form](https://github.com/abahocodes/awesome-llm-workflows/issues/new?template=suggest-a-tool.yml). One tool per PR, one-line factual description. Full guidelines in [CONTRIBUTING.md](CONTRIBUTING.md).

If this list is useful to you, a star helps others find it.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
