
# 🚀 AI Travel Agent (Agent1)

## 🌍 Project Overview

This Jupyter Notebook (`agent1.ipynb`) is an implementation of an AI-based travel assistant from scratch. The goal of the project is to build an AI agent capable of executing tasks iteratively through the **Think-Act-Learn** cycle. The agent follows the **ReAct** pattern, where it reasons about a problem, takes action based on observations, and refines its approach iteratively.

The project does not rely on **LangGraph** but instead implements a foundational AI agent architecture using Python libraries.

## ✨ Features

- **🧠 AI Reasoning and Decision Making**: The agent follows the **ReAct** pattern, first reasoning about a situation, taking action (API calls, calculations, user queries), and refining its decisions based on observations.
- **🔄 Task Execution Cycle**: The agent performs tasks iteratively until a goal is achieved.
- **⚙️ Environment Setup**: Uses OpenAI API and other required tools for natural language processing.

## 🔧 Installation & Setup

Ensure you have an environment file (`enviroments.env`) with the required API keys:

```ini
OPENAI_API_KEY=your_api_key_here
```

Load the environment variables within the notebook:

```python
import os
from dotenv import load_dotenv

load_dotenv(dotenv_path="path_to_your_env_file", override=True)
print("✅ API key loaded:", os.environ.get("OPENAI_API_KEY") is not None)
```

## 📌 Usage

Open the Jupyter Notebook:

```bash
jupyter notebook agent1.ipynb
```

Run each cell sequentially to set up the environment and initialize the agent.
Modify and extend the agent's capabilities as needed.

## 🚀 Future Enhancements

```sql
🤖 Enable multi-agent collaboration for complex travel planning.
📢 Implement real-time notifications and alerts for flight and hotel updates.
📷 Add image recognition for scanning and analyzing travel documents.
🎙️ Support multilingual conversation capabilities for global users.
💾 Store user preferences and past trips for personalized recommendations.
```

Just copy and paste it into your project! 🚀 Let me know if you need any changes! 😊


