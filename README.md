# 🎯 ResumeSense AI – AI Resume Analyzer

> **An AI-powered ATS Resume Analyzer that evaluates resumes against job descriptions and provides intelligent ATS-style feedback using DeepSeek AI via OpenRouter.**

---

# 📌 Project Overview

ResumeSense AI is an AI-powered web application designed to help users evaluate and optimize their resumes against job descriptions.

The application analyzes uploaded resumes using Artificial Intelligence and provides ATS-style feedback, including:

- ✅ Matching Skills
- ❌ Missing Skills
- 💪 Resume Strengths
- 💡 Personalized Improvement Suggestions
- 📊 ATS Match Score

The system assists job seekers in improving their resumes for better compatibility with Applicant Tracking Systems (ATS) and enhances their chances of securing interviews by providing actionable recommendations.

---

# 🎯 Objectives

- Analyze resumes against job descriptions using Artificial Intelligence
- Provide ATS-style resume evaluation
- Identify matching and missing skills
- Generate personalized resume improvement suggestions
- Simplify the resume optimization process for job seekers

---

# 👤 User Features

- 📄 Upload Resume in PDF format
- 💼 Paste any Job Description
- 🤖 Analyze Resume using AI
- 📊 View ATS Match Score
- ✅ View Matching Skills
- ❌ View Missing Skills
- 💪 View Resume Strengths
- 💡 Receive AI-generated Improvement Suggestions
- 📥 Download Professional PDF Analysis Report

---

# 🤖 AI Features

## 📊 ATS Resume Analysis

Compares the uploaded resume with the provided job description and evaluates the overall compatibility.

---

## ✅ Skill Matching

Identifies the skills that are present in both the resume and the job description.

---

## ❌ Missing Skill Detection

Highlights important skills or keywords that are missing from the resume.

---

## 💪 Resume Strength Analysis

Identifies strong areas within the resume based on the job description.

---

## 💡 AI Suggestions

Generates personalized recommendations to improve resume quality and ATS compatibility.

---

# ⚙️ System Workflow

1. 📄 User uploads a Resume in PDF format.
2. 💼 User pastes the desired Job Description.
3. 📚 Resume text is extracted using PyPDF2.
4. 🤖 AI analyzes the resume against the job description.
5. 📊 ATS Score and detailed analysis are generated.
6. 👀 User views the analysis report.
7. 📥 User downloads the report as a professional PDF.

---

# 🏗️ System Architecture

## 🎨 Frontend

- Streamlit

### Backend

- Python

### AI Service

- OpenRouter API
- DeepSeek Chat Model

### PDF Processing

- PyPDF2
- ReportLab

---

# 🧪 Algorithms & Logic Used

- 📄 PDF Text Extraction using PyPDF2
- 🧠 Prompt Engineering for AI Analysis
- 🤖 AI-assisted Resume Evaluation
- 📊 ATS-style Skill Matching
- 💡 AI-generated Recommendation System
- 📥 PDF Report Generation using ReportLab

---

# 🗃️ Input Details

The system processes the following inputs:

- 📄 Resume (PDF)
- 💼 Job Description

The generated analysis includes:

- 📊 ATS Match Score
- ✅ Matching Skills
- ❌ Missing Skills
- 💪 Resume Strengths
- 💡 Improvement Suggestions

---

# 📊 Result Analysis

- ✅ Successfully extracts resume content from PDF documents
- 🤖 Accurately compares resumes with job descriptions
- 📊 Generates ATS-style compatibility score
- 🎯 Identifies relevant and missing skills
- 💡 Provides AI-generated recommendations for resume enhancement
- 📥 Produces downloadable professional PDF reports

---

# 🚀 How to Run the Project

## 📋 Prerequisites

- Python 3.10 or above
- OpenRouter API Key
- Required Python Libraries

---

## 📦 Installation

Clone the repository

```bash
git clone https://github.com/charitha2004-max/ResumeSense-AI.git
```

Navigate to the project folder

```bash
cd ResumeSense-AI
```

Install dependencies

```bash
pip install -r requirements.txt
```

Create a `.env` file

```env
OPENROUTER_API_KEY=your_api_key
```

Run the application

```bash
streamlit run app.py
```

Open the local Streamlit URL in your browser.

---

# 🔮 Future Enhancements

- 📄 Support for DOCX Resume Uploads
- 🎯 Resume Keyword Optimization Recommendations
- 📊 Interactive Skill Comparison Charts
- 📈 Resume Score History Tracking
- 🔄 Multiple Resume Version Comparison
- ☁️ Cloud Deployment using Streamlit Community Cloud
- 💼 LinkedIn Profile Analysis Integration

---

# 🏁 Conclusion

ResumeSense AI provides an intelligent and user-friendly solution for evaluating resumes against job descriptions using Artificial Intelligence.

By combining AI-powered analysis with ATS-style feedback, the application helps users identify skill gaps, improve resume quality, and enhance their chances of succeeding in today's competitive job market.

---

# 👨‍💻 Developer Details

**Developer**

**Charitha H K**

---

**Project Type**

AI-Powered Resume Analyzer

---

# 🛠️ Technology Stack

- 🐍 Python
- 🎨 Streamlit
- 🤖 OpenRouter API
- 🧠 DeepSeek AI
- 📄 PyPDF2
- 📑 ReportLab

---

