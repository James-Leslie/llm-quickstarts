# llm-quickstarts
Example notebooks for doing LLM things.

Most of the notebooks are simply lifted from the [Langchain Python docs](https://python.langchain.com/docs)

# Setup

Create a new conda environment with the following command:
```bash
conda create -f environment.yml
conda activate llm
```

Create a `.env` file in the root directory with the following contents:
```
OPENAI_API_KEY=<your-openai-api-key>
LANGCHAIN_API_KEY=<your-langchain-api-key>
LANGCHAIN_TRACING_V2=true
```

