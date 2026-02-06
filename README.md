# DTSense Simple RAG and Agent
---

## 🛠️ Instalasi

### Prasyarat
Pastikan Anda telah menginstal:
- Python 3.8 atau lebih tinggi
- Pip atau Anaconda

1. **Kloning Repositori**

   ```bash
   git clone https://github.com/DTSense/DTSense_Agent.git
   cd DTSense_Agent
   ```
2. Buat dan Aktifkan Virtual Environment
    ```bash
   python -m venv .venv
   source .venv/bin/activate   # Pada Windows gunakan: venv\Scripts\activate    
   ```
3. Install Dependensi
    ```bash
   pip install -r requirements.txt    
   ```
4. JALANKAN STREAMLIT di Terminal untuk aplikasi simple RAG text based dan Agentic RAG with Pinecone
    ```bash
   streamlit run app_st.py 
   atau
   streamlit run dtsense_agent.py
   ```
