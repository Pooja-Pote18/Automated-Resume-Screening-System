# Automated-Resume-Screening-System


This project is an **Automatic Resume Analysis Tool** that helps HR teams, recruiters, and students analyze resumes.  
It extracts text from resumes (`PDF` & `DOCX`), preprocesses using **NLP**, compares against a given Job Description (JD),  
and generates an **ATS Score (%)** for ranking candidates.

✅ Features:
- Extracts text from resumes (`.pdf`, `.docx`)
- Cleans & preprocesses text (stopwords removal, lemmatization)
- Extracts keywords using **NLTK**
- Calculates **ATS Score (%)** based on JD matching
- Ranks candidates & exports results to `CSV`

⚙️ Tech Stack
- Python 3.10+
- NLTK (NLP processing)
- PyMuPDF (PDF extraction)
- python-docx (DOCX extraction)
- Pandas, NumPy (data analysis)

