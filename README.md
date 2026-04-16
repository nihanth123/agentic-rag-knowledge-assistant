# Agentic RAG Knowledge Assistant
A multi-agent Retrieval-Augmented Generation (RAG) system built on AWS.

## Architecture
- **Amazon Bedrock** — Foundation model (Claude 3 Sonnet) for generation
- **Amazon OpenSearch** — Vector search for semantic retrieval  
- **Amazon S3** — Document knowledge base

## Agents
1. **Planner Agent** — Query decomposition
2. **Retrieval Agent** — Multi-hop semantic search
3. **Evaluation Agent** — Grounded, cited response generation

## Tech Stack
Python | Boto3 | LangChain | OpenSearch-py | Jupyter Notebook
