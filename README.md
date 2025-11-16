# AI Project Dashboard

This repository contains the code for the Depression Detection Dashboard using RoBERTa model, Streamlit, Visual Analytics, and Ngrok deployment.

---

## 🚀 Live Demo (Temporary - Ngrok)
This link allows you to view the dashboard live while the Colab session is active.  
⚠️ Note: The link expires when Colab disconnects.

🔗 **Live Dashboard:**  
https://scoldedly-intercranial-joetta.ngrok-free.dev/

---

## 📌 Project Features
- Depression vs Non-Depression distribution
- Depression intensity visualization
- Word clouds (Depressed & Non-Depressed)
- Live text prediction using trained RoBERTa model
- Interactive dashboard built with Streamlit
- Model + Dataset integration

---

## 📂 Project Files
- `dashboard.py` → Streamlit dashboard code  
- `Final_Depression.csv` → dataset  
- `model.pth` → trained RoBERTa model  
- `roberta_results/` → saved weights & logs  

---

## 🧠 Model Overview
The model uses:
- RoBERTa-base embeddings  
- Additional intensity feature  
- Fully connected layers for classification  

---

## 📦 How to Run Locally

```bash
streamlit run dashboard.py
