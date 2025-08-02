# Graph RAG

## Introduction

 Graph  RAG (Retrieval Augmented Generation) is a technology that uses graph databases to store relationships between data points, replacing traditional text embedding methods like Chuck and enhancing the performance of RAG. This project is base on [Langchain](https://github.com/langchain-ai/langchain/tree/master) and [Neo4j](https://github.com/neo4j/neo4j?tab=readme-ov-file).

> Showcase:
Question is "how about the performance of llava"
![gif](res/5.gif)
Answer is "The performance of LLaVA, as mentioned in the structured data, has an overall score of 66.7 + 0.3, with a complex reasoning score of 81.4 + 0.3, a performance score of 58.8 + 0.6, and an improvement score of 49.2 + 0.8."
The reference is a knowledge graph shown below
![kg](res/graph.png)

## Features

- Create a RAG from PDFs
- Connect to Zotero to retrival PDFs
- Graph visulation through Neo4j Browser
- All data are stored locally, supporting llama.cpp and Ollama local LLM


 
