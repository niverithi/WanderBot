# 🌍 WanderBot | AI-Powered Travel Assistant

**WanderBot** is an AI-powered multi-agent web application that automates personalized trip planning based on user preferences such as travel dates, destination, and interests.

Instead of manually searching for hotels, attractions, and logistics, WanderBot leverages intelligent agents and real-time data fetching to generate a complete, day-by-day itinerary—all in one streamlined experience.

---

## 🚀 Features

- 🤖 **AI Trip Planner**  
  Automatically builds travel plans using specialized AI agents (Local Guide, Trip Expert, and Planner).

- 🌐 **Live Web Search**  
  Uses DuckDuckGo API to fetch real-time data for accommodations, transportation, events, weather, and more.

- 🧠 **LLaMA 3.2 Integration**  
  Runs a powerful local language model via Ollama—no cloud API required.

- 🧩 **Multi-Agent Architecture**  
  Powered by Crew AI and LangChain for smooth agent collaboration and task handling.

- 📅 **Interactive UI**  
  Built with Streamlit to collect user inputs and display live agent activity.

- 📂 **Exportable Output**  
  Generates a downloadable Markdown (.md) file with a full day-wise itinerary.

---

## 🛠️ Tech Stack

| Component            | Technology             |
|---------------------|------------------------|
| Frontend            | Streamlit (Python)     |
| Agent Framework     | Crew AI                |
| Model Management    | LangChain              |
| Language Model      | LLaMA 3.2 via Ollama   |
| Search API          | DuckDuckGo             |
| Output Format       | Markdown (.md)         |

---

## 📸 Screenshots

*(Add screenshots of your app interface here if available)*

---

## 🧠 How It Works

1. User enters trip details (destination, dates, interests).
2. AI agents (Local Guide, Trip Expert, Planner) fetch and process real-time travel data.
3. The planner compiles a detailed itinerary.
4. The user receives a downloadable Markdown file with all recommendations.

---

## 📦 Setup & Installation

```bash
# Clone the repo
git clone https://github.com/yourusername/WanderBot.git
cd WanderBot

# Install dependencies
pip install -r requirements.txt

# Run the Streamlit app
streamlit run app.py
