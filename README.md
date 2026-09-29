# Aster Portfolio Draft — for Pruthviii23

Status: Drafted 2026-09-29. Do not publish verbatim until the account holder checks the facts, links, and preferred public contact route.

## Strategic selection

**Lead project: ConstiBot — Indian Constitution AI Chatbot.** It is the best proof of a modern, end-to-end AI application: it has an explicit retrieval architecture, source citations, conversational follow-ups, a FastAPI backend, a Next.js frontend, and documented deployment. This is the project I am most proud to put first because it solves a meaningful information-access problem while being precise about its evidence.

**Signature project: SP3 — Mono-Wheel EV.** This is the memorable differentiator: a real vehicle prototype built by a four-person student team. Its README is unusually honest about current limits—the control is tilt-controlled and speed-based, not self-balancing—and that honesty is an asset. We will not take sole credit or claim the planned PID/VESC system is complete.

**Supporting project: Formula 1 Data Scraping & Prediction.** A useful data-pipeline proof point, but not a lead project because the prediction work is partly exploratory/planned. We will position it as dataset engineering and analysis, not as a validated prediction product.

**Suggested GitHub pin order:** `constitution_chatbot`, `Mono-Wheel-EV-SP3`, `Formula-1-Data-Scraping-Prediction-Project`, then `Face-Tracking-Table-Fan`.

## GitHub profile README

Create a public repository named exactly `Pruthviii23`, add this as its `README.md`, and pin it. Replace the bracketed placeholders only after verifying them.

```md
# Hi, I’m Pruthviraj 👋

AI/ML graduate and AI Product Management intern building practical AI systems—from source-grounded RAG apps to data pipelines and physical prototypes.

I work primarily with Python and also build with TypeScript, JavaScript, HTML, and CSS. I’m interested in retrieval systems, applied machine learning, developer tools, and products that turn complex information into something people can use.

## Featured work

### 🏛️ ConstiBot — Indian Constitution AI Chatbot
An AI assistant for asking questions about the Indian Constitution with cited source pages.

- Built a RAG pipeline over a 402-page source document, indexed as 2,628 chunks
- Used MMR retrieval and history-aware follow-up handling to retrieve relevant context
- Built with FastAPI, LangChain, ChromaDB, Groq/Ollama, Next.js, and Tailwind
- [Repository](https://github.com/Pruthviii23/constitution_chatbot) · [Live demo](https://constitution-chatbot-pruthviii23s-projects.vercel.app)

### ⚡ SP3 — Mono-Wheel EV
Part of a four-person team building a full-scale mono-wheel electric-vehicle prototype from scratch.

- 2000W hub motor, custom 72V (20s5p) Li-ion battery pack, Arduino control, MPU6500 IMU, and DAC throttle control
- The current prototype is tilt-controlled and speed-based; true PID self-balancing is future work
- [Repository](https://github.com/Pruthviii23/Mono-Wheel-EV-SP3)

### 🏁 Formula 1 Data Pipeline
A Python pipeline that collects, integrates, and analyzes Formula 1 results from 2016–2024 for ML exploration.

- Selenium/BeautifulSoup data collection and Pandas/NumPy data processing
- Integrates race results, qualifying, practice, fastest-lap, and pit-stop data
- [Repository](https://github.com/Pruthviii23/Formula-1-Data-Scraping-Prediction-Project)

## Currently

- AI PM intern at a service-based company
- Building AI/ML projects and improving end-to-end product engineering skills

## Let’s connect

[Add LinkedIn] · [Add professional email or portfolio when ready]
```

## Case-study briefs

### ConstiBot

**One-sentence portfolio claim:** Designed and deployed an AI assistant that retrieves relevant passages from the Indian Constitution and answers with cited source pages.

**Problem:** Long legal documents are hard for a non-specialist to navigate. A useful assistant must make source material discoverable without presenting unsupported answers as fact.

**Approach:** Ingest a 402-page Constitution PDF; split it into 2,628 chunks; embed and persist them in ChromaDB; retrieve a diverse top-four context set using MMR; use a history-aware retriever for follow-ups; return the answer alongside cited pages. Use a Next.js UI and FastAPI service, with local Ollama development and Groq in deployment.

**Evidence we can show:** architecture diagram, live application, API endpoints, repository structure, documented limitations/roadmap.

**Careful wording:** Say “source-grounded answers with citations,” not “legal advice,” “fully accurate,” or “hallucination-free.” The README’s refusal behavior is a design intent, not a universal accuracy guarantee.

### SP3

**One-sentence portfolio claim:** Collaborated in a four-person student team on a 2000W mono-wheel EV prototype combining fabrication, battery systems, sensors, and embedded control.

**Problem:** Explore the design and control challenges of a high-power, single-wheel EV rather than treating AI/ML education as software-only.

**Approach:** Combine a 17-inch 2000W BLDC hub motor, 72V 20s5p pack, Arduino control, MPU6500 tilt sensing, MCP4725 DAC throttle output, stainless-steel chassis fabrication, and iterative testing.

**Current state:** Tilt-controlled, speed-based drive tests work. Torque-controlled self-balancing remains planned and requires a controller upgrade.

**Attribution rule:** Credit every team member and do not assign a precise individual contribution unless Pruthviraj verifies it.

## First-service positioning derived from this portfolio

**Offer name:** *Turn your AI/engineering project into a portfolio people can understand.*

For students and early-career developers with a project that works but a GitHub profile that does not communicate its value, we will create:

1. a sharp GitHub profile README;
2. one rewritten project README / case study;
3. a LinkedIn project description; and
4. optional simple static portfolio page.

We sell clarity, documentation, and presentation—not guaranteed jobs, fabricated metrics, or false technical authorship.


<!--
**Pruthviii23/Pruthviii23** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
