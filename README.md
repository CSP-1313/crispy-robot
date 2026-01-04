# Enterprise PDF to Searchable Knowledge

This project converts enterprise PDFs into structured, searchable knowledge using OCR and vector databases.

## Features
- Upload enterprise PDFs
- OCR for scanned documents
- Semantic search using FAISS
- Clean UI using Streamlit

## Run Instructions
See below.
▶ HOW TO RUN (STEP-BY-STEP)
1️⃣ Create Virtual Environment 
python -m venv venv
venv\Scripts\activate
2️⃣ Install Dependencies
pip install -r requirements.txt
3️⃣ Install Tesseract OCR
✔ Install Windows EXE
✔ Path:
C:\Program Files\Tesseract-OCR\tesseract.exe
4️⃣ Run the App
streamlit run app.py
Browser opens automatically.
HOW IT WORKS (SHORT FLOW)

Upload PDF
   ↓
Detect Text / OCR
   ↓
Split into meaningful chunks
   ↓
Convert to embeddings
   ↓
Store in Vector DB
   ↓
Semantic Search