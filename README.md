# AI-Powered-Health-Assistant
# AICTE INTERNSHIP Project on AI-Powered Health Assistant
# AI-Powered Health Assistant Chatbot

## 🚀 Overview
The **AI-Powered Health Assistant Chatbot** is a smart healthcare solution designed to provide users with quick, AI-driven answers to medical and health-related queries. It leverages **Natural Language Processing (NLP)** and **Semantic Search** to retrieve relevant information from medical documents and respond in an interactive chatbot interface.

## 🏗️ Project Architecture
The chatbot operates in **three main phases**:

### 📌 Phase 1: Data Preparation & Storage
- Extracts text from **medical PDF documents**.
- Splits extracted text into meaningful **chunks**.
- Generates **vector embeddings** using **Hugging Face** models.
- Stores embeddings in **FAISS (Facebook AI Similarity Search) vector database**.

### 📌 Phase 2: Query Processing & Semantic Search
- Converts user query into **vector embeddings**.
- Performs **semantic search** in the FAISS database.
- Retrieves and ranks **most relevant document chunks**.

### 📌 Phase 3: Response Generation
- Passes top-ranked results to a **Large Language Model (LLM)**.
- Generates a **natural language response**.
- Displays the answer in a **Streamlit-based chatbot UI**.

## 🛠️ Tools & Technologies
### **Hardware Requirements**
- **Processor:** Intel Core i5/i7 or AMD Ryzen 5/7 (or higher)
- **RAM:** 8GB minimum (16GB recommended)
- **Storage:** 50GB free (SSD recommended)
- **GPU:** NVIDIA GPU with CUDA support (optional, but improves performance)

### **Software Requirements**
- **Operating System:** Windows 10/11, Linux (Ubuntu 20.04+), macOS
- **Programming Language:** Python 3.8+
- **Key Libraries & Frameworks:**
  - `Hugging Face Transformers` - For embeddings & LLM
  - `FAISS` - For efficient semantic search
  - `LangChain` - For retrieval-augmented generation
  - `PyMuPDF / pdfminer.six` - For PDF text extraction
  - `Streamlit` - For interactive chatbot UI
  - `scikit-learn` - For additional text processing
  - `NumPy & Pandas` - For data handling
- **Deployment:** Docker, FastAPI (for API), Streamlit Cloud

## 📥 Installation & Setup
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/ai-health-chatbot.git
   cd ai-health-chatbot
   ```

2. **Create a virtual environment & install dependencies:**
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   pip install -r requirements.txt
   ```

3. **Run the chatbot:**
   ```bash
   streamlit run app.py
   ```

## 🎯 Features
✅ Extracts knowledge from **medical PDFs**
✅ Performs **semantic search** for relevant answers
✅ Uses **Hugging Face LLM** for response generation
✅ Interactive UI powered by **Streamlit**
✅ Fast and scalable with **FAISS vector storage**

## 📸 Snapshots
### **1️⃣ Data Processing & Embedding Storage**
> 📌 Shows extracted text chunks from PDFs and stored vector embeddings.

### **2️⃣ Query Processing & Search Results**
> 📌 Demonstrates semantic search retrieving the most relevant text chunks for a given query.

### **3️⃣ Final Response in Chatbot UI**
> 📌 Displays the LLM-generated response in the **Streamlit chatbot interface**.

## 🤝 Contributing
Want to improve this chatbot? Contributions are welcome! Follow these steps:
1. Fork the repo.
2. Create a new branch: `git checkout -b feature-name`
3. Commit changes: `git commit -m "Added new feature"`
4. Push to branch: `git push origin feature-name`
5. Create a pull request.

## 📜 License
This project is licensed under the **MIT License**.

## 📞 Contact
For questions or suggestions, feel free to reach out!
- ✉️ Email: thatharohith062@gmail.com

---
🚀 **Transforming Healthcare with AI!** 🌍


