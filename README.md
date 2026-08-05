# 📺 VIDGENIUS

VIDGENIUS is an **open-source RAG-powered AI tool** that transforms YouTube videos into:

- 💬 **Interactive chat experiences** — ask questions directly to the video content.  
- 📝 **Smart, structured notes** — automatically extract key topics and generate bullet-pointed summaries.  
- 🌍 **Multi-language support** — input any video with a language code (e.g., `en`, `hi`) and get **English-translated notes**.  

It leverages **Streamlit** for UI, **LangChain** for RAG and embeddings, and **Google Gemini models** for AI-driven understanding and translation.

---

## 🎬 Project Demo
[https://github.com/Thakurbhanupratap/VIDGENIUS/blob/development/assets/VidGenius_demo.mp4](https://github.com/user-attachments/assets/ea61156e-9eed-47b0-9914-ea4cd8503825)

## ⚡ Features

- 🔗 Paste **YouTube URL** and select video language.  
- 💬 **Chat with Video**: Ask questions, get answers from transcript context.  
- 📝 **Notes for You**: Generate concise, structured notes and highlight important topics.  
- 🌍 **Automatic translation** of transcripts into English.  
- 📚 **Chunking & vector store** for efficient similarity search.  
- 🤝 **Open-source** and easy for contributors to enhance and extend.  

---

## 🛠️ Tech Stack

| Layer                        | Technology Used |
|------------------------------|-----------------|
| **Frontend / UI**            | Streamlit |
| **AI / NLP**                 | LangChain, GoogleGenerativeAI, ChatGoogleGenerativeAI |
| **Embeddings & Vector Store**| Chroma, GoogleGenerativeAIEmbeddings |
| **Transcript Extraction**    | youtube_transcript_api |
| **Translation & Summarization** | Gemini-2.5 AI model |

---

## 🚀 Quick Start

1️⃣ **Clone the Repository**
```bash
git clone https://github.com/Thakurbhanupratap/VIDGENIUS.git
cd VIDGENIUS
```

2️⃣ **Install Dependencies**
```bash
pip install -r requirements.txt
```

3️⃣ **Set Environment Variables**
```bash
GOOGLE_API_KEY=<your_google_api_key>
```

4️⃣ **Run the App**
```
streamlit run src/app.py
```

5️⃣ **Use the App**
  - Enter YouTube video URL.
  - Enter language code (en for English).
  - Select task: Chat with Video or Notes for You.
  - Click Start Processing and interact with the AI.

## 📄 Code Structure
```bash
├── src/
│   ├── app.py
│   ├── core/
│   │   ├── functions.py
│   │   ├── youtube_utils.py
│   │   └── rag_pipeline.py
├── requirements.txt
├── README.md
├── LICENSE
├── .env.example
```

## 🤝 Contributing
We welcome contributions!
  - Fork the repo
  - Create a feature branch: git checkout -b feature/new-feature
  - Commit changes: git commit -m "Add new feature"
  - Push to branch: git push origin feature/new-feature
  - Open a pull request using the PR template
Please follow our [Code of Conduct](CODE_OF_CONDUCT.md) and [Contributing Guidelines](CONTRIBUTING.md).

## 📜 License
This project is licensed under the MIT License — see [LICENSE](LICENSE) for details.

## 📧 Contact / Support
For questions or issues, contact: bhanugahlot2003@gmail.com
