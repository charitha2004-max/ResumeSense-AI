🎯 ResumeSense AI – AI Resume Analyzer
📌 Project Overview

ResumeSense AI is an AI-powered web application designed to help users evaluate and optimize their resumes against job descriptions.

The application analyzes uploaded resumes using Artificial Intelligence and provides ATS-style feedback, including:

✅ Matching Skills
❌ Missing Skills
💪 Resume Strengths
💡 Personalized Improvement Suggestions

The system assists job seekers in improving their resumes for better compatibility with Applicant Tracking Systems (ATS) and enhances their chances of securing interviews by providing actionable recommendations.

🎯 Objectives
Analyze resumes against job descriptions using Artificial Intelligence.
Provide ATS-style resume evaluation.
Identify matching and missing skills.
Generate personalized resume improvement suggestions.
Simplify the resume optimization process for job seekers.
👤 User Features
📄 Upload Resume in PDF format.
💼 Paste any Job Description.
🤖 Analyze Resume using AI.
📊 View ATS Match Score.
✅ View Matching Skills.
❌ View Missing Skills.
💪 View Resume Strengths.
💡 Receive AI-generated improvement suggestions.
📥 Download Professional PDF Analysis Report.
🤖 AI Features
📊 ATS Resume Analysis

Compares the uploaded resume with the provided job description and evaluates the overall compatibility.

✅ Skill Matching

Identifies the skills that are present in both the resume and the job description.

❌ Missing Skill Detection

Highlights important skills or keywords that are missing from the resume.

💪 Resume Strength Analysis

Identifies the strongest areas of the resume based on the job description.

💡 AI Suggestions

Generates personalized recommendations to improve resume quality and ATS compatibility.

⚙️ System Workflow
📄 User uploads a Resume in PDF format.
💼 User pastes the desired Job Description.
📑 Resume text is extracted using PyPDF2.
🤖 DeepSeek AI analyzes the resume against the job description.
📊 ATS score and detailed analysis are generated.
👀 User views the complete analysis report.
📥 User downloads the report as a professional PDF.
🏗️ System Architecture
🎨 Frontend
Streamlit
⚙️ Backend
Python
🤖 AI Service
OpenRouter API
DeepSeek Chat Model
📄 PDF Processing
PyPDF2
ReportLab
🧪 Algorithms & Logic Used
📄 PDF Text Extraction using PyPDF2
🧠 Prompt Engineering for AI Analysis
🤖 AI-Assisted Resume Evaluation
📊 ATS-Style Skill Matching
💡 AI-Based Recommendation Generation
📑 PDF Report Generation using ReportLab
🗃️ Input Details

The application accepts the following inputs:

📄 Resume (PDF)
💼 Job Description
📊 Generated Output
ATS Match Score
Matching Skills
Missing Skills
Resume Strengths
Improvement Suggestions
📈 Result Analysis
✅ Successfully extracts resume content from PDF documents.
✅ Accurately compares resumes with job descriptions.
✅ Generates ATS-style compatibility scores.
✅ Identifies relevant and missing skills.
✅ Provides AI-generated recommendations.
✅ Produces downloadable professional PDF reports.
🚀 How to Run the Project
📌 Prerequisites
Python 3.10 or above
OpenRouter API Key
Required Python Libraries
▶️ Steps
1️⃣ Clone the Repository
2️⃣ Navigate to the Project Folder
3️⃣ Install Dependencies
pip install -r requirements.txt
4️⃣ Create a .env File
OPENROUTER_API_KEY=your_api_key
5️⃣ Run the Application
streamlit run app.py
6️⃣ Open the Local Streamlit URL in Your Browser
🔮 Future Enhancements
📄 Support for DOCX Resume Uploads
🎯 Resume Keyword Optimization
📈 Interactive Skill Comparison Charts
📚 Resume Score History Tracking
🔄 Multiple Resume Version Comparison
☁️ Cloud Deployment using Streamlit Community Cloud
🔗 LinkedIn Profile Analysis Integration
🏁 Conclusion

ResumeSense AI provides an intelligent and user-friendly solution for evaluating resumes against job descriptions using Artificial Intelligence.

By combining AI-powered analysis with ATS-style feedback, the application helps users identify skill gaps, improve resume quality, and enhance their chances of succeeding in today's competitive job market.

👤 Developer Details
👨‍💻 Developer

Charitha H K

📂 Project Type

AI-Powered Resume Analyzer

💻 Technology Stack
Python
Streamlit
OpenRouter API
DeepSeek AI
PyPDF2
ReportLab
⭐ Project Highlights

✅ AI-Powered Resume Analysis

✅ ATS Score Generation

✅ Intelligent Skill Matching

✅ Missing Skill Identification

✅ Personalized Resume Suggestions

✅ Professional PDF Report Generation

✅ Interactive Streamlit Interface

✅ Modern LLM Integration using DeepSeek AI
