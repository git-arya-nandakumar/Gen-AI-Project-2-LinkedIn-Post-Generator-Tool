## Gen-AI-Project-2-LinkedIn-Post-Generator-Tool 🚀
An AI-powered LinkedIn post generation tool that analyzes a creator’s past posts and generates new posts in a similar writing style using LLMs and few-shot learning.

This project was built as a learning and practice project by following the Codebasics GenAI tutorial series and implementing the concepts hands-on.

## 📌 Project Overview
This application helps LinkedIn influencers or content creators generate future posts based on their existing writing style.

The user can provide previous LinkedIn posts, and the system will:

- Extract topics and writing patterns
- Identify language and post length
- Use similar historical posts as few-shot examples
- Generate a brand-new LinkedIn post that matches the creator’s tone and style

Example:

Suppose a LinkedIn influencer named Mohan regularly writes about AI, career growth, and productivity. By feeding his old posts into the tool, the application learns his style and generates new posts that sound similar to how Mohan naturally writes.

## ✨ Features
- 🔍 Analyze historical LinkedIn posts
- 🧠 Extract:
        - Topic
        - Language
        - Post length
- ✍️ Generate AI-powered LinkedIn posts
- 🎯 Few-shot prompting for writing style consistency
- 🌐 Streamlit-based interactive UI
- ⚡ Powered by Groq LLM API
- 📚 Beginner-friendly GenAI project structure

## 🛠️ Tech Stack
### Frontend
Streamlit

### Backend / AI
Python
LangChain
Groq LLM API

### Data Processing
Pandas
Regex / Text Processing

### Environment & Tools
dotenv
Virtual Environment (venv)

## 🧠 How It Works
### Stage 1: Post Analysis

The application first analyzes previously written LinkedIn posts and extracts important metadata such as:

- Topic
- Writing language
- Post size/length
- Style patterns

This creates a structured dataset of historical posts.

### Stage 2: AI Post Generation

When the user selects:

- Topic
- Language
- Length

The system:

1. Finds similar historical posts
2. Uses them as few-shot examples
3. Sends the prompt to the LLM
4. Generates a new LinkedIn post in a similar tone and style

## 📂 Project Structure

- **main.py** : Streamlit application entry point
- **few_shot.py** : Few-shot example handling
- **post_generator.py** : LLM-based post generation
- **preprocess.py** : Data preprocessing utilities
- **llm_helper.py** : Groq LLM integration
- **requirements.txt** : Project dependencies
- **.env** : Environment variables
- **posts.json** : Historical LinkedIn posts

## 🎯 Learning Outcomes

Through this project, I learned:

- Prompt engineering
- Few-shot learning
- LLM integration using Groq
- Streamlit app development
- Text preprocessing techniques
- Building end-to-end GenAI applications

## 🚀 Future Improvements
- Add support for multiple influencers
- Save generated posts history
- Add LinkedIn post scheduling
- Improve topic clustering using embeddings
- Support image generation for posts
- Deploy using Docker / Cloud platforms

## 🙌 Acknowledgements

This project was inspired by and built while learning from the Codebasics Generative AI tutorials.

Special thanks to the Codebasics team for the educational content and project guidance.
