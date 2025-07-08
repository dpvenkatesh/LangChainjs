# LangChain.js

LangChain Framework if an AI toolChain for Javascript developers.

## Benefits
* Use multiple LLMs through the same interface
* Engineer promps with prompt templates
* Provides output parsers to Transform and Translate the LLM reponses
* Provived utils for RAGs, Memory Management, Ebeddings, Tool Calling, etc.

## Architecture
![LangChain.js Architecture](assets/images/LangChain.js%20Architecture.png)

#### @langchain/core
Core package providing essential abstractions, types, and utilities for building AI applications with LangChain.js. It includes foundational components such as chains, tools, memory, and schema definitions, enabling seamless integration and extensibility.

#### @langchain/community
Community-driven package that extends LangChain.js with integrations, connectors, and tools contributed by the open-source community. It offers additional modules for connecting to various data sources, APIs, and third-party services, accelerating development and experimentation.

Contains integrations for different LLMs like `Vectore Stores`, `RAG retrivers` etc..

### @lanchain/[partner]
Integration for major LLM providers like Anthropic, OpenAI, Google AI are packaged separately as partner packages

### LangChain
Consists of chains, agents and retriever strategies that make up the architecture.

### LangGraph
Is a specialized agent building framework. It is a library for building statefull multifactor applications with LLMs. Can be used along with LangChain to build autonomous agents with defined workflows.

### LangSmith
Is an AI Observasbility Tool for monitoring the LLM applications. This can also be used to monitor the inner workings for perfomance evaluations.

Use of `LangGraph` and `LangSmith` are optional.

