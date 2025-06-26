# 📊 Investor Summary Extractor using Gemini + LangChain + Vertex AI

This project is a fully functional Google Colab notebook that extracts investor-relevant insights from company financial PDFs using **Google Gemini 2.0 Flash**, **LangChain**, and **Vertex AI**.

---

## 🚀 Features

✅ Extracts critical financial insights for investors:
- **Growth Prospects**
- **Business Changes**
- **Key Triggers / Catalysts**
- **Material Impact on Earnings**

✅ Built with:
- 🔹 `LangChain`
- 🔹 `Google Gemini 2.0 Flash` via `Vertex AI`
- 🔹 `PyMuPDF` for accurate PDF parsing
- 🔹 `RecursiveCharacterTextSplitter` for intelligent text chunking
- 🔹 JSON-parsed output per chunk for structured summaries

✅ Works on:
- Company financial reports
- Investor presentations
- Analyst research PDFs

---

## 🧠 How It Works

1. Upload a PDF via Colab
2. Text is extracted using PyMuPDF
3. Split into intelligent chunks
4. Each chunk is processed with Gemini using an investor-centric prompt
5. Results are parsed, filtered, and merged into a final summary

---

## 🛠️ Installation (in Colab)

```bash
!pip install -q langchain langchain-community google-generativeai langchain-google-vertexai PyMuPDF tiktoken
```

---

## 📎 Google Colab Link

> 👉 [Open in Colab](https://colab.research.google.com/) and upload the `Investor_Summary_Gemini.ipynb` file

---

## 📁 Repository Structure
```
.
├── Secure_Investor_Summary_Gemini.ipynb   # Main notebook
├── README.md                              # Project overview
└── requirements.txt                       # Optional: for pip install
```

---

## 🔐 API Key Safety
- Uses `getpass()` in Colab for secure input
- No hardcoded keys
- Avoids API abuse or accidental sharing

---

## 🤖 Author
**Vamsi Krishna Prasad Manchiraju**  
Built using GPT & Gemini for AI-driven investment intelligence

---

## 📄 License
MIT License (or add your custom one)

---

## 📬 Contact
Need help integrating it with a dashboard or custom tool? Reach out!

