# 🎥 AI YouTube Video Analyzer (Agentic AI)

## 📌 Overview

AI YouTube Video Analyzer is an **Agentic AI application** that intelligently analyzes YouTube videos and generates structured insights instead of simply summarizing the transcript.

The application leverages an autonomous AI agent built using **Agno Agent Framework**, powered by **OpenRouter GPT-4o Mini**, to understand video content, identify important sections, generate timestamps, organize topics, and highlight the key learning outcomes.

A simple **Streamlit** interface allows users to paste any YouTube video URL and receive an organized analysis report within seconds.

---

# 🚀 Features

* 🤖 Agentic AI-powered YouTube analysis
* 🎥 Accepts any public YouTube video URL
* 📖 Generates a detailed video overview
* ⏱ Automatically creates meaningful timestamps
* 🧩 Groups related content into logical sections
* 📚 Extracts key learning points
* 🛠 Detects practical demonstrations
* 📌 Highlights important concepts and references
* 🎯 Identifies the type of content (Tutorial, Lecture, Review, etc.)
* 📝 Produces clean Markdown reports
* ⚡ Fast and interactive Streamlit interface
* 💾 Cached AI agent for improved performance
* 📅 Uses current date and time context during analysis

---

# 🏗️ Tech Stack

### Frontend

* Streamlit

### Agent Framework

* Agno Agent

### AI Model

* OpenRouter
* GPT-4o Mini

### AI Tool

* YouTubeTools

### Environment

* Python
* dotenv

---

# 🧠 Agent Workflow

1. User enters a YouTube video URL.
2. Streamlit sends the URL to the Agent.
3. The Agent invokes **YouTubeTools**.
4. The tool retrieves video information.
5. GPT-4o Mini analyzes the content.
6. The Agent structures the response.
7. Streamlit displays the final analysis report.

---

# 📊 Analysis Generated

The AI agent produces:

* Video Overview
* Video Metadata
* Content Structure
* Topic-wise Segmentation
* Timestamp Generation
* Topic Progression
* Key Learning Points
* Practical Demonstrations
* Important References
* Organized Markdown Report

---

# ⭐ Project Highlights

Unlike traditional YouTube summarizers, this project uses an **Agentic AI workflow**.

Instead of simply summarizing a transcript, the AI agent:

* Understands the entire video.
* Organizes the content logically.
* Detects major topic transitions.
* Creates structured timestamps.
* Highlights practical demonstrations.
* Extracts valuable learning points.
* Generates an easy-to-read report for users.

The agent independently reasons about the video and produces an organized analysis rather than returning a plain text summary.


---

# 📂 Project Structure

```
project/
│
├── ui.py                  # Streamlit User Interface
├── youtube_analyzer.py    # Agent Configuration
├── .env                   # API Keys, you can add your own API keys
├── requirements.txt
└── README.md
```

---

# ▶️ How to Run

```bash
git clone <repository-url>

cd youtube-video-analyzer

pip install -r requirements.txt

streamlit run ui.py
```

---

# 🔮 Future Enhancements

* Multi-language video analysis
* Sentiment analysis
* Speaker identification
* Export report as PDF
* Download analysis as Markdown
* Keyword extraction
* Mind map generation
* Question Answering over video content
* RAG integration for long videos
* Voice-based interaction
* Video comparison feature

---

# 🎯 Use Cases

* Students
* AI/ML Learners
* Software Engineers
* Content Creators
* Researchers
* Educators
* Interview Preparation
* Online Course Analysis

---

# 📈 Skills Demonstrated

* Agentic AI
* Large Language Models (LLMs)
* Prompt Engineering
* AI Tool Integration
* OpenRouter API
* Agno Framework
* Streamlit Development
* Python Programming
* Environment Management
* AI Application Development

---

# 👩‍💻 Author

**Anusha R**

Aspiring AI/ML Engineer passionate about building intelligent applications using Agentic AI, Large Language Models, and Generative AI technologies.
