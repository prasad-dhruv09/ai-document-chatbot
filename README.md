🧠 AI Document Chatbot

Chat with your documents using LlamaIndex + OpenRouter + HuggingFace Embeddings.

✅ Features

Upload PDF, TXT, DOCX, CSV

Extract + embed text automatically

Chat with context-aware answers

Uses HuggingFace MiniLM-L6-v2

LlamaIndex chat engine

Secure API key through .env

Clean Streamlit UI

🛠 Tech Stack

Streamlit (Frontend)

LlamaIndex (Vector Index + Query Engine)

OpenRouter API (LLM Provider)

HuggingFace Embeddings

Python

📦 Project Structure
project/
│── app.py
│── style.css
│── requirements.txt
│── README.md
│── .gitignore
│── .env
└── data/

🔧 Installation
1️⃣ Clone the repo
git clone https://github.com/your-username/your-repo.git
cd your-repo

2️⃣ Install dependencies
pip install -r requirements.txt

3️⃣ Add your API key

Create a .env file:

OPENROUTER_API_KEY=your_openrouter_key_here

4️⃣ Run the app
streamlit run app.py

📁 Supported File Types

PDF

TXT

DOCX

CSV
(Max size: 200MB per file)

🧠 How It Works
Upload File → Extract Text → Create Embeddings →
Vector Index → Ask Question → Get Context-aware Answer

🖼️ Screenshots (Add your own)
./assets/home.png
./assets/upload.png
./assets/chat.png

🤝 Contributing

Feel free to fork and improve the project.

⭐ Support

If you like the project, please ⭐ the repository.

📜 License

MIT License.