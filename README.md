

## 📊 Automated Applicant Tracking System (ATS) Resume Analyzer

This project allows users to upload their resumes (PDF) and compare them against a job description. It leverages a Flan-T5 large model to evaluate resumes, detect missing keywords, and estimate a match percentage.

### Features

-Upload PDF Resumes – Extracts text from uploaded PDF files.

-ATS Evaluation – Provides insights into resume strengths and weaknesses.

-Missing Keywords Detection – Highlights job-relevant keywords missing from the resume.

-Match Percentage – Estimates how well a resume matches a given job description.

-Streamlit Web Interface – User-friendly, interactive web app.

<img width="1801" height="670" alt="image" src="https://github.com/user-attachments/assets/e6a844ba-b0be-4b3d-b125-bce415f1c976" />
<img width="1918" height="761" alt="image" src="https://github.com/user-attachments/assets/5101828b-894e-4be9-b3fb-1520ce2e69cc" />
<img width="1789" height="663" alt="image" src="https://github.com/user-attachments/assets/0967812c-60ec-4e45-8f00-48751429b558" />
<img width="1860" height="719" alt="image" src="https://github.com/user-attachments/assets/339b9bc1-acac-4767-985b-8f0689a665ea" />
<img width="1916" height="837" alt="image" src="https://github.com/user-attachments/assets/7830cf7a-592b-4f64-a6c6-cfe5a1a4cbc7" />
<img width="1901" height="786" alt="image" src="https://github.com/user-attachments/assets/ba6ef871-2266-4955-8466-9b11523a2bdd" />


## How it Works

-PDF to Text – PyPDF2 extracts raw text from uploaded resumes.

-Prompt Flan-T5 – Prompts the LLM to evaluate resume vs job description.

-Parse Response – Extract missing keywords, final thoughts, and match percentage.

-Display in UI – Results are shown in a user-friendly Streamlit interface.
