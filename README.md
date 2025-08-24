# AI-Powered Resume Screener

Automatically rank resumes against a job description using **TF-IDF + skill matching**.  
Supports **PDF, DOCX, and TXT** resumes.

## ✨ Features
- Extracts text from resumes
- Finds emails & phone numbers
- Matches skills against a vocabulary list
- Computes:
  - Cosine similarity between resume & job description
  - Skill overlap score
- Outputs a ranked CSV

## 🛠 Tech Stack
- Python 3.9+
- [PyMuPDF](https://pymupdf.readthedocs.io/) (`fitz`)
- [python-docx](https://python-docx.readthedocs.io/)
- [scikit-learn](https://scikit-learn.org/)
- pandas, numpy

## 📦 Installation
```bash
pip install pymupdf python-docx scikit-learn pandas numpy
