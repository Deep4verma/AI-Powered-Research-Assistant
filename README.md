# AI-Powered Research Proposal Generator using LangGraph and RAG

## Project Overview

Developed an AI-powered research proposal generation system that automates the creation of structured research proposals from academic documents and user-provided research ideas. The system combines Retrieval-Augmented Generation (RAG), LangGraph workflows, FAISS vector search, and Large Language Models (LLMs) to generate research topics, hypotheses, literature reviews, methodologies, ethical considerations, and complete research proposals.

## Objective

Build an intelligent research assistant that:

* Extracts knowledge from PDF and DOCX research documents.
* Retrieves relevant academic context using RAG.
* Generates research topics and idea frameworks.
* Creates research questions and hypotheses.
* Produces literature reviews and methodologies.
* Identifies research significance and ethical considerations.
* Generates timelines and budget plans.
* Compiles a complete research proposal automatically.

## Tech Stack

* Python
* LangGraph
* LangChain
* Groq LLM (Llama 3 70B)
* FAISS Vector Database
* Hugging Face Embeddings
* PyPDF
* Docx2Txt
* Retrieval-Augmented Generation (RAG)

## System Architecture

### Document Processing

* Extract text from PDF documents using PyPDF.
* Extract text from Word documents using Docx2Txt.
* Split documents into chunks using RecursiveCharacterTextSplitter.

### Knowledge Retrieval

* Generate embeddings using Hugging Face Embeddings.
* Store document vectors in FAISS.
* Retrieve relevant context using RetrievalQA.

### Proposal Generation Workflow

The LangGraph workflow consists of the following stages:

1. Document Extraction
2. Context Retrieval (RAG)
3. Research Topic Generation
4. Idea Generation
5. Research Question Generation
6. Hypothesis Generation
7. Literature Review Creation
8. Methodology Design
9. Research Significance Analysis
10. Ethical Consideration Assessment
11. Timeline and Budget Planning
12. Final Proposal Compilation

## Workflow

```text
Research Documents
       │
       ▼
Document Extraction
       │
       ▼
Text Chunking
       │
       ▼
Hugging Face Embeddings
       │
       ▼
FAISS Vector Store
       │
       ▼
RAG Retrieval
       │
       ▼
LangGraph Workflow
       │
       ├── Research Topic
       ├── Research Questions
       ├── Hypothesis
       ├── Literature Review
       ├── Methodology
       ├── Significance
       ├── Ethics
       └── Timeline & Budget
       │
       ▼
Final Research Proposal
```

## Key Features

### Document Intelligence

* PDF document processing
* DOCX document processing
* Multi-document knowledge extraction

### Retrieval-Augmented Generation (RAG)

* Context-aware proposal generation
* Semantic document retrieval
* Vector-based knowledge search

### Automated Research Planning

* Research topic identification
* Research question generation
* Hypothesis formulation
* Literature review generation

### Proposal Development

* Methodology design
* Significance analysis
* Ethical assessment
* Timeline planning
* Budget estimation

## Results

* Successfully automated research proposal creation.
* Reduced manual effort required for proposal drafting.
* Generated structured and comprehensive research proposals.
* Improved proposal quality using document-grounded retrieval.
* Demonstrated end-to-end integration of LangGraph and RAG pipelines.

## Applications

* Academic Research
* PhD Proposal Development
* Grant Proposal Writing
* Literature Review Assistance
* Research Planning and Documentation
* Educational Research Projects

## Future Improvements

* Citation and reference generation.
* Integration with Google Scholar and research databases.
* Multi-agent research collaboration workflow.
* Web application deployment using Streamlit or FastAPI.
* Export proposals to PDF and DOCX formats.
* Support for multiple LLM providers.



## Author

**Deepti Verma**

GitHub: [https://github.com/Deep4verma/]

LinkedIn: [https://www.linkedin.com/in/deeptiverma1004/]
