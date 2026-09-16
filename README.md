<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0e27,50:0f2440,100:1a3a5c&height=220&section=header&text=Shivanand%20Devakate&fontSize=40&fontColor=e6f1ff&animation=fadeIn&fontAlignY=36&desc=AI%20Engineer%20%C2%B7%20Data%20Scientist%20%C2%B7%20Backend%20%26%20GenAI%20Systems&descAlignY=54&descSize=17"/>

<a href="https://www.linkedin.com/in/shivanand-devakate"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://github.com/shivanand-1"><img src="https://img.shields.io/badge/GitHub-121826?style=for-the-badge&logo=github&logoColor=00e5ff"/></a>
<a href="https://shivanand-1.netlify.app"><img src="https://img.shields.io/badge/Portfolio-0f2440?style=for-the-badge&logo=vercel&logoColor=00e5ff"/></a>
<a href="mailto:shivananddevakate497@gmail.com"><img src="https://img.shields.io/badge/Email-1a3a5c?style=for-the-badge&logo=gmail&logoColor=00e5ff"/></a>

<br/><br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=00E5FF&center=true&vCenter=true&width=650&lines=Building+production-ready+AI+systems;Engineering+RAG+pipelines;Deploying+Computer+Vision+APIs;Turning+ML+models+into+scalable+services;Python+%E2%80%A2+FastAPI+%E2%80%A2+GenAI+%E2%80%A2+Computer+Vision"/>

</div>

<br/>

## About Me

I build AI and data-driven applications that connect machine learning models with production-oriented backend systems. My work spans Retrieval-Augmented Generation, computer vision inference, and predictive modeling — each shipped as a working API rather than a notebook experiment.

I hold a B.E. in Computer Science & Engineering (VTU) and currently work as a freelance Data Scientist / AI Engineer based in Bengaluru, India, building end-to-end systems: FastAPI service layers, vector-store-backed retrieval, and ML pipelines wired into usable products.

<br/>

## Engineering Profile

```python
class ShivanandDevakate:
    role        = "AI Engineer / Data Scientist"
    location    = "Bengaluru, India"
    focus       = ["RAG Systems", "Computer Vision", "FastAPI Backends", "Predictive ML"]
    stack       = ["Python", "FastAPI", "LangChain", "PyTorch", "TensorFlow", "PostgreSQL"]
    building    = "Production-oriented AI services, one pipeline at a time"
    philosophy  = "A model isn't done until it's behind an API"
```

<br/>

## Tech Stack

**Languages**
<br/>
<img src="https://skillicons.dev/icons?i=python,mysql"/>

**AI / Machine Learning**
<br/>
<img src="https://skillicons.dev/icons?i=tensorflow,pytorch,opencv"/>
<br/>
<img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white"/> <img src="https://img.shields.io/badge/XGBoost-EC0000?style=flat-square"/>

**Generative AI**
<br/>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=00e5ff"/> <img src="https://img.shields.io/badge/RAG-1a3a5c?style=flat-square"/> <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black"/> <img src="https://img.shields.io/badge/Embeddings-1a3a5c?style=flat-square"/>

**Computer Vision**
<br/>
<img src="https://img.shields.io/badge/YOLOv8-111F68?style=flat-square"/> <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white"/>

**Backend**
<br/>
<img src="https://skillicons.dev/icons?i=fastapi,flask"/> <img src="https://img.shields.io/badge/REST%20APIs-1a3a5c?style=flat-square"/>

**Data**
<br/>
<img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white"/> <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white"/> <img src="https://img.shields.io/badge/Matplotlib-11557C?style=flat-square"/> <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black"/>

**Databases**
<br/>
<img src="https://skillicons.dev/icons?i=postgres,mysql,sqlite"/> <img src="https://img.shields.io/badge/ChromaDB-1a3a5c?style=flat-square"/>

**DevOps / Tools**
<br/>
<img src="https://skillicons.dev/icons?i=docker,git,github,vscode"/>

<br/>

## ⚙️ How I Build AI Systems

```mermaid
flowchart TD
    A[User] --> B[Frontend / API Client]
    B --> C[FastAPI Service Layer]
    C --> D[AI / ML Pipeline]
    D --> E[RAG · Model Inference · Computer Vision]
    E --> F[Vector DB / PostgreSQL]
    F --> G[Response]
```

Every project follows this shape: a thin, predictable API in front, the model or retrieval logic isolated in its own layer, and persistence handled separately from inference — so components can be swapped without rewriting the system.

<br/>

## Featured Projects

### 🧠 AI-Powered RAG Knowledge System

**Problem:** Static documents are hard to query — users need direct, grounded answers instead of manually searching through files.

**Solution:** A retrieval-augmented question-answering service that ingests documents, indexes them for semantic search, and answers queries with context pulled from the source material.

**Engineering:** Document ingestion → chunking → embedding generation → vector storage in ChromaDB → semantic retrieval → context-augmented LLM response, exposed through a FastAPI layer.

```mermaid
flowchart TD
    A[Documents] --> B[Ingestion]
    B --> C[Text Splitting]
    C --> D[Embeddings]
    D --> E[ChromaDB]
    E --> F[Semantic Retrieval]
    F --> G[Relevant Context]
    G --> H[LLM]
    H --> I[Grounded Response]
```

