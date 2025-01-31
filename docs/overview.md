# Spring AI
The Spring AI project aims to streamline the development of applications that incorporate artificial intelligence functionality without unnecessary complexity.

The project draws inspiration from notable Python projects, such as LangChain and LlamaIndex, but Spring AI is not a direct port of those projects. The project was founded with the belief that the next wave of Generative AI applications will not be only for Python developers but will be ubiquitous across many programming languages.

At its core, Spring AI provides abstractions that serve as the foundation for developing AI applications. These abstractions have multiple implementations, enabling easy component swapping with minimal code changes.

Spring AI provides the following features:

- Support for all major Model providers such as OpenAI, Microsoft, Amazon, Google, and Hugging Face.
- Supported Model types are Chat, Text to Image, Audio Transcription, Text to Speech, and more on the way.
- Portable API across AI providers for all models. Both synchronous and stream API options are supported. Dropping down to access model specific features is also 
  supported.
- Mapping of AI Model output to POJOs.
- Support for all major Vector Database providers such as Apache Cassandra, Azure Vector Search, Chroma, Milvus, MongoDB Atlas, Neo4j, Oracle, PostgreSQL/PGVector, 
  PineCone, Qdrant, Redis, and Weaviate.
- Portable API across Vector Store providers, including a novel SQL-like metadata filter API that is also portable.
- Function calling.
- Spring Boot Auto Configuration and Starters for AI Models and Vector Stores.
- ETL framework for Data Engineering.
  
This feature set lets you implement common use cases such as “Q&A over your documentation” or “Chat with your documentation.”

The [concepts section](./aiconcepts.md) provides a high-level overview of AI concepts and their representation in Spring AI.

The [Getting Started](./getstarted.md) section shows you how to create your first AI application. Subsequent sections delve into each component and common use cases with a code-focused approach.
