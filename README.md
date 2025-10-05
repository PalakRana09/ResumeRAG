ResumeRAG – AI-Powered Resume Search & Job Match (Django)

ResumeRAG is a minimal full-stack Django web application designed to upload, manage, and match resumes with job descriptions using AI-powered techniques (TF-IDF + cosine similarity).
This project is ideal for hackathons, portfolio showcase, or recruiters looking for a quick solution to shortlist candidates.

🔹 Features

Resume Upload

Upload resumes in .txt format or paste text directly.

Automatically stores resumes with name, email, and content.

Resume Management

View a list of all uploaded resumes.

Preview resume text directly in the web app.

Job Matching

Paste a job description or required skills.

System calculates fit scores for each candidate using TF-IDF vectorization and cosine similarity.

Ranked results displayed with snippets for quick review.

Simple HTML Frontend

Clean and responsive interface built with Django templates and CSS.

Easy navigation: Home → Upload Resume → View Resumes → Job Match.

Admin Panel

Optional Django admin for advanced management (http://127.0.0.1:8000/admin).

💻 Tech Stack
Layer	Technology
Backend	Django 4.x, SQLite
Frontend	Django templates (HTML/CSS)
AI Matching	Python, scikit-learn (TF-IDF & cosine similarity)
Dependencies	numpy, scikit-learn, Django
