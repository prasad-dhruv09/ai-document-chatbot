# 🧠 AI Document Chatbot
**Chat with your documents using LlamaIndex + OpenRouter + HuggingFace Embeddings.**  
Upload PDFs, Docs, CSVs and ask anything — get context-aware answers instantly.

---

## ⭐ Features

✅ Upload **PDF, TXT, DOCX, CSV**  
✅ Automatic text extraction from all formats  
✅ Uses **MiniLM-L6-v2 embeddings** for accuracy  
✅ LlamaIndex **Vector Store + Chat Engine**  
✅ Chat with memory — multi-turn conversation  
✅ Clean & modern **Streamlit UI**  
✅ Secure API key handling through `.env`  
✅ Sidebar **chat history**  
✅ Custom CSS support for modern UI  

---

## 🛠 Tech Stack

| Layer | Technology |
|------|------------|
| Frontend | Streamlit |
| Embeddings | HuggingFace MiniLM-L6-v2 |
| LLM | OpenRouter (GPT Models) |
| Vector Index | LlamaIndex |
| Backend | Python |
| Styling | Custom CSS |

---

## 📁 Project Structure

project/
│── app.py
│── style.css
│── requirements.txt
│── README.md
│── .gitignore
│── .env # your API key (NOT uploaded to GitHub)
└── data/ # optional folder for sample docs

---

##📁 Supported File Types

File Type	Support
✅ PDF	Yes
✅ TXT	Yes
✅ DOCX	Yes
✅ CSV	Yes

---

##🧠 How It Works
1️⃣ Upload Document
2️⃣ Text extracted using PyPDF2 / python-docx / pandas
3️⃣ Converted into embeddings (MiniLM-L6-v2)
4️⃣ LlamaIndex creates a vector index
5️⃣ You ask → AI searches → gives accurate, contextual answers
6️⃣ Chat history stored locally in session
---

##🖥️ Screenshots
![Screenshot](https://github.<img width="1908" height="890" alt="Screenshot 2025-11-06 115705" src="https://github.com/user-attachments/assets/ff9330c8-69b8-4229-9ce4-5e0de099b2bb" />
---

##🤝 Contributing
Pull requests are welcome!
If you find a bug or have an idea for improvement — feel free to contribute.

---

##⭐ Support
If you like this project, please star ⭐ the repository.

---
##📜 License
This project is licensed under the MIT License.
