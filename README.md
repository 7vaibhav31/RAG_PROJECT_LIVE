# ⚡ RAG — AI Document Assistant

An advanced, premium-designed Retrieval-Augmented Generation (RAG) system built as a Single-Page Application (SPA). Upload text files (.txt) and query the AI with questions grounded strictly in the provided document, avoiding hallucinations.

---

## 🌟 Features

- **Document Analysis:** Upload `.txt` text files to index them into the RAG pipeline.
- **Zero Hallucination RAG:** Uses lightweight local TF-IDF vectorization and Cosine Similarity to select the most relevant document chunks.
- **Modern Dark UI:** Premium glassmorphism design with a dark mode color palette, smooth transition animations, and real-time response rendering.
- **Live Telemetry:** Real-time metrics dashboard tracking latency (ms), token speed (tokens/sec), and search confidence.
- **Vercel Optimized:** Extremely lightweight design with no heavy deep-learning dependencies (such as PyTorch), making it 100% free to deploy on serverless platforms.

---

## 🏗️ Architecture Stack

- **Frontend:** Vanilla HTML5, CSS3 (Glassmorphism), JavaScript
- **Backend:** Python, Flask
- **RAG Engine:** Scikit-Learn (TF-IDF Vectorization)
- **AI Inference:** OpenRouter API
- **Hosting:** Vercel Serverless

---

## 🚀 How to Run Locally

### 1. Clone the repository and navigate into it:
```bash
git clone https://github.com/7vaibhav31/RAG_PROJECT_LIVE.git
cd RAG_PROJECT_LIVE/rag
```

### 2. Set up a Virtual Environment:
```bash
python -m venv venv

# On Windows:
venv\Scripts\activate

# On Mac/Linux:
source venv/bin/activate
```

### 3. Install Dependencies:
```bash
pip install -r requirements.txt
```

### 4. Run the Application:
```bash
python app.py
```

### 5. Open in Web Browser:
Go to **http://127.0.0.1:5000** and upload a text file to start testing!
