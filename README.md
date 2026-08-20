# SkillGap AI 🎯

**AI-powered resume-to-job-description matcher** that helps candidates identify skill gaps and understand their fit for a role — instantly, using generative AI.

🔗 **Live Demo:** [Add your deployed Streamlit link here]
📂 **Repo:** github.com/Venky1316/Skillgap_ai

---

## 📌 Overview

SkillGap AI is a full-stack web application that compares a candidate's resume against a job description using large language models (Claude/OpenAI APIs). It identifies missing skills, highlights matching qualifications, and generates structured, actionable feedback — helping job seekers tailor their applications more effectively.

Built end-to-end, from concept to a live, demo-ready Streamlit application.

---

## ✨ Features

- 📄 Upload a resume and paste/upload a job description
- 🤖 AI-driven analysis using Claude/OpenAI APIs
- 🔍 Skill gap identification — what's missing, what matches
- 📊 Structured, easy-to-read match-relevance feedback
- 🖥️ Clean, interactive Streamlit interface

---

## 🛠️ Tech Stack

| Category            | Technology              |
|----------------------|--------------------------|
| Language              | Python                  |
| Web Framework         | Streamlit                |
| AI/LLM Integration     | Claude API / OpenAI API |
| Resume Parsing         | PyPDF2 / python-docx |
| Data Handling          | Pandas                  |
| Version Control        | Git & GitHub            |

---

## 🚀 Getting Started

### Prerequisites
- Python 3.9+
- pip
- A Claude or OpenAI API key

### Installation

git clone https://github.com/Venky1316/Skillgap_ai.git
cd Skillgap_ai

python -m venv venv
source venv/bin/activate

pip install -r requirements.txt

### Environment Setup

Create a `.env` file in the project root:

ANTHROPIC_API_KEY=your_api_key_here

### Run the App

streamlit run app.py

Then open http://localhost:8501 in your browser.

---

## 📁 Project Structure

Skillgap_ai/
├── app.py
├── requirements.txt
├── utils/
├── .env.example
└── README.md

---

## 📸 Screenshots

> Add screenshots or a short GIF of the app in action here.

![App Screenshot](assets/screenshot1.png)

![Match Results](assets/screenshot2.png)

---

## 🗺️ Roadmap / Future Improvements

- [ ] Support multiple resume formats (PDF, DOCX)
- [ ] Batch processing for multiple job descriptions
- [ ] Downloadable match report (PDF export)
- [ ] Score history / candidate dashboard

---

## 👤 Author

**Bapathi Venkatesh Reddy**
B.Tech, Artificial Intelligence | AI/ML & IT Fresher
📧 bapathivenkateshreddy9@gmail.com
🔗 [LinkedIn](https://www.linkedin.com/in/venkatesh-reddy-bapathi-769917349) · [GitHub](https://github.com/Venky1316)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
