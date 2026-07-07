# 📅 Day 4 Learning Journey

On Day 4 of the AI Training Program, I explored cloud computing with AWS, vector databases, Retrieval-Augmented Generation (RAG), and ChromaDB. These technologies form the backbone of modern AI applications that use custom knowledge instead of relying only on an LLM's pre-trained information.

---

# 📚 Topics Covered

# 1. Amazon Web Services (AWS)

## What is AWS?

Amazon Web Services (AWS) is the world's leading cloud computing platform that provides on-demand computing resources over the internet.

Instead of purchasing physical servers, developers can rent cloud services whenever needed.

---

## Common AWS Services

### EC2 (Elastic Compute Cloud)

- Virtual servers in the cloud
- Run applications
- Deploy AI models
- Host websites

### S3 (Simple Storage Service)

- Object storage service
- Store images, videos, PDFs
- Backup files
- AI datasets

### Lambda

- Serverless computing
- Run code without managing servers
- Pay only for execution time

### RDS

- Managed SQL databases
- PostgreSQL
- MySQL
- MariaDB

### IAM

Identity and Access Management

Used to:

- Create users
- Manage permissions
- Secure AWS resources

---

## Benefits of AWS

- Highly scalable
- Secure
- Global infrastructure
- Pay-as-you-go pricing
- Reliable cloud services

---

# 2. PGVector

## What is PGVector?

PGVector is a PostgreSQL extension that allows storing and searching **vector embeddings** directly inside PostgreSQL.

It combines the reliability of SQL databases with AI-powered semantic search.

---

## Why PGVector?

Traditional databases search using keywords.

PGVector searches using **meaning (semantic similarity)**.

Example:

User Query:

```
Best laptop for students
```

Stored Document:

```
Affordable notebooks for college students
```

Even though the words are different, PGVector can understand that both have a similar meaning.

---

## Features

- Stores vector embeddings
- Similarity Search
- Cosine Similarity
- Euclidean Distance
- Inner Product Search
- Works with PostgreSQL

---

## Applications

- Semantic Search
- Recommendation Systems
- AI Chatbots
- RAG Applications
- Document Search

---

# 3. Retrieval-Augmented Generation (RAG)

## What is RAG?

Retrieval-Augmented Generation (RAG) is an AI architecture that combines **information retrieval** with **Large Language Models**.

Instead of relying only on the model's training data, RAG first retrieves relevant information from external sources and then generates an answer.

---

## Why RAG?

Without RAG:

- Limited to model knowledge
- May generate incorrect information (hallucinations)
- Cannot answer questions about private company data

With RAG:

- Uses latest information
- Answers from custom documents
- More accurate responses
- Reduced hallucinations

---

## Important Concepts in RAG

### 1. Document Loading

Load data from:

- PDFs
- Word files
- Websites
- Databases
- Text files

---

### 2. Text Chunking

Large documents are divided into smaller chunks.

Benefits:

- Faster retrieval
- Better context
- Improved accuracy

---

### 3. Embeddings

Text is converted into numerical vectors using embedding models.

Similar meanings produce similar vectors.

---

### 4. Vector Database

Embeddings are stored in a vector database such as:

- ChromaDB
- PGVector
- Pinecone
- Weaviate
- Milvus

---

### 5. Similarity Search

When a user asks a question:

- Query is converted into an embedding.
- Similar vectors are retrieved.
- Relevant chunks are returned.

---

### 6. Prompt Augmentation

Retrieved information is added to the prompt before sending it to the LLM.

This gives the model additional context for generating accurate answers.

---

### 7. Response Generation

The LLM uses both:

- Retrieved context
- User question

to generate the final answer.

---

## RAG Workflow

```
User Query
     │
     ▼
Embedding Model
     │
     ▼
Vector Database
     │
Similarity Search
     │
Relevant Documents
     │
     ▼
Large Language Model
     │
     ▼
Final Response
```

---

## Applications of RAG

- Enterprise Chatbots
- Customer Support
- Legal AI
- Medical AI
- Internal Company Knowledge Bases
- Research Assistants
- Document Question Answering

---

# 4. ChromaDB

## What is ChromaDB?

ChromaDB is an open-source vector database designed specifically for AI and Large Language Model applications.

It stores embeddings and performs fast similarity searches.

---

## Features

- Open Source
- Lightweight
- Easy Python Integration
- Stores embeddings efficiently
- Fast semantic search
- Perfect for RAG applications

---

## Basic Workflow

```
Documents
     │
Chunking
     │
Embedding Model
     │
Store Embeddings
     │
ChromaDB
     │
Similarity Search
     │
Relevant Context
```

---

## Example (Python)

```python
import chromadb

client = chromadb.Client()

collection = client.create_collection("documents")

collection.add(
    documents=["Artificial Intelligence is transforming industries."],
    ids=["1"]
)

results = collection.query(
    query_texts=["What is AI?"],
    n_results=1
)

print(results)
```

---

## Advantages of ChromaDB

- Beginner friendly
- Open source
- Local deployment
- Fast retrieval
- Excellent for AI chatbots
- Easy integration with LangChain and LlamaIndex

---

# 🧠 Key Takeaways

✅ Learned the fundamentals of AWS cloud computing and its core services.

✅ Understood how PGVector enables semantic search within PostgreSQL.

✅ Explored the complete RAG pipeline, including document loading, chunking, embeddings, vector databases, similarity search, prompt augmentation, and response generation.

✅ Learned how ChromaDB stores vector embeddings and powers efficient retrieval in AI applications.

---

# 🛠 Technologies & Concepts Learned

- Amazon Web Services (AWS)
- EC2
- S3
- Lambda
- IAM
- RDS
- PostgreSQL
- PGVector
- Embeddings
- Semantic Search
- Retrieval-Augmented Generation (RAG)
- Document Chunking
- Similarity Search
- Prompt Augmentation
- ChromaDB
- Vector Databases

---

# 📈 Outcome

By the end of Day 4, I understood how cloud platforms like AWS support scalable AI applications, how vector databases such as PGVector and ChromaDB enable semantic search, and how Retrieval-Augmented Generation (RAG) combines document retrieval with Large Language Models to build accurate, context-aware AI systems capable of answering questions using external knowledge sources.
