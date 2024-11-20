# Using Pinecone for Retrieval-Augmented Generation (RAG)
This repository demonstrates a simple implementation of using the Pinecone vector database to store information in the cloud. The stored data is then utilized in a Retrieval-Augmented Generation (RAG) solution, combining LangChain for orchestration and a QA retriever for querying.

Requirements
* A `.env` file with an OpenAI API token and Pinecone API token named `OPENAI_API_KEY` and `PINECONE_API_KEY` is required.  
* Also, the code assumes that the index (name) of the Pinecone DB is `pinecone-test`.
