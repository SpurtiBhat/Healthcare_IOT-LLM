# 🏥 Healthcare IoT + LLM

An AI-driven real-time patient monitoring and diagnosis system that combines **IoT sensors** with **Large Language Models (LLMs)** to enhance healthcare through smart insights and geolocation-based emergency support.

---

## 📌 Overview

This project connects live vitals data (like heart rate and temperature) from sensors via **ThingSpeak**, then leverages **LLMs (Gemini Pro via LangChain)** to analyze conditions and provide **medical suggestions** by retrieving data from trusted sources like the **Gale Encyclopedia**. 

---

## 🚀 Features

- 🌡️ **Live Sensor Integration** via ThingSpeak (Heartbeat + Temperature)
- 🧠 **LLM-powered Medical Analysis** using Gemini Pro and LangChain
- 🔍 **RAG (Retrieval-Augmented Generation)** from Gale Encyclopedia
- 📍 **Geolocation-based Hospital Detection**
- 🧾 **Medical Report Generation** via LLMs
- 🌐 **User-friendly Web Interface** using Gradio
- 🧠 **ChromaDB Vector Store** for semantic search

---

## 🛠️ Tech Stack

### ⚙️ Backend
- Python
- LangChain
- Gemini Pro
- ChromaDB
- ThingSpeak API

### 💻 Frontend
- Gradio (for web-based interaction)

### 🗃️ Data
- Gale Encyclopedia (medical articles PDF)
- Real-time sensor data via ThingSpeak

---

## 🧪 Setup Instructions

### 🔧 Backend Setup
# Clone the repository
git clone https://github.com/SpurtiBhat/Healthcare_IOT-LLM.git
cd Healthcare_IOT-LLM

# Set up virtual environment (optional)
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt

# Run it
python app.py

