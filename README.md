# 📃 AI Resume Critiquer

AI-powered resume feedback tool using Streamlit and Google Gemini API.

Upload your resume (PDF or TXT), specify the job role you're applying for (optional), and receive actionable, AI-generated feedback on how to improve your resume.

## 🚀 Features

- 📄 Upload PDF or TXT resumes
- 🎯 Tailored feedback for specific job roles
- 🤖 AI-generated analysis using Google Gemini
- ⚡ Built with Streamlit for quick deployment

## 🛠️ Installation

### 1️⃣ Clone the repository
```bash
git clone https://github.com/yourusername/ai-resume-critiquer.git
cd ai-resume-critiquer
```

### 2️⃣ Install dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Set up environment variables
Create a `.env` file in the project root with your Google Gemini API key:

```ini
GENAI_API_KEY=your_google_gemini_api_key
```

### 4️⃣ Run the application
```bash
streamlit run app.py
```

## 📂 File Structure

```
ai-resume-critiquer/
├── app.py          # Main Streamlit app
├── .env            # API Key (not committed)
├── requirements.txt
└── README.md
```

## 🧩 Requirements

- Python 3.8+
- Streamlit
- PyPDF2
- google-generativeai
- python-dotenv

## 🗝️ API Key Setup

You need a **Google Gemini API key** to use this app. Set it in the `.env` file like this:

```ini
GENAI_API_KEY=your_google_gemini_api_key
```

## 🙌 Contributing

Pull requests and feature suggestions are welcome!

