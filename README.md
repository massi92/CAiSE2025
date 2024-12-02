# CAiSE 2025
## An LLM-based Approach for Data Service Discovery

Supplementary material for CAiSE2025

Specifically, the content is uploaded following the subsequent organisation.

* Examples of analysis scenarios -  (_Analysis Scenarios - Samples_ folder)
* Examples of Atomic Data Services described through the [OpenAPI specification](https://spec.openapis.org/oas/v3.1.0) (_Data Services - Samples_ folder)
   * Adopting a partial description of services (i.e., emptying the majority of `summary` or `description` fields, especially the ones which are evocative of the functionalities provided by the services)
   * Adopting a complete description of services
* Colab Notebooks used to both interact with the LLM and to perform the quantitative assessment of the RAG module performance (_Colab Notebooks_ folder)
    * Framework used to interact with the LLM: [LangChain](https://python.langchain.com/v0.1/docs/get_started/introduction)
    * Evaluation framework for the RAG module: [Ragas](https://docs.ragas.io/en/stable/)
    * Vector Database for the Retrieval component of RAG: [ChromaDB](https://www.trychroma.com/)
    * LLMs tested for the Generation component of RAG (from [Ollama](https://ollama.com/) open source models): [granite3-dense](https://ollama.com/library/granite3-dense:8b) and [gemma2](https://ollama.com/library/gemma2:27b)
* Examples of interactions with the LLM, according to the devised prompt templates, provided as PDF files (_Excerpt of sample interactions_ folder)
