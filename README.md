<h1 align="center">🧠 Customer Categorizer – ML + FastAPI Project</h1>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?color=00E5FF&size=25&center=true&vCenter=true&width=600&lines=Customer+Personality+Segmentation;Machine+Learning+Project;FastAPI+Web+App;End-to-End+ML+Pipeline;Built+by+Lakhan+Singh" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/FastAPI-Backend-009688?style=for-the-badge&logo=fastapi" />
  <img src="https://img.shields.io/badge/Machine%20Learning-Project-orange?style=for-the-badge&logo=ai" />
  <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Docker-Ready-blue?style=for-the-badge&logo=docker" />
</p>

---

# 📌 Project Summary

This is a full **end-to-end Machine Learning system** that predicts the *customer’s personality cluster* based on:

- Demographics  
- Spending habits  
- Purchase history  
- Lifestyle metrics  

🎯 **Goal:** Help businesses target customers with personalized marketing & improve retention.

This project includes:

✅ ML pipeline (Clustering + Classification)  
✅ FastAPI Web App  
✅ HTML + CSS UI  
✅ Docker container  
✅ Detailed PPT included  
✅ Clean modular architecture  
✅ Notebook + flowcharts + documentation  

---

# 🔗 Live Repository

👉 **Repo Link:**  
https://github.com/Lakhan-gehlot/customer-categorizer-ml

---

# 🎓 Project Presentation (PPT)

📌 **Download PPT:**  
👉 [Customer Categorizer Project PPT](./ppt_customer_categorizer.pptx)

---

# 🧩 Tech Stack

### 🟦 **Languages + ML**
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

### 🟩 **Backend**
- FastAPI  
- Uvicorn  
- Jinja2 Templates  

### 🐳 **Deployment**
- Docker  
- AWS/Azure ready  

### 🧰 **Utilities**
- Config-driven code  
- Modular folder architecture  
- Logging & exception handling  

---

# 🗂 Project Folder Structure

customer-categorizer-ml/
│
├── app.py
├── Dockerfile
├── requirements.txt
├── setup.py
├── README.md
├── ppt_customer_categorizer.pptx
│
├── src/
│ ├── pipeline/
│ ├── components/
│ ├── utils/
│ ├── config/
│ ├── constant/
│
├── templates/
│ └── customer.html
│
├── static/
│ └── css/
│
├── notebooks/
├── flowchart/
└── docs/

---

# 🧠 Machine Learning Workflow

### **1️⃣ Data Preparation**
- Data ingestion  
- Handling missing values  
- Categorical encoding  
- Feature scaling  

### **2️⃣ Clustering (K-Means)**
- Find optimal `k` using Elbow Method  
- Visualize clusters  
- Assign cluster labels  

### **3️⃣ Classification**
- Train classifier to predict clusters  
- Hyperparameter optimization  
- Evaluate using metrics  

### **4️⃣ Prediction Pipeline**
- Accepts customer inputs from UI  
- Passes through preprocessing pipeline  
- Predicts cluster label  

---

# 🌐 FastAPI Web Application Routes

| Method | Route | Description |
|--------|--------|-------------|
| GET | `/` | Loads input form UI |
| POST | `/` | Predict cluster |
| GET | `/train` | Train the ML pipeline |

---

# ▶️ How to Run Locally

### **1️⃣ Clone repo**
```bash
git clone https://github.com/Lakhan-gehlot/customer-categorizer-ml
cd customer-categorizer-ml

2️⃣ Install dependencies
pip install -r requirements.txt

3️⃣ Run FastAPI
python app.py

4️⃣ Open browser
http://localhost:8000/

🐳 Run Using Docker
1️⃣ Build
docker build -t customer-app .

2️⃣ Run
docker run -p 8000:8000 customer-app

📊 Visuals & Demo
<p align="center">
  <img src="assets/demo.png" width="650">
</p>
🎯 Business Use Cases

Customer segmentation

Personalised marketing

Customer lifetime value analysis

Offer targeting

Upsell / Cross-sell optimisation

👨‍💻 Author

Lakhan Singh
📍 India
🔗 LinkedIn: https://www.linkedin.com/in/lakhansingh-dataanalyst/

🐙 GitHub: https://github.com/Lakhan-gehlot

<p align="center"> ⭐ If you like this project, consider giving it a star! </p> ```
