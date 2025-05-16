# AI Resume Analyzer

The **AI Resume Analyzer** is a smart web application designed to help job seekers evaluate how well their resume aligns with a given job description using AI-powered similarity scoring and feedback.

## Features

- **Resume and Job Description Upload:** Supports PDF and DOCX formats for resumes.
- **AI Matching Engine:** Uses `sentence-transformers` (MiniLM) from Hugging Face to generate semantic embeddings of resume and job description, and computes a **match score** using cosine similarity.
- **Real-Time Feedback:** Provides intelligent suggestions on missing or weak areas in the resume based on job description keywords.
- **Visual Score Representation:** Displays match percentage with score bars and keyword highlights.
- **Technologies Used:**
  - Python, Flask
  - HTML, CSS, JavaScript
  - [`sentence-transformers`](https://huggingface.co/sentence-transformers) for embeddings

## How It Works

1. **Upload Resume:** The user uploads their resume (PDF/DOCX).
2. **Paste Job Description:** The user inputs the job description.
3. **AI Analysis:** The app extracts text, computes semanticai-resume-analyzer
4. **Result Displayed:** A match percentage and keyword feedback are shown.

## Folder Structure (Simplified)
│Ai-resume-analyzer
├── app.py
├── utils/
│ ├── parser.py
│ └── analyzer.py
│
├── templates/
│ ├── index.html
│ ├── result.html
│ └── upload.html
│
├── static/
│ └── style.css
├── uploads/
├── requirements.txt
└── README.md similarity, and identifies keyword gaps.

