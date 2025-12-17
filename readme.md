## click_me - https://smart-study-assistant-pdf-to-notes-quiz-generator-00.streamlit.app/
# 📘 Smart Study Assistant

An AI-powered study assistant that converts **text or PDFs** into  
✔ structured notes  
✔ auto-generated quizzes  
✔ downloadable Word documents  

Built using **Streamlit + LangChain + Google Gemini models**.

---

## 🚀 Features

- 📄 Upload PDF or paste text
- 📝 AI-generated notes (Short / Medium / Detailed)
- ❓ Automatically creates quiz questions with answers
- ⚡ Parallel LLM execution for faster output
- 📥 Download notes as a Word document
- 🎛 User-friendly Streamlit UI

---

## 🛠 Tech Stack

- **Python**
- **Streamlit**
- **LangChain**
- **Google Gemini (2.5 Flash & Pro)**
- **Groq (optional)**
- **PyPDF**
- **python-docx**

---

## 🧠 Architecture

- Parallel LLM chains using `RunnableParallel`
- Gemini Flash → Notes Generation
- Gemini Pro → Quiz Generation
- Output merged into a single study guide

---

## Demo

---

## ⚙️ Setup Instructions

1. Clone the repo
```bash
git clone https://github.com/yourusername/smart-study-assistant.git
cd smart-study-assistant

```

## Create Environments
``` bash
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
```

## Add API KEYS
GOOGLE_API_KEY=your_key

GROQ_API_KEY=your_key


---

## 9️⃣ Git Commands (Step-by-Step)

```bash
git init
git add .
git commit -m "Initial commit: Smart Study Assistant using Gemini"
git branch -M main
git remote add origin https://github.com/yourusername/smart-study-assistant.git
git push -u origin main
```

## 📦 Dependency Management

Dependencies are managed using **pip-tools**.

- `requirements.in` contains top-level project dependencies
- `requirements.txt` is auto-generated with pinned versions for reproducibility

To install:
```bash
pip install -r requirements.txt
```



## 👨‍💻 Author

Kishlay Kumar

Aspiring Data Scientist | GenAI & ML Enthusiast
