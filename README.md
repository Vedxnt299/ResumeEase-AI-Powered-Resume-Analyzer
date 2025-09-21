# ResumeEase – AI-Powered Resume Analyzer

ResumeEase is a Streamlit web app that scans PDF resumes, extracts text with OCR,  
and uses Google Generative AI to give insights and improvement tips.

## Features
- Extracts text from PDF resumes (even scanned PDFs) using **pdfplumber** + **pytesseract**.
- Analyzes content with **Google Generative AI** for skills, summary, and ATS optimization.
- Simple **Streamlit** UI for quick upload and results.

## Installation
```bash
git clone https://github.com/<your-username>/ResumeEase.git
cd ResumeEase
pip install -r requirements.txt
streamlit run app.py
