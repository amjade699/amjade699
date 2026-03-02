<div align="center">

# 👋 Hi, I'm @amjade699

### 🤖 AI/ML Engineer · 🧠 NLP & RAG Specialist · ♿ Assistive Tech Builder

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![LangChain](https://img.shields.io/badge/LangChain-Framework-1C3C3C?style=for-the-badge&logo=chainlink&logoColor=white)](https://www.langchain.com/)
[![OpenAI](https://img.shields.io/badge/OpenAI-API-412991?style=for-the-badge&logo=openai&logoColor=white)](https://openai.com/)
[![HTML5](https://img.shields.io/badge/HTML5-CSS3-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![GitHub](https://img.shields.io/badge/GitHub-amjade699-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/amjade699)

---

*Building intelligent systems that make information more accessible, workflows smarter, and technology more inclusive.*

</div>

---

## 👤 About Me

I'm an AI/ML developer with a passion for building **real-world intelligent applications** — from document intelligence and healthcare assistance to assistive communication tools and automated journalism. My work sits at the intersection of **Large Language Models**, **Retrieval-Augmented Generation (RAG)**, and **human-centred design**.

I believe technology should be **useful, accessible, and impactful**. Whether it's helping a doctor retrieve clinical knowledge from PDFs, enabling someone to communicate through sign language, or automating tedious documentation tasks — I build tools that solve genuine problems.

**🎯 Core Interests:**
- Retrieval-Augmented Generation (RAG) & Document AI
- NLP, Computer Vision & Assistive Technologies
- AI-powered web applications & automation
- Open-source tooling for developer productivity

---

## 🚀 Tech Stack

<div align="center">

| Domain | Technologies |
|---|---|
| **Languages** | Python 3.10+, HTML5, CSS3, JavaScript |
| **AI / LLM** | OpenAI GPT, Google Gemini, HuggingFace Transformers |
| **RAG & Vector DB** | LangChain, FAISS, ChromaDB, Embeddings |
| **NLP & CV** | spaCy, NLTK, Tesseract OCR, MediaPipe, OpenCV |
| **PDF & Document AI** | PyMuPDF, PDFPlumber, pdfminer |
| **Web & UI** | Streamlit, Flask, Gradio |
| **Dev Tools** | Git, GitHub, VS Code, Jupyter Notebooks |

</div>

---

## 🧠 Highlighted Projects

---

### 🔗 [PDF-Based-RAG](https://github.com/amjade699/PDF-Based-RAG)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square)
![FAISS](https://img.shields.io/badge/FAISS-VectorDB-blue?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-Enabled-green?style=flat-square)

**📋 Description:**
A Retrieval-Augmented Generation (RAG) pipeline that enables intelligent question-answering over PDF documents. Instead of hallucinating answers, the system retrieves the most relevant document chunks and grounds its responses in real content.

**🛠 Tech:** Python · LangChain · FAISS / ChromaDB · OpenAI / HuggingFace Embeddings · PyMuPDF / PDFPlumber

**⚙️ What It Does:**
Parses and chunks PDF documents, generates vector embeddings, and uses a similarity-search pipeline to retrieve relevant passages before generating accurate, contextually grounded answers via an LLM.

**✨ Key Features:**
- Upload any PDF and query it in natural language
- Semantic search using dense vector embeddings
- Context-aware LLM responses grounded in source documents
- Modular design — swap out the LLM or vector store easily

**💻 How to Use:**
```bash
git clone https://github.com/amjade699/PDF-Based-RAG
cd PDF-Based-RAG
pip install -r requirements.txt

# Run the app
streamlit run app.py

# Example query
# Upload your PDF → Ask: "What are the main findings in Chapter 3?"
```

**💡 Why It Matters:**
RAG is the backbone of enterprise document intelligence. This project demonstrates production-grade patterns for querying large documents without expensive fine-tuning — applicable to legal, medical, academic, and corporate use cases.

---

### 🔗 [healthcare-assistance](https://github.com/amjade699/healthcare-assistance)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![NLP](https://img.shields.io/badge/NLP-Enabled-brightgreen?style=flat-square)
![LLM](https://img.shields.io/badge/LLM-Powered-purple?style=flat-square)
![Healthcare](https://img.shields.io/badge/Domain-Healthcare-red?style=flat-square)

**📋 Description:**
An AI-powered healthcare assistance platform that helps users understand medical information, symptoms, and guidance through a conversational interface — designed to make health knowledge more accessible.

**🛠 Tech:** Python · LangChain or OpenAI API · NLP · Streamlit / Flask · Medical Knowledge Base

**⚙️ What It Does:**
Provides intelligent, conversational responses to healthcare-related queries, potentially combining a curated medical knowledge base with an LLM backbone to deliver safe, informative guidance.

**✨ Key Features:**
- Natural language medical Q&A interface
- AI-driven symptom understanding and information retrieval
- Accessible web UI for non-technical users
- Designed with responsible AI principles for sensitive domains

**💻 How to Use:**
```bash
git clone https://github.com/amjade699/healthcare-assistance
cd healthcare-assistance
pip install -r requirements.txt

# Set your API key
export OPENAI_API_KEY="your-key-here"

# Launch the assistant
python app.py
# or
streamlit run app.py
```

**💡 Why It Matters:**
Healthcare information is complex and often inaccessible. This project bridges the gap by making reliable health guidance available through a natural conversational interface — particularly valuable in underserved areas with limited access to professionals.

---

### 🔗 [resume-analyser](https://github.com/amjade699/resume-analyser)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![NLP](https://img.shields.io/badge/NLP-spaCy-09A3D5?style=flat-square)
![PDF](https://img.shields.io/badge/PDF-Parsing-orange?style=flat-square)
![AI](https://img.shields.io/badge/AI-Powered-blueviolet?style=flat-square)

**📋 Description:**
An intelligent resume parsing and analysis tool that extracts structured information from resumes, evaluates candidate profiles, and can match them against job descriptions using NLP and LLM reasoning.

**🛠 Tech:** Python · NLP (spaCy / NLTK) · PDF parsing · OpenAI API · Streamlit / HTML UI

**⚙️ What It Does:**
Ingests resumes in PDF or text format, extracts key entities (skills, experience, education, contact info), and provides structured analysis or job-fit scoring — automating a core part of the recruitment pipeline.

**✨ Key Features:**
- Automatic extraction of skills, experience, education and contact details
- Job description matching with relevance scoring
- Structured output (JSON or visual dashboard)
- Supports batch processing of multiple resumes

**💻 How to Use:**
```bash
git clone https://github.com/amjade699/resume-analyser
cd resume-analyser
pip install -r requirements.txt

# Analyse a single resume
python analyse.py --input resume.pdf --job "Software Engineer at a fintech startup"

# Or launch the web UI
streamlit run app.py
```

**💡 Why It Matters:**
Recruiters spend enormous time manually screening resumes. This tool automates parsing and scoring, reducing hiring bias, saving time, and enabling data-driven recruitment decisions.

---

### 🔗 [sign-language-interpreter](https://github.com/amjade699/sign-language-interpreter)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer_Vision-5C3EE8?style=flat-square&logo=opencv)
![MediaPipe](https://img.shields.io/badge/MediaPipe-HandTracking-orange?style=flat-square)
![Accessibility](https://img.shields.io/badge/Accessibility-Assistive_Tech-success?style=flat-square)

**📋 Description:**
A real-time sign language interpretation system using computer vision and hand landmark detection to translate hand gestures into text or speech — breaking communication barriers for the Deaf and Hard of Hearing community.

**🛠 Tech:** Python · OpenCV · MediaPipe · TensorFlow / Keras · Machine Learning classifiers

**⚙️ What It Does:**
Captures live video feed, detects and tracks hand landmarks using MediaPipe, classifies gestures using a trained ML model, and outputs the corresponding letter, word, or phrase in real time.

**✨ Key Features:**
- Real-time hand gesture recognition via webcam
- High-accuracy landmark detection with MediaPipe
- Custom-trained classification model for sign language alphabets / vocabulary
- Text output with optional text-to-speech conversion

**💻 How to Use:**
```bash
git clone https://github.com/amjade699/sign-language-interpreter
cd sign-language-interpreter
pip install -r requirements.txt

# Run real-time interpreter
python main.py

# Train your own model (optional)
python train.py --dataset ./data
```

**💡 Why It Matters:**
Over 70 million people globally use sign language as their primary communication method. This project directly addresses an accessibility gap, demonstrating the power of AI to foster inclusivity and bridge communication divides.

---

### 🔗 [README-and-Documentation-generator](https://github.com/amjade699/README-and-Documentation-generator)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LLM](https://img.shields.io/badge/LLM-Automation-blueviolet?style=flat-square)
![Markdown](https://img.shields.io/badge/Output-Markdown-lightgrey?style=flat-square&logo=markdown)
![DevTools](https://img.shields.io/badge/Dev-Tooling-informational?style=flat-square)

**📋 Description:**
An AI-powered tool that automatically generates professional README files and technical documentation for GitHub repositories by analysing code structure, function signatures, and project context.

**🛠 Tech:** Python · OpenAI / LLM API · AST parsing · Markdown templating · GitHub API (optional)

**⚙️ What It Does:**
Scans a repository's codebase, extracts meaningful context (modules, functions, dependencies, structure), and uses an LLM to produce a well-formatted, human-readable README and documentation suite — eliminating one of the most tedious tasks in software development.

**✨ Key Features:**
- Automatic README generation from code analysis
- Supports multiple output sections: usage, installation, API reference, examples
- Customisable documentation templates
- Works on any Python (or multi-language) project

**💻 How to Use:**
```bash
git clone https://github.com/amjade699/README-and-Documentation-generator
cd README-and-Documentation-generator
pip install -r requirements.txt

# Generate docs for a target project
python generate.py --path /path/to/your/project --output README.md

# Output: A polished README.md in your project directory
```

**💡 Why It Matters:**
Good documentation is what separates a hobby project from a professional one. This tool democratises documentation quality — helping developers, students, and open-source contributors present their work professionally without spending hours writing docs manually.

---

### 🔗 [AI-Powered-Journalism](https://github.com/amjade699/AI-Powered-Journalism-)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![NLP](https://img.shields.io/badge/NLP-Text_Gen-brightgreen?style=flat-square)
![LLM](https://img.shields.io/badge/LLM-Content_AI-purple?style=flat-square)
![WebScraping](https://img.shields.io/badge/Web-Scraping-yellow?style=flat-square)

**📋 Description:**
An AI-driven journalism assistant that automates the research, summarisation, and drafting of news articles and reports — combining web scraping, NLP summarisation, and LLM-powered writing into a single editorial pipeline.

**🛠 Tech:** Python · OpenAI / LLM API · BeautifulSoup / Scrapy · NLP summarisation · HTML/CSS UI

**⚙️ What It Does:**
Ingests a topic or set of URLs, scrapes and aggregates relevant content from the web, summarises key points, and generates a structured draft article or news report with proper attribution and context.

**✨ Key Features:**
- Topic-based news research and aggregation
- Automated summarisation of multiple web sources
- AI-assisted article drafting in various journalistic styles
- Source tracking and citation generation

**💻 How to Use:**
```bash
git clone https://github.com/amjade699/AI-Powered-Journalism-
cd AI-Powered-Journalism-
pip install -r requirements.txt

# Generate a news brief on a topic
python journalist.py --topic "Advances in renewable energy 2024"

# Output: A structured article draft with sources
```

**💡 Why It Matters:**
Newsrooms are under pressure to produce more content faster. This tool assists journalists by handling the research and drafting groundwork, letting human editors focus on analysis, ethics, and storytelling.

---

## 🛠️ Skills & Expertise

```
┌─────────────────────────────────────────────────────────────┐
│  🤖  LLM Integration & Prompt Engineering                   │
│  📄  PDF Intelligence & Document AI (RAG pipelines)         │
│  🔍  Semantic Search & Vector Databases (FAISS, ChromaDB)   │
│  🏥  Domain AI — Healthcare, Journalism, HR Tech            │
│  👁️  Computer Vision & Hand Gesture Recognition             │
│  📝  NLP — Entity Extraction, Summarisation, Classification │
│  🌐  Web UI Development (Streamlit, Flask, HTML/CSS)        │
│  🔧  Automation & Developer Tooling                         │
│  ♿  Assistive Technology & Inclusive Design                 │
└─────────────────────────────────────────────────────────────┘
```

---

## 🌟 Open-Source Impact

| Project | Domain | Impact |
|---|---|---|
| 📄 PDF-Based-RAG | Document AI | Enables no-hallucination Q&A over any PDF |
| 🏥 healthcare-assistance | Health Tech | Democratises access to medical information |
| 📋 resume-analyser | HR / Recruitment | Automates resume parsing & job matching |
| 🤟 sign-language-interpreter | Accessibility | Breaks communication barriers in real time |
| 📖 README-and-Docs-generator | Dev Tooling | Automates documentation for any project |
| 📰 AI-Powered-Journalism | Media Tech | Accelerates research-to-article pipelines |

> All repositories are public and open for contribution, forks, and adaptation. Each project targets a real-world problem domain with practical, deployable solutions.

---

## 📊 GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=amjade699&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=amjade699&layout=compact&theme=tokyonight&hide_border=true)

</div>

---

## 📫 Let's Connect

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-amjade699-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/amjade699)
[![Email](https://img.shields.io/badge/Email-Reach_Out-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/)

</div>

---

<div align="center">

*"AI should not replace human intelligence — it should amplify it."*

⭐ **If any of my projects are useful to you, a star goes a long way!** ⭐

</div>
