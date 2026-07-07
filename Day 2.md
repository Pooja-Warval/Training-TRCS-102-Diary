# 🚀 AI Training Program - Day 2

## 📅 Day 2 Learning Journey

On the second day of my AI Training Program, I explored several important concepts that are widely used in modern AI application development, automation, and software engineering.

---

# 📚 Topics Covered

## 1. MCP (Model Context Protocol)

### What is MCP?
Model Context Protocol (MCP) is an open standard that enables AI models to securely communicate with external tools, APIs, databases, and applications.

### Why is it important?
- Standard communication between AI and tools
- Secure data exchange
- Makes AI assistants more powerful
- Easy integration with external services

### Example
ChatGPT accessing:
- Files
- Databases
- GitHub
- Browser
- APIs

---

## 2. Environment Variables

### What are Environment Variables?

Environment variables store sensitive information separately from the source code.

Examples:
- API Keys
- Database URLs
- Secret Tokens
- Passwords

Example:

```env
GEMINI_API_KEY=xxxxxxxxxxxxxxxx
DATABASE_URL=postgres://...
```

### Benefits

- Better security
- Easy configuration
- Different settings for development and production
- Prevents exposing secrets on GitHub

---

## 3. Playwright Library

### What is Playwright?

Playwright is a browser automation framework developed by Microsoft.

It can automate:

- Chrome
- Edge
- Firefox
- Safari

### Uses

- Web Testing
- Web Scraping
- Browser Automation
- UI Testing

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

## 4. QA LLM (Question Answering using LLM)

### What is QA LLM?

QA LLM refers to Large Language Models designed to answer user questions based on:

- Documents
- PDFs
- Databases
- Knowledge Bases
- Websites

Examples:

- ChatGPT
- Gemini
- Claude

Applications:

- AI Chatbots
- Customer Support
- Education
- Enterprise Search
- Research Assistants

---

## 5. Forward Deployed Engineer (FDE)

### Who is a Forward Deployed Engineer?

A Forward Deployed Engineer works directly with customers to build customized AI and software solutions.

Responsibilities:

- Understand client requirements
- Build AI solutions
- Integrate APIs
- Deploy applications
- Solve real-world problems

Skills Required:

- Programming
- AI
- Cloud Computing
- APIs
- Communication
- Problem Solving

---

# 🧠 Key Takeaways

✅ Learned how AI communicates with external tools using MCP.

✅ Understood the importance of Environment Variables for securing API keys.

✅ Explored Playwright for browser automation and testing.

✅ Learned how QA LLM systems answer questions using AI.

✅ Got introduced to the role of a Forward Deployed Engineer in AI companies.

---

# 🖼️ Learning Screenshots

## MCP

<p align="center">
<img src="images/mcp.png" width="700">
</p>

---

## Environment Variables

<p align="center">
<img src="images/environment-variables.png" width="700">
</p>

---

## Playwright

<p align="center">
<img src="images/playwright.png" width="700">
</p>

---

## QA LLM

<p align="center">
<img src="images/qa-llm.png" width="700">
</p>

---

## Forward Deployed Engineer

<p align="center">
<img src="images/fde.png" width="700">
</p>

---

# 🛠 Technologies & Concepts Learned

- MCP (Model Context Protocol)
- Environment Variables
- Playwright
- QA LLM
- Browser Automation
- AI Integration
- API Security
- Large Language Models
- Software Testing
- Forward Deployed Engineering

---

# 📈 Outcome

By the end of Day 2, I gained a better understanding of how modern AI applications interact with external systems, how sensitive information is managed securely, how browser automation works, and the responsibilities of engineers who deploy AI solutions for real-world customers.

---

## 🌟 Repository Goal

This repository documents my daily learning throughout the AI Training Program, helping me strengthen my understanding of AI concepts, software development, and modern engineering practices.

---

### ⭐ If you found this repository helpful, consider giving it a Star!