**Stack:** `LangChain` `FastAPI` `ChromaDB` `Groq` `Embeddings`

**Key Engineering Concepts:** RAG · Vector Search · Embeddings · API Integration

---

### 🍎 AI Nutrition Detection System

**Problem:** Manually logging food intake and nutrition is tedious and error-prone.

**Solution:** A computer-vision pipeline that detects food items from an image, estimates portion size, and maps detections to nutritional data — served through a FastAPI endpoint.

```mermaid
flowchart TD
    A[Image] --> B[Preprocessing]
    B --> C[YOLOv8]
    C --> D[Food Detection]
    D --> E[Quantity Estimation]
    E --> F[Nutrition Mapping]
    F --> G[FastAPI]
    G --> H[Result]
```

**Stack:** `YOLOv8` `FastAPI` `OpenCV`

**Key Engineering Concepts:** Object Detection · Model Inference · API Integration

---

### 🎥 YouTube Video RAG Summarizer

**Problem:** Long-form video content is time-consuming to review for specific information.

**Solution:** Extracts and transcribes video audio (including Hindi-to-English transcription via Whisper), then enables retrieval-augmented Q&A and summarization over the transcript.

```mermaid
flowchart TD
    A[YouTube URL] --> B[Audio Extraction]
    B --> C[Whisper Transcription]
    C --> D[Text Processing]
    D --> E[Chunking]
    E --> F[Embeddings]
    F --> G[Vector Retrieval]
    G --> H[LLM]
    H --> I[Summary / Q&A]
```

**Stack:** `Whisper` `yt-dlp` `LangChain` `RAG`

**Key Engineering Concepts:** Speech-to-Text · RAG · Vector Search · Data Processing

---

### 💊 MediSense AI

**Problem:** Checking for drug interactions manually is slow and easy to get wrong.

**Solution:** A drug-interaction checker combining an XGBoost classification model with a full-stack FastAPI + React application, using hybrid PostgreSQL and ChromaDB storage.

**Stack:** `XGBoost` `FastAPI` `React` `PostgreSQL` `ChromaDB`

**Key Engineering Concepts:** Model Inference · REST API · Database Integration

---

### 🌾 AgriContract

**Problem:** Farmers often lack direct, transparent access to buyers and agronomic guidance.

**Solution:** An agritech platform combining crop recommendation, soil analysis, and disease prediction with blockchain-backed contracts connecting farmers directly to buyers.

**Stack:** `Python` `FastAPI` `Machine Learning`

**Key Engineering Concepts:** Predictive Modeling · API Integration · Data Processing

---

### 🏠 Bengaluru House Price Prediction

**Problem:** Real estate pricing in Bengaluru varies widely and is hard to estimate consistently.

**Solution:** A regression-based pricing model with feature engineering, trained and compared across multiple algorithms to estimate property prices.

**Stack:** `Scikit-learn` `Pandas` `Regression`

**Key Engineering Concepts:** Feature Engineering · Model Evaluation · Data Processing

<div align="center">

*More projects on <a href="https://github.com/shivanand-1">GitHub</a> and in my <a href="https://shivanand-1.netlify.app">portfolio</a>.*

</div>

<br/>

## 🧩 Engineering Principles

- Build before over-engineering
- Keep APIs predictable
- Separate data, business logic, and inference
- Prefer measurable results over assumptions
- Design ML systems for integration, not isolation
- Write software that can be maintained by someone else

<br/>

## Currently Building

- Production-oriented RAG systems
- FastAPI services around ML and CV models
- Computer vision inference pipelines
- Data-driven APIs for real-world use cases

<br/>

## 📊 GitHub Analytics

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=shivanand-1&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=shivanand-1&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117"/>

<img src="https://streak-stats.demolab.com?user=shivanand-1&theme=tokyonight&hide_border=true&background=0D1117"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=shivanand-1&theme=tokyo-night&hide_border=true&bg_color=0D1117"/>

</div>

<br/>

## 🏆 Certifications

| Certification | Issuer |
|---|---|
| Data Science Internship | QSpiders |
| Data Preprocessing & ML | YHills |
| Data Science | Infosys Springboard |
| Data Science | CodeWithHarry |

<br/>

## Connect

<div align="center">

**Interested in building AI-powered products or data-driven systems?**

<a href="https://www.linkedin.com/in/shivanand-devakate"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://github.com/shivanand-1"><img src="https://img.shields.io/badge/GitHub-121826?style=for-the-badge&logo=github&logoColor=00e5ff"/></a>
<a href="https://shivanand-1.netlify.app"><img src="https://img.shields.io/badge/Portfolio-0f2440?style=for-the-badge&logo=vercel&logoColor=00e5ff"/></a>
<a href="mailto:shivananddevakate497@gmail.com"><img src="https://img.shields.io/badge/Email-1a3a5c?style=for-the-badge&logo=gmail&logoColor=00e5ff"/></a>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a3a5c,50:0f2440,100:0a0e27&height=120&section=footer"/>

</div>
