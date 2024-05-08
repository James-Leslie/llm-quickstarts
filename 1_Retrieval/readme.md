# Retrieval
> Source: [python.langchain.com/docs/modules/data_connection](https://python.langchain.com/docs/modules/data_connection/)

Many LLM applications require user-specific data that is not part of the model's training set. The primary way of accomplishing this is through Retrieval Augmented Generation (RAG). In this process, external data is _retrieved_ and then passed to the LLM when doing the generation step.

LangChain provides all the building blocks for RAG applications - from simple to complex. This section of the documentation covers everything related to the _retrieval_ step - e.g. the fetching of the data. Although this sounds simple, it can be subtly complex. This encompasses several key modules.

![Retrieval](https://python.langchain.com/assets/images/data_connection-95ff2033a8faa5f3ba41376c0f6dd32a.jpg)