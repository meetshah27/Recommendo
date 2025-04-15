# 🎧 Recommendo – GPT-Powered Music Playlist Generator

A conversational music recommendation app powered by **LangChain**, **LlamaIndex**, and **OpenAI’s GPT-3.5**. Recommendo creates mood-based playlists using natural language inputs, bringing AI-powered music discovery to life.

---

## 🚀 Project Overview

**Recommendo** is an intelligent playlist generator that understands user intent through plain language prompts and delivers personalized music suggestions. Built for music lovers and tech enthusiasts alike, it leverages advanced LLM tools to semantically search a structured music dataset of over 10,000 songs.

---

## ✨ Key Features

- 🧠 **GPT-3.5-powered LangChain agent** to understand conversational inputs
- 🎶 **Natural language-based playlist generation** (e.g., *"Uplifting indie songs from the 2010s"*)
- 📊 **Indexed music metadata using LlamaIndex** for fast semantic search
- 🔁 **Custom prompt chaining** pipeline with GPT-agent orchestration
- 💬 Conversational experience that feels like chatting with a DJ
- ⚡ Rapid response time and accurate context-based results

---

## 🛠 Tech Stack

| Area           | Tools / Libraries                     |
|----------------|----------------------------------------|
| Language       | Python                                 |
| AI / LLM       | OpenAI GPT-3.5, LangChain              |
| Indexing       | LlamaIndex (GPT Index)                 |
| Data           | Custom CSV dataset (10K+ songs)        |
| Dev Tools      | Jupyter, Streamlit / CLI (if applicable) |

---

🧠 Challenges Faced & Learnings

-Learned how to chain GPT agents to interpret and generate content in a conversational flow

-Built a semantic search system using LlamaIndex over structured CSV data

-Fine-tuned GPT prompts to balance creativity and accuracy in song recommendations

-Developed a deeper understanding of LangChain memory, tools, and agents

🔮 Future Improvements

-Integrate with Spotify API to directly create playlists

-Add multi-turn chat support with context retention

-Deploy as a Streamlit web app for public use

-Improve dataset richness with genre, tempo, and artist embeddings

-Expand LLM support to Claude or Gemini for experimentation



## ⚙️ Getting Started

```bash
# Clone the repo
git clone https://github.com/meetshah27/Recommendo.git
cd Recommendo

# Create a virtual environment
python -m venv venv
source venv/bin/activate  # on Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Add your OpenAI API key
export OPENAI_API_KEY=your_key_here

# Run the script (CLI or Streamlit)
python recommendo.py
# or, if Streamlit is supported
streamlit run app.py

