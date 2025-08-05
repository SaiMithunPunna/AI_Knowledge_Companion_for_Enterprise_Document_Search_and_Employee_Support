
# 🧠 AI-Powered Knowledge Companion for Enterprise Document Search and Employee Support

AI-Powered Knowledge Companion for Enterprise Document Search and Employee Support is a full-stack AI chatbot that uses Natural Language Processing and vector similarity search (FAISS) to answer domain-specific queries. It features a Flask backend, a static HTML/CSS/JS frontend, and a document-based knowledge base.

---

## 📁 Project Structure

```
AI-Powered Knowledge Companion for Enterprise Document Search and Employee Support/
├── chatbot.py                # Chatbot logic using embeddings
├── create_vectorstore.py     # Script to create FAISS vectorstore
├── .env                      # Environment variables
├── requirements.txt          # Dependencies for general use
├── backend/
│   ├── app.py                # Flask backend server
│   └── requirements.txt      # Backend-specific dependencies
├── frontend/
│   ├── index.html            # Web interface
│   ├── script.js             # Chatbot interaction logic
│   └── style.css             # Styling for chatbot UI
├── data/
│   └── Updated_major_dataset.txt  # Knowledge base document
├── vectorstore/
│   ├── index.faiss           # FAISS index file
│   └── index.pkl             # Metadata for vectorstore
```

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/SaiMithunPunna/AI_Knowledge_Companion_for_Enterprise_Document_Search_and_Employee_Support.git
cd AI_Knowledge_Companion_for_Enterprise_Document_Search_and_Employee_Support
```

### 2. Setup virtual environment

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
pip install -r backend/requirements.txt
```

### 4. Create the vectorstore (only first time)

```bash
python create_vectorstore.py
```

### 5. Run the backend server

```bash
cd backend
python app.py
```

The server will start on `http://localhost:5000`

### 6. Open the frontend

Open `frontend/index.html` in a browser. Make sure the backend is running for chatbot interaction.

---

## 📌 Features

- Document-based AI chatbot
- Embedding-based semantic search (FAISS)
- Flask backend API
- Responsive frontend UI
- Easy-to-extend modular structure

---

## 📄 Dataset

The chatbot uses `Updated_major_dataset.txt` as its knowledge source. You can replace it with your own domain-specific content.

---

## 🛠 Technologies Used

- Python, Flask
- FAISS (Facebook AI Similarity Search)
- HTML, CSS, JavaScript
- dotenv for environment variables


