# CVision – AI-Powered Resume Checker

**CVision** is an AI-powered resume analysis tool built using **Python**, **Flask**, and **Streamlit**, integrated with the **Google Gemini API** to provide professional resume review and feedback.  
It supports `.pdf` and `.docx` files, extracts structured information, and uses AI to generate actionable improvement suggestions.

---

## 🚀 Features
- **Multiple Format Support** – Upload `.pdf` or `.docx` resumes.
- **Advanced AI Feedback** – Google Gemini API analyzes clarity, achievements, keywords, formatting, and improvements.
- **Dual Interface** – Flask for backend logic, Streamlit for interactive UI.
- **Automatic Data Extraction** – Pulls name, email, phone, LinkedIn, GitHub, skills, and education from resumes.
- **Keyword & ATS Optimization** – AI checks for job role-specific keywords.
- **Actionable Suggestions** – Clear and specific recommendations for better job readiness.

---

## 🛠️ Tech Stack
**Backend**
- Python 3.x
- Flask (API)
- Google Gemini API

**Frontend**
- Streamlit (User Interface)

**Libraries**
- `google-generativeai` – AI integration
- `fitz` (PyMuPDF) – PDF text extraction
- `python-docx` – Word file text extraction
- `re` – Regex parsing
- `dotenv` – Environment variable handling
- `requests` – API calls

---

## 📦 Installation & Setup

1. **Clone Repository**
   ```bash
   git clone https://github.com/MohitKumar987/CVision.git
   cd CVision
