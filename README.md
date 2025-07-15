# 🚗 Crash Rate Prediction from Traffic Volume Data using AI

An interactive web application built to help transportation researchers and agencies forecast crash rates based on historical traffic volume data using machine learning.

---

## 🔍 Overview

This project was developed in collaboration with the Center for Sustainable Mobility (CSM) at the Virginia Tech Transportation Institute under the guidance of Dr. Mohamed Farag. The tool enables users to upload traffic data, view past crash predictions, and manage machine learning models—all within a secure web interface.

---

## 🛠️ Tech Stack

- **Frontend**: React, Next.js, Material-UI  
- **Backend**: FastAPI (ML), Next.js API routes (web backend)  
- **ML Development**: Google Colab, TensorFlow  
- **Authentication**: JWT-based login/signup  
- **Deployment**: Docker (for local dev)  

---

## ✨ Key Features

- 🔐 Secure login/signup with JWT token authentication  
- 📁 Upload traffic volume datasets (CSV)  
- 🤖 Run crash prediction models trained offline via Google Colab  
- 📊 View historical predictions with model metadata  
- 🧑‍💼 Admin tools for uploading and managing models  

---

## 📊 Evaluation & Testing

- Machine learning models were trained and evaluated offline in Google Colab  
- Frontend and backend modules were tested with real-world traffic datasets  
- Client feedback was gathered from Dr. Farag and incorporated into the final product  

---

## 🧪 How to Run Locally

### Backend (FastAPI ML server)
```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
```

### Frontend (Next.js web server)
```bash
cd frontend
npm install
npm run dev
```

---

## 📁 Folder Structure

```
traffic-crash-predictor/
│
├── backend/           # ML backend (FastAPI)
├── frontend/          # Web interface (React + Next.js)
├── colab_models/      # Offline Colab notebooks for model training
├── utils/             # Data processing scripts
└── docker-compose.yml
```

---

## 📎 Project Report

- 📄 [Project page ](https://vtechworks.lib.vt.edu/items/bd9772e1-81d0-48af-89fe-31c788c01ec5)
- 🖥️ Developed as part of Virginia Tech CS4624 (Fall 2024)

---

## 📫 Contact

Devanshu Khadka  
[LinkedIn](https://linkedin.com/in/devanshukhadka)  
📧 khadkadevanshu@gmail.com

---

## 📜 License

For academic and research use only. Contact authors for reuse or extension rights.
