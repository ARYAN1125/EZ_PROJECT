# 🧠 GenAI Smart Research Summarizer

An AI-powered assistant that can **read**, **understand**, **summarize**, and **quiz** you on uploaded documents (PDF/TXT).  
Built with ❤️ for the **EZ Works GenAI Internship Assignment**.

---

## 🔧 Features

- 📄 **Document Upload** – Supports `.pdf` and `.txt` files.
- ✍️ **Auto Summary** – Extracts and summarizes content in under **150 words**.
- 💬 **Ask Anything Mode** – Free-form intelligent Q&A on uploaded content.
- 🎯 **Challenge Me Mode** – Generates logic-based questions and evaluates your answers.
- 🧠 **Fully Local Execution** – Powered by Hugging Face models; no API keys needed.

---

## 🛠️ Tech Stack

- **Python** 🐍
- **Streamlit** 🖼️ – for the interactive web app interface.
- **HuggingFace Transformers** 🤗 – for NLP tasks.
- **pdfminer.six** – for parsing PDFs.

---

## 🚀 Getting Started

### 🔨 Installation Steps

```bash
# 1. Clone the repo
git clone https://github.com/ARYAN1125/genai-summarizer.git
cd genai-summarizer

# 2. Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the app
streamlit run app.py
