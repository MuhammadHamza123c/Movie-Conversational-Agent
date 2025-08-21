# 🎬 Movie Conversational Agent

A **conversational Movie Bot** built with **LangChain** that remembers conversation history and answers everything about movies:  
- Plot, history, cast & crew  
- Box office and trivia  
- Movie recommendations and quizzes  

Supports multiple LLMs:  
- **Gemini (gemini-2.5-flash)**  
- **Groq (deepseek-r1-distill-llama-70b)**  

---

## 🚀 Features
- Conversational bot with **memory** using `ConversationChain` and `ConversationBufferMemory`.
- Multi-LLM support for Gemini & Groq.
- Handles detailed movie queries: trivia, cast, recommendations, and box office info.
- Maintains context across multiple questions.
- Clean **Jupyter Notebook** implementations for each LLM.

---

## 📂 Project Structure

├── gemini_main.ipynb # Notebook using Gemini API

├── groq_main.ipynb # Notebook using Groq API

├── .gitignore # Hides .env and other sensitive files

└── README.md # Project documentation

### Create a .env file in the project root and add your API keys:
GROQ_API_KEY=your_groq_api_key_here

GEMINI_API_KEY=your_gemini_api_key_here

### Install dependencies

pip install -r requirements.txt


### Open the notebooks in Jupyter or Google Colab:

gemini_main.ipynb

groq_main.ipynb

### Run the cells and interact with your Movie Bot!


### 📚 Tech Stack

Python

Jupyter Notebook

LangChain (ConversationChain, ConversationBufferMemory)

Gemini API (gemini-2.5-flash)

Groq API (deepseek-r1-distill-llama-70b)

 ### 🤝 Contributing

Pull requests are welcome! For major changes, open an issue first to discuss what you would like to change.

### 📜 License

This project is licensed under the MIT License.




---

## ⚙️ Setup & Installation

1. **Clone the repository**
```bash
git clone https://github.com/MuhammadHamza123c/movie-conversational-agent.git
cd movie-conversational-agent
