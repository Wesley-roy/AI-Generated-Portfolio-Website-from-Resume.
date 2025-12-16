# AI-Generated-Portfolio-Website-from-Resume

## 🧠 AI Portfolio Generator

An AI-powered **Streamlit application** that transforms your resume into a fully responsive **personal portfolio website — instantly**.

Upload your **PDF or DOCX resume**, and the app uses **Google Gemini (via LangChain)** to analyze your resume and generate a complete **HTML, CSS, and JavaScript portfolio website**, bundled as a downloadable ZIP file.

---

## 🚀 Features

- 📄 Upload resume in **PDF or DOCX** format  
- 🧠 AI-powered resume analysis using **Google Gemini**  
- 🌐 Automatically generates:
  - `index.html`
  - `style.css`
  - `script.js`
- 📦 One-click **ZIP download** of the complete website  
- 🎨 Modern, responsive portfolio layout  
- ⚡ Built with **Streamlit** for fast and interactive UI  

---

## 🛠️ Tech Stack

- **Python**
- **Streamlit**
- **LangChain**
- **Google Gemini API**
- **PyPDF2** (PDF parsing)
- **python-docx** (DOCX parsing)
- **dotenv** (environment variable management)

---
## 🔐 Environment Setup

- This app requires a Google Gemini API key.

- Create a .env file in the project root: gemini=YOUR_GOOGLE_API_KEY

-The app automatically loads the key using python-dotenv.

## 📦 Installation

- Clone the repository:

- git clone https://github.com/your-username/ai-portfolio-generator.git
cd ai-portfolio-generator

- Install dependencies:

- pip install -r requirements.txt

## Required Packages

- streamlit

- python-dotenv

- PyPDF2

- python-docx

- langchain-google-genai

## ▶️ Run the App

- Start the Streamlit application: streamlit run portfolio.py


- Then open your browser at: http://localhost:8501

## 🧩 How It Works

- User uploads a resume (PDF or DOCX)

- Resume text is extracted

- AI analyzes and structures resume data

## AI generates:

- HTML layout

- CSS styling

- JavaScript interactions

- Files are bundled into a ZIP

- User downloads the complete portfolio website

---

## 📁 Project Structure

```text
.
├── portfolio.py          # Main Streamlit application
├── index.html            # Generated portfolio HTML
├── style.css             # Generated CSS styles
├── script.js             # Generated JavaScript
├── portfolio_website.zip # Downloadable website bundle
├── .env                  # Environment variables (not committed)
└── README.md
