# 🧠 AI Toxicity Filter for Kids  

A hybrid AI and ML-based moderation system that detects and filters harmful or offensive text in real time.  
The project is designed to promote safe and positive online communication for children and family-friendly platforms.

---

## 📘 Project Overview  

**AI Toxicity Filter for Kids** is an intelligent text-moderation platform that leverages advanced NLP models to analyze and classify user-generated content as **Allow**, **Review**, or **Block**.  
It integrates transformer-based AI models for semantic understanding and interpretable ML techniques for transparent, explainable decisions.

The system includes:  
- ⚙️ A **FastAPI backend** for text analysis, inference, and logging  
- 🧠 A **hybrid AI engine** combining Groq AI and a fine-tuned DistilBERT model  
- 💻 A **React + Tailwind CSS frontend** simulating real-time moderation  
- 🗄️ **MongoDB** and **JSONL** data logging for transparency and evaluation  

The goal is to build a scalable, explainable, and child-safe content moderation framework suitable for modern digital environments.

---

## 🧩 Key Features  

- Real-time detection and classification of toxic text  
- AI + ML hybrid model for accurate moderation  
- Explainable and auditable prediction pipeline  
- Centralized log management using MongoDB and JSONL  
- Kid-friendly, accessible frontend design  
- Lightweight and deployment-ready architecture  

---

## 🏗️ System Architecture  

Frontend (React + Tailwind)
↓
Backend API (FastAPI)
↓
AI / ML Processing Engine
↓
Database & Logging (MongoDB + JSONL)

| Layer | Technologies | Description |
|--------|---------------|-------------|
| **Frontend** | React.js · Tailwind CSS · Axios | Interactive web interface for message input and moderation feedback |
| **Backend** | FastAPI · Pydantic · Uvicorn | REST API handling text input, preprocessing, and inference |
| **AI Engine** | Groq AI · DistilBERT | Transformer-based toxicity classification |
| **Database** | MongoDB · JSONL | Stores moderation results, decisions, and timestamps |
| **Evaluation** | Scikit-learn · Matplotlib | Generates model performance metrics |

---

## 🚀 Workflow  

1. The user types a message in the web interface.  
2. The message is sent to the `/predict` API endpoint.  
3. Text is normalized and preprocessed for analysis.  
4. The AI model computes toxicity probabilities.  
5. The ML model validates and benchmarks the result.  
6. The final decision (Allow / Review / Block) is sent back to the UI.  
7. All results and scores are logged for review and evaluation.  

---

## 📊 Model Performance  

| Metric | Groq AI | DistilBERT |
|--------|----------|-------------|
| **Accuracy** | 94.3 % | 89.2 % |
| **Precision** | 0.91 | 0.85 |
| **Recall** | 0.95 | 0.87 |
| **F1-Score** | 0.93 | 0.86 |
| **Latency** | < 10 ms | ≈ 120 ms |

---

## 👩‍💻 Developer Responsibilities  

**Developed and maintained by:** **Gamya Komma**

### Major Contributions  
- Designed and implemented the overall architecture (frontend + backend)  
- Integrated **DistilBERT** model with a FastAPI backend for real-time inference  
- Created REST endpoints for moderation, logging, and evaluation  
- Developed preprocessing and text normalization utilities  
- Configured performance metrics and validation framework  
- Built a responsive frontend interface for live moderation feedback  
- Authored all documentation and established repository structure  

---

## 🧰 Tech Stack  

**Languages:** Python · JavaScript · HTML · CSS  
**Frameworks & Tools:** FastAPI · React.js · Tailwind CSS · Uvicorn  
**AI / ML Libraries:** Hugging Face Transformers · PyTorch · Scikit-learn  
**Database:** MongoDB  
**Deployment:** GitHub Pages (frontend) · Render / Fly.io (backend)

---

## 🔮 Future Enhancements  

- Multi-language toxicity detection support  
- Voice and image moderation capabilities  
- Enhanced accessibility for child-friendly UX  
- Real-time parental dashboard with activity summaries  

---


## 📂 Repository Structure

```
toxicity-filter-kids/
│
├── frontend/           # React + Tailwind user interface
├── backend/            # FastAPI server and model logic
├── docs/               # Reports and architecture diagrams
├── Procfile            # Deployment configuration
├── .gitignore
└── README.md
```



---

## ⚙️ Local Setup  

### Frontend  
cd frontend
npm install
npm start

### Backend
cd backend
python -m venv venv
source venv/bin/activate      # For macOS/Linux
pip install -r requirements.txt
uvicorn main:app --reload

🧾 License

MIT License © 2025 Gamya Komma
All source code and documentation are authored and maintained by Gamya Komma.
This project is intended for educational, research, and ethical development purposes.
