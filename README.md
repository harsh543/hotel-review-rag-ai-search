# Azure AI Search RAG: Hotel Finder Demo

This repository demonstrates how to leverage Retrieval-Augmented Generation (RAG) technology using Azure AI Search to perform efficient and intelligent queries on a hotel dataset.

## Overview

With holidays approaching, especially events like July 4th weekend, finding the ideal accommodation quickly becomes crucial. This project shows how to build a powerful hotel search engine using vector search technology powered by Azure AI services.

## Dataset

- **Source**: [Kaggle](https://www.kaggle.com/)
- **Contents**: Detailed hotel information, including amenities, location, guest experiences, and more.

## Technology Stack

- **Azure AI Search**: Vector search indexing for fast and relevant query results.
- **Azure Machine Learning**: Integration via Python SDK for model deployment and management.
- **Azure OpenAI Service**: LLM for intelligent query responses.
- **Azure Foundry**: Deployment environment for the intelligent AI agent.

## Setup

### 1. Clone the repository

```bash
git clone https://github.com/hhimanshu/ps-rag-azure-ai-search.git
cd ps-rag-azure-ai-search/src
```

### 2. Install required packages

```bash
pip install -r requirements.txt
```

### 3. Configuration

Update your Azure credentials and endpoints in `.env file`:

```
OPENAI_API_KEY=

SERVICE_NAME=hotels
SEARCH_ADMIN_KEY=
SEARCH_INDEX_NAME=hotel-reviews-index
```

### 4. Run the demo

Execute your query script:

```bash
python your_query_script.py
```

## Demo

Watch our complete demo showing how to query hotels using vector search technology:

[▶️ Watch Demo Video](./Demo69.mp4)

**Sample Query:**

```text
"Which hotels are the most walkable and closest to public transportation in New York?"
```

Observe the AI agent delivering accurate and relevant hotel suggestions instantly!

## Contributions

Feel free to open an issue or submit pull requests for enhancements and new features.

## License

This project is licensed under the MIT License.

