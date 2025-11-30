<!-- Header Banner -->
<h1 align="center">🧠 Customer Categorizer – ML + FastAPI Project</h1>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?color=00E5FF&size=25&center=true&vCenter=true&width=600&lines=Machine+Learning+Project;Customer+Personality+Segmentation;FastAPI+%7C+Docker+%7C+Python;End-to-End+ML+Pipeline;Built+by+Lakhan+Singh" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/FastAPI-0.95-009688?style=for-the-badge&logo=fastapi" />
  <img src="https://img.shields.io/badge/ML-Model-orange?style=for-the-badge&logo=ai" />
  <img src="https://img.shields.io/badge/Docker-Ready-blue?style=for-the-badge&logo=docker" />
</p>

---

# 📌 **Project Summary**

This is a full **end-to-end Machine Learning project** that predicts **customer personality clusters** based on their:

- Demographic data  
- Spending behavior  
- Purchase patterns  
- Recency & customer lifecycle metrics  

The project includes:

✔ Complete ML pipeline  
✔ K-Means clustering  
✔ Classification for cluster prediction  
✔ FastAPI web app  
✔ Docker containerization  
✔ HTML UI  
✔ PPT project presentation  
✔ Modular `src/` folder architecture  

---

# 🧩 **Tech Stack**

### **🔹 Programming & ML**
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  

### **🔹 Web Framework**
- FastAPI  
- Uvicorn  
- Jinja2 Templates  

### **🔹 Deployment**
- Docker  
- AWS / Azure ready  

### **🔹 Supporting Tools**
- Config-driven architecture  
- Logging + exception layers  
- Automated pipelines  

---

# 🗂 **Project Folder Structure**
customer-categorizer-ml/
│
├── app.py # FastAPI web server
├── Dockerfile # Docker container file
├── requirements.txt # ML + FastAPI dependencies
├── README.md # Project documentation
├── setup.py # Makes src package installable
├── ppt_customer categorizer.pptx # Project presentation
├── .gitignore
├── .dockerignore
│
├── src/
│ ├── pipeline/ # Training + prediction pipelines
│ ├── components/ # ML components (validation, clustering)
│ ├── config/ # Configuration files
│ ├── utils/ # Helper functions
│ ├── constant/ # Application constants
│
├── templates/
│ ├── customer.html # User interface
│
├── static/
│ ├── css/ # Styling
│
├── docs/ # Project documentation
├── flowchart/ # ML workflow diagrams
└── notebooks/ # EDA, model experiments


---

# 🧠 **Machine Learning Workflow**

### **1️⃣ Data Ingestion**
- Reads data from source  
- Handles missing values  
- Basic cleaning & validation  

### **2️⃣ Data Transformation**
- Encoding  
- Scaling  
- Feature engineering  

### **3️⃣ Clustering (Unsupervised)**
- K-Means clustering  
- Elbow method for optimal K  
- Cluster visualization  

### **4️⃣ Classification (Supervised)**
- Train ML model to predict clusters  
- Hyperparameter tuning using GridSearchCV  

### **5️⃣ Prediction Pipeline**
- Takes user input  
- Processes through ML pipeline  
- Outputs cluster number  

---

# 🌐 **FastAPI Web Application**

The project includes a beautiful frontend built using:

- HTML  
- CSS  
- FastAPI templates  

### ⭐ Endpoints

| Method | Route | Description |
|--------|--------|--------------|
| GET | `/` | Load input form |
| POST | `/` | Predict customer cluster |
| GET | `/train` | Train ML model |

---

# ▶️ **How to Run the Project**

## **Option 1 — Run Locally**

### **1️⃣ Clone the repo**
```bash
git clone https://github.com/Lakhan-gehlot/customer-categorizer-ml.git
cd customer-categorizer-ml

2️⃣ Install dependencies
pip install -r requirements.txt

3️⃣ Run FastAPI
python app.py

4️⃣ Open browser
http://localhost:8000/

Option 2 — Run with Docker
1️⃣ Build image
docker build -t customer-app .

2️⃣ Run container
docker run -p 8000:8000 customer-app

📊 Project Screenshots (Add later)
<p align="center">
  <img src="assets/demo.gif" width="600">
</p>

🎯 Business Use Cases

✔ Customer segmentation
✔ Targeted marketing
✔ Personalized offers
✔ Cross-selling
✔ Customer retention analysis

🎓 Project Presentation (PPT)

📌 Download the PPT:
👉 ppt_customer categorizer.pptx

👨‍💻 Author

Lakhan Singh
📍 India
🔗 LinkedIn: https://www.linkedin.com/in/lakhansingh-dataanalyst/

🐙 GitHub: https://github.com/Lakhan-gehlot

<p align="center"> ⭐ If you like this project, please give it a star — it motivates me to build more! </p> ```
