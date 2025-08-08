<div align="center">
  <img src="https://github.com/prashanthsword/Multi-Agent-Medical-Assistant/blob/main/assets/logo_rounded.png" width="120" alt="Project Logo" />
</div>

<h1 align="center">⚕️ Multi-Agent Medical Assistant</h1>
<p align="center"><strong>AI-powered multi-agent system for medical diagnosis and patient support</strong></p>

<div align="center">
  <img src="https://img.shields.io/github/license/prashanthsword/Multi-Agent-Medical-Assistant?style=flat-square" />
  <img src="https://img.shields.io/github/languages/top/prashanthsword/Multi-Agent-Medical-Assistant?style=flat-square" />
  <img src="https://img.shields.io/github/last-commit/prashanthsword/Multi-Agent-Medical-Assistant?style=flat-square" />
</div>

---

## 🧠 Overview

The **Multi-Agent Medical Assistant** is an AI-driven platform designed to streamline preliminary medical diagnosis, patient triage, and healthcare assistance using a multi-agentic framework. It leverages cutting-edge NLP, LLMs, and decision-based agents to simulate the expertise of medical professionals.

---

## 🚀 Features

- 🩺 **Medical Diagnosis Bot** – Provides likely diagnosis based on patient symptoms.
- 💊 **Prescription Assistant** – Suggests potential medication (for informational purposes only).
- 📅 **Appointment Scheduler** – Automates basic scheduling queries.
- 🧠 **LLM Integration** – Uses transformer-based models (MiniLM, GPT-based) for intent classification and context handling.
- 🧑‍⚕️ **Multi-Agent Architecture** – Assigns tasks to specialized agents for accurate and efficient responses.
- 📈 **Offline Transformer Fine-Tuning** – Custom-trained MiniLM for improved healthcare domain performance.

---

## 🛠️ Tech Stack

- 🐍 Python 3.11+
- 🤖 Transformers (HuggingFace)
- ⚙️ PyTorch / TensorFlow
- 🧠 LangChain & LLM agents
- 🔄 FastAPI (or Flask)
- 🖥️ Streamlit (for UI)
- 📝 .env + Dotenv for API key management

---

## 📁 Project Structure

```bash
Multi-Agent-Medical-Assistant/
│
├── assets/                    # Logos and visual assets
├── agents/                   # Agent definitions and logic
├── data/                     # Sample datasets
├── models/                   # Pretrained or fine-tuned models
├── utils/                    # Helper functions and utilities
├── app.py                    # Entry-point for web UI (e.g., Streamlit)
├── main.py                   # Backend orchestration and routing
├── requirements.txt          # Python dependencies
└── README.md                 # You're reading it!
⚙️ Installation
bash
Copy code
git clone https://github.com/prashanthsword/Multi-Agent-Medical-Assistant.git
cd Multi-Agent-Medical-Assistant
pip install -r requirements.txt
Set your API keys in a .env file:

env
Copy code
OPENAI_API_KEY=your_openai_key
MODEL_NAME=minilm
▶️ Usage
bash
Copy code
# Run the main application
python main.py

# (or if using Streamlit)
streamlit run app.py
📊 Results
Training Dataset: 57K+ medical records

Classification Accuracy: ~47% validation (MiniLM base)

Deployment: Offline fine-tuned LLM agent + multi-agent router

🤝 Contributing
Pull requests are welcome! Please open issues first to discuss major changes.

🙋 Author
Name: Banothu Prashanth

GitHub: @prashanthsword

Email: banothuprashanth121@gmail.com

📌 Disclaimer
⚠️ This project is for educational and research purposes only. Do not use it for actual medical advice, diagnosis, or treatment. Always consult a qualified healthcare provider.

vbnet
Copy code
