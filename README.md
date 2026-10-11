@@ -0,0 +1,314 @@
🤖 Generative AI Tasks & Practical Implementations

Welcome to Gen-AI Tasks, a collection of practical implementations and learning exercises covering Generative AI, NLP, Embeddings, Vector Databases, ChromaDB, Cosine Similarity, and Retrieval-Augmented Generation (RAG).

This repository documents hands-on learning activities, practical implementations, experiments, and supporting assessment documents developed while exploring modern Generative AI technologies.

👩‍💻 Author

RANGANI PRIYANKA

Registration Number: 99230040055
Email: 99230040055@klu.ac.in
Department: CSE – AI & ML
Institution: Kalasalingam Academy of Research and Education

📌 About This Repository

The objective of this repository is to demonstrate practical understanding of important Generative AI and NLP concepts, progressing from fundamental text representations to advanced retrieval-based AI systems.

The repository covers:

Word Embeddings
Hugging Face Embeddings
Cosine Similarity
Vector Databases
ChromaDB
CRUD Operations
Document Loading
Document Chunking
Retrieval-Augmented Generation (RAG)
AI-powered Retrieval Systems
Generative AI Practical Assessments
🧠 Topics Covered
1. Word Embeddings

Exploration of how words and text can be represented as numerical vectors.

Key concepts:

Text representation
Vector representations
Semantic relationships
Word-level embeddings
Similarity between vectors

Word embeddings form the foundation for many modern NLP and Generative AI applications.

2. Hugging Face Embeddings

Practical exploration of embedding models using the Hugging Face ecosystem.

The implementation covers the process of converting text into meaningful numerical vector representations.

Concepts include:

Loading embedding models
Generating embeddings
Text-to-vector conversion
Semantic representation
Embedding comparison
3. Cosine Similarity

Implementation and mathematical understanding of Cosine Similarity for comparing vector representations.

Cosine similarity measures the directional similarity between two vectors.

It is widely used in:

Semantic search
Document similarity
Recommendation systems
Information retrieval
RAG systems
Vector databases
4. Vector Databases

Introduction to Vector Databases and their role in Generative AI applications.

The repository explores ChromaDB for vector storage and similarity-based retrieval.

Important concepts include:

Vector storage
Embeddings
Similarity search
Metadata
Document retrieval
Semantic search
5. ChromaDB CRUD Operations

Practical implementation of CRUD operations using ChromaDB.

CRUD = Create, Read, Update, Delete

Operation	Purpose
Create	Add documents and vectors
Read	Retrieve stored information
Update	Modify existing information
Delete	Remove stored information

This provides practical experience with managing information inside a vector database.

6. Retrieval-Augmented Generation (RAG)

The repository explores Retrieval-Augmented Generation, an important architecture for building knowledge-grounded AI applications.

A typical RAG workflow is:

Documents
     ↓
Document Loading
     ↓
Text Chunking
     ↓
Embedding Generation
     ↓
Vector Database
     ↓
Similarity Search
     ↓
Relevant Context
     ↓
Language Model
     ↓
Generated Response

RAG allows an AI system to retrieve relevant information before generating an answer.

7. Document Loading & Chunking

Document preparation is an important part of a RAG pipeline.

The practical work covers:

Document loading
Text extraction
Document processing
Chunking strategies
Embedding generation
Vector storage
Retrieval

Proper chunking helps improve the quality and relevance of retrieved information.

🛠️ Technologies & Tools
Programming
Python
Jupyter Notebook
Google Colab
Generative AI
Generative AI
Large Language Models
Prompt Engineering
Retrieval-Augmented Generation
Natural Language Processing
NLP
Word Embeddings
Text Embeddings
Semantic Similarity
Vector Search
ChromaDB
Vector Databases
Cosine Similarity
Similarity Search
AI Ecosystem
Hugging Face
Embedding Models
RAG Pipelines
🚀 Getting Started
Clone the Repository
git clone https://github.com/YOUR-USERNAME/Gen-AI_tasks.git
Navigate to the Project
cd Gen-AI_tasks
Run the Practical Work

The practical implementations can be executed using:

Google Colab
Jupyter Notebook
Python environments

The notebook implementations can be opened and executed after installing the required dependencies.

📚 Recommended Learning Path

The practical concepts can be understood in the following order:

                Word Embeddings
                       ↓
              Hugging Face Embeddings
                       ↓
               Cosine Similarity
                       ↓
              Vector Databases
                       ↓
                  ChromaDB
                       ↓
             ChromaDB CRUD
                       ↓
              Document Loading
                       ↓
             Document Chunking
                       ↓
                     RAG
                       ↓
              RAG Practice

This learning path progresses from fundamental NLP concepts to practical Generative AI retrieval systems.

🔍 RAG Architecture
                     ┌──────────────────┐
                     │    Documents     │
                     └────────┬─────────┘
                              │
                              ▼
                    ┌──────────────────┐
                    │ Document Loader  │
                    └────────┬─────────┘
                             │
                             ▼
                    ┌──────────────────┐
                    │     Chunking     │
                    └────────┬─────────┘
                             │
                             ▼
                    ┌──────────────────┐
                    │   Embeddings     │
                    └────────┬─────────┘
                             │
                             ▼
                    ┌──────────────────┐
                    │    ChromaDB      │
                    │ Vector Database  │
                    └────────┬─────────┘
                             │
                             │
                       User Query
                             │
                             ▼
                    ┌──────────────────┐
                    │ Similarity Search│
                    └────────┬─────────┘
                             │
                             ▼
                    ┌──────────────────┐
                    │ Relevant Context │
                    └────────┬─────────┘
                             │
                             ▼
                    ┌──────────────────┐
                    │       LLM        │
                    └────────┬─────────┘
                             │
                             ▼
                    ┌──────────────────┐
                    │ AI Generated     │
                    │    Response      │
                    └──────────────────┘
🎯 Learning Objectives

This repository demonstrates practical understanding of:

Text and word embeddings
Hugging Face embedding models
Vector representations
Cosine similarity
Vector databases
ChromaDB
CRUD operations
Document preprocessing
Text chunking
Semantic retrieval
RAG architecture
Generative AI applications
📈 Future Improvements

Potential future enhancements include:

Advanced RAG pipelines
Hybrid search
Metadata filtering
Reranking models
RAG evaluation
Advanced vector database techniques
LLM integration
Multimodal RAG
Agentic AI workflows
AI-powered web applications
Streamlit or React-based interfaces
🎓 Academic Purpose

This repository serves as a practical learning portfolio demonstrating the progression from fundamental NLP and embedding concepts to modern Generative AI and RAG-based applications.

The overall learning progression can be summarized as:

Embeddings → Vector Databases → Retrieval → RAG → Generative AI

👩‍💻 Author

RANGANI PRIYANKA

B.Tech – Computer Science & Engineering (AI & ML)
Kalasalingam Academy of Research and Education

Registration Number: 99230040055
Email: 99230040055@klu.ac.in

⭐ Acknowledgement

This repository was developed as part of practical learning and experimentation in:

Generative AI • NLP • Embeddings • Vector Databases • ChromaDB • RAG

⭐ If you find this repository useful, consider giving it a star!
