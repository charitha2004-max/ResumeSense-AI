🎯 ResumeSense AI – AI Resume Analyzer

📌 Project Overview

ResumeSense AI is an AI-powered web application designed to help users evaluate and optimize their resumes against job descriptions. The application analyzes uploaded resumes using Artificial Intelligence and provides ATS-style feedback, including matching skills, missing keywords, strengths, and improvement suggestions.

The system assists job seekers in improving their resumes for better compatibility with Applicant Tracking Systems (ATS) and enhances their chances of securing interviews by providing actionable recommendations.

🎯 Objectives

To analyze resumes against job descriptions using Artificial Intelligence
To provide ATS-style resume evaluation
To identify matching and missing skills
To generate personalized resume improvement suggestions
To simplify the resume optimization process for job seekers
👤 User Features
Upload resume in PDF format
Paste any job description
Analyze resume using AI
View ATS Match Score
View Matching Skills
View Missing Skills
View Resume Strengths
Receive AI-generated improvement suggestions
Download professional PDF analysis report

🤖 AI Features
ATS Resume Analysis

Compares the uploaded resume with the provided job description and evaluates overall compatibility.

Skill Matching

Identifies the skills present in both the resume and the job description.

Missing Skill Detection

Highlights important skills or keywords missing from the resume.

Resume Strength Analysis

Identifies strong areas within the resume based on the job description.

AI Suggestions

Generates personalized recommendations to improve resume quality and ATS compatibility.


⚙️ System Workflow

User uploads a resume in PDF format.
User pastes the desired job description.
Resume text is extracted using PyPDF2.
AI model analyzes the resume against the job description.
ATS score and detailed analysis are generated.
User views the analysis report.
User downloads the report as a professional PDF.

🏗️ System Architecture

Frontend
Streamlit
Backend
Python
AI Service
OpenRouter API
DeepSeek Chat Model
PDF Processing
PyPDF2
ReportLab

🧪 Algorithms & Logic Used

PDF text extraction using PyPDF2
Prompt Engineering for AI analysis
AI-assisted resume evaluation
ATS-style skill matching
AI-generated recommendation system
PDF report generation using ReportLab

🗃️ Input Details

The system processes the following inputs:

Resume (PDF)
Job Description

The generated analysis includes:

ATS Match Score
Matching Skills
Missing Skills
Resume Strengths
Improvement Suggestions

📊 Result Analysis

Successfully extracts resume content from PDF documents
Accurately compares resumes with job descriptions
Generates ATS-style compatibility score
Identifies relevant and missing skills
Provides AI-generated recommendations for resume enhancement
Produces downloadable professional PDF reports

🚀 How to Run the Project

Prerequisites
Python 3.10 or above
OpenRouter API Key
Required Python Libraries
Steps

Clone the repository.

Navigate to the project folder.

Install dependencies:

pip install -r requirements.txt

Create a .env file:

OPENROUTER_API_KEY=your_api_key

Run the application:

streamlit run app.py

Open the local Streamlit URL in your browser.

🔮 Future Enhancements

Support for DOCX resume uploads
Resume keyword optimization recommendations
Interactive skill comparison charts
Resume score history tracking
Multiple resume version comparison
Cloud deployment using Streamlit Community Cloud
Integration with LinkedIn profile analysis

🏁 Conclusion

ResumeSense AI provides an intelligent and user-friendly solution for evaluating resumes against job descriptions using Artificial Intelligence. By combining AI-powered analysis with ATS-style feedback, the application helps users identify skill gaps, improve resume quality, and enhance their chances of succeeding in today's competitive job market.


👤 Developer Details

Developer:
Charitha H K

Project Type:
AI-Powered Resume Analyzer

Technology Stack:
Python, Streamlit, OpenRouter API, DeepSeek AI, PyPDF2, ReportLab
