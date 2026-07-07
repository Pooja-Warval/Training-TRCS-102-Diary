# AI Engineering Learning Notes 🚀

This repository contains my learning notes and resources from AI workshops and self-study.

## Topics Covered

- Generative AI
- Agentic AI
- Large Language Models (LLMs)
- Retrieval Augmented Generation (RAG)
- Semantic Search
- Vector Databases
- Agent Orchestration
- Multi-Agent Systems
- Playwright
- MCP (Model Context Protocol)
- Prompt Engineering
- Transformer Architecture
- Local LLMs using Ollama
- Google AI Studio
- Gemini API
- Perplexity AI

---

## AI Tools

- Gemini API
- Google AI Studio
- Ollama
- Alibaba Models
- Perplexity AI
- Local LLMs

---

## AI Concepts

### Generative AI
Generative AI creates new content such as text, images, videos, and code by learning patterns from existing data.

Example:
- ChatGPT
- Gemini
- Claude

---

### Agentic AI
Agentic AI goes beyond content generation by reasoning, planning, making decisions, and taking actions automatically to accomplish goals.

Example:
- Write an email
- Send the email
- Follow up automatically if there is no response

---

### Large Language Models (LLMs)

LLMs are AI models trained on massive datasets that understand and generate human language.

Examples:
- GPT
- Gemini
- Claude
- Llama

---

### Retrieval-Augmented Generation (RAG)

RAG combines LLMs with external knowledge sources to generate more accurate and up-to-date responses.

Components:
- Embeddings
- Semantic Search
- Vector Database

---

### Semantic Search

Searches based on meaning instead of exact keyword matching.

---

### Vector Database

Stores embeddings for fast similarity search.

Examples:
- ChromaDB
- FAISS
- Pinecone

---

### Agent Orchestration

Coordinates multiple AI agents and tools to complete complex tasks.

---

### Multi-Agent Systems

Multiple AI agents collaborate to solve problems together.

---

### Prompt Engineering

Designing effective prompts to improve AI responses.

---

### Context Engineering

Providing relevant context so AI can generate better responses.

---

### Transformer Architecture

The deep learning architecture behind modern LLMs.

---

### MCP (Model Context Protocol)

A protocol that enables AI models to securely communicate with external tools and data sources.

---

### Playwright

Playwright is a browser automation framework used for:

- Automated testing
- End-to-end testing
- Browser automation
- Web scraping

Example:

```javascript
const { chromium } = require('playwright');

(async () => {
    const browser = await chromium.launch();
    const page = await browser.newPage();

    await page.goto('https://google.com');
    console.log(await page.title());

    await browser.close();
})();
```

---

## Learning Resources

- Anthropic Academy
- DeepLearning.AI
- Coursera
- Google AI Studio Documentation
- Playwright Documentation

---

## Future Learning

- LangGraph
- CrewAI
- AutoGen
- LangChain
- Vector Databases
- Local LLM Deployment
- AI Agents

---

## Repository Purpose

This repository serves as my personal AI Engineering learning notebook where I continuously update concepts, examples, code snippets, and projects.

Happy Learning! 🚀
